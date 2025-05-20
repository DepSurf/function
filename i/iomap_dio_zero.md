# Function: <code>iomap_dio_zero</code>

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
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
blk_qc_t iomap_dio_zero(struct iomap_dio *dio, struct iomap *iomap, loff_t pos, unsigned int len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/iomap.c (ffffffff812b0b10)
Location: fs/iomap.c:712
Inline: False
Direct callers:
  - fs/iomap.c:iomap_dio_actor
  - fs/iomap.c:iomap_dio_actor
```
**Symbols:**

```
ffffffff812b0b10-ffffffff812b0c20: iomap_dio_zero (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
blk_qc_t iomap_dio_zero(struct iomap_dio *dio, struct iomap *iomap, loff_t pos, unsigned int len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/iomap.c (ffffffff812bdf20)
Location: fs/iomap.c:801
Inline: False
Direct callers:
  - fs/iomap.c:iomap_dio_actor
  - fs/iomap.c:iomap_dio_actor
```
**Symbols:**

```
ffffffff812bdf20-ffffffff812be013: iomap_dio_zero (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
blk_qc_t iomap_dio_zero(struct iomap_dio *dio, struct iomap *iomap, loff_t pos, unsigned int len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/iomap.c (ffffffff812e17f0)
Location: fs/iomap.c:825
Inline: False
Direct callers:
  - fs/iomap.c:iomap_dio_actor
  - fs/iomap.c:iomap_dio_actor
```
**Symbols:**

```
ffffffff812e17f0-ffffffff812e1915: iomap_dio_zero (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
blk_qc_t iomap_dio_zero(struct iomap_dio *dio, struct iomap *iomap, loff_t pos, unsigned int len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/iomap.c (ffffffff8130df10)
Location: fs/iomap.c:945
Inline: False
Direct callers:
  - fs/iomap.c:iomap_dio_actor
  - fs/iomap.c:iomap_dio_actor
```
**Symbols:**

```
ffffffff8130df10-ffffffff8130e026: iomap_dio_zero (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
blk_qc_t iomap_dio_zero(struct iomap_dio *dio, struct iomap *iomap, loff_t pos, unsigned int len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/iomap.c (ffffffff81323630)
Location: fs/iomap.c:1579
Inline: False
Direct callers:
  - fs/iomap.c:iomap_dio_bio_actor
  - fs/iomap.c:iomap_dio_bio_actor
```
**Symbols:**

```
ffffffff81323630-ffffffff81323767: iomap_dio_zero (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void iomap_dio_zero(struct iomap_dio *dio, struct iomap *iomap, loff_t pos, unsigned int len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/iomap/direct-io.c (ffffffff8134d6a0)
Location: fs/iomap/direct-io.c:182
Inline: False
Direct callers:
  - fs/iomap/direct-io.c:iomap_dio_bio_actor
  - fs/iomap/direct-io.c:iomap_dio_bio_actor
```
**Symbols:**

```
ffffffff8134d6a0-ffffffff8134d7ba: iomap_dio_zero (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void iomap_dio_zero(struct iomap_dio *dio, struct iomap *iomap, loff_t pos, unsigned int len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/iomap/direct-io.c (ffffffff81365960)
Location: fs/iomap/direct-io.c:178
Inline: False
Direct callers:
  - fs/iomap/direct-io.c:iomap_dio_bio_actor
  - fs/iomap/direct-io.c:iomap_dio_bio_actor
```
**Symbols:**

```
ffffffff81365960-ffffffff81365a7a: iomap_dio_zero (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void iomap_dio_zero(struct iomap_dio *dio, struct iomap *iomap, loff_t pos, unsigned int len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/iomap/direct-io.c (ffffffff813acde0)
Location: fs/iomap/direct-io.c:183
Inline: False
Direct callers:
  - fs/iomap/direct-io.c:iomap_dio_bio_actor
  - fs/iomap/direct-io.c:iomap_dio_bio_actor
```
**Symbols:**

```
ffffffff813acde0-ffffffff813aceff: iomap_dio_zero (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void iomap_dio_zero(struct iomap_dio *dio, struct iomap *iomap, loff_t pos, unsigned int len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/iomap/direct-io.c (ffffffff813be4c0)
Location: fs/iomap/direct-io.c:185
Inline: False
Direct callers:
  - fs/iomap/direct-io.c:iomap_dio_bio_actor
  - fs/iomap/direct-io.c:iomap_dio_bio_actor
```
**Symbols:**

```
ffffffff813be4c0-ffffffff813be5e2: iomap_dio_zero (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void iomap_dio_zero(struct iomap_dio *dio, struct iomap *iomap, loff_t pos, unsigned int len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/iomap/direct-io.c (ffffffff813c5500)
Location: fs/iomap/direct-io.c:185
Inline: False
Direct callers:
  - fs/iomap/direct-io.c:iomap_dio_bio_actor
  - fs/iomap/direct-io.c:iomap_dio_bio_actor
```
**Symbols:**

```
ffffffff813c5500-ffffffff813c5615: iomap_dio_zero (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void iomap_dio_zero(const struct iomap_iter *iter, struct iomap_dio *dio, loff_t pos, unsigned int len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/iomap/direct-io.c (ffffffff814152a0)
Location: fs/iomap/direct-io.c:182
Inline: False
Direct callers:
  - fs/iomap/direct-io.c:iomap_dio_bio_iter
  - fs/iomap/direct-io.c:iomap_dio_bio_iter
```
**Symbols:**

```
ffffffff814152a0-ffffffff814153b6: iomap_dio_zero (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void iomap_dio_zero(const struct iomap_iter *iter, struct iomap_dio *dio, loff_t pos, unsigned int len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/iomap/direct-io.c (0)
Location: fs/iomap/direct-io.c:191
Inline: False
Direct callers:
  - fs/iomap/direct-io.c:iomap_dio_bio_iter
  - fs/iomap/direct-io.c:iomap_dio_bio_iter
```
**Symbols:**

```
ffffffff8148c970-ffffffff8148cac3: iomap_dio_zero (STB_LOCAL)
ffffffff81e7a5ed-ffffffff81e7a613: iomap_dio_zero.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void iomap_dio_zero(const struct iomap_iter *iter, struct iomap_dio *dio, loff_t pos, unsigned int len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/iomap/direct-io.c (0)
Location: fs/iomap/direct-io.c:191
Inline: False
Direct callers:
  - fs/iomap/direct-io.c:iomap_dio_bio_iter
  - fs/iomap/direct-io.c:iomap_dio_bio_iter
```
**Symbols:**

```
ffffffff8151fe80-ffffffff8151ffd3: iomap_dio_zero (STB_LOCAL)
ffffffff8206b5be-ffffffff8206b5e4: iomap_dio_zero.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void iomap_dio_zero(const struct iomap_iter *iter, struct iomap_dio *dio, loff_t pos, unsigned int len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/iomap/direct-io.c (0)
Location: fs/iomap/direct-io.c:185
Inline: False
Direct callers:
  - fs/iomap/direct-io.c:iomap_dio_bio_iter
  - fs/iomap/direct-io.c:iomap_dio_bio_iter
```
**Symbols:**

```
ffffffff81557f30-ffffffff81558047: iomap_dio_zero (STB_LOCAL)
ffffffff820eb52a-ffffffff820eb550: iomap_dio_zero.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void iomap_dio_zero(const struct iomap_iter *iter, struct iomap_dio *dio, loff_t pos, unsigned int len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/iomap/direct-io.c (0)
Location: fs/iomap/direct-io.c:235
Inline: False
Direct callers:
  - fs/iomap/direct-io.c:iomap_dio_bio_iter
  - fs/iomap/direct-io.c:iomap_dio_bio_iter
```
**Symbols:**

```
ffffffff8158e560-ffffffff8158e677: iomap_dio_zero (STB_LOCAL)
ffffffff821c8771-ffffffff821c8797: iomap_dio_zero.cold (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
void iomap_dio_zero(struct iomap_dio *dio, struct iomap *iomap, loff_t pos, unsigned int len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/iomap/direct-io.c (ffff80001042c7e8)
Location: fs/iomap/direct-io.c:178
Inline: False
Direct callers:
  - fs/iomap/direct-io.c:iomap_dio_bio_actor
  - fs/iomap/direct-io.c:iomap_dio_bio_actor
```
**Symbols:**

```
ffff80001042c7e8-ffff80001042c91c: iomap_dio_zero (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void iomap_dio_zero(struct iomap_dio *dio, struct iomap *iomap, loff_t pos, unsigned int len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/iomap/direct-io.c (c05f5400)
Location: fs/iomap/direct-io.c:178
Inline: False
Direct callers:
  - fs/iomap/direct-io.c:iomap_dio_bio_actor
  - fs/iomap/direct-io.c:iomap_dio_bio_actor
```
**Symbols:**

```
c05f5400-c05f551c: iomap_dio_zero (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void iomap_dio_zero(struct iomap_dio *dio, struct iomap *iomap, loff_t pos, unsigned int len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/iomap/direct-io.c (c00000000053de30)
Location: fs/iomap/direct-io.c:178
Inline: False
Direct callers:
  - fs/iomap/direct-io.c:iomap_dio_bio_actor
  - fs/iomap/direct-io.c:iomap_dio_bio_actor
```
**Symbols:**

```
c00000000053de30-c00000000053dfa8: iomap_dio_zero (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void iomap_dio_zero(struct iomap_dio *dio, struct iomap *iomap, loff_t pos, unsigned int len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/iomap/direct-io.c (ffffffe0002c9c12)
Location: fs/iomap/direct-io.c:178
Inline: False
Direct callers:
  - fs/iomap/direct-io.c:iomap_dio_bio_actor
  - fs/iomap/direct-io.c:iomap_dio_bio_actor
```
**Symbols:**

```
ffffffe0002c9c12-ffffffe0002c9d20: iomap_dio_zero (STB_LOCAL)
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
void iomap_dio_zero(struct iomap_dio *dio, struct iomap *iomap, loff_t pos, unsigned int len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/iomap/direct-io.c (ffffffff8135df40)
Location: fs/iomap/direct-io.c:178
Inline: False
Direct callers:
  - fs/iomap/direct-io.c:iomap_dio_bio_actor
  - fs/iomap/direct-io.c:iomap_dio_bio_actor
```
**Symbols:**

```
ffffffff8135df40-ffffffff8135e05a: iomap_dio_zero (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void iomap_dio_zero(struct iomap_dio *dio, struct iomap *iomap, loff_t pos, unsigned int len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/iomap/direct-io.c (ffffffff8134ebe0)
Location: fs/iomap/direct-io.c:178
Inline: False
Direct callers:
  - fs/iomap/direct-io.c:iomap_dio_bio_actor
  - fs/iomap/direct-io.c:iomap_dio_bio_actor
```
**Symbols:**

```
ffffffff8134ebe0-ffffffff8134ecfa: iomap_dio_zero (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void iomap_dio_zero(struct iomap_dio *dio, struct iomap *iomap, loff_t pos, unsigned int len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/iomap/direct-io.c (ffffffff8135ba10)
Location: fs/iomap/direct-io.c:178
Inline: False
Direct callers:
  - fs/iomap/direct-io.c:iomap_dio_bio_actor
  - fs/iomap/direct-io.c:iomap_dio_bio_actor
```
**Symbols:**

```
ffffffff8135ba10-ffffffff8135bb2a: iomap_dio_zero (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void iomap_dio_zero(struct iomap_dio *dio, struct iomap *iomap, loff_t pos, unsigned int len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/iomap/direct-io.c (ffffffff8136f160)
Location: fs/iomap/direct-io.c:178
Inline: False
Direct callers:
  - fs/iomap/direct-io.c:iomap_dio_bio_actor
  - fs/iomap/direct-io.c:iomap_dio_bio_actor
```
**Symbols:**

```
ffffffff8136f160-ffffffff8136f27a: iomap_dio_zero (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.0</code> and <code>5.3</code> ⚠️</summary>
<ul>
<li>
<b>Return type changed. </b>
<code>blk_qc_t</code> ➡️ <code>void</code>
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
<code>dio, iomap, pos, len</code> ➡️ <code>iter, dio, pos, len</code>
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
