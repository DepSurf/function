# Function: <code>node_reclaim_enabled</code>

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
<summary>In <code>5.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/page_alloc.c (ffffffff812c2f60)
Location: include/linux/swap.h:397
Inline: True
Inline callers:
  - mm/page_alloc.c:get_page_from_freelist
```
```
In mm/khugepaged.c (ffffffff81302205)
Location: include/linux/swap.h:397
Inline: True
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
In mm/page_alloc.c (ffffffff81306c31)
Location: include/linux/swap.h:403
Inline: True
Inline callers:
  - mm/page_alloc.c:get_page_from_freelist
```
```
In mm/khugepaged.c (ffffffff8134bdb5)
Location: include/linux/swap.h:403
Inline: True
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
In mm/page_alloc.c (ffffffff8136edf0)
Location: include/linux/swap.h:435
Inline: True
Inline callers:
  - mm/page_alloc.c:get_page_from_freelist
```
```
In mm/khugepaged.c (ffffffff813c3365)
Location: include/linux/swap.h:435
Inline: True
Inline callers:
  - mm/khugepaged.c:khugepaged_scan_abort
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
In mm/page_alloc.c (ffffffff813eb343)
Location: include/linux/swap.h:439
Inline: True
Inline callers:
  - mm/page_alloc.c:get_page_from_freelist
```
```
In mm/khugepaged.c (ffffffff81445aa5)
Location: include/linux/swap.h:439
Inline: True
Inline callers:
  - mm/khugepaged.c:hpage_collapse_scan_abort
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
In mm/page_alloc.c (ffffffff814202c7)
Location: include/linux/swap.h:435
Inline: True
Inline callers:
  - mm/page_alloc.c:get_page_from_freelist
```
```
In mm/khugepaged.c (ffffffff8147b105)
Location: include/linux/swap.h:435
Inline: True
Inline callers:
  - mm/khugepaged.c:hpage_collapse_scan_abort
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
In mm/page_alloc.c (ffffffff8144cffc)
Location: include/linux/swap.h:427
Inline: True
Inline callers:
  - mm/page_alloc.c:get_page_from_freelist
```
```
In mm/khugepaged.c (ffffffff814aa5f5)
Location: include/linux/swap.h:427
Inline: True
Inline callers:
  - mm/khugepaged.c:hpage_collapse_scan_abort
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
