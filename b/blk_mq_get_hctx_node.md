# Function: <code>blk_mq_get_hctx_node</code>

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
In <code>5.15</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int blk_mq_get_hctx_node(struct blk_mq_tag_set *set, unsigned int hctx_idx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff81683020)
Location: block/blk-mq.c:3139
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_realloc_hw_ctxs
  - block/blk-mq.c:blk_mq_alloc_map_and_rqs
  - block/blk-mq.c:blk_mq_alloc_rqs
```
**Symbols:**

```
ffffffff81683020-ffffffff81683111: blk_mq_get_hctx_node (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
int blk_mq_get_hctx_node(struct blk_mq_tag_set *set, unsigned int hctx_idx);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff81745382)
Location: block/blk-mq.c:3302
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_realloc_hw_ctxs
Direct callers:
  - block/blk-mq.c:blk_mq_alloc_map_and_rqs
  - block/blk-mq.c:blk_mq_alloc_rqs
```
**Symbols:**

```
ffffffff81740850-ffffffff81740941: blk_mq_get_hctx_node (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
int blk_mq_get_hctx_node(struct blk_mq_tag_set *set, unsigned int hctx_idx);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff817812f2)
Location: block/blk-mq.c:3314
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_realloc_hw_ctxs
Direct callers:
  - block/blk-mq.c:blk_mq_alloc_map_and_rqs
  - block/blk-mq.c:blk_mq_alloc_rqs
```
**Symbols:**

```
ffffffff8177cad0-ffffffff8177cbba: blk_mq_get_hctx_node (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
int blk_mq_get_hctx_node(struct blk_mq_tag_set *set, unsigned int hctx_idx);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff817c3b52)
Location: block/blk-mq.c:3330
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_realloc_hw_ctxs
Direct callers:
  - block/blk-mq.c:blk_mq_alloc_map_and_rqs
  - block/blk-mq.c:blk_mq_alloc_rqs
```
**Symbols:**

```
ffffffff817beed0-ffffffff817befba: blk_mq_get_hctx_node (STB_LOCAL)
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
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
