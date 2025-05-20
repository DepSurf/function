# Function: <code>show_rcu_gp_kthreads</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void show_rcu_gp_kthreads();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff810e42e0)
Location: kernel/rcu/tree.c:501
Inline: False
```
**Symbols:**

```
ffffffff810e42e0-ffffffff810e4341: show_rcu_gp_kthreads (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void show_rcu_gp_kthreads();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff810eaa70)
Location: kernel/rcu/tree.c:536
Inline: False
```
**Symbols:**

```
ffffffff810eaa70-ffffffff810eaad8: show_rcu_gp_kthreads (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void show_rcu_gp_kthreads();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff810f1a30)
Location: kernel/rcu/tree.c:537
Inline: False
```
**Symbols:**

```
ffffffff810f1a30-ffffffff810f1a99: show_rcu_gp_kthreads (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void show_rcu_gp_kthreads();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff810f2850)
Location: kernel/rcu/tree.c:655
Inline: False
```
**Symbols:**

```
ffffffff810f2850-ffffffff810f28ba: show_rcu_gp_kthreads (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void show_rcu_gp_kthreads();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff810fc630)
Location: kernel/rcu/tree.c:652
Inline: False
```
**Symbols:**

```
ffffffff810fc630-ffffffff810fc69a: show_rcu_gp_kthreads (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
void show_rcu_gp_kthreads();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/rcu/tree.c (0)
Location: kernel/rcu/tree.c:637
Inline: False
```
**Symbols:**

```
ffffffff81108ba3-ffffffff81108bf1: show_rcu_gp_kthreads.cold.76 (STB_LOCAL)
ffffffff811049f0-ffffffff81104a14: show_rcu_gp_kthreads (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void show_rcu_gp_kthreads();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff81113fb2)
Location: kernel/rcu/tree.c:528
Inline: False
Direct callers:
  - kernel/rcu/tree.c:rcu_fwd_progress_check
```
**Symbols:**

```
ffffffff81113fb2-ffffffff811140d8: show_rcu_gp_kthreads (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void show_rcu_gp_kthreads();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff8111dc52)
Location: kernel/rcu/tree_stall.h:548
Inline: False
Direct callers:
  - kernel/rcu/tree.c:sysrq_show_rcu
  - kernel/rcu/tree.c:rcu_fwd_progress_check
```
**Symbols:**

```
ffffffff8111dc52-ffffffff8111ddc9: show_rcu_gp_kthreads (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void show_rcu_gp_kthreads();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff8112a20f)
Location: kernel/rcu/tree_stall.h:552
Inline: False
Direct callers:
  - kernel/rcu/tree.c:sysrq_show_rcu
  - kernel/rcu/tree.c:rcu_fwd_progress_check
```
**Symbols:**

```
ffffffff8112a20f-ffffffff8112a3a2: show_rcu_gp_kthreads (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void show_rcu_gp_kthreads();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff81138b6d)
Location: kernel/rcu/tree_stall.h:650
Inline: False
Direct callers:
  - kernel/rcu/tree.c:sysrq_show_rcu
  - kernel/rcu/tree.c:rcu_fwd_progress_check
```
**Symbols:**

```
ffffffff81138b6d-ffffffff81138d0d: show_rcu_gp_kthreads (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void show_rcu_gp_kthreads();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff81be250f)
Location: kernel/rcu/tree_stall.h:666
Inline: False
Direct callers:
  - kernel/rcu/tree.c:sysrq_show_rcu
  - kernel/rcu/tree.c:rcu_fwd_progress_check
```
**Symbols:**

```
ffffffff81be250f-ffffffff81be26e0: show_rcu_gp_kthreads (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void show_rcu_gp_kthreads();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff81bd44ae)
Location: kernel/rcu/tree_stall.h:722
Inline: False
Direct callers:
  - kernel/rcu/tree.c:sysrq_show_rcu
  - kernel/rcu/tree.c:rcu_fwd_progress_check
```
**Symbols:**

```
ffffffff81bd44ae-ffffffff81bd4683: show_rcu_gp_kthreads (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void show_rcu_gp_kthreads();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/rcu/tree.c (0)
Location: kernel/rcu/tree_stall.h:805
Inline: False
Direct callers:
  - kernel/rcu/tree.c:sysrq_show_rcu
  - kernel/rcu/tree.c:rcu_fwd_progress_check
```
**Symbols:**

```
ffffffff81cae7d2-ffffffff81caea36: show_rcu_gp_kthreads.cold (STB_LOCAL)
ffffffff81150f60-ffffffff811510b8: show_rcu_gp_kthreads (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void show_rcu_gp_kthreads();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/rcu/tree.c (0)
Location: kernel/rcu/tree_stall.h:845
Inline: False
Direct callers:
  - kernel/rcu/tree.c:sysrq_show_rcu
  - kernel/rcu/tree.c:rcu_fwd_progress_check
```
**Symbols:**

```
ffffffff81e5ee61-ffffffff81e5f0d9: show_rcu_gp_kthreads.cold (STB_LOCAL)
ffffffff81178f10-ffffffff81179068: show_rcu_gp_kthreads (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void show_rcu_gp_kthreads();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/rcu/tree.c (0)
Location: kernel/rcu/tree_stall.h:837
Inline: False
Direct callers:
  - kernel/rcu/tree.c:sysrq_show_rcu
  - kernel/rcu/tree.c:rcu_fwd_progress_check
```
**Symbols:**

```
ffffffff8205a1e9-ffffffff8205a1fe: show_rcu_gp_kthreads.cold (STB_LOCAL)
ffffffff811b7730-ffffffff811b7b58: show_rcu_gp_kthreads (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void show_rcu_gp_kthreads();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/rcu/tree.c (0)
Location: kernel/rcu/tree_stall.h:868
Inline: False
Direct callers:
  - kernel/rcu/tree.c:sysrq_show_rcu
  - kernel/rcu/tree.c:rcu_fwd_progress_check
```
**Symbols:**

```
ffffffff820d89c6-ffffffff820d89db: show_rcu_gp_kthreads.cold (STB_LOCAL)
ffffffff811c91f0-ffffffff811c9618: show_rcu_gp_kthreads (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void show_rcu_gp_kthreads();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/rcu/tree.c (0)
Location: kernel/rcu/tree_stall.h:874
Inline: False
Direct callers:
  - kernel/rcu/tree.c:sysrq_show_rcu
  - kernel/rcu/tree.c:rcu_fwd_progress_check
```
**Symbols:**

```
ffffffff821b3c47-ffffffff821b3c5c: show_rcu_gp_kthreads.cold (STB_LOCAL)
ffffffff811d8560-ffffffff811d898d: show_rcu_gp_kthreads (STB_GLOBAL)
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
void show_rcu_gp_kthreads();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffff80001019275c)
Location: kernel/rcu/tree_stall.h:552
Inline: False
Direct callers:
  - kernel/rcu/tree.c:sysrq_show_rcu
  - kernel/rcu/tree.c:rcu_fwd_progress_check
```
**Symbols:**

```
ffff80001019275c-ffff800010192938: show_rcu_gp_kthreads (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void show_rcu_gp_kthreads();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (c03dfb24)
Location: kernel/rcu/tree_stall.h:552
Inline: False
Direct callers:
  - kernel/rcu/tree.c:sysrq_show_rcu
  - kernel/rcu/tree.c:rcu_fwd_progress_check
```
**Symbols:**

```
c03dfb24-c03dfd28: show_rcu_gp_kthreads (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void show_rcu_gp_kthreads();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (c0000000001ed70c)
Location: kernel/rcu/tree_stall.h:552
Inline: False
Direct callers:
  - kernel/rcu/tree.c:sysrq_show_rcu
  - kernel/rcu/tree.c:rcu_fwd_progress_check
```
**Symbols:**

```
c0000000001ed70c-c0000000001ed96c: show_rcu_gp_kthreads (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void show_rcu_gp_kthreads();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffe000124ede)
Location: kernel/rcu/tree_stall.h:552
Inline: False
Direct callers:
  - kernel/rcu/tree.c:sysrq_show_rcu
  - kernel/rcu/tree.c:rcu_fwd_progress_check
```
**Symbols:**

```
ffffffe000124ede-ffffffe0001250b2: show_rcu_gp_kthreads (STB_GLOBAL)
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
void show_rcu_gp_kthreads();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff811227ef)
Location: kernel/rcu/tree_stall.h:552
Inline: False
Direct callers:
  - kernel/rcu/tree.c:sysrq_show_rcu
  - kernel/rcu/tree.c:rcu_fwd_progress_check
```
**Symbols:**

```
ffffffff811227ef-ffffffff81122982: show_rcu_gp_kthreads (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void show_rcu_gp_kthreads();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff81114f02)
Location: kernel/rcu/tree_stall.h:552
Inline: False
Direct callers:
  - kernel/rcu/tree.c:sysrq_show_rcu
  - kernel/rcu/tree.c:rcu_fwd_progress_check
```
**Symbols:**

```
ffffffff81114f02-ffffffff8111543b: show_rcu_gp_kthreads (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void show_rcu_gp_kthreads();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff811206df)
Location: kernel/rcu/tree_stall.h:552
Inline: False
Direct callers:
  - kernel/rcu/tree.c:sysrq_show_rcu
  - kernel/rcu/tree.c:rcu_fwd_progress_check
```
**Symbols:**

```
ffffffff811206df-ffffffff81120872: show_rcu_gp_kthreads (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void show_rcu_gp_kthreads();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff8112c99f)
Location: kernel/rcu/tree_stall.h:552
Inline: False
Direct callers:
  - kernel/rcu/tree.c:sysrq_show_rcu
  - kernel/rcu/tree.c:rcu_fwd_progress_check
```
**Symbols:**

```
ffffffff8112c99f-ffffffff8112cb32: show_rcu_gp_kthreads (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
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
