# Function: <code>__blk_mq_update_nr_hw_queues</code>

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
In block/blk-mq.c (ffffffff81433023)
Location: block/blk-mq.c:2620
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_update_nr_hw_queues
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
In block/blk-mq.c (ffffffff8145ebd4)
Location: block/blk-mq.c:2786
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_update_nr_hw_queues
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
In block/blk-mq.c (ffffffff81492523)
Location: block/blk-mq.c:2850
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_update_nr_hw_queues
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff814ac0bf)
Location: block/blk-mq.c:3206
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_update_nr_hw_queues
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff814da2fb)
Location: block/blk-mq.c:3241
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_update_nr_hw_queues
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff814f36bb)
Location: block/blk-mq.c:3261
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_update_nr_hw_queues
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
void __blk_mq_update_nr_hw_queues(struct blk_mq_tag_set *set, int nr_hw_queues);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/blk-mq.c (0)
Location: block/blk-mq.c:3481
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_update_nr_hw_queues
```
**Symbols:**

```
ffffffff81553c20-ffffffff81553f6a: __blk_mq_update_nr_hw_queues (STB_LOCAL)
ffffffff815546e9-ffffffff8155470c: __blk_mq_update_nr_hw_queues.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
void __blk_mq_update_nr_hw_queues(struct blk_mq_tag_set *set, int nr_hw_queues);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/blk-mq.c (0)
Location: block/blk-mq.c:3611
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_update_nr_hw_queues
```
**Symbols:**

```
ffffffff815702e0-ffffffff8157062a: __blk_mq_update_nr_hw_queues (STB_LOCAL)
ffffffff81bf27b7-ffffffff81bf27da: __blk_mq_update_nr_hw_queues.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
void __blk_mq_update_nr_hw_queues(struct blk_mq_tag_set *set, int nr_hw_queues);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/blk-mq.c (0)
Location: block/blk-mq.c:3673
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_update_nr_hw_queues
```
**Symbols:**

```
ffffffff81578240-ffffffff81578587: __blk_mq_update_nr_hw_queues (STB_LOCAL)
ffffffff81be477d-ffffffff81be47a0: __blk_mq_update_nr_hw_queues.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void __blk_mq_update_nr_hw_queues(struct blk_mq_tag_set *set, int nr_hw_queues);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/blk-mq.c (0)
Location: block/blk-mq.c:3730
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_update_nr_hw_queues
```
**Symbols:**

```
ffffffff815dd320-ffffffff815dd669: __blk_mq_update_nr_hw_queues (STB_LOCAL)
ffffffff81cd8595-ffffffff81cd85b8: __blk_mq_update_nr_hw_queues.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void __blk_mq_update_nr_hw_queues(struct blk_mq_tag_set *set, int nr_hw_queues);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/blk-mq.c (0)
Location: block/blk-mq.c:4488
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_update_nr_hw_queues
```
**Symbols:**

```
ffffffff8168aed0-ffffffff8168b249: __blk_mq_update_nr_hw_queues (STB_LOCAL)
ffffffff81e8bce9-ffffffff81e8bd26: __blk_mq_update_nr_hw_queues.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void __blk_mq_update_nr_hw_queues(struct blk_mq_tag_set *set, int nr_hw_queues);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff81748e70)
Location: block/blk-mq.c:4699
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_update_nr_hw_queues
```
**Symbols:**

```
ffffffff81748e70-ffffffff81749226: __blk_mq_update_nr_hw_queues (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void __blk_mq_update_nr_hw_queues(struct blk_mq_tag_set *set, int nr_hw_queues);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff81785590)
Location: block/blk-mq.c:4702
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_update_nr_hw_queues
```
**Symbols:**

```
ffffffff81785590-ffffffff81785962: __blk_mq_update_nr_hw_queues (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void __blk_mq_update_nr_hw_queues(struct blk_mq_tag_set *set, int nr_hw_queues);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff817c7bd0)
Location: block/blk-mq.c:4729
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_update_nr_hw_queues
```
**Symbols:**

```
ffffffff817c7bd0-ffffffff817c7fee: __blk_mq_update_nr_hw_queues (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffff8000105f2f0c)
Location: block/blk-mq.c:3261
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_update_nr_hw_queues
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (c079effc)
Location: block/blk-mq.c:3261
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_update_nr_hw_queues
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (c00000000078a5a4)
Location: block/blk-mq.c:3261
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_update_nr_hw_queues
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffe0004316ee)
Location: block/blk-mq.c:3261
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_update_nr_hw_queues
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff814ebc9b)
Location: block/blk-mq.c:3261
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_update_nr_hw_queues
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff814dc1eb)
Location: block/blk-mq.c:3261
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_update_nr_hw_queues
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff814e7d2b)
Location: block/blk-mq.c:3261
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_update_nr_hw_queues
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff81500ccb)
Location: block/blk-mq.c:3261
Inline: True
Inline callers:
  - block/blk-mq.c:blk_mq_update_nr_hw_queues
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
