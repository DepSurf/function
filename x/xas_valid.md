# Function: <code>xas_valid</code>

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
In lib/xarray.c (ffffffff81a18474)
Location: include/linux/xarray.h:1257
Inline: True
Inline callers:
  - lib/xarray.c:xas_create_range
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
In lib/xarray.c (ffffffff81a88094)
Location: include/linux/xarray.h:1386
Inline: True
Inline callers:
  - lib/xarray.c:xas_create_range
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
In lib/xarray.c (ffffffff81abf334)
Location: include/linux/xarray.h:1386
Inline: True
Inline callers:
  - lib/xarray.c:xas_create_range
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
In lib/xarray.c (ffffffff815fb4c4)
Location: include/linux/xarray.h:1421
Inline: True
Inline callers:
  - lib/xarray.c:xas_create_range
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
In lib/xarray.c (ffffffff81620035)
Location: include/linux/xarray.h:1423
Inline: True
Inline callers:
  - lib/xarray.c:xas_create_range
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
In lib/xarray.c (ffffffff81603795)
Location: include/linux/xarray.h:1425
Inline: True
Inline callers:
  - lib/xarray.c:xas_create_range
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
In lib/xarray.c (ffffffff81671d12)
Location: include/linux/xarray.h:1425
Inline: True
Inline callers:
  - lib/xarray.c:xas_create_range
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
Location: include/linux/xarray.h:1428
Inline: True
Inline callers:
  - mm/filemap.c:filemap_get_read_batch
```
```
In lib/xarray.c (ffffffff8178be0f)
Location: include/linux/xarray.h:1428
Inline: True
Inline callers:
  - lib/xarray.c:xas_create_range
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
Location: include/linux/xarray.h:1443
Inline: True
Inline callers:
  - mm/filemap.c:filemap_get_read_batch
```
```
In lib/xarray.c (ffffffff8204936f)
Location: include/linux/xarray.h:1443
Inline: True
Inline callers:
  - lib/xarray.c:xas_create_range
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
Location: include/linux/xarray.h:1443
Inline: True
Inline callers:
  - mm/filemap.c:filemap_get_read_batch
```
```
In lib/xarray.c (ffffffff820c7c2f)
Location: include/linux/xarray.h:1443
Inline: True
Inline callers:
  - lib/xarray.c:xas_create_range
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
Location: include/linux/xarray.h:1461
Inline: True
Inline callers:
  - mm/filemap.c:filemap_get_read_batch
```
```
In lib/xarray.c (ffffffff821a25af)
Location: include/linux/xarray.h:1461
Inline: True
Inline callers:
  - lib/xarray.c:xas_create_range
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
In lib/xarray.c (ffff800010d9a560)
Location: include/linux/xarray.h:1386
Inline: True
Inline callers:
  - lib/xarray.c:xas_create_range
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
In lib/xarray.c (c0e972c4)
Location: include/linux/xarray.h:1386
Inline: True
Inline callers:
  - lib/xarray.c:xas_create_range
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
In lib/xarray.c (c000000000ee0b8c)
Location: include/linux/xarray.h:1386
Inline: True
Inline callers:
  - lib/xarray.c:xas_create_range
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
In lib/xarray.c (ffffffe0008c1de6)
Location: include/linux/xarray.h:1386
Inline: True
Inline callers:
  - lib/xarray.c:xas_create_range
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
In lib/xarray.c (ffffffff81a5e184)
Location: include/linux/xarray.h:1386
Inline: True
Inline callers:
  - lib/xarray.c:xas_create_range
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
In lib/xarray.c (ffffffff81a1b254)
Location: include/linux/xarray.h:1386
Inline: True
Inline callers:
  - lib/xarray.c:xas_create_range
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
In lib/xarray.c (ffffffff81aca574)
Location: include/linux/xarray.h:1386
Inline: True
Inline callers:
  - lib/xarray.c:xas_create_range
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
In lib/xarray.c (ffffffff81ad6b44)
Location: include/linux/xarray.h:1386
Inline: True
Inline callers:
  - lib/xarray.c:xas_create_range
```
</details>
</li>
</ul>

## Differences
