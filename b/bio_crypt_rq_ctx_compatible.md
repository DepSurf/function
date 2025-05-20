# Function: <code>bio_crypt_rq_ctx_compatible</code>

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
bool bio_crypt_rq_ctx_compatible(struct request *rq, struct bio *bio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-crypto.c (ffffffff81581a50)
Location: block/blk-crypto.c:173
Inline: False
Direct callers:
  - block/blk-merge.c:blk_rq_merge_ok
```
**Symbols:**

```
ffffffff81581a50-ffffffff81581a87: bio_crypt_rq_ctx_compatible (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
bool bio_crypt_rq_ctx_compatible(struct request *rq, struct bio *bio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-crypto.c (ffffffff8159ea40)
Location: block/blk-crypto.c:184
Inline: False
```
**Symbols:**

```
ffffffff8159ea40-ffffffff8159ea77: bio_crypt_rq_ctx_compatible (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
bool bio_crypt_rq_ctx_compatible(struct request *rq, struct bio *bio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-crypto.c (ffffffff815a5810)
Location: block/blk-crypto.c:184
Inline: False
```
**Symbols:**

```
ffffffff815a5810-ffffffff815a5847: bio_crypt_rq_ctx_compatible (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
bool bio_crypt_rq_ctx_compatible(struct request *rq, struct bio *bio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-crypto.c (ffffffff8160e310)
Location: block/blk-crypto.c:184
Inline: False
```
**Symbols:**

```
ffffffff8160e310-ffffffff8160e347: bio_crypt_rq_ctx_compatible (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
bool bio_crypt_rq_ctx_compatible(struct request *rq, struct bio *bio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-crypto.c (ffffffff816c1970)
Location: block/blk-crypto.c:186
Inline: False
Direct callers:
  - block/blk-merge.c:blk_rq_merge_ok
```
**Symbols:**

```
ffffffff816c1970-ffffffff816c19af: bio_crypt_rq_ctx_compatible (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
bool bio_crypt_rq_ctx_compatible(struct request *rq, struct bio *bio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-crypto.c (ffffffff81782b20)
Location: block/blk-crypto.c:192
Inline: False
Direct callers:
  - block/blk-merge.c:blk_rq_merge_ok
```
**Symbols:**

```
ffffffff81782b20-ffffffff81782b5f: bio_crypt_rq_ctx_compatible (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
bool bio_crypt_rq_ctx_compatible(struct request *rq, struct bio *bio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-crypto.c (ffffffff817c2d00)
Location: block/blk-crypto.c:193
Inline: False
Direct callers:
  - block/blk-merge.c:blk_rq_merge_ok
```
**Symbols:**

```
ffffffff817c2d00-ffffffff817c2d3f: bio_crypt_rq_ctx_compatible (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
bool bio_crypt_rq_ctx_compatible(struct request *rq, struct bio *bio);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-crypto.c (ffffffff81807990)
Location: block/blk-crypto.c:193
Inline: False
Direct callers:
  - block/blk-merge.c:blk_rq_merge_ok
```
**Symbols:**

```
ffffffff81807990-ffffffff818079cf: bio_crypt_rq_ctx_compatible (STB_GLOBAL)
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
