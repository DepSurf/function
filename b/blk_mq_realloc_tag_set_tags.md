# Function: <code>blk_mq_realloc_tag_set_tags</code>

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
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In block/blk-mq.c (ffffffff81553da4)
Location: block/blk-mq.c:3236
Inline: True
Inline callers:
  - block/blk-mq.c:__blk_mq_update_nr_hw_queues
  - block/blk-mq.c:blk_mq_alloc_tag_set
Direct callers:
  - block/blk-mq.c:__blk_mq_update_nr_hw_queues
  - block/blk-mq.c:blk_mq_alloc_tag_set
```
**Symbols:**

```
ffffffff81550d20-ffffffff81550dab: blk_mq_realloc_tag_set_tags.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In block/blk-mq.c (ffffffff81570464)
Location: block/blk-mq.c:3343
Inline: True
Inline callers:
  - block/blk-mq.c:__blk_mq_update_nr_hw_queues
  - block/blk-mq.c:blk_mq_alloc_tag_set
Direct callers:
  - block/blk-mq.c:__blk_mq_update_nr_hw_queues
  - block/blk-mq.c:blk_mq_alloc_tag_set
```
**Symbols:**

```
ffffffff8156d540-ffffffff8156d5d1: blk_mq_realloc_tag_set_tags.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In block/blk-mq.c (ffffffff815783c1)
Location: block/blk-mq.c:3405
Inline: True
Inline callers:
  - block/blk-mq.c:__blk_mq_update_nr_hw_queues
  - block/blk-mq.c:blk_mq_alloc_tag_set
Direct callers:
  - block/blk-mq.c:__blk_mq_update_nr_hw_queues
  - block/blk-mq.c:blk_mq_alloc_tag_set
```
**Symbols:**

```
ffffffff815746c0-ffffffff81574751: blk_mq_realloc_tag_set_tags.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In block/blk-mq.c (ffffffff815dd4a1)
Location: block/blk-mq.c:3437
Inline: True
Inline callers:
  - block/blk-mq.c:__blk_mq_update_nr_hw_queues
  - block/blk-mq.c:blk_mq_alloc_tag_set
Direct callers:
  - block/blk-mq.c:__blk_mq_update_nr_hw_queues
  - block/blk-mq.c:blk_mq_alloc_tag_set
```
**Symbols:**

```
ffffffff815d8b70-ffffffff815d8c01: blk_mq_realloc_tag_set_tags.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int blk_mq_realloc_tag_set_tags(struct blk_mq_tag_set *set, int cur_nr_hw_queues, int new_nr_hw_queues);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff81683160)
Location: block/blk-mq.c:4200
Inline: False
Direct callers:
  - block/blk-mq.c:__blk_mq_update_nr_hw_queues
  - block/blk-mq.c:blk_mq_alloc_tag_set
```
**Symbols:**

```
ffffffff81683160-ffffffff816831fa: blk_mq_realloc_tag_set_tags (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int blk_mq_realloc_tag_set_tags(struct blk_mq_tag_set *set, int new_nr_hw_queues);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff81745810)
Location: block/blk-mq.c:4402
Inline: False
Direct callers:
  - block/blk-mq.c:__blk_mq_update_nr_hw_queues
```
**Symbols:**

```
ffffffff81745810-ffffffff8174589a: blk_mq_realloc_tag_set_tags (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int blk_mq_realloc_tag_set_tags(struct blk_mq_tag_set *set, int new_nr_hw_queues);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff8177cdd0)
Location: block/blk-mq.c:4401
Inline: False
Direct callers:
  - block/blk-mq.c:__blk_mq_update_nr_hw_queues
```
**Symbols:**

```
ffffffff8177cdd0-ffffffff8177ce5a: blk_mq_realloc_tag_set_tags (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int blk_mq_realloc_tag_set_tags(struct blk_mq_tag_set *set, int new_nr_hw_queues);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff817c7ad0)
Location: block/blk-mq.c:4417
Inline: False
Direct callers:
  - block/blk-mq.c:__blk_mq_update_nr_hw_queues
```
**Symbols:**

```
ffffffff817c7ad0-ffffffff817c7bbb: blk_mq_realloc_tag_set_tags (STB_LOCAL)
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
<details>
<summary>Changed between <code>5.19</code> and <code>6.2</code> ⚠️</summary>
<ul>
<li>
<b>Param removed. </b>
<code>int cur_nr_hw_queues</code>
</li>
<li>
<b>Param reordered. </b>
<code>set, cur_nr_hw_queues, new_nr_hw_queues</code> ➡️ <code>set, new_nr_hw_queues</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
