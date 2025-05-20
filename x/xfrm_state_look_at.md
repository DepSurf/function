# Function: <code>xfrm_state_look_at</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
void xfrm_state_look_at(struct xfrm_policy *pol, struct xfrm_state *x, const struct flowi *fl, short unsigned int family, struct xfrm_state **best, int *acq_in_progress, int *error);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_state.c (ffffffff817b7ea0)
Location: net/xfrm/xfrm_state.c:726
Inline: True
Direct callers:
  - net/xfrm/xfrm_state.c:xfrm_state_find
  - net/xfrm/xfrm_state.c:xfrm_state_find
```
**Symbols:**

```
ffffffff817b7ea0-ffffffff817b7f9e: xfrm_state_look_at (STB_LOCAL)
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
In net/xfrm/xfrm_state.c (ffffffff81825320)
Location: net/xfrm/xfrm_state.c:727
Inline: True
Direct callers:
  - net/xfrm/xfrm_state.c:xfrm_state_find
  - net/xfrm/xfrm_state.c:xfrm_state_find
```
**Symbols:**

```
ffffffff81825320-ffffffff81825424: xfrm_state_look_at.constprop.18 (STB_LOCAL)
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
In net/xfrm/xfrm_state.c (ffffffff81856c80)
Location: net/xfrm/xfrm_state.c:738
Inline: True
Direct callers:
  - net/xfrm/xfrm_state.c:xfrm_state_find
  - net/xfrm/xfrm_state.c:xfrm_state_find
```
**Symbols:**

```
ffffffff81856c80-ffffffff81856d84: xfrm_state_look_at.constprop.21 (STB_LOCAL)
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
In net/xfrm/xfrm_state.c (ffffffff8187a9a0)
Location: net/xfrm/xfrm_state.c:883
Inline: True
Direct callers:
  - net/xfrm/xfrm_state.c:xfrm_state_find
  - net/xfrm/xfrm_state.c:xfrm_state_find
```
**Symbols:**

```
ffffffff8187a9a0-ffffffff8187aa9c: xfrm_state_look_at.constprop.24 (STB_LOCAL)
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
In net/xfrm/xfrm_state.c (ffffffff818fb490)
Location: net/xfrm/xfrm_state.c:892
Inline: True
Direct callers:
  - net/xfrm/xfrm_state.c:xfrm_state_find
  - net/xfrm/xfrm_state.c:xfrm_state_find
```
**Symbols:**

```
ffffffff818fb490-ffffffff818fb58c: xfrm_state_look_at.constprop.24 (STB_LOCAL)
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
In net/xfrm/xfrm_state.c (ffffffff81951eb0)
Location: net/xfrm/xfrm_state.c:893
Inline: True
Direct callers:
  - net/xfrm/xfrm_state.c:xfrm_state_find
  - net/xfrm/xfrm_state.c:xfrm_state_find
```
**Symbols:**

```
ffffffff81951eb0-ffffffff81951fb7: xfrm_state_look_at.constprop.36 (STB_LOCAL)
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
In net/xfrm/xfrm_state.c (ffffffff81985240)
Location: net/xfrm/xfrm_state.c:906
Inline: True
Direct callers:
  - net/xfrm/xfrm_state.c:xfrm_state_find
  - net/xfrm/xfrm_state.c:xfrm_state_find
```
**Symbols:**

```
ffffffff81985240-ffffffff81985347: xfrm_state_look_at.constprop.35 (STB_LOCAL)
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
In net/xfrm/xfrm_state.c (ffffffff819ef070)
Location: net/xfrm/xfrm_state.c:999
Inline: True
Direct callers:
  - net/xfrm/xfrm_state.c:xfrm_state_find
  - net/xfrm/xfrm_state.c:xfrm_state_find
```
**Symbols:**

```
ffffffff819ef070-ffffffff819ef17a: xfrm_state_look_at.constprop.0 (STB_LOCAL)
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
In net/xfrm/xfrm_state.c (ffffffff81a25f40)
Location: net/xfrm/xfrm_state.c:1001
Inline: True
Direct callers:
  - net/xfrm/xfrm_state.c:xfrm_state_find
  - net/xfrm/xfrm_state.c:xfrm_state_find
```
**Symbols:**

```
ffffffff81a25f40-ffffffff81a2604a: xfrm_state_look_at.constprop.0 (STB_LOCAL)
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
In net/xfrm/xfrm_state.c (ffffffff81b171d0)
Location: net/xfrm/xfrm_state.c:1004
Inline: True
Direct callers:
  - net/xfrm/xfrm_state.c:xfrm_state_find
  - net/xfrm/xfrm_state.c:xfrm_state_find
```
**Symbols:**

```
ffffffff81b171d0-ffffffff81b172da: xfrm_state_look_at.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void xfrm_state_look_at(struct xfrm_policy *pol, struct xfrm_state *x, const struct flowi *fl, short unsigned int family, struct xfrm_state **best, int *acq_in_progress, int *error);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_state.c (ffffffff81b25200)
Location: net/xfrm/xfrm_state.c:1004
Inline: False
Direct callers:
  - net/xfrm/xfrm_state.c:xfrm_state_find
  - net/xfrm/xfrm_state.c:xfrm_state_find
```
**Symbols:**

```
ffffffff81b25200-ffffffff81b25305: xfrm_state_look_at (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void xfrm_state_look_at(struct xfrm_policy *pol, struct xfrm_state *x, const struct flowi *fl, short unsigned int family, struct xfrm_state **best, int *acq_in_progress, int *error);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_state.c (ffffffff81b12e20)
Location: net/xfrm/xfrm_state.c:1003
Inline: False
Direct callers:
  - net/xfrm/xfrm_state.c:xfrm_state_find
  - net/xfrm/xfrm_state.c:xfrm_state_find
```
**Symbols:**

```
ffffffff81b12e20-ffffffff81b12f25: xfrm_state_look_at (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void xfrm_state_look_at(struct xfrm_policy *pol, struct xfrm_state *x, const struct flowi *fl, short unsigned int family, struct xfrm_state **best, int *acq_in_progress, int *error);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_state.c (ffffffff81bd6d20)
Location: net/xfrm/xfrm_state.c:1027
Inline: False
Direct callers:
  - net/xfrm/xfrm_state.c:xfrm_state_find
  - net/xfrm/xfrm_state.c:xfrm_state_find
```
**Symbols:**

```
ffffffff81bd6d20-ffffffff81bd6e25: xfrm_state_look_at (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void xfrm_state_look_at(struct xfrm_policy *pol, struct xfrm_state *x, const struct flowi *fl, short unsigned int family, struct xfrm_state **best, int *acq_in_progress, int *error);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_state.c (ffffffff81d6d3e0)
Location: net/xfrm/xfrm_state.c:1028
Inline: False
Direct callers:
  - net/xfrm/xfrm_state.c:xfrm_state_find
  - net/xfrm/xfrm_state.c:xfrm_state_find
```
**Symbols:**

```
ffffffff81d6d3e0-ffffffff81d6d516: xfrm_state_look_at (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void xfrm_state_look_at(struct xfrm_policy *pol, struct xfrm_state *x, const struct flowi *fl, short unsigned int family, struct xfrm_state **best, int *acq_in_progress, int *error);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_state.c (ffffffff81f388a0)
Location: net/xfrm/xfrm_state.c:1094
Inline: False
Direct callers:
  - net/xfrm/xfrm_state.c:xfrm_state_find
  - net/xfrm/xfrm_state.c:xfrm_state_find
```
**Symbols:**

```
ffffffff81f388a0-ffffffff81f389d6: xfrm_state_look_at (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void xfrm_state_look_at(struct xfrm_policy *pol, struct xfrm_state *x, const struct flowi *fl, short unsigned int family, struct xfrm_state **best, int *acq_in_progress, int *error);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_state.c (ffffffff81f98290)
Location: net/xfrm/xfrm_state.c:1094
Inline: False
Direct callers:
  - net/xfrm/xfrm_state.c:xfrm_state_find
  - net/xfrm/xfrm_state.c:xfrm_state_find
```
**Symbols:**

```
ffffffff81f98290-ffffffff81f983c6: xfrm_state_look_at (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void xfrm_state_look_at(struct xfrm_policy *pol, struct xfrm_state *x, const struct flowi *fl, short unsigned int family, struct xfrm_state **best, int *acq_in_progress, int *error);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_state.c (ffffffff82065600)
Location: net/xfrm/xfrm_state.c:1094
Inline: False
Direct callers:
  - net/xfrm/xfrm_state.c:xfrm_state_find
  - net/xfrm/xfrm_state.c:xfrm_state_find
```
**Symbols:**

```
ffffffff82065600-ffffffff82065736: xfrm_state_look_at (STB_LOCAL)
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
In net/xfrm/xfrm_state.c (ffff800010ce3140)
Location: net/xfrm/xfrm_state.c:1001
Inline: True
Direct callers:
  - net/xfrm/xfrm_state.c:xfrm_state_find
  - net/xfrm/xfrm_state.c:xfrm_state_find
```
**Symbols:**

```
ffff800010ce3140-ffff800010ce3270: xfrm_state_look_at.isra.0 (STB_LOCAL)
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
In net/xfrm/xfrm_state.c (c0decb24)
Location: net/xfrm/xfrm_state.c:1001
Inline: True
Direct callers:
  - net/xfrm/xfrm_state.c:xfrm_state_find
  - net/xfrm/xfrm_state.c:xfrm_state_find
```
**Symbols:**

```
c0decb24-c0decc2c: xfrm_state_look_at.constprop.0 (STB_LOCAL)
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
In net/xfrm/xfrm_state.c (c000000000e06720)
Location: net/xfrm/xfrm_state.c:1001
Inline: True
Direct callers:
  - net/xfrm/xfrm_state.c:xfrm_state_find
  - net/xfrm/xfrm_state.c:xfrm_state_find
```
**Symbols:**

```
c000000000e06720-c000000000e068f4: xfrm_state_look_at.isra.0 (STB_LOCAL)
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
In net/xfrm/xfrm_state.c (ffffffe000831a38)
Location: net/xfrm/xfrm_state.c:1001
Inline: True
Direct callers:
  - net/xfrm/xfrm_state.c:xfrm_state_find
  - net/xfrm/xfrm_state.c:xfrm_state_find
```
**Symbols:**

```
ffffffe000831a38-ffffffe000831b10: xfrm_state_look_at.isra.0 (STB_LOCAL)
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
In net/xfrm/xfrm_state.c (ffffffff819c55d0)
Location: net/xfrm/xfrm_state.c:1001
Inline: True
Direct callers:
  - net/xfrm/xfrm_state.c:xfrm_state_find
  - net/xfrm/xfrm_state.c:xfrm_state_find
```
**Symbols:**

```
ffffffff819c55d0-ffffffff819c56da: xfrm_state_look_at.constprop.0 (STB_LOCAL)
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
In net/xfrm/xfrm_state.c (ffffffff819823c0)
Location: net/xfrm/xfrm_state.c:1001
Inline: True
Direct callers:
  - net/xfrm/xfrm_state.c:xfrm_state_find
  - net/xfrm/xfrm_state.c:xfrm_state_find
```
**Symbols:**

```
ffffffff819823c0-ffffffff819824ca: xfrm_state_look_at.constprop.0 (STB_LOCAL)
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
In net/xfrm/xfrm_state.c (ffffffff81a30050)
Location: net/xfrm/xfrm_state.c:1001
Inline: True
Direct callers:
  - net/xfrm/xfrm_state.c:xfrm_state_find
  - net/xfrm/xfrm_state.c:xfrm_state_find
```
**Symbols:**

```
ffffffff81a30050-ffffffff81a3015a: xfrm_state_look_at.constprop.0 (STB_LOCAL)
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
In net/xfrm/xfrm_state.c (ffffffff81a3b9d0)
Location: net/xfrm/xfrm_state.c:1001
Inline: True
Direct callers:
  - net/xfrm/xfrm_state.c:xfrm_state_find
  - net/xfrm/xfrm_state.c:xfrm_state_find
```
**Symbols:**

```
ffffffff81a3b9d0-ffffffff81a3bada: xfrm_state_look_at.constprop.0 (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
