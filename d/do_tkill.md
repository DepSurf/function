# Function: <code>do_tkill</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int do_tkill(pid_t tgid, pid_t pid, int sig);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff8108f3d0)
Location: kernel/signal.c:2890
Inline: False
Direct callers:
  - kernel/signal.c:SyS_tgkill
  - kernel/signal.c:SyS_tkill
```
**Symbols:**

```
ffffffff8108f3d0-ffffffff8108f493: do_tkill (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int do_tkill(pid_t tgid, pid_t pid, int sig);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff81092440)
Location: kernel/signal.c:2890
Inline: False
Direct callers:
  - kernel/signal.c:SyS_tkill
  - kernel/signal.c:SyS_tgkill
```
**Symbols:**

```
ffffffff81092440-ffffffff81092503: do_tkill (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int do_tkill(pid_t tgid, pid_t pid, int sig);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810973d0)
Location: kernel/signal.c:2903
Inline: False
Direct callers:
  - kernel/signal.c:SyS_tkill
  - kernel/signal.c:SyS_tgkill
```
**Symbols:**

```
ffffffff810973d0-ffffffff81097493: do_tkill (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int do_tkill(pid_t tgid, pid_t pid, int sig);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810946d0)
Location: kernel/signal.c:2958
Inline: False
Direct callers:
  - kernel/signal.c:SyS_tkill
  - kernel/signal.c:SyS_tgkill
```
**Symbols:**

```
ffffffff810946d0-ffffffff810947a2: do_tkill (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int do_tkill(pid_t tgid, pid_t pid, int sig);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff8109b570)
Location: kernel/signal.c:2979
Inline: False
Direct callers:
  - kernel/signal.c:SyS_tkill
  - kernel/signal.c:SyS_tgkill
```
**Symbols:**

```
ffffffff8109b570-ffffffff8109b642: do_tkill (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int do_tkill(pid_t tgid, pid_t pid, int sig);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff8109f560)
Location: kernel/signal.c:3211
Inline: False
Direct callers:
  - kernel/signal.c:__ia32_sys_tkill
  - kernel/signal.c:__x64_sys_tkill
  - kernel/signal.c:__ia32_sys_tgkill
  - kernel/signal.c:__x64_sys_tgkill
```
**Symbols:**

```
ffffffff8109f560-ffffffff8109f632: do_tkill (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int do_tkill(pid_t tgid, pid_t pid, int sig);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810a7810)
Location: kernel/signal.c:3539
Inline: False
Direct callers:
  - kernel/signal.c:__ia32_sys_tkill
  - kernel/signal.c:__x64_sys_tkill
  - kernel/signal.c:__ia32_sys_tgkill
  - kernel/signal.c:__x64_sys_tgkill
```
**Symbols:**

```
ffffffff810a7810-ffffffff810a78c7: do_tkill (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int do_tkill(pid_t tgid, pid_t pid, int sig);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810adfb0)
Location: kernel/signal.c:3787
Inline: False
Direct callers:
  - kernel/signal.c:__ia32_sys_tkill
  - kernel/signal.c:__x64_sys_tkill
  - kernel/signal.c:__ia32_sys_tgkill
  - kernel/signal.c:__x64_sys_tgkill
```
**Symbols:**

```
ffffffff810adfb0-ffffffff810ae07c: do_tkill (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int do_tkill(pid_t tgid, pid_t pid, int sig);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810b45c0)
Location: kernel/signal.c:3795
Inline: False
Direct callers:
  - kernel/signal.c:__ia32_sys_tkill
  - kernel/signal.c:__x64_sys_tkill
  - kernel/signal.c:__ia32_sys_tgkill
  - kernel/signal.c:__x64_sys_tgkill
```
**Symbols:**

```
ffffffff810b45c0-ffffffff810b468c: do_tkill (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int do_tkill(pid_t tgid, pid_t pid, int sig);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810bcaf0)
Location: kernel/signal.c:3813
Inline: False
Direct callers:
  - kernel/signal.c:__ia32_sys_tkill
  - kernel/signal.c:__x64_sys_tkill
  - kernel/signal.c:__ia32_sys_tgkill
  - kernel/signal.c:__x64_sys_tgkill
```
**Symbols:**

```
ffffffff810bcaf0-ffffffff810bcb9f: do_tkill (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int do_tkill(pid_t tgid, pid_t pid, int sig);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810b7e10)
Location: kernel/signal.c:3834
Inline: False
Direct callers:
  - kernel/signal.c:__ia32_sys_tkill
  - kernel/signal.c:__x64_sys_tkill
  - kernel/signal.c:__ia32_sys_tgkill
  - kernel/signal.c:__x64_sys_tgkill
```
**Symbols:**

```
ffffffff810b7e10-ffffffff810b7ebf: do_tkill (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int do_tkill(pid_t tgid, pid_t pid, int sig);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810b9370)
Location: kernel/signal.c:3856
Inline: False
Direct callers:
  - kernel/signal.c:__ia32_sys_tkill
  - kernel/signal.c:__x64_sys_tkill
  - kernel/signal.c:__ia32_sys_tgkill
  - kernel/signal.c:__x64_sys_tgkill
```
**Symbols:**

```
ffffffff810b9370-ffffffff810b941f: do_tkill (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int do_tkill(pid_t tgid, pid_t pid, int sig);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810cb980)
Location: kernel/signal.c:3944
Inline: False
Direct callers:
  - kernel/signal.c:__ia32_sys_tkill
  - kernel/signal.c:__x64_sys_tkill
  - kernel/signal.c:__ia32_sys_tgkill
  - kernel/signal.c:__x64_sys_tgkill
```
**Symbols:**

```
ffffffff810cb980-ffffffff810cba2f: do_tkill (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int do_tkill(pid_t tgid, pid_t pid, int sig);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810e2a50)
Location: kernel/signal.c:3927
Inline: False
Direct callers:
  - kernel/signal.c:__ia32_sys_tkill
  - kernel/signal.c:__x64_sys_tkill
  - kernel/signal.c:__ia32_sys_tgkill
  - kernel/signal.c:__x64_sys_tgkill
```
**Symbols:**

```
ffffffff810e2a50-ffffffff810e2b13: do_tkill (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int do_tkill(pid_t tgid, pid_t pid, int sig);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff81102eb0)
Location: kernel/signal.c:3929
Inline: False
Direct callers:
  - kernel/signal.c:__ia32_sys_tkill
  - kernel/signal.c:__x64_sys_tkill
  - kernel/signal.c:__ia32_sys_tgkill
  - kernel/signal.c:__x64_sys_tgkill
```
**Symbols:**

```
ffffffff81102eb0-ffffffff81102f73: do_tkill (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int do_tkill(pid_t tgid, pid_t pid, int sig);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff8110f0f0)
Location: kernel/signal.c:3953
Inline: False
Direct callers:
  - kernel/signal.c:__ia32_sys_tkill
  - kernel/signal.c:__x64_sys_tkill
  - kernel/signal.c:__ia32_sys_tgkill
  - kernel/signal.c:__x64_sys_tgkill
```
**Symbols:**

```
ffffffff8110f0f0-ffffffff8110f1b3: do_tkill (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int do_tkill(pid_t tgid, pid_t pid, int sig);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff81118a70)
Location: kernel/signal.c:3964
Inline: False
Direct callers:
  - kernel/signal.c:__ia32_sys_tkill
  - kernel/signal.c:__x64_sys_tkill
  - kernel/signal.c:__ia32_sys_tgkill
  - kernel/signal.c:__x64_sys_tgkill
```
**Symbols:**

```
ffffffff81118a70-ffffffff81118b33: do_tkill (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
int do_tkill(pid_t tgid, pid_t pid, int sig);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffff800010110698)
Location: kernel/signal.c:3795
Inline: False
Direct callers:
  - kernel/signal.c:__arm64_sys_tkill
  - kernel/signal.c:__arm64_sys_tgkill
```
**Symbols:**

```
ffff800010110698-ffff80001011075c: do_tkill (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int do_tkill(pid_t tgid, pid_t pid, int sig);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (c0368034)
Location: kernel/signal.c:3795
Inline: False
Direct callers:
  - kernel/signal.c:__se_sys_tkill
  - kernel/signal.c:__se_sys_tgkill
```
**Symbols:**

```
c0368034-c0368114: do_tkill (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int do_tkill(pid_t tgid, pid_t pid, int sig);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (c000000000157e50)
Location: kernel/signal.c:3795
Inline: False
Direct callers:
  - kernel/signal.c:__se_sys_tkill
  - kernel/signal.c:__se_sys_tgkill
```
**Symbols:**

```
c000000000157e50-c000000000157f44: do_tkill (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int do_tkill(pid_t tgid, pid_t pid, int sig);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffe0000d0504)
Location: kernel/signal.c:3795
Inline: False
Direct callers:
  - kernel/signal.c:__se_sys_tkill
  - kernel/signal.c:__se_sys_tgkill
```
**Symbols:**

```
ffffffe0000d0504-ffffffe0000d058c: do_tkill (STB_LOCAL)
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
int do_tkill(pid_t tgid, pid_t pid, int sig);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810ae930)
Location: kernel/signal.c:3795
Inline: False
Direct callers:
  - kernel/signal.c:__ia32_sys_tkill
  - kernel/signal.c:__x64_sys_tkill
  - kernel/signal.c:__ia32_sys_tgkill
  - kernel/signal.c:__x64_sys_tgkill
```
**Symbols:**

```
ffffffff810ae930-ffffffff810ae9fc: do_tkill (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int do_tkill(pid_t tgid, pid_t pid, int sig);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff8109d280)
Location: kernel/signal.c:3795
Inline: False
Direct callers:
  - kernel/signal.c:__ia32_sys_tkill
  - kernel/signal.c:__x64_sys_tkill
  - kernel/signal.c:__ia32_sys_tgkill
  - kernel/signal.c:__x64_sys_tgkill
```
**Symbols:**

```
ffffffff8109d280-ffffffff8109d34c: do_tkill (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int do_tkill(pid_t tgid, pid_t pid, int sig);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810ade90)
Location: kernel/signal.c:3795
Inline: False
Direct callers:
  - kernel/signal.c:__ia32_sys_tkill
  - kernel/signal.c:__x64_sys_tkill
  - kernel/signal.c:__ia32_sys_tgkill
  - kernel/signal.c:__x64_sys_tgkill
```
**Symbols:**

```
ffffffff810ade90-ffffffff810adf5c: do_tkill (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int do_tkill(pid_t tgid, pid_t pid, int sig);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/signal.c (ffffffff810b6100)
Location: kernel/signal.c:3795
Inline: False
Direct callers:
  - kernel/signal.c:__ia32_sys_tkill
  - kernel/signal.c:__x64_sys_tkill
  - kernel/signal.c:__ia32_sys_tgkill
  - kernel/signal.c:__x64_sys_tgkill
```
**Symbols:**

```
ffffffff810b6100-ffffffff810b61cc: do_tkill (STB_LOCAL)
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
