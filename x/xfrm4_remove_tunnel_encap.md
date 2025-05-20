# Function: <code>xfrm4_remove_tunnel_encap</code>

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
In net/xfrm/xfrm_input.c (ffffffff819f4ff0)
Location: net/xfrm/xfrm_input.c:225
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
In net/xfrm/xfrm_input.c (ffffffff81a2bca0)
Location: net/xfrm/xfrm_input.c:225
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int xfrm4_remove_tunnel_encap(struct xfrm_state *x, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_input.c (ffffffff81b1de70)
Location: net/xfrm/xfrm_input.c:226
Inline: False
Direct callers:
  - net/xfrm/xfrm_input.c:xfrm_prepare_input
```
**Symbols:**

```
ffffffff81b1de70-ffffffff81b1e04f: xfrm4_remove_tunnel_encap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int xfrm4_remove_tunnel_encap(struct xfrm_state *x, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_input.c (ffffffff81b2c740)
Location: net/xfrm/xfrm_input.c:228
Inline: False
Direct callers:
  - net/xfrm/xfrm_input.c:xfrm_prepare_input
```
**Symbols:**

```
ffffffff81b2c740-ffffffff81b2c920: xfrm4_remove_tunnel_encap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int xfrm4_remove_tunnel_encap(struct xfrm_state *x, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_input.c (ffffffff81b1a390)
Location: net/xfrm/xfrm_input.c:228
Inline: False
Direct callers:
  - net/xfrm/xfrm_input.c:xfrm_prepare_input
```
**Symbols:**

```
ffffffff81b1a390-ffffffff81b1a558: xfrm4_remove_tunnel_encap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int xfrm4_remove_tunnel_encap(struct xfrm_state *x, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_input.c (ffffffff81bde9b0)
Location: net/xfrm/xfrm_input.c:228
Inline: False
Direct callers:
  - net/xfrm/xfrm_input.c:xfrm_prepare_input
```
**Symbols:**

```
ffffffff81bde9b0-ffffffff81bdeb78: xfrm4_remove_tunnel_encap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int xfrm4_remove_tunnel_encap(struct xfrm_state *x, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_input.c (ffffffff81d75820)
Location: net/xfrm/xfrm_input.c:228
Inline: False
Direct callers:
  - net/xfrm/xfrm_input.c:xfrm_prepare_input
```
**Symbols:**

```
ffffffff81d75820-ffffffff81d75a0c: xfrm4_remove_tunnel_encap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int xfrm4_remove_tunnel_encap(struct xfrm_state *x, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_input.c (ffffffff81f41e50)
Location: net/xfrm/xfrm_input.c:230
Inline: False
Direct callers:
  - net/xfrm/xfrm_input.c:xfrm_prepare_input
```
**Symbols:**

```
ffffffff81f41e50-ffffffff81f4203c: xfrm4_remove_tunnel_encap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int xfrm4_remove_tunnel_encap(struct xfrm_state *x, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_input.c (ffffffff81fa16d0)
Location: net/xfrm/xfrm_input.c:233
Inline: False
Direct callers:
  - net/xfrm/xfrm_input.c:xfrm_prepare_input
```
**Symbols:**

```
ffffffff81fa16d0-ffffffff81fa18ab: xfrm4_remove_tunnel_encap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int xfrm4_remove_tunnel_encap(struct xfrm_state *x, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_input.c (ffffffff8206e9f0)
Location: net/xfrm/xfrm_input.c:233
Inline: False
Direct callers:
  - net/xfrm/xfrm_input.c:xfrm_prepare_input
```
**Symbols:**

```
ffffffff8206e9f0-ffffffff8206ebcb: xfrm4_remove_tunnel_encap (STB_LOCAL)
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
In net/xfrm/xfrm_input.c (ffff800010cea6bc)
Location: net/xfrm/xfrm_input.c:225
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
In net/xfrm/xfrm_input.c (c0df23b8)
Location: net/xfrm/xfrm_input.c:225
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
In net/xfrm/xfrm_input.c (c000000000e0e294)
Location: net/xfrm/xfrm_input.c:225
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
In net/xfrm/xfrm_input.c (ffffffe00083829e)
Location: net/xfrm/xfrm_input.c:225
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
In net/xfrm/xfrm_input.c (ffffffff819cb330)
Location: net/xfrm/xfrm_input.c:225
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
In net/xfrm/xfrm_input.c (ffffffff81988120)
Location: net/xfrm/xfrm_input.c:225
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
In net/xfrm/xfrm_input.c (ffffffff81a35db0)
Location: net/xfrm/xfrm_input.c:225
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
In net/xfrm/xfrm_input.c (ffffffff81a41720)
Location: net/xfrm/xfrm_input.c:225
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
