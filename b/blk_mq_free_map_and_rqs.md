# Function: <code>blk_mq_free_map_and_rqs</code>

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
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void blk_mq_free_map_and_rqs(struct blk_mq_tag_set *set, struct blk_mq_tags *tags, unsigned int hctx_idx);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff8168a0cc)
Location: block/blk-mq.c:3638
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_free_tag_set
  - block/blk-mq.c:blk_mq_free_tag_set
  - block/blk-mq.c:blk_mq_alloc_set_map_and_rqs
  - block/blk-mq.c:blk_mq_alloc_set_map_and_rqs
  - block/blk-mq.c:__blk_mq_free_map_and_rqs
  - block/blk-mq.c:__blk_mq_free_map_and_rqs
Direct callers:
  - block/blk-mq-tag.c:blk_mq_tag_update_depth
```
**Symbols:**

```
ffffffff8168b7b0-ffffffff8168b818: blk_mq_free_map_and_rqs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void blk_mq_free_map_and_rqs(struct blk_mq_tag_set *set, struct blk_mq_tags *tags, unsigned int hctx_idx);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff8174866c)
Location: block/blk-mq.c:3802
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_free_tag_set
  - block/blk-mq.c:blk_mq_free_tag_set
  - block/blk-mq.c:blk_mq_alloc_set_map_and_rqs
  - block/blk-mq.c:blk_mq_alloc_set_map_and_rqs
  - block/blk-mq.c:__blk_mq_free_map_and_rqs
  - block/blk-mq.c:__blk_mq_free_map_and_rqs
Direct callers:
  - block/blk-mq-tag.c:blk_mq_tag_update_depth
```
**Symbols:**

```
ffffffff817498a0-ffffffff81749908: blk_mq_free_map_and_rqs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void blk_mq_free_map_and_rqs(struct blk_mq_tag_set *set, struct blk_mq_tags *tags, unsigned int hctx_idx);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff81784d7c)
Location: block/blk-mq.c:3814
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_free_tag_set
  - block/blk-mq.c:blk_mq_free_tag_set
  - block/blk-mq.c:blk_mq_alloc_set_map_and_rqs
  - block/blk-mq.c:blk_mq_alloc_set_map_and_rqs
  - block/blk-mq.c:__blk_mq_free_map_and_rqs
  - block/blk-mq.c:__blk_mq_free_map_and_rqs
Direct callers:
  - block/blk-mq-tag.c:blk_mq_tag_update_depth
```
**Symbols:**

```
ffffffff81785fd0-ffffffff81786038: blk_mq_free_map_and_rqs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void blk_mq_free_map_and_rqs(struct blk_mq_tag_set *set, struct blk_mq_tags *tags, unsigned int hctx_idx);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff817c728c)
Location: block/blk-mq.c:3830
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_free_tag_set
  - block/blk-mq.c:blk_mq_free_tag_set
  - block/blk-mq.c:blk_mq_alloc_set_map_and_rqs
  - block/blk-mq.c:blk_mq_alloc_set_map_and_rqs
  - block/blk-mq.c:__blk_mq_free_map_and_rqs
  - block/blk-mq.c:__blk_mq_free_map_and_rqs
Direct callers:
  - block/blk-mq-tag.c:blk_mq_tag_update_depth
```
**Symbols:**

```
ffffffff817c8680-ffffffff817c86e8: blk_mq_free_map_and_rqs (STB_GLOBAL)
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
