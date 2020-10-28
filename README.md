# ioctl_Windows
Windows wdk driver: ioctl demo

For driver:
D:\workspace_VisualStudio\ioctl_Windows\x64\Debug>sc create io1 binpath=D:\workspace_VisualStudio\ioctl_Windows\x64\Debug\ioctl_Windows.sys type=kernel

[SC] CreateService SUCCESS

D:\workspace_VisualStudio\ioctl_Windows\x64\Debug>sc start io1

SERVICE_NAME: io1
        TYPE               : 1  KERNEL_DRIVER
        STATE              : 4  RUNNING
                                (STOPPABLE, NOT_PAUSABLE, IGNORES_SHUTDOWN)
        WIN32_EXIT_CODE    : 0  (0x0)
        SERVICE_EXIT_CODE  : 0  (0x0)
        CHECKPOINT         : 0x0
        WAIT_HINT          : 0x0
        PID                : 0
        FLAGS              :


For App:
D:\workspace_VisualStudio\ioctl_Windows\x64\Debug>app

D:\workspace_VisualStudio\ioctl_Windows\x64\Debug>



And use Dbgview to check the kernel log.
