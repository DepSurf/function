# Function: <code>is_fat32</code>

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
In fs/fat/cache.c (0)
Location: fs/fat/fat.h:159
Inline: True
```
```
In fs/fat/dir.c (0)
Location: fs/fat/fat.h:159
Inline: True
```
```
In fs/fat/fatent.c (0)
Location: fs/fat/fat.h:159
Inline: True
```
```
In fs/fat/inode.c (0)
Location: fs/fat/fat.h:159
Inline: True
```
```
In fs/fat/misc.c (0)
Location: fs/fat/fat.h:159
Inline: True
```
```
In fs/fat/nfs.c (0)
Location: fs/fat/fat.h:159
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
In fs/fat/cache.c (0)
Location: fs/fat/fat.h:159
Inline: True
```
```
In fs/fat/dir.c (0)
Location: fs/fat/fat.h:159
Inline: True
```
```
In fs/fat/fatent.c (0)
Location: fs/fat/fat.h:159
Inline: True
```
```
In fs/fat/inode.c (0)
Location: fs/fat/fat.h:159
Inline: True
```
```
In fs/fat/misc.c (0)
Location: fs/fat/fat.h:159
Inline: True
```
```
In fs/fat/nfs.c (0)
Location: fs/fat/fat.h:159
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
In fs/fat/cache.c (0)
Location: fs/fat/fat.h:159
Inline: True
```
```
In fs/fat/dir.c (0)
Location: fs/fat/fat.h:159
Inline: True
```
```
In fs/fat/fatent.c (0)
Location: fs/fat/fat.h:159
Inline: True
```
```
In fs/fat/inode.c (0)
Location: fs/fat/fat.h:159
Inline: True
```
```
In fs/fat/misc.c (0)
Location: fs/fat/fat.h:159
Inline: True
```
```
In fs/fat/nfs.c (0)
Location: fs/fat/fat.h:159
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
In fs/fat/cache.c (ffffffff81452934)
Location: fs/fat/fat.h:159
Inline: True
Inline callers:
  - fs/fat/cache.c:fat_bmap
```
```
In fs/fat/dir.c (ffffffff8145430d)
Location: fs/fat/fat.h:159
Inline: True
Inline callers:
  - fs/fat/dir.c:fat_add_entries
  - fs/fat/dir.c:fat_scan_logstart
  - fs/fat/dir.c:fat__get_entry
```
```
In fs/fat/fatent.c (ffffffff81457485)
Location: fs/fat/fat.h:159
Inline: True
Inline callers:
  - fs/fat/fatent.c:fat_count_free_clusters
  - fs/fat/fatent.c:fat_free_clusters
  - fs/fat/fatent.c:fat_alloc_clusters
  - fs/fat/fatent.c:fat_ent_access_init
```
```
In fs/fat/inode.c (ffffffff8145a77c)
Location: fs/fat/fat.h:159
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_read_root
  - fs/fat/inode.c:fat_set_state
  - fs/fat/inode.c:fat_fill_inode
  - fs/fat/inode.c:fat_fill_inode
```
```
In fs/fat/misc.c (ffffffff8145c157)
Location: fs/fat/fat.h:159
Inline: True
Inline callers:
  - fs/fat/misc.c:fat_clusters_flush
```
```
In fs/fat/nfs.c (ffffffff8145c998)
Location: fs/fat/fat.h:159
Inline: True
Inline callers:
  - fs/fat/nfs.c:fat_get_parent
  - fs/fat/nfs.c:fat_rebuild_parent
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/fat/cache.c (ffffffff8146ee14)
Location: fs/fat/fat.h:159
Inline: True
Inline callers:
  - fs/fat/cache.c:fat_bmap
```
```
In fs/fat/dir.c (ffffffff814707bd)
Location: fs/fat/fat.h:159
Inline: True
Inline callers:
  - fs/fat/dir.c:fat_add_entries
  - fs/fat/dir.c:fat_scan_logstart
  - fs/fat/dir.c:fat__get_entry
```
```
In fs/fat/fatent.c (ffffffff81473845)
Location: fs/fat/fat.h:159
Inline: True
Inline callers:
  - fs/fat/fatent.c:fat_count_free_clusters
  - fs/fat/fatent.c:fat_free_clusters
  - fs/fat/fatent.c:fat_alloc_clusters
  - fs/fat/fatent.c:fat_ent_access_init
```
```
In fs/fat/inode.c (ffffffff81476acc)
Location: fs/fat/fat.h:159
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_read_root
  - fs/fat/inode.c:fat_set_state
  - fs/fat/inode.c:fat_fill_inode
  - fs/fat/inode.c:fat_fill_inode
```
```
In fs/fat/misc.c (ffffffff81478057)
Location: fs/fat/fat.h:159
Inline: True
Inline callers:
  - fs/fat/misc.c:fat_clusters_flush
```
```
In fs/fat/nfs.c (ffffffff814786c8)
Location: fs/fat/fat.h:159
Inline: True
Inline callers:
  - fs/fat/nfs.c:fat_get_parent
  - fs/fat/nfs.c:fat_rebuild_parent
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/fat/cache.c (ffffffff81474424)
Location: fs/fat/fat.h:159
Inline: True
Inline callers:
  - fs/fat/cache.c:fat_bmap
```
```
In fs/fat/dir.c (ffffffff81475c4f)
Location: fs/fat/fat.h:159
Inline: True
Inline callers:
  - fs/fat/dir.c:fat_add_entries
  - fs/fat/dir.c:fat_scan_logstart
  - fs/fat/dir.c:fat__get_entry
```
```
In fs/fat/fatent.c (ffffffff81479295)
Location: fs/fat/fat.h:159
Inline: True
Inline callers:
  - fs/fat/fatent.c:fat_count_free_clusters
  - fs/fat/fatent.c:fat_free_clusters
  - fs/fat/fatent.c:fat_alloc_clusters
  - fs/fat/fatent.c:fat_ent_access_init
```
```
In fs/fat/inode.c (ffffffff8147c543)
Location: fs/fat/fat.h:159
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_read_root
  - fs/fat/inode.c:fat_set_state
  - fs/fat/inode.c:fat_fill_inode
  - fs/fat/inode.c:fat_fill_inode
```
```
In fs/fat/misc.c (ffffffff8147dae7)
Location: fs/fat/fat.h:159
Inline: True
Inline callers:
  - fs/fat/misc.c:fat_clusters_flush
```
```
In fs/fat/nfs.c (ffffffff8147e138)
Location: fs/fat/fat.h:159
Inline: True
Inline callers:
  - fs/fat/nfs.c:fat_get_parent
  - fs/fat/nfs.c:fat_rebuild_parent
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/fat/cache.c (ffffffff814cb0eb)
Location: fs/fat/fat.h:159
Inline: True
Inline callers:
  - fs/fat/cache.c:fat_bmap
```
```
In fs/fat/dir.c (ffffffff814cdd9e)
Location: fs/fat/fat.h:159
Inline: True
Inline callers:
  - fs/fat/dir.c:fat_add_entries
  - fs/fat/dir.c:fat_scan_logstart
  - fs/fat/dir.c:fat__get_entry
```
```
In fs/fat/fatent.c (ffffffff814d075d)
Location: fs/fat/fat.h:159
Inline: True
Inline callers:
  - fs/fat/fatent.c:fat_count_free_clusters
  - fs/fat/fatent.c:fat_free_clusters
  - fs/fat/fatent.c:fat_alloc_clusters
  - fs/fat/fatent.c:fat_ent_access_init
```
```
In fs/fat/inode.c (ffffffff814d3c43)
Location: fs/fat/fat.h:159
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_read_root
  - fs/fat/inode.c:fat_set_state
  - fs/fat/inode.c:fat_fill_inode
  - fs/fat/inode.c:fat_fill_inode
```
```
In fs/fat/misc.c (ffffffff814d5367)
Location: fs/fat/fat.h:159
Inline: True
Inline callers:
  - fs/fat/misc.c:fat_clusters_flush
```
```
In fs/fat/nfs.c (ffffffff814d58d8)
Location: fs/fat/fat.h:159
Inline: True
Inline callers:
  - fs/fat/nfs.c:fat_get_parent
  - fs/fat/nfs.c:fat_rebuild_parent
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/fat/cache.c (ffffffff8155718b)
Location: fs/fat/fat.h:160
Inline: True
Inline callers:
  - fs/fat/cache.c:fat_bmap
```
```
In fs/fat/dir.c (ffffffff81559e11)
Location: fs/fat/fat.h:160
Inline: True
Inline callers:
  - fs/fat/dir.c:fat_add_entries
  - fs/fat/dir.c:fat_scan_logstart
  - fs/fat/dir.c:fat__get_entry
```
```
In fs/fat/fatent.c (ffffffff8155d290)
Location: fs/fat/fat.h:160
Inline: True
Inline callers:
  - fs/fat/fatent.c:fat_count_free_clusters
  - fs/fat/fatent.c:fat_free_clusters
  - fs/fat/fatent.c:fat_alloc_clusters
  - fs/fat/fatent.c:fat_ent_access_init
```
```
In fs/fat/inode.c (ffffffff81560e7f)
Location: fs/fat/fat.h:160
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_read_root
  - fs/fat/inode.c:fat_set_state
  - fs/fat/inode.c:fat_fill_inode
  - fs/fat/inode.c:fat_fill_inode
```
```
In fs/fat/misc.c (ffffffff81562385)
Location: fs/fat/fat.h:160
Inline: True
Inline callers:
  - fs/fat/misc.c:fat_clusters_flush
```
```
In fs/fat/nfs.c (ffffffff81562a02)
Location: fs/fat/fat.h:160
Inline: True
Inline callers:
  - fs/fat/nfs.c:fat_get_parent
  - fs/fat/nfs.c:fat_rebuild_parent
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
In fs/fat/cache.c (ffffffff815f8d4b)
Location: fs/fat/fat.h:160
Inline: True
Inline callers:
  - fs/fat/cache.c:fat_bmap
```
```
In fs/fat/dir.c (ffffffff815fcf47)
Location: fs/fat/fat.h:160
Inline: True
Inline callers:
  - fs/fat/dir.c:fat_add_entries
  - fs/fat/dir.c:fat_scan_logstart
  - fs/fat/dir.c:fat__get_entry
```
```
In fs/fat/fatent.c (ffffffff815ff2d0)
Location: fs/fat/fat.h:160
Inline: True
Inline callers:
  - fs/fat/fatent.c:fat_count_free_clusters
  - fs/fat/fatent.c:fat_free_clusters
  - fs/fat/fatent.c:fat_alloc_clusters
  - fs/fat/fatent.c:fat_ent_access_init
```
```
In fs/fat/inode.c (ffffffff8160312f)
Location: fs/fat/fat.h:160
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_set_state
  - fs/fat/inode.c:fat_fill_inode
  - fs/fat/inode.c:fat_fill_inode
```
```
In fs/fat/misc.c (ffffffff81604cd5)
Location: fs/fat/fat.h:160
Inline: True
Inline callers:
  - fs/fat/misc.c:fat_clusters_flush
```
```
In fs/fat/nfs.c (ffffffff81605432)
Location: fs/fat/fat.h:160
Inline: True
Inline callers:
  - fs/fat/nfs.c:fat_get_parent
  - fs/fat/nfs.c:fat_rebuild_parent
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
In fs/fat/cache.c (ffffffff81630cc7)
Location: fs/fat/fat.h:160
Inline: True
Inline callers:
  - fs/fat/cache.c:fat_bmap
```
```
In fs/fat/dir.c (ffffffff81634dba)
Location: fs/fat/fat.h:160
Inline: True
Inline callers:
  - fs/fat/dir.c:fat_add_entries
  - fs/fat/dir.c:fat_scan_logstart
  - fs/fat/dir.c:fat__get_entry
```
```
In fs/fat/fatent.c (ffffffff816372b0)
Location: fs/fat/fat.h:160
Inline: True
Inline callers:
  - fs/fat/fatent.c:fat_count_free_clusters
  - fs/fat/fatent.c:fat_free_clusters
  - fs/fat/fatent.c:fat_alloc_clusters
  - fs/fat/fatent.c:fat_ent_access_init
```
```
In fs/fat/inode.c (ffffffff8163b04f)
Location: fs/fat/fat.h:160
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_set_state
  - fs/fat/inode.c:fat_fill_inode
  - fs/fat/inode.c:fat_fill_inode
```
```
In fs/fat/misc.c (ffffffff8163cbe5)
Location: fs/fat/fat.h:160
Inline: True
Inline callers:
  - fs/fat/misc.c:fat_clusters_flush
```
```
In fs/fat/nfs.c (ffffffff8163d342)
Location: fs/fat/fat.h:160
Inline: True
Inline callers:
  - fs/fat/nfs.c:fat_get_parent
  - fs/fat/nfs.c:fat_rebuild_parent
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
In fs/fat/cache.c (ffffffff8166a177)
Location: fs/fat/fat.h:160
Inline: True
Inline callers:
  - fs/fat/cache.c:fat_bmap
```
```
In fs/fat/dir.c (ffffffff8166e29a)
Location: fs/fat/fat.h:160
Inline: True
Inline callers:
  - fs/fat/dir.c:fat_add_entries
  - fs/fat/dir.c:fat_scan_logstart
  - fs/fat/dir.c:fat__get_entry
```
```
In fs/fat/fatent.c (ffffffff816707a0)
Location: fs/fat/fat.h:160
Inline: True
Inline callers:
  - fs/fat/fatent.c:fat_count_free_clusters
  - fs/fat/fatent.c:fat_free_clusters
  - fs/fat/fatent.c:fat_alloc_clusters
  - fs/fat/fatent.c:fat_ent_access_init
```
```
In fs/fat/inode.c (ffffffff816745ae)
Location: fs/fat/fat.h:160
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_set_state
  - fs/fat/inode.c:fat_fill_inode
  - fs/fat/inode.c:fat_fill_inode
```
```
In fs/fat/misc.c (ffffffff81676155)
Location: fs/fat/fat.h:160
Inline: True
Inline callers:
  - fs/fat/misc.c:fat_clusters_flush
```
```
In fs/fat/nfs.c (ffffffff816768b2)
Location: fs/fat/fat.h:160
Inline: True
Inline callers:
  - fs/fat/nfs.c:fat_get_parent
  - fs/fat/nfs.c:fat_rebuild_parent
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
In fs/fat/cache.c (0)
Location: fs/fat/fat.h:159
Inline: True
```
```
In fs/fat/dir.c (0)
Location: fs/fat/fat.h:159
Inline: True
```
```
In fs/fat/fatent.c (0)
Location: fs/fat/fat.h:159
Inline: True
```
```
In fs/fat/inode.c (0)
Location: fs/fat/fat.h:159
Inline: True
```
```
In fs/fat/misc.c (0)
Location: fs/fat/fat.h:159
Inline: True
```
```
In fs/fat/nfs.c (0)
Location: fs/fat/fat.h:159
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
In fs/fat/cache.c (c06a28ac)
Location: fs/fat/fat.h:159
Inline: True
Inline callers:
  - fs/fat/cache.c:fat_bmap
```
```
In fs/fat/dir.c (c06a4500)
Location: fs/fat/fat.h:159
Inline: True
Inline callers:
  - fs/fat/dir.c:fat_add_entries
  - fs/fat/dir.c:fat_scan_logstart
  - fs/fat/dir.c:fat__get_entry
```
```
In fs/fat/fatent.c (c06a6870)
Location: fs/fat/fat.h:159
Inline: True
Inline callers:
  - fs/fat/fatent.c:mark_fsinfo_dirty
  - fs/fat/fatent.c:fat_ent_access_init
```
```
In fs/fat/inode.c (c06ab244)
Location: fs/fat/fat.h:159
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_set_state
  - fs/fat/inode.c:fat_fill_inode
  - fs/fat/inode.c:fat_fill_inode
```
```
In fs/fat/misc.c (c06aca18)
Location: fs/fat/fat.h:159
Inline: True
Inline callers:
  - fs/fat/misc.c:fat_clusters_flush
```
```
In fs/fat/nfs.c (c06ad170)
Location: fs/fat/fat.h:159
Inline: True
Inline callers:
  - fs/fat/nfs.c:fat_get_parent
  - fs/fat/nfs.c:fat_get_parent
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
In fs/fat/cache.c (c000000000620988)
Location: fs/fat/fat.h:159
Inline: True
Inline callers:
  - fs/fat/cache.c:fat_bmap
```
```
In fs/fat/dir.c (c000000000622d40)
Location: fs/fat/fat.h:159
Inline: True
Inline callers:
  - fs/fat/dir.c:fat_add_entries
  - fs/fat/dir.c:fat_scan_logstart
  - fs/fat/dir.c:fat__get_entry
```
```
In fs/fat/fatent.c (c000000000626640)
Location: fs/fat/fat.h:159
Inline: True
Inline callers:
  - fs/fat/fatent.c:mark_fsinfo_dirty
  - fs/fat/fatent.c:fat_ent_access_init
```
```
In fs/fat/inode.c (c00000000062c2ec)
Location: fs/fat/fat.h:159
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_set_state
  - fs/fat/inode.c:fat_fill_inode
  - fs/fat/inode.c:fat_fill_inode
```
```
In fs/fat/misc.c (c00000000062e05c)
Location: fs/fat/fat.h:159
Inline: True
Inline callers:
  - fs/fat/misc.c:fat_clusters_flush
```
```
In fs/fat/nfs.c (c00000000062ea0c)
Location: fs/fat/fat.h:159
Inline: True
Inline callers:
  - fs/fat/nfs.c:fat_get_parent
  - fs/fat/nfs.c:fat_get_parent
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
In fs/fat/cache.c (ffffffe000356e2e)
Location: fs/fat/fat.h:159
Inline: True
Inline callers:
  - fs/fat/cache.c:fat_bmap
```
```
In fs/fat/dir.c (ffffffe000358372)
Location: fs/fat/fat.h:159
Inline: True
Inline callers:
  - fs/fat/dir.c:fat_add_entries
  - fs/fat/dir.c:fat_scan_logstart
  - fs/fat/dir.c:fat__get_entry
```
```
In fs/fat/fatent.c (ffffffe000359f14)
Location: fs/fat/fat.h:159
Inline: True
Inline callers:
  - fs/fat/fatent.c:mark_fsinfo_dirty
  - fs/fat/fatent.c:fat_ent_access_init
```
```
In fs/fat/inode.c (ffffffe00035dab8)
Location: fs/fat/fat.h:159
Inline: True
Inline callers:
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_fill_super
  - fs/fat/inode.c:fat_set_state
  - fs/fat/inode.c:fat_fill_inode
  - fs/fat/inode.c:fat_fill_inode
```
```
In fs/fat/misc.c (ffffffe00035ef9c)
Location: fs/fat/fat.h:159
Inline: True
Inline callers:
  - fs/fat/misc.c:fat_clusters_flush
```
```
In fs/fat/nfs.c (ffffffe00035f95a)
Location: fs/fat/fat.h:159
Inline: True
Inline callers:
  - fs/fat/nfs.c:fat_get_parent
  - fs/fat/nfs.c:fat_get_parent
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
In fs/fat/cache.c (0)
Location: fs/fat/fat.h:159
Inline: True
```
```
In fs/fat/dir.c (0)
Location: fs/fat/fat.h:159
Inline: True
```
```
In fs/fat/fatent.c (0)
Location: fs/fat/fat.h:159
Inline: True
```
```
In fs/fat/inode.c (0)
Location: fs/fat/fat.h:159
Inline: True
```
```
In fs/fat/misc.c (0)
Location: fs/fat/fat.h:159
Inline: True
```
```
In fs/fat/nfs.c (0)
Location: fs/fat/fat.h:159
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
In fs/fat/cache.c (0)
Location: fs/fat/fat.h:159
Inline: True
```
```
In fs/fat/dir.c (0)
Location: fs/fat/fat.h:159
Inline: True
```
```
In fs/fat/fatent.c (0)
Location: fs/fat/fat.h:159
Inline: True
```
```
In fs/fat/inode.c (0)
Location: fs/fat/fat.h:159
Inline: True
```
```
In fs/fat/misc.c (0)
Location: fs/fat/fat.h:159
Inline: True
```
```
In fs/fat/nfs.c (0)
Location: fs/fat/fat.h:159
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
In fs/fat/cache.c (0)
Location: fs/fat/fat.h:159
Inline: True
```
```
In fs/fat/dir.c (0)
Location: fs/fat/fat.h:159
Inline: True
```
```
In fs/fat/fatent.c (0)
Location: fs/fat/fat.h:159
Inline: True
```
```
In fs/fat/inode.c (0)
Location: fs/fat/fat.h:159
Inline: True
```
```
In fs/fat/misc.c (0)
Location: fs/fat/fat.h:159
Inline: True
```
```
In fs/fat/nfs.c (0)
Location: fs/fat/fat.h:159
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
In fs/fat/cache.c (0)
Location: fs/fat/fat.h:159
Inline: True
```
```
In fs/fat/dir.c (0)
Location: fs/fat/fat.h:159
Inline: True
```
```
In fs/fat/fatent.c (0)
Location: fs/fat/fat.h:159
Inline: True
```
```
In fs/fat/inode.c (0)
Location: fs/fat/fat.h:159
Inline: True
```
```
In fs/fat/misc.c (0)
Location: fs/fat/fat.h:159
Inline: True
```
```
In fs/fat/nfs.c (0)
Location: fs/fat/fat.h:159
Inline: True
```
</details>
</li>
</ul>

## Differences
