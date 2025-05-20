# Function: <code>rcu_cblist_enqueue</code>

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
In <code>4.15</code>: Absent ⚠️
</li>
<li>
In <code>4.18</code>: Absent ⚠️
</li>
<li>
In <code>5.0</code>: Absent ⚠️
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void rcu_cblist_enqueue(struct rcu_cblist *rclp, struct callback_head *rhp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/rcu_segcblist.c (ffffffff8112af70)
Location: kernel/rcu/rcu_segcblist.c:32
Inline: False
```
**Symbols:**

```
ffffffff8112af70-ffffffff8112af92: rcu_cblist_enqueue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void rcu_cblist_enqueue(struct rcu_cblist *rclp, struct callback_head *rhp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/rcu_segcblist.c (ffffffff811395a0)
Location: kernel/rcu/rcu_segcblist.c:28
Inline: False
```
**Symbols:**

```
ffffffff811395a0-ffffffff811395c2: rcu_cblist_enqueue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void rcu_cblist_enqueue(struct rcu_cblist *rclp, struct callback_head *rhp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/rcu_segcblist.c (ffffffff81134070)
Location: kernel/rcu/rcu_segcblist.c:28
Inline: False
```
**Symbols:**

```
ffffffff81134070-ffffffff81134092: rcu_cblist_enqueue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void rcu_cblist_enqueue(struct rcu_cblist *rclp, struct callback_head *rhp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/rcu_segcblist.c (ffffffff81134de0)
Location: kernel/rcu/rcu_segcblist.c:28
Inline: False
```
**Symbols:**

```
ffffffff81134de0-ffffffff81134e02: rcu_cblist_enqueue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void rcu_cblist_enqueue(struct rcu_cblist *rclp, struct callback_head *rhp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/rcu_segcblist.c (ffffffff811575e0)
Location: kernel/rcu/rcu_segcblist.c:28
Inline: False
```
**Symbols:**

```
ffffffff811575e0-ffffffff81157602: rcu_cblist_enqueue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void rcu_cblist_enqueue(struct rcu_cblist *rclp, struct callback_head *rhp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/rcu_segcblist.c (ffffffff811807f0)
Location: kernel/rcu/rcu_segcblist.c:28
Inline: False
```
**Symbols:**

```
ffffffff811807f0-ffffffff8118081c: rcu_cblist_enqueue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void rcu_cblist_enqueue(struct rcu_cblist *rclp, struct callback_head *rhp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/rcu_segcblist.c (ffffffff811baff0)
Location: kernel/rcu/rcu_segcblist.c:28
Inline: False
```
**Symbols:**

```
ffffffff811baff0-ffffffff811bb01c: rcu_cblist_enqueue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void rcu_cblist_enqueue(struct rcu_cblist *rclp, struct callback_head *rhp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/rcu_segcblist.c (ffffffff811cd930)
Location: kernel/rcu/rcu_segcblist.c:28
Inline: False
```
**Symbols:**

```
ffffffff811cd930-ffffffff811cd95c: rcu_cblist_enqueue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void rcu_cblist_enqueue(struct rcu_cblist *rclp, struct callback_head *rhp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/rcu_segcblist.c (ffffffff811e2570)
Location: kernel/rcu/rcu_segcblist.c:28
Inline: False
Direct callers:
  - kernel/rcu/tree.c:rcu_nocb_try_bypass
  - kernel/rcu/tree.c:rcu_nocb_do_flush_bypass
```
**Symbols:**

```
ffffffff811e2570-ffffffff811e259c: rcu_cblist_enqueue (STB_GLOBAL)
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
void rcu_cblist_enqueue(struct rcu_cblist *rclp, struct callback_head *rhp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/rcu_segcblist.c (ffff800010192ee0)
Location: kernel/rcu/rcu_segcblist.c:32
Inline: False
```
**Symbols:**

```
ffff800010192ee0-ffff800010192f20: rcu_cblist_enqueue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void rcu_cblist_enqueue(struct rcu_cblist *rclp, struct callback_head *rhp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/rcu_segcblist.c (c03e02c4)
Location: kernel/rcu/rcu_segcblist.c:32
Inline: False
```
**Symbols:**

```
c03e02c4-c03e02f4: rcu_cblist_enqueue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void rcu_cblist_enqueue(struct rcu_cblist *rclp, struct callback_head *rhp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/rcu_segcblist.c (c0000000001ee070)
Location: kernel/rcu/rcu_segcblist.c:32
Inline: False
```
**Symbols:**

```
c0000000001ee070-c0000000001ee094: rcu_cblist_enqueue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void rcu_cblist_enqueue(struct rcu_cblist *rclp, struct callback_head *rhp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/rcu_segcblist.c (ffffffe0001255c2)
Location: kernel/rcu/rcu_segcblist.c:32
Inline: False
```
**Symbols:**

```
ffffffe0001255c2-ffffffe0001255f8: rcu_cblist_enqueue (STB_GLOBAL)
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
void rcu_cblist_enqueue(struct rcu_cblist *rclp, struct callback_head *rhp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/rcu_segcblist.c (ffffffff81123550)
Location: kernel/rcu/rcu_segcblist.c:32
Inline: False
```
**Symbols:**

```
ffffffff81123550-ffffffff81123572: rcu_cblist_enqueue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void rcu_cblist_enqueue(struct rcu_cblist *rclp, struct callback_head *rhp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/rcu_segcblist.c (ffffffff81116030)
Location: kernel/rcu/rcu_segcblist.c:32
Inline: False
Direct callers:
  - kernel/rcu/tree.c:__call_rcu
```
**Symbols:**

```
ffffffff81116030-ffffffff81116052: rcu_cblist_enqueue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void rcu_cblist_enqueue(struct rcu_cblist *rclp, struct callback_head *rhp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/rcu_segcblist.c (ffffffff81121440)
Location: kernel/rcu/rcu_segcblist.c:32
Inline: False
```
**Symbols:**

```
ffffffff81121440-ffffffff81121462: rcu_cblist_enqueue (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void rcu_cblist_enqueue(struct rcu_cblist *rclp, struct callback_head *rhp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/rcu_segcblist.c (ffffffff8112da50)
Location: kernel/rcu/rcu_segcblist.c:32
Inline: False
```
**Symbols:**

```
ffffffff8112da50-ffffffff8112da72: rcu_cblist_enqueue (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
