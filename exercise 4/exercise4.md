1. Ps (process status): This command provides a snapshot of the currently running
processes.
• Ps aux: This is a very common and useful combination.
• A: Shows processes for all users.
• U: Displays detailed information (user, CPU usage, memory usage, etc.).
• X: Includes processes not associated with a terminal.
• Ps -ef: Another popular option for a full-format listing.
• Ps -axjf: Displays processes in a hierarchical (tree) view, showing parent-child
relationships.
2. Top: This command provides a real-time, dynamic view of running processes, sorted
by CPU usage by default. It’s interactive, so you can press keys to sort by different columns
(e.g., M for memory, P for CPU). Press q to exit.
3. Htop: An enhanced and more user-friendly version of top. It offers a more interactive
interface, colored output, and easier navigation/filtering. You might need to install it first (e.g.,
sudo apt install htop on Ubuntu/Debian, brew install htop on macOS with Homebrew).
4. Atop: Another advanced process monitor that provides real-time information and
historical logging. It’s also often not installed by default.
5. Pstree: Displays processes in a tree format, showing parent-child relationships.
Useful for understanding process hierarchies.
In my opinion, these processes are important to understand the system’s behaviour,
performance monitoring, troubleshooting, debugging, security, etc. Without them, we
won’t exactly know what the system is actually doing, so they are good for effective
system administration.