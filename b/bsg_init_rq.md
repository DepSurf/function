# Function: <code>bsg_init_rq</code>

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
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int bsg_init_rq(struct request_queue *q, struct request *req, gfp_t gfp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bsg-lib.c (ffffffff81445790)
Location: block/bsg-lib.c:206
Inline: False
```
**Symbols:**

```
ffffffff81445790-ffffffff8144585e: bsg_init_rq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int bsg_init_rq(struct request_queue *q, struct request *req, gfp_t gfp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bsg-lib.c (ffffffff81472330)
Location: block/bsg-lib.c:205
Inline: False
```
**Symbols:**

```
ffffffff81472330-ffffffff8147237a: bsg_init_rq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int bsg_init_rq(struct request_queue *q, struct request *req, gfp_t gfp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bsg-lib.c (ffffffff814a6850)
Location: block/bsg-lib.c:271
Inline: False
```
**Symbols:**

```
ffffffff814a6850-ffffffff814a689a: bsg_init_rq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int bsg_init_rq(struct blk_mq_tag_set *set, struct request *req, unsigned int hctx_idx, unsigned int numa_node);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bsg-lib.c (ffffffff814c06d0)
Location: block/bsg-lib.c:269
Inline: False
```
**Symbols:**

```
ffffffff814c06d0-ffffffff814c0706: bsg_init_rq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int bsg_init_rq(struct blk_mq_tag_set *set, struct request *req, unsigned int hctx_idx, unsigned int numa_node);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bsg-lib.c (ffffffff814eede0)
Location: block/bsg-lib.c:288
Inline: False
```
**Symbols:**

```
ffffffff814eede0-ffffffff814eee16: bsg_init_rq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int bsg_init_rq(struct blk_mq_tag_set *set, struct request *req, unsigned int hctx_idx, unsigned int numa_node);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bsg-lib.c (ffffffff81508290)
Location: block/bsg-lib.c:290
Inline: False
```
**Symbols:**

```
ffffffff81508290-ffffffff815082c6: bsg_init_rq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int bsg_init_rq(struct blk_mq_tag_set *set, struct request *req, unsigned int hctx_idx, unsigned int numa_node);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bsg-lib.c (ffffffff815697b0)
Location: block/bsg-lib.c:290
Inline: False
```
**Symbols:**

```
ffffffff815697b0-ffffffff815697e9: bsg_init_rq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int bsg_init_rq(struct blk_mq_tag_set *set, struct request *req, unsigned int hctx_idx, unsigned int numa_node);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bsg-lib.c (ffffffff81584190)
Location: block/bsg-lib.c:293
Inline: False
```
**Symbols:**

```
ffffffff81584190-ffffffff815841c9: bsg_init_rq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int bsg_init_rq(struct blk_mq_tag_set *set, struct request *req, unsigned int hctx_idx, unsigned int numa_node);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bsg-lib.c (ffffffff8158af90)
Location: block/bsg-lib.c:293
Inline: False
```
**Symbols:**

```
ffffffff8158af90-ffffffff8158afc9: bsg_init_rq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int bsg_init_rq(struct blk_mq_tag_set *set, struct request *req, unsigned int hctx_idx, unsigned int numa_node);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bsg-lib.c (ffffffff815eff90)
Location: block/bsg-lib.c:294
Inline: False
```
**Symbols:**

```
ffffffff815eff90-ffffffff815effc9: bsg_init_rq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int bsg_init_rq(struct blk_mq_tag_set *set, struct request *req, unsigned int hctx_idx, unsigned int numa_node);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bsg-lib.c (ffffffff816a0f80)
Location: block/bsg-lib.c:301
Inline: False
```
**Symbols:**

```
ffffffff816a0f80-ffffffff816a0fc3: bsg_init_rq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int bsg_init_rq(struct blk_mq_tag_set *set, struct request *req, unsigned int hctx_idx, unsigned int numa_node);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bsg-lib.c (ffffffff8175fb60)
Location: block/bsg-lib.c:301
Inline: False
```
**Symbols:**

```
ffffffff8175fb60-ffffffff8175fba3: bsg_init_rq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int bsg_init_rq(struct blk_mq_tag_set *set, struct request *req, unsigned int hctx_idx, unsigned int numa_node);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bsg-lib.c (ffffffff8179ea40)
Location: block/bsg-lib.c:301
Inline: False
```
**Symbols:**

```
ffffffff8179ea40-ffffffff8179ea83: bsg_init_rq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int bsg_init_rq(struct blk_mq_tag_set *set, struct request *req, unsigned int hctx_idx, unsigned int numa_node);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bsg-lib.c (ffffffff817e24f0)
Location: block/bsg-lib.c:301
Inline: False
```
**Symbols:**

```
ffffffff817e24f0-ffffffff817e2562: bsg_init_rq (STB_LOCAL)
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
int bsg_init_rq(struct blk_mq_tag_set *set, struct request *req, unsigned int hctx_idx, unsigned int numa_node);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bsg-lib.c (ffff80001060ad48)
Location: block/bsg-lib.c:290
Inline: False
```
**Symbols:**

```
ffff80001060ad48-ffff80001060ad90: bsg_init_rq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int bsg_init_rq(struct blk_mq_tag_set *set, struct request *req, unsigned int hctx_idx, unsigned int numa_node);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bsg-lib.c (c07b5d08)
Location: block/bsg-lib.c:290
Inline: False
```
**Symbols:**

```
c07b5d08-c07b5d4c: bsg_init_rq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int bsg_init_rq(struct blk_mq_tag_set *set, struct request *req, unsigned int hctx_idx, unsigned int numa_node);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bsg-lib.c (c0000000007a7830)
Location: block/bsg-lib.c:290
Inline: False
```
**Symbols:**

```
c0000000007a7830-c0000000007a7898: bsg_init_rq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int bsg_init_rq(struct blk_mq_tag_set *set, struct request *req, unsigned int hctx_idx, unsigned int numa_node);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bsg-lib.c (ffffffe000443f7c)
Location: block/bsg-lib.c:290
Inline: False
```
**Symbols:**

```
ffffffe000443f7c-ffffffe000443fc4: bsg_init_rq (STB_LOCAL)
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
int bsg_init_rq(struct blk_mq_tag_set *set, struct request *req, unsigned int hctx_idx, unsigned int numa_node);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bsg-lib.c (ffffffff81500870)
Location: block/bsg-lib.c:290
Inline: False
```
**Symbols:**

```
ffffffff81500870-ffffffff815008a6: bsg_init_rq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int bsg_init_rq(struct blk_mq_tag_set *set, struct request *req, unsigned int hctx_idx, unsigned int numa_node);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bsg-lib.c (ffffffff814f0d80)
Location: block/bsg-lib.c:290
Inline: False
```
**Symbols:**

```
ffffffff814f0d80-ffffffff814f0db6: bsg_init_rq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int bsg_init_rq(struct blk_mq_tag_set *set, struct request *req, unsigned int hctx_idx, unsigned int numa_node);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bsg-lib.c (ffffffff814fc900)
Location: block/bsg-lib.c:290
Inline: False
```
**Symbols:**

```
ffffffff814fc900-ffffffff814fc936: bsg_init_rq (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int bsg_init_rq(struct blk_mq_tag_set *set, struct request *req, unsigned int hctx_idx, unsigned int numa_node);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bsg-lib.c (ffffffff815159b0)
Location: block/bsg-lib.c:290
Inline: False
```
**Symbols:**

```
ffffffff815159b0-ffffffff815159e6: bsg_init_rq (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>4.18</code> and <code>5.0</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct blk_mq_tag_set *set</code>
</li>
<li>
<b>Param added. </b>
<code>unsigned int hctx_idx</code>
</li>
<li>
<b>Param added. </b>
<code>unsigned int numa_node</code>
</li>
<li>
<b>Param removed. </b>
<code>struct request_queue *q</code>
</li>
<li>
<b>Param removed. </b>
<code>gfp_t gfp</code>
</li>
</ul>
</details>
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
