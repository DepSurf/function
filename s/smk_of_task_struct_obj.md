# Function: <code>smk_of_task_struct_obj</code>

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
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/smack/smack_lsm.c (ffffffff814f7ee7)
Location: security/smack/smack.h:414
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_task_to_inode
  - security/smack/smack_lsm.c:smack_task_kill
  - security/smack/smack_lsm.c:smack_task_getsecid_obj
  - security/smack/smack_lsm.c:smack_ptrace_access_check
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/smack/smack_lsm.c (ffffffff81551575)
Location: security/smack/smack.h:414
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_getprocattr
  - security/smack/smack_lsm.c:smack_task_to_inode
  - security/smack/smack_lsm.c:smack_task_kill
  - security/smack/smack_lsm.c:smack_task_getsecid_obj
  - security/smack/smack_lsm.c:smk_curacc_on_task
  - security/smack/smack_lsm.c:smack_ptrace_access_check
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/smack/smack_lsm.c (ffffffff815eace3)
Location: security/smack/smack.h:398
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_getprocattr
  - security/smack/smack_lsm.c:smack_task_to_inode
  - security/smack/smack_lsm.c:smack_task_kill
  - security/smack/smack_lsm.c:smack_task_movememory
  - security/smack/smack_lsm.c:smack_task_getscheduler
  - security/smack/smack_lsm.c:smack_task_setscheduler
  - security/smack/smack_lsm.c:smack_task_getioprio
  - security/smack/smack_lsm.c:smack_task_setioprio
  - security/smack/smack_lsm.c:smack_task_setnice
  - security/smack/smack_lsm.c:smack_task_getsecid_obj
  - security/smack/smack_lsm.c:smack_task_getsid
  - security/smack/smack_lsm.c:smack_task_getpgid
  - security/smack/smack_lsm.c:smack_task_setpgid
  - security/smack/smack_lsm.c:smack_ptrace_access_check
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/smack/smack_lsm.c (ffffffff8169a943)
Location: security/smack/smack.h:389
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_getprocattr
  - security/smack/smack_lsm.c:smack_task_to_inode
  - security/smack/smack_lsm.c:smack_task_kill
  - security/smack/smack_lsm.c:smack_task_movememory
  - security/smack/smack_lsm.c:smack_task_getscheduler
  - security/smack/smack_lsm.c:smack_task_setscheduler
  - security/smack/smack_lsm.c:smack_task_getioprio
  - security/smack/smack_lsm.c:smack_task_setioprio
  - security/smack/smack_lsm.c:smack_task_setnice
  - security/smack/smack_lsm.c:smack_task_getsecid_obj
  - security/smack/smack_lsm.c:smack_task_getsid
  - security/smack/smack_lsm.c:smack_task_getpgid
  - security/smack/smack_lsm.c:smack_task_setpgid
  - security/smack/smack_lsm.c:smack_ptrace_access_check
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/smack/smack_lsm.c (ffffffff816d3113)
Location: security/smack/smack.h:390
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_getprocattr
  - security/smack/smack_lsm.c:smack_task_to_inode
  - security/smack/smack_lsm.c:smack_task_kill
  - security/smack/smack_lsm.c:smack_task_movememory
  - security/smack/smack_lsm.c:smack_task_getscheduler
  - security/smack/smack_lsm.c:smack_task_setscheduler
  - security/smack/smack_lsm.c:smack_task_getioprio
  - security/smack/smack_lsm.c:smack_task_setioprio
  - security/smack/smack_lsm.c:smack_task_setnice
  - security/smack/smack_lsm.c:smack_task_getsecid_obj
  - security/smack/smack_lsm.c:smack_task_getsid
  - security/smack/smack_lsm.c:smack_task_getpgid
  - security/smack/smack_lsm.c:smack_task_setpgid
  - security/smack/smack_lsm.c:smack_ptrace_access_check
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/smack/smack_lsm.c (ffffffff8170f4b3)
Location: security/smack/smack.h:406
Inline: True
Inline callers:
  - security/smack/smack_lsm.c:smack_getprocattr
  - security/smack/smack_lsm.c:smack_task_to_inode
  - security/smack/smack_lsm.c:smack_task_kill
  - security/smack/smack_lsm.c:smack_task_movememory
  - security/smack/smack_lsm.c:smack_task_getscheduler
  - security/smack/smack_lsm.c:smack_task_setscheduler
  - security/smack/smack_lsm.c:smack_task_getioprio
  - security/smack/smack_lsm.c:smack_task_setioprio
  - security/smack/smack_lsm.c:smack_task_setnice
  - security/smack/smack_lsm.c:smack_task_getlsmblob_obj
  - security/smack/smack_lsm.c:smack_task_getsid
  - security/smack/smack_lsm.c:smack_task_getpgid
  - security/smack/smack_lsm.c:smack_task_setpgid
  - security/smack/smack_lsm.c:smack_ptrace_access_check
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
