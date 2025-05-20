# Function: <code>ex_handler_ext</code>

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
bool ex_handler_ext(const struct exception_table_entry *fixup, struct pt_regs *regs, int trapnr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/extable.c (ffffffff8106be60)
Location: arch/x86/mm/extable.c:37
Inline: False
```
**Symbols:**

```
ffffffff8106be60-ffffffff8106be90: ex_handler_ext (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
bool ex_handler_ext(const struct exception_table_entry *fixup, struct pt_regs *regs, int trapnr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/extable.c (ffffffff8106fa80)
Location: arch/x86/mm/extable.c:37
Inline: False
```
**Symbols:**

```
ffffffff8106fa80-ffffffff8106fab0: ex_handler_ext (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
bool ex_handler_ext(const struct exception_table_entry *fixup, struct pt_regs *regs, int trapnr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/extable.c (ffffffff8106f1a0)
Location: arch/x86/mm/extable.c:39
Inline: False
```
**Symbols:**

```
ffffffff8106f1a0-ffffffff8106f1d0: ex_handler_ext (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
bool ex_handler_ext(const struct exception_table_entry *fixup, struct pt_regs *regs, int trapnr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/extable.c (ffffffff81074450)
Location: arch/x86/mm/extable.c:111
Inline: False
```
**Symbols:**

```
ffffffff81074450-ffffffff81074480: ex_handler_ext (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
bool ex_handler_ext(const struct exception_table_entry *fixup, struct pt_regs *regs, int trapnr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/extable.c (ffffffff81076eb0)
Location: arch/x86/mm/extable.c:111
Inline: False
```
**Symbols:**

```
ffffffff81076eb0-ffffffff81076ee0: ex_handler_ext (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
bool ex_handler_ext(const struct exception_table_entry *fixup, struct pt_regs *regs, int trapnr, long unsigned int error_code, long unsigned int fault_addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/extable.c (ffffffff8107d540)
Location: arch/x86/mm/extable.c:130
Inline: False
```
**Symbols:**

```
ffffffff8107d540-ffffffff8107d570: ex_handler_ext (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
bool ex_handler_ext(const struct exception_table_entry *fixup, struct pt_regs *regs, int trapnr, long unsigned int error_code, long unsigned int fault_addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/extable.c (ffffffff81080e10)
Location: arch/x86/mm/extable.c:132
Inline: False
```
**Symbols:**

```
ffffffff81080e10-ffffffff81080e40: ex_handler_ext (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
bool ex_handler_ext(const struct exception_table_entry *fixup, struct pt_regs *regs, int trapnr, long unsigned int error_code, long unsigned int fault_addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/extable.c (ffffffff81081ed0)
Location: arch/x86/mm/extable.c:132
Inline: False
```
**Symbols:**

```
ffffffff81081ed0-ffffffff81081f00: ex_handler_ext (STB_GLOBAL)
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
bool ex_handler_ext(const struct exception_table_entry *fixup, struct pt_regs *regs, int trapnr, long unsigned int error_code, long unsigned int fault_addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/extable.c (ffffffff81080ed0)
Location: arch/x86/mm/extable.c:132
Inline: False
```
**Symbols:**

```
ffffffff81080ed0-ffffffff81080f00: ex_handler_ext (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
bool ex_handler_ext(const struct exception_table_entry *fixup, struct pt_regs *regs, int trapnr, long unsigned int error_code, long unsigned int fault_addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/extable.c (ffffffff8106fe20)
Location: arch/x86/mm/extable.c:132
Inline: False
```
**Symbols:**

```
ffffffff8106fe20-ffffffff8106fe50: ex_handler_ext (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
bool ex_handler_ext(const struct exception_table_entry *fixup, struct pt_regs *regs, int trapnr, long unsigned int error_code, long unsigned int fault_addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/extable.c (ffffffff81080e80)
Location: arch/x86/mm/extable.c:132
Inline: False
```
**Symbols:**

```
ffffffff81080e80-ffffffff81080eb0: ex_handler_ext (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
bool ex_handler_ext(const struct exception_table_entry *fixup, struct pt_regs *regs, int trapnr, long unsigned int error_code, long unsigned int fault_addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/extable.c (ffffffff81082fa0)
Location: arch/x86/mm/extable.c:132
Inline: False
```
**Symbols:**

```
ffffffff81082fa0-ffffffff81082fd0: ex_handler_ext (STB_GLOBAL)
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
