# Function: <code>__do_execve_file</code>

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
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/exec.c (ffffffff812a28f0)
Location: fs/exec.c:1720
Inline: True
Direct callers:
  - fs/exec.c:__x32_compat_sys_execveat
  - fs/exec.c:__ia32_compat_sys_execveat
  - fs/exec.c:__x32_compat_sys_execve
  - fs/exec.c:__ia32_compat_sys_execve
  - fs/exec.c:__ia32_sys_execveat
  - fs/exec.c:__x64_sys_execveat
  - fs/exec.c:__ia32_sys_execve
  - fs/exec.c:__x64_sys_execve
  - fs/exec.c:do_execve_file
```
**Symbols:**

```
ffffffff812a28f0-ffffffff812a30eb: __do_execve_file.isra.41 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/exec.c (ffffffff812b7760)
Location: fs/exec.c:1724
Inline: True
Direct callers:
  - fs/exec.c:__x32_compat_sys_execveat
  - fs/exec.c:__ia32_compat_sys_execveat
  - fs/exec.c:__x32_compat_sys_execve
  - fs/exec.c:__ia32_compat_sys_execve
  - fs/exec.c:__ia32_sys_execveat
  - fs/exec.c:__x64_sys_execveat
  - fs/exec.c:__ia32_sys_execve
  - fs/exec.c:__x64_sys_execve
  - fs/exec.c:do_execve_file
```
**Symbols:**

```
ffffffff812b7760-ffffffff812b818a: __do_execve_file.isra.41 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/exec.c (ffffffff812d3de0)
Location: fs/exec.c:1727
Inline: True
Direct callers:
  - fs/exec.c:__x32_compat_sys_execveat
  - fs/exec.c:__ia32_compat_sys_execveat
  - fs/exec.c:__x32_compat_sys_execve
  - fs/exec.c:__ia32_compat_sys_execve
  - fs/exec.c:__ia32_sys_execveat
  - fs/exec.c:__x64_sys_execveat
  - fs/exec.c:__ia32_sys_execve
  - fs/exec.c:__x64_sys_execve
  - fs/exec.c:do_execve_file
```
**Symbols:**

```
ffffffff812d3de0-ffffffff812d4640: __do_execve_file.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/exec.c (ffffffff812e5970)
Location: fs/exec.c:1728
Inline: True
Direct callers:
  - fs/exec.c:__x32_compat_sys_execveat
  - fs/exec.c:__ia32_compat_sys_execveat
  - fs/exec.c:__x32_compat_sys_execve
  - fs/exec.c:__ia32_compat_sys_execve
  - fs/exec.c:__ia32_sys_execveat
  - fs/exec.c:__x64_sys_execveat
  - fs/exec.c:__ia32_sys_execve
  - fs/exec.c:__x64_sys_execve
  - fs/exec.c:do_execve_file
```
**Symbols:**

```
ffffffff812e5970-ffffffff812e61bf: __do_execve_file.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int __do_execve_file(int fd, struct filename *filename, struct user_arg_ptr argv, struct user_arg_ptr envp, int flags, struct file *file);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/exec.c (ffffffff8131d460)
Location: fs/exec.c:1829
Inline: False
Direct callers:
  - fs/exec.c:__x32_compat_sys_execveat
  - fs/exec.c:__ia32_compat_sys_execveat
  - fs/exec.c:__x32_compat_sys_execve
  - fs/exec.c:__ia32_compat_sys_execve
  - fs/exec.c:do_execveat
  - fs/exec.c:do_execve
  - fs/exec.c:do_execve_file
```
**Symbols:**

```
ffffffff8131d460-ffffffff8131d9d0: __do_execve_file (STB_LOCAL)
```
</details>
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
<details>
<summary>In <code>arm64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/exec.c (ffff80001038dcf8)
Location: fs/exec.c:1728
Inline: True
Direct callers:
  - fs/exec.c:__arm64_compat_sys_execveat
  - fs/exec.c:__arm64_compat_sys_execve
  - fs/exec.c:__arm64_sys_execveat
  - fs/exec.c:__arm64_sys_execve
  - fs/exec.c:do_execve_file
```
**Symbols:**

```
ffff80001038dcf8-ffff80001038e4ac: __do_execve_file.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int __do_execve_file(int fd, struct filename *filename, struct user_arg_ptr argv, struct user_arg_ptr envp, int flags, struct file *file);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/exec.c (c0575628)
Location: fs/exec.c:1728
Inline: False
Direct callers:
  - fs/exec.c:__se_sys_execveat
  - fs/exec.c:__se_sys_execve
  - fs/exec.c:do_execve_file
```
**Symbols:**

```
c0575628-c0575e9c: __do_execve_file (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/exec.c (c000000000485f00)
Location: fs/exec.c:1728
Inline: True
Direct callers:
  - fs/exec.c:__se_compat_sys_execveat
  - fs/exec.c:__se_compat_sys_execve
  - fs/exec.c:__se_sys_execveat
  - fs/exec.c:__se_sys_execve
  - fs/exec.c:do_execve_file
```
**Symbols:**

```
c000000000485f00-c000000000486920: __do_execve_file.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int __do_execve_file(int fd, struct filename *filename, struct user_arg_ptr argv, struct user_arg_ptr envp, int flags, struct file *file);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/exec.c (ffffffe00025e872)
Location: fs/exec.c:1728
Inline: False
Direct callers:
  - fs/exec.c:__se_sys_execveat
  - fs/exec.c:__se_sys_execve
  - fs/exec.c:do_execve_file
```
**Symbols:**

```
ffffffe00025e872-ffffffe00025ef08: __do_execve_file (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/exec.c (ffffffff812ddf50)
Location: fs/exec.c:1728
Inline: True
Direct callers:
  - fs/exec.c:__x32_compat_sys_execveat
  - fs/exec.c:__ia32_compat_sys_execveat
  - fs/exec.c:__x32_compat_sys_execve
  - fs/exec.c:__ia32_compat_sys_execve
  - fs/exec.c:__ia32_sys_execveat
  - fs/exec.c:__x64_sys_execveat
  - fs/exec.c:__ia32_sys_execve
  - fs/exec.c:__x64_sys_execve
  - fs/exec.c:do_execve_file
```
**Symbols:**

```
ffffffff812ddf50-ffffffff812de79f: __do_execve_file.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/exec.c (ffffffff812cf280)
Location: fs/exec.c:1728
Inline: True
Direct callers:
  - fs/exec.c:__x32_compat_sys_execveat
  - fs/exec.c:__ia32_compat_sys_execveat
  - fs/exec.c:__x32_compat_sys_execve
  - fs/exec.c:__ia32_compat_sys_execve
  - fs/exec.c:__ia32_sys_execveat
  - fs/exec.c:__x64_sys_execveat
  - fs/exec.c:__ia32_sys_execve
  - fs/exec.c:__x64_sys_execve
  - fs/exec.c:do_execve_file
```
**Symbols:**

```
ffffffff812cf280-ffffffff812cfacf: __do_execve_file.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/exec.c (ffffffff812dbd60)
Location: fs/exec.c:1728
Inline: True
Direct callers:
  - fs/exec.c:__x32_compat_sys_execveat
  - fs/exec.c:__ia32_compat_sys_execveat
  - fs/exec.c:__x32_compat_sys_execve
  - fs/exec.c:__ia32_compat_sys_execve
  - fs/exec.c:__ia32_sys_execveat
  - fs/exec.c:__x64_sys_execveat
  - fs/exec.c:__ia32_sys_execve
  - fs/exec.c:__x64_sys_execve
  - fs/exec.c:do_execve_file
```
**Symbols:**

```
ffffffff812dbd60-ffffffff812dc5af: __do_execve_file.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/exec.c (ffffffff812ecae0)
Location: fs/exec.c:1728
Inline: True
Direct callers:
  - fs/exec.c:__x32_compat_sys_execveat
  - fs/exec.c:__ia32_compat_sys_execveat
  - fs/exec.c:__x32_compat_sys_execve
  - fs/exec.c:__ia32_compat_sys_execve
  - fs/exec.c:__ia32_sys_execveat
  - fs/exec.c:__x64_sys_execveat
  - fs/exec.c:__ia32_sys_execve
  - fs/exec.c:__x64_sys_execve
  - fs/exec.c:do_execve_file
```
**Symbols:**

```
ffffffff812ecae0-ffffffff812ed36b: __do_execve_file.isra.0 (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
</ul>
<b>Arch</b>
<ul>
</ul>
