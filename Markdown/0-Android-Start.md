## 系统启动用到的文件

```
.
├── frameworks
│   └── base
│       ├── cmds
│       │   └── app_process
│       │       └── app_main.cpp
│       ├── core
│       │   ├── java
│       │   │   ├── android
│       │   │   │   └── app
│       │   │   │       ├── ActivityThread.java
│       │   │   │       ├── ContextImpl.java
│       │   │   │       └── LoadedApk.java
│       │   │   └── com
│       │   │       └── android
│       │   │           ├── internal
│       │   │           │   └── os
│       │   │           │       ├── RuntimeInit.java
│       │   │           │       ├── ZygoteInit.java
│       │   │           │       └── Zygote.java
│       │   │           └── server
│       │   │               └── LocalServices.java
│       │   └── jni
│       │       ├── AndroidRuntime.cpp
│       │       └── com_android_internal_os_Zygote.cpp
│       └── services
│           ├── core
│           │   └── java
│           │       └── com
│           │           └── android
│           │               └── server
│           │                   ├── am
│           │                   │   └── ActivityManagerService.java
│           │                   ├── pm
│           │                   │   └── Installer.java
│           │                   ├── ServiceThread.java
│           │                   └── SystemServiceManager.java
│           └── java
│               └── com
│                   └── android
│                       └── server
│                           └── SystemServer.java
├── Markdown
│   └── 0-Android-Start.md
└── system
    └── core
        ├── init
        │   ├── init.cpp
        │   ├── init.h
        │   ├── init_parser.cpp
        │   ├── init_parser.h
        │   ├── property_service.cpp
        │   ├── property_service.h
        │   ├── signal_handler.cpp
        │   └── signal_handler.h
        └── libutils
            └── Threads.cpp

31 directories, 25 files
```
