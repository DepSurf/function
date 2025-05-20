# Function: <code>rcu_segcblist_insert_done_cbs</code>

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
void rcu_segcblist_insert_done_cbs(struct rcu_segcblist *rsclp, struct rcu_cblist *rclp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/rcu_segcblist.c (ffffffff810f73d0)
Location: kernel/rcu/rcu_segcblist.c:346
Inline: False
Direct callers:
  - kernel/rcu/tree.c:rcutree_dead_cpu
  - kernel/rcu/tree.c:rcu_process_callbacks
```
**Symbols:**

```
ffffffff810f73d0-ffffffff810f741a: rcu_segcblist_insert_done_cbs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void rcu_segcblist_insert_done_cbs(struct rcu_segcblist *rsclp, struct rcu_cblist *rclp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/rcu/rcu_segcblist.c (ffffffff81101544)
Location: kernel/rcu/rcu_segcblist.c:263
Inline: True
Inline callers:
  - kernel/rcu/rcu_segcblist.c:rcu_segcblist_merge
Direct callers:
  - kernel/rcu/tree.c:rcu_process_callbacks
```
**Symbols:**

```
ffffffff811012d0-ffffffff8110131a: rcu_segcblist_insert_done_cbs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void rcu_segcblist_insert_done_cbs(struct rcu_segcblist *rsclp, struct rcu_cblist *rclp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/rcu/rcu_segcblist.c (ffffffff811099ae)
Location: kernel/rcu/rcu_segcblist.c:263
Inline: True
Inline callers:
  - kernel/rcu/rcu_segcblist.c:rcu_segcblist_merge
Direct callers:
  - kernel/rcu/tree.c:rcu_process_callbacks
```
**Symbols:**

```
ffffffff81109760-ffffffff811097aa: rcu_segcblist_insert_done_cbs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void rcu_segcblist_insert_done_cbs(struct rcu_segcblist *rsclp, struct rcu_cblist *rclp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/rcu/rcu_segcblist.c (ffffffff8111517e)
Location: kernel/rcu/rcu_segcblist.c:263
Inline: True
Inline callers:
  - kernel/rcu/rcu_segcblist.c:rcu_segcblist_merge
  - kernel/rcu/rcu_segcblist.c:rcu_segcblist_merge
Direct callers:
  - kernel/rcu/tree.c:rcu_process_callbacks
```
**Symbols:**

```
ffffffff81114f30-ffffffff81114f7a: rcu_segcblist_insert_done_cbs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void rcu_segcblist_insert_done_cbs(struct rcu_segcblist *rsclp, struct rcu_cblist *rclp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/rcu/rcu_segcblist.c (ffffffff8111efae)
Location: kernel/rcu/rcu_segcblist.c:250
Inline: True
Inline callers:
  - kernel/rcu/rcu_segcblist.c:rcu_segcblist_merge
  - kernel/rcu/rcu_segcblist.c:rcu_segcblist_merge
Direct callers:
  - kernel/rcu/tree.c:rcu_core
```
**Symbols:**

```
ffffffff8111ed60-ffffffff8111edaa: rcu_segcblist_insert_done_cbs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void rcu_segcblist_insert_done_cbs(struct rcu_segcblist *rsclp, struct rcu_cblist *rclp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/rcu/rcu_segcblist.c (ffffffff8112b6e1)
Location: kernel/rcu/rcu_segcblist.c:374
Inline: True
Inline callers:
  - kernel/rcu/rcu_segcblist.c:rcu_segcblist_merge
  - kernel/rcu/rcu_segcblist.c:rcu_segcblist_merge
Direct callers:
  - kernel/rcu/tree.c:rcu_do_batch
```
**Symbols:**

```
ffffffff8112b450-ffffffff8112b49a: rcu_segcblist_insert_done_cbs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void rcu_segcblist_insert_done_cbs(struct rcu_segcblist *rsclp, struct rcu_cblist *rclp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/rcu/rcu_segcblist.c (ffffffff81139bb0)
Location: kernel/rcu/rcu_segcblist.c:355
Inline: True
Inline callers:
  - kernel/rcu/rcu_segcblist.c:rcu_segcblist_merge
  - kernel/rcu/rcu_segcblist.c:rcu_segcblist_merge
Direct callers:
  - kernel/rcu/tree.c:rcu_do_batch
```
**Symbols:**

```
ffffffff811399a0-ffffffff811399eb: rcu_segcblist_insert_done_cbs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void rcu_segcblist_insert_done_cbs(struct rcu_segcblist *rsclp, struct rcu_cblist *rclp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/rcu/rcu_segcblist.c (ffffffff811346a0)
Location: kernel/rcu/rcu_segcblist.c:355
Inline: True
Inline callers:
  - kernel/rcu/rcu_segcblist.c:rcu_segcblist_merge
  - kernel/rcu/rcu_segcblist.c:rcu_segcblist_merge
Direct callers:
  - kernel/rcu/tree.c:rcu_do_batch
```
**Symbols:**

```
ffffffff81134470-ffffffff811344bb: rcu_segcblist_insert_done_cbs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void rcu_segcblist_insert_done_cbs(struct rcu_segcblist *rsclp, struct rcu_cblist *rclp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/rcu/rcu_segcblist.c (ffffffff811352b0)
Location: kernel/rcu/rcu_segcblist.c:444
Inline: True
Direct callers:
  - kernel/rcu/tree.c:rcu_do_batch
  - kernel/rcu/rcu_segcblist.c:rcu_segcblist_merge
```
**Symbols:**

```
ffffffff811352b0-ffffffff81135307: rcu_segcblist_insert_done_cbs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void rcu_segcblist_insert_done_cbs(struct rcu_segcblist *rsclp, struct rcu_cblist *rclp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/rcu/rcu_segcblist.c (ffffffff81157c00)
Location: kernel/rcu/rcu_segcblist.c:444
Inline: True
Direct callers:
  - kernel/rcu/tree.c:rcu_do_batch
  - kernel/rcu/rcu_segcblist.c:rcu_segcblist_merge
```
**Symbols:**

```
ffffffff81157c00-ffffffff81157c9a: rcu_segcblist_insert_done_cbs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void rcu_segcblist_insert_done_cbs(struct rcu_segcblist *rsclp, struct rcu_cblist *rclp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/rcu/rcu_segcblist.c (ffffffff81180f10)
Location: kernel/rcu/rcu_segcblist.c:442
Inline: True
Direct callers:
  - kernel/rcu/tree.c:rcu_do_batch
  - kernel/rcu/rcu_segcblist.c:rcu_segcblist_merge
```
**Symbols:**

```
ffffffff81180f10-ffffffff81180fc2: rcu_segcblist_insert_done_cbs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void rcu_segcblist_insert_done_cbs(struct rcu_segcblist *rsclp, struct rcu_cblist *rclp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/rcu/rcu_segcblist.c (ffffffff811bb840)
Location: kernel/rcu/rcu_segcblist.c:442
Inline: True
Direct callers:
  - kernel/rcu/tree.c:rcu_do_batch
  - kernel/rcu/rcu_segcblist.c:rcu_segcblist_merge
```
**Symbols:**

```
ffffffff811bb840-ffffffff811bb8f2: rcu_segcblist_insert_done_cbs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void rcu_segcblist_insert_done_cbs(struct rcu_segcblist *rsclp, struct rcu_cblist *rclp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/rcu/rcu_segcblist.c (ffffffff811ce1e0)
Location: kernel/rcu/rcu_segcblist.c:442
Inline: True
Direct callers:
  - kernel/rcu/tree.c:rcu_do_batch
  - kernel/rcu/rcu_segcblist.c:rcu_segcblist_merge
```
**Symbols:**

```
ffffffff811ce1e0-ffffffff811ce292: rcu_segcblist_insert_done_cbs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void rcu_segcblist_insert_done_cbs(struct rcu_segcblist *rsclp, struct rcu_cblist *rclp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/rcu/rcu_segcblist.c (ffffffff811e2dd0)
Location: kernel/rcu/rcu_segcblist.c:442
Inline: True
Direct callers:
  - kernel/rcu/tree.c:rcu_do_batch
  - kernel/rcu/rcu_segcblist.c:rcu_segcblist_merge
```
**Symbols:**

```
ffffffff811e2dd0-ffffffff811e2e82: rcu_segcblist_insert_done_cbs (STB_GLOBAL)
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
void rcu_segcblist_insert_done_cbs(struct rcu_segcblist *rsclp, struct rcu_cblist *rclp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/rcu/rcu_segcblist.c (ffff800010193954)
Location: kernel/rcu/rcu_segcblist.c:374
Inline: True
Inline callers:
  - kernel/rcu/rcu_segcblist.c:rcu_segcblist_merge
  - kernel/rcu/rcu_segcblist.c:rcu_segcblist_merge
Direct callers:
  - kernel/rcu/tree.c:rcu_do_batch
```
**Symbols:**

```
ffff800010193638-ffff8000101936a4: rcu_segcblist_insert_done_cbs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void rcu_segcblist_insert_done_cbs(struct rcu_segcblist *rsclp, struct rcu_cblist *rclp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/rcu/rcu_segcblist.c (c03e0c8c)
Location: kernel/rcu/rcu_segcblist.c:374
Inline: True
Inline callers:
  - kernel/rcu/rcu_segcblist.c:rcu_segcblist_merge
  - kernel/rcu/rcu_segcblist.c:rcu_segcblist_merge
Direct callers:
  - kernel/rcu/tree.c:rcu_core
```
**Symbols:**

```
c03e0914-c03e097c: rcu_segcblist_insert_done_cbs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void rcu_segcblist_insert_done_cbs(struct rcu_segcblist *rsclp, struct rcu_cblist *rclp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/rcu/rcu_segcblist.c (c0000000001ee9c4)
Location: kernel/rcu/rcu_segcblist.c:374
Inline: True
Inline callers:
  - kernel/rcu/rcu_segcblist.c:rcu_segcblist_merge
  - kernel/rcu/rcu_segcblist.c:rcu_segcblist_merge
Direct callers:
  - kernel/rcu/tree.c:rcu_core
```
**Symbols:**

```
c0000000001ee670-c0000000001ee6cc: rcu_segcblist_insert_done_cbs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void rcu_segcblist_insert_done_cbs(struct rcu_segcblist *rsclp, struct rcu_cblist *rclp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/rcu/rcu_segcblist.c (ffffffe000125dba)
Location: kernel/rcu/rcu_segcblist.c:374
Inline: True
Inline callers:
  - kernel/rcu/rcu_segcblist.c:rcu_segcblist_merge
  - kernel/rcu/rcu_segcblist.c:rcu_segcblist_merge
Direct callers:
  - kernel/rcu/tree.c:rcu_core
```
**Symbols:**

```
ffffffe000125b60-ffffffe000125bb8: rcu_segcblist_insert_done_cbs (STB_GLOBAL)
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
void rcu_segcblist_insert_done_cbs(struct rcu_segcblist *rsclp, struct rcu_cblist *rclp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/rcu/rcu_segcblist.c (ffffffff81123cc1)
Location: kernel/rcu/rcu_segcblist.c:374
Inline: True
Inline callers:
  - kernel/rcu/rcu_segcblist.c:rcu_segcblist_merge
  - kernel/rcu/rcu_segcblist.c:rcu_segcblist_merge
Direct callers:
  - kernel/rcu/tree.c:rcu_do_batch
```
**Symbols:**

```
ffffffff81123a30-ffffffff81123a7a: rcu_segcblist_insert_done_cbs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void rcu_segcblist_insert_done_cbs(struct rcu_segcblist *rsclp, struct rcu_cblist *rclp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/rcu/rcu_segcblist.c (ffffffff8111671f)
Location: kernel/rcu/rcu_segcblist.c:374
Inline: True
Inline callers:
  - kernel/rcu/rcu_segcblist.c:rcu_segcblist_merge
  - kernel/rcu/rcu_segcblist.c:rcu_segcblist_merge
Direct callers:
  - kernel/rcu/tree.c:rcu_do_batch
```
**Symbols:**

```
ffffffff811164b0-ffffffff811164fa: rcu_segcblist_insert_done_cbs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void rcu_segcblist_insert_done_cbs(struct rcu_segcblist *rsclp, struct rcu_cblist *rclp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/rcu/rcu_segcblist.c (ffffffff81121bb1)
Location: kernel/rcu/rcu_segcblist.c:374
Inline: True
Inline callers:
  - kernel/rcu/rcu_segcblist.c:rcu_segcblist_merge
  - kernel/rcu/rcu_segcblist.c:rcu_segcblist_merge
Direct callers:
  - kernel/rcu/tree.c:rcu_do_batch
```
**Symbols:**

```
ffffffff81121920-ffffffff8112196a: rcu_segcblist_insert_done_cbs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void rcu_segcblist_insert_done_cbs(struct rcu_segcblist *rsclp, struct rcu_cblist *rclp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/rcu/rcu_segcblist.c (ffffffff8112e1c1)
Location: kernel/rcu/rcu_segcblist.c:374
Inline: True
Inline callers:
  - kernel/rcu/rcu_segcblist.c:rcu_segcblist_merge
  - kernel/rcu/rcu_segcblist.c:rcu_segcblist_merge
Direct callers:
  - kernel/rcu/tree.c:rcu_do_batch
```
**Symbols:**

```
ffffffff8112df30-ffffffff8112df7a: rcu_segcblist_insert_done_cbs (STB_GLOBAL)
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
