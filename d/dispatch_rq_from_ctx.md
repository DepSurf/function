# Function: <code>dispatch_rq_from_ctx</code>

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
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
bool dispatch_rq_from_ctx(struct sbitmap *sb, unsigned int bitnr, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff8145a520)
Location: block/blk-mq.c:927
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_dequeue_from_ctx
```
**Symbols:**

```
ffffffff8145a520-ffffffff8145a5c5: dispatch_rq_from_ctx (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
bool dispatch_rq_from_ctx(struct sbitmap *sb, unsigned int bitnr, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff8148faf0)
Location: block/blk-mq.c:925
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_dequeue_from_ctx
```
**Symbols:**

```
ffffffff8148faf0-ffffffff8148fb99: dispatch_rq_from_ctx (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
bool dispatch_rq_from_ctx(struct sbitmap *sb, unsigned int bitnr, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff814a9560)
Location: block/blk-mq.c:998
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_dequeue_from_ctx
```
**Symbols:**

```
ffffffff814a9560-ffffffff814a9634: dispatch_rq_from_ctx (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
bool dispatch_rq_from_ctx(struct sbitmap *sb, unsigned int bitnr, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff814d72d0)
Location: block/blk-mq.c:997
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_dequeue_from_ctx
```
**Symbols:**

```
ffffffff814d72d0-ffffffff814d73a4: dispatch_rq_from_ctx (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
bool dispatch_rq_from_ctx(struct sbitmap *sb, unsigned int bitnr, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff814f0650)
Location: block/blk-mq.c:1013
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_dequeue_from_ctx
```
**Symbols:**

```
ffffffff814f0650-ffffffff814f0724: dispatch_rq_from_ctx (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
bool dispatch_rq_from_ctx(struct sbitmap *sb, unsigned int bitnr, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff81550a90)
Location: block/blk-mq.c:1012
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_dequeue_from_ctx
```
**Symbols:**

```
ffffffff81550a90-ffffffff81550b54: dispatch_rq_from_ctx (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
bool dispatch_rq_from_ctx(struct sbitmap *sb, unsigned int bitnr, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff8156d1d0)
Location: block/blk-mq.c:1062
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_dequeue_from_ctx
```
**Symbols:**

```
ffffffff8156d1d0-ffffffff8156d294: dispatch_rq_from_ctx (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
bool dispatch_rq_from_ctx(struct sbitmap *sb, unsigned int bitnr, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff815750f0)
Location: block/blk-mq.c:1020
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_dequeue_from_ctx
```
**Symbols:**

```
ffffffff815750f0-ffffffff815751b4: dispatch_rq_from_ctx (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
bool dispatch_rq_from_ctx(struct sbitmap *sb, unsigned int bitnr, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/blk-mq.c (0)
Location: block/blk-mq.c:1026
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_dequeue_from_ctx
```
**Symbols:**

```
ffffffff815d9580-ffffffff815d96d2: dispatch_rq_from_ctx (STB_LOCAL)
ffffffff81cd83fc-ffffffff81cd8443: dispatch_rq_from_ctx.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
bool dispatch_rq_from_ctx(struct sbitmap *sb, unsigned int bitnr, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/blk-mq.c (0)
Location: block/blk-mq.c:1565
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_dequeue_from_ctx
```
**Symbols:**

```
ffffffff81683d00-ffffffff81683e58: dispatch_rq_from_ctx (STB_LOCAL)
ffffffff81e8b88f-ffffffff81e8b8d2: dispatch_rq_from_ctx.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
bool dispatch_rq_from_ctx(struct sbitmap *sb, unsigned int bitnr, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/blk-mq.c (0)
Location: block/blk-mq.c:1726
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_dequeue_from_ctx
```
**Symbols:**

```
ffffffff81741a90-ffffffff81741be8: dispatch_rq_from_ctx (STB_LOCAL)
ffffffff82075f4b-ffffffff82075f8e: dispatch_rq_from_ctx.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
bool dispatch_rq_from_ctx(struct sbitmap *sb, unsigned int bitnr, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/blk-mq.c (0)
Location: block/blk-mq.c:1719
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_dequeue_from_ctx
```
**Symbols:**

```
ffffffff8177d480-ffffffff8177d5d8: dispatch_rq_from_ctx (STB_LOCAL)
ffffffff820f5dd4-ffffffff820f5e17: dispatch_rq_from_ctx.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
bool dispatch_rq_from_ctx(struct sbitmap *sb, unsigned int bitnr, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/blk-mq.c (0)
Location: block/blk-mq.c:1734
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_dequeue_from_ctx
```
**Symbols:**

```
ffffffff817bf810-ffffffff817bf968: dispatch_rq_from_ctx (STB_LOCAL)
ffffffff821d32de-ffffffff821d3321: dispatch_rq_from_ctx.cold (STB_LOCAL)
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
bool dispatch_rq_from_ctx(struct sbitmap *sb, unsigned int bitnr, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffff8000105eeae8)
Location: block/blk-mq.c:1013
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_dequeue_from_ctx
```
**Symbols:**

```
ffff8000105eeae8-ffff8000105eec24: dispatch_rq_from_ctx (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
bool dispatch_rq_from_ctx(struct sbitmap *sb, unsigned int bitnr, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (c0799f50)
Location: block/blk-mq.c:1013
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_dequeue_from_ctx
```
**Symbols:**

```
c0799f50-c079a024: dispatch_rq_from_ctx (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
bool dispatch_rq_from_ctx(struct sbitmap *sb, unsigned int bitnr, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (c000000000782bf0)
Location: block/blk-mq.c:1013
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_dequeue_from_ctx
```
**Symbols:**

```
c000000000782bf0-c000000000782d7c: dispatch_rq_from_ctx (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
bool dispatch_rq_from_ctx(struct sbitmap *sb, unsigned int bitnr, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffe00042ea36)
Location: block/blk-mq.c:1013
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_dequeue_from_ctx
```
**Symbols:**

```
ffffffe00042ea36-ffffffe00042eb64: dispatch_rq_from_ctx (STB_LOCAL)
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
bool dispatch_rq_from_ctx(struct sbitmap *sb, unsigned int bitnr, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff814e8c30)
Location: block/blk-mq.c:1013
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_dequeue_from_ctx
```
**Symbols:**

```
ffffffff814e8c30-ffffffff814e8d04: dispatch_rq_from_ctx (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
bool dispatch_rq_from_ctx(struct sbitmap *sb, unsigned int bitnr, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff814d91a0)
Location: block/blk-mq.c:1013
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_dequeue_from_ctx
```
**Symbols:**

```
ffffffff814d91a0-ffffffff814d9274: dispatch_rq_from_ctx (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
bool dispatch_rq_from_ctx(struct sbitmap *sb, unsigned int bitnr, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff814e4cc0)
Location: block/blk-mq.c:1013
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_dequeue_from_ctx
```
**Symbols:**

```
ffffffff814e4cc0-ffffffff814e4d94: dispatch_rq_from_ctx (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
bool dispatch_rq_from_ctx(struct sbitmap *sb, unsigned int bitnr, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff814fc610)
Location: block/blk-mq.c:1013
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_dequeue_from_ctx
```
**Symbols:**

```
ffffffff814fc610-ffffffff814fc6e2: dispatch_rq_from_ctx (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
