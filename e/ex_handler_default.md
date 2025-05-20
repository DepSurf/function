# Function: <code>ex_handler_default</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
bool ex_handler_default(const struct exception_table_entry *fixup, struct pt_regs *regs, int trapnr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/mm/extable.c (ffffffff8106bea9)
Location: arch/x86/mm/extable.c:20
Inline: True
Inline callers:
  - arch/x86/mm/extable.c:ex_handler_clear_fs
```
**Symbols:**

```
ffffffff8106be10-ffffffff8106be30: ex_handler_default (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
bool ex_handler_default(const struct exception_table_entry *fixup, struct pt_regs *regs, int trapnr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/mm/extable.c (ffffffff8106fac9)
Location: arch/x86/mm/extable.c:20
Inline: True
Inline callers:
  - arch/x86/mm/extable.c:ex_handler_clear_fs
```
**Symbols:**

```
ffffffff8106fa30-ffffffff8106fa50: ex_handler_default (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
bool ex_handler_default(const struct exception_table_entry *fixup, struct pt_regs *regs, int trapnr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/mm/extable.c (ffffffff8106f1e9)
Location: arch/x86/mm/extable.c:22
Inline: True
Inline callers:
  - arch/x86/mm/extable.c:ex_handler_clear_fs
```
**Symbols:**

```
ffffffff8106f150-ffffffff8106f170: ex_handler_default (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
bool ex_handler_default(const struct exception_table_entry *fixup, struct pt_regs *regs, int trapnr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/mm/extable.c (ffffffff81074499)
Location: arch/x86/mm/extable.c:24
Inline: True
Inline callers:
  - arch/x86/mm/extable.c:ex_handler_clear_fs
```
**Symbols:**

```
ffffffff81074400-ffffffff81074420: ex_handler_default (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
bool ex_handler_default(const struct exception_table_entry *fixup, struct pt_regs *regs, int trapnr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/mm/extable.c (ffffffff81076ef9)
Location: arch/x86/mm/extable.c:24
Inline: True
Inline callers:
  - arch/x86/mm/extable.c:ex_handler_clear_fs
```
**Symbols:**

```
ffffffff81076e60-ffffffff81076e80: ex_handler_default (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
bool ex_handler_default(const struct exception_table_entry *fixup, struct pt_regs *regs, int trapnr, long unsigned int error_code, long unsigned int fault_addr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/mm/extable.c (ffffffff8107d589)
Location: arch/x86/mm/extable.c:25
Inline: True
Inline callers:
  - arch/x86/mm/extable.c:ex_handler_clear_fs
```
**Symbols:**

```
ffffffff8107d4f0-ffffffff8107d510: ex_handler_default (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
bool ex_handler_default(const struct exception_table_entry *fixup, struct pt_regs *regs, int trapnr, long unsigned int error_code, long unsigned int fault_addr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/mm/extable.c (ffffffff81080e59)
Location: arch/x86/mm/extable.c:26
Inline: True
Inline callers:
  - arch/x86/mm/extable.c:ex_handler_clear_fs
```
**Symbols:**

```
ffffffff81080dc0-ffffffff81080de0: ex_handler_default (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
bool ex_handler_default(const struct exception_table_entry *fixup, struct pt_regs *regs, int trapnr, long unsigned int error_code, long unsigned int fault_addr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/mm/extable.c (ffffffff81081f19)
Location: arch/x86/mm/extable.c:26
Inline: True
Inline callers:
  - arch/x86/mm/extable.c:ex_handler_clear_fs
```
**Symbols:**

```
ffffffff81081e80-ffffffff81081ea0: ex_handler_default (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
bool ex_handler_default(const struct exception_table_entry *fixup, struct pt_regs *regs, int trapnr, long unsigned int error_code, long unsigned int fault_addr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/mm/extable.c (ffffffff81088f99)
Location: arch/x86/mm/extable.c:26
Inline: True
Inline callers:
  - arch/x86/mm/extable.c:ex_handler_clear_fs
```
**Symbols:**

```
ffffffff81088f30-ffffffff81088f50: ex_handler_default (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
bool ex_handler_default(const struct exception_table_entry *fixup, struct pt_regs *regs, int trapnr, long unsigned int error_code, long unsigned int fault_addr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/mm/extable.c (ffffffff81089149)
Location: arch/x86/mm/extable.c:27
Inline: True
Inline callers:
  - arch/x86/mm/extable.c:ex_handler_clear_fs
```
**Symbols:**

```
ffffffff810890e0-ffffffff81089100: ex_handler_default (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
bool ex_handler_default(const struct exception_table_entry *fixup, struct pt_regs *regs, int trapnr, long unsigned int error_code, long unsigned int fault_addr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/mm/extable.c (ffffffff81089dc9)
Location: arch/x86/mm/extable.c:27
Inline: True
Inline callers:
  - arch/x86/mm/extable.c:ex_handler_clear_fs
```
**Symbols:**

```
ffffffff81089d60-ffffffff81089d80: ex_handler_default (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
bool ex_handler_default(const struct exception_table_entry *fixup, struct pt_regs *regs, int trapnr, long unsigned int error_code, long unsigned int fault_addr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/mm/extable.c (ffffffff81099299)
Location: arch/x86/mm/extable.c:27
Inline: True
Inline callers:
  - arch/x86/mm/extable.c:ex_handler_clear_fs
```
**Symbols:**

```
ffffffff81099230-ffffffff81099250: ex_handler_default (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/mm/extable.c (ffffffff810ac329)
Location: arch/x86/mm/extable.c:32
Inline: True
Inline callers:
  - arch/x86/mm/extable.c:fixup_exception
  - arch/x86/mm/extable.c:fixup_exception
  - arch/x86/mm/extable.c:fixup_exception
  - arch/x86/mm/extable.c:fixup_exception
  - arch/x86/mm/extable.c:ex_handler_msr
  - arch/x86/mm/extable.c:ex_handler_uaccess
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/mm/extable.c (ffffffff810c62c7)
Location: arch/x86/mm/extable.c:32
Inline: True
Inline callers:
  - arch/x86/mm/extable.c:fixup_exception
  - arch/x86/mm/extable.c:fixup_exception
  - arch/x86/mm/extable.c:fixup_exception
  - arch/x86/mm/extable.c:fixup_exception
  - arch/x86/mm/extable.c:ex_handler_msr
  - arch/x86/mm/extable.c:ex_handler_uaccess
  - arch/x86/mm/extable.c:ex_handler_zeropad
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
In arch/x86/mm/extable.c (ffffffff810c9a2e)
Location: arch/x86/mm/extable.c:32
Inline: True
Inline callers:
  - arch/x86/mm/extable.c:fixup_exception
  - arch/x86/mm/extable.c:fixup_exception
  - arch/x86/mm/extable.c:fixup_exception
  - arch/x86/mm/extable.c:ex_handler_msr
  - arch/x86/mm/extable.c:ex_handler_uaccess
  - arch/x86/mm/extable.c:ex_handler_zeropad
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
In arch/x86/mm/extable.c (ffffffff810d1e8e)
Location: arch/x86/mm/extable.c:32
Inline: True
Inline callers:
  - arch/x86/mm/extable.c:fixup_exception
  - arch/x86/mm/extable.c:fixup_exception
  - arch/x86/mm/extable.c:fixup_exception
  - arch/x86/mm/extable.c:ex_handler_msr
  - arch/x86/mm/extable.c:ex_handler_uaccess
  - arch/x86/mm/extable.c:ex_handler_zeropad
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
bool ex_handler_default(const struct exception_table_entry *fixup, struct pt_regs *regs, int trapnr, long unsigned int error_code, long unsigned int fault_addr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/mm/extable.c (ffffffff81080f19)
Location: arch/x86/mm/extable.c:26
Inline: True
Inline callers:
  - arch/x86/mm/extable.c:ex_handler_clear_fs
```
**Symbols:**

```
ffffffff81080e80-ffffffff81080ea0: ex_handler_default (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
bool ex_handler_default(const struct exception_table_entry *fixup, struct pt_regs *regs, int trapnr, long unsigned int error_code, long unsigned int fault_addr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/mm/extable.c (ffffffff8106fe69)
Location: arch/x86/mm/extable.c:26
Inline: True
Inline callers:
  - arch/x86/mm/extable.c:ex_handler_clear_fs
```
**Symbols:**

```
ffffffff8106fdd0-ffffffff8106fdf0: ex_handler_default (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
bool ex_handler_default(const struct exception_table_entry *fixup, struct pt_regs *regs, int trapnr, long unsigned int error_code, long unsigned int fault_addr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/mm/extable.c (ffffffff81080ec9)
Location: arch/x86/mm/extable.c:26
Inline: True
Inline callers:
  - arch/x86/mm/extable.c:ex_handler_clear_fs
```
**Symbols:**

```
ffffffff81080e30-ffffffff81080e50: ex_handler_default (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
bool ex_handler_default(const struct exception_table_entry *fixup, struct pt_regs *regs, int trapnr, long unsigned int error_code, long unsigned int fault_addr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/mm/extable.c (ffffffff81082fe9)
Location: arch/x86/mm/extable.c:26
Inline: True
Inline callers:
  - arch/x86/mm/extable.c:ex_handler_clear_fs
```
**Symbols:**

```
ffffffff81082f50-ffffffff81082f70: ex_handler_default (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
<code>long unsigned int error_code</code>
</li>
<li>
<b>Param added. </b>
<code>long unsigned int fault_addr</code>
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
