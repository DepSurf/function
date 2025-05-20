# Function: <code>fib_rebalance</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void fib_rebalance(struct fib_info *fi);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_semantics.c (ffffffff8179bf50)
Location: net/ipv4/fib_semantics.c:534
Inline: False
Direct callers:
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_sync_down_dev
  - net/ipv4/fib_semantics.c:fib_sync_down_dev
  - net/ipv4/fib_semantics.c:fib_sync_up
```
**Symbols:**

```
ffffffff8179bf50-ffffffff8179c088: fib_rebalance (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void fib_rebalance(struct fib_info *fi);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_semantics.c (ffffffff81809ad0)
Location: net/ipv4/fib_semantics.c:537
Inline: False
Direct callers:
  - net/ipv4/fib_semantics.c:fib_sync_up
  - net/ipv4/fib_semantics.c:fib_sync_down_dev
  - net/ipv4/fib_semantics.c:fib_create_info
```
**Symbols:**

```
ffffffff81809ad0-ffffffff81809c0d: fib_rebalance (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void fib_rebalance(struct fib_info *fi);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_semantics.c (ffffffff8183ac50)
Location: net/ipv4/fib_semantics.c:538
Inline: False
Direct callers:
  - net/ipv4/fib_semantics.c:fib_sync_up
  - net/ipv4/fib_semantics.c:fib_sync_down_dev
  - net/ipv4/fib_semantics.c:fib_create_info
```
**Symbols:**

```
ffffffff8183ac50-ffffffff8183ad8d: fib_rebalance (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void fib_rebalance(struct fib_info *fi);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_semantics.c (ffffffff8185c120)
Location: net/ipv4/fib_semantics.c:558
Inline: False
Direct callers:
  - net/ipv4/fib_semantics.c:fib_sync_up
  - net/ipv4/fib_semantics.c:fib_sync_down_dev
  - net/ipv4/fib_semantics.c:fib_create_info
```
**Symbols:**

```
ffffffff8185c120-ffffffff8185c204: fib_rebalance (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void fib_rebalance(struct fib_info *fi);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_semantics.c (ffffffff818dc010)
Location: net/ipv4/fib_semantics.c:559
Inline: False
Direct callers:
  - net/ipv4/fib_semantics.c:fib_sync_up
  - net/ipv4/fib_semantics.c:fib_sync_down_dev
  - net/ipv4/fib_semantics.c:fib_create_info
```
**Symbols:**

```
ffffffff818dc010-ffffffff818dc0f4: fib_rebalance (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void fib_rebalance(struct fib_info *fi);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_semantics.c (ffffffff81932c60)
Location: net/ipv4/fib_semantics.c:559
Inline: False
Direct callers:
  - net/ipv4/fib_semantics.c:fib_sync_up
  - net/ipv4/fib_semantics.c:fib_sync_down_dev
  - net/ipv4/fib_semantics.c:fib_create_info
```
**Symbols:**

```
ffffffff81932c60-ffffffff81932d33: fib_rebalance (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void fib_rebalance(struct fib_info *fi);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_semantics.c (ffffffff819624f0)
Location: net/ipv4/fib_semantics.c:557
Inline: False
Direct callers:
  - net/ipv4/fib_semantics.c:fib_sync_up
  - net/ipv4/fib_semantics.c:fib_sync_down_dev
  - net/ipv4/fib_semantics.c:fib_create_info
```
**Symbols:**

```
ffffffff819624f0-ffffffff819625c3: fib_rebalance (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void fib_rebalance(struct fib_info *fi);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_semantics.c (ffffffff819c7dc0)
Location: net/ipv4/fib_semantics.c:757
Inline: True
Direct callers:
  - net/ipv4/fib_semantics.c:fib_sync_up
  - net/ipv4/fib_semantics.c:fib_sync_down_dev
  - net/ipv4/fib_semantics.c:fib_create_info
```
**Symbols:**

```
ffffffff819c7dc0-ffffffff819c7f24: fib_rebalance (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void fib_rebalance(struct fib_info *fi);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_semantics.c (ffffffff819fe970)
Location: net/ipv4/fib_semantics.c:757
Inline: True
Direct callers:
  - net/ipv4/fib_semantics.c:fib_sync_up
  - net/ipv4/fib_semantics.c:fib_sync_down_dev
  - net/ipv4/fib_semantics.c:fib_create_info
```
**Symbols:**

```
ffffffff819fe970-ffffffff819fead4: fib_rebalance (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void fib_rebalance(struct fib_info *fi);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_semantics.c (ffffffff81aed940)
Location: net/ipv4/fib_semantics.c:766
Inline: False
Direct callers:
  - net/ipv4/fib_semantics.c:fib_sync_up
  - net/ipv4/fib_semantics.c:fib_sync_down_dev
  - net/ipv4/fib_semantics.c:fib_create_info
```
**Symbols:**

```
ffffffff81aed940-ffffffff81aeda99: fib_rebalance (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void fib_rebalance(struct fib_info *fi);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_semantics.c (ffffffff81afa810)
Location: net/ipv4/fib_semantics.c:766
Inline: False
Direct callers:
  - net/ipv4/fib_semantics.c:fib_sync_up
  - net/ipv4/fib_semantics.c:fib_sync_down_dev
  - net/ipv4/fib_semantics.c:fib_create_info
```
**Symbols:**

```
ffffffff81afa810-ffffffff81afa9ad: fib_rebalance (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void fib_rebalance(struct fib_info *fi);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_semantics.c (ffffffff81ae5e10)
Location: net/ipv4/fib_semantics.c:767
Inline: False
Direct callers:
  - net/ipv4/fib_semantics.c:fib_sync_up
  - net/ipv4/fib_semantics.c:fib_sync_down_dev
  - net/ipv4/fib_semantics.c:fib_create_info
```
**Symbols:**

```
ffffffff81ae5e10-ffffffff81ae5fb0: fib_rebalance (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void fib_rebalance(struct fib_info *fi);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/fib_semantics.c (0)
Location: net/ipv4/fib_semantics.c:797
Inline: False
Direct callers:
  - net/ipv4/fib_semantics.c:fib_sync_up
  - net/ipv4/fib_semantics.c:fib_sync_down_dev
  - net/ipv4/fib_semantics.c:fib_create_info
```
**Symbols:**

```
ffffffff81ba5840-ffffffff81ba5a6b: fib_rebalance (STB_LOCAL)
ffffffff81d3c929-ffffffff81d3c9ea: fib_rebalance.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void fib_rebalance(struct fib_info *fi);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/fib_semantics.c (0)
Location: net/ipv4/fib_semantics.c:799
Inline: False
Direct callers:
  - net/ipv4/fib_semantics.c:fib_sync_up
  - net/ipv4/fib_semantics.c:fib_sync_down_dev
  - net/ipv4/fib_semantics.c:fib_create_info
```
**Symbols:**

```
ffffffff81d384c0-ffffffff81d386fc: fib_rebalance (STB_LOCAL)
ffffffff81f091f7-ffffffff81f092b8: fib_rebalance.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void fib_rebalance(struct fib_info *fi);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/fib_semantics.c (0)
Location: net/ipv4/fib_semantics.c:801
Inline: False
Direct callers:
  - net/ipv4/fib_semantics.c:fib_sync_up
  - net/ipv4/fib_semantics.c:fib_sync_down_dev
  - net/ipv4/fib_semantics.c:fib_create_info
```
**Symbols:**

```
ffffffff81f00a50-ffffffff81f00c8c: fib_rebalance (STB_LOCAL)
ffffffff820b0ae7-ffffffff820b0ba8: fib_rebalance.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void fib_rebalance(struct fib_info *fi);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/fib_semantics.c (0)
Location: net/ipv4/fib_semantics.c:801
Inline: False
Direct callers:
  - net/ipv4/fib_semantics.c:fib_sync_up
  - net/ipv4/fib_semantics.c:fib_sync_down_dev
  - net/ipv4/fib_semantics.c:fib_create_info
```
**Symbols:**

```
ffffffff81f604d0-ffffffff81f6070c: fib_rebalance (STB_LOCAL)
ffffffff82131d6e-ffffffff82131e2f: fib_rebalance.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void fib_rebalance(struct fib_info *fi);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/fib_semantics.c (0)
Location: net/ipv4/fib_semantics.c:802
Inline: False
Direct callers:
  - net/ipv4/fib_semantics.c:fib_sync_up
  - net/ipv4/fib_semantics.c:fib_sync_down_dev
  - net/ipv4/fib_semantics.c:fib_create_info
```
**Symbols:**

```
ffffffff82026aa0-ffffffff82026cdc: fib_rebalance (STB_LOCAL)
ffffffff8221372c-ffffffff822137ed: fib_rebalance.cold (STB_LOCAL)
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
void fib_rebalance(struct fib_info *fi);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_semantics.c (ffff800010cb66e8)
Location: net/ipv4/fib_semantics.c:757
Inline: True
Direct callers:
  - net/ipv4/fib_semantics.c:fib_sync_up
  - net/ipv4/fib_semantics.c:fib_sync_down_dev
  - net/ipv4/fib_semantics.c:fib_create_info
```
**Symbols:**

```
ffff800010cb66e8-ffff800010cb6878: fib_rebalance (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline, Transformation ⚠️</summary>

```c
void fib_rebalance(struct fib_info *fi);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv4/fib_semantics.c (c0dc2358)
Location: net/ipv4/fib_semantics.c:757
Inline: True
Direct callers:
  - net/ipv4/fib_semantics.c:fib_sync_up
  - net/ipv4/fib_semantics.c:fib_sync_down_dev
  - net/ipv4/fib_semantics.c:fib_create_info
```
**Symbols:**

```
c0dc2358-c0dc2510: fib_rebalance.part.0 (STB_LOCAL)
c0dc2510-c0dc256c: fib_rebalance (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void fib_rebalance(struct fib_info *fi);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_semantics.c (c000000000dcece0)
Location: net/ipv4/fib_semantics.c:757
Inline: True
Direct callers:
  - net/ipv4/fib_semantics.c:fib_sync_up
  - net/ipv4/fib_semantics.c:fib_sync_down_dev
  - net/ipv4/fib_semantics.c:fib_create_info
```
**Symbols:**

```
c000000000dcece0-c000000000dceed8: fib_rebalance (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void fib_rebalance(struct fib_info *fi);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_semantics.c (ffffffe00080e21a)
Location: net/ipv4/fib_semantics.c:757
Inline: True
Direct callers:
  - net/ipv4/fib_semantics.c:fib_sync_up
  - net/ipv4/fib_semantics.c:fib_sync_down_dev
  - net/ipv4/fib_semantics.c:fib_create_info
```
**Symbols:**

```
ffffffe00080e21a-ffffffe00080e368: fib_rebalance (STB_LOCAL)
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
void fib_rebalance(struct fib_info *fi);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_semantics.c (ffffffff8199e710)
Location: net/ipv4/fib_semantics.c:757
Inline: True
Direct callers:
  - net/ipv4/fib_semantics.c:fib_sync_up
  - net/ipv4/fib_semantics.c:fib_sync_down_dev
  - net/ipv4/fib_semantics.c:fib_create_info
```
**Symbols:**

```
ffffffff8199e710-ffffffff8199e874: fib_rebalance (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void fib_rebalance(struct fib_info *fi);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_semantics.c (ffffffff819581d0)
Location: net/ipv4/fib_semantics.c:757
Inline: True
Direct callers:
  - net/ipv4/fib_semantics.c:fib_sync_up
  - net/ipv4/fib_semantics.c:fib_sync_down_dev
  - net/ipv4/fib_semantics.c:fib_create_info
```
**Symbols:**

```
ffffffff819581d0-ffffffff81958334: fib_rebalance (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void fib_rebalance(struct fib_info *fi);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_semantics.c (ffffffff81a08fb0)
Location: net/ipv4/fib_semantics.c:757
Inline: True
Direct callers:
  - net/ipv4/fib_semantics.c:fib_sync_up
  - net/ipv4/fib_semantics.c:fib_sync_down_dev
  - net/ipv4/fib_semantics.c:fib_create_info
```
**Symbols:**

```
ffffffff81a08fb0-ffffffff81a09114: fib_rebalance (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void fib_rebalance(struct fib_info *fi);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_semantics.c (ffffffff81a13760)
Location: net/ipv4/fib_semantics.c:757
Inline: True
Direct callers:
  - net/ipv4/fib_semantics.c:fib_sync_up
  - net/ipv4/fib_semantics.c:fib_sync_down_dev
  - net/ipv4/fib_semantics.c:fib_create_info
```
**Symbols:**

```
ffffffff81a13760-ffffffff81a138c4: fib_rebalance (STB_LOCAL)
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
