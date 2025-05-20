# Function: <code>seccomp_init_siginfo</code>

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
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void seccomp_init_siginfo(siginfo_t *info, int syscall, int reason);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/seccomp.c (ffffffff8114fa00)
Location: kernel/seccomp.c:505
Inline: False
Direct callers:
  - kernel/seccomp.c:__seccomp_filter
  - kernel/seccomp.c:seccomp_send_sigsys
```
**Symbols:**

```
ffffffff8114fa00-ffffffff8114fa84: seccomp_init_siginfo (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void seccomp_init_siginfo(siginfo_t *info, int syscall, int reason);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/seccomp.c (ffffffff8115bfb0)
Location: kernel/seccomp.c:516
Inline: False
Direct callers:
  - kernel/seccomp.c:__seccomp_filter
  - kernel/seccomp.c:__seccomp_filter
  - kernel/seccomp.c:seccomp_send_sigsys
```
**Symbols:**

```
ffffffff8115bfb0-ffffffff8115c031: seccomp_init_siginfo (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void seccomp_init_siginfo(siginfo_t *info, int syscall, int reason);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/seccomp.c (ffffffff8116abc0)
Location: kernel/seccomp.c:525
Inline: False
Direct callers:
  - kernel/seccomp.c:__seccomp_filter
  - kernel/seccomp.c:__seccomp_filter
  - kernel/seccomp.c:seccomp_send_sigsys
```
**Symbols:**

```
ffffffff8116abc0-ffffffff8116ac41: seccomp_init_siginfo (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void seccomp_init_siginfo(kernel_siginfo_t *info, int syscall, int reason);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/seccomp.c (ffffffff81177d00)
Location: kernel/seccomp.c:585
Inline: False
Direct callers:
  - kernel/seccomp.c:__seccomp_filter
  - kernel/seccomp.c:__seccomp_filter
  - kernel/seccomp.c:__seccomp_filter
```
**Symbols:**

```
ffffffff81177d00-ffffffff81177d7e: seccomp_init_siginfo (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void seccomp_init_siginfo(kernel_siginfo_t *info, int syscall, int reason);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/seccomp.c (ffffffff81184aa0)
Location: kernel/seccomp.c:590
Inline: False
Direct callers:
  - kernel/seccomp.c:__seccomp_filter
  - kernel/seccomp.c:__seccomp_filter
  - kernel/seccomp.c:__seccomp_filter
```
**Symbols:**

```
ffffffff81184aa0-ffffffff81184b1f: seccomp_init_siginfo (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void seccomp_init_siginfo(kernel_siginfo_t *info, int syscall, int reason);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/seccomp.c (ffffffff81190920)
Location: kernel/seccomp.c:591
Inline: False
Direct callers:
  - kernel/seccomp.c:__seccomp_filter
  - kernel/seccomp.c:__seccomp_filter
  - kernel/seccomp.c:__seccomp_filter
```
**Symbols:**

```
ffffffff81190920-ffffffff8119099f: seccomp_init_siginfo (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void seccomp_init_siginfo(kernel_siginfo_t *info, int syscall, int reason);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/seccomp.c (ffffffff811a67c4)
Location: kernel/seccomp.c:601
Inline: True
Inline callers:
  - kernel/seccomp.c:__seccomp_filter
Direct callers:
  - kernel/seccomp.c:__seccomp_filter
  - kernel/seccomp.c:__seccomp_filter
```
**Symbols:**

```
ffffffff811a5650-ffffffff811a56b0: seccomp_init_siginfo (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void seccomp_init_siginfo(kernel_siginfo_t *info, int syscall, int reason);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/seccomp.c (ffffffff811a3dd4)
Location: kernel/seccomp.c:920
Inline: True
Inline callers:
  - kernel/seccomp.c:__seccomp_filter
Direct callers:
  - kernel/seccomp.c:__seccomp_filter
  - kernel/seccomp.c:__seccomp_filter
```
**Symbols:**

```
ffffffff811a2600-ffffffff811a2660: seccomp_init_siginfo (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void seccomp_init_siginfo(kernel_siginfo_t *info, int syscall, int reason);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/seccomp.c (ffffffff811a47a1)
Location: kernel/seccomp.c:925
Inline: True
Inline callers:
  - kernel/seccomp.c:__seccomp_filter
Direct callers:
  - kernel/seccomp.c:__seccomp_filter
  - kernel/seccomp.c:__seccomp_filter
```
**Symbols:**

```
ffffffff811a3220-ffffffff811a3280: seccomp_init_siginfo (STB_LOCAL)
```
</details>
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
void seccomp_init_siginfo(kernel_siginfo_t *info, int syscall, int reason);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/seccomp.c (ffff800010207fd0)
Location: kernel/seccomp.c:591
Inline: False
Direct callers:
  - kernel/seccomp.c:__seccomp_filter
  - kernel/seccomp.c:__seccomp_filter
  - kernel/seccomp.c:__seccomp_filter
```
**Symbols:**

```
ffff800010207fd0-ffff800010208054: seccomp_init_siginfo (STB_LOCAL)
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
In kernel/seccomp.c (c04482a8)
Location: kernel/seccomp.c:591
Inline: True
Inline callers:
  - kernel/seccomp.c:__seccomp_filter
  - kernel/seccomp.c:__seccomp_filter
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void seccomp_init_siginfo(kernel_siginfo_t *info, int syscall, int reason);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/seccomp.c (c000000000284bc0)
Location: kernel/seccomp.c:591
Inline: False
Direct callers:
  - kernel/seccomp.c:__seccomp_filter
  - kernel/seccomp.c:__seccomp_filter
  - kernel/seccomp.c:__seccomp_filter
```
**Symbols:**

```
c000000000284bc0-c000000000284c58: seccomp_init_siginfo (STB_LOCAL)
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
In kernel/seccomp.c (ffffffe00016b58c)
Location: kernel/seccomp.c:591
Inline: True
Inline callers:
  - kernel/seccomp.c:__seccomp_filter
  - kernel/seccomp.c:__seccomp_filter
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
void seccomp_init_siginfo(kernel_siginfo_t *info, int syscall, int reason);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/seccomp.c (ffffffff81188f40)
Location: kernel/seccomp.c:591
Inline: False
Direct callers:
  - kernel/seccomp.c:__seccomp_filter
  - kernel/seccomp.c:__seccomp_filter
  - kernel/seccomp.c:__seccomp_filter
```
**Symbols:**

```
ffffffff81188f40-ffffffff81188fbf: seccomp_init_siginfo (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void seccomp_init_siginfo(kernel_siginfo_t *info, int syscall, int reason);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/seccomp.c (ffffffff8117c080)
Location: kernel/seccomp.c:591
Inline: False
Direct callers:
  - kernel/seccomp.c:__seccomp_filter
  - kernel/seccomp.c:__seccomp_filter
  - kernel/seccomp.c:__seccomp_filter
```
**Symbols:**

```
ffffffff8117c080-ffffffff8117c0ff: seccomp_init_siginfo (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void seccomp_init_siginfo(kernel_siginfo_t *info, int syscall, int reason);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/seccomp.c (ffffffff81186d10)
Location: kernel/seccomp.c:591
Inline: False
Direct callers:
  - kernel/seccomp.c:__seccomp_filter
  - kernel/seccomp.c:__seccomp_filter
  - kernel/seccomp.c:__seccomp_filter
```
**Symbols:**

```
ffffffff81186d10-ffffffff81186d8f: seccomp_init_siginfo (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void seccomp_init_siginfo(kernel_siginfo_t *info, int syscall, int reason);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/seccomp.c (ffffffff81194660)
Location: kernel/seccomp.c:591
Inline: False
Direct callers:
  - kernel/seccomp.c:__seccomp_filter
  - kernel/seccomp.c:__seccomp_filter
  - kernel/seccomp.c:__seccomp_filter
```
**Symbols:**

```
ffffffff81194660-ffffffff811946df: seccomp_init_siginfo (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>4.18</code> and <code>5.0</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>siginfo_t *info</code> ➡️ <code>kernel_siginfo_t *info</code>
</li>
</ul>
</details>
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
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
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
