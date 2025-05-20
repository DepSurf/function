# Function: <code>blkif_queue_rw_req</code>

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
In drivers/block/xen-blkfront.c (ffffffff81576450)
Location: drivers/block/xen-blkfront.c:569
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
In drivers/block/xen-blkfront.c (ffffffff815cbcd1)
Location: drivers/block/xen-blkfront.c:688
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
In drivers/block/xen-blkfront.c (ffffffff815f88ce)
Location: drivers/block/xen-blkfront.c:688
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
In drivers/block/xen-blkfront.c (ffffffff8160b1b8)
Location: drivers/block/xen-blkfront.c:692
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
In drivers/block/xen-blkfront.c (ffffffff81673a88)
Location: drivers/block/xen-blkfront.c:692
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
In drivers/block/xen-blkfront.c (ffffffff816afa93)
Location: drivers/block/xen-blkfront.c:692
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
In drivers/block/xen-blkfront.c (ffffffff816cfbe0)
Location: drivers/block/xen-blkfront.c:691
Inline: True
Inline callers:
  - drivers/block/xen-blkfront.c:blkif_queue_rq
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int blkif_queue_rw_req(struct request *req, struct blkfront_ring_info *rinfo);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/block/xen-blkfront.c (ffffffff8170b540)
Location: drivers/block/xen-blkfront.c:691
Inline: False
Direct callers:
  - drivers/block/xen-blkfront.c:blkif_queue_rq
```
**Symbols:**

```
ffffffff8170b540-ffffffff8170bae2: blkif_queue_rw_req (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int blkif_queue_rw_req(struct request *req, struct blkfront_ring_info *rinfo);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/block/xen-blkfront.c (ffffffff8172f840)
Location: drivers/block/xen-blkfront.c:691
Inline: False
Direct callers:
  - drivers/block/xen-blkfront.c:blkif_queue_rq
```
**Symbols:**

```
ffffffff8172f840-ffffffff8172fde2: blkif_queue_rw_req (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int blkif_queue_rw_req(struct request *req, struct blkfront_ring_info *rinfo);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/block/xen-blkfront.c (ffffffff817ee320)
Location: drivers/block/xen-blkfront.c:702
Inline: False
Direct callers:
  - drivers/block/xen-blkfront.c:blkif_queue_rq
```
**Symbols:**

```
ffffffff817ee320-ffffffff817ee907: blkif_queue_rw_req (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int blkif_queue_rw_req(struct request *req, struct blkfront_ring_info *rinfo);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/block/xen-blkfront.c (ffffffff81802c20)
Location: drivers/block/xen-blkfront.c:702
Inline: False
Direct callers:
  - drivers/block/xen-blkfront.c:blkif_queue_rq
```
**Symbols:**

```
ffffffff81802c20-ffffffff81803207: blkif_queue_rw_req (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int blkif_queue_rw_req(struct request *req, struct blkfront_ring_info *rinfo);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/block/xen-blkfront.c (ffffffff817e72a0)
Location: drivers/block/xen-blkfront.c:702
Inline: False
Direct callers:
  - drivers/block/xen-blkfront.c:blkif_queue_rq
```
**Symbols:**

```
ffffffff817e72a0-ffffffff817e7861: blkif_queue_rw_req (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int blkif_queue_rw_req(struct request *req, struct blkfront_ring_info *rinfo);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/block/xen-blkfront.c (0)
Location: drivers/block/xen-blkfront.c:694
Inline: False
Direct callers:
  - drivers/block/xen-blkfront.c:blkif_queue_rq
```
**Symbols:**

```
ffffffff818732f0-ffffffff81873877: blkif_queue_rw_req (STB_LOCAL)
ffffffff81d05adf-ffffffff81d05b25: blkif_queue_rw_req.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int blkif_queue_rw_req(struct request *req, struct blkfront_ring_info *rinfo);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/block/xen-blkfront.c (0)
Location: drivers/block/xen-blkfront.c:699
Inline: False
Direct callers:
  - drivers/block/xen-blkfront.c:blkif_queue_rq
```
**Symbols:**

```
ffffffff819bd240-ffffffff819bd869: blkif_queue_rw_req (STB_LOCAL)
ffffffff81ece565-ffffffff81ece5ab: blkif_queue_rw_req.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int blkif_queue_rw_req(struct request *req, struct blkfront_ring_info *rinfo);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/block/xen-blkfront.c (0)
Location: drivers/block/xen-blkfront.c:702
Inline: False
Direct callers:
  - drivers/block/xen-blkfront.c:blkif_queue_rq
```
**Symbols:**

```
ffffffff81b32910-ffffffff81b32f39: blkif_queue_rw_req (STB_LOCAL)
ffffffff82099c09-ffffffff82099c4f: blkif_queue_rw_req.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int blkif_queue_rw_req(struct request *req, struct blkfront_ring_info *rinfo);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/block/xen-blkfront.c (0)
Location: drivers/block/xen-blkfront.c:702
Inline: False
Direct callers:
  - drivers/block/xen-blkfront.c:blkif_queue_rq
```
**Symbols:**

```
ffffffff81b85dd0-ffffffff81b8645c: blkif_queue_rw_req (STB_LOCAL)
ffffffff8211ad23-ffffffff8211ad6a: blkif_queue_rw_req.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int blkif_queue_rw_req(struct request *req, struct blkfront_ring_info *rinfo);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/block/xen-blkfront.c (0)
Location: drivers/block/xen-blkfront.c:702
Inline: False
Direct callers:
  - drivers/block/xen-blkfront.c:blkif_queue_rq
```
**Symbols:**

```
ffffffff81bd9ce0-ffffffff81bda331: blkif_queue_rw_req (STB_LOCAL)
ffffffff821f8ba9-ffffffff821f8bf0: blkif_queue_rw_req.cold (STB_LOCAL)
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
int blkif_queue_rw_req(struct request *req, struct blkfront_ring_info *rinfo);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/block/xen-blkfront.c (ffff800010926598)
Location: drivers/block/xen-blkfront.c:691
Inline: False
Direct callers:
  - drivers/block/xen-blkfront.c:blkif_queue_rq
```
**Symbols:**

```
ffff800010926598-ffff800010926a50: blkif_queue_rw_req (STB_LOCAL)
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
<summary>In <code>aws</code>: ✅</summary>

```c
int blkif_queue_rw_req(struct request *req, struct blkfront_ring_info *rinfo);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/block/xen-blkfront.c (ffffffff816f57b0)
Location: drivers/block/xen-blkfront.c:706
Inline: False
Direct callers:
  - drivers/block/xen-blkfront.c:blkif_queue_rq
```
**Symbols:**

```
ffffffff816f57b0-ffffffff816f5d52: blkif_queue_rw_req (STB_LOCAL)
```
</details>
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int blkif_queue_rw_req(struct request *req, struct blkfront_ring_info *rinfo);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/block/xen-blkfront.c (ffffffff81722d00)
Location: drivers/block/xen-blkfront.c:691
Inline: False
Direct callers:
  - drivers/block/xen-blkfront.c:blkif_queue_rq
```
**Symbols:**

```
ffffffff81722d00-ffffffff817232a2: blkif_queue_rw_req (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int blkif_queue_rw_req(struct request *req, struct blkfront_ring_info *rinfo);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/block/xen-blkfront.c (ffffffff8173e140)
Location: drivers/block/xen-blkfront.c:691
Inline: False
Direct callers:
  - drivers/block/xen-blkfront.c:blkif_queue_rq
```
**Symbols:**

```
ffffffff8173e140-ffffffff8173e71a: blkif_queue_rw_req (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
