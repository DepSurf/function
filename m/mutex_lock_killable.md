# Function: <code>mutex_lock_killable</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int mutex_lock_killable(struct mutex *lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/mutex.c (ffffffff81821dc0)
Location: kernel/locking/mutex.c:801
Inline: False
Direct callers:
  - kernel/fork.c:mm_access
  - kernel/kcmp.c:SyS_kcmp
  - kernel/kcmp.c:SyS_kcmp
  - kernel/kcmp.c:SyS_kcmp
  - fs/readdir.c:iterate_dir
  - fs/proc/base.c:do_io_accounting
  - drivers/pci/access.c:pci_vpd_pci22_write
  - drivers/pci/access.c:pci_vpd_pci22_read
```
**Symbols:**

```
ffffffff81821dc0-ffffffff81821dfd: mutex_lock_killable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int mutex_lock_killable(struct mutex *lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/mutex.c (ffffffff8189c220)
Location: kernel/locking/mutex.c:805
Inline: False
Direct callers:
  - kernel/fork.c:mm_access
  - kernel/kcmp.c:SyS_kcmp
  - kernel/kcmp.c:SyS_kcmp
  - kernel/kcmp.c:SyS_kcmp
  - mm/oom_kill.c:oom_killer_disable
  - fs/proc/base.c:do_io_accounting
  - drivers/pci/access.c:pci_vpd_write
  - drivers/pci/access.c:pci_vpd_read
```
**Symbols:**

```
ffffffff8189c220-ffffffff8189c25d: mutex_lock_killable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int mutex_lock_killable(struct mutex *lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/mutex.c (ffffffff818d0bf0)
Location: kernel/locking/mutex.c:942
Inline: False
Direct callers:
  - kernel/fork.c:mm_access
  - kernel/kcmp.c:SyS_kcmp
  - kernel/kcmp.c:SyS_kcmp
  - kernel/kcmp.c:SyS_kcmp
  - mm/oom_kill.c:oom_killer_disable
  - fs/proc/base.c:do_io_accounting
  - drivers/pci/access.c:pci_vpd_write
  - drivers/pci/access.c:pci_vpd_read
  - net/core/net_namespace.c:copy_net_ns
  - net/core/net_namespace.c:copy_net_ns
```
**Symbols:**

```
ffffffff818d0bf0-ffffffff818d0c22: mutex_lock_killable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int mutex_lock_killable(struct mutex *lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/mutex.c (ffffffff81908160)
Location: kernel/locking/mutex.c:1107
Inline: False
Direct callers:
  - kernel/fork.c:mm_access
  - kernel/kcmp.c:SyS_kcmp
  - kernel/kcmp.c:SyS_kcmp
  - kernel/kcmp.c:SyS_kcmp
  - mm/oom_kill.c:oom_killer_disable
  - fs/proc/base.c:do_io_accounting
  - drivers/pci/access.c:pci_vpd_write
  - drivers/pci/access.c:pci_vpd_read
  - net/core/net_namespace.c:copy_net_ns
  - net/core/net_namespace.c:copy_net_ns
```
**Symbols:**

```
ffffffff81908160-ffffffff8190819a: mutex_lock_killable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int mutex_lock_killable(struct mutex *lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/mutex.c (ffffffff81992240)
Location: kernel/locking/mutex.c:1107
Inline: False
Direct callers:
  - kernel/fork.c:mm_access
  - kernel/kcmp.c:SyS_kcmp
  - kernel/kcmp.c:SyS_kcmp
  - kernel/kcmp.c:SyS_kcmp
  - mm/oom_kill.c:oom_killer_disable
  - fs/proc/base.c:do_io_accounting
  - drivers/pci/access.c:pci_vpd_write
  - drivers/pci/access.c:pci_vpd_read
  - net/core/net_namespace.c:copy_net_ns
  - net/core/net_namespace.c:copy_net_ns
```
**Symbols:**

```
ffffffff81992240-ffffffff8199227a: mutex_lock_killable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int mutex_lock_killable(struct mutex *lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/mutex.c (ffffffff819eeff0)
Location: kernel/locking/mutex.c:1121
Inline: False
Direct callers:
  - kernel/fork.c:mm_access
  - kernel/kcmp.c:__ia32_sys_kcmp
  - kernel/kcmp.c:__ia32_sys_kcmp
  - kernel/kcmp.c:__ia32_sys_kcmp
  - kernel/kcmp.c:__ia32_sys_kcmp
  - kernel/kcmp.c:__x64_sys_kcmp
  - kernel/kcmp.c:__x64_sys_kcmp
  - kernel/kcmp.c:__x64_sys_kcmp
  - kernel/kcmp.c:__x64_sys_kcmp
  - mm/oom_kill.c:oom_killer_disable
  - mm/percpu.c:pcpu_alloc
  - fs/proc/base.c:do_io_accounting
  - drivers/pci/vpd.c:pci_vpd_write
  - drivers/pci/vpd.c:pci_vpd_read
  - drivers/block/loop.c:loop_control_ioctl
  - drivers/block/loop.c:lo_compat_ioctl
  - drivers/block/loop.c:lo_compat_ioctl
  - drivers/block/loop.c:lo_ioctl
  - net/core/rtnetlink.c:rtnl_lock_killable
```
**Symbols:**

```
ffffffff819eeff0-ffffffff819ef024: mutex_lock_killable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int mutex_lock_killable(struct mutex *lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/mutex.c (ffffffff81a2a330)
Location: kernel/locking/mutex.c:1299
Inline: False
Direct callers:
  - kernel/fork.c:mm_access
  - kernel/kcmp.c:__ia32_sys_kcmp
  - kernel/kcmp.c:__ia32_sys_kcmp
  - kernel/kcmp.c:__ia32_sys_kcmp
  - kernel/kcmp.c:__ia32_sys_kcmp
  - kernel/kcmp.c:__x64_sys_kcmp
  - kernel/kcmp.c:__x64_sys_kcmp
  - kernel/kcmp.c:__x64_sys_kcmp
  - kernel/kcmp.c:__x64_sys_kcmp
  - mm/oom_kill.c:oom_killer_disable
  - mm/percpu.c:pcpu_alloc
  - fs/proc/base.c:do_io_accounting
  - drivers/pci/vpd.c:pci_vpd_write
  - drivers/pci/vpd.c:pci_vpd_read
  - drivers/block/loop.c:lo_ioctl
  - drivers/block/loop.c:lo_ioctl
  - drivers/block/loop.c:lo_ioctl
  - drivers/block/loop.c:lo_ioctl
  - drivers/block/loop.c:lo_ioctl
  - drivers/block/loop.c:loop_set_status
  - net/core/rtnetlink.c:rtnl_lock_killable
```
**Symbols:**

```
ffffffff81a2a330-ffffffff81a2a364: mutex_lock_killable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int mutex_lock_killable(struct mutex *lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/mutex.c (ffffffff81a9aac0)
Location: kernel/locking/mutex.c:1304
Inline: False
Direct callers:
  - kernel/fork.c:mm_access
  - kernel/kcmp.c:__do_sys_kcmp
  - kernel/kcmp.c:__do_sys_kcmp
  - kernel/kcmp.c:__do_sys_kcmp
  - kernel/kcmp.c:__do_sys_kcmp
  - kernel/seccomp.c:seccomp_set_mode_filter
  - mm/oom_kill.c:oom_killer_disable
  - mm/percpu.c:pcpu_alloc
  - mm/memcontrol.c:mem_cgroup_out_of_memory
  - fs/proc/base.c:do_io_accounting
  - drivers/pci/vpd.c:pci_vpd_write
  - drivers/pci/vpd.c:pci_vpd_read
  - drivers/block/loop.c:lo_ioctl
  - drivers/block/loop.c:lo_ioctl
  - drivers/block/loop.c:lo_ioctl
  - drivers/block/loop.c:lo_ioctl
  - drivers/block/loop.c:loop_set_status
  - drivers/block/loop.c:loop_set_fd
  - drivers/block/loop.c:loop_set_fd
  - net/core/rtnetlink.c:rtnl_lock_killable
```
**Symbols:**

```
ffffffff81a9aac0-ffffffff81a9aaf8: mutex_lock_killable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int mutex_lock_killable(struct mutex *lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/mutex.c (ffffffff81ad2410)
Location: kernel/locking/mutex.c:1330
Inline: False
Direct callers:
  - kernel/fork.c:mm_access
  - kernel/kcmp.c:__do_sys_kcmp
  - kernel/kcmp.c:__do_sys_kcmp
  - kernel/kcmp.c:__do_sys_kcmp
  - kernel/kcmp.c:__do_sys_kcmp
  - kernel/seccomp.c:seccomp_set_mode_filter
  - mm/oom_kill.c:oom_killer_disable
  - mm/percpu.c:pcpu_alloc
  - mm/memcontrol.c:mem_cgroup_out_of_memory
  - fs/proc/base.c:do_io_accounting
  - drivers/pci/vpd.c:pci_vpd_write
  - drivers/pci/vpd.c:pci_vpd_read
  - drivers/block/loop.c:lo_ioctl
  - drivers/block/loop.c:lo_ioctl
  - drivers/block/loop.c:lo_ioctl
  - drivers/block/loop.c:lo_ioctl
  - drivers/block/loop.c:loop_set_status
  - drivers/block/loop.c:loop_set_fd
  - drivers/block/loop.c:loop_set_fd
  - net/core/rtnetlink.c:rtnl_lock_killable
```
**Symbols:**

```
ffffffff81ad2410-ffffffff81ad2448: mutex_lock_killable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int mutex_lock_killable(struct mutex *lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/mutex.c (ffffffff81bca440)
Location: kernel/locking/mutex.c:1330
Inline: False
Direct callers:
  - kernel/fork.c:mm_access
  - kernel/pid.c:pidfd_getfd
  - kernel/kcmp.c:__do_sys_kcmp
  - kernel/kcmp.c:__do_sys_kcmp
  - kernel/kcmp.c:__do_sys_kcmp
  - kernel/kcmp.c:__do_sys_kcmp
  - kernel/seccomp.c:seccomp_set_mode_filter
  - mm/oom_kill.c:oom_killer_disable
  - mm/percpu.c:pcpu_alloc
  - mm/memcontrol.c:mem_cgroup_out_of_memory
  - fs/exec.c:exec_mmap
  - fs/exec.c:exec_mmap
  - fs/proc/base.c:do_io_accounting
  - fs/proc/base.c:proc_pid_stack
  - drivers/pci/vpd.c:pci_vpd_write
  - drivers/pci/vpd.c:pci_vpd_read
  - drivers/block/loop.c:loop_get_status_compat
  - drivers/block/loop.c:lo_ioctl
  - drivers/block/loop.c:lo_ioctl
  - drivers/block/loop.c:lo_simple_ioctl
  - drivers/block/loop.c:loop_get_status_old
  - drivers/block/loop.c:loop_set_status
  - drivers/block/loop.c:loop_configure
  - drivers/block/loop.c:loop_configure
  - drivers/block/loop.c:loop_change_fd
  - net/core/rtnetlink.c:rtnl_lock_killable
```
**Symbols:**

```
ffffffff81bca440-ffffffff81bca47c: mutex_lock_killable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int mutex_lock_killable(struct mutex *lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/mutex.c (ffffffff81c432a0)
Location: kernel/locking/mutex.c:1333
Inline: False
Direct callers:
  - kernel/seccomp.c:seccomp_set_mode_filter
  - mm/oom_kill.c:oom_killer_disable
  - mm/percpu.c:pcpu_alloc
  - mm/memcontrol.c:mem_cgroup_out_of_memory
  - drivers/pci/vpd.c:pci_vpd_write
  - drivers/pci/vpd.c:pci_vpd_read
  - drivers/block/loop.c:loop_get_status_compat
  - drivers/block/loop.c:lo_ioctl
  - drivers/block/loop.c:lo_ioctl
  - drivers/block/loop.c:lo_simple_ioctl
  - drivers/block/loop.c:loop_get_status_old
  - drivers/block/loop.c:loop_set_status
  - drivers/block/loop.c:loop_configure
  - drivers/block/loop.c:loop_configure
  - drivers/block/loop.c:loop_change_fd
  - net/core/rtnetlink.c:rtnl_lock_killable
```
**Symbols:**

```
ffffffff81c432a0-ffffffff81c432dc: mutex_lock_killable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int mutex_lock_killable(struct mutex *lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/mutex.c (ffffffff81c34960)
Location: kernel/locking/mutex.c:1331
Inline: False
Direct callers:
  - kernel/seccomp.c:seccomp_set_mode_filter
  - mm/oom_kill.c:oom_killer_disable
  - mm/percpu.c:pcpu_alloc
  - mm/memcontrol.c:mem_cgroup_out_of_memory
  - drivers/pci/vpd.c:pci_vpd_write
  - drivers/pci/vpd.c:pci_vpd_read
  - drivers/block/loop.c:lo_open
  - drivers/block/loop.c:lo_ioctl
  - drivers/block/loop.c:lo_simple_ioctl
  - drivers/block/loop.c:loop_get_status
  - drivers/block/loop.c:loop_set_status
  - drivers/block/loop.c:loop_configure
  - drivers/block/loop.c:loop_configure
  - drivers/block/loop.c:loop_configure
  - drivers/block/loop.c:loop_change_fd
  - drivers/block/loop.c:loop_change_fd
  - drivers/block/loop.c:loop_change_fd
  - net/core/rtnetlink.c:rtnl_lock_killable
```
**Symbols:**

```
ffffffff81c34960-ffffffff81c3499c: mutex_lock_killable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int mutex_lock_killable(struct mutex *lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/mutex.c (ffffffff81d531f0)
Location: kernel/locking/mutex.c:945
Inline: False
Direct callers:
  - kernel/seccomp.c:seccomp_set_mode_filter
  - mm/oom_kill.c:oom_killer_disable
  - mm/percpu.c:pcpu_alloc
  - mm/memcontrol.c:mem_cgroup_out_of_memory
  - drivers/pci/vpd.c:pci_vpd_write
  - drivers/pci/vpd.c:pci_vpd_read
  - drivers/block/loop.c:loop_control_ioctl
  - drivers/block/loop.c:loop_control_ioctl
  - drivers/block/loop.c:loop_control_ioctl
  - drivers/block/loop.c:loop_add
  - drivers/block/loop.c:lo_open
  - drivers/block/loop.c:lo_ioctl
  - drivers/block/loop.c:lo_simple_ioctl
  - drivers/block/loop.c:loop_get_status
  - drivers/block/loop.c:loop_set_status
  - drivers/block/loop.c:loop_configure
  - drivers/block/loop.c:loop_configure
  - drivers/block/loop.c:loop_configure
  - drivers/block/loop.c:loop_change_fd
  - drivers/block/loop.c:loop_change_fd
  - drivers/block/loop.c:loop_change_fd
  - net/core/rtnetlink.c:rtnl_lock_killable
```
**Symbols:**

```
ffffffff81d531f0-ffffffff81d5322c: mutex_lock_killable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int mutex_lock_killable(struct mutex *lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/mutex.c (ffffffff81f24ac0)
Location: kernel/locking/mutex.c:1001
Inline: False
Direct callers:
  - kernel/seccomp.c:seccomp_set_mode_filter
  - mm/oom_kill.c:oom_killer_disable
  - mm/percpu.c:pcpu_alloc
  - mm/memcontrol.c:mem_cgroup_out_of_memory
  - drivers/pci/vpd.c:pci_vpd_write
  - drivers/pci/vpd.c:pci_vpd_read
  - drivers/pci/vpd.c:pci_vpd_read
  - drivers/block/loop.c:loop_control_ioctl
  - drivers/block/loop.c:loop_control_ioctl
  - drivers/block/loop.c:loop_control_ioctl
  - drivers/block/loop.c:loop_add
  - drivers/block/loop.c:lo_ioctl
  - drivers/block/loop.c:lo_ioctl
  - drivers/block/loop.c:lo_simple_ioctl
  - drivers/block/loop.c:loop_get_status
  - drivers/block/loop.c:loop_set_status
  - drivers/block/loop.c:loop_configure
  - drivers/block/loop.c:loop_configure
  - drivers/block/loop.c:loop_configure
  - drivers/block/loop.c:loop_change_fd
  - drivers/block/loop.c:loop_change_fd
  - drivers/block/loop.c:loop_change_fd
  - net/core/rtnetlink.c:rtnl_lock_killable
```
**Symbols:**

```
ffffffff81f24ac0-ffffffff81f24b0a: mutex_lock_killable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int mutex_lock_killable(struct mutex *lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/mutex.c (ffffffff820d0010)
Location: kernel/locking/mutex.c:1001
Inline: False
Direct callers:
  - kernel/seccomp.c:seccomp_set_mode_filter
  - mm/oom_kill.c:oom_killer_disable
  - mm/percpu.c:pcpu_alloc
  - mm/memcontrol.c:mem_cgroup_out_of_memory
  - drivers/pci/vpd.c:pci_vpd_write
  - drivers/pci/vpd.c:pci_vpd_read
  - drivers/pci/vpd.c:pci_vpd_read
  - drivers/block/loop.c:loop_control_ioctl
  - drivers/block/loop.c:loop_control_ioctl
  - drivers/block/loop.c:loop_control_ioctl
  - drivers/block/loop.c:loop_add
  - drivers/block/loop.c:lo_ioctl
  - drivers/block/loop.c:lo_ioctl
  - drivers/block/loop.c:lo_simple_ioctl
  - drivers/block/loop.c:loop_get_status
  - drivers/block/loop.c:loop_set_status
  - drivers/block/loop.c:loop_configure
  - drivers/block/loop.c:loop_configure
  - drivers/block/loop.c:loop_configure
  - drivers/block/loop.c:loop_change_fd
  - drivers/block/loop.c:loop_change_fd
  - drivers/block/loop.c:loop_change_fd
  - net/core/rtnetlink.c:rtnl_lock_killable
```
**Symbols:**

```
ffffffff820d0010-ffffffff820d005a: mutex_lock_killable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int mutex_lock_killable(struct mutex *lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/mutex.c (ffffffff821537d0)
Location: kernel/locking/mutex.c:1001
Inline: False
Direct callers:
  - kernel/seccomp.c:seccomp_set_mode_filter
  - mm/oom_kill.c:oom_killer_disable
  - mm/percpu.c:pcpu_alloc
  - mm/memcontrol.c:mem_cgroup_out_of_memory
  - drivers/pci/vpd.c:pci_vpd_write
  - drivers/pci/vpd.c:pci_vpd_read
  - drivers/pci/vpd.c:pci_vpd_read
  - drivers/block/loop.c:loop_control_ioctl
  - drivers/block/loop.c:loop_control_ioctl
  - drivers/block/loop.c:loop_control_ioctl
  - drivers/block/loop.c:loop_add
  - drivers/block/loop.c:lo_ioctl
  - drivers/block/loop.c:lo_ioctl
  - drivers/block/loop.c:lo_simple_ioctl
  - drivers/block/loop.c:loop_get_status
  - drivers/block/loop.c:loop_set_status
  - drivers/block/loop.c:loop_configure
  - drivers/block/loop.c:loop_configure
  - drivers/block/loop.c:loop_configure
  - drivers/block/loop.c:loop_configure
  - drivers/block/loop.c:loop_configure
  - drivers/block/loop.c:loop_change_fd
  - drivers/block/loop.c:loop_change_fd
  - drivers/block/loop.c:loop_change_fd
  - net/core/rtnetlink.c:rtnl_lock_killable
```
**Symbols:**

```
ffffffff821537d0-ffffffff8215381a: mutex_lock_killable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int mutex_lock_killable(struct mutex *lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/mutex.c (ffffffff82236610)
Location: kernel/locking/mutex.c:1006
Inline: False
Direct callers:
  - kernel/seccomp.c:seccomp_set_mode_filter
  - mm/oom_kill.c:oom_killer_disable
  - mm/percpu.c:pcpu_alloc
  - mm/memcontrol.c:mem_cgroup_out_of_memory
  - drivers/pci/vpd.c:pci_vpd_write
  - drivers/pci/vpd.c:pci_vpd_read
  - drivers/pci/vpd.c:pci_vpd_read
  - drivers/block/loop.c:loop_control_ioctl
  - drivers/block/loop.c:loop_control_ioctl
  - drivers/block/loop.c:loop_control_ioctl
  - drivers/block/loop.c:loop_add
  - drivers/block/loop.c:lo_ioctl
  - drivers/block/loop.c:lo_ioctl
  - drivers/block/loop.c:lo_simple_ioctl
  - drivers/block/loop.c:loop_get_status
  - drivers/block/loop.c:loop_set_status
  - drivers/block/loop.c:loop_configure
  - drivers/block/loop.c:loop_configure
  - drivers/block/loop.c:loop_configure
  - drivers/block/loop.c:loop_configure
  - drivers/block/loop.c:loop_configure
  - drivers/block/loop.c:loop_change_fd
  - drivers/block/loop.c:loop_change_fd
  - drivers/block/loop.c:loop_change_fd
  - net/core/rtnetlink.c:rtnl_lock_killable
```
**Symbols:**

```
ffffffff82236610-ffffffff8223665a: mutex_lock_killable (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
int mutex_lock_killable(struct mutex *lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/mutex.c (ffff800010da3788)
Location: kernel/locking/mutex.c:1330
Inline: False
Direct callers:
  - virt/kvm/kvm_main.c:kvm_vcpu_ioctl
  - kernel/fork.c:mm_access
  - kernel/kcmp.c:__arm64_sys_kcmp
  - kernel/kcmp.c:__arm64_sys_kcmp
  - kernel/kcmp.c:__arm64_sys_kcmp
  - kernel/kcmp.c:__arm64_sys_kcmp
  - kernel/seccomp.c:seccomp_set_mode_filter
  - mm/oom_kill.c:oom_killer_disable
  - mm/percpu.c:pcpu_alloc
  - mm/memcontrol.c:mem_cgroup_out_of_memory
  - fs/proc/base.c:do_io_accounting
  - drivers/pci/vpd.c:pci_vpd_write
  - drivers/pci/vpd.c:pci_vpd_read
  - drivers/block/loop.c:lo_ioctl
  - drivers/block/loop.c:lo_ioctl
  - drivers/block/loop.c:lo_ioctl
  - drivers/block/loop.c:lo_ioctl
  - drivers/block/loop.c:loop_set_status
  - drivers/block/loop.c:loop_set_fd
  - drivers/block/loop.c:loop_set_fd
  - net/core/rtnetlink.c:rtnl_lock_killable
```
**Symbols:**

```
ffff800010da3788-ffff800010da37f0: mutex_lock_killable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int mutex_lock_killable(struct mutex *lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/mutex.c (c0e9c77c)
Location: kernel/locking/mutex.c:1330
Inline: False
Direct callers:
  - kernel/fork.c:mm_access
  - kernel/kcmp.c:__se_sys_kcmp
  - kernel/kcmp.c:__se_sys_kcmp
  - kernel/kcmp.c:__se_sys_kcmp
  - kernel/kcmp.c:__se_sys_kcmp
  - kernel/seccomp.c:seccomp_set_mode_filter
  - mm/oom_kill.c:oom_killer_disable
  - mm/percpu.c:pcpu_alloc
  - mm/memcontrol.c:mem_cgroup_out_of_memory
  - fs/proc/base.c:do_io_accounting
  - drivers/pci/vpd.c:pci_vpd_write
  - drivers/pci/vpd.c:pci_vpd_read
  - drivers/block/loop.c:lo_ioctl
  - drivers/block/loop.c:lo_ioctl
  - drivers/block/loop.c:lo_ioctl
  - drivers/block/loop.c:loop_set_status
  - drivers/block/loop.c:loop_set_fd
  - drivers/block/loop.c:loop_set_fd
  - net/core/rtnetlink.c:rtnl_lock_killable
```
**Symbols:**

```
c0e9c77c-c0e9c7dc: mutex_lock_killable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int mutex_lock_killable(struct mutex *lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/mutex.c (c000000000ee5dc0)
Location: kernel/locking/mutex.c:1330
Inline: False
Direct callers:
  - kernel/fork.c:mm_access
  - kernel/kcmp.c:__se_sys_kcmp
  - kernel/kcmp.c:__se_sys_kcmp
  - kernel/kcmp.c:__se_sys_kcmp
  - kernel/kcmp.c:__se_sys_kcmp
  - kernel/seccomp.c:seccomp_set_mode_filter
  - mm/oom_kill.c:oom_killer_disable
  - mm/percpu.c:pcpu_alloc
  - mm/memcontrol.c:mem_cgroup_out_of_memory
  - fs/proc/base.c:do_io_accounting
  - drivers/pci/vpd.c:pci_vpd_write
  - drivers/pci/vpd.c:pci_vpd_read
  - drivers/block/loop.c:lo_ioctl
  - drivers/block/loop.c:lo_ioctl
  - drivers/block/loop.c:lo_ioctl
  - drivers/block/loop.c:loop_set_status
  - drivers/block/loop.c:loop_set_fd
  - drivers/block/loop.c:loop_set_fd
  - net/core/rtnetlink.c:rtnl_lock_killable
```
**Symbols:**

```
c000000000ee5dc0-c000000000ee5e48: mutex_lock_killable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int mutex_lock_killable(struct mutex *lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/mutex.c (ffffffe0008c7594)
Location: kernel/locking/mutex.c:1330
Inline: False
Direct callers:
  - kernel/fork.c:mm_access
  - kernel/kcmp.c:__se_sys_kcmp
  - kernel/kcmp.c:__se_sys_kcmp
  - kernel/kcmp.c:__se_sys_kcmp
  - kernel/kcmp.c:__se_sys_kcmp
  - kernel/seccomp.c:seccomp_set_mode_filter
  - mm/oom_kill.c:oom_killer_disable
  - mm/percpu.c:pcpu_alloc
  - mm/memcontrol.c:mem_cgroup_out_of_memory
  - fs/proc/base.c:do_io_accounting
  - drivers/pci/vpd.c:pci_vpd_write
  - drivers/pci/vpd.c:pci_vpd_read
  - drivers/block/loop.c:lo_ioctl
  - drivers/block/loop.c:lo_ioctl
  - drivers/block/loop.c:lo_ioctl
  - drivers/block/loop.c:loop_set_status
  - drivers/block/loop.c:loop_set_fd
  - drivers/block/loop.c:loop_set_fd
  - net/core/rtnetlink.c:rtnl_lock_killable
```
**Symbols:**

```
ffffffe0008c7594-ffffffe0008c75da: mutex_lock_killable (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
int mutex_lock_killable(struct mutex *lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/mutex.c (ffffffff81a71280)
Location: kernel/locking/mutex.c:1330
Inline: False
Direct callers:
  - kernel/fork.c:mm_access
  - kernel/kcmp.c:__do_sys_kcmp
  - kernel/kcmp.c:__do_sys_kcmp
  - kernel/kcmp.c:__do_sys_kcmp
  - kernel/kcmp.c:__do_sys_kcmp
  - kernel/seccomp.c:seccomp_set_mode_filter
  - mm/oom_kill.c:oom_killer_disable
  - mm/percpu.c:pcpu_alloc
  - mm/memcontrol.c:mem_cgroup_out_of_memory
  - fs/proc/base.c:do_io_accounting
  - drivers/pci/vpd.c:pci_vpd_write
  - drivers/pci/vpd.c:pci_vpd_read
  - drivers/block/loop.c:lo_ioctl
  - drivers/block/loop.c:lo_ioctl
  - drivers/block/loop.c:lo_ioctl
  - drivers/block/loop.c:lo_ioctl
  - drivers/block/loop.c:loop_set_status
  - drivers/block/loop.c:loop_set_fd
  - drivers/block/loop.c:loop_set_fd
  - net/core/rtnetlink.c:rtnl_lock_killable
```
**Symbols:**

```
ffffffff81a71280-ffffffff81a712b8: mutex_lock_killable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int mutex_lock_killable(struct mutex *lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/mutex.c (ffffffff81a2d670)
Location: kernel/locking/mutex.c:1330
Inline: False
Direct callers:
  - kernel/fork.c:mm_access
  - kernel/kcmp.c:__do_sys_kcmp
  - kernel/kcmp.c:__do_sys_kcmp
  - kernel/kcmp.c:__do_sys_kcmp
  - kernel/kcmp.c:__do_sys_kcmp
  - kernel/seccomp.c:seccomp_set_mode_filter
  - mm/oom_kill.c:oom_killer_disable
  - mm/percpu.c:pcpu_alloc
  - mm/memcontrol.c:mem_cgroup_out_of_memory
  - fs/proc/base.c:do_io_accounting
  - drivers/pci/vpd.c:pci_vpd_write
  - drivers/pci/vpd.c:pci_vpd_read
  - drivers/block/loop.c:lo_ioctl
  - drivers/block/loop.c:lo_ioctl
  - drivers/block/loop.c:lo_ioctl
  - drivers/block/loop.c:lo_ioctl
  - drivers/block/loop.c:loop_set_status
  - drivers/block/loop.c:loop_set_fd
  - drivers/block/loop.c:loop_set_fd
  - net/core/rtnetlink.c:rtnl_lock_killable
```
**Symbols:**

```
ffffffff81a2d670-ffffffff81a2d6a8: mutex_lock_killable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int mutex_lock_killable(struct mutex *lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/mutex.c (ffffffff81add690)
Location: kernel/locking/mutex.c:1330
Inline: False
Direct callers:
  - kernel/fork.c:mm_access
  - kernel/kcmp.c:__do_sys_kcmp
  - kernel/kcmp.c:__do_sys_kcmp
  - kernel/kcmp.c:__do_sys_kcmp
  - kernel/kcmp.c:__do_sys_kcmp
  - kernel/seccomp.c:seccomp_set_mode_filter
  - mm/oom_kill.c:oom_killer_disable
  - mm/percpu.c:pcpu_alloc
  - mm/memcontrol.c:mem_cgroup_out_of_memory
  - fs/proc/base.c:do_io_accounting
  - drivers/pci/vpd.c:pci_vpd_write
  - drivers/pci/vpd.c:pci_vpd_read
  - drivers/block/loop.c:lo_ioctl
  - drivers/block/loop.c:lo_ioctl
  - drivers/block/loop.c:lo_ioctl
  - drivers/block/loop.c:lo_ioctl
  - drivers/block/loop.c:loop_set_status
  - drivers/block/loop.c:loop_set_fd
  - drivers/block/loop.c:loop_set_fd
  - net/core/rtnetlink.c:rtnl_lock_killable
```
**Symbols:**

```
ffffffff81add690-ffffffff81add6c8: mutex_lock_killable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int mutex_lock_killable(struct mutex *lock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/locking/mutex.c (ffffffff81ae9230)
Location: kernel/locking/mutex.c:1330
Inline: False
Direct callers:
  - kernel/fork.c:mm_access
  - kernel/kcmp.c:__do_sys_kcmp
  - kernel/kcmp.c:__do_sys_kcmp
  - kernel/kcmp.c:__do_sys_kcmp
  - kernel/seccomp.c:seccomp_set_mode_filter
  - mm/oom_kill.c:oom_killer_disable
  - mm/percpu.c:pcpu_alloc
  - mm/memcontrol.c:mem_cgroup_out_of_memory
  - fs/proc/base.c:do_io_accounting
  - drivers/pci/vpd.c:pci_vpd_write
  - drivers/pci/vpd.c:pci_vpd_read
  - drivers/block/loop.c:lo_ioctl
  - drivers/block/loop.c:lo_ioctl
  - drivers/block/loop.c:lo_ioctl
  - drivers/block/loop.c:lo_ioctl
  - drivers/block/loop.c:loop_set_status
  - drivers/block/loop.c:loop_set_fd
  - drivers/block/loop.c:loop_set_fd
  - net/core/rtnetlink.c:rtnl_lock_killable
```
**Symbols:**

```
ffffffff81ae9230-ffffffff81ae9255: mutex_lock_killable (STB_GLOBAL)
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
