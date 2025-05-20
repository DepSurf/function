# Function: <code>blk_mq_init_sq_queue</code>

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
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
struct request_queue *blk_mq_init_sq_queue(struct blk_mq_tag_set *set, const struct blk_mq_ops *ops, unsigned int queue_depth, unsigned int set_flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff814ac6c0)
Location: block/blk-mq.c:2657
Inline: True
```
**Symbols:**

```
ffffffff814ac6c0-ffffffff814ac75a: blk_mq_init_sq_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
struct request_queue *blk_mq_init_sq_queue(struct blk_mq_tag_set *set, const struct blk_mq_ops *ops, unsigned int queue_depth, unsigned int set_flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff814da8e0)
Location: block/blk-mq.c:2703
Inline: True
```
**Symbols:**

```
ffffffff814da8e0-ffffffff814da986: blk_mq_init_sq_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
struct request_queue *blk_mq_init_sq_queue(struct blk_mq_tag_set *set, const struct blk_mq_ops *ops, unsigned int queue_depth, unsigned int set_flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff814f3ca0)
Location: block/blk-mq.c:2726
Inline: True
```
**Symbols:**

```
ffffffff814f3ca0-ffffffff814f3d46: blk_mq_init_sq_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct request_queue *blk_mq_init_sq_queue(struct blk_mq_tag_set *set, const struct blk_mq_ops *ops, unsigned int queue_depth, unsigned int set_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff81554290)
Location: block/blk-mq.c:2926
Inline: False
```
**Symbols:**

```
ffffffff81554290-ffffffff81554372: blk_mq_init_sq_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct request_queue *blk_mq_init_sq_queue(struct blk_mq_tag_set *set, const struct blk_mq_ops *ops, unsigned int queue_depth, unsigned int set_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff815709a0)
Location: block/blk-mq.c:3031
Inline: False
```
**Symbols:**

```
ffffffff815709a0-ffffffff81570a82: blk_mq_init_sq_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct request_queue *blk_mq_init_sq_queue(struct blk_mq_tag_set *set, const struct blk_mq_ops *ops, unsigned int queue_depth, unsigned int set_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff81578900)
Location: block/blk-mq.c:3091
Inline: False
```
**Symbols:**

```
ffffffff81578900-ffffffff815789e2: blk_mq_init_sq_queue (STB_GLOBAL)
```
</details>
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
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
struct request_queue *blk_mq_init_sq_queue(struct blk_mq_tag_set *set, const struct blk_mq_ops *ops, unsigned int queue_depth, unsigned int set_flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffff8000105f3530)
Location: block/blk-mq.c:2726
Inline: True
```
**Symbols:**

```
ffff8000105f3530-ffff8000105f35e0: blk_mq_init_sq_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
struct request_queue *blk_mq_init_sq_queue(struct blk_mq_tag_set *set, const struct blk_mq_ops *ops, unsigned int queue_depth, unsigned int set_flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (c079f680)
Location: block/blk-mq.c:2726
Inline: True
Direct callers:
  - drivers/mtd/mtd_blkdevs.c:add_mtd_blktrans_dev
```
**Symbols:**

```
c079f680-c079f708: blk_mq_init_sq_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
struct request_queue *blk_mq_init_sq_queue(struct blk_mq_tag_set *set, const struct blk_mq_ops *ops, unsigned int queue_depth, unsigned int set_flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (c00000000078adc0)
Location: block/blk-mq.c:2726
Inline: True
```
**Symbols:**

```
c00000000078adc0-c00000000078ae84: blk_mq_init_sq_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
struct request_queue *blk_mq_init_sq_queue(struct blk_mq_tag_set *set, const struct blk_mq_ops *ops, unsigned int queue_depth, unsigned int set_flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffe000431b9e)
Location: block/blk-mq.c:2726
Inline: True
```
**Symbols:**

```
ffffffe000431b9e-ffffffe000431c24: blk_mq_init_sq_queue (STB_GLOBAL)
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
struct request_queue *blk_mq_init_sq_queue(struct blk_mq_tag_set *set, const struct blk_mq_ops *ops, unsigned int queue_depth, unsigned int set_flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff814ec280)
Location: block/blk-mq.c:2726
Inline: True
```
**Symbols:**

```
ffffffff814ec280-ffffffff814ec326: blk_mq_init_sq_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
struct request_queue *blk_mq_init_sq_queue(struct blk_mq_tag_set *set, const struct blk_mq_ops *ops, unsigned int queue_depth, unsigned int set_flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff814dc7d0)
Location: block/blk-mq.c:2726
Inline: True
```
**Symbols:**

```
ffffffff814dc7d0-ffffffff814dc876: blk_mq_init_sq_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
struct request_queue *blk_mq_init_sq_queue(struct blk_mq_tag_set *set, const struct blk_mq_ops *ops, unsigned int queue_depth, unsigned int set_flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff814e8310)
Location: block/blk-mq.c:2726
Inline: True
```
**Symbols:**

```
ffffffff814e8310-ffffffff814e83b6: blk_mq_init_sq_queue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
struct request_queue *blk_mq_init_sq_queue(struct blk_mq_tag_set *set, const struct blk_mq_ops *ops, unsigned int queue_depth, unsigned int set_flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff815012b0)
Location: block/blk-mq.c:2726
Inline: True
```
**Symbols:**

```
ffffffff815012b0-ffffffff81501356: blk_mq_init_sq_queue (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
