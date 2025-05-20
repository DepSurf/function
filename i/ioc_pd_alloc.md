# Function: <code>ioc_pd_alloc</code>

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
struct blkg_policy_data *ioc_pd_alloc(gfp_t gfp, struct request_queue *q, struct blkcg *blkcg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-iocost.c (ffffffff81510170)
Location: block/blk-iocost.c:1976
Inline: False
```
**Symbols:**

```
ffffffff81510170-ffffffff815101a7: ioc_pd_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct blkg_policy_data *ioc_pd_alloc(gfp_t gfp, struct request_queue *q, struct blkcg *blkcg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-iocost.c (ffffffff815712b0)
Location: block/blk-iocost.c:2042
Inline: False
```
**Symbols:**

```
ffffffff815712b0-ffffffff815712e7: ioc_pd_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct blkg_policy_data *ioc_pd_alloc(gfp_t gfp, struct request_queue *q, struct blkcg *blkcg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-iocost.c (ffffffff8158c370)
Location: block/blk-iocost.c:2900
Inline: False
```
**Symbols:**

```
ffffffff8158c370-ffffffff8158c41b: ioc_pd_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct blkg_policy_data *ioc_pd_alloc(gfp_t gfp, struct request_queue *q, struct blkcg *blkcg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-iocost.c (ffffffff81593230)
Location: block/blk-iocost.c:2907
Inline: False
```
**Symbols:**

```
ffffffff81593230-ffffffff815932d0: ioc_pd_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct blkg_policy_data *ioc_pd_alloc(gfp_t gfp, struct request_queue *q, struct blkcg *blkcg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-iocost.c (ffffffff815fa4e0)
Location: block/blk-iocost.c:2914
Inline: False
```
**Symbols:**

```
ffffffff815fa4e0-ffffffff815fa580: ioc_pd_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct blkg_policy_data *ioc_pd_alloc(gfp_t gfp, struct request_queue *q, struct blkcg *blkcg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-iocost.c (ffffffff816ac870)
Location: block/blk-iocost.c:2923
Inline: False
```
**Symbols:**

```
ffffffff816ac870-ffffffff816ac916: ioc_pd_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct blkg_policy_data *ioc_pd_alloc(gfp_t gfp, struct request_queue *q, struct blkcg *blkcg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-iocost.c (ffffffff8176b370)
Location: block/blk-iocost.c:2931
Inline: False
```
**Symbols:**

```
ffffffff8176b370-ffffffff8176b416: ioc_pd_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct blkg_policy_data *ioc_pd_alloc(struct gendisk *disk, struct blkcg *blkcg, gfp_t gfp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-iocost.c (ffffffff817aa450)
Location: block/blk-iocost.c:2945
Inline: False
```
**Symbols:**

```
ffffffff817aa450-ffffffff817aa4f9: ioc_pd_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct blkg_policy_data *ioc_pd_alloc(struct gendisk *disk, struct blkcg *blkcg, gfp_t gfp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-iocost.c (ffffffff817ee200)
Location: block/blk-iocost.c:2952
Inline: False
```
**Symbols:**

```
ffffffff817ee200-ffffffff817ee2a9: ioc_pd_alloc (STB_LOCAL)
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
struct blkg_policy_data *ioc_pd_alloc(gfp_t gfp, struct request_queue *q, struct blkcg *blkcg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-iocost.c (ffff800010613978)
Location: block/blk-iocost.c:1976
Inline: False
```
**Symbols:**

```
ffff800010613978-ffff8000106139d0: ioc_pd_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct blkg_policy_data *ioc_pd_alloc(gfp_t gfp, struct request_queue *q, struct blkcg *blkcg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-iocost.c (c07bfcd8)
Location: block/blk-iocost.c:1976
Inline: False
```
**Symbols:**

```
c07bfcd8-c07bfd08: ioc_pd_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct blkg_policy_data *ioc_pd_alloc(gfp_t gfp, struct request_queue *q, struct blkcg *blkcg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-iocost.c (c0000000007b2af0)
Location: block/blk-iocost.c:1976
Inline: False
```
**Symbols:**

```
c0000000007b2af0-c0000000007b2b48: ioc_pd_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct blkg_policy_data *ioc_pd_alloc(gfp_t gfp, struct request_queue *q, struct blkcg *blkcg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-iocost.c (ffffffe00044b6ba)
Location: block/blk-iocost.c:1976
Inline: False
```
**Symbols:**

```
ffffffe00044b6ba-ffffffe00044b6fc: ioc_pd_alloc (STB_LOCAL)
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
struct blkg_policy_data *ioc_pd_alloc(gfp_t gfp, struct request_queue *q, struct blkcg *blkcg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-iocost.c (ffffffff81508750)
Location: block/blk-iocost.c:1976
Inline: False
```
**Symbols:**

```
ffffffff81508750-ffffffff81508787: ioc_pd_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct blkg_policy_data *ioc_pd_alloc(gfp_t gfp, struct request_queue *q, struct blkcg *blkcg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-iocost.c (ffffffff814f8c00)
Location: block/blk-iocost.c:1976
Inline: False
```
**Symbols:**

```
ffffffff814f8c00-ffffffff814f8c37: ioc_pd_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct blkg_policy_data *ioc_pd_alloc(gfp_t gfp, struct request_queue *q, struct blkcg *blkcg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-iocost.c (ffffffff815047e0)
Location: block/blk-iocost.c:1976
Inline: False
```
**Symbols:**

```
ffffffff815047e0-ffffffff81504817: ioc_pd_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct blkg_policy_data *ioc_pd_alloc(gfp_t gfp, struct request_queue *q, struct blkcg *blkcg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-iocost.c (ffffffff8151dd90)
Location: block/blk-iocost.c:1976
Inline: False
```
**Symbols:**

```
ffffffff8151dd90-ffffffff8151ddc7: ioc_pd_alloc (STB_LOCAL)
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
<details>
<summary>Changed between <code>6.2</code> and <code>6.5</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct gendisk *disk</code>
</li>
<li>
<b>Param removed. </b>
<code>struct request_queue *q</code>
</li>
<li>
<b>Param reordered. </b>
<code>gfp, q, blkcg</code> ➡️ <code>disk, blkcg, gfp</code>
</li>
</ul>
</details>
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
