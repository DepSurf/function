# Function: <code>ioprio_alloc_pd</code>

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
struct blkg_policy_data *ioprio_alloc_pd(gfp_t gfp, struct request_queue *q, struct blkcg *blkcg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-ioprio.c (ffffffff815f95d0)
Location: block/blk-ioprio.c:120
Inline: False
```
**Symbols:**

```
ffffffff815f95d0-ffffffff815f9649: ioprio_alloc_pd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct blkg_policy_data *ioprio_alloc_pd(gfp_t gfp, struct request_queue *q, struct blkcg *blkcg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-ioprio.c (ffffffff816ab5e0)
Location: block/blk-ioprio.c:121
Inline: False
```
**Symbols:**

```
ffffffff816ab5e0-ffffffff816ab663: ioprio_alloc_pd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct blkg_policy_data *ioprio_alloc_pd(gfp_t gfp, struct request_queue *q, struct blkcg *blkcg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-ioprio.c (ffffffff81769ea0)
Location: block/blk-ioprio.c:119
Inline: False
```
**Symbols:**

```
ffffffff81769ea0-ffffffff81769f24: ioprio_alloc_pd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct blkg_policy_data *ioprio_alloc_pd(struct gendisk *disk, struct blkcg *blkcg, gfp_t gfp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-ioprio.c (ffffffff817a8ef0)
Location: block/blk-ioprio.c:122
Inline: False
```
**Symbols:**

```
ffffffff817a8ef0-ffffffff817a8f73: ioprio_alloc_pd (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct blkg_policy_data *ioprio_alloc_pd(struct gendisk *disk, struct blkcg *blkcg, gfp_t gfp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-ioprio.c (ffffffff817ecc80)
Location: block/blk-ioprio.c:122
Inline: False
```
**Symbols:**

```
ffffffff817ecc80-ffffffff817ecd1f: ioprio_alloc_pd (STB_LOCAL)
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
