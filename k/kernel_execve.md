# Function: <code>kernel_execve</code>

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
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int kernel_execve(const char *kernel_filename, const const char * *argv, const const char * *envp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/exec.c (ffffffff81329850)
Location: fs/exec.c:1932
Inline: False
Direct callers:
  - init/main.c:run_init_process
  - kernel/umh.c:call_usermodehelper_exec_async
```
**Symbols:**

```
ffffffff81329850-ffffffff81329a05: kernel_execve (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int kernel_execve(const char *kernel_filename, const const char * *argv, const const char * *envp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/exec.c (ffffffff8132f690)
Location: fs/exec.c:1932
Inline: False
Direct callers:
  - init/main.c:run_init_process
  - kernel/umh.c:call_usermodehelper_exec_async
```
**Symbols:**

```
ffffffff8132f690-ffffffff8132f832: kernel_execve (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int kernel_execve(const char *kernel_filename, const const char * *argv, const const char * *envp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/exec.c (ffffffff8137ce40)
Location: fs/exec.c:1934
Inline: False
Direct callers:
  - init/main.c:run_init_process
  - kernel/umh.c:call_usermodehelper_exec_async
```
**Symbols:**

```
ffffffff8137ce40-ffffffff8137cfe2: kernel_execve (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int kernel_execve(const char *kernel_filename, const const char * *argv, const const char * *envp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/exec.c (ffffffff813fcad0)
Location: fs/exec.c:1955
Inline: False
Direct callers:
  - init/main.c:run_init_process
  - kernel/umh.c:call_usermodehelper_exec_async
```
**Symbols:**

```
ffffffff813fcad0-ffffffff813fcc7e: kernel_execve (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int kernel_execve(const char *kernel_filename, const const char * *argv, const const char * *envp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/exec.c (ffffffff81486640)
Location: fs/exec.c:1965
Inline: False
Direct callers:
  - init/main.c:run_init_process
  - kernel/umh.c:call_usermodehelper_exec_async
```
**Symbols:**

```
ffffffff81486640-ffffffff814867ee: kernel_execve (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int kernel_execve(const char *kernel_filename, const const char * *argv, const const char * *envp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/exec.c (ffffffff814bb2f0)
Location: fs/exec.c:1972
Inline: False
Direct callers:
  - init/main.c:run_init_process
  - kernel/umh.c:call_usermodehelper_exec_async
```
**Symbols:**

```
ffffffff814bb2f0-ffffffff814bb49e: kernel_execve (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int kernel_execve(const char *kernel_filename, const const char * *argv, const const char * *envp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/exec.c (ffffffff814ed860)
Location: fs/exec.c:1993
Inline: False
Direct callers:
  - init/main.c:run_init_process
  - kernel/umh.c:call_usermodehelper_exec_async
```
**Symbols:**

```
ffffffff814ed860-ffffffff814eda06: kernel_execve (STB_GLOBAL)
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
