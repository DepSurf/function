# Function: <code>current_has_perm</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int current_has_perm(const struct task_struct *tsk, u32 perms);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff81342200)
Location: security/selinux/hooks.c:1571
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_task_movememory
  - security/selinux/hooks.c:selinux_task_getscheduler
  - security/selinux/hooks.c:selinux_task_getsid
  - security/selinux/hooks.c:selinux_task_getpgid
  - security/selinux/hooks.c:selinux_task_setpgid
  - security/selinux/hooks.c:selinux_task_create
  - security/selinux/hooks.c:selinux_capget
  - security/selinux/hooks.c:selinux_task_kill
  - security/selinux/hooks.c:selinux_file_mprotect
  - security/selinux/hooks.c:selinux_getprocattr
  - security/selinux/hooks.c:selinux_setprocattr
  - security/selinux/hooks.c:selinux_setprocattr
  - security/selinux/hooks.c:selinux_setprocattr
  - security/selinux/hooks.c:selinux_setprocattr
  - security/selinux/hooks.c:selinux_setprocattr
```
**Symbols:**

```
ffffffff81342200-ffffffff8134223f: current_has_perm (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int current_has_perm(const struct task_struct *tsk, u32 perms);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff813775e0)
Location: security/selinux/hooks.c:1642
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_setprocattr
  - security/selinux/hooks.c:selinux_setprocattr
  - security/selinux/hooks.c:selinux_setprocattr
  - security/selinux/hooks.c:selinux_setprocattr
  - security/selinux/hooks.c:selinux_setprocattr
  - security/selinux/hooks.c:selinux_getprocattr
  - security/selinux/hooks.c:selinux_task_kill
  - security/selinux/hooks.c:selinux_task_movememory
  - security/selinux/hooks.c:selinux_task_getscheduler
  - security/selinux/hooks.c:selinux_task_getsid
  - security/selinux/hooks.c:selinux_task_getpgid
  - security/selinux/hooks.c:selinux_task_setpgid
  - security/selinux/hooks.c:selinux_task_create
  - security/selinux/hooks.c:selinux_file_mprotect
  - security/selinux/hooks.c:selinux_capget
```
**Symbols:**

```
ffffffff813775e0-ffffffff8137761f: current_has_perm (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int current_has_perm(const struct task_struct *tsk, u32 perms);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff8138dff0)
Location: security/selinux/hooks.c:1650
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_setprocattr
  - security/selinux/hooks.c:selinux_setprocattr
  - security/selinux/hooks.c:selinux_setprocattr
  - security/selinux/hooks.c:selinux_setprocattr
  - security/selinux/hooks.c:selinux_setprocattr
  - security/selinux/hooks.c:selinux_getprocattr
  - security/selinux/hooks.c:selinux_task_kill
  - security/selinux/hooks.c:selinux_task_movememory
  - security/selinux/hooks.c:selinux_task_getscheduler
  - security/selinux/hooks.c:selinux_task_getsid
  - security/selinux/hooks.c:selinux_task_getpgid
  - security/selinux/hooks.c:selinux_task_setpgid
  - security/selinux/hooks.c:selinux_task_create
  - security/selinux/hooks.c:selinux_file_mprotect
  - security/selinux/hooks.c:selinux_capget
```
**Symbols:**

```
ffffffff8138dff0-ffffffff8138e02f: current_has_perm (STB_LOCAL)
```
</details>
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
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
</ul>
