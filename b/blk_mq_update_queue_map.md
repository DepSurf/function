# Function: <code>blk_mq_update_queue_map</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int blk_mq_update_queue_map(unsigned int *map, unsigned int nr_queues, const struct cpumask *online_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-cpumap.c (ffffffff813c85c0)
Location: block/blk-mq-cpumap.c:34
Inline: False
Direct callers:
  - block/blk-mq-cpumap.c:blk_mq_make_queue_map
```
**Symbols:**

```
ffffffff813c85c0-ffffffff813c8790: blk_mq_update_queue_map (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int blk_mq_update_queue_map(unsigned int *map, unsigned int nr_queues, const struct cpumask *online_mask);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq-cpumap.c (ffffffff8140c820)
Location: block/blk-mq-cpumap.c:34
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_queue_reinit
  - block/blk-mq-cpumap.c:blk_mq_make_queue_map
```
**Symbols:**

```
ffffffff8140c820-ffffffff8140c9eb: blk_mq_update_queue_map (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>4.10</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int blk_mq_update_queue_map(struct blk_mq_tag_set *set);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff8142fed0)
Location: block/blk-mq.c:2481
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_update_nr_hw_queues
  - block/blk-mq.c:blk_mq_alloc_tag_set
```
**Symbols:**

```
ffffffff8142fed0-ffffffff8142fef1: blk_mq_update_queue_map (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int blk_mq_update_queue_map(struct blk_mq_tag_set *set);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff8145be60)
Location: block/blk-mq.c:2627
Inline: True
Direct callers:
  - block/blk-mq.c:blk_mq_update_nr_hw_queues
  - block/blk-mq.c:blk_mq_alloc_tag_set
```
**Symbols:**

```
ffffffff8145be60-ffffffff8145bec8: blk_mq_update_queue_map (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
int blk_mq_update_queue_map(struct blk_mq_tag_set *set);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff8148ea30)
Location: block/blk-mq.c:2689
Inline: True
Direct callers:
  - block/blk-mq.c:blk_mq_update_nr_hw_queues
  - block/blk-mq.c:blk_mq_alloc_tag_set
```
**Symbols:**

```
ffffffff8148ea30-ffffffff8148ea98: blk_mq_update_queue_map (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int blk_mq_update_queue_map(struct blk_mq_tag_set *set);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff814a84d0)
Location: block/blk-mq.c:2955
Inline: True
Direct callers:
  - block/blk-mq.c:blk_mq_update_nr_hw_queues
  - block/blk-mq.c:blk_mq_alloc_tag_set
```
**Symbols:**

```
ffffffff814a84d0-ffffffff814a8580: blk_mq_update_queue_map (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
int blk_mq_update_queue_map(struct blk_mq_tag_set *set);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff814d5f20)
Location: block/blk-mq.c:2988
Inline: True
Direct callers:
  - block/blk-mq.c:blk_mq_update_nr_hw_queues
  - block/blk-mq.c:blk_mq_alloc_tag_set
```
**Symbols:**

```
ffffffff814d5f20-ffffffff814d5fbf: blk_mq_update_queue_map (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int blk_mq_update_queue_map(struct blk_mq_tag_set *set);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff814ef250)
Location: block/blk-mq.c:3008
Inline: True
Direct callers:
  - block/blk-mq.c:blk_mq_update_nr_hw_queues
  - block/blk-mq.c:blk_mq_alloc_tag_set
```
**Symbols:**

```
ffffffff814ef250-ffffffff814ef2ef: blk_mq_update_queue_map (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int blk_mq_update_queue_map(struct blk_mq_tag_set *set);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff8154e810)
Location: block/blk-mq.c:3199
Inline: False
Direct callers:
  - block/blk-mq.c:__blk_mq_update_nr_hw_queues
  - block/blk-mq.c:blk_mq_alloc_tag_set
```
**Symbols:**

```
ffffffff8154e810-ffffffff8154e8cf: blk_mq_update_queue_map (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int blk_mq_update_queue_map(struct blk_mq_tag_set *set);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff8156acf0)
Location: block/blk-mq.c:3306
Inline: False
Direct callers:
  - block/blk-mq.c:__blk_mq_update_nr_hw_queues
  - block/blk-mq.c:blk_mq_alloc_tag_set
```
**Symbols:**

```
ffffffff8156acf0-ffffffff8156adaf: blk_mq_update_queue_map (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int blk_mq_update_queue_map(struct blk_mq_tag_set *set);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff81572b60)
Location: block/blk-mq.c:3368
Inline: False
Direct callers:
  - block/blk-mq.c:__blk_mq_update_nr_hw_queues
  - block/blk-mq.c:blk_mq_alloc_tag_set
```
**Symbols:**

```
ffffffff81572b60-ffffffff81572c35: blk_mq_update_queue_map (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int blk_mq_update_queue_map(struct blk_mq_tag_set *set);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff815d7320)
Location: block/blk-mq.c:3400
Inline: True
Direct callers:
  - block/blk-mq.c:__blk_mq_update_nr_hw_queues
  - block/blk-mq.c:blk_mq_alloc_tag_set
```
**Symbols:**

```
ffffffff815d7320-ffffffff815d740c: blk_mq_update_queue_map (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
int blk_mq_update_queue_map(struct blk_mq_tag_set *set);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff816834c0)
Location: block/blk-mq.c:4163
Inline: True
Direct callers:
  - block/blk-mq.c:__blk_mq_update_nr_hw_queues
  - block/blk-mq.c:blk_mq_alloc_tag_set
```
**Symbols:**

```
ffffffff816834c0-ffffffff816835c0: blk_mq_update_queue_map (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void blk_mq_update_queue_map(struct blk_mq_tag_set *set);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff81742130)
Location: block/blk-mq.c:4365
Inline: True
Direct callers:
  - block/blk-mq.c:__blk_mq_update_nr_hw_queues
  - block/blk-mq.c:blk_mq_alloc_tag_set
```
**Symbols:**

```
ffffffff81742130-ffffffff8174224e: blk_mq_update_queue_map (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void blk_mq_update_queue_map(struct blk_mq_tag_set *set);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff8177d820)
Location: block/blk-mq.c:4364
Inline: True
Direct callers:
  - block/blk-mq.c:__blk_mq_update_nr_hw_queues
  - block/blk-mq.c:blk_mq_alloc_tag_set
```
**Symbols:**

```
ffffffff8177d820-ffffffff8177d93e: blk_mq_update_queue_map (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void blk_mq_update_queue_map(struct blk_mq_tag_set *set);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff817bfbb0)
Location: block/blk-mq.c:4380
Inline: True
Direct callers:
  - block/blk-mq.c:__blk_mq_update_nr_hw_queues
  - block/blk-mq.c:blk_mq_alloc_tag_set
```
**Symbols:**

```
ffffffff817bfbb0-ffffffff817bfcce: blk_mq_update_queue_map (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
int blk_mq_update_queue_map(struct blk_mq_tag_set *set);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffff8000105ed720)
Location: block/blk-mq.c:3008
Inline: True
Direct callers:
  - block/blk-mq.c:blk_mq_update_nr_hw_queues
  - block/blk-mq.c:blk_mq_alloc_tag_set
```
**Symbols:**

```
ffff8000105ed720-ffff8000105ed800: blk_mq_update_queue_map (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int blk_mq_update_queue_map(struct blk_mq_tag_set *set);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (c079a788)
Location: block/blk-mq.c:3008
Inline: True
Direct callers:
  - block/blk-mq.c:blk_mq_update_nr_hw_queues
  - block/blk-mq.c:blk_mq_alloc_tag_set
```
**Symbols:**

```
c079a788-c079a85c: blk_mq_update_queue_map (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
int blk_mq_update_queue_map(struct blk_mq_tag_set *set);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (c000000000784440)
Location: block/blk-mq.c:3008
Inline: True
Direct callers:
  - block/blk-mq.c:blk_mq_update_nr_hw_queues
  - block/blk-mq.c:blk_mq_alloc_tag_set
```
**Symbols:**

```
c000000000784440-c00000000078458c: blk_mq_update_queue_map (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
int blk_mq_update_queue_map(struct blk_mq_tag_set *set);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffe00042d812)
Location: block/blk-mq.c:3008
Inline: True
Direct callers:
  - block/blk-mq.c:blk_mq_update_nr_hw_queues
  - block/blk-mq.c:blk_mq_alloc_tag_set
```
**Symbols:**

```
ffffffe00042d812-ffffffe00042d8b8: blk_mq_update_queue_map (STB_LOCAL)
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
int blk_mq_update_queue_map(struct blk_mq_tag_set *set);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff814e7830)
Location: block/blk-mq.c:3008
Inline: True
Direct callers:
  - block/blk-mq.c:blk_mq_update_nr_hw_queues
  - block/blk-mq.c:blk_mq_alloc_tag_set
```
**Symbols:**

```
ffffffff814e7830-ffffffff814e78cf: blk_mq_update_queue_map (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int blk_mq_update_queue_map(struct blk_mq_tag_set *set);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff814d7da0)
Location: block/blk-mq.c:3008
Inline: True
Direct callers:
  - block/blk-mq.c:blk_mq_update_nr_hw_queues
  - block/blk-mq.c:blk_mq_alloc_tag_set
```
**Symbols:**

```
ffffffff814d7da0-ffffffff814d7e3f: blk_mq_update_queue_map (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int blk_mq_update_queue_map(struct blk_mq_tag_set *set);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff814e38c0)
Location: block/blk-mq.c:3008
Inline: True
Direct callers:
  - block/blk-mq.c:blk_mq_update_nr_hw_queues
  - block/blk-mq.c:blk_mq_alloc_tag_set
```
**Symbols:**

```
ffffffff814e38c0-ffffffff814e395f: blk_mq_update_queue_map (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int blk_mq_update_queue_map(struct blk_mq_tag_set *set);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff814fce10)
Location: block/blk-mq.c:3008
Inline: True
Direct callers:
  - block/blk-mq.c:blk_mq_update_nr_hw_queues
  - block/blk-mq.c:blk_mq_alloc_tag_set
```
**Symbols:**

```
ffffffff814fce10-ffffffff814fceaf: blk_mq_update_queue_map (STB_LOCAL)
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
<details>
<summary>Changed between <code>5.19</code> and <code>6.2</code> ⚠️</summary>
<ul>
<li>
<b>Return type changed. </b>
<code>int</code> ➡️ <code>void</code>
</li>
</ul>
</details>
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
