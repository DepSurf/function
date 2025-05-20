# Function: <code>mpol_set_nodemask</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int mpol_set_nodemask(struct mempolicy *pol, const nodemask_t *nodes, struct nodemask_scratch *nsc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffffffff811e0940)
Location: mm/mempolicy.c:214
Inline: False
Direct callers:
  - mm/mempolicy.c:do_set_mempolicy
  - mm/mempolicy.c:do_mbind
  - mm/mempolicy.c:mpol_shared_policy_init
```
**Symbols:**

```
ffffffff811e0940-ffffffff811e0a0f: mpol_set_nodemask (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int mpol_set_nodemask(struct mempolicy *pol, const nodemask_t *nodes, struct nodemask_scratch *nsc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffffffff811ff350)
Location: mm/mempolicy.c:213
Inline: False
Direct callers:
  - mm/mempolicy.c:mpol_shared_policy_init
  - mm/mempolicy.c:do_mbind
  - mm/mempolicy.c:do_set_mempolicy
```
**Symbols:**

```
ffffffff811ff350-ffffffff811ff41f: mpol_set_nodemask (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int mpol_set_nodemask(struct mempolicy *pol, const nodemask_t *nodes, struct nodemask_scratch *nsc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/mempolicy.c (ffffffff81210010)
Location: mm/mempolicy.c:213
Inline: False
Direct callers:
  - mm/mempolicy.c:mpol_shared_policy_init
  - mm/mempolicy.c:SYSC_mbind
  - mm/mempolicy.c:do_set_mempolicy
```
**Symbols:**

```
ffffffff81210010-ffffffff812102be: mpol_set_nodemask (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/mempolicy.c (ffffffff8121e9bb)
Location: mm/mempolicy.c:201
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_shared_policy_init
  - mm/mempolicy.c:SYSC_mbind
  - mm/mempolicy.c:do_set_mempolicy
Direct callers:
  - mm/mempolicy.c:mpol_shared_policy_init
  - mm/mempolicy.c:SYSC_mbind
  - mm/mempolicy.c:do_set_mempolicy
```
**Symbols:**

```
ffffffff8121b490-ffffffff8121b730: mpol_set_nodemask.part.19 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/mempolicy.c (ffffffff81239bdb)
Location: mm/mempolicy.c:203
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_shared_policy_init
  - mm/mempolicy.c:SYSC_mbind
  - mm/mempolicy.c:do_set_mempolicy
Direct callers:
  - mm/mempolicy.c:mpol_shared_policy_init
  - mm/mempolicy.c:SYSC_mbind
  - mm/mempolicy.c:do_set_mempolicy
```
**Symbols:**

```
ffffffff812366b0-ffffffff81236956: mpol_set_nodemask.part.21 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/mempolicy.c (ffffffff8125d1bc)
Location: mm/mempolicy.c:203
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_shared_policy_init
  - mm/mempolicy.c:kernel_mbind
  - mm/mempolicy.c:do_set_mempolicy
Direct callers:
  - mm/mempolicy.c:mpol_shared_policy_init
  - mm/mempolicy.c:kernel_mbind
  - mm/mempolicy.c:do_set_mempolicy
```
**Symbols:**

```
ffffffff81259680-ffffffff81259926: mpol_set_nodemask.part.25 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/mempolicy.c (ffffffff81271a7c)
Location: mm/mempolicy.c:203
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_shared_policy_init
  - mm/mempolicy.c:kernel_mbind
  - mm/mempolicy.c:do_set_mempolicy
Direct callers:
  - mm/mempolicy.c:mpol_shared_policy_init
  - mm/mempolicy.c:kernel_mbind
  - mm/mempolicy.c:do_set_mempolicy
```
**Symbols:**

```
ffffffff8126eb00-ffffffff8126eda6: mpol_set_nodemask.part.27 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/mempolicy.c (ffffffff8128d098)
Location: mm/mempolicy.c:203
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_shared_policy_init
  - mm/mempolicy.c:kernel_mbind
  - mm/mempolicy.c:do_set_mempolicy
Direct callers:
  - mm/mempolicy.c:mpol_shared_policy_init
  - mm/mempolicy.c:kernel_mbind
  - mm/mempolicy.c:do_set_mempolicy
```
**Symbols:**

```
ffffffff8128a170-ffffffff8128a432: mpol_set_nodemask.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/mempolicy.c (ffffffff8129ccc8)
Location: mm/mempolicy.c:203
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_shared_policy_init
  - mm/mempolicy.c:kernel_mbind
  - mm/mempolicy.c:do_set_mempolicy
Direct callers:
  - mm/mempolicy.c:mpol_shared_policy_init
  - mm/mempolicy.c:kernel_mbind
  - mm/mempolicy.c:do_set_mempolicy
```
**Symbols:**

```
ffffffff81299ce0-ffffffff81299fa2: mpol_set_nodemask.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/mempolicy.c (ffffffff812d0858)
Location: mm/mempolicy.c:229
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_shared_policy_init
  - mm/mempolicy.c:do_mbind
  - mm/mempolicy.c:do_set_mempolicy
Direct callers:
  - mm/mempolicy.c:mpol_shared_policy_init
  - mm/mempolicy.c:do_mbind
  - mm/mempolicy.c:do_set_mempolicy
```
**Symbols:**

```
ffffffff812cc250-ffffffff812cc512: mpol_set_nodemask.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/mempolicy.c (ffffffff812dc378)
Location: mm/mempolicy.c:229
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_shared_policy_init
  - mm/mempolicy.c:do_mbind
  - mm/mempolicy.c:do_set_mempolicy
Direct callers:
  - mm/mempolicy.c:mpol_shared_policy_init
  - mm/mempolicy.c:do_mbind
  - mm/mempolicy.c:do_set_mempolicy
```
**Symbols:**

```
ffffffff812d7ae0-ffffffff812d7da7: mpol_set_nodemask.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/mempolicy.c (ffffffff812e3c08)
Location: mm/mempolicy.c:229
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_shared_policy_init
  - mm/mempolicy.c:do_mbind
  - mm/mempolicy.c:do_set_mempolicy
Direct callers:
  - mm/mempolicy.c:mpol_shared_policy_init
  - mm/mempolicy.c:do_mbind
  - mm/mempolicy.c:do_set_mempolicy
```
**Symbols:**

```
ffffffff812df670-ffffffff812df935: mpol_set_nodemask.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/mempolicy.c (ffffffff8132aee8)
Location: mm/mempolicy.c:221
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_shared_policy_init
  - mm/mempolicy.c:do_mbind
  - mm/mempolicy.c:do_set_mempolicy
Direct callers:
  - mm/mempolicy.c:mpol_shared_policy_init
  - mm/mempolicy.c:do_mbind
  - mm/mempolicy.c:do_set_mempolicy
```
**Symbols:**

```
ffffffff81326340-ffffffff813265cd: mpol_set_nodemask.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/mempolicy.c (ffffffff8139a8f7)
Location: mm/mempolicy.c:224
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_shared_policy_init
  - mm/mempolicy.c:do_mbind
  - mm/mempolicy.c:do_set_mempolicy
Direct callers:
  - mm/mempolicy.c:mpol_shared_policy_init
  - mm/mempolicy.c:do_mbind
  - mm/mempolicy.c:do_set_mempolicy
```
**Symbols:**

```
ffffffff81395390-ffffffff81395613: mpol_set_nodemask.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/mempolicy.c (ffffffff8141a937)
Location: mm/mempolicy.c:224
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_shared_policy_init
  - mm/mempolicy.c:do_mbind
  - mm/mempolicy.c:do_set_mempolicy
Direct callers:
  - mm/mempolicy.c:mpol_shared_policy_init
  - mm/mempolicy.c:do_mbind
  - mm/mempolicy.c:do_set_mempolicy
```
**Symbols:**

```
ffffffff81414ec0-ffffffff81415143: mpol_set_nodemask.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/mempolicy.c (ffffffff8144deab)
Location: mm/mempolicy.c:224
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_shared_policy_init
  - mm/mempolicy.c:do_mbind
  - mm/mempolicy.c:do_set_mempolicy
Direct callers:
  - mm/mempolicy.c:mpol_shared_policy_init
  - mm/mempolicy.c:do_mbind
  - mm/mempolicy.c:do_set_mempolicy
```
**Symbols:**

```
ffffffff81448460-ffffffff814486e3: mpol_set_nodemask.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/mempolicy.c (ffffffff81487883)
Location: mm/mempolicy.c:229
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_shared_policy_init
  - mm/mempolicy.c:do_mbind
  - mm/mempolicy.c:do_set_mempolicy
Direct callers:
  - mm/mempolicy.c:mpol_shared_policy_init
  - mm/mempolicy.c:do_mbind
  - mm/mempolicy.c:do_set_mempolicy
```
**Symbols:**

```
ffffffff81481cc0-ffffffff81481f43: mpol_set_nodemask.part.0 (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/mempolicy.c (ffff80001033bce0)
Location: mm/mempolicy.c:203
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_shared_policy_init
  - mm/mempolicy.c:kernel_mbind
  - mm/mempolicy.c:do_set_mempolicy
Direct callers:
  - mm/mempolicy.c:mpol_shared_policy_init
  - mm/mempolicy.c:kernel_mbind
  - mm/mempolicy.c:do_set_mempolicy
```
**Symbols:**

```
ffff800010338a50-ffff800010338b70: mpol_set_nodemask.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/mempolicy.c (c000000000416bc8)
Location: mm/mempolicy.c:203
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_shared_policy_init
  - mm/mempolicy.c:do_mbind
  - mm/mempolicy.c:do_set_mempolicy
Direct callers:
  - mm/mempolicy.c:mpol_shared_policy_init
  - mm/mempolicy.c:do_mbind
  - mm/mempolicy.c:do_set_mempolicy
```
**Symbols:**

```
c000000000411f90-c000000000412164: mpol_set_nodemask.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/mempolicy.c (ffffffff812952a8)
Location: mm/mempolicy.c:203
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_shared_policy_init
  - mm/mempolicy.c:kernel_mbind
  - mm/mempolicy.c:do_set_mempolicy
Direct callers:
  - mm/mempolicy.c:mpol_shared_policy_init
  - mm/mempolicy.c:kernel_mbind
  - mm/mempolicy.c:do_set_mempolicy
```
**Symbols:**

```
ffffffff812922c0-ffffffff81292582: mpol_set_nodemask.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/mempolicy.c (ffffffff81286eb8)
Location: mm/mempolicy.c:203
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_shared_policy_init
  - mm/mempolicy.c:kernel_mbind
  - mm/mempolicy.c:do_set_mempolicy
Direct callers:
  - mm/mempolicy.c:mpol_shared_policy_init
  - mm/mempolicy.c:kernel_mbind
  - mm/mempolicy.c:do_set_mempolicy
```
**Symbols:**

```
ffffffff81283ed0-ffffffff81284192: mpol_set_nodemask.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/mempolicy.c (ffffffff812930b8)
Location: mm/mempolicy.c:203
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_shared_policy_init
  - mm/mempolicy.c:kernel_mbind
  - mm/mempolicy.c:do_set_mempolicy
Direct callers:
  - mm/mempolicy.c:mpol_shared_policy_init
  - mm/mempolicy.c:kernel_mbind
  - mm/mempolicy.c:do_set_mempolicy
```
**Symbols:**

```
ffffffff812900d0-ffffffff81290392: mpol_set_nodemask.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/mempolicy.c (ffffffff812a2eee)
Location: mm/mempolicy.c:203
Inline: True
Inline callers:
  - mm/mempolicy.c:mpol_shared_policy_init
  - mm/mempolicy.c:kernel_mbind
  - mm/mempolicy.c:do_set_mempolicy
Direct callers:
  - mm/mempolicy.c:mpol_shared_policy_init
  - mm/mempolicy.c:kernel_mbind
  - mm/mempolicy.c:do_set_mempolicy
```
**Symbols:**

```
ffffffff8129ff00-ffffffff812a01c2: mpol_set_nodemask.part.0 (STB_LOCAL)
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
</ul>
