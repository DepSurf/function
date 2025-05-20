# Function: <code>register_sysctl_sz</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
In <code>4.8</code>: Absent ⚠️
</li>
<li>
In <code>4.10</code>: Absent ⚠️
</li>
<li>
In <code>4.13</code>: Absent ⚠️
</li>
<li>
In <code>4.15</code>: Absent ⚠️
</li>
<li>
In <code>4.18</code>: Absent ⚠️
</li>
<li>
In <code>5.0</code>: Absent ⚠️
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
struct ctl_table_header *register_sysctl_sz(const char *path, struct ctl_table *table, size_t table_size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/proc/proc_sysctl.c (ffffffff83923b15)
Location: fs/proc/proc_sysctl.c:1414
Inline: True
Inline callers:
  - fs/proc/proc_sysctl.c:__register_sysctl_init
  - fs/proc/proc_sysctl.c:register_sysctl_mount_point
Direct callers:
  - arch/x86/entry/vdso/vdso32-setup.c:ia32_binfmt_init
  - arch/x86/kernel/itmt.c:sched_set_itmt_support
  - kernel/ucount.c:user_namespace_sysctl_init
  - kernel/time/timer.c:timer_sysctl_init
  - kernel/pid_namespace.c:pid_namespaces_init
  - kernel/utsname_sysctl.c:utsname_sysctl_init
  - fs/notify/inotify/inotify_user.c:inotify_user_setup
  - fs/notify/fanotify/fanotify_user.c:fanotify_user_setup
  - fs/eventpoll.c:eventpoll_init
  - fs/verity/init.c:fsverity_init
  - fs/devpts/inode.c:init_devpts_fs
  - security/apparmor/lsm.c:apparmor_init
  - security/yama/yama_lsm.c:yama_init
  - drivers/char/hpet.c:hpet_init
  - drivers/base/firmware_loader/fallback_table.c:register_firmware_config_sysctl
  - drivers/scsi/scsi_sysctl.c:scsi_init_sysctl
  - drivers/scsi/sg.c:init_sg
  - drivers/md/md.c:md_init
  - drivers/hv/hv_common.c:hv_common_init
  - net/sysctl_net.c:net_sysctl_init
```
**Symbols:**

```
ffffffff815b45d0-ffffffff815b45fc: register_sysctl_sz (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
</ul>
