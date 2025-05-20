# Function: <code>bio_unmap_user</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void bio_unmap_user(struct bio *bio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff813b28c0)
Location: block/bio.c:1397
Inline: False
Direct callers:
  - block/blk-map.c:__blk_rq_unmap_user
```
**Symbols:**

```
ffffffff813b28c0-ffffffff813b2923: bio_unmap_user (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void bio_unmap_user(struct bio *bio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff813f6010)
Location: block/bio.c:1398
Inline: False
Direct callers:
  - block/blk-map.c:__blk_rq_unmap_user
```
**Symbols:**

```
ffffffff813f6010-ffffffff813f60bc: bio_unmap_user (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void bio_unmap_user(struct bio *bio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff8140fa10)
Location: block/bio.c:1453
Inline: False
Direct callers:
  - block/blk-map.c:__blk_rq_unmap_user
```
**Symbols:**

```
ffffffff8140fa10-ffffffff8140fab8: bio_unmap_user (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void bio_unmap_user(struct bio *bio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff8141d3c0)
Location: block/bio.c:1460
Inline: False
Direct callers:
  - block/blk-map.c:__blk_rq_unmap_user
```
**Symbols:**

```
ffffffff8141d3c0-ffffffff8141d437: bio_unmap_user (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void bio_unmap_user(struct bio *bio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff81448220)
Location: block/bio.c:1424
Inline: False
Direct callers:
  - block/blk-map.c:__blk_rq_unmap_user
```
**Symbols:**

```
ffffffff81448220-ffffffff814482c1: bio_unmap_user (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void bio_unmap_user(struct bio *bio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff8147b370)
Location: block/bio.c:1479
Inline: False
Direct callers:
  - block/blk-map.c:__blk_rq_unmap_user
```
**Symbols:**

```
ffffffff8147b370-ffffffff8147b416: bio_unmap_user (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void bio_unmap_user(struct bio *bio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff81499610)
Location: block/bio.c:1405
Inline: False
Direct callers:
  - block/blk-map.c:__blk_rq_unmap_user
```
**Symbols:**

```
ffffffff81499610-ffffffff814996b6: bio_unmap_user (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void bio_unmap_user(struct bio *bio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff814c77e0)
Location: block/bio.c:1438
Inline: False
Direct callers:
  - block/blk-map.c:__blk_rq_unmap_user
```
**Symbols:**

```
ffffffff814c77e0-ffffffff814c7816: bio_unmap_user (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void bio_unmap_user(struct bio *bio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff814e06f0)
Location: block/bio.c:1481
Inline: False
Direct callers:
  - block/blk-map.c:__blk_rq_unmap_user
```
**Symbols:**

```
ffffffff814e06f0-ffffffff814e0726: bio_unmap_user (STB_GLOBAL)
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
In block/blk-map.c (ffffffff8154a5f2)
Location: block/blk-map.c:348
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
In block/blk-map.c (ffffffff81566484)
Location: block/blk-map.c:345
Inline: True
Inline callers:
  - block/blk-map.c:blk_rq_unmap_user
```
</details>
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
void bio_unmap_user(struct bio *bio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio.c (ffff8000105dd240)
Location: block/bio.c:1481
Inline: False
Direct callers:
  - block/blk-map.c:__blk_rq_unmap_user
```
**Symbols:**

```
ffff8000105dd240-ffff8000105dd290: bio_unmap_user (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void bio_unmap_user(struct bio *bio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio.c (c078a6a0)
Location: block/bio.c:1481
Inline: False
Direct callers:
  - block/blk-map.c:__blk_rq_unmap_user
```
**Symbols:**

```
c078a6a0-c078a6e8: bio_unmap_user (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void bio_unmap_user(struct bio *bio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio.c (c00000000076e8f0)
Location: block/bio.c:1481
Inline: False
Direct callers:
  - block/blk-map.c:__blk_rq_unmap_user
```
**Symbols:**

```
c00000000076e8f0-c00000000076e954: bio_unmap_user (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void bio_unmap_user(struct bio *bio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffe0004203ee)
Location: block/bio.c:1481
Inline: False
Direct callers:
  - block/blk-map.c:__blk_rq_unmap_user
```
**Symbols:**

```
ffffffe0004203ee-ffffffe00042043c: bio_unmap_user (STB_GLOBAL)
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
void bio_unmap_user(struct bio *bio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff814d8cd0)
Location: block/bio.c:1481
Inline: False
Direct callers:
  - block/blk-map.c:__blk_rq_unmap_user
```
**Symbols:**

```
ffffffff814d8cd0-ffffffff814d8d06: bio_unmap_user (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void bio_unmap_user(struct bio *bio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff814c9680)
Location: block/bio.c:1481
Inline: False
Direct callers:
  - block/blk-map.c:__blk_rq_unmap_user
```
**Symbols:**

```
ffffffff814c9680-ffffffff814c96b6: bio_unmap_user (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void bio_unmap_user(struct bio *bio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff814d4d60)
Location: block/bio.c:1481
Inline: False
Direct callers:
  - block/blk-map.c:__blk_rq_unmap_user
```
**Symbols:**

```
ffffffff814d4d60-ffffffff814d4d96: bio_unmap_user (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void bio_unmap_user(struct bio *bio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff814ed910)
Location: block/bio.c:1481
Inline: False
Direct callers:
  - block/blk-map.c:__blk_rq_unmap_user
```
**Symbols:**

```
ffffffff814ed910-ffffffff814ed946: bio_unmap_user (STB_GLOBAL)
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
