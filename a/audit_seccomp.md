# Function: <code>audit_seccomp</code>

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
In kernel/seccomp.c (ffffffff8113be26)
Location: include/linux/audit.h:213
Inline: True
Inline callers:
  - kernel/seccomp.c:seccomp_phase2
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
In kernel/seccomp.c (ffffffff8114450a)
Location: include/linux/audit.h:316
Inline: True
Inline callers:
  - kernel/seccomp.c:__secure_computing
  - kernel/seccomp.c:__seccomp_filter
  - kernel/seccomp.c:__seccomp_filter
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
In kernel/seccomp.c (ffffffff8114e3a6)
Location: include/linux/audit.h:316
Inline: True
Inline callers:
  - kernel/seccomp.c:__secure_computing
  - kernel/seccomp.c:__seccomp_filter
  - kernel/seccomp.c:__seccomp_filter
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
In kernel/seccomp.c (ffffffff81150a4f)
Location: include/linux/audit.h:315
Inline: True
Inline callers:
  - kernel/seccomp.c:__secure_computing
  - kernel/seccomp.c:__seccomp_filter
  - kernel/seccomp.c:__seccomp_filter
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
In kernel/seccomp.c (ffffffff8115d245)
Location: include/linux/audit.h:307
Inline: True
Inline callers:
  - kernel/seccomp.c:__secure_computing
  - kernel/seccomp.c:__seccomp_filter
  - kernel/seccomp.c:__seccomp_filter
  - kernel/seccomp.c:__seccomp_filter
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void audit_seccomp(long unsigned int syscall, long int signr, int code);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/auditsc.c (ffffffff81158570)
Location: kernel/auditsc.c:2489
Inline: False
Direct callers:
  - kernel/seccomp.c:__secure_computing
  - kernel/seccomp.c:__seccomp_filter
  - kernel/seccomp.c:__seccomp_filter
  - kernel/seccomp.c:__seccomp_filter
```
**Symbols:**

```
ffffffff81158570-ffffffff8115862a: audit_seccomp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void audit_seccomp(long unsigned int syscall, long int signr, int code);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/auditsc.c (ffffffff81165580)
Location: kernel/auditsc.c:2474
Inline: False
Direct callers:
  - kernel/seccomp.c:__secure_computing
  - kernel/seccomp.c:__seccomp_filter
  - kernel/seccomp.c:__seccomp_filter
  - kernel/seccomp.c:__seccomp_filter
```
**Symbols:**

```
ffffffff81165580-ffffffff81165644: audit_seccomp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void audit_seccomp(long unsigned int syscall, long int signr, int code);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/auditsc.c (ffffffff811720e0)
Location: kernel/auditsc.c:2607
Inline: False
Direct callers:
  - kernel/seccomp.c:__secure_computing
  - kernel/seccomp.c:__seccomp_filter
  - kernel/seccomp.c:__seccomp_filter
  - kernel/seccomp.c:__seccomp_filter
```
**Symbols:**

```
ffffffff811720e0-ffffffff811721a4: audit_seccomp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void audit_seccomp(long unsigned int syscall, long int signr, int code);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/auditsc.c (ffffffff8117df90)
Location: kernel/auditsc.c:2607
Inline: False
Direct callers:
  - kernel/seccomp.c:__secure_computing
  - kernel/seccomp.c:__seccomp_filter
  - kernel/seccomp.c:__seccomp_filter
  - kernel/seccomp.c:__seccomp_filter
```
**Symbols:**

```
ffffffff8117df90-ffffffff8117e054: audit_seccomp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void audit_seccomp(long unsigned int syscall, long int signr, int code);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/auditsc.c (ffffffff81191380)
Location: kernel/auditsc.c:2681
Inline: False
Direct callers:
  - kernel/seccomp.c:__secure_computing
  - kernel/seccomp.c:__seccomp_filter
  - kernel/seccomp.c:__seccomp_filter
  - kernel/seccomp.c:__seccomp_filter
```
**Symbols:**

```
ffffffff81191380-ffffffff81191444: audit_seccomp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void audit_seccomp(long unsigned int syscall, long int signr, int code);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/auditsc.c (ffffffff8118e5a0)
Location: kernel/auditsc.c:2698
Inline: False
Direct callers:
  - kernel/seccomp.c:__secure_computing
  - kernel/seccomp.c:__seccomp_filter
  - kernel/seccomp.c:__seccomp_filter
  - kernel/seccomp.c:__seccomp_filter
```
**Symbols:**

```
ffffffff8118e5a0-ffffffff8118e664: audit_seccomp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void audit_seccomp(long unsigned int syscall, long int signr, int code);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/auditsc.c (ffffffff8118f520)
Location: kernel/auditsc.c:2696
Inline: False
Direct callers:
  - kernel/seccomp.c:__secure_computing
  - kernel/seccomp.c:__seccomp_filter
  - kernel/seccomp.c:__seccomp_filter
  - kernel/seccomp.c:__seccomp_filter
```
**Symbols:**

```
ffffffff8118f520-ffffffff8118f5e4: audit_seccomp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void audit_seccomp(long unsigned int syscall, long int signr, int code);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/auditsc.c (ffffffff811b8400)
Location: kernel/auditsc.c:2714
Inline: False
Direct callers:
  - kernel/seccomp.c:__secure_computing
  - kernel/seccomp.c:__seccomp_filter
  - kernel/seccomp.c:__seccomp_filter
  - kernel/seccomp.c:__seccomp_filter
```
**Symbols:**

```
ffffffff811b8400-ffffffff811b84c4: audit_seccomp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void audit_seccomp(long unsigned int syscall, long int signr, int code);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/auditsc.c (ffffffff811eb2d0)
Location: kernel/auditsc.c:2989
Inline: False
Direct callers:
  - kernel/seccomp.c:__secure_computing
  - kernel/seccomp.c:__seccomp_filter
  - kernel/seccomp.c:__seccomp_filter
  - kernel/seccomp.c:__seccomp_filter
  - kernel/seccomp.c:__seccomp_filter
```
**Symbols:**

```
ffffffff811eb2d0-ffffffff811eb38c: audit_seccomp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void audit_seccomp(long unsigned int syscall, long int signr, int code);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/auditsc.c (ffffffff81231670)
Location: kernel/auditsc.c:2967
Inline: False
Direct callers:
  - kernel/seccomp.c:__secure_computing
  - kernel/seccomp.c:__seccomp_filter
  - kernel/seccomp.c:__seccomp_filter
  - kernel/seccomp.c:__seccomp_filter
  - kernel/seccomp.c:__seccomp_filter
```
**Symbols:**

```
ffffffff81231670-ffffffff8123172c: audit_seccomp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void audit_seccomp(long unsigned int syscall, long int signr, int code);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/auditsc.c (ffffffff81248300)
Location: kernel/auditsc.c:2977
Inline: False
Direct callers:
  - kernel/seccomp.c:__secure_computing
  - kernel/seccomp.c:__seccomp_filter
  - kernel/seccomp.c:__seccomp_filter
  - kernel/seccomp.c:__seccomp_filter
  - kernel/seccomp.c:__seccomp_filter
```
**Symbols:**

```
ffffffff81248300-ffffffff812483bc: audit_seccomp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void audit_seccomp(long unsigned int syscall, long int signr, int code);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/auditsc.c (ffffffff81262160)
Location: kernel/auditsc.c:2967
Inline: False
Direct callers:
  - kernel/seccomp.c:__secure_computing
  - kernel/seccomp.c:__seccomp_filter
  - kernel/seccomp.c:__seccomp_filter
  - kernel/seccomp.c:__seccomp_filter
  - kernel/seccomp.c:__seccomp_filter
```
**Symbols:**

```
ffffffff81262160-ffffffff8126221c: audit_seccomp (STB_GLOBAL)
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
void audit_seccomp(long unsigned int syscall, long int signr, int code);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/auditsc.c (ffff8000101f2e10)
Location: kernel/auditsc.c:2607
Inline: False
Direct callers:
  - kernel/seccomp.c:__secure_computing
  - kernel/seccomp.c:__seccomp_filter
  - kernel/seccomp.c:__seccomp_filter
  - kernel/seccomp.c:__seccomp_filter
  - kernel/seccomp.c:__seccomp_filter
```
**Symbols:**

```
ffff8000101f2e10-ffff8000101f2ebc: audit_seccomp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void audit_seccomp(long unsigned int syscall, long int signr, int code);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/auditsc.c (c0433390)
Location: kernel/auditsc.c:2607
Inline: False
Direct callers:
  - kernel/seccomp.c:__secure_computing
  - kernel/seccomp.c:__seccomp_filter
  - kernel/seccomp.c:__seccomp_filter
  - kernel/seccomp.c:__seccomp_filter
  - kernel/seccomp.c:__seccomp_filter
```
**Symbols:**

```
c0433390-c0433434: audit_seccomp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void audit_seccomp(long unsigned int syscall, long int signr, int code);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/auditsc.c (c0000000002677a0)
Location: kernel/auditsc.c:2607
Inline: False
Direct callers:
  - kernel/seccomp.c:__secure_computing
  - kernel/seccomp.c:__seccomp_filter
  - kernel/seccomp.c:__seccomp_filter
  - kernel/seccomp.c:__seccomp_filter
  - kernel/seccomp.c:__seccomp_filter
```
**Symbols:**

```
c0000000002677a0-c00000000026789c: audit_seccomp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void audit_seccomp(long unsigned int syscall, long int signr, int code);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/auditsc.c (ffffffe000166408)
Location: kernel/auditsc.c:2607
Inline: False
Direct callers:
  - kernel/seccomp.c:__secure_computing
  - kernel/seccomp.c:__seccomp_filter
  - kernel/seccomp.c:__seccomp_filter
  - kernel/seccomp.c:__seccomp_filter
  - kernel/seccomp.c:__seccomp_filter
  - kernel/seccomp.c:__seccomp_filter
```
**Symbols:**

```
ffffffe000166408-ffffffe000166492: audit_seccomp (STB_GLOBAL)
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
void audit_seccomp(long unsigned int syscall, long int signr, int code);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/auditsc.c (ffffffff811765b0)
Location: kernel/auditsc.c:2607
Inline: False
Direct callers:
  - kernel/seccomp.c:__secure_computing
  - kernel/seccomp.c:__seccomp_filter
  - kernel/seccomp.c:__seccomp_filter
  - kernel/seccomp.c:__seccomp_filter
```
**Symbols:**

```
ffffffff811765b0-ffffffff81176674: audit_seccomp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void audit_seccomp(long unsigned int syscall, long int signr, int code);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/auditsc.c (ffffffff81169750)
Location: kernel/auditsc.c:2607
Inline: False
Direct callers:
  - kernel/seccomp.c:__secure_computing
  - kernel/seccomp.c:__seccomp_filter
  - kernel/seccomp.c:__seccomp_filter
  - kernel/seccomp.c:__seccomp_filter
```
**Symbols:**

```
ffffffff81169750-ffffffff81169814: audit_seccomp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void audit_seccomp(long unsigned int syscall, long int signr, int code);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/auditsc.c (ffffffff81174380)
Location: kernel/auditsc.c:2607
Inline: False
Direct callers:
  - kernel/seccomp.c:__secure_computing
  - kernel/seccomp.c:__seccomp_filter
  - kernel/seccomp.c:__seccomp_filter
  - kernel/seccomp.c:__seccomp_filter
```
**Symbols:**

```
ffffffff81174380-ffffffff81174444: audit_seccomp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void audit_seccomp(long unsigned int syscall, long int signr, int code);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/auditsc.c (ffffffff81181c60)
Location: kernel/auditsc.c:2607
Inline: False
Direct callers:
  - kernel/seccomp.c:__secure_computing
  - kernel/seccomp.c:__seccomp_filter
  - kernel/seccomp.c:__seccomp_filter
  - kernel/seccomp.c:__seccomp_filter
```
**Symbols:**

```
ffffffff81181c60-ffffffff81181d24: audit_seccomp (STB_GLOBAL)
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
