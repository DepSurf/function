# Function: <code>rcu_segcblist_extract_pend_cbs</code>

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
void rcu_segcblist_extract_pend_cbs(struct rcu_segcblist *rsclp, struct rcu_cblist *rclp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/rcu_segcblist.c (ffffffff810f7350)
Location: kernel/rcu/rcu_segcblist.c:314
Inline: False
Direct callers:
  - kernel/rcu/tree.c:rcutree_dead_cpu
```
**Symbols:**

```
ffffffff810f7350-ffffffff810f7398: rcu_segcblist_extract_pend_cbs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void rcu_segcblist_extract_pend_cbs(struct rcu_segcblist *rsclp, struct rcu_cblist *rclp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/rcu/rcu_segcblist.c (ffffffff81101250)
Location: kernel/rcu/rcu_segcblist.c:231
Inline: True
Direct callers:
  - kernel/rcu/rcu_segcblist.c:rcu_segcblist_merge
```
**Symbols:**

```
ffffffff81101250-ffffffff81101298: rcu_segcblist_extract_pend_cbs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void rcu_segcblist_extract_pend_cbs(struct rcu_segcblist *rsclp, struct rcu_cblist *rclp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/rcu/rcu_segcblist.c (ffffffff811096e0)
Location: kernel/rcu/rcu_segcblist.c:231
Inline: True
Direct callers:
  - kernel/rcu/rcu_segcblist.c:rcu_segcblist_merge
```
**Symbols:**

```
ffffffff811096e0-ffffffff81109728: rcu_segcblist_extract_pend_cbs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void rcu_segcblist_extract_pend_cbs(struct rcu_segcblist *rsclp, struct rcu_cblist *rclp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/rcu/rcu_segcblist.c (ffffffff81114eb0)
Location: kernel/rcu/rcu_segcblist.c:231
Inline: True
Direct callers:
  - kernel/rcu/rcu_segcblist.c:rcu_segcblist_merge
```
**Symbols:**

```
ffffffff81114eb0-ffffffff81114ef8: rcu_segcblist_extract_pend_cbs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void rcu_segcblist_extract_pend_cbs(struct rcu_segcblist *rsclp, struct rcu_cblist *rclp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/rcu/rcu_segcblist.c (ffffffff8111ece0)
Location: kernel/rcu/rcu_segcblist.c:218
Inline: True
Direct callers:
  - kernel/rcu/rcu_segcblist.c:rcu_segcblist_merge
```
**Symbols:**

```
ffffffff8111ece0-ffffffff8111ed28: rcu_segcblist_extract_pend_cbs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void rcu_segcblist_extract_pend_cbs(struct rcu_segcblist *rsclp, struct rcu_cblist *rclp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/rcu/rcu_segcblist.c (ffffffff8112b3c0)
Location: kernel/rcu/rcu_segcblist.c:343
Inline: True
Direct callers:
  - kernel/rcu/rcu_segcblist.c:rcu_segcblist_merge
```
**Symbols:**

```
ffffffff8112b3c0-ffffffff8112b40e: rcu_segcblist_extract_pend_cbs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void rcu_segcblist_extract_pend_cbs(struct rcu_segcblist *rsclp, struct rcu_cblist *rclp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/rcu/rcu_segcblist.c (ffffffff81139920)
Location: kernel/rcu/rcu_segcblist.c:326
Inline: True
Direct callers:
  - kernel/rcu/rcu_segcblist.c:rcu_segcblist_merge
```
**Symbols:**

```
ffffffff81139920-ffffffff8113996e: rcu_segcblist_extract_pend_cbs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void rcu_segcblist_extract_pend_cbs(struct rcu_segcblist *rsclp, struct rcu_cblist *rclp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/rcu/rcu_segcblist.c (ffffffff811343f0)
Location: kernel/rcu/rcu_segcblist.c:326
Inline: True
Direct callers:
  - kernel/rcu/rcu_segcblist.c:rcu_segcblist_merge
```
**Symbols:**

```
ffffffff811343f0-ffffffff8113443e: rcu_segcblist_extract_pend_cbs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void rcu_segcblist_extract_pend_cbs(struct rcu_segcblist *rsclp, struct rcu_cblist *rclp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/rcu/rcu_segcblist.c (ffffffff81135200)
Location: kernel/rcu/rcu_segcblist.c:412
Inline: True
Direct callers:
  - kernel/rcu/rcu_segcblist.c:rcu_segcblist_merge
```
**Symbols:**

```
ffffffff81135200-ffffffff8113527b: rcu_segcblist_extract_pend_cbs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void rcu_segcblist_extract_pend_cbs(struct rcu_segcblist *rsclp, struct rcu_cblist *rclp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/rcu/rcu_segcblist.c (ffffffff81157af0)
Location: kernel/rcu/rcu_segcblist.c:412
Inline: True
Direct callers:
  - kernel/rcu/rcu_segcblist.c:rcu_segcblist_merge
```
**Symbols:**

```
ffffffff81157af0-ffffffff81157bc9: rcu_segcblist_extract_pend_cbs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void rcu_segcblist_extract_pend_cbs(struct rcu_segcblist *rsclp, struct rcu_cblist *rclp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/rcu/rcu_segcblist.c (ffffffff81180de0)
Location: kernel/rcu/rcu_segcblist.c:410
Inline: True
Direct callers:
  - kernel/rcu/rcu_segcblist.c:rcu_segcblist_merge
```
**Symbols:**

```
ffffffff81180de0-ffffffff81180ed1: rcu_segcblist_extract_pend_cbs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void rcu_segcblist_extract_pend_cbs(struct rcu_segcblist *rsclp, struct rcu_cblist *rclp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/rcu/rcu_segcblist.c (ffffffff811bb6f0)
Location: kernel/rcu/rcu_segcblist.c:410
Inline: True
Direct callers:
  - kernel/rcu/rcu_segcblist.c:rcu_segcblist_merge
```
**Symbols:**

```
ffffffff811bb6f0-ffffffff811bb7e1: rcu_segcblist_extract_pend_cbs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void rcu_segcblist_extract_pend_cbs(struct rcu_segcblist *rsclp, struct rcu_cblist *rclp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/rcu/rcu_segcblist.c (ffffffff811ce090)
Location: kernel/rcu/rcu_segcblist.c:410
Inline: True
Direct callers:
  - kernel/rcu/rcu_segcblist.c:rcu_segcblist_merge
```
**Symbols:**

```
ffffffff811ce090-ffffffff811ce181: rcu_segcblist_extract_pend_cbs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void rcu_segcblist_extract_pend_cbs(struct rcu_segcblist *rsclp, struct rcu_cblist *rclp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/rcu/rcu_segcblist.c (ffffffff811e2c90)
Location: kernel/rcu/rcu_segcblist.c:410
Inline: True
Direct callers:
  - kernel/rcu/rcu_segcblist.c:rcu_segcblist_merge
```
**Symbols:**

```
ffffffff811e2c90-ffffffff811e2d81: rcu_segcblist_extract_pend_cbs (STB_GLOBAL)
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
void rcu_segcblist_extract_pend_cbs(struct rcu_segcblist *rsclp, struct rcu_cblist *rclp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/rcu/rcu_segcblist.c (ffff800010193570)
Location: kernel/rcu/rcu_segcblist.c:343
Inline: True
Direct callers:
  - kernel/rcu/rcu_segcblist.c:rcu_segcblist_merge
```
**Symbols:**

```
ffff800010193570-ffff8000101935dc: rcu_segcblist_extract_pend_cbs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void rcu_segcblist_extract_pend_cbs(struct rcu_segcblist *rsclp, struct rcu_cblist *rclp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/rcu/rcu_segcblist.c (c03e0860)
Location: kernel/rcu/rcu_segcblist.c:343
Inline: True
Direct callers:
  - kernel/rcu/rcu_segcblist.c:rcu_segcblist_merge
```
**Symbols:**

```
c03e0860-c03e08c8: rcu_segcblist_extract_pend_cbs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void rcu_segcblist_extract_pend_cbs(struct rcu_segcblist *rsclp, struct rcu_cblist *rclp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/rcu/rcu_segcblist.c (c0000000001ee5d0)
Location: kernel/rcu/rcu_segcblist.c:343
Inline: True
Direct callers:
  - kernel/rcu/rcu_segcblist.c:rcu_segcblist_merge
```
**Symbols:**

```
c0000000001ee5d0-c0000000001ee62c: rcu_segcblist_extract_pend_cbs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void rcu_segcblist_extract_pend_cbs(struct rcu_segcblist *rsclp, struct rcu_cblist *rclp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/rcu/rcu_segcblist.c (ffffffe000125ac2)
Location: kernel/rcu/rcu_segcblist.c:343
Inline: True
Direct callers:
  - kernel/rcu/rcu_segcblist.c:rcu_segcblist_merge
```
**Symbols:**

```
ffffffe000125ac2-ffffffe000125b12: rcu_segcblist_extract_pend_cbs (STB_GLOBAL)
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
void rcu_segcblist_extract_pend_cbs(struct rcu_segcblist *rsclp, struct rcu_cblist *rclp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/rcu/rcu_segcblist.c (ffffffff811239a0)
Location: kernel/rcu/rcu_segcblist.c:343
Inline: True
Direct callers:
  - kernel/rcu/rcu_segcblist.c:rcu_segcblist_merge
```
**Symbols:**

```
ffffffff811239a0-ffffffff811239ee: rcu_segcblist_extract_pend_cbs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void rcu_segcblist_extract_pend_cbs(struct rcu_segcblist *rsclp, struct rcu_cblist *rclp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/rcu/rcu_segcblist.c (ffffffff81116430)
Location: kernel/rcu/rcu_segcblist.c:343
Inline: True
Direct callers:
  - kernel/rcu/rcu_segcblist.c:rcu_segcblist_merge
```
**Symbols:**

```
ffffffff81116430-ffffffff8111647e: rcu_segcblist_extract_pend_cbs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void rcu_segcblist_extract_pend_cbs(struct rcu_segcblist *rsclp, struct rcu_cblist *rclp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/rcu/rcu_segcblist.c (ffffffff81121890)
Location: kernel/rcu/rcu_segcblist.c:343
Inline: True
Direct callers:
  - kernel/rcu/rcu_segcblist.c:rcu_segcblist_merge
```
**Symbols:**

```
ffffffff81121890-ffffffff811218de: rcu_segcblist_extract_pend_cbs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void rcu_segcblist_extract_pend_cbs(struct rcu_segcblist *rsclp, struct rcu_cblist *rclp);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/rcu/rcu_segcblist.c (ffffffff8112dea0)
Location: kernel/rcu/rcu_segcblist.c:343
Inline: True
Direct callers:
  - kernel/rcu/rcu_segcblist.c:rcu_segcblist_merge
```
**Symbols:**

```
ffffffff8112dea0-ffffffff8112deee: rcu_segcblist_extract_pend_cbs (STB_GLOBAL)
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
