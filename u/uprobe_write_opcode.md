# Function: <code>uprobe_write_opcode</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int uprobe_write_opcode(struct mm_struct *mm, long unsigned int vaddr, uprobe_opcode_t opcode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/uprobes.c (ffffffff81187530)
Location: kernel/events/uprobes.c:292
Inline: False
Direct callers:
  - kernel/events/uprobes.c:set_swbp
  - kernel/events/uprobes.c:set_orig_insn
```
**Symbols:**

```
ffffffff81187530-ffffffff811879ec: uprobe_write_opcode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int uprobe_write_opcode(struct mm_struct *mm, long unsigned int vaddr, uprobe_opcode_t opcode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/uprobes.c (ffffffff81199ad0)
Location: kernel/events/uprobes.c:294
Inline: False
Direct callers:
  - kernel/events/uprobes.c:set_orig_insn
  - kernel/events/uprobes.c:set_swbp
```
**Symbols:**

```
ffffffff81199ad0-ffffffff8119a09f: uprobe_write_opcode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int uprobe_write_opcode(struct mm_struct *mm, long unsigned int vaddr, uprobe_opcode_t opcode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/uprobes.c (ffffffff811a9220)
Location: kernel/events/uprobes.c:294
Inline: False
Direct callers:
  - kernel/events/uprobes.c:set_orig_insn
  - kernel/events/uprobes.c:set_swbp
```
**Symbols:**

```
ffffffff811a9220-ffffffff811a980c: uprobe_write_opcode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int uprobe_write_opcode(struct mm_struct *mm, long unsigned int vaddr, uprobe_opcode_t opcode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/uprobes.c (ffffffff811b0790)
Location: kernel/events/uprobes.c:302
Inline: False
Direct callers:
  - kernel/events/uprobes.c:set_orig_insn
  - kernel/events/uprobes.c:set_swbp
```
**Symbols:**

```
ffffffff811b0790-ffffffff811b0caf: uprobe_write_opcode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int uprobe_write_opcode(struct mm_struct *mm, long unsigned int vaddr, uprobe_opcode_t opcode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/uprobes.c (ffffffff811c42a0)
Location: kernel/events/uprobes.c:302
Inline: False
Direct callers:
  - kernel/events/uprobes.c:set_orig_insn
  - kernel/events/uprobes.c:set_swbp
```
**Symbols:**

```
ffffffff811c42a0-ffffffff811c4837: uprobe_write_opcode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int uprobe_write_opcode(struct mm_struct *mm, long unsigned int vaddr, uprobe_opcode_t opcode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/uprobes.c (ffffffff811e47b0)
Location: kernel/events/uprobes.c:302
Inline: False
Direct callers:
  - kernel/events/uprobes.c:set_orig_insn
  - kernel/events/uprobes.c:set_swbp
```
**Symbols:**

```
ffffffff811e47b0-ffffffff811e4d7b: uprobe_write_opcode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int uprobe_write_opcode(struct arch_uprobe *auprobe, struct mm_struct *mm, long unsigned int vaddr, uprobe_opcode_t opcode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/uprobes.c (ffffffff811f5600)
Location: kernel/events/uprobes.c:472
Inline: False
Direct callers:
  - kernel/events/uprobes.c:set_orig_insn
  - kernel/events/uprobes.c:set_swbp
```
**Symbols:**

```
ffffffff811f5600-ffffffff811f5929: uprobe_write_opcode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int uprobe_write_opcode(struct arch_uprobe *auprobe, struct mm_struct *mm, long unsigned int vaddr, uprobe_opcode_t opcode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/uprobes.c (ffffffff8120d370)
Location: kernel/events/uprobes.c:460
Inline: False
Direct callers:
  - kernel/events/uprobes.c:set_orig_insn
  - kernel/events/uprobes.c:set_swbp
```
**Symbols:**

```
ffffffff8120d370-ffffffff8120d6af: uprobe_write_opcode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int uprobe_write_opcode(struct arch_uprobe *auprobe, struct mm_struct *mm, long unsigned int vaddr, uprobe_opcode_t opcode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/uprobes.c (ffffffff8121a700)
Location: kernel/events/uprobes.c:469
Inline: False
Direct callers:
  - kernel/events/uprobes.c:set_orig_insn
  - kernel/events/uprobes.c:set_swbp
```
**Symbols:**

```
ffffffff8121a700-ffffffff8121acd4: uprobe_write_opcode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int uprobe_write_opcode(struct arch_uprobe *auprobe, struct mm_struct *mm, long unsigned int vaddr, uprobe_opcode_t opcode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/uprobes.c (ffffffff81247120)
Location: kernel/events/uprobes.c:463
Inline: False
Direct callers:
  - kernel/events/uprobes.c:set_orig_insn
  - kernel/events/uprobes.c:set_swbp
```
**Symbols:**

```
ffffffff81247120-ffffffff812476f8: uprobe_write_opcode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int uprobe_write_opcode(struct arch_uprobe *auprobe, struct mm_struct *mm, long unsigned int vaddr, uprobe_opcode_t opcode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/uprobes.c (ffffffff812517a0)
Location: kernel/events/uprobes.c:463
Inline: False
Direct callers:
  - kernel/events/uprobes.c:set_orig_insn
  - kernel/events/uprobes.c:set_swbp
```
**Symbols:**

```
ffffffff812517a0-ffffffff81251d68: uprobe_write_opcode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int uprobe_write_opcode(struct arch_uprobe *auprobe, struct mm_struct *mm, long unsigned int vaddr, uprobe_opcode_t opcode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/uprobes.c (ffffffff812555f0)
Location: kernel/events/uprobes.c:463
Inline: False
Direct callers:
  - kernel/events/uprobes.c:set_orig_insn
  - kernel/events/uprobes.c:set_swbp
```
**Symbols:**

```
ffffffff812555f0-ffffffff81255baa: uprobe_write_opcode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int uprobe_write_opcode(struct arch_uprobe *auprobe, struct mm_struct *mm, long unsigned int vaddr, uprobe_opcode_t opcode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/uprobes.c (ffffffff812912a0)
Location: kernel/events/uprobes.c:464
Inline: False
Direct callers:
  - kernel/events/uprobes.c:set_orig_insn
  - kernel/events/uprobes.c:set_swbp
```
**Symbols:**

```
ffffffff812912a0-ffffffff81291857: uprobe_write_opcode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int uprobe_write_opcode(struct arch_uprobe *auprobe, struct mm_struct *mm, long unsigned int vaddr, uprobe_opcode_t opcode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/uprobes.c (ffffffff812e6860)
Location: kernel/events/uprobes.c:458
Inline: False
Direct callers:
  - kernel/events/uprobes.c:set_orig_insn
  - kernel/events/uprobes.c:set_swbp
```
**Symbols:**

```
ffffffff812e6860-ffffffff812e6fb2: uprobe_write_opcode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int uprobe_write_opcode(struct arch_uprobe *auprobe, struct mm_struct *mm, long unsigned int vaddr, uprobe_opcode_t opcode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/uprobes.c (ffffffff81350350)
Location: kernel/events/uprobes.c:461
Inline: False
Direct callers:
  - kernel/events/uprobes.c:set_orig_insn
  - kernel/events/uprobes.c:set_swbp
```
**Symbols:**

```
ffffffff81350350-ffffffff81350a94: uprobe_write_opcode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int uprobe_write_opcode(struct arch_uprobe *auprobe, struct mm_struct *mm, long unsigned int vaddr, uprobe_opcode_t opcode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/uprobes.c (ffffffff81381550)
Location: kernel/events/uprobes.c:459
Inline: False
Direct callers:
  - kernel/events/uprobes.c:set_orig_insn
  - kernel/events/uprobes.c:set_swbp
```
**Symbols:**

```
ffffffff81381550-ffffffff81381cfd: uprobe_write_opcode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int uprobe_write_opcode(struct arch_uprobe *auprobe, struct mm_struct *mm, long unsigned int vaddr, uprobe_opcode_t opcode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/uprobes.c (ffffffff813aa8f0)
Location: kernel/events/uprobes.c:459
Inline: False
Direct callers:
  - kernel/events/uprobes.c:set_orig_insn
  - kernel/events/uprobes.c:set_swbp
```
**Symbols:**

```
ffffffff813aa8f0-ffffffff813ab0d2: uprobe_write_opcode (STB_GLOBAL)
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
int uprobe_write_opcode(struct arch_uprobe *auprobe, struct mm_struct *mm, long unsigned int vaddr, uprobe_opcode_t opcode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/uprobes.c (ffff8000102a5b58)
Location: kernel/events/uprobes.c:469
Inline: False
Direct callers:
  - kernel/events/uprobes.c:set_orig_insn
  - kernel/events/uprobes.c:set_swbp
```
**Symbols:**

```
ffff8000102a5b58-ffff8000102a6044: uprobe_write_opcode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int uprobe_write_opcode(struct arch_uprobe *auprobe, struct mm_struct *mm, long unsigned int vaddr, uprobe_opcode_t opcode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/uprobes.c (c04d4d38)
Location: kernel/events/uprobes.c:469
Inline: False
Direct callers:
  - arch/arm/probes/uprobes/core.c:set_swbp
  - kernel/events/uprobes.c:set_orig_insn
  - kernel/events/uprobes.c:set_swbp
```
**Symbols:**

```
c04d4d38-c04d5218: uprobe_write_opcode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int uprobe_write_opcode(struct arch_uprobe *auprobe, struct mm_struct *mm, long unsigned int vaddr, uprobe_opcode_t opcode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/uprobes.c (c000000000358a60)
Location: kernel/events/uprobes.c:469
Inline: False
Direct callers:
  - kernel/events/uprobes.c:set_orig_insn
  - kernel/events/uprobes.c:set_swbp
```
**Symbols:**

```
c000000000358a60-c0000000003591fc: uprobe_write_opcode (STB_GLOBAL)
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
<summary>In <code>aws</code>: ✅</summary>

```c
int uprobe_write_opcode(struct arch_uprobe *auprobe, struct mm_struct *mm, long unsigned int vaddr, uprobe_opcode_t opcode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/uprobes.c (ffffffff81212d50)
Location: kernel/events/uprobes.c:469
Inline: False
Direct callers:
  - kernel/events/uprobes.c:set_orig_insn
  - kernel/events/uprobes.c:set_swbp
```
**Symbols:**

```
ffffffff81212d50-ffffffff81213324: uprobe_write_opcode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int uprobe_write_opcode(struct arch_uprobe *auprobe, struct mm_struct *mm, long unsigned int vaddr, uprobe_opcode_t opcode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/uprobes.c (ffffffff81205ac0)
Location: kernel/events/uprobes.c:469
Inline: False
Direct callers:
  - kernel/events/uprobes.c:set_orig_insn
  - kernel/events/uprobes.c:set_swbp
```
**Symbols:**

```
ffffffff81205ac0-ffffffff81206094: uprobe_write_opcode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int uprobe_write_opcode(struct arch_uprobe *auprobe, struct mm_struct *mm, long unsigned int vaddr, uprobe_opcode_t opcode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/uprobes.c (ffffffff81210af0)
Location: kernel/events/uprobes.c:469
Inline: False
Direct callers:
  - kernel/events/uprobes.c:set_orig_insn
  - kernel/events/uprobes.c:set_swbp
```
**Symbols:**

```
ffffffff81210af0-ffffffff812110c4: uprobe_write_opcode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int uprobe_write_opcode(struct arch_uprobe *auprobe, struct mm_struct *mm, long unsigned int vaddr, uprobe_opcode_t opcode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/events/uprobes.c (ffffffff8121fa00)
Location: kernel/events/uprobes.c:469
Inline: False
Direct callers:
  - kernel/events/uprobes.c:set_orig_insn
  - kernel/events/uprobes.c:set_swbp
```
**Symbols:**

```
ffffffff8121fa00-ffffffff8122001d: uprobe_write_opcode (STB_GLOBAL)
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
<b>Param added. </b>
<code>struct arch_uprobe *auprobe</code>
</li>
<li>
<b>Param reordered. </b>
<code>mm, vaddr, opcode</code> ➡️ <code>auprobe, mm, vaddr, opcode</code>
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
