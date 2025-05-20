# Function: <code>insn_jump_into_range</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/kprobes/opt.c (ffffffff810600cd)
Location: arch/x86/kernel/kprobes/opt.c:202
Inline: True
Inline callers:
  - arch/x86/kernel/kprobes/opt.c:can_optimize
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/kprobes/opt.c (ffffffff8105fecd)
Location: arch/x86/kernel/kprobes/opt.c:203
Inline: True
Inline callers:
  - arch/x86/kernel/kprobes/opt.c:can_optimize
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/kprobes/opt.c (ffffffff81062f6d)
Location: arch/x86/kernel/kprobes/opt.c:203
Inline: True
Inline callers:
  - arch/x86/kernel/kprobes/opt.c:can_optimize
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/kprobes/opt.c (ffffffff81061fb6)
Location: arch/x86/kernel/kprobes/opt.c:215
Inline: True
Inline callers:
  - arch/x86/kernel/kprobes/opt.c:can_optimize
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int insn_jump_into_range(struct insn *insn, long unsigned int start, int len);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/kprobes/opt.c (ffffffff81065f40)
Location: arch/x86/kernel/kprobes/opt.c:215
Inline: True
Direct callers:
  - arch/x86/kernel/kprobes/opt.c:can_optimize
  - arch/x86/kernel/kprobes/opt.c:can_optimize
```
**Symbols:**

```
ffffffff81065f40-ffffffff81065f9d: insn_jump_into_range (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
int insn_jump_into_range(struct insn *insn, long unsigned int start, int len);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/kprobes/opt.c (ffffffff81068b00)
Location: arch/x86/kernel/kprobes/opt.c:215
Inline: True
Direct callers:
  - arch/x86/kernel/kprobes/opt.c:can_optimize
  - arch/x86/kernel/kprobes/opt.c:can_optimize
```
**Symbols:**

```
ffffffff81068b00-ffffffff81068b5b: insn_jump_into_range (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int insn_jump_into_range(struct insn *insn, long unsigned int start, int len);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/kprobes/opt.c (ffffffff8106e8c0)
Location: arch/x86/kernel/kprobes/opt.c:220
Inline: True
Direct callers:
  - arch/x86/kernel/kprobes/opt.c:can_optimize
  - arch/x86/kernel/kprobes/opt.c:can_optimize
```
**Symbols:**

```
ffffffff8106e8c0-ffffffff8106e91b: insn_jump_into_range (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
int insn_jump_into_range(struct insn *insn, long unsigned int start, int len);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/kprobes/opt.c (ffffffff81072930)
Location: arch/x86/kernel/kprobes/opt.c:206
Inline: True
Direct callers:
  - arch/x86/kernel/kprobes/opt.c:can_optimize
  - arch/x86/kernel/kprobes/opt.c:can_optimize
```
**Symbols:**

```
ffffffff81072930-ffffffff810729a1: insn_jump_into_range (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int insn_jump_into_range(struct insn *insn, long unsigned int start, int len);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/kprobes/opt.c (ffffffff81073920)
Location: arch/x86/kernel/kprobes/opt.c:206
Inline: True
Direct callers:
  - arch/x86/kernel/kprobes/opt.c:can_optimize
  - arch/x86/kernel/kprobes/opt.c:can_optimize
```
**Symbols:**

```
ffffffff81073920-ffffffff81073991: insn_jump_into_range (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int insn_jump_into_range(struct insn *insn, long unsigned int start, int len);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/kprobes/opt.c (ffffffff8107ab20)
Location: arch/x86/kernel/kprobes/opt.c:227
Inline: True
Direct callers:
  - arch/x86/kernel/kprobes/opt.c:can_optimize
  - arch/x86/kernel/kprobes/opt.c:can_optimize
```
**Symbols:**

```
ffffffff8107ab20-ffffffff8107ab91: insn_jump_into_range (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int insn_jump_into_range(struct insn *insn, long unsigned int start, int len);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/kprobes/opt.c (ffffffff8107a8b0)
Location: arch/x86/kernel/kprobes/opt.c:229
Inline: True
Direct callers:
  - arch/x86/kernel/kprobes/opt.c:can_optimize
  - arch/x86/kernel/kprobes/opt.c:can_optimize
```
**Symbols:**

```
ffffffff8107a8b0-ffffffff8107a921: insn_jump_into_range (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int insn_jump_into_range(struct insn *insn, long unsigned int start, int len);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/kprobes/opt.c (ffffffff8107bab0)
Location: arch/x86/kernel/kprobes/opt.c:229
Inline: True
Direct callers:
  - arch/x86/kernel/kprobes/opt.c:can_optimize
  - arch/x86/kernel/kprobes/opt.c:can_optimize
```
**Symbols:**

```
ffffffff8107bab0-ffffffff8107bb0d: insn_jump_into_range (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int insn_jump_into_range(struct insn *insn, long unsigned int start, int len);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/kprobes/opt.c (ffffffff81089c20)
Location: arch/x86/kernel/kprobes/opt.c:229
Inline: True
Direct callers:
  - arch/x86/kernel/kprobes/opt.c:can_optimize
  - arch/x86/kernel/kprobes/opt.c:can_optimize
```
**Symbols:**

```
ffffffff81089c20-ffffffff81089c7d: insn_jump_into_range (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int insn_jump_into_range(struct insn *insn, long unsigned int start, int len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/kprobes/opt.c (ffffffff81099e30)
Location: arch/x86/kernel/kprobes/opt.c:236
Inline: False
Direct callers:
  - arch/x86/kernel/kprobes/opt.c:can_optimize
  - arch/x86/kernel/kprobes/opt.c:can_optimize
```
**Symbols:**

```
ffffffff81099e30-ffffffff81099ea9: insn_jump_into_range (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int insn_jump_into_range(struct insn *insn, long unsigned int start, int len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/kprobes/opt.c (ffffffff810b07c0)
Location: arch/x86/kernel/kprobes/opt.c:237
Inline: False
Direct callers:
  - arch/x86/kernel/kprobes/opt.c:can_optimize
  - arch/x86/kernel/kprobes/opt.c:can_optimize
```
**Symbols:**

```
ffffffff810b07c0-ffffffff810b0839: insn_jump_into_range (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/kprobes/opt.c (ffffffff810b3bc5)
Location: arch/x86/kernel/kprobes/opt.c:237
Inline: True
Inline callers:
  - arch/x86/kernel/kprobes/opt.c:can_optimize
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/kprobes/opt.c (ffffffff810bb025)
Location: arch/x86/kernel/kprobes/opt.c:237
Inline: True
Inline callers:
  - arch/x86/kernel/kprobes/opt.c:can_optimize
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
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
int insn_jump_into_range(struct insn *insn, long unsigned int start, int len);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/kprobes/opt.c (ffffffff81072920)
Location: arch/x86/kernel/kprobes/opt.c:206
Inline: True
Direct callers:
  - arch/x86/kernel/kprobes/opt.c:can_optimize
  - arch/x86/kernel/kprobes/opt.c:can_optimize
```
**Symbols:**

```
ffffffff81072920-ffffffff81072991: insn_jump_into_range (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int insn_jump_into_range(struct insn *insn, long unsigned int start, int len);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/kprobes/opt.c (ffffffff810629a0)
Location: arch/x86/kernel/kprobes/opt.c:206
Inline: True
Direct callers:
  - arch/x86/kernel/kprobes/opt.c:can_optimize
  - arch/x86/kernel/kprobes/opt.c:can_optimize
```
**Symbols:**

```
ffffffff810629a0-ffffffff81062a11: insn_jump_into_range (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int insn_jump_into_range(struct insn *insn, long unsigned int start, int len);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/kprobes/opt.c (ffffffff810728d0)
Location: arch/x86/kernel/kprobes/opt.c:206
Inline: True
Direct callers:
  - arch/x86/kernel/kprobes/opt.c:can_optimize
  - arch/x86/kernel/kprobes/opt.c:can_optimize
```
**Symbols:**

```
ffffffff810728d0-ffffffff81072941: insn_jump_into_range (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int insn_jump_into_range(struct insn *insn, long unsigned int start, int len);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/kprobes/opt.c (ffffffff81074920)
Location: arch/x86/kernel/kprobes/opt.c:206
Inline: True
Direct callers:
  - arch/x86/kernel/kprobes/opt.c:can_optimize
  - arch/x86/kernel/kprobes/opt.c:can_optimize
```
**Symbols:**

```
ffffffff81074920-ffffffff81074991: insn_jump_into_range (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
