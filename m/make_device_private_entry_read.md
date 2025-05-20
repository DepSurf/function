# Function: <code>make_device_private_entry_read</code>

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
<details>
<summary>In <code>4.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memory.c (0)
Location: include/linux/swapops.h:117
Inline: True
```
```
In mm/mprotect.c (0)
Location: include/linux/swapops.h:117
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memory.c (0)
Location: include/linux/swapops.h:117
Inline: True
```
```
In mm/mprotect.c (ffffffff812393ad)
Location: include/linux/swapops.h:117
Inline: True
Inline callers:
  - mm/mprotect.c:change_pte_range
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
In mm/memory.c (0)
Location: include/linux/swapops.h:113
Inline: True
```
```
In mm/mprotect.c (ffffffff8124db1b)
Location: include/linux/swapops.h:113
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
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
In mm/memory.c (0)
Location: include/linux/swapops.h:113
Inline: True
```
```
In mm/mprotect.c (ffffffff8125f94e)
Location: include/linux/swapops.h:113
Inline: True
Inline callers:
  - mm/mprotect.c:change_pte_range
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
In mm/memory.c (0)
Location: include/linux/swapops.h:113
Inline: True
```
```
In mm/mprotect.c (ffffffff8126e15e)
Location: include/linux/swapops.h:113
Inline: True
Inline callers:
  - mm/mprotect.c:change_pte_range
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
In mm/memory.c (0)
Location: include/linux/swapops.h:115
Inline: True
```
```
In mm/mprotect.c (ffffffff8129e9b3)
Location: include/linux/swapops.h:115
Inline: True
Inline callers:
  - mm/mprotect.c:change_pte_range
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
In mm/memory.c (0)
Location: include/linux/swapops.h:115
Inline: True
```
```
In mm/mprotect.c (ffffffff812a9d68)
Location: include/linux/swapops.h:115
Inline: True
Inline callers:
  - mm/mprotect.c:change_pte_range
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
In mm/memory.c (0)
Location: include/linux/swapops.h:122
Inline: True
```
```
In mm/mprotect.c (ffffffff812af1f3)
Location: include/linux/swapops.h:122
Inline: True
Inline callers:
  - mm/mprotect.c:change_pte_range
```
</details>
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
<details>
<summary>In <code>arm64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memory.c (0)
Location: include/linux/swapops.h:138
Inline: True
```
```
In mm/mprotect.c (0)
Location: include/linux/swapops.h:138
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memory.c (0)
Location: include/linux/swapops.h:138
Inline: True
```
```
In mm/mprotect.c (0)
Location: include/linux/swapops.h:138
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memory.c (0)
Location: include/linux/swapops.h:113
Inline: True
```
```
In mm/mprotect.c (0)
Location: include/linux/swapops.h:113
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memory.c (0)
Location: include/linux/swapops.h:138
Inline: True
```
```
In mm/mprotect.c (0)
Location: include/linux/swapops.h:138
Inline: True
```
</details>
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
In mm/memory.c (0)
Location: include/linux/swapops.h:113
Inline: True
```
```
In mm/mprotect.c (ffffffff812667ae)
Location: include/linux/swapops.h:113
Inline: True
Inline callers:
  - mm/mprotect.c:change_pte_range
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
In mm/memory.c (0)
Location: include/linux/swapops.h:113
Inline: True
```
```
In mm/mprotect.c (ffffffff81258e5c)
Location: include/linux/swapops.h:113
Inline: True
Inline callers:
  - mm/mprotect.c:change_protection_range
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
In mm/memory.c (0)
Location: include/linux/swapops.h:113
Inline: True
```
```
In mm/mprotect.c (ffffffff8126454e)
Location: include/linux/swapops.h:113
Inline: True
Inline callers:
  - mm/mprotect.c:change_pte_range
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
In mm/memory.c (0)
Location: include/linux/swapops.h:113
Inline: True
```
```
In mm/mprotect.c (ffffffff81273f0c)
Location: include/linux/swapops.h:113
Inline: True
Inline callers:
  - mm/mprotect.c:change_pte_range
```
</details>
</li>
</ul>

## Differences
