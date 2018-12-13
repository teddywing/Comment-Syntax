Comment Syntax
==============

A database of comment markers in a variety of languages. Given a language or
file extension, this makes it possible to easily get the comment marker syntax
for that language.


## Keys

### Inline
| Key                 | Definition                                                         |
| ---                 | ----------                                                         |
| `line`              | Line comment marker                                                |
| `line_alt[#]`       | Alternate line comment marker                                      |
| `line_solo`         | Whole line comment (cannot appear on the same line as source code) |
| `line_solo_alt[#]`  | Alternate whole line comment                                       |
| `line_start`        | Single-line starting marker                                        |
| `line_end`          | Single-line ending marker                                          |
| `line_start_alt[#]` | Alternate single-line starting marker                              |
| `line_end_alt[#]`   | Alternate single-line ending marker                                |
| `inline`            | Inline comment (must follow source code)                           |

### Multiline
| Key                       | Definition                                                         |
| ---                       | ----------                                                         |
| `multi_start`             | Multi-line starting marker                                         |
| `multi_end`               | Multi-line ending marker                                           |
| `multi_start_alt[#]`      | Alternate multi-line starting marker                               |
| `multi_end_alt[#]`        | Alternate multi-line ending marker                                 |
| `multi_solo_start`        | Multi-line starting marker (must appear on its own line)           |
| `multi_solo_end`          | Multi-line ending marker (must appear on its own line)             |
| `multi_solo_start_alt[#]` | Alternate multi-line starting marker (must appear on its own line) |
| `multi_solo_end_alt[#]`   | Alternate multi-line ending marker (must appear on its own line)   |

### Miscellaneous
| Key          | Definition                                          |
| ---          | ----------                                          |
| `end_solo`   | End of program marker (must appear on its own line) |
| `extensions` | List of file extensions associated with a language  |

### Documentation
| Key                      | Definition                                                             |
| ---                      | ----------                                                             |
| `doc_line`               | Documentation line comment marker                                      |
| `doc_line_alt[#]`        | Alternate documentation line comment marker                            |
| `doc_multi_start`        | Multi-line documentation starting marker                               |
| `doc_multi_end`          | Multi-line documentation ending marker                                 |
| `doc_multi_start_alt[#]` | Alternate multi-line documentation starting marker                     |
| `doc_multi_end_alt[#]`   | Alternate multi-line documentation ending marker                       |
| `doc_multi_solo_start`   | Multi-line documentation starting marker (must appear on its own line) |
| `doc_multi_solo_end`     | Multi-line documentation ending marker (must appear on its own line)   |


`[#]` denotes an optional number, permitting more than one alternate.


## License
Copyright © 2018 Teddy Wing. Licensed under the Creative Commons
Attribution-ShareAlike 4.0 International Public License (see the included
LICENSE file).
