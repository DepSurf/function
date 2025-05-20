# Function: <code>rcu_segcblist_nextgp</code>

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
bool rcu_segcblist_nextgp(struct rcu_segcblist *rsclp, long unsigned int *lp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/rcu_segcblist.c (ffffffff8112b1f0)
Location: kernel/rcu/rcu_segcblist.c:238
Inline: False
```
**Symbols:**

```
ffffffff8112b1f0-ffffffff8112b21b: rcu_segcblist_nextgp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
bool rcu_segcblist_nextgp(struct rcu_segcblist *rsclp, long unsigned int *lp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/rcu_segcblist.c (ffffffff81139790)
Location: kernel/rcu/rcu_segcblist.c:227
Inline: False
```
**Symbols:**

```
ffffffff81139790-ffffffff811397bb: rcu_segcblist_nextgp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
bool rcu_segcblist_nextgp(struct rcu_segcblist *rsclp, long unsigned int *lp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/rcu_segcblist.c (ffffffff81134260)
Location: kernel/rcu/rcu_segcblist.c:227
Inline: False
```
**Symbols:**

```
ffffffff81134260-ffffffff8113428b: rcu_segcblist_nextgp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
bool rcu_segcblist_nextgp(struct rcu_segcblist *rsclp, long unsigned int *lp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/rcu_segcblist.c (ffffffff81135070)
Location: kernel/rcu/rcu_segcblist.c:325
Inline: False
```
**Symbols:**

```
ffffffff81135070-ffffffff8113509b: rcu_segcblist_nextgp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
bool rcu_segcblist_nextgp(struct rcu_segcblist *rsclp, long unsigned int *lp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/rcu_segcblist.c (ffffffff81157870)
Location: kernel/rcu/rcu_segcblist.c:325
Inline: False
```
**Symbols:**

```
ffffffff81157870-ffffffff8115789b: rcu_segcblist_nextgp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
bool rcu_segcblist_nextgp(struct rcu_segcblist *rsclp, long unsigned int *lp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/rcu_segcblist.c (ffffffff81180b20)
Location: kernel/rcu/rcu_segcblist.c:323
Inline: False
```
**Symbols:**

```
ffffffff81180b20-ffffffff81180b5f: rcu_segcblist_nextgp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
bool rcu_segcblist_nextgp(struct rcu_segcblist *rsclp, long unsigned int *lp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/rcu_segcblist.c (ffffffff811bb3f0)
Location: kernel/rcu/rcu_segcblist.c:323
Inline: False
```
**Symbols:**

```
ffffffff811bb3f0-ffffffff811bb42f: rcu_segcblist_nextgp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
bool rcu_segcblist_nextgp(struct rcu_segcblist *rsclp, long unsigned int *lp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/rcu_segcblist.c (ffffffff811cdd90)
Location: kernel/rcu/rcu_segcblist.c:323
Inline: False
```
**Symbols:**

```
ffffffff811cdd90-ffffffff811cddcf: rcu_segcblist_nextgp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
bool rcu_segcblist_nextgp(struct rcu_segcblist *rsclp, long unsigned int *lp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/rcu_segcblist.c (ffffffff811e29b0)
Location: kernel/rcu/rcu_segcblist.c:323
Inline: False
Direct callers:
  - kernel/rcu/tree.c:nocb_cb_wait
  - kernel/rcu/tree.c:nocb_gp_wait
  - kernel/rcu/tree.c:nocb_gp_wait
  - kernel/rcu/tree.c:__call_rcu_nocb_wake
  - kernel/rcu/tree.c:rcu_nocb_try_bypass
```
**Symbols:**

```
ffffffff811e29b0-ffffffff811e29ef: rcu_segcblist_nextgp (STB_GLOBAL)
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
bool rcu_segcblist_nextgp(struct rcu_segcblist *rsclp, long unsigned int *lp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/rcu_segcblist.c (ffff8000101932e8)
Location: kernel/rcu/rcu_segcblist.c:238
Inline: False
```
**Symbols:**

```
ffff8000101932e8-ffff800010193340: rcu_segcblist_nextgp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
bool rcu_segcblist_nextgp(struct rcu_segcblist *rsclp, long unsigned int *lp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/rcu_segcblist.c (c03e0650)
Location: kernel/rcu/rcu_segcblist.c:238
Inline: False
```
**Symbols:**

```
c03e0650-c03e0698: rcu_segcblist_nextgp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
bool rcu_segcblist_nextgp(struct rcu_segcblist *rsclp, long unsigned int *lp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/rcu_segcblist.c (c0000000001ee380)
Location: kernel/rcu/rcu_segcblist.c:238
Inline: False
```
**Symbols:**

```
c0000000001ee380-c0000000001ee3c8: rcu_segcblist_nextgp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
bool rcu_segcblist_nextgp(struct rcu_segcblist *rsclp, long unsigned int *lp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/rcu_segcblist.c (ffffffe0001258e8)
Location: kernel/rcu/rcu_segcblist.c:238
Inline: False
```
**Symbols:**

```
ffffffe0001258e8-ffffffe000125930: rcu_segcblist_nextgp (STB_GLOBAL)
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
bool rcu_segcblist_nextgp(struct rcu_segcblist *rsclp, long unsigned int *lp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/rcu_segcblist.c (ffffffff811237d0)
Location: kernel/rcu/rcu_segcblist.c:238
Inline: False
```
**Symbols:**

```
ffffffff811237d0-ffffffff811237fb: rcu_segcblist_nextgp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
bool rcu_segcblist_nextgp(struct rcu_segcblist *rsclp, long unsigned int *lp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/rcu_segcblist.c (ffffffff81116290)
Location: kernel/rcu/rcu_segcblist.c:238
Inline: False
Direct callers:
  - kernel/rcu/tree.c:rcu_nocb_cb_kthread
  - kernel/rcu/tree.c:nocb_gp_wait
  - kernel/rcu/tree.c:nocb_gp_wait
  - kernel/rcu/tree.c:__call_rcu
```
**Symbols:**

```
ffffffff81116290-ffffffff811162bb: rcu_segcblist_nextgp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
bool rcu_segcblist_nextgp(struct rcu_segcblist *rsclp, long unsigned int *lp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/rcu_segcblist.c (ffffffff811216c0)
Location: kernel/rcu/rcu_segcblist.c:238
Inline: False
```
**Symbols:**

```
ffffffff811216c0-ffffffff811216eb: rcu_segcblist_nextgp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
bool rcu_segcblist_nextgp(struct rcu_segcblist *rsclp, long unsigned int *lp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/rcu_segcblist.c (ffffffff8112dcd0)
Location: kernel/rcu/rcu_segcblist.c:238
Inline: False
```
**Symbols:**

```
ffffffff8112dcd0-ffffffff8112dcfb: rcu_segcblist_nextgp (STB_GLOBAL)
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
