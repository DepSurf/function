# Function: <code>ex_handler_uaccess</code>

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
<summary>In <code>5.0</code>: ✅</summary>

```c
bool ex_handler_uaccess(const struct exception_table_entry *fixup, struct pt_regs *regs, int trapnr, long unsigned int error_code, long unsigned int fault_addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/extable.c (0)
Location: arch/x86/mm/extable.c:120
Inline: False
```
**Symbols:**

```
ffffffff8107d720-ffffffff8107d740: ex_handler_uaccess (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
bool ex_handler_uaccess(const struct exception_table_entry *fixup, struct pt_regs *regs, int trapnr, long unsigned int error_code, long unsigned int fault_addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/extable.c (ffffffff81080ee0)
Location: arch/x86/mm/extable.c:121
Inline: False
```
**Symbols:**

```
ffffffff81080ee0-ffffffff81080f3a: ex_handler_uaccess (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
bool ex_handler_uaccess(const struct exception_table_entry *fixup, struct pt_regs *regs, int trapnr, long unsigned int error_code, long unsigned int fault_addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/extable.c (ffffffff81081fa0)
Location: arch/x86/mm/extable.c:121
Inline: False
```
**Symbols:**

```
ffffffff81081fa0-ffffffff81081ffa: ex_handler_uaccess (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
bool ex_handler_uaccess(const struct exception_table_entry *fixup, struct pt_regs *regs, int trapnr, long unsigned int error_code, long unsigned int fault_addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/extable.c (ffffffff81088fb0)
Location: arch/x86/mm/extable.c:72
Inline: False
```
**Symbols:**

```
ffffffff81088fb0-ffffffff81089009: ex_handler_uaccess (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
bool ex_handler_uaccess(const struct exception_table_entry *fixup, struct pt_regs *regs, int trapnr, long unsigned int error_code, long unsigned int fault_addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/extable.c (ffffffff81089160)
Location: arch/x86/mm/extable.c:73
Inline: False
```
**Symbols:**

```
ffffffff81089160-ffffffff810891b9: ex_handler_uaccess (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
bool ex_handler_uaccess(const struct exception_table_entry *fixup, struct pt_regs *regs, int trapnr, long unsigned int error_code, long unsigned int fault_addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/extable.c (ffffffff81089de0)
Location: arch/x86/mm/extable.c:73
Inline: False
```
**Symbols:**

```
ffffffff81089de0-ffffffff81089e39: ex_handler_uaccess (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
bool ex_handler_uaccess(const struct exception_table_entry *fixup, struct pt_regs *regs, int trapnr, long unsigned int error_code, long unsigned int fault_addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/mm/extable.c (0)
Location: arch/x86/mm/extable.c:73
Inline: False
```
**Symbols:**

```
ffffffff81ca0f4e-ffffffff81ca0f63: ex_handler_uaccess.cold (STB_LOCAL)
ffffffff810992b0-ffffffff81099315: ex_handler_uaccess (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
bool ex_handler_uaccess(const struct exception_table_entry *fixup, struct pt_regs *regs, int trapnr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/mm/extable.c (0)
Location: arch/x86/mm/extable.c:80
Inline: False
Direct callers:
  - arch/x86/mm/extable.c:fixup_exception
```
**Symbols:**

```
ffffffff810ac000-ffffffff810ac091: ex_handler_uaccess (STB_LOCAL)
ffffffff81e50512-ffffffff81e50527: ex_handler_uaccess.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
bool ex_handler_uaccess(const struct exception_table_entry *fixup, struct pt_regs *regs, int trapnr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/mm/extable.c (0)
Location: arch/x86/mm/extable.c:133
Inline: False
Direct callers:
  - arch/x86/mm/extable.c:fixup_exception
```
**Symbols:**

```
ffffffff810c5f50-ffffffff810c5fe1: ex_handler_uaccess (STB_LOCAL)
ffffffff82054a53-ffffffff82054a68: ex_handler_uaccess.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
bool ex_handler_uaccess(const struct exception_table_entry *fixup, struct pt_regs *regs, int trapnr, long unsigned int fault_address);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/mm/extable.c (0)
Location: arch/x86/mm/extable.c:157
Inline: False
Direct callers:
  - arch/x86/mm/extable.c:fixup_exception
```
**Symbols:**

```
ffffffff810c96c0-ffffffff810c9765: ex_handler_uaccess (STB_LOCAL)
ffffffff820d305f-ffffffff820d3074: ex_handler_uaccess.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
bool ex_handler_uaccess(const struct exception_table_entry *fixup, struct pt_regs *regs, int trapnr, long unsigned int fault_address);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/mm/extable.c (0)
Location: arch/x86/mm/extable.c:157
Inline: False
Direct callers:
  - arch/x86/mm/extable.c:fixup_exception
```
**Symbols:**

```
ffffffff810d1b20-ffffffff810d1bc5: ex_handler_uaccess (STB_LOCAL)
ffffffff821adecd-ffffffff821adee2: ex_handler_uaccess.cold (STB_LOCAL)
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
bool ex_handler_uaccess(const struct exception_table_entry *fixup, struct pt_regs *regs, int trapnr, long unsigned int error_code, long unsigned int fault_addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/extable.c (ffffffff81080fa0)
Location: arch/x86/mm/extable.c:121
Inline: False
```
**Symbols:**

```
ffffffff81080fa0-ffffffff81080ffa: ex_handler_uaccess (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
bool ex_handler_uaccess(const struct exception_table_entry *fixup, struct pt_regs *regs, int trapnr, long unsigned int error_code, long unsigned int fault_addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/extable.c (ffffffff8106fef0)
Location: arch/x86/mm/extable.c:121
Inline: False
```
**Symbols:**

```
ffffffff8106fef0-ffffffff8106ff4a: ex_handler_uaccess (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
bool ex_handler_uaccess(const struct exception_table_entry *fixup, struct pt_regs *regs, int trapnr, long unsigned int error_code, long unsigned int fault_addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/extable.c (ffffffff81080f50)
Location: arch/x86/mm/extable.c:121
Inline: False
```
**Symbols:**

```
ffffffff81080f50-ffffffff81080faa: ex_handler_uaccess (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
bool ex_handler_uaccess(const struct exception_table_entry *fixup, struct pt_regs *regs, int trapnr, long unsigned int error_code, long unsigned int fault_addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/extable.c (ffffffff81083070)
Location: arch/x86/mm/extable.c:121
Inline: False
```
**Symbols:**

```
ffffffff81083070-ffffffff810830ca: ex_handler_uaccess (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
<details>
<summary>Changed between <code>5.15</code> and <code>5.19</code> ⚠️</summary>
<ul>
<li>
<b>Param removed. </b>
<code>long unsigned int error_code</code>
</li>
<li>
<b>Param removed. </b>
<code>long unsigned int fault_addr</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>6.2</code> and <code>6.5</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>long unsigned int fault_address</code>
</li>
</ul>
</details>
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
