# Function: <code>wbt_issue</code>

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
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void wbt_issue(struct rq_wb *rwb, struct blk_issue_stat *stat);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-wbt.c (ffffffff8144ac00)
Location: block/blk-wbt.c:626
Inline: False
Direct callers:
  - block/blk-mq.c:blk_mq_start_request
```
**Symbols:**

```
ffffffff8144ac00-ffffffff8144ac39: wbt_issue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void wbt_issue(struct rq_wb *rwb, struct blk_issue_stat *stat);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-wbt.c (ffffffff81458e80)
Location: block/blk-wbt.c:613
Inline: False
Direct callers:
  - block/blk-core.c:blk_start_request
  - block/blk-mq.c:blk_mq_start_request
```
**Symbols:**

```
ffffffff81458e80-ffffffff81458eb9: wbt_issue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void wbt_issue(struct rq_wb *rwb, struct blk_issue_stat *stat);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-wbt.c (ffffffff81484be0)
Location: block/blk-wbt.c:612
Inline: False
Direct callers:
  - block/blk-core.c:blk_start_request
  - block/blk-mq.c:blk_mq_start_request
```
**Symbols:**

```
ffffffff81484be0-ffffffff81484c19: wbt_issue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void wbt_issue(struct rq_wb *rwb, struct request *rq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-wbt.c (ffffffff814b9aa0)
Location: block/blk-wbt.c:646
Inline: False
Direct callers:
  - block/blk-core.c:blk_start_request
  - block/blk-mq.c:blk_mq_start_request
```
**Symbols:**

```
ffffffff814b9aa0-ffffffff814b9ad6: wbt_issue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void wbt_issue(struct rq_qos *rqos, struct request *rq);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-wbt.c (ffffffff814cd330)
Location: block/blk-wbt.c:600
Inline: True
```
**Symbols:**

```
ffffffff814cd330-ffffffff814cd367: wbt_issue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void wbt_issue(struct rq_qos *rqos, struct request *rq);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-wbt.c (ffffffff814fbbc0)
Location: block/blk-wbt.c:601
Inline: True
```
**Symbols:**

```
ffffffff814fbbc0-ffffffff814fbbf7: wbt_issue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void wbt_issue(struct rq_qos *rqos, struct request *rq);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-wbt.c (ffffffff81519ae0)
Location: block/blk-wbt.c:603
Inline: True
```
**Symbols:**

```
ffffffff81519ae0-ffffffff81519b17: wbt_issue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void wbt_issue(struct rq_qos *rqos, struct request *rq);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-wbt.c (ffffffff81579df0)
Location: block/blk-wbt.c:595
Inline: True
```
**Symbols:**

```
ffffffff81579df0-ffffffff81579e27: wbt_issue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void wbt_issue(struct rq_qos *rqos, struct request *rq);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-wbt.c (ffffffff81596d00)
Location: block/blk-wbt.c:595
Inline: True
```
**Symbols:**

```
ffffffff81596d00-ffffffff81596d37: wbt_issue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void wbt_issue(struct rq_qos *rqos, struct request *rq);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-wbt.c (ffffffff8159dcd0)
Location: block/blk-wbt.c:596
Inline: True
```
**Symbols:**

```
ffffffff8159dcd0-ffffffff8159dd0e: wbt_issue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void wbt_issue(struct rq_qos *rqos, struct request *rq);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-wbt.c (ffffffff816063b0)
Location: block/blk-wbt.c:598
Inline: True
```
**Symbols:**

```
ffffffff816063b0-ffffffff816063ee: wbt_issue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void wbt_issue(struct rq_qos *rqos, struct request *rq);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-wbt.c (ffffffff816ba0b0)
Location: block/blk-wbt.c:598
Inline: True
```
**Symbols:**

```
ffffffff816ba0b0-ffffffff816ba0f2: wbt_issue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void wbt_issue(struct rq_qos *rqos, struct request *rq);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-wbt.c (ffffffff8177a5f0)
Location: block/blk-wbt.c:612
Inline: True
```
**Symbols:**

```
ffffffff8177a5f0-ffffffff8177a632: wbt_issue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void wbt_issue(struct rq_qos *rqos, struct request *rq);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-wbt.c (ffffffff817ba3d0)
Location: block/blk-wbt.c:671
Inline: True
```
**Symbols:**

```
ffffffff817ba3d0-ffffffff817ba41d: wbt_issue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void wbt_issue(struct rq_qos *rqos, struct request *rq);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-wbt.c (ffffffff817feb40)
Location: block/blk-wbt.c:670
Inline: True
```
**Symbols:**

```
ffffffff817feb40-ffffffff817feb8d: wbt_issue (STB_LOCAL)
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
void wbt_issue(struct rq_qos *rqos, struct request *rq);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-wbt.c (ffff800010620f90)
Location: block/blk-wbt.c:603
Inline: True
```
**Symbols:**

```
ffff800010620f90-ffff800010620fe4: wbt_issue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void wbt_issue(struct rq_qos *rqos, struct request *rq);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-wbt.c (c07c906c)
Location: block/blk-wbt.c:603
Inline: True
```
**Symbols:**

```
c07c906c-c07c90b8: wbt_issue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void wbt_issue(struct rq_qos *rqos, struct request *rq);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-wbt.c (c0000000007c1650)
Location: block/blk-wbt.c:603
Inline: True
```
**Symbols:**

```
c0000000007c1650-c0000000007c1694: wbt_issue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void wbt_issue(struct rq_qos *rqos, struct request *rq);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-wbt.c (ffffffe000453a8a)
Location: block/blk-wbt.c:603
Inline: True
```
**Symbols:**

```
ffffffe000453a8a-ffffffe000453ad6: wbt_issue (STB_LOCAL)
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
void wbt_issue(struct rq_qos *rqos, struct request *rq);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-wbt.c (ffffffff815120c0)
Location: block/blk-wbt.c:603
Inline: True
```
**Symbols:**

```
ffffffff815120c0-ffffffff815120f7: wbt_issue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void wbt_issue(struct rq_qos *rqos, struct request *rq);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-wbt.c (ffffffff815023e0)
Location: block/blk-wbt.c:603
Inline: True
```
**Symbols:**

```
ffffffff815023e0-ffffffff81502417: wbt_issue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void wbt_issue(struct rq_qos *rqos, struct request *rq);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-wbt.c (ffffffff8150e150)
Location: block/blk-wbt.c:603
Inline: True
```
**Symbols:**

```
ffffffff8150e150-ffffffff8150e187: wbt_issue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void wbt_issue(struct rq_qos *rqos, struct request *rq);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-wbt.c (ffffffff81527770)
Location: block/blk-wbt.c:603
Inline: True
```
**Symbols:**

```
ffffffff81527770-ffffffff815277a7: wbt_issue (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>4.15</code> and <code>4.18</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct request *rq</code>
</li>
<li>
<b>Param removed. </b>
<code>struct blk_issue_stat *stat</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>4.18</code> and <code>5.0</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct rq_qos *rqos</code>
</li>
<li>
<b>Param removed. </b>
<code>struct rq_wb *rwb</code>
</li>
</ul>
</details>
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
