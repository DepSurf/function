# Function: <code>rcu_segcblist_extract_done_cbs</code>

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
void rcu_segcblist_extract_done_cbs(struct rcu_segcblist *rsclp, struct rcu_cblist *rclp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/rcu_segcblist.c (ffffffff810f72f0)
Location: kernel/rcu/rcu_segcblist.c:291
Inline: False
Direct callers:
  - kernel/rcu/srcutree.c:srcu_invoke_callbacks
  - kernel/rcu/tree.c:rcutree_dead_cpu
  - kernel/rcu/tree.c:rcu_process_callbacks
```
**Symbols:**

```
ffffffff810f72f0-ffffffff810f7346: rcu_segcblist_extract_done_cbs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void rcu_segcblist_extract_done_cbs(struct rcu_segcblist *rsclp, struct rcu_cblist *rclp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/rcu/rcu_segcblist.c (ffffffff8110149f)
Location: kernel/rcu/rcu_segcblist.c:208
Inline: True
Inline callers:
  - kernel/rcu/rcu_segcblist.c:rcu_segcblist_merge
Direct callers:
  - kernel/rcu/srcutree.c:srcu_invoke_callbacks
  - kernel/rcu/tree.c:rcu_process_callbacks
```
**Symbols:**

```
ffffffff811011f0-ffffffff81101246: rcu_segcblist_extract_done_cbs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void rcu_segcblist_extract_done_cbs(struct rcu_segcblist *rsclp, struct rcu_cblist *rclp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/rcu/rcu_segcblist.c (ffffffff8110992c)
Location: kernel/rcu/rcu_segcblist.c:208
Inline: True
Inline callers:
  - kernel/rcu/rcu_segcblist.c:rcu_segcblist_merge
Direct callers:
  - kernel/rcu/srcutree.c:srcu_invoke_callbacks
  - kernel/rcu/tree.c:rcu_process_callbacks
```
**Symbols:**

```
ffffffff81109680-ffffffff811096d6: rcu_segcblist_extract_done_cbs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void rcu_segcblist_extract_done_cbs(struct rcu_segcblist *rsclp, struct rcu_cblist *rclp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/rcu/rcu_segcblist.c (ffffffff811150fc)
Location: kernel/rcu/rcu_segcblist.c:208
Inline: True
Inline callers:
  - kernel/rcu/rcu_segcblist.c:rcu_segcblist_merge
  - kernel/rcu/rcu_segcblist.c:rcu_segcblist_merge
Direct callers:
  - kernel/rcu/srcutree.c:srcu_invoke_callbacks
  - kernel/rcu/tree.c:rcu_process_callbacks
```
**Symbols:**

```
ffffffff81114e50-ffffffff81114ea6: rcu_segcblist_extract_done_cbs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void rcu_segcblist_extract_done_cbs(struct rcu_segcblist *rsclp, struct rcu_cblist *rclp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/rcu/rcu_segcblist.c (ffffffff8111ef2c)
Location: kernel/rcu/rcu_segcblist.c:195
Inline: True
Inline callers:
  - kernel/rcu/rcu_segcblist.c:rcu_segcblist_merge
  - kernel/rcu/rcu_segcblist.c:rcu_segcblist_merge
Direct callers:
  - kernel/rcu/srcutree.c:srcu_invoke_callbacks
  - kernel/rcu/tree.c:rcu_core
```
**Symbols:**

```
ffffffff8111ec80-ffffffff8111ecd6: rcu_segcblist_extract_done_cbs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void rcu_segcblist_extract_done_cbs(struct rcu_segcblist *rsclp, struct rcu_cblist *rclp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/rcu/rcu_segcblist.c (ffffffff8112b64f)
Location: kernel/rcu/rcu_segcblist.c:320
Inline: True
Inline callers:
  - kernel/rcu/rcu_segcblist.c:rcu_segcblist_merge
  - kernel/rcu/rcu_segcblist.c:rcu_segcblist_merge
Direct callers:
  - kernel/rcu/srcutree.c:srcu_invoke_callbacks
  - kernel/rcu/tree.c:rcu_do_batch
```
**Symbols:**

```
ffffffff8112b360-ffffffff8112b3b5: rcu_segcblist_extract_done_cbs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void rcu_segcblist_extract_done_cbs(struct rcu_segcblist *rsclp, struct rcu_cblist *rclp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/rcu/rcu_segcblist.c (ffffffff811398c0)
Location: kernel/rcu/rcu_segcblist.c:303
Inline: True
Direct callers:
  - kernel/rcu/srcutree.c:srcu_invoke_callbacks
  - kernel/rcu/tree.c:rcu_do_batch
  - kernel/rcu/rcu_segcblist.c:rcu_segcblist_merge
```
**Symbols:**

```
ffffffff811398c0-ffffffff8113991d: rcu_segcblist_extract_done_cbs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void rcu_segcblist_extract_done_cbs(struct rcu_segcblist *rsclp, struct rcu_cblist *rclp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/rcu/rcu_segcblist.c (ffffffff81134390)
Location: kernel/rcu/rcu_segcblist.c:303
Inline: True
Direct callers:
  - kernel/rcu/srcutree.c:srcu_invoke_callbacks
  - kernel/rcu/tree.c:rcu_do_batch
  - kernel/rcu/rcu_segcblist.c:rcu_segcblist_merge
```
**Symbols:**

```
ffffffff81134390-ffffffff811343ed: rcu_segcblist_extract_done_cbs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void rcu_segcblist_extract_done_cbs(struct rcu_segcblist *rsclp, struct rcu_cblist *rclp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/rcu/rcu_segcblist.c (ffffffff81135190)
Location: kernel/rcu/rcu_segcblist.c:387
Inline: True
Direct callers:
  - kernel/rcu/srcutree.c:srcu_invoke_callbacks
  - kernel/rcu/tree.c:rcu_do_batch
  - kernel/rcu/rcu_segcblist.c:rcu_segcblist_merge
```
**Symbols:**

```
ffffffff81135190-ffffffff811351ff: rcu_segcblist_extract_done_cbs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void rcu_segcblist_extract_done_cbs(struct rcu_segcblist *rsclp, struct rcu_cblist *rclp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/rcu/rcu_segcblist.c (ffffffff81157a30)
Location: kernel/rcu/rcu_segcblist.c:387
Inline: True
Direct callers:
  - kernel/rcu/srcutree.c:srcu_invoke_callbacks
  - kernel/rcu/tree.c:rcu_do_batch
  - kernel/rcu/rcu_segcblist.c:rcu_segcblist_merge
```
**Symbols:**

```
ffffffff81157a30-ffffffff81157ae1: rcu_segcblist_extract_done_cbs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void rcu_segcblist_extract_done_cbs(struct rcu_segcblist *rsclp, struct rcu_cblist *rclp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/rcu/rcu_segcblist.c (ffffffff81180d10)
Location: kernel/rcu/rcu_segcblist.c:385
Inline: True
Direct callers:
  - kernel/rcu/update.c:rcu_tasks_invoke_cbs
  - kernel/rcu/srcutree.c:srcu_invoke_callbacks
  - kernel/rcu/tree.c:rcu_do_batch
  - kernel/rcu/rcu_segcblist.c:rcu_segcblist_merge
```
**Symbols:**

```
ffffffff81180d10-ffffffff81180dd9: rcu_segcblist_extract_done_cbs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void rcu_segcblist_extract_done_cbs(struct rcu_segcblist *rsclp, struct rcu_cblist *rclp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/rcu/rcu_segcblist.c (ffffffff811bb610)
Location: kernel/rcu/rcu_segcblist.c:385
Inline: True
Direct callers:
  - kernel/rcu/update.c:rcu_tasks_invoke_cbs
  - kernel/rcu/srcutree.c:srcu_invoke_callbacks
  - kernel/rcu/tree.c:rcu_do_batch
  - kernel/rcu/rcu_segcblist.c:rcu_segcblist_merge
```
**Symbols:**

```
ffffffff811bb610-ffffffff811bb6d9: rcu_segcblist_extract_done_cbs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void rcu_segcblist_extract_done_cbs(struct rcu_segcblist *rsclp, struct rcu_cblist *rclp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/rcu/rcu_segcblist.c (ffffffff811cdfb0)
Location: kernel/rcu/rcu_segcblist.c:385
Inline: True
Direct callers:
  - kernel/rcu/update.c:rcu_tasks_invoke_cbs
  - kernel/rcu/srcutree.c:srcu_invoke_callbacks
  - kernel/rcu/tree.c:rcu_do_batch
  - kernel/rcu/rcu_segcblist.c:rcu_segcblist_merge
```
**Symbols:**

```
ffffffff811cdfb0-ffffffff811ce079: rcu_segcblist_extract_done_cbs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void rcu_segcblist_extract_done_cbs(struct rcu_segcblist *rsclp, struct rcu_cblist *rclp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/rcu/rcu_segcblist.c (ffffffff811e2bb0)
Location: kernel/rcu/rcu_segcblist.c:385
Inline: True
Direct callers:
  - kernel/rcu/update.c:rcu_tasks_invoke_cbs
  - kernel/rcu/srcutree.c:srcu_invoke_callbacks
  - kernel/rcu/tree.c:rcu_do_batch
  - kernel/rcu/rcu_segcblist.c:rcu_segcblist_merge
```
**Symbols:**

```
ffffffff811e2bb0-ffffffff811e2c79: rcu_segcblist_extract_done_cbs (STB_GLOBAL)
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
void rcu_segcblist_extract_done_cbs(struct rcu_segcblist *rsclp, struct rcu_cblist *rclp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/rcu/rcu_segcblist.c (ffff8000101938ac)
Location: kernel/rcu/rcu_segcblist.c:320
Inline: True
Inline callers:
  - kernel/rcu/rcu_segcblist.c:rcu_segcblist_merge
  - kernel/rcu/rcu_segcblist.c:rcu_segcblist_merge
Direct callers:
  - kernel/rcu/srcutree.c:srcu_invoke_callbacks
  - kernel/rcu/tree.c:rcu_do_batch
```
**Symbols:**

```
ffff8000101934e8-ffff800010193570: rcu_segcblist_extract_done_cbs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void rcu_segcblist_extract_done_cbs(struct rcu_segcblist *rsclp, struct rcu_cblist *rclp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/rcu/rcu_segcblist.c (c03e0bec)
Location: kernel/rcu/rcu_segcblist.c:320
Inline: True
Inline callers:
  - kernel/rcu/rcu_segcblist.c:rcu_segcblist_merge
  - kernel/rcu/rcu_segcblist.c:rcu_segcblist_merge
Direct callers:
  - kernel/rcu/srcutree.c:srcu_invoke_callbacks
  - kernel/rcu/tree.c:rcu_core
```
**Symbols:**

```
c03e07e4-c03e0860: rcu_segcblist_extract_done_cbs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void rcu_segcblist_extract_done_cbs(struct rcu_segcblist *rsclp, struct rcu_cblist *rclp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/rcu/rcu_segcblist.c (c0000000001ee908)
Location: kernel/rcu/rcu_segcblist.c:320
Inline: True
Inline callers:
  - kernel/rcu/rcu_segcblist.c:rcu_segcblist_merge
  - kernel/rcu/rcu_segcblist.c:rcu_segcblist_merge
Direct callers:
  - kernel/rcu/srcutree.c:srcu_invoke_callbacks
  - kernel/rcu/tree.c:rcu_core
```
**Symbols:**

```
c0000000001ee550-c0000000001ee5cc: rcu_segcblist_extract_done_cbs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void rcu_segcblist_extract_done_cbs(struct rcu_segcblist *rsclp, struct rcu_cblist *rclp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/rcu/rcu_segcblist.c (ffffffe000125d44)
Location: kernel/rcu/rcu_segcblist.c:320
Inline: True
Inline callers:
  - kernel/rcu/rcu_segcblist.c:rcu_segcblist_merge
  - kernel/rcu/rcu_segcblist.c:rcu_segcblist_merge
Direct callers:
  - kernel/rcu/srcutree.c:srcu_invoke_callbacks
  - kernel/rcu/tree.c:rcu_core
```
**Symbols:**

```
ffffffe000125a62-ffffffe000125ac2: rcu_segcblist_extract_done_cbs (STB_GLOBAL)
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
void rcu_segcblist_extract_done_cbs(struct rcu_segcblist *rsclp, struct rcu_cblist *rclp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/rcu/rcu_segcblist.c (ffffffff81123c2f)
Location: kernel/rcu/rcu_segcblist.c:320
Inline: True
Inline callers:
  - kernel/rcu/rcu_segcblist.c:rcu_segcblist_merge
  - kernel/rcu/rcu_segcblist.c:rcu_segcblist_merge
Direct callers:
  - kernel/rcu/srcutree.c:srcu_invoke_callbacks
  - kernel/rcu/tree.c:rcu_do_batch
```
**Symbols:**

```
ffffffff81123940-ffffffff81123995: rcu_segcblist_extract_done_cbs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void rcu_segcblist_extract_done_cbs(struct rcu_segcblist *rsclp, struct rcu_cblist *rclp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/rcu/rcu_segcblist.c (ffffffff8111669d)
Location: kernel/rcu/rcu_segcblist.c:320
Inline: True
Inline callers:
  - kernel/rcu/rcu_segcblist.c:rcu_segcblist_merge
  - kernel/rcu/rcu_segcblist.c:rcu_segcblist_merge
Direct callers:
  - kernel/rcu/srcutree.c:srcu_invoke_callbacks
  - kernel/rcu/tree.c:rcu_do_batch
```
**Symbols:**

```
ffffffff811163d0-ffffffff81116425: rcu_segcblist_extract_done_cbs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void rcu_segcblist_extract_done_cbs(struct rcu_segcblist *rsclp, struct rcu_cblist *rclp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/rcu/rcu_segcblist.c (ffffffff81121b1f)
Location: kernel/rcu/rcu_segcblist.c:320
Inline: True
Inline callers:
  - kernel/rcu/rcu_segcblist.c:rcu_segcblist_merge
  - kernel/rcu/rcu_segcblist.c:rcu_segcblist_merge
Direct callers:
  - kernel/rcu/srcutree.c:srcu_invoke_callbacks
  - kernel/rcu/tree.c:rcu_do_batch
```
**Symbols:**

```
ffffffff81121830-ffffffff81121885: rcu_segcblist_extract_done_cbs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void rcu_segcblist_extract_done_cbs(struct rcu_segcblist *rsclp, struct rcu_cblist *rclp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/rcu/rcu_segcblist.c (ffffffff8112e12f)
Location: kernel/rcu/rcu_segcblist.c:320
Inline: True
Inline callers:
  - kernel/rcu/rcu_segcblist.c:rcu_segcblist_merge
  - kernel/rcu/rcu_segcblist.c:rcu_segcblist_merge
Direct callers:
  - kernel/rcu/srcutree.c:srcu_invoke_callbacks
  - kernel/rcu/tree.c:rcu_do_batch
```
**Symbols:**

```
ffffffff8112de40-ffffffff8112de95: rcu_segcblist_extract_done_cbs (STB_GLOBAL)
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
