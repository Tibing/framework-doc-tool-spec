# Custom Documentation Format Specification

Custom documentation form should be implemented according to [this example](custom-format-spec-example.json).

Sections:
- Metadata: contains language and framework. Other sections depends on this metadata.
- Modules: modules section should contains entities names lists in it properties or another identifier.
- Components: components contains metadata, component description, for example, description in comment above component, props and methods lists and constructor.
- Services, directives and pipes defines in the same way.

According to me react components haven't got inputs and outputs, they have just props, so we need to handle this.