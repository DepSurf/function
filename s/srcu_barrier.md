# Function: <code>srcu_barrier</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void srcu_barrier(struct srcu_struct *sp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/srcu.c (ffffffff810e4110)
Location: kernel/rcu/srcu.c:518
Inline: False
Direct callers:
  - mm/mmu_notifier.c:mmu_notifier_synchronize
```
**Symbols:**

```
ffffffff810e4110-ffffffff810e4120: srcu_barrier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void srcu_barrier(struct srcu_struct *sp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/srcu.c (ffffffff810ea420)
Location: kernel/rcu/srcu.c:518
Inline: False
Direct callers:
  - mm/mmu_notifier.c:mmu_notifier_synchronize
```
**Symbols:**

```
ffffffff810ea420-ffffffff810ea430: srcu_barrier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void srcu_barrier(struct srcu_struct *sp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/srcu.c (ffffffff810f1300)
Location: kernel/rcu/srcu.c:518
Inline: False
Direct callers:
  - mm/mmu_notifier.c:mmu_notifier_synchronize
```
**Symbols:**

```
ffffffff810f1300-ffffffff810f1310: srcu_barrier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void srcu_barrier(struct srcu_struct *sp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/srcutree.c (ffffffff810f1580)
Location: kernel/rcu/srcutree.c:997
Inline: False
Direct callers:
  - mm/mmu_notifier.c:mmu_notifier_synchronize
```
**Symbols:**

```
ffffffff810f1580-ffffffff810f1739: srcu_barrier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void srcu_barrier(struct srcu_struct *sp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/srcutree.c (ffffffff810fb2e0)
Location: kernel/rcu/srcutree.c:998
Inline: False
Direct callers:
  - mm/mmu_notifier.c:mmu_notifier_synchronize
```
**Symbols:**

```
ffffffff810fb2e0-ffffffff810fb49c: srcu_barrier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void srcu_barrier(struct srcu_struct *sp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/srcutree.c (ffffffff81103800)
Location: kernel/rcu/srcutree.c:1028
Inline: False
Direct callers:
  - mm/mmu_notifier.c:mmu_notifier_synchronize
```
**Symbols:**

```
ffffffff81103800-ffffffff811039bc: srcu_barrier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void srcu_barrier(struct srcu_struct *ssp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/srcutree.c (ffffffff8110f110)
Location: kernel/rcu/srcutree.c:1046
Inline: False
```
**Symbols:**

```
ffffffff8110f110-ffffffff8110f2d7: srcu_barrier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void srcu_barrier(struct srcu_struct *ssp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/srcutree.c (ffffffff81118e70)
Location: kernel/rcu/srcutree.c:1021
Inline: False
```
**Symbols:**

```
ffffffff81118e70-ffffffff81119047: srcu_barrier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void srcu_barrier(struct srcu_struct *ssp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/srcutree.c (ffffffff81125240)
Location: kernel/rcu/srcutree.c:1022
Inline: False
```
**Symbols:**

```
ffffffff81125240-ffffffff81125417: srcu_barrier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void srcu_barrier(struct srcu_struct *ssp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/srcutree.c (ffffffff811323f0)
Location: kernel/rcu/srcutree.c:1035
Inline: False
```
**Symbols:**

```
ffffffff811323f0-ffffffff811325b9: srcu_barrier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void srcu_barrier(struct srcu_struct *ssp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/srcutree.c (ffffffff8112dbe0)
Location: kernel/rcu/srcutree.c:1024
Inline: False
```
**Symbols:**

```
ffffffff8112dbe0-ffffffff8112dda9: srcu_barrier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void srcu_barrier(struct srcu_struct *ssp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/srcutree.c (ffffffff8112e130)
Location: kernel/rcu/srcutree.c:1109
Inline: False
```
**Symbols:**

```
ffffffff8112e130-ffffffff8112e2f9: srcu_barrier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void srcu_barrier(struct srcu_struct *ssp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/srcutree.c (ffffffff8114f5e0)
Location: kernel/rcu/srcutree.c:1104
Inline: False
```
**Symbols:**

```
ffffffff8114f5e0-ffffffff8114f7ca: srcu_barrier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void srcu_barrier(struct srcu_struct *ssp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/srcutree.c (ffffffff81177120)
Location: kernel/rcu/srcutree.c:1411
Inline: False
```
**Symbols:**

```
ffffffff81177120-ffffffff81177335: srcu_barrier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void srcu_barrier(struct srcu_struct *ssp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/srcutree.c (ffffffff811ae810)
Location: kernel/rcu/srcutree.c:1480
Inline: False
```
**Symbols:**

```
ffffffff811ae810-ffffffff811aea5a: srcu_barrier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void srcu_barrier(struct srcu_struct *ssp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/srcutree.c (ffffffff811c0800)
Location: kernel/rcu/srcutree.c:1556
Inline: False
```
**Symbols:**

```
ffffffff811c0800-ffffffff811c0a5a: srcu_barrier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void srcu_barrier(struct srcu_struct *ssp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/srcutree.c (ffffffff811d0ce0)
Location: kernel/rcu/srcutree.c:1576
Inline: False
```
**Symbols:**

```
ffffffff811d0ce0-ffffffff811d0f3a: srcu_barrier (STB_GLOBAL)
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
void srcu_barrier(struct srcu_struct *ssp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/srcutree.c (ffff80001018a4a8)
Location: kernel/rcu/srcutree.c:1022
Inline: False
```
**Symbols:**

```
ffff80001018a4a8-ffff80001018a764: srcu_barrier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void srcu_barrier(struct srcu_struct *ssp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/srcutree.c (c03d8b84)
Location: kernel/rcu/srcutree.c:1022
Inline: False
```
**Symbols:**

```
c03d8b84-c03d8de8: srcu_barrier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void srcu_barrier(struct srcu_struct *ssp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/srcutree.c (c0000000001e53a0)
Location: kernel/rcu/srcutree.c:1022
Inline: False
```
**Symbols:**

```
c0000000001e53a0-c0000000001e5668: srcu_barrier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void srcu_barrier(struct srcu_struct *ssp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/srcutree.c (ffffffe00011f230)
Location: kernel/rcu/srcutree.c:1022
Inline: False
```
**Symbols:**

```
ffffffe00011f230-ffffffe00011f410: srcu_barrier (STB_GLOBAL)
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
void srcu_barrier(struct srcu_struct *ssp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/srcutree.c (ffffffff8111d820)
Location: kernel/rcu/srcutree.c:1022
Inline: False
```
**Symbols:**

```
ffffffff8111d820-ffffffff8111d9f7: srcu_barrier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void srcu_barrier(struct srcu_struct *ssp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/srcutree.c (ffffffff8110e8c0)
Location: kernel/rcu/srcutree.c:1022
Inline: False
```
**Symbols:**

```
ffffffff8110e8c0-ffffffff8110ea91: srcu_barrier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void srcu_barrier(struct srcu_struct *ssp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/srcutree.c (ffffffff8111b710)
Location: kernel/rcu/srcutree.c:1022
Inline: False
```
**Symbols:**

```
ffffffff8111b710-ffffffff8111b8e7: srcu_barrier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void srcu_barrier(struct srcu_struct *ssp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/srcutree.c (ffffffff81126970)
Location: kernel/rcu/srcutree.c:1022
Inline: False
```
**Symbols:**

```
ffffffff81126970-ffffffff81126b3e: srcu_barrier (STB_GLOBAL)
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
<details>
<summary>Changed between <code>4.18</code> and <code>5.0</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct srcu_struct *ssp</code>
</li>
<li>
<b>Param removed. </b>
<code>struct srcu_struct *sp</code>
</li>
</ul>
</details>
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
