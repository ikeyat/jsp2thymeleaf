# jsp2thymeleaf

A migration soluition from JSP to Thymeleaf template.
* Migration rules and verifications
* Conversion tools

# Motivation

There are a lot of existing JSP resources. However, JSP has been legacy view technology in Java.
Nowaday most developers are using other template technologies such as Thymeleaf and Freemarker.
Especially in Spring users, they love to use Thymeleaf because it provides powerful supports to Spring.
In addition, Spring Boot unrecommends to use JSP.

I forecast most people want to migrate existing JSP resources to Thyemeleaf templates.
Of course, it is impossible to migrate completely because JSP is more flexible.
But partial migration must help developers.

# Pre-conditions
## Scope
- View only
- Pure JSP, Spring and Apache Tiles

## Versions of libraries

|Libraries         | version   |
|:-----------------|:----------|
|Java SE           |1.8.x      |
|JSP               |2.2        |
|Thymeleaf         |3.0.x      |
|Thymeleaf-Spring4 |3.0.x      |
|Spring            |4.3.x      |
|Spring Security   |4.2.x      |
|Spring Boot       |1.5.x      |
|Apache Tiles      |3.0.x      |

## Knowledge baseline for readers
- Java SE / Java EE (JSP/Servlet)
- Thymeleaf
- Spring MVC
- Spring Security (recommended)
- Spring Boot (recommended)
- Apache Tiles (recommended)
- Maven (recommended)

# Migration policy
- Don't aim exact same html
    - Aim similar looking html
- Don't cover all patterns completely
    - In some cases we must be forced to giveup
    - Limitation of time and resources
- Test first
    - Write rules after experiments and testing
- Expect automation in the fucture
    - This is not a dream
- Use English
    - For all people!

# Migration rules

See [MigrationRules.md](MigrationRules.md)

# Migration verifications

We are providing verifications and evidences of migration rules.
In other words, we verify we can get almost same html from both JSPs and migrated Thymeleaf templates.

TBD

# Conversion tools

TBD
