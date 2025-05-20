# Function: <code>__blk_alloc_disk</code>

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
<summary>In <code>5.15</code>: ✅</summary>

```c
struct gendisk *__blk_alloc_disk(int node, struct lock_class_key *lkclass);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/genhd.c (ffffffff815e3f50)
Location: block/genhd.c:1330
Inline: False
Direct callers:
  - drivers/md/md.c:md_alloc
  - drivers/md/md.c:md_alloc
  - drivers/md/dm.c:alloc_dev
```
**Symbols:**

```
ffffffff815e3f50-ffffffff815e3fb5: __blk_alloc_disk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct gendisk *__blk_alloc_disk(int node, struct lock_class_key *lkclass);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/genhd.c (ffffffff81693240)
Location: block/genhd.c:1396
Inline: False
Direct callers:
  - drivers/md/md.c:md_alloc
  - drivers/md/md.c:md_alloc
  - drivers/md/dm.c:alloc_dev
```
**Symbols:**

```
ffffffff81693240-ffffffff81693293: __blk_alloc_disk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct gendisk *__blk_alloc_disk(int node, struct lock_class_key *lkclass);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/genhd.c (ffffffff817529e0)
Location: block/genhd.c:1418
Inline: False
Direct callers:
  - drivers/md/md.c:md_alloc
  - drivers/md/dm.c:alloc_dev
```
**Symbols:**

```
ffffffff817529e0-ffffffff81752a39: __blk_alloc_disk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct gendisk *__blk_alloc_disk(int node, struct lock_class_key *lkclass);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/genhd.c (ffffffff8178eba0)
Location: block/genhd.c:1381
Inline: False
Direct callers:
  - drivers/md/md.c:md_alloc
  - drivers/md/dm.c:alloc_dev
```
**Symbols:**

```
ffffffff8178eba0-ffffffff8178ebf9: __blk_alloc_disk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct gendisk *__blk_alloc_disk(int node, struct lock_class_key *lkclass);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/genhd.c (ffffffff817d1490)
Location: block/genhd.c:1394
Inline: False
Direct callers:
  - drivers/md/md.c:md_alloc
  - drivers/md/dm.c:alloc_dev
```
**Symbols:**

```
ffffffff817d1490-ffffffff817d14e9: __blk_alloc_disk (STB_GLOBAL)
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
