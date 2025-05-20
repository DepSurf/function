# Function: <code>is_vsyscall_vaddr</code>

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
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/mm/fault.c (ffffffff8107c221)
Location: arch/x86/mm/fault.c:895
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:__do_page_fault
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/mm/fault.c (ffffffff8107ff60)
Location: arch/x86/mm/fault.c:860
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:__do_page_fault
  - arch/x86/mm/fault.c:do_user_addr_fault
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/mm/fault.c (ffffffff81080ff0)
Location: arch/x86/mm/fault.c:882
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:__do_page_fault
  - arch/x86/mm/fault.c:do_user_addr_fault
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/mm/fault.c (ffffffff81bbf633)
Location: arch/x86/mm/fault.c:846
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:exc_page_fault
  - arch/x86/mm/fault.c:do_user_addr_fault
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/mm/fault.c (ffffffff810880b3)
Location: arch/x86/mm/fault.c:795
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:do_user_addr_fault
  - arch/x86/mm/fault.c:fault_in_kernel_space
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/mm/fault.c (ffffffff81c2a8af)
Location: arch/x86/mm/fault.c:789
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:exc_page_fault
  - arch/x86/mm/fault.c:do_user_addr_fault
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/mm/fault.c (ffffffff81d48e99)
Location: arch/x86/mm/fault.c:794
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:exc_page_fault
  - arch/x86/mm/fault.c:do_user_addr_fault
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
In arch/x86/mm/fault.c (ffffffff81f1821e)
Location: arch/x86/mm/fault.c:794
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:exc_page_fault
  - arch/x86/mm/fault.c:do_user_addr_fault
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
In arch/x86/mm/fault.c (ffffffff820bfa0e)
Location: arch/x86/mm/fault.c:825
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:exc_page_fault
  - arch/x86/mm/fault.c:do_user_addr_fault
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
In arch/x86/mm/fault.c (ffffffff82141711)
Location: arch/x86/mm/fault.c:805
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:exc_page_fault
  - arch/x86/mm/fault.c:do_user_addr_fault
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
In arch/x86/mm/fault.c (ffffffff82223691)
Location: arch/x86/include/asm/vsyscall.h:32
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:exc_page_fault
  - arch/x86/mm/fault.c:do_user_addr_fault
```
```
In arch/x86/mm/maccess.c (ffffffff810d581f)
Location: arch/x86/include/asm/vsyscall.h:32
Inline: True
Inline callers:
  - arch/x86/mm/maccess.c:copy_from_kernel_nofault_allowed
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
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/mm/fault.c (ffffffff8107fff0)
Location: arch/x86/mm/fault.c:882
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:__do_page_fault
  - arch/x86/mm/fault.c:do_user_addr_fault
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/mm/fault.c (ffffffff8106ed70)
Location: arch/x86/mm/fault.c:882
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:__do_page_fault
  - arch/x86/mm/fault.c:do_user_addr_fault
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/mm/fault.c (ffffffff8107ffa0)
Location: arch/x86/mm/fault.c:882
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:__do_page_fault
  - arch/x86/mm/fault.c:do_user_addr_fault
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/mm/fault.c (ffffffff810820a0)
Location: arch/x86/mm/fault.c:882
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:__do_page_fault
  - arch/x86/mm/fault.c:do_user_addr_fault
```
</details>
</li>
</ul>

## Differences
