# Function: <code>xa_parent_locked</code>

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
<summary>In <code>5.0</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/workingset.c (0)
Location: include/linux/xarray.h:1026
Inline: True
```
```
In lib/xarray.c (0)
Location: include/linux/xarray.h:1026
Inline: True
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
In mm/workingset.c (0)
Location: include/linux/xarray.h:1167
Inline: True
```
```
In lib/xarray.c (0)
Location: include/linux/xarray.h:1167
Inline: True
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
In mm/workingset.c (0)
Location: include/linux/xarray.h:1167
Inline: True
```
```
In lib/xarray.c (0)
Location: include/linux/xarray.h:1167
Inline: True
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
In mm/workingset.c (ffffffff81286931)
Location: include/linux/xarray.h:1202
Inline: True
Inline callers:
  - mm/workingset.c:shadow_lru_isolate
```
```
In lib/xarray.c (ffffffff815f9c82)
Location: include/linux/xarray.h:1202
Inline: True
Inline callers:
  - lib/xarray.c:xas_find_conflict
  - lib/xarray.c:xas_store
  - lib/xarray.c:xas_create_range
  - lib/xarray.c:xas_free_nodes
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
In lib/xarray.c (ffffffff81620c60)
Location: include/linux/xarray.h:1202
Inline: True
Inline callers:
  - lib/xarray.c:xa_delete_node
  - lib/xarray.c:xas_find_conflict
  - lib/xarray.c:xas_store
  - lib/xarray.c:xas_create_range
  - lib/xarray.c:xas_free_nodes
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
In lib/xarray.c (ffffffff81604440)
Location: include/linux/xarray.h:1204
Inline: True
Inline callers:
  - lib/xarray.c:xa_delete_node
  - lib/xarray.c:xas_find_conflict
  - lib/xarray.c:xas_store
  - lib/xarray.c:xas_create_range
  - lib/xarray.c:xas_free_nodes
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
In lib/xarray.c (ffffffff81672d35)
Location: include/linux/xarray.h:1204
Inline: True
Inline callers:
  - lib/xarray.c:xa_delete_node
  - lib/xarray.c:xas_find_conflict
  - lib/xarray.c:xas_store
  - lib/xarray.c:xas_create_range
  - lib/xarray.c:xas_free_nodes
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
In lib/xarray.c (ffffffff8178d245)
Location: include/linux/xarray.h:1205
Inline: True
Inline callers:
  - lib/xarray.c:xa_delete_node
  - lib/xarray.c:xas_find_conflict
  - lib/xarray.c:xas_store
  - lib/xarray.c:xas_create_range
  - lib/xarray.c:xas_free_nodes
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
In lib/xarray.c (ffffffff8204a885)
Location: include/linux/xarray.h:1220
Inline: True
Inline callers:
  - lib/xarray.c:xa_delete_node
  - lib/xarray.c:xas_find_conflict
  - lib/xarray.c:xas_store
  - lib/xarray.c:xas_create_range
  - lib/xarray.c:xas_free_nodes
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
In lib/xarray.c (ffffffff820c9185)
Location: include/linux/xarray.h:1220
Inline: True
Inline callers:
  - lib/xarray.c:xa_delete_node
  - lib/xarray.c:xas_find_conflict
  - lib/xarray.c:xas_store
  - lib/xarray.c:xas_create_range
  - lib/xarray.c:xas_free_nodes
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In lib/xarray.c (ffffffff821a3b05)
Location: include/linux/xarray.h:1238
Inline: True
Inline callers:
  - lib/xarray.c:xa_delete_node
  - lib/xarray.c:xas_find_conflict
  - lib/xarray.c:xas_store
  - lib/xarray.c:xas_create_range
  - lib/xarray.c:xas_free_nodes
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
In mm/workingset.c (0)
Location: include/linux/xarray.h:1167
Inline: True
```
```
In lib/xarray.c (0)
Location: include/linux/xarray.h:1167
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
In mm/workingset.c (c05134cc)
Location: include/linux/xarray.h:1167
Inline: True
Inline callers:
  - mm/workingset.c:shadow_lru_isolate
```
```
In lib/xarray.c (c0e968e4)
Location: include/linux/xarray.h:1167
Inline: True
Inline callers:
  - lib/xarray.c:xas_find_conflict
  - lib/xarray.c:xas_store
  - lib/xarray.c:xas_create_range
  - lib/xarray.c:xas_free_nodes
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
In mm/workingset.c (0)
Location: include/linux/xarray.h:1167
Inline: True
```
```
In lib/xarray.c (0)
Location: include/linux/xarray.h:1167
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
In mm/workingset.c (0)
Location: include/linux/xarray.h:1167
Inline: True
```
```
In lib/xarray.c (0)
Location: include/linux/xarray.h:1167
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
In mm/workingset.c (0)
Location: include/linux/xarray.h:1167
Inline: True
```
```
In lib/xarray.c (0)
Location: include/linux/xarray.h:1167
Inline: True
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
In mm/workingset.c (0)
Location: include/linux/xarray.h:1167
Inline: True
```
```
In lib/xarray.c (0)
Location: include/linux/xarray.h:1167
Inline: True
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
In mm/workingset.c (0)
Location: include/linux/xarray.h:1167
Inline: True
```
```
In lib/xarray.c (0)
Location: include/linux/xarray.h:1167
Inline: True
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
In mm/workingset.c (0)
Location: include/linux/xarray.h:1167
Inline: True
```
```
In lib/xarray.c (0)
Location: include/linux/xarray.h:1167
Inline: True
```
</details>
</li>
</ul>

## Differences
