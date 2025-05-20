# Function: <code>blk_mq_init_sched</code>

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
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int blk_mq_init_sched(struct request_queue *q, struct elevator_type *e);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-sched.c (ffffffff81435f60)
Location: block/blk-mq-sched.c:505
Inline: False
Direct callers:
  - block/elevator.c:elevator_switch
  - block/elevator.c:elevator_init
```
**Symbols:**

```
ffffffff81435f60-ffffffff814360ab: blk_mq_init_sched (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int blk_mq_init_sched(struct request_queue *q, struct elevator_type *e);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-sched.c (ffffffff81461c80)
Location: block/blk-mq-sched.c:564
Inline: False
Direct callers:
  - block/elevator.c:elevator_switch
  - block/elevator.c:elevator_init
```
**Symbols:**

```
ffffffff81461c80-ffffffff81461dd3: blk_mq_init_sched (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int blk_mq_init_sched(struct request_queue *q, struct elevator_type *e);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-sched.c (ffffffff814955e0)
Location: block/blk-mq-sched.c:580
Inline: False
Direct callers:
  - block/elevator.c:elevator_switch
  - block/elevator.c:elevator_init_mq
```
**Symbols:**

```
ffffffff814955e0-ffffffff8149573d: blk_mq_init_sched (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int blk_mq_init_sched(struct request_queue *q, struct elevator_type *e);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-sched.c (ffffffff814af430)
Location: block/blk-mq-sched.c:475
Inline: False
Direct callers:
  - block/elevator.c:elevator_init_mq
```
**Symbols:**

```
ffffffff814af430-ffffffff814af5ed: blk_mq_init_sched (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int blk_mq_init_sched(struct request_queue *q, struct elevator_type *e);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-sched.c (ffffffff814dd790)
Location: block/blk-mq-sched.c:493
Inline: False
Direct callers:
  - block/elevator.c:elevator_init_mq
```
**Symbols:**

```
ffffffff814dd790-ffffffff814dd96b: blk_mq_init_sched (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int blk_mq_init_sched(struct request_queue *q, struct elevator_type *e);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-sched.c (ffffffff814f6c20)
Location: block/blk-mq-sched.c:523
Inline: False
Direct callers:
  - block/elevator.c:elevator_init_mq
```
**Symbols:**

```
ffffffff814f6c20-ffffffff814f6dfb: blk_mq_init_sched (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int blk_mq_init_sched(struct request_queue *q, struct elevator_type *e);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-sched.c (ffffffff815576f0)
Location: block/blk-mq-sched.c:588
Inline: False
Direct callers:
  - block/elevator.c:elevator_init_mq
  - block/elevator.c:elevator_switch_mq
```
**Symbols:**

```
ffffffff815576f0-ffffffff8155795f: blk_mq_init_sched (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int blk_mq_init_sched(struct request_queue *q, struct elevator_type *e);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-sched.c (ffffffff81573d00)
Location: block/blk-mq-sched.c:557
Inline: False
Direct callers:
  - block/elevator.c:elevator_init_mq
  - block/elevator.c:elevator_switch_mq
```
**Symbols:**

```
ffffffff81573d00-ffffffff81573f8e: blk_mq_init_sched (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int blk_mq_init_sched(struct request_queue *q, struct elevator_type *e);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-sched.c (ffffffff8157bd90)
Location: block/blk-mq-sched.c:559
Inline: False
Direct callers:
  - block/elevator.c:elevator_init_mq
  - block/elevator.c:elevator_switch_mq
```
**Symbols:**

```
ffffffff8157bd90-ffffffff8157c01a: blk_mq_init_sched (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int blk_mq_init_sched(struct request_queue *q, struct elevator_type *e);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-sched.c (ffffffff815e11f0)
Location: block/blk-mq-sched.c:590
Inline: False
Direct callers:
  - block/elevator.c:elevator_init_mq
  - block/elevator.c:elevator_switch_mq
```
**Symbols:**

```
ffffffff815e11f0-ffffffff815e1570: blk_mq_init_sched (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int blk_mq_init_sched(struct request_queue *q, struct elevator_type *e);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-sched.c (ffffffff8168feb0)
Location: block/blk-mq-sched.c:558
Inline: False
Direct callers:
  - block/elevator.c:elevator_init_mq
```
**Symbols:**

```
ffffffff8168feb0-ffffffff8169014e: blk_mq_init_sched (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int blk_mq_init_sched(struct request_queue *q, struct elevator_type *e);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-sched.c (ffffffff8174ea70)
Location: block/blk-mq-sched.c:558
Inline: False
Direct callers:
  - block/elevator.c:elevator_switch
  - block/elevator.c:elevator_init_mq
```
**Symbols:**

```
ffffffff8174ea70-ffffffff8174ecbe: blk_mq_init_sched (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int blk_mq_init_sched(struct request_queue *q, struct elevator_type *e);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-sched.c (ffffffff8178ad00)
Location: block/blk-mq-sched.c:443
Inline: False
Direct callers:
  - block/elevator.c:elevator_switch
  - block/elevator.c:elevator_init_mq
```
**Symbols:**

```
ffffffff8178ad00-ffffffff8178af4e: blk_mq_init_sched (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int blk_mq_init_sched(struct request_queue *q, struct elevator_type *e);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-sched.c (ffffffff817cd450)
Location: block/blk-mq-sched.c:441
Inline: False
Direct callers:
  - block/elevator.c:elevator_switch
  - block/elevator.c:elevator_init_mq
```
**Symbols:**

```
ffffffff817cd450-ffffffff817cd69e: blk_mq_init_sched (STB_GLOBAL)
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
int blk_mq_init_sched(struct request_queue *q, struct elevator_type *e);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-sched.c (ffff8000105f7338)
Location: block/blk-mq-sched.c:523
Inline: False
Direct callers:
  - block/elevator.c:elevator_init_mq
```
**Symbols:**

```
ffff8000105f7338-ffff8000105f7508: blk_mq_init_sched (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int blk_mq_init_sched(struct request_queue *q, struct elevator_type *e);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-sched.c (c07a2a78)
Location: block/blk-mq-sched.c:523
Inline: False
Direct callers:
  - block/elevator.c:elevator_init_mq
```
**Symbols:**

```
c07a2a78-c07a2c24: blk_mq_init_sched (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int blk_mq_init_sched(struct request_queue *q, struct elevator_type *e);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-sched.c (c00000000078f9b0)
Location: block/blk-mq-sched.c:523
Inline: False
Direct callers:
  - block/elevator.c:elevator_init_mq
```
**Symbols:**

```
c00000000078f9b0-c00000000078fc54: blk_mq_init_sched (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int blk_mq_init_sched(struct request_queue *q, struct elevator_type *e);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-sched.c (ffffffe0004349cc)
Location: block/blk-mq-sched.c:523
Inline: False
Direct callers:
  - block/elevator.c:elevator_init_mq
```
**Symbols:**

```
ffffffe0004349cc-ffffffe000434b4a: blk_mq_init_sched (STB_GLOBAL)
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
int blk_mq_init_sched(struct request_queue *q, struct elevator_type *e);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-sched.c (ffffffff814ef200)
Location: block/blk-mq-sched.c:523
Inline: False
Direct callers:
  - block/elevator.c:elevator_init_mq
```
**Symbols:**

```
ffffffff814ef200-ffffffff814ef3db: blk_mq_init_sched (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int blk_mq_init_sched(struct request_queue *q, struct elevator_type *e);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-sched.c (ffffffff814df740)
Location: block/blk-mq-sched.c:523
Inline: False
Direct callers:
  - block/elevator.c:elevator_init_mq
```
**Symbols:**

```
ffffffff814df740-ffffffff814df91b: blk_mq_init_sched (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int blk_mq_init_sched(struct request_queue *q, struct elevator_type *e);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-sched.c (ffffffff814eb290)
Location: block/blk-mq-sched.c:523
Inline: False
Direct callers:
  - block/elevator.c:elevator_init_mq
```
**Symbols:**

```
ffffffff814eb290-ffffffff814eb46b: blk_mq_init_sched (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int blk_mq_init_sched(struct request_queue *q, struct elevator_type *e);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-sched.c (ffffffff815042a0)
Location: block/blk-mq-sched.c:523
Inline: False
Direct callers:
  - block/elevator.c:elevator_init_mq
```
**Symbols:**

```
ffffffff815042a0-ffffffff8150447b: blk_mq_init_sched (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
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
