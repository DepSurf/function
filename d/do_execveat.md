# Function: <code>do_execveat</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
int do_execveat(int fd, struct filename *filename, const const char * *__argv, const const char * *__envp, int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/exec.c (ffffffff81214560)
Location: fs/exec.c:1649
Inline: True
Inline callers:
  - fs/exec.c:SyS_execveat
```
**Symbols:**

```
ffffffff81214560-ffffffff81214583: do_execveat (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
int do_execveat(int fd, struct filename *filename, const const char * *__argv, const const char * *__envp, int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/exec.c (ffffffff8123b5ab)
Location: fs/exec.c:1798
Inline: True
Inline callers:
  - fs/exec.c:SyS_execveat
```
**Symbols:**

```
ffffffff8123b2f0-ffffffff8123b313: do_execveat (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
int do_execveat(int fd, struct filename *filename, const const char * *__argv, const const char * *__envp, int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/exec.c (ffffffff8124e34b)
Location: fs/exec.c:1826
Inline: True
Inline callers:
  - fs/exec.c:SyS_execveat
```
**Symbols:**

```
ffffffff8124e0e0-ffffffff8124e103: do_execveat (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int do_execveat(int fd, struct filename *filename, const const char * *__argv, const const char * *__envp, int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/exec.c (ffffffff8125a2f4)
Location: fs/exec.c:1858
Inline: True
Inline callers:
  - fs/exec.c:SyS_execveat
```
**Symbols:**

```
ffffffff8125a0a0-ffffffff8125a0bd: do_execveat (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int do_execveat(int fd, struct filename *filename, const const char * *__argv, const const char * *__envp, int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/exec.c (ffffffff8127c5f4)
Location: fs/exec.c:1862
Inline: True
Inline callers:
  - fs/exec.c:SyS_execveat
```
**Symbols:**

```
ffffffff8127c390-ffffffff8127c3ad: do_execveat (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
int do_execveat(int fd, struct filename *filename, const const char * *__argv, const const char * *__envp, int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/exec.c (ffffffff812a3238)
Location: fs/exec.c:1897
Inline: True
Inline callers:
  - fs/exec.c:__ia32_sys_execveat
  - fs/exec.c:__x64_sys_execveat
```
**Symbols:**

```
ffffffff812a3440-ffffffff812a345f: do_execveat (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int do_execveat(int fd, struct filename *filename, const const char * *__argv, const const char * *__envp, int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/exec.c (ffffffff812b82d8)
Location: fs/exec.c:1897
Inline: True
Inline callers:
  - fs/exec.c:__ia32_sys_execveat
  - fs/exec.c:__x64_sys_execveat
```
**Symbols:**

```
ffffffff812b8590-ffffffff812b85af: do_execveat (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
int do_execveat(int fd, struct filename *filename, const const char * *__argv, const const char * *__envp, int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/exec.c (ffffffff812d4795)
Location: fs/exec.c:1900
Inline: True
Inline callers:
  - fs/exec.c:__ia32_sys_execveat
  - fs/exec.c:__x64_sys_execveat
```
**Symbols:**

```
ffffffff812d5120-ffffffff812d513f: do_execveat (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int do_execveat(int fd, struct filename *filename, const const char * *__argv, const const char * *__envp, int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/exec.c (ffffffff812e6315)
Location: fs/exec.c:1900
Inline: True
Inline callers:
  - fs/exec.c:__ia32_sys_execveat
  - fs/exec.c:__x64_sys_execveat
```
**Symbols:**

```
ffffffff812e6cb0-ffffffff812e6ccf: do_execveat (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int do_execveat(int fd, struct filename *filename, const const char * *__argv, const const char * *__envp, int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/exec.c (ffffffff8131e380)
Location: fs/exec.c:2008
Inline: False
Direct callers:
  - fs/exec.c:__ia32_sys_execveat
  - fs/exec.c:__x64_sys_execveat
```
**Symbols:**

```
ffffffff8131e380-ffffffff8131e3a4: do_execveat (STB_GLOBAL)
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
In fs/exec.c (ffffffff81328e47)
Location: fs/exec.c:1994
Inline: True
Inline callers:
  - fs/exec.c:__ia32_sys_execveat
  - fs/exec.c:__x64_sys_execveat
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
In fs/exec.c (ffffffff8132ecf4)
Location: fs/exec.c:1994
Inline: True
Inline callers:
  - fs/exec.c:__ia32_sys_execveat
  - fs/exec.c:__x64_sys_execveat
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
In fs/exec.c (ffffffff8137c4f7)
Location: fs/exec.c:1996
Inline: True
Inline callers:
  - fs/exec.c:__ia32_sys_execveat
  - fs/exec.c:__x64_sys_execveat
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
In fs/exec.c (ffffffff813fc887)
Location: fs/exec.c:2023
Inline: True
Inline callers:
  - fs/exec.c:__ia32_sys_execveat
  - fs/exec.c:__x64_sys_execveat
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
In fs/exec.c (ffffffff81486397)
Location: fs/exec.c:2033
Inline: True
Inline callers:
  - fs/exec.c:__ia32_sys_execveat
  - fs/exec.c:__x64_sys_execveat
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
In fs/exec.c (ffffffff814baf07)
Location: fs/exec.c:2040
Inline: True
Inline callers:
  - fs/exec.c:__ia32_sys_execveat
  - fs/exec.c:__x64_sys_execveat
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
In fs/exec.c (ffffffff814ed477)
Location: fs/exec.c:2061
Inline: True
Inline callers:
  - fs/exec.c:__ia32_sys_execveat
  - fs/exec.c:__x64_sys_execveat
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
int do_execveat(int fd, struct filename *filename, const const char * *__argv, const const char * *__envp, int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/exec.c (ffff80001038e614)
Location: fs/exec.c:1900
Inline: True
Inline callers:
  - fs/exec.c:__arm64_sys_execveat
```
**Symbols:**

```
ffff80001038f138-ffff80001038f1a0: do_execveat (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int do_execveat(int fd, struct filename *filename, const const char * *__argv, const const char * *__envp, int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/exec.c (c0576470)
Location: fs/exec.c:1900
Inline: True
Inline callers:
  - fs/exec.c:__se_sys_execveat
```
**Symbols:**

```
c05761d8-c0576208: do_execveat (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
int do_execveat(int fd, struct filename *filename, const const char * *__argv, const const char * *__envp, int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/exec.c (c000000000486ac0)
Location: fs/exec.c:1900
Inline: True
Inline callers:
  - fs/exec.c:__se_sys_execveat
```
**Symbols:**

```
c000000000486cd0-c000000000486d00: do_execveat (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
int do_execveat(int fd, struct filename *filename, const const char * *__argv, const const char * *__envp, int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/exec.c (ffffffe00025f41e)
Location: fs/exec.c:1900
Inline: True
Inline callers:
  - fs/exec.c:__se_sys_execveat
```
**Symbols:**

```
ffffffe00025f1f0-ffffffe00025f23c: do_execveat (STB_GLOBAL)
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
int do_execveat(int fd, struct filename *filename, const const char * *__argv, const const char * *__envp, int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/exec.c (ffffffff812de8f5)
Location: fs/exec.c:1900
Inline: True
Inline callers:
  - fs/exec.c:__ia32_sys_execveat
  - fs/exec.c:__x64_sys_execveat
```
**Symbols:**

```
ffffffff812df290-ffffffff812df2af: do_execveat (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int do_execveat(int fd, struct filename *filename, const const char * *__argv, const const char * *__envp, int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/exec.c (ffffffff812cfc25)
Location: fs/exec.c:1900
Inline: True
Inline callers:
  - fs/exec.c:__ia32_sys_execveat
  - fs/exec.c:__x64_sys_execveat
```
**Symbols:**

```
ffffffff812cfed0-ffffffff812cfeef: do_execveat (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int do_execveat(int fd, struct filename *filename, const const char * *__argv, const const char * *__envp, int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/exec.c (ffffffff812dc705)
Location: fs/exec.c:1900
Inline: True
Inline callers:
  - fs/exec.c:__ia32_sys_execveat
  - fs/exec.c:__x64_sys_execveat
```
**Symbols:**

```
ffffffff812dd0a0-ffffffff812dd0bf: do_execveat (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int do_execveat(int fd, struct filename *filename, const const char * *__argv, const const char * *__envp, int flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/exec.c (ffffffff812ed4c5)
Location: fs/exec.c:1900
Inline: True
Inline callers:
  - fs/exec.c:__ia32_sys_execveat
  - fs/exec.c:__x64_sys_execveat
```
**Symbols:**

```
ffffffff812ee030-ffffffff812ee04f: do_execveat (STB_GLOBAL)
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
