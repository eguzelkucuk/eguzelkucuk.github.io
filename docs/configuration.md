---
layout: default
title: Docker-based Microservice Architecture with .Net 8
nav_order: 2
---

# Docker-based Microservice Architecture with .Net 8
{: .no_toc }

Software architecture is a discipline of planning and design that forms the foundation of a project, playing a crucial role in the software development process.
{: .fs-6 .fw-300 }

## Table of contents
{: .no_toc .text-delta }

1. TOC
{:toc}

---

View this site's [\_config.yml](https://github.com/just-the-docs/just-the-docs/tree/main/_config.yml) file as an example.

## Preface

Dear Readers,

The world of technology is evolving rapidly, and the field of software development continues to grow steadily. This growth presents new opportunities and challenges, and as developers, we must closely monitor these changes and keep up with the latest technologies.

This book is titled ".Net 8 with Docker-Based Microservice Architecture" and brings together these exciting technologies, addressing a crucial aspect of modern software development. By harnessing the power of .Net 8 and the flexibility of Docker, this book is prepared for anyone interested in exploring the intricacies of Microservice Architecture.

Within the pages of this book, you will learn all the intricacies of creating Microservices using .Net 8 and Docker. Whether you are an experienced developer or a beginner, this book will guide you step by step in building complex systems. Through the examination of real-world scenarios and applications, you will learn to apply these concepts in practice.

The aim of this book is to take you into the world of Microservices with .Net 8 and Docker, enabling you to confidently harness these exciting technologies. Each chapter is filled with practical examples that will help you acquire more knowledge and improve your skills.

I am here to guide you on this journey. I hope this book becomes a valuable resource in your software development journey and opens the doors to the world of .Net 8 with Docker-based Microservices.

Wishing you happy reading!

## What Is Architecture?

In the rapidly advancing world of software technologies, software architecture serves as a fundamental determinant and guide in the process of creating a system, application, or structure. The concept of architecture ensures that a project begins on the right foundation, has a solid structure, and can adapt to future requirements. Consequently, in the corporate world, architecture is not just a luxury but a necessity.

Architecture serves as a tool for managing complexity. Modern software projects typically involve numerous components, subsystems, and dependencies. Managing this complexity requires careful planning and design to provide the functionality and performance the job demands. Architecture provides the necessary framework to address, control, and manage this complexity while determining how different components of the project will come together and collaborate.

Optimizing systems is another critical role of architecture. A good architectural design ensures that resources are used efficiently. Efficiently managing resources such as database access, network traffic, and server resources is crucial for the success of a project. Additionally, optimizing business processes and eliminating unnecessary complexities are part of architectural decisions.

Long-term success is also a goal for architecture. Architecture considers not only the current needs of a project but also future requirements. A good architecture takes into account sustainability and growth potential at all stages of the project's lifecycle. This helps organizations adapt to future changes effectively.

### Architectural Perspective: The Fundamental Determinant of Software

Software projects are growing in complexity and requirements every day. Consequently, every software project requires a solid foundation for successful completion. This is where the "Architectural Perspective" comes into play.

The architectural perspective determines the fundamental design and organization of a software project. This approach plans how the project will be structured, how components will be assembled, and how the operation will be conducted.

### Building a Plan

Architecture is the construction of a plan that forms the foundation of an organization or project. This plan is typically created with a long-term perspective and is designed to help the organization achieve its goals. A good architectural plan simplifies complexity, enhances efficiency, and enables the organization to adapt to growth.

### Optimization and Efficiency:

Architecture aims to optimize systems and processes, helping them make efficient use of resources. This includes saving time, costs, and resources. A well-designed architecture ensures that the organization optimally utilizes its resources.

## Managing Complexity: The Key to Success in Software Projects

The software development process is becoming increasingly complex with each passing day. Large and complex software projects involve numerous components, subsystems, and dependencies. This complexity can potentially impact the success of a project, but it's important to note that it can be overcome with the right approach. This is where "Managing Complexity" comes into play and offers the key to success in software projects.

### Understanding Complexity

To manage complexity, it is essential to first understand it. Understanding how different components, data flows, and interactions work within a software project is the foundation for addressing complexity correctly. This begins with clearly defining the project's requirements and objectives.

The project's core requirements are the starting point for understanding complexity. Understanding user needs and project goals helps determine the project's scope and complexity. Details such as the necessity of specific functions, the processing of data, and the desired user experience are factors that shape the project's complexity.

Understanding how the components and systems within the project come together and interact aids in reducing complexity. Mapping workflows and interactions, such as data flows, business processes, user interfaces, and inter-system connections, visually represents the complexity of the project. Understanding dependencies and integrations among the components used in the project assists in managing complexity.

Clearly identifying dependencies on external resources, such as external services, APIs, or databases, helps us understand the potential risks and challenges of the project. Determining the technologies and platforms to be used in the project influences its complexity. Technical decisions like which programming languages, databases, server architectures, or development tools to use shape the project's complexity.

Identifying potential risks and issues that can affect the project is crucial for reducing complexity. Defining risks, such as data security, performance issues, compliance requirements, and resource constraints, enables better project management.

### Effective Planning

Effective planning begins with clearly defining the project's requirements. These requirements may encompass user needs, business processes, and technical details. The clear definition of requirements ensures an understanding of the project's scope and goals. Every project has specific objectives, and a good planning process necessitates the clear definition of these goals. Clear goal-setting is important for measuring and tracking the project's success.

A well-thought-out planning process requires the project to be supported by an appropriate software architecture. This entails selecting an architecture that aligns with the project's requirements, scalability expectations, and performance goals. Technical details such as database management, user interface design, and security requirements are evaluated at this stage.

Effective planning involves determining the project's timeline and resource requirements. The identification of when specific tasks need to be completed and which resources will be included in the project is determined during this phase. Time and resource management significantly impact the project's budget and duration.

Facilitating effective communication and collaboration among different teams working on the project is critical for success. A good planning process establishes communication channels and collaboration processes.

Clear communication among team members aids in the smooth progress of the project. Continuous monitoring and evaluation of the project are important for measuring the success of the plan and making necessary adjustments when needed. Adapting to changing requirements and conditions ensures the successful completion of the project.

### Modular Approach

The modular approach suggests breaking down software into small, independent components, known as modules. Each module takes on a specific function or responsibility. Modules typically interact in a limited manner with one another and are developed, tested, and maintained independently.

A modular approach simplifies software maintenance. Changes in one module can be made without affecting other modules. This allows for easier detection and correction of errors. Additionally, adding new features or making updates becomes smoother.

A modular approach facilitates the concurrent work of different teams or developers on different modules. This can aid in the project's swift progression. The independence among modules supports parallel development. Modularity encourages the reusability of software components. A module can be used in different projects or different sections, which accelerates the software development process and reduces costs.

A modular approach makes it easy to isolate errors. An error in one module does not affect other modules. This enables faster identification and correction of errors. Modularity allows software to be scalable. New requirements or increased loads can be accommodated by adding new modules, ensuring the project's readiness for future growth.

### Documentation and Communication

Effective communication and documentation processes are necessary to manage complexity. Clear and continuous communication within the project team allows everyone to track the project's progress and changes. Additionally, documenting the project helps team members and future developers understand it.

1. Defining Requirements: Documentation ensures a clear definition of the project's requirements, helping us understand the project's scope and goals.

Design Documentation: Design details such as software architecture, design patterns, and component functionality are documented. This helps us understand how the project works and how it is structured.

2. Code Documentation: The code itself must be documented. Good code documentation makes it easier for other developers or teams to understand and use the code.

3. Issue Tracking: Documentation is an important tool for recording and tracking issues. Documenting where and when an issue arises helps resolve issues quickly.

Communication refers to the interaction and sharing of information among all teams involved in the project. Effective communication plays a critical role in the success of the project.

4. Team Communication: Clear and effective communication within the project team enhances collaboration and coordination. Regular communication among developers, designers, testing teams, and business analysts ensures the smooth progress of the project.

5. Client Communication: Communication with the client or project owner helps us understand the project's requirements and goals. Client feedback ensures the project is moving in the right direction.

6. Change Management: Good communication makes it easier to manage changes in the project. The reasons, impacts, and approvals of changes are regularly shared.

7. Problem Solving: Problems and obstacles encountered during the project must be resolved promptly. Good communication enables early detection and resolution of issues.

### Testing and Feedback

To manage complexity, continuous testing and feedback processes should be implemented. This helps in early error detection and correction. Tests should be conducted at every stage of the project, and their results should be taken into account.

#### Testing

1. Unit Tests: These are used to test the smallest components of the software, such as functions or classes. Unit tests verify whether each component produces the expected results.

2. Integration Tests: These test whether different components come together and work correctly. Interactions between components are examined in this stage.

3. System Tests: These assess the entire software, often through user scenarios, to test usability, performance, and reliability.

4. Acceptance Tests: These ensure that the software is approved by end-users or the project owner. Acceptance tests demonstrate whether the software meets the defined requirements.

#### Feedback

1. Bug Reports: Errors and issues discovered during software testing are documented. Bug reports explain what the issues are, how they can be reproduced, and how critical they are.

2. Performance Monitoring: Software performance is monitored during real usage. Performance metrics such as processing times, response times, and resource utilization are examined.

3. User Feedback: Feedback provided by end-users or project owners offers crucial information about software usability and functionality.

4. Change Requests: New requirements or changes may arise as the project progresses. Change requests facilitate the continuous updating of the software.

## Search

```yaml
# Enable or disable the site search
# Supports true (default) or false
search_enabled: true

search:
  # Split pages into sections that can be searched individually
  # Supports 1 - 6, default: 2
  heading_level: 2
  # Maximum amount of previews per search result
  # Default: 3
  previews: 3
  # Maximum amount of words to display before a matched word in the preview
  # Default: 5
  preview_words_before: 5
  # Maximum amount of words to display after a matched word in the preview
  # Default: 10
  preview_words_after: 10
  # Set the search token separator
  # Default: /[\s\-/]+/
  # Example: enable support for hyphenated search words
  tokenizer_separator: /[\s/]+/
  # Display the relative url in search results
  # Supports true (default) or false
  rel_url: true
  # Enable or disable the search button that appears in the bottom right corner of every page
  # Supports true or false (default)
  button: false
```

## Mermaid Diagrams
{: .d-inline-block }

New (v0.4.0)
{: .label .label-green }

The minimum configuration requires the key for `version` ([from jsDelivr](https://cdn.jsdelivr.net/npm/mermaid/)) in `_config.yml`:

```yaml
mermaid:
  # Version of mermaid library
  # Pick an available version from https://cdn.jsdelivr.net/npm/mermaid/
  version: "9.1.3"
```

Provide a `path` instead of a `version` key to load the mermaid library from a local file.

See [the Code documentation]({% link docs/ui-components/code.md %}#mermaid-diagram-code-blocks) for more configuration options and information.

## Aux links

```yaml
# Aux links for the upper right navigation
aux_links:
  "Just the Docs on GitHub":
    - "//github.com/just-the-docs/just-the-docs"

# Makes Aux links open in a new tab. Default is false
aux_links_new_tab: false
```

## Heading anchor links

```yaml
# Heading anchor links appear on hover over h1-h6 tags in page content
# allowing users to deep link to a particular heading on a page.
#
# Supports true (default) or false
heading_anchors: true
```

## External navigation links
{: .d-inline-block }

New (v0.4.0)
{: .label .label-green }

External links can be added to the navigation through the `nav_external_links` option.
See [Navigation Structure]({% link docs/navigation-structure.md %}#external-navigation-links) for more details.

## Footer content

```yaml
# Footer content
# appears at the bottom of every page's main content
# Note: The footer_content option is deprecated and will be removed in a future major release. Please use `_includes/footer_custom.html` for more robust
markup / liquid-based content.
footer_content: "Copyright &copy; 2017-2020 Patrick Marsceill. Distributed by an <a href=\"https://github.com/just-the-docs/just-the-docs/tree/main/LICENSE.txt\">MIT license.</a>"

# Footer last edited timestamp
last_edit_timestamp: true # show or hide edit time - page must have `last_modified_date` defined in the frontmatter
last_edit_time_format: "%b %e %Y at %I:%M %p" # uses ruby's time format: https://ruby-doc.org/stdlib-2.7.0/libdoc/time/rdoc/Time.html

# Footer "Edit this page on GitHub" link text
gh_edit_link: true # show or hide edit this page link
gh_edit_link_text: "Edit this page on GitHub."
gh_edit_repository: "https://github.com/just-the-docs/just-the-docs" # the github URL for your repo
gh_edit_branch: "main" # the branch that your docs is served from
# gh_edit_source: docs # the source that your files originate from
gh_edit_view_mode: "tree" # "tree" or "edit" if you want the user to jump into the editor immediately
```

_note: `footer_content` is deprecated, but still supported. For a better experience we have moved this into an include called `_includes/footer_custom.html` which will allow for robust markup / liquid-based content._

- the "page last modified" data will only display if a page has a key called `last_modified_date`, formatted in some readable date format
- `last_edit_time_format` uses Ruby's DateTime formatter; see examples and more information [at this link.](https://apidock.com/ruby/DateTime/strftime)
- `gh_edit_repository` is the URL of the project's GitHub repository
- `gh_edit_branch` is the branch that the docs site is served from; defaults to `main`
- `gh_edit_source` is the source directory that your project files are stored in (should be the same as [site.source](https://jekyllrb.com/docs/configuration/options/))
- `gh_edit_view_mode` is `"tree"` by default, which brings the user to the github page; switch to `"edit"` to bring the user directly into editing mode

## Color scheme

```yaml
# Color scheme supports "light" (default) and "dark"
color_scheme: dark
```

<button class="btn js-toggle-dark-mode">Preview dark color scheme</button>

<script>
const toggleDarkMode = document.querySelector('.js-toggle-dark-mode');

jtd.addEvent(toggleDarkMode, 'click', function(){
  if (jtd.getTheme() === 'dark') {
    jtd.setTheme('light');
    toggleDarkMode.textContent = 'Preview dark color scheme';
  } else {
    jtd.setTheme('dark');
    toggleDarkMode.textContent = 'Return to the light side';
  }
});
</script>

See [Customization]({% link docs/customization.md %}) for more information.

## Callouts
{: .d-inline-block }

New (v0.4.0)
{: .label .label-green }

To use this feature, you need to configure a `color` and (optionally) `title` for each kind of callout you want to use, e.g.:

```yaml
callouts:
  warning:
    title: Warning
    color: red
```

This uses the color `$red-000` for the background of the callout, and `$red-300` for the title and box decoration.[^dark] You can then style a paragraph as a `warning` callout like this:

```markdown
{: .warning }
A paragraph...
```

[^dark]:
    If you use the `dark` color scheme, this callout uses `$red-300` for the background, and `$red-000` for the title.

The colors `grey-lt`, `grey-dk`, `purple`, `blue`, `green`, `yellow`, and `red` are predefined; to use a custom color, you need to define its `000` and `300` levels in your SCSS files. For example, to use `pink`, add the following to your `_sass/custom/setup.scss` file:

```scss
$pink-000: #f77ef1;
$pink-100: #f967f1;
$pink-200: #e94ee1;
$pink-300: #dd2cd4;
```

You can override the default `opacity` of the background for a particular callout, e.g.:

```yaml
callouts:
  custom:
    color: pink
    opacity: 0.3
```

You can change the default opacity (`0.2`) for all callouts, e.g.:

```yaml
callouts_opacity: 0.3
```

You can also adjust the overall level of callouts.
The value of `callouts_level` is either `quiet` or `loud`;
`loud` increases the saturation and lightness of the backgrounds.
The default level is `quiet` when using the `light` or custom color schemes,
and `loud` when using the `dark color scheme.`

See [Callouts]({% link docs/ui-components/callouts.md %}) for more information.

## Google Analytics

{: .warning }
> [Google Analytics 4 will replace Universal Analytics](https://support.google.com/analytics/answer/11583528). On **July 1, 2023**, standard Universal Analytics properties will stop processing new hits. The earlier you migrate, the more historical data and insights you will have in Google Analytics 4.

Universal Analytics (UA) and Google Analytics 4 (GA4) properties are supported.

```yaml
# Google Analytics Tracking (optional)
# Supports a CSV of tracking ID strings (eg. "UA-1234567-89,G-1AB234CDE5")
ga_tracking: UA-2709176-10
ga_tracking_anonymize_ip: true # Use GDPR compliant Google Analytics settings (true/nil by default)
```

### Multiple IDs
{: .d-inline-block .no_toc }

New (v0.4.0)
{: .label .label-green }

This theme supports multiple comma-separated tracking IDs. This helps seamlessly transition UA properties to GA4 properties by tracking both for a while.

```yaml
ga_tracking: "UA-1234567-89,G-1AB234CDE5"
```

## Document collections

By default, the navigation and search include normal [pages](https://jekyllrb.com/docs/pages/).
You can also use [Jekyll collections](https://jekyllrb.com/docs/collections/) which group documents semantically together.

{: .warning }
> Collection folders always start with an underscore (`_`), e.g. `_tests`. You won't see your collections if you omit the prefix.

For example, put all your test files in the `_tests` folder and create the `tests` collection:

```yaml
# Define Jekyll collections
collections:
  # Define a collection named "tests", its documents reside in the "_tests" directory
  tests:
    permalink: "/:collection/:path/"
    output: true

just_the_docs:
  # Define which collections are used in just-the-docs
  collections:
    # Reference the "tests" collection
    tests:
      # Give the collection a name
      name: Tests
      # Exclude the collection from the navigation
      # Supports true or false (default)
      # nav_exclude: true
      # Fold the collection in the navigation
      # Supports true or false (default)
      # nav_fold: true  # note: this option is new in v0.4
      # Exclude the collection from the search
      # Supports true or false (default)
      # search_exclude: true
```

The navigation for all your normal pages (if any) is displayed before those in collections.

<span>New (v0.4.0)</span>{: .label .label-green }
Including `nav_fold: true` in a collection configuration *folds* that collection:
an expander symbol appears next to the collection name,
and clicking it displays/hides the links to the top-level pages of the collection.[^js-disabled]

[^js-disabled]: <span>New (v0.6.0)</span>{: .label .label-green }
    When JavaScript is disabled in the browser, all folded collections are automatically expanded,
    since clicking expander symbols has no effect.
    (In previous releases, navigation into folded collections required JavaScript to be enabled.)

You can reference multiple collections.
This creates categories in the navigation with the configured names.

```yaml
collections:
  tests:
    permalink: "/:collection/:path/"
    output: true
  tutorials:
    permalink: "/:collection/:path/"
    output: true

just_the_docs:
  collections:
    tests:
      name: Tests
    tutorials:
      name: Tutorials
```

When *all* your pages are in a single collection, its name is not displayed.

The navigation for each collection is a separate name space for page titles: a page in one collection cannot be a child of a page in a different collection, or of a normal page.
