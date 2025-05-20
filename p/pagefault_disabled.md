# Function: <code>pagefault_disabled</code>

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
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/mm/fault.c (ffffffff8107f854)
Location: include/linux/uaccess.h:206
Inline: True
Inline callers:
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
In arch/x86/mm/fault.c (ffffffff810808e4)
Location: include/linux/uaccess.h:206
Inline: True
Inline callers:
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
In arch/x86/mm/fault.c (ffffffff810878df)
Location: include/linux/uaccess.h:206
Inline: True
Inline callers:
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
In arch/x86/mm/fault.c (ffffffff8108803b)
Location: include/linux/uaccess.h:267
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:do_user_addr_fault
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
In arch/x86/mm/fault.c (ffffffff81088b06)
Location: include/linux/uaccess.h:267
Inline: True
Inline callers:
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
In arch/x86/mm/fault.c (ffffffff81097f3f)
Location: include/linux/uaccess.h:257
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:do_user_addr_fault
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
In arch/x86/mm/fault.c (ffffffff810aab7e)
Location: include/linux/uaccess.h:217
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:do_user_addr_fault
```
```
In lib/scatterlist.c (ffffffff816df4a1)
Location: include/linux/uaccess.h:217
Inline: True
Inline callers:
  - lib/scatterlist.c:sg_miter_stop
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
In arch/x86/mm/fault.c (ffffffff810c486e)
Location: include/linux/uaccess.h:226
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:do_user_addr_fault
```
```
In lib/scatterlist.c (ffffffff817cf6e1)
Location: include/linux/uaccess.h:226
Inline: True
Inline callers:
  - lib/scatterlist.c:sg_miter_stop
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
In arch/x86/mm/fault.c (ffffffff810c806e)
Location: include/linux/uaccess.h:248
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:do_user_addr_fault
```
```
In mm/usercopy.c (ffffffff814a2f7e)
Location: include/linux/uaccess.h:248
Inline: True
Inline callers:
  - mm/usercopy.c:check_heap_object
```
```
In lib/scatterlist.c (ffffffff8180db91)
Location: include/linux/uaccess.h:248
Inline: True
Inline callers:
  - lib/scatterlist.c:sg_miter_stop
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
In arch/x86/mm/fault.c (ffffffff810d0542)
Location: include/linux/uaccess.h:248
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:do_user_addr_fault
```
```
In mm/usercopy.c (ffffffff814d3e10)
Location: include/linux/uaccess.h:248
Inline: True
Inline callers:
  - mm/usercopy.c:check_heap_object
```
```
In lib/scatterlist.c (ffffffff81853841)
Location: include/linux/uaccess.h:248
Inline: True
Inline callers:
  - lib/scatterlist.c:sg_miter_stop
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/arm64/mm/fault.c (ffff800010da901c)
Location: include/linux/uaccess.h:206
Inline: True
Inline callers:
  - arch/arm64/mm/fault.c:do_page_fault
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/arm/mm/fault.c (c0e9f8a8)
Location: include/linux/uaccess.h:206
Inline: True
Inline callers:
  - arch/arm/mm/fault.c:do_page_fault
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/powerpc/mm/fault.c (c000000000086e74)
Location: include/linux/uaccess.h:206
Inline: True
Inline callers:
  - arch/powerpc/mm/fault.c:__do_page_fault
  - arch/powerpc/mm/fault.c:__do_page_fault
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/riscv/mm/fault.c (ffffffe0000b9bc4)
Location: include/linux/uaccess.h:206
Inline: True
Inline callers:
  - arch/riscv/mm/fault.c:do_page_fault
```
</details>
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
In arch/x86/mm/fault.c (ffffffff8107f8e4)
Location: include/linux/uaccess.h:206
Inline: True
Inline callers:
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
In arch/x86/mm/fault.c (ffffffff8106e954)
Location: include/linux/uaccess.h:206
Inline: True
Inline callers:
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
In arch/x86/mm/fault.c (ffffffff8107f894)
Location: include/linux/uaccess.h:206
Inline: True
Inline callers:
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
In arch/x86/mm/fault.c (ffffffff810819bc)
Location: include/linux/uaccess.h:206
Inline: True
Inline callers:
  - arch/x86/mm/fault.c:do_user_addr_fault
```
</details>
</li>
</ul>

## Differences
