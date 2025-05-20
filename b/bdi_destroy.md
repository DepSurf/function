# Function: <code>bdi_destroy</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
void bdi_destroy(struct backing_dev_info *bdi);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/backing-dev.c (ffffffff811afa20)
Location: mm/backing-dev.c:860
Inline: True
Direct callers:
  - fs/ecryptfs/main.c:ecryptfs_kill_block_super
  - fs/fuse/inode.c:fuse_put_super
  - fs/fuse/inode.c:fuse_fill_super
  - block/blk-core.c:blk_alloc_queue_node
```
**Symbols:**

```
ffffffff811afa20-ffffffff811afa3d: bdi_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void bdi_destroy(struct backing_dev_info *bdi);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/backing-dev.c (ffffffff811c8ec0)
Location: mm/backing-dev.c:879
Inline: True
Direct callers:
  - fs/ecryptfs/main.c:ecryptfs_kill_block_super
  - fs/fuse/inode.c:fuse_fill_super
  - fs/fuse/inode.c:fuse_put_super
  - block/blk-core.c:blk_alloc_queue_node
```
**Symbols:**

```
ffffffff811c8ec0-ffffffff811c8edd: bdi_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void bdi_destroy(struct backing_dev_info *bdi);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/backing-dev.c (ffffffff811d8fa0)
Location: mm/backing-dev.c:885
Inline: True
Direct callers:
  - fs/ecryptfs/main.c:ecryptfs_kill_block_super
  - fs/fuse/inode.c:fuse_fill_super
  - fs/fuse/inode.c:fuse_put_super
  - block/blk-core.c:blk_alloc_queue_node
```
**Symbols:**

```
ffffffff811d8fa0-ffffffff811d8fbd: bdi_destroy (STB_GLOBAL)
```
</details>
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
In <code>5.15</code>: Absent ⚠️
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
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
</ul>
