# Function: <code>rcu_segcblist_enqueue</code>

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
void rcu_segcblist_enqueue(struct rcu_segcblist *rsclp, struct callback_head *rhp, bool lazy);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/rcu_segcblist.c (ffffffff810f7200)
Location: kernel/rcu/rcu_segcblist.c:225
Inline: False
Direct callers:
  - kernel/rcu/srcutree.c:__call_srcu
```
**Symbols:**

```
ffffffff810f7200-ffffffff810f7235: rcu_segcblist_enqueue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void rcu_segcblist_enqueue(struct rcu_segcblist *rsclp, struct callback_head *rhp, bool lazy);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/rcu_segcblist.c (ffffffff81101100)
Location: kernel/rcu/rcu_segcblist.c:142
Inline: False
Direct callers:
  - kernel/rcu/srcutree.c:__call_srcu
```
**Symbols:**

```
ffffffff81101100-ffffffff81101138: rcu_segcblist_enqueue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void rcu_segcblist_enqueue(struct rcu_segcblist *rsclp, struct callback_head *rhp, bool lazy);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/rcu_segcblist.c (ffffffff81109580)
Location: kernel/rcu/rcu_segcblist.c:142
Inline: False
Direct callers:
  - kernel/rcu/srcutree.c:__call_srcu
```
**Symbols:**

```
ffffffff81109580-ffffffff811095b8: rcu_segcblist_enqueue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void rcu_segcblist_enqueue(struct rcu_segcblist *rsclp, struct callback_head *rhp, bool lazy);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/rcu_segcblist.c (ffffffff81114d50)
Location: kernel/rcu/rcu_segcblist.c:142
Inline: False
Direct callers:
  - kernel/rcu/srcutree.c:__call_srcu
```
**Symbols:**

```
ffffffff81114d50-ffffffff81114d88: rcu_segcblist_enqueue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void rcu_segcblist_enqueue(struct rcu_segcblist *rsclp, struct callback_head *rhp, bool lazy);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/rcu_segcblist.c (ffffffff8111eb80)
Location: kernel/rcu/rcu_segcblist.c:129
Inline: False
Direct callers:
  - kernel/rcu/srcutree.c:__call_srcu
```
**Symbols:**

```
ffffffff8111eb80-ffffffff8111ebb8: rcu_segcblist_enqueue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void rcu_segcblist_enqueue(struct rcu_segcblist *rsclp, struct callback_head *rhp, bool lazy);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/rcu_segcblist.c (ffffffff8112b220)
Location: kernel/rcu/rcu_segcblist.c:255
Inline: False
Direct callers:
  - kernel/rcu/srcutree.c:__call_srcu
  - kernel/rcu/tree.c:__call_rcu
```
**Symbols:**

```
ffffffff8112b220-ffffffff8112b264: rcu_segcblist_enqueue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void rcu_segcblist_enqueue(struct rcu_segcblist *rsclp, struct callback_head *rhp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/rcu_segcblist.c (ffffffff811397c0)
Location: kernel/rcu/rcu_segcblist.c:244
Inline: False
Direct callers:
  - kernel/rcu/srcutree.c:__call_srcu
  - kernel/rcu/tree.c:__call_rcu
```
**Symbols:**

```
ffffffff811397c0-ffffffff811397fb: rcu_segcblist_enqueue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void rcu_segcblist_enqueue(struct rcu_segcblist *rsclp, struct callback_head *rhp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/rcu_segcblist.c (ffffffff81134290)
Location: kernel/rcu/rcu_segcblist.c:244
Inline: False
Direct callers:
  - kernel/rcu/srcutree.c:__call_srcu
  - kernel/rcu/tree.c:__call_rcu
```
**Symbols:**

```
ffffffff81134290-ffffffff811342cb: rcu_segcblist_enqueue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void rcu_segcblist_enqueue(struct rcu_segcblist *rsclp, struct callback_head *rhp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/rcu_segcblist.c (ffffffff811350a0)
Location: kernel/rcu/rcu_segcblist.c:342
Inline: False
Direct callers:
  - kernel/rcu/srcutree.c:srcu_gp_start_if_needed
  - kernel/rcu/tree.c:__call_rcu
```
**Symbols:**

```
ffffffff811350a0-ffffffff811350e1: rcu_segcblist_enqueue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void rcu_segcblist_enqueue(struct rcu_segcblist *rsclp, struct callback_head *rhp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/rcu_segcblist.c (ffffffff811578a0)
Location: kernel/rcu/rcu_segcblist.c:342
Inline: False
Direct callers:
  - kernel/rcu/srcutree.c:srcu_gp_start_if_needed
  - kernel/rcu/tree.c:__call_rcu
```
**Symbols:**

```
ffffffff811578a0-ffffffff811578e1: rcu_segcblist_enqueue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void rcu_segcblist_enqueue(struct rcu_segcblist *rsclp, struct callback_head *rhp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/rcu_segcblist.c (ffffffff81180b60)
Location: kernel/rcu/rcu_segcblist.c:340
Inline: False
Direct callers:
  - kernel/rcu/update.c:call_rcu_tasks_generic
  - kernel/rcu/update.c:call_rcu_tasks_generic
  - kernel/rcu/srcutree.c:srcu_gp_start_if_needed
  - kernel/rcu/tree.c:call_rcu
```
**Symbols:**

```
ffffffff81180b60-ffffffff81180bab: rcu_segcblist_enqueue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void rcu_segcblist_enqueue(struct rcu_segcblist *rsclp, struct callback_head *rhp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/rcu_segcblist.c (ffffffff811bb440)
Location: kernel/rcu/rcu_segcblist.c:340
Inline: False
Direct callers:
  - kernel/rcu/update.c:call_rcu_tasks_generic
  - kernel/rcu/update.c:call_rcu_tasks_generic
  - kernel/rcu/srcutree.c:srcu_gp_start_if_needed
```
**Symbols:**

```
ffffffff811bb440-ffffffff811bb48b: rcu_segcblist_enqueue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void rcu_segcblist_enqueue(struct rcu_segcblist *rsclp, struct callback_head *rhp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/rcu_segcblist.c (ffffffff811cdde0)
Location: kernel/rcu/rcu_segcblist.c:340
Inline: False
Direct callers:
  - kernel/rcu/update.c:call_rcu_tasks_generic
  - kernel/rcu/update.c:call_rcu_tasks_generic
  - kernel/rcu/srcutree.c:srcu_gp_start_if_needed
```
**Symbols:**

```
ffffffff811cdde0-ffffffff811cde2b: rcu_segcblist_enqueue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void rcu_segcblist_enqueue(struct rcu_segcblist *rsclp, struct callback_head *rhp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/rcu_segcblist.c (ffffffff811e2a00)
Location: kernel/rcu/rcu_segcblist.c:340
Inline: False
Direct callers:
  - kernel/rcu/update.c:call_rcu_tasks_generic
  - kernel/rcu/update.c:call_rcu_tasks_generic
  - kernel/rcu/srcutree.c:srcu_gp_start_if_needed
  - kernel/rcu/tree.c:__call_rcu_common
```
**Symbols:**

```
ffffffff811e2a00-ffffffff811e2a39: rcu_segcblist_enqueue (STB_GLOBAL)
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
void rcu_segcblist_enqueue(struct rcu_segcblist *rsclp, struct callback_head *rhp, bool lazy);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/rcu_segcblist.c (ffff800010193340)
Location: kernel/rcu/rcu_segcblist.c:255
Inline: False
Direct callers:
  - kernel/rcu/srcutree.c:__call_srcu
  - kernel/rcu/tree.c:__call_rcu
```
**Symbols:**

```
ffff800010193340-ffff8000101933ac: rcu_segcblist_enqueue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void rcu_segcblist_enqueue(struct rcu_segcblist *rsclp, struct callback_head *rhp, bool lazy);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/rcu_segcblist.c (c03e0698)
Location: kernel/rcu/rcu_segcblist.c:255
Inline: False
Direct callers:
  - kernel/rcu/srcutree.c:__call_srcu
  - kernel/rcu/tree.c:__call_rcu
```
**Symbols:**

```
c03e0698-c03e06ec: rcu_segcblist_enqueue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void rcu_segcblist_enqueue(struct rcu_segcblist *rsclp, struct callback_head *rhp, bool lazy);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/rcu_segcblist.c (c0000000001ee3d0)
Location: kernel/rcu/rcu_segcblist.c:255
Inline: False
Direct callers:
  - kernel/rcu/srcutree.c:__call_srcu
  - kernel/rcu/tree.c:__call_rcu
```
**Symbols:**

```
c0000000001ee3d0-c0000000001ee41c: rcu_segcblist_enqueue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void rcu_segcblist_enqueue(struct rcu_segcblist *rsclp, struct callback_head *rhp, bool lazy);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/rcu_segcblist.c (ffffffe000125930)
Location: kernel/rcu/rcu_segcblist.c:255
Inline: False
Direct callers:
  - kernel/rcu/srcutree.c:__call_srcu
  - kernel/rcu/tree.c:__call_rcu
```
**Symbols:**

```
ffffffe000125930-ffffffe000125986: rcu_segcblist_enqueue (STB_GLOBAL)
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
void rcu_segcblist_enqueue(struct rcu_segcblist *rsclp, struct callback_head *rhp, bool lazy);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/rcu_segcblist.c (ffffffff81123800)
Location: kernel/rcu/rcu_segcblist.c:255
Inline: False
Direct callers:
  - kernel/rcu/srcutree.c:__call_srcu
  - kernel/rcu/tree.c:__call_rcu
```
**Symbols:**

```
ffffffff81123800-ffffffff81123844: rcu_segcblist_enqueue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void rcu_segcblist_enqueue(struct rcu_segcblist *rsclp, struct callback_head *rhp, bool lazy);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/rcu_segcblist.c (ffffffff811162c0)
Location: kernel/rcu/rcu_segcblist.c:255
Inline: False
Direct callers:
  - kernel/rcu/srcutree.c:__call_srcu
  - kernel/rcu/tree.c:__call_rcu
```
**Symbols:**

```
ffffffff811162c0-ffffffff811162f2: rcu_segcblist_enqueue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void rcu_segcblist_enqueue(struct rcu_segcblist *rsclp, struct callback_head *rhp, bool lazy);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/rcu_segcblist.c (ffffffff811216f0)
Location: kernel/rcu/rcu_segcblist.c:255
Inline: False
Direct callers:
  - kernel/rcu/srcutree.c:__call_srcu
  - kernel/rcu/tree.c:__call_rcu
```
**Symbols:**

```
ffffffff811216f0-ffffffff81121734: rcu_segcblist_enqueue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void rcu_segcblist_enqueue(struct rcu_segcblist *rsclp, struct callback_head *rhp, bool lazy);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/rcu_segcblist.c (ffffffff8112dd00)
Location: kernel/rcu/rcu_segcblist.c:255
Inline: False
Direct callers:
  - kernel/rcu/srcutree.c:__call_srcu
  - kernel/rcu/tree.c:__call_rcu
```
**Symbols:**

```
ffffffff8112dd00-ffffffff8112dd44: rcu_segcblist_enqueue (STB_GLOBAL)
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
