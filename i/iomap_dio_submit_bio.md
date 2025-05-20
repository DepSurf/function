# Function: <code>iomap_dio_submit_bio</code>

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
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/iomap/direct-io.c (ffffffff8134d640)
Location: fs/iomap/direct-io.c:61
Inline: True
Direct callers:
  - fs/iomap/direct-io.c:iomap_dio_bio_actor
  - fs/iomap/direct-io.c:iomap_dio_zero
```
**Symbols:**

```
ffffffff8134d640-ffffffff8134d69b: iomap_dio_submit_bio.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/iomap/direct-io.c (ffffffff81365900)
Location: fs/iomap/direct-io.c:61
Inline: True
Direct callers:
  - fs/iomap/direct-io.c:iomap_dio_bio_actor
  - fs/iomap/direct-io.c:iomap_dio_zero
```
**Symbols:**

```
ffffffff81365900-ffffffff8136595b: iomap_dio_submit_bio.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void iomap_dio_submit_bio(struct iomap_dio *dio, struct iomap *iomap, struct bio *bio, loff_t pos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/iomap/direct-io.c (ffffffff813acd50)
Location: fs/iomap/direct-io.c:61
Inline: False
Direct callers:
  - fs/iomap/direct-io.c:iomap_dio_bio_actor
  - fs/iomap/direct-io.c:iomap_dio_zero
```
**Symbols:**

```
ffffffff813acd50-ffffffff813acddf: iomap_dio_submit_bio (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void iomap_dio_submit_bio(struct iomap_dio *dio, struct iomap *iomap, struct bio *bio, loff_t pos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/iomap/direct-io.c (ffffffff813be430)
Location: fs/iomap/direct-io.c:62
Inline: False
Direct callers:
  - fs/iomap/direct-io.c:iomap_dio_bio_actor
  - fs/iomap/direct-io.c:iomap_dio_zero
```
**Symbols:**

```
ffffffff813be430-ffffffff813be4bc: iomap_dio_submit_bio (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void iomap_dio_submit_bio(struct iomap_dio *dio, struct iomap *iomap, struct bio *bio, loff_t pos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/iomap/direct-io.c (ffffffff813c5470)
Location: fs/iomap/direct-io.c:62
Inline: False
Direct callers:
  - fs/iomap/direct-io.c:iomap_dio_bio_actor
  - fs/iomap/direct-io.c:iomap_dio_bio_actor
  - fs/iomap/direct-io.c:iomap_dio_zero
```
**Symbols:**

```
ffffffff813c5470-ffffffff813c54fc: iomap_dio_submit_bio (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void iomap_dio_submit_bio(const struct iomap_iter *iter, struct iomap_dio *dio, struct bio *bio, loff_t pos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/iomap/direct-io.c (ffffffff81415210)
Location: fs/iomap/direct-io.c:62
Inline: False
Direct callers:
  - fs/iomap/direct-io.c:iomap_dio_bio_iter
  - fs/iomap/direct-io.c:iomap_dio_bio_iter
  - fs/iomap/direct-io.c:iomap_dio_zero
```
**Symbols:**

```
ffffffff81415210-ffffffff81415295: iomap_dio_submit_bio (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void iomap_dio_submit_bio(const struct iomap_iter *iter, struct iomap_dio *dio, struct bio *bio, loff_t pos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/iomap/direct-io.c (ffffffff8148c880)
Location: fs/iomap/direct-io.c:63
Inline: False
Direct callers:
  - fs/iomap/direct-io.c:iomap_dio_bio_iter
  - fs/iomap/direct-io.c:iomap_dio_bio_iter
  - fs/iomap/direct-io.c:iomap_dio_zero
```
**Symbols:**

```
ffffffff8148c880-ffffffff8148c919: iomap_dio_submit_bio (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void iomap_dio_submit_bio(const struct iomap_iter *iter, struct iomap_dio *dio, struct bio *bio, loff_t pos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/iomap/direct-io.c (ffffffff8151fd70)
Location: fs/iomap/direct-io.c:63
Inline: False
Direct callers:
  - fs/iomap/direct-io.c:iomap_dio_bio_iter
  - fs/iomap/direct-io.c:iomap_dio_bio_iter
  - fs/iomap/direct-io.c:iomap_dio_zero
```
**Symbols:**

```
ffffffff8151fd70-ffffffff8151fe09: iomap_dio_submit_bio (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void iomap_dio_submit_bio(const struct iomap_iter *iter, struct iomap_dio *dio, struct bio *bio, loff_t pos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/iomap/direct-io.c (ffffffff81557e20)
Location: fs/iomap/direct-io.c:63
Inline: False
Direct callers:
  - fs/iomap/direct-io.c:iomap_dio_bio_iter
  - fs/iomap/direct-io.c:iomap_dio_bio_iter
  - fs/iomap/direct-io.c:iomap_dio_zero
```
**Symbols:**

```
ffffffff81557e20-ffffffff81557eba: iomap_dio_submit_bio (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void iomap_dio_submit_bio(const struct iomap_iter *iter, struct iomap_dio *dio, struct bio *bio, loff_t pos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/iomap/direct-io.c (ffffffff8158e450)
Location: fs/iomap/direct-io.c:64
Inline: False
Direct callers:
  - fs/iomap/direct-io.c:iomap_dio_bio_iter
  - fs/iomap/direct-io.c:iomap_dio_bio_iter
  - fs/iomap/direct-io.c:iomap_dio_zero
```
**Symbols:**

```
ffffffff8158e450-ffffffff8158e4ea: iomap_dio_submit_bio (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/iomap/direct-io.c (ffff80001042c748)
Location: fs/iomap/direct-io.c:61
Inline: True
Direct callers:
  - fs/iomap/direct-io.c:iomap_dio_bio_actor
  - fs/iomap/direct-io.c:iomap_dio_zero
```
**Symbols:**

```
ffff80001042c748-ffff80001042c7e8: iomap_dio_submit_bio.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void iomap_dio_submit_bio(struct iomap_dio *dio, struct iomap *iomap, struct bio *bio);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/iomap/direct-io.c (c05f5380)
Location: fs/iomap/direct-io.c:61
Inline: False
Direct callers:
  - fs/iomap/direct-io.c:iomap_dio_bio_actor
  - fs/iomap/direct-io.c:iomap_dio_zero
```
**Symbols:**

```
c05f5380-c05f5400: iomap_dio_submit_bio (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/iomap/direct-io.c (c00000000053dd90)
Location: fs/iomap/direct-io.c:61
Inline: True
Direct callers:
  - fs/iomap/direct-io.c:iomap_dio_bio_actor
  - fs/iomap/direct-io.c:iomap_dio_zero
```
**Symbols:**

```
c00000000053dd90-c00000000053de2c: iomap_dio_submit_bio.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/iomap/direct-io.c (ffffffe0002c9ba0)
Location: fs/iomap/direct-io.c:61
Inline: True
Direct callers:
  - fs/iomap/direct-io.c:iomap_dio_bio_actor
  - fs/iomap/direct-io.c:iomap_dio_zero
```
**Symbols:**

```
ffffffe0002c9ba0-ffffffe0002c9c12: iomap_dio_submit_bio.isra.0 (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/iomap/direct-io.c (ffffffff8135dee0)
Location: fs/iomap/direct-io.c:61
Inline: True
Direct callers:
  - fs/iomap/direct-io.c:iomap_dio_bio_actor
  - fs/iomap/direct-io.c:iomap_dio_zero
```
**Symbols:**

```
ffffffff8135dee0-ffffffff8135df3b: iomap_dio_submit_bio.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/iomap/direct-io.c (ffffffff8134eb80)
Location: fs/iomap/direct-io.c:61
Inline: True
Direct callers:
  - fs/iomap/direct-io.c:iomap_dio_bio_actor
  - fs/iomap/direct-io.c:iomap_dio_zero
```
**Symbols:**

```
ffffffff8134eb80-ffffffff8134ebdb: iomap_dio_submit_bio.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/iomap/direct-io.c (ffffffff8135b9b0)
Location: fs/iomap/direct-io.c:61
Inline: True
Direct callers:
  - fs/iomap/direct-io.c:iomap_dio_bio_actor
  - fs/iomap/direct-io.c:iomap_dio_zero
```
**Symbols:**

```
ffffffff8135b9b0-ffffffff8135ba0b: iomap_dio_submit_bio.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/iomap/direct-io.c (ffffffff8136f100)
Location: fs/iomap/direct-io.c:61
Inline: True
Direct callers:
  - fs/iomap/direct-io.c:iomap_dio_bio_actor
  - fs/iomap/direct-io.c:iomap_dio_zero
```
**Symbols:**

```
ffffffff8136f100-ffffffff8136f15b: iomap_dio_submit_bio.isra.0 (STB_LOCAL)
```
</details>
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
<details>
<summary>Changed between <code>5.13</code> and <code>5.15</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>const struct iomap_iter *iter</code>
</li>
<li>
<b>Param removed. </b>
<code>struct iomap *iomap</code>
</li>
<li>
<b>Param reordered. </b>
<code>dio, iomap, bio, pos</code> ➡️ <code>iter, dio, bio, pos</code>
</li>
</ul>
</details>
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
<b>Arch</b>
<ul>
</ul>
