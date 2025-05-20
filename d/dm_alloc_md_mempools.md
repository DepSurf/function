# Function: <code>dm_alloc_md_mempools</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct dm_md_mempools *dm_alloc_md_mempools(struct mapped_device *md, unsigned int type, unsigned int integrity, unsigned int per_bio_data_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffff816a4a30)
Location: drivers/md/dm.c:3484
Inline: False
Direct callers:
  - drivers/md/dm-table.c:dm_table_complete
```
**Symbols:**

```
ffffffff816a4a30-ffffffff816a4c7b: dm_alloc_md_mempools (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct dm_md_mempools *dm_alloc_md_mempools(struct mapped_device *md, unsigned int type, unsigned int integrity, unsigned int per_io_data_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffff81704be0)
Location: drivers/md/dm.c:2487
Inline: False
Direct callers:
  - drivers/md/dm-table.c:dm_table_complete
```
**Symbols:**

```
ffffffff81704be0-ffffffff81704d84: dm_alloc_md_mempools (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct dm_md_mempools *dm_alloc_md_mempools(struct mapped_device *md, unsigned int type, unsigned int integrity, unsigned int per_io_data_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffff81736a90)
Location: drivers/md/dm.c:2547
Inline: False
Direct callers:
  - drivers/md/dm-table.c:dm_table_complete
```
**Symbols:**

```
ffffffff81736a90-ffffffff81736c34: dm_alloc_md_mempools (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct dm_md_mempools *dm_alloc_md_mempools(struct mapped_device *md, enum dm_queue_mode type, unsigned int integrity, unsigned int per_io_data_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffff8174fe80)
Location: drivers/md/dm.c:2759
Inline: False
Direct callers:
  - drivers/md/dm-table.c:dm_table_complete
```
**Symbols:**

```
ffffffff8174fe80-ffffffff8174ff98: dm_alloc_md_mempools (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct dm_md_mempools *dm_alloc_md_mempools(struct mapped_device *md, enum dm_queue_mode type, unsigned int integrity, unsigned int per_io_data_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffff817c2060)
Location: drivers/md/dm.c:2738
Inline: False
Direct callers:
  - drivers/md/dm-table.c:dm_table_complete
```
**Symbols:**

```
ffffffff817c2060-ffffffff817c2175: dm_alloc_md_mempools (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct dm_md_mempools *dm_alloc_md_mempools(struct mapped_device *md, enum dm_queue_mode type, unsigned int integrity, unsigned int per_io_data_size, unsigned int min_pool_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffff8180a7c0)
Location: drivers/md/dm.c:2927
Inline: False
Direct callers:
  - drivers/md/dm-table.c:dm_table_complete
```
**Symbols:**

```
ffffffff8180a7c0-ffffffff8180a943: dm_alloc_md_mempools (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct dm_md_mempools *dm_alloc_md_mempools(struct mapped_device *md, enum dm_queue_mode type, unsigned int integrity, unsigned int per_io_data_size, unsigned int min_pool_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffff818367c0)
Location: drivers/md/dm.c:2950
Inline: False
Direct callers:
  - drivers/md/dm-table.c:dm_table_complete
```
**Symbols:**

```
ffffffff818367c0-ffffffff81836942: dm_alloc_md_mempools (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct dm_md_mempools *dm_alloc_md_mempools(struct mapped_device *md, enum dm_queue_mode type, unsigned int integrity, unsigned int per_io_data_size, unsigned int min_pool_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffff81879380)
Location: drivers/md/dm.c:2981
Inline: False
Direct callers:
  - drivers/md/dm-table.c:dm_table_complete
```
**Symbols:**

```
ffffffff81879380-ffffffff818794f5: dm_alloc_md_mempools (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct dm_md_mempools *dm_alloc_md_mempools(struct mapped_device *md, enum dm_queue_mode type, unsigned int integrity, unsigned int per_io_data_size, unsigned int min_pool_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffff818ab1c0)
Location: drivers/md/dm.c:2986
Inline: False
Direct callers:
  - drivers/md/dm-table.c:dm_table_complete
```
**Symbols:**

```
ffffffff818ab1c0-ffffffff818ab335: dm_alloc_md_mempools (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct dm_md_mempools *dm_alloc_md_mempools(struct mapped_device *md, enum dm_queue_mode type, unsigned int integrity, unsigned int per_io_data_size, unsigned int min_pool_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffff8197b390)
Location: drivers/md/dm.c:3049
Inline: False
Direct callers:
  - drivers/md/dm-table.c:dm_table_complete
```
**Symbols:**

```
ffffffff8197b390-ffffffff8197b50d: dm_alloc_md_mempools (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct dm_md_mempools *dm_alloc_md_mempools(struct mapped_device *md, enum dm_queue_mode type, unsigned int integrity, unsigned int per_io_data_size, unsigned int min_pool_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffff8197fbb0)
Location: drivers/md/dm.c:2896
Inline: False
Direct callers:
  - drivers/md/dm-table.c:dm_table_complete
```
**Symbols:**

```
ffffffff8197fbb0-ffffffff8197fd1b: dm_alloc_md_mempools (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct dm_md_mempools *dm_alloc_md_mempools(struct mapped_device *md, enum dm_queue_mode type, unsigned int integrity, unsigned int per_io_data_size, unsigned int min_pool_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffff81963d30)
Location: drivers/md/dm.c:2915
Inline: False
Direct callers:
  - drivers/md/dm-table.c:dm_table_complete
```
**Symbols:**

```
ffffffff81963d30-ffffffff81963e9a: dm_alloc_md_mempools (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct dm_md_mempools *dm_alloc_md_mempools(struct mapped_device *md, enum dm_queue_mode type, unsigned int integrity, unsigned int per_io_data_size, unsigned int min_pool_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffff81a0bce0)
Location: drivers/md/dm.c:2804
Inline: False
Direct callers:
  - drivers/md/dm-table.c:dm_table_complete
```
**Symbols:**

```
ffffffff81a0bce0-ffffffff81a0be4a: dm_alloc_md_mempools (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct dm_md_mempools *dm_alloc_md_mempools(struct mapped_device *md, enum dm_queue_mode type, unsigned int per_io_data_size, unsigned int min_pool_size, bool integrity, bool poll);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffff81b741d0)
Location: drivers/md/dm.c:2985
Inline: False
Direct callers:
  - drivers/md/dm-table.c:dm_table_complete
```
**Symbols:**

```
ffffffff81b741d0-ffffffff81b74370: dm_alloc_md_mempools (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
struct dm_md_mempools *dm_alloc_md_mempools(struct mapped_device *md, enum dm_queue_mode type, unsigned int integrity, unsigned int per_io_data_size, unsigned int min_pool_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffff800010b01478)
Location: drivers/md/dm.c:2986
Inline: False
Direct callers:
  - drivers/md/dm-table.c:dm_table_complete
```
**Symbols:**

```
ffff800010b01478-ffff800010b01660: dm_alloc_md_mempools (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct dm_md_mempools *dm_alloc_md_mempools(struct mapped_device *md, enum dm_queue_mode type, unsigned int integrity, unsigned int per_io_data_size, unsigned int min_pool_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (c0be0c00)
Location: drivers/md/dm.c:2986
Inline: False
Direct callers:
  - drivers/md/dm-table.c:dm_table_complete
```
**Symbols:**

```
c0be0c00-c0be0d7c: dm_alloc_md_mempools (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct dm_md_mempools *dm_alloc_md_mempools(struct mapped_device *md, enum dm_queue_mode type, unsigned int integrity, unsigned int per_io_data_size, unsigned int min_pool_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (c000000000bf07b0)
Location: drivers/md/dm.c:2986
Inline: False
Direct callers:
  - drivers/md/dm-table.c:dm_table_complete
```
**Symbols:**

```
c000000000bf07b0-c000000000bf0a30: dm_alloc_md_mempools (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct dm_md_mempools *dm_alloc_md_mempools(struct mapped_device *md, enum dm_queue_mode type, unsigned int integrity, unsigned int per_io_data_size, unsigned int min_pool_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffe0006f1452)
Location: drivers/md/dm.c:2986
Inline: False
Direct callers:
  - drivers/md/dm-table.c:dm_table_complete
```
**Symbols:**

```
ffffffe0006f1452-ffffffe0006f15ce: dm_alloc_md_mempools (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
struct dm_md_mempools *dm_alloc_md_mempools(struct mapped_device *md, enum dm_queue_mode type, unsigned int integrity, unsigned int per_io_data_size, unsigned int min_pool_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffff81851040)
Location: drivers/md/dm.c:2986
Inline: False
Direct callers:
  - drivers/md/dm-table.c:dm_table_complete
```
**Symbols:**

```
ffffffff81851040-ffffffff818511b5: dm_alloc_md_mempools (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct dm_md_mempools *dm_alloc_md_mempools(struct mapped_device *md, enum dm_queue_mode type, unsigned int integrity, unsigned int per_io_data_size, unsigned int min_pool_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffff81818650)
Location: drivers/md/dm.c:2986
Inline: False
Direct callers:
  - drivers/md/dm-table.c:dm_table_complete
```
**Symbols:**

```
ffffffff81818650-ffffffff818187c5: dm_alloc_md_mempools (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct dm_md_mempools *dm_alloc_md_mempools(struct mapped_device *md, enum dm_queue_mode type, unsigned int integrity, unsigned int per_io_data_size, unsigned int min_pool_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffff818a0670)
Location: drivers/md/dm.c:2986
Inline: False
Direct callers:
  - drivers/md/dm-table.c:dm_table_complete
```
**Symbols:**

```
ffffffff818a0670-ffffffff818a07e5: dm_alloc_md_mempools (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct dm_md_mempools *dm_alloc_md_mempools(struct mapped_device *md, enum dm_queue_mode type, unsigned int integrity, unsigned int per_io_data_size, unsigned int min_pool_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffff818bc8b0)
Location: drivers/md/dm.c:2986
Inline: False
Direct callers:
  - drivers/md/dm-table.c:dm_table_complete
```
**Symbols:**

```
ffffffff818bc8b0-ffffffff818bca25: dm_alloc_md_mempools (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Changed between <code>4.4</code> and <code>4.8</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>unsigned int per_io_data_size</code>
</li>
<li>
<b>Param removed. </b>
<code>unsigned int per_bio_data_size</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>4.10</code> and <code>4.13</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>unsigned int type</code> ➡️ <code>enum dm_queue_mode type</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>4.15</code> and <code>4.18</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>unsigned int min_pool_size</code>
</li>
</ul>
</details>
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
<details>
<summary>Changed between <code>5.15</code> and <code>5.19</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>bool poll</code>
</li>
<li>
<b>Param reordered. </b>
<code>md, type, integrity, per_io_data_size, min_pool_size</code> ➡️ <code>md, type, per_io_data_size, min_pool_size, integrity, poll</code>
</li>
<li>
<b>Param type changed. </b>
<code>unsigned int integrity</code> ➡️ <code>bool integrity</code>
</li>
</ul>
</details>
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
