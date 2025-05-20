# Function: <code>pcpu_update_empty_pages</code>

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
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/percpu.c (ffffffff8123e27b)
Location: mm/percpu.c:571
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_balance_workfn
  - mm/percpu.c:pcpu_chunk_populated
  - mm/percpu.c:pcpu_free_area
  - mm/percpu.c:pcpu_block_update_hint_alloc
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
In mm/percpu.c (ffffffff8124c6ce)
Location: mm/percpu.c:571
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_balance_workfn
  - mm/percpu.c:pcpu_chunk_populated
  - mm/percpu.c:pcpu_free_area
  - mm/percpu.c:pcpu_block_update_hint_alloc
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
In mm/percpu.c (ffffffff8127a906)
Location: mm/percpu.c:545
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_balance_workfn
  - mm/percpu.c:pcpu_chunk_populated
  - mm/percpu.c:pcpu_block_update_hint_free
  - mm/percpu.c:pcpu_block_update_hint_alloc
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
In mm/percpu.c (ffffffff8128509b)
Location: mm/percpu.c:554
Inline: True
Inline callers:
  - mm/percpu.c:__pcpu_balance_workfn
  - mm/percpu.c:pcpu_chunk_populated
  - mm/percpu.c:pcpu_block_update_hint_free
  - mm/percpu.c:pcpu_block_update_hint_alloc
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
In mm/percpu.c (ffffffff8128b013)
Location: mm/percpu.c:555
Inline: True
Inline callers:
  - mm/percpu.c:__pcpu_balance_workfn
  - mm/percpu.c:pcpu_chunk_populated
  - mm/percpu.c:pcpu_block_update_hint_free
  - mm/percpu.c:pcpu_block_update_hint_alloc
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
In mm/percpu.c (ffffffff812c8eef)
Location: mm/percpu.c:602
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_chunk_depopulated
  - mm/percpu.c:pcpu_chunk_populated
  - mm/percpu.c:pcpu_block_update_hint_free
  - mm/percpu.c:pcpu_block_update_hint_alloc
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
In mm/percpu.c (ffffffff81326b9f)
Location: mm/percpu.c:602
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_chunk_depopulated
  - mm/percpu.c:pcpu_chunk_depopulated
  - mm/percpu.c:pcpu_chunk_populated
  - mm/percpu.c:pcpu_chunk_populated
  - mm/percpu.c:pcpu_block_update_hint_free
  - mm/percpu.c:pcpu_block_update_hint_free
  - mm/percpu.c:pcpu_block_update_hint_alloc
  - mm/percpu.c:pcpu_block_update_hint_alloc
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
In mm/percpu.c (ffffffff8139b83f)
Location: mm/percpu.c:598
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_chunk_depopulated
  - mm/percpu.c:pcpu_chunk_depopulated
  - mm/percpu.c:pcpu_chunk_populated
  - mm/percpu.c:pcpu_chunk_populated
  - mm/percpu.c:pcpu_block_update_hint_free
  - mm/percpu.c:pcpu_block_update_hint_free
  - mm/percpu.c:pcpu_block_update_hint_alloc
  - mm/percpu.c:pcpu_block_update_hint_alloc
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
In mm/percpu.c (ffffffff813ce81f)
Location: mm/percpu.c:598
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_chunk_depopulated
  - mm/percpu.c:pcpu_chunk_depopulated
  - mm/percpu.c:pcpu_chunk_populated
  - mm/percpu.c:pcpu_chunk_populated
  - mm/percpu.c:pcpu_block_update_hint_free
  - mm/percpu.c:pcpu_block_update_hint_free
  - mm/percpu.c:pcpu_block_update_hint_alloc
  - mm/percpu.c:pcpu_block_update_hint_alloc
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
In mm/percpu.c (ffffffff813f937f)
Location: mm/percpu.c:598
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_chunk_depopulated
  - mm/percpu.c:pcpu_chunk_depopulated
  - mm/percpu.c:pcpu_chunk_populated
  - mm/percpu.c:pcpu_chunk_populated
  - mm/percpu.c:pcpu_block_update_hint_free
  - mm/percpu.c:pcpu_block_update_hint_free
  - mm/percpu.c:pcpu_block_update_hint_alloc
  - mm/percpu.c:pcpu_block_update_hint_alloc
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
In mm/percpu.c (ffff8000102e165c)
Location: mm/percpu.c:571
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_balance_workfn
  - mm/percpu.c:pcpu_chunk_populated
  - mm/percpu.c:pcpu_free_area
  - mm/percpu.c:pcpu_block_update_hint_alloc
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
In mm/percpu.c (c050703c)
Location: mm/percpu.c:571
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_balance_workfn
  - mm/percpu.c:pcpu_chunk_populated
  - mm/percpu.c:pcpu_free_area
  - mm/percpu.c:pcpu_block_update_hint_alloc
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
In mm/percpu.c (c0000000003a38d8)
Location: mm/percpu.c:571
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_balance_workfn
  - mm/percpu.c:pcpu_chunk_populated
  - mm/percpu.c:pcpu_free_area
  - mm/percpu.c:pcpu_block_update_hint_alloc
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
In mm/percpu.c (ffffffe0001f9f06)
Location: mm/percpu.c:571
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_balance_workfn
  - mm/percpu.c:pcpu_chunk_populated
  - mm/percpu.c:pcpu_free_area
  - mm/percpu.c:pcpu_block_update_hint_alloc
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
In mm/percpu.c (ffffffff81244d1e)
Location: mm/percpu.c:571
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_balance_workfn
  - mm/percpu.c:pcpu_chunk_populated
  - mm/percpu.c:pcpu_free_area
  - mm/percpu.c:pcpu_block_update_hint_alloc
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
In mm/percpu.c (ffffffff81237a28)
Location: mm/percpu.c:571
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_balance_workfn
  - mm/percpu.c:pcpu_chunk_populated
  - mm/percpu.c:pcpu_free_area
  - mm/percpu.c:pcpu_block_update_hint_alloc
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
In mm/percpu.c (ffffffff81242abe)
Location: mm/percpu.c:571
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_balance_workfn
  - mm/percpu.c:pcpu_chunk_populated
  - mm/percpu.c:pcpu_free_area
  - mm/percpu.c:pcpu_block_update_hint_alloc
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
In mm/percpu.c (ffffffff81251fa5)
Location: mm/percpu.c:571
Inline: True
Inline callers:
  - mm/percpu.c:pcpu_balance_workfn
  - mm/percpu.c:pcpu_chunk_populated
  - mm/percpu.c:pcpu_free_area
  - mm/percpu.c:pcpu_block_update_hint_alloc
```
</details>
</li>
</ul>

## Differences
