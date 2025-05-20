# Function: <code>blk_mq_in_flight</code>

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
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void blk_mq_in_flight(struct request_queue *q, struct hd_struct *part, unsigned int *inflight);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff8145c5d0)
Location: block/blk-mq.c:113
Inline: False
```
**Symbols:**

```
ffffffff8145c5d0-ffffffff8145c621: blk_mq_in_flight (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void blk_mq_in_flight(struct request_queue *q, struct hd_struct *part, unsigned int *inflight);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff8148fea0)
Location: block/blk-mq.c:109
Inline: False
```
**Symbols:**

```
ffffffff8148fea0-ffffffff8148fef1: blk_mq_in_flight (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
unsigned int blk_mq_in_flight(struct request_queue *q, struct hd_struct *part);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff814a97b0)
Location: block/blk-mq.c:111
Inline: False
```
**Symbols:**

```
ffffffff814a97b0-ffffffff814a9809: blk_mq_in_flight (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
unsigned int blk_mq_in_flight(struct request_queue *q, struct hd_struct *part);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff814d7610)
Location: block/blk-mq.c:113
Inline: False
```
**Symbols:**

```
ffffffff814d7610-ffffffff814d7669: blk_mq_in_flight (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
unsigned int blk_mq_in_flight(struct request_queue *q, struct hd_struct *part);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff814f0990)
Location: block/blk-mq.c:114
Inline: False
```
**Symbols:**

```
ffffffff814f0990-ffffffff814f09e9: blk_mq_in_flight (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
unsigned int blk_mq_in_flight(struct request_queue *q, struct hd_struct *part);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff81551b80)
Location: block/blk-mq.c:112
Inline: False
Direct callers:
  - block/genhd.c:diskstats_show
  - block/genhd.c:part_stat_show
```
**Symbols:**

```
ffffffff81551b80-ffffffff81551bd4: blk_mq_in_flight (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
unsigned int blk_mq_in_flight(struct request_queue *q, struct block_device *part);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff8156dcb0)
Location: block/blk-mq.c:115
Inline: False
Direct callers:
  - block/genhd.c:diskstats_show
  - block/genhd.c:part_stat_show
```
**Symbols:**

```
ffffffff8156dcb0-ffffffff8156dd04: blk_mq_in_flight (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
unsigned int blk_mq_in_flight(struct request_queue *q, struct block_device *part);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff81575790)
Location: block/blk-mq.c:115
Inline: False
Direct callers:
  - block/genhd.c:diskstats_show
  - block/genhd.c:part_stat_show
```
**Symbols:**

```
ffffffff81575790-ffffffff815757e4: blk_mq_in_flight (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
unsigned int blk_mq_in_flight(struct request_queue *q, struct block_device *part);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff815d9c30)
Location: block/blk-mq.c:115
Inline: False
Direct callers:
  - block/genhd.c:diskstats_show
  - block/genhd.c:part_stat_show
```
**Symbols:**

```
ffffffff815d9c30-ffffffff815d9c84: blk_mq_in_flight (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
unsigned int blk_mq_in_flight(struct request_queue *q, struct block_device *part);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff816875a0)
Location: block/blk-mq.c:144
Inline: False
Direct callers:
  - block/genhd.c:diskstats_show
  - block/genhd.c:part_stat_show
```
**Symbols:**

```
ffffffff816875a0-ffffffff816875fe: blk_mq_in_flight (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
unsigned int blk_mq_in_flight(struct request_queue *q, struct block_device *part);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff817458b0)
Location: block/blk-mq.c:144
Inline: False
Direct callers:
  - block/genhd.c:diskstats_show
  - block/genhd.c:part_stat_show
```
**Symbols:**

```
ffffffff817458b0-ffffffff8174590e: blk_mq_in_flight (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
unsigned int blk_mq_in_flight(struct request_queue *q, struct block_device *part);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff81782240)
Location: block/blk-mq.c:103
Inline: False
Direct callers:
  - block/genhd.c:diskstats_show
  - block/genhd.c:part_stat_show
```
**Symbols:**

```
ffffffff81782240-ffffffff8178229e: blk_mq_in_flight (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
unsigned int blk_mq_in_flight(struct request_queue *q, struct block_device *part);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff817c45e0)
Location: block/blk-mq.c:103
Inline: False
Direct callers:
  - block/genhd.c:diskstats_show
  - block/genhd.c:part_stat_show
```
**Symbols:**

```
ffffffff817c45e0-ffffffff817c463e: blk_mq_in_flight (STB_GLOBAL)
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
unsigned int blk_mq_in_flight(struct request_queue *q, struct hd_struct *part);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffff8000105efd48)
Location: block/blk-mq.c:114
Inline: False
```
**Symbols:**

```
ffff8000105efd48-ffff8000105efdc0: blk_mq_in_flight (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
unsigned int blk_mq_in_flight(struct request_queue *q, struct hd_struct *part);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (c079bf2c)
Location: block/blk-mq.c:114
Inline: False
```
**Symbols:**

```
c079bf2c-c079bfac: blk_mq_in_flight (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
unsigned int blk_mq_in_flight(struct request_queue *q, struct hd_struct *part);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (c000000000786440)
Location: block/blk-mq.c:114
Inline: False
```
**Symbols:**

```
c000000000786440-c0000000007864c4: blk_mq_in_flight (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
unsigned int blk_mq_in_flight(struct request_queue *q, struct hd_struct *part);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffe00042ede8)
Location: block/blk-mq.c:114
Inline: False
```
**Symbols:**

```
ffffffe00042ede8-ffffffe00042ee38: blk_mq_in_flight (STB_GLOBAL)
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
unsigned int blk_mq_in_flight(struct request_queue *q, struct hd_struct *part);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff814e8f70)
Location: block/blk-mq.c:114
Inline: False
```
**Symbols:**

```
ffffffff814e8f70-ffffffff814e8fc9: blk_mq_in_flight (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
unsigned int blk_mq_in_flight(struct request_queue *q, struct hd_struct *part);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff814d94e0)
Location: block/blk-mq.c:114
Inline: False
```
**Symbols:**

```
ffffffff814d94e0-ffffffff814d9539: blk_mq_in_flight (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
unsigned int blk_mq_in_flight(struct request_queue *q, struct hd_struct *part);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff814e5000)
Location: block/blk-mq.c:114
Inline: False
```
**Symbols:**

```
ffffffff814e5000-ffffffff814e5059: blk_mq_in_flight (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
unsigned int blk_mq_in_flight(struct request_queue *q, struct hd_struct *part);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff814fdf60)
Location: block/blk-mq.c:114
Inline: False
```
**Symbols:**

```
ffffffff814fdf60-ffffffff814fdfb9: blk_mq_in_flight (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>4.18</code> and <code>5.0</code> ⚠️</summary>
<ul>
<li>
<b>Param removed. </b>
<code>unsigned int *inflight</code>
</li>
<li>
<b>Return type changed. </b>
<code>void</code> ➡️ <code>unsigned int</code>
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
