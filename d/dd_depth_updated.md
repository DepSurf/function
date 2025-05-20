# Function: <code>dd_depth_updated</code>

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
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void dd_depth_updated(struct blk_mq_hw_ctx *hctx);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/mq-deadline.c (ffffffff81601e85)
Location: block/mq-deadline.c:514
Inline: True
Inline callers:
  - block/mq-deadline.c:dd_init_hctx
```
**Symbols:**

```
ffffffff81601550-ffffffff8160159a: dd_depth_updated (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void dd_depth_updated(struct blk_mq_hw_ctx *hctx);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/mq-deadline.c (ffffffff816b4ce5)
Location: block/mq-deadline.c:562
Inline: True
Inline callers:
  - block/mq-deadline.c:dd_init_hctx
```
**Symbols:**

```
ffffffff816b3eb0-ffffffff816b3f08: dd_depth_updated (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void dd_depth_updated(struct blk_mq_hw_ctx *hctx);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/mq-deadline.c (ffffffff817747b5)
Location: block/mq-deadline.c:620
Inline: True
Inline callers:
  - block/mq-deadline.c:dd_init_hctx
```
**Symbols:**

```
ffffffff81773610-ffffffff81773668: dd_depth_updated (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

```c
void dd_depth_updated(struct blk_mq_hw_ctx *hctx);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In block/mq-deadline.c (ffffffff817b2d35)
Location: block/mq-deadline.c:644
Inline: True
Inline callers:
  - block/mq-deadline.c:dd_init_hctx
```
**Symbols:**

```
ffffffff817b24b0-ffffffff817b251c: dd_depth_updated (STB_LOCAL)
ffffffff820f6e21-ffffffff820f6e3f: dd_depth_updated.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
void dd_depth_updated(struct blk_mq_hw_ctx *hctx);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In block/mq-deadline.c (ffffffff817f6b65)
Location: block/mq-deadline.c:644
Inline: True
Inline callers:
  - block/mq-deadline.c:dd_init_hctx
```
**Symbols:**

```
ffffffff817f62c0-ffffffff817f632c: dd_depth_updated (STB_LOCAL)
ffffffff821d426f-ffffffff821d428d: dd_depth_updated.cold (STB_LOCAL)
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
