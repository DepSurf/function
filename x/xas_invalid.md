# Function: <code>xas_invalid</code>

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
In lib/xarray.c (ffffffff81a16bc4)
Location: include/linux/xarray.h:1246
Inline: True
Inline callers:
  - lib/xarray.c:xas_pause
  - lib/xarray.c:xas_store
  - lib/xarray.c:xas_create_range
  - lib/xarray.c:xas_alloc
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
In lib/xarray.c (ffffffff81a86754)
Location: include/linux/xarray.h:1375
Inline: True
Inline callers:
  - lib/xarray.c:xas_pause
  - lib/xarray.c:xas_store
  - lib/xarray.c:xas_create_range
  - lib/xarray.c:xas_alloc
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
In lib/xarray.c (ffffffff81abe629)
Location: include/linux/xarray.h:1375
Inline: True
Inline callers:
  - lib/xarray.c:xa_find_after
  - lib/xarray.c:xas_pause
  - lib/xarray.c:xas_store
  - lib/xarray.c:xas_create_range
  - lib/xarray.c:xas_alloc
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
In lib/xarray.c (ffffffff815fae65)
Location: include/linux/xarray.h:1410
Inline: True
Inline callers:
  - lib/xarray.c:xa_find_after
  - lib/xarray.c:xa_get_mark
  - lib/xarray.c:xas_pause
  - lib/xarray.c:xas_store
  - lib/xarray.c:xas_create_range
  - lib/xarray.c:xas_alloc
  - lib/xarray.c:xas_start
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
In lib/xarray.c (ffffffff8161f67f)
Location: include/linux/xarray.h:1412
Inline: True
Inline callers:
  - lib/xarray.c:xa_find_after
  - lib/xarray.c:xa_get_mark
  - lib/xarray.c:xas_pause
  - lib/xarray.c:xas_store
  - lib/xarray.c:xas_create_range
  - lib/xarray.c:xas_alloc
  - lib/xarray.c:xas_start
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
In lib/xarray.c (ffffffff81602caf)
Location: include/linux/xarray.h:1414
Inline: True
Inline callers:
  - lib/xarray.c:xa_find_after
  - lib/xarray.c:xa_get_mark
  - lib/xarray.c:xas_pause
  - lib/xarray.c:xas_store
  - lib/xarray.c:xas_create_range
  - lib/xarray.c:xas_alloc
  - lib/xarray.c:xas_start
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
In lib/xarray.c (ffffffff81671149)
Location: include/linux/xarray.h:1414
Inline: True
Inline callers:
  - lib/xarray.c:xa_find_after
  - lib/xarray.c:xa_get_mark
  - lib/xarray.c:xas_pause
  - lib/xarray.c:xas_store
  - lib/xarray.c:xas_create_range
  - lib/xarray.c:xas_alloc
  - lib/xarray.c:xas_start
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
In mm/filemap.c (ffffffff812f2bb8)
Location: include/linux/xarray.h:1417
Inline: True
Inline callers:
  - mm/filemap.c:filemap_get_read_batch
```
```
In lib/xarray.c (ffffffff8178aba2)
Location: include/linux/xarray.h:1417
Inline: True
Inline callers:
  - lib/xarray.c:xa_find_after
  - lib/xarray.c:xa_get_mark
  - lib/xarray.c:xas_pause
  - lib/xarray.c:xas_store
  - lib/xarray.c:xas_create_range
  - lib/xarray.c:xas_alloc
  - lib/xarray.c:xas_start
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
In mm/filemap.c (ffffffff8135cf83)
Location: include/linux/xarray.h:1432
Inline: True
Inline callers:
  - mm/filemap.c:filemap_get_read_batch
```
```
In lib/xarray.c (ffffffff82048102)
Location: include/linux/xarray.h:1432
Inline: True
Inline callers:
  - lib/xarray.c:xa_find_after
  - lib/xarray.c:xa_get_mark
  - lib/xarray.c:xas_pause
  - lib/xarray.c:xas_store
  - lib/xarray.c:xas_create_range
  - lib/xarray.c:xas_alloc
  - lib/xarray.c:xas_start
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
In mm/filemap.c (ffffffff8138efbf)
Location: include/linux/xarray.h:1432
Inline: True
Inline callers:
  - mm/filemap.c:filemap_get_read_batch
```
```
In lib/xarray.c (ffffffff820c68a2)
Location: include/linux/xarray.h:1432
Inline: True
Inline callers:
  - lib/xarray.c:xa_find_after
  - lib/xarray.c:xa_get_mark
  - lib/xarray.c:xas_pause
  - lib/xarray.c:xas_store
  - lib/xarray.c:xas_create_range
  - lib/xarray.c:xas_alloc
  - lib/xarray.c:xas_start
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
In mm/filemap.c (ffffffff813b866c)
Location: include/linux/xarray.h:1450
Inline: True
Inline callers:
  - mm/filemap.c:filemap_get_read_batch
```
```
In lib/xarray.c (ffffffff821a1222)
Location: include/linux/xarray.h:1450
Inline: True
Inline callers:
  - lib/xarray.c:xa_find_after
  - lib/xarray.c:xa_get_mark
  - lib/xarray.c:xas_pause
  - lib/xarray.c:xas_store
  - lib/xarray.c:xas_create_range
  - lib/xarray.c:xas_alloc
  - lib/xarray.c:xas_start
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
In lib/xarray.c (ffff800010d998cc)
Location: include/linux/xarray.h:1375
Inline: True
Inline callers:
  - lib/xarray.c:xa_find_after
  - lib/xarray.c:xas_pause
  - lib/xarray.c:xas_store
  - lib/xarray.c:xas_create_range
  - lib/xarray.c:xas_alloc
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
In lib/xarray.c (c0e96678)
Location: include/linux/xarray.h:1375
Inline: True
Inline callers:
  - lib/xarray.c:xa_find_after
  - lib/xarray.c:xas_pause
  - lib/xarray.c:xas_store
  - lib/xarray.c:xas_create_range
  - lib/xarray.c:xas_alloc
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
In lib/xarray.c (c000000000edf758)
Location: include/linux/xarray.h:1375
Inline: True
Inline callers:
  - lib/xarray.c:xa_find_after
  - lib/xarray.c:xas_pause
  - lib/xarray.c:xas_store
  - lib/xarray.c:xas_create_range
  - lib/xarray.c:xas_alloc
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
In lib/xarray.c (ffffffe0008c27b0)
Location: include/linux/xarray.h:1375
Inline: True
Inline callers:
  - lib/xarray.c:xa_find_after
  - lib/xarray.c:xas_pause
  - lib/xarray.c:xas_store
  - lib/xarray.c:xas_create_range
  - lib/xarray.c:xas_alloc
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
In lib/xarray.c (ffffffff81a5d479)
Location: include/linux/xarray.h:1375
Inline: True
Inline callers:
  - lib/xarray.c:xa_find_after
  - lib/xarray.c:xas_pause
  - lib/xarray.c:xas_store
  - lib/xarray.c:xas_create_range
  - lib/xarray.c:xas_alloc
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
In lib/xarray.c (ffffffff81a1a549)
Location: include/linux/xarray.h:1375
Inline: True
Inline callers:
  - lib/xarray.c:xa_find_after
  - lib/xarray.c:xas_pause
  - lib/xarray.c:xas_store
  - lib/xarray.c:xas_create_range
  - lib/xarray.c:xas_alloc
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
In lib/xarray.c (ffffffff81ac9869)
Location: include/linux/xarray.h:1375
Inline: True
Inline callers:
  - lib/xarray.c:xa_find_after
  - lib/xarray.c:xas_pause
  - lib/xarray.c:xas_store
  - lib/xarray.c:xas_create_range
  - lib/xarray.c:xas_alloc
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
In lib/xarray.c (ffffffff81ad5d97)
Location: include/linux/xarray.h:1375
Inline: True
Inline callers:
  - lib/xarray.c:xa_find_after
  - lib/xarray.c:xas_pause
  - lib/xarray.c:xas_store
  - lib/xarray.c:xas_create_range
  - lib/xarray.c:xas_alloc
```
</details>
</li>
</ul>

## Differences
