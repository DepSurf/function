# Function: <code>wbt_done</code>

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
void wbt_done(struct rq_wb *rwb, struct blk_issue_stat *stat);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-wbt.c (ffffffff8144a770)
Location: block/blk-wbt.c:168
Inline: False
Direct callers:
  - block/blk-core.c:blk_finish_request
  - block/blk-core.c:__blk_put_request
  - block/blk-mq.c:__blk_mq_free_request
```
**Symbols:**

```
ffffffff8144a770-ffffffff8144a84f: wbt_done (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void wbt_done(struct rq_wb *rwb, struct blk_issue_stat *stat);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-wbt.c (ffffffff81458a50)
Location: block/blk-wbt.c:168
Inline: False
Direct callers:
  - block/blk-core.c:blk_finish_request
  - block/blk-core.c:__blk_put_request
  - block/blk-mq.c:blk_mq_free_request
```
**Symbols:**

```
ffffffff81458a50-ffffffff81458af6: wbt_done (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void wbt_done(struct rq_wb *rwb, struct blk_issue_stat *stat);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-wbt.c (ffffffff814847c0)
Location: block/blk-wbt.c:168
Inline: False
Direct callers:
  - block/blk-core.c:blk_finish_request
  - block/blk-core.c:__blk_put_request
  - block/blk-mq.c:blk_mq_free_request
```
**Symbols:**

```
ffffffff814847c0-ffffffff81484857: wbt_done (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void wbt_done(struct rq_wb *rwb, struct request *rq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-wbt.c (ffffffff814b95e0)
Location: block/blk-wbt.c:197
Inline: False
Direct callers:
  - block/blk-core.c:blk_finish_request
  - block/blk-core.c:__blk_put_request
  - block/blk-mq.c:blk_mq_free_request
```
**Symbols:**

```
ffffffff814b95e0-ffffffff814b965b: wbt_done (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void wbt_done(struct rq_qos *rqos, struct request *rq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-wbt.c (ffffffff814cd080)
Location: block/blk-wbt.c:184
Inline: False
```
**Symbols:**

```
ffffffff814cd080-ffffffff814cd105: wbt_done (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void wbt_done(struct rq_qos *rqos, struct request *rq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-wbt.c (ffffffff814fb8f0)
Location: block/blk-wbt.c:185
Inline: False
```
**Symbols:**

```
ffffffff814fb8f0-ffffffff814fb97b: wbt_done (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void wbt_done(struct rq_qos *rqos, struct request *rq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-wbt.c (ffffffff81519c10)
Location: block/blk-wbt.c:185
Inline: False
```
**Symbols:**

```
ffffffff81519c10-ffffffff81519c9b: wbt_done (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void wbt_done(struct rq_qos *rqos, struct request *rq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-wbt.c (ffffffff81579ed0)
Location: block/blk-wbt.c:185
Inline: False
```
**Symbols:**

```
ffffffff81579ed0-ffffffff81579f84: wbt_done (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void wbt_done(struct rq_qos *rqos, struct request *rq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-wbt.c (ffffffff81596de0)
Location: block/blk-wbt.c:185
Inline: False
```
**Symbols:**

```
ffffffff81596de0-ffffffff81596e94: wbt_done (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void wbt_done(struct rq_qos *rqos, struct request *rq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-wbt.c (ffffffff8159ddc0)
Location: block/blk-wbt.c:186
Inline: False
```
**Symbols:**

```
ffffffff8159ddc0-ffffffff8159de88: wbt_done (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void wbt_done(struct rq_qos *rqos, struct request *rq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-wbt.c (ffffffff816064a0)
Location: block/blk-wbt.c:186
Inline: False
```
**Symbols:**

```
ffffffff816064a0-ffffffff81606568: wbt_done (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void wbt_done(struct rq_qos *rqos, struct request *rq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-wbt.c (ffffffff816ba540)
Location: block/blk-wbt.c:186
Inline: False
```
**Symbols:**

```
ffffffff816ba540-ffffffff816ba62f: wbt_done (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void wbt_done(struct rq_qos *rqos, struct request *rq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-wbt.c (ffffffff8177aae0)
Location: block/blk-wbt.c:187
Inline: False
```
**Symbols:**

```
ffffffff8177aae0-ffffffff8177abcf: wbt_done (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void wbt_done(struct rq_qos *rqos, struct request *rq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-wbt.c (ffffffff817ba490)
Location: block/blk-wbt.c:245
Inline: False
```
**Symbols:**

```
ffffffff817ba490-ffffffff817ba57a: wbt_done (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void wbt_done(struct rq_qos *rqos, struct request *rq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-wbt.c (ffffffff817fec00)
Location: block/blk-wbt.c:244
Inline: False
```
**Symbols:**

```
ffffffff817fec00-ffffffff817fecea: wbt_done (STB_LOCAL)
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
void wbt_done(struct rq_qos *rqos, struct request *rq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-wbt.c (ffff8000106211e8)
Location: block/blk-wbt.c:185
Inline: False
```
**Symbols:**

```
ffff8000106211e8-ffff8000106212a4: wbt_done (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void wbt_done(struct rq_qos *rqos, struct request *rq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-wbt.c (c07c8d94)
Location: block/blk-wbt.c:185
Inline: False
```
**Symbols:**

```
c07c8d94-c07c8e78: wbt_done (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void wbt_done(struct rq_qos *rqos, struct request *rq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-wbt.c (c0000000007c1890)
Location: block/blk-wbt.c:185
Inline: False
```
**Symbols:**

```
c0000000007c1890-c0000000007c1968: wbt_done (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void wbt_done(struct rq_qos *rqos, struct request *rq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-wbt.c (ffffffe0004537f2)
Location: block/blk-wbt.c:185
Inline: False
```
**Symbols:**

```
ffffffe0004537f2-ffffffe000453886: wbt_done (STB_LOCAL)
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
void wbt_done(struct rq_qos *rqos, struct request *rq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-wbt.c (ffffffff815121f0)
Location: block/blk-wbt.c:185
Inline: False
```
**Symbols:**

```
ffffffff815121f0-ffffffff8151227b: wbt_done (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void wbt_done(struct rq_qos *rqos, struct request *rq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-wbt.c (ffffffff81502510)
Location: block/blk-wbt.c:185
Inline: False
```
**Symbols:**

```
ffffffff81502510-ffffffff8150259b: wbt_done (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void wbt_done(struct rq_qos *rqos, struct request *rq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-wbt.c (ffffffff8150e280)
Location: block/blk-wbt.c:185
Inline: False
```
**Symbols:**

```
ffffffff8150e280-ffffffff8150e30b: wbt_done (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void wbt_done(struct rq_qos *rqos, struct request *rq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-wbt.c (ffffffff815279e0)
Location: block/blk-wbt.c:185
Inline: False
```
**Symbols:**

```
ffffffff815279e0-ffffffff81527a6b: wbt_done (STB_LOCAL)
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
