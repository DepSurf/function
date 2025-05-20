# Function: <code>rcu_segcblist_insert_pend_cbs</code>

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
void rcu_segcblist_insert_pend_cbs(struct rcu_segcblist *rsclp, struct rcu_cblist *rclp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/rcu_segcblist.c (ffffffff810f7420)
Location: kernel/rcu/rcu_segcblist.c:368
Inline: False
Direct callers:
  - kernel/rcu/tree.c:rcutree_dead_cpu
```
**Symbols:**

```
ffffffff810f7420-ffffffff810f744d: rcu_segcblist_insert_pend_cbs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void rcu_segcblist_insert_pend_cbs(struct rcu_segcblist *rsclp, struct rcu_cblist *rclp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/rcu/rcu_segcblist.c (ffffffff8110159e)
Location: kernel/rcu/rcu_segcblist.c:285
Inline: True
Inline callers:
  - kernel/rcu/rcu_segcblist.c:rcu_segcblist_merge
```
**Symbols:**

```
ffffffff81101320-ffffffff8110134d: rcu_segcblist_insert_pend_cbs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void rcu_segcblist_insert_pend_cbs(struct rcu_segcblist *rsclp, struct rcu_cblist *rclp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/rcu/rcu_segcblist.c (ffffffff811099ee)
Location: kernel/rcu/rcu_segcblist.c:285
Inline: True
Inline callers:
  - kernel/rcu/rcu_segcblist.c:rcu_segcblist_merge
```
**Symbols:**

```
ffffffff811097b0-ffffffff811097dd: rcu_segcblist_insert_pend_cbs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void rcu_segcblist_insert_pend_cbs(struct rcu_segcblist *rsclp, struct rcu_cblist *rclp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/rcu/rcu_segcblist.c (ffffffff811151be)
Location: kernel/rcu/rcu_segcblist.c:285
Inline: True
Inline callers:
  - kernel/rcu/rcu_segcblist.c:rcu_segcblist_merge
```
**Symbols:**

```
ffffffff81114f80-ffffffff81114fad: rcu_segcblist_insert_pend_cbs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void rcu_segcblist_insert_pend_cbs(struct rcu_segcblist *rsclp, struct rcu_cblist *rclp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/rcu/rcu_segcblist.c (ffffffff8111efee)
Location: kernel/rcu/rcu_segcblist.c:272
Inline: True
Inline callers:
  - kernel/rcu/rcu_segcblist.c:rcu_segcblist_merge
```
**Symbols:**

```
ffffffff8111edb0-ffffffff8111eddd: rcu_segcblist_insert_pend_cbs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void rcu_segcblist_insert_pend_cbs(struct rcu_segcblist *rsclp, struct rcu_cblist *rclp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/rcu/rcu_segcblist.c (ffffffff8112b721)
Location: kernel/rcu/rcu_segcblist.c:396
Inline: True
Inline callers:
  - kernel/rcu/rcu_segcblist.c:rcu_segcblist_merge
```
**Symbols:**

```
ffffffff8112b4a0-ffffffff8112b4cd: rcu_segcblist_insert_pend_cbs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void rcu_segcblist_insert_pend_cbs(struct rcu_segcblist *rsclp, struct rcu_cblist *rclp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/rcu/rcu_segcblist.c (ffffffff81139bee)
Location: kernel/rcu/rcu_segcblist.c:377
Inline: True
Inline callers:
  - kernel/rcu/rcu_segcblist.c:rcu_segcblist_merge
```
**Symbols:**

```
ffffffff811399f0-ffffffff81139a12: rcu_segcblist_insert_pend_cbs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void rcu_segcblist_insert_pend_cbs(struct rcu_segcblist *rsclp, struct rcu_cblist *rclp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/rcu/rcu_segcblist.c (ffffffff811346de)
Location: kernel/rcu/rcu_segcblist.c:377
Inline: True
Inline callers:
  - kernel/rcu/rcu_segcblist.c:rcu_segcblist_merge
```
**Symbols:**

```
ffffffff811344c0-ffffffff811344e2: rcu_segcblist_insert_pend_cbs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void rcu_segcblist_insert_pend_cbs(struct rcu_segcblist *rsclp, struct rcu_cblist *rclp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/rcu/rcu_segcblist.c (ffffffff811355a7)
Location: kernel/rcu/rcu_segcblist.c:467
Inline: True
Inline callers:
  - kernel/rcu/rcu_segcblist.c:rcu_segcblist_merge
```
**Symbols:**

```
ffffffff81135310-ffffffff8113533f: rcu_segcblist_insert_pend_cbs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void rcu_segcblist_insert_pend_cbs(struct rcu_segcblist *rsclp, struct rcu_cblist *rclp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/rcu/rcu_segcblist.c (ffffffff81158087)
Location: kernel/rcu/rcu_segcblist.c:467
Inline: True
Inline callers:
  - kernel/rcu/rcu_segcblist.c:rcu_segcblist_merge
```
**Symbols:**

```
ffffffff81157ca0-ffffffff81157ccf: rcu_segcblist_insert_pend_cbs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void rcu_segcblist_insert_pend_cbs(struct rcu_segcblist *rsclp, struct rcu_cblist *rclp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/rcu/rcu_segcblist.c (ffffffff811813e7)
Location: kernel/rcu/rcu_segcblist.c:465
Inline: True
Inline callers:
  - kernel/rcu/rcu_segcblist.c:rcu_segcblist_merge
```
**Symbols:**

```
ffffffff81180fd0-ffffffff8118100b: rcu_segcblist_insert_pend_cbs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void rcu_segcblist_insert_pend_cbs(struct rcu_segcblist *rsclp, struct rcu_cblist *rclp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/rcu/rcu_segcblist.c (ffffffff811bbd57)
Location: kernel/rcu/rcu_segcblist.c:465
Inline: True
Inline callers:
  - kernel/rcu/rcu_segcblist.c:rcu_segcblist_merge
```
**Symbols:**

```
ffffffff811bb910-ffffffff811bb94b: rcu_segcblist_insert_pend_cbs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void rcu_segcblist_insert_pend_cbs(struct rcu_segcblist *rsclp, struct rcu_cblist *rclp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/rcu/rcu_segcblist.c (ffffffff811ce6f7)
Location: kernel/rcu/rcu_segcblist.c:465
Inline: True
Inline callers:
  - kernel/rcu/rcu_segcblist.c:rcu_segcblist_merge
```
**Symbols:**

```
ffffffff811ce2b0-ffffffff811ce2eb: rcu_segcblist_insert_pend_cbs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void rcu_segcblist_insert_pend_cbs(struct rcu_segcblist *rsclp, struct rcu_cblist *rclp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/rcu/rcu_segcblist.c (ffffffff811e32d9)
Location: kernel/rcu/rcu_segcblist.c:465
Inline: True
Inline callers:
  - kernel/rcu/rcu_segcblist.c:rcu_segcblist_merge
Direct callers:
  - kernel/rcu/tree.c:rcu_nocb_do_flush_bypass
```
**Symbols:**

```
ffffffff811e2ea0-ffffffff811e2edb: rcu_segcblist_insert_pend_cbs (STB_GLOBAL)
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
void rcu_segcblist_insert_pend_cbs(struct rcu_segcblist *rsclp, struct rcu_cblist *rclp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/rcu/rcu_segcblist.c (ffff800010193990)
Location: kernel/rcu/rcu_segcblist.c:396
Inline: True
Inline callers:
  - kernel/rcu/rcu_segcblist.c:rcu_segcblist_merge
```
**Symbols:**

```
ffff8000101936a8-ffff8000101936ec: rcu_segcblist_insert_pend_cbs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void rcu_segcblist_insert_pend_cbs(struct rcu_segcblist *rsclp, struct rcu_cblist *rclp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/rcu/rcu_segcblist.c (c03e0cd4)
Location: kernel/rcu/rcu_segcblist.c:396
Inline: True
Inline callers:
  - kernel/rcu/rcu_segcblist.c:rcu_segcblist_merge
```
**Symbols:**

```
c03e097c-c03e09bc: rcu_segcblist_insert_pend_cbs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void rcu_segcblist_insert_pend_cbs(struct rcu_segcblist *rsclp, struct rcu_cblist *rclp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/rcu/rcu_segcblist.c (c0000000001eea10)
Location: kernel/rcu/rcu_segcblist.c:396
Inline: True
Inline callers:
  - kernel/rcu/rcu_segcblist.c:rcu_segcblist_merge
```
**Symbols:**

```
c0000000001ee6d0-c0000000001ee704: rcu_segcblist_insert_pend_cbs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void rcu_segcblist_insert_pend_cbs(struct rcu_segcblist *rsclp, struct rcu_cblist *rclp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/rcu/rcu_segcblist.c (ffffffe000125dec)
Location: kernel/rcu/rcu_segcblist.c:396
Inline: True
Inline callers:
  - kernel/rcu/rcu_segcblist.c:rcu_segcblist_merge
```
**Symbols:**

```
ffffffe000125bb8-ffffffe000125bf4: rcu_segcblist_insert_pend_cbs (STB_GLOBAL)
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
void rcu_segcblist_insert_pend_cbs(struct rcu_segcblist *rsclp, struct rcu_cblist *rclp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/rcu/rcu_segcblist.c (ffffffff81123d01)
Location: kernel/rcu/rcu_segcblist.c:396
Inline: True
Inline callers:
  - kernel/rcu/rcu_segcblist.c:rcu_segcblist_merge
```
**Symbols:**

```
ffffffff81123a80-ffffffff81123aad: rcu_segcblist_insert_pend_cbs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void rcu_segcblist_insert_pend_cbs(struct rcu_segcblist *rsclp, struct rcu_cblist *rclp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/rcu/rcu_segcblist.c (ffffffff8111675f)
Location: kernel/rcu/rcu_segcblist.c:396
Inline: True
Inline callers:
  - kernel/rcu/rcu_segcblist.c:rcu_segcblist_merge
Direct callers:
  - kernel/rcu/tree.c:rcu_nocb_do_flush_bypass
```
**Symbols:**

```
ffffffff81116500-ffffffff8111652d: rcu_segcblist_insert_pend_cbs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void rcu_segcblist_insert_pend_cbs(struct rcu_segcblist *rsclp, struct rcu_cblist *rclp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/rcu/rcu_segcblist.c (ffffffff81121bf1)
Location: kernel/rcu/rcu_segcblist.c:396
Inline: True
Inline callers:
  - kernel/rcu/rcu_segcblist.c:rcu_segcblist_merge
```
**Symbols:**

```
ffffffff81121970-ffffffff8112199d: rcu_segcblist_insert_pend_cbs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void rcu_segcblist_insert_pend_cbs(struct rcu_segcblist *rsclp, struct rcu_cblist *rclp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/rcu/rcu_segcblist.c (ffffffff8112e201)
Location: kernel/rcu/rcu_segcblist.c:396
Inline: True
Inline callers:
  - kernel/rcu/rcu_segcblist.c:rcu_segcblist_merge
```
**Symbols:**

```
ffffffff8112df80-ffffffff8112dfad: rcu_segcblist_insert_pend_cbs (STB_GLOBAL)
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
