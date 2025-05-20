# Function: <code>xfrm_expand_policies</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
int xfrm_expand_policies(const struct flowi *fl, u16 family, struct xfrm_policy **pols, int *num_pols, int *num_xfrms);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_policy.c (ffffffff817b1540)
Location: net/xfrm/xfrm_policy.c:1816
Inline: True
Direct callers:
  - net/xfrm/xfrm_policy.c:xfrm_bundle_lookup
  - net/xfrm/xfrm_policy.c:xfrm_lookup
```
**Symbols:**

```
ffffffff817b1540-ffffffff817b15be: xfrm_expand_policies (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/xfrm/xfrm_policy.c (ffffffff8181e4d0)
Location: net/xfrm/xfrm_policy.c:1820
Inline: True
Direct callers:
  - net/xfrm/xfrm_policy.c:xfrm_lookup
  - net/xfrm/xfrm_policy.c:xfrm_bundle_lookup
```
**Symbols:**

```
ffffffff8181e4d0-ffffffff8181e54b: xfrm_expand_policies.constprop.42 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/xfrm/xfrm_policy.c (ffffffff8184fc60)
Location: net/xfrm/xfrm_policy.c:1848
Inline: True
Direct callers:
  - net/xfrm/xfrm_policy.c:xfrm_lookup
  - net/xfrm/xfrm_policy.c:xfrm_bundle_lookup
```
**Symbols:**

```
ffffffff8184fc60-ffffffff8184fcdb: xfrm_expand_policies.constprop.45 (STB_LOCAL)
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
In net/xfrm/xfrm_policy.c (ffffffff81873a20)
Location: net/xfrm/xfrm_policy.c:1799
Inline: True
Direct callers:
  - net/xfrm/xfrm_policy.c:xfrm_lookup
  - net/xfrm/xfrm_policy.c:xfrm_bundle_lookup
```
**Symbols:**

```
ffffffff81873a20-ffffffff81873a9a: xfrm_expand_policies.constprop.37 (STB_LOCAL)
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
In net/xfrm/xfrm_policy.c (ffffffff818f43d0)
Location: net/xfrm/xfrm_policy.c:1670
Inline: True
Direct callers:
  - net/xfrm/xfrm_policy.c:xfrm_lookup
  - net/xfrm/xfrm_policy.c:xfrm_lookup
```
**Symbols:**

```
ffffffff818f43d0-ffffffff818f444a: xfrm_expand_policies.constprop.38 (STB_LOCAL)
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
In net/xfrm/xfrm_policy.c (ffffffff8194a9b0)
Location: net/xfrm/xfrm_policy.c:1673
Inline: True
Direct callers:
  - net/xfrm/xfrm_policy.c:xfrm_lookup
  - net/xfrm/xfrm_policy.c:xfrm_lookup
```
**Symbols:**

```
ffffffff8194a9b0-ffffffff8194aa2a: xfrm_expand_policies.constprop.53 (STB_LOCAL)
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
In net/xfrm/xfrm_policy.c (ffffffff8197cf20)
Location: net/xfrm/xfrm_policy.c:2670
Inline: True
Direct callers:
  - net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid
  - net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid
```
**Symbols:**

```
ffffffff8197cf20-ffffffff8197cf9a: xfrm_expand_policies.constprop.68 (STB_LOCAL)
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
In net/xfrm/xfrm_policy.c (ffffffff819e62f0)
Location: net/xfrm/xfrm_policy.c:2669
Inline: True
Direct callers:
  - net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid
  - net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid
```
**Symbols:**

```
ffffffff819e62f0-ffffffff819e635b: xfrm_expand_policies.constprop.0 (STB_LOCAL)
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
In net/xfrm/xfrm_policy.c (ffffffff81a1d2e0)
Location: net/xfrm/xfrm_policy.c:2671
Inline: True
Direct callers:
  - net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid
  - net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid
```
**Symbols:**

```
ffffffff81a1d2e0-ffffffff81a1d34b: xfrm_expand_policies.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_policy.c (ffffffff81b15266)
Location: net/xfrm/xfrm_policy.c:2661
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid
  - net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_policy.c (ffffffff81b23666)
Location: net/xfrm/xfrm_policy.c:2671
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid
  - net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_policy.c (ffffffff81b11266)
Location: net/xfrm/xfrm_policy.c:2670
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid
  - net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_policy.c (ffffffff81bd4d26)
Location: net/xfrm/xfrm_policy.c:2670
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid
  - net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_policy.c (ffffffff81d6b460)
Location: net/xfrm/xfrm_policy.c:2670
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_policy.c (ffffffff81f36770)
Location: net/xfrm/xfrm_policy.c:2744
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_policy.c (ffffffff81f96136)
Location: net/xfrm/xfrm_policy.c:2746
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_policy.c (ffffffff82063526)
Location: net/xfrm/xfrm_policy.c:2768
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid
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
In net/xfrm/xfrm_policy.c (ffff800010cd98e0)
Location: net/xfrm/xfrm_policy.c:2671
Inline: True
Direct callers:
  - net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid
  - net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid
```
**Symbols:**

```
ffff800010cd98e0-ffff800010cd999c: xfrm_expand_policies.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/xfrm/xfrm_policy.c (c0de3570)
Location: net/xfrm/xfrm_policy.c:2671
Inline: True
Direct callers:
  - net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid
  - net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid
```
**Symbols:**

```
c0de3570-c0de3614: xfrm_expand_policies.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/xfrm/xfrm_policy.c (c000000000dfa690)
Location: net/xfrm/xfrm_policy.c:2671
Inline: True
Direct callers:
  - net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid
  - net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid
```
**Symbols:**

```
c000000000dfa690-c000000000dfa758: xfrm_expand_policies.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/xfrm/xfrm_policy.c (ffffffe000829aac)
Location: net/xfrm/xfrm_policy.c:2671
Inline: True
Direct callers:
  - net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid
  - net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid
```
**Symbols:**

```
ffffffe000829aac-ffffffe000829b4a: xfrm_expand_policies.isra.0 (STB_LOCAL)
```
</details>
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
In net/xfrm/xfrm_policy.c (ffffffff819bc970)
Location: net/xfrm/xfrm_policy.c:2671
Inline: True
Direct callers:
  - net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid
  - net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid
```
**Symbols:**

```
ffffffff819bc970-ffffffff819bc9db: xfrm_expand_policies.constprop.0 (STB_LOCAL)
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
In net/xfrm/xfrm_policy.c (ffffffff81979760)
Location: net/xfrm/xfrm_policy.c:2671
Inline: True
Direct callers:
  - net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid
  - net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid
```
**Symbols:**

```
ffffffff81979760-ffffffff819797cb: xfrm_expand_policies.constprop.0 (STB_LOCAL)
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
In net/xfrm/xfrm_policy.c (ffffffff81a273f0)
Location: net/xfrm/xfrm_policy.c:2671
Inline: True
Direct callers:
  - net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid
  - net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid
```
**Symbols:**

```
ffffffff81a273f0-ffffffff81a2745b: xfrm_expand_policies.constprop.0 (STB_LOCAL)
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
In net/xfrm/xfrm_policy.c (ffffffff81a32a20)
Location: net/xfrm/xfrm_policy.c:2671
Inline: True
Direct callers:
  - net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid
  - net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid
```
**Symbols:**

```
ffffffff81a32a20-ffffffff81a32a8b: xfrm_expand_policies.constprop.0 (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
</ul>
