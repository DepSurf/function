# Function: <code>bio_uncopy_user</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int bio_uncopy_user(struct bio *bio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff813b1fc0)
Location: block/bio.c:1085
Inline: False
Direct callers:
  - block/blk-map.c:__blk_rq_unmap_user
```
**Symbols:**

```
ffffffff813b1fc0-ffffffff813b210b: bio_uncopy_user (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int bio_uncopy_user(struct bio *bio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff813f5610)
Location: block/bio.c:1087
Inline: False
Direct callers:
  - block/blk-map.c:__blk_rq_unmap_user
```
**Symbols:**

```
ffffffff813f5610-ffffffff813f575f: bio_uncopy_user (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int bio_uncopy_user(struct bio *bio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff8140f030)
Location: block/bio.c:1142
Inline: False
Direct callers:
  - block/blk-map.c:__blk_rq_unmap_user
```
**Symbols:**

```
ffffffff8140f030-ffffffff8140f176: bio_uncopy_user (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int bio_uncopy_user(struct bio *bio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff8141caa0)
Location: block/bio.c:1158
Inline: False
Direct callers:
  - block/blk-map.c:__blk_rq_unmap_user
```
**Symbols:**

```
ffffffff8141caa0-ffffffff8141cbea: bio_uncopy_user (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int bio_uncopy_user(struct bio *bio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff81447a80)
Location: block/bio.c:1163
Inline: False
Direct callers:
  - block/blk-map.c:__blk_rq_unmap_user
```
**Symbols:**

```
ffffffff81447a80-ffffffff81447bca: bio_uncopy_user (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int bio_uncopy_user(struct bio *bio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff8147ab80)
Location: block/bio.c:1218
Inline: False
Direct callers:
  - block/blk-map.c:__blk_rq_unmap_user
```
**Symbols:**

```
ffffffff8147ab80-ffffffff8147acc6: bio_uncopy_user (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int bio_uncopy_user(struct bio *bio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff81498e00)
Location: block/bio.c:1142
Inline: False
Direct callers:
  - block/blk-map.c:__blk_rq_unmap_user
```
**Symbols:**

```
ffffffff81498e00-ffffffff81498f46: bio_uncopy_user (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int bio_uncopy_user(struct bio *bio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff814c6fb0)
Location: block/bio.c:1200
Inline: False
Direct callers:
  - block/blk-map.c:__blk_rq_unmap_user
```
**Symbols:**

```
ffffffff814c6fb0-ffffffff814c711c: bio_uncopy_user (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int bio_uncopy_user(struct bio *bio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff814dfe20)
Location: block/bio.c:1239
Inline: False
Direct callers:
  - block/blk-map.c:__blk_rq_unmap_user
```
**Symbols:**

```
ffffffff814dfe20-ffffffff814dff8c: bio_uncopy_user (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-map.c (ffffffff8154a61f)
Location: block/blk-map.c:106
Inline: True
Inline callers:
  - block/blk-map.c:__blk_rq_unmap_user
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-map.c (ffffffff8156645a)
Location: block/blk-map.c:107
Inline: True
Inline callers:
  - block/blk-map.c:blk_rq_unmap_user
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-map.c (ffffffff8156e8a7)
Location: block/blk-map.c:107
Inline: True
Inline callers:
  - block/blk-map.c:blk_rq_unmap_user
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-map.c (ffffffff815d2ed7)
Location: block/blk-map.c:107
Inline: True
Inline callers:
  - block/blk-map.c:blk_rq_unmap_user
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-map.c (ffffffff8167eb67)
Location: block/blk-map.c:107
Inline: True
Inline callers:
  - block/blk-map.c:blk_rq_unmap_user
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-map.c (ffffffff8173bade)
Location: block/blk-map.c:107
Inline: True
Inline callers:
  - block/blk-map.c:blk_rq_unmap_user
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-map.c (ffffffff8177821e)
Location: block/blk-map.c:109
Inline: True
Inline callers:
  - block/blk-map.c:blk_rq_unmap_user
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-map.c (ffffffff817ba5fe)
Location: block/blk-map.c:109
Inline: True
Inline callers:
  - block/blk-map.c:blk_rq_unmap_user
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
int bio_uncopy_user(struct bio *bio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio.c (ffff8000105dc9d0)
Location: block/bio.c:1239
Inline: False
Direct callers:
  - block/blk-map.c:__blk_rq_unmap_user
```
**Symbols:**

```
ffff8000105dc9d0-ffff8000105dcb60: bio_uncopy_user (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int bio_uncopy_user(struct bio *bio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio.c (c0789e68)
Location: block/bio.c:1239
Inline: False
Direct callers:
  - block/blk-map.c:__blk_rq_unmap_user
```
**Symbols:**

```
c0789e68-c0789ff4: bio_uncopy_user (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int bio_uncopy_user(struct bio *bio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio.c (c00000000076dc50)
Location: block/bio.c:1239
Inline: False
Direct callers:
  - block/blk-map.c:__blk_rq_unmap_user
```
**Symbols:**

```
c00000000076dc50-c00000000076de8c: bio_uncopy_user (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int bio_uncopy_user(struct bio *bio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffe00041fcfc)
Location: block/bio.c:1239
Inline: False
Direct callers:
  - block/blk-map.c:__blk_rq_unmap_user
```
**Symbols:**

```
ffffffe00041fcfc-ffffffe00041fe36: bio_uncopy_user (STB_GLOBAL)
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
int bio_uncopy_user(struct bio *bio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff814d8400)
Location: block/bio.c:1239
Inline: False
Direct callers:
  - block/blk-map.c:__blk_rq_unmap_user
```
**Symbols:**

```
ffffffff814d8400-ffffffff814d856c: bio_uncopy_user (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int bio_uncopy_user(struct bio *bio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff814c8db0)
Location: block/bio.c:1239
Inline: False
Direct callers:
  - block/blk-map.c:__blk_rq_unmap_user
```
**Symbols:**

```
ffffffff814c8db0-ffffffff814c8f1c: bio_uncopy_user (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int bio_uncopy_user(struct bio *bio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff814d4490)
Location: block/bio.c:1239
Inline: False
Direct callers:
  - block/blk-map.c:__blk_rq_unmap_user
```
**Symbols:**

```
ffffffff814d4490-ffffffff814d45fc: bio_uncopy_user (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int bio_uncopy_user(struct bio *bio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff814ed040)
Location: block/bio.c:1239
Inline: False
Direct callers:
  - block/blk-map.c:__blk_rq_unmap_user
```
**Symbols:**

```
ffffffff814ed040-ffffffff814ed1ac: bio_uncopy_user (STB_GLOBAL)
```
</details>
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
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
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
