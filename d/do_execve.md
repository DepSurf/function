# Function: <code>do_execve</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
int do_execve(struct filename *filename, const const char * *__argv, const const char * *__envp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/exec.c (ffffffff81214530)
Location: fs/exec.c:1640
Inline: True
Inline callers:
  - fs/exec.c:SyS_execve
Direct callers:
  - init/main.c:run_init_process
  - kernel/kmod.c:call_usermodehelper_exec_async
```
**Symbols:**

```
ffffffff81214530-ffffffff8121455e: do_execve (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
int do_execve(struct filename *filename, const const char * *__argv, const const char * *__envp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/exec.c (ffffffff8123b53b)
Location: fs/exec.c:1789
Inline: True
Inline callers:
  - fs/exec.c:SyS_execve
Direct callers:
  - init/main.c:run_init_process
  - kernel/kmod.c:call_usermodehelper_exec_async
```
**Symbols:**

```
ffffffff8123b2c0-ffffffff8123b2ee: do_execve (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
int do_execve(struct filename *filename, const const char * *__argv, const const char * *__envp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/exec.c (ffffffff8124e2db)
Location: fs/exec.c:1817
Inline: True
Inline callers:
  - fs/exec.c:SyS_execve
Direct callers:
  - init/main.c:run_init_process
  - kernel/kmod.c:call_usermodehelper_exec_async
```
**Symbols:**

```
ffffffff8124e0b0-ffffffff8124e0de: do_execve (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int do_execve(struct filename *filename, const const char * *__argv, const const char * *__envp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/exec.c (ffffffff8125a297)
Location: fs/exec.c:1849
Inline: True
Inline callers:
  - fs/exec.c:SyS_execve
Direct callers:
  - init/main.c:run_init_process
  - kernel/kmod.c:call_usermodehelper_exec_async
```
**Symbols:**

```
ffffffff8125a070-ffffffff8125a095: do_execve (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int do_execve(struct filename *filename, const const char * *__argv, const const char * *__envp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/exec.c (ffffffff8127c597)
Location: fs/exec.c:1853
Inline: True
Inline callers:
  - fs/exec.c:SyS_execve
Direct callers:
  - init/main.c:run_init_process
  - kernel/umh.c:call_usermodehelper_exec_async
```
**Symbols:**

```
ffffffff8127c360-ffffffff8127c385: do_execve (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
int do_execve(struct filename *filename, const const char * *__argv, const const char * *__envp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/exec.c (ffffffff812a31cb)
Location: fs/exec.c:1888
Inline: True
Inline callers:
  - fs/exec.c:__ia32_sys_execve
  - fs/exec.c:__x64_sys_execve
Direct callers:
  - init/main.c:run_init_process
  - kernel/umh.c:call_usermodehelper_exec_async
```
**Symbols:**

```
ffffffff812a3410-ffffffff812a3437: do_execve (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int do_execve(struct filename *filename, const const char * *__argv, const const char * *__envp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/exec.c (ffffffff812b826b)
Location: fs/exec.c:1888
Inline: True
Inline callers:
  - fs/exec.c:__ia32_sys_execve
  - fs/exec.c:__x64_sys_execve
Direct callers:
  - init/main.c:run_init_process
  - kernel/umh.c:call_usermodehelper_exec_async
```
**Symbols:**

```
ffffffff812b8560-ffffffff812b8587: do_execve (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
int do_execve(struct filename *filename, const const char * *__argv, const const char * *__envp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/exec.c (ffffffff812d4729)
Location: fs/exec.c:1891
Inline: True
Inline callers:
  - fs/exec.c:__ia32_sys_execve
  - fs/exec.c:__x64_sys_execve
Direct callers:
  - init/main.c:run_init_process
  - kernel/umh.c:call_usermodehelper_exec_async
```
**Symbols:**

```
ffffffff812d50f0-ffffffff812d5117: do_execve (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int do_execve(struct filename *filename, const const char * *__argv, const const char * *__envp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/exec.c (ffffffff812e62a9)
Location: fs/exec.c:1891
Inline: True
Inline callers:
  - fs/exec.c:__ia32_sys_execve
  - fs/exec.c:__x64_sys_execve
Direct callers:
  - init/main.c:run_init_process
  - kernel/umh.c:call_usermodehelper_exec_async
```
**Symbols:**

```
ffffffff812e6c80-ffffffff812e6ca7: do_execve (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int do_execve(struct filename *filename, const const char * *__argv, const const char * *__envp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/exec.c (ffffffff8131e2d0)
Location: fs/exec.c:1999
Inline: False
Direct callers:
  - init/main.c:run_init_process
  - kernel/umh.c:call_usermodehelper_exec_async
  - fs/exec.c:__ia32_sys_execve
  - fs/exec.c:__x64_sys_execve
```
**Symbols:**

```
ffffffff8131e2d0-ffffffff8131e2f9: do_execve (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/exec.c (ffffffff81328ddb)
Location: fs/exec.c:1985
Inline: True
Inline callers:
  - fs/exec.c:__ia32_sys_execve
  - fs/exec.c:__x64_sys_execve
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/exec.c (ffffffff8132ed39)
Location: fs/exec.c:1985
Inline: True
Inline callers:
  - fs/exec.c:__ia32_sys_execve
  - fs/exec.c:__x64_sys_execve
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
In fs/exec.c (ffffffff8137c539)
Location: fs/exec.c:1987
Inline: True
Inline callers:
  - fs/exec.c:__ia32_sys_execve
  - fs/exec.c:__x64_sys_execve
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
In fs/exec.c (ffffffff813fc8e9)
Location: fs/exec.c:2014
Inline: True
Inline callers:
  - fs/exec.c:__ia32_sys_execve
  - fs/exec.c:__x64_sys_execve
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
In fs/exec.c (ffffffff81486409)
Location: fs/exec.c:2024
Inline: True
Inline callers:
  - fs/exec.c:__ia32_sys_execve
  - fs/exec.c:__x64_sys_execve
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
In fs/exec.c (ffffffff814baf79)
Location: fs/exec.c:2031
Inline: True
Inline callers:
  - fs/exec.c:__ia32_sys_execve
  - fs/exec.c:__x64_sys_execve
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
In fs/exec.c (ffffffff814ed4e9)
Location: fs/exec.c:2052
Inline: True
Inline callers:
  - fs/exec.c:__ia32_sys_execve
  - fs/exec.c:__x64_sys_execve
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
int do_execve(struct filename *filename, const const char * *__argv, const const char * *__envp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/exec.c (ffff80001038e5a4)
Location: fs/exec.c:1891
Inline: True
Inline callers:
  - fs/exec.c:__arm64_sys_execve
Direct callers:
  - init/main.c:run_init_process
  - kernel/umh.c:call_usermodehelper_exec_async
```
**Symbols:**

```
ffff80001038f0e0-ffff80001038f138: do_execve (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int do_execve(struct filename *filename, const const char * *__argv, const const char * *__envp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/exec.c (c057640c)
Location: fs/exec.c:1891
Inline: True
Inline callers:
  - fs/exec.c:__se_sys_execve
Direct callers:
  - init/main.c:run_init_process
  - kernel/umh.c:call_usermodehelper_exec_async
```
**Symbols:**

```
c0576194-c05761d8: do_execve (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
int do_execve(struct filename *filename, const const char * *__argv, const const char * *__envp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/exec.c (c000000000486a3c)
Location: fs/exec.c:1891
Inline: True
Inline callers:
  - fs/exec.c:__se_sys_execve
Direct callers:
  - init/main.c:run_init_process
  - kernel/umh.c:call_usermodehelper_exec_async
```
**Symbols:**

```
c000000000486c90-c000000000486cc8: do_execve (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
int do_execve(struct filename *filename, const const char * *__argv, const const char * *__envp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/exec.c (ffffffe00025f3ba)
Location: fs/exec.c:1891
Inline: True
Inline callers:
  - fs/exec.c:__se_sys_execve
Direct callers:
  - init/main.c:run_init_process
  - kernel/umh.c:call_usermodehelper_exec_async
```
**Symbols:**

```
ffffffe00025f1ae-ffffffe00025f1f0: do_execve (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
int do_execve(struct filename *filename, const const char * *__argv, const const char * *__envp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/exec.c (ffffffff812de889)
Location: fs/exec.c:1891
Inline: True
Inline callers:
  - fs/exec.c:__ia32_sys_execve
  - fs/exec.c:__x64_sys_execve
Direct callers:
  - init/main.c:run_init_process
  - kernel/umh.c:call_usermodehelper_exec_async
```
**Symbols:**

```
ffffffff812df260-ffffffff812df287: do_execve (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int do_execve(struct filename *filename, const const char * *__argv, const const char * *__envp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/exec.c (ffffffff812cfbb9)
Location: fs/exec.c:1891
Inline: True
Inline callers:
  - fs/exec.c:__ia32_sys_execve
  - fs/exec.c:__x64_sys_execve
Direct callers:
  - init/main.c:run_init_process
  - kernel/umh.c:call_usermodehelper_exec_async
```
**Symbols:**

```
ffffffff812cfea0-ffffffff812cfec7: do_execve (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int do_execve(struct filename *filename, const const char * *__argv, const const char * *__envp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/exec.c (ffffffff812dc699)
Location: fs/exec.c:1891
Inline: True
Inline callers:
  - fs/exec.c:__ia32_sys_execve
  - fs/exec.c:__x64_sys_execve
Direct callers:
  - init/main.c:run_init_process
  - kernel/umh.c:call_usermodehelper_exec_async
```
**Symbols:**

```
ffffffff812dd070-ffffffff812dd097: do_execve (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int do_execve(struct filename *filename, const const char * *__argv, const const char * *__envp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/exec.c (ffffffff812ed459)
Location: fs/exec.c:1891
Inline: True
Inline callers:
  - fs/exec.c:__ia32_sys_execve
  - fs/exec.c:__x64_sys_execve
Direct callers:
  - init/main.c:run_init_process
  - kernel/umh.c:call_usermodehelper_exec_async
```
**Symbols:**

```
ffffffff812ee000-ffffffff812ee027: do_execve (STB_GLOBAL)
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
