# PRR - Pull Request Reference

## Table of Contents

[1. Intro to PRR](#1-intro-to-prr)

[2. Definitions](#2-definitions)

[3. Reviewers](#3-reviewers)

&nbsp;&nbsp;[3.1 Comment Labels](#31-comment-labels)

&nbsp;&nbsp;[3.2 Comment Labels Exceptions](#32-comment-label-exceptions)

&nbsp;&nbsp;[3.3 Resolved](#33-resolved)

## 1. Intro to PRR

PRR, the Pull Request Reference, is a comprehensive guide that you can refer to when working with pull requests.

## 2. Definitions

Author - The person that created the pull request. By default, when using the word "Author", we mean someone that works on the team that owns the codebase. Otherwise, "External Author" refers to an author that created a pull request to a codebase that their teams does not own.

Reviewer - A person assigned to review a pull request. They leave comments to a pull request, and mark it as "approved" or "changes requested". 

## 3. Reviewers

### 3.1 Comment Labels

As a reviewer, when making a comment that is not a reply, you must include one of the **standard** "Comment Labels". These "Comment Labels" quickly indicates to others how well a pull request is going. Here are the following **standard** "Comment Labels":

* `Discussion:` - Something that the reviewer wants to talk about with others. Does not impact approval.
* `Recommendation:` - A change recommended by the reviewer. Does not impact approval
* `Minor:` - Indicating an issue with the pull request. The pull request is not going to be approved, untill this minor issue is resolved. 
* `Major:` - Indicating a major issue with the pull request. The reviewer is going to mark the pull request as "changes requested", untill this major issue is resolved.

### 3.2 Comment Label Exceptions
There are two exceptions cases, where you do not have to use a Comment Label:

* You are giving a compliment on a pull request change.
* The mandatory comment as part of marking a pull request as "changes requested", or the optional comment that can be provided when marking a pull request as "approved".

### 3.3 Resolved

After leaving a comment that is either "Major", "Minor", or "Recommendation", the pull request may be updated to address the comment. After an author replies that they believe the necessary changes have been made for this comment, you (the reviewer) must follow up with a reply. This reply should be one of the following scenarios:

* If the changes are not satisfactory, the reviewer should reply and state what still needs to be done
* If the changes are satisfactory, the reviewer should leave a replying including the word "Resolved", and mark the comment thread as resolved.
