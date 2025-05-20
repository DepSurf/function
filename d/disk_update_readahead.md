# Function: <code>disk_update_readahead</code>

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
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void disk_update_readahead(struct gendisk *disk);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-settings.c (ffffffff815d1953)
Location: block/blk-settings.c:386
Inline: True
Inline callers:
  - block/blk-settings.c:disk_stack_limits
Direct callers:
  - block/genhd.c:device_add_disk
  - drivers/md/dm-table.c:dm_table_set_restrictions
```
**Symbols:**

```
ffffffff815d1030-ffffffff815d1075: disk_update_readahead (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void disk_update_readahead(struct gendisk *disk);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-settings.c (ffffffff8167d46f)
Location: block/blk-settings.c:385
Inline: True
Inline callers:
  - block/blk-settings.c:disk_stack_limits
Direct callers:
  - block/genhd.c:device_add_disk
  - drivers/md/dm-table.c:dm_table_set_restrictions
```
**Symbols:**

```
ffffffff8167c920-ffffffff8167c973: disk_update_readahead (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void disk_update_readahead(struct gendisk *disk);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-settings.c (ffffffff81739f3b)
Location: block/blk-settings.c:385
Inline: True
Inline callers:
  - block/blk-settings.c:disk_stack_limits
Direct callers:
  - block/genhd.c:device_add_disk
  - drivers/md/dm-table.c:dm_table_set_restrictions
```
**Symbols:**

```
ffffffff817391e0-ffffffff81739233: disk_update_readahead (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void disk_update_readahead(struct gendisk *disk);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-settings.c (ffffffff81776618)
Location: block/blk-settings.c:391
Inline: True
Inline callers:
  - block/blk-settings.c:disk_stack_limits
Direct callers:
  - block/genhd.c:device_add_disk
  - drivers/md/dm-table.c:dm_table_set_restrictions
```
**Symbols:**

```
ffffffff817758b0-ffffffff81775903: disk_update_readahead (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void disk_update_readahead(struct gendisk *disk);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-settings.c (ffffffff817b8942)
Location: block/blk-settings.c:394
Inline: True
Inline callers:
  - block/blk-settings.c:disk_stack_limits
Direct callers:
  - block/genhd.c:device_add_disk
  - drivers/md/dm-table.c:dm_table_set_restrictions
```
**Symbols:**

```
ffffffff817b7b80-ffffffff817b7bd3: disk_update_readahead (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
