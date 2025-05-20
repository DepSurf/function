# Function: <code>page_has_type</code>

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
In fs/proc/page.c (ffffffff813414ac)
Location: include/linux/page-flags.h:681
Inline: True
Inline callers:
  - fs/proc/page.c:kpagecount_read
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
In mm/memory.c (ffffffff81255f61)
Location: include/linux/page-flags.h:715
Inline: True
Inline callers:
  - mm/memory.c:vm_insert_page
```
```
In fs/proc/page.c (ffffffff81369939)
Location: include/linux/page-flags.h:715
Inline: True
Inline callers:
  - fs/proc/page.c:kpagecount_read
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
In mm/memory.c (ffffffff812644f1)
Location: include/linux/page-flags.h:731
Inline: True
Inline callers:
  - mm/memory.c:vm_insert_page
```
```
In fs/proc/page.c (ffffffff81381ba7)
Location: include/linux/page-flags.h:731
Inline: True
Inline callers:
  - fs/proc/page.c:kpagecount_read
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
In mm/memory.c (ffffffff81292f0c)
Location: include/linux/page-flags.h:747
Inline: True
```
```
In fs/proc/page.c (ffffffff813cc1bf)
Location: include/linux/page-flags.h:747
Inline: True
Inline callers:
  - fs/proc/page.c:kpagecount_read
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
In mm/memory.c (ffffffff8129d7aa)
Location: include/linux/page-flags.h:723
Inline: True
```
```
In fs/proc/page.c (ffffffff813dddf8)
Location: include/linux/page-flags.h:723
Inline: True
Inline callers:
  - fs/proc/page.c:kpagecount_read
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
In mm/memory.c (ffffffff812a2e5b)
Location: include/linux/page-flags.h:717
Inline: True
Inline callers:
  - mm/memory.c:vm_insert_page
```
```
In fs/proc/page.c (ffffffff813e4d3f)
Location: include/linux/page-flags.h:717
Inline: True
Inline callers:
  - fs/proc/page.c:kpagecount_read
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
In mm/memory.c (ffffffff812dd425)
Location: include/linux/page-flags.h:726
Inline: True
Inline callers:
  - mm/memory.c:validate_page_before_insert
```
```
In fs/proc/page.c (ffffffff8143690f)
Location: include/linux/page-flags.h:726
Inline: True
Inline callers:
  - fs/proc/page.c:kpagecount_read
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
In mm/memory.c (ffffffff81345236)
Location: include/linux/page-flags.h:949
Inline: True
Inline callers:
  - mm/memory.c:vm_insert_page
  - mm/memory.c:insert_pages
```
```
In fs/proc/page.c (ffffffff814b1050)
Location: include/linux/page-flags.h:949
Inline: True
Inline callers:
  - fs/proc/page.c:kpagecount_read
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
In mm/memory.c (ffffffff813bd460)
Location: include/linux/page-flags.h:928
Inline: True
Inline callers:
  - mm/memory.c:vm_insert_page
  - mm/memory.c:insert_pages
```
```
In fs/proc/page.c (ffffffff815479d0)
Location: include/linux/page-flags.h:928
Inline: True
Inline callers:
  - fs/proc/page.c:kpagecount_read
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
In mm/memory.c (ffffffff813f2174)
Location: include/linux/page-flags.h:917
Inline: True
Inline callers:
  - mm/memory.c:vm_insert_page
  - mm/memory.c:vm_insert_pages
```
```
In fs/proc/page.c (ffffffff8157f5f0)
Location: include/linux/page-flags.h:917
Inline: True
Inline callers:
  - fs/proc/page.c:kpagecount_read
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
In mm/memory.c (ffffffff8141cdec)
Location: include/linux/page-flags.h:949
Inline: True
Inline callers:
  - mm/memory.c:vm_insert_page
  - mm/memory.c:vm_insert_pages
```
```
In fs/proc/page.c (ffffffff815b8030)
Location: include/linux/page-flags.h:949
Inline: True
Inline callers:
  - fs/proc/page.c:kpagecount_read
```
</details>
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
In mm/memory.c (ffff8000102fb1f0)
Location: include/linux/page-flags.h:731
Inline: True
Inline callers:
  - mm/memory.c:vm_insert_page
```
```
In fs/proc/page.c (ffff80001044ff10)
Location: include/linux/page-flags.h:731
Inline: True
Inline callers:
  - fs/proc/page.c:kpagecount_read
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
In mm/memory.c (c0519a3c)
Location: include/linux/page-flags.h:731
Inline: True
Inline callers:
  - mm/memory.c:insert_page
```
```
In fs/proc/page.c (c0613154)
Location: include/linux/page-flags.h:731
Inline: True
Inline callers:
  - fs/proc/page.c:kpagecount_read
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
In mm/memory.c (c0000000003c5f48)
Location: include/linux/page-flags.h:731
Inline: True
Inline callers:
  - mm/memory.c:vm_insert_page
```
```
In fs/proc/page.c (c000000000567bd8)
Location: include/linux/page-flags.h:731
Inline: True
Inline callers:
  - fs/proc/page.c:kpagecount_read
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
In mm/memory.c (ffffffe00020a9a2)
Location: include/linux/page-flags.h:731
Inline: True
Inline callers:
  - mm/memory.c:vm_insert_page
```
```
In fs/proc/page.c (ffffffe0002e2f70)
Location: include/linux/page-flags.h:731
Inline: True
Inline callers:
  - fs/proc/page.c:kpagecount_read
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
In mm/memory.c (ffffffff8125cb41)
Location: include/linux/page-flags.h:731
Inline: True
Inline callers:
  - mm/memory.c:vm_insert_page
```
```
In fs/proc/page.c (ffffffff8137a187)
Location: include/linux/page-flags.h:731
Inline: True
Inline callers:
  - fs/proc/page.c:kpagecount_read
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
In mm/memory.c (ffffffff8124f020)
Location: include/linux/page-flags.h:731
Inline: True
Inline callers:
  - mm/memory.c:vm_insert_page
```
```
In fs/proc/page.c (ffffffff8136ac57)
Location: include/linux/page-flags.h:731
Inline: True
Inline callers:
  - fs/proc/page.c:kpagecount_read
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
In mm/memory.c (ffffffff8125a8e1)
Location: include/linux/page-flags.h:731
Inline: True
Inline callers:
  - mm/memory.c:vm_insert_page
```
```
In fs/proc/page.c (ffffffff81377c57)
Location: include/linux/page-flags.h:731
Inline: True
Inline callers:
  - fs/proc/page.c:kpagecount_read
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
In mm/memory.c (ffffffff8126a2c1)
Location: include/linux/page-flags.h:731
Inline: True
Inline callers:
  - mm/memory.c:vm_insert_page
```
```
In fs/proc/page.c (ffffffff8138b6f8)
Location: include/linux/page-flags.h:731
Inline: True
Inline callers:
  - fs/proc/page.c:kpagecount_read
```
</details>
</li>
</ul>

## Differences
