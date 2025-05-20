# Function: <code>blk_mq_put_tag</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void blk_mq_put_tag(struct blk_mq_hw_ctx *hctx, unsigned int tag, unsigned int *last_tag);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-tag.c (ffffffff813c76d0)
Location: block/blk-mq-tag.c:404
Inline: False
Direct callers:
  - block/blk-mq.c:__blk_mq_free_request
```
**Symbols:**

```
ffffffff813c76d0-ffffffff813c772e: blk_mq_put_tag (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void blk_mq_put_tag(struct blk_mq_hw_ctx *hctx, unsigned int tag, unsigned int *last_tag);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-tag.c (ffffffff8140b910)
Location: block/blk-mq-tag.c:404
Inline: False
Direct callers:
  - block/blk-mq.c:__blk_mq_free_request
```
**Symbols:**

```
ffffffff8140b910-ffffffff8140b96e: blk_mq_put_tag (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void blk_mq_put_tag(struct blk_mq_hw_ctx *hctx, struct blk_mq_ctx *ctx, unsigned int tag);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-tag.c (ffffffff81425f10)
Location: block/blk-mq-tag.c:195
Inline: False
Direct callers:
  - block/blk-mq.c:__blk_mq_free_request
```
**Symbols:**

```
ffffffff81425f10-ffffffff81425f51: blk_mq_put_tag (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void blk_mq_put_tag(struct blk_mq_hw_ctx *hctx, struct blk_mq_tags *tags, struct blk_mq_ctx *ctx, unsigned int tag);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-tag.c (ffffffff81433c80)
Location: block/blk-mq-tag.c:184
Inline: False
Direct callers:
  - block/blk-mq.c:__blk_mq_put_driver_tag
  - block/blk-mq.c:blk_mq_free_request
  - block/blk-mq.c:blk_mq_free_request
```
**Symbols:**

```
ffffffff81433c80-ffffffff81433cbb: blk_mq_put_tag (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void blk_mq_put_tag(struct blk_mq_hw_ctx *hctx, struct blk_mq_tags *tags, struct blk_mq_ctx *ctx, unsigned int tag);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-tag.c (ffffffff8145f940)
Location: block/blk-mq-tag.c:184
Inline: False
Direct callers:
  - block/blk-flush.c:mq_flush_data_end_io
  - block/blk-flush.c:flush_end_io
  - block/blk-mq.c:__blk_mq_try_issue_directly
  - block/blk-mq.c:blk_mq_dispatch_rq_list
  - block/blk-mq.c:blk_mq_dispatch_rq_list
  - block/blk-mq.c:blk_mq_free_request
  - block/blk-mq.c:blk_mq_free_request
```
**Symbols:**

```
ffffffff8145f940-ffffffff8145f97b: blk_mq_put_tag (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void blk_mq_put_tag(struct blk_mq_hw_ctx *hctx, struct blk_mq_tags *tags, struct blk_mq_ctx *ctx, unsigned int tag);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-tag.c (ffffffff81493230)
Location: block/blk-mq-tag.c:200
Inline: False
Direct callers:
  - block/blk-flush.c:mq_flush_data_end_io
  - block/blk-flush.c:flush_end_io
  - block/blk-mq.c:blk_mq_dispatch_rq_list
  - block/blk-mq.c:__blk_mq_free_request
  - block/blk-mq.c:__blk_mq_free_request
```
**Symbols:**

```
ffffffff81493230-ffffffff8149326b: blk_mq_put_tag (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void blk_mq_put_tag(struct blk_mq_hw_ctx *hctx, struct blk_mq_tags *tags, struct blk_mq_ctx *ctx, unsigned int tag);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-tag.c (ffffffff814ad1e0)
Location: block/blk-mq-tag.c:200
Inline: False
Direct callers:
  - block/blk-flush.c:mq_flush_data_end_io
  - block/blk-flush.c:flush_end_io
  - block/blk-mq.c:blk_mq_dispatch_rq_list
  - block/blk-mq.c:__blk_mq_free_request
  - block/blk-mq.c:__blk_mq_free_request
```
**Symbols:**

```
ffffffff814ad1e0-ffffffff814ad21b: blk_mq_put_tag (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void blk_mq_put_tag(struct blk_mq_hw_ctx *hctx, struct blk_mq_tags *tags, struct blk_mq_ctx *ctx, unsigned int tag);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-tag.c (ffffffff814db450)
Location: block/blk-mq-tag.c:193
Inline: False
Direct callers:
  - block/blk-flush.c:mq_flush_data_end_io
  - block/blk-flush.c:flush_end_io
  - block/blk-mq.c:blk_mq_dispatch_rq_list
  - block/blk-mq.c:__blk_mq_free_request
  - block/blk-mq.c:__blk_mq_free_request
```
**Symbols:**

```
ffffffff814db450-ffffffff814db48e: blk_mq_put_tag (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void blk_mq_put_tag(struct blk_mq_hw_ctx *hctx, struct blk_mq_tags *tags, struct blk_mq_ctx *ctx, unsigned int tag);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-tag.c (ffffffff814f4880)
Location: block/blk-mq-tag.c:194
Inline: False
Direct callers:
  - block/blk-flush.c:mq_flush_data_end_io
  - block/blk-flush.c:flush_end_io
  - block/blk-mq.c:blk_mq_dispatch_rq_list
  - block/blk-mq.c:__blk_mq_free_request
  - block/blk-mq.c:__blk_mq_free_request
```
**Symbols:**

```
ffffffff814f4880-ffffffff814f48be: blk_mq_put_tag (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void blk_mq_put_tag(struct blk_mq_tags *tags, struct blk_mq_ctx *ctx, unsigned int tag);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-mq-tag.c (ffffffff81554dc0)
Location: block/blk-mq-tag.c:221
Inline: True
Direct callers:
  - block/blk-flush.c:mq_flush_data_end_io
  - block/blk-flush.c:flush_end_io
  - block/blk-mq.c:blk_mq_dispatch_rq_list
  - block/blk-mq.c:blk_mq_dispatch_rq_list
  - block/blk-mq.c:__blk_mq_free_request
  - block/blk-mq.c:__blk_mq_free_request
  - block/blk-mq-tag.c:blk_mq_get_tag
```
**Symbols:**

```
ffffffff81554dc0-ffffffff81554df9: blk_mq_put_tag (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void blk_mq_put_tag(struct blk_mq_tags *tags, struct blk_mq_ctx *ctx, unsigned int tag);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-mq-tag.c (ffffffff81571470)
Location: block/blk-mq-tag.c:181
Inline: True
Direct callers:
  - block/blk-flush.c:mq_flush_data_end_io
  - block/blk-flush.c:flush_end_io
  - block/blk-mq.c:blk_mq_dispatch_rq_list
  - block/blk-mq.c:blk_mq_dispatch_rq_list
  - block/blk-mq.c:__blk_mq_free_request
  - block/blk-mq.c:__blk_mq_free_request
  - block/blk-mq-tag.c:blk_mq_get_tag
```
**Symbols:**

```
ffffffff81571470-ffffffff815714a9: blk_mq_put_tag (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void blk_mq_put_tag(struct blk_mq_tags *tags, struct blk_mq_ctx *ctx, unsigned int tag);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-mq-tag.c (ffffffff815794a0)
Location: block/blk-mq-tag.c:181
Inline: True
Direct callers:
  - block/blk-flush.c:mq_flush_data_end_io
  - block/blk-flush.c:flush_end_io
  - block/blk-mq.c:blk_mq_dispatch_rq_list
  - block/blk-mq.c:blk_mq_dispatch_rq_list
  - block/blk-mq.c:__blk_mq_free_request
  - block/blk-mq.c:__blk_mq_free_request
  - block/blk-mq-tag.c:blk_mq_get_tag
```
**Symbols:**

```
ffffffff815794a0-ffffffff815794d9: blk_mq_put_tag (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void blk_mq_put_tag(struct blk_mq_tags *tags, struct blk_mq_ctx *ctx, unsigned int tag);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-mq-tag.c (ffffffff815de963)
Location: block/blk-mq-tag.c:182
Inline: True
Inline callers:
  - block/blk-mq-tag.c:blk_mq_get_tag
  - block/blk-mq-tag.c:blk_mq_get_tag
Direct callers:
  - block/blk-flush.c:mq_flush_data_end_io
  - block/blk-flush.c:flush_end_io
  - block/blk-mq.c:blk_mq_dispatch_rq_list
  - block/blk-mq.c:blk_mq_dispatch_rq_list
  - block/blk-mq.c:__blk_mq_free_request
  - block/blk-mq.c:__blk_mq_free_request
```
**Symbols:**

```
ffffffff815de9e0-ffffffff815dea19: blk_mq_put_tag (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void blk_mq_put_tag(struct blk_mq_tags *tags, struct blk_mq_ctx *ctx, unsigned int tag);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-mq-tag.c (ffffffff8168cbc4)
Location: block/blk-mq-tag.c:222
Inline: True
Inline callers:
  - block/blk-mq-tag.c:blk_mq_get_tag
  - block/blk-mq-tag.c:blk_mq_get_tag
Direct callers:
  - block/blk-flush.c:mq_flush_data_end_io
  - block/blk-flush.c:flush_end_io
  - block/blk-mq.c:blk_mq_dispatch_rq_list
  - block/blk-mq.c:blk_mq_dispatch_rq_list
  - block/blk-mq.c:__blk_mq_free_request
  - block/blk-mq.c:__blk_mq_free_request
```
**Symbols:**

```
ffffffff8168cc20-ffffffff8168cc71: blk_mq_put_tag (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void blk_mq_put_tag(struct blk_mq_tags *tags, struct blk_mq_ctx *ctx, unsigned int tag);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-mq-tag.c (ffffffff8174b3b9)
Location: block/blk-mq-tag.c:218
Inline: True
Inline callers:
  - block/blk-mq-tag.c:blk_mq_get_tag
  - block/blk-mq-tag.c:blk_mq_get_tag
Direct callers:
  - block/blk-flush.c:mq_flush_data_end_io
  - block/blk-flush.c:flush_end_io
  - block/blk-mq.c:blk_mq_dispatch_rq_list
  - block/blk-mq.c:blk_mq_dispatch_rq_list
  - block/blk-mq.c:__blk_mq_free_request
  - block/blk-mq.c:__blk_mq_free_request
```
**Symbols:**

```
ffffffff8174b430-ffffffff8174b481: blk_mq_put_tag (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void blk_mq_put_tag(struct blk_mq_tags *tags, struct blk_mq_ctx *ctx, unsigned int tag);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-mq-tag.c (ffffffff81787ad9)
Location: block/blk-mq-tag.c:225
Inline: True
Inline callers:
  - block/blk-mq-tag.c:blk_mq_get_tag
  - block/blk-mq-tag.c:blk_mq_get_tag
Direct callers:
  - block/blk-flush.c:mq_flush_data_end_io
  - block/blk-flush.c:flush_end_io
  - block/blk-mq.c:blk_mq_dispatch_rq_list
  - block/blk-mq.c:__blk_mq_free_request
  - block/blk-mq.c:__blk_mq_free_request
```
**Symbols:**

```
ffffffff81787b50-ffffffff81787ba1: blk_mq_put_tag (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void blk_mq_put_tag(struct blk_mq_tags *tags, struct blk_mq_ctx *ctx, unsigned int tag);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-mq-tag.c (ffffffff817ca1a9)
Location: block/blk-mq-tag.c:225
Inline: True
Inline callers:
  - block/blk-mq-tag.c:blk_mq_get_tag
  - block/blk-mq-tag.c:blk_mq_get_tag
Direct callers:
  - block/blk-flush.c:mq_flush_data_end_io
  - block/blk-flush.c:flush_end_io
  - block/blk-mq.c:blk_mq_dispatch_rq_list
  - block/blk-mq.c:__blk_mq_free_request
  - block/blk-mq.c:__blk_mq_free_request
```
**Symbols:**

```
ffffffff817ca220-ffffffff817ca271: blk_mq_put_tag (STB_GLOBAL)
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
void blk_mq_put_tag(struct blk_mq_hw_ctx *hctx, struct blk_mq_tags *tags, struct blk_mq_ctx *ctx, unsigned int tag);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-tag.c (ffff8000105f4680)
Location: block/blk-mq-tag.c:194
Inline: False
Direct callers:
  - block/blk-flush.c:mq_flush_data_end_io
  - block/blk-flush.c:flush_end_io
  - block/blk-mq.c:blk_mq_dispatch_rq_list
  - block/blk-mq.c:__blk_mq_free_request
  - block/blk-mq.c:__blk_mq_free_request
```
**Symbols:**

```
ffff8000105f4680-ffff8000105f4700: blk_mq_put_tag (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void blk_mq_put_tag(struct blk_mq_hw_ctx *hctx, struct blk_mq_tags *tags, struct blk_mq_ctx *ctx, unsigned int tag);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-tag.c (c07a02d0)
Location: block/blk-mq-tag.c:194
Inline: False
Direct callers:
  - block/blk-flush.c:mq_flush_data_end_io
  - block/blk-flush.c:flush_end_io
  - block/blk-mq.c:blk_mq_dispatch_rq_list
  - block/blk-mq.c:__blk_mq_free_request
  - block/blk-mq.c:__blk_mq_free_request
```
**Symbols:**

```
c07a02d0-c07a032c: blk_mq_put_tag (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void blk_mq_put_tag(struct blk_mq_hw_ctx *hctx, struct blk_mq_tags *tags, struct blk_mq_ctx *ctx, unsigned int tag);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-tag.c (c00000000078bf50)
Location: block/blk-mq-tag.c:194
Inline: False
Direct callers:
  - block/blk-flush.c:mq_flush_data_end_io
  - block/blk-flush.c:flush_end_io
  - block/blk-mq.c:blk_mq_dispatch_rq_list
  - block/blk-mq.c:__blk_mq_free_request
  - block/blk-mq.c:__blk_mq_free_request
```
**Symbols:**

```
c00000000078bf50-c00000000078bfe0: blk_mq_put_tag (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void blk_mq_put_tag(struct blk_mq_hw_ctx *hctx, struct blk_mq_tags *tags, struct blk_mq_ctx *ctx, unsigned int tag);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-tag.c (ffffffe00043262e)
Location: block/blk-mq-tag.c:194
Inline: False
Direct callers:
  - block/blk-flush.c:mq_flush_data_end_io
  - block/blk-flush.c:flush_end_io
  - block/blk-mq.c:blk_mq_dispatch_rq_list
  - block/blk-mq.c:__blk_mq_free_request
  - block/blk-mq.c:__blk_mq_free_request
```
**Symbols:**

```
ffffffe00043262e-ffffffe0004326a0: blk_mq_put_tag (STB_GLOBAL)
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
void blk_mq_put_tag(struct blk_mq_hw_ctx *hctx, struct blk_mq_tags *tags, struct blk_mq_ctx *ctx, unsigned int tag);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-tag.c (ffffffff814ece60)
Location: block/blk-mq-tag.c:194
Inline: False
Direct callers:
  - block/blk-flush.c:mq_flush_data_end_io
  - block/blk-flush.c:flush_end_io
  - block/blk-mq.c:blk_mq_dispatch_rq_list
  - block/blk-mq.c:__blk_mq_free_request
  - block/blk-mq.c:__blk_mq_free_request
```
**Symbols:**

```
ffffffff814ece60-ffffffff814ece9e: blk_mq_put_tag (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void blk_mq_put_tag(struct blk_mq_hw_ctx *hctx, struct blk_mq_tags *tags, struct blk_mq_ctx *ctx, unsigned int tag);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-tag.c (ffffffff814dd3b0)
Location: block/blk-mq-tag.c:194
Inline: False
Direct callers:
  - block/blk-flush.c:mq_flush_data_end_io
  - block/blk-flush.c:flush_end_io
  - block/blk-mq.c:blk_mq_dispatch_rq_list
  - block/blk-mq.c:__blk_mq_free_request
  - block/blk-mq.c:__blk_mq_free_request
```
**Symbols:**

```
ffffffff814dd3b0-ffffffff814dd3ee: blk_mq_put_tag (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void blk_mq_put_tag(struct blk_mq_hw_ctx *hctx, struct blk_mq_tags *tags, struct blk_mq_ctx *ctx, unsigned int tag);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-tag.c (ffffffff814e8ef0)
Location: block/blk-mq-tag.c:194
Inline: False
Direct callers:
  - block/blk-flush.c:mq_flush_data_end_io
  - block/blk-flush.c:flush_end_io
  - block/blk-mq.c:blk_mq_dispatch_rq_list
  - block/blk-mq.c:__blk_mq_free_request
  - block/blk-mq.c:__blk_mq_free_request
```
**Symbols:**

```
ffffffff814e8ef0-ffffffff814e8f2e: blk_mq_put_tag (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void blk_mq_put_tag(struct blk_mq_hw_ctx *hctx, struct blk_mq_tags *tags, struct blk_mq_ctx *ctx, unsigned int tag);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-tag.c (ffffffff81501e90)
Location: block/blk-mq-tag.c:194
Inline: False
Direct callers:
  - block/blk-flush.c:mq_flush_data_end_io
  - block/blk-flush.c:flush_end_io
  - block/blk-mq.c:blk_mq_dispatch_rq_list
  - block/blk-mq.c:__blk_mq_free_request
  - block/blk-mq.c:__blk_mq_free_request
```
**Symbols:**

```
ffffffff81501e90-ffffffff81501ece: blk_mq_put_tag (STB_GLOBAL)
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
<details>
<summary>Changed between <code>4.8</code> and <code>4.10</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct blk_mq_ctx *ctx</code>
</li>
<li>
<b>Param removed. </b>
<code>unsigned int *last_tag</code>
</li>
<li>
<b>Param reordered. </b>
<code>hctx, tag, last_tag</code> ➡️ <code>hctx, ctx, tag</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>4.10</code> and <code>4.13</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct blk_mq_tags *tags</code>
</li>
<li>
<b>Param reordered. </b>
<code>hctx, ctx, tag</code> ➡️ <code>hctx, tags, ctx, tag</code>
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
<details>
<summary>Changed between <code>5.4</code> and <code>5.8</code> ⚠️</summary>
<ul>
<li>
<b>Param removed. </b>
<code>struct blk_mq_hw_ctx *hctx</code>
</li>
<li>
<b>Param reordered. </b>
<code>hctx, tags, ctx, tag</code> ➡️ <code>tags, ctx, tag</code>
</li>
</ul>
</details>
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
