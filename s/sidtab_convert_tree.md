# Function: <code>sidtab_convert_tree</code>

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
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/selinux/ss/sidtab.c (ffffffff81423eb0)
Location: security/selinux/ss/sidtab.c:360
Inline: True
Direct callers:
  - security/selinux/ss/sidtab.c:sidtab_convert
```
**Symbols:**

```
ffffffff81423eb0-ffffffff81423fe0: sidtab_convert_tree.isra.4 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/selinux/ss/sidtab.c (ffffffff81451a30)
Location: security/selinux/ss/sidtab.c:365
Inline: True
Direct callers:
  - security/selinux/ss/sidtab.c:sidtab_convert
```
**Symbols:**

```
ffffffff81451a30-ffffffff81451b61: sidtab_convert_tree.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/selinux/ss/sidtab.c (ffffffff8146b810)
Location: security/selinux/ss/sidtab.c:359
Inline: True
Direct callers:
  - security/selinux/ss/sidtab.c:sidtab_convert
```
**Symbols:**

```
ffffffff8146b810-ffffffff8146b941: sidtab_convert_tree.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int sidtab_convert_tree(union sidtab_entry_inner *edst, union sidtab_entry_inner *esrc, u32 *pos, u32 count, u32 level, struct sidtab_convert_params *convert);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/sidtab.c (ffffffff814bfe90)
Location: security/selinux/ss/sidtab.c:361
Inline: False
Direct callers:
  - security/selinux/ss/sidtab.c:sidtab_convert
  - security/selinux/ss/sidtab.c:sidtab_convert_tree
```
**Symbols:**

```
ffffffff814bfe90-ffffffff814bffc4: sidtab_convert_tree (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int sidtab_convert_tree(union sidtab_entry_inner *edst, union sidtab_entry_inner *esrc, u32 *pos, u32 count, u32 level, struct sidtab_convert_params *convert);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/sidtab.c (ffffffff814dd8f0)
Location: security/selinux/ss/sidtab.c:361
Inline: False
Direct callers:
  - security/selinux/ss/sidtab.c:sidtab_convert
  - security/selinux/ss/sidtab.c:sidtab_convert_tree
```
**Symbols:**

```
ffffffff814dd8f0-ffffffff814dda24: sidtab_convert_tree (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int sidtab_convert_tree(union sidtab_entry_inner *edst, union sidtab_entry_inner *esrc, u32 *pos, u32 count, u32 level, struct sidtab_convert_params *convert);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/sidtab.c (ffffffff814e4260)
Location: security/selinux/ss/sidtab.c:371
Inline: False
Direct callers:
  - security/selinux/ss/sidtab.c:sidtab_convert
  - security/selinux/ss/sidtab.c:sidtab_convert_tree
```
**Symbols:**

```
ffffffff814e4260-ffffffff814e4397: sidtab_convert_tree (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int sidtab_convert_tree(union sidtab_entry_inner *edst, union sidtab_entry_inner *esrc, u32 *pos, u32 count, u32 level, struct sidtab_convert_params *convert);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/sidtab.c (ffffffff8153d680)
Location: security/selinux/ss/sidtab.c:371
Inline: False
Direct callers:
  - security/selinux/ss/sidtab.c:sidtab_convert
  - security/selinux/ss/sidtab.c:sidtab_convert_tree
```
**Symbols:**

```
ffffffff8153d680-ffffffff8153d7b7: sidtab_convert_tree (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int sidtab_convert_tree(union sidtab_entry_inner *edst, union sidtab_entry_inner *esrc, u32 *pos, u32 count, u32 level, struct sidtab_convert_params *convert);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/sidtab.c (ffffffff815d4fd0)
Location: security/selinux/ss/sidtab.c:371
Inline: False
Direct callers:
  - security/selinux/ss/sidtab.c:sidtab_convert
  - security/selinux/ss/sidtab.c:sidtab_convert_tree
```
**Symbols:**

```
ffffffff815d4fd0-ffffffff815d5118: sidtab_convert_tree (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int sidtab_convert_tree(union sidtab_entry_inner *edst, union sidtab_entry_inner *esrc, u32 *pos, u32 count, u32 level, struct sidtab_convert_params *convert);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/sidtab.c (ffffffff816831c0)
Location: security/selinux/ss/sidtab.c:375
Inline: False
Direct callers:
  - security/selinux/ss/sidtab.c:sidtab_convert
  - security/selinux/ss/sidtab.c:sidtab_convert_tree
```
**Symbols:**

```
ffffffff816831c0-ffffffff8168330c: sidtab_convert_tree (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int sidtab_convert_tree(union sidtab_entry_inner *edst, union sidtab_entry_inner *esrc, u32 *pos, u32 count, u32 level, struct sidtab_convert_params *convert);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/sidtab.c (ffffffff816bb380)
Location: security/selinux/ss/sidtab.c:375
Inline: False
Direct callers:
  - security/selinux/ss/sidtab.c:sidtab_convert
  - security/selinux/ss/sidtab.c:sidtab_convert_tree
```
**Symbols:**

```
ffffffff816bb380-ffffffff816bb5a7: sidtab_convert_tree (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int sidtab_convert_tree(union sidtab_entry_inner *edst, union sidtab_entry_inner *esrc, u32 *pos, u32 count, u32 level, struct sidtab_convert_params *convert);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/sidtab.c (ffffffff816f7d80)
Location: security/selinux/ss/sidtab.c:375
Inline: False
Direct callers:
  - security/selinux/ss/sidtab.c:sidtab_convert
  - security/selinux/ss/sidtab.c:sidtab_convert_tree
```
**Symbols:**

```
ffffffff816f7d80-ffffffff816f8005: sidtab_convert_tree (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/selinux/ss/sidtab.c (ffff80001055a6b8)
Location: security/selinux/ss/sidtab.c:359
Inline: True
Direct callers:
  - security/selinux/ss/sidtab.c:sidtab_convert
```
**Symbols:**

```
ffff80001055a6b8-ffff80001055a800: sidtab_convert_tree.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int sidtab_convert_tree(union sidtab_entry_inner *edst, union sidtab_entry_inner *esrc, u32 *pos, u32 count, u32 level, struct sidtab_convert_params *convert);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/ss/sidtab.c (c070eed4)
Location: security/selinux/ss/sidtab.c:359
Inline: False
Direct callers:
  - security/selinux/ss/sidtab.c:sidtab_convert
  - security/selinux/ss/sidtab.c:sidtab_convert_tree
```
**Symbols:**

```
c070eed4-c070f028: sidtab_convert_tree (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/selinux/ss/sidtab.c (c0000000006b90f0)
Location: security/selinux/ss/sidtab.c:359
Inline: True
Direct callers:
  - security/selinux/ss/sidtab.c:sidtab_convert
```
**Symbols:**

```
c0000000006b90f0-c0000000006b9380: sidtab_convert_tree.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/selinux/ss/sidtab.c (ffffffe0003b163a)
Location: security/selinux/ss/sidtab.c:359
Inline: True
Direct callers:
  - security/selinux/ss/sidtab.c:sidtab_convert
```
**Symbols:**

```
ffffffe0003b163a-ffffffe0003b174a: sidtab_convert_tree.isra.0 (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/selinux/ss/sidtab.c (ffffffff81463df0)
Location: security/selinux/ss/sidtab.c:359
Inline: True
Direct callers:
  - security/selinux/ss/sidtab.c:sidtab_convert
```
**Symbols:**

```
ffffffff81463df0-ffffffff81463f21: sidtab_convert_tree.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/selinux/ss/sidtab.c (ffffffff81454820)
Location: security/selinux/ss/sidtab.c:359
Inline: True
Direct callers:
  - security/selinux/ss/sidtab.c:sidtab_convert
```
**Symbols:**

```
ffffffff81454820-ffffffff81454951: sidtab_convert_tree.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/selinux/ss/sidtab.c (ffffffff8145fe90)
Location: security/selinux/ss/sidtab.c:359
Inline: True
Direct callers:
  - security/selinux/ss/sidtab.c:sidtab_convert
```
**Symbols:**

```
ffffffff8145fe90-ffffffff8145ffc1: sidtab_convert_tree.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/selinux/ss/sidtab.c (ffffffff814776a0)
Location: security/selinux/ss/sidtab.c:359
Inline: True
Direct callers:
  - security/selinux/ss/sidtab.c:sidtab_convert
```
**Symbols:**

```
ffffffff814776a0-ffffffff814777c9: sidtab_convert_tree.isra.0 (STB_LOCAL)
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
<b>Arch</b>
<ul>
</ul>
