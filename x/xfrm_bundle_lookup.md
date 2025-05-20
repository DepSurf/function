# Function: <code>xfrm_bundle_lookup</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct flow_cache_object *xfrm_bundle_lookup(struct net *net, const struct flowi *fl, u16 family, u8 dir, struct flow_cache_object *oldflo, void *ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_policy.c (ffffffff817b53a0)
Location: net/xfrm/xfrm_policy.c:2082
Inline: False
```
**Symbols:**

```
ffffffff817b53a0-ffffffff817b5979: xfrm_bundle_lookup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct flow_cache_object *xfrm_bundle_lookup(struct net *net, const struct flowi *fl, u16 family, u8 dir, struct flow_cache_object *oldflo, void *ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_policy.c (ffffffff818223d0)
Location: net/xfrm/xfrm_policy.c:2086
Inline: False
```
**Symbols:**

```
ffffffff818223d0-ffffffff8182299d: xfrm_bundle_lookup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct flow_cache_object *xfrm_bundle_lookup(struct net *net, const struct flowi *fl, u16 family, u8 dir, struct flow_cache_object *oldflo, void *ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_policy.c (ffffffff81853cd0)
Location: net/xfrm/xfrm_policy.c:2114
Inline: False
```
**Symbols:**

```
ffffffff81853cd0-ffffffff8185429d: xfrm_bundle_lookup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct flow_cache_object *xfrm_bundle_lookup(struct net *net, const struct flowi *fl, u16 family, u8 dir, struct flow_cache_object *oldflo, void *ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_policy.c (ffffffff81877620)
Location: net/xfrm/xfrm_policy.c:2055
Inline: False
```
**Symbols:**

```
ffffffff81877620-ffffffff81877d28: xfrm_bundle_lookup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_policy.c (ffffffff818f83c7)
Location: net/xfrm/xfrm_policy.c:2047
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_lookup
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_policy.c (ffffffff8194eeb8)
Location: net/xfrm/xfrm_policy.c:2054
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_lookup
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_policy.c (ffffffff819823e9)
Location: net/xfrm/xfrm_policy.c:2930
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_policy.c (ffffffff819ec080)
Location: net/xfrm/xfrm_policy.c:2929
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_policy.c (ffffffff81a23095)
Location: net/xfrm/xfrm_policy.c:2931
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid
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
In net/xfrm/xfrm_policy.c (ffffffff81b14d20)
Location: net/xfrm/xfrm_policy.c:2921
Inline: True
Direct callers:
  - net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid
```
**Symbols:**

```
ffffffff81b14d20-ffffffff81b151dd: xfrm_bundle_lookup.constprop.0 (STB_LOCAL)
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
In net/xfrm/xfrm_policy.c (ffffffff81b230d0)
Location: net/xfrm/xfrm_policy.c:2942
Inline: True
Direct callers:
  - net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid
```
**Symbols:**

```
ffffffff81b230d0-ffffffff81b235d3: xfrm_bundle_lookup.constprop.0 (STB_LOCAL)
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
In net/xfrm/xfrm_policy.c (ffffffff81b10cc0)
Location: net/xfrm/xfrm_policy.c:2941
Inline: True
Direct callers:
  - net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid
```
**Symbols:**

```
ffffffff81b10cc0-ffffffff81b111e0: xfrm_bundle_lookup.constprop.0 (STB_LOCAL)
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
In net/xfrm/xfrm_policy.c (ffffffff81bd4730)
Location: net/xfrm/xfrm_policy.c:2941
Inline: True
Direct callers:
  - net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid
```
**Symbols:**

```
ffffffff81bd4730-ffffffff81bd4c99: xfrm_bundle_lookup.constprop.0 (STB_LOCAL)
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
In net/xfrm/xfrm_policy.c (ffffffff81d6ae50)
Location: net/xfrm/xfrm_policy.c:2944
Inline: True
Direct callers:
  - net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid
```
**Symbols:**

```
ffffffff81d6ae50-ffffffff81d6b3c2: xfrm_bundle_lookup.constprop.0 (STB_LOCAL)
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
In net/xfrm/xfrm_policy.c (ffffffff81f361d0)
Location: net/xfrm/xfrm_policy.c:3018
Inline: True
Direct callers:
  - net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid
```
**Symbols:**

```
ffffffff81f361d0-ffffffff81f366c1: xfrm_bundle_lookup.constprop.0 (STB_LOCAL)
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
In net/xfrm/xfrm_policy.c (ffffffff81f95b90)
Location: net/xfrm/xfrm_policy.c:3020
Inline: True
Direct callers:
  - net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid
```
**Symbols:**

```
ffffffff81f95b90-ffffffff81f9608e: xfrm_bundle_lookup.constprop.0 (STB_LOCAL)
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
In net/xfrm/xfrm_policy.c (ffffffff82062f80)
Location: net/xfrm/xfrm_policy.c:3042
Inline: True
Direct callers:
  - net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid
```
**Symbols:**

```
ffffffff82062f80-ffffffff82063478: xfrm_bundle_lookup.constprop.0 (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_policy.c (ffff800010ce0124)
Location: net/xfrm/xfrm_policy.c:2931
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_policy.c (c0de9548)
Location: net/xfrm/xfrm_policy.c:2931
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_policy.c (c000000000e023b0)
Location: net/xfrm/xfrm_policy.c:2931
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_policy.c (ffffffe00082efc8)
Location: net/xfrm/xfrm_policy.c:2931
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_policy.c (ffffffff819c2725)
Location: net/xfrm/xfrm_policy.c:2931
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_policy.c (ffffffff8197f515)
Location: net/xfrm/xfrm_policy.c:2931
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_policy.c (ffffffff81a2d1a5)
Location: net/xfrm/xfrm_policy.c:2931
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_policy.c (ffffffff81a388ed)
Location: net/xfrm/xfrm_policy.c:2931
Inline: True
Inline callers:
  - net/xfrm/xfrm_policy.c:xfrm_lookup_with_ifid
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
</ul>
