# Function: <code>ex_handler_zeropad</code>

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
In <code>5.0</code>: Absent ⚠️
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
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
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
bool ex_handler_zeropad(const struct exception_table_entry *e, struct pt_regs *regs, long unsigned int fault_addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/extable.c (ffffffff810c5dd0)
Location: arch/x86/mm/extable.c:56
Inline: False
Direct callers:
  - arch/x86/mm/extable.c:fixup_exception
```
**Symbols:**

```
ffffffff810c5dd0-ffffffff810c5f33: ex_handler_zeropad (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
bool ex_handler_zeropad(const struct exception_table_entry *e, struct pt_regs *regs, long unsigned int fault_addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/extable.c (ffffffff810c9540)
Location: arch/x86/mm/extable.c:56
Inline: False
Direct callers:
  - arch/x86/mm/extable.c:fixup_exception
```
**Symbols:**

```
ffffffff810c9540-ffffffff810c96a3: ex_handler_zeropad (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
bool ex_handler_zeropad(const struct exception_table_entry *e, struct pt_regs *regs, long unsigned int fault_addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/extable.c (ffffffff810d19a0)
Location: arch/x86/mm/extable.c:56
Inline: False
Direct callers:
  - arch/x86/mm/extable.c:fixup_exception
```
**Symbols:**

```
ffffffff810d19a0-ffffffff810d1b03: ex_handler_zeropad (STB_LOCAL)
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
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
