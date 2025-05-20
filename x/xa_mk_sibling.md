# Function: <code>xa_mk_sibling</code>

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
In lib/xarray.c (ffffffff81a1860c)
Location: include/linux/xarray.h:1052
Inline: True
Inline callers:
  - lib/xarray.c:xas_store
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
In lib/xarray.c (ffffffff81a8823a)
Location: include/linux/xarray.h:1193
Inline: True
Inline callers:
  - lib/xarray.c:xas_store
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
In lib/xarray.c (ffffffff81abf4da)
Location: include/linux/xarray.h:1193
Inline: True
Inline callers:
  - lib/xarray.c:xas_store
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
In lib/xarray.c (ffffffff815fb9bf)
Location: include/linux/xarray.h:1228
Inline: True
Inline callers:
  - lib/xarray.c:xas_store
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
In mm/filemap.c (0)
Location: include/linux/xarray.h:1228
Inline: True
```
```
In lib/xarray.c (ffffffff8161fadd)
Location: include/linux/xarray.h:1228
Inline: True
Inline callers:
  - lib/xarray.c:xas_split
  - lib/xarray.c:xas_store
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
In mm/filemap.c (0)
Location: include/linux/xarray.h:1230
Inline: True
```
```
In lib/iov_iter.c (0)
Location: include/linux/xarray.h:1230
Inline: True
```
```
In lib/xarray.c (ffffffff8160325d)
Location: include/linux/xarray.h:1230
Inline: True
Inline callers:
  - lib/xarray.c:xas_split
  - lib/xarray.c:xas_split_alloc
  - lib/xarray.c:xas_store
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
In mm/filemap.c (0)
Location: include/linux/xarray.h:1230
Inline: True
```
```
In lib/iov_iter.c (0)
Location: include/linux/xarray.h:1230
Inline: True
```
```
In lib/xarray.c (ffffffff81671749)
Location: include/linux/xarray.h:1230
Inline: True
Inline callers:
  - lib/xarray.c:xas_split
  - lib/xarray.c:xas_split_alloc
  - lib/xarray.c:xas_store
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
In mm/filemap.c (0)
Location: include/linux/xarray.h:1231
Inline: True
```
```
In lib/iov_iter.c (0)
Location: include/linux/xarray.h:1231
Inline: True
```
```
In lib/xarray.c (ffffffff8178c1fd)
Location: include/linux/xarray.h:1231
Inline: True
Inline callers:
  - lib/xarray.c:xas_split
  - lib/xarray.c:xas_split_alloc
  - lib/xarray.c:xas_store
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
In mm/filemap.c (0)
Location: include/linux/xarray.h:1246
Inline: True
```
```
In lib/iov_iter.c (0)
Location: include/linux/xarray.h:1246
Inline: True
```
```
In lib/xarray.c (ffffffff820487a1)
Location: include/linux/xarray.h:1246
Inline: True
Inline callers:
  - lib/xarray.c:xas_split
  - lib/xarray.c:xas_split_alloc
  - lib/xarray.c:xas_store
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
In mm/filemap.c (0)
Location: include/linux/xarray.h:1246
Inline: True
```
```
In lib/iov_iter.c (0)
Location: include/linux/xarray.h:1246
Inline: True
```
```
In lib/xarray.c (ffffffff820c6fce)
Location: include/linux/xarray.h:1246
Inline: True
Inline callers:
  - lib/xarray.c:xas_split
  - lib/xarray.c:xas_split_alloc
  - lib/xarray.c:xas_store
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
In mm/filemap.c (0)
Location: include/linux/xarray.h:1264
Inline: True
```
```
In lib/iov_iter.c (0)
Location: include/linux/xarray.h:1264
Inline: True
```
```
In lib/xarray.c (ffffffff821a194e)
Location: include/linux/xarray.h:1264
Inline: True
Inline callers:
  - lib/xarray.c:xas_split
  - lib/xarray.c:xas_split_alloc
  - lib/xarray.c:xas_store
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
In lib/xarray.c (ffff800010d9a768)
Location: include/linux/xarray.h:1193
Inline: True
Inline callers:
  - lib/xarray.c:xas_store
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
In lib/xarray.c (c0e97464)
Location: include/linux/xarray.h:1193
Inline: True
Inline callers:
  - lib/xarray.c:xas_store
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
In lib/xarray.c (c000000000ee0e38)
Location: include/linux/xarray.h:1193
Inline: True
Inline callers:
  - lib/xarray.c:xas_store
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
In lib/xarray.c (ffffffe0008c2d34)
Location: include/linux/xarray.h:1193
Inline: True
Inline callers:
  - lib/xarray.c:xas_store
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
In lib/xarray.c (ffffffff81a5e32a)
Location: include/linux/xarray.h:1193
Inline: True
Inline callers:
  - lib/xarray.c:xas_store
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
In lib/xarray.c (ffffffff81a1b3fa)
Location: include/linux/xarray.h:1193
Inline: True
Inline callers:
  - lib/xarray.c:xas_store
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
In lib/xarray.c (ffffffff81aca71a)
Location: include/linux/xarray.h:1193
Inline: True
Inline callers:
  - lib/xarray.c:xas_store
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
In lib/xarray.c (ffffffff81ad6cea)
Location: include/linux/xarray.h:1193
Inline: True
Inline callers:
  - lib/xarray.c:xas_store
```
</details>
</li>
</ul>

## Differences
