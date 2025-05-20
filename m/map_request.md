# Function: <code>map_request</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int map_request(struct dm_rq_target_io *tio, struct request *rq, struct mapped_device *md);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffff816a24e0)
Location: drivers/md/dm.c:1940
Inline: False
Direct callers:
  - drivers/md/dm.c:map_tio_request
  - drivers/md/dm.c:dm_mq_queue_rq
```
**Symbols:**

```
ffffffff816a24e0-ffffffff816a2770: map_request (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int map_request(struct dm_rq_target_io *tio, struct request *rq, struct mapped_device *md);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-rq.c (ffffffff8170f620)
Location: drivers/md/dm-rq.c:619
Inline: False
Direct callers:
  - drivers/md/dm-rq.c:dm_mq_queue_rq
  - drivers/md/dm-rq.c:map_tio_request
```
**Symbols:**

```
ffffffff8170f620-ffffffff8170f84c: map_request (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int map_request(struct dm_rq_target_io *tio);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-rq.c (ffffffff81741620)
Location: drivers/md/dm-rq.c:628
Inline: False
Direct callers:
  - drivers/md/dm-rq.c:dm_mq_queue_rq
  - drivers/md/dm-rq.c:map_tio_request
```
**Symbols:**

```
ffffffff81741620-ffffffff81741862: map_request (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int map_request(struct dm_rq_target_io *tio);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-rq.c (ffffffff8175ae40)
Location: drivers/md/dm-rq.c:475
Inline: False
Direct callers:
  - drivers/md/dm-rq.c:dm_mq_queue_rq
  - drivers/md/dm-rq.c:map_tio_request
```
**Symbols:**

```
ffffffff8175ae40-ffffffff8175b024: map_request (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int map_request(struct dm_rq_target_io *tio);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-rq.c (ffffffff817cd080)
Location: drivers/md/dm-rq.c:472
Inline: False
Direct callers:
  - drivers/md/dm-rq.c:dm_mq_queue_rq
  - drivers/md/dm-rq.c:map_tio_request
```
**Symbols:**

```
ffffffff817cd080-ffffffff817cd27d: map_request (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
int map_request(struct dm_rq_target_io *tio);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/md/dm-rq.c (0)
Location: drivers/md/dm-rq.c:477
Inline: False
Direct callers:
  - drivers/md/dm-rq.c:dm_mq_queue_rq
  - drivers/md/dm-rq.c:map_tio_request
```
**Symbols:**

```
ffffffff81815e40-ffffffff8181608a: map_request (STB_LOCAL)
ffffffff81816ab1-ffffffff81816ac1: map_request.cold.10 (STB_LOCAL)
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
In drivers/md/dm-rq.c (ffffffff81841c96)
Location: drivers/md/dm-rq.c:365
Inline: True
Inline callers:
  - drivers/md/dm-rq.c:dm_mq_queue_rq
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
In drivers/md/dm-rq.c (ffffffff81884ad1)
Location: drivers/md/dm-rq.c:384
Inline: True
Inline callers:
  - drivers/md/dm-rq.c:dm_mq_queue_rq
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int map_request(struct dm_rq_target_io *tio);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/md/dm-rq.c (0)
Location: drivers/md/dm-rq.c:384
Inline: False
Direct callers:
  - drivers/md/dm-rq.c:dm_mq_queue_rq
```
**Symbols:**

```
ffffffff818b68d0-ffffffff818b6b61: map_request (STB_LOCAL)
ffffffff818b719d-ffffffff818b71ae: map_request.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int map_request(struct dm_rq_target_io *tio);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/md/dm-rq.c (0)
Location: drivers/md/dm-rq.c:377
Inline: False
Direct callers:
  - drivers/md/dm-rq.c:dm_mq_queue_rq
```
**Symbols:**

```
ffffffff81987190-ffffffff81987421: map_request (STB_LOCAL)
ffffffff81987b40-ffffffff81987b51: map_request.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int map_request(struct dm_rq_target_io *tio);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/md/dm-rq.c (0)
Location: drivers/md/dm-rq.c:378
Inline: False
Direct callers:
  - drivers/md/dm-rq.c:dm_mq_queue_rq
```
**Symbols:**

```
ffffffff8198b170-ffffffff8198b3c5: map_request (STB_LOCAL)
ffffffff81c286f4-ffffffff81c28705: map_request.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int map_request(struct dm_rq_target_io *tio);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/md/dm-rq.c (0)
Location: drivers/md/dm-rq.c:378
Inline: False
Direct callers:
  - drivers/md/dm-rq.c:dm_mq_queue_rq
```
**Symbols:**

```
ffffffff8196f860-ffffffff8196fab5: map_request (STB_LOCAL)
ffffffff81c1a8d3-ffffffff81c1a8e4: map_request.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int map_request(struct dm_rq_target_io *tio);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/md/dm-rq.c (0)
Location: drivers/md/dm-rq.c:378
Inline: False
Direct callers:
  - drivers/md/dm-rq.c:dm_mq_queue_rq
```
**Symbols:**

```
ffffffff81a181a0-ffffffff81a183f5: map_request (STB_LOCAL)
ffffffff81d2a7cf-ffffffff81d2a7e0: map_request.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int map_request(struct dm_rq_target_io *tio);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/md/dm-rq.c (0)
Location: drivers/md/dm-rq.c:359
Inline: False
Direct callers:
  - drivers/md/dm-rq.c:dm_mq_queue_rq
```
**Symbols:**

```
ffffffff81b80ed0-ffffffff81b81110: map_request (STB_LOCAL)
ffffffff81ef69b5-ffffffff81ef69c6: map_request.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int map_request(struct dm_rq_target_io *tio);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-rq.c (ffffffff81d1f1e0)
Location: drivers/md/dm-rq.c:360
Inline: False
Direct callers:
  - drivers/md/dm-rq.c:dm_mq_queue_rq
```
**Symbols:**

```
ffffffff81d1f1e0-ffffffff81d1f42b: map_request (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int map_request(struct dm_rq_target_io *tio);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-rq.c (ffffffff81d883c0)
Location: drivers/md/dm-rq.c:362
Inline: False
Direct callers:
  - drivers/md/dm-rq.c:dm_mq_queue_rq
```
**Symbols:**

```
ffffffff81d883c0-ffffffff81d8860f: map_request (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int map_request(struct dm_rq_target_io *tio);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-rq.c (ffffffff81e3fad0)
Location: drivers/md/dm-rq.c:362
Inline: False
Direct callers:
  - drivers/md/dm-rq.c:dm_mq_queue_rq
```
**Symbols:**

```
ffffffff81e3fad0-ffffffff81e3fd1f: map_request (STB_LOCAL)
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
int map_request(struct dm_rq_target_io *tio);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-rq.c (ffff800010b0e918)
Location: drivers/md/dm-rq.c:384
Inline: False
Direct callers:
  - drivers/md/dm-rq.c:dm_mq_queue_rq
  - drivers/md/dm-rq.c:dm_mq_queue_rq
```
**Symbols:**

```
ffff800010b0e918-ffff800010b0ebc0: map_request (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int map_request(struct dm_rq_target_io *tio);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-rq.c (c0becce8)
Location: drivers/md/dm-rq.c:384
Inline: False
Direct callers:
  - drivers/md/dm-rq.c:dm_mq_queue_rq
```
**Symbols:**

```
c0becce8-c0becfa8: map_request (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int map_request(struct dm_rq_target_io *tio);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-rq.c (c000000000c019d0)
Location: drivers/md/dm-rq.c:384
Inline: False
Direct callers:
  - drivers/md/dm-rq.c:dm_mq_queue_rq
  - drivers/md/dm-rq.c:dm_mq_queue_rq
```
**Symbols:**

```
c000000000c019d0-c000000000c01d74: map_request (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int map_request(struct dm_rq_target_io *tio);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm-rq.c (ffffffe0006fbc0e)
Location: drivers/md/dm-rq.c:384
Inline: False
Direct callers:
  - drivers/md/dm-rq.c:dm_mq_queue_rq
  - drivers/md/dm-rq.c:dm_mq_queue_rq
```
**Symbols:**

```
ffffffe0006fbc0e-ffffffe0006fbe28: map_request (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
int map_request(struct dm_rq_target_io *tio);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/md/dm-rq.c (0)
Location: drivers/md/dm-rq.c:384
Inline: False
Direct callers:
  - drivers/md/dm-rq.c:dm_mq_queue_rq
```
**Symbols:**

```
ffffffff8185c750-ffffffff8185c9e1: map_request (STB_LOCAL)
ffffffff8185d01d-ffffffff8185d02e: map_request.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int map_request(struct dm_rq_target_io *tio);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/md/dm-rq.c (0)
Location: drivers/md/dm-rq.c:384
Inline: False
Direct callers:
  - drivers/md/dm-rq.c:dm_mq_queue_rq
```
**Symbols:**

```
ffffffff81823d20-ffffffff81823fb1: map_request (STB_LOCAL)
ffffffff818245ed-ffffffff818245fe: map_request.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int map_request(struct dm_rq_target_io *tio);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/md/dm-rq.c (0)
Location: drivers/md/dm-rq.c:384
Inline: False
Direct callers:
  - drivers/md/dm-rq.c:dm_mq_queue_rq
```
**Symbols:**

```
ffffffff818abd80-ffffffff818ac011: map_request (STB_LOCAL)
ffffffff818ac64d-ffffffff818ac65e: map_request.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int map_request(struct dm_rq_target_io *tio);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/md/dm-rq.c (0)
Location: drivers/md/dm-rq.c:384
Inline: False
Direct callers:
  - drivers/md/dm-rq.c:dm_mq_queue_rq
```
**Symbols:**

```
ffffffff818c7fc0-ffffffff818c8268: map_request (STB_LOCAL)
ffffffff818c889d-ffffffff818c88ae: map_request.cold (STB_LOCAL)
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
<details>
<summary>Changed between <code>4.8</code> and <code>4.10</code> ⚠️</summary>
<ul>
<li>
<b>Param removed. </b>
<code>struct request *rq</code>
</li>
<li>
<b>Param removed. </b>
<code>struct mapped_device *md</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
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
