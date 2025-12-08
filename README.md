# SRC-D_MAV
A high-fidelity, self-contained, offline-first HTML/JS dashboard for tactical project and incident management, featuring namespace-isolated dual instances (Shared &amp; MΛVΞRICK).


​SRC-D Cyber-Conspectus Matrix (MΛVΞRICK Edition)

​⚡ SRC-D Cyber-Conspectus Matrix (MΛVΞRICK Edition)
​This is a single-file, inline HTML, JavaScript, and CSS application designed for efficient, compartmentalized data management. It serves as a portable and resilient cyber-console interface for tracking Projects, Incidents, and Ephemeral Context (Scratchpad).

​The application is built on the core SRC-D philosophy: Survivalism, Resilience, Cooperation, and Development—a framework focused on optimizing planning and enjoying the journey.

​🔑 Key Features

​Offline-First & Self-Contained: The entire application resides in one HTML file, requiring no server, external libraries (only Tailwind CDN), or initial configuration.
​Dual-Instance Isolation (MΛVΞRICK Namespace): This specific version operates on an independent data namespace (_MVRK_) within your browser's LocalStorage and IndexedDB. It runs perfectly alongside the standard SRC-D2_WEYU version without data conflict.

​Robust Data Persistence: Uses LocalStorage for core entries (Projects/Incidents) and IndexedDB for large file attachments (Blobs, Media, PDFs), ensuring data persistence across sessions.

​Context Management (Scratchpad): Features a multi-tab Scratchpad (Main, Snippet, VIP_Context) for saving critical, ephemeral notes with autosave functionality.
​Advanced Incident Sorting: Incidents are intelligently sorted based on chronological dates or extracted numerical sequences (e.g., Version numbers V1 > V10) found in the attachment labels.

​Data Portability (.srcd Format): Allows for full-stack export and import (.srcd files) for easy backup, migration, or merging of data across different instances.

​🛠️ Technology Stack

​Frontend: Inline HTML, CSS, JavaScript (Vanilla ES6+)
​Styling: Tailwind CSS (CDN) for a rapid, cyber-console aesthetic.

​Persistence: HTML5 LocalStorage, SessionStorage, and IndexedDB.

​💡 Philosophy

​Developed by MΛVΞRICK to embody the principles of personal optimization and resilience, the application is intentionally designed to be fully functional even in low-connectivity environments. The namespace isolation ensures that while contributing to the shared domain, personal development, testing, and private context remains secure and separate.
