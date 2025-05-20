# Function: <code>rcu_segcblist_merge</code>

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
In <code>4.13</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void rcu_segcblist_merge(struct rcu_segcblist *dst_rsclp, struct rcu_segcblist *src_rsclp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/rcu_segcblist.c (ffffffff81101460)
Location: kernel/rcu/rcu_segcblist.c:431
Inline: False
Direct callers:
  - kernel/rcu/tree.c:rcutree_migrate_callbacks
```
**Symbols:**

```
ffffffff81101460-ffffffff811015fe: rcu_segcblist_merge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void rcu_segcblist_merge(struct rcu_segcblist *dst_rsclp, struct rcu_segcblist *src_rsclp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/rcu_segcblist.c (ffffffff811098b0)
Location: kernel/rcu/rcu_segcblist.c:413
Inline: False
Direct callers:
  - kernel/rcu/tree.c:rcutree_migrate_callbacks
  - kernel/rcu/tree.c:rcutree_migrate_callbacks
```
**Symbols:**

```
ffffffff811098b0-ffffffff81109a4e: rcu_segcblist_merge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void rcu_segcblist_merge(struct rcu_segcblist *dst_rsclp, struct rcu_segcblist *src_rsclp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/rcu_segcblist.c (ffffffff81115080)
Location: kernel/rcu/rcu_segcblist.c:413
Inline: False
Direct callers:
  - kernel/rcu/tree.c:rcutree_migrate_callbacks
  - kernel/rcu/tree.c:rcutree_migrate_callbacks
```
**Symbols:**

```
ffffffff81115080-ffffffff8111521e: rcu_segcblist_merge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void rcu_segcblist_merge(struct rcu_segcblist *dst_rsclp, struct rcu_segcblist *src_rsclp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/rcu_segcblist.c (ffffffff8111eeb0)
Location: kernel/rcu/rcu_segcblist.c:400
Inline: False
Direct callers:
  - kernel/rcu/tree.c:rcutree_migrate_callbacks
  - kernel/rcu/tree.c:rcutree_migrate_callbacks
```
**Symbols:**

```
ffffffff8111eeb0-ffffffff8111f04e: rcu_segcblist_merge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void rcu_segcblist_merge(struct rcu_segcblist *dst_rsclp, struct rcu_segcblist *src_rsclp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/rcu_segcblist.c (ffffffff8112b5c0)
Location: kernel/rcu/rcu_segcblist.c:524
Inline: False
Direct callers:
  - kernel/rcu/tree.c:rcutree_migrate_callbacks
  - kernel/rcu/tree.c:rcutree_migrate_callbacks
```
**Symbols:**

```
ffffffff8112b5c0-ffffffff8112b785: rcu_segcblist_merge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void rcu_segcblist_merge(struct rcu_segcblist *dst_rsclp, struct rcu_segcblist *src_rsclp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/rcu_segcblist.c (ffffffff81139b00)
Location: kernel/rcu/rcu_segcblist.c:503
Inline: False
Direct callers:
  - kernel/rcu/tree.c:rcutree_migrate_callbacks
  - kernel/rcu/tree.c:rcutree_migrate_callbacks
```
**Symbols:**

```
ffffffff81139b00-ffffffff81139c4a: rcu_segcblist_merge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void rcu_segcblist_merge(struct rcu_segcblist *dst_rsclp, struct rcu_segcblist *src_rsclp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/rcu_segcblist.c (ffffffff811345f0)
Location: kernel/rcu/rcu_segcblist.c:511
Inline: False
Direct callers:
  - kernel/rcu/tree.c:rcutree_migrate_callbacks
  - kernel/rcu/tree.c:rcutree_migrate_callbacks
```
**Symbols:**

```
ffffffff811345f0-ffffffff8113473a: rcu_segcblist_merge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void rcu_segcblist_merge(struct rcu_segcblist *dst_rsclp, struct rcu_segcblist *src_rsclp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/rcu_segcblist.c (ffffffff811354f0)
Location: kernel/rcu/rcu_segcblist.c:609
Inline: False
Direct callers:
  - kernel/rcu/tree.c:rcutree_migrate_callbacks
  - kernel/rcu/tree.c:rcutree_migrate_callbacks
```
**Symbols:**

```
ffffffff811354f0-ffffffff8113562f: rcu_segcblist_merge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void rcu_segcblist_merge(struct rcu_segcblist *dst_rsclp, struct rcu_segcblist *src_rsclp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/rcu_segcblist.c (ffffffff81157fd0)
Location: kernel/rcu/rcu_segcblist.c:609
Inline: False
Direct callers:
  - kernel/rcu/tree.c:rcutree_migrate_callbacks
  - kernel/rcu/tree.c:rcutree_migrate_callbacks
```
**Symbols:**

```
ffffffff81157fd0-ffffffff8115810f: rcu_segcblist_merge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void rcu_segcblist_merge(struct rcu_segcblist *dst_rsclp, struct rcu_segcblist *src_rsclp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/rcu_segcblist.c (ffffffff81181300)
Location: kernel/rcu/rcu_segcblist.c:607
Inline: False
Direct callers:
  - kernel/rcu/tree.c:rcutree_migrate_callbacks
  - kernel/rcu/tree.c:rcutree_migrate_callbacks
```
**Symbols:**

```
ffffffff81181300-ffffffff81181481: rcu_segcblist_merge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void rcu_segcblist_merge(struct rcu_segcblist *dst_rsclp, struct rcu_segcblist *src_rsclp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/rcu_segcblist.c (ffffffff811bbc70)
Location: kernel/rcu/rcu_segcblist.c:607
Inline: False
Direct callers:
  - kernel/rcu/tree.c:rcutree_migrate_callbacks
  - kernel/rcu/tree.c:rcutree_migrate_callbacks
```
**Symbols:**

```
ffffffff811bbc70-ffffffff811bbdf1: rcu_segcblist_merge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void rcu_segcblist_merge(struct rcu_segcblist *dst_rsclp, struct rcu_segcblist *src_rsclp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/rcu_segcblist.c (ffffffff811ce610)
Location: kernel/rcu/rcu_segcblist.c:607
Inline: False
Direct callers:
  - kernel/rcu/tree.c:rcutree_migrate_callbacks
  - kernel/rcu/tree.c:rcutree_migrate_callbacks
  - kernel/rcu/tree.c:rcutree_migrate_callbacks
```
**Symbols:**

```
ffffffff811ce610-ffffffff811ce791: rcu_segcblist_merge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void rcu_segcblist_merge(struct rcu_segcblist *dst_rsclp, struct rcu_segcblist *src_rsclp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/rcu_segcblist.c (ffffffff811e3210)
Location: kernel/rcu/rcu_segcblist.c:607
Inline: False
Direct callers:
  - kernel/rcu/tree.c:rcutree_migrate_callbacks
  - kernel/rcu/tree.c:rcutree_migrate_callbacks
  - kernel/rcu/tree.c:rcutree_migrate_callbacks
```
**Symbols:**

```
ffffffff811e3210-ffffffff811e3373: rcu_segcblist_merge (STB_GLOBAL)
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
void rcu_segcblist_merge(struct rcu_segcblist *dst_rsclp, struct rcu_segcblist *src_rsclp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/rcu_segcblist.c (ffff800010193848)
Location: kernel/rcu/rcu_segcblist.c:524
Inline: False
Direct callers:
  - kernel/rcu/tree.c:rcutree_migrate_callbacks
  - kernel/rcu/tree.c:rcutree_migrate_callbacks
```
**Symbols:**

```
ffff800010193848-ffff8000101939e8: rcu_segcblist_merge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void rcu_segcblist_merge(struct rcu_segcblist *dst_rsclp, struct rcu_segcblist *src_rsclp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/rcu_segcblist.c (c03e0b6c)
Location: kernel/rcu/rcu_segcblist.c:524
Inline: False
Direct callers:
  - kernel/rcu/tree.c:rcutree_migrate_callbacks
  - kernel/rcu/tree.c:rcutree_migrate_callbacks
```
**Symbols:**

```
c03e0b6c-c03e0d38: rcu_segcblist_merge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void rcu_segcblist_merge(struct rcu_segcblist *dst_rsclp, struct rcu_segcblist *src_rsclp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/rcu_segcblist.c (c0000000001ee880)
Location: kernel/rcu/rcu_segcblist.c:524
Inline: False
Direct callers:
  - kernel/rcu/tree.c:rcutree_migrate_callbacks
  - kernel/rcu/tree.c:rcutree_migrate_callbacks
```
**Symbols:**

```
c0000000001ee880-c0000000001eea8c: rcu_segcblist_merge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void rcu_segcblist_merge(struct rcu_segcblist *dst_rsclp, struct rcu_segcblist *src_rsclp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/rcu_segcblist.c (ffffffe000125cee)
Location: kernel/rcu/rcu_segcblist.c:524
Inline: False
```
**Symbols:**

```
ffffffe000125cee-ffffffe000125e26: rcu_segcblist_merge (STB_GLOBAL)
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
void rcu_segcblist_merge(struct rcu_segcblist *dst_rsclp, struct rcu_segcblist *src_rsclp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/rcu_segcblist.c (ffffffff81123ba0)
Location: kernel/rcu/rcu_segcblist.c:524
Inline: False
Direct callers:
  - kernel/rcu/tree.c:rcutree_migrate_callbacks
  - kernel/rcu/tree.c:rcutree_migrate_callbacks
```
**Symbols:**

```
ffffffff81123ba0-ffffffff81123d65: rcu_segcblist_merge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void rcu_segcblist_merge(struct rcu_segcblist *dst_rsclp, struct rcu_segcblist *src_rsclp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/rcu_segcblist.c (ffffffff81116620)
Location: kernel/rcu/rcu_segcblist.c:524
Inline: False
Direct callers:
  - kernel/rcu/tree.c:rcutree_migrate_callbacks
  - kernel/rcu/tree.c:rcutree_migrate_callbacks
```
**Symbols:**

```
ffffffff81116620-ffffffff811167c3: rcu_segcblist_merge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void rcu_segcblist_merge(struct rcu_segcblist *dst_rsclp, struct rcu_segcblist *src_rsclp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/rcu_segcblist.c (ffffffff81121a90)
Location: kernel/rcu/rcu_segcblist.c:524
Inline: False
Direct callers:
  - kernel/rcu/tree.c:rcutree_migrate_callbacks
  - kernel/rcu/tree.c:rcutree_migrate_callbacks
```
**Symbols:**

```
ffffffff81121a90-ffffffff81121c55: rcu_segcblist_merge (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void rcu_segcblist_merge(struct rcu_segcblist *dst_rsclp, struct rcu_segcblist *src_rsclp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/rcu_segcblist.c (ffffffff8112e0a0)
Location: kernel/rcu/rcu_segcblist.c:524
Inline: False
Direct callers:
  - kernel/rcu/tree.c:rcutree_migrate_callbacks
  - kernel/rcu/tree.c:rcutree_migrate_callbacks
```
**Symbols:**

```
ffffffff8112e0a0-ffffffff8112e265: rcu_segcblist_merge (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
