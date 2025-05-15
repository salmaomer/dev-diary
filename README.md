# dev-diary

### About My Self

##### A highly motivated recent graduate with a degree in Computer Network Systems, possessing a strong foundation in programming, software development, and a variety of programming languages. I am adept at problem-solving, creative thinking, and thriving in dynamic, fast-paced environments. I am eager to contribute to cutting-edge projects and further develop my skills and experience within the technology sector.

---

### What I learned from the Good Developer Mindset article

##### The article emphasizes that being a great developer is about more than just writing code—it's about how you think and approach your work. It outlines 16 key mindsets, from embracing continuous learning and breaking problems down, to prioritizing simplicity, user value, and effective collaboration. Developers should aim to write maintainable, readable code, automate repetitive tasks, and plan for long-term adaptability. The most effective developers iterate quickly, focus on solving real problems, and are comfortable making trade-offs. Ultimately, it's about cultivating habits and mental models that lead to smarter decisions and better software.

| Mindset / Principle             | Description                                                        | Benefit                               |
|--------------------------------|--------------------------------------------------------------------|----------------------------------------|
| Lifelong Learning              | Stay current by reading, taking courses, and learning from others  | Continuous growth                      |
| Problem Decomposition          | Break large problems into smaller tasks                            | Easier debugging and development       |
| Detective Debugging            | Investigate issues systematically with evidence                    | Faster, more accurate fixes            |
| Growth Mindset                 | Believe skills improve with practice                               | More resilience and persistence        |
| User-Focused Development       | Code for value, not elegance                                       | Real-world impact                      |
| Simplicity Over Complexity     | Avoid overengineering                                              | Easier maintenance                     |
| Prioritization and Trade-offs  | Make smart, goal-driven decisions                                  | Efficient use of time and resources    |
| Maintainability First          | Code with future changes in mind                                   | Sustainable development                |
| Design for Extensibility       | Make parts of the system pluggable and future-proof                | Adaptability                           |
| Iterative Development          | Ship early, iterate often                                          | Better alignment with user needs       |
| Collaboration and Communication| Work and share knowledge with team                                 | Stronger teamwork and better outcomes  |
| Complexity Management          | Use solid design principles like SRP, low coupling, high cohesion  | Cleaner architecture                   |
| Readable Code                  | Write understandable code with good naming and structure           | Easier onboarding and debugging        |
| System Understanding           | Learn how your code interacts with dependencies and infrastructure | Better performance and reliability     |
| Automation                     | Script repetitive tasks                                            | Time savings and reduced errors        |
| Progress Over Perfection       | Don’t let perfection delay delivery                                | Faster feedback and improvement loop   |


----

### What I learned from the Terminal Command Cheat sheet.
#### Basic Shell Commands:

##### ~ **pwd (Print Working Directory):** Displays the full path of the current directory from the root directory to where you are.[example](imge/pwd.PNG)

##### ~ **mkdir (Make Directory):** Creates a new directory in the specified location. If no path is given, it creates the directory in the current working directory.[example](imge/mkdir.PNG)


##### ~ **ls (List):** Lists the contents of a directory. If no directory is specified, it lists the contents of the current working directory.[example](imge/ls.PNG)

##### ~ **cd (Change Directory):** Changes the current directory. You can specify either a relative or absolute path. You can also use .. to move up one directory level.[example](imge/cd.PNG)


##### ~ **touch (Create New File):** Creates a new, empty file in the current directory with the specified name.[example](touch/ls.PNG)


##### ~ Helper Commands:
- **clear**: Clears the terminal screen.
- **Tab**: Autocompletes file and folder names.
- **↑ and ↓**: Cycle through previously entered commands.

#### File Management Commands:

##### ~ **cp:** (Copy) Copies files or directories from a source to a destination.[example](imge/cp.PNG)


##### ~  ***mv (Move):** Moves files or directories. It can also be used for renaming.[example](imge/mv.PNG)*


##### ~ **rm (Remove):** Deletes files or directories. Use -r to delete directories recursively.

#### Additional ls Command Options:
| Option | Description                                                 | Example  |
|--------|-------------------------------------------------------------|----------|
| `-a`   | Lists **all** contents including hidden files               | `ls -a`  |
| `-l`   | Lists contents in **long format** (permissions, size, etc.) | `ls -l`  |
| `-t`   | Sorts by **modification time**                              | `ls -t`  |

[example](imge/lso.PNG)


#### Redirection and Pipes: 

##### ~ **Append Redirect (>>):** Appends output from a command to a file.

##### ~ **Pipe (|):** Takes the output of one command and passes it as input to another command.

##### ~ **Redirect Output (> and >>):** Redirects output to a file, either overwriting or appending it.

##### ~ **cat:** Displays the contents of one or more files.[example](imge/cat.PNG)


##### ~ **grep (Search):** Searches for patterns within files. Can be used with different options like -i for case-insensitive search or -R to search recursively.

#### Command-Line Environment:

| Command                   | Purpose                                                              | Example                   |
|---------------------------|----------------------------------------------------------------------|---------------------------|
| `env`                     | Displays all **environment variables** for the current user          | `env`                     |
| `alias`                   | Creates a **shortcut** for a longer command                          | `alias pd="pwd"`          |
| `export`                  | Makes a **variable** available to child sessions                     | `export USER="Jane Doe"`  |
| `echo $HOME`              | Displays the path to the **home directory**                          | `echo $HOME`              |
| `history`                 | Shows the list of **previous commands** used in the session          | `history`                 |
| `source ~/.bash_profile`  | Loads or **refreshes configuration** changes made in `.bash_profile` | `source ~/.bash_profile`  |

#### Understanding the File System:

- The file system is organized in a **tree-like hierarchy**, with the **root directory (`/`)** at the top. Each directory can contain files and subdirectories.
  
- The **home directory (`$HOME`)** is specific to the current user and typically contains personal files, configurations, and settings.