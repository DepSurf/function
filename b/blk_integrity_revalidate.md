# Function: <code>blk_integrity_revalidate</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
void blk_integrity_revalidate(struct gendisk *disk);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-integrity.c (ffffffff813e7b95)
Location: block/blk-integrity.c:438
Inline: True
Inline callers:
  - block/blk-integrity.c:blk_integrity_register
  - block/blk-integrity.c:blk_integrity_unregister
Direct callers:
  - fs/block_dev.c:revalidate_disk
  - block/partition-generic.c:rescan_partitions
```
**Symbols:**

```
ffffffff813e8740-ffffffff813e8775: blk_integrity_revalidate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void blk_integrity_revalidate(struct gendisk *disk);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-integrity.c (ffffffff8142e2d5)
Location: block/blk-integrity.c:438
Inline: True
Inline callers:
  - block/blk-integrity.c:blk_integrity_unregister
  - block/blk-integrity.c:blk_integrity_register
Direct callers:
  - fs/block_dev.c:revalidate_disk
  - block/partition-generic.c:rescan_partitions
```
**Symbols:**

```
ffffffff8142e9a0-ffffffff8142e9d5: blk_integrity_revalidate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void blk_integrity_revalidate(struct gendisk *disk);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-integrity.c (ffffffff81448075)
Location: block/blk-integrity.c:438
Inline: True
Inline callers:
  - block/blk-integrity.c:blk_integrity_unregister
  - block/blk-integrity.c:blk_integrity_register
Direct callers:
  - fs/block_dev.c:revalidate_disk
  - block/partition-generic.c:rescan_partitions
```
**Symbols:**

```
ffffffff81448720-ffffffff81448755: blk_integrity_revalidate (STB_GLOBAL)
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
