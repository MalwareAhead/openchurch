# OpenChruch

*OpenChurch* is an open source church management system designed to organize all kinds of data, events and tasks related to the complexity of daily church life.

## Motivation

The Church is a complex organism, not just on Sunday morning.

- First of all it consists of people who are connect by Jesus Christ and His word.
- The people gather at specific places and are using different resources to take steps forward.
- Resources are e. g. rooms, inventory, songs including lyrics and sheets, etc.
- The church members organize themselves in groups. They set goals, make decisions, share knowledge.

For all that *OpenChurch* shall be a platform connecting all the relevant parts of the Church.

## Features (for now)

### 1. Members

- Members are able to see, who their Brothers and Sisters are. Therefore every member gets a minimal about page.
- Members can be managed by admins. Furthermore they need to be different roles for each member.

#### More Ideas for Members

- Members are able to organize in different groups (bible study groups, worship teams, etc.).
- Members can offer all kinds of services and at the same time ask for help (e. g. helping with a move or supporting with job applications).

### 2. Ministry (Tasks and Responsibilities)

- An organigramm provides information about ministries, responsibilities and contacts at specific concerns.
- Authorized staff can organize plans for "housekeeping" the church amenities and other duty rosters.

## Project setup

This rails app connects itself to a postgres database running in a docker container. I am currently using `postgres:16.3-alpine`.
For your dev environment to work properly, start a persistant postgres container and configure your database.yml to fit your connection.

That's it for now. Let's see how far we can go to provide a useful tool to all churches for free, to help them grow and work properly.

Soli Deo Gloria.
