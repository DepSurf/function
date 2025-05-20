# Function: <code>xfrm6_tunnel_encap_add</code>

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
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_output.c (ffffffff819f6217)
Location: net/xfrm/xfrm_output.c:236
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
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
In net/xfrm/xfrm_output.c (ffffffff81a2ce97)
Location: net/xfrm/xfrm_output.c:236
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int xfrm6_tunnel_encap_add(struct xfrm_state *x, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_output.c (ffffffff81b1ed90)
Location: net/xfrm/xfrm_output.c:242
Inline: False
Direct callers:
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
```
**Symbols:**

```
ffffffff81b1ed90-ffffffff81b1eef1: xfrm6_tunnel_encap_add (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int xfrm6_tunnel_encap_add(struct xfrm_state *x, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_output.c (ffffffff81b2d640)
Location: net/xfrm/xfrm_output.c:242
Inline: False
Direct callers:
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
```
**Symbols:**

```
ffffffff81b2d640-ffffffff81b2d7a1: xfrm6_tunnel_encap_add (STB_LOCAL)
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
In net/xfrm/xfrm_output.c (ffffffff81b1b300)
Location: net/xfrm/xfrm_output.c:242
Inline: True
Direct callers:
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
```
**Symbols:**

```
ffffffff81b1b300-ffffffff81b1b466: xfrm6_tunnel_encap_add.constprop.0 (STB_LOCAL)
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
In net/xfrm/xfrm_output.c (ffffffff81bdfb70)
Location: net/xfrm/xfrm_output.c:319
Inline: True
Direct callers:
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
```
**Symbols:**

```
ffffffff81bdfb70-ffffffff81bdfcd6: xfrm6_tunnel_encap_add.constprop.0 (STB_LOCAL)
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
In net/xfrm/xfrm_output.c (ffffffff81d76a50)
Location: net/xfrm/xfrm_output.c:320
Inline: True
Direct callers:
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
```
**Symbols:**

```
ffffffff81d76a50-ffffffff81d76bbf: xfrm6_tunnel_encap_add.constprop.0 (STB_LOCAL)
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
In net/xfrm/xfrm_output.c (ffffffff81f43280)
Location: net/xfrm/xfrm_output.c:318
Inline: True
Direct callers:
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
```
**Symbols:**

```
ffffffff81f43280-ffffffff81f433f8: xfrm6_tunnel_encap_add.constprop.0 (STB_LOCAL)
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
In net/xfrm/xfrm_output.c (ffffffff81fa2a80)
Location: net/xfrm/xfrm_output.c:319
Inline: True
Direct callers:
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
```
**Symbols:**

```
ffffffff81fa2a80-ffffffff81fa2bf6: xfrm6_tunnel_encap_add.constprop.0 (STB_LOCAL)
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
In net/xfrm/xfrm_output.c (ffffffff8206fd80)
Location: net/xfrm/xfrm_output.c:319
Inline: True
Direct callers:
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
```
**Symbols:**

```
ffffffff8206fd80-ffffffff8206fef6: xfrm6_tunnel_encap_add.constprop.0 (STB_LOCAL)
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
In net/xfrm/xfrm_output.c (ffff800010cebadc)
Location: net/xfrm/xfrm_output.c:236
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
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
In net/xfrm/xfrm_output.c (c0df382c)
Location: net/xfrm/xfrm_output.c:236
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
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
In net/xfrm/xfrm_output.c (c000000000e0fa20)
Location: net/xfrm/xfrm_output.c:236
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
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
In net/xfrm/xfrm_output.c (ffffffe0008393f2)
Location: net/xfrm/xfrm_output.c:236
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
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
In net/xfrm/xfrm_output.c (ffffffff819cc527)
Location: net/xfrm/xfrm_output.c:236
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
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
In net/xfrm/xfrm_output.c (ffffffff81989317)
Location: net/xfrm/xfrm_output.c:236
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
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
In net/xfrm/xfrm_output.c (ffffffff81a36fa7)
Location: net/xfrm/xfrm_output.c:236
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
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
In net/xfrm/xfrm_output.c (ffffffff81a42937)
Location: net/xfrm/xfrm_output.c:236
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
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
</ul>
