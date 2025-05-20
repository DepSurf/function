# Function: <code>dm_mq_init_request</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int dm_mq_init_request(void *data, struct request *rq, unsigned int hctx_idx, unsigned int request_idx, unsigned int numa_node);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffff816a01a0)
Location: drivers/md/dm.c:2632
Inline: False
```
**Symbols:**

```
ffffffff816a01a0-ffffffff816a01b4: dm_mq_init_request (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int dm_mq_init_request(void *data, struct request *rq, unsigned int hctx_idx, unsigned int request_idx, unsigned int numa_node);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-rq.c (ffffffff8170ebe0)
Location: drivers/md/dm-rq.c:837
Inline: False
```
**Symbols:**

```
ffffffff8170ebe0-ffffffff8170ec0b: dm_mq_init_request (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int dm_mq_init_request(void *data, struct request *rq, unsigned int hctx_idx, unsigned int request_idx, unsigned int numa_node);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-rq.c (ffffffff81740bf0)
Location: drivers/md/dm-rq.c:855
Inline: False
```
**Symbols:**

```
ffffffff81740bf0-ffffffff81740c1b: dm_mq_init_request (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int dm_mq_init_request(struct blk_mq_tag_set *set, struct request *rq, unsigned int hctx_idx, unsigned int numa_node);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-rq.c (ffffffff8175a9c0)
Location: drivers/md/dm-rq.c:724
Inline: False
```
**Symbols:**

```
ffffffff8175a9c0-ffffffff8175a9ef: dm_mq_init_request (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int dm_mq_init_request(struct blk_mq_tag_set *set, struct request *rq, unsigned int hctx_idx, unsigned int numa_node);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-rq.c (ffffffff817ccbf0)
Location: drivers/md/dm-rq.c:721
Inline: False
```
**Symbols:**

```
ffffffff817ccbf0-ffffffff817ccc1f: dm_mq_init_request (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int dm_mq_init_request(struct blk_mq_tag_set *set, struct request *rq, unsigned int hctx_idx, unsigned int numa_node);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-rq.c (ffffffff818159b0)
Location: drivers/md/dm-rq.c:735
Inline: False
```
**Symbols:**

```
ffffffff818159b0-ffffffff818159df: dm_mq_init_request (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int dm_mq_init_request(struct blk_mq_tag_set *set, struct request *rq, unsigned int hctx_idx, unsigned int numa_node);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-rq.c (ffffffff81841950)
Location: drivers/md/dm-rq.c:451
Inline: False
```
**Symbols:**

```
ffffffff81841950-ffffffff8184197f: dm_mq_init_request (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int dm_mq_init_request(struct blk_mq_tag_set *set, struct request *rq, unsigned int hctx_idx, unsigned int numa_node);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-rq.c (ffffffff81884770)
Location: drivers/md/dm-rq.c:470
Inline: False
```
**Symbols:**

```
ffffffff81884770-ffffffff8188479f: dm_mq_init_request (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int dm_mq_init_request(struct blk_mq_tag_set *set, struct request *rq, unsigned int hctx_idx, unsigned int numa_node);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-rq.c (ffffffff818b6660)
Location: drivers/md/dm-rq.c:471
Inline: False
```
**Symbols:**

```
ffffffff818b6660-ffffffff818b668f: dm_mq_init_request (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int dm_mq_init_request(struct blk_mq_tag_set *set, struct request *rq, unsigned int hctx_idx, unsigned int numa_node);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-rq.c (ffffffff81986f90)
Location: drivers/md/dm-rq.c:464
Inline: False
```
**Symbols:**

```
ffffffff81986f90-ffffffff81986fbf: dm_mq_init_request (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int dm_mq_init_request(struct blk_mq_tag_set *set, struct request *rq, unsigned int hctx_idx, unsigned int numa_node);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-rq.c (ffffffff8198af70)
Location: drivers/md/dm-rq.c:465
Inline: False
```
**Symbols:**

```
ffffffff8198af70-ffffffff8198af9f: dm_mq_init_request (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int dm_mq_init_request(struct blk_mq_tag_set *set, struct request *rq, unsigned int hctx_idx, unsigned int numa_node);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-rq.c (ffffffff8196f660)
Location: drivers/md/dm-rq.c:465
Inline: False
```
**Symbols:**

```
ffffffff8196f660-ffffffff8196f68f: dm_mq_init_request (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int dm_mq_init_request(struct blk_mq_tag_set *set, struct request *rq, unsigned int hctx_idx, unsigned int numa_node);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-rq.c (ffffffff81a17fa0)
Location: drivers/md/dm-rq.c:465
Inline: False
```
**Symbols:**

```
ffffffff81a17fa0-ffffffff81a17fcf: dm_mq_init_request (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int dm_mq_init_request(struct blk_mq_tag_set *set, struct request *rq, unsigned int hctx_idx, unsigned int numa_node);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-rq.c (ffffffff81b80c90)
Location: drivers/md/dm-rq.c:453
Inline: False
```
**Symbols:**

```
ffffffff81b80c90-ffffffff81b80cc7: dm_mq_init_request (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int dm_mq_init_request(struct blk_mq_tag_set *set, struct request *rq, unsigned int hctx_idx, unsigned int numa_node);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-rq.c (ffffffff81d1ef80)
Location: drivers/md/dm-rq.c:454
Inline: False
```
**Symbols:**

```
ffffffff81d1ef80-ffffffff81d1efb7: dm_mq_init_request (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int dm_mq_init_request(struct blk_mq_tag_set *set, struct request *rq, unsigned int hctx_idx, unsigned int numa_node);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-rq.c (ffffffff81d88160)
Location: drivers/md/dm-rq.c:457
Inline: False
```
**Symbols:**

```
ffffffff81d88160-ffffffff81d88197: dm_mq_init_request (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int dm_mq_init_request(struct blk_mq_tag_set *set, struct request *rq, unsigned int hctx_idx, unsigned int numa_node);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-rq.c (ffffffff81e3f870)
Location: drivers/md/dm-rq.c:457
Inline: False
```
**Symbols:**

```
ffffffff81e3f870-ffffffff81e3f8a7: dm_mq_init_request (STB_LOCAL)
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
int dm_mq_init_request(struct blk_mq_tag_set *set, struct request *rq, unsigned int hctx_idx, unsigned int numa_node);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-rq.c (ffff800010b0e640)
Location: drivers/md/dm-rq.c:471
Inline: False
```
**Symbols:**

```
ffff800010b0e640-ffff800010b0e688: dm_mq_init_request (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int dm_mq_init_request(struct blk_mq_tag_set *set, struct request *rq, unsigned int hctx_idx, unsigned int numa_node);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-rq.c (c0beca84)
Location: drivers/md/dm-rq.c:471
Inline: False
```
**Symbols:**

```
c0beca84-c0becab8: dm_mq_init_request (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int dm_mq_init_request(struct blk_mq_tag_set *set, struct request *rq, unsigned int hctx_idx, unsigned int numa_node);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-rq.c (c000000000c01600)
Location: drivers/md/dm-rq.c:471
Inline: False
```
**Symbols:**

```
c000000000c01600-c000000000c0162c: dm_mq_init_request (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int dm_mq_init_request(struct blk_mq_tag_set *set, struct request *rq, unsigned int hctx_idx, unsigned int numa_node);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-rq.c (ffffffe0006fb95c)
Location: drivers/md/dm-rq.c:471
Inline: False
```
**Symbols:**

```
ffffffe0006fb95c-ffffffe0006fb99c: dm_mq_init_request (STB_LOCAL)
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
int dm_mq_init_request(struct blk_mq_tag_set *set, struct request *rq, unsigned int hctx_idx, unsigned int numa_node);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-rq.c (ffffffff8185c4e0)
Location: drivers/md/dm-rq.c:471
Inline: False
```
**Symbols:**

```
ffffffff8185c4e0-ffffffff8185c50f: dm_mq_init_request (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int dm_mq_init_request(struct blk_mq_tag_set *set, struct request *rq, unsigned int hctx_idx, unsigned int numa_node);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-rq.c (ffffffff81823ab0)
Location: drivers/md/dm-rq.c:471
Inline: False
```
**Symbols:**

```
ffffffff81823ab0-ffffffff81823adf: dm_mq_init_request (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int dm_mq_init_request(struct blk_mq_tag_set *set, struct request *rq, unsigned int hctx_idx, unsigned int numa_node);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-rq.c (ffffffff818abb10)
Location: drivers/md/dm-rq.c:471
Inline: False
```
**Symbols:**

```
ffffffff818abb10-ffffffff818abb3f: dm_mq_init_request (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int dm_mq_init_request(struct blk_mq_tag_set *set, struct request *rq, unsigned int hctx_idx, unsigned int numa_node);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-rq.c (ffffffff818c7d50)
Location: drivers/md/dm-rq.c:471
Inline: False
```
**Symbols:**

```
ffffffff818c7d50-ffffffff818c7d7f: dm_mq_init_request (STB_LOCAL)
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
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>4.10</code> and <code>4.13</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct blk_mq_tag_set *set</code>
</li>
<li>
<b>Param removed. </b>
<code>void *data</code>
</li>
<li>
<b>Param removed. </b>
<code>unsigned int request_idx</code>
</li>
<li>
<b>Param reordered. </b>
<code>data, rq, hctx_idx, request_idx, numa_node</code> ➡️ <code>set, rq, hctx_idx, numa_node</code>
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
