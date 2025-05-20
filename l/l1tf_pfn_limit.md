# Function: <code>l1tf_pfn_limit</code>

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
<details>
<summary>In <code>4.18</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/bugs.c (ffffffff826de99e)
Location: arch/x86/include/asm/processor.h:186
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/bugs.c:check_bugs
```
```
In arch/x86/mm/init.c (ffffffff810730ac)
Location: arch/x86/include/asm/processor.h:186
Inline: True
Inline callers:
  - arch/x86/mm/init.c:max_swapfile_size
```
```
In arch/x86/mm/mmap.c (ffffffff8107acd0)
Location: arch/x86/include/asm/processor.h:186
Inline: True
Inline callers:
  - arch/x86/mm/mmap.c:pfn_modify_allowed
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/bugs.c (ffffffff82895041)
Location: arch/x86/include/asm/processor.h:175
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/bugs.c:check_bugs
```
```
In arch/x86/mm/init.c (ffffffff81079146)
Location: arch/x86/include/asm/processor.h:175
Inline: True
Inline callers:
  - arch/x86/mm/init.c:max_swapfile_size
```
```
In arch/x86/mm/mmap.c (ffffffff81081610)
Location: arch/x86/include/asm/processor.h:175
Inline: True
Inline callers:
  - arch/x86/mm/mmap.c:pfn_modify_allowed
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/bugs.c (ffffffff828aca2b)
Location: arch/x86/include/asm/processor.h:178
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/bugs.c:check_bugs
```
```
In arch/x86/mm/init.c (ffffffff8107cd46)
Location: arch/x86/include/asm/processor.h:178
Inline: True
Inline callers:
  - arch/x86/mm/init.c:max_swapfile_size
```
```
In arch/x86/mm/mmap.c (ffffffff810852ab)
Location: arch/x86/include/asm/processor.h:178
Inline: True
Inline callers:
  - arch/x86/mm/mmap.c:pfn_modify_allowed
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/bugs.c (ffffffff828afb9f)
Location: arch/x86/include/asm/processor.h:178
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/bugs.c:check_bugs
```
```
In arch/x86/mm/init.c (ffffffff8107dde6)
Location: arch/x86/include/asm/processor.h:178
Inline: True
Inline callers:
  - arch/x86/mm/init.c:max_swapfile_size
```
```
In arch/x86/mm/mmap.c (ffffffff81085f9b)
Location: arch/x86/include/asm/processor.h:178
Inline: True
Inline callers:
  - arch/x86/mm/mmap.c:pfn_modify_allowed
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/bugs.c (ffffffff82cd4d21)
Location: arch/x86/include/asm/processor.h:192
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/bugs.c:l1tf_select_mitigation
```
```
In arch/x86/mm/init.c (ffffffff810844e6)
Location: arch/x86/include/asm/processor.h:192
Inline: True
Inline callers:
  - arch/x86/mm/init.c:max_swapfile_size
```
```
In arch/x86/mm/mmap.c (ffffffff810896f8)
Location: arch/x86/include/asm/processor.h:192
Inline: True
Inline callers:
  - arch/x86/mm/mmap.c:pfn_modify_allowed
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/bugs.c (ffffffff82fc0cc7)
Location: arch/x86/include/asm/processor.h:192
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/bugs.c:l1tf_select_mitigation
```
```
In arch/x86/mm/init.c (ffffffff81085a36)
Location: arch/x86/include/asm/processor.h:192
Inline: True
Inline callers:
  - arch/x86/mm/init.c:max_swapfile_size
```
```
In arch/x86/mm/mmap.c (ffffffff810898d8)
Location: arch/x86/include/asm/processor.h:192
Inline: True
Inline callers:
  - arch/x86/mm/mmap.c:pfn_modify_allowed
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/bugs.c (ffffffff831cb07f)
Location: arch/x86/include/asm/processor.h:192
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/bugs.c:l1tf_select_mitigation
```
```
In arch/x86/mm/init.c (ffffffff81086727)
Location: arch/x86/include/asm/processor.h:192
Inline: True
Inline callers:
  - arch/x86/mm/init.c:max_swapfile_size
```
```
In arch/x86/mm/mmap.c (ffffffff8108a57e)
Location: arch/x86/include/asm/processor.h:192
Inline: True
Inline callers:
  - arch/x86/mm/mmap.c:pfn_modify_allowed
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/bugs.c (ffffffff832ac6a4)
Location: arch/x86/include/asm/processor.h:194
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/bugs.c:l1tf_select_mitigation
```
```
In arch/x86/mm/init.c (ffffffff810959fd)
Location: arch/x86/include/asm/processor.h:194
Inline: True
Inline callers:
  - arch/x86/mm/init.c:max_swapfile_size
```
```
In arch/x86/mm/mmap.c (ffffffff81099b03)
Location: arch/x86/include/asm/processor.h:194
Inline: True
Inline callers:
  - arch/x86/mm/mmap.c:pfn_modify_allowed
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/bugs.c (ffffffff8345ce59)
Location: arch/x86/include/asm/processor.h:197
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/bugs.c:l1tf_select_mitigation
```
```
In arch/x86/mm/init.c (ffffffff810a7bf9)
Location: arch/x86/include/asm/processor.h:197
Inline: True
Inline callers:
  - arch/x86/mm/init.c:max_swapfile_size
```
```
In arch/x86/mm/mmap.c (ffffffff810acafd)
Location: arch/x86/include/asm/processor.h:197
Inline: True
Inline callers:
  - arch/x86/mm/mmap.c:pfn_modify_allowed
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/bugs.c (ffffffff83e7d2d8)
Location: arch/x86/include/asm/processor.h:187
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/bugs.c:l1tf_select_mitigation
```
```
In arch/x86/mm/init.c (ffffffff810c1079)
Location: arch/x86/include/asm/processor.h:187
Inline: True
Inline callers:
  - arch/x86/mm/init.c:arch_max_swapfile_size
```
```
In arch/x86/mm/mmap.c (ffffffff810c6b95)
Location: arch/x86/include/asm/processor.h:187
Inline: True
Inline callers:
  - arch/x86/mm/mmap.c:pfn_modify_allowed
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/bugs.c (ffffffff8369ffd5)
Location: arch/x86/include/asm/processor.h:187
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/bugs.c:l1tf_select_mitigation
```
```
In arch/x86/mm/init.c (ffffffff810c4758)
Location: arch/x86/include/asm/processor.h:187
Inline: True
Inline callers:
  - arch/x86/mm/init.c:arch_max_swapfile_size
```
```
In arch/x86/mm/mmap.c (ffffffff810ca341)
Location: arch/x86/include/asm/processor.h:187
Inline: True
Inline callers:
  - arch/x86/mm/mmap.c:pfn_modify_allowed
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/bugs.c (ffffffff838cff25)
Location: arch/x86/include/asm/processor.h:203
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/bugs.c:l1tf_select_mitigation
```
```
In arch/x86/mm/init.c (ffffffff810ccba9)
Location: arch/x86/include/asm/processor.h:203
Inline: True
Inline callers:
  - arch/x86/mm/init.c:arch_max_swapfile_size
```
```
In arch/x86/mm/mmap.c (ffffffff810d27c2)
Location: arch/x86/include/asm/processor.h:203
Inline: True
Inline callers:
  - arch/x86/mm/mmap.c:pfn_modify_allowed
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
<summary>In <code>aws</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/bugs.c (ffffffff8289dbbe)
Location: arch/x86/include/asm/processor.h:178
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/bugs.c:check_bugs
```
```
In arch/x86/mm/init.c (ffffffff8107cde6)
Location: arch/x86/include/asm/processor.h:178
Inline: True
Inline callers:
  - arch/x86/mm/init.c:max_swapfile_size
```
```
In arch/x86/mm/mmap.c (ffffffff81084f9b)
Location: arch/x86/include/asm/processor.h:178
Inline: True
Inline callers:
  - arch/x86/mm/mmap.c:pfn_modify_allowed
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/bugs.c (ffffffff82895dcf)
Location: arch/x86/include/asm/processor.h:178
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/bugs.c:check_bugs
```
```
In arch/x86/mm/init.c (ffffffff8106c556)
Location: arch/x86/include/asm/processor.h:178
Inline: True
Inline callers:
  - arch/x86/mm/init.c:max_swapfile_size
```
```
In arch/x86/mm/mmap.c (ffffffff81073c6b)
Location: arch/x86/include/asm/processor.h:178
Inline: True
Inline callers:
  - arch/x86/mm/mmap.c:pfn_modify_allowed
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/bugs.c (ffffffff828b0b81)
Location: arch/x86/include/asm/processor.h:178
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/bugs.c:check_bugs
```
```
In arch/x86/mm/init.c (ffffffff8107cd96)
Location: arch/x86/include/asm/processor.h:178
Inline: True
Inline callers:
  - arch/x86/mm/init.c:max_swapfile_size
```
```
In arch/x86/mm/mmap.c (ffffffff81084f4b)
Location: arch/x86/include/asm/processor.h:178
Inline: True
Inline callers:
  - arch/x86/mm/mmap.c:pfn_modify_allowed
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/bugs.c (ffffffff828b0baf)
Location: arch/x86/include/asm/processor.h:178
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/bugs.c:check_bugs
```
```
In arch/x86/mm/init.c (ffffffff8107ee96)
Location: arch/x86/include/asm/processor.h:178
Inline: True
Inline callers:
  - arch/x86/mm/init.c:max_swapfile_size
```
```
In arch/x86/mm/mmap.c (ffffffff8108709b)
Location: arch/x86/include/asm/processor.h:178
Inline: True
Inline callers:
  - arch/x86/mm/mmap.c:pfn_modify_allowed
```
</details>
</li>
</ul>

## Differences
