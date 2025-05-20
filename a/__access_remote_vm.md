# Function: <code>__access_remote_vm</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int __access_remote_vm(struct task_struct *tsk, struct mm_struct *mm, long unsigned int addr, void *buf, int len, int write);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff811bb920)
Location: mm/memory.c:3659
Inline: False
Direct callers:
  - mm/memory.c:access_remote_vm
  - mm/memory.c:access_process_vm
```
**Symbols:**

```
ffffffff811bb920-ffffffff811bbbec: __access_remote_vm (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int __access_remote_vm(struct task_struct *tsk, struct mm_struct *mm, long unsigned int addr, void *buf, int len, int write);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff811d65c0)
Location: mm/memory.c:3854
Inline: False
Direct callers:
  - mm/memory.c:access_process_vm
  - mm/memory.c:access_remote_vm
```
**Symbols:**

```
ffffffff811d65c0-ffffffff811d68db: __access_remote_vm (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int __access_remote_vm(struct task_struct *tsk, struct mm_struct *mm, long unsigned int addr, void *buf, int len, unsigned int gup_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff811ed500)
Location: mm/memory.c:3932
Inline: False
Direct callers:
  - kernel/ptrace.c:ptrace_access_vm
  - mm/memory.c:access_process_vm
  - mm/memory.c:access_remote_vm
```
**Symbols:**

```
ffffffff811ed500-ffffffff811ed81e: __access_remote_vm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int __access_remote_vm(struct task_struct *tsk, struct mm_struct *mm, long unsigned int addr, void *buf, int len, unsigned int gup_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff811f8500)
Location: mm/memory.c:4222
Inline: False
Direct callers:
  - kernel/ptrace.c:ptrace_access_vm
  - mm/memory.c:access_process_vm
  - mm/memory.c:access_remote_vm
```
**Symbols:**

```
ffffffff811f8500-ffffffff811f87d7: __access_remote_vm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int __access_remote_vm(struct task_struct *tsk, struct mm_struct *mm, long unsigned int addr, void *buf, int len, unsigned int gup_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff812106c0)
Location: mm/memory.c:4400
Inline: False
Direct callers:
  - kernel/ptrace.c:ptrace_access_vm
  - mm/memory.c:access_process_vm
  - mm/memory.c:access_remote_vm
```
**Symbols:**

```
ffffffff812106c0-ffffffff812109d2: __access_remote_vm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int __access_remote_vm(struct task_struct *tsk, struct mm_struct *mm, long unsigned int addr, void *buf, int len, unsigned int gup_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff812310d0)
Location: mm/memory.c:4448
Inline: False
Direct callers:
  - kernel/ptrace.c:ptrace_access_vm
  - mm/memory.c:access_process_vm
  - mm/memory.c:access_remote_vm
```
**Symbols:**

```
ffffffff812310d0-ffffffff812313ef: __access_remote_vm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int __access_remote_vm(struct task_struct *tsk, struct mm_struct *mm, long unsigned int addr, void *buf, int len, unsigned int gup_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff812448a0)
Location: mm/memory.c:4238
Inline: False
Direct callers:
  - kernel/ptrace.c:ptrace_access_vm
  - mm/memory.c:access_process_vm
  - mm/memory.c:access_remote_vm
```
**Symbols:**

```
ffffffff812448a0-ffffffff81244bbf: __access_remote_vm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int __access_remote_vm(struct task_struct *tsk, struct mm_struct *mm, long unsigned int addr, void *buf, int len, unsigned int gup_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff81256860)
Location: mm/memory.c:4289
Inline: False
Direct callers:
  - kernel/ptrace.c:ptrace_access_vm
  - mm/memory.c:access_process_vm
  - mm/memory.c:access_remote_vm
```
**Symbols:**

```
ffffffff81256860-ffffffff81256b8e: __access_remote_vm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int __access_remote_vm(struct task_struct *tsk, struct mm_struct *mm, long unsigned int addr, void *buf, int len, unsigned int gup_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff81264df0)
Location: mm/memory.c:4314
Inline: False
Direct callers:
  - kernel/ptrace.c:ptrace_access_vm
  - mm/memory.c:access_process_vm
  - mm/memory.c:access_remote_vm
```
**Symbols:**

```
ffffffff81264df0-ffffffff8126511e: __access_remote_vm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int __access_remote_vm(struct task_struct *tsk, struct mm_struct *mm, long unsigned int addr, void *buf, int len, unsigned int gup_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff812951c0)
Location: mm/memory.c:4679
Inline: False
Direct callers:
  - mm/memory.c:access_process_vm
  - mm/memory.c:access_remote_vm
```
**Symbols:**

```
ffffffff812951c0-ffffffff812954ee: __access_remote_vm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int __access_remote_vm(struct mm_struct *mm, long unsigned int addr, void *buf, int len, unsigned int gup_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff812a0030)
Location: mm/memory.c:4906
Inline: False
Direct callers:
  - mm/memory.c:access_process_vm
  - mm/memory.c:access_remote_vm
```
**Symbols:**

```
ffffffff812a0030-ffffffff812a03ae: __access_remote_vm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int __access_remote_vm(struct mm_struct *mm, long unsigned int addr, void *buf, int len, unsigned int gup_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff812a5970)
Location: mm/memory.c:4973
Inline: False
Direct callers:
  - mm/memory.c:access_process_vm
  - mm/memory.c:access_remote_vm
```
**Symbols:**

```
ffffffff812a5970-ffffffff812a5cef: __access_remote_vm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int __access_remote_vm(struct mm_struct *mm, long unsigned int addr, void *buf, int len, unsigned int gup_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff812e6e60)
Location: mm/memory.c:5119
Inline: False
Direct callers:
  - mm/memory.c:access_process_vm
  - mm/memory.c:access_remote_vm
```
**Symbols:**

```
ffffffff812e6e60-ffffffff812e717c: __access_remote_vm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int __access_remote_vm(struct mm_struct *mm, long unsigned int addr, void *buf, int len, unsigned int gup_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff81347ff0)
Location: mm/memory.c:5426
Inline: False
Direct callers:
  - mm/memory.c:access_process_vm
  - mm/memory.c:access_remote_vm
```
**Symbols:**

```
ffffffff81347ff0-ffffffff813483e2: __access_remote_vm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int __access_remote_vm(struct mm_struct *mm, long unsigned int addr, void *buf, int len, unsigned int gup_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff813c0490)
Location: mm/memory.c:5506
Inline: False
Direct callers:
  - mm/memory.c:access_process_vm
  - mm/memory.c:access_remote_vm
```
**Symbols:**

```
ffffffff813c0490-ffffffff813c086c: __access_remote_vm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int __access_remote_vm(struct mm_struct *mm, long unsigned int addr, void *buf, int len, unsigned int gup_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff813f5180)
Location: mm/memory.c:5697
Inline: False
Direct callers:
  - mm/memory.c:access_process_vm
  - mm/memory.c:access_remote_vm
```
**Symbols:**

```
ffffffff813f5180-ffffffff813f55e7: __access_remote_vm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int __access_remote_vm(struct mm_struct *mm, long unsigned int addr, void *buf, int len, unsigned int gup_flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff814157b0)
Location: mm/memory.c:5923
Inline: False
Direct callers:
  - mm/memory.c:access_process_vm
  - mm/memory.c:access_remote_vm
```
**Symbols:**

```
ffffffff814157b0-ffffffff81415bfc: __access_remote_vm (STB_LOCAL)
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
int __access_remote_vm(struct task_struct *tsk, struct mm_struct *mm, long unsigned int addr, void *buf, int len, unsigned int gup_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffff8000102fb8f0)
Location: mm/memory.c:4314
Inline: False
Direct callers:
  - kernel/ptrace.c:ptrace_access_vm
  - mm/memory.c:access_process_vm
  - mm/memory.c:access_remote_vm
```
**Symbols:**

```
ffff8000102fb8f0-ffff8000102fbac4: __access_remote_vm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int __access_remote_vm(struct task_struct *tsk, struct mm_struct *mm, long unsigned int addr, void *buf, int len, unsigned int gup_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (c051bff8)
Location: mm/memory.c:4314
Inline: False
Direct callers:
  - kernel/ptrace.c:ptrace_access_vm
  - mm/memory.c:access_process_vm
  - mm/memory.c:access_remote_vm
```
**Symbols:**

```
c051bff8-c051c1c4: __access_remote_vm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int __access_remote_vm(struct task_struct *tsk, struct mm_struct *mm, long unsigned int addr, void *buf, int len, unsigned int gup_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (c0000000003c6c00)
Location: mm/memory.c:4314
Inline: False
Direct callers:
  - kernel/ptrace.c:ptrace_access_vm
  - mm/memory.c:access_process_vm
  - mm/memory.c:access_remote_vm
```
**Symbols:**

```
c0000000003c6c00-c0000000003c6fa4: __access_remote_vm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int __access_remote_vm(struct task_struct *tsk, struct mm_struct *mm, long unsigned int addr, void *buf, int len, unsigned int gup_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffe00020af68)
Location: mm/memory.c:4314
Inline: False
Direct callers:
  - kernel/ptrace.c:ptrace_access_vm
  - mm/memory.c:access_process_vm
  - mm/memory.c:access_remote_vm
```
**Symbols:**

```
ffffffe00020af68-ffffffe00020b110: __access_remote_vm (STB_GLOBAL)
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
int __access_remote_vm(struct task_struct *tsk, struct mm_struct *mm, long unsigned int addr, void *buf, int len, unsigned int gup_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff8125d440)
Location: mm/memory.c:4314
Inline: False
Direct callers:
  - kernel/ptrace.c:ptrace_access_vm
  - mm/memory.c:access_process_vm
  - mm/memory.c:access_remote_vm
```
**Symbols:**

```
ffffffff8125d440-ffffffff8125d76e: __access_remote_vm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int __access_remote_vm(struct task_struct *tsk, struct mm_struct *mm, long unsigned int addr, void *buf, int len, unsigned int gup_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff8124f890)
Location: mm/memory.c:4314
Inline: False
Direct callers:
  - kernel/ptrace.c:ptrace_access_vm
  - mm/memory.c:access_process_vm
  - mm/memory.c:access_remote_vm
```
**Symbols:**

```
ffffffff8124f890-ffffffff8124fbbe: __access_remote_vm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int __access_remote_vm(struct task_struct *tsk, struct mm_struct *mm, long unsigned int addr, void *buf, int len, unsigned int gup_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff8125b1e0)
Location: mm/memory.c:4314
Inline: False
Direct callers:
  - kernel/ptrace.c:ptrace_access_vm
  - mm/memory.c:access_process_vm
  - mm/memory.c:access_remote_vm
```
**Symbols:**

```
ffffffff8125b1e0-ffffffff8125b50e: __access_remote_vm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int __access_remote_vm(struct task_struct *tsk, struct mm_struct *mm, long unsigned int addr, void *buf, int len, unsigned int gup_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff8126abb0)
Location: mm/memory.c:4314
Inline: False
Direct callers:
  - kernel/ptrace.c:ptrace_access_vm
  - mm/memory.c:access_process_vm
  - mm/memory.c:access_remote_vm
```
**Symbols:**

```
ffffffff8126abb0-ffffffff8126aee9: __access_remote_vm (STB_GLOBAL)
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
<details>
<summary>Changed between <code>4.8</code> and <code>4.10</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>unsigned int gup_flags</code>
</li>
<li>
<b>Param removed. </b>
<code>int write</code>
</li>
</ul>
</details>
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
<details>
<summary>Changed between <code>5.8</code> and <code>5.11</code> ⚠️</summary>
<ul>
<li>
<b>Param removed. </b>
<code>struct task_struct *tsk</code>
</li>
<li>
<b>Param reordered. </b>
<code>tsk, mm, addr, buf, len, gup_flags</code> ➡️ <code>mm, addr, buf, len, gup_flags</code>
</li>
</ul>
</details>
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
