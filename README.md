# Zig Code Flow

> [!NOTE]
> This extension is only in Beta. Please report any issues or suggestions on the GitHub repository.

A comprehensive VS Code extension providing Zig language support with powerful snippets, code completion, and productivity tools to enhance your Zig development experience.

## Features

📝 60+ Zig-specific code snippets covering all common patterns

### Snippet Categories
- 🔧 Basic language constructs
- 🏗️ Functions and data structures
- 🔄 Control flow and error handling
- 📚 Memory management utilities
- ✅ Testing helpers
- 🛠️ Development tools

Learn more about available snippets in the sections below.

## Installation

1. Open VS Code
2. Go to Extensions (Ctrl+Shift+X)
3. Search for "Zig Code Flow"
4. Click Install
5. Rate 5 stars!

## Snippets

### Basic Snippets
| Prefix | Description |
|--------|-------------|
| `ziglove` | Prints 'I love ZIG!' to the console |
| `zighello`, `helloworld` | Prints 'Hello, World!' to the console |
| `launch`, `startup` | Initializes a main function |
| `project`, `template` | Creates a new project template |
| `import` | Import a module using @import |
| `import_std`, `imps` | Import the standard library |
| `import_builtin`, `impb` | Import the builtin module |

### Functions
| Prefix | Description |
|--------|-------------|
| `fn` | Create a function with optional error union return type |
| `fn_generic` | Create a generic function with compile-time type parameter |
| `pub_fn` | Create a public function with optional error union return type |
| `inline_fn` | Create an inline function |
| `nested_fn` | Create a nested function inside a struct |

### Debug
| Prefix | Description |
|--------|-------------|
| `debug` | Print debug output using std.debug.print |

### Variables
| Prefix | Description |
|--------|-------------|
| `comptime` | Define a compile-time variable |
| `var` | Declare a variable with explicit type |
| `const` | Declare a constant with inferred type |
| `const_type` | Declare a constant with explicit type |

### Data Structures
| Prefix | Description |
|--------|-------------|
| `struct` | Create an anonymous struct |
| `const_struct` | Create a named struct type |
| `enum` | Create an enumeration with specified integer type |
| `union` | Create a tagged union type |

### Loops
| Prefix | Description |
|--------|-------------|
| `for_value` | Create a for loop iterating over values |
| `for_value_index` | Create a for loop with both value and index |
| `for_inline` | Create an inline for loop |
| `for_label` | Create a labeled for loop |
| `for_else` | Create a for loop with else branch |
| `while` | Create a while loop |
| `while_else` | Create a while loop with else branch |
| `while?` | Create a while loop for optional values with error handling |
| `while_label` | Create a labeled while loop with nested break |
| `while_inline` | Create an inline while loop |

### Array and Lists
| Prefix | Description |
|--------|-------------|
| `list` | Create an anonymous list literal |
| `array_init` | Initialize an array with optional sentinel |
| `array_list` | Create a dynamic array list |
| `fixed_array_list`, `array_list_length` | Create an array list with fixed capacity |
| `to_owned_slice` | Convert ArrayList to owned slice |
| `string_hash_map` | Create a hash map with string keys |
| `sort` | Sort slice using std.sort |

### Memory Management
| Prefix | Description |
|--------|-------------|
| `GPA`, `general_purpose_allocator` | Initialize a General Purpose Allocator (GPA) |
| `arena_allocator` | Initialize an Arena Allocator |
| `FBA`, `fixed_buffer_allocator` | Initialize a Fixed Buffer Allocator (FBA) |

### Control Flow
| Prefix | Description |
|--------|-------------|
| `if` | Create an if statement |
| `if_else` | Create an if-else statement |
| `if_else?` | Create an if-else for optional values with error handling |
| `switch` | Create a switch statement |
| `orelse` | Handle null with orelse return |

### Error Handling
| Prefix | Description |
|--------|-------------|
| `try` | Try an expression that may return an error |
| `catch` | Catch and handle errors from an expression |
| `defer` | Create a defer block |
| `errdefer` | Create an errdefer block |
| `error` | Create an error value |
| `error_set` | Define an error set |

### Testing
| Prefix | Description |
|--------|-------------|
| `test` | Create a test block |
| `expect` | Add a test expectation using std.testing |

### Assembly
| Prefix | Description |
|--------|-------------|
| `asm` | Insert inline assembly code |

### File Information
| Prefix | Description |
|--------|-------------|
| `filename` | Insert current file name with extension |
| `filenamebase` | Insert current file name without extension |
| `directory` | Insert current directory path |
| `abspath` | Insert absolute path of current file |
| `relpath` | Insert workspace-relative path of current file |
| `workspacename` | Insert current workspace name |
| `workspacefolder` | Insert current workspace root folder path |

### Random values
| Prefix | Description |
|--------|-------------|
| `randomvalue` | Insert random number |
| `randomhex` | Insert random hexadecimal value |
| `uuid` | Insert a UUID (Universal Unique Identifier) |

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request. For major changes, please open an issue first to discuss what you would like to change.

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add some amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## Support

If you find any bugs or have feature requests, please open an issue on the GitHub repository.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
