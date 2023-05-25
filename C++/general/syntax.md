# C/C++ Syntax

## 1 Environment

### 1.1 Language

- All code shall conform to ISO/IEC 14882 standard C++.

- Source code can only contain ASCII characters.

- Literal suffixes shall use uppercase rather than lowercase letters.

## 2 Naming Conventions

### 2.1 Naming Identifiers

#### `const`

Use `SCREAMING_SNAKE_CASE` for all const variables.

#### `static`

Identifier `static` should be in the back of the `volatile`.

#### `volatile`

Identifier `volatile` should be in the front.

### 2.2 Naming Entities

#### namespace

Use `snake_case` for namespace.

#### Macro

Use `SCREAMING_SNAKE_CASE` for Macro.

- `#define` should not be used to define numerical constants.

#### Class

Use `PascalCase` for class.

#### Class Members

Generally, class member functions name should start with a verb.

##### Public

Use `camelCase` for public functions.

##### Private

Use `_camelCase` for private functions.
Use Hungarian notation for private variables;

##### Protected

Use `_camelCase` for private functions.
Use Hungarian notation for protected variables;

#### Struct

#### Struct Member functions

#### Union

#### Enum

Use `PascalCase` for enum class.

Enum type should be defined in the following patterns:

```c++
enum class SomeName : uint8_t{
    A,
    B,
    C,

    ENUM_SIZE
};
```

#### Enumerator

Use `SCREAMING_SNAKE_CASE` for enumerator.

#### Typedef

`typedef` should be deprecated in modern C++, use `using` instead.

#### Global Functions

Use `PascalCase` for global functions.

#### Global Variables

Use `PascalCase` for global variables.

#### Local Variables

Use `camelCase` for local variables.

- Local variables should be marked as `static` in embedded dev.

#### Parameter

Use `camelCase` for parameters.
