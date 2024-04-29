# OmniStack

## Useful Links

- [Feature List](https://github.com/JordanBourne/OmniStack/documents/FEATURES.md)

## Project Goals

The OmniStack's purpose is to be an ever-growing project to continue to explore what it means to be a Software Engineer in every sense of the word, though definitely with a strong bias towards web functionality. The initial goal for the project is to set out to define a core set of functionality that occurs commonly on the web and in related applications.

This project sets out to accomplish this by defining a core [Feature List](https://github.com/JordanBourne/OmniStack/documents/FEATURES.md) that should be replicated in each of the target languages within reasonable capabilities. The extra layer of difficulty of trying to build to the ability of hot swapping out different stacks on demand will add complexity in managing a large amount of dev ops skills as well.

Through the process of working on these applications, one should expect to improve significantly in their understanding of the fundamentals of the web, the current landscape of modern web development tools, how they all interact with each other, and the purpose each one serves.

## Project Decisions

##### Project Structure

The initial decision for the structure is creating a [OmniStack Repo](https://github.com/JordanBourne/OmniStack) that has a sub module for each codebase traded as a micro-service. The reason for following this behavior is as follows:
  - Allow for easily starting development on each new application since they can be treated as standalone applications
  - Allow for versioning of each micro-service so not everything needs to be updated at once
  - Allow for retroactive fixes of previous versions of each micro-service easily by managing version branches
