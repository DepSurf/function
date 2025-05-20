# Function: <code>sem_wait_array</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In ipc/sem.c (ffffffff81326df0)
Location: ipc/sem.c:272
Inline: True
Inline callers:
  - ipc/sem.c:sysvipc_sem_proc_show
  - ipc/sem.c:SYSC_semtimedop
  - ipc/sem.c:SYSC_semtimedop
  - ipc/sem.c:SYSC_semtimedop
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_main
  - ipc/sem.c:SyS_semctl
  - ipc/sem.c:exit_sem
Direct callers:
  - ipc/sem.c:sysvipc_sem_proc_show
  - ipc/sem.c:SYSC_semtimedop
  - ipc/sem.c:SYSC_semtimedop
  - ipc/sem.c:SYSC_semtimedop
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_main
  - ipc/sem.c:SyS_semctl
  - ipc/sem.c:exit_sem
```
**Symbols:**

```
ffffffff81326df0-ffffffff81326e27: sem_wait_array.part.2 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In ipc/sem.c (ffffffff8135b93e)
Location: ipc/sem.c:269
Inline: True
Inline callers:
  - ipc/sem.c:sysvipc_sem_proc_show
  - ipc/sem.c:exit_sem
  - ipc/sem.c:SYSC_semtimedop
  - ipc/sem.c:SYSC_semtimedop
  - ipc/sem.c:SYSC_semtimedop
  - ipc/sem.c:SyS_semctl
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_main
Direct callers:
  - ipc/sem.c:sysvipc_sem_proc_show
  - ipc/sem.c:exit_sem
  - ipc/sem.c:SYSC_semtimedop
  - ipc/sem.c:SYSC_semtimedop
  - ipc/sem.c:SYSC_semtimedop
  - ipc/sem.c:SyS_semctl
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_main
  - ipc/sem.c:semctl_main
```
**Symbols:**

```
ffffffff8135b8d0-ffffffff8135b90d: sem_wait_array.part.4 (STB_LOCAL)
```
</details>
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
In <code>6.8</code>: Absent ⚠️
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
