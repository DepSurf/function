# Function: <code>blk_mq_sched_free_requests</code>

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
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void blk_mq_sched_free_requests(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-sched.c (ffffffff814dd690)
Location: block/blk-mq-sched.c:553
Inline: False
Direct callers:
  - block/blk-core.c:blk_cleanup_queue
  - block/blk-mq-sched.c:blk_mq_init_sched
  - block/blk-mq-sched.c:blk_mq_init_sched
```
**Symbols:**

```
ffffffff814dd690-ffffffff814dd6df: blk_mq_sched_free_requests (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void blk_mq_sched_free_requests(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-sched.c (ffffffff814f6b20)
Location: block/blk-mq-sched.c:583
Inline: False
Direct callers:
  - block/blk-core.c:blk_cleanup_queue
  - block/blk-mq-sched.c:blk_mq_init_sched
  - block/blk-mq-sched.c:blk_mq_init_sched
```
**Symbols:**

```
ffffffff814f6b20-ffffffff814f6b6f: blk_mq_sched_free_requests (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void blk_mq_sched_free_requests(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-mq-sched.c (ffffffff815577dd)
Location: block/blk-mq-sched.c:648
Inline: True
Inline callers:
  - block/blk-mq-sched.c:blk_mq_init_sched
  - block/blk-mq-sched.c:blk_mq_init_sched
Direct callers:
  - block/elevator.c:elevator_switch_mq
  - block/elevator.c:elevator_switch_mq
  - block/blk-core.c:blk_cleanup_queue
```
**Symbols:**

```
ffffffff815575c0-ffffffff8155760f: blk_mq_sched_free_requests (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void blk_mq_sched_free_requests(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-mq-sched.c (ffffffff81573e02)
Location: block/blk-mq-sched.c:617
Inline: True
Inline callers:
  - block/blk-mq-sched.c:blk_mq_init_sched
  - block/blk-mq-sched.c:blk_mq_init_sched
Direct callers:
  - block/elevator.c:elevator_switch_mq
  - block/elevator.c:elevator_switch_mq
  - block/blk-core.c:blk_cleanup_queue
```
**Symbols:**

```
ffffffff81573bd0-ffffffff81573c1f: blk_mq_sched_free_requests (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void blk_mq_sched_free_requests(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-mq-sched.c (ffffffff8157be8e)
Location: block/blk-mq-sched.c:619
Inline: True
Inline callers:
  - block/blk-mq-sched.c:blk_mq_init_sched
  - block/blk-mq-sched.c:blk_mq_init_sched
Direct callers:
  - block/elevator.c:elevator_switch_mq
  - block/elevator.c:elevator_switch_mq
  - block/blk-core.c:blk_cleanup_queue
```
**Symbols:**

```
ffffffff8157bc60-ffffffff8157bcaf: blk_mq_sched_free_requests (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void blk_mq_sched_free_requests(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-mq-sched.c (ffffffff815e12ca)
Location: block/blk-mq-sched.c:659
Inline: True
Inline callers:
  - block/blk-mq-sched.c:blk_mq_init_sched
  - block/blk-mq-sched.c:blk_mq_init_sched
Direct callers:
  - block/elevator.c:elevator_switch_mq
  - block/elevator.c:elevator_switch_mq
  - block/blk-core.c:blk_cleanup_queue
```
**Symbols:**

```
ffffffff815e1040-ffffffff815e108f: blk_mq_sched_free_requests (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
void blk_mq_sched_free_requests(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-sched.c (ffff8000105f7228)
Location: block/blk-mq-sched.c:583
Inline: False
Direct callers:
  - block/blk-core.c:blk_cleanup_queue
  - block/blk-mq-sched.c:blk_mq_init_sched
  - block/blk-mq-sched.c:blk_mq_init_sched
```
**Symbols:**

```
ffff8000105f7228-ffff8000105f7288: blk_mq_sched_free_requests (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void blk_mq_sched_free_requests(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-sched.c (c07a296c)
Location: block/blk-mq-sched.c:583
Inline: False
Direct callers:
  - block/blk-core.c:blk_cleanup_queue
  - block/blk-mq-sched.c:blk_mq_init_sched
  - block/blk-mq-sched.c:blk_mq_init_sched
```
**Symbols:**

```
c07a296c-c07a29c8: blk_mq_sched_free_requests (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void blk_mq_sched_free_requests(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-sched.c (c00000000078f800)
Location: block/blk-mq-sched.c:583
Inline: False
Direct callers:
  - block/blk-core.c:blk_cleanup_queue
  - block/blk-mq-sched.c:blk_mq_init_sched
  - block/blk-mq-sched.c:blk_mq_init_sched
```
**Symbols:**

```
c00000000078f800-c00000000078f894: blk_mq_sched_free_requests (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void blk_mq_sched_free_requests(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-sched.c (ffffffe0004348d6)
Location: block/blk-mq-sched.c:583
Inline: False
Direct callers:
  - block/blk-core.c:blk_cleanup_queue
  - block/blk-mq-sched.c:blk_mq_init_sched
  - block/blk-mq-sched.c:blk_mq_init_sched
```
**Symbols:**

```
ffffffe0004348d6-ffffffe000434936: blk_mq_sched_free_requests (STB_GLOBAL)
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
void blk_mq_sched_free_requests(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-sched.c (ffffffff814ef100)
Location: block/blk-mq-sched.c:583
Inline: False
Direct callers:
  - block/blk-core.c:blk_cleanup_queue
  - block/blk-mq-sched.c:blk_mq_init_sched
  - block/blk-mq-sched.c:blk_mq_init_sched
```
**Symbols:**

```
ffffffff814ef100-ffffffff814ef14f: blk_mq_sched_free_requests (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void blk_mq_sched_free_requests(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-sched.c (ffffffff814df640)
Location: block/blk-mq-sched.c:583
Inline: False
Direct callers:
  - block/blk-core.c:blk_cleanup_queue
  - block/blk-mq-sched.c:blk_mq_init_sched
  - block/blk-mq-sched.c:blk_mq_init_sched
```
**Symbols:**

```
ffffffff814df640-ffffffff814df68f: blk_mq_sched_free_requests (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void blk_mq_sched_free_requests(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-sched.c (ffffffff814eb190)
Location: block/blk-mq-sched.c:583
Inline: False
Direct callers:
  - block/blk-core.c:blk_cleanup_queue
  - block/blk-mq-sched.c:blk_mq_init_sched
  - block/blk-mq-sched.c:blk_mq_init_sched
```
**Symbols:**

```
ffffffff814eb190-ffffffff814eb1df: blk_mq_sched_free_requests (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void blk_mq_sched_free_requests(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-sched.c (ffffffff815041a0)
Location: block/blk-mq-sched.c:583
Inline: False
Direct callers:
  - block/blk-core.c:blk_cleanup_queue
  - block/blk-mq-sched.c:blk_mq_init_sched
  - block/blk-mq-sched.c:blk_mq_init_sched
```
**Symbols:**

```
ffffffff815041a0-ffffffff815041ef: blk_mq_sched_free_requests (STB_GLOBAL)
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
