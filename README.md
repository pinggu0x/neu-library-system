# NEU Library Management System

This is the local HTML, CSS, and JavaScript version of our New Era University
library interface. It follows the four assignment modules:

1. **Books Entry:** record books received by the library.
2. **User Entry:** record student details.
3. **Issue Books:** issue an available book and enter the issue and due dates.
4. **Return Books:** enter the return date, calculate a delayed fine, and restore availability.

## Run locally

From this folder, start any simple static file server:

```bash
python3 -m http.server 4173
```

Open [http://localhost:4173](http://localhost:4173). The interface uses local
browser-session data and does not require a database, build tool, or hosting
service.
