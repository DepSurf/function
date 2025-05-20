# Function: <code>blk_mq_tag_update_depth</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int blk_mq_tag_update_depth(struct blk_mq_tags *tags, unsigned int tdepth);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-tag.c (ffffffff813c7960)
Location: block/blk-mq-tag.c:658
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_update_nr_requests
```
**Symbols:**

```
ffffffff813c7960-ffffffff813c7992: blk_mq_tag_update_depth (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int blk_mq_tag_update_depth(struct blk_mq_tags *tags, unsigned int tdepth);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-tag.c (ffffffff8140bba0)
Location: block/blk-mq-tag.c:695
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_update_nr_requests
```
**Symbols:**

```
ffffffff8140bba0-ffffffff8140bbd2: blk_mq_tag_update_depth (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int blk_mq_tag_update_depth(struct blk_mq_tags *tags, unsigned int tdepth);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-tag.c (ffffffff814262c0)
Location: block/blk-mq-tag.c:414
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_update_nr_requests
```
**Symbols:**

```
ffffffff814262c0-ffffffff814262f0: blk_mq_tag_update_depth (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int blk_mq_tag_update_depth(struct blk_mq_hw_ctx *hctx, struct blk_mq_tags **tagsptr, unsigned int tdepth, bool can_grow);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-tag.c (ffffffff81434010)
Location: block/blk-mq-tag.c:399
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_update_nr_requests
  - block/blk-mq.c:blk_mq_update_nr_requests
```
**Symbols:**

```
ffffffff81434010-ffffffff81434116: blk_mq_tag_update_depth (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int blk_mq_tag_update_depth(struct blk_mq_hw_ctx *hctx, struct blk_mq_tags **tagsptr, unsigned int tdepth, bool can_grow);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-tag.c (ffffffff8145fd40)
Location: block/blk-mq-tag.c:409
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_update_nr_requests
  - block/blk-mq.c:blk_mq_update_nr_requests
```
**Symbols:**

```
ffffffff8145fd40-ffffffff8145fe46: blk_mq_tag_update_depth (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int blk_mq_tag_update_depth(struct blk_mq_hw_ctx *hctx, struct blk_mq_tags **tagsptr, unsigned int tdepth, bool can_grow);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-tag.c (ffffffff81493620)
Location: block/blk-mq-tag.c:396
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_update_nr_requests
  - block/blk-mq.c:blk_mq_update_nr_requests
```
**Symbols:**

```
ffffffff81493620-ffffffff81493707: blk_mq_tag_update_depth (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int blk_mq_tag_update_depth(struct blk_mq_hw_ctx *hctx, struct blk_mq_tags **tagsptr, unsigned int tdepth, bool can_grow);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-tag.c (ffffffff814ad650)
Location: block/blk-mq-tag.c:466
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_update_nr_requests
  - block/blk-mq.c:blk_mq_update_nr_requests
```
**Symbols:**

```
ffffffff814ad650-ffffffff814ad737: blk_mq_tag_update_depth (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int blk_mq_tag_update_depth(struct blk_mq_hw_ctx *hctx, struct blk_mq_tags **tagsptr, unsigned int tdepth, bool can_grow);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-tag.c (ffffffff814db8e0)
Location: block/blk-mq-tag.c:459
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_update_nr_requests
  - block/blk-mq.c:blk_mq_update_nr_requests
```
**Symbols:**

```
ffffffff814db8e0-ffffffff814db9d6: blk_mq_tag_update_depth (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int blk_mq_tag_update_depth(struct blk_mq_hw_ctx *hctx, struct blk_mq_tags **tagsptr, unsigned int tdepth, bool can_grow);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-tag.c (ffffffff814f4d10)
Location: block/blk-mq-tag.c:491
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_update_nr_requests
  - block/blk-mq.c:blk_mq_update_nr_requests
```
**Symbols:**

```
ffffffff814f4d10-ffffffff814f4e06: blk_mq_tag_update_depth (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int blk_mq_tag_update_depth(struct blk_mq_hw_ctx *hctx, struct blk_mq_tags **tagsptr, unsigned int tdepth, bool can_grow);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-tag.c (ffffffff815556e0)
Location: block/blk-mq-tag.c:538
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_update_nr_requests
  - block/blk-mq.c:blk_mq_update_nr_requests
```
**Symbols:**

```
ffffffff815556e0-ffffffff815557d6: blk_mq_tag_update_depth (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int blk_mq_tag_update_depth(struct blk_mq_hw_ctx *hctx, struct blk_mq_tags **tagsptr, unsigned int tdepth, bool can_grow);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-tag.c (ffffffff81571f30)
Location: block/blk-mq-tag.c:539
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_update_nr_requests
  - block/blk-mq.c:blk_mq_update_nr_requests
```
**Symbols:**

```
ffffffff81571f30-ffffffff81572036: blk_mq_tag_update_depth (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int blk_mq_tag_update_depth(struct blk_mq_hw_ctx *hctx, struct blk_mq_tags **tagsptr, unsigned int tdepth, bool can_grow);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-tag.c (ffffffff81579f50)
Location: block/blk-mq-tag.c:566
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_update_nr_requests
  - block/blk-mq.c:blk_mq_update_nr_requests
```
**Symbols:**

```
ffffffff81579f50-ffffffff8157a056: blk_mq_tag_update_depth (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int blk_mq_tag_update_depth(struct blk_mq_hw_ctx *hctx, struct blk_mq_tags **tagsptr, unsigned int tdepth, bool can_grow);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-tag.c (ffffffff815df270)
Location: block/blk-mq-tag.c:579
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_update_nr_requests
  - block/blk-mq.c:blk_mq_update_nr_requests
```
**Symbols:**

```
ffffffff815df270-ffffffff815df375: blk_mq_tag_update_depth (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int blk_mq_tag_update_depth(struct blk_mq_hw_ctx *hctx, struct blk_mq_tags **tagsptr, unsigned int tdepth, bool can_grow);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-tag.c (ffffffff8168d8d0)
Location: block/blk-mq-tag.c:601
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_update_nr_requests
  - block/blk-mq.c:blk_mq_update_nr_requests
```
**Symbols:**

```
ffffffff8168d8d0-ffffffff8168d97f: blk_mq_tag_update_depth (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int blk_mq_tag_update_depth(struct blk_mq_hw_ctx *hctx, struct blk_mq_tags **tagsptr, unsigned int tdepth, bool can_grow);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-tag.c (ffffffff8174c110)
Location: block/blk-mq-tag.c:594
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_update_nr_requests
  - block/blk-mq.c:blk_mq_update_nr_requests
```
**Symbols:**

```
ffffffff8174c110-ffffffff8174c1bf: blk_mq_tag_update_depth (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int blk_mq_tag_update_depth(struct blk_mq_hw_ctx *hctx, struct blk_mq_tags **tagsptr, unsigned int tdepth, bool can_grow);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-tag.c (ffffffff81788830)
Location: block/blk-mq-tag.c:601
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_update_nr_requests
  - block/blk-mq.c:blk_mq_update_nr_requests
```
**Symbols:**

```
ffffffff81788830-ffffffff817888df: blk_mq_tag_update_depth (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int blk_mq_tag_update_depth(struct blk_mq_hw_ctx *hctx, struct blk_mq_tags **tagsptr, unsigned int tdepth, bool can_grow);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-tag.c (ffffffff817caf30)
Location: block/blk-mq-tag.c:601
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_update_nr_requests
  - block/blk-mq.c:blk_mq_update_nr_requests
```
**Symbols:**

```
ffffffff817caf30-ffffffff817cafdf: blk_mq_tag_update_depth (STB_GLOBAL)
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
int blk_mq_tag_update_depth(struct blk_mq_hw_ctx *hctx, struct blk_mq_tags **tagsptr, unsigned int tdepth, bool can_grow);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-tag.c (ffff8000105f4b78)
Location: block/blk-mq-tag.c:491
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_update_nr_requests
  - block/blk-mq.c:blk_mq_update_nr_requests
```
**Symbols:**

```
ffff8000105f4b78-ffff8000105f4c9c: blk_mq_tag_update_depth (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int blk_mq_tag_update_depth(struct blk_mq_hw_ctx *hctx, struct blk_mq_tags **tagsptr, unsigned int tdepth, bool can_grow);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-tag.c (c07a07b4)
Location: block/blk-mq-tag.c:491
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_update_nr_requests
```
**Symbols:**

```
c07a07b4-c07a089c: blk_mq_tag_update_depth (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int blk_mq_tag_update_depth(struct blk_mq_hw_ctx *hctx, struct blk_mq_tags **tagsptr, unsigned int tdepth, bool can_grow);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-tag.c (c00000000078c5d0)
Location: block/blk-mq-tag.c:491
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_update_nr_requests
  - block/blk-mq.c:blk_mq_update_nr_requests
```
**Symbols:**

```
c00000000078c5d0-c00000000078c744: blk_mq_tag_update_depth (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int blk_mq_tag_update_depth(struct blk_mq_hw_ctx *hctx, struct blk_mq_tags **tagsptr, unsigned int tdepth, bool can_grow);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-tag.c (ffffffe000432a4e)
Location: block/blk-mq-tag.c:491
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_update_nr_requests
  - block/blk-mq.c:blk_mq_update_nr_requests
```
**Symbols:**

```
ffffffe000432a4e-ffffffe000432b20: blk_mq_tag_update_depth (STB_GLOBAL)
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
int blk_mq_tag_update_depth(struct blk_mq_hw_ctx *hctx, struct blk_mq_tags **tagsptr, unsigned int tdepth, bool can_grow);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-tag.c (ffffffff814ed2f0)
Location: block/blk-mq-tag.c:491
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_update_nr_requests
  - block/blk-mq.c:blk_mq_update_nr_requests
```
**Symbols:**

```
ffffffff814ed2f0-ffffffff814ed3e6: blk_mq_tag_update_depth (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int blk_mq_tag_update_depth(struct blk_mq_hw_ctx *hctx, struct blk_mq_tags **tagsptr, unsigned int tdepth, bool can_grow);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-tag.c (ffffffff814dd840)
Location: block/blk-mq-tag.c:491
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_update_nr_requests
  - block/blk-mq.c:blk_mq_update_nr_requests
```
**Symbols:**

```
ffffffff814dd840-ffffffff814dd936: blk_mq_tag_update_depth (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int blk_mq_tag_update_depth(struct blk_mq_hw_ctx *hctx, struct blk_mq_tags **tagsptr, unsigned int tdepth, bool can_grow);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-tag.c (ffffffff814e9380)
Location: block/blk-mq-tag.c:491
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_update_nr_requests
  - block/blk-mq.c:blk_mq_update_nr_requests
```
**Symbols:**

```
ffffffff814e9380-ffffffff814e9476: blk_mq_tag_update_depth (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int blk_mq_tag_update_depth(struct blk_mq_hw_ctx *hctx, struct blk_mq_tags **tagsptr, unsigned int tdepth, bool can_grow);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-tag.c (ffffffff81502340)
Location: block/blk-mq-tag.c:491
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_update_nr_requests
  - block/blk-mq.c:blk_mq_update_nr_requests
```
**Symbols:**

```
ffffffff81502340-ffffffff81502436: blk_mq_tag_update_depth (STB_GLOBAL)
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
<details>
<summary>Changed between <code>4.10</code> and <code>4.13</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct blk_mq_hw_ctx *hctx</code>
</li>
<li>
<b>Param added. </b>
<code>struct blk_mq_tags **tagsptr</code>
</li>
<li>
<b>Param added. </b>
<code>bool can_grow</code>
</li>
<li>
<b>Param removed. </b>
<code>struct blk_mq_tags *tags</code>
</li>
<li>
<b>Param reordered. </b>
<code>tags, tdepth</code> ➡️ <code>hctx, tagsptr, tdepth, can_grow</code>
</li>
</ul>
</details>
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
