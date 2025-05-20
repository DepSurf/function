# Function: <code>dax_is_pmd_entry</code>

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
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/dax.c (0)
Location: fs/dax.c:80
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/dax.c (0)
Location: fs/dax.c:91
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/dax.c (0)
Location: fs/dax.c:94
Inline: True
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
In fs/dax.c (ffffffff812f8101)
Location: fs/dax.c:94
Inline: True
Inline callers:
  - fs/dax.c:dax_finish_sync_fault
  - fs/dax.c:dax_insert_mapping_entry
  - fs/dax.c:dax_insert_mapping_entry
  - fs/dax.c:dax_insert_mapping_entry
  - fs/dax.c:dax_insert_mapping_entry
  - fs/dax.c:grab_mapping_entry
  - fs/dax.c:dax_disassociate_entry
  - fs/dax.c:__get_unlocked_mapping_entry
  - fs/dax.c:dax_wake_mapping_entry_waiter
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
In fs/dax.c (ffffffff8130e9e3)
Location: fs/dax.c:113
Inline: True
Inline callers:
  - fs/dax.c:dax_finish_sync_fault
  - fs/dax.c:dax_insert_entry
  - fs/dax.c:dax_insert_entry
  - fs/dax.c:dax_insert_entry
  - fs/dax.c:dax_insert_entry
  - fs/dax.c:dax_layout_busy_page
  - fs/dax.c:dax_disassociate_entry
  - fs/dax.c:wait_entry_unlocked
  - fs/dax.c:get_unlocked_entry
  - fs/dax.c:dax_wake_entry
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
In fs/dax.c (ffffffff8133443e)
Location: fs/dax.c:105
Inline: True
Inline callers:
  - fs/dax.c:dax_insert_entry
  - fs/dax.c:dax_insert_entry
  - fs/dax.c:dax_insert_entry
  - fs/dax.c:dax_layout_busy_page
  - fs/dax.c:grab_mapping_entry
  - fs/dax.c:dax_disassociate_entry
  - fs/dax.c:wait_entry_unlocked
  - fs/dax.c:dax_wake_entry
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
In fs/dax.c (ffffffff81348009)
Location: fs/dax.c:105
Inline: True
Inline callers:
  - fs/dax.c:dax_insert_entry
  - fs/dax.c:dax_insert_entry
  - fs/dax.c:dax_insert_entry
  - fs/dax.c:dax_layout_busy_page
  - fs/dax.c:grab_mapping_entry
  - fs/dax.c:dax_disassociate_entry
  - fs/dax.c:wait_entry_unlocked
  - fs/dax.c:dax_wake_entry
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
In fs/dax.c (ffffffff8138d591)
Location: fs/dax.c:105
Inline: True
Inline callers:
  - fs/dax.c:dax_insert_entry
  - fs/dax.c:dax_insert_entry
  - fs/dax.c:dax_layout_busy_page
  - fs/dax.c:grab_mapping_entry
  - fs/dax.c:dax_disassociate_entry
  - fs/dax.c:wait_entry_unlocked
  - fs/dax.c:dax_wake_entry
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
In fs/dax.c (ffffffff8139ed21)
Location: fs/dax.c:105
Inline: True
Inline callers:
  - fs/dax.c:dax_insert_entry
  - fs/dax.c:dax_insert_entry
  - fs/dax.c:dax_layout_busy_page_range
  - fs/dax.c:grab_mapping_entry
  - fs/dax.c:dax_disassociate_entry
  - fs/dax.c:wait_entry_unlocked
  - fs/dax.c:dax_wake_entry
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
In fs/dax.c (ffffffff813a5e31)
Location: fs/dax.c:105
Inline: True
Inline callers:
  - fs/dax.c:dax_insert_entry
  - fs/dax.c:dax_insert_entry
  - fs/dax.c:dax_layout_busy_page_range
  - fs/dax.c:grab_mapping_entry
  - fs/dax.c:dax_disassociate_entry
  - fs/dax.c:wait_entry_unlocked
  - fs/dax.c:dax_wake_entry
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
In fs/dax.c (ffffffff813f58a1)
Location: fs/dax.c:105
Inline: True
Inline callers:
  - fs/dax.c:dax_insert_entry
  - fs/dax.c:dax_insert_entry
  - fs/dax.c:dax_layout_busy_page_range
  - fs/dax.c:grab_mapping_entry
  - fs/dax.c:dax_disassociate_entry
  - fs/dax.c:wait_entry_unlocked
  - fs/dax.c:dax_wake_entry
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
In fs/dax.c (ffffffff81468a05)
Location: fs/dax.c:105
Inline: True
Inline callers:
  - fs/dax.c:dax_insert_entry
  - fs/dax.c:dax_insert_entry
  - fs/dax.c:dax_layout_busy_page_range
  - fs/dax.c:grab_mapping_entry
  - fs/dax.c:dax_disassociate_entry
  - fs/dax.c:wait_entry_unlocked
  - fs/dax.c:dax_wake_entry
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
In fs/dax.c (ffffffff814f9539)
Location: fs/dax.c:105
Inline: True
Inline callers:
  - fs/dax.c:dax_insert_entry
  - fs/dax.c:dax_insert_entry
  - fs/dax.c:dax_layout_busy_page_range
  - fs/dax.c:grab_mapping_entry
  - fs/dax.c:dax_disassociate_entry
  - fs/dax.c:wait_entry_unlocked
  - fs/dax.c:dax_wake_entry
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
In fs/dax.c (ffffffff815309fd)
Location: fs/dax.c:105
Inline: True
Inline callers:
  - fs/dax.c:dax_insert_entry
  - fs/dax.c:dax_layout_busy_page_range
  - fs/dax.c:grab_mapping_entry
  - fs/dax.c:dax_disassociate_entry
  - fs/dax.c:wait_entry_unlocked
  - fs/dax.c:dax_wake_entry
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
In fs/dax.c (ffffffff815658f1)
Location: fs/dax.c:91
Inline: True
Inline callers:
  - fs/dax.c:dax_insert_entry
  - fs/dax.c:dax_layout_busy_page_range
  - fs/dax.c:grab_mapping_entry
  - fs/dax.c:dax_disassociate_entry
  - fs/dax.c:wait_entry_unlocked
  - fs/dax.c:dax_wake_entry
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
In fs/dax.c (ffff800010408edc)
Location: fs/dax.c:105
Inline: True
Inline callers:
  - fs/dax.c:dax_layout_busy_page
  - fs/dax.c:dax_disassociate_entry
  - fs/dax.c:dax_wake_entry
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
In fs/dax.c (c000000000515974)
Location: fs/dax.c:105
Inline: True
Inline callers:
  - fs/dax.c:grab_mapping_entry
  - fs/dax.c:wait_entry_unlocked
  - fs/dax.c:dax_wake_entry
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
In fs/dax.c (ffffffe0002b3272)
Location: fs/dax.c:105
Inline: True
Inline callers:
  - fs/dax.c:dax_layout_busy_page
  - fs/dax.c:dax_disassociate_entry
  - fs/dax.c:wait_entry_unlocked
  - fs/dax.c:dax_wake_entry
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
In fs/dax.c (ffffffff813405e9)
Location: fs/dax.c:105
Inline: True
Inline callers:
  - fs/dax.c:dax_insert_entry
  - fs/dax.c:dax_insert_entry
  - fs/dax.c:dax_insert_entry
  - fs/dax.c:dax_layout_busy_page
  - fs/dax.c:grab_mapping_entry
  - fs/dax.c:dax_disassociate_entry
  - fs/dax.c:wait_entry_unlocked
  - fs/dax.c:dax_wake_entry
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
In fs/dax.c (ffffffff81331249)
Location: fs/dax.c:105
Inline: True
Inline callers:
  - fs/dax.c:dax_insert_entry
  - fs/dax.c:dax_insert_entry
  - fs/dax.c:dax_insert_entry
  - fs/dax.c:dax_layout_busy_page
  - fs/dax.c:grab_mapping_entry
  - fs/dax.c:dax_disassociate_entry
  - fs/dax.c:wait_entry_unlocked
  - fs/dax.c:dax_wake_entry
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
In fs/dax.c (ffffffff8133e0b9)
Location: fs/dax.c:105
Inline: True
Inline callers:
  - fs/dax.c:dax_insert_entry
  - fs/dax.c:dax_insert_entry
  - fs/dax.c:dax_insert_entry
  - fs/dax.c:dax_layout_busy_page
  - fs/dax.c:grab_mapping_entry
  - fs/dax.c:dax_disassociate_entry
  - fs/dax.c:wait_entry_unlocked
  - fs/dax.c:dax_wake_entry
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
In fs/dax.c (ffffffff81350ce9)
Location: fs/dax.c:105
Inline: True
Inline callers:
  - fs/dax.c:dax_insert_entry
  - fs/dax.c:dax_insert_entry
  - fs/dax.c:dax_insert_entry
  - fs/dax.c:dax_layout_busy_page
  - fs/dax.c:grab_mapping_entry
  - fs/dax.c:dax_disassociate_entry
  - fs/dax.c:wait_entry_unlocked
  - fs/dax.c:dax_wake_entry
```
</details>
</li>
</ul>

## Differences
