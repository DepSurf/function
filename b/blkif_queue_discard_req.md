# Function: <code>blkif_queue_discard_req</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/block/xen-blkfront.c (ffffffff81576a31)
Location: drivers/block/xen-blkfront.c:459
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkif_queue_rq
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/block/xen-blkfront.c (ffffffff815cc30b)
Location: drivers/block/xen-blkfront.c:540
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkif_queue_rq
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/block/xen-blkfront.c (ffffffff815f8eef)
Location: drivers/block/xen-blkfront.c:540
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkif_queue_rq
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/block/xen-blkfront.c (ffffffff8160b782)
Location: drivers/block/xen-blkfront.c:544
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkif_queue_rq
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/block/xen-blkfront.c (ffffffff8167404d)
Location: drivers/block/xen-blkfront.c:544
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkif_queue_rq
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/block/xen-blkfront.c (ffffffff816b0027)
Location: drivers/block/xen-blkfront.c:544
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkif_queue_rq
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/block/xen-blkfront.c (ffffffff816d0174)
Location: drivers/block/xen-blkfront.c:543
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkif_queue_rq
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/block/xen-blkfront.c (ffffffff8170bc98)
Location: drivers/block/xen-blkfront.c:543
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkif_queue_rq
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/block/xen-blkfront.c (ffffffff8172ff98)
Location: drivers/block/xen-blkfront.c:543
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkif_queue_rq
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int blkif_queue_discard_req(struct request *req, struct blkfront_ring_info *rinfo);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/block/xen-blkfront.c (ffffffff817ed860)
Location: drivers/block/xen-blkfront.c:554
Inline: False
Direct callers:
  - drivers/block/xen-blkfront.c:blkif_queue_rq
```
**Symbols:**

```
ffffffff817ed860-ffffffff817ed9e5: blkif_queue_discard_req (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int blkif_queue_discard_req(struct request *req, struct blkfront_ring_info *rinfo);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/block/xen-blkfront.c (ffffffff81802190)
Location: drivers/block/xen-blkfront.c:554
Inline: False
Direct callers:
  - drivers/block/xen-blkfront.c:blkif_queue_rq
```
**Symbols:**

```
ffffffff81802190-ffffffff81802315: blkif_queue_discard_req (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/block/xen-blkfront.c (ffffffff817e79f8)
Location: drivers/block/xen-blkfront.c:554
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkif_queue_rq
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/block/xen-blkfront.c (ffffffff81873a08)
Location: drivers/block/xen-blkfront.c:544
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkif_queue_rq
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/block/xen-blkfront.c (ffffffff819bda17)
Location: drivers/block/xen-blkfront.c:549
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkif_queue_rq
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/block/xen-blkfront.c (ffffffff81b330f7)
Location: drivers/block/xen-blkfront.c:552
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkif_queue_rq
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/block/xen-blkfront.c (ffffffff81b86619)
Location: drivers/block/xen-blkfront.c:552
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkif_queue_rq
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/block/xen-blkfront.c (ffffffff81bda4f6)
Location: drivers/block/xen-blkfront.c:552
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkif_queue_rq
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/block/xen-blkfront.c (ffff80001092a478)
Location: drivers/block/xen-blkfront.c:543
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkif_queue_rq
```
</details>
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
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/block/xen-blkfront.c (ffffffff816f5f08)
Location: drivers/block/xen-blkfront.c:558
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkif_queue_rq
```
</details>
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/block/xen-blkfront.c (ffffffff81723458)
Location: drivers/block/xen-blkfront.c:543
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkif_queue_rq
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/block/xen-blkfront.c (ffffffff8173e8c8)
Location: drivers/block/xen-blkfront.c:543
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkif_queue_rq
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
</ul>
