# Function: <code>bio_copy_kern_endio</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void bio_copy_kern_endio(struct bio *bio);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff813b2c50)
Location: block/bio.c:1460
Inline: False
Direct callers:
  - block/bio.c:bio_copy_kern_endio_read
```
**Symbols:**

```
ffffffff813b2c50-ffffffff813b2c98: bio_copy_kern_endio (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void bio_copy_kern_endio(struct bio *bio);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff813f6410)
Location: block/bio.c:1460
Inline: False
Direct callers:
  - block/bio.c:bio_copy_kern_endio_read
```
**Symbols:**

```
ffffffff813f6410-ffffffff813f6458: bio_copy_kern_endio (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void bio_copy_kern_endio(struct bio *bio);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff8140fdf0)
Location: block/bio.c:1515
Inline: False
Direct callers:
  - block/bio.c:bio_copy_kern_endio_read
```
**Symbols:**

```
ffffffff8140fdf0-ffffffff8140fe38: bio_copy_kern_endio (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void bio_copy_kern_endio(struct bio *bio);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff8141d770)
Location: block/bio.c:1522
Inline: False
Direct callers:
  - block/bio.c:bio_copy_kern_endio_read
```
**Symbols:**

```
ffffffff8141d770-ffffffff8141d7ba: bio_copy_kern_endio (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void bio_copy_kern_endio(struct bio *bio);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff81448600)
Location: block/bio.c:1486
Inline: False
Direct callers:
  - block/bio.c:bio_copy_kern_endio_read
```
**Symbols:**

```
ffffffff81448600-ffffffff8144864a: bio_copy_kern_endio (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void bio_copy_kern_endio(struct bio *bio);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff8147b740)
Location: block/bio.c:1541
Inline: False
Direct callers:
  - block/bio.c:bio_copy_kern_endio_read
```
**Symbols:**

```
ffffffff8147b740-ffffffff8147b78a: bio_copy_kern_endio (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void bio_copy_kern_endio(struct bio *bio);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff814986f0)
Location: block/bio.c:1467
Inline: False
Direct callers:
  - block/bio.c:bio_copy_kern_endio_read
```
**Symbols:**

```
ffffffff814986f0-ffffffff8149873a: bio_copy_kern_endio (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void bio_copy_kern_endio(struct bio *bio);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff814c65d6)
Location: block/bio.c:1526
Inline: True
Inline callers:
  - block/bio.c:bio_copy_kern_endio_read
```
**Symbols:**

```
ffffffff814c65a0-ffffffff814c65bf: bio_copy_kern_endio (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void bio_copy_kern_endio(struct bio *bio);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff814df3d6)
Location: block/bio.c:1568
Inline: True
Inline callers:
  - block/bio.c:bio_copy_kern_endio_read
```
**Symbols:**

```
ffffffff814df3a0-ffffffff814df3bf: bio_copy_kern_endio (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void bio_copy_kern_endio(struct bio *bio);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-map.c (ffffffff81549a36)
Location: block/blk-map.c:435
Inline: True
Inline callers:
  - block/blk-map.c:bio_copy_kern_endio_read
```
**Symbols:**

```
ffffffff81549940-ffffffff81549961: bio_copy_kern_endio (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void bio_copy_kern_endio(struct bio *bio);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-map.c (ffffffff81565906)
Location: block/blk-map.c:432
Inline: True
Inline callers:
  - block/blk-map.c:bio_copy_kern_endio_read
```
**Symbols:**

```
ffffffff815658c0-ffffffff815658e1: bio_copy_kern_endio (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void bio_copy_kern_endio(struct bio *bio);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-map.c (ffffffff8156df36)
Location: block/blk-map.c:390
Inline: True
Inline callers:
  - block/blk-map.c:bio_copy_kern_endio_read
```
**Symbols:**

```
ffffffff8156dee0-ffffffff8156df01: bio_copy_kern_endio (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void bio_copy_kern_endio(struct bio *bio);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-map.c (ffffffff815d2996)
Location: block/blk-map.c:390
Inline: True
Inline callers:
  - block/blk-map.c:bio_copy_kern_endio_read
```
**Symbols:**

```
ffffffff815d24d0-ffffffff815d24f1: bio_copy_kern_endio (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void bio_copy_kern_endio(struct bio *bio);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-map.c (ffffffff8167f456)
Location: block/blk-map.c:395
Inline: True
Inline callers:
  - block/blk-map.c:bio_copy_kern_endio_read
```
**Symbols:**

```
ffffffff8167e1d0-ffffffff8167e1fe: bio_copy_kern_endio (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void bio_copy_kern_endio(struct bio *bio);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-map.c (ffffffff8173b926)
Location: block/blk-map.c:436
Inline: True
Inline callers:
  - block/blk-map.c:bio_copy_kern_endio_read
```
**Symbols:**

```
ffffffff8173af60-ffffffff8173af8e: bio_copy_kern_endio (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void bio_copy_kern_endio(struct bio *bio);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-map.c (ffffffff81778066)
Location: block/blk-map.c:435
Inline: True
Inline callers:
  - block/blk-map.c:bio_copy_kern_endio_read
```
**Symbols:**

```
ffffffff81777600-ffffffff8177762e: bio_copy_kern_endio (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void bio_copy_kern_endio(struct bio *bio);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-map.c (ffffffff817ba446)
Location: block/blk-map.c:442
Inline: True
Inline callers:
  - block/blk-map.c:bio_copy_kern_endio_read
```
**Symbols:**

```
ffffffff817b9820-ffffffff817b984e: bio_copy_kern_endio (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
void bio_copy_kern_endio(struct bio *bio);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/bio.c (ffff8000105dbea0)
Location: block/bio.c:1568
Inline: True
Inline callers:
  - block/bio.c:bio_copy_kern_endio_read
```
**Symbols:**

```
ffff8000105dbe48-ffff8000105dbe7c: bio_copy_kern_endio (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void bio_copy_kern_endio(struct bio *bio);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/bio.c (c0789388)
Location: block/bio.c:1568
Inline: True
Inline callers:
  - block/bio.c:bio_copy_kern_endio_read
```
**Symbols:**

```
c078933c-c0789364: bio_copy_kern_endio (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void bio_copy_kern_endio(struct bio *bio);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/bio.c (c00000000076cd80)
Location: block/bio.c:1568
Inline: True
Inline callers:
  - block/bio.c:bio_copy_kern_endio_read
```
**Symbols:**

```
c00000000076ca00-c00000000076ca40: bio_copy_kern_endio (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void bio_copy_kern_endio(struct bio *bio);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffe00041f39e)
Location: block/bio.c:1568
Inline: True
Inline callers:
  - block/bio.c:bio_copy_kern_endio_read
```
**Symbols:**

```
ffffffe00041f33c-ffffffe00041f370: bio_copy_kern_endio (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
void bio_copy_kern_endio(struct bio *bio);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff814d79b6)
Location: block/bio.c:1568
Inline: True
Inline callers:
  - block/bio.c:bio_copy_kern_endio_read
```
**Symbols:**

```
ffffffff814d7980-ffffffff814d799f: bio_copy_kern_endio (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void bio_copy_kern_endio(struct bio *bio);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff814c8376)
Location: block/bio.c:1568
Inline: True
Inline callers:
  - block/bio.c:bio_copy_kern_endio_read
```
**Symbols:**

```
ffffffff814c8340-ffffffff814c835f: bio_copy_kern_endio (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void bio_copy_kern_endio(struct bio *bio);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff814d3a46)
Location: block/bio.c:1568
Inline: True
Inline callers:
  - block/bio.c:bio_copy_kern_endio_read
```
**Symbols:**

```
ffffffff814d3a10-ffffffff814d3a2f: bio_copy_kern_endio (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void bio_copy_kern_endio(struct bio *bio);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/bio.c (ffffffff814ec5e6)
Location: block/bio.c:1568
Inline: True
Inline callers:
  - block/bio.c:bio_copy_kern_endio_read
```
**Symbols:**

```
ffffffff814ec5b0-ffffffff814ec5cf: bio_copy_kern_endio (STB_LOCAL)
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
