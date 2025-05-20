# Function: <code>xa_is_advanced</code>

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
In lib/xarray.c (ffffffff81a18fea)
Location: include/linux/xarray.h:1106
Inline: True
Inline callers:
  - lib/xarray.c:__xa_alloc
  - lib/xarray.c:__xa_insert
  - lib/xarray.c:__xa_cmpxchg
  - lib/xarray.c:__xa_store
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
In lib/xarray.c (ffffffff81a88c0a)
Location: include/linux/xarray.h:1235
Inline: True
Inline callers:
  - lib/xarray.c:__xa_alloc
  - lib/xarray.c:__xa_insert
  - lib/xarray.c:__xa_cmpxchg
  - lib/xarray.c:__xa_store
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
In lib/xarray.c (ffffffff81abfeaa)
Location: include/linux/xarray.h:1235
Inline: True
Inline callers:
  - lib/xarray.c:__xa_alloc
  - lib/xarray.c:__xa_insert
  - lib/xarray.c:__xa_cmpxchg
  - lib/xarray.c:__xa_store
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
In lib/xarray.c (ffffffff815fc4aa)
Location: include/linux/xarray.h:1270
Inline: True
Inline callers:
  - lib/xarray.c:__xa_alloc
  - lib/xarray.c:__xa_insert
  - lib/xarray.c:__xa_cmpxchg
  - lib/xarray.c:__xa_store
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
In lib/xarray.c (ffffffff816210ca)
Location: include/linux/xarray.h:1270
Inline: True
Inline callers:
  - lib/xarray.c:__xa_alloc
  - lib/xarray.c:__xa_insert
  - lib/xarray.c:__xa_cmpxchg
  - lib/xarray.c:__xa_store
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
In lib/xarray.c (ffffffff81604aad)
Location: include/linux/xarray.h:1272
Inline: True
Inline callers:
  - lib/xarray.c:__xa_alloc
  - lib/xarray.c:__xa_insert
  - lib/xarray.c:__xa_cmpxchg
  - lib/xarray.c:__xa_store
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
In lib/xarray.c (ffffffff8167339d)
Location: include/linux/xarray.h:1272
Inline: True
Inline callers:
  - lib/xarray.c:__xa_alloc
  - lib/xarray.c:__xa_insert
  - lib/xarray.c:__xa_cmpxchg
  - lib/xarray.c:__xa_store
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
In lib/xarray.c (ffffffff8178d9d6)
Location: include/linux/xarray.h:1273
Inline: True
Inline callers:
  - lib/xarray.c:__xa_alloc
  - lib/xarray.c:__xa_insert
  - lib/xarray.c:__xa_cmpxchg
  - lib/xarray.c:__xa_store
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
In lib/maple_tree.c (ffffffff8203690f)
Location: include/linux/xarray.h:1288
Inline: True
Inline callers:
  - lib/maple_tree.c:mtree_insert_range
  - lib/maple_tree.c:mtree_store_range
```
```
In lib/xarray.c (ffffffff8204b076)
Location: include/linux/xarray.h:1288
Inline: True
Inline callers:
  - lib/xarray.c:__xa_alloc
  - lib/xarray.c:__xa_insert
  - lib/xarray.c:__xa_cmpxchg
  - lib/xarray.c:__xa_store
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
In lib/maple_tree.c (ffffffff820b588f)
Location: include/linux/xarray.h:1288
Inline: True
Inline callers:
  - lib/maple_tree.c:mtree_insert_range
  - lib/maple_tree.c:mtree_store_range
```
```
In lib/xarray.c (ffffffff820c9976)
Location: include/linux/xarray.h:1288
Inline: True
Inline callers:
  - lib/xarray.c:__xa_alloc
  - lib/xarray.c:__xa_insert
  - lib/xarray.c:__xa_cmpxchg
  - lib/xarray.c:__xa_store
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
In lib/maple_tree.c (ffffffff8218fa16)
Location: include/linux/xarray.h:1306
Inline: True
Inline callers:
  - lib/maple_tree.c:mtree_insert_range
  - lib/maple_tree.c:mtree_store_range
```
```
In lib/xarray.c (ffffffff821a42f6)
Location: include/linux/xarray.h:1306
Inline: True
Inline callers:
  - lib/xarray.c:__xa_alloc
  - lib/xarray.c:__xa_insert
  - lib/xarray.c:__xa_cmpxchg
  - lib/xarray.c:__xa_store
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
In lib/xarray.c (ffff800010d9b834)
Location: include/linux/xarray.h:1235
Inline: True
Inline callers:
  - lib/xarray.c:__xa_alloc
  - lib/xarray.c:__xa_insert
  - lib/xarray.c:__xa_cmpxchg
  - lib/xarray.c:__xa_store
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
In lib/xarray.c (c0e97f7c)
Location: include/linux/xarray.h:1235
Inline: True
Inline callers:
  - lib/xarray.c:__xa_alloc
  - lib/xarray.c:__xa_insert
  - lib/xarray.c:__xa_cmpxchg
  - lib/xarray.c:__xa_store
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
In lib/xarray.c (c000000000ee1c04)
Location: include/linux/xarray.h:1235
Inline: True
Inline callers:
  - lib/xarray.c:__xa_alloc
  - lib/xarray.c:__xa_insert
  - lib/xarray.c:__xa_cmpxchg
  - lib/xarray.c:__xa_store
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
In lib/xarray.c (ffffffe0008c3a6a)
Location: include/linux/xarray.h:1235
Inline: True
Inline callers:
  - lib/xarray.c:__xa_alloc
  - lib/xarray.c:__xa_insert
  - lib/xarray.c:__xa_cmpxchg
  - lib/xarray.c:__xa_store
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
In lib/xarray.c (ffffffff81a5ecfa)
Location: include/linux/xarray.h:1235
Inline: True
Inline callers:
  - lib/xarray.c:__xa_alloc
  - lib/xarray.c:__xa_insert
  - lib/xarray.c:__xa_cmpxchg
  - lib/xarray.c:__xa_store
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
In lib/xarray.c (ffffffff81a1bdca)
Location: include/linux/xarray.h:1235
Inline: True
Inline callers:
  - lib/xarray.c:__xa_alloc
  - lib/xarray.c:__xa_insert
  - lib/xarray.c:__xa_cmpxchg
  - lib/xarray.c:__xa_store
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
In lib/xarray.c (ffffffff81acb0ea)
Location: include/linux/xarray.h:1235
Inline: True
Inline callers:
  - lib/xarray.c:__xa_alloc
  - lib/xarray.c:__xa_insert
  - lib/xarray.c:__xa_cmpxchg
  - lib/xarray.c:__xa_store
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
In lib/xarray.c (ffffffff81ad774a)
Location: include/linux/xarray.h:1235
Inline: True
Inline callers:
  - lib/xarray.c:__xa_alloc
  - lib/xarray.c:__xa_insert
  - lib/xarray.c:__xa_cmpxchg
  - lib/xarray.c:__xa_store
```
</details>
</li>
</ul>

## Differences
