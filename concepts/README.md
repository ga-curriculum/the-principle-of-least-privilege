<h1>
  <span class="headline">The Principle of Least Privilege</span>
  <span class="subhead">Concepts</span>
</h1>

**Learning objective:** By the end of this lesson, students will be able to explain the principle of least privilege and what happens when it isn't implemented correctly.

## What is the principle of least privilege (PLoP)?

At its core, the principle of least privilege is all about giving users and systems only the bare minimum access they need to get their jobs done. It's like giving someone a key that only opens a specific door instead of a master key that opens every room in the building.

The Principle of least privilege applies from the top to the bottom of an organization - from the CEO to the summer intern and from critical servers to a shared printer. It's a key part of *zero trust* security.

> 📚 *Zero trust* means always verifying that a user is who they say they are and that they're allowed to be where they're trying to go. In short, nothing and no one is to be trusted by default.

### Why the principle of least privilege matters

- **Reduces attack surface**: Limits the potential damage if an account is compromised.
- **Limits malware spread**: Prevents malware from spreading across the network.
- **Prevents accidental changes**: Reduces the risk of unintentional changes to critical systems.
- **Creates clear audit trails**: Makes it easier to track and audit access.
- **Protects sensitive data**: Ensures that only authorized users can access sensitive information.

The idea is to limit the potential damage if something goes wrong, such as a hacker getting their hands on someone's login. If that compromised account only has access to a small slice of the network, the attacker can't create as much chaos.

### Core components

The principle of least privilege is built on several key components:

- **Authentication**: Ensure that users are who they claim to be before granting access. Imagine authentication as a security guard checking IDs at the entrance. Only verified individuals are allowed in.
- **Authorization**: Determine what actions authenticated users are allowed to perform. Think of authorization as assigning different access levels to employees based on their roles. For example, a manager might have access to more areas than an intern.
- **User permissions**: Defines what actions users can perform. Consider user permissions as setting specific rules for what each user can do within the system.
- **Access control**: Manages how permissions are granted. Think of access control as the process of distributing keys to different doors based on the user's role and needs.
- **Duration**: Specifies how long permissions are valid. Imagine duration as a temporary pass that expires after a certain period, ensuring that access is not indefinite.
- **Context**: Determines when an individual can use their permissions. Consider context as setting conditions under which access is granted, such as time of day or location.

## Case study - the principle of least privilege in action

In many cases, data breaches that you see could be easily prevented by implementing the principle of least privilege. A past [breach at Tesla](https://www.infosecurity-magazine.com/news/tesla-insiders-responsible-for/) is a real-life example of this.

In this case, insiders of the company had access to sensitive data that they didn't require to do their day-to-day jobs. They used their access to exfiltrate data on their devices.

This example is employees using over-permissioned access to take data willfully. However, there are many situations in which an external entity gains access. Let's look at a fictional situation that is all too common.

<div class="activity discussion">
  <h2 class="title">Data breach example</h2>
  <span class="minutes">5 min</span>
</div>

Consider this hypothetical scenario:

An intern has full admin access to the customer database. They clicked a phishing link while logged in as the admin user, allowing an attacker to access the system. From here, malware spread through the entire network. Before the problem was resolved, 50,000 customer records were exposed and the company faced $2 million in damages.

As you can see, not following the principle of least privilege can cause significant problems!

Let's discuss what went wrong and how the principle of least privilege could have prevented this breach.
