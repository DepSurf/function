# Function: <code>xfrm6_remove_tunnel_encap</code>

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
In net/xfrm/xfrm_input.c (ffffffff819f4dab)
Location: net/xfrm/xfrm_input.c:263
Inline: True
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
In net/xfrm/xfrm_input.c (ffffffff81a2ba5b)
Location: net/xfrm/xfrm_input.c:263
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int xfrm6_remove_tunnel_encap(struct xfrm_state *x, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_input.c (ffffffff81b1dcc0)
Location: net/xfrm/xfrm_input.c:264
Inline: False
Direct callers:
  - net/xfrm/xfrm_input.c:xfrm_prepare_input
```
**Symbols:**

```
ffffffff81b1dcc0-ffffffff81b1de6a: xfrm6_remove_tunnel_encap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int xfrm6_remove_tunnel_encap(struct xfrm_state *x, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_input.c (ffffffff81b2c590)
Location: net/xfrm/xfrm_input.c:266
Inline: False
Direct callers:
  - net/xfrm/xfrm_input.c:xfrm_prepare_input
```
**Symbols:**

```
ffffffff81b2c590-ffffffff81b2c738: xfrm6_remove_tunnel_encap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int xfrm6_remove_tunnel_encap(struct xfrm_state *x, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_input.c (ffffffff81b1a1f0)
Location: net/xfrm/xfrm_input.c:266
Inline: False
Direct callers:
  - net/xfrm/xfrm_input.c:xfrm_prepare_input
```
**Symbols:**

```
ffffffff81b1a1f0-ffffffff81b1a38c: xfrm6_remove_tunnel_encap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int xfrm6_remove_tunnel_encap(struct xfrm_state *x, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_input.c (ffffffff81bde810)
Location: net/xfrm/xfrm_input.c:266
Inline: False
Direct callers:
  - net/xfrm/xfrm_input.c:xfrm_prepare_input
```
**Symbols:**

```
ffffffff81bde810-ffffffff81bde9ac: xfrm6_remove_tunnel_encap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int xfrm6_remove_tunnel_encap(struct xfrm_state *x, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_input.c (ffffffff81d75660)
Location: net/xfrm/xfrm_input.c:266
Inline: False
Direct callers:
  - net/xfrm/xfrm_input.c:xfrm_prepare_input
```
**Symbols:**

```
ffffffff81d75660-ffffffff81d75820: xfrm6_remove_tunnel_encap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int xfrm6_remove_tunnel_encap(struct xfrm_state *x, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_input.c (ffffffff81f41c80)
Location: net/xfrm/xfrm_input.c:268
Inline: False
Direct callers:
  - net/xfrm/xfrm_input.c:xfrm_prepare_input
```
**Symbols:**

```
ffffffff81f41c80-ffffffff81f41e3d: xfrm6_remove_tunnel_encap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int xfrm6_remove_tunnel_encap(struct xfrm_state *x, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_input.c (ffffffff81fa1510)
Location: net/xfrm/xfrm_input.c:270
Inline: False
Direct callers:
  - net/xfrm/xfrm_input.c:xfrm_prepare_input
```
**Symbols:**

```
ffffffff81fa1510-ffffffff81fa16bc: xfrm6_remove_tunnel_encap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int xfrm6_remove_tunnel_encap(struct xfrm_state *x, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_input.c (ffffffff8206e830)
Location: net/xfrm/xfrm_input.c:270
Inline: False
Direct callers:
  - net/xfrm/xfrm_input.c:xfrm_prepare_input
```
**Symbols:**

```
ffffffff8206e830-ffffffff8206e9dc: xfrm6_remove_tunnel_encap (STB_LOCAL)
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
In net/xfrm/xfrm_input.c (ffff800010cea504)
Location: net/xfrm/xfrm_input.c:263
Inline: True
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
In net/xfrm/xfrm_input.c (c0df22ac)
Location: net/xfrm/xfrm_input.c:263
Inline: True
Inline callers:
  - net/xfrm/xfrm_input.c:xfrm_inner_mode_input
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
In net/xfrm/xfrm_input.c (c000000000e0e0d4)
Location: net/xfrm/xfrm_input.c:263
Inline: True
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
In net/xfrm/xfrm_input.c (ffffffe0008380f8)
Location: net/xfrm/xfrm_input.c:263
Inline: True
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
In net/xfrm/xfrm_input.c (ffffffff819cb0eb)
Location: net/xfrm/xfrm_input.c:263
Inline: True
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
In net/xfrm/xfrm_input.c (ffffffff81987edb)
Location: net/xfrm/xfrm_input.c:263
Inline: True
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
In net/xfrm/xfrm_input.c (ffffffff81a35b6b)
Location: net/xfrm/xfrm_input.c:263
Inline: True
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
In net/xfrm/xfrm_input.c (ffffffff81a414db)
Location: net/xfrm/xfrm_input.c:263
Inline: True
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
