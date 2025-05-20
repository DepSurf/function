# Function: <code>dump_pagetable</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void dump_pagetable(long unsigned int address);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/fault.c (ffffffff8106a8e0)
Location: arch/x86/mm/fault.c:467
Inline: False
Direct callers:
  - arch/x86/mm/fault.c:pgtable_bad
  - arch/x86/mm/fault.c:no_context
```
**Symbols:**

```
ffffffff8106a8e0-ffffffff8106ab64: dump_pagetable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void dump_pagetable(long unsigned int address);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/fault.c (ffffffff8106a670)
Location: arch/x86/mm/fault.c:524
Inline: False
Direct callers:
  - arch/x86/mm/fault.c:no_context
  - arch/x86/mm/fault.c:pgtable_bad
```
**Symbols:**

```
ffffffff8106a670-ffffffff8106a8ca: dump_pagetable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void dump_pagetable(long unsigned int address);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/fault.c (ffffffff8106e210)
Location: arch/x86/mm/fault.c:524
Inline: False
Direct callers:
  - arch/x86/mm/fault.c:no_context
  - arch/x86/mm/fault.c:pgtable_bad
```
**Symbols:**

```
ffffffff8106e210-ffffffff8106e46a: dump_pagetable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void dump_pagetable(long unsigned int address);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/fault.c (ffffffff8106d950)
Location: arch/x86/mm/fault.c:556
Inline: False
Direct callers:
  - arch/x86/mm/fault.c:no_context
  - arch/x86/mm/fault.c:pgtable_bad
```
**Symbols:**

```
ffffffff8106d950-ffffffff8106dbe6: dump_pagetable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void dump_pagetable(long unsigned int address);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/fault.c (ffffffff810728d0)
Location: arch/x86/mm/fault.c:535
Inline: False
Direct callers:
  - arch/x86/mm/fault.c:no_context
  - arch/x86/mm/fault.c:pgtable_bad
```
**Symbols:**

```
ffffffff810728d0-ffffffff81072bfd: dump_pagetable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
void dump_pagetable(long unsigned int address);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/mm/fault.c (0)
Location: arch/x86/mm/fault.c:512
Inline: False
Direct callers:
  - arch/x86/mm/fault.c:no_context
  - arch/x86/mm/fault.c:pgtable_bad
```
**Symbols:**

```
ffffffff810753b0-ffffffff81075659: dump_pagetable (STB_LOCAL)
ffffffff81076501-ffffffff81076536: dump_pagetable.cold.27 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
void dump_pagetable(long unsigned int address);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/mm/fault.c (0)
Location: arch/x86/mm/fault.c:445
Inline: False
Direct callers:
  - arch/x86/mm/fault.c:no_context
  - arch/x86/mm/fault.c:pgtable_bad
```
**Symbols:**

```
ffffffff8107b1b0-ffffffff8107b459: dump_pagetable (STB_LOCAL)
ffffffff8107c8e7-ffffffff8107c91c: dump_pagetable.cold.30 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void dump_pagetable(long unsigned int address);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/mm/fault.c (0)
Location: arch/x86/mm/fault.c:424
Inline: False
Direct callers:
  - arch/x86/mm/fault.c:no_context
  - arch/x86/mm/fault.c:pgtable_bad
```
**Symbols:**

```
ffffffff8107ecd0-ffffffff8107ef85: dump_pagetable (STB_LOCAL)
ffffffff810801cb-ffffffff81080200: dump_pagetable.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
void dump_pagetable(long unsigned int address);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/mm/fault.c (0)
Location: arch/x86/mm/fault.c:446
Inline: False
Direct callers:
  - arch/x86/mm/fault.c:no_context
  - arch/x86/mm/fault.c:pgtable_bad
```
**Symbols:**

```
ffffffff8107fd60-ffffffff81080015: dump_pagetable (STB_LOCAL)
ffffffff81081275-ffffffff810812aa: dump_pagetable.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
void dump_pagetable(long unsigned int address);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/mm/fault.c (0)
Location: arch/x86/mm/fault.c:418
Inline: False
Direct callers:
  - arch/x86/mm/fault.c:pgtable_bad
  - arch/x86/mm/fault.c:show_fault_oops
```
**Symbols:**

```
ffffffff81086da0-ffffffff810870a6: dump_pagetable (STB_LOCAL)
ffffffff810881f2-ffffffff81088227: dump_pagetable.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
void dump_pagetable(long unsigned int address);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/mm/fault.c (0)
Location: arch/x86/mm/fault.c:361
Inline: False
Direct callers:
  - arch/x86/mm/fault.c:pgtable_bad
  - arch/x86/mm/fault.c:show_fault_oops
```
**Symbols:**

```
ffffffff81087420-ffffffff81087726: dump_pagetable (STB_LOCAL)
ffffffff81bd93d2-ffffffff81bd9407: dump_pagetable.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
void dump_pagetable(long unsigned int address);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/mm/fault.c (0)
Location: arch/x86/mm/fault.c:347
Inline: False
Direct callers:
  - arch/x86/mm/fault.c:pgtable_bad
  - arch/x86/mm/fault.c:show_fault_oops
```
**Symbols:**

```
ffffffff81088090-ffffffff81088368: dump_pagetable (STB_LOCAL)
ffffffff81bcb35f-ffffffff81bcb394: dump_pagetable.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void dump_pagetable(long unsigned int address);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/mm/fault.c (0)
Location: arch/x86/mm/fault.c:348
Inline: False
Direct callers:
  - arch/x86/mm/fault.c:pgtable_bad
  - arch/x86/mm/fault.c:show_fault_oops
```
**Symbols:**

```
ffffffff81097410-ffffffff810976f1: dump_pagetable (STB_LOCAL)
ffffffff81ca09f4-ffffffff81ca0a4f: dump_pagetable.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void dump_pagetable(long unsigned int address);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/mm/fault.c (0)
Location: arch/x86/mm/fault.c:348
Inline: False
Direct callers:
  - arch/x86/mm/fault.c:pgtable_bad
  - arch/x86/mm/fault.c:show_fault_oops
```
**Symbols:**

```
ffffffff810a9f10-ffffffff810aa20f: dump_pagetable (STB_LOCAL)
ffffffff81e4ff41-ffffffff81e4ffb6: dump_pagetable.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void dump_pagetable(long unsigned int address);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/mm/fault.c (0)
Location: arch/x86/mm/fault.c:369
Inline: False
Direct callers:
  - arch/x86/mm/fault.c:pgtable_bad
  - arch/x86/mm/fault.c:show_fault_oops
```
**Symbols:**

```
ffffffff810c3770-ffffffff810c3ac2: dump_pagetable (STB_LOCAL)
ffffffff820549c9-ffffffff820549ed: dump_pagetable.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void dump_pagetable(long unsigned int address);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/mm/fault.c (0)
Location: arch/x86/mm/fault.c:349
Inline: False
Direct callers:
  - arch/x86/mm/fault.c:pgtable_bad
  - arch/x86/mm/fault.c:show_fault_oops
```
**Symbols:**

```
ffffffff810c6fc0-ffffffff810c730c: dump_pagetable (STB_LOCAL)
ffffffff820d2fd7-ffffffff820d2ffb: dump_pagetable.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void dump_pagetable(long unsigned int address);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/mm/fault.c (0)
Location: arch/x86/mm/fault.c:349
Inline: False
Direct callers:
  - arch/x86/mm/fault.c:pgtable_bad
  - arch/x86/mm/fault.c:show_fault_oops
```
**Symbols:**

```
ffffffff810cf490-ffffffff810cf7dc: dump_pagetable (STB_LOCAL)
ffffffff821ade45-ffffffff821ade69: dump_pagetable.cold (STB_LOCAL)
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
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
void dump_pagetable(long unsigned int address);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/mm/fault.c (0)
Location: arch/x86/mm/fault.c:446
Inline: False
Direct callers:
  - arch/x86/mm/fault.c:no_context
  - arch/x86/mm/fault.c:pgtable_bad
```
**Symbols:**

```
ffffffff8107ed60-ffffffff8107f015: dump_pagetable (STB_LOCAL)
ffffffff81080275-ffffffff810802aa: dump_pagetable.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
void dump_pagetable(long unsigned int address);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/mm/fault.c (0)
Location: arch/x86/mm/fault.c:446
Inline: False
Direct callers:
  - arch/x86/mm/fault.c:no_context
  - arch/x86/mm/fault.c:pgtable_bad
```
**Symbols:**

```
ffffffff8106dc00-ffffffff8106dc77: dump_pagetable (STB_LOCAL)
ffffffff8106f035-ffffffff8106f1fa: dump_pagetable.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
void dump_pagetable(long unsigned int address);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/mm/fault.c (0)
Location: arch/x86/mm/fault.c:446
Inline: False
Direct callers:
  - arch/x86/mm/fault.c:no_context
  - arch/x86/mm/fault.c:pgtable_bad
```
**Symbols:**

```
ffffffff8107ed10-ffffffff8107efc5: dump_pagetable (STB_LOCAL)
ffffffff81080225-ffffffff8108025a: dump_pagetable.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
void dump_pagetable(long unsigned int address);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/mm/fault.c (0)
Location: arch/x86/mm/fault.c:446
Inline: False
Direct callers:
  - arch/x86/mm/fault.c:no_context
  - arch/x86/mm/fault.c:pgtable_bad
```
**Symbols:**

```
ffffffff81080e00-ffffffff810810b5: dump_pagetable (STB_LOCAL)
ffffffff81082345-ffffffff8108237a: dump_pagetable.cold (STB_LOCAL)
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
