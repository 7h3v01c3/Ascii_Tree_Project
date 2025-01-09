# ASCII Tree Flow Builder

A simple, intuitive web-based tool for creating and managing ASCII tree diagrams. Perfect for documenting hierarchical structures, workflows, and site maps.

Check it out https://7h3v01c3.github.io/Ascii_Tree_Project/

## Features

- **Interactive Tree Building**: Click-to-edit nodes with simple commands
- **Node Management**:
  - Add new nodes with custom types
  - Mark nodes as complete (✔) or incomplete (✘)
  - Delete nodes
  - Navigate through the tree structure
- **Import/Export**:
  - Copy tree as ASCII text
  - Import existing ASCII trees
- **Node Types**:
  - Page
  - Section
  - Button
  - Breadcrumb
  - Modal
  - Dropdown
  - Form
  - Input
  - Link

## Usage

### Basic Operations

1. **Adding Nodes**:
   - Enter node name
   - Select node type
   - Add optional actions
   - Click "Add Node"

2. **Editing Nodes**:
   Click any node to:
   - Rename it
   - Mark as complete/incomplete/update 
   - Delete it
   - Navigate to it

3. **Node Commands**:
   When clicking a node, enter:
   - `select` to navigate to that node
   - `delete` to remove the node
   - `pass` to mark as complete (✔)
   - `fail` to mark as incomplete (✘)

### Example Tree
```├── Root: Your Cool Website
  ├── Link: Page 1
    └── Page: Page 1
      ├── Page: Page Stuff [Actions: Sign Up here goodness]
        └── Button: Signup
    ├── Link: Page 2
    ├── Link: Page 3
    └── Link: Page 4
```
## Contributing

We welcome contributions! Here are some areas where you can help improve the project:

### Planned Improvements
- Enhanced node editing (type changes, custom types)
- Better node insertion order handling
- Improved tree visualization
- Additional export formats

If you'd like to contribute:
1. Fork the repository
2. Create your feature branch
3. Submit a Pull Request

For major changes, please open an issue first to discuss what you would like to change.

## License

This project is licensed under the GNU General Public License v3.0 - see the [LICENSE](LICENSE) file for details.
