# Function: <code>dm_process_bio</code>

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
<summary>In <code>5.0</code>: ✅</summary>

```c
blk_qc_t dm_process_bio(struct mapped_device *md, struct dm_table *map, struct bio *bio);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffff81834c10)
Location: drivers/md/dm.c:1733
Inline: False
Direct callers:
  - drivers/md/dm.c:dm_wq_work
  - drivers/md/dm.c:dm_make_request
```
**Symbols:**

```
ffffffff81834c10-ffffffff81834c30: dm_process_bio (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
blk_qc_t dm_process_bio(struct mapped_device *md, struct dm_table *map, struct bio *bio);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffff81876b70)
Location: drivers/md/dm.c:1738
Inline: False
Direct callers:
  - drivers/md/dm.c:dm_wq_work
  - drivers/md/dm.c:dm_make_request
```
**Symbols:**

```
ffffffff81876b70-ffffffff81876d9d: dm_process_bio (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
blk_qc_t dm_process_bio(struct mapped_device *md, struct dm_table *map, struct bio *bio);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffff818a8a90)
Location: drivers/md/dm.c:1738
Inline: False
Direct callers:
  - drivers/md/dm.c:dm_wq_work
  - drivers/md/dm.c:dm_make_request
```
**Symbols:**

```
ffffffff818a8a90-ffffffff818a8cb7: dm_process_bio (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
blk_qc_t dm_process_bio(struct mapped_device *md, struct dm_table *map, struct bio *bio);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffff81979760)
Location: drivers/md/dm.c:1731
Inline: False
Direct callers:
  - drivers/md/dm.c:dm_wq_work
  - drivers/md/dm.c:dm_make_request
```
**Symbols:**

```
ffffffff81979760-ffffffff8197985c: dm_process_bio (STB_LOCAL)
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
blk_qc_t dm_process_bio(struct mapped_device *md, struct dm_table *map, struct bio *bio);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffff800010aff418)
Location: drivers/md/dm.c:1738
Inline: False
Direct callers:
  - drivers/md/dm.c:dm_wq_work
  - drivers/md/dm.c:dm_make_request
```
**Symbols:**

```
ffff800010aff418-ffff800010aff640: dm_process_bio (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
blk_qc_t dm_process_bio(struct mapped_device *md, struct dm_table *map, struct bio *bio);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (c0bde900)
Location: drivers/md/dm.c:1738
Inline: False
Direct callers:
  - drivers/md/dm.c:dm_wq_work
  - drivers/md/dm.c:dm_make_request
```
**Symbols:**

```
c0bde900-c0bdeb24: dm_process_bio (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
blk_qc_t dm_process_bio(struct mapped_device *md, struct dm_table *map, struct bio *bio);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (c000000000bed940)
Location: drivers/md/dm.c:1738
Inline: False
Direct callers:
  - drivers/md/dm.c:dm_wq_work
  - drivers/md/dm.c:dm_make_request
```
**Symbols:**

```
c000000000bed940-c000000000bedc50: dm_process_bio (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
blk_qc_t dm_process_bio(struct mapped_device *md, struct dm_table *map, struct bio *bio);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffe0006eecc8)
Location: drivers/md/dm.c:1738
Inline: False
Direct callers:
  - drivers/md/dm.c:dm_wq_work
  - drivers/md/dm.c:dm_make_request
```
**Symbols:**

```
ffffffe0006eecc8-ffffffe0006eeeac: dm_process_bio (STB_LOCAL)
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
blk_qc_t dm_process_bio(struct mapped_device *md, struct dm_table *map, struct bio *bio);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffff8184e910)
Location: drivers/md/dm.c:1738
Inline: False
Direct callers:
  - drivers/md/dm.c:dm_wq_work
  - drivers/md/dm.c:dm_make_request
```
**Symbols:**

```
ffffffff8184e910-ffffffff8184eb37: dm_process_bio (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
blk_qc_t dm_process_bio(struct mapped_device *md, struct dm_table *map, struct bio *bio);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffff81815f30)
Location: drivers/md/dm.c:1738
Inline: False
Direct callers:
  - drivers/md/dm.c:dm_wq_work
  - drivers/md/dm.c:dm_make_request
```
**Symbols:**

```
ffffffff81815f30-ffffffff81816157: dm_process_bio (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
blk_qc_t dm_process_bio(struct mapped_device *md, struct dm_table *map, struct bio *bio);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffff8189df40)
Location: drivers/md/dm.c:1738
Inline: False
Direct callers:
  - drivers/md/dm.c:dm_wq_work
  - drivers/md/dm.c:dm_make_request
```
**Symbols:**

```
ffffffff8189df40-ffffffff8189e167: dm_process_bio (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
blk_qc_t dm_process_bio(struct mapped_device *md, struct dm_table *map, struct bio *bio);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffff818badd0)
Location: drivers/md/dm.c:1738
Inline: False
Direct callers:
  - drivers/md/dm.c:dm_wq_work
  - drivers/md/dm.c:dm_make_request
```
**Symbols:**

```
ffffffff818badd0-ffffffff818bb00e: dm_process_bio (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
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
