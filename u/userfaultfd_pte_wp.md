# Function: <code>userfaultfd_pte_wp</code>

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
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/memory.c (ffffffff81290ee9)
Location: include/linux/userfaultfd_k.h:65
Inline: True
Inline callers:
  - mm/memory.c:do_wp_page
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
In mm/memory.c (ffffffff8129b976)
Location: include/linux/userfaultfd_k.h:65
Inline: True
Inline callers:
  - mm/memory.c:do_wp_page
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
In mm/memory.c (ffffffff812a0a6f)
Location: include/linux/userfaultfd_k.h:107
Inline: True
Inline callers:
  - mm/memory.c:do_wp_page
  - mm/memory.c:copy_pte_range
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
In mm/memory.c (ffffffff812e1b8f)
Location: include/linux/userfaultfd_k.h:112
Inline: True
Inline callers:
  - mm/memory.c:do_wp_page
  - mm/memory.c:copy_pte_range
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
In mm/gup.c (ffffffff81338876)
Location: include/linux/userfaultfd_k.h:129
Inline: True
Inline callers:
  - mm/gup.c:follow_page_pte
```
```
In mm/memory.c (ffffffff813429c4)
Location: include/linux/userfaultfd_k.h:129
Inline: True
Inline callers:
  - mm/memory.c:do_wp_page
  - mm/memory.c:copy_present_pte
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
In mm/gup.c (ffffffff813b003f)
Location: include/linux/userfaultfd_k.h:129
Inline: True
Inline callers:
  - mm/gup.c:follow_page_pte
```
```
In mm/memory.c (ffffffff813baa40)
Location: include/linux/userfaultfd_k.h:129
Inline: True
Inline callers:
  - mm/memory.c:do_wp_page
  - mm/memory.c:copy_present_pte
```
```
In mm/mprotect.c (ffffffff813cdd7a)
Location: include/linux/userfaultfd_k.h:129
Inline: True
Inline callers:
  - mm/mprotect.c:can_change_pte_writable
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
In mm/gup.c (ffffffff813e466b)
Location: include/linux/userfaultfd_k.h:142
Inline: True
Inline callers:
  - mm/gup.c:follow_page_pte
```
```
In mm/memory.c (ffffffff813ef550)
Location: include/linux/userfaultfd_k.h:142
Inline: True
Inline callers:
  - mm/memory.c:do_wp_page
  - mm/memory.c:copy_present_pte
```
```
In mm/mprotect.c (ffffffff8140273a)
Location: include/linux/userfaultfd_k.h:142
Inline: True
Inline callers:
  - mm/mprotect.c:can_change_pte_writable
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
In mm/gup.c (ffffffff8140f013)
Location: include/linux/userfaultfd_k.h:157
Inline: True
Inline callers:
  - mm/gup.c:follow_page_pte
```
```
In mm/memory.c (ffffffff814199b0)
Location: include/linux/userfaultfd_k.h:157
Inline: True
Inline callers:
  - mm/memory.c:do_wp_page
  - mm/memory.c:copy_present_pte
```
```
In mm/mprotect.c (ffffffff8142ed6a)
Location: include/linux/userfaultfd_k.h:157
Inline: True
Inline callers:
  - mm/mprotect.c:can_change_pte_writable
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
