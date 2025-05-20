# Function: <code>kfence_handle_page_fault</code>

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
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/mm/fault.c (0)
Location: include/linux/kfence.h:215
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
bool kfence_handle_page_fault(long unsigned int addr, bool is_write, struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/kfence/core.c (0)
Location: mm/kfence/core.c:819
Inline: False
Direct callers:
  - arch/x86/mm/fault.c:page_fault_oops
```
**Symbols:**

```
ffffffff81cc1eaa-ffffffff81cc1ebf: kfence_handle_page_fault.cold (STB_LOCAL)
ffffffff8133c8f0-ffffffff8133cbbb: kfence_handle_page_fault (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
bool kfence_handle_page_fault(long unsigned int addr, bool is_write, struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/kfence/core.c (0)
Location: mm/kfence/core.c:1087
Inline: False
Direct callers:
  - arch/x86/mm/fault.c:page_fault_oops
```
**Symbols:**

```
ffffffff81e74424-ffffffff81e74447: kfence_handle_page_fault.cold (STB_LOCAL)
ffffffff813afcf0-ffffffff813b003a: kfence_handle_page_fault (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
bool kfence_handle_page_fault(long unsigned int addr, bool is_write, struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/kfence/core.c (0)
Location: mm/kfence/core.c:1073
Inline: False
Direct callers:
  - arch/x86/mm/fault.c:page_fault_oops
```
**Symbols:**

```
ffffffff82067957-ffffffff8206797a: kfence_handle_page_fault.cold (STB_LOCAL)
ffffffff814302f0-ffffffff8143063a: kfence_handle_page_fault (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
bool kfence_handle_page_fault(long unsigned int addr, bool is_write, struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/kfence/core.c (0)
Location: mm/kfence/core.c:1111
Inline: False
Direct callers:
  - arch/x86/mm/fault.c:page_fault_oops
```
**Symbols:**

```
ffffffff820e728b-ffffffff820e72a8: kfence_handle_page_fault.cold (STB_LOCAL)
ffffffff81465c80-ffffffff81465f9b: kfence_handle_page_fault (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
bool kfence_handle_page_fault(long unsigned int addr, bool is_write, struct pt_regs *regs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/kfence/core.c (0)
Location: mm/kfence/core.c:1157
Inline: False
Direct callers:
  - arch/x86/mm/fault.c:page_fault_oops
```
**Symbols:**

```
ffffffff821c3e43-ffffffff821c3e6e: kfence_handle_page_fault.cold (STB_LOCAL)
ffffffff81494ee0-ffffffff814951ac: kfence_handle_page_fault (STB_GLOBAL)
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
