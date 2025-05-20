# Function: <code>kprobe_emulate_ret</code>

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
<summary>In <code>5.13</code>: ✅</summary>

```c
void kprobe_emulate_ret(struct kprobe *p, struct pt_regs *regs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/kprobes/core.c (ffffffff8107a760)
Location: arch/x86/kernel/kprobes/core.c:453
Inline: False
```
**Symbols:**

```
ffffffff8107a760-ffffffff8107a787: kprobe_emulate_ret (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void kprobe_emulate_ret(struct kprobe *p, struct pt_regs *regs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/kprobes/core.c (ffffffff810888b0)
Location: arch/x86/kernel/kprobes/core.c:447
Inline: False
```
**Symbols:**

```
ffffffff810888b0-ffffffff810888d7: kprobe_emulate_ret (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void kprobe_emulate_ret(struct kprobe *p, struct pt_regs *regs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/kprobes/core.c (ffffffff81098ab0)
Location: arch/x86/kernel/kprobes/core.c:457
Inline: False
```
**Symbols:**

```
ffffffff81098ab0-ffffffff81098ae1: kprobe_emulate_ret (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void kprobe_emulate_ret(struct kprobe *p, struct pt_regs *regs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/kprobes/core.c (ffffffff810af250)
Location: arch/x86/kernel/kprobes/core.c:452
Inline: False
```
**Symbols:**

```
ffffffff810af250-ffffffff810af281: kprobe_emulate_ret (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void kprobe_emulate_ret(struct kprobe *p, struct pt_regs *regs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/kprobes/core.c (ffffffff810b2250)
Location: arch/x86/kernel/kprobes/core.c:452
Inline: False
```
**Symbols:**

```
ffffffff810b2250-ffffffff810b2281: kprobe_emulate_ret (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void kprobe_emulate_ret(struct kprobe *p, struct pt_regs *regs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/kprobes/core.c (ffffffff810b9680)
Location: arch/x86/kernel/kprobes/core.c:486
Inline: False
```
**Symbols:**

```
ffffffff810b9680-ffffffff810b96b1: kprobe_emulate_ret (STB_LOCAL)
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
