# Function: <code>dm_destroy_keyslot_manager</code>

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
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

```c
void dm_destroy_keyslot_manager(struct blk_keyslot_manager *ksm);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/md/dm-table.c (ffffffff81966a6d)
Location: drivers/md/dm-table.c:1262
Inline: True
Inline callers:
  - drivers/md/dm-table.c:dm_table_set_restrictions
  - drivers/md/dm-table.c:dm_table_set_restrictions
  - drivers/md/dm-table.c:dm_table_construct_keyslot_manager
  - drivers/md/dm-table.c:dm_table_construct_keyslot_manager
  - drivers/md/dm-table.c:dm_table_construct_keyslot_manager
  - drivers/md/dm-table.c:dm_table_destroy
  - drivers/md/dm-table.c:dm_table_destroy
Direct callers:
  - drivers/md/dm.c:cleanup_mapped_device
  - drivers/md/dm-table.c:dm_table_construct_keyslot_manager
```
**Symbols:**

```
ffffffff81964bb0-ffffffff81964bd1: dm_destroy_keyslot_manager.part.0 (STB_LOCAL)
ffffffff81965ce0-ffffffff81965d07: dm_destroy_keyslot_manager (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
void dm_destroy_keyslot_manager(struct blk_keyslot_manager *ksm);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/md/dm-table.c (ffffffff81a0ec7d)
Location: drivers/md/dm-table.c:1257
Inline: True
Inline callers:
  - drivers/md/dm-table.c:dm_table_set_restrictions
  - drivers/md/dm-table.c:dm_table_set_restrictions
  - drivers/md/dm-table.c:dm_table_construct_keyslot_manager
  - drivers/md/dm-table.c:dm_table_construct_keyslot_manager
  - drivers/md/dm-table.c:dm_table_construct_keyslot_manager
  - drivers/md/dm-table.c:dm_table_destroy
  - drivers/md/dm-table.c:dm_table_destroy
Direct callers:
  - drivers/md/dm.c:cleanup_mapped_device
  - drivers/md/dm-table.c:dm_table_construct_keyslot_manager
```
**Symbols:**

```
ffffffff81a0cb20-ffffffff81a0cb41: dm_destroy_keyslot_manager.part.0 (STB_LOCAL)
ffffffff81a0dc70-ffffffff81a0dc97: dm_destroy_keyslot_manager (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>5.19</code>: Absent ⚠️
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
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
</ul>
