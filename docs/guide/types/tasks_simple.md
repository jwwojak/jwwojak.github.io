# Documenting Simple Procedures

Task documentation shows readers how to do something. It breaks down a workflow into the sequential or non-sequential steps required to complete a process. Write task docs to explain how to use the thing you built rather than why you created it.

For a task document example, see [Adding gRPC to Apollo](https://backstage.spotify.net/docs/default/component/declarative-infra/#concepts).

## Structure

This diagram shows how to organize a simple task document:

![hbk_task_doc.png](../images/hbk_task_doc.png)

Describing each step in a task is essential. This includes obvious steps like "Click **Save**." Simple actions might not be self-evident, or require a separate step, so you need to include them. For your readers, few things are more maddening than vague or incomplete instructions. You just gotta do it.

!!! tip
    For procedures that have 6 or more steps, see [Documenting Complex Tasks][4].


## Features

Common features of task documentation include:

- [Descriptive titles][5] that suggest or summarize the main topic.
- Numbered steps (if steps must be completed sequentially).
- **Bold text** for UI elements that you interact with. See the section on [Bold Text](../style/hbk_style_bold.md).
- Bulleted steps (if steps don't need to follow in sequential order).
- The text "_(Optional)_" at the beginning of a step to indicate that it isn't required.
- Images.
- Separate sections to break up long procedures. See [Writing About Complex Tasks][4].

## Style advice

When writing task documentation:

- Start the document title with a verb that matches the procedure (e.g., Create, Build, Configure, Implement, etc.). This indicates the document's type (task) and content (steps on how to do something).

- Start the procedure right away. Avoid long introductions or overviews (use a concept page for that). It is OK to note task pre- and post-requisites or provide context, but try to start the task steps quickly.

- Start each step using a verb in the [imperative mood][1]. For example, "Click this," "Select that," "Choose X." Procedural steps are commands, not requests.

- Link to other docs that describe step options or strategies. You can list the options (try bullets), but don't clutter up instructions with extensive explanations. Put that information in a separate document.

- Follow the advice in [Writing About UI Controls][6] when describing user interactions with UI features.

## What to avoid

Don't start your task doc with a long introduction or "overview" content. Put this information in a separate [concept document][2]. Remember, your users read task documents to complete a process. They want instructions first and foremost. Don't bury the steps under a long introduction.

## Related topics

- [Concept Docs][2]
- [Reference Docs][3]
- [Writing About Complex Tasks][4]

<!-- Reference links -->

[1]: https://en.wikipedia.org/wiki/Imperative_mood "imperative mood"
[2]: hbk_types_concepts.md "concept doc link"
[3]: hbk_types_reference.md "reference doc link"
[4]: hbk_types_complex.md "complex tasks"
[5]: ../style/hbk_style_headers.md "titles"
[6]: ../style/hbk_style_intro.md "UI style guide section"
