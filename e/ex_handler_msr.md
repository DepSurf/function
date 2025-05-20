# Function: <code>ex_handler_msr</code>

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
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
bool ex_handler_msr(const struct exception_table_entry *fixup, struct pt_regs *regs, bool wrmsr, bool safe, int reg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/mm/extable.c (0)
Location: arch/x86/mm/extable.c:94
Inline: False
Direct callers:
  - arch/x86/mm/extable.c:fixup_exception
  - arch/x86/mm/extable.c:fixup_exception
```
**Symbols:**

```
ffffffff810ac0a0-ffffffff810ac1bd: ex_handler_msr (STB_LOCAL)
ffffffff81e50527-ffffffff81e505c3: ex_handler_msr.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
bool ex_handler_msr(const struct exception_table_entry *fixup, struct pt_regs *regs, bool wrmsr, bool safe, int reg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/mm/extable.c (0)
Location: arch/x86/mm/extable.c:147
Inline: False
Direct callers:
  - arch/x86/mm/extable.c:fixup_exception
  - arch/x86/mm/extable.c:fixup_exception
```
**Symbols:**

```
ffffffff810c6000-ffffffff810c6187: ex_handler_msr (STB_LOCAL)
ffffffff82054a68-ffffffff82054aa4: ex_handler_msr.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
bool ex_handler_msr(const struct exception_table_entry *fixup, struct pt_regs *regs, bool wrmsr, bool safe, int reg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/mm/extable.c (0)
Location: arch/x86/mm/extable.c:173
Inline: False
Direct callers:
  - arch/x86/mm/extable.c:fixup_exception
  - arch/x86/mm/extable.c:fixup_exception
```
**Symbols:**

```
ffffffff810c9780-ffffffff810c98f7: ex_handler_msr (STB_LOCAL)
ffffffff820d3074-ffffffff820d30ae: ex_handler_msr.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
bool ex_handler_msr(const struct exception_table_entry *fixup, struct pt_regs *regs, bool wrmsr, bool safe, int reg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/mm/extable.c (0)
Location: arch/x86/mm/extable.c:173
Inline: False
Direct callers:
  - arch/x86/mm/extable.c:fixup_exception
  - arch/x86/mm/extable.c:fixup_exception
```
**Symbols:**

```
ffffffff810d1be0-ffffffff810d1d57: ex_handler_msr (STB_LOCAL)
ffffffff821adee2-ffffffff821adf1c: ex_handler_msr.cold (STB_LOCAL)
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
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
