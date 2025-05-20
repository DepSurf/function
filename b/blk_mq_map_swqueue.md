# Function: <code>blk_mq_map_swqueue</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void blk_mq_map_swqueue(struct request_queue *q, const struct cpumask *online_mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff813c4220)
Location: block/blk-mq.c:1797
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_init_allocated_queue
```
**Symbols:**

```
ffffffff813c4220-ffffffff813c44c7: blk_mq_map_swqueue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void blk_mq_map_swqueue(struct request_queue *q, const struct cpumask *online_mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff81408340)
Location: block/blk-mq.c:1826
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_queue_reinit
  - block/blk-mq.c:blk_mq_init_allocated_queue
```
**Symbols:**

```
ffffffff81408340-ffffffff814085de: blk_mq_map_swqueue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void blk_mq_map_swqueue(struct request_queue *q, const struct cpumask *online_mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff81422dd0)
Location: block/blk-mq.c:1860
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_queue_reinit
  - block/blk-mq.c:blk_mq_init_allocated_queue
```
**Symbols:**

```
ffffffff81422dd0-ffffffff81423071: blk_mq_map_swqueue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void blk_mq_map_swqueue(struct request_queue *q);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff814329b0)
Location: block/blk-mq.c:2046
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_update_nr_hw_queues
  - block/blk-mq.c:blk_mq_init_allocated_queue
```
**Symbols:**

```
ffffffff814329b0-ffffffff81432be3: blk_mq_map_swqueue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void blk_mq_map_swqueue(struct request_queue *q);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff8145e580)
Location: block/blk-mq.c:2184
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_update_nr_hw_queues
  - block/blk-mq.c:blk_mq_init_allocated_queue
```
**Symbols:**

```
ffffffff8145e580-ffffffff8145e7a4: blk_mq_map_swqueue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void blk_mq_map_swqueue(struct request_queue *q);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff81491eb0)
Location: block/blk-mq.c:2246
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_update_nr_hw_queues
  - block/blk-mq.c:blk_mq_init_allocated_queue
```
**Symbols:**

```
ffffffff81491eb0-ffffffff814920f5: blk_mq_map_swqueue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void blk_mq_map_swqueue(struct request_queue *q);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff814ab920)
Location: block/blk-mq.c:2412
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_update_nr_hw_queues
  - block/blk-mq.c:blk_mq_init_allocated_queue
```
**Symbols:**

```
ffffffff814ab920-ffffffff814abba7: blk_mq_map_swqueue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void blk_mq_map_swqueue(struct request_queue *q);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/blk-mq.c (0)
Location: block/blk-mq.c:2449
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_update_nr_hw_queues
  - block/blk-mq.c:blk_mq_init_allocated_queue
```
**Symbols:**

```
ffffffff814d9b10-ffffffff814d9df6: blk_mq_map_swqueue (STB_LOCAL)
ffffffff814dacd4-ffffffff814dacf0: blk_mq_map_swqueue.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void blk_mq_map_swqueue(struct request_queue *q);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff814f2ed0)
Location: block/blk-mq.c:2475
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_update_nr_hw_queues
  - block/blk-mq.c:blk_mq_init_allocated_queue
```
**Symbols:**

```
ffffffff814f2ed0-ffffffff814f3191: blk_mq_map_swqueue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void blk_mq_map_swqueue(struct request_queue *q);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff815534e0)
Location: block/blk-mq.c:2667
Inline: False
Direct callers:
  - block/blk-mq.c:__blk_mq_update_nr_hw_queues
  - block/blk-mq.c:blk_mq_init_allocated_queue
```
**Symbols:**

```
ffffffff815534e0-ffffffff815537e9: blk_mq_map_swqueue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void blk_mq_map_swqueue(struct request_queue *q);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff8156fb90)
Location: block/blk-mq.c:2772
Inline: False
Direct callers:
  - block/blk-mq.c:__blk_mq_update_nr_hw_queues
  - block/blk-mq.c:blk_mq_init_allocated_queue
```
**Symbols:**

```
ffffffff8156fb90-ffffffff8156fea6: blk_mq_map_swqueue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void blk_mq_map_swqueue(struct request_queue *q);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff81577a50)
Location: block/blk-mq.c:2832
Inline: False
Direct callers:
  - block/blk-mq.c:__blk_mq_update_nr_hw_queues
  - block/blk-mq.c:blk_mq_init_allocated_queue
```
**Symbols:**

```
ffffffff81577a50-ffffffff81577d44: blk_mq_map_swqueue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void blk_mq_map_swqueue(struct request_queue *q);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff815dc770)
Location: block/blk-mq.c:2888
Inline: False
Direct callers:
  - block/blk-mq.c:__blk_mq_update_nr_hw_queues
  - block/blk-mq.c:blk_mq_init_allocated_queue
```
**Symbols:**

```
ffffffff815dc770-ffffffff815dcc92: blk_mq_map_swqueue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void blk_mq_map_swqueue(struct request_queue *q);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff8168a320)
Location: block/blk-mq.c:3657
Inline: False
Direct callers:
  - block/blk-mq.c:__blk_mq_update_nr_hw_queues
  - block/blk-mq.c:blk_mq_init_allocated_queue
```
**Symbols:**

```
ffffffff8168a320-ffffffff8168a85b: blk_mq_map_swqueue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void blk_mq_map_swqueue(struct request_queue *q);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff81748920)
Location: block/blk-mq.c:3821
Inline: False
Direct callers:
  - block/blk-mq.c:__blk_mq_update_nr_hw_queues
  - block/blk-mq.c:blk_mq_init_allocated_queue
```
**Symbols:**

```
ffffffff81748920-ffffffff81748e5d: blk_mq_map_swqueue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void blk_mq_map_swqueue(struct request_queue *q);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff81785030)
Location: block/blk-mq.c:3833
Inline: False
Direct callers:
  - block/blk-mq.c:__blk_mq_update_nr_hw_queues
  - block/blk-mq.c:blk_mq_init_allocated_queue
```
**Symbols:**

```
ffffffff81785030-ffffffff81785572: blk_mq_map_swqueue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void blk_mq_map_swqueue(struct request_queue *q);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff817c75c0)
Location: block/blk-mq.c:3849
Inline: False
Direct callers:
  - block/blk-mq.c:__blk_mq_update_nr_hw_queues
  - block/blk-mq.c:blk_mq_init_allocated_queue
```
**Symbols:**

```
ffffffff817c75c0-ffffffff817c7ab8: blk_mq_map_swqueue (STB_LOCAL)
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
void blk_mq_map_swqueue(struct request_queue *q);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffff8000105f2728)
Location: block/blk-mq.c:2475
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_update_nr_hw_queues
  - block/blk-mq.c:blk_mq_init_allocated_queue
```
**Symbols:**

```
ffff8000105f2728-ffff8000105f2a28: blk_mq_map_swqueue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void blk_mq_map_swqueue(struct request_queue *q);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (c079e7f0)
Location: block/blk-mq.c:2475
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_update_nr_hw_queues
  - block/blk-mq.c:blk_mq_init_allocated_queue
```
**Symbols:**

```
c079e7f0-c079eb34: blk_mq_map_swqueue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void blk_mq_map_swqueue(struct request_queue *q);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (c000000000789ab0)
Location: block/blk-mq.c:2475
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_update_nr_hw_queues
  - block/blk-mq.c:blk_mq_init_allocated_queue
```
**Symbols:**

```
c000000000789ab0-c000000000789ec0: blk_mq_map_swqueue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void blk_mq_map_swqueue(struct request_queue *q);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffe000430f94)
Location: block/blk-mq.c:2475
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_update_nr_hw_queues
  - block/blk-mq.c:blk_mq_init_allocated_queue
```
**Symbols:**

```
ffffffe000430f94-ffffffe000431268: blk_mq_map_swqueue (STB_LOCAL)
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
void blk_mq_map_swqueue(struct request_queue *q);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff814eb4b0)
Location: block/blk-mq.c:2475
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_update_nr_hw_queues
  - block/blk-mq.c:blk_mq_init_allocated_queue
```
**Symbols:**

```
ffffffff814eb4b0-ffffffff814eb771: blk_mq_map_swqueue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void blk_mq_map_swqueue(struct request_queue *q);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff814dba00)
Location: block/blk-mq.c:2475
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_update_nr_hw_queues
  - block/blk-mq.c:blk_mq_init_allocated_queue
```
**Symbols:**

```
ffffffff814dba00-ffffffff814dbcc1: blk_mq_map_swqueue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void blk_mq_map_swqueue(struct request_queue *q);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff814e7540)
Location: block/blk-mq.c:2475
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_update_nr_hw_queues
  - block/blk-mq.c:blk_mq_init_allocated_queue
```
**Symbols:**

```
ffffffff814e7540-ffffffff814e7801: blk_mq_map_swqueue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void blk_mq_map_swqueue(struct request_queue *q);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff815004e0)
Location: block/blk-mq.c:2475
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_update_nr_hw_queues
  - block/blk-mq.c:blk_mq_init_allocated_queue
```
**Symbols:**

```
ffffffff815004e0-ffffffff815007a1: blk_mq_map_swqueue (STB_LOCAL)
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
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>4.10</code> and <code>4.13</code> ⚠️</summary>
<ul>
<li>
<b>Param removed. </b>
<code>const struct cpumask *online_mask</code>
</li>
</ul>
</details>
</li>
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
