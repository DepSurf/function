# Function: <code>blk_mq_in_flight_rw</code>

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
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void blk_mq_in_flight_rw(struct request_queue *q, struct hd_struct *part, unsigned int *inflight);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff8148ff00)
Location: block/blk-mq.c:128
Inline: False
Direct callers:
  - block/genhd.c:part_in_flight_rw
```
**Symbols:**

```
ffffffff8148ff00-ffffffff8148ff51: blk_mq_in_flight_rw (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void blk_mq_in_flight_rw(struct request_queue *q, struct hd_struct *part, unsigned int *inflight);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff814a9810)
Location: block/blk-mq.c:134
Inline: False
Direct callers:
  - block/genhd.c:part_in_flight_rw
```
**Symbols:**

```
ffffffff814a9810-ffffffff814a9861: blk_mq_in_flight_rw (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void blk_mq_in_flight_rw(struct request_queue *q, struct hd_struct *part, unsigned int *inflight);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff814d7670)
Location: block/blk-mq.c:136
Inline: False
Direct callers:
  - block/genhd.c:part_in_flight_rw
```
**Symbols:**

```
ffffffff814d7670-ffffffff814d76c1: blk_mq_in_flight_rw (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void blk_mq_in_flight_rw(struct request_queue *q, struct hd_struct *part, unsigned int *inflight);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff814f09f0)
Location: block/blk-mq.c:137
Inline: False
Direct callers:
  - block/genhd.c:part_in_flight_rw
```
**Symbols:**

```
ffffffff814f09f0-ffffffff814f0a41: blk_mq_in_flight_rw (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void blk_mq_in_flight_rw(struct request_queue *q, struct hd_struct *part, unsigned int *inflight);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff81551be0)
Location: block/blk-mq.c:121
Inline: False
Direct callers:
  - block/genhd.c:part_inflight_show
```
**Symbols:**

```
ffffffff81551be0-ffffffff81551c3d: blk_mq_in_flight_rw (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void blk_mq_in_flight_rw(struct request_queue *q, struct block_device *part, unsigned int *inflight);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff8156dd10)
Location: block/blk-mq.c:125
Inline: False
Direct callers:
  - block/genhd.c:part_inflight_show
```
**Symbols:**

```
ffffffff8156dd10-ffffffff8156dd6d: blk_mq_in_flight_rw (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void blk_mq_in_flight_rw(struct request_queue *q, struct block_device *part, unsigned int *inflight);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff815757f0)
Location: block/blk-mq.c:125
Inline: False
Direct callers:
  - block/genhd.c:part_inflight_show
```
**Symbols:**

```
ffffffff815757f0-ffffffff8157584d: blk_mq_in_flight_rw (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void blk_mq_in_flight_rw(struct request_queue *q, struct block_device *part, unsigned int *inflight);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff815d9c90)
Location: block/blk-mq.c:125
Inline: False
Direct callers:
  - block/genhd.c:part_inflight_show
```
**Symbols:**

```
ffffffff815d9c90-ffffffff815d9ced: blk_mq_in_flight_rw (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void blk_mq_in_flight_rw(struct request_queue *q, struct block_device *part, unsigned int *inflight);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff81687600)
Location: block/blk-mq.c:154
Inline: False
Direct callers:
  - block/genhd.c:part_inflight_show
```
**Symbols:**

```
ffffffff81687600-ffffffff81687669: blk_mq_in_flight_rw (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void blk_mq_in_flight_rw(struct request_queue *q, struct block_device *part, unsigned int *inflight);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff81745920)
Location: block/blk-mq.c:154
Inline: False
Direct callers:
  - block/genhd.c:part_inflight_show
```
**Symbols:**

```
ffffffff81745920-ffffffff81745989: blk_mq_in_flight_rw (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void blk_mq_in_flight_rw(struct request_queue *q, struct block_device *part, unsigned int *inflight);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff817822b0)
Location: block/blk-mq.c:113
Inline: False
Direct callers:
  - block/genhd.c:part_inflight_show
```
**Symbols:**

```
ffffffff817822b0-ffffffff81782319: blk_mq_in_flight_rw (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void blk_mq_in_flight_rw(struct request_queue *q, struct block_device *part, unsigned int *inflight);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff817c4650)
Location: block/blk-mq.c:113
Inline: False
Direct callers:
  - block/genhd.c:part_inflight_show
```
**Symbols:**

```
ffffffff817c4650-ffffffff817c46b9: blk_mq_in_flight_rw (STB_GLOBAL)
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
void blk_mq_in_flight_rw(struct request_queue *q, struct hd_struct *part, unsigned int *inflight);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffff8000105efdc0)
Location: block/blk-mq.c:137
Inline: False
Direct callers:
  - block/genhd.c:part_in_flight_rw
```
**Symbols:**

```
ffff8000105efdc0-ffff8000105efe34: blk_mq_in_flight_rw (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void blk_mq_in_flight_rw(struct request_queue *q, struct hd_struct *part, unsigned int *inflight);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (c079bfac)
Location: block/blk-mq.c:137
Inline: False
Direct callers:
  - block/genhd.c:part_in_flight_rw
```
**Symbols:**

```
c079bfac-c079c028: blk_mq_in_flight_rw (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void blk_mq_in_flight_rw(struct request_queue *q, struct hd_struct *part, unsigned int *inflight);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (c0000000007864d0)
Location: block/blk-mq.c:137
Inline: False
Direct callers:
  - block/genhd.c:part_in_flight_rw
```
**Symbols:**

```
c0000000007864d0-c000000000786550: blk_mq_in_flight_rw (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void blk_mq_in_flight_rw(struct request_queue *q, struct hd_struct *part, unsigned int *inflight);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffe00042ee38)
Location: block/blk-mq.c:137
Inline: False
Direct callers:
  - block/genhd.c:part_in_flight_rw
```
**Symbols:**

```
ffffffe00042ee38-ffffffe00042ee8a: blk_mq_in_flight_rw (STB_GLOBAL)
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
void blk_mq_in_flight_rw(struct request_queue *q, struct hd_struct *part, unsigned int *inflight);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff814e8fd0)
Location: block/blk-mq.c:137
Inline: False
Direct callers:
  - block/genhd.c:part_in_flight_rw
```
**Symbols:**

```
ffffffff814e8fd0-ffffffff814e9021: blk_mq_in_flight_rw (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void blk_mq_in_flight_rw(struct request_queue *q, struct hd_struct *part, unsigned int *inflight);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff814d9540)
Location: block/blk-mq.c:137
Inline: False
Direct callers:
  - block/genhd.c:part_in_flight_rw
```
**Symbols:**

```
ffffffff814d9540-ffffffff814d9591: blk_mq_in_flight_rw (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void blk_mq_in_flight_rw(struct request_queue *q, struct hd_struct *part, unsigned int *inflight);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff814e5060)
Location: block/blk-mq.c:137
Inline: False
Direct callers:
  - block/genhd.c:part_in_flight_rw
```
**Symbols:**

```
ffffffff814e5060-ffffffff814e50b1: blk_mq_in_flight_rw (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void blk_mq_in_flight_rw(struct request_queue *q, struct hd_struct *part, unsigned int *inflight);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff814fdfc0)
Location: block/blk-mq.c:137
Inline: False
Direct callers:
  - block/genhd.c:part_in_flight_rw
```
**Symbols:**

```
ffffffff814fdfc0-ffffffff814fe011: blk_mq_in_flight_rw (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
<details>
<summary>Changed between <code>5.8</code> and <code>5.11</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>struct hd_struct *part</code> ➡️ <code>struct block_device *part</code>
</li>
</ul>
</details>
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
