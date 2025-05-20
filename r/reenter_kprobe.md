# Function: <code>reenter_kprobe</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
int reenter_kprobe(struct kprobe *p, struct pt_regs *regs, struct kprobe_ctlblk *kcb);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/kprobes/core.c (ffffffff8105f1f0)
Location: arch/x86/kernel/kprobes/core.c:567
Inline: True
```
**Symbols:**

```
ffffffff8105f1f0-ffffffff8105f281: reenter_kprobe (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
int reenter_kprobe(struct kprobe *p, struct pt_regs *regs, struct kprobe_ctlblk *kcb);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/kprobes/core.c (ffffffff8105eff0)
Location: arch/x86/kernel/kprobes/core.c:569
Inline: True
```
**Symbols:**

```
ffffffff8105eff0-ffffffff8105f081: reenter_kprobe (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
int reenter_kprobe(struct kprobe *p, struct pt_regs *regs, struct kprobe_ctlblk *kcb);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/kprobes/core.c (ffffffff81062090)
Location: arch/x86/kernel/kprobes/core.c:570
Inline: True
```
**Symbols:**

```
ffffffff81062090-ffffffff81062121: reenter_kprobe (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int reenter_kprobe(struct kprobe *p, struct pt_regs *regs, struct kprobe_ctlblk *kcb);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/kprobes/core.c (ffffffff81061040)
Location: arch/x86/kernel/kprobes/core.c:603
Inline: True
```
**Symbols:**

```
ffffffff81061040-ffffffff810610c2: reenter_kprobe (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int reenter_kprobe(struct kprobe *p, struct pt_regs *regs, struct kprobe_ctlblk *kcb);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/kprobes/core.c (ffffffff810654e0)
Location: arch/x86/kernel/kprobes/core.c:622
Inline: True
```
**Symbols:**

```
ffffffff810654e0-ffffffff81065562: reenter_kprobe (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

```c
int reenter_kprobe(struct kprobe *p, struct pt_regs *regs, struct kprobe_ctlblk *kcb);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/kprobes/core.c (0)
Location: arch/x86/kernel/kprobes/core.c:624
Inline: True
```
**Symbols:**

```
ffffffff81068080-ffffffff810680e8: reenter_kprobe (STB_LOCAL)
ffffffff8106897a-ffffffff81068990: reenter_kprobe.cold.17 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

```c
int reenter_kprobe(struct kprobe *p, struct pt_regs *regs, struct kprobe_ctlblk *kcb);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/kprobes/core.c (ffffffff8106e73d)
Location: arch/x86/kernel/kprobes/core.c:621
Inline: True
```
**Symbols:**

```
ffffffff8106df10-ffffffff8106df78: reenter_kprobe (STB_LOCAL)
ffffffff8106e73d-ffffffff8106e753: reenter_kprobe.cold.14 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

```c
int reenter_kprobe(struct kprobe *p, struct pt_regs *regs, struct kprobe_ctlblk *kcb);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/kprobes/core.c (ffffffff810727f9)
Location: arch/x86/kernel/kprobes/core.c:620
Inline: True
```
**Symbols:**

```
ffffffff81071f60-ffffffff81071fc3: reenter_kprobe (STB_LOCAL)
ffffffff810727de-ffffffff8107280f: reenter_kprobe.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

```c
int reenter_kprobe(struct kprobe *p, struct pt_regs *regs, struct kprobe_ctlblk *kcb);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/kprobes/core.c (ffffffff810737f9)
Location: arch/x86/kernel/kprobes/core.c:620
Inline: True
```
**Symbols:**

```
ffffffff81072f90-ffffffff81072ffd: reenter_kprobe (STB_LOCAL)
ffffffff810737f9-ffffffff8107380f: reenter_kprobe.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int reenter_kprobe(struct kprobe *p, struct pt_regs *regs, struct kprobe_ctlblk *kcb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/kprobes/core.c (0)
Location: arch/x86/kernel/kprobes/core.c:628
Inline: False
```
**Symbols:**

```
ffffffff81079ee0-ffffffff81079f4d: reenter_kprobe (STB_LOCAL)
ffffffff8107a91d-ffffffff8107a933: reenter_kprobe.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int reenter_kprobe(struct kprobe *p, struct pt_regs *regs, struct kprobe_ctlblk *kcb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/kprobes/core.c (0)
Location: arch/x86/kernel/kprobes/core.c:641
Inline: False
```
**Symbols:**

```
ffffffff81079d20-ffffffff81079d8d: reenter_kprobe (STB_LOCAL)
ffffffff81bd7b8c-ffffffff81bd7ba2: reenter_kprobe.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int reenter_kprobe(struct kprobe *p, struct pt_regs *regs, struct kprobe_ctlblk *kcb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/kprobes/core.c (0)
Location: arch/x86/kernel/kprobes/core.c:913
Inline: False
```
**Symbols:**

```
ffffffff8107afa0-ffffffff8107b00d: reenter_kprobe (STB_LOCAL)
ffffffff81bc9b2e-ffffffff81bc9b44: reenter_kprobe.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
int reenter_kprobe(struct kprobe *p, struct pt_regs *regs, struct kprobe_ctlblk *kcb);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/kprobes/core.c (ffffffff81c9e9ce)
Location: arch/x86/kernel/kprobes/core.c:907
Inline: True
```
**Symbols:**

```
ffffffff81089110-ffffffff8108917d: reenter_kprobe (STB_LOCAL)
ffffffff81c9e9ce-ffffffff81c9e9e4: reenter_kprobe.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

```c
int reenter_kprobe(struct kprobe *p, struct pt_regs *regs, struct kprobe_ctlblk *kcb);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/kprobes/core.c (ffffffff81e4de01)
Location: arch/x86/kernel/kprobes/core.c:909
Inline: True
Direct callers:
  - arch/x86/kernel/kprobes/core.c:kprobe_int3_handler
```
**Symbols:**

```
ffffffff810993c0-ffffffff81099442: reenter_kprobe (STB_LOCAL)
ffffffff81e4de01-ffffffff81e4de17: reenter_kprobe.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
int reenter_kprobe(struct kprobe *p, struct pt_regs *regs, struct kprobe_ctlblk *kcb);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/kprobes/core.c (ffffffff810afde0)
Location: arch/x86/kernel/kprobes/core.c:882
Inline: True
Direct callers:
  - arch/x86/kernel/kprobes/core.c:kprobe_int3_handler
```
**Symbols:**

```
ffffffff810afde0-ffffffff810afe72: reenter_kprobe (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
int reenter_kprobe(struct kprobe *p, struct pt_regs *regs, struct kprobe_ctlblk *kcb);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/kprobes/core.c (ffffffff810b2e00)
Location: arch/x86/kernel/kprobes/core.c:884
Inline: True
Direct callers:
  - arch/x86/kernel/kprobes/core.c:kprobe_int3_handler
```
**Symbols:**

```
ffffffff810b2e00-ffffffff810b2e92: reenter_kprobe (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
int reenter_kprobe(struct kprobe *p, struct pt_regs *regs, struct kprobe_ctlblk *kcb);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/kprobes/core.c (ffffffff810ba260)
Location: arch/x86/kernel/kprobes/core.c:919
Inline: True
Direct callers:
  - arch/x86/kernel/kprobes/core.c:kprobe_int3_handler
```
**Symbols:**

```
ffffffff810ba260-ffffffff810ba2f2: reenter_kprobe (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/arm64/kernel/probes/kprobes.c (ffff800010da8084)
Location: arch/arm64/kernel/probes/kprobes.c:239
Inline: True
Inline callers:
  - arch/arm64/kernel/probes/kprobes.c:kprobe_breakpoint_handler
```
</details>
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
<details>
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

```c
int reenter_kprobe(struct kprobe *p, struct pt_regs *regs, struct kprobe_ctlblk *kcb);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/kprobes/core.c (ffffffff810727f9)
Location: arch/x86/kernel/kprobes/core.c:620
Inline: True
```
**Symbols:**

```
ffffffff81071f90-ffffffff81071ffd: reenter_kprobe (STB_LOCAL)
ffffffff810727f9-ffffffff8107280f: reenter_kprobe.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

```c
int reenter_kprobe(struct kprobe *p, struct pt_regs *regs, struct kprobe_ctlblk *kcb);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/kprobes/core.c (ffffffff81062879)
Location: arch/x86/kernel/kprobes/core.c:620
Inline: True
```
**Symbols:**

```
ffffffff81062010-ffffffff8106207d: reenter_kprobe (STB_LOCAL)
ffffffff81062879-ffffffff8106288f: reenter_kprobe.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

```c
int reenter_kprobe(struct kprobe *p, struct pt_regs *regs, struct kprobe_ctlblk *kcb);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/kprobes/core.c (ffffffff810727a9)
Location: arch/x86/kernel/kprobes/core.c:620
Inline: True
```
**Symbols:**

```
ffffffff81071f40-ffffffff81071fad: reenter_kprobe (STB_LOCAL)
ffffffff810727a9-ffffffff810727bf: reenter_kprobe.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

```c
int reenter_kprobe(struct kprobe *p, struct pt_regs *regs, struct kprobe_ctlblk *kcb);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/kprobes/core.c (ffffffff810747f9)
Location: arch/x86/kernel/kprobes/core.c:620
Inline: True
```
**Symbols:**

```
ffffffff81073f90-ffffffff81073ffd: reenter_kprobe (STB_LOCAL)
ffffffff810747f9-ffffffff8107480f: reenter_kprobe.cold (STB_LOCAL)
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
