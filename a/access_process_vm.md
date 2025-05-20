# Function: <code>access_process_vm</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int access_process_vm(struct task_struct *tsk, long unsigned int addr, void *buf, int len, int write);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff811c1ed0)
Location: mm/memory.c:3740
Inline: False
Direct callers:
  - arch/x86/kernel/step.c:enable_step
  - kernel/ptrace.c:ptrace_readdata
  - kernel/ptrace.c:ptrace_writedata
  - kernel/ptrace.c:ptrace_request
  - kernel/ptrace.c:ptrace_request
  - kernel/ptrace.c:compat_ptrace_request
  - kernel/ptrace.c:compat_ptrace_request
  - mm/util.c:get_cmdline
  - mm/util.c:get_cmdline
```
**Symbols:**

```
ffffffff811c1ed0-ffffffff811c1f3b: access_process_vm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int access_process_vm(struct task_struct *tsk, long unsigned int addr, void *buf, int len, int write);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff811dda00)
Location: mm/memory.c:3935
Inline: False
Direct callers:
  - arch/x86/kernel/step.c:enable_step
  - kernel/ptrace.c:compat_ptrace_request
  - kernel/ptrace.c:compat_ptrace_request
  - kernel/ptrace.c:ptrace_request
  - kernel/ptrace.c:ptrace_request
  - kernel/ptrace.c:ptrace_writedata
  - kernel/ptrace.c:ptrace_readdata
  - mm/util.c:get_cmdline
  - mm/util.c:get_cmdline
```
**Symbols:**

```
ffffffff811dda00-ffffffff811dda71: access_process_vm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int access_process_vm(struct task_struct *tsk, long unsigned int addr, void *buf, int len, unsigned int gup_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff811ed820)
Location: mm/memory.c:4014
Inline: False
Direct callers:
  - arch/x86/kernel/step.c:enable_step
  - mm/util.c:get_cmdline
  - mm/util.c:get_cmdline
```
**Symbols:**

```
ffffffff811ed820-ffffffff811ed891: access_process_vm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int access_process_vm(struct task_struct *tsk, long unsigned int addr, void *buf, int len, unsigned int gup_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff811f87e0)
Location: mm/memory.c:4304
Inline: False
Direct callers:
  - arch/x86/kernel/step.c:enable_step
  - mm/util.c:get_cmdline
  - mm/util.c:get_cmdline
```
**Symbols:**

```
ffffffff811f87e0-ffffffff811f884d: access_process_vm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int access_process_vm(struct task_struct *tsk, long unsigned int addr, void *buf, int len, unsigned int gup_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff812109e0)
Location: mm/memory.c:4482
Inline: False
Direct callers:
  - arch/x86/kernel/step.c:enable_step
  - mm/util.c:get_cmdline
  - mm/util.c:get_cmdline
```
**Symbols:**

```
ffffffff812109e0-ffffffff81210a4d: access_process_vm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int access_process_vm(struct task_struct *tsk, long unsigned int addr, void *buf, int len, unsigned int gup_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff812313f0)
Location: mm/memory.c:4530
Inline: False
Direct callers:
  - arch/x86/kernel/step.c:enable_step
  - mm/util.c:get_cmdline
  - mm/util.c:get_cmdline
```
**Symbols:**

```
ffffffff812313f0-ffffffff81231461: access_process_vm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int access_process_vm(struct task_struct *tsk, long unsigned int addr, void *buf, int len, unsigned int gup_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff81244bc0)
Location: mm/memory.c:4320
Inline: False
Direct callers:
  - arch/x86/kernel/step.c:enable_step
  - mm/util.c:get_cmdline
  - mm/util.c:get_cmdline
```
**Symbols:**

```
ffffffff81244bc0-ffffffff81244c31: access_process_vm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int access_process_vm(struct task_struct *tsk, long unsigned int addr, void *buf, int len, unsigned int gup_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff81256b90)
Location: mm/memory.c:4375
Inline: False
Direct callers:
  - arch/x86/kernel/step.c:enable_step
  - mm/util.c:get_cmdline
  - mm/util.c:get_cmdline
```
**Symbols:**

```
ffffffff81256b90-ffffffff81256bfe: access_process_vm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int access_process_vm(struct task_struct *tsk, long unsigned int addr, void *buf, int len, unsigned int gup_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff81265120)
Location: mm/memory.c:4400
Inline: False
Direct callers:
  - arch/x86/kernel/step.c:enable_step
  - mm/util.c:get_cmdline
  - mm/util.c:get_cmdline
```
**Symbols:**

```
ffffffff81265120-ffffffff8126518e: access_process_vm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int access_process_vm(struct task_struct *tsk, long unsigned int addr, void *buf, int len, unsigned int gup_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff812954f0)
Location: mm/memory.c:4765
Inline: False
Direct callers:
  - arch/x86/kernel/step.c:is_setting_trap_flag
  - mm/util.c:get_cmdline
  - mm/util.c:get_cmdline
```
**Symbols:**

```
ffffffff812954f0-ffffffff8129555e: access_process_vm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int access_process_vm(struct task_struct *tsk, long unsigned int addr, void *buf, int len, unsigned int gup_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff812a03b0)
Location: mm/memory.c:4992
Inline: False
Direct callers:
  - arch/x86/kernel/step.c:is_setting_trap_flag
  - mm/util.c:get_cmdline
  - mm/util.c:get_cmdline
```
**Symbols:**

```
ffffffff812a03b0-ffffffff812a0413: access_process_vm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int access_process_vm(struct task_struct *tsk, long unsigned int addr, void *buf, int len, unsigned int gup_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff812a5cf0)
Location: mm/memory.c:5059
Inline: False
Direct callers:
  - arch/x86/kernel/step.c:enable_step
  - mm/util.c:get_cmdline
  - mm/util.c:get_cmdline
```
**Symbols:**

```
ffffffff812a5cf0-ffffffff812a5d53: access_process_vm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int access_process_vm(struct task_struct *tsk, long unsigned int addr, void *buf, int len, unsigned int gup_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff812e7180)
Location: mm/memory.c:5205
Inline: False
Direct callers:
  - arch/x86/kernel/step.c:enable_step
  - mm/util.c:get_cmdline
  - mm/util.c:get_cmdline
```
**Symbols:**

```
ffffffff812e7180-ffffffff812e71e3: access_process_vm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int access_process_vm(struct task_struct *tsk, long unsigned int addr, void *buf, int len, unsigned int gup_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff813483f0)
Location: mm/memory.c:5512
Inline: False
Direct callers:
  - kernel/bpf/helpers.c:bpf_copy_from_user_task
  - mm/util.c:get_cmdline
  - mm/util.c:get_cmdline
```
**Symbols:**

```
ffffffff813483f0-ffffffff81348461: access_process_vm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int access_process_vm(struct task_struct *tsk, long unsigned int addr, void *buf, int len, unsigned int gup_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff813c0880)
Location: mm/memory.c:5592
Inline: False
Direct callers:
  - arch/x86/kernel/step.c:enable_single_step
  - kernel/bpf/helpers.c:bpf_copy_from_user_task
  - mm/util.c:get_cmdline
  - mm/util.c:get_cmdline
```
**Symbols:**

```
ffffffff813c0880-ffffffff813c08f1: access_process_vm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int access_process_vm(struct task_struct *tsk, long unsigned int addr, void *buf, int len, unsigned int gup_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff813f5600)
Location: mm/memory.c:5798
Inline: False
Direct callers:
  - arch/x86/kernel/step.c:enable_single_step
  - kernel/bpf/helpers.c:bpf_copy_from_user_task
  - mm/util.c:get_cmdline
  - mm/util.c:get_cmdline
```
**Symbols:**

```
ffffffff813f5600-ffffffff813f5671: access_process_vm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int access_process_vm(struct task_struct *tsk, long unsigned int addr, void *buf, int len, unsigned int gup_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff81415c10)
Location: mm/memory.c:6022
Inline: False
Direct callers:
  - arch/x86/kernel/step.c:enable_single_step
  - kernel/bpf/helpers.c:bpf_copy_from_user_task
  - mm/util.c:get_cmdline
  - mm/util.c:get_cmdline
```
**Symbols:**

```
ffffffff81415c10-ffffffff81415c81: access_process_vm (STB_GLOBAL)
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
int access_process_vm(struct task_struct *tsk, long unsigned int addr, void *buf, int len, unsigned int gup_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffff8000102fbac8)
Location: mm/memory.c:4400
Inline: False
Direct callers:
  - mm/util.c:get_cmdline
  - mm/util.c:get_cmdline
```
**Symbols:**

```
ffff8000102fbac8-ffff8000102fbb64: access_process_vm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int access_process_vm(struct task_struct *tsk, long unsigned int addr, void *buf, int len, unsigned int gup_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (c051c1c4)
Location: mm/memory.c:4400
Inline: False
Direct callers:
  - mm/util.c:get_cmdline
  - mm/util.c:get_cmdline
```
**Symbols:**

```
c051c1c4-c051c234: access_process_vm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int access_process_vm(struct task_struct *tsk, long unsigned int addr, void *buf, int len, unsigned int gup_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (c0000000003c6fb0)
Location: mm/memory.c:4400
Inline: False
Direct callers:
  - mm/util.c:get_cmdline
  - mm/util.c:get_cmdline
```
**Symbols:**

```
c0000000003c6fb0-c0000000003c70a0: access_process_vm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int access_process_vm(struct task_struct *tsk, long unsigned int addr, void *buf, int len, unsigned int gup_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffe00020b110)
Location: mm/memory.c:4400
Inline: False
Direct callers:
  - mm/util.c:get_cmdline
  - mm/util.c:get_cmdline
```
**Symbols:**

```
ffffffe00020b110-ffffffe00020b182: access_process_vm (STB_GLOBAL)
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
int access_process_vm(struct task_struct *tsk, long unsigned int addr, void *buf, int len, unsigned int gup_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff8125d770)
Location: mm/memory.c:4400
Inline: False
Direct callers:
  - arch/x86/kernel/step.c:enable_step
  - mm/util.c:get_cmdline
  - mm/util.c:get_cmdline
```
**Symbols:**

```
ffffffff8125d770-ffffffff8125d7de: access_process_vm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int access_process_vm(struct task_struct *tsk, long unsigned int addr, void *buf, int len, unsigned int gup_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff8124fbc0)
Location: mm/memory.c:4400
Inline: False
Direct callers:
  - arch/x86/kernel/step.c:enable_step
  - mm/util.c:get_cmdline
  - mm/util.c:get_cmdline
```
**Symbols:**

```
ffffffff8124fbc0-ffffffff8124fc2e: access_process_vm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int access_process_vm(struct task_struct *tsk, long unsigned int addr, void *buf, int len, unsigned int gup_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff8125b510)
Location: mm/memory.c:4400
Inline: False
Direct callers:
  - arch/x86/kernel/step.c:enable_step
  - mm/util.c:get_cmdline
  - mm/util.c:get_cmdline
```
**Symbols:**

```
ffffffff8125b510-ffffffff8125b57e: access_process_vm (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int access_process_vm(struct task_struct *tsk, long unsigned int addr, void *buf, int len, unsigned int gup_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff8126aef0)
Location: mm/memory.c:4400
Inline: False
Direct callers:
  - arch/x86/kernel/step.c:enable_step
  - mm/util.c:get_cmdline
  - mm/util.c:get_cmdline
```
**Symbols:**

```
ffffffff8126aef0-ffffffff8126af5e: access_process_vm (STB_GLOBAL)
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
