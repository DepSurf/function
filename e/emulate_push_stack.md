# Function: <code>emulate_push_stack</code>

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
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/uprobes.c (ffffffff8106ec20)
Location: arch/x86/kernel/uprobes.c:535
Inline: True
Direct callers:
  - arch/x86/kernel/uprobes.c:push_emulate_op
  - arch/x86/kernel/uprobes.c:branch_emulate_op
  - arch/x86/kernel/uprobes.c:default_post_xol_op
```
**Symbols:**

```
ffffffff8106ec20-ffffffff8106ec99: emulate_push_stack.isra.7 (STB_LOCAL)
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
In arch/x86/kernel/uprobes.c (ffffffff81074c30)
Location: arch/x86/kernel/uprobes.c:535
Inline: True
Direct callers:
  - arch/x86/kernel/uprobes.c:push_emulate_op
  - arch/x86/kernel/uprobes.c:branch_emulate_op
  - arch/x86/kernel/uprobes.c:default_post_xol_op
```
**Symbols:**

```
ffffffff81074c30-ffffffff81074ca9: emulate_push_stack.isra.6 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int emulate_push_stack(struct pt_regs *regs, long unsigned int val);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/uprobes.c (ffffffff810787f0)
Location: arch/x86/kernel/uprobes.c:525
Inline: False
Direct callers:
  - arch/x86/kernel/uprobes.c:push_emulate_op
  - arch/x86/kernel/uprobes.c:branch_emulate_op
  - arch/x86/kernel/uprobes.c:default_post_xol_op
```
**Symbols:**

```
ffffffff810787f0-ffffffff8107887d: emulate_push_stack (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int emulate_push_stack(struct pt_regs *regs, long unsigned int val);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/uprobes.c (ffffffff81079840)
Location: arch/x86/kernel/uprobes.c:525
Inline: False
Direct callers:
  - arch/x86/kernel/uprobes.c:push_emulate_op
  - arch/x86/kernel/uprobes.c:branch_emulate_op
  - arch/x86/kernel/uprobes.c:default_post_xol_op
```
**Symbols:**

```
ffffffff81079840-ffffffff810798cd: emulate_push_stack (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int emulate_push_stack(struct pt_regs *regs, long unsigned int val);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/uprobes.c (ffffffff81080b90)
Location: arch/x86/kernel/uprobes.c:525
Inline: False
Direct callers:
  - arch/x86/kernel/uprobes.c:push_emulate_op
  - arch/x86/kernel/uprobes.c:branch_emulate_op
  - arch/x86/kernel/uprobes.c:default_post_xol_op
```
**Symbols:**

```
ffffffff81080b90-ffffffff81080c1f: emulate_push_stack (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int emulate_push_stack(struct pt_regs *regs, long unsigned int val);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/uprobes.c (ffffffff81080640)
Location: arch/x86/kernel/uprobes.c:526
Inline: False
Direct callers:
  - arch/x86/kernel/uprobes.c:push_emulate_op
  - arch/x86/kernel/uprobes.c:branch_emulate_op
  - arch/x86/kernel/uprobes.c:default_post_xol_op
```
**Symbols:**

```
ffffffff81080640-ffffffff810806cf: emulate_push_stack (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int emulate_push_stack(struct pt_regs *regs, long unsigned int val);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/uprobes.c (ffffffff810814b0)
Location: arch/x86/kernel/uprobes.c:526
Inline: False
Direct callers:
  - arch/x86/kernel/uprobes.c:push_emulate_op
  - arch/x86/kernel/uprobes.c:branch_emulate_op
  - arch/x86/kernel/uprobes.c:default_post_xol_op
```
**Symbols:**

```
ffffffff810814b0-ffffffff8108153f: emulate_push_stack (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int emulate_push_stack(struct pt_regs *regs, long unsigned int val);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/uprobes.c (ffffffff810904d0)
Location: arch/x86/kernel/uprobes.c:526
Inline: False
Direct callers:
  - arch/x86/kernel/uprobes.c:push_emulate_op
  - arch/x86/kernel/uprobes.c:branch_emulate_op
  - arch/x86/kernel/uprobes.c:default_post_xol_op
```
**Symbols:**

```
ffffffff810904d0-ffffffff8109055f: emulate_push_stack (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int emulate_push_stack(struct pt_regs *regs, long unsigned int val);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/uprobes.c (ffffffff810a14e0)
Location: arch/x86/kernel/uprobes.c:526
Inline: False
Direct callers:
  - arch/x86/kernel/uprobes.c:push_emulate_op
  - arch/x86/kernel/uprobes.c:branch_emulate_op
  - arch/x86/kernel/uprobes.c:default_post_xol_op
```
**Symbols:**

```
ffffffff810a14e0-ffffffff810a1577: emulate_push_stack (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int emulate_push_stack(struct pt_regs *regs, long unsigned int val);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/uprobes.c (ffffffff810b9640)
Location: arch/x86/kernel/uprobes.c:526
Inline: False
Direct callers:
  - arch/x86/kernel/uprobes.c:push_emulate_op
  - arch/x86/kernel/uprobes.c:branch_emulate_op
  - arch/x86/kernel/uprobes.c:default_post_xol_op
```
**Symbols:**

```
ffffffff810b9640-ffffffff810b96d7: emulate_push_stack (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int emulate_push_stack(struct pt_regs *regs, long unsigned int val);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/uprobes.c (ffffffff810bc690)
Location: arch/x86/kernel/uprobes.c:526
Inline: False
Direct callers:
  - arch/x86/kernel/uprobes.c:push_emulate_op
  - arch/x86/kernel/uprobes.c:branch_emulate_op
  - arch/x86/kernel/uprobes.c:default_post_xol_op
```
**Symbols:**

```
ffffffff810bc690-ffffffff810bc727: emulate_push_stack (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int emulate_push_stack(struct pt_regs *regs, long unsigned int val);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/uprobes.c (ffffffff810c3810)
Location: arch/x86/kernel/uprobes.c:526
Inline: False
Direct callers:
  - arch/x86/kernel/uprobes.c:push_emulate_op
  - arch/x86/kernel/uprobes.c:branch_emulate_op
  - arch/x86/kernel/uprobes.c:default_post_xol_op
```
**Symbols:**

```
ffffffff810c3810-ffffffff810c38a7: emulate_push_stack (STB_LOCAL)
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
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
int emulate_push_stack(struct pt_regs *regs, long unsigned int val);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/uprobes.c (ffffffff81078840)
Location: arch/x86/kernel/uprobes.c:525
Inline: False
Direct callers:
  - arch/x86/kernel/uprobes.c:push_emulate_op
  - arch/x86/kernel/uprobes.c:branch_emulate_op
  - arch/x86/kernel/uprobes.c:default_post_xol_op
```
**Symbols:**

```
ffffffff81078840-ffffffff810788cd: emulate_push_stack (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int emulate_push_stack(struct pt_regs *regs, long unsigned int val);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/uprobes.c (ffffffff81068030)
Location: arch/x86/kernel/uprobes.c:525
Inline: False
Direct callers:
  - arch/x86/kernel/uprobes.c:push_emulate_op
  - arch/x86/kernel/uprobes.c:branch_emulate_op
  - arch/x86/kernel/uprobes.c:default_post_xol_op
```
**Symbols:**

```
ffffffff81068030-ffffffff810680a8: emulate_push_stack (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int emulate_push_stack(struct pt_regs *regs, long unsigned int val);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/uprobes.c (ffffffff810787f0)
Location: arch/x86/kernel/uprobes.c:525
Inline: False
Direct callers:
  - arch/x86/kernel/uprobes.c:push_emulate_op
  - arch/x86/kernel/uprobes.c:branch_emulate_op
  - arch/x86/kernel/uprobes.c:default_post_xol_op
```
**Symbols:**

```
ffffffff810787f0-ffffffff8107887d: emulate_push_stack (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int emulate_push_stack(struct pt_regs *regs, long unsigned int val);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/uprobes.c (ffffffff8107a8f0)
Location: arch/x86/kernel/uprobes.c:525
Inline: False
Direct callers:
  - arch/x86/kernel/uprobes.c:push_emulate_op
  - arch/x86/kernel/uprobes.c:branch_emulate_op
  - arch/x86/kernel/uprobes.c:default_post_xol_op
```
**Symbols:**

```
ffffffff8107a8f0-ffffffff8107a97d: emulate_push_stack (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
