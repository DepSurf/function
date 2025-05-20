# Function: <code>wbt_requeue</code>

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
void wbt_requeue(struct rq_wb *rwb, struct blk_issue_stat *stat);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-wbt.c (ffffffff8144ac40)
Location: block/blk-wbt.c:645
Inline: False
```
**Symbols:**

```
ffffffff8144ac40-ffffffff8144ac6f: wbt_requeue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void wbt_requeue(struct rq_wb *rwb, struct blk_issue_stat *stat);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-wbt.c (ffffffff81458ec0)
Location: block/blk-wbt.c:632
Inline: False
Direct callers:
  - block/blk-core.c:blk_requeue_request
```
**Symbols:**

```
ffffffff81458ec0-ffffffff81458eef: wbt_requeue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void wbt_requeue(struct rq_wb *rwb, struct blk_issue_stat *stat);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-wbt.c (ffffffff81484c20)
Location: block/blk-wbt.c:631
Inline: False
Direct callers:
  - block/blk-core.c:blk_requeue_request
```
**Symbols:**

```
ffffffff81484c20-ffffffff81484c4f: wbt_requeue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void wbt_requeue(struct rq_wb *rwb, struct request *rq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-wbt.c (ffffffff814b9ae0)
Location: block/blk-wbt.c:664
Inline: False
Direct callers:
  - block/blk-core.c:blk_requeue_request
```
**Symbols:**

```
ffffffff814b9ae0-ffffffff814b9b0f: wbt_requeue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void wbt_requeue(struct rq_qos *rqos, struct request *rq);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-wbt.c (ffffffff814cd370)
Location: block/blk-wbt.c:620
Inline: True
```
**Symbols:**

```
ffffffff814cd370-ffffffff814cd3a0: wbt_requeue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void wbt_requeue(struct rq_qos *rqos, struct request *rq);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-wbt.c (ffffffff814fbc00)
Location: block/blk-wbt.c:621
Inline: True
```
**Symbols:**

```
ffffffff814fbc00-ffffffff814fbc30: wbt_requeue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void wbt_requeue(struct rq_qos *rqos, struct request *rq);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-wbt.c (ffffffff81519b20)
Location: block/blk-wbt.c:623
Inline: True
```
**Symbols:**

```
ffffffff81519b20-ffffffff81519b50: wbt_requeue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void wbt_requeue(struct rq_qos *rqos, struct request *rq);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-wbt.c (ffffffff81579e30)
Location: block/blk-wbt.c:615
Inline: True
```
**Symbols:**

```
ffffffff81579e30-ffffffff81579e60: wbt_requeue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void wbt_requeue(struct rq_qos *rqos, struct request *rq);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-wbt.c (ffffffff81596d40)
Location: block/blk-wbt.c:615
Inline: True
```
**Symbols:**

```
ffffffff81596d40-ffffffff81596d70: wbt_requeue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void wbt_requeue(struct rq_qos *rqos, struct request *rq);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-wbt.c (ffffffff8159dd10)
Location: block/blk-wbt.c:616
Inline: True
```
**Symbols:**

```
ffffffff8159dd10-ffffffff8159dd47: wbt_requeue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void wbt_requeue(struct rq_qos *rqos, struct request *rq);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-wbt.c (ffffffff816063f0)
Location: block/blk-wbt.c:618
Inline: True
```
**Symbols:**

```
ffffffff816063f0-ffffffff81606427: wbt_requeue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void wbt_requeue(struct rq_qos *rqos, struct request *rq);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-wbt.c (ffffffff816ba100)
Location: block/blk-wbt.c:618
Inline: True
```
**Symbols:**

```
ffffffff816ba100-ffffffff816ba14b: wbt_requeue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void wbt_requeue(struct rq_qos *rqos, struct request *rq);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-wbt.c (ffffffff8177a650)
Location: block/blk-wbt.c:632
Inline: True
```
**Symbols:**

```
ffffffff8177a650-ffffffff8177a69b: wbt_requeue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void wbt_requeue(struct rq_qos *rqos, struct request *rq);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-wbt.c (ffffffff817ba430)
Location: block/blk-wbt.c:691
Inline: True
```
**Symbols:**

```
ffffffff817ba430-ffffffff817ba47a: wbt_requeue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void wbt_requeue(struct rq_qos *rqos, struct request *rq);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-wbt.c (ffffffff817feba0)
Location: block/blk-wbt.c:690
Inline: True
```
**Symbols:**

```
ffffffff817feba0-ffffffff817febea: wbt_requeue (STB_LOCAL)
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
void wbt_requeue(struct rq_qos *rqos, struct request *rq);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-wbt.c (ffff800010620fe8)
Location: block/blk-wbt.c:623
Inline: True
```
**Symbols:**

```
ffff800010620fe8-ffff80001062103c: wbt_requeue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void wbt_requeue(struct rq_qos *rqos, struct request *rq);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-wbt.c (c07c90b8)
Location: block/blk-wbt.c:623
Inline: True
```
**Symbols:**

```
c07c90b8-c07c9104: wbt_requeue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void wbt_requeue(struct rq_qos *rqos, struct request *rq);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-wbt.c (c0000000007c16a0)
Location: block/blk-wbt.c:623
Inline: True
```
**Symbols:**

```
c0000000007c16a0-c0000000007c16d8: wbt_requeue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void wbt_requeue(struct rq_qos *rqos, struct request *rq);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-wbt.c (ffffffe000453ad6)
Location: block/blk-wbt.c:623
Inline: True
```
**Symbols:**

```
ffffffe000453ad6-ffffffe000453b24: wbt_requeue (STB_LOCAL)
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
void wbt_requeue(struct rq_qos *rqos, struct request *rq);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-wbt.c (ffffffff81512100)
Location: block/blk-wbt.c:623
Inline: True
```
**Symbols:**

```
ffffffff81512100-ffffffff81512130: wbt_requeue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void wbt_requeue(struct rq_qos *rqos, struct request *rq);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-wbt.c (ffffffff81502420)
Location: block/blk-wbt.c:623
Inline: True
```
**Symbols:**

```
ffffffff81502420-ffffffff81502450: wbt_requeue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void wbt_requeue(struct rq_qos *rqos, struct request *rq);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-wbt.c (ffffffff8150e190)
Location: block/blk-wbt.c:623
Inline: True
```
**Symbols:**

```
ffffffff8150e190-ffffffff8150e1c0: wbt_requeue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void wbt_requeue(struct rq_qos *rqos, struct request *rq);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/blk-wbt.c (ffffffff815277b0)
Location: block/blk-wbt.c:623
Inline: True
```
**Symbols:**

```
ffffffff815277b0-ffffffff815277e0: wbt_requeue (STB_LOCAL)
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
