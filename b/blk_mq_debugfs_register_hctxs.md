# Function: <code>blk_mq_debugfs_register_hctxs</code>

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
int blk_mq_debugfs_register_hctxs(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-debugfs.c (ffffffff8145a310)
Location: block/blk-mq-debugfs.c:901
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_update_nr_hw_queues
```
**Symbols:**

```
ffffffff8145a310-ffffffff8145a369: blk_mq_debugfs_register_hctxs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int blk_mq_debugfs_register_hctxs(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-debugfs.c (ffffffff81486090)
Location: block/blk-mq-debugfs.c:902
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_update_nr_hw_queues
```
**Symbols:**

```
ffffffff81486090-ffffffff814860e9: blk_mq_debugfs_register_hctxs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int blk_mq_debugfs_register_hctxs(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-debugfs.c (ffffffff814bafc0)
Location: block/blk-mq-debugfs.c:928
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_update_nr_hw_queues
```
**Symbols:**

```
ffffffff814bafc0-ffffffff814bb019: blk_mq_debugfs_register_hctxs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int blk_mq_debugfs_register_hctxs(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-debugfs.c (ffffffff814cf1a0)
Location: block/blk-mq-debugfs.c:967
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_update_nr_hw_queues
```
**Symbols:**

```
ffffffff814cf1a0-ffffffff814cf1f0: blk_mq_debugfs_register_hctxs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void blk_mq_debugfs_register_hctxs(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-debugfs.c (ffffffff814fd9c0)
Location: block/blk-mq-debugfs.c:899
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_update_nr_hw_queues
```
**Symbols:**

```
ffffffff814fd9c0-ffffffff814fd9fc: blk_mq_debugfs_register_hctxs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void blk_mq_debugfs_register_hctxs(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-debugfs.c (ffffffff8151b910)
Location: block/blk-mq-debugfs.c:899
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_update_nr_hw_queues
```
**Symbols:**

```
ffffffff8151b910-ffffffff8151b94c: blk_mq_debugfs_register_hctxs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void blk_mq_debugfs_register_hctxs(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-debugfs.c (ffffffff8157c0b0)
Location: block/blk-mq-debugfs.c:903
Inline: False
Direct callers:
  - block/blk-mq.c:__blk_mq_update_nr_hw_queues
```
**Symbols:**

```
ffffffff8157c0b0-ffffffff8157c0ec: blk_mq_debugfs_register_hctxs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void blk_mq_debugfs_register_hctxs(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-debugfs.c (ffffffff81599150)
Location: block/blk-mq-debugfs.c:899
Inline: False
Direct callers:
  - block/blk-mq.c:__blk_mq_update_nr_hw_queues
```
**Symbols:**

```
ffffffff81599150-ffffffff8159918c: blk_mq_debugfs_register_hctxs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void blk_mq_debugfs_register_hctxs(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-debugfs.c (ffffffff8159ff50)
Location: block/blk-mq-debugfs.c:897
Inline: False
Direct callers:
  - block/blk-mq.c:__blk_mq_update_nr_hw_queues
```
**Symbols:**

```
ffffffff8159ff50-ffffffff8159ff8c: blk_mq_debugfs_register_hctxs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void blk_mq_debugfs_register_hctxs(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-debugfs.c (ffffffff81608770)
Location: block/blk-mq-debugfs.c:898
Inline: False
Direct callers:
  - block/blk-mq.c:__blk_mq_update_nr_hw_queues
```
**Symbols:**

```
ffffffff81608770-ffffffff816087ac: blk_mq_debugfs_register_hctxs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void blk_mq_debugfs_register_hctxs(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-debugfs.c (ffffffff816bc230)
Location: block/blk-mq-debugfs.c:754
Inline: False
Direct callers:
  - block/blk-mq.c:__blk_mq_update_nr_hw_queues
```
**Symbols:**

```
ffffffff816bc230-ffffffff816bc2d1: blk_mq_debugfs_register_hctxs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void blk_mq_debugfs_register_hctxs(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-debugfs.c (ffffffff8177cbe0)
Location: block/blk-mq-debugfs.c:754
Inline: False
Direct callers:
  - block/blk-mq.c:__blk_mq_update_nr_hw_queues
```
**Symbols:**

```
ffffffff8177cbe0-ffffffff8177cc81: blk_mq_debugfs_register_hctxs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void blk_mq_debugfs_register_hctxs(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-debugfs.c (ffffffff817bc580)
Location: block/blk-mq-debugfs.c:728
Inline: False
Direct callers:
  - block/blk-mq.c:__blk_mq_update_nr_hw_queues
```
**Symbols:**

```
ffffffff817bc580-ffffffff817bc621: blk_mq_debugfs_register_hctxs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void blk_mq_debugfs_register_hctxs(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-debugfs.c (ffffffff81800c40)
Location: block/blk-mq-debugfs.c:709
Inline: False
Direct callers:
  - block/blk-mq.c:__blk_mq_update_nr_hw_queues
```
**Symbols:**

```
ffffffff81800c40-ffffffff81800ce1: blk_mq_debugfs_register_hctxs (STB_GLOBAL)
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
void blk_mq_debugfs_register_hctxs(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-debugfs.c (ffff800010623f50)
Location: block/blk-mq-debugfs.c:899
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_update_nr_hw_queues
```
**Symbols:**

```
ffff800010623f50-ffff800010623fa4: blk_mq_debugfs_register_hctxs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void blk_mq_debugfs_register_hctxs(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-debugfs.c (c07cb5a4)
Location: block/blk-mq-debugfs.c:899
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_update_nr_hw_queues
```
**Symbols:**

```
c07cb5a4-c07cb5f0: blk_mq_debugfs_register_hctxs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void blk_mq_debugfs_register_hctxs(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-debugfs.c (c0000000007c4980)
Location: block/blk-mq-debugfs.c:899
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_update_nr_hw_queues
```
**Symbols:**

```
c0000000007c4980-c0000000007c4a00: blk_mq_debugfs_register_hctxs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void blk_mq_debugfs_register_hctxs(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-debugfs.c (ffffffe000455b46)
Location: block/blk-mq-debugfs.c:899
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_update_nr_hw_queues
```
**Symbols:**

```
ffffffe000455b46-ffffffe000455b92: blk_mq_debugfs_register_hctxs (STB_GLOBAL)
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
void blk_mq_debugfs_register_hctxs(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-debugfs.c (ffffffff81513ef0)
Location: block/blk-mq-debugfs.c:899
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_update_nr_hw_queues
```
**Symbols:**

```
ffffffff81513ef0-ffffffff81513f2c: blk_mq_debugfs_register_hctxs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void blk_mq_debugfs_register_hctxs(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-debugfs.c (ffffffff81504200)
Location: block/blk-mq-debugfs.c:899
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_update_nr_hw_queues
```
**Symbols:**

```
ffffffff81504200-ffffffff8150423c: blk_mq_debugfs_register_hctxs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void blk_mq_debugfs_register_hctxs(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-debugfs.c (ffffffff8150ff80)
Location: block/blk-mq-debugfs.c:899
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_update_nr_hw_queues
```
**Symbols:**

```
ffffffff8150ff80-ffffffff8150ffbc: blk_mq_debugfs_register_hctxs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void blk_mq_debugfs_register_hctxs(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-debugfs.c (ffffffff81529740)
Location: block/blk-mq-debugfs.c:899
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_update_nr_hw_queues
```
**Symbols:**

```
ffffffff81529740-ffffffff8152977c: blk_mq_debugfs_register_hctxs (STB_GLOBAL)
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
<details>
<summary>Changed between <code>5.0</code> and <code>5.3</code> ⚠️</summary>
<ul>
<li>
<b>Return type changed. </b>
<code>int</code> ➡️ <code>void</code>
</li>
</ul>
</details>
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
