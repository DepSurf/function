# Function: <code>blk_rq_unprep_clone</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
void blk_rq_unprep_clone(struct request *rq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff813b5b10)
Location: block/blk-core.c:3037
Inline: True
Inline callers:
  - block/blk-core.c:blk_rq_prep_clone
Direct callers:
  - drivers/md/dm.c:free_rq_clone
```
**Symbols:**

```
ffffffff813b5b10-ffffffff813b5b3e: blk_rq_unprep_clone (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void blk_rq_unprep_clone(struct request *rq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff813faaee)
Location: block/blk-core.c:3008
Inline: True
Inline callers:
  - block/blk-core.c:blk_rq_prep_clone
Direct callers:
  - drivers/md/dm-rq.c:free_rq_clone
```
**Symbols:**

```
ffffffff813fa980-ffffffff813fa9ae: blk_rq_unprep_clone (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void blk_rq_unprep_clone(struct request *rq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff81414439)
Location: block/blk-core.c:3003
Inline: True
Inline callers:
  - block/blk-core.c:blk_rq_prep_clone
Direct callers:
  - drivers/md/dm-rq.c:free_rq_clone
```
**Symbols:**

```
ffffffff81414300-ffffffff8141432e: blk_rq_unprep_clone (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void blk_rq_unprep_clone(struct request *rq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff81421fba)
Location: block/blk-core.c:3101
Inline: True
Inline callers:
  - block/blk-core.c:blk_rq_prep_clone
Direct callers:
  - drivers/md/dm-rq.c:dm_requeue_original_request
```
**Symbols:**

```
ffffffff81421e90-ffffffff81421ebe: blk_rq_unprep_clone (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void blk_rq_unprep_clone(struct request *rq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff8144ce2d)
Location: block/blk-core.c:3325
Inline: True
Inline callers:
  - block/blk-core.c:blk_rq_prep_clone
Direct callers:
  - drivers/md/dm-rq.c:dm_requeue_original_request
```
**Symbols:**

```
ffffffff8144cd00-ffffffff8144cd2e: blk_rq_unprep_clone (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void blk_rq_unprep_clone(struct request *rq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff81480078)
Location: block/blk-core.c:3472
Inline: True
Inline callers:
  - block/blk-core.c:blk_rq_prep_clone
Direct callers:
  - drivers/md/dm-rq.c:map_request
  - drivers/md/dm-rq.c:dm_requeue_original_request
```
**Symbols:**

```
ffffffff8147ff40-ffffffff8147ff6e: blk_rq_unprep_clone (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void blk_rq_unprep_clone(struct request *rq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff8149d100)
Location: block/blk-core.c:1579
Inline: True
Inline callers:
  - block/blk-core.c:blk_rq_prep_clone
Direct callers:
  - drivers/md/dm-rq.c:dm_mq_queue_rq
  - drivers/md/dm-rq.c:dm_requeue_original_request
```
**Symbols:**

```
ffffffff8149cfd0-ffffffff8149cffe: blk_rq_unprep_clone (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void blk_rq_unprep_clone(struct request *rq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff814cb160)
Location: block/blk-core.c:1530
Inline: True
Inline callers:
  - block/blk-core.c:blk_rq_prep_clone
Direct callers:
  - drivers/md/dm-rq.c:dm_mq_queue_rq
  - drivers/md/dm-rq.c:dm_requeue_original_request
```
**Symbols:**

```
ffffffff814cb160-ffffffff814cb18e: blk_rq_unprep_clone (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void blk_rq_unprep_clone(struct request *rq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff814e4350)
Location: block/blk-core.c:1571
Inline: True
Inline callers:
  - block/blk-core.c:blk_rq_prep_clone
Direct callers:
  - drivers/md/dm-rq.c:map_request
  - drivers/md/dm-rq.c:dm_requeue_original_request
```
**Symbols:**

```
ffffffff814e4350-ffffffff814e437e: blk_rq_unprep_clone (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void blk_rq_unprep_clone(struct request *rq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff81542d20)
Location: block/blk-core.c:1676
Inline: True
Inline callers:
  - block/blk-core.c:blk_rq_prep_clone
Direct callers:
  - drivers/md/dm-rq.c:map_request
  - drivers/md/dm-rq.c:dm_done
  - drivers/md/dm-rq.c:dm_requeue_original_request
```
**Symbols:**

```
ffffffff81542d20-ffffffff81542d51: blk_rq_unprep_clone (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void blk_rq_unprep_clone(struct request *rq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff8155f630)
Location: block/blk-core.c:1568
Inline: True
Inline callers:
  - block/blk-core.c:blk_rq_prep_clone
Direct callers:
  - drivers/md/dm-rq.c:map_request
  - drivers/md/dm-rq.c:dm_done
  - drivers/md/dm-rq.c:dm_requeue_original_request
```
**Symbols:**

```
ffffffff8155f630-ffffffff8155f661: blk_rq_unprep_clone (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void blk_rq_unprep_clone(struct request *rq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff81567dd0)
Location: block/blk-core.c:1560
Inline: True
Inline callers:
  - block/blk-core.c:blk_rq_prep_clone
Direct callers:
  - drivers/md/dm-rq.c:map_request
  - drivers/md/dm-rq.c:dm_done
  - drivers/md/dm-rq.c:dm_requeue_original_request
```
**Symbols:**

```
ffffffff81567dd0-ffffffff81567e01: blk_rq_unprep_clone (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void blk_rq_unprep_clone(struct request *rq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff815cc420)
Location: block/blk-core.c:1546
Inline: True
Inline callers:
  - block/blk-core.c:blk_rq_prep_clone
Direct callers:
  - drivers/md/dm-rq.c:map_request
  - drivers/md/dm-rq.c:dm_requeue_original_request
```
**Symbols:**

```
ffffffff815cc420-ffffffff815cc451: blk_rq_unprep_clone (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void blk_rq_unprep_clone(struct request *rq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff81684713)
Location: block/blk-mq.c:2924
Inline: True
Inline callers:
  - block/blk-mq.c:blk_rq_prep_clone
Direct callers:
  - drivers/md/dm-rq.c:map_request
  - drivers/md/dm-rq.c:dm_requeue_original_request
```
**Symbols:**

```
ffffffff81682fe0-ffffffff81683019: blk_rq_unprep_clone (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void blk_rq_unprep_clone(struct request *rq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff817420c3)
Location: block/blk-mq.c:3084
Inline: True
Inline callers:
  - block/blk-mq.c:blk_rq_prep_clone
Direct callers:
  - drivers/md/dm-rq.c:map_request
  - drivers/md/dm-rq.c:dm_requeue_original_request
```
**Symbols:**

```
ffffffff81740800-ffffffff81740839: blk_rq_unprep_clone (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void blk_rq_unprep_clone(struct request *rq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff8177da9f)
Location: block/blk-mq.c:3096
Inline: True
Inline callers:
  - block/blk-mq.c:blk_rq_prep_clone
Direct callers:
  - drivers/md/dm-rq.c:map_request
  - drivers/md/dm-rq.c:dm_requeue_original_request
```
**Symbols:**

```
ffffffff8177ca80-ffffffff8177cab9: blk_rq_unprep_clone (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void blk_rq_unprep_clone(struct request *rq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-mq.c (ffffffff817bfe2c)
Location: block/blk-mq.c:3112
Inline: True
Inline callers:
  - block/blk-mq.c:blk_rq_prep_clone
Direct callers:
  - drivers/md/dm-rq.c:map_request
  - drivers/md/dm-rq.c:dm_requeue_original_request
```
**Symbols:**

```
ffffffff817bee80-ffffffff817beeb9: blk_rq_unprep_clone (STB_GLOBAL)
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
void blk_rq_unprep_clone(struct request *rq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffff8000105e084c)
Location: block/blk-core.c:1571
Inline: True
Inline callers:
  - block/blk-core.c:blk_rq_prep_clone
Direct callers:
  - drivers/md/dm-rq.c:map_request
  - drivers/md/dm-rq.c:dm_requeue_original_request
```
**Symbols:**

```
ffff8000105e0718-ffff8000105e0758: blk_rq_unprep_clone (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void blk_rq_unprep_clone(struct request *rq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-core.c (c078e9bc)
Location: block/blk-core.c:1571
Inline: True
Inline callers:
  - block/blk-core.c:blk_rq_prep_clone
Direct callers:
  - drivers/md/dm-rq.c:map_request
  - drivers/md/dm-rq.c:dm_requeue_original_request
```
**Symbols:**

```
c078e9bc-c078e9fc: blk_rq_unprep_clone (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void blk_rq_unprep_clone(struct request *rq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-core.c (c000000000774ab0)
Location: block/blk-core.c:1571
Inline: True
Inline callers:
  - block/blk-core.c:blk_rq_prep_clone
Direct callers:
  - drivers/md/dm-rq.c:map_request
  - drivers/md/dm-rq.c:dm_requeue_original_request
```
**Symbols:**

```
c000000000774ab0-c000000000774b10: blk_rq_unprep_clone (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void blk_rq_unprep_clone(struct request *rq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffe000423b94)
Location: block/blk-core.c:1571
Inline: True
Inline callers:
  - block/blk-core.c:blk_rq_prep_clone
Direct callers:
  - drivers/md/dm-rq.c:map_request
  - drivers/md/dm-rq.c:dm_requeue_original_request
```
**Symbols:**

```
ffffffe000423a90-ffffffe000423ac4: blk_rq_unprep_clone (STB_GLOBAL)
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
void blk_rq_unprep_clone(struct request *rq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff814dc930)
Location: block/blk-core.c:1571
Inline: True
Inline callers:
  - block/blk-core.c:blk_rq_prep_clone
Direct callers:
  - drivers/md/dm-rq.c:map_request
  - drivers/md/dm-rq.c:dm_requeue_original_request
```
**Symbols:**

```
ffffffff814dc930-ffffffff814dc95e: blk_rq_unprep_clone (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void blk_rq_unprep_clone(struct request *rq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff814cd2e0)
Location: block/blk-core.c:1571
Inline: True
Inline callers:
  - block/blk-core.c:blk_rq_prep_clone
Direct callers:
  - drivers/md/dm-rq.c:map_request
  - drivers/md/dm-rq.c:dm_requeue_original_request
```
**Symbols:**

```
ffffffff814cd2e0-ffffffff814cd30e: blk_rq_unprep_clone (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void blk_rq_unprep_clone(struct request *rq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff814d89c0)
Location: block/blk-core.c:1571
Inline: True
Inline callers:
  - block/blk-core.c:blk_rq_prep_clone
Direct callers:
  - drivers/md/dm-rq.c:map_request
  - drivers/md/dm-rq.c:dm_requeue_original_request
```
**Symbols:**

```
ffffffff814d89c0-ffffffff814d89ee: blk_rq_unprep_clone (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void blk_rq_unprep_clone(struct request *rq);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-core.c (ffffffff814f15d0)
Location: block/blk-core.c:1571
Inline: True
Inline callers:
  - block/blk-core.c:blk_rq_prep_clone
Direct callers:
  - drivers/md/dm-rq.c:map_request
  - drivers/md/dm-rq.c:dm_requeue_original_request
```
**Symbols:**

```
ffffffff814f15d0-ffffffff814f15fe: blk_rq_unprep_clone (STB_GLOBAL)
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
No changes between <code>4.10</code> and <code>4.13</code> ✅
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
