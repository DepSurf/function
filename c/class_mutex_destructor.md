# Function: <code>class_mutex_destructor</code>

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
<summary>In <code>6.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/ptrace.c (ffffffff81111082)
Location: include/linux/mutex.h:173
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_attach
  - kernel/ptrace.c:ptrace_attach
```
```
In kernel/sched/core.c (ffffffff81150046)
Location: include/linux/mutex.h:173
Inline: True
Inline callers:
  - kernel/sched/core.c:tg_set_cfs_bandwidth
  - kernel/sched/core.c:cpu_cgroup_css_online
  - kernel/sched/core.c:sysctl_sched_uclamp_handler
```
```
In kernel/sched/build_utility.c (ffffffff8118fc9c)
Location: include/linux/mutex.h:173
Inline: True
Inline callers:
  - kernel/sched/build_utility.c:__do_sys_membarrier
  - kernel/sched/build_utility.c:sync_runqueues_membarrier_state
  - kernel/sched/build_utility.c:membarrier_private_expedited
```
```
In fs/pstore/inode.c (ffffffff816ac1d8)
Location: include/linux/mutex.h:173
Inline: True
Inline callers:
  - fs/pstore/inode.c:pstore_kill_sb
  - fs/pstore/inode.c:pstore_kill_sb
  - fs/pstore/inode.c:pstore_fill_super
  - fs/pstore/inode.c:pstore_get_records
  - fs/pstore/inode.c:pstore_mkfile
  - fs/pstore/inode.c:pstore_put_backend_records
  - fs/pstore/inode.c:pstore_put_backend_records
  - fs/pstore/inode.c:pstore_unlink
  - fs/pstore/inode.c:pstore_unlink
  - fs/pstore/inode.c:pstore_unlink
```
```
In drivers/gpio/gpiolib.c (ffffffff819472aa)
Location: include/linux/mutex.h:173
Inline: True
Inline callers:
  - drivers/gpio/gpiolib.c:gpiod_count
  - drivers/gpio/gpiolib.c:gpiod_count
  - drivers/gpio/gpiolib.c:gpiod_find
```
```
In drivers/gpio/gpiolib-cdev.c (ffffffff8194fe80)
Location: include/linux/mutex.h:173
Inline: True
Inline callers:
  - drivers/gpio/gpiolib-cdev.c:linereq_set_config
  - drivers/gpio/gpiolib-cdev.c:linereq_set_values
```
```
In drivers/acpi/numa/hmat.c (ffffffff81a6e05c)
Location: include/linux/mutex.h:173
Inline: True
Inline callers:
  - drivers/acpi/numa/hmat.c:acpi_get_genport_coordinates
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
