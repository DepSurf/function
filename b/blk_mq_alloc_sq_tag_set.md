# Function: <code>blk_mq_alloc_sq_tag_set</code>

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
<summary>In <code>5.15</code>: ✅</summary>

```c
int blk_mq_alloc_sq_tag_set(struct blk_mq_tag_set *set, const struct blk_mq_ops *ops, unsigned int queue_depth, unsigned int set_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff815ddaa0)
Location: block/blk-mq.c:3569
Inline: False
```
**Symbols:**

```
ffffffff815ddaa0-ffffffff815ddb0c: blk_mq_alloc_sq_tag_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int blk_mq_alloc_sq_tag_set(struct blk_mq_tag_set *set, const struct blk_mq_ops *ops, unsigned int queue_depth, unsigned int set_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff8168b720)
Location: block/blk-mq.c:4320
Inline: False
```
**Symbols:**

```
ffffffff8168b720-ffffffff8168b7a2: blk_mq_alloc_sq_tag_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int blk_mq_alloc_sq_tag_set(struct blk_mq_tag_set *set, const struct blk_mq_ops *ops, unsigned int queue_depth, unsigned int set_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff81749800)
Location: block/blk-mq.c:4532
Inline: False
```
**Symbols:**

```
ffffffff81749800-ffffffff81749882: blk_mq_alloc_sq_tag_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int blk_mq_alloc_sq_tag_set(struct blk_mq_tag_set *set, const struct blk_mq_ops *ops, unsigned int queue_depth, unsigned int set_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff81785f40)
Location: block/blk-mq.c:4531
Inline: False
```
**Symbols:**

```
ffffffff81785f40-ffffffff81785fbe: blk_mq_alloc_sq_tag_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int blk_mq_alloc_sq_tag_set(struct blk_mq_tag_set *set, const struct blk_mq_ops *ops, unsigned int queue_depth, unsigned int set_flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff817c85f0)
Location: block/blk-mq.c:4558
Inline: False
```
**Symbols:**

```
ffffffff817c85f0-ffffffff817c866e: blk_mq_alloc_sq_tag_set (STB_GLOBAL)
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
