# Function: <code>__xfrm_mode_tunnel_prep</code>

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
In net/xfrm/xfrm_device.c (ffffffff819f8340)
Location: net/xfrm/xfrm_device.c:36
Inline: True
```
**Symbols:**

```
ffffffff819f8340-ffffffff819f83fb: __xfrm_mode_tunnel_prep.isra.0 (STB_LOCAL)
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
In net/xfrm/xfrm_device.c (ffffffff81a2efa0)
Location: net/xfrm/xfrm_device.c:36
Inline: True
```
**Symbols:**

```
ffffffff81a2efa0-ffffffff81a2f05b: __xfrm_mode_tunnel_prep.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void __xfrm_mode_tunnel_prep(struct xfrm_state *x, struct sk_buff *skb, unsigned int hsize);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_device.c (ffffffff81b21970)
Location: net/xfrm/xfrm_device.c:34
Inline: False
Direct callers:
  - net/xfrm/xfrm_device.c:xfrm_outer_mode_prep
  - net/xfrm/xfrm_device.c:xfrm_outer_mode_prep
```
**Symbols:**

```
ffffffff81b21970-ffffffff81b21a32: __xfrm_mode_tunnel_prep (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void __xfrm_mode_tunnel_prep(struct xfrm_state *x, struct sk_buff *skb, unsigned int hsize);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_device.c (ffffffff81b30340)
Location: net/xfrm/xfrm_device.c:34
Inline: False
Direct callers:
  - net/xfrm/xfrm_device.c:xfrm_outer_mode_prep
  - net/xfrm/xfrm_device.c:xfrm_outer_mode_prep
```
**Symbols:**

```
ffffffff81b30340-ffffffff81b30402: __xfrm_mode_tunnel_prep (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void __xfrm_mode_tunnel_prep(struct xfrm_state *x, struct sk_buff *skb, unsigned int hsize);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_device.c (ffffffff81b1e1c0)
Location: net/xfrm/xfrm_device.c:34
Inline: False
Direct callers:
  - net/xfrm/xfrm_device.c:xfrm_outer_mode_prep
  - net/xfrm/xfrm_device.c:xfrm_outer_mode_prep
```
**Symbols:**

```
ffffffff81b1e1c0-ffffffff81b1e27f: __xfrm_mode_tunnel_prep (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void __xfrm_mode_tunnel_prep(struct xfrm_state *x, struct sk_buff *skb, unsigned int hsize);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_device.c (ffffffff81be2cb0)
Location: net/xfrm/xfrm_device.c:34
Inline: False
Direct callers:
  - net/xfrm/xfrm_device.c:xfrm_outer_mode_prep
  - net/xfrm/xfrm_device.c:xfrm_outer_mode_prep
```
**Symbols:**

```
ffffffff81be2cb0-ffffffff81be2d6f: __xfrm_mode_tunnel_prep (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void __xfrm_mode_tunnel_prep(struct xfrm_state *x, struct sk_buff *skb, unsigned int hsize);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_device.c (ffffffff81d79e40)
Location: net/xfrm/xfrm_device.c:34
Inline: False
Direct callers:
  - net/xfrm/xfrm_device.c:xfrm_outer_mode_prep
  - net/xfrm/xfrm_device.c:xfrm_outer_mode_prep
```
**Symbols:**

```
ffffffff81d79e40-ffffffff81d79f0d: __xfrm_mode_tunnel_prep (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void __xfrm_mode_tunnel_prep(struct xfrm_state *x, struct sk_buff *skb, unsigned int hsize);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_device.c (ffffffff81f46c70)
Location: net/xfrm/xfrm_device.c:34
Inline: False
Direct callers:
  - net/xfrm/xfrm_device.c:xfrm_outer_mode_prep
  - net/xfrm/xfrm_device.c:xfrm_outer_mode_prep
```
**Symbols:**

```
ffffffff81f46c70-ffffffff81f46d3d: __xfrm_mode_tunnel_prep (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void __xfrm_mode_tunnel_prep(struct xfrm_state *x, struct sk_buff *skb, unsigned int hsize);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_device.c (ffffffff81fa65c0)
Location: net/xfrm/xfrm_device.c:35
Inline: False
Direct callers:
  - net/xfrm/xfrm_device.c:xfrm_outer_mode_prep
  - net/xfrm/xfrm_device.c:xfrm_outer_mode_prep
```
**Symbols:**

```
ffffffff81fa65c0-ffffffff81fa66d9: __xfrm_mode_tunnel_prep (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void __xfrm_mode_tunnel_prep(struct xfrm_state *x, struct sk_buff *skb, unsigned int hsize);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_device.c (ffffffff820738b0)
Location: net/xfrm/xfrm_device.c:35
Inline: False
Direct callers:
  - net/xfrm/xfrm_device.c:xfrm_outer_mode_prep
  - net/xfrm/xfrm_device.c:xfrm_outer_mode_prep
```
**Symbols:**

```
ffffffff820738b0-ffffffff820739c9: __xfrm_mode_tunnel_prep (STB_LOCAL)
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
In net/xfrm/xfrm_device.c (ffff800010cedcd8)
Location: net/xfrm/xfrm_device.c:36
Inline: True
```
**Symbols:**

```
ffff800010cedcd8-ffff800010ceddd0: __xfrm_mode_tunnel_prep.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void __xfrm_mode_tunnel_prep(struct xfrm_state *x, struct sk_buff *skb, unsigned int hsize);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_device.c (c0df5f20)
Location: net/xfrm/xfrm_device.c:36
Inline: False
```
**Symbols:**

```
c0df5f20-c0df6004: __xfrm_mode_tunnel_prep (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void __xfrm_mode_tunnel_prep(struct xfrm_state *x, struct sk_buff *skb, unsigned int hsize);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_device.c (c000000000e128c0)
Location: net/xfrm/xfrm_device.c:36
Inline: False
```
**Symbols:**

```
c000000000e128c0-c000000000e12a0c: __xfrm_mode_tunnel_prep (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void __xfrm_mode_tunnel_prep(struct xfrm_state *x, struct sk_buff *skb, unsigned int hsize);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_device.c (ffffffe00083b33c)
Location: net/xfrm/xfrm_device.c:36
Inline: False
```
**Symbols:**

```
ffffffe00083b33c-ffffffe00083b406: __xfrm_mode_tunnel_prep (STB_LOCAL)
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
In net/xfrm/xfrm_device.c (ffffffff819ce630)
Location: net/xfrm/xfrm_device.c:36
Inline: True
```
**Symbols:**

```
ffffffff819ce630-ffffffff819ce6eb: __xfrm_mode_tunnel_prep.isra.0 (STB_LOCAL)
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
In net/xfrm/xfrm_device.c (ffffffff8198b410)
Location: net/xfrm/xfrm_device.c:36
Inline: True
```
**Symbols:**

```
ffffffff8198b410-ffffffff8198b4cb: __xfrm_mode_tunnel_prep.isra.0 (STB_LOCAL)
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
In net/xfrm/xfrm_device.c (ffffffff81a390b0)
Location: net/xfrm/xfrm_device.c:36
Inline: True
```
**Symbols:**

```
ffffffff81a390b0-ffffffff81a3916b: __xfrm_mode_tunnel_prep.isra.0 (STB_LOCAL)
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
In net/xfrm/xfrm_device.c (ffffffff81a44ae0)
Location: net/xfrm/xfrm_device.c:36
Inline: True
```
**Symbols:**

```
ffffffff81a44ae0-ffffffff81a44b9b: __xfrm_mode_tunnel_prep.isra.0 (STB_LOCAL)
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
</ul>
