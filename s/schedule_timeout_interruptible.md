# Function: <code>schedule_timeout_interruptible</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
long int schedule_timeout_interruptible(long int timeout);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff818235d0)
Location: kernel/time/timer.c:1548
Inline: True
Inline callers:
  - kernel/time/timer.c:msleep_interruptible
Direct callers:
  - kernel/signal.c:do_sigtimedwait
  - kernel/workqueue.c:worker_thread
  - kernel/hung_task.c:watchdog
  - kernel/hung_task.c:watchdog
  - mm/ksm.c:ksm_scan_thread
  - mm/huge_memory.c:khugepaged
  - fs/ext4/mmp.c:kmmpd
  - fs/ext4/mmp.c:ext4_multi_mount_protect
  - fs/ext4/mmp.c:ext4_multi_mount_protect
  - fs/ecryptfs/messaging.c:ecryptfs_wait_for_response
  - drivers/xen/xenbus/xenbus_probe_frontend.c:wait_loop
  - drivers/tty/hvc/hvc_console.c:khvcd
  - drivers/char/hw_random/core.c:rng_dev_read
  - drivers/usb/early/ehci-dbgp.c:kgdbdbgp_reader_thread
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
```
**Symbols:**

```
ffffffff818235d0-ffffffff818235f0: schedule_timeout_interruptible (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
long int schedule_timeout_interruptible(long int timeout);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff810f3d43)
Location: kernel/time/timer.c:1764
Inline: True
Inline callers:
  - kernel/time/timer.c:msleep_interruptible
Direct callers:
  - kernel/workqueue.c:worker_thread
  - kernel/rcu/update.c:rcu_tasks_kthread
  - kernel/rcu/update.c:rcu_tasks_kthread
  - kernel/hung_task.c:watchdog
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/khugepaged.c:khugepaged
  - fs/ext4/mmp.c:ext4_multi_mount_protect
  - fs/ext4/mmp.c:ext4_multi_mount_protect
  - fs/ext4/mmp.c:kmmpd
  - fs/ecryptfs/messaging.c:ecryptfs_wait_for_response
  - drivers/xen/xenbus/xenbus_probe_frontend.c:wait_loop
  - drivers/tty/hvc/hvc_console.c:khvcd
  - drivers/char/hw_random/core.c:rng_dev_read
  - drivers/usb/early/ehci-dbgp.c:kgdbdbgp_reader_thread
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
```
**Symbols:**

```
ffffffff8189e220-ffffffff8189e240: schedule_timeout_interruptible (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
long int schedule_timeout_interruptible(long int timeout);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff810faef3)
Location: kernel/time/timer.c:1769
Inline: True
Inline callers:
  - kernel/time/timer.c:msleep_interruptible
Direct callers:
  - kernel/workqueue.c:worker_thread
  - kernel/rcu/update.c:rcu_tasks_kthread
  - kernel/rcu/update.c:rcu_tasks_kthread
  - kernel/hung_task.c:watchdog
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/khugepaged.c:khugepaged
  - fs/ext4/mmp.c:ext4_multi_mount_protect
  - fs/ext4/mmp.c:ext4_multi_mount_protect
  - fs/ext4/mmp.c:kmmpd
  - fs/ecryptfs/messaging.c:ecryptfs_wait_for_response
  - drivers/xen/xenbus/xenbus_probe_frontend.c:wait_loop
  - drivers/tty/hvc/hvc_console.c:khvcd
  - drivers/char/hw_random/core.c:rng_dev_read
  - drivers/usb/early/ehci-dbgp.c:kgdbdbgp_reader_thread
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
```
**Symbols:**

```
ffffffff818d3080-ffffffff818d30a1: schedule_timeout_interruptible (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
long int schedule_timeout_interruptible(long int timeout);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff810fdfa3)
Location: kernel/time/timer.c:1760
Inline: True
Inline callers:
  - kernel/time/timer.c:msleep_interruptible
Direct callers:
  - kernel/workqueue.c:worker_thread
  - kernel/rcu/update.c:rcu_tasks_kthread
  - kernel/rcu/update.c:rcu_tasks_kthread
  - kernel/hung_task.c:watchdog
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/khugepaged.c:khugepaged
  - fs/ext4/mmp.c:ext4_multi_mount_protect
  - fs/ext4/mmp.c:ext4_multi_mount_protect
  - fs/ext4/mmp.c:kmmpd
  - fs/ecryptfs/messaging.c:ecryptfs_wait_for_response
  - drivers/xen/xenbus/xenbus_probe_frontend.c:wait_loop
  - drivers/tty/hvc/hvc_console.c:khvcd
  - drivers/char/hw_random/core.c:rng_dev_read
  - drivers/usb/early/ehci-dbgp.c:kgdbdbgp_reader_thread
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
```
**Symbols:**

```
ffffffff8190a1f0-ffffffff8190a211: schedule_timeout_interruptible (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
long int schedule_timeout_interruptible(long int timeout);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff81108858)
Location: kernel/time/timer.c:1810
Inline: True
Inline callers:
  - kernel/time/timer.c:msleep_interruptible
Direct callers:
  - kernel/workqueue.c:worker_thread
  - kernel/rcu/update.c:rcu_tasks_kthread
  - kernel/rcu/update.c:rcu_tasks_kthread
  - kernel/hung_task.c:watchdog
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/khugepaged.c:khugepaged
  - fs/ext4/mmp.c:ext4_multi_mount_protect
  - fs/ext4/mmp.c:ext4_multi_mount_protect
  - fs/ext4/mmp.c:kmmpd
  - fs/ecryptfs/messaging.c:ecryptfs_wait_for_response
  - drivers/xen/xenbus/xenbus_probe_frontend.c:wait_loop
  - drivers/tty/hvc/hvc_console.c:khvcd
  - drivers/char/hw_random/core.c:rng_dev_read
  - drivers/usb/early/ehci-dbgp.c:kgdbdbgp_reader_thread
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
```
**Symbols:**

```
ffffffff81994530-ffffffff81994551: schedule_timeout_interruptible (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
long int schedule_timeout_interruptible(long int timeout);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff81113b41)
Location: kernel/time/timer.c:1821
Inline: True
Inline callers:
  - kernel/time/timer.c:msleep_interruptible
Direct callers:
  - kernel/workqueue.c:worker_thread
  - kernel/rcu/update.c:rcu_tasks_kthread
  - kernel/rcu/update.c:rcu_tasks_kthread
  - kernel/hung_task.c:watchdog
  - mm/ksm.c:ksm_scan_thread
  - mm/ksm.c:ksm_scan_thread
  - mm/khugepaged.c:khugepaged
  - fs/ext4/mmp.c:ext4_multi_mount_protect
  - fs/ext4/mmp.c:ext4_multi_mount_protect
  - fs/ext4/mmp.c:kmmpd
  - fs/ecryptfs/messaging.c:ecryptfs_wait_for_response
  - drivers/xen/xenbus/xenbus_probe_frontend.c:wait_loop
  - drivers/tty/hvc/hvc_console.c:khvcd
  - drivers/char/hw_random/core.c:rng_dev_read
  - drivers/usb/early/ehci-dbgp.c:kgdbdbgp_reader_thread
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
```
**Symbols:**

```
ffffffff819f0ac0-ffffffff819f0ae1: schedule_timeout_interruptible (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
long int schedule_timeout_interruptible(long int timeout);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff811203a1)
Location: kernel/time/timer.c:1820
Inline: True
Inline callers:
  - kernel/time/timer.c:msleep_interruptible
Direct callers:
  - kernel/workqueue.c:worker_thread
  - kernel/rcu/update.c:rcu_tasks_kthread
  - kernel/rcu/update.c:rcu_tasks_kthread
  - kernel/hung_task.c:watchdog
  - mm/khugepaged.c:khugepaged
  - fs/ext4/mmp.c:ext4_multi_mount_protect
  - fs/ext4/mmp.c:ext4_multi_mount_protect
  - fs/ext4/mmp.c:kmmpd
  - fs/ecryptfs/messaging.c:ecryptfs_wait_for_response
  - drivers/xen/xenbus/xenbus_probe_frontend.c:wait_loop
  - drivers/tty/hvc/hvc_console.c:khvcd
  - drivers/char/hw_random/core.c:rng_dev_read
  - drivers/usb/early/ehci-dbgp.c:kgdbdbgp_reader_thread
  - drivers/usb/early/xhci-dbc.c:xdbc_scrub_function
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
```
**Symbols:**

```
ffffffff81a2be40-ffffffff81a2be61: schedule_timeout_interruptible (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
long int schedule_timeout_interruptible(long int timeout);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff8112ac83)
Location: kernel/time/timer.c:1824
Inline: True
Inline callers:
  - kernel/time/timer.c:msleep_interruptible
Direct callers:
  - kernel/workqueue.c:worker_thread
  - kernel/rcu/update.c:rcu_tasks_kthread
  - kernel/rcu/update.c:rcu_tasks_kthread
  - kernel/rcu/tree.c:rcu_cpu_kthread
  - kernel/hung_task.c:watchdog
  - mm/khugepaged.c:khugepaged
  - fs/ext4/mmp.c:ext4_multi_mount_protect
  - fs/ext4/mmp.c:ext4_multi_mount_protect
  - fs/ext4/mmp.c:kmmpd
  - fs/ecryptfs/messaging.c:ecryptfs_wait_for_response
  - drivers/xen/xenbus/xenbus_probe_frontend.c:wait_loop
  - drivers/tty/hvc/hvc_console.c:khvcd
  - drivers/char/hw_random/core.c:rng_dev_read
  - drivers/usb/early/ehci-dbgp.c:kgdbdbgp_reader_thread
  - drivers/usb/early/xhci-dbc.c:xdbc_scrub_function
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
```
**Symbols:**

```
ffffffff81a9c000-ffffffff81a9c021: schedule_timeout_interruptible (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
long int schedule_timeout_interruptible(long int timeout);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff81136c23)
Location: kernel/time/timer.c:1912
Inline: True
Inline callers:
  - kernel/time/timer.c:msleep_interruptible
Direct callers:
  - kernel/workqueue.c:worker_thread
  - kernel/rcu/update.c:rcu_tasks_kthread
  - kernel/rcu/update.c:rcu_tasks_kthread
  - kernel/rcu/tree.c:rcu_cpu_kthread
  - kernel/hung_task.c:watchdog
  - mm/khugepaged.c:khugepaged
  - fs/ext4/mmp.c:ext4_multi_mount_protect
  - fs/ext4/mmp.c:ext4_multi_mount_protect
  - fs/ext4/mmp.c:kmmpd
  - fs/ecryptfs/messaging.c:ecryptfs_wait_for_response
  - drivers/xen/xenbus/xenbus_probe_frontend.c:wait_loop
  - drivers/tty/hvc/hvc_console.c:khvcd
  - drivers/char/hw_random/core.c:rng_dev_read
  - drivers/usb/early/ehci-dbgp.c:kgdbdbgp_reader_thread
  - drivers/usb/early/xhci-dbc.c:xdbc_scrub_function
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
```
**Symbols:**

```
ffffffff81ad3950-ffffffff81ad3971: schedule_timeout_interruptible (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
long int schedule_timeout_interruptible(long int timeout);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff81144a83)
Location: kernel/time/timer.c:1933
Inline: True
Inline callers:
  - kernel/time/timer.c:msleep_interruptible
Direct callers:
  - kernel/workqueue.c:maybe_create_worker
  - kernel/rcu/update.c:rcu_tasks_wait_gp
  - kernel/rcu/update.c:rcu_tasks_kthread
  - kernel/rcu/tree.c:rcu_cpu_kthread
  - kernel/hung_task.c:watchdog
  - mm/khugepaged.c:khugepaged_do_scan
  - fs/ext4/mmp.c:ext4_multi_mount_protect
  - fs/ext4/mmp.c:ext4_multi_mount_protect
  - fs/ext4/mmp.c:kmmpd
  - fs/ecryptfs/messaging.c:ecryptfs_wait_for_response
  - drivers/xen/xenbus/xenbus_probe_frontend.c:wait_loop
  - drivers/tty/hvc/hvc_console.c:khvcd
  - drivers/char/hw_random/core.c:rng_dev_read
  - drivers/usb/early/ehci-dbgp.c:kgdbdbgp_reader_thread
  - drivers/usb/early/xhci-dbc.c:xdbc_scrub_function
  - net/ethtool/ioctl.c:ethtool_phys_id
  - net/ethtool/ioctl.c:ethtool_phys_id
```
**Symbols:**

```
ffffffff81bcb8d0-ffffffff81bcb8f1: schedule_timeout_interruptible (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
long int schedule_timeout_interruptible(long int timeout);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff81141e4a)
Location: kernel/time/timer.c:1895
Inline: True
Inline callers:
  - kernel/time/timer.c:msleep_interruptible
Direct callers:
  - kernel/workqueue.c:maybe_create_worker
  - kernel/hung_task.c:watchdog
  - mm/khugepaged.c:khugepaged_do_scan
  - fs/ext4/mmp.c:ext4_multi_mount_protect
  - fs/ext4/mmp.c:ext4_multi_mount_protect
  - fs/ext4/mmp.c:kmmpd
  - fs/ecryptfs/messaging.c:ecryptfs_wait_for_response
  - drivers/xen/xenbus/xenbus_probe_frontend.c:wait_loop
  - drivers/tty/hvc/hvc_console.c:khvcd
  - drivers/char/hw_random/core.c:rng_dev_read
  - drivers/usb/early/ehci-dbgp.c:kgdbdbgp_reader_thread
  - drivers/usb/early/xhci-dbc.c:xdbc_scrub_function
  - net/ethtool/ioctl.c:ethtool_phys_id
  - net/ethtool/ioctl.c:ethtool_phys_id
```
**Symbols:**

```
ffffffff81c44750-ffffffff81c44771: schedule_timeout_interruptible (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
long int schedule_timeout_interruptible(long int timeout);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff81142c4a)
Location: kernel/time/timer.c:1912
Inline: True
Inline callers:
  - kernel/time/timer.c:msleep_interruptible
Direct callers:
  - kernel/workqueue.c:worker_thread
  - kernel/hung_task.c:watchdog
  - mm/khugepaged.c:khugepaged
  - fs/ext4/mmp.c:ext4_multi_mount_protect
  - fs/ext4/mmp.c:ext4_multi_mount_protect
  - fs/ext4/mmp.c:kmmpd
  - fs/ecryptfs/messaging.c:ecryptfs_wait_for_response
  - drivers/xen/xenbus/xenbus_probe_frontend.c:wait_loop
  - drivers/tty/hvc/hvc_console.c:khvcd
  - drivers/char/hw_random/core.c:rng_dev_read
  - drivers/usb/early/ehci-dbgp.c:kgdbdbgp_reader_thread
  - drivers/usb/early/xhci-dbc.c:xdbc_scrub_function
  - net/ethtool/ioctl.c:ethtool_phys_id
  - net/ethtool/ioctl.c:ethtool_phys_id
```
**Symbols:**

```
ffffffff81c379c0-ffffffff81c379e1: schedule_timeout_interruptible (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
long int schedule_timeout_interruptible(long int timeout);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff8116614a)
Location: kernel/time/timer.c:1898
Inline: True
Inline callers:
  - kernel/time/timer.c:msleep_interruptible
Direct callers:
  - kernel/workqueue.c:worker_thread
  - kernel/hung_task.c:watchdog
  - mm/khugepaged.c:khugepaged
  - fs/ext4/mmp.c:ext4_multi_mount_protect
  - fs/ext4/mmp.c:ext4_multi_mount_protect
  - fs/ext4/mmp.c:kmmpd
  - fs/ecryptfs/messaging.c:ecryptfs_wait_for_response
  - drivers/xen/balloon.c:balloon_wait_finish
  - drivers/xen/xenbus/xenbus_probe_frontend.c:wait_loop
  - drivers/tty/hvc/hvc_console.c:khvcd
  - drivers/char/hw_random/core.c:rng_dev_read
  - drivers/usb/early/ehci-dbgp.c:kgdbdbgp_reader_thread
  - drivers/usb/early/xhci-dbc.c:xdbc_scrub_function
  - net/ethtool/ioctl.c:ethtool_phys_id
  - net/ethtool/ioctl.c:ethtool_phys_id
```
**Symbols:**

```
ffffffff81d56280-ffffffff81d562a0: schedule_timeout_interruptible (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
long int schedule_timeout_interruptible(long int timeout);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff81199cca)
Location: kernel/time/timer.c:1952
Inline: True
Inline callers:
  - kernel/time/timer.c:msleep_interruptible
Direct callers:
  - kernel/workqueue.c:worker_thread
  - kernel/hung_task.c:watchdog
  - mm/khugepaged.c:khugepaged
  - fs/ext4/mmp.c:ext4_multi_mount_protect
  - fs/ext4/mmp.c:ext4_multi_mount_protect
  - fs/ext4/mmp.c:kmmpd
  - fs/ecryptfs/messaging.c:ecryptfs_wait_for_response
  - drivers/xen/balloon.c:balloon_wait_finish
  - drivers/xen/xenbus/xenbus_probe_frontend.c:wait_loop
  - drivers/tty/tty_port.c:tty_port_close_start
  - drivers/tty/hvc/hvc_console.c:khvcd
  - drivers/char/random.c:add_hwgenerator_randomness
  - drivers/char/hw_random/core.c:rng_dev_read
  - drivers/usb/early/ehci-dbgp.c:kgdbdbgp_reader_thread
  - drivers/usb/early/xhci-dbc.c:xdbc_scrub_function
  - net/ethtool/ioctl.c:ethtool_phys_id
  - net/ethtool/ioctl.c:ethtool_phys_id
```
**Symbols:**

```
ffffffff81f282a0-ffffffff81f282c6: schedule_timeout_interruptible (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
long int schedule_timeout_interruptible(long int timeout);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff811d836a)
Location: kernel/time/timer.c:2184
Inline: True
Inline callers:
  - kernel/time/timer.c:msleep_interruptible
Direct callers:
  - kernel/workqueue.c:worker_thread
  - kernel/hung_task.c:watchdog
  - fs/ext4/mmp.c:ext4_multi_mount_protect
  - fs/ext4/mmp.c:ext4_multi_mount_protect
  - fs/ext4/mmp.c:kmmpd
  - fs/ecryptfs/messaging.c:ecryptfs_wait_for_response
  - drivers/xen/balloon.c:balloon_wait_finish
  - drivers/xen/xenbus/xenbus_probe_frontend.c:wait_loop
  - drivers/tty/tty_port.c:tty_port_close_start
  - drivers/tty/hvc/hvc_console.c:khvcd
  - drivers/char/random.c:add_hwgenerator_randomness
  - drivers/char/hw_random/core.c:rng_dev_read
  - drivers/usb/early/ehci-dbgp.c:kgdbdbgp_reader_thread
  - drivers/usb/early/xhci-dbc.c:xdbc_scrub_function
  - net/ethtool/ioctl.c:ethtool_phys_id
  - net/ethtool/ioctl.c:ethtool_phys_id
```
**Symbols:**

```
ffffffff820d3eb0-ffffffff820d3ed6: schedule_timeout_interruptible (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
long int schedule_timeout_interruptible(long int timeout);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff811ec79a)
Location: kernel/time/timer.c:2184
Inline: True
Inline callers:
  - kernel/time/timer.c:msleep_interruptible
Direct callers:
  - kernel/workqueue.c:worker_thread
  - kernel/hung_task.c:watchdog
  - fs/ext4/mmp.c:ext4_multi_mount_protect
  - fs/ext4/mmp.c:ext4_multi_mount_protect
  - fs/ext4/mmp.c:kmmpd
  - fs/ecryptfs/messaging.c:ecryptfs_wait_for_response
  - drivers/xen/balloon.c:balloon_wait_finish
  - drivers/xen/xenbus/xenbus_probe_frontend.c:wait_loop
  - drivers/tty/tty_port.c:tty_port_close_start
  - drivers/tty/hvc/hvc_console.c:khvcd
  - drivers/char/random.c:add_hwgenerator_randomness
  - drivers/char/hw_random/core.c:rng_dev_read
  - drivers/usb/early/ehci-dbgp.c:kgdbdbgp_reader_thread
  - drivers/usb/early/xhci-dbc.c:xdbc_scrub_function
  - net/ethtool/ioctl.c:ethtool_phys_id
  - net/ethtool/ioctl.c:ethtool_phys_id
```
**Symbols:**

```
ffffffff82158130-ffffffff82158156: schedule_timeout_interruptible (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
long int schedule_timeout_interruptible(long int timeout);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff812027ba)
Location: kernel/time/timer.c:2200
Inline: True
Inline callers:
  - kernel/time/timer.c:msleep_interruptible
Direct callers:
  - kernel/workqueue.c:worker_thread
  - kernel/hung_task.c:watchdog
  - fs/ext4/mmp.c:ext4_multi_mount_protect
  - fs/ext4/mmp.c:ext4_multi_mount_protect
  - fs/ext4/mmp.c:kmmpd
  - fs/ecryptfs/messaging.c:ecryptfs_wait_for_response
  - drivers/xen/balloon.c:balloon_wait_finish
  - drivers/xen/xenbus/xenbus_probe_frontend.c:wait_loop
  - drivers/tty/tty_port.c:tty_port_close_start
  - drivers/tty/hvc/hvc_console.c:khvcd
  - drivers/char/random.c:add_hwgenerator_randomness
  - drivers/char/hw_random/core.c:rng_dev_read
  - drivers/usb/early/ehci-dbgp.c:kgdbdbgp_reader_thread
  - drivers/usb/early/xhci-dbc.c:xdbc_scrub_function
  - net/ethtool/ioctl.c:ethtool_phys_id
  - net/ethtool/ioctl.c:ethtool_phys_id
```
**Symbols:**

```
ffffffff8223afa0-ffffffff8223afc6: schedule_timeout_interruptible (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
long int schedule_timeout_interruptible(long int timeout);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffff80001019f180)
Location: kernel/time/timer.c:1912
Inline: True
Inline callers:
  - kernel/time/timer.c:msleep_interruptible
Direct callers:
  - kernel/workqueue.c:worker_thread
  - kernel/rcu/update.c:rcu_tasks_kthread
  - kernel/rcu/update.c:rcu_tasks_kthread
  - kernel/rcu/tree.c:rcu_cpu_kthread
  - kernel/hung_task.c:watchdog
  - kernel/hung_task.c:watchdog
  - mm/khugepaged.c:khugepaged
  - fs/ext4/mmp.c:ext4_multi_mount_protect
  - fs/ext4/mmp.c:ext4_multi_mount_protect
  - fs/ext4/mmp.c:kmmpd
  - fs/ecryptfs/messaging.c:ecryptfs_wait_for_response
  - drivers/xen/xenbus/xenbus_probe_frontend.c:wait_loop
  - drivers/tty/hvc/hvc_console.c:khvcd
  - drivers/char/hw_random/core.c:rng_dev_read
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
```
**Symbols:**

```
ffff800010da64b0-ffff800010da64e8: schedule_timeout_interruptible (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
long int schedule_timeout_interruptible(long int timeout);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (c03e9050)
Location: kernel/time/timer.c:1912
Inline: True
Inline callers:
  - kernel/time/timer.c:msleep_interruptible
Direct callers:
  - kernel/workqueue.c:worker_thread
  - kernel/rcu/update.c:rcu_tasks_kthread
  - kernel/rcu/update.c:rcu_tasks_kthread
  - kernel/rcu/tree.c:rcu_cpu_kthread
  - kernel/hung_task.c:watchdog
  - fs/ext4/mmp.c:ext4_multi_mount_protect
  - fs/ext4/mmp.c:ext4_multi_mount_protect
  - fs/ext4/mmp.c:kmmpd
  - fs/ecryptfs/messaging.c:ecryptfs_wait_for_response
  - drivers/tty/hvc/hvc_console.c:khvcd
  - drivers/char/hw_random/core.c:rng_dev_read
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
```
**Symbols:**

```
c0e9e240-c0e9e274: schedule_timeout_interruptible (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
long int schedule_timeout_interruptible(long int timeout);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (c0000000001ffee0)
Location: kernel/time/timer.c:1912
Inline: True
Inline callers:
  - kernel/time/timer.c:msleep_interruptible
Direct callers:
  - kernel/workqueue.c:worker_thread
  - kernel/rcu/update.c:rcu_tasks_kthread
  - kernel/rcu/update.c:rcu_tasks_kthread
  - kernel/rcu/tree.c:rcu_cpu_kthread
  - kernel/hung_task.c:watchdog
  - mm/khugepaged.c:khugepaged
  - fs/ext4/mmp.c:ext4_multi_mount_protect
  - fs/ext4/mmp.c:ext4_multi_mount_protect
  - fs/ext4/mmp.c:kmmpd
  - fs/ecryptfs/messaging.c:ecryptfs_wait_for_response
  - drivers/tty/hvc/hvc_console.c:khvcd
  - drivers/char/hw_random/core.c:rng_dev_read
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
```
**Symbols:**

```
c000000000ee8cd0-c000000000ee8cf0: schedule_timeout_interruptible (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
long int schedule_timeout_interruptible(long int timeout);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffe00012db1a)
Location: kernel/time/timer.c:1912
Inline: True
Inline callers:
  - kernel/time/timer.c:msleep_interruptible
Direct callers:
  - kernel/workqueue.c:worker_thread
  - kernel/rcu/update.c:rcu_tasks_kthread
  - kernel/rcu/update.c:rcu_tasks_kthread
  - kernel/rcu/tree.c:rcu_cpu_kthread
  - kernel/hung_task.c:watchdog
  - fs/ext4/mmp.c:ext4_multi_mount_protect
  - fs/ext4/mmp.c:ext4_multi_mount_protect
  - fs/ext4/mmp.c:kmmpd
  - fs/ecryptfs/messaging.c:ecryptfs_wait_for_response
  - drivers/tty/hvc/hvc_console.c:khvcd
  - drivers/char/hw_random/core.c:rng_dev_read
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
```
**Symbols:**

```
ffffffe0008c8920-ffffffe0008c8950: schedule_timeout_interruptible (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
long int schedule_timeout_interruptible(long int timeout);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff8112f3d3)
Location: kernel/time/timer.c:1912
Inline: True
Inline callers:
  - kernel/time/timer.c:msleep_interruptible
Direct callers:
  - kernel/workqueue.c:worker_thread
  - kernel/rcu/update.c:rcu_tasks_kthread
  - kernel/rcu/update.c:rcu_tasks_kthread
  - kernel/rcu/tree.c:rcu_cpu_kthread
  - kernel/hung_task.c:watchdog
  - mm/khugepaged.c:khugepaged
  - fs/ext4/mmp.c:ext4_multi_mount_protect
  - fs/ext4/mmp.c:ext4_multi_mount_protect
  - fs/ext4/mmp.c:kmmpd
  - fs/ecryptfs/messaging.c:ecryptfs_wait_for_response
  - drivers/xen/xenbus/xenbus_probe_frontend.c:wait_loop
  - drivers/tty/hvc/hvc_console.c:khvcd
  - drivers/char/hw_random/core.c:rng_dev_read
  - drivers/usb/early/ehci-dbgp.c:kgdbdbgp_reader_thread
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
```
**Symbols:**

```
ffffffff81a727c0-ffffffff81a727e1: schedule_timeout_interruptible (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
long int schedule_timeout_interruptible(long int timeout);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff81121e53)
Location: kernel/time/timer.c:1912
Inline: True
Inline callers:
  - kernel/time/timer.c:msleep_interruptible
Direct callers:
  - kernel/workqueue.c:worker_thread
  - kernel/rcu/update.c:rcu_tasks_kthread
  - kernel/rcu/update.c:rcu_tasks_kthread
  - kernel/rcu/tree.c:nocb_gp_wait
  - kernel/rcu/tree.c:rcu_cpu_kthread
  - kernel/hung_task.c:watchdog
  - mm/khugepaged.c:khugepaged
  - fs/ext4/mmp.c:ext4_multi_mount_protect
  - fs/ext4/mmp.c:ext4_multi_mount_protect
  - fs/ext4/mmp.c:kmmpd
  - fs/ecryptfs/messaging.c:ecryptfs_wait_for_response
  - drivers/tty/hvc/hvc_console.c:khvcd
  - drivers/char/hw_random/core.c:rng_dev_read
  - drivers/usb/early/ehci-dbgp.c:kgdbdbgp_reader_thread
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
```
**Symbols:**

```
ffffffff81a2eb90-ffffffff81a2ebb1: schedule_timeout_interruptible (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
long int schedule_timeout_interruptible(long int timeout);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff8112d0f3)
Location: kernel/time/timer.c:1912
Inline: True
Inline callers:
  - kernel/time/timer.c:msleep_interruptible
Direct callers:
  - kernel/workqueue.c:worker_thread
  - kernel/rcu/update.c:rcu_tasks_kthread
  - kernel/rcu/update.c:rcu_tasks_kthread
  - kernel/rcu/tree.c:rcu_cpu_kthread
  - kernel/hung_task.c:watchdog
  - mm/khugepaged.c:khugepaged
  - fs/ext4/mmp.c:ext4_multi_mount_protect
  - fs/ext4/mmp.c:ext4_multi_mount_protect
  - fs/ext4/mmp.c:kmmpd
  - fs/ecryptfs/messaging.c:ecryptfs_wait_for_response
  - drivers/xen/xenbus/xenbus_probe_frontend.c:wait_loop
  - drivers/tty/hvc/hvc_console.c:khvcd
  - drivers/char/hw_random/core.c:rng_dev_read
  - drivers/usb/early/ehci-dbgp.c:kgdbdbgp_reader_thread
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
```
**Symbols:**

```
ffffffff81adebd0-ffffffff81adebf1: schedule_timeout_interruptible (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
long int schedule_timeout_interruptible(long int timeout);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/time/timer.c (ffffffff81138e83)
Location: kernel/time/timer.c:1912
Inline: True
Inline callers:
  - kernel/time/timer.c:msleep_interruptible
Direct callers:
  - kernel/workqueue.c:worker_thread
  - kernel/rcu/update.c:rcu_tasks_kthread
  - kernel/rcu/update.c:rcu_tasks_kthread
  - kernel/rcu/tree.c:rcu_cpu_kthread
  - kernel/hung_task.c:watchdog
  - mm/khugepaged.c:khugepaged
  - fs/ext4/mmp.c:ext4_multi_mount_protect
  - fs/ext4/mmp.c:ext4_multi_mount_protect
  - fs/ext4/mmp.c:kmmpd
  - fs/ecryptfs/messaging.c:ecryptfs_wait_for_response
  - drivers/xen/xenbus/xenbus_probe_frontend.c:wait_loop
  - drivers/tty/hvc/hvc_console.c:khvcd
  - drivers/char/hw_random/core.c:rng_dev_read
  - drivers/usb/early/ehci-dbgp.c:kgdbdbgp_reader_thread
  - drivers/usb/early/xhci-dbc.c:xdbc_scrub_function
  - net/core/ethtool.c:dev_ethtool
  - net/core/ethtool.c:dev_ethtool
```
**Symbols:**

```
ffffffff81aeb060-ffffffff81aeb081: schedule_timeout_interruptible (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
<li>
No changes between <code>5.15</code> and <code>5.19</code> ✅
</li>
<li>
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
