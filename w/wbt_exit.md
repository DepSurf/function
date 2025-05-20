# Function: <code>wbt_exit</code>

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
void wbt_exit(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-wbt.c (ffffffff8144ae70)
Location: block/blk-wbt.c:742
Inline: False
Direct callers:
  - block/blk-core.c:blk_init_allocated_queue
  - block/blk-sysfs.c:blk_release_queue
  - block/blk-mq.c:blk_mq_free_queue
```
**Symbols:**

```
ffffffff8144ae70-ffffffff8144aea7: wbt_exit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void wbt_exit(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-wbt.c (ffffffff81459150)
Location: block/blk-wbt.c:748
Inline: False
Direct callers:
  - block/blk-sysfs.c:blk_unregister_queue
  - block/blk-wbt.c:wbt_disable_default
```
**Symbols:**

```
ffffffff81459150-ffffffff81459191: wbt_exit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void wbt_exit(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-wbt.c (ffffffff81484ea0)
Location: block/blk-wbt.c:753
Inline: False
Direct callers:
  - block/blk-sysfs.c:blk_unregister_queue
  - block/blk-wbt.c:wbt_disable_default
```
**Symbols:**

```
ffffffff81484ea0-ffffffff81484ee1: wbt_exit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void wbt_exit(struct request_queue *q);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-wbt.c (ffffffff814b9d70)
Location: block/blk-wbt.c:784
Inline: False
Direct callers:
  - block/blk-sysfs.c:blk_unregister_queue
  - block/blk-wbt.c:wbt_disable_default
```
**Symbols:**

```
ffffffff814b9d70-ffffffff814b9db1: wbt_exit (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void wbt_exit(struct rq_qos *rqos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-wbt.c (ffffffff814ccf40)
Location: block/blk-wbt.c:691
Inline: False
```
**Symbols:**

```
ffffffff814ccf40-ffffffff814ccf6f: wbt_exit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void wbt_exit(struct rq_qos *rqos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-wbt.c (ffffffff814fb690)
Location: block/blk-wbt.c:692
Inline: False
```
**Symbols:**

```
ffffffff814fb690-ffffffff814fb6bf: wbt_exit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void wbt_exit(struct rq_qos *rqos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-wbt.c (ffffffff815195e0)
Location: block/blk-wbt.c:691
Inline: False
```
**Symbols:**

```
ffffffff815195e0-ffffffff8151960f: wbt_exit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void wbt_exit(struct rq_qos *rqos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-wbt.c (ffffffff81579b90)
Location: block/blk-wbt.c:683
Inline: False
```
**Symbols:**

```
ffffffff81579b90-ffffffff81579bc2: wbt_exit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void wbt_exit(struct rq_qos *rqos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-wbt.c (ffffffff81596aa0)
Location: block/blk-wbt.c:683
Inline: False
```
**Symbols:**

```
ffffffff81596aa0-ffffffff81596ad2: wbt_exit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void wbt_exit(struct rq_qos *rqos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-wbt.c (ffffffff8159d8d0)
Location: block/blk-wbt.c:688
Inline: False
```
**Symbols:**

```
ffffffff8159d8d0-ffffffff8159d902: wbt_exit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void wbt_exit(struct rq_qos *rqos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-wbt.c (ffffffff81605f90)
Location: block/blk-wbt.c:690
Inline: False
```
**Symbols:**

```
ffffffff81605f90-ffffffff81605fc2: wbt_exit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void wbt_exit(struct rq_qos *rqos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-wbt.c (ffffffff816b9e20)
Location: block/blk-wbt.c:690
Inline: False
```
**Symbols:**

```
ffffffff816b9e20-ffffffff816b9e5a: wbt_exit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void wbt_exit(struct rq_qos *rqos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-wbt.c (ffffffff8177a310)
Location: block/blk-wbt.c:708
Inline: False
```
**Symbols:**

```
ffffffff8177a310-ffffffff8177a34a: wbt_exit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void wbt_exit(struct rq_qos *rqos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-wbt.c (ffffffff817ba040)
Location: block/blk-wbt.c:770
Inline: False
```
**Symbols:**

```
ffffffff817ba040-ffffffff817ba080: wbt_exit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void wbt_exit(struct rq_qos *rqos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-wbt.c (ffffffff817fe7b0)
Location: block/blk-wbt.c:762
Inline: False
```
**Symbols:**

```
ffffffff817fe7b0-ffffffff817fe7f0: wbt_exit (STB_LOCAL)
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
void wbt_exit(struct rq_qos *rqos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-wbt.c (ffff800010620be0)
Location: block/blk-wbt.c:691
Inline: False
```
**Symbols:**

```
ffff800010620be0-ffff800010620c24: wbt_exit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void wbt_exit(struct rq_qos *rqos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-wbt.c (c07c8bac)
Location: block/blk-wbt.c:691
Inline: False
```
**Symbols:**

```
c07c8bac-c07c8be4: wbt_exit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void wbt_exit(struct rq_qos *rqos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-wbt.c (c0000000007c0e60)
Location: block/blk-wbt.c:691
Inline: False
```
**Symbols:**

```
c0000000007c0e60-c0000000007c0ec0: wbt_exit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void wbt_exit(struct rq_qos *rqos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-wbt.c (ffffffe000453486)
Location: block/blk-wbt.c:691
Inline: False
```
**Symbols:**

```
ffffffe000453486-ffffffe0004534cc: wbt_exit (STB_LOCAL)
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
void wbt_exit(struct rq_qos *rqos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-wbt.c (ffffffff81511bc0)
Location: block/blk-wbt.c:691
Inline: False
```
**Symbols:**

```
ffffffff81511bc0-ffffffff81511bef: wbt_exit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void wbt_exit(struct rq_qos *rqos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-wbt.c (ffffffff81501ee0)
Location: block/blk-wbt.c:691
Inline: False
```
**Symbols:**

```
ffffffff81501ee0-ffffffff81501f0f: wbt_exit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void wbt_exit(struct rq_qos *rqos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-wbt.c (ffffffff8150dc50)
Location: block/blk-wbt.c:691
Inline: False
```
**Symbols:**

```
ffffffff8150dc50-ffffffff8150dc7f: wbt_exit (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void wbt_exit(struct rq_qos *rqos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-wbt.c (ffffffff81527270)
Location: block/blk-wbt.c:691
Inline: False
```
**Symbols:**

```
ffffffff81527270-ffffffff8152729f: wbt_exit (STB_LOCAL)
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
No changes between <code>4.15</code> and <code>4.18</code> ✅
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
<code>struct request_queue *q</code>
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
