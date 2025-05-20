# Function: <code>pcpu_off_to_block_index</code>

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
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/percpu.c (ffffffff811fa1ac)
Location: mm/percpu.c:297
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_free_area
  - mm/percpu.c:pcpu_free_area
  - mm/percpu.c:pcpu_block_update_hint_alloc
  - mm/percpu.c:pcpu_block_update_hint_alloc
  - mm/percpu.c:pcpu_next_md_free_region
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/percpu.c (ffffffff8121a345)
Location: mm/percpu.c:298
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_free_area
  - mm/percpu.c:pcpu_free_area
  - mm/percpu.c:pcpu_block_update_hint_alloc
  - mm/percpu.c:pcpu_block_update_hint_alloc
  - mm/percpu.c:pcpu_next_md_free_region
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/percpu.c (ffffffff8122d257)
Location: mm/percpu.c:306
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_free_area
  - mm/percpu.c:pcpu_free_area
  - mm/percpu.c:pcpu_block_update_hint_alloc
  - mm/percpu.c:pcpu_block_update_hint_alloc
  - mm/percpu.c:pcpu_next_md_free_region
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
In mm/percpu.c (ffffffff8123cf3c)
Location: mm/percpu.c:310
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_free_area
  - mm/percpu.c:pcpu_free_area
  - mm/percpu.c:pcpu_alloc_area
  - mm/percpu.c:pcpu_block_update_hint_alloc
  - mm/percpu.c:pcpu_block_update_hint_alloc
  - mm/percpu.c:pcpu_next_md_free_region
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
In mm/percpu.c (ffffffff8124b38c)
Location: mm/percpu.c:310
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_free_area
  - mm/percpu.c:pcpu_free_area
  - mm/percpu.c:pcpu_alloc_area
  - mm/percpu.c:pcpu_block_update_hint_alloc
  - mm/percpu.c:pcpu_block_update_hint_alloc
  - mm/percpu.c:pcpu_next_md_free_region
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
In mm/percpu.c (ffffffff8127aee2)
Location: mm/percpu.c:284
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_alloc_area
  - mm/percpu.c:pcpu_block_update_hint_free
  - mm/percpu.c:pcpu_block_update_hint_free
  - mm/percpu.c:pcpu_block_update_hint_alloc
  - mm/percpu.c:pcpu_block_update_hint_alloc
  - mm/percpu.c:pcpu_next_md_free_region
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
In mm/percpu.c (ffffffff812858f2)
Location: mm/percpu.c:290
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_alloc_area
  - mm/percpu.c:pcpu_block_update_hint_free
  - mm/percpu.c:pcpu_block_update_hint_free
  - mm/percpu.c:pcpu_block_update_hint_alloc
  - mm/percpu.c:pcpu_block_update_hint_alloc
  - mm/percpu.c:pcpu_next_md_free_region
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
In mm/percpu.c (ffffffff8128a12c)
Location: mm/percpu.c:291
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_alloc_area
  - mm/percpu.c:pcpu_block_update_hint_free
  - mm/percpu.c:pcpu_block_update_hint_free
  - mm/percpu.c:pcpu_block_update_hint_alloc
  - mm/percpu.c:pcpu_block_update_hint_alloc
  - mm/percpu.c:pcpu_next_md_free_region
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
In mm/percpu.c (ffffffff812c9c0c)
Location: mm/percpu.c:296
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_alloc_area
  - mm/percpu.c:pcpu_block_update_hint_free
  - mm/percpu.c:pcpu_block_update_hint_free
  - mm/percpu.c:pcpu_block_update_hint_alloc
  - mm/percpu.c:pcpu_block_update_hint_alloc
  - mm/percpu.c:pcpu_next_md_free_region
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
In mm/percpu.c (ffffffff81328195)
Location: mm/percpu.c:296
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_alloc_area
  - mm/percpu.c:pcpu_block_update_hint_free
  - mm/percpu.c:pcpu_block_update_hint_free
  - mm/percpu.c:pcpu_block_update_hint_alloc
  - mm/percpu.c:pcpu_block_update_hint_alloc
  - mm/percpu.c:pcpu_next_md_free_region
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
In mm/percpu.c (ffffffff8139c431)
Location: mm/percpu.c:292
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_alloc_area
  - mm/percpu.c:pcpu_block_update_hint_free
  - mm/percpu.c:pcpu_block_update_hint_free
  - mm/percpu.c:pcpu_block_update_hint_alloc
  - mm/percpu.c:pcpu_block_update_hint_alloc
  - mm/percpu.c:pcpu_next_md_free_region
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
In mm/percpu.c (ffffffff813cf523)
Location: mm/percpu.c:292
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_alloc_area
  - mm/percpu.c:pcpu_block_update_hint_free
  - mm/percpu.c:pcpu_block_update_hint_free
  - mm/percpu.c:pcpu_block_update_hint_alloc
  - mm/percpu.c:pcpu_block_update_hint_alloc
  - mm/percpu.c:pcpu_next_md_free_region
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
In mm/percpu.c (ffffffff813fa011)
Location: mm/percpu.c:292
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_alloc_area
  - mm/percpu.c:pcpu_block_update_hint_free
  - mm/percpu.c:pcpu_block_update_hint_free
  - mm/percpu.c:pcpu_block_update_hint_alloc
  - mm/percpu.c:pcpu_block_update_hint_alloc
  - mm/percpu.c:pcpu_next_md_free_region
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
In mm/percpu.c (ffff8000102e1588)
Location: mm/percpu.c:310
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_free_area
  - mm/percpu.c:pcpu_free_area
  - mm/percpu.c:pcpu_alloc_area
  - mm/percpu.c:pcpu_block_update_hint_alloc
  - mm/percpu.c:pcpu_block_update_hint_alloc
  - mm/percpu.c:pcpu_next_md_free_region
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
In mm/percpu.c (c0506708)
Location: mm/percpu.c:310
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_free_area
  - mm/percpu.c:pcpu_free_area
  - mm/percpu.c:pcpu_alloc_area
  - mm/percpu.c:pcpu_block_update_hint_alloc
  - mm/percpu.c:pcpu_block_update_hint_alloc
  - mm/percpu.c:pcpu_next_md_free_region
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
In mm/percpu.c (c0000000003a23ac)
Location: mm/percpu.c:310
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_free_area
  - mm/percpu.c:pcpu_free_area
  - mm/percpu.c:pcpu_alloc_area
  - mm/percpu.c:pcpu_block_update_hint_alloc
  - mm/percpu.c:pcpu_block_update_hint_alloc
  - mm/percpu.c:pcpu_next_md_free_region
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
In mm/percpu.c (ffffffe0001f915a)
Location: mm/percpu.c:310
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_free_area
  - mm/percpu.c:pcpu_free_area
  - mm/percpu.c:pcpu_alloc_area
  - mm/percpu.c:pcpu_block_update_hint_alloc
  - mm/percpu.c:pcpu_block_update_hint_alloc
  - mm/percpu.c:pcpu_next_md_free_region
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
In mm/percpu.c (ffffffff812439dc)
Location: mm/percpu.c:310
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_free_area
  - mm/percpu.c:pcpu_free_area
  - mm/percpu.c:pcpu_alloc_area
  - mm/percpu.c:pcpu_block_update_hint_alloc
  - mm/percpu.c:pcpu_block_update_hint_alloc
  - mm/percpu.c:pcpu_next_md_free_region
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
In mm/percpu.c (ffffffff812369ac)
Location: mm/percpu.c:310
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_free_area
  - mm/percpu.c:pcpu_free_area
  - mm/percpu.c:pcpu_alloc_area
  - mm/percpu.c:pcpu_block_update_hint_alloc
  - mm/percpu.c:pcpu_block_update_hint_alloc
  - mm/percpu.c:pcpu_next_md_free_region
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
In mm/percpu.c (ffffffff8124177c)
Location: mm/percpu.c:310
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_free_area
  - mm/percpu.c:pcpu_free_area
  - mm/percpu.c:pcpu_alloc_area
  - mm/percpu.c:pcpu_block_update_hint_alloc
  - mm/percpu.c:pcpu_block_update_hint_alloc
  - mm/percpu.c:pcpu_next_md_free_region
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
In mm/percpu.c (ffffffff81250efc)
Location: mm/percpu.c:310
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_free_area
  - mm/percpu.c:pcpu_free_area
  - mm/percpu.c:pcpu_alloc_area
  - mm/percpu.c:pcpu_block_update_hint_alloc
  - mm/percpu.c:pcpu_block_update_hint_alloc
  - mm/percpu.c:pcpu_next_md_free_region
```
</details>
</li>
</ul>

## Differences
