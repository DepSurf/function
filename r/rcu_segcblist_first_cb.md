# Function: <code>rcu_segcblist_first_cb</code>

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
struct callback_head *rcu_segcblist_first_cb(struct rcu_segcblist *rsclp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/rcu_segcblist.c (ffffffff810f71a0)
Location: kernel/rcu/rcu_segcblist.c:184
Inline: False
Direct callers:
  - kernel/rcu/tree.c:rcutree_dead_cpu
```
**Symbols:**

```
ffffffff810f71a0-ffffffff810f71b9: rcu_segcblist_first_cb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct callback_head *rcu_segcblist_first_cb(struct rcu_segcblist *rsclp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/rcu_segcblist.c (ffffffff811010c0)
Location: kernel/rcu/rcu_segcblist.c:112
Inline: False
Direct callers:
  - kernel/rcu/tree.c:rcutree_migrate_callbacks
```
**Symbols:**

```
ffffffff811010c0-ffffffff811010d9: rcu_segcblist_first_cb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct callback_head *rcu_segcblist_first_cb(struct rcu_segcblist *rsclp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/rcu_segcblist.c (ffffffff81109540)
Location: kernel/rcu/rcu_segcblist.c:112
Inline: False
Direct callers:
  - kernel/rcu/tree.c:rcutree_migrate_callbacks
```
**Symbols:**

```
ffffffff81109540-ffffffff81109557: rcu_segcblist_first_cb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct callback_head *rcu_segcblist_first_cb(struct rcu_segcblist *rsclp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/rcu_segcblist.c (ffffffff81114d10)
Location: kernel/rcu/rcu_segcblist.c:112
Inline: False
Direct callers:
  - kernel/rcu/tree.c:rcutree_migrate_callbacks
```
**Symbols:**

```
ffffffff81114d10-ffffffff81114d27: rcu_segcblist_first_cb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct callback_head *rcu_segcblist_first_cb(struct rcu_segcblist *rsclp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/rcu_segcblist.c (ffffffff8111eb40)
Location: kernel/rcu/rcu_segcblist.c:99
Inline: False
Direct callers:
  - kernel/rcu/tree.c:rcutree_migrate_callbacks
```
**Symbols:**

```
ffffffff8111eb40-ffffffff8111eb57: rcu_segcblist_first_cb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct callback_head *rcu_segcblist_first_cb(struct rcu_segcblist *rsclp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/rcu_segcblist.c (ffffffff8112b1b0)
Location: kernel/rcu/rcu_segcblist.c:213
Inline: False
Direct callers:
  - kernel/rcu/tree.c:rcutree_migrate_callbacks
```
**Symbols:**

```
ffffffff8112b1b0-ffffffff8112b1c6: rcu_segcblist_first_cb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct callback_head *rcu_segcblist_first_cb(struct rcu_segcblist *rsclp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/rcu_segcblist.c (ffffffff81139750)
Location: kernel/rcu/rcu_segcblist.c:202
Inline: False
Direct callers:
  - kernel/rcu/tree.c:rcutree_migrate_callbacks
```
**Symbols:**

```
ffffffff81139750-ffffffff81139766: rcu_segcblist_first_cb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct callback_head *rcu_segcblist_first_cb(struct rcu_segcblist *rsclp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/rcu_segcblist.c (ffffffff81134220)
Location: kernel/rcu/rcu_segcblist.c:202
Inline: False
Direct callers:
  - kernel/rcu/tree.c:rcutree_migrate_callbacks
```
**Symbols:**

```
ffffffff81134220-ffffffff81134236: rcu_segcblist_first_cb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct callback_head *rcu_segcblist_first_cb(struct rcu_segcblist *rsclp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/rcu_segcblist.c (ffffffff81135030)
Location: kernel/rcu/rcu_segcblist.c:300
Inline: False
Direct callers:
  - kernel/rcu/tree.c:rcutree_migrate_callbacks
```
**Symbols:**

```
ffffffff81135030-ffffffff8113504b: rcu_segcblist_first_cb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct callback_head *rcu_segcblist_first_cb(struct rcu_segcblist *rsclp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/rcu_segcblist.c (ffffffff81157830)
Location: kernel/rcu/rcu_segcblist.c:300
Inline: False
Direct callers:
  - kernel/rcu/tree.c:rcutree_migrate_callbacks
```
**Symbols:**

```
ffffffff81157830-ffffffff8115784b: rcu_segcblist_first_cb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct callback_head *rcu_segcblist_first_cb(struct rcu_segcblist *rsclp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/rcu_segcblist.c (ffffffff81180ac0)
Location: kernel/rcu/rcu_segcblist.c:298
Inline: False
Direct callers:
  - kernel/rcu/tree.c:rcutree_migrate_callbacks
```
**Symbols:**

```
ffffffff81180ac0-ffffffff81180aeb: rcu_segcblist_first_cb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct callback_head *rcu_segcblist_first_cb(struct rcu_segcblist *rsclp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/rcu_segcblist.c (ffffffff811bb370)
Location: kernel/rcu/rcu_segcblist.c:298
Inline: False
Direct callers:
  - kernel/rcu/tree.c:rcutree_migrate_callbacks
```
**Symbols:**

```
ffffffff811bb370-ffffffff811bb39b: rcu_segcblist_first_cb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct callback_head *rcu_segcblist_first_cb(struct rcu_segcblist *rsclp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/rcu_segcblist.c (ffffffff811cdd10)
Location: kernel/rcu/rcu_segcblist.c:298
Inline: False
Direct callers:
  - kernel/rcu/tree.c:rcutree_migrate_callbacks
```
**Symbols:**

```
ffffffff811cdd10-ffffffff811cdd3b: rcu_segcblist_first_cb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct callback_head *rcu_segcblist_first_cb(struct rcu_segcblist *rsclp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/rcu_segcblist.c (ffffffff811e2930)
Location: kernel/rcu/rcu_segcblist.c:298
Inline: False
Direct callers:
  - kernel/rcu/tree.c:rcutree_migrate_callbacks
```
**Symbols:**

```
ffffffff811e2930-ffffffff811e295b: rcu_segcblist_first_cb (STB_GLOBAL)
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
struct callback_head *rcu_segcblist_first_cb(struct rcu_segcblist *rsclp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/rcu_segcblist.c (ffff800010193260)
Location: kernel/rcu/rcu_segcblist.c:213
Inline: False
Direct callers:
  - kernel/rcu/tree.c:rcutree_migrate_callbacks
```
**Symbols:**

```
ffff800010193260-ffff8000101932a0: rcu_segcblist_first_cb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct callback_head *rcu_segcblist_first_cb(struct rcu_segcblist *rsclp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/rcu_segcblist.c (c03e05fc)
Location: kernel/rcu/rcu_segcblist.c:213
Inline: False
Direct callers:
  - kernel/rcu/tree.c:rcutree_migrate_callbacks
```
**Symbols:**

```
c03e05fc-c03e0624: rcu_segcblist_first_cb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct callback_head *rcu_segcblist_first_cb(struct rcu_segcblist *rsclp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/rcu_segcblist.c (c0000000001ee320)
Location: kernel/rcu/rcu_segcblist.c:213
Inline: False
Direct callers:
  - kernel/rcu/tree.c:rcutree_migrate_callbacks
```
**Symbols:**

```
c0000000001ee320-c0000000001ee348: rcu_segcblist_first_cb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct callback_head *rcu_segcblist_first_cb(struct rcu_segcblist *rsclp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/rcu_segcblist.c (ffffffe000125892)
Location: kernel/rcu/rcu_segcblist.c:213
Inline: False
```
**Symbols:**

```
ffffffe000125892-ffffffe0001258bc: rcu_segcblist_first_cb (STB_GLOBAL)
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
struct callback_head *rcu_segcblist_first_cb(struct rcu_segcblist *rsclp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/rcu_segcblist.c (ffffffff81123790)
Location: kernel/rcu/rcu_segcblist.c:213
Inline: False
Direct callers:
  - kernel/rcu/tree.c:rcutree_migrate_callbacks
```
**Symbols:**

```
ffffffff81123790-ffffffff811237a6: rcu_segcblist_first_cb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct callback_head *rcu_segcblist_first_cb(struct rcu_segcblist *rsclp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/rcu_segcblist.c (ffffffff81116250)
Location: kernel/rcu/rcu_segcblist.c:213
Inline: False
Direct callers:
  - kernel/rcu/tree.c:rcutree_migrate_callbacks
```
**Symbols:**

```
ffffffff81116250-ffffffff81116266: rcu_segcblist_first_cb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct callback_head *rcu_segcblist_first_cb(struct rcu_segcblist *rsclp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/rcu_segcblist.c (ffffffff81121680)
Location: kernel/rcu/rcu_segcblist.c:213
Inline: False
Direct callers:
  - kernel/rcu/tree.c:rcutree_migrate_callbacks
```
**Symbols:**

```
ffffffff81121680-ffffffff81121696: rcu_segcblist_first_cb (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct callback_head *rcu_segcblist_first_cb(struct rcu_segcblist *rsclp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/rcu_segcblist.c (ffffffff8112dc90)
Location: kernel/rcu/rcu_segcblist.c:213
Inline: False
Direct callers:
  - kernel/rcu/tree.c:rcutree_migrate_callbacks
```
**Symbols:**

```
ffffffff8112dc90-ffffffff8112dca6: rcu_segcblist_first_cb (STB_GLOBAL)
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
