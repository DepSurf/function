# Function: <code>dm_get_md_type</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline, Transformation ⚠️</summary>

```c
unsigned int dm_get_md_type(struct mapped_device *md);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/md/dm.c (ffffffff816a23e0)
Location: drivers/md/dm.c:2575
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_setup_md_queue
  - drivers/md/dm.c:dm_setup_md_queue
Direct callers:
  - drivers/md/dm.c:dm_setup_md_queue
  - drivers/md/dm-table.c:dm_table_complete
  - drivers/md/dm-ioctl.c:table_load
  - drivers/md/dm-ioctl.c:table_load
```
**Symbols:**

```
ffffffff816a23e0-ffffffff816a23eb: dm_get_md_type.part.33 (STB_LOCAL)
ffffffff816a37b0-ffffffff816a37d0: dm_get_md_type (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
unsigned int dm_get_md_type(struct mapped_device *md);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffff817040de)
Location: drivers/md/dm.c:1747
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_setup_md_queue
Direct callers:
  - drivers/md/dm-table.c:dm_table_complete
  - drivers/md/dm-ioctl.c:table_load
  - drivers/md/dm-ioctl.c:table_load
  - drivers/md/dm-rq.c:dm_attr_rq_based_seq_io_merge_deadline_store
```
**Symbols:**

```
ffffffff81704090-ffffffff817040a1: dm_get_md_type (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
unsigned int dm_get_md_type(struct mapped_device *md);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffff81735fae)
Location: drivers/md/dm.c:1804
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_setup_md_queue
Direct callers:
  - drivers/md/dm-table.c:dm_table_complete
  - drivers/md/dm-ioctl.c:table_load
  - drivers/md/dm-ioctl.c:table_load
  - drivers/md/dm-rq.c:dm_attr_rq_based_seq_io_merge_deadline_store
```
**Symbols:**

```
ffffffff81735f60-ffffffff81735f71: dm_get_md_type (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
enum dm_queue_mode dm_get_md_type(struct mapped_device *md);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffff8174f40e)
Location: drivers/md/dm.c:2011
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_setup_md_queue
Direct callers:
  - drivers/md/dm-table.c:dm_table_complete
  - drivers/md/dm-ioctl.c:table_load
  - drivers/md/dm-ioctl.c:table_load
  - drivers/md/dm-rq.c:dm_attr_rq_based_seq_io_merge_deadline_store
```
**Symbols:**

```
ffffffff8174f3c0-ffffffff8174f3d1: dm_get_md_type (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
enum dm_queue_mode dm_get_md_type(struct mapped_device *md);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffff817c165e)
Location: drivers/md/dm.c:1990
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_setup_md_queue
Direct callers:
  - drivers/md/dm-table.c:dm_table_complete
  - drivers/md/dm-ioctl.c:table_load
  - drivers/md/dm-ioctl.c:table_load
  - drivers/md/dm-rq.c:dm_attr_rq_based_seq_io_merge_deadline_store
```
**Symbols:**

```
ffffffff817c1620-ffffffff817c162e: dm_get_md_type (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
enum dm_queue_mode dm_get_md_type(struct mapped_device *md);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffff81809d27)
Location: drivers/md/dm.c:2175
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_setup_md_queue
Direct callers:
  - drivers/md/dm-table.c:dm_table_complete
  - drivers/md/dm-ioctl.c:table_load
  - drivers/md/dm-ioctl.c:table_load
  - drivers/md/dm-ioctl.c:table_load
  - drivers/md/dm-rq.c:dm_attr_rq_based_seq_io_merge_deadline_store
```
**Symbols:**

```
ffffffff81809cc0-ffffffff81809cd1: dm_get_md_type (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
enum dm_queue_mode dm_get_md_type(struct mapped_device *md);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffff81835d97)
Location: drivers/md/dm.c:2215
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_setup_md_queue
  - drivers/md/dm.c:dm_process_bio
Direct callers:
  - drivers/md/dm-table.c:dm_table_complete
  - drivers/md/dm-ioctl.c:table_load
  - drivers/md/dm-ioctl.c:table_load
  - drivers/md/dm-ioctl.c:table_load
```
**Symbols:**

```
ffffffff81835d30-ffffffff81835d41: dm_get_md_type (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
enum dm_queue_mode dm_get_md_type(struct mapped_device *md);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffff81878927)
Location: drivers/md/dm.c:2246
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_setup_md_queue
  - drivers/md/dm.c:dm_process_bio
Direct callers:
  - drivers/md/dm-table.c:dm_table_complete
  - drivers/md/dm-ioctl.c:table_load
  - drivers/md/dm-ioctl.c:table_load
  - drivers/md/dm-ioctl.c:table_load
```
**Symbols:**

```
ffffffff818788c0-ffffffff818788d1: dm_get_md_type (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
enum dm_queue_mode dm_get_md_type(struct mapped_device *md);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffff818aa777)
Location: drivers/md/dm.c:2244
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_setup_md_queue
  - drivers/md/dm.c:dm_process_bio
Direct callers:
  - drivers/md/dm-table.c:dm_table_complete
  - drivers/md/dm-ioctl.c:table_load
  - drivers/md/dm-ioctl.c:table_load
  - drivers/md/dm-ioctl.c:table_load
```
**Symbols:**

```
ffffffff818aa710-ffffffff818aa721: dm_get_md_type (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
enum dm_queue_mode dm_get_md_type(struct mapped_device *md);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffff8197aa68)
Location: drivers/md/dm.c:2247
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_setup_md_queue
  - drivers/md/dm.c:dm_make_request
  - drivers/md/dm.c:dm_process_bio
Direct callers:
  - drivers/md/dm-table.c:dm_table_determine_type
  - drivers/md/dm-ioctl.c:table_load
  - drivers/md/dm-ioctl.c:table_load
  - drivers/md/dm-ioctl.c:table_load
```
**Symbols:**

```
ffffffff8197aa10-ffffffff8197aa21: dm_get_md_type (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
enum dm_queue_mode dm_get_md_type(struct mapped_device *md);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffff8197f2a8)
Location: drivers/md/dm.c:2121
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_setup_md_queue
Direct callers:
  - drivers/md/dm-table.c:dm_table_determine_type
  - drivers/md/dm-ioctl.c:table_load
  - drivers/md/dm-ioctl.c:table_load
  - drivers/md/dm-ioctl.c:table_load
```
**Symbols:**

```
ffffffff8197f250-ffffffff8197f261: dm_get_md_type (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
enum dm_queue_mode dm_get_md_type(struct mapped_device *md);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffff819633c8)
Location: drivers/md/dm.c:2140
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_setup_md_queue
Direct callers:
  - drivers/md/dm-table.c:dm_table_determine_type
  - drivers/md/dm-ioctl.c:table_load
  - drivers/md/dm-ioctl.c:table_load
  - drivers/md/dm-ioctl.c:table_load
```
**Symbols:**

```
ffffffff81963370-ffffffff81963381: dm_get_md_type (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
enum dm_queue_mode dm_get_md_type(struct mapped_device *md);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffff81a09599)
Location: drivers/md/dm.c:2021
Inline: True
Inline callers:
  - drivers/md/dm.c:cleanup_mapped_device
Direct callers:
  - drivers/md/dm-table.c:dm_table_determine_type
  - drivers/md/dm-ioctl.c:table_load
  - drivers/md/dm-ioctl.c:table_load
  - drivers/md/dm-ioctl.c:table_load
```
**Symbols:**

```
ffffffff81a0b440-ffffffff81a0b451: dm_get_md_type (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
enum dm_queue_mode dm_get_md_type(struct mapped_device *md);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffff81b710bb)
Location: drivers/md/dm.c:2201
Inline: True
Inline callers:
  - drivers/md/dm.c:cleanup_mapped_device
Direct callers:
  - drivers/md/dm-table.c:dm_table_determine_type
  - drivers/md/dm-ioctl.c:table_load
  - drivers/md/dm-ioctl.c:table_load
  - drivers/md/dm-ioctl.c:table_load
```
**Symbols:**

```
ffffffff81b73850-ffffffff81b73867: dm_get_md_type (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
enum dm_queue_mode dm_get_md_type(struct mapped_device *md);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffff81d0de7d)
Location: drivers/md/dm.c:2279
Inline: True
Inline callers:
  - drivers/md/dm.c:cleanup_mapped_device
Direct callers:
  - drivers/md/dm-table.c:dm_table_determine_type
  - drivers/md/dm-ioctl.c:table_load
  - drivers/md/dm-ioctl.c:table_load
  - drivers/md/dm-ioctl.c:table_load
```
**Symbols:**

```
ffffffff81d10490-ffffffff81d104a7: dm_get_md_type (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
enum dm_queue_mode dm_get_md_type(struct mapped_device *md);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffff81d7747d)
Location: drivers/md/dm.c:2325
Inline: True
Inline callers:
  - drivers/md/dm.c:cleanup_mapped_device
Direct callers:
  - drivers/md/dm-table.c:dm_table_determine_type
  - drivers/md/dm-ioctl.c:table_load
  - drivers/md/dm-ioctl.c:table_load
  - drivers/md/dm-ioctl.c:table_load
```
**Symbols:**

```
ffffffff81d79900-ffffffff81d79917: dm_get_md_type (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
enum dm_queue_mode dm_get_md_type(struct mapped_device *md);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffff81e2e6ad)
Location: drivers/md/dm.c:2333
Inline: True
Inline callers:
  - drivers/md/dm.c:cleanup_mapped_device
Direct callers:
  - drivers/md/dm-table.c:dm_table_determine_type
  - drivers/md/dm-ioctl.c:table_load
  - drivers/md/dm-ioctl.c:table_load
  - drivers/md/dm-ioctl.c:table_load
```
**Symbols:**

```
ffffffff81e30aa0-ffffffff81e30ab7: dm_get_md_type (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
enum dm_queue_mode dm_get_md_type(struct mapped_device *md);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffff800010b00730)
Location: drivers/md/dm.c:2244
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_setup_md_queue
  - drivers/md/dm.c:dm_process_bio
Direct callers:
  - drivers/md/dm-table.c:dm_table_complete
  - drivers/md/dm-ioctl.c:table_load
  - drivers/md/dm-ioctl.c:table_load
  - drivers/md/dm-ioctl.c:table_load
```
**Symbols:**

```
ffff800010b006b0-ffff800010b006d8: dm_get_md_type (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
enum dm_queue_mode dm_get_md_type(struct mapped_device *md);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (c0be0148)
Location: drivers/md/dm.c:2244
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_setup_md_queue
  - drivers/md/dm.c:dm_process_bio
Direct callers:
  - drivers/md/dm-table.c:dm_table_complete
  - drivers/md/dm-ioctl.c:table_load
  - drivers/md/dm-ioctl.c:table_load
  - drivers/md/dm-ioctl.c:table_load
```
**Symbols:**

```
c0be00dc-c0be00f8: dm_get_md_type (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
enum dm_queue_mode dm_get_md_type(struct mapped_device *md);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (c000000000befc04)
Location: drivers/md/dm.c:2244
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_setup_md_queue
  - drivers/md/dm.c:dm_process_bio
Direct callers:
  - drivers/md/dm-table.c:dm_table_complete
  - drivers/md/dm-ioctl.c:table_load
  - drivers/md/dm-ioctl.c:table_load
  - drivers/md/dm-ioctl.c:table_load
```
**Symbols:**

```
c000000000befbb0-c000000000befbc0: dm_get_md_type (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
enum dm_queue_mode dm_get_md_type(struct mapped_device *md);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffe0006f0bfc)
Location: drivers/md/dm.c:2244
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_setup_md_queue
  - drivers/md/dm.c:dm_process_bio
Direct callers:
  - drivers/md/dm-table.c:dm_table_complete
  - drivers/md/dm-ioctl.c:table_load
  - drivers/md/dm-ioctl.c:table_load
  - drivers/md/dm-ioctl.c:table_load
```
**Symbols:**

```
ffffffe0006f0b9a-ffffffe0006f0bbe: dm_get_md_type (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
enum dm_queue_mode dm_get_md_type(struct mapped_device *md);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffff818505f7)
Location: drivers/md/dm.c:2244
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_setup_md_queue
  - drivers/md/dm.c:dm_process_bio
Direct callers:
  - drivers/md/dm-table.c:dm_table_complete
  - drivers/md/dm-ioctl.c:table_load
  - drivers/md/dm-ioctl.c:table_load
  - drivers/md/dm-ioctl.c:table_load
```
**Symbols:**

```
ffffffff81850590-ffffffff818505a1: dm_get_md_type (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
enum dm_queue_mode dm_get_md_type(struct mapped_device *md);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffff81817c07)
Location: drivers/md/dm.c:2244
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_setup_md_queue
  - drivers/md/dm.c:dm_process_bio
Direct callers:
  - drivers/md/dm-table.c:dm_table_complete
  - drivers/md/dm-ioctl.c:table_load
  - drivers/md/dm-ioctl.c:table_load
  - drivers/md/dm-ioctl.c:table_load
```
**Symbols:**

```
ffffffff81817ba0-ffffffff81817bb1: dm_get_md_type (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
enum dm_queue_mode dm_get_md_type(struct mapped_device *md);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffff8189fc27)
Location: drivers/md/dm.c:2244
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_setup_md_queue
  - drivers/md/dm.c:dm_process_bio
Direct callers:
  - drivers/md/dm-table.c:dm_table_complete
  - drivers/md/dm-ioctl.c:table_load
  - drivers/md/dm-ioctl.c:table_load
  - drivers/md/dm-ioctl.c:table_load
```
**Symbols:**

```
ffffffff8189fbc0-ffffffff8189fbd1: dm_get_md_type (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
enum dm_queue_mode dm_get_md_type(struct mapped_device *md);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffff818bbe87)
Location: drivers/md/dm.c:2244
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_setup_md_queue
  - drivers/md/dm.c:dm_process_bio
Direct callers:
  - drivers/md/dm-table.c:dm_table_complete
  - drivers/md/dm-ioctl.c:table_load
  - drivers/md/dm-ioctl.c:table_load
  - drivers/md/dm-ioctl.c:table_load
```
**Symbols:**

```
ffffffff818bbe20-ffffffff818bbe31: dm_get_md_type (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>4.10</code> and <code>4.13</code> ⚠️</summary>
<ul>
<li>
<b>Return type changed. </b>
<code>unsigned int</code> ➡️ <code>enum dm_queue_mode</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
<li>
No changes between <code>5.15</code> and <code>5.19</code> ✅
</li>
<li>
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
