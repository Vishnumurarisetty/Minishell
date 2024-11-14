✨ Project Highlights:

🔹 Custom Command Processing: Minishell supports both internal and external command execution, allowing users to perform essential shell functions directly, such as navigating directories, viewing files, and executing complex commands. I implemented a structured command parser, allowing commands to be processed seamlessly and dynamically. This feature was challenging and required in-depth understanding of command structures and efficient parsing, but it taught me a lot about system command handling and user-space interaction in Linux.

🔹 Inter-Process Communication (IPC): This feature was one of the most complex aspects of the project. By developing a robust command parser and process handler that could support redirection and piping, I enabled Minishell to facilitate multi-process communication. For instance, the shell can redirect output to files or another process, creating a powerful multitasking environment within the application. Learning to handle data exchanges between processes in real-time was immensely valuable and deepened my understanding of process control and concurrency.

🔹 Error Handling and Signal Management: Ensuring that Minishell operates smoothly required adding detailed error handling mechanisms and managing signals such as interrupts and terminations. This was crucial for preventing unexpected crashes and ensuring that the shell handled errors gracefully, even in challenging scenarios. Implementing structured error handling significantly improved the reliability of the application.

💻 Tools & Technologies Used: Throughout this project, I worked extensively with Embedded C, Linux System Calls, Process Control, Signal Handling, and Debugging with GDB.
