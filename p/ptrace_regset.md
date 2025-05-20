# Function: <code>ptrace_regset</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int ptrace_regset(struct task_struct *task, int req, unsigned int type, struct iovec *kiov);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/ptrace.c (ffffffff8108b090)
Location: kernel/ptrace.c:825
Inline: False
Direct callers:
  - kernel/ptrace.c:ptrace_request
  - kernel/ptrace.c:compat_ptrace_request
```
**Symbols:**

```
ffffffff8108b090-ffffffff8108b1c1: ptrace_regset (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int ptrace_regset(struct task_struct *task, int req, unsigned int type, struct iovec *kiov);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/ptrace.c (ffffffff8108e080)
Location: kernel/ptrace.c:830
Inline: False
Direct callers:
  - kernel/ptrace.c:compat_ptrace_request
  - kernel/ptrace.c:ptrace_request
```
**Symbols:**

```
ffffffff8108e080-ffffffff8108e1b0: ptrace_regset (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int ptrace_regset(struct task_struct *task, int req, unsigned int type, struct iovec *kiov);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/ptrace.c (ffffffff81092c50)
Location: kernel/ptrace.c:840
Inline: False
Direct callers:
  - kernel/ptrace.c:compat_ptrace_request
  - kernel/ptrace.c:ptrace_request
```
**Symbols:**

```
ffffffff81092c50-ffffffff81092d80: ptrace_regset (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int ptrace_regset(struct task_struct *task, int req, unsigned int type, struct iovec *kiov);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/ptrace.c (ffffffff8108fd60)
Location: kernel/ptrace.c:855
Inline: False
Direct callers:
  - kernel/ptrace.c:compat_ptrace_request
  - kernel/ptrace.c:ptrace_request
```
**Symbols:**

```
ffffffff8108fd60-ffffffff8108fe83: ptrace_regset (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int ptrace_regset(struct task_struct *task, int req, unsigned int type, struct iovec *kiov);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/ptrace.c (ffffffff81096c30)
Location: kernel/ptrace.c:853
Inline: False
Direct callers:
  - kernel/ptrace.c:compat_ptrace_request
  - kernel/ptrace.c:ptrace_request
```
**Symbols:**

```
ffffffff81096c30-ffffffff81096d46: ptrace_regset (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/ptrace.c (ffffffff81099e30)
Location: kernel/ptrace.c:853
Inline: True
Direct callers:
  - kernel/ptrace.c:compat_ptrace_request
  - kernel/ptrace.c:ptrace_request
```
**Symbols:**

```
ffffffff81099e30-ffffffff81099f43: ptrace_regset.isra.16 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/ptrace.c (ffffffff810a2340)
Location: kernel/ptrace.c:853
Inline: True
Direct callers:
  - kernel/ptrace.c:compat_ptrace_request
  - kernel/ptrace.c:ptrace_request
```
**Symbols:**

```
ffffffff810a2340-ffffffff810a2453: ptrace_regset.isra.15 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/ptrace.c (ffffffff810a6fe0)
Location: kernel/ptrace.c:874
Inline: True
Direct callers:
  - kernel/ptrace.c:compat_ptrace_request
  - kernel/ptrace.c:ptrace_request
```
**Symbols:**

```
ffffffff810a6fe0-ffffffff810a70e6: ptrace_regset.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/ptrace.c (ffffffff810ad600)
Location: kernel/ptrace.c:879
Inline: True
Direct callers:
  - kernel/ptrace.c:compat_ptrace_request
  - kernel/ptrace.c:ptrace_request
```
**Symbols:**

```
ffffffff810ad600-ffffffff810ad706: ptrace_regset.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int ptrace_regset(struct task_struct *task, int req, unsigned int type, struct iovec *kiov);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/ptrace.c (ffffffff810b4ec0)
Location: kernel/ptrace.c:879
Inline: False
Direct callers:
  - kernel/ptrace.c:compat_ptrace_request
  - kernel/ptrace.c:ptrace_request
```
**Symbols:**

```
ffffffff810b4ec0-ffffffff810b4fc2: ptrace_regset (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int ptrace_regset(struct task_struct *task, int req, unsigned int type, struct iovec *kiov);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/ptrace.c (ffffffff810b00a0)
Location: kernel/ptrace.c:873
Inline: False
Direct callers:
  - kernel/ptrace.c:compat_ptrace_request
  - kernel/ptrace.c:ptrace_request
```
**Symbols:**

```
ffffffff810b00a0-ffffffff810b01e8: ptrace_regset (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int ptrace_regset(struct task_struct *task, int req, unsigned int type, struct iovec *kiov);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/ptrace.c (ffffffff810b1630)
Location: kernel/ptrace.c:908
Inline: False
Direct callers:
  - kernel/ptrace.c:compat_ptrace_request
  - kernel/ptrace.c:ptrace_request
```
**Symbols:**

```
ffffffff810b1630-ffffffff810b175c: ptrace_regset (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int ptrace_regset(struct task_struct *task, int req, unsigned int type, struct iovec *kiov);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/ptrace.c (ffffffff810c3450)
Location: kernel/ptrace.c:908
Inline: False
Direct callers:
  - kernel/ptrace.c:compat_ptrace_request
  - kernel/ptrace.c:ptrace_request
```
**Symbols:**

```
ffffffff810c3450-ffffffff810c357c: ptrace_regset (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int ptrace_regset(struct task_struct *task, int req, unsigned int type, struct iovec *kiov);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/ptrace.c (ffffffff810dab60)
Location: kernel/ptrace.c:907
Inline: False
Direct callers:
  - kernel/ptrace.c:compat_ptrace_request
  - kernel/ptrace.c:ptrace_request
```
**Symbols:**

```
ffffffff810dab60-ffffffff810dacdb: ptrace_regset (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int ptrace_regset(struct task_struct *task, int req, unsigned int type, struct iovec *kiov);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/ptrace.c (ffffffff810fac80)
Location: kernel/ptrace.c:907
Inline: False
Direct callers:
  - kernel/ptrace.c:compat_ptrace_request
  - kernel/ptrace.c:ptrace_request
```
**Symbols:**

```
ffffffff810fac80-ffffffff810fadfb: ptrace_regset (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int ptrace_regset(struct task_struct *task, int req, unsigned int type, struct iovec *kiov);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/ptrace.c (ffffffff81107030)
Location: kernel/ptrace.c:908
Inline: False
Direct callers:
  - kernel/ptrace.c:compat_ptrace_request
  - kernel/ptrace.c:ptrace_request
```
**Symbols:**

```
ffffffff81107030-ffffffff811071a2: ptrace_regset (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int ptrace_regset(struct task_struct *task, int req, unsigned int type, struct iovec *kiov);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/ptrace.c (ffffffff81110980)
Location: kernel/ptrace.c:891
Inline: False
Direct callers:
  - kernel/ptrace.c:compat_ptrace_request
  - kernel/ptrace.c:ptrace_request
```
**Symbols:**

```
ffffffff81110980-ffffffff81110af2: ptrace_regset (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/ptrace.c (ffff800010106e88)
Location: kernel/ptrace.c:879
Inline: True
Direct callers:
  - kernel/ptrace.c:compat_ptrace_request
  - kernel/ptrace.c:ptrace_request
```
**Symbols:**

```
ffff800010106e88-ffff800010107030: ptrace_regset.isra.0 (STB_LOCAL)
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
In kernel/ptrace.c (c0362dc4)
Location: kernel/ptrace.c:879
Inline: True
Inline callers:
  - kernel/ptrace.c:ptrace_request
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/ptrace.c (c00000000014e560)
Location: kernel/ptrace.c:879
Inline: True
Direct callers:
  - kernel/ptrace.c:compat_ptrace_request
  - kernel/ptrace.c:ptrace_request
```
**Symbols:**

```
c00000000014e560-c00000000014e734: ptrace_regset.isra.0 (STB_LOCAL)
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
In kernel/ptrace.c (ffffffe0000ccb1e)
Location: kernel/ptrace.c:879
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
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/ptrace.c (ffffffff810a7970)
Location: kernel/ptrace.c:879
Inline: True
Direct callers:
  - kernel/ptrace.c:compat_ptrace_request
  - kernel/ptrace.c:ptrace_request
```
**Symbols:**

```
ffffffff810a7970-ffffffff810a7a76: ptrace_regset.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/ptrace.c (ffffffff81096350)
Location: kernel/ptrace.c:879
Inline: True
Direct callers:
  - kernel/ptrace.c:compat_ptrace_request
  - kernel/ptrace.c:ptrace_request
```
**Symbols:**

```
ffffffff81096350-ffffffff81096456: ptrace_regset.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/ptrace.c (ffffffff810a6ed0)
Location: kernel/ptrace.c:879
Inline: True
Direct callers:
  - kernel/ptrace.c:compat_ptrace_request
  - kernel/ptrace.c:ptrace_request
```
**Symbols:**

```
ffffffff810a6ed0-ffffffff810a6fd6: ptrace_regset.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/ptrace.c (ffffffff810af1a0)
Location: kernel/ptrace.c:879
Inline: True
Direct callers:
  - kernel/ptrace.c:compat_ptrace_request
  - kernel/ptrace.c:ptrace_request
```
**Symbols:**

```
ffffffff810af1a0-ffffffff810af2a6: ptrace_regset.isra.0 (STB_LOCAL)
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
