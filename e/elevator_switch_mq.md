# Function: <code>elevator_switch_mq</code>

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
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/elevator.c (ffffffff8141eb83)
Location: block/elevator.c:948
Inline: True
Inline callers:
  - block/elevator.c:elevator_switch
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
In block/elevator.c (ffffffff8144965e)
Location: block/elevator.c:965
Inline: True
Inline callers:
  - block/elevator.c:elevator_switch
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
In block/elevator.c (ffffffff8147d10a)
Location: block/elevator.c:936
Inline: True
Inline callers:
  - block/elevator.c:elevator_switch
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int elevator_switch_mq(struct request_queue *q, struct elevator_type *new_e);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/elevator.c (ffffffff8149aa50)
Location: block/elevator.c:563
Inline: True
Direct callers:
  - block/elevator.c:elevator_switch
  - block/blk-mq.c:blk_mq_update_nr_hw_queues
  - block/blk-mq.c:blk_mq_update_nr_hw_queues
```
**Symbols:**

```
ffffffff8149aa50-ffffffff8149ab1e: elevator_switch_mq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
int elevator_switch_mq(struct request_queue *q, struct elevator_type *new_e);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/elevator.c (ffffffff814c8b10)
Location: block/elevator.c:562
Inline: True
Direct callers:
  - block/elevator.c:elevator_switch
  - block/blk-mq.c:blk_mq_update_nr_hw_queues
  - block/blk-mq.c:blk_mq_update_nr_hw_queues
```
**Symbols:**

```
ffffffff814c8b10-ffffffff814c8bf4: elevator_switch_mq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int elevator_switch_mq(struct request_queue *q, struct elevator_type *new_e);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/elevator.c (ffffffff814e1c40)
Location: block/elevator.c:581
Inline: True
Direct callers:
  - block/elevator.c:elevator_switch
  - block/blk-mq.c:blk_mq_update_nr_hw_queues
  - block/blk-mq.c:blk_mq_update_nr_hw_queues
```
**Symbols:**

```
ffffffff814e1c40-ffffffff814e1d37: elevator_switch_mq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int elevator_switch_mq(struct request_queue *q, struct elevator_type *new_e);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/elevator.c (ffffffff81540840)
Location: block/elevator.c:581
Inline: False
Direct callers:
  - block/elevator.c:__elevator_change
  - block/blk-mq.c:__blk_mq_update_nr_hw_queues
  - block/blk-mq.c:__blk_mq_update_nr_hw_queues
```
**Symbols:**

```
ffffffff81540840-ffffffff815409bf: elevator_switch_mq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int elevator_switch_mq(struct request_queue *q, struct elevator_type *new_e);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/elevator.c (ffffffff8155cfe0)
Location: block/elevator.c:574
Inline: False
Direct callers:
  - block/elevator.c:__elevator_change
  - block/blk-mq.c:__blk_mq_update_nr_hw_queues
  - block/blk-mq.c:__blk_mq_update_nr_hw_queues
```
**Symbols:**

```
ffffffff8155cfe0-ffffffff8155d135: elevator_switch_mq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int elevator_switch_mq(struct request_queue *q, struct elevator_type *new_e);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/elevator.c (ffffffff81565870)
Location: block/elevator.c:574
Inline: False
Direct callers:
  - block/elevator.c:__elevator_change
  - block/blk-mq.c:__blk_mq_update_nr_hw_queues
  - block/blk-mq.c:__blk_mq_update_nr_hw_queues
```
**Symbols:**

```
ffffffff81565870-ffffffff815659c5: elevator_switch_mq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int elevator_switch_mq(struct request_queue *q, struct elevator_type *new_e);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/elevator.c (ffffffff815c9c50)
Location: block/elevator.c:584
Inline: False
Direct callers:
  - block/elevator.c:__elevator_change
  - block/blk-mq.c:__blk_mq_update_nr_hw_queues
  - block/blk-mq.c:__blk_mq_update_nr_hw_queues
```
**Symbols:**

```
ffffffff815c9c50-ffffffff815c9d9d: elevator_switch_mq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
int elevator_switch_mq(struct request_queue *q, struct elevator_type *new_e);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/elevator.c (ffffffff81674fd0)
Location: block/elevator.c:591
Inline: True
Direct callers:
  - block/elevator.c:__elevator_change
  - block/blk-mq.c:__blk_mq_update_nr_hw_queues
  - block/blk-mq.c:__blk_mq_update_nr_hw_queues
```
**Symbols:**

```
ffffffff81674fd0-ffffffff8167514f: elevator_switch_mq (STB_GLOBAL)
```
</details>
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
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
int elevator_switch_mq(struct request_queue *q, struct elevator_type *new_e);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/elevator.c (ffff8000105dee30)
Location: block/elevator.c:581
Inline: True
Direct callers:
  - block/elevator.c:elevator_switch
  - block/blk-mq.c:blk_mq_update_nr_hw_queues
  - block/blk-mq.c:blk_mq_update_nr_hw_queues
```
**Symbols:**

```
ffff8000105dee30-ffff8000105def30: elevator_switch_mq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int elevator_switch_mq(struct request_queue *q, struct elevator_type *new_e);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/elevator.c (c078bd24)
Location: block/elevator.c:581
Inline: True
Direct callers:
  - block/elevator.c:elevator_switch
  - block/blk-mq.c:blk_mq_update_nr_hw_queues
  - block/blk-mq.c:blk_mq_update_nr_hw_queues
```
**Symbols:**

```
c078bd24-c078be24: elevator_switch_mq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
int elevator_switch_mq(struct request_queue *q, struct elevator_type *new_e);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/elevator.c (c000000000770d60)
Location: block/elevator.c:581
Inline: True
Direct callers:
  - block/elevator.c:elevator_switch
  - block/blk-mq.c:blk_mq_update_nr_hw_queues
  - block/blk-mq.c:blk_mq_update_nr_hw_queues
```
**Symbols:**

```
c000000000770d60-c000000000770ecc: elevator_switch_mq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
int elevator_switch_mq(struct request_queue *q, struct elevator_type *new_e);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/elevator.c (ffffffe00042191e)
Location: block/elevator.c:581
Inline: True
Direct callers:
  - block/elevator.c:elevator_switch
  - block/blk-mq.c:blk_mq_update_nr_hw_queues
  - block/blk-mq.c:blk_mq_update_nr_hw_queues
```
**Symbols:**

```
ffffffe00042191e-ffffffe000421a00: elevator_switch_mq (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
int elevator_switch_mq(struct request_queue *q, struct elevator_type *new_e);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/elevator.c (ffffffff814da220)
Location: block/elevator.c:581
Inline: True
Direct callers:
  - block/elevator.c:elevator_switch
  - block/blk-mq.c:blk_mq_update_nr_hw_queues
  - block/blk-mq.c:blk_mq_update_nr_hw_queues
```
**Symbols:**

```
ffffffff814da220-ffffffff814da317: elevator_switch_mq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int elevator_switch_mq(struct request_queue *q, struct elevator_type *new_e);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/elevator.c (ffffffff814cabd0)
Location: block/elevator.c:581
Inline: True
Direct callers:
  - block/elevator.c:elevator_switch
  - block/blk-mq.c:blk_mq_update_nr_hw_queues
  - block/blk-mq.c:blk_mq_update_nr_hw_queues
```
**Symbols:**

```
ffffffff814cabd0-ffffffff814cacc7: elevator_switch_mq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int elevator_switch_mq(struct request_queue *q, struct elevator_type *new_e);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/elevator.c (ffffffff814d62b0)
Location: block/elevator.c:581
Inline: True
Direct callers:
  - block/elevator.c:elevator_switch
  - block/blk-mq.c:blk_mq_update_nr_hw_queues
  - block/blk-mq.c:blk_mq_update_nr_hw_queues
```
**Symbols:**

```
ffffffff814d62b0-ffffffff814d63a7: elevator_switch_mq (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int elevator_switch_mq(struct request_queue *q, struct elevator_type *new_e);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/elevator.c (ffffffff814eeeb0)
Location: block/elevator.c:581
Inline: True
Direct callers:
  - block/elevator.c:elevator_switch
  - block/blk-mq.c:blk_mq_update_nr_hw_queues
  - block/blk-mq.c:blk_mq_update_nr_hw_queues
```
**Symbols:**

```
ffffffff814eeeb0-ffffffff814eefac: elevator_switch_mq (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
