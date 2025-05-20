# Function: <code>blk_mq_init_tags</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct blk_mq_tags *blk_mq_init_tags(unsigned int total_tags, unsigned int reserved_tags, int node, int alloc_policy);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-tag.c (ffffffff813c77f0)
Location: block/blk-mq-tag.c:617
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_init_rq_map
```
**Symbols:**

```
ffffffff813c77f0-ffffffff813c78e9: blk_mq_init_tags (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct blk_mq_tags *blk_mq_init_tags(unsigned int total_tags, unsigned int reserved_tags, int node, int alloc_policy);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-tag.c (ffffffff8140ba30)
Location: block/blk-mq-tag.c:654
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_init_rq_map
```
**Symbols:**

```
ffffffff8140ba30-ffffffff8140bb22: blk_mq_init_tags (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct blk_mq_tags *blk_mq_init_tags(unsigned int total_tags, unsigned int reserved_tags, int node, int alloc_policy);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-tag.c (ffffffff81426150)
Location: block/blk-mq-tag.c:386
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_init_rq_map
```
**Symbols:**

```
ffffffff81426150-ffffffff81426251: blk_mq_init_tags (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct blk_mq_tags *blk_mq_init_tags(unsigned int total_tags, unsigned int reserved_tags, int node, int alloc_policy);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-tag.c (ffffffff81433eb0)
Location: block/blk-mq-tag.c:371
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_alloc_rq_map
```
**Symbols:**

```
ffffffff81433eb0-ffffffff81433fa6: blk_mq_init_tags (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct blk_mq_tags *blk_mq_init_tags(unsigned int total_tags, unsigned int reserved_tags, int node, int alloc_policy);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-tag.c (ffffffff8145fbe0)
Location: block/blk-mq-tag.c:381
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_alloc_rq_map
```
**Symbols:**

```
ffffffff8145fbe0-ffffffff8145fcd6: blk_mq_init_tags (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
struct blk_mq_tags *blk_mq_init_tags(unsigned int total_tags, unsigned int reserved_tags, int node, int alloc_policy);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/blk-mq-tag.c (0)
Location: block/blk-mq-tag.c:368
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_alloc_rq_map
```
**Symbols:**

```
ffffffff81493707-ffffffff8149371a: blk_mq_init_tags.cold.13 (STB_LOCAL)
ffffffff814934d0-ffffffff814935b6: blk_mq_init_tags (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
struct blk_mq_tags *blk_mq_init_tags(unsigned int total_tags, unsigned int reserved_tags, int node, int alloc_policy);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/blk-mq-tag.c (0)
Location: block/blk-mq-tag.c:438
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_alloc_rq_map
```
**Symbols:**

```
ffffffff814ad737-ffffffff814ad74a: blk_mq_init_tags.cold.12 (STB_LOCAL)
ffffffff814ad500-ffffffff814ad5e6: blk_mq_init_tags (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
struct blk_mq_tags *blk_mq_init_tags(unsigned int total_tags, unsigned int reserved_tags, int node, int alloc_policy);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/blk-mq-tag.c (0)
Location: block/blk-mq-tag.c:431
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_alloc_rq_map
```
**Symbols:**

```
ffffffff814db9d6-ffffffff814db9ea: blk_mq_init_tags.cold (STB_LOCAL)
ffffffff814db780-ffffffff814db86b: blk_mq_init_tags (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
struct blk_mq_tags *blk_mq_init_tags(unsigned int total_tags, unsigned int reserved_tags, int node, int alloc_policy);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/blk-mq-tag.c (0)
Location: block/blk-mq-tag.c:463
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_alloc_rq_map
```
**Symbols:**

```
ffffffff814f4e06-ffffffff814f4e1a: blk_mq_init_tags.cold (STB_LOCAL)
ffffffff814f4bb0-ffffffff814f4c9b: blk_mq_init_tags (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
struct blk_mq_tags *blk_mq_init_tags(unsigned int total_tags, unsigned int reserved_tags, int node, int alloc_policy);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/blk-mq-tag.c (0)
Location: block/blk-mq-tag.c:510
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_alloc_rq_map
```
**Symbols:**

```
ffffffff815557d6-ffffffff815557ea: blk_mq_init_tags.cold (STB_LOCAL)
ffffffff81555580-ffffffff8155566b: blk_mq_init_tags (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
struct blk_mq_tags *blk_mq_init_tags(unsigned int total_tags, unsigned int reserved_tags, int node, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/blk-mq-tag.c (0)
Location: block/blk-mq-tag.c:501
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_alloc_rq_map
```
**Symbols:**

```
ffffffff81bf280d-ffffffff81bf2821: blk_mq_init_tags.cold (STB_LOCAL)
ffffffff81571db0-ffffffff81571eaf: blk_mq_init_tags (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
struct blk_mq_tags *blk_mq_init_tags(unsigned int total_tags, unsigned int reserved_tags, int node, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/blk-mq-tag.c (0)
Location: block/blk-mq-tag.c:527
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_alloc_rq_map
```
**Symbols:**

```
ffffffff81be47d3-ffffffff81be47e7: blk_mq_init_tags.cold (STB_LOCAL)
ffffffff81579dc0-ffffffff81579ec9: blk_mq_init_tags (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
struct blk_mq_tags *blk_mq_init_tags(unsigned int total_tags, unsigned int reserved_tags, int node, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/blk-mq-tag.c (0)
Location: block/blk-mq-tag.c:540
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_alloc_rq_map
```
**Symbols:**

```
ffffffff81cd8807-ffffffff81cd881b: blk_mq_init_tags.cold (STB_LOCAL)
ffffffff815df130-ffffffff815df1ef: blk_mq_init_tags (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
struct blk_mq_tags *blk_mq_init_tags(unsigned int total_tags, unsigned int reserved_tags, int node, int alloc_policy);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/blk-mq-tag.c (0)
Location: block/blk-mq-tag.c:566
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_alloc_map_and_rqs
```
**Symbols:**

```
ffffffff81e8c28d-ffffffff81e8c29e: blk_mq_init_tags.cold (STB_LOCAL)
ffffffff8168d7b0-ffffffff8168d85c: blk_mq_init_tags (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct blk_mq_tags *blk_mq_init_tags(unsigned int total_tags, unsigned int reserved_tags, int node, int alloc_policy);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-tag.c (ffffffff8174bfc0)
Location: block/blk-mq-tag.c:559
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_alloc_map_and_rqs
```
**Symbols:**

```
ffffffff8174bfc0-ffffffff8174c07a: blk_mq_init_tags (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct blk_mq_tags *blk_mq_init_tags(unsigned int total_tags, unsigned int reserved_tags, int node, int alloc_policy);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-tag.c (ffffffff817886e0)
Location: block/blk-mq-tag.c:566
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_alloc_map_and_rqs
```
**Symbols:**

```
ffffffff817886e0-ffffffff8178879a: blk_mq_init_tags (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct blk_mq_tags *blk_mq_init_tags(unsigned int total_tags, unsigned int reserved_tags, int node, int alloc_policy);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-tag.c (ffffffff817cadb0)
Location: block/blk-mq-tag.c:566
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_alloc_map_and_rqs
```
**Symbols:**

```
ffffffff817cadb0-ffffffff817caea0: blk_mq_init_tags (STB_GLOBAL)
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
struct blk_mq_tags *blk_mq_init_tags(unsigned int total_tags, unsigned int reserved_tags, int node, int alloc_policy);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-tag.c (ffff8000105f49f8)
Location: block/blk-mq-tag.c:463
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_alloc_rq_map
```
**Symbols:**

```
ffff8000105f49f8-ffff8000105f4b08: blk_mq_init_tags (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct blk_mq_tags *blk_mq_init_tags(unsigned int total_tags, unsigned int reserved_tags, int node, int alloc_policy);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-tag.c (c07a0654)
Location: block/blk-mq-tag.c:463
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_alloc_rq_map
```
**Symbols:**

```
c07a0654-c07a0754: blk_mq_init_tags (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct blk_mq_tags *blk_mq_init_tags(unsigned int total_tags, unsigned int reserved_tags, int node, int alloc_policy);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-tag.c (c00000000078c3b0)
Location: block/blk-mq-tag.c:463
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_alloc_rq_map
```
**Symbols:**

```
c00000000078c3b0-c00000000078c528: blk_mq_init_tags (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct blk_mq_tags *blk_mq_init_tags(unsigned int total_tags, unsigned int reserved_tags, int node, int alloc_policy);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-tag.c (ffffffe0004328fa)
Location: block/blk-mq-tag.c:463
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_alloc_rq_map
```
**Symbols:**

```
ffffffe0004328fa-ffffffe0004329e0: blk_mq_init_tags (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
struct blk_mq_tags *blk_mq_init_tags(unsigned int total_tags, unsigned int reserved_tags, int node, int alloc_policy);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/blk-mq-tag.c (0)
Location: block/blk-mq-tag.c:463
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_alloc_rq_map
```
**Symbols:**

```
ffffffff814ed3e6-ffffffff814ed3fa: blk_mq_init_tags.cold (STB_LOCAL)
ffffffff814ed190-ffffffff814ed27b: blk_mq_init_tags (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
struct blk_mq_tags *blk_mq_init_tags(unsigned int total_tags, unsigned int reserved_tags, int node, int alloc_policy);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/blk-mq-tag.c (0)
Location: block/blk-mq-tag.c:463
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_alloc_rq_map
```
**Symbols:**

```
ffffffff814dd936-ffffffff814dd94a: blk_mq_init_tags.cold (STB_LOCAL)
ffffffff814dd6e0-ffffffff814dd7cb: blk_mq_init_tags (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
struct blk_mq_tags *blk_mq_init_tags(unsigned int total_tags, unsigned int reserved_tags, int node, int alloc_policy);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/blk-mq-tag.c (0)
Location: block/blk-mq-tag.c:463
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_alloc_rq_map
```
**Symbols:**

```
ffffffff814e9476-ffffffff814e948a: blk_mq_init_tags.cold (STB_LOCAL)
ffffffff814e9220-ffffffff814e930b: blk_mq_init_tags (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
struct blk_mq_tags *blk_mq_init_tags(unsigned int total_tags, unsigned int reserved_tags, int node, int alloc_policy);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/blk-mq-tag.c (0)
Location: block/blk-mq-tag.c:463
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_alloc_rq_map
```
**Symbols:**

```
ffffffff81502436-ffffffff8150244a: blk_mq_init_tags.cold (STB_LOCAL)
ffffffff815021e0-ffffffff815022cb: blk_mq_init_tags (STB_GLOBAL)
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
<details>
<summary>Changed between <code>5.8</code> and <code>5.11</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>unsigned int flags</code>
</li>
<li>
<b>Param removed. </b>
<code>int alloc_policy</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.15</code> and <code>5.19</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>int alloc_policy</code>
</li>
<li>
<b>Param removed. </b>
<code>unsigned int flags</code>
</li>
</ul>
</details>
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
