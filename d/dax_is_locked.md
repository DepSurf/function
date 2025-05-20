# Function: <code>dax_is_locked</code>

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
In fs/dax.c (ffffffff8130e718)
Location: fs/dax.c:101
Inline: True
Inline callers:
  - fs/dax.c:dax_layout_busy_page
  - fs/dax.c:dax_lock_page
  - fs/dax.c:dax_unlock_entry
  - fs/dax.c:dax_unlock_entry
  - fs/dax.c:get_unlocked_entry
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
In fs/dax.c (ffffffff81334e43)
Location: fs/dax.c:93
Inline: True
Inline callers:
  - fs/dax.c:dax_layout_busy_page
  - fs/dax.c:dax_lock_page
  - fs/dax.c:dax_unlock_entry
  - fs/dax.c:dax_unlock_entry
  - fs/dax.c:get_unlocked_entry
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
In fs/dax.c (ffffffff81348a23)
Location: fs/dax.c:93
Inline: True
Inline callers:
  - fs/dax.c:dax_layout_busy_page
  - fs/dax.c:dax_lock_page
  - fs/dax.c:get_unlocked_entry
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
In fs/dax.c (ffffffff8138da85)
Location: fs/dax.c:93
Inline: True
Inline callers:
  - fs/dax.c:dax_writeback_one
  - fs/dax.c:dax_layout_busy_page
  - fs/dax.c:dax_lock_page
  - fs/dax.c:dax_unlock_entry
  - fs/dax.c:dax_unlock_entry
  - fs/dax.c:get_unlocked_entry
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
In fs/dax.c (ffffffff8139f4ec)
Location: fs/dax.c:93
Inline: True
Inline callers:
  - fs/dax.c:dax_writeback_one
  - fs/dax.c:dax_layout_busy_page_range
  - fs/dax.c:dax_lock_page
  - fs/dax.c:dax_unlock_entry
  - fs/dax.c:dax_unlock_entry
  - fs/dax.c:get_unlocked_entry
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
In fs/dax.c (ffffffff813a625c)
Location: fs/dax.c:93
Inline: True
Inline callers:
  - fs/dax.c:dax_writeback_one
  - fs/dax.c:dax_layout_busy_page_range
  - fs/dax.c:dax_lock_page
  - fs/dax.c:dax_unlock_entry
  - fs/dax.c:dax_unlock_entry
  - fs/dax.c:get_unlocked_entry
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
In fs/dax.c (ffffffff813f5ccc)
Location: fs/dax.c:93
Inline: True
Inline callers:
  - fs/dax.c:dax_writeback_one
  - fs/dax.c:dax_layout_busy_page_range
  - fs/dax.c:dax_lock_page
  - fs/dax.c:dax_unlock_entry
  - fs/dax.c:dax_unlock_entry
  - fs/dax.c:get_unlocked_entry
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
In fs/dax.c (ffffffff814694f4)
Location: fs/dax.c:93
Inline: True
Inline callers:
  - fs/dax.c:dax_writeback_one
  - fs/dax.c:dax_layout_busy_page_range
  - fs/dax.c:dax_lock_page
  - fs/dax.c:dax_unlock_entry
  - fs/dax.c:dax_unlock_entry
  - fs/dax.c:get_unlocked_entry
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
In fs/dax.c (ffffffff814f9f94)
Location: fs/dax.c:93
Inline: True
Inline callers:
  - fs/dax.c:dax_writeback_one
  - fs/dax.c:dax_layout_busy_page_range
  - fs/dax.c:dax_lock_mapping_entry
  - fs/dax.c:dax_lock_page
  - fs/dax.c:dax_unlock_entry
  - fs/dax.c:dax_unlock_entry
  - fs/dax.c:get_unlocked_entry
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
In fs/dax.c (ffffffff81530664)
Location: fs/dax.c:93
Inline: True
Inline callers:
  - fs/dax.c:dax_layout_busy_page_range
  - fs/dax.c:dax_lock_mapping_entry
  - fs/dax.c:dax_lock_page
  - fs/dax.c:dax_unlock_entry
  - fs/dax.c:dax_unlock_entry
  - fs/dax.c:get_unlocked_entry
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
In fs/dax.c (ffffffff81565544)
Location: fs/dax.c:79
Inline: True
Inline callers:
  - fs/dax.c:dax_layout_busy_page_range
  - fs/dax.c:dax_lock_mapping_entry
  - fs/dax.c:dax_lock_folio
  - fs/dax.c:dax_unlock_entry
  - fs/dax.c:dax_unlock_entry
  - fs/dax.c:get_unlocked_entry
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
In fs/dax.c (ffff800010408e8c)
Location: fs/dax.c:93
Inline: True
Inline callers:
  - fs/dax.c:dax_layout_busy_page
  - fs/dax.c:dax_lock_page
  - fs/dax.c:dax_unlock_entry
  - fs/dax.c:dax_unlock_entry
  - fs/dax.c:get_unlocked_entry
```
</details>
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/dax.c (c000000000514b6c)
Location: fs/dax.c:93
Inline: True
Inline callers:
  - fs/dax.c:dax_writeback_mapping_range
  - fs/dax.c:dax_lock_page
  - fs/dax.c:dax_unlock_entry
  - fs/dax.c:dax_unlock_entry
  - fs/dax.c:get_unlocked_entry
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
In fs/dax.c (ffffffe0002b325c)
Location: fs/dax.c:93
Inline: True
Inline callers:
  - fs/dax.c:dax_layout_busy_page
  - fs/dax.c:dax_lock_page
  - fs/dax.c:get_unlocked_entry
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
In fs/dax.c (ffffffff81341003)
Location: fs/dax.c:93
Inline: True
Inline callers:
  - fs/dax.c:dax_layout_busy_page
  - fs/dax.c:dax_lock_page
  - fs/dax.c:get_unlocked_entry
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
In fs/dax.c (ffffffff813319e3)
Location: fs/dax.c:93
Inline: True
Inline callers:
  - fs/dax.c:dax_layout_busy_page
  - fs/dax.c:dax_lock_page
  - fs/dax.c:get_unlocked_entry
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
In fs/dax.c (ffffffff8133ead3)
Location: fs/dax.c:93
Inline: True
Inline callers:
  - fs/dax.c:dax_layout_busy_page
  - fs/dax.c:dax_lock_page
  - fs/dax.c:get_unlocked_entry
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
In fs/dax.c (ffffffff813519a3)
Location: fs/dax.c:93
Inline: True
Inline callers:
  - fs/dax.c:dax_layout_busy_page
  - fs/dax.c:dax_lock_page
  - fs/dax.c:get_unlocked_entry
```
</details>
</li>
</ul>

## Differences
