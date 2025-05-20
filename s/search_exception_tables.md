# Function: <code>search_exception_tables</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
const struct exception_table_entry *search_exception_tables(long unsigned int addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/extable.c (ffffffff8109e990)
Location: kernel/extable.c:51
Inline: False
Direct callers:
  - arch/x86/kernel/kprobes/opt.c:can_optimize
  - arch/x86/mm/fault.c:__do_page_fault
  - arch/x86/mm/extable.c:fixup_exception
  - arch/x86/mm/extable.c:early_fixup_exception
```
**Symbols:**

```
ffffffff8109e990-ffffffff8109e9c9: search_exception_tables (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
const struct exception_table_entry *search_exception_tables(long unsigned int addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/extable.c (ffffffff810a2040)
Location: kernel/extable.c:51
Inline: False
Direct callers:
  - arch/x86/kernel/kprobes/opt.c:can_optimize
  - arch/x86/mm/fault.c:__do_page_fault
  - arch/x86/mm/extable.c:fixup_exception
  - arch/x86/mm/extable.c:ex_has_fault_handler
```
**Symbols:**

```
ffffffff810a2040-ffffffff810a2079: search_exception_tables (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
const struct exception_table_entry *search_exception_tables(long unsigned int addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/extable.c (ffffffff810a7100)
Location: kernel/extable.c:51
Inline: False
Direct callers:
  - arch/x86/kernel/kprobes/opt.c:can_optimize
  - arch/x86/mm/fault.c:__do_page_fault
  - arch/x86/mm/extable.c:fixup_exception
  - arch/x86/mm/extable.c:ex_has_fault_handler
```
**Symbols:**

```
ffffffff810a7100-ffffffff810a7139: search_exception_tables (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
const struct exception_table_entry *search_exception_tables(long unsigned int addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/extable.c (ffffffff810a4030)
Location: kernel/extable.c:54
Inline: False
Direct callers:
  - arch/x86/kernel/kprobes/opt.c:can_optimize
  - arch/x86/mm/fault.c:__do_page_fault
  - arch/x86/mm/extable.c:fixup_exception
  - arch/x86/mm/extable.c:ex_has_fault_handler
```
**Symbols:**

```
ffffffff810a4030-ffffffff810a407f: search_exception_tables (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
const struct exception_table_entry *search_exception_tables(long unsigned int addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/extable.c (ffffffff810aa660)
Location: kernel/extable.c:56
Inline: False
Direct callers:
  - arch/x86/kernel/kprobes/opt.c:can_optimize
  - arch/x86/mm/fault.c:__do_page_fault
  - arch/x86/mm/extable.c:fixup_exception
  - arch/x86/mm/extable.c:ex_has_fault_handler
```
**Symbols:**

```
ffffffff810aa660-ffffffff810aa6af: search_exception_tables (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
const struct exception_table_entry *search_exception_tables(long unsigned int addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/extable.c (ffffffff810b1290)
Location: kernel/extable.c:56
Inline: False
Direct callers:
  - arch/x86/kernel/kprobes/opt.c:can_optimize
  - arch/x86/mm/fault.c:__do_page_fault
  - arch/x86/mm/extable.c:fixup_exception
  - arch/x86/mm/extable.c:ex_has_fault_handler
```
**Symbols:**

```
ffffffff810b1290-ffffffff810b12df: search_exception_tables (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
const struct exception_table_entry *search_exception_tables(long unsigned int addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/extable.c (ffffffff810ba3d0)
Location: kernel/extable.c:56
Inline: False
Direct callers:
  - arch/x86/kernel/kprobes/opt.c:can_optimize
  - arch/x86/mm/fault.c:__do_page_fault
  - arch/x86/mm/extable.c:fixup_exception
  - arch/x86/mm/extable.c:ex_has_fault_handler
```
**Symbols:**

```
ffffffff810ba3d0-ffffffff810ba41f: search_exception_tables (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
const struct exception_table_entry *search_exception_tables(long unsigned int addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/extable.c (ffffffff810c02d0)
Location: kernel/extable.c:44
Inline: False
Direct callers:
  - arch/x86/kernel/kprobes/opt.c:can_optimize
  - arch/x86/mm/fault.c:do_user_addr_fault
  - arch/x86/mm/extable.c:fixup_exception
  - arch/x86/mm/extable.c:ex_has_fault_handler
```
**Symbols:**

```
ffffffff810c02d0-ffffffff810c0322: search_exception_tables (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
const struct exception_table_entry *search_exception_tables(long unsigned int addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/extable.c (ffffffff810c66d0)
Location: kernel/extable.c:52
Inline: False
Direct callers:
  - arch/x86/kernel/kprobes/opt.c:can_optimize
  - arch/x86/mm/fault.c:do_user_addr_fault
  - arch/x86/mm/extable.c:fixup_exception
  - arch/x86/mm/extable.c:ex_has_fault_handler
```
**Symbols:**

```
ffffffff810c66d0-ffffffff810c6722: search_exception_tables (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
const struct exception_table_entry *search_exception_tables(long unsigned int addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/extable.c (ffffffff810ce740)
Location: kernel/extable.c:53
Inline: False
Direct callers:
  - arch/x86/kernel/kprobes/opt.c:can_optimize
  - arch/x86/mm/fault.c:do_user_addr_fault
  - arch/x86/mm/extable.c:fixup_exception
  - arch/x86/mm/extable.c:ex_has_fault_handler
```
**Symbols:**

```
ffffffff810ce740-ffffffff810ce7a3: search_exception_tables (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
const struct exception_table_entry *search_exception_tables(long unsigned int addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/extable.c (ffffffff810c9260)
Location: kernel/extable.c:53
Inline: False
Direct callers:
  - arch/x86/kernel/kprobes/opt.c:can_optimize
  - arch/x86/mm/fault.c:do_user_addr_fault
  - arch/x86/mm/extable.c:fixup_exception
  - arch/x86/mm/extable.c:ex_get_fault_handler_type
```
**Symbols:**

```
ffffffff810c9260-ffffffff810c92c3: search_exception_tables (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
const struct exception_table_entry *search_exception_tables(long unsigned int addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/extable.c (ffffffff810cacf0)
Location: kernel/extable.c:53
Inline: False
Direct callers:
  - arch/x86/kernel/kprobes/opt.c:can_optimize
  - arch/x86/mm/fault.c:do_user_addr_fault
  - arch/x86/mm/extable.c:fixup_exception
  - arch/x86/mm/extable.c:ex_get_fault_handler_type
```
**Symbols:**

```
ffffffff810cacf0-ffffffff810cad53: search_exception_tables (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
const struct exception_table_entry *search_exception_tables(long unsigned int addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/extable.c (ffffffff810dddd0)
Location: kernel/extable.c:53
Inline: False
Direct callers:
  - arch/x86/kernel/kprobes/opt.c:can_optimize
  - arch/x86/mm/fault.c:do_user_addr_fault
  - arch/x86/mm/extable.c:fixup_exception
  - arch/x86/mm/extable.c:ex_get_fault_handler_type
```
**Symbols:**

```
ffffffff810dddd0-ffffffff810dde33: search_exception_tables (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
const struct exception_table_entry *search_exception_tables(long unsigned int addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/extable.c (ffffffff810f7a10)
Location: kernel/extable.c:54
Inline: False
Direct callers:
  - arch/x86/kernel/kprobes/core.c:can_boost
  - arch/x86/kernel/kprobes/opt.c:can_optimize
  - arch/x86/mm/fault.c:do_user_addr_fault
  - arch/x86/mm/extable.c:fixup_exception
  - arch/x86/mm/extable.c:ex_get_fixup_type
```
**Symbols:**

```
ffffffff810f7a10-ffffffff810f7a78: search_exception_tables (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
const struct exception_table_entry *search_exception_tables(long unsigned int addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/extable.c (ffffffff8111a220)
Location: kernel/extable.c:54
Inline: False
Direct callers:
  - arch/x86/kernel/kprobes/core.c:can_boost
  - arch/x86/kernel/kprobes/opt.c:can_optimize
  - arch/x86/mm/fault.c:do_user_addr_fault
  - arch/x86/mm/extable.c:fixup_exception
  - arch/x86/mm/extable.c:ex_get_fixup_type
```
**Symbols:**

```
ffffffff8111a220-ffffffff8111a288: search_exception_tables (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
const struct exception_table_entry *search_exception_tables(long unsigned int addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/extable.c (ffffffff81127490)
Location: kernel/extable.c:54
Inline: False
Direct callers:
  - arch/x86/kernel/kprobes/core.c:can_boost
  - arch/x86/kernel/kprobes/opt.c:can_optimize
  - arch/x86/mm/extable.c:fixup_exception
  - arch/x86/mm/extable.c:ex_get_fixup_type
  - mm/memory.c:lock_mm_and_find_vma
  - mm/memory.c:lock_mm_and_find_vma
```
**Symbols:**

```
ffffffff81127490-ffffffff811274f8: search_exception_tables (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
const struct exception_table_entry *search_exception_tables(long unsigned int addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/extable.c (ffffffff81131a70)
Location: kernel/extable.c:54
Inline: False
Direct callers:
  - arch/x86/kernel/kprobes/core.c:can_boost
  - arch/x86/kernel/kprobes/opt.c:can_optimize
  - arch/x86/mm/extable.c:fixup_exception
  - arch/x86/mm/extable.c:ex_get_fixup_type
  - mm/memory.c:lock_mm_and_find_vma
  - mm/memory.c:lock_mm_and_find_vma
```
**Symbols:**

```
ffffffff81131a70-ffffffff81131ad8: search_exception_tables (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
const struct exception_table_entry *search_exception_tables(long unsigned int addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/extable.c (ffff800010125218)
Location: kernel/extable.c:52
Inline: False
Direct callers:
  - arch/arm64/kernel/probes/kprobes.c:arch_prepare_kprobe
  - arch/arm64/mm/extable.c:fixup_exception
  - arch/arm64/mm/fault.c:do_page_fault
  - arch/arm64/mm/fault.c:do_page_fault
```
**Symbols:**

```
ffff800010125218-ffff800010125274: search_exception_tables (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
const struct exception_table_entry *search_exception_tables(long unsigned int addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/extable.c (c0378024)
Location: kernel/extable.c:52
Inline: False
Direct callers:
  - arch/arm/mm/extable.c:fixup_exception
  - arch/arm/mm/fault.c:do_page_fault
```
**Symbols:**

```
c0378024-c0378074: search_exception_tables (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
const struct exception_table_entry *search_exception_tables(long unsigned int addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/extable.c (c00000000016ef90)
Location: kernel/extable.c:52
Inline: False
Direct callers:
  - arch/powerpc/kernel/kprobes.c:kprobe_fault_handler
  - arch/powerpc/mm/fault.c:bad_page_fault
  - arch/powerpc/mm/fault.c:__do_page_fault
  - arch/powerpc/mm/fault.c:__do_page_fault
  - arch/powerpc/mm/fault.c:__do_page_fault
```
**Symbols:**

```
c00000000016ef90-c00000000016f020: search_exception_tables (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
const struct exception_table_entry *search_exception_tables(long unsigned int addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/extable.c (ffffffe0000dcfcc)
Location: kernel/extable.c:52
Inline: False
Direct callers:
  - arch/riscv/mm/extable.c:fixup_exception
```
**Symbols:**

```
ffffffe0000dcfcc-ffffffe0000dd020: search_exception_tables (STB_GLOBAL)
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
const struct exception_table_entry *search_exception_tables(long unsigned int addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/extable.c (ffffffff810c0a50)
Location: kernel/extable.c:52
Inline: False
Direct callers:
  - arch/x86/kernel/kprobes/opt.c:can_optimize
  - arch/x86/mm/fault.c:do_user_addr_fault
  - arch/x86/mm/extable.c:fixup_exception
  - arch/x86/mm/extable.c:ex_has_fault_handler
```
**Symbols:**

```
ffffffff810c0a50-ffffffff810c0aa2: search_exception_tables (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
const struct exception_table_entry *search_exception_tables(long unsigned int addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/extable.c (ffffffff810af240)
Location: kernel/extable.c:52
Inline: False
Direct callers:
  - arch/x86/kernel/kprobes/opt.c:can_optimize
  - arch/x86/mm/fault.c:do_user_addr_fault
  - arch/x86/mm/extable.c:fixup_exception
  - arch/x86/mm/extable.c:ex_has_fault_handler
```
**Symbols:**

```
ffffffff810af240-ffffffff810af292: search_exception_tables (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
const struct exception_table_entry *search_exception_tables(long unsigned int addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/extable.c (ffffffff810bffa0)
Location: kernel/extable.c:52
Inline: False
Direct callers:
  - arch/x86/kernel/kprobes/opt.c:can_optimize
  - arch/x86/mm/fault.c:do_user_addr_fault
  - arch/x86/mm/extable.c:fixup_exception
  - arch/x86/mm/extable.c:ex_has_fault_handler
```
**Symbols:**

```
ffffffff810bffa0-ffffffff810bfff2: search_exception_tables (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
const struct exception_table_entry *search_exception_tables(long unsigned int addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/extable.c (ffffffff810c83d0)
Location: kernel/extable.c:52
Inline: False
Direct callers:
  - arch/x86/kernel/kprobes/opt.c:can_optimize
  - arch/x86/mm/fault.c:do_user_addr_fault
  - arch/x86/mm/extable.c:fixup_exception
  - arch/x86/mm/extable.c:ex_has_fault_handler
```
**Symbols:**

```
ffffffff810c83d0-ffffffff810c8422: search_exception_tables (STB_GLOBAL)
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
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
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
