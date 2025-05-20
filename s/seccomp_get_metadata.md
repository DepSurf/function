# Function: <code>seccomp_get_metadata</code>

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
long int seccomp_get_metadata(struct task_struct *task, long unsigned int size, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/seccomp.c (ffffffff8116c2a0)
Location: kernel/seccomp.c:1071
Inline: False
Direct callers:
  - kernel/ptrace.c:ptrace_request
```
**Symbols:**

```
ffffffff8116c2a0-ffffffff8116c42b: seccomp_get_metadata (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
long int seccomp_get_metadata(struct task_struct *task, long unsigned int size, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/seccomp.c (ffffffff81179cc0)
Location: kernel/seccomp.c:1515
Inline: False
Direct callers:
  - kernel/ptrace.c:ptrace_request
```
**Symbols:**

```
ffffffff81179cc0-ffffffff81179e4b: seccomp_get_metadata (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
long int seccomp_get_metadata(struct task_struct *task, long unsigned int size, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/seccomp.c (ffffffff81186aa0)
Location: kernel/seccomp.c:1530
Inline: False
Direct callers:
  - kernel/ptrace.c:ptrace_request
```
**Symbols:**

```
ffffffff81186aa0-ffffffff81186c12: seccomp_get_metadata (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
long int seccomp_get_metadata(struct task_struct *task, long unsigned int size, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/seccomp.c (ffffffff81192a20)
Location: kernel/seccomp.c:1553
Inline: False
Direct callers:
  - kernel/ptrace.c:ptrace_request
```
**Symbols:**

```
ffffffff81192a20-ffffffff81192b92: seccomp_get_metadata (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
long int seccomp_get_metadata(struct task_struct *task, long unsigned int size, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/seccomp.c (ffffffff811a7860)
Location: kernel/seccomp.c:1574
Inline: False
Direct callers:
  - kernel/ptrace.c:ptrace_request
```
**Symbols:**

```
ffffffff811a7860-ffffffff811a79d2: seccomp_get_metadata (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
long int seccomp_get_metadata(struct task_struct *task, long unsigned int size, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/seccomp.c (ffffffff811a5010)
Location: kernel/seccomp.c:2065
Inline: False
Direct callers:
  - kernel/ptrace.c:ptrace_request
```
**Symbols:**

```
ffffffff811a5010-ffffffff811a5182: seccomp_get_metadata (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
long int seccomp_get_metadata(struct task_struct *task, long unsigned int size, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/seccomp.c (ffffffff811a5c20)
Location: kernel/seccomp.c:2113
Inline: False
Direct callers:
  - kernel/ptrace.c:ptrace_request
```
**Symbols:**

```
ffffffff811a5c20-ffffffff811a5d56: seccomp_get_metadata (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
long int seccomp_get_metadata(struct task_struct *task, long unsigned int size, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/seccomp.c (0)
Location: kernel/seccomp.c:2095
Inline: False
Direct callers:
  - kernel/ptrace.c:ptrace_request
```
**Symbols:**

```
ffffffff81cb3fa8-ffffffff81cb3fbd: seccomp_get_metadata.cold (STB_LOCAL)
ffffffff811cf3a0-ffffffff811cf4e5: seccomp_get_metadata (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
long int seccomp_get_metadata(struct task_struct *task, long unsigned int size, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/seccomp.c (0)
Location: kernel/seccomp.c:2132
Inline: False
Direct callers:
  - kernel/ptrace.c:ptrace_request
```
**Symbols:**

```
ffffffff81e64ef2-ffffffff81e64f07: seccomp_get_metadata.cold (STB_LOCAL)
ffffffff81203580-ffffffff81203700: seccomp_get_metadata (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
long int seccomp_get_metadata(struct task_struct *task, long unsigned int size, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/seccomp.c (0)
Location: kernel/seccomp.c:2132
Inline: False
Direct callers:
  - kernel/ptrace.c:ptrace_request
```
**Symbols:**

```
ffffffff8205ca0b-ffffffff8205ca20: seccomp_get_metadata.cold (STB_LOCAL)
ffffffff8124b480-ffffffff8124b600: seccomp_get_metadata (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
long int seccomp_get_metadata(struct task_struct *task, long unsigned int size, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/seccomp.c (0)
Location: kernel/seccomp.c:2132
Inline: False
Direct callers:
  - kernel/ptrace.c:ptrace_request
```
**Symbols:**

```
ffffffff820db3ac-ffffffff820db3c1: seccomp_get_metadata.cold (STB_LOCAL)
ffffffff812627a0-ffffffff81262920: seccomp_get_metadata (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
long int seccomp_get_metadata(struct task_struct *task, long unsigned int size, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/seccomp.c (0)
Location: kernel/seccomp.c:2196
Inline: False
Direct callers:
  - kernel/ptrace.c:ptrace_request
```
**Symbols:**

```
ffffffff821b70cd-ffffffff821b70e2: seccomp_get_metadata.cold (STB_LOCAL)
ffffffff8127c9e0-ffffffff8127cb60: seccomp_get_metadata (STB_GLOBAL)
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
long int seccomp_get_metadata(struct task_struct *task, long unsigned int size, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/seccomp.c (ffff80001020a4a8)
Location: kernel/seccomp.c:1553
Inline: False
Direct callers:
  - kernel/ptrace.c:ptrace_request
```
**Symbols:**

```
ffff80001020a4a8-ffff80001020a714: seccomp_get_metadata (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
long int seccomp_get_metadata(struct task_struct *task, long unsigned int size, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/seccomp.c (c0449238)
Location: kernel/seccomp.c:1553
Inline: False
Direct callers:
  - kernel/ptrace.c:ptrace_request
```
**Symbols:**

```
c0449238-c04493fc: seccomp_get_metadata (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
long int seccomp_get_metadata(struct task_struct *task, long unsigned int size, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/seccomp.c (c0000000002878f0)
Location: kernel/seccomp.c:1553
Inline: False
Direct callers:
  - kernel/ptrace.c:ptrace_request
```
**Symbols:**

```
c0000000002878f0-c000000000287b2c: seccomp_get_metadata (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
long int seccomp_get_metadata(struct task_struct *task, long unsigned int size, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/seccomp.c (ffffffe00016c1a6)
Location: kernel/seccomp.c:1553
Inline: False
Direct callers:
  - kernel/ptrace.c:ptrace_request
```
**Symbols:**

```
ffffffe00016c1a6-ffffffe00016c2a8: seccomp_get_metadata (STB_GLOBAL)
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
long int seccomp_get_metadata(struct task_struct *task, long unsigned int size, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/seccomp.c (ffffffff8118b040)
Location: kernel/seccomp.c:1553
Inline: False
Direct callers:
  - kernel/ptrace.c:ptrace_request
```
**Symbols:**

```
ffffffff8118b040-ffffffff8118b1b2: seccomp_get_metadata (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
long int seccomp_get_metadata(struct task_struct *task, long unsigned int size, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/seccomp.c (ffffffff8117e150)
Location: kernel/seccomp.c:1553
Inline: False
Direct callers:
  - kernel/ptrace.c:ptrace_request
```
**Symbols:**

```
ffffffff8117e150-ffffffff8117e2bc: seccomp_get_metadata (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
long int seccomp_get_metadata(struct task_struct *task, long unsigned int size, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/seccomp.c (ffffffff81188e10)
Location: kernel/seccomp.c:1553
Inline: False
Direct callers:
  - kernel/ptrace.c:ptrace_request
```
**Symbols:**

```
ffffffff81188e10-ffffffff81188f82: seccomp_get_metadata (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
long int seccomp_get_metadata(struct task_struct *task, long unsigned int size, void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/seccomp.c (ffffffff81196770)
Location: kernel/seccomp.c:1553
Inline: False
Direct callers:
  - kernel/ptrace.c:ptrace_request
```
**Symbols:**

```
ffffffff81196770-ffffffff811968d9: seccomp_get_metadata (STB_GLOBAL)
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
