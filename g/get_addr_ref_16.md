# Function: <code>get_addr_ref_16</code>

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
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/lib/insn-eval.c (ffffffff81983ab3)
Location: arch/x86/lib/insn-eval.c:1138
Inline: True
Inline callers:
  - arch/x86/lib/insn-eval.c:insn_get_addr_ref
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/lib/insn-eval.c (ffffffff819dff69)
Location: arch/x86/lib/insn-eval.c:1138
Inline: True
Inline callers:
  - arch/x86/lib/insn-eval.c:insn_get_addr_ref
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/lib/insn-eval.c (ffffffff81a1aef9)
Location: arch/x86/lib/insn-eval.c:1138
Inline: True
Inline callers:
  - arch/x86/lib/insn-eval.c:insn_get_addr_ref
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/lib/insn-eval.c (ffffffff81a8ac99)
Location: arch/x86/lib/insn-eval.c:1141
Inline: True
Inline callers:
  - arch/x86/lib/insn-eval.c:insn_get_addr_ref
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/lib/insn-eval.c (ffffffff81ac1f59)
Location: arch/x86/lib/insn-eval.c:1141
Inline: True
Inline callers:
  - arch/x86/lib/insn-eval.c:insn_get_addr_ref
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void *get_addr_ref_16(struct insn *insn, struct pt_regs *regs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/insn-eval.c (ffffffff815fe320)
Location: arch/x86/lib/insn-eval.c:1145
Inline: False
Direct callers:
  - arch/x86/lib/insn-eval.c:insn_get_addr_ref
```
**Symbols:**

```
ffffffff815fe320-ffffffff815fe476: get_addr_ref_16 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void *get_addr_ref_16(struct insn *insn, struct pt_regs *regs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/insn-eval.c (ffffffff81623130)
Location: arch/x86/lib/insn-eval.c:1190
Inline: False
Direct callers:
  - arch/x86/lib/insn-eval.c:insn_get_addr_ref
```
**Symbols:**

```
ffffffff81623130-ffffffff81623286: get_addr_ref_16 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void *get_addr_ref_16(struct insn *insn, struct pt_regs *regs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/insn-eval.c (ffffffff816069e0)
Location: arch/x86/lib/insn-eval.c:1192
Inline: False
Direct callers:
  - arch/x86/lib/insn-eval.c:insn_get_addr_ref
```
**Symbols:**

```
ffffffff816069e0-ffffffff81606b36: get_addr_ref_16 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void *get_addr_ref_16(struct insn *insn, struct pt_regs *regs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/insn-eval.c (ffffffff81675440)
Location: arch/x86/lib/insn-eval.c:1192
Inline: False
Direct callers:
  - arch/x86/lib/insn-eval.c:insn_get_addr_ref
```
**Symbols:**

```
ffffffff81675440-ffffffff81675596: get_addr_ref_16 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void *get_addr_ref_16(struct insn *insn, struct pt_regs *regs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/insn-eval.c (ffffffff8178ff20)
Location: arch/x86/lib/insn-eval.c:1234
Inline: False
Direct callers:
  - arch/x86/lib/insn-eval.c:insn_get_addr_ref
```
**Symbols:**

```
ffffffff8178ff20-ffffffff8179009e: get_addr_ref_16 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void *get_addr_ref_16(struct insn *insn, struct pt_regs *regs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/insn-eval.c (ffffffff8204dab0)
Location: arch/x86/lib/insn-eval.c:1234
Inline: False
Direct callers:
  - arch/x86/lib/insn-eval.c:insn_get_addr_ref
```
**Symbols:**

```
ffffffff8204dab0-ffffffff8204dc2e: get_addr_ref_16 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void *get_addr_ref_16(struct insn *insn, struct pt_regs *regs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/insn-eval.c (ffffffff820cc350)
Location: arch/x86/lib/insn-eval.c:1234
Inline: False
Direct callers:
  - arch/x86/lib/insn-eval.c:insn_get_addr_ref
```
**Symbols:**

```
ffffffff820cc350-ffffffff820cc4cf: get_addr_ref_16 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void *get_addr_ref_16(struct insn *insn, struct pt_regs *regs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/lib/insn-eval.c (ffffffff821a6b80)
Location: arch/x86/lib/insn-eval.c:1234
Inline: False
Direct callers:
  - arch/x86/lib/insn-eval.c:insn_get_addr_ref
```
**Symbols:**

```
ffffffff821a6b80-ffffffff821a6cff: get_addr_ref_16 (STB_LOCAL)
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
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/lib/insn-eval.c (ffffffff81a60da9)
Location: arch/x86/lib/insn-eval.c:1141
Inline: True
Inline callers:
  - arch/x86/lib/insn-eval.c:insn_get_addr_ref
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/lib/insn-eval.c (ffffffff81a1de29)
Location: arch/x86/lib/insn-eval.c:1141
Inline: True
Inline callers:
  - arch/x86/lib/insn-eval.c:insn_get_addr_ref
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/lib/insn-eval.c (ffffffff81acd199)
Location: arch/x86/lib/insn-eval.c:1141
Inline: True
Inline callers:
  - arch/x86/lib/insn-eval.c:insn_get_addr_ref
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/lib/insn-eval.c (ffffffff81ad96a9)
Location: arch/x86/lib/insn-eval.c:1141
Inline: True
Inline callers:
  - arch/x86/lib/insn-eval.c:insn_get_addr_ref
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
