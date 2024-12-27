## YAML-Crash-Course
=====================

### 1. Human-Readable Format:

- YAML (YAML Ain't Markup Language) is designed to be easy for humans to read and write. It uses indentation to define structure, making it similar in appearance to Python or plain text.

### 2. Key-Value Pairs:

- YAML primarily uses key-value pairs, where the key and value are separated by a colon and a space. Example:

```YAML
name: John Doe
age: 30
```

### 3. Hierarchy Through Indentation:

- YAML uses indentation (spaces, not tabs) to represent nested structures, like dictionaries or lists. Proper indentation is crucial as it defines the structure of the data.

```YAML
address:
  street: 123 Main St
  city: Anytown
```

### 4. Lists:

- Lists in YAML are denoted by a hyphen followed by a space. Each item in the list is placed on a new line.

```YAML
fruits:
  - Apple
  - Orange
  - Banana
```

### 5. Comments:

- Comments in YAML start with a # and can be placed anywhere in the document.

```YAML
# This is a comment
name: John Doe  # Inline comment
```

### 6. Data Types:

- YAML supports various data types including strings, numbers, booleans, nulls, and complex types like lists and dictionaries. Strings don’t need to be quoted unless they contain special characters.

```YAML
age: 30         # Integer
married: true   # Boolean
children: null  # Null
```

### 7. Multiline Strings:

- YAML allows for multiline strings using | (preserves newlines) or > (folds newlines into spaces).

```YAML
description: |
  This is a
  multiline string
```

### 8. Anchors & Aliases:

- Anchors (&) and aliases (*) allow you to reuse content. An anchor defines a value, and an alias refers back to it.

```YAML
default: &default_settings
  timeout: 30
  retries: 3

server1:
  <<: *default_settings
  host: server1.example.com
```

### 9. YAML vs JSON:

- YAML is a superset of JSON, meaning any valid JSON is also valid YAML. However, YAML is more user-friendly due to its readability and concise syntax.

### 10. File Extensions and Usage:

- YAML files typically have the .yaml or .yml extension and are commonly used for configuration files, data exchange between languages, and more in DevOps, CI/CD pipelines, and other contexts.

