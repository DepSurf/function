# Function: <code>elevator_init_mq</code>

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
int elevator_init_mq(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/elevator.c (ffffffff8147d290)
Location: block/elevator.c:981
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_init_allocated_queue
```
**Symbols:**

```
ffffffff8147d290-ffffffff8147d320: elevator_init_mq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int elevator_init_mq(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/elevator.c (ffffffff8149ab70)
Location: block/elevator.c:603
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_init_allocated_queue
```
**Symbols:**

```
ffffffff8149ab70-ffffffff8149abfa: elevator_init_mq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int elevator_init_mq(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/elevator.c (ffffffff814c8c50)
Location: block/elevator.c:602
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_init_allocated_queue
```
**Symbols:**

```
ffffffff814c8c50-ffffffff814c8ce6: elevator_init_mq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
void elevator_init_mq(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/elevator.c (0)
Location: block/elevator.c:668
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_init_allocated_queue
  - block/genhd.c:__device_add_disk
```
**Symbols:**

```
ffffffff814e2233-ffffffff814e2257: elevator_init_mq.cold (STB_LOCAL)
ffffffff814e1d90-ffffffff814e1ec3: elevator_init_mq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
void elevator_init_mq(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/elevator.c (0)
Location: block/elevator.c:668
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_init_allocated_queue
  - block/genhd.c:__device_add_disk
```
**Symbols:**

```
ffffffff81540ef9-ffffffff81540f1d: elevator_init_mq.cold (STB_LOCAL)
ffffffff81540bc0-ffffffff81540d00: elevator_init_mq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
void elevator_init_mq(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/elevator.c (0)
Location: block/elevator.c:661
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_init_allocated_queue
  - block/genhd.c:__device_add_disk
```
**Symbols:**

```
ffffffff81bf2557-ffffffff81bf257b: elevator_init_mq.cold (STB_LOCAL)
ffffffff8155d340-ffffffff8155d480: elevator_init_mq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
void elevator_init_mq(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/elevator.c (0)
Location: block/elevator.c:662
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_init_allocated_queue
  - block/genhd.c:__device_add_disk
```
**Symbols:**

```
ffffffff81be451b-ffffffff81be453f: elevator_init_mq.cold (STB_LOCAL)
ffffffff81565bc0-ffffffff81565d1c: elevator_init_mq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void elevator_init_mq(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/elevator.c (0)
Location: block/elevator.c:675
Inline: False
Direct callers:
  - block/genhd.c:device_add_disk
```
**Symbols:**

```
ffffffff81cd7fbd-ffffffff81cd7fe1: elevator_init_mq.cold (STB_LOCAL)
ffffffff815c9f90-ffffffff815ca0e2: elevator_init_mq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void elevator_init_mq(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/elevator.c (0)
Location: block/elevator.c:679
Inline: False
Direct callers:
  - block/genhd.c:device_add_disk
```
**Symbols:**

```
ffffffff81e8b3d1-ffffffff81e8b3f5: elevator_init_mq.cold (STB_LOCAL)
ffffffff81675360-ffffffff816754e7: elevator_init_mq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void elevator_init_mq(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/elevator.c (ffffffff81730d90)
Location: block/elevator.c:609
Inline: False
Direct callers:
  - block/genhd.c:device_add_disk
```
**Symbols:**

```
ffffffff81730d90-ffffffff81730f32: elevator_init_mq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void elevator_init_mq(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/elevator.c (ffffffff8176cff0)
Location: block/elevator.c:612
Inline: False
Direct callers:
  - block/genhd.c:device_add_disk
```
**Symbols:**

```
ffffffff8176cff0-ffffffff8176d195: elevator_init_mq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void elevator_init_mq(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/elevator.c (ffffffff817af220)
Location: block/elevator.c:612
Inline: False
Direct callers:
  - block/genhd.c:device_add_disk
```
**Symbols:**

```
ffffffff817af220-ffffffff817af3c2: elevator_init_mq (STB_GLOBAL)
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
void elevator_init_mq(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/elevator.c (ffff8000105def90)
Location: block/elevator.c:668
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_init_allocated_queue
  - block/genhd.c:__device_add_disk
```
**Symbols:**

```
ffff8000105def90-ffff8000105df140: elevator_init_mq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void elevator_init_mq(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/elevator.c (c078be74)
Location: block/elevator.c:668
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_init_allocated_queue
  - block/genhd.c:__device_add_disk
```
**Symbols:**

```
c078be74-c078c018: elevator_init_mq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void elevator_init_mq(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/elevator.c (c000000000770f60)
Location: block/elevator.c:668
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_init_allocated_queue
  - block/genhd.c:__device_add_disk
```
**Symbols:**

```
c000000000770f60-c000000000771194: elevator_init_mq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void elevator_init_mq(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/elevator.c (ffffffe000421a5e)
Location: block/elevator.c:668
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_init_allocated_queue
  - block/genhd.c:__device_add_disk
```
**Symbols:**

```
ffffffe000421a5e-ffffffe000421bc8: elevator_init_mq (STB_GLOBAL)
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
void elevator_init_mq(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/elevator.c (0)
Location: block/elevator.c:668
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_init_allocated_queue
  - block/genhd.c:__device_add_disk
```
**Symbols:**

```
ffffffff814da813-ffffffff814da837: elevator_init_mq.cold (STB_LOCAL)
ffffffff814da370-ffffffff814da4a3: elevator_init_mq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
void elevator_init_mq(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/elevator.c (0)
Location: block/elevator.c:668
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_init_allocated_queue
  - block/genhd.c:__device_add_disk
```
**Symbols:**

```
ffffffff814cb1c3-ffffffff814cb1e7: elevator_init_mq.cold (STB_LOCAL)
ffffffff814cad20-ffffffff814cae53: elevator_init_mq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
void elevator_init_mq(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/elevator.c (0)
Location: block/elevator.c:668
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_init_allocated_queue
  - block/genhd.c:__device_add_disk
```
**Symbols:**

```
ffffffff814d68a3-ffffffff814d68c7: elevator_init_mq.cold (STB_LOCAL)
ffffffff814d6400-ffffffff814d6533: elevator_init_mq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
void elevator_init_mq(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/elevator.c (0)
Location: block/elevator.c:668
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_init_allocated_queue
  - block/genhd.c:__device_add_disk
```
**Symbols:**

```
ffffffff814ef4b1-ffffffff814ef4d5: elevator_init_mq.cold (STB_LOCAL)
ffffffff814ef000-ffffffff814ef141: elevator_init_mq (STB_GLOBAL)
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
<details>
<summary>Changed between <code>5.3</code> and <code>5.4</code> ⚠️</summary>
<ul>
<li>
<b>Return type changed. </b>
<code>int</code> ➡️ <code>void</code>
</li>
</ul>
</details>
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
