# General ideas
1. This document contains all relevant development procedures, and/or links to other more detailed explanations
2. Let's try to follow these procedures, and if something doesn't work - let's discuss it (e.g. in Telegram group), reach some understanding about proposed changes and then write them down in this document. 
3. If you don't understand some procedure, or if you believe it should be changed and/or abandoned - please don't just ignore it, please post your concerns in Telegram group, or discuss them during lessons.
4. We don't want to create "bureaucracy for the sake of bureaucracy" - each procedure should be meaningful and useful. If you believe there is a better way to do something - please talk about it (e.g. in Telegram group, or during lessons)

# Programming languages
1. Our projects can be in different languages
2. Interaction between parts in different languages is done via CLI for now (e.g. implementation in LangA calls CLI for LangB, then can use changes in filesystem or other storages)
3. You may want to port some features available in one language to another language - in this case, please discuss it in Telegram group, create issues and start working
4. [Language-specific details](LanguageSpecific.md)

# Contributing
1. Choose an issue to work on (**not a multi-issue**)
2. You should be assigned to this issue - see [assignment procedure details](#assigning-contributors-to-issues)
3. Fork repository (or pull latest changes if you have forked it previously), implement issue in your forked repository
4. Before sharing your changes, please sync your fork with upstream repository (sync in web interface, then pull in your git client), fix merge conflicts if needed
5. Create pull request (single pull request per issue), reference issue in pull request
6.  Someone with write access (currently organization owner @kzhereb ) reviews pull requests, either accepts it, or comments on what should be changed
7. (Optional) Other contributors can also review pull request and comment on it (procedure TBD)
8.  Pull request gets integrated into main repository, and issue gets closed

# Assigning contributors to issues
1. In each student group, there is (at least) one student with Triage rights to repository; this student can assign contributors to issues
2. At the end of each practice lesson, we discuss issue assignments and some students get assigned to issues
3. If you want to work on some unassigned issue between lessons (and don't want to wait until next lesson) - please post a message in Telegram group. If there are no objections - you will be assigned to this issue.
4. If you want to work on some issue and there is already assignee - please contact them. You can work on issues together, but assignee is responsible for coordinating your contribution.
5. If you want to work on some functionality, but there is no issue for it - please discuss it, either during lesson or in Telegram group. Then the issues will be added and you can work on them.
