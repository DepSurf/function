# Function: <code>do_page_fault</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void do_page_fault(struct pt_regs *regs, long unsigned int error_code);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/fault.c (ffffffff8106b7a0)
Location: arch/x86/mm/fault.c:1294
Inline: False
```
**Symbols:**

```
ffffffff8106b7a0-ffffffff8106b7c7: do_page_fault (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void do_page_fault(struct pt_regs *regs, long unsigned int error_code);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/fault.c (ffffffff8106b680)
Location: arch/x86/mm/fault.c:1405
Inline: False
```
**Symbols:**

```
ffffffff8106b680-ffffffff8106b6a7: do_page_fault (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void do_page_fault(struct pt_regs *regs, long unsigned int error_code);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/fault.c (ffffffff8106f2a0)
Location: arch/x86/mm/fault.c:1445
Inline: False
```
**Symbols:**

```
ffffffff8106f2a0-ffffffff8106f2c7: do_page_fault (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void do_page_fault(struct pt_regs *regs, long unsigned int error_code);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/fault.c (ffffffff8106e9f0)
Location: arch/x86/mm/fault.c:1494
Inline: False
```
**Symbols:**

```
ffffffff8106e9f0-ffffffff8106ea17: do_page_fault (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void do_page_fault(struct pt_regs *regs, long unsigned int error_code);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/fault.c (ffffffff81073aa0)
Location: arch/x86/mm/fault.c:1488
Inline: False
```
**Symbols:**

```
ffffffff81073aa0-ffffffff81073b79: do_page_fault (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void do_page_fault(struct pt_regs *regs, long unsigned int error_code);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/fault.c (ffffffff810763f0)
Location: arch/x86/mm/fault.c:1460
Inline: False
```
**Symbols:**

```
ffffffff810763f0-ffffffff810764c9: do_page_fault (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void do_page_fault(struct pt_regs *regs, long unsigned int error_code);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/fault.c (ffffffff8107c6a0)
Location: arch/x86/mm/fault.c:1563
Inline: False
```
**Symbols:**

```
ffffffff8107c6a0-ffffffff8107c779: do_page_fault (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void do_page_fault(struct pt_regs *regs, long unsigned int error_code, long unsigned int address);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/fault.c (ffffffff8107ffc0)
Location: arch/x86/mm/fault.c:1524
Inline: False
```
**Symbols:**

```
ffffffff8107ffc0-ffffffff81080097: do_page_fault (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void do_page_fault(struct pt_regs *regs, long unsigned int error_code, long unsigned int address);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/fault.c (ffffffff81081050)
Location: arch/x86/mm/fault.c:1546
Inline: False
```
**Symbols:**

```
ffffffff81081050-ffffffff81081127: do_page_fault (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
int do_page_fault(long unsigned int addr, unsigned int esr, struct pt_regs *regs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/arm64/mm/fault.c (ffff800010da8fc0)
Location: arch/arm64/mm/fault.c:451
Inline: False
Direct callers:
  - arch/arm64/mm/fault.c:do_translation_fault
```
**Symbols:**

```
ffff800010da8fc0-ffff800010da946c: do_page_fault (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int do_page_fault(long unsigned int addr, unsigned int fsr, struct pt_regs *regs);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/arm/mm/fault.c (c0e9f828)
Location: arch/arm/mm/fault.c:238
Inline: False
Direct callers:
  - arch/arm/mm/fault.c:do_translation_fault
```
**Symbols:**

```
c0e9f828-c0e9fc10: do_page_fault (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int do_page_fault(struct pt_regs *regs, long unsigned int address, long unsigned int error_code);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/powerpc/mm/fault.c (c000000000086eb0)
Location: arch/powerpc/mm/fault.c:633
Inline: False
```
**Symbols:**

```
c000000000086eb0-c000000000086ec4: do_page_fault (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void do_page_fault(struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/riscv/mm/fault.c (ffffffe0000b9b70)
Location: arch/riscv/mm/fault.c:27
Inline: False
```
**Symbols:**

```
ffffffe0000b9b70-ffffffe0000b9ef2: do_page_fault (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
void do_page_fault(struct pt_regs *regs, long unsigned int error_code, long unsigned int address);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/fault.c (ffffffff81080050)
Location: arch/x86/mm/fault.c:1546
Inline: False
```
**Symbols:**

```
ffffffff81080050-ffffffff81080127: do_page_fault (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void do_page_fault(struct pt_regs *regs, long unsigned int error_code, long unsigned int address);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/fault.c (ffffffff8106edd0)
Location: arch/x86/mm/fault.c:1546
Inline: False
```
**Symbols:**

```
ffffffff8106edd0-ffffffff8106eee3: do_page_fault (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void do_page_fault(struct pt_regs *regs, long unsigned int error_code, long unsigned int address);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/fault.c (ffffffff81080000)
Location: arch/x86/mm/fault.c:1546
Inline: False
```
**Symbols:**

```
ffffffff81080000-ffffffff810800d7: do_page_fault (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void do_page_fault(struct pt_regs *regs, long unsigned int error_code, long unsigned int address);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/fault.c (ffffffff81082100)
Location: arch/x86/mm/fault.c:1546
Inline: False
```
**Symbols:**

```
ffffffff81082100-ffffffff810821f3: do_page_fault (STB_GLOBAL)
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
<details>
<summary>Changed between <code>5.0</code> and <code>5.3</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>long unsigned int address</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>Changed between <code>amd64</code> and <code>arm64</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>long unsigned int addr</code>
</li>
<li>
<b>Param added. </b>
<code>unsigned int esr</code>
</li>
<li>
<b>Param removed. </b>
<code>long unsigned int error_code</code>
</li>
<li>
<b>Param removed. </b>
<code>long unsigned int address</code>
</li>
<li>
<b>Param reordered. </b>
<code>regs, error_code, address</code> ➡️ <code>addr, esr, regs</code>
</li>
<li>
<b>Return type changed. </b>
<code>void</code> ➡️ <code>int</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>amd64</code> and <code>armhf</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>long unsigned int addr</code>
</li>
<li>
<b>Param added. </b>
<code>unsigned int fsr</code>
</li>
<li>
<b>Param removed. </b>
<code>long unsigned int error_code</code>
</li>
<li>
<b>Param removed. </b>
<code>long unsigned int address</code>
</li>
<li>
<b>Param reordered. </b>
<code>regs, error_code, address</code> ➡️ <code>addr, fsr, regs</code>
</li>
<li>
<b>Return type changed. </b>
<code>void</code> ➡️ <code>int</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>amd64</code> and <code>ppc64el</code> ⚠️</summary>
<ul>
<li>
<b>Param reordered. </b>
<code>regs, error_code, address</code> ➡️ <code>regs, address, error_code</code>
</li>
<li>
<b>Return type changed. </b>
<code>void</code> ➡️ <code>int</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>amd64</code> and <code>riscv64</code> ⚠️</summary>
<ul>
<li>
<b>Param removed. </b>
<code>long unsigned int error_code</code>
</li>
<li>
<b>Param removed. </b>
<code>long unsigned int address</code>
</li>
</ul>
</details>
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
