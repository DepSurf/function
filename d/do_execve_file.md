# Function: <code>do_execve_file</code>

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
<summary>In <code>4.18</code>: ✅</summary>

```c
int do_execve_file(struct file *file, void *__argv, void *__envp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/exec.c (ffffffff812a33e0)
Location: fs/exec.c:1880
Inline: False
Direct callers:
  - kernel/umh.c:call_usermodehelper_exec_async
```
**Symbols:**

```
ffffffff812a33e0-ffffffff812a3405: do_execve_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int do_execve_file(struct file *file, void *__argv, void *__envp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/exec.c (ffffffff812b8530)
Location: fs/exec.c:1880
Inline: False
Direct callers:
  - kernel/umh.c:call_usermodehelper_exec_async
```
**Symbols:**

```
ffffffff812b8530-ffffffff812b8555: do_execve_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int do_execve_file(struct file *file, void *__argv, void *__envp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/exec.c (ffffffff812d50c0)
Location: fs/exec.c:1883
Inline: False
Direct callers:
  - kernel/umh.c:call_usermodehelper_exec_async
```
**Symbols:**

```
ffffffff812d50c0-ffffffff812d50e5: do_execve_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int do_execve_file(struct file *file, void *__argv, void *__envp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/exec.c (ffffffff812e6c50)
Location: fs/exec.c:1883
Inline: False
Direct callers:
  - kernel/umh.c:call_usermodehelper_exec_async
```
**Symbols:**

```
ffffffff812e6c50-ffffffff812e6c75: do_execve_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int do_execve_file(struct file *file, void *__argv, void *__envp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/exec.c (ffffffff8131e2a0)
Location: fs/exec.c:1991
Inline: False
Direct callers:
  - kernel/umh.c:call_usermodehelper_exec_async
```
**Symbols:**

```
ffffffff8131e2a0-ffffffff8131e2c7: do_execve_file (STB_GLOBAL)
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
<summary>In <code>arm64</code>: ✅</summary>

```c
int do_execve_file(struct file *file, void *__argv, void *__envp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/exec.c (ffff80001038f088)
Location: fs/exec.c:1883
Inline: False
Direct callers:
  - kernel/umh.c:call_usermodehelper_exec_async
```
**Symbols:**

```
ffff80001038f088-ffff80001038f0e0: do_execve_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int do_execve_file(struct file *file, void *__argv, void *__envp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/exec.c (c0576154)
Location: fs/exec.c:1883
Inline: False
Direct callers:
  - kernel/umh.c:call_usermodehelper_exec_async
```
**Symbols:**

```
c0576154-c0576194: do_execve_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int do_execve_file(struct file *file, void *__argv, void *__envp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/exec.c (c000000000486c50)
Location: fs/exec.c:1883
Inline: False
Direct callers:
  - kernel/umh.c:call_usermodehelper_exec_async
```
**Symbols:**

```
c000000000486c50-c000000000486c84: do_execve_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int do_execve_file(struct file *file, void *__argv, void *__envp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/exec.c (ffffffe00025f16c)
Location: fs/exec.c:1883
Inline: False
Direct callers:
  - kernel/umh.c:call_usermodehelper_exec_async
```
**Symbols:**

```
ffffffe00025f16c-ffffffe00025f1ae: do_execve_file (STB_GLOBAL)
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
int do_execve_file(struct file *file, void *__argv, void *__envp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/exec.c (ffffffff812df230)
Location: fs/exec.c:1883
Inline: False
Direct callers:
  - kernel/umh.c:call_usermodehelper_exec_async
```
**Symbols:**

```
ffffffff812df230-ffffffff812df255: do_execve_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int do_execve_file(struct file *file, void *__argv, void *__envp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/exec.c (ffffffff812cfe70)
Location: fs/exec.c:1883
Inline: False
Direct callers:
  - kernel/umh.c:call_usermodehelper_exec_async
```
**Symbols:**

```
ffffffff812cfe70-ffffffff812cfe95: do_execve_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int do_execve_file(struct file *file, void *__argv, void *__envp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/exec.c (ffffffff812dd040)
Location: fs/exec.c:1883
Inline: False
Direct callers:
  - kernel/umh.c:call_usermodehelper_exec_async
```
**Symbols:**

```
ffffffff812dd040-ffffffff812dd065: do_execve_file (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int do_execve_file(struct file *file, void *__argv, void *__envp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/exec.c (ffffffff812edfd0)
Location: fs/exec.c:1883
Inline: False
Direct callers:
  - kernel/umh.c:call_usermodehelper_exec_async
```
**Symbols:**

```
ffffffff812edfd0-ffffffff812edff5: do_execve_file (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
