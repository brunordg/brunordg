# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Repository Overview

This is a personal portfolio repository that showcases work with Java and related technologies. Currently, it contains a GitHub profile README. As projects are added, this document will be expanded with specific build, test, and development commands.

## Primary Technologies

- **Java** — primary language for projects in this repository
- **Spring Framework** — preferred for backend development
- **Kotlin** — used for some projects
- **Build Tools** — Maven (pom.xml) or Gradle (build.gradle) depending on project

## Development Setup

When Java projects are added to this repository, include:

1. **Build Instructions** — How to compile and package the project
   - For Maven: `mvn clean install`
   - For Gradle: `./gradlew build`

2. **Running Tests**
   - For Maven: `mvn test` or `mvn test -Dtest=ClassName`
   - For Gradle: `./gradlew test` or `./gradlew test --tests ClassName`

3. **Linting and Code Quality**
   - Checkstyle for style enforcement
   - SpotBugs for bug detection
   - PMD for code analysis

4. **Running the Application**
   - Document how to start each application (Spring Boot server, CLI tool, etc.)
   - Include port numbers and environment variables if applicable

## Code Architecture Notes

As projects are added, document:
- Main application entry points and package structure
- Key design patterns or architectural choices
- Major dependencies and their purposes
- Database schema if applicable
- API endpoints (if applicable)

## Adding to This Repository

When adding a new Java project:
1. Create a new subdirectory for the project
2. Include its own README with project-specific documentation
3. Update this CLAUDE.md with build/test commands and key architecture details
4. Ensure each project has a pom.xml or build.gradle with clear dependencies
