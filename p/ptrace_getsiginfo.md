# Function: <code>ptrace_getsiginfo</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int ptrace_getsiginfo(struct task_struct *child, siginfo_t *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/ptrace.c (ffffffff8108a9c0)
Location: kernel/ptrace.c:624
Inline: False
Direct callers:
  - kernel/ptrace.c:ptrace_request
  - kernel/ptrace.c:compat_ptrace_request
```
**Symbols:**

```
ffffffff8108a9c0-ffffffff8108aad3: ptrace_getsiginfo (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int ptrace_getsiginfo(struct task_struct *child, siginfo_t *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/ptrace.c (ffffffff8108d9b0)
Location: kernel/ptrace.c:629
Inline: False
Direct callers:
  - kernel/ptrace.c:compat_ptrace_request
  - kernel/ptrace.c:ptrace_request
```
**Symbols:**

```
ffffffff8108d9b0-ffffffff8108dac3: ptrace_getsiginfo (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int ptrace_getsiginfo(struct task_struct *child, siginfo_t *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/ptrace.c (ffffffff810927b0)
Location: kernel/ptrace.c:639
Inline: False
Direct callers:
  - kernel/ptrace.c:compat_ptrace_request
  - kernel/ptrace.c:ptrace_request
```
**Symbols:**

```
ffffffff810927b0-ffffffff810928c3: ptrace_getsiginfo (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int ptrace_getsiginfo(struct task_struct *child, siginfo_t *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/ptrace.c (ffffffff8108f8f0)
Location: kernel/ptrace.c:654
Inline: False
Direct callers:
  - kernel/ptrace.c:compat_ptrace_request
  - kernel/ptrace.c:ptrace_request
```
**Symbols:**

```
ffffffff8108f8f0-ffffffff8108fa03: ptrace_getsiginfo (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int ptrace_getsiginfo(struct task_struct *child, siginfo_t *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/ptrace.c (ffffffff810967b0)
Location: kernel/ptrace.c:654
Inline: False
Direct callers:
  - kernel/ptrace.c:compat_ptrace_request
  - kernel/ptrace.c:ptrace_request
```
**Symbols:**

```
ffffffff810967b0-ffffffff810968c3: ptrace_getsiginfo (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int ptrace_getsiginfo(struct task_struct *child, siginfo_t *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/ptrace.c (ffffffff81099f50)
Location: kernel/ptrace.c:654
Inline: False
Direct callers:
  - kernel/ptrace.c:compat_ptrace_request
  - kernel/ptrace.c:ptrace_request
```
**Symbols:**

```
ffffffff81099f50-ffffffff8109a063: ptrace_getsiginfo (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int ptrace_getsiginfo(struct task_struct *child, kernel_siginfo_t *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/ptrace.c (ffffffff810a2060)
Location: kernel/ptrace.c:654
Inline: False
Direct callers:
  - kernel/ptrace.c:compat_ptrace_request
  - kernel/ptrace.c:ptrace_request
```
**Symbols:**

```
ffffffff810a2060-ffffffff810a211b: ptrace_getsiginfo (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int ptrace_getsiginfo(struct task_struct *child, kernel_siginfo_t *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/ptrace.c (ffffffff810a70f0)
Location: kernel/ptrace.c:669
Inline: False
Direct callers:
  - kernel/ptrace.c:compat_ptrace_request
  - kernel/ptrace.c:ptrace_request
```
**Symbols:**

```
ffffffff810a70f0-ffffffff810a71a6: ptrace_getsiginfo (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int ptrace_getsiginfo(struct task_struct *child, kernel_siginfo_t *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/ptrace.c (ffffffff810ad710)
Location: kernel/ptrace.c:674
Inline: False
Direct callers:
  - kernel/ptrace.c:compat_ptrace_request
  - kernel/ptrace.c:ptrace_request
```
**Symbols:**

```
ffffffff810ad710-ffffffff810ad7c6: ptrace_getsiginfo (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int ptrace_getsiginfo(struct task_struct *child, kernel_siginfo_t *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/ptrace.c (ffffffff810b5150)
Location: kernel/ptrace.c:674
Inline: False
Direct callers:
  - kernel/ptrace.c:compat_ptrace_request
  - kernel/ptrace.c:ptrace_request
```
**Symbols:**

```
ffffffff810b5150-ffffffff810b5206: ptrace_getsiginfo (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int ptrace_getsiginfo(struct task_struct *child, kernel_siginfo_t *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/ptrace.c (ffffffff810affe0)
Location: kernel/ptrace.c:668
Inline: False
Direct callers:
  - kernel/ptrace.c:compat_ptrace_request
  - kernel/ptrace.c:ptrace_request
```
**Symbols:**

```
ffffffff810affe0-ffffffff810b0096: ptrace_getsiginfo (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int ptrace_getsiginfo(struct task_struct *child, kernel_siginfo_t *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/ptrace.c (ffffffff810b18c0)
Location: kernel/ptrace.c:685
Inline: False
Direct callers:
  - kernel/ptrace.c:compat_ptrace_request
  - kernel/ptrace.c:ptrace_request
```
**Symbols:**

```
ffffffff810b18c0-ffffffff810b1976: ptrace_getsiginfo (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int ptrace_getsiginfo(struct task_struct *child, kernel_siginfo_t *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/ptrace.c (ffffffff810c39b0)
Location: kernel/ptrace.c:685
Inline: False
Direct callers:
  - kernel/ptrace.c:compat_ptrace_request
  - kernel/ptrace.c:ptrace_request
```
**Symbols:**

```
ffffffff810c39b0-ffffffff810c3a66: ptrace_getsiginfo (STB_LOCAL)
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
In kernel/ptrace.c (ffffffff810dcded)
Location: kernel/ptrace.c:696
Inline: True
Inline callers:
  - kernel/ptrace.c:compat_ptrace_request
  - kernel/ptrace.c:ptrace_request
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
In kernel/ptrace.c (ffffffff810fd0a9)
Location: kernel/ptrace.c:696
Inline: True
Inline callers:
  - kernel/ptrace.c:compat_ptrace_request
  - kernel/ptrace.c:ptrace_request
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
In kernel/ptrace.c (ffffffff81109075)
Location: kernel/ptrace.c:697
Inline: True
Inline callers:
  - kernel/ptrace.c:compat_ptrace_request
  - kernel/ptrace.c:ptrace_request
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
In kernel/ptrace.c (ffffffff81112a05)
Location: kernel/ptrace.c:680
Inline: True
Inline callers:
  - kernel/ptrace.c:compat_ptrace_request
  - kernel/ptrace.c:ptrace_request
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
int ptrace_getsiginfo(struct task_struct *child, kernel_siginfo_t *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/ptrace.c (ffff800010106c30)
Location: kernel/ptrace.c:674
Inline: False
Direct callers:
  - kernel/ptrace.c:compat_ptrace_request
  - kernel/ptrace.c:ptrace_request
```
**Symbols:**

```
ffff800010106c30-ffff800010106ce4: ptrace_getsiginfo (STB_LOCAL)
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
In kernel/ptrace.c (c0362c44)
Location: kernel/ptrace.c:674
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_request
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int ptrace_getsiginfo(struct task_struct *child, kernel_siginfo_t *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/ptrace.c (c00000000014e2f0)
Location: kernel/ptrace.c:674
Inline: False
Direct callers:
  - kernel/ptrace.c:compat_ptrace_request
  - kernel/ptrace.c:ptrace_request
```
**Symbols:**

```
c00000000014e2f0-c00000000014e3e8: ptrace_getsiginfo (STB_LOCAL)
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
In kernel/ptrace.c (ffffffe0000ccbd0)
Location: kernel/ptrace.c:674
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_request
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
int ptrace_getsiginfo(struct task_struct *child, kernel_siginfo_t *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/ptrace.c (ffffffff810a7a80)
Location: kernel/ptrace.c:674
Inline: False
Direct callers:
  - kernel/ptrace.c:compat_ptrace_request
  - kernel/ptrace.c:ptrace_request
```
**Symbols:**

```
ffffffff810a7a80-ffffffff810a7b36: ptrace_getsiginfo (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int ptrace_getsiginfo(struct task_struct *child, kernel_siginfo_t *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/ptrace.c (ffffffff81096460)
Location: kernel/ptrace.c:674
Inline: False
Direct callers:
  - kernel/ptrace.c:compat_ptrace_request
  - kernel/ptrace.c:ptrace_request
```
**Symbols:**

```
ffffffff81096460-ffffffff81096516: ptrace_getsiginfo (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int ptrace_getsiginfo(struct task_struct *child, kernel_siginfo_t *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/ptrace.c (ffffffff810a6fe0)
Location: kernel/ptrace.c:674
Inline: False
Direct callers:
  - kernel/ptrace.c:compat_ptrace_request
  - kernel/ptrace.c:ptrace_request
```
**Symbols:**

```
ffffffff810a6fe0-ffffffff810a7096: ptrace_getsiginfo (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int ptrace_getsiginfo(struct task_struct *child, kernel_siginfo_t *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/ptrace.c (ffffffff810af5a0)
Location: kernel/ptrace.c:674
Inline: False
Direct callers:
  - kernel/ptrace.c:compat_ptrace_request
  - kernel/ptrace.c:ptrace_request
```
**Symbols:**

```
ffffffff810af5a0-ffffffff810af656: ptrace_getsiginfo (STB_LOCAL)
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
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
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
