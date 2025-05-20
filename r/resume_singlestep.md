# Function: <code>resume_singlestep</code>

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
In <code>4.18</code>: Absent ⚠️
</li>
<li>
In <code>5.0</code>: Absent ⚠️
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void resume_singlestep(struct kprobe *p, struct pt_regs *regs, struct kprobe_ctlblk *kcb);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/kprobes/core.c (ffffffff8107ac20)
Location: arch/x86/kernel/kprobes/core.c:895
Inline: True
```
**Symbols:**

```
ffffffff8107ac20-ffffffff8107ac57: resume_singlestep (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void resume_singlestep(struct kprobe *p, struct pt_regs *regs, struct kprobe_ctlblk *kcb);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/kprobes/core.c (ffffffff81088da0)
Location: arch/x86/kernel/kprobes/core.c:889
Inline: True
```
**Symbols:**

```
ffffffff81088da0-ffffffff81088dd7: resume_singlestep (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void resume_singlestep(struct kprobe *p, struct pt_regs *regs, struct kprobe_ctlblk *kcb);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/kprobes/core.c (ffffffff81099578)
Location: arch/x86/kernel/kprobes/core.c:891
Inline: True
Inline callers:
  - arch/x86/kernel/kprobes/core.c:kprobe_int3_handler
```
**Symbols:**

```
ffffffff81099010-ffffffff81099055: resume_singlestep (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void resume_singlestep(struct kprobe *p, struct pt_regs *regs, struct kprobe_ctlblk *kcb);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/kprobes/core.c (ffffffff810affb8)
Location: arch/x86/kernel/kprobes/core.c:864
Inline: True
Inline callers:
  - arch/x86/kernel/kprobes/core.c:kprobe_int3_handler
```
**Symbols:**

```
ffffffff810af7c0-ffffffff810af805: resume_singlestep (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void resume_singlestep(struct kprobe *p, struct pt_regs *regs, struct kprobe_ctlblk *kcb);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/kprobes/core.c (ffffffff810b2fd4)
Location: arch/x86/kernel/kprobes/core.c:866
Inline: True
Inline callers:
  - arch/x86/kernel/kprobes/core.c:kprobe_int3_handler
```
**Symbols:**

```
ffffffff810b27e0-ffffffff810b2825: resume_singlestep (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void resume_singlestep(struct kprobe *p, struct pt_regs *regs, struct kprobe_ctlblk *kcb);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/kprobes/core.c (ffffffff810ba434)
Location: arch/x86/kernel/kprobes/core.c:901
Inline: True
Inline callers:
  - arch/x86/kernel/kprobes/core.c:kprobe_int3_handler
```
**Symbols:**

```
ffffffff810b9c10-ffffffff810b9c55: resume_singlestep (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
