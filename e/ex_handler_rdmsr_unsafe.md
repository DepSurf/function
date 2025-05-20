# Function: <code>ex_handler_rdmsr_unsafe</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
bool ex_handler_rdmsr_unsafe(const struct exception_table_entry *fixup, struct pt_regs *regs, int trapnr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/extable.c (ffffffff8106bec0)
Location: arch/x86/mm/extable.c:47
Inline: False
```
**Symbols:**

```
ffffffff8106bec0-ffffffff8106bf30: ex_handler_rdmsr_unsafe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
bool ex_handler_rdmsr_unsafe(const struct exception_table_entry *fixup, struct pt_regs *regs, int trapnr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/extable.c (ffffffff8106fae0)
Location: arch/x86/mm/extable.c:47
Inline: False
```
**Symbols:**

```
ffffffff8106fae0-ffffffff8106fb50: ex_handler_rdmsr_unsafe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
bool ex_handler_rdmsr_unsafe(const struct exception_table_entry *fixup, struct pt_regs *regs, int trapnr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/extable.c (ffffffff8106f200)
Location: arch/x86/mm/extable.c:49
Inline: False
```
**Symbols:**

```
ffffffff8106f200-ffffffff8106f270: ex_handler_rdmsr_unsafe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
bool ex_handler_rdmsr_unsafe(const struct exception_table_entry *fixup, struct pt_regs *regs, int trapnr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/extable.c (ffffffff81074530)
Location: arch/x86/mm/extable.c:121
Inline: False
```
**Symbols:**

```
ffffffff81074530-ffffffff810745a0: ex_handler_rdmsr_unsafe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
bool ex_handler_rdmsr_unsafe(const struct exception_table_entry *fixup, struct pt_regs *regs, int trapnr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/mm/extable.c (0)
Location: arch/x86/mm/extable.c:121
Inline: False
```
**Symbols:**

```
ffffffff81077109-ffffffff81077136: ex_handler_rdmsr_unsafe.cold.3 (STB_LOCAL)
ffffffff81076f90-ffffffff81076fda: ex_handler_rdmsr_unsafe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
bool ex_handler_rdmsr_unsafe(const struct exception_table_entry *fixup, struct pt_regs *regs, int trapnr, long unsigned int error_code, long unsigned int fault_addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/mm/extable.c (0)
Location: arch/x86/mm/extable.c:142
Inline: False
```
**Symbols:**

```
ffffffff8107d7d1-ffffffff8107d7fe: ex_handler_rdmsr_unsafe.cold.3 (STB_LOCAL)
ffffffff8107d620-ffffffff8107d66a: ex_handler_rdmsr_unsafe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
bool ex_handler_rdmsr_unsafe(const struct exception_table_entry *fixup, struct pt_regs *regs, int trapnr, long unsigned int error_code, long unsigned int fault_addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/mm/extable.c (0)
Location: arch/x86/mm/extable.c:144
Inline: False
```
**Symbols:**

```
ffffffff810810d1-ffffffff810810fe: ex_handler_rdmsr_unsafe.cold (STB_LOCAL)
ffffffff81080f40-ffffffff81080f8a: ex_handler_rdmsr_unsafe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
bool ex_handler_rdmsr_unsafe(const struct exception_table_entry *fixup, struct pt_regs *regs, int trapnr, long unsigned int error_code, long unsigned int fault_addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/mm/extable.c (0)
Location: arch/x86/mm/extable.c:144
Inline: False
```
**Symbols:**

```
ffffffff81082191-ffffffff810821be: ex_handler_rdmsr_unsafe.cold (STB_LOCAL)
ffffffff81082000-ffffffff8108204a: ex_handler_rdmsr_unsafe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
bool ex_handler_rdmsr_unsafe(const struct exception_table_entry *fixup, struct pt_regs *regs, int trapnr, long unsigned int error_code, long unsigned int fault_addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/mm/extable.c (0)
Location: arch/x86/mm/extable.c:83
Inline: False
```
**Symbols:**

```
ffffffff810891a1-ffffffff810891ce: ex_handler_rdmsr_unsafe.cold (STB_LOCAL)
ffffffff81089010-ffffffff8108905a: ex_handler_rdmsr_unsafe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
bool ex_handler_rdmsr_unsafe(const struct exception_table_entry *fixup, struct pt_regs *regs, int trapnr, long unsigned int error_code, long unsigned int fault_addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/mm/extable.c (0)
Location: arch/x86/mm/extable.c:96
Inline: False
```
**Symbols:**

```
ffffffff81bd9756-ffffffff81bd9783: ex_handler_rdmsr_unsafe.cold (STB_LOCAL)
ffffffff81089230-ffffffff8108927a: ex_handler_rdmsr_unsafe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
bool ex_handler_rdmsr_unsafe(const struct exception_table_entry *fixup, struct pt_regs *regs, int trapnr, long unsigned int error_code, long unsigned int fault_addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/mm/extable.c (0)
Location: arch/x86/mm/extable.c:96
Inline: False
```
**Symbols:**

```
ffffffff81bcb7be-ffffffff81bcb7eb: ex_handler_rdmsr_unsafe.cold (STB_LOCAL)
ffffffff81089eb0-ffffffff81089efa: ex_handler_rdmsr_unsafe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
bool ex_handler_rdmsr_unsafe(const struct exception_table_entry *fixup, struct pt_regs *regs, int trapnr, long unsigned int error_code, long unsigned int fault_addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/mm/extable.c (0)
Location: arch/x86/mm/extable.c:96
Inline: False
```
**Symbols:**

```
ffffffff81ca0f93-ffffffff81ca0fcd: ex_handler_rdmsr_unsafe.cold (STB_LOCAL)
ffffffff81099420-ffffffff81099485: ex_handler_rdmsr_unsafe (STB_GLOBAL)
```
</details>
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
bool ex_handler_rdmsr_unsafe(const struct exception_table_entry *fixup, struct pt_regs *regs, int trapnr, long unsigned int error_code, long unsigned int fault_addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/mm/extable.c (0)
Location: arch/x86/mm/extable.c:144
Inline: False
```
**Symbols:**

```
ffffffff81081191-ffffffff810811be: ex_handler_rdmsr_unsafe.cold (STB_LOCAL)
ffffffff81081000-ffffffff8108104a: ex_handler_rdmsr_unsafe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
bool ex_handler_rdmsr_unsafe(const struct exception_table_entry *fixup, struct pt_regs *regs, int trapnr, long unsigned int error_code, long unsigned int fault_addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/mm/extable.c (0)
Location: arch/x86/mm/extable.c:144
Inline: False
```
**Symbols:**

```
ffffffff810700e1-ffffffff8107010e: ex_handler_rdmsr_unsafe.cold (STB_LOCAL)
ffffffff8106ff50-ffffffff8106ff9a: ex_handler_rdmsr_unsafe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
bool ex_handler_rdmsr_unsafe(const struct exception_table_entry *fixup, struct pt_regs *regs, int trapnr, long unsigned int error_code, long unsigned int fault_addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/mm/extable.c (0)
Location: arch/x86/mm/extable.c:144
Inline: False
```
**Symbols:**

```
ffffffff81081141-ffffffff8108116e: ex_handler_rdmsr_unsafe.cold (STB_LOCAL)
ffffffff81080fb0-ffffffff81080ffa: ex_handler_rdmsr_unsafe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
bool ex_handler_rdmsr_unsafe(const struct exception_table_entry *fixup, struct pt_regs *regs, int trapnr, long unsigned int error_code, long unsigned int fault_addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/mm/extable.c (0)
Location: arch/x86/mm/extable.c:144
Inline: False
```
**Symbols:**

```
ffffffff81083261-ffffffff8108328e: ex_handler_rdmsr_unsafe.cold (STB_LOCAL)
ffffffff810830d0-ffffffff8108311a: ex_handler_rdmsr_unsafe (STB_GLOBAL)
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
