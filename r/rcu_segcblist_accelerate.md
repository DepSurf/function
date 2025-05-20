# Function: <code>rcu_segcblist_accelerate</code>

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
bool rcu_segcblist_accelerate(struct rcu_segcblist *rsclp, long unsigned int seq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/rcu_segcblist.c (ffffffff810f74b0)
Location: kernel/rcu/rcu_segcblist.c:438
Inline: False
Direct callers:
  - kernel/rcu/srcutree.c:srcu_invoke_callbacks
  - kernel/rcu/srcutree.c:__call_srcu
  - kernel/rcu/srcutree.c:srcu_gp_start
  - kernel/rcu/tree.c:rcu_accelerate_cbs
  - kernel/rcu/tree.c:rcu_accelerate_cbs
```
**Symbols:**

```
ffffffff810f74b0-ffffffff810f7520: rcu_segcblist_accelerate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
bool rcu_segcblist_accelerate(struct rcu_segcblist *rsclp, long unsigned int seq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/rcu_segcblist.c (ffffffff811013b0)
Location: kernel/rcu/rcu_segcblist.c:355
Inline: False
Direct callers:
  - kernel/rcu/srcutree.c:srcu_invoke_callbacks
  - kernel/rcu/srcutree.c:__call_srcu
  - kernel/rcu/srcutree.c:srcu_gp_start
  - kernel/rcu/tree.c:rcu_accelerate_cbs
  - kernel/rcu/tree.c:rcu_accelerate_cbs
```
**Symbols:**

```
ffffffff811013b0-ffffffff81101420: rcu_segcblist_accelerate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
bool rcu_segcblist_accelerate(struct rcu_segcblist *rsclp, long unsigned int seq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/rcu_segcblist.c (ffffffff81109840)
Location: kernel/rcu/rcu_segcblist.c:355
Inline: False
Direct callers:
  - kernel/rcu/srcutree.c:srcu_invoke_callbacks
  - kernel/rcu/srcutree.c:__call_srcu
  - kernel/rcu/srcutree.c:srcu_gp_start
  - kernel/rcu/tree.c:rcu_accelerate_cbs
```
**Symbols:**

```
ffffffff81109840-ffffffff811098a9: rcu_segcblist_accelerate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
bool rcu_segcblist_accelerate(struct rcu_segcblist *rsclp, long unsigned int seq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/rcu_segcblist.c (ffffffff81115010)
Location: kernel/rcu/rcu_segcblist.c:355
Inline: False
Direct callers:
  - kernel/rcu/srcutree.c:srcu_invoke_callbacks
  - kernel/rcu/srcutree.c:__call_srcu
  - kernel/rcu/srcutree.c:srcu_gp_start
  - kernel/rcu/tree.c:rcu_accelerate_cbs_unlocked
  - kernel/rcu/tree.c:rcu_accelerate_cbs
```
**Symbols:**

```
ffffffff81115010-ffffffff81115079: rcu_segcblist_accelerate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
bool rcu_segcblist_accelerate(struct rcu_segcblist *rsclp, long unsigned int seq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/rcu_segcblist.c (ffffffff8111ee40)
Location: kernel/rcu/rcu_segcblist.c:342
Inline: False
Direct callers:
  - kernel/rcu/srcutree.c:srcu_invoke_callbacks
  - kernel/rcu/srcutree.c:__call_srcu
  - kernel/rcu/srcutree.c:srcu_gp_start
  - kernel/rcu/tree.c:rcu_accelerate_cbs_unlocked
  - kernel/rcu/tree.c:rcu_accelerate_cbs
```
**Symbols:**

```
ffffffff8111ee40-ffffffff8111eea9: rcu_segcblist_accelerate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
bool rcu_segcblist_accelerate(struct rcu_segcblist *rsclp, long unsigned int seq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/rcu_segcblist.c (ffffffff8112b540)
Location: kernel/rcu/rcu_segcblist.c:466
Inline: False
Direct callers:
  - kernel/rcu/srcutree.c:srcu_invoke_callbacks
  - kernel/rcu/srcutree.c:__call_srcu
  - kernel/rcu/srcutree.c:srcu_gp_start
  - kernel/rcu/tree.c:rcu_accelerate_cbs_unlocked
  - kernel/rcu/tree.c:rcu_accelerate_cbs
```
**Symbols:**

```
ffffffff8112b540-ffffffff8112b5bb: rcu_segcblist_accelerate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
bool rcu_segcblist_accelerate(struct rcu_segcblist *rsclp, long unsigned int seq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/rcu_segcblist.c (ffffffff81139a90)
Location: kernel/rcu/rcu_segcblist.c:445
Inline: False
Direct callers:
  - kernel/rcu/srcutree.c:srcu_invoke_callbacks
  - kernel/rcu/srcutree.c:__call_srcu
  - kernel/rcu/srcutree.c:srcu_gp_start
  - kernel/rcu/tree.c:rcu_accelerate_cbs_unlocked
  - kernel/rcu/tree.c:rcu_accelerate_cbs
```
**Symbols:**

```
ffffffff81139a90-ffffffff81139afd: rcu_segcblist_accelerate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
bool rcu_segcblist_accelerate(struct rcu_segcblist *rsclp, long unsigned int seq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/rcu_segcblist.c (ffffffff81134560)
Location: kernel/rcu/rcu_segcblist.c:445
Inline: False
Direct callers:
  - kernel/rcu/srcutree.c:srcu_invoke_callbacks
  - kernel/rcu/srcutree.c:__call_srcu
  - kernel/rcu/srcutree.c:srcu_gp_start
  - kernel/rcu/tree.c:rcu_accelerate_cbs_unlocked
  - kernel/rcu/tree.c:rcu_accelerate_cbs
```
**Symbols:**

```
ffffffff81134560-ffffffff811345eb: rcu_segcblist_accelerate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
bool rcu_segcblist_accelerate(struct rcu_segcblist *rsclp, long unsigned int seq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/rcu_segcblist.c (ffffffff81135400)
Location: kernel/rcu/rcu_segcblist.c:539
Inline: False
Direct callers:
  - kernel/rcu/srcutree.c:srcu_invoke_callbacks
  - kernel/rcu/srcutree.c:srcu_gp_start_if_needed
  - kernel/rcu/srcutree.c:srcu_gp_start
  - kernel/rcu/tree.c:rcu_accelerate_cbs_unlocked
  - kernel/rcu/tree.c:rcu_accelerate_cbs
```
**Symbols:**

```
ffffffff81135400-ffffffff811354e3: rcu_segcblist_accelerate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
bool rcu_segcblist_accelerate(struct rcu_segcblist *rsclp, long unsigned int seq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/rcu_segcblist.c (ffffffff81157da0)
Location: kernel/rcu/rcu_segcblist.c:539
Inline: False
Direct callers:
  - kernel/rcu/srcutree.c:srcu_invoke_callbacks
  - kernel/rcu/srcutree.c:srcu_gp_start_if_needed
  - kernel/rcu/srcutree.c:srcu_gp_start
  - kernel/rcu/tree.c:rcu_accelerate_cbs_unlocked
  - kernel/rcu/tree.c:rcu_accelerate_cbs
```
**Symbols:**

```
ffffffff81157da0-ffffffff81157fc9: rcu_segcblist_accelerate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
bool rcu_segcblist_accelerate(struct rcu_segcblist *rsclp, long unsigned int seq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/rcu_segcblist.c (ffffffff811810f0)
Location: kernel/rcu/rcu_segcblist.c:537
Inline: False
Direct callers:
  - kernel/rcu/update.c:rcu_tasks_invoke_cbs
  - kernel/rcu/update.c:rcu_tasks_need_gpcb
  - kernel/rcu/srcutree.c:srcu_invoke_callbacks
  - kernel/rcu/srcutree.c:srcu_gp_start_if_needed
  - kernel/rcu/srcutree.c:srcu_gp_start
  - kernel/rcu/tree.c:rcu_accelerate_cbs_unlocked
  - kernel/rcu/tree.c:rcu_accelerate_cbs
```
**Symbols:**

```
ffffffff811810f0-ffffffff811812fd: rcu_segcblist_accelerate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
bool rcu_segcblist_accelerate(struct rcu_segcblist *rsclp, long unsigned int seq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/rcu_segcblist.c (ffffffff811bba50)
Location: kernel/rcu/rcu_segcblist.c:537
Inline: False
Direct callers:
  - kernel/rcu/update.c:rcu_tasks_invoke_cbs
  - kernel/rcu/update.c:rcu_tasks_need_gpcb
  - kernel/rcu/srcutree.c:srcu_invoke_callbacks
  - kernel/rcu/srcutree.c:srcu_gp_start_if_needed
  - kernel/rcu/srcutree.c:srcu_gp_start
  - kernel/rcu/tree.c:rcu_accelerate_cbs_unlocked
  - kernel/rcu/tree.c:rcu_accelerate_cbs
```
**Symbols:**

```
ffffffff811bba50-ffffffff811bbc5d: rcu_segcblist_accelerate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
bool rcu_segcblist_accelerate(struct rcu_segcblist *rsclp, long unsigned int seq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/rcu_segcblist.c (ffffffff811ce3f0)
Location: kernel/rcu/rcu_segcblist.c:537
Inline: False
Direct callers:
  - kernel/rcu/update.c:rcu_tasks_invoke_cbs
  - kernel/rcu/update.c:rcu_tasks_need_gpcb
  - kernel/rcu/srcutree.c:srcu_invoke_callbacks
  - kernel/rcu/srcutree.c:srcu_gp_start_if_needed
  - kernel/rcu/srcutree.c:srcu_gp_start
  - kernel/rcu/tree.c:rcu_accelerate_cbs_unlocked
  - kernel/rcu/tree.c:rcu_accelerate_cbs
```
**Symbols:**

```
ffffffff811ce3f0-ffffffff811ce5fd: rcu_segcblist_accelerate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
bool rcu_segcblist_accelerate(struct rcu_segcblist *rsclp, long unsigned int seq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/rcu_segcblist.c (ffffffff811e2fe0)
Location: kernel/rcu/rcu_segcblist.c:537
Inline: False
Direct callers:
  - kernel/rcu/update.c:rcu_tasks_invoke_cbs
  - kernel/rcu/update.c:rcu_tasks_need_gpcb
  - kernel/rcu/srcutree.c:srcu_gp_start_if_needed
  - kernel/rcu/tree.c:rcu_accelerate_cbs_unlocked
  - kernel/rcu/tree.c:rcu_accelerate_cbs
```
**Symbols:**

```
ffffffff811e2fe0-ffffffff811e31f5: rcu_segcblist_accelerate (STB_GLOBAL)
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
bool rcu_segcblist_accelerate(struct rcu_segcblist *rsclp, long unsigned int seq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/rcu_segcblist.c (ffff800010193798)
Location: kernel/rcu/rcu_segcblist.c:466
Inline: False
Direct callers:
  - kernel/rcu/srcutree.c:srcu_invoke_callbacks
  - kernel/rcu/srcutree.c:__call_srcu
  - kernel/rcu/srcutree.c:srcu_gp_start
  - kernel/rcu/tree.c:rcu_accelerate_cbs_unlocked
  - kernel/rcu/tree.c:rcu_accelerate_cbs
```
**Symbols:**

```
ffff800010193798-ffff800010193848: rcu_segcblist_accelerate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
bool rcu_segcblist_accelerate(struct rcu_segcblist *rsclp, long unsigned int seq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/rcu_segcblist.c (c03e0a8c)
Location: kernel/rcu/rcu_segcblist.c:466
Inline: False
Direct callers:
  - kernel/rcu/srcutree.c:srcu_invoke_callbacks
  - kernel/rcu/srcutree.c:__call_srcu
  - kernel/rcu/srcutree.c:srcu_gp_start
  - kernel/rcu/tree.c:rcu_accelerate_cbs_unlocked
  - kernel/rcu/tree.c:rcu_accelerate_cbs
```
**Symbols:**

```
c03e0a8c-c03e0b6c: rcu_segcblist_accelerate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
bool rcu_segcblist_accelerate(struct rcu_segcblist *rsclp, long unsigned int seq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/rcu_segcblist.c (c0000000001ee7c0)
Location: kernel/rcu/rcu_segcblist.c:466
Inline: False
Direct callers:
  - kernel/rcu/srcutree.c:srcu_invoke_callbacks
  - kernel/rcu/srcutree.c:__call_srcu
  - kernel/rcu/srcutree.c:srcu_gp_start
  - kernel/rcu/tree.c:rcu_accelerate_cbs_unlocked
  - kernel/rcu/tree.c:rcu_accelerate_cbs
```
**Symbols:**

```
c0000000001ee7c0-c0000000001ee878: rcu_segcblist_accelerate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
bool rcu_segcblist_accelerate(struct rcu_segcblist *rsclp, long unsigned int seq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/rcu_segcblist.c (ffffffe000125c6a)
Location: kernel/rcu/rcu_segcblist.c:466
Inline: False
Direct callers:
  - kernel/rcu/srcutree.c:srcu_invoke_callbacks
  - kernel/rcu/srcutree.c:__call_srcu
  - kernel/rcu/srcutree.c:srcu_gp_start
  - kernel/rcu/tree.c:rcu_accelerate_cbs_unlocked
  - kernel/rcu/tree.c:rcu_accelerate_cbs
```
**Symbols:**

```
ffffffe000125c6a-ffffffe000125cee: rcu_segcblist_accelerate (STB_GLOBAL)
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
bool rcu_segcblist_accelerate(struct rcu_segcblist *rsclp, long unsigned int seq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/rcu_segcblist.c (ffffffff81123b20)
Location: kernel/rcu/rcu_segcblist.c:466
Inline: False
Direct callers:
  - kernel/rcu/srcutree.c:srcu_invoke_callbacks
  - kernel/rcu/srcutree.c:__call_srcu
  - kernel/rcu/srcutree.c:srcu_gp_start
  - kernel/rcu/tree.c:rcu_accelerate_cbs_unlocked
  - kernel/rcu/tree.c:rcu_accelerate_cbs
```
**Symbols:**

```
ffffffff81123b20-ffffffff81123b9b: rcu_segcblist_accelerate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
bool rcu_segcblist_accelerate(struct rcu_segcblist *rsclp, long unsigned int seq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/rcu_segcblist.c (ffffffff811165a0)
Location: kernel/rcu/rcu_segcblist.c:466
Inline: False
Direct callers:
  - kernel/rcu/srcutree.c:srcu_invoke_callbacks
  - kernel/rcu/srcutree.c:__call_srcu
  - kernel/rcu/srcutree.c:srcu_gp_start
  - kernel/rcu/tree.c:rcu_accelerate_cbs_unlocked
  - kernel/rcu/tree.c:rcu_accelerate_cbs
```
**Symbols:**

```
ffffffff811165a0-ffffffff8111661b: rcu_segcblist_accelerate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
bool rcu_segcblist_accelerate(struct rcu_segcblist *rsclp, long unsigned int seq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/rcu_segcblist.c (ffffffff81121a10)
Location: kernel/rcu/rcu_segcblist.c:466
Inline: False
Direct callers:
  - kernel/rcu/srcutree.c:srcu_invoke_callbacks
  - kernel/rcu/srcutree.c:__call_srcu
  - kernel/rcu/srcutree.c:srcu_gp_start
  - kernel/rcu/tree.c:rcu_accelerate_cbs_unlocked
  - kernel/rcu/tree.c:rcu_accelerate_cbs
```
**Symbols:**

```
ffffffff81121a10-ffffffff81121a8b: rcu_segcblist_accelerate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
bool rcu_segcblist_accelerate(struct rcu_segcblist *rsclp, long unsigned int seq);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/rcu_segcblist.c (ffffffff8112e020)
Location: kernel/rcu/rcu_segcblist.c:466
Inline: False
Direct callers:
  - kernel/rcu/srcutree.c:srcu_invoke_callbacks
  - kernel/rcu/srcutree.c:__call_srcu
  - kernel/rcu/srcutree.c:srcu_gp_start
  - kernel/rcu/tree.c:rcu_accelerate_cbs_unlocked
  - kernel/rcu/tree.c:rcu_accelerate_cbs
```
**Symbols:**

```
ffffffff8112e020-ffffffff8112e09b: rcu_segcblist_accelerate (STB_GLOBAL)
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
