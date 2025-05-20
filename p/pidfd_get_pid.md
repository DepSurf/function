# Function: <code>pidfd_get_pid</code>

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
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/exit.c (ffffffff810a5bc2)
Location: kernel/exit.c:1473
Inline: True
Inline callers:
  - kernel/exit.c:kernel_waitid
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/exit.c (ffffffff810ad6ea)
Location: kernel/exit.c:1477
Inline: True
Inline callers:
  - kernel/exit.c:kernel_waitid
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct pid *pidfd_get_pid(unsigned int fd, unsigned int *flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/pid.c (ffffffff810c8ee0)
Location: kernel/pid.c:523
Inline: False
Direct callers:
  - kernel/exit.c:kernel_waitid
  - kernel/bpf/bpf_task_storage.c:bpf_pid_task_storage_delete_elem
  - kernel/bpf/bpf_task_storage.c:bpf_pid_task_storage_update_elem
  - kernel/bpf/bpf_task_storage.c:bpf_pid_task_storage_lookup_elem
  - mm/madvise.c:__do_sys_process_madvise
```
**Symbols:**

```
ffffffff810c8ee0-ffffffff810c8f84: pidfd_get_pid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct pid *pidfd_get_pid(unsigned int fd, unsigned int *flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/pid.c (ffffffff810ca980)
Location: kernel/pid.c:523
Inline: False
Direct callers:
  - kernel/exit.c:kernel_waitid
  - kernel/bpf/bpf_task_storage.c:bpf_pid_task_storage_delete_elem
  - kernel/bpf/bpf_task_storage.c:bpf_pid_task_storage_update_elem
  - kernel/bpf/bpf_task_storage.c:bpf_pid_task_storage_lookup_elem
  - mm/madvise.c:__do_sys_process_madvise
```
**Symbols:**

```
ffffffff810ca980-ffffffff810caa24: pidfd_get_pid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct pid *pidfd_get_pid(unsigned int fd, unsigned int *flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/pid.c (ffffffff810dd8d0)
Location: kernel/pid.c:523
Inline: False
Direct callers:
  - kernel/exit.c:kernel_waitid
  - kernel/bpf/bpf_task_storage.c:bpf_pid_task_storage_delete_elem
  - kernel/bpf/bpf_task_storage.c:bpf_pid_task_storage_update_elem
  - kernel/bpf/bpf_task_storage.c:bpf_pid_task_storage_lookup_elem
  - mm/oom_kill.c:__do_sys_process_mrelease
  - mm/madvise.c:__do_sys_process_madvise
```
**Symbols:**

```
ffffffff810dd8d0-ffffffff810dd974: pidfd_get_pid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct pid *pidfd_get_pid(unsigned int fd, unsigned int *flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/pid.c (ffffffff810f7250)
Location: kernel/pid.c:523
Inline: False
Direct callers:
  - kernel/exit.c:kernel_waitid
  - kernel/pid.c:pidfd_get_task
  - kernel/bpf/bpf_task_storage.c:bpf_pid_task_storage_delete_elem
  - kernel/bpf/bpf_task_storage.c:bpf_pid_task_storage_update_elem
  - kernel/bpf/bpf_task_storage.c:bpf_pid_task_storage_lookup_elem
```
**Symbols:**

```
ffffffff810f7250-ffffffff810f7323: pidfd_get_pid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct pid *pidfd_get_pid(unsigned int fd, unsigned int *flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/pid.c (ffffffff811199a0)
Location: kernel/pid.c:524
Inline: False
Direct callers:
  - kernel/exit.c:kernel_waitid
  - kernel/pid.c:pidfd_get_task
  - kernel/bpf/task_iter.c:bpf_iter_attach_task
  - kernel/bpf/bpf_task_storage.c:bpf_pid_task_storage_delete_elem
  - kernel/bpf/bpf_task_storage.c:bpf_pid_task_storage_update_elem
  - kernel/bpf/bpf_task_storage.c:bpf_pid_task_storage_lookup_elem
```
**Symbols:**

```
ffffffff811199a0-ffffffff81119a73: pidfd_get_pid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct pid *pidfd_get_pid(unsigned int fd, unsigned int *flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/pid.c (ffffffff81126e80)
Location: kernel/pid.c:527
Inline: False
Direct callers:
  - kernel/exit.c:kernel_waitid
  - kernel/pid.c:pidfd_get_task
  - kernel/bpf/task_iter.c:bpf_iter_attach_task
  - kernel/bpf/bpf_task_storage.c:bpf_pid_task_storage_delete_elem
  - kernel/bpf/bpf_task_storage.c:bpf_pid_task_storage_update_elem
  - kernel/bpf/bpf_task_storage.c:bpf_pid_task_storage_lookup_elem
```
**Symbols:**

```
ffffffff81126e80-ffffffff81126f53: pidfd_get_pid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct pid *pidfd_get_pid(unsigned int fd, unsigned int *flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/pid.c (ffffffff81131460)
Location: kernel/pid.c:527
Inline: False
Direct callers:
  - kernel/exit.c:kernel_waitid_prepare
  - kernel/pid.c:pidfd_get_task
  - kernel/bpf/task_iter.c:bpf_iter_attach_task
  - kernel/bpf/bpf_task_storage.c:bpf_pid_task_storage_delete_elem
  - kernel/bpf/bpf_task_storage.c:bpf_pid_task_storage_update_elem
  - kernel/bpf/bpf_task_storage.c:bpf_pid_task_storage_lookup_elem
```
**Symbols:**

```
ffffffff81131460-ffffffff81131533: pidfd_get_pid (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/exit.c (ffff8000100fbc6c)
Location: kernel/exit.c:1473
Inline: True
Inline callers:
  - kernel/exit.c:kernel_waitid
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/exit.c (c0359c5c)
Location: kernel/exit.c:1473
Inline: True
Inline callers:
  - kernel/exit.c:kernel_waitid
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/exit.c (c0000000001432b0)
Location: kernel/exit.c:1473
Inline: True
Inline callers:
  - kernel/exit.c:kernel_waitid
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/exit.c (ffffffe0000c56be)
Location: kernel/exit.c:1473
Inline: True
Inline callers:
  - kernel/exit.c:kernel_waitid
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/exit.c (ffffffff8109f4e2)
Location: kernel/exit.c:1473
Inline: True
Inline callers:
  - kernel/exit.c:kernel_waitid
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/exit.c (ffffffff8108df12)
Location: kernel/exit.c:1473
Inline: True
Inline callers:
  - kernel/exit.c:kernel_waitid
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/exit.c (ffffffff8109f492)
Location: kernel/exit.c:1473
Inline: True
Inline callers:
  - kernel/exit.c:kernel_waitid
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/exit.c (ffffffff810a73f2)
Location: kernel/exit.c:1473
Inline: True
Inline callers:
  - kernel/exit.c:kernel_waitid
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
