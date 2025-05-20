# Function: <code>xfrm_get_mode</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct xfrm_mode *xfrm_get_mode(unsigned int encap, int family);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_state.c (ffffffff817b7710)
Location: net/xfrm/xfrm_state.c:298
Inline: False
Direct callers:
  - net/xfrm/xfrm_state.c:__xfrm_init_state
  - net/xfrm/xfrm_state.c:__xfrm_init_state
  - net/xfrm/xfrm_state.c:__xfrm_init_state
  - net/xfrm/xfrm_state.c:__xfrm_init_state
```
**Symbols:**

```
ffffffff817b7710-ffffffff817b77ca: xfrm_get_mode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct xfrm_mode *xfrm_get_mode(unsigned int encap, int family);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_state.c (ffffffff81824760)
Location: net/xfrm/xfrm_state.c:298
Inline: False
Direct callers:
  - net/xfrm/xfrm_state.c:__xfrm_init_state
  - net/xfrm/xfrm_state.c:__xfrm_init_state
  - net/xfrm/xfrm_state.c:__xfrm_init_state
  - net/xfrm/xfrm_state.c:__xfrm_init_state
```
**Symbols:**

```
ffffffff81824760-ffffffff8182480f: xfrm_get_mode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct xfrm_mode *xfrm_get_mode(unsigned int encap, int family);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_state.c (ffffffff81856250)
Location: net/xfrm/xfrm_state.c:316
Inline: False
Direct callers:
  - net/xfrm/xfrm_state.c:__xfrm_init_state
  - net/xfrm/xfrm_state.c:__xfrm_init_state
  - net/xfrm/xfrm_state.c:__xfrm_init_state
  - net/xfrm/xfrm_state.c:__xfrm_init_state
```
**Symbols:**

```
ffffffff81856250-ffffffff818562ff: xfrm_get_mode (STB_LOCAL)
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
In net/xfrm/xfrm_state.c (ffffffff8187a72c)
Location: net/xfrm/xfrm_state.c:386
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:__xfrm_init_state
  - net/xfrm/xfrm_state.c:__xfrm_init_state
  - net/xfrm/xfrm_state.c:__xfrm_init_state
  - net/xfrm/xfrm_state.c:__xfrm_init_state
Direct callers:
  - net/xfrm/xfrm_state.c:__xfrm_init_state
  - net/xfrm/xfrm_state.c:__xfrm_init_state
  - net/xfrm/xfrm_state.c:__xfrm_init_state
  - net/xfrm/xfrm_state.c:__xfrm_init_state
```
**Symbols:**

```
ffffffff8187a600-ffffffff8187a6aa: xfrm_get_mode.part.23 (STB_LOCAL)
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
In net/xfrm/xfrm_state.c (ffffffff818fb1b5)
Location: net/xfrm/xfrm_state.c:395
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:__xfrm_init_state
  - net/xfrm/xfrm_state.c:__xfrm_init_state
  - net/xfrm/xfrm_state.c:__xfrm_init_state
  - net/xfrm/xfrm_state.c:__xfrm_init_state
Direct callers:
  - net/xfrm/xfrm_state.c:__xfrm_init_state
  - net/xfrm/xfrm_state.c:__xfrm_init_state
  - net/xfrm/xfrm_state.c:__xfrm_init_state
  - net/xfrm/xfrm_state.c:__xfrm_init_state
```
**Symbols:**

```
ffffffff818fb070-ffffffff818fb11a: xfrm_get_mode.part.23 (STB_LOCAL)
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
In net/xfrm/xfrm_state.c (ffffffff81951bec)
Location: net/xfrm/xfrm_state.c:396
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:__xfrm_init_state
  - net/xfrm/xfrm_state.c:__xfrm_init_state
  - net/xfrm/xfrm_state.c:__xfrm_init_state
  - net/xfrm/xfrm_state.c:__xfrm_init_state
Direct callers:
  - net/xfrm/xfrm_state.c:__xfrm_init_state
  - net/xfrm/xfrm_state.c:__xfrm_init_state
  - net/xfrm/xfrm_state.c:__xfrm_init_state
  - net/xfrm/xfrm_state.c:__xfrm_init_state
```
**Symbols:**

```
ffffffff81951aa0-ffffffff81951b4a: xfrm_get_mode.part.35 (STB_LOCAL)
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
In net/xfrm/xfrm_state.c (ffffffff81984f7c)
Location: net/xfrm/xfrm_state.c:396
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:__xfrm_init_state
  - net/xfrm/xfrm_state.c:__xfrm_init_state
  - net/xfrm/xfrm_state.c:__xfrm_init_state
  - net/xfrm/xfrm_state.c:__xfrm_init_state
Direct callers:
  - net/xfrm/xfrm_state.c:__xfrm_init_state
  - net/xfrm/xfrm_state.c:__xfrm_init_state
  - net/xfrm/xfrm_state.c:__xfrm_init_state
  - net/xfrm/xfrm_state.c:__xfrm_init_state
```
**Symbols:**

```
ffffffff81984e30-ffffffff81984eda: xfrm_get_mode.part.34 (STB_LOCAL)
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
In net/xfrm/xfrm_state.c (ffffffff819ee705)
Location: net/xfrm/xfrm_state.c:449
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:__xfrm_init_state
  - net/xfrm/xfrm_state.c:__xfrm_init_state
  - net/xfrm/xfrm_state.c:__xfrm_init_state
  - net/xfrm/xfrm_state.c:__xfrm_init_state
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
In net/xfrm/xfrm_state.c (ffffffff81a255e5)
Location: net/xfrm/xfrm_state.c:449
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:__xfrm_init_state
  - net/xfrm/xfrm_state.c:__xfrm_init_state
  - net/xfrm/xfrm_state.c:__xfrm_init_state
  - net/xfrm/xfrm_state.c:__xfrm_init_state
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
In net/xfrm/xfrm_state.c (ffffffff81b18b6a)
Location: net/xfrm/xfrm_state.c:449
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:__xfrm_init_state
  - net/xfrm/xfrm_state.c:__xfrm_init_state
  - net/xfrm/xfrm_state.c:__xfrm_init_state
  - net/xfrm/xfrm_state.c:__xfrm_init_state
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
In net/xfrm/xfrm_state.c (ffffffff81b271ba)
Location: net/xfrm/xfrm_state.c:449
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:__xfrm_init_state
  - net/xfrm/xfrm_state.c:__xfrm_init_state
  - net/xfrm/xfrm_state.c:__xfrm_init_state
  - net/xfrm/xfrm_state.c:__xfrm_init_state
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
In net/xfrm/xfrm_state.c (ffffffff81b14dda)
Location: net/xfrm/xfrm_state.c:448
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:__xfrm_init_state
  - net/xfrm/xfrm_state.c:__xfrm_init_state
  - net/xfrm/xfrm_state.c:__xfrm_init_state
  - net/xfrm/xfrm_state.c:__xfrm_init_state
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
In net/xfrm/xfrm_state.c (ffffffff81bd8f2d)
Location: net/xfrm/xfrm_state.c:469
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:__xfrm_init_state
  - net/xfrm/xfrm_state.c:__xfrm_init_state
  - net/xfrm/xfrm_state.c:__xfrm_init_state
  - net/xfrm/xfrm_state.c:__xfrm_init_state
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
In net/xfrm/xfrm_state.c (ffffffff81d6fcc0)
Location: net/xfrm/xfrm_state.c:470
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:__xfrm_init_state
  - net/xfrm/xfrm_state.c:__xfrm_init_state
  - net/xfrm/xfrm_state.c:__xfrm_init_state
  - net/xfrm/xfrm_state.c:__xfrm_init_state
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
In net/xfrm/xfrm_state.c (ffffffff81f3b4d4)
Location: net/xfrm/xfrm_state.c:491
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:__xfrm_init_state
  - net/xfrm/xfrm_state.c:__xfrm_init_state
  - net/xfrm/xfrm_state.c:__xfrm_init_state
  - net/xfrm/xfrm_state.c:__xfrm_init_state
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
In net/xfrm/xfrm_state.c (ffffffff81f9aef7)
Location: net/xfrm/xfrm_state.c:491
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:__xfrm_init_state
  - net/xfrm/xfrm_state.c:__xfrm_init_state
  - net/xfrm/xfrm_state.c:__xfrm_init_state
  - net/xfrm/xfrm_state.c:__xfrm_init_state
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
In net/xfrm/xfrm_state.c (ffffffff82068257)
Location: net/xfrm/xfrm_state.c:491
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:__xfrm_init_state
  - net/xfrm/xfrm_state.c:__xfrm_init_state
  - net/xfrm/xfrm_state.c:__xfrm_init_state
  - net/xfrm/xfrm_state.c:__xfrm_init_state
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
In net/xfrm/xfrm_state.c (ffff800010ce2aa0)
Location: net/xfrm/xfrm_state.c:449
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:__xfrm_init_state
  - net/xfrm/xfrm_state.c:__xfrm_init_state
  - net/xfrm/xfrm_state.c:__xfrm_init_state
  - net/xfrm/xfrm_state.c:__xfrm_init_state
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
In net/xfrm/xfrm_state.c (c0dec214)
Location: net/xfrm/xfrm_state.c:449
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:__xfrm_init_state
  - net/xfrm/xfrm_state.c:__xfrm_init_state
  - net/xfrm/xfrm_state.c:__xfrm_init_state
  - net/xfrm/xfrm_state.c:__xfrm_init_state
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
In net/xfrm/xfrm_state.c (c000000000e05c90)
Location: net/xfrm/xfrm_state.c:449
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:__xfrm_init_state
  - net/xfrm/xfrm_state.c:__xfrm_init_state
  - net/xfrm/xfrm_state.c:__xfrm_init_state
  - net/xfrm/xfrm_state.c:__xfrm_init_state
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
In net/xfrm/xfrm_state.c (ffffffe0008313bc)
Location: net/xfrm/xfrm_state.c:449
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:__xfrm_init_state
  - net/xfrm/xfrm_state.c:__xfrm_init_state
  - net/xfrm/xfrm_state.c:__xfrm_init_state
  - net/xfrm/xfrm_state.c:__xfrm_init_state
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
In net/xfrm/xfrm_state.c (ffffffff819c4c75)
Location: net/xfrm/xfrm_state.c:449
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:__xfrm_init_state
  - net/xfrm/xfrm_state.c:__xfrm_init_state
  - net/xfrm/xfrm_state.c:__xfrm_init_state
  - net/xfrm/xfrm_state.c:__xfrm_init_state
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
In net/xfrm/xfrm_state.c (ffffffff81981a65)
Location: net/xfrm/xfrm_state.c:449
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:__xfrm_init_state
  - net/xfrm/xfrm_state.c:__xfrm_init_state
  - net/xfrm/xfrm_state.c:__xfrm_init_state
  - net/xfrm/xfrm_state.c:__xfrm_init_state
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
In net/xfrm/xfrm_state.c (ffffffff81a2f6f5)
Location: net/xfrm/xfrm_state.c:449
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:__xfrm_init_state
  - net/xfrm/xfrm_state.c:__xfrm_init_state
  - net/xfrm/xfrm_state.c:__xfrm_init_state
  - net/xfrm/xfrm_state.c:__xfrm_init_state
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
In net/xfrm/xfrm_state.c (ffffffff81a3b057)
Location: net/xfrm/xfrm_state.c:449
Inline: True
Inline callers:
  - net/xfrm/xfrm_state.c:__xfrm_init_state
  - net/xfrm/xfrm_state.c:__xfrm_init_state
  - net/xfrm/xfrm_state.c:__xfrm_init_state
  - net/xfrm/xfrm_state.c:__xfrm_init_state
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
