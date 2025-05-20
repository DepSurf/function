# Function: <code>xfrm_inner_mode_input</code>

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
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/xfrm/xfrm_input.c (ffffffff819f4940)
Location: net/xfrm/xfrm_input.c:430
Inline: True
Direct callers:
  - net/xfrm/xfrm_input.c:xfrm_input
```
**Symbols:**

```
ffffffff819f4940-ffffffff819f51e2: xfrm_inner_mode_input.isra.0 (STB_LOCAL)
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
In net/xfrm/xfrm_input.c (ffffffff81a2b5f0)
Location: net/xfrm/xfrm_input.c:430
Inline: True
Direct callers:
  - net/xfrm/xfrm_input.c:xfrm_input
```
**Symbols:**

```
ffffffff81a2b5f0-ffffffff81a2be92: xfrm_inner_mode_input.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int xfrm_inner_mode_input(struct xfrm_state *x, const struct xfrm_mode *inner_mode, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_input.c (ffffffff81b1e1e0)
Location: net/xfrm/xfrm_input.c:432
Inline: False
Direct callers:
  - net/xfrm/xfrm_input.c:xfrm_input
```
**Symbols:**

```
ffffffff81b1e1e0-ffffffff81b1e34e: xfrm_inner_mode_input (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int xfrm_inner_mode_input(struct xfrm_state *x, const struct xfrm_mode *inner_mode, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_input.c (ffffffff81b2cab0)
Location: net/xfrm/xfrm_input.c:434
Inline: False
Direct callers:
  - net/xfrm/xfrm_input.c:xfrm_input
```
**Symbols:**

```
ffffffff81b2cab0-ffffffff81b2cc19: xfrm_inner_mode_input (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int xfrm_inner_mode_input(struct xfrm_state *x, const struct xfrm_mode *inner_mode, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_input.c (ffffffff81b1a6f0)
Location: net/xfrm/xfrm_input.c:434
Inline: False
Direct callers:
  - net/xfrm/xfrm_input.c:xfrm_input
```
**Symbols:**

```
ffffffff81b1a6f0-ffffffff81b1a854: xfrm_inner_mode_input (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int xfrm_inner_mode_input(struct xfrm_state *x, const struct xfrm_mode *inner_mode, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_input.c (ffffffff81bded10)
Location: net/xfrm/xfrm_input.c:434
Inline: False
Direct callers:
  - net/xfrm/xfrm_input.c:xfrm_input
```
**Symbols:**

```
ffffffff81bded10-ffffffff81bdee74: xfrm_inner_mode_input (STB_LOCAL)
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
In net/xfrm/xfrm_input.c (ffffffff81d76169)
Location: net/xfrm/xfrm_input.c:434
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_input
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
In net/xfrm/xfrm_input.c (ffffffff81f428b5)
Location: net/xfrm/xfrm_input.c:435
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_input
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
In net/xfrm/xfrm_input.c (ffffffff81fa2098)
Location: net/xfrm/xfrm_input.c:423
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_input
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
In net/xfrm/xfrm_input.c (ffffffff8206f48e)
Location: net/xfrm/xfrm_input.c:423
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_input
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
In net/xfrm/xfrm_input.c (ffff800010cea090)
Location: net/xfrm/xfrm_input.c:430
Inline: True
Direct callers:
  - net/xfrm/xfrm_input.c:xfrm_input
```
**Symbols:**

```
ffff800010cea090-ffff800010cea958: xfrm_inner_mode_input.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int xfrm_inner_mode_input(struct xfrm_state *x, const struct xfrm_mode *inner_mode, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_input.c (c0df2050)
Location: net/xfrm/xfrm_input.c:430
Inline: False
Direct callers:
  - net/xfrm/xfrm_input.c:xfrm_input
```
**Symbols:**

```
c0df2050-c0df2970: xfrm_inner_mode_input (STB_LOCAL)
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
In net/xfrm/xfrm_input.c (c000000000e0dad0)
Location: net/xfrm/xfrm_input.c:430
Inline: True
Direct callers:
  - net/xfrm/xfrm_input.c:xfrm_input
```
**Symbols:**

```
c000000000e0dad0-c000000000e0e598: xfrm_inner_mode_input.isra.0 (STB_LOCAL)
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
In net/xfrm/xfrm_input.c (ffffffe000837d28)
Location: net/xfrm/xfrm_input.c:430
Inline: True
Direct callers:
  - net/xfrm/xfrm_input.c:xfrm_input
```
**Symbols:**

```
ffffffe000837d28-ffffffe0008384e4: xfrm_inner_mode_input.isra.0 (STB_LOCAL)
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
In net/xfrm/xfrm_input.c (ffffffff819cac80)
Location: net/xfrm/xfrm_input.c:430
Inline: True
Direct callers:
  - net/xfrm/xfrm_input.c:xfrm_input
```
**Symbols:**

```
ffffffff819cac80-ffffffff819cb522: xfrm_inner_mode_input.isra.0 (STB_LOCAL)
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
In net/xfrm/xfrm_input.c (ffffffff81987a70)
Location: net/xfrm/xfrm_input.c:430
Inline: True
Direct callers:
  - net/xfrm/xfrm_input.c:xfrm_input
```
**Symbols:**

```
ffffffff81987a70-ffffffff81988312: xfrm_inner_mode_input.isra.0 (STB_LOCAL)
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
In net/xfrm/xfrm_input.c (ffffffff81a35700)
Location: net/xfrm/xfrm_input.c:430
Inline: True
Direct callers:
  - net/xfrm/xfrm_input.c:xfrm_input
```
**Symbols:**

```
ffffffff81a35700-ffffffff81a35fa2: xfrm_inner_mode_input.isra.0 (STB_LOCAL)
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
In net/xfrm/xfrm_input.c (ffffffff81a41060)
Location: net/xfrm/xfrm_input.c:430
Inline: True
Direct callers:
  - net/xfrm/xfrm_input.c:xfrm_input
```
**Symbols:**

```
ffffffff81a41060-ffffffff81a41912: xfrm_inner_mode_input.isra.0 (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
</ul>
