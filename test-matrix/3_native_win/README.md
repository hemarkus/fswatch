# 3: Host OS (Windows) + Native app (Windows)

| Host OS | App run as<br/>native app | App run as<br/>Linux Container |  App run as<br/>Windows Container | ‖<br/>‖ | App run in<br/>K8s (Linux Container) |
|---------|------------|-----------------|-------------------|----|-----------------------|
| Linux   | 1          | 4               | N/A               | ‖ | 8             |
| Mac     | 2          | 5               | N/A               |
| Windows | **★ 3 ★**  | 6               | 7                 |


Type `run.bat` to track the changes of this directory.

```
.
├── run.bat
└── site
    ├── css
    │   └── main.css
    ├── index.html
    └── js
        └── main.js

3 directories, 4 files
```