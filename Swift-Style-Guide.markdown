# Fundamentals
- Clarity at the point of use is your most important goal
- Clarity is more important than brevity
- Write a documentation comment for every declaration
# Naming
- Include all the words needed to avoid ambiguity for a person reading code where the name is used
- Omit needless words. Every word in a name should convey salient information at the use site.
- Name variables, parameters, and associated types according to their roles,rather than their type constraints
- Compensate for weak type information to clarify a parameter’s role
- Prefer method and function names that make use sites form grammatical English phrases.
- Begin names of factory methods with “make”
- The first argument to initializer and factory methods calls should not form a phrase starting with the base name
- Those without side-effects should read as noun phrases
- Those with side-effects should read as imperative verb phrases
- When the operation is naturally described by a verb, use the verb’s imperative for the mutating method and apply the “ed” or “ing” suffix to name its nonmutating counterpart
- When the operation is naturally described by a noun, use the noun for the nonmutating method and apply the “form” prefix to name its mutating counterpart
- Uses of Boolean methods and properties should read as assertions about the receiver when the use is nonmutating
- Protocols that describe what something is should read as nouns
- Protocols that describe a capability should be named using the suffixes able, ible, or ing
- The names of other types, properties, variables, and constants should read as nouns
- Avoid obscure terms if a more common word conveys meaning just as well
- Stick to the established meaning if you do use a term of art
- Avoid abbreviations
- Embrace precedent. Don’t optimize terms for the total beginner at the expense of conformance to existing culture
- Document the complexity of any computed property that is not O(1)
- Prefer methods and properties to free functions
- Follow case conventions. Names of types and protocols are UpperCamelCase. Everything else is lowerCamelCase.
- Methods can share a base name when they share the same basic meaning or when they operate in distinct domains
- Choose parameter names to serve documentation
- Take advantage of defaulted parameters when it simplifies common uses
- Prefer to locate parameters with defaults toward the end of the parameter list
- Omit all labels when arguments can’t be usefully distinguished
- In initializers that perform value preserving type conversions, omit the first argument label
- When the first argument forms part of a prepositional phrase, give it an argument label
if the first argument forms part of a grammatical phrase, omit its label, appending any preceding words to the base name
- Label all other arguments
- Label tuple members and name closure parameters where they appear in your API
- Take extra care with unconstrained polymorphism (e.g. Any, AnyObject, and unconstrained generic parameters) to avoid ambiguities in overload sets
- When creating custom delegate methods, an unnamed first parameter should be the delegate source.
# Reference
[1. API Design Guidelines](https://swift.org/documentation/api-design-guidelines/)
[2. raywenderlich/swift-style-guide](https://github.com/raywenderlich/swift-style-guide)
