<h1>
  <span class="headline">The Principle of Least Privilege</span>
  <span class="subhead">Understanding Access Control: The Principle of Least Privilege</span>
</h1>

**Learning objective:** By the end of this lesson, students will be able to explain what the Principle of Least Privilege is and what happens when it isn't implemented properly.

## What is the Principle of Least Privilege?

At it's core, the principle of least privilege is all about giving users and systems only the bare minimum access they need to get their jobs done. It's like giving someone a key that only opens on specific door instead of a master key tha opens every room in the building.

Principle of least privilege applies from the top to the bottom of an organization - from the CEO to the summer intern, and from critical servers to a shared printer. It's a key part of "zero trust" security, which basically means you should always verify that someone is who they say they are and that they're allowed to be where they're trying to go.

### Why Principle of Least Privilege Matters

- Reduces attack surface
- Limits malware spread
- Prevents accidental changes
- Creates clear audit trails
- Protects sensitive data

The idea is to limit the potential damage if something goes wrong, like a hacker getting their hands on someone's login. If that compromised account only has access to a small slice of the network, the attacker can't create as much chaos.

### Core Components

1. **User Permissions:** What actions can be performed
2. **Access Control:** How permissions are managed
3. **Duration:** How long permissions are granted
4. **Context:** When permissions can be used

## Case Study - Principle of Least Privilege in Action

In many cases, data breaches that you see could be easily prevented by implementing the principle of least privilege.

A real life example can be found with a [Tesla breach](https://www.infosecurity-magazine.com/news/tesla-insiders-responsible-for/).

In this case, insiders of the company had access to sensitive data that was not required for their day to day jobs. They used their access to exfiltrate the data and keep it on their devices.

This example is employees using over permissioned access to willfully take data. However, there are many situations that it is an external entity that gets access. Let's take a look at a fictional situation that is all to common.

### Databreach Example

- An intern with full admin access to the customer database
- They clicked a phishing link while logged in as admin
- Malware spread through entire system
- 50,000 customer records exposed
- Company faced $2 million in damages

**What Went Wrong:**

- Unnecessary admin access
- No access time limits
- No context-based restrictions
- Poor access review process

**How Principle of Least Privilege Could Have Prevented This:**

- Intern would have limited, supervised access
- Admin tasks would require an elevation process
- System would flag unusual access patterns
- Damage would be contained to one area

As you can see, not following the principle of least privilege can cause big problems!
