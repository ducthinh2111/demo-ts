# Introduction to TypeScript

# Agenda:
[ ] 1. What is TypeScript and Why use?
        + JavaScript is dynamic typing (run the code to know the type) which has drawbacks
        + TypeScript uses static typing (know the type before running)
        Why use:
            + Reveal potential bugs
            + Non-exceptions failure
            + Suggestion
            + Rich configurations options (When you know your code better than TS)
            + Generics and Interface
[ ] 2. Installing TypeScript
        + tsc (TypeScript compiler)
        + Why need compiler?
[ ] 3. Type
        + Explicit type (type annotation, return type annotation)
        + Implicit type
        + Basics:
            * Primitive types: string, number, boolean
            * Array type
            * any type
            * Object type
                - Optional properties
            * Union type
                - Common member
                - Type guard
            * Type alias
                - Don't want to repeat declare union type or object type
                - "type" keyword
            * Interface
                - Another way to declare object type
            * Type casting (ex: DOM manipulation)
                - "as" keyword
            * Literal type
                - Variables that are assigned using "const"
                - string literal
                - numeric literal
                - boolean literal
            * Non-null Assertion Operator
[ ] 4. Decorator
        + Example: Autobind