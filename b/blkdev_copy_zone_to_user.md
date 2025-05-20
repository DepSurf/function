# Function: <code>blkdev_copy_zone_to_user</code>

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
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int blkdev_copy_zone_to_user(struct blk_zone *zone, unsigned int idx, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-zoned.c (ffffffff81578920)
Location: block/blk-zoned.c:266
Inline: False
```
**Symbols:**

```
ffffffff81578920-ffffffff8157894f: blkdev_copy_zone_to_user (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int blkdev_copy_zone_to_user(struct blk_zone *zone, unsigned int idx, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-zoned.c (ffffffff81595170)
Location: block/blk-zoned.c:266
Inline: False
```
**Symbols:**

```
ffffffff81595170-ffffffff8159519f: blkdev_copy_zone_to_user (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int blkdev_copy_zone_to_user(struct blk_zone *zone, unsigned int idx, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-zoned.c (ffffffff8159bf30)
Location: block/blk-zoned.c:258
Inline: False
```
**Symbols:**

```
ffffffff8159bf30-ffffffff8159bf5c: blkdev_copy_zone_to_user (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int blkdev_copy_zone_to_user(struct blk_zone *zone, unsigned int idx, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-zoned.c (ffffffff81604310)
Location: block/blk-zoned.c:330
Inline: False
```
**Symbols:**

```
ffffffff81604310-ffffffff8160433c: blkdev_copy_zone_to_user (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int blkdev_copy_zone_to_user(struct blk_zone *zone, unsigned int idx, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-zoned.c (ffffffff816b7a50)
Location: block/blk-zoned.c:323
Inline: False
```
**Symbols:**

```
ffffffff816b7a50-ffffffff816b7a86: blkdev_copy_zone_to_user (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int blkdev_copy_zone_to_user(struct blk_zone *zone, unsigned int idx, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-zoned.c (ffffffff81777b90)
Location: block/blk-zoned.c:318
Inline: False
```
**Symbols:**

```
ffffffff81777b90-ffffffff81777bc6: blkdev_copy_zone_to_user (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int blkdev_copy_zone_to_user(struct blk_zone *zone, unsigned int idx, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-zoned.c (ffffffff817b7720)
Location: block/blk-zoned.c:312
Inline: False
```
**Symbols:**

```
ffffffff817b7720-ffffffff817b7756: blkdev_copy_zone_to_user (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int blkdev_copy_zone_to_user(struct blk_zone *zone, unsigned int idx, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-zoned.c (ffffffff817fc000)
Location: block/blk-zoned.c:312
Inline: False
```
**Symbols:**

```
ffffffff817fc000-ffffffff817fc036: blkdev_copy_zone_to_user (STB_LOCAL)
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
