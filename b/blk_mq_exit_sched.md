# Function: <code>blk_mq_exit_sched</code>

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
void blk_mq_exit_sched(struct request_queue *q, struct elevator_queue *e);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-sched.c (ffffffff81435ec0)
Location: block/blk-mq-sched.c:558
Inline: False
Direct callers:
  - block/elevator.c:elevator_exit
  - block/blk-mq-sched.c:blk_mq_init_sched
```
**Symbols:**

```
ffffffff81435ec0-ffffffff81435f5f: blk_mq_exit_sched (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void blk_mq_exit_sched(struct request_queue *q, struct elevator_queue *e);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-sched.c (ffffffff81461bd0)
Location: block/blk-mq-sched.c:617
Inline: False
Direct callers:
  - block/elevator.c:elevator_exit
  - block/blk-mq-sched.c:blk_mq_init_sched
```
**Symbols:**

```
ffffffff81461bd0-ffffffff81461c75: blk_mq_exit_sched (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void blk_mq_exit_sched(struct request_queue *q, struct elevator_queue *e);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-sched.c (ffffffff81495530)
Location: block/blk-mq-sched.c:634
Inline: False
Direct callers:
  - block/elevator.c:elevator_exit
  - block/blk-mq-sched.c:blk_mq_init_sched
```
**Symbols:**

```
ffffffff81495530-ffffffff814955d8: blk_mq_exit_sched (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void blk_mq_exit_sched(struct request_queue *q, struct elevator_queue *e);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-sched.c (ffffffff814af390)
Location: block/blk-mq-sched.c:529
Inline: False
Direct callers:
  - block/elevator.c:elevator_exit
  - block/blk-mq-sched.c:blk_mq_init_sched
```
**Symbols:**

```
ffffffff814af390-ffffffff814af42f: blk_mq_exit_sched (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void blk_mq_exit_sched(struct request_queue *q, struct elevator_queue *e);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-sched.c (ffffffff814dd6e0)
Location: block/blk-mq-sched.c:566
Inline: False
Direct callers:
  - block/elevator.c:__elevator_exit
  - block/blk-mq-sched.c:blk_mq_init_sched
```
**Symbols:**

```
ffffffff814dd6e0-ffffffff814dd783: blk_mq_exit_sched (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void blk_mq_exit_sched(struct request_queue *q, struct elevator_queue *e);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-sched.c (ffffffff814f6b70)
Location: block/blk-mq-sched.c:594
Inline: False
Direct callers:
  - block/elevator.c:__elevator_exit
  - block/blk-mq-sched.c:blk_mq_init_sched
```
**Symbols:**

```
ffffffff814f6b70-ffffffff814f6c13: blk_mq_exit_sched (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void blk_mq_exit_sched(struct request_queue *q, struct elevator_queue *e);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-sched.c (ffffffff81557610)
Location: block/blk-mq-sched.c:659
Inline: False
Direct callers:
  - block/elevator.c:elevator_switch_mq
  - block/elevator.c:elevator_switch_mq
  - block/blk-mq-sched.c:blk_mq_init_sched
```
**Symbols:**

```
ffffffff81557610-ffffffff815576e3: blk_mq_exit_sched (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void blk_mq_exit_sched(struct request_queue *q, struct elevator_queue *e);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-sched.c (ffffffff81573c20)
Location: block/blk-mq-sched.c:628
Inline: False
Direct callers:
  - block/elevator.c:elevator_switch_mq
  - block/elevator.c:elevator_switch_mq
  - block/blk-mq-sched.c:blk_mq_init_sched
```
**Symbols:**

```
ffffffff81573c20-ffffffff81573cfd: blk_mq_exit_sched (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void blk_mq_exit_sched(struct request_queue *q, struct elevator_queue *e);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-sched.c (ffffffff8157bcb0)
Location: block/blk-mq-sched.c:630
Inline: False
Direct callers:
  - block/elevator.c:elevator_switch_mq
  - block/elevator.c:elevator_switch_mq
  - block/blk-mq-sched.c:blk_mq_init_sched
```
**Symbols:**

```
ffffffff8157bcb0-ffffffff8157bd8d: blk_mq_exit_sched (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void blk_mq_exit_sched(struct request_queue *q, struct elevator_queue *e);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-sched.c (ffffffff815e1090)
Location: block/blk-mq-sched.c:670
Inline: False
Direct callers:
  - block/elevator.c:elevator_switch_mq
  - block/elevator.c:elevator_switch_mq
  - block/blk-mq-sched.c:blk_mq_init_sched
```
**Symbols:**

```
ffffffff815e1090-ffffffff815e11e1: blk_mq_exit_sched (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void blk_mq_exit_sched(struct request_queue *q, struct elevator_queue *e);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-sched.c (ffffffff8168fd60)
Location: block/blk-mq-sched.c:648
Inline: False
Direct callers:
  - block/blk-mq-sched.c:blk_mq_init_sched
```
**Symbols:**

```
ffffffff8168fd60-ffffffff8168fead: blk_mq_exit_sched (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void blk_mq_exit_sched(struct request_queue *q, struct elevator_queue *e);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-sched.c (ffffffff8174e910)
Location: block/blk-mq-sched.c:641
Inline: False
Direct callers:
  - block/elevator.c:elevator_disable
  - block/elevator.c:elevator_switch
  - block/elevator.c:elevator_switch
  - block/blk-mq-sched.c:blk_mq_init_sched
```
**Symbols:**

```
ffffffff8174e910-ffffffff8174ea5d: blk_mq_exit_sched (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void blk_mq_exit_sched(struct request_queue *q, struct elevator_queue *e);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-sched.c (ffffffff8178ab90)
Location: block/blk-mq-sched.c:526
Inline: False
Direct callers:
  - block/elevator.c:elevator_disable
  - block/elevator.c:elevator_switch
  - block/elevator.c:elevator_switch
  - block/blk-mq-sched.c:blk_mq_init_sched
```
**Symbols:**

```
ffffffff8178ab90-ffffffff8178aceb: blk_mq_exit_sched (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void blk_mq_exit_sched(struct request_queue *q, struct elevator_queue *e);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-sched.c (ffffffff817cd2e0)
Location: block/blk-mq-sched.c:524
Inline: False
Direct callers:
  - block/elevator.c:elevator_disable
  - block/elevator.c:elevator_switch
  - block/elevator.c:elevator_switch
  - block/blk-mq-sched.c:blk_mq_init_sched
```
**Symbols:**

```
ffffffff817cd2e0-ffffffff817cd43b: blk_mq_exit_sched (STB_GLOBAL)
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
void blk_mq_exit_sched(struct request_queue *q, struct elevator_queue *e);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-sched.c (ffff8000105f7288)
Location: block/blk-mq-sched.c:594
Inline: False
Direct callers:
  - block/elevator.c:__elevator_exit
  - block/blk-mq-sched.c:blk_mq_init_sched
```
**Symbols:**

```
ffff8000105f7288-ffff8000105f7338: blk_mq_exit_sched (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void blk_mq_exit_sched(struct request_queue *q, struct elevator_queue *e);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-sched.c (c07a29c8)
Location: block/blk-mq-sched.c:594
Inline: False
Direct callers:
  - block/elevator.c:__elevator_exit
  - block/blk-mq-sched.c:blk_mq_init_sched
```
**Symbols:**

```
c07a29c8-c07a2a78: blk_mq_exit_sched (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void blk_mq_exit_sched(struct request_queue *q, struct elevator_queue *e);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-sched.c (c00000000078f8a0)
Location: block/blk-mq-sched.c:594
Inline: False
Direct callers:
  - block/elevator.c:__elevator_exit
  - block/blk-mq-sched.c:blk_mq_init_sched
```
**Symbols:**

```
c00000000078f8a0-c00000000078f9b0: blk_mq_exit_sched (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void blk_mq_exit_sched(struct request_queue *q, struct elevator_queue *e);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-sched.c (ffffffe000434936)
Location: block/blk-mq-sched.c:594
Inline: False
Direct callers:
  - block/elevator.c:__elevator_exit
  - block/blk-mq-sched.c:blk_mq_init_sched
```
**Symbols:**

```
ffffffe000434936-ffffffe0004349cc: blk_mq_exit_sched (STB_GLOBAL)
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
void blk_mq_exit_sched(struct request_queue *q, struct elevator_queue *e);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-sched.c (ffffffff814ef150)
Location: block/blk-mq-sched.c:594
Inline: False
Direct callers:
  - block/elevator.c:__elevator_exit
  - block/blk-mq-sched.c:blk_mq_init_sched
```
**Symbols:**

```
ffffffff814ef150-ffffffff814ef1f3: blk_mq_exit_sched (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void blk_mq_exit_sched(struct request_queue *q, struct elevator_queue *e);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-sched.c (ffffffff814df690)
Location: block/blk-mq-sched.c:594
Inline: False
Direct callers:
  - block/elevator.c:__elevator_exit
  - block/blk-mq-sched.c:blk_mq_init_sched
```
**Symbols:**

```
ffffffff814df690-ffffffff814df733: blk_mq_exit_sched (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void blk_mq_exit_sched(struct request_queue *q, struct elevator_queue *e);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-sched.c (ffffffff814eb1e0)
Location: block/blk-mq-sched.c:594
Inline: False
Direct callers:
  - block/elevator.c:__elevator_exit
  - block/blk-mq-sched.c:blk_mq_init_sched
```
**Symbols:**

```
ffffffff814eb1e0-ffffffff814eb283: blk_mq_exit_sched (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void blk_mq_exit_sched(struct request_queue *q, struct elevator_queue *e);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-sched.c (ffffffff815041f0)
Location: block/blk-mq-sched.c:594
Inline: False
Direct callers:
  - block/elevator.c:__elevator_exit
  - block/blk-mq-sched.c:blk_mq_init_sched
```
**Symbols:**

```
ffffffff815041f0-ffffffff81504293: blk_mq_exit_sched (STB_GLOBAL)
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
