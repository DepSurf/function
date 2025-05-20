# Function: <code>__process_bio</code>

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
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
blk_qc_t __process_bio(struct mapped_device *md, struct dm_table *map, struct bio *bio);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffff81808890)
Location: drivers/md/dm.c:1627
Inline: False
```
**Symbols:**

```
ffffffff81808890-ffffffff818089ea: __process_bio (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
blk_qc_t __process_bio(struct mapped_device *md, struct dm_table *map, struct bio *bio);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffff81834a50)
Location: drivers/md/dm.c:1678
Inline: False
Direct callers:
  - drivers/md/dm.c:dm_process_bio
```
**Symbols:**

```
ffffffff81834a50-ffffffff81834c03: __process_bio (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
blk_qc_t __process_bio(struct mapped_device *md, struct dm_table *map, struct bio *bio, struct dm_target *ti);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffff818767e0)
Location: drivers/md/dm.c:1681
Inline: False
Direct callers:
  - drivers/md/dm.c:dm_process_bio
```
**Symbols:**

```
ffffffff818767e0-ffffffff8187693e: __process_bio (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
blk_qc_t __process_bio(struct mapped_device *md, struct dm_table *map, struct bio *bio, struct dm_target *ti);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffff818a85e0)
Location: drivers/md/dm.c:1681
Inline: False
Direct callers:
  - drivers/md/dm.c:dm_process_bio
```
**Symbols:**

```
ffffffff818a85e0-ffffffff818a873e: __process_bio (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
blk_qc_t __process_bio(struct mapped_device *md, struct dm_table *map, struct bio *bio, struct dm_target *ti);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffff81979180)
Location: drivers/md/dm.c:1690
Inline: False
Direct callers:
  - drivers/md/dm.c:dm_process_bio
```
**Symbols:**

```
ffffffff81979180-ffffffff81979340: __process_bio (STB_LOCAL)
```
</details>
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
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
blk_qc_t __process_bio(struct mapped_device *md, struct dm_table *map, struct bio *bio, struct dm_target *ti);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffff800010aff048)
Location: drivers/md/dm.c:1681
Inline: False
Direct callers:
  - drivers/md/dm.c:dm_process_bio
```
**Symbols:**

```
ffff800010aff048-ffff800010aff194: __process_bio (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
blk_qc_t __process_bio(struct mapped_device *md, struct dm_table *map, struct bio *bio, struct dm_target *ti);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (c0bde234)
Location: drivers/md/dm.c:1681
Inline: False
Direct callers:
  - drivers/md/dm.c:dm_process_bio
```
**Symbols:**

```
c0bde234-c0bde378: __process_bio (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
blk_qc_t __process_bio(struct mapped_device *md, struct dm_table *map, struct bio *bio, struct dm_target *ti);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (c000000000bed3c0)
Location: drivers/md/dm.c:1681
Inline: False
Direct callers:
  - drivers/md/dm.c:dm_process_bio
```
**Symbols:**

```
c000000000bed3c0-c000000000bed554: __process_bio (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
blk_qc_t __process_bio(struct mapped_device *md, struct dm_table *map, struct bio *bio, struct dm_target *ti);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffe0006eea46)
Location: drivers/md/dm.c:1681
Inline: False
Direct callers:
  - drivers/md/dm.c:dm_process_bio
```
**Symbols:**

```
ffffffe0006eea46-ffffffe0006eeb5c: __process_bio (STB_LOCAL)
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
blk_qc_t __process_bio(struct mapped_device *md, struct dm_table *map, struct bio *bio, struct dm_target *ti);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffff8184e460)
Location: drivers/md/dm.c:1681
Inline: False
Direct callers:
  - drivers/md/dm.c:dm_process_bio
```
**Symbols:**

```
ffffffff8184e460-ffffffff8184e5be: __process_bio (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
blk_qc_t __process_bio(struct mapped_device *md, struct dm_table *map, struct bio *bio, struct dm_target *ti);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffff81815a80)
Location: drivers/md/dm.c:1681
Inline: False
Direct callers:
  - drivers/md/dm.c:dm_process_bio
```
**Symbols:**

```
ffffffff81815a80-ffffffff81815bde: __process_bio (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
blk_qc_t __process_bio(struct mapped_device *md, struct dm_table *map, struct bio *bio, struct dm_target *ti);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffff8189da90)
Location: drivers/md/dm.c:1681
Inline: False
Direct callers:
  - drivers/md/dm.c:dm_process_bio
```
**Symbols:**

```
ffffffff8189da90-ffffffff8189dbee: __process_bio (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
blk_qc_t __process_bio(struct mapped_device *md, struct dm_table *map, struct bio *bio, struct dm_target *ti);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffff818b9e40)
Location: drivers/md/dm.c:1681
Inline: False
Direct callers:
  - drivers/md/dm.c:dm_process_bio
```
**Symbols:**

```
ffffffff818b9e40-ffffffff818b9f9e: __process_bio (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.0</code> and <code>5.3</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct dm_target *ti</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
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
