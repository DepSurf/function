# Function: <code>kill_something_info</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff8108f95a)
Location: kernel/signal.c:1374
Inline: True
Inline callers:
  - kernel/signal.c:SYSC_kill
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810929da)
Location: kernel/signal.c:1374
Inline: True
Inline callers:
  - kernel/signal.c:SYSC_kill
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff8109796a)
Location: kernel/signal.c:1380
Inline: True
Inline callers:
  - kernel/signal.c:SYSC_kill
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff81094c8d)
Location: kernel/signal.c:1398
Inline: True
Inline callers:
  - kernel/signal.c:SYSC_kill
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff8109bb2e)
Location: kernel/signal.c:1399
Inline: True
Inline callers:
  - kernel/signal.c:SYSC_kill
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff8109fbab)
Location: kernel/signal.c:1397
Inline: True
Inline callers:
  - kernel/signal.c:__do_sys_kill
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int kill_something_info(int sig, struct kernel_siginfo *info, pid_t pid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810a7de0)
Location: kernel/signal.c:1482
Inline: False
Direct callers:
  - kernel/signal.c:__ia32_sys_kill
  - kernel/signal.c:__x64_sys_kill
```
**Symbols:**

```
ffffffff810a7de0-ffffffff810a7f2d: kill_something_info (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int kill_something_info(int sig, struct kernel_siginfo *info, pid_t pid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810ada90)
Location: kernel/signal.c:1551
Inline: False
Direct callers:
  - kernel/signal.c:__ia32_sys_kill
  - kernel/signal.c:__x64_sys_kill
```
**Symbols:**

```
ffffffff810ada90-ffffffff810adbfa: kill_something_info (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int kill_something_info(int sig, struct kernel_siginfo *info, pid_t pid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810b40b0)
Location: kernel/signal.c:1556
Inline: False
Direct callers:
  - kernel/signal.c:__ia32_sys_kill
  - kernel/signal.c:__x64_sys_kill
```
**Symbols:**

```
ffffffff810b40b0-ffffffff810b421a: kill_something_info (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int kill_something_info(int sig, struct kernel_siginfo *info, pid_t pid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810bd390)
Location: kernel/signal.c:1556
Inline: False
Direct callers:
  - kernel/signal.c:__ia32_sys_kill
  - kernel/signal.c:__x64_sys_kill
```
**Symbols:**

```
ffffffff810bd390-ffffffff810bd511: kill_something_info (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int kill_something_info(int sig, struct kernel_siginfo *info, pid_t pid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810b8690)
Location: kernel/signal.c:1557
Inline: False
Direct callers:
  - kernel/signal.c:__ia32_sys_kill
  - kernel/signal.c:__x64_sys_kill
```
**Symbols:**

```
ffffffff810b8690-ffffffff810b8827: kill_something_info (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int kill_something_info(int sig, struct kernel_siginfo *info, pid_t pid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810b9c10)
Location: kernel/signal.c:1559
Inline: False
Direct callers:
  - kernel/signal.c:__ia32_sys_kill
  - kernel/signal.c:__x64_sys_kill
```
**Symbols:**

```
ffffffff810b9c10-ffffffff810b9da7: kill_something_info (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int kill_something_info(int sig, struct kernel_siginfo *info, pid_t pid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810cc220)
Location: kernel/signal.c:1585
Inline: False
Direct callers:
  - kernel/signal.c:__ia32_sys_kill
  - kernel/signal.c:__x64_sys_kill
```
**Symbols:**

```
ffffffff810cc220-ffffffff810cc3b7: kill_something_info (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int kill_something_info(int sig, struct kernel_siginfo *info, pid_t pid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810e3450)
Location: kernel/signal.c:1586
Inline: False
Direct callers:
  - kernel/signal.c:__ia32_sys_kill
  - kernel/signal.c:__x64_sys_kill
```
**Symbols:**

```
ffffffff810e3450-ffffffff810e35fc: kill_something_info (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int kill_something_info(int sig, struct kernel_siginfo *info, pid_t pid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff811039c0)
Location: kernel/signal.c:1587
Inline: False
Direct callers:
  - kernel/signal.c:__ia32_sys_kill
  - kernel/signal.c:__x64_sys_kill
```
**Symbols:**

```
ffffffff811039c0-ffffffff81103b6c: kill_something_info (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int kill_something_info(int sig, struct kernel_siginfo *info, pid_t pid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff8110fc00)
Location: kernel/signal.c:1593
Inline: False
Direct callers:
  - kernel/signal.c:__ia32_sys_kill
  - kernel/signal.c:__x64_sys_kill
```
**Symbols:**

```
ffffffff8110fc00-ffffffff8110fdac: kill_something_info (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int kill_something_info(int sig, struct kernel_siginfo *info, pid_t pid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff81119570)
Location: kernel/signal.c:1599
Inline: False
Direct callers:
  - kernel/signal.c:__ia32_sys_kill
  - kernel/signal.c:__x64_sys_kill
```
**Symbols:**

```
ffffffff81119570-ffffffff8111971c: kill_something_info (STB_LOCAL)
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
In kernel/signal.c (ffff800010110200)
Location: kernel/signal.c:1556
Inline: True
Inline callers:
  - kernel/signal.c:__arm64_sys_kill
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
In kernel/signal.c (c036960c)
Location: kernel/signal.c:1556
Inline: True
Inline callers:
  - kernel/signal.c:__se_sys_kill
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
In kernel/signal.c (c000000000157998)
Location: kernel/signal.c:1556
Inline: True
Inline callers:
  - kernel/signal.c:__se_sys_kill
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
In kernel/signal.c (ffffffe0000d1626)
Location: kernel/signal.c:1556
Inline: True
Inline callers:
  - kernel/signal.c:__se_sys_kill
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
int kill_something_info(int sig, struct kernel_siginfo *info, pid_t pid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810ae420)
Location: kernel/signal.c:1556
Inline: False
Direct callers:
  - kernel/signal.c:__ia32_sys_kill
  - kernel/signal.c:__x64_sys_kill
```
**Symbols:**

```
ffffffff810ae420-ffffffff810ae58a: kill_something_info (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int kill_something_info(int sig, struct kernel_siginfo *info, pid_t pid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff8109cd70)
Location: kernel/signal.c:1556
Inline: False
Direct callers:
  - kernel/signal.c:__ia32_sys_kill
  - kernel/signal.c:__x64_sys_kill
```
**Symbols:**

```
ffffffff8109cd70-ffffffff8109ceda: kill_something_info (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int kill_something_info(int sig, struct kernel_siginfo *info, pid_t pid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810ad980)
Location: kernel/signal.c:1556
Inline: False
Direct callers:
  - kernel/signal.c:__ia32_sys_kill
  - kernel/signal.c:__x64_sys_kill
```
**Symbols:**

```
ffffffff810ad980-ffffffff810adaea: kill_something_info (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int kill_something_info(int sig, struct kernel_siginfo *info, pid_t pid);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810b5bd0)
Location: kernel/signal.c:1556
Inline: False
Direct callers:
  - kernel/signal.c:__ia32_sys_kill
  - kernel/signal.c:__x64_sys_kill
```
**Symbols:**

```
ffffffff810b5bd0-ffffffff810b5d44: kill_something_info (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
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
<b>Arch</b>
<ul>
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
