# Function: <code>rcu_cblist_init</code>

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
void rcu_cblist_init(struct rcu_cblist *rclp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/rcu_segcblist.c (ffffffff810f6f30)
Location: kernel/rcu/rcu_segcblist.c:30
Inline: False
Direct callers:
  - kernel/rcu/srcutree.c:srcu_invoke_callbacks
```
**Symbols:**

```
ffffffff810f6f30-ffffffff810f6f56: rcu_cblist_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void rcu_cblist_init(struct rcu_cblist *rclp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/rcu/rcu_segcblist.c (ffffffff81101471)
Location: kernel/rcu/rcu_segcblist.c:31
Inline: True
Inline callers:
  - kernel/rcu/rcu_segcblist.c:rcu_segcblist_merge
  - kernel/rcu/rcu_segcblist.c:rcu_segcblist_merge
Direct callers:
  - kernel/rcu/srcutree.c:srcu_invoke_callbacks
```
**Symbols:**

```
ffffffff81100f90-ffffffff81100fb6: rcu_cblist_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void rcu_cblist_init(struct rcu_cblist *rclp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/rcu/rcu_segcblist.c (ffffffff811098df)
Location: kernel/rcu/rcu_segcblist.c:31
Inline: True
Inline callers:
  - kernel/rcu/rcu_segcblist.c:rcu_segcblist_merge
  - kernel/rcu/rcu_segcblist.c:rcu_segcblist_merge
Direct callers:
  - kernel/rcu/srcutree.c:srcu_invoke_callbacks
```
**Symbols:**

```
ffffffff81109420-ffffffff81109446: rcu_cblist_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void rcu_cblist_init(struct rcu_cblist *rclp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/rcu/rcu_segcblist.c (ffffffff811150af)
Location: kernel/rcu/rcu_segcblist.c:31
Inline: True
Inline callers:
  - kernel/rcu/rcu_segcblist.c:rcu_segcblist_merge
  - kernel/rcu/rcu_segcblist.c:rcu_segcblist_merge
Direct callers:
  - kernel/rcu/srcutree.c:srcu_invoke_callbacks
```
**Symbols:**

```
ffffffff81114bf0-ffffffff81114c16: rcu_cblist_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void rcu_cblist_init(struct rcu_cblist *rclp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/rcu/rcu_segcblist.c (ffffffff8111eedf)
Location: kernel/rcu/rcu_segcblist.c:18
Inline: True
Inline callers:
  - kernel/rcu/rcu_segcblist.c:rcu_segcblist_merge
  - kernel/rcu/rcu_segcblist.c:rcu_segcblist_merge
Direct callers:
  - kernel/rcu/srcutree.c:srcu_invoke_callbacks
```
**Symbols:**

```
ffffffff8111ea10-ffffffff8111ea36: rcu_cblist_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void rcu_cblist_init(struct rcu_cblist *rclp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/rcu/rcu_segcblist.c (ffffffff8112b5ef)
Location: kernel/rcu/rcu_segcblist.c:18
Inline: True
Inline callers:
  - kernel/rcu/rcu_segcblist.c:rcu_segcblist_merge
  - kernel/rcu/rcu_segcblist.c:rcu_segcblist_merge
  - kernel/rcu/rcu_segcblist.c:rcu_cblist_flush_enqueue
Direct callers:
  - kernel/rcu/srcutree.c:srcu_invoke_callbacks
```
**Symbols:**

```
ffffffff8112af40-ffffffff8112af66: rcu_cblist_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void rcu_cblist_init(struct rcu_cblist *rclp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/rcu/rcu_segcblist.c (ffffffff81139b49)
Location: kernel/rcu/rcu_segcblist.c:18
Inline: True
Inline callers:
  - kernel/rcu/rcu_segcblist.c:rcu_segcblist_merge
  - kernel/rcu/rcu_segcblist.c:rcu_segcblist_merge
  - kernel/rcu/rcu_segcblist.c:rcu_cblist_flush_enqueue
Direct callers:
  - kernel/rcu/srcutree.c:srcu_invoke_callbacks
```
**Symbols:**

```
ffffffff81139580-ffffffff8113959e: rcu_cblist_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void rcu_cblist_init(struct rcu_cblist *rclp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/rcu/rcu_segcblist.c (ffffffff81134639)
Location: kernel/rcu/rcu_segcblist.c:18
Inline: True
Inline callers:
  - kernel/rcu/rcu_segcblist.c:rcu_segcblist_merge
  - kernel/rcu/rcu_segcblist.c:rcu_segcblist_merge
  - kernel/rcu/rcu_segcblist.c:rcu_cblist_flush_enqueue
Direct callers:
  - kernel/rcu/srcutree.c:srcu_invoke_callbacks
```
**Symbols:**

```
ffffffff81134050-ffffffff8113406e: rcu_cblist_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void rcu_cblist_init(struct rcu_cblist *rclp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/rcu/rcu_segcblist.c (ffffffff81135540)
Location: kernel/rcu/rcu_segcblist.c:18
Inline: True
Inline callers:
  - kernel/rcu/rcu_segcblist.c:rcu_segcblist_merge
  - kernel/rcu/rcu_segcblist.c:rcu_segcblist_merge
  - kernel/rcu/rcu_segcblist.c:rcu_cblist_flush_enqueue
Direct callers:
  - kernel/rcu/srcutree.c:srcu_invoke_callbacks
```
**Symbols:**

```
ffffffff81134dc0-ffffffff81134dde: rcu_cblist_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void rcu_cblist_init(struct rcu_cblist *rclp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/rcu/rcu_segcblist.c (ffffffff81158020)
Location: kernel/rcu/rcu_segcblist.c:18
Inline: True
Inline callers:
  - kernel/rcu/rcu_segcblist.c:rcu_segcblist_merge
  - kernel/rcu/rcu_segcblist.c:rcu_segcblist_merge
  - kernel/rcu/rcu_segcblist.c:rcu_cblist_flush_enqueue
Direct callers:
  - kernel/rcu/srcutree.c:srcu_invoke_callbacks
```
**Symbols:**

```
ffffffff811575c0-ffffffff811575de: rcu_cblist_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void rcu_cblist_init(struct rcu_cblist *rclp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/rcu/rcu_segcblist.c (ffffffff81181366)
Location: kernel/rcu/rcu_segcblist.c:18
Inline: True
Inline callers:
  - kernel/rcu/rcu_segcblist.c:rcu_segcblist_merge
  - kernel/rcu/rcu_segcblist.c:rcu_segcblist_merge
  - kernel/rcu/rcu_segcblist.c:rcu_cblist_flush_enqueue
Direct callers:
  - kernel/rcu/srcutree.c:srcu_invoke_callbacks
```
**Symbols:**

```
ffffffff811807c0-ffffffff811807e4: rcu_cblist_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void rcu_cblist_init(struct rcu_cblist *rclp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/rcu/rcu_segcblist.c (ffffffff811bbcd6)
Location: kernel/rcu/rcu_segcblist.c:18
Inline: True
Inline callers:
  - kernel/rcu/rcu_segcblist.c:rcu_segcblist_merge
  - kernel/rcu/rcu_segcblist.c:rcu_segcblist_merge
  - kernel/rcu/rcu_segcblist.c:rcu_cblist_flush_enqueue
Direct callers:
  - kernel/rcu/srcutree.c:srcu_invoke_callbacks
```
**Symbols:**

```
ffffffff811bafb0-ffffffff811bafd4: rcu_cblist_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void rcu_cblist_init(struct rcu_cblist *rclp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/rcu/rcu_segcblist.c (ffffffff811ce676)
Location: kernel/rcu/rcu_segcblist.c:18
Inline: True
Inline callers:
  - kernel/rcu/rcu_segcblist.c:rcu_segcblist_merge
  - kernel/rcu/rcu_segcblist.c:rcu_segcblist_merge
  - kernel/rcu/rcu_segcblist.c:rcu_cblist_flush_enqueue
Direct callers:
  - kernel/rcu/srcutree.c:srcu_invoke_callbacks
```
**Symbols:**

```
ffffffff811cd8f0-ffffffff811cd914: rcu_cblist_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void rcu_cblist_init(struct rcu_cblist *rclp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/rcu/rcu_segcblist.c (ffffffff811e3276)
Location: kernel/rcu/rcu_segcblist.c:18
Inline: True
Inline callers:
  - kernel/rcu/rcu_segcblist.c:rcu_segcblist_merge
  - kernel/rcu/rcu_segcblist.c:rcu_segcblist_merge
  - kernel/rcu/rcu_segcblist.c:rcu_cblist_flush_enqueue
Direct callers:
  - kernel/rcu/srcutree.c:srcu_invoke_callbacks
  - kernel/rcu/tree.c:rcu_init_one
```
**Symbols:**

```
ffffffff811e2530-ffffffff811e2554: rcu_cblist_init (STB_GLOBAL)
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
void rcu_cblist_init(struct rcu_cblist *rclp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/rcu/rcu_segcblist.c (ffff800010193878)
Location: kernel/rcu/rcu_segcblist.c:18
Inline: True
Inline callers:
  - kernel/rcu/rcu_segcblist.c:rcu_segcblist_merge
  - kernel/rcu/rcu_segcblist.c:rcu_segcblist_merge
  - kernel/rcu/rcu_segcblist.c:rcu_cblist_flush_enqueue
Direct callers:
  - kernel/rcu/srcutree.c:srcu_invoke_callbacks
```
**Symbols:**

```
ffff800010192eb0-ffff800010192edc: rcu_cblist_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void rcu_cblist_init(struct rcu_cblist *rclp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/rcu/rcu_segcblist.c (c03e0ba0)
Location: kernel/rcu/rcu_segcblist.c:18
Inline: True
Inline callers:
  - kernel/rcu/rcu_segcblist.c:rcu_segcblist_merge
  - kernel/rcu/rcu_segcblist.c:rcu_segcblist_merge
  - kernel/rcu/rcu_segcblist.c:rcu_cblist_flush_enqueue
Direct callers:
  - kernel/rcu/srcutree.c:srcu_invoke_callbacks
```
**Symbols:**

```
c03e0298-c03e02c4: rcu_cblist_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void rcu_cblist_init(struct rcu_cblist *rclp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/rcu/rcu_segcblist.c (c0000000001ee8b8)
Location: kernel/rcu/rcu_segcblist.c:18
Inline: True
Inline callers:
  - kernel/rcu/rcu_segcblist.c:rcu_segcblist_merge
  - kernel/rcu/rcu_segcblist.c:rcu_segcblist_merge
  - kernel/rcu/rcu_segcblist.c:rcu_cblist_flush_enqueue
Direct callers:
  - kernel/rcu/srcutree.c:srcu_invoke_callbacks
```
**Symbols:**

```
c0000000001ee050-c0000000001ee070: rcu_cblist_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void rcu_cblist_init(struct rcu_cblist *rclp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/rcu/rcu_segcblist.c (ffffffe000125d08)
Location: kernel/rcu/rcu_segcblist.c:18
Inline: True
Inline callers:
  - kernel/rcu/rcu_segcblist.c:rcu_segcblist_merge
  - kernel/rcu/rcu_segcblist.c:rcu_segcblist_merge
  - kernel/rcu/rcu_segcblist.c:rcu_cblist_flush_enqueue
Direct callers:
  - kernel/rcu/srcutree.c:srcu_invoke_callbacks
```
**Symbols:**

```
ffffffe000125594-ffffffe0001255c2: rcu_cblist_init (STB_GLOBAL)
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
void rcu_cblist_init(struct rcu_cblist *rclp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/rcu/rcu_segcblist.c (ffffffff81123bcf)
Location: kernel/rcu/rcu_segcblist.c:18
Inline: True
Inline callers:
  - kernel/rcu/rcu_segcblist.c:rcu_segcblist_merge
  - kernel/rcu/rcu_segcblist.c:rcu_segcblist_merge
  - kernel/rcu/rcu_segcblist.c:rcu_cblist_flush_enqueue
Direct callers:
  - kernel/rcu/srcutree.c:srcu_invoke_callbacks
```
**Symbols:**

```
ffffffff81123520-ffffffff81123546: rcu_cblist_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void rcu_cblist_init(struct rcu_cblist *rclp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/rcu/rcu_segcblist.c (ffffffff8111664f)
Location: kernel/rcu/rcu_segcblist.c:18
Inline: True
Inline callers:
  - kernel/rcu/rcu_segcblist.c:rcu_segcblist_merge
  - kernel/rcu/rcu_segcblist.c:rcu_segcblist_merge
  - kernel/rcu/rcu_segcblist.c:rcu_cblist_flush_enqueue
Direct callers:
  - kernel/rcu/srcutree.c:srcu_invoke_callbacks
  - kernel/rcu/tree.c:rcu_init
```
**Symbols:**

```
ffffffff81116000-ffffffff81116026: rcu_cblist_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void rcu_cblist_init(struct rcu_cblist *rclp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/rcu/rcu_segcblist.c (ffffffff81121abf)
Location: kernel/rcu/rcu_segcblist.c:18
Inline: True
Inline callers:
  - kernel/rcu/rcu_segcblist.c:rcu_segcblist_merge
  - kernel/rcu/rcu_segcblist.c:rcu_segcblist_merge
  - kernel/rcu/rcu_segcblist.c:rcu_cblist_flush_enqueue
Direct callers:
  - kernel/rcu/srcutree.c:srcu_invoke_callbacks
```
**Symbols:**

```
ffffffff81121410-ffffffff81121436: rcu_cblist_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void rcu_cblist_init(struct rcu_cblist *rclp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/rcu/rcu_segcblist.c (ffffffff8112e0cf)
Location: kernel/rcu/rcu_segcblist.c:18
Inline: True
Inline callers:
  - kernel/rcu/rcu_segcblist.c:rcu_segcblist_merge
  - kernel/rcu/rcu_segcblist.c:rcu_segcblist_merge
  - kernel/rcu/rcu_segcblist.c:rcu_cblist_flush_enqueue
Direct callers:
  - kernel/rcu/srcutree.c:srcu_invoke_callbacks
```
**Symbols:**

```
ffffffff8112da20-ffffffff8112da46: rcu_cblist_init (STB_GLOBAL)
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
