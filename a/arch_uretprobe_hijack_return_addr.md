# Function: <code>arch_uretprobe_hijack_return_addr</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
long unsigned int arch_uretprobe_hijack_return_addr(long unsigned int trampoline_vaddr, struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/uprobes.c (ffffffff810660a0)
Location: arch/x86/kernel/uprobes.c:963
Inline: False
Direct callers:
  - kernel/events/uprobes.c:uprobe_notify_resume
```
**Symbols:**

```
ffffffff810660a0-ffffffff81066194: arch_uretprobe_hijack_return_addr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
long unsigned int arch_uretprobe_hijack_return_addr(long unsigned int trampoline_vaddr, struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/uprobes.c (ffffffff81065d80)
Location: arch/x86/kernel/uprobes.c:963
Inline: False
Direct callers:
  - kernel/events/uprobes.c:uprobe_notify_resume
```
**Symbols:**

```
ffffffff81065d80-ffffffff81065eb3: arch_uretprobe_hijack_return_addr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
long unsigned int arch_uretprobe_hijack_return_addr(long unsigned int trampoline_vaddr, struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/uprobes.c (ffffffff810692b0)
Location: arch/x86/kernel/uprobes.c:963
Inline: False
Direct callers:
  - kernel/events/uprobes.c:uprobe_notify_resume
```
**Symbols:**

```
ffffffff810692b0-ffffffff810693e9: arch_uretprobe_hijack_return_addr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
long unsigned int arch_uretprobe_hijack_return_addr(long unsigned int trampoline_vaddr, struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/uprobes.c (ffffffff81068560)
Location: arch/x86/kernel/uprobes.c:963
Inline: False
Direct callers:
  - kernel/events/uprobes.c:uprobe_notify_resume
```
**Symbols:**

```
ffffffff81068560-ffffffff8106868c: arch_uretprobe_hijack_return_addr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
long unsigned int arch_uretprobe_hijack_return_addr(long unsigned int trampoline_vaddr, struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/uprobes.c (ffffffff8106c840)
Location: arch/x86/kernel/uprobes.c:966
Inline: False
Direct callers:
  - kernel/events/uprobes.c:uprobe_notify_resume
```
**Symbols:**

```
ffffffff8106c840-ffffffff8106c969: arch_uretprobe_hijack_return_addr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
long unsigned int arch_uretprobe_hijack_return_addr(long unsigned int trampoline_vaddr, struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/uprobes.c (0)
Location: arch/x86/kernel/uprobes.c:1069
Inline: False
Direct callers:
  - kernel/events/uprobes.c:uprobe_notify_resume
```
**Symbols:**

```
ffffffff8106f7f8-ffffffff8106f834: arch_uretprobe_hijack_return_addr.cold.11 (STB_LOCAL)
ffffffff8106f6d0-ffffffff8106f7c6: arch_uretprobe_hijack_return_addr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
long unsigned int arch_uretprobe_hijack_return_addr(long unsigned int trampoline_vaddr, struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/uprobes.c (0)
Location: arch/x86/kernel/uprobes.c:1069
Inline: False
Direct callers:
  - kernel/events/uprobes.c:uprobe_notify_resume
```
**Symbols:**

```
ffffffff81075868-ffffffff8107589f: arch_uretprobe_hijack_return_addr.cold.10 (STB_LOCAL)
ffffffff81075740-ffffffff81075836: arch_uretprobe_hijack_return_addr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
long unsigned int arch_uretprobe_hijack_return_addr(long unsigned int trampoline_vaddr, struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/uprobes.c (0)
Location: arch/x86/kernel/uprobes.c:1060
Inline: False
Direct callers:
  - kernel/events/uprobes.c:handler_chain
```
**Symbols:**

```
ffffffff81079418-ffffffff81079454: arch_uretprobe_hijack_return_addr.cold (STB_LOCAL)
ffffffff810792d0-ffffffff810793e2: arch_uretprobe_hijack_return_addr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
long unsigned int arch_uretprobe_hijack_return_addr(long unsigned int trampoline_vaddr, struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/uprobes.c (0)
Location: arch/x86/kernel/uprobes.c:1060
Inline: False
Direct callers:
  - kernel/events/uprobes.c:handle_swbp
```
**Symbols:**

```
ffffffff8107a468-ffffffff8107a4a4: arch_uretprobe_hijack_return_addr.cold (STB_LOCAL)
ffffffff8107a320-ffffffff8107a432: arch_uretprobe_hijack_return_addr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
long unsigned int arch_uretprobe_hijack_return_addr(long unsigned int trampoline_vaddr, struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/uprobes.c (0)
Location: arch/x86/kernel/uprobes.c:1060
Inline: False
Direct callers:
  - kernel/events/uprobes.c:prepare_uretprobe
```
**Symbols:**

```
ffffffff810818b8-ffffffff810818f4: arch_uretprobe_hijack_return_addr.cold (STB_LOCAL)
ffffffff81081780-ffffffff81081890: arch_uretprobe_hijack_return_addr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
long unsigned int arch_uretprobe_hijack_return_addr(long unsigned int trampoline_vaddr, struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/uprobes.c (0)
Location: arch/x86/kernel/uprobes.c:1064
Inline: False
Direct callers:
  - kernel/events/uprobes.c:prepare_uretprobe
```
**Symbols:**

```
ffffffff81bd82b9-ffffffff81bd82f5: arch_uretprobe_hijack_return_addr.cold (STB_LOCAL)
ffffffff81081220-ffffffff81081330: arch_uretprobe_hijack_return_addr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
long unsigned int arch_uretprobe_hijack_return_addr(long unsigned int trampoline_vaddr, struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/uprobes.c (0)
Location: arch/x86/kernel/uprobes.c:1064
Inline: False
Direct callers:
  - kernel/events/uprobes.c:prepare_uretprobe
```
**Symbols:**

```
ffffffff81bca0f6-ffffffff81bca132: arch_uretprobe_hijack_return_addr.cold (STB_LOCAL)
ffffffff81082040-ffffffff81082150: arch_uretprobe_hijack_return_addr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
long unsigned int arch_uretprobe_hijack_return_addr(long unsigned int trampoline_vaddr, struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/uprobes.c (0)
Location: arch/x86/kernel/uprobes.c:1064
Inline: False
Direct callers:
  - kernel/events/uprobes.c:prepare_uretprobe
```
**Symbols:**

```
ffffffff81c9f418-ffffffff81c9f454: arch_uretprobe_hijack_return_addr.cold (STB_LOCAL)
ffffffff810910a0-ffffffff810911b0: arch_uretprobe_hijack_return_addr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
long unsigned int arch_uretprobe_hijack_return_addr(long unsigned int trampoline_vaddr, struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/uprobes.c (0)
Location: arch/x86/kernel/uprobes.c:1064
Inline: False
Direct callers:
  - kernel/events/uprobes.c:prepare_uretprobe
```
**Symbols:**

```
ffffffff81e4ebc7-ffffffff81e4ebff: arch_uretprobe_hijack_return_addr.cold (STB_LOCAL)
ffffffff810a2190-ffffffff810a22a9: arch_uretprobe_hijack_return_addr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
long unsigned int arch_uretprobe_hijack_return_addr(long unsigned int trampoline_vaddr, struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/uprobes.c (ffffffff810ba2e0)
Location: arch/x86/kernel/uprobes.c:1066
Inline: False
Direct callers:
  - kernel/events/uprobes.c:prepare_uretprobe
```
**Symbols:**

```
ffffffff810ba2e0-ffffffff810ba42d: arch_uretprobe_hijack_return_addr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
long unsigned int arch_uretprobe_hijack_return_addr(long unsigned int trampoline_vaddr, struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/uprobes.c (ffffffff810bd4b0)
Location: arch/x86/kernel/uprobes.c:1066
Inline: False
Direct callers:
  - kernel/events/uprobes.c:prepare_uretprobe
```
**Symbols:**

```
ffffffff810bd4b0-ffffffff810bd5fd: arch_uretprobe_hijack_return_addr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
long unsigned int arch_uretprobe_hijack_return_addr(long unsigned int trampoline_vaddr, struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/uprobes.c (ffffffff810c4630)
Location: arch/x86/kernel/uprobes.c:1066
Inline: False
Direct callers:
  - kernel/events/uprobes.c:prepare_uretprobe
```
**Symbols:**

```
ffffffff810c4630-ffffffff810c477d: arch_uretprobe_hijack_return_addr (STB_GLOBAL)
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
long unsigned int arch_uretprobe_hijack_return_addr(long unsigned int trampoline_vaddr, struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/arm64/kernel/probes/uprobes.c (ffff8000100aca38)
Location: arch/arm64/kernel/probes/uprobes.c:150
Inline: False
Direct callers:
  - kernel/events/uprobes.c:handler_chain
```
**Symbols:**

```
ffff8000100aca38-ffff8000100aca68: arch_uretprobe_hijack_return_addr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
long unsigned int arch_uretprobe_hijack_return_addr(long unsigned int trampoline_vaddr, struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/arm/probes/uprobes/core.c (c0327a94)
Location: arch/arm/probes/uprobes/core.c:61
Inline: False
Direct callers:
  - kernel/events/uprobes.c:handle_swbp
```
**Symbols:**

```
c0327a94-c0327ab8: arch_uretprobe_hijack_return_addr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
long unsigned int arch_uretprobe_hijack_return_addr(long unsigned int trampoline_vaddr, struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/powerpc/kernel/uprobes.c (c0000000000685e0)
Location: arch/powerpc/kernel/uprobes.c:184
Inline: False
Direct callers:
  - kernel/events/uprobes.c:handle_swbp
```
**Symbols:**

```
c0000000000685e0-c0000000000685f8: arch_uretprobe_hijack_return_addr (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
long unsigned int arch_uretprobe_hijack_return_addr(long unsigned int trampoline_vaddr, struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/uprobes.c (0)
Location: arch/x86/kernel/uprobes.c:1060
Inline: False
Direct callers:
  - kernel/events/uprobes.c:handle_swbp
```
**Symbols:**

```
ffffffff81079468-ffffffff810794a4: arch_uretprobe_hijack_return_addr.cold (STB_LOCAL)
ffffffff81079320-ffffffff81079432: arch_uretprobe_hijack_return_addr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
long unsigned int arch_uretprobe_hijack_return_addr(long unsigned int trampoline_vaddr, struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/uprobes.c (0)
Location: arch/x86/kernel/uprobes.c:1060
Inline: False
Direct callers:
  - kernel/events/uprobes.c:handle_swbp
```
**Symbols:**

```
ffffffff81068be8-ffffffff81068c24: arch_uretprobe_hijack_return_addr.cold (STB_LOCAL)
ffffffff81068ad0-ffffffff81068bbe: arch_uretprobe_hijack_return_addr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
long unsigned int arch_uretprobe_hijack_return_addr(long unsigned int trampoline_vaddr, struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/uprobes.c (0)
Location: arch/x86/kernel/uprobes.c:1060
Inline: False
Direct callers:
  - kernel/events/uprobes.c:handle_swbp
```
**Symbols:**

```
ffffffff81079418-ffffffff81079454: arch_uretprobe_hijack_return_addr.cold (STB_LOCAL)
ffffffff810792d0-ffffffff810793e2: arch_uretprobe_hijack_return_addr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
long unsigned int arch_uretprobe_hijack_return_addr(long unsigned int trampoline_vaddr, struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/uprobes.c (0)
Location: arch/x86/kernel/uprobes.c:1060
Inline: False
Direct callers:
  - kernel/events/uprobes.c:handle_swbp
```
**Symbols:**

```
ffffffff8107b518-ffffffff8107b554: arch_uretprobe_hijack_return_addr.cold (STB_LOCAL)
ffffffff8107b3d0-ffffffff8107b4e2: arch_uretprobe_hijack_return_addr (STB_GLOBAL)
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
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
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
