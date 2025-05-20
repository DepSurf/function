# Function: <code>ioc_rqos_merge</code>

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
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void ioc_rqos_merge(struct rq_qos *rqos, struct request *rq, struct bio *bio);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-iocost.c (ffffffff81510030)
Location: block/blk-iocost.c:1798
Inline: False
```
**Symbols:**

```
ffffffff81510030-ffffffff8151016e: ioc_rqos_merge (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void ioc_rqos_merge(struct rq_qos *rqos, struct request *rq, struct bio *bio);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-iocost.c (ffffffff81571110)
Location: block/blk-iocost.c:1848
Inline: False
```
**Symbols:**

```
ffffffff81571110-ffffffff815712a2: ioc_rqos_merge (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void ioc_rqos_merge(struct rq_qos *rqos, struct request *rq, struct bio *bio);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-iocost.c (ffffffff815904f0)
Location: block/blk-iocost.c:2678
Inline: False
```
**Symbols:**

```
ffffffff815904f0-ffffffff815906ef: ioc_rqos_merge (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void ioc_rqos_merge(struct rq_qos *rqos, struct request *rq, struct bio *bio);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-iocost.c (ffffffff815972a0)
Location: block/blk-iocost.c:2685
Inline: False
```
**Symbols:**

```
ffffffff815972a0-ffffffff8159749e: ioc_rqos_merge (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void ioc_rqos_merge(struct rq_qos *rqos, struct request *rq, struct bio *bio);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/blk-iocost.c (0)
Location: block/blk-iocost.c:2692
Inline: False
```
**Symbols:**

```
ffffffff815fe8c0-ffffffff815feb1a: ioc_rqos_merge (STB_LOCAL)
ffffffff81cd9ef0-ffffffff81cd9f13: ioc_rqos_merge.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void ioc_rqos_merge(struct rq_qos *rqos, struct request *rq, struct bio *bio);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/blk-iocost.c (0)
Location: block/blk-iocost.c:2695
Inline: False
```
**Symbols:**

```
ffffffff816b20e0-ffffffff816b23ad: ioc_rqos_merge (STB_LOCAL)
ffffffff81e8da09-ffffffff81e8da2d: ioc_rqos_merge.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void ioc_rqos_merge(struct rq_qos *rqos, struct request *rq, struct bio *bio);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/blk-iocost.c (0)
Location: block/blk-iocost.c:2702
Inline: False
```
**Symbols:**

```
ffffffff81771620-ffffffff817718e4: ioc_rqos_merge (STB_LOCAL)
ffffffff82076f4f-ffffffff82076f73: ioc_rqos_merge.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void ioc_rqos_merge(struct rq_qos *rqos, struct request *rq, struct bio *bio);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/blk-iocost.c (0)
Location: block/blk-iocost.c:2723
Inline: False
```
**Symbols:**

```
ffffffff817b0910-ffffffff817b0bc3: ioc_rqos_merge (STB_LOCAL)
ffffffff820f6dd3-ffffffff820f6df7: ioc_rqos_merge.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void ioc_rqos_merge(struct rq_qos *rqos, struct request *rq, struct bio *bio);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/blk-iocost.c (0)
Location: block/blk-iocost.c:2730
Inline: False
```
**Symbols:**

```
ffffffff817f4720-ffffffff817f49d3: ioc_rqos_merge (STB_LOCAL)
ffffffff821d4221-ffffffff821d4245: ioc_rqos_merge.cold (STB_LOCAL)
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
void ioc_rqos_merge(struct rq_qos *rqos, struct request *rq, struct bio *bio);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-iocost.c (ffff800010616510)
Location: block/blk-iocost.c:1798
Inline: False
```
**Symbols:**

```
ffff800010616510-ffff8000106166a0: ioc_rqos_merge (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void ioc_rqos_merge(struct rq_qos *rqos, struct request *rq, struct bio *bio);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-iocost.c (c07c1698)
Location: block/blk-iocost.c:1798
Inline: False
```
**Symbols:**

```
c07c1698-c07c188c: ioc_rqos_merge (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void ioc_rqos_merge(struct rq_qos *rqos, struct request *rq, struct bio *bio);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-iocost.c (c0000000007b28f0)
Location: block/blk-iocost.c:1798
Inline: False
```
**Symbols:**

```
c0000000007b28f0-c0000000007b2ae8: ioc_rqos_merge (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void ioc_rqos_merge(struct rq_qos *rqos, struct request *rq, struct bio *bio);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-iocost.c (ffffffe00044b25e)
Location: block/blk-iocost.c:1798
Inline: False
```
**Symbols:**

```
ffffffe00044b25e-ffffffe00044b368: ioc_rqos_merge (STB_LOCAL)
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
void ioc_rqos_merge(struct rq_qos *rqos, struct request *rq, struct bio *bio);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-iocost.c (ffffffff81508610)
Location: block/blk-iocost.c:1798
Inline: False
```
**Symbols:**

```
ffffffff81508610-ffffffff8150874e: ioc_rqos_merge (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void ioc_rqos_merge(struct rq_qos *rqos, struct request *rq, struct bio *bio);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-iocost.c (ffffffff814f8ac0)
Location: block/blk-iocost.c:1798
Inline: False
```
**Symbols:**

```
ffffffff814f8ac0-ffffffff814f8bfe: ioc_rqos_merge (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void ioc_rqos_merge(struct rq_qos *rqos, struct request *rq, struct bio *bio);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-iocost.c (ffffffff815046a0)
Location: block/blk-iocost.c:1798
Inline: False
```
**Symbols:**

```
ffffffff815046a0-ffffffff815047de: ioc_rqos_merge (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void ioc_rqos_merge(struct rq_qos *rqos, struct request *rq, struct bio *bio);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-iocost.c (ffffffff8151dc50)
Location: block/blk-iocost.c:1798
Inline: False
```
**Symbols:**

```
ffffffff8151dc50-ffffffff8151dd8e: ioc_rqos_merge (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
