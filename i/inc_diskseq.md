# Function: <code>inc_diskseq</code>

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
void inc_diskseq(struct gendisk *disk);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/genhd.c (ffffffff815e3ea7)
Location: block/genhd.c:1419
Inline: True
Inline callers:
  - block/genhd.c:__alloc_disk_node
Direct callers:
  - block/disk-events.c:disk_check_events
```
**Symbols:**

```
ffffffff815e4a10-ffffffff815e4a34: inc_diskseq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void inc_diskseq(struct gendisk *disk);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/genhd.c (ffffffff81693182)
Location: block/genhd.c:1479
Inline: True
Inline callers:
  - block/genhd.c:__alloc_disk_node
Direct callers:
  - block/disk-events.c:disk_check_events
```
**Symbols:**

```
ffffffff81693ad0-ffffffff81693afc: inc_diskseq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void inc_diskseq(struct gendisk *disk);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/genhd.c (ffffffff8175291b)
Location: block/genhd.c:1489
Inline: True
Inline callers:
  - block/genhd.c:__alloc_disk_node
Direct callers:
  - block/disk-events.c:disk_check_events
```
**Symbols:**

```
ffffffff81752a50-ffffffff81752a7c: inc_diskseq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void inc_diskseq(struct gendisk *disk);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/genhd.c (ffffffff8178eade)
Location: block/genhd.c:1452
Inline: True
Inline callers:
  - block/genhd.c:__alloc_disk_node
Direct callers:
  - block/disk-events.c:disk_check_events
```
**Symbols:**

```
ffffffff8178ec10-ffffffff8178ec3c: inc_diskseq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void inc_diskseq(struct gendisk *disk);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/genhd.c (ffffffff817d13cd)
Location: block/genhd.c:1465
Inline: True
Inline callers:
  - block/genhd.c:__alloc_disk_node
Direct callers:
  - block/disk-events.c:disk_force_media_change
  - block/disk-events.c:disk_check_events
```
**Symbols:**

```
ffffffff817d1500-ffffffff817d152c: inc_diskseq (STB_GLOBAL)
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
