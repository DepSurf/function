# Function: <code>ioc_rqos_throttle</code>

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
void ioc_rqos_throttle(struct rq_qos *rqos, struct bio *bio);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-iocost.c (ffffffff815135e0)
Location: block/blk-iocost.c:1679
Inline: False
```
**Symbols:**

```
ffffffff815135e0-ffffffff81513dc2: ioc_rqos_throttle (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void ioc_rqos_throttle(struct rq_qos *rqos, struct bio *bio);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-iocost.c (ffffffff81574950)
Location: block/blk-iocost.c:1722
Inline: False
```
**Symbols:**

```
ffffffff81574950-ffffffff81574de3: ioc_rqos_throttle (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void ioc_rqos_throttle(struct rq_qos *rqos, struct bio *bio);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-iocost.c (ffffffff815916e0)
Location: block/blk-iocost.c:2543
Inline: False
```
**Symbols:**

```
ffffffff815916e0-ffffffff81591bb7: ioc_rqos_throttle (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void ioc_rqos_throttle(struct rq_qos *rqos, struct bio *bio);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-iocost.c (ffffffff81598530)
Location: block/blk-iocost.c:2550
Inline: False
```
**Symbols:**

```
ffffffff81598530-ffffffff81598a0d: ioc_rqos_throttle (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void ioc_rqos_throttle(struct rq_qos *rqos, struct bio *bio);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/blk-iocost.c (0)
Location: block/blk-iocost.c:2557
Inline: False
```
**Symbols:**

```
ffffffff815ffcd0-ffffffff81600212: ioc_rqos_throttle (STB_LOCAL)
ffffffff81cd9f3c-ffffffff81cd9f81: ioc_rqos_throttle.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void ioc_rqos_throttle(struct rq_qos *rqos, struct bio *bio);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/blk-iocost.c (0)
Location: block/blk-iocost.c:2560
Inline: False
```
**Symbols:**

```
ffffffff816b23b0-ffffffff816b2950: ioc_rqos_throttle (STB_LOCAL)
ffffffff81e8da2d-ffffffff81e8da56: ioc_rqos_throttle.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void ioc_rqos_throttle(struct rq_qos *rqos, struct bio *bio);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/blk-iocost.c (0)
Location: block/blk-iocost.c:2567
Inline: False
```
**Symbols:**

```
ffffffff81771900-ffffffff81771e91: ioc_rqos_throttle (STB_LOCAL)
ffffffff82076f73-ffffffff82076f9c: ioc_rqos_throttle.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void ioc_rqos_throttle(struct rq_qos *rqos, struct bio *bio);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/blk-iocost.c (0)
Location: block/blk-iocost.c:2588
Inline: False
```
**Symbols:**

```
ffffffff817b0be0-ffffffff817b1163: ioc_rqos_throttle (STB_LOCAL)
ffffffff820f6df7-ffffffff820f6e21: ioc_rqos_throttle.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void ioc_rqos_throttle(struct rq_qos *rqos, struct bio *bio);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/blk-iocost.c (0)
Location: block/blk-iocost.c:2595
Inline: False
```
**Symbols:**

```
ffffffff817f49f0-ffffffff817f4f73: ioc_rqos_throttle (STB_LOCAL)
ffffffff821d4245-ffffffff821d426f: ioc_rqos_throttle.cold (STB_LOCAL)
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
void ioc_rqos_throttle(struct rq_qos *rqos, struct bio *bio);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-iocost.c (ffff800010617a58)
Location: block/blk-iocost.c:1679
Inline: False
```
**Symbols:**

```
ffff800010617a58-ffff8000106182f4: ioc_rqos_throttle (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void ioc_rqos_throttle(struct rq_qos *rqos, struct bio *bio);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-iocost.c (c07c2e94)
Location: block/blk-iocost.c:1679
Inline: False
```
**Symbols:**

```
c07c2e94-c07c33c4: ioc_rqos_throttle (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void ioc_rqos_throttle(struct rq_qos *rqos, struct bio *bio);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-iocost.c (c0000000007b7150)
Location: block/blk-iocost.c:1679
Inline: False
```
**Symbols:**

```
c0000000007b7150-c0000000007b7a54: ioc_rqos_throttle (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void ioc_rqos_throttle(struct rq_qos *rqos, struct bio *bio);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-iocost.c (ffffffe00044e03e)
Location: block/blk-iocost.c:1679
Inline: False
```
**Symbols:**

```
ffffffe00044e03e-ffffffe00044e6d6: ioc_rqos_throttle (STB_LOCAL)
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
void ioc_rqos_throttle(struct rq_qos *rqos, struct bio *bio);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-iocost.c (ffffffff8150bbc0)
Location: block/blk-iocost.c:1679
Inline: False
```
**Symbols:**

```
ffffffff8150bbc0-ffffffff8150c3a2: ioc_rqos_throttle (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void ioc_rqos_throttle(struct rq_qos *rqos, struct bio *bio);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-iocost.c (ffffffff814fc010)
Location: block/blk-iocost.c:1679
Inline: False
```
**Symbols:**

```
ffffffff814fc010-ffffffff814fc7d4: ioc_rqos_throttle (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void ioc_rqos_throttle(struct rq_qos *rqos, struct bio *bio);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-iocost.c (ffffffff81507c50)
Location: block/blk-iocost.c:1679
Inline: False
```
**Symbols:**

```
ffffffff81507c50-ffffffff81508432: ioc_rqos_throttle (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void ioc_rqos_throttle(struct rq_qos *rqos, struct bio *bio);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-iocost.c (ffffffff8151ef20)
Location: block/blk-iocost.c:1679
Inline: False
```
**Symbols:**

```
ffffffff8151ef20-ffffffff8151f7e7: ioc_rqos_throttle (STB_LOCAL)
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
