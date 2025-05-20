# Function: <code>ex_handler_wrmsr_unsafe</code>

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
bool ex_handler_wrmsr_unsafe(const struct exception_table_entry *fixup, struct pt_regs *regs, int trapnr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/extable.c (ffffffff8106bf30)
Location: arch/x86/mm/extable.c:62
Inline: False
```
**Symbols:**

```
ffffffff8106bf30-ffffffff8106bf96: ex_handler_wrmsr_unsafe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
bool ex_handler_wrmsr_unsafe(const struct exception_table_entry *fixup, struct pt_regs *regs, int trapnr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/extable.c (ffffffff8106fb50)
Location: arch/x86/mm/extable.c:62
Inline: False
```
**Symbols:**

```
ffffffff8106fb50-ffffffff8106fbb6: ex_handler_wrmsr_unsafe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
bool ex_handler_wrmsr_unsafe(const struct exception_table_entry *fixup, struct pt_regs *regs, int trapnr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/extable.c (ffffffff8106f270)
Location: arch/x86/mm/extable.c:64
Inline: False
```
**Symbols:**

```
ffffffff8106f270-ffffffff8106f2d6: ex_handler_wrmsr_unsafe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
bool ex_handler_wrmsr_unsafe(const struct exception_table_entry *fixup, struct pt_regs *regs, int trapnr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/extable.c (ffffffff810745a0)
Location: arch/x86/mm/extable.c:136
Inline: False
```
**Symbols:**

```
ffffffff810745a0-ffffffff81074606: ex_handler_wrmsr_unsafe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
bool ex_handler_wrmsr_unsafe(const struct exception_table_entry *fixup, struct pt_regs *regs, int trapnr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/mm/extable.c (0)
Location: arch/x86/mm/extable.c:136
Inline: False
```
**Symbols:**

```
ffffffff81077136-ffffffff81077169: ex_handler_wrmsr_unsafe.cold.4 (STB_LOCAL)
ffffffff81076fe0-ffffffff8107701a: ex_handler_wrmsr_unsafe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
bool ex_handler_wrmsr_unsafe(const struct exception_table_entry *fixup, struct pt_regs *regs, int trapnr, long unsigned int error_code, long unsigned int fault_addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/mm/extable.c (0)
Location: arch/x86/mm/extable.c:159
Inline: False
```
**Symbols:**

```
ffffffff8107d7fe-ffffffff8107d831: ex_handler_wrmsr_unsafe.cold.4 (STB_LOCAL)
ffffffff8107d670-ffffffff8107d6aa: ex_handler_wrmsr_unsafe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
bool ex_handler_wrmsr_unsafe(const struct exception_table_entry *fixup, struct pt_regs *regs, int trapnr, long unsigned int error_code, long unsigned int fault_addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/mm/extable.c (0)
Location: arch/x86/mm/extable.c:161
Inline: False
```
**Symbols:**

```
ffffffff810810fe-ffffffff81081131: ex_handler_wrmsr_unsafe.cold (STB_LOCAL)
ffffffff81080f90-ffffffff81080fca: ex_handler_wrmsr_unsafe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
bool ex_handler_wrmsr_unsafe(const struct exception_table_entry *fixup, struct pt_regs *regs, int trapnr, long unsigned int error_code, long unsigned int fault_addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/mm/extable.c (0)
Location: arch/x86/mm/extable.c:161
Inline: False
```
**Symbols:**

```
ffffffff810821be-ffffffff810821f1: ex_handler_wrmsr_unsafe.cold (STB_LOCAL)
ffffffff81082050-ffffffff8108208a: ex_handler_wrmsr_unsafe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
bool ex_handler_wrmsr_unsafe(const struct exception_table_entry *fixup, struct pt_regs *regs, int trapnr, long unsigned int error_code, long unsigned int fault_addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/mm/extable.c (0)
Location: arch/x86/mm/extable.c:100
Inline: False
```
**Symbols:**

```
ffffffff810891ce-ffffffff81089201: ex_handler_wrmsr_unsafe.cold (STB_LOCAL)
ffffffff81089060-ffffffff8108909a: ex_handler_wrmsr_unsafe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
bool ex_handler_wrmsr_unsafe(const struct exception_table_entry *fixup, struct pt_regs *regs, int trapnr, long unsigned int error_code, long unsigned int fault_addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/mm/extable.c (0)
Location: arch/x86/mm/extable.c:113
Inline: False
```
**Symbols:**

```
ffffffff81bd9783-ffffffff81bd97b6: ex_handler_wrmsr_unsafe.cold (STB_LOCAL)
ffffffff81089280-ffffffff810892ba: ex_handler_wrmsr_unsafe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
bool ex_handler_wrmsr_unsafe(const struct exception_table_entry *fixup, struct pt_regs *regs, int trapnr, long unsigned int error_code, long unsigned int fault_addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/mm/extable.c (0)
Location: arch/x86/mm/extable.c:113
Inline: False
```
**Symbols:**

```
ffffffff81bcb7eb-ffffffff81bcb81e: ex_handler_wrmsr_unsafe.cold (STB_LOCAL)
ffffffff81089f00-ffffffff81089f3a: ex_handler_wrmsr_unsafe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
bool ex_handler_wrmsr_unsafe(const struct exception_table_entry *fixup, struct pt_regs *regs, int trapnr, long unsigned int error_code, long unsigned int fault_addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/mm/extable.c (0)
Location: arch/x86/mm/extable.c:113
Inline: False
```
**Symbols:**

```
ffffffff81ca0fcd-ffffffff81ca100d: ex_handler_wrmsr_unsafe.cold (STB_LOCAL)
ffffffff81099490-ffffffff810994e4: ex_handler_wrmsr_unsafe (STB_GLOBAL)
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
bool ex_handler_wrmsr_unsafe(const struct exception_table_entry *fixup, struct pt_regs *regs, int trapnr, long unsigned int error_code, long unsigned int fault_addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/mm/extable.c (0)
Location: arch/x86/mm/extable.c:161
Inline: False
```
**Symbols:**

```
ffffffff810811be-ffffffff810811f1: ex_handler_wrmsr_unsafe.cold (STB_LOCAL)
ffffffff81081050-ffffffff8108108a: ex_handler_wrmsr_unsafe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
bool ex_handler_wrmsr_unsafe(const struct exception_table_entry *fixup, struct pt_regs *regs, int trapnr, long unsigned int error_code, long unsigned int fault_addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/mm/extable.c (0)
Location: arch/x86/mm/extable.c:161
Inline: False
```
**Symbols:**

```
ffffffff8107010e-ffffffff81070141: ex_handler_wrmsr_unsafe.cold (STB_LOCAL)
ffffffff8106ffa0-ffffffff8106ffda: ex_handler_wrmsr_unsafe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
bool ex_handler_wrmsr_unsafe(const struct exception_table_entry *fixup, struct pt_regs *regs, int trapnr, long unsigned int error_code, long unsigned int fault_addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/mm/extable.c (0)
Location: arch/x86/mm/extable.c:161
Inline: False
```
**Symbols:**

```
ffffffff8108116e-ffffffff810811a1: ex_handler_wrmsr_unsafe.cold (STB_LOCAL)
ffffffff81081000-ffffffff8108103a: ex_handler_wrmsr_unsafe (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
bool ex_handler_wrmsr_unsafe(const struct exception_table_entry *fixup, struct pt_regs *regs, int trapnr, long unsigned int error_code, long unsigned int fault_addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/mm/extable.c (0)
Location: arch/x86/mm/extable.c:161
Inline: False
```
**Symbols:**

```
ffffffff8108328e-ffffffff810832c1: ex_handler_wrmsr_unsafe.cold (STB_LOCAL)
ffffffff81083120-ffffffff8108315a: ex_handler_wrmsr_unsafe (STB_GLOBAL)
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
