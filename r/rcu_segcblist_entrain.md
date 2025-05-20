# Function: <code>rcu_segcblist_entrain</code>

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
bool rcu_segcblist_entrain(struct rcu_segcblist *rsclp, struct callback_head *rhp, bool lazy);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/rcu_segcblist.c (ffffffff810f7240)
Location: kernel/rcu/rcu_segcblist.c:247
Inline: False
Direct callers:
  - kernel/rcu/srcutree.c:srcu_barrier
```
**Symbols:**

```
ffffffff810f7240-ffffffff810f72b4: rcu_segcblist_entrain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
bool rcu_segcblist_entrain(struct rcu_segcblist *rsclp, struct callback_head *rhp, bool lazy);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/rcu_segcblist.c (ffffffff81101140)
Location: kernel/rcu/rcu_segcblist.c:164
Inline: False
Direct callers:
  - kernel/rcu/srcutree.c:srcu_barrier
```
**Symbols:**

```
ffffffff81101140-ffffffff811011b8: rcu_segcblist_entrain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
bool rcu_segcblist_entrain(struct rcu_segcblist *rsclp, struct callback_head *rhp, bool lazy);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/rcu_segcblist.c (ffffffff811095c0)
Location: kernel/rcu/rcu_segcblist.c:164
Inline: False
Direct callers:
  - kernel/rcu/srcutree.c:srcu_barrier
```
**Symbols:**

```
ffffffff811095c0-ffffffff81109649: rcu_segcblist_entrain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
bool rcu_segcblist_entrain(struct rcu_segcblist *rsclp, struct callback_head *rhp, bool lazy);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/rcu_segcblist.c (ffffffff81114d90)
Location: kernel/rcu/rcu_segcblist.c:164
Inline: False
Direct callers:
  - kernel/rcu/srcutree.c:srcu_barrier
```
**Symbols:**

```
ffffffff81114d90-ffffffff81114e19: rcu_segcblist_entrain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
bool rcu_segcblist_entrain(struct rcu_segcblist *rsclp, struct callback_head *rhp, bool lazy);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/rcu_segcblist.c (ffffffff8111ebc0)
Location: kernel/rcu/rcu_segcblist.c:151
Inline: False
Direct callers:
  - kernel/rcu/srcutree.c:srcu_barrier
```
**Symbols:**

```
ffffffff8111ebc0-ffffffff8111ec48: rcu_segcblist_entrain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
bool rcu_segcblist_entrain(struct rcu_segcblist *rsclp, struct callback_head *rhp, bool lazy);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/rcu_segcblist.c (ffffffff8112b270)
Location: kernel/rcu/rcu_segcblist.c:277
Inline: False
Direct callers:
  - kernel/rcu/srcutree.c:srcu_barrier
```
**Symbols:**

```
ffffffff8112b270-ffffffff8112b317: rcu_segcblist_entrain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
bool rcu_segcblist_entrain(struct rcu_segcblist *rsclp, struct callback_head *rhp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/rcu_segcblist.c (ffffffff81139800)
Location: kernel/rcu/rcu_segcblist.c:264
Inline: False
Direct callers:
  - kernel/rcu/srcutree.c:srcu_barrier
```
**Symbols:**

```
ffffffff81139800-ffffffff81139883: rcu_segcblist_entrain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
bool rcu_segcblist_entrain(struct rcu_segcblist *rsclp, struct callback_head *rhp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/rcu_segcblist.c (ffffffff811342d0)
Location: kernel/rcu/rcu_segcblist.c:264
Inline: False
Direct callers:
  - kernel/rcu/srcutree.c:srcu_barrier
```
**Symbols:**

```
ffffffff811342d0-ffffffff81134353: rcu_segcblist_entrain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
bool rcu_segcblist_entrain(struct rcu_segcblist *rsclp, struct callback_head *rhp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/rcu_segcblist.c (ffffffff811350f0)
Location: kernel/rcu/rcu_segcblist.c:362
Inline: False
Direct callers:
  - kernel/rcu/srcutree.c:srcu_barrier
```
**Symbols:**

```
ffffffff811350f0-ffffffff8113518f: rcu_segcblist_entrain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
bool rcu_segcblist_entrain(struct rcu_segcblist *rsclp, struct callback_head *rhp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/rcu_segcblist.c (ffffffff811578f0)
Location: kernel/rcu/rcu_segcblist.c:362
Inline: False
Direct callers:
  - kernel/rcu/srcutree.c:srcu_barrier
```
**Symbols:**

```
ffffffff811578f0-ffffffff81157a28: rcu_segcblist_entrain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
bool rcu_segcblist_entrain(struct rcu_segcblist *rsclp, struct callback_head *rhp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/rcu_segcblist.c (ffffffff81180bb0)
Location: kernel/rcu/rcu_segcblist.c:360
Inline: False
Direct callers:
  - kernel/rcu/update.c:rcu_barrier_tasks_generic
  - kernel/rcu/srcutree.c:srcu_barrier_one_cpu
  - kernel/rcu/tree.c:rcu_barrier_entrain
```
**Symbols:**

```
ffffffff81180bb0-ffffffff81180d07: rcu_segcblist_entrain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
bool rcu_segcblist_entrain(struct rcu_segcblist *rsclp, struct callback_head *rhp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/rcu_segcblist.c (ffffffff811bb4a0)
Location: kernel/rcu/rcu_segcblist.c:360
Inline: False
Direct callers:
  - kernel/rcu/update.c:rcu_barrier_tasks_generic
  - kernel/rcu/srcutree.c:srcu_barrier_one_cpu
  - kernel/rcu/tree.c:rcu_barrier_entrain
```
**Symbols:**

```
ffffffff811bb4a0-ffffffff811bb5f7: rcu_segcblist_entrain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
bool rcu_segcblist_entrain(struct rcu_segcblist *rsclp, struct callback_head *rhp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/rcu_segcblist.c (ffffffff811cde40)
Location: kernel/rcu/rcu_segcblist.c:360
Inline: False
Direct callers:
  - kernel/rcu/update.c:rcu_barrier_tasks_generic
  - kernel/rcu/srcutree.c:srcu_barrier_one_cpu
  - kernel/rcu/tree.c:rcu_barrier_entrain
```
**Symbols:**

```
ffffffff811cde40-ffffffff811cdf97: rcu_segcblist_entrain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
bool rcu_segcblist_entrain(struct rcu_segcblist *rsclp, struct callback_head *rhp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/rcu_segcblist.c (ffffffff811e2a50)
Location: kernel/rcu/rcu_segcblist.c:360
Inline: False
Direct callers:
  - kernel/rcu/update.c:rcu_barrier_tasks_generic
  - kernel/rcu/srcutree.c:srcu_barrier_one_cpu
  - kernel/rcu/tree.c:rcu_barrier_entrain
```
**Symbols:**

```
ffffffff811e2a50-ffffffff811e2b95: rcu_segcblist_entrain (STB_GLOBAL)
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
bool rcu_segcblist_entrain(struct rcu_segcblist *rsclp, struct callback_head *rhp, bool lazy);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/rcu_segcblist.c (ffff8000101933b0)
Location: kernel/rcu/rcu_segcblist.c:277
Inline: False
Direct callers:
  - kernel/rcu/srcutree.c:srcu_barrier
  - kernel/rcu/srcutree.c:srcu_barrier
```
**Symbols:**

```
ffff8000101933b0-ffff800010193494: rcu_segcblist_entrain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
bool rcu_segcblist_entrain(struct rcu_segcblist *rsclp, struct callback_head *rhp, bool lazy);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/rcu_segcblist.c (c03e06ec)
Location: kernel/rcu/rcu_segcblist.c:277
Inline: False
Direct callers:
  - kernel/rcu/srcutree.c:srcu_barrier
```
**Symbols:**

```
c03e06ec-c03e07a0: rcu_segcblist_entrain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
bool rcu_segcblist_entrain(struct rcu_segcblist *rsclp, struct callback_head *rhp, bool lazy);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/rcu_segcblist.c (c0000000001ee420)
Location: kernel/rcu/rcu_segcblist.c:277
Inline: False
Direct callers:
  - kernel/rcu/srcutree.c:srcu_barrier
```
**Symbols:**

```
c0000000001ee420-c0000000001ee504: rcu_segcblist_entrain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
bool rcu_segcblist_entrain(struct rcu_segcblist *rsclp, struct callback_head *rhp, bool lazy);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/rcu_segcblist.c (ffffffe000125986)
Location: kernel/rcu/rcu_segcblist.c:277
Inline: False
Direct callers:
  - kernel/rcu/srcutree.c:srcu_barrier
  - kernel/rcu/tree.c:rcu_barrier_func
```
**Symbols:**

```
ffffffe000125986-ffffffe000125a1a: rcu_segcblist_entrain (STB_GLOBAL)
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
bool rcu_segcblist_entrain(struct rcu_segcblist *rsclp, struct callback_head *rhp, bool lazy);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/rcu_segcblist.c (ffffffff81123850)
Location: kernel/rcu/rcu_segcblist.c:277
Inline: False
Direct callers:
  - kernel/rcu/srcutree.c:srcu_barrier
```
**Symbols:**

```
ffffffff81123850-ffffffff811238f7: rcu_segcblist_entrain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
bool rcu_segcblist_entrain(struct rcu_segcblist *rsclp, struct callback_head *rhp, bool lazy);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/rcu_segcblist.c (ffffffff81116300)
Location: kernel/rcu/rcu_segcblist.c:277
Inline: False
Direct callers:
  - kernel/rcu/srcutree.c:srcu_barrier
  - kernel/rcu/tree.c:rcu_barrier_func
```
**Symbols:**

```
ffffffff81116300-ffffffff81116395: rcu_segcblist_entrain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
bool rcu_segcblist_entrain(struct rcu_segcblist *rsclp, struct callback_head *rhp, bool lazy);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/rcu_segcblist.c (ffffffff81121740)
Location: kernel/rcu/rcu_segcblist.c:277
Inline: False
Direct callers:
  - kernel/rcu/srcutree.c:srcu_barrier
```
**Symbols:**

```
ffffffff81121740-ffffffff811217e7: rcu_segcblist_entrain (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
bool rcu_segcblist_entrain(struct rcu_segcblist *rsclp, struct callback_head *rhp, bool lazy);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/rcu_segcblist.c (ffffffff8112dd50)
Location: kernel/rcu/rcu_segcblist.c:277
Inline: False
Direct callers:
  - kernel/rcu/srcutree.c:srcu_barrier
```
**Symbols:**

```
ffffffff8112dd50-ffffffff8112ddf7: rcu_segcblist_entrain (STB_GLOBAL)
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
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.4</code> and <code>5.8</code> ⚠️</summary>
<ul>
<li>
<b>Param removed. </b>
<code>bool lazy</code>
</li>
</ul>
</details>
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
