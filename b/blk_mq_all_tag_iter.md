# Function: <code>blk_mq_all_tag_iter</code>

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
void blk_mq_all_tag_iter(struct blk_mq_tags *tags, busy_tag_iter_fn *fn, void *priv);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-tag.c (ffffffff81555070)
Location: block/blk-mq-tag.c:376
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_hctx_notify_offline
```
**Symbols:**

```
ffffffff81555070-ffffffff81555274: blk_mq_all_tag_iter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void blk_mq_all_tag_iter(struct blk_mq_tags *tags, busy_tag_iter_fn *fn, void *priv);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-tag.c (ffffffff81571720)
Location: block/blk-mq-tag.c:336
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_hctx_notify_offline
```
**Symbols:**

```
ffffffff81571720-ffffffff8157192d: blk_mq_all_tag_iter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void blk_mq_all_tag_iter(struct blk_mq_tags *tags, busy_tag_iter_fn *fn, void *priv);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-tag.c (ffffffff81579750)
Location: block/blk-mq-tag.c:359
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_hctx_notify_offline
```
**Symbols:**

```
ffffffff81579750-ffffffff8157996b: blk_mq_all_tag_iter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void blk_mq_all_tag_iter(struct blk_mq_tags *tags, busy_tag_iter_fn *fn, void *priv);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/blk-mq-tag.c (0)
Location: block/blk-mq-tag.c:360
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_hctx_notify_offline
```
**Symbols:**

```
ffffffff81cd86b2-ffffffff81cd8758: blk_mq_all_tag_iter.cold (STB_LOCAL)
ffffffff815dea20-ffffffff815dec61: blk_mq_all_tag_iter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void blk_mq_all_tag_iter(struct blk_mq_tags *tags, busy_tag_iter_fn *fn, void *priv);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/blk-mq-tag.c (0)
Location: block/blk-mq-tag.c:416
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_hctx_notify_offline
```
**Symbols:**

```
ffffffff81e8bece-ffffffff81e8bffb: blk_mq_all_tag_iter.cold (STB_LOCAL)
ffffffff8168ccb0-ffffffff8168cfc4: blk_mq_all_tag_iter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void blk_mq_all_tag_iter(struct blk_mq_tags *tags, busy_tag_iter_fn *fn, void *priv);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/blk-mq-tag.c (0)
Location: block/blk-mq-tag.c:410
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_hctx_notify_offline
```
**Symbols:**

```
ffffffff820764a0-ffffffff820765cd: blk_mq_all_tag_iter.cold (STB_LOCAL)
ffffffff8174b4e0-ffffffff8174b7dd: blk_mq_all_tag_iter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void blk_mq_all_tag_iter(struct blk_mq_tags *tags, busy_tag_iter_fn *fn, void *priv);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/blk-mq-tag.c (0)
Location: block/blk-mq-tag.c:417
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_hctx_notify_offline
```
**Symbols:**

```
ffffffff820f6322-ffffffff820f644f: blk_mq_all_tag_iter.cold (STB_LOCAL)
ffffffff81787c00-ffffffff81787efd: blk_mq_all_tag_iter (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void blk_mq_all_tag_iter(struct blk_mq_tags *tags, busy_tag_iter_fn *fn, void *priv);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/blk-mq-tag.c (0)
Location: block/blk-mq-tag.c:417
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_hctx_notify_offline
```
**Symbols:**

```
ffffffff821d3847-ffffffff821d3974: blk_mq_all_tag_iter.cold (STB_LOCAL)
ffffffff817ca2d0-ffffffff817ca5cd: blk_mq_all_tag_iter (STB_GLOBAL)
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
