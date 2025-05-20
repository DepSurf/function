# Function: <code>blk_mq_hctx_set_fq_lock_class</code>

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
In <code>5.8</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void blk_mq_hctx_set_fq_lock_class(struct blk_mq_hw_ctx *hctx, struct lock_class_key *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-flush.c (ffffffff81563830)
Location: block/blk-flush.c:512
Inline: False
```
**Symbols:**

```
ffffffff81563830-ffffffff8156383b: blk_mq_hctx_set_fq_lock_class (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void blk_mq_hctx_set_fq_lock_class(struct blk_mq_hw_ctx *hctx, struct lock_class_key *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-flush.c (ffffffff8156bfa0)
Location: block/blk-flush.c:506
Inline: False
```
**Symbols:**

```
ffffffff8156bfa0-ffffffff8156bfab: blk_mq_hctx_set_fq_lock_class (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void blk_mq_hctx_set_fq_lock_class(struct blk_mq_hw_ctx *hctx, struct lock_class_key *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-flush.c (ffffffff815d0420)
Location: block/blk-flush.c:521
Inline: False
```
**Symbols:**

```
ffffffff815d0420-ffffffff815d042b: blk_mq_hctx_set_fq_lock_class (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void blk_mq_hctx_set_fq_lock_class(struct blk_mq_hw_ctx *hctx, struct lock_class_key *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-flush.c (ffffffff8167bc30)
Location: block/blk-flush.c:525
Inline: False
```
**Symbols:**

```
ffffffff8167bc30-ffffffff8167bc3f: blk_mq_hctx_set_fq_lock_class (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void blk_mq_hctx_set_fq_lock_class(struct blk_mq_hw_ctx *hctx, struct lock_class_key *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-flush.c (ffffffff81738490)
Location: block/blk-flush.c:528
Inline: False
```
**Symbols:**

```
ffffffff81738490-ffffffff8173849f: blk_mq_hctx_set_fq_lock_class (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void blk_mq_hctx_set_fq_lock_class(struct blk_mq_hw_ctx *hctx, struct lock_class_key *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-flush.c (ffffffff81774a60)
Location: block/blk-flush.c:537
Inline: False
```
**Symbols:**

```
ffffffff81774a60-ffffffff81774a6f: blk_mq_hctx_set_fq_lock_class (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void blk_mq_hctx_set_fq_lock_class(struct blk_mq_hw_ctx *hctx, struct lock_class_key *key);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-flush.c (ffffffff817b6de0)
Location: block/blk-flush.c:534
Inline: False
```
**Symbols:**

```
ffffffff817b6de0-ffffffff817b6def: blk_mq_hctx_set_fq_lock_class (STB_GLOBAL)
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
