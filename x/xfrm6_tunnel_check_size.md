# Function: <code>xfrm6_tunnel_check_size</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv6/xfrm6_output.c (ffffffff817fd27c)
Location: net/ipv6/xfrm6_output.c:71
Inline: True
Inline callers:
  - net/ipv6/xfrm6_output.c:xfrm6_extract_output
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv6/xfrm6_output.c (ffffffff8186cbac)
Location: net/ipv6/xfrm6_output.c:71
Inline: True
Inline callers:
  - net/ipv6/xfrm6_output.c:xfrm6_extract_output
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv6/xfrm6_output.c (ffffffff8189f99c)
Location: net/ipv6/xfrm6_output.c:71
Inline: True
Inline callers:
  - net/ipv6/xfrm6_output.c:xfrm6_extract_output
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv6/xfrm6_output.c (ffffffff818c5ed3)
Location: net/ipv6/xfrm6_output.c:71
Inline: True
Inline callers:
  - net/ipv6/xfrm6_output.c:xfrm6_extract_output
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
In net/ipv6/xfrm6_output.c (ffffffff81949263)
Location: net/ipv6/xfrm6_output.c:71
Inline: True
Inline callers:
  - net/ipv6/xfrm6_output.c:xfrm6_extract_output
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
In net/ipv6/xfrm6_output.c (ffffffff819a2385)
Location: net/ipv6/xfrm6_output.c:71
Inline: True
Inline callers:
  - net/ipv6/xfrm6_output.c:xfrm6_extract_output
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
In net/ipv6/xfrm6_output.c (ffffffff819d8ff5)
Location: net/ipv6/xfrm6_output.c:71
Inline: True
Inline callers:
  - net/ipv6/xfrm6_output.c:xfrm6_extract_output
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
In net/ipv6/xfrm6_output.c (ffffffff81a47865)
Location: net/ipv6/xfrm6_output.c:67
Inline: True
Inline callers:
  - net/ipv6/xfrm6_output.c:xfrm6_extract_output
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
In net/ipv6/xfrm6_output.c (ffffffff81a7e415)
Location: net/ipv6/xfrm6_output.c:67
Inline: True
Inline callers:
  - net/ipv6/xfrm6_output.c:xfrm6_extract_output
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int xfrm6_tunnel_check_size(struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_output.c (ffffffff81b1eff0)
Location: net/xfrm/xfrm_output.c:674
Inline: False
Direct callers:
  - net/xfrm/xfrm_output.c:xfrm_inner_extract_output
```
**Symbols:**

```
ffffffff81b1eff0-ffffffff81b1f188: xfrm6_tunnel_check_size (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int xfrm6_tunnel_check_size(struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_output.c (ffffffff81b2d8b0)
Location: net/xfrm/xfrm_output.c:674
Inline: False
Direct callers:
  - net/xfrm/xfrm_output.c:xfrm_inner_extract_output
```
**Symbols:**

```
ffffffff81b2d8b0-ffffffff81b2da54: xfrm6_tunnel_check_size (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int xfrm6_tunnel_check_size(struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xfrm/xfrm_output.c (ffffffff81b1b900)
Location: net/xfrm/xfrm_output.c:680
Inline: False
Direct callers:
  - net/xfrm/xfrm_output.c:xfrm_inner_extract_output
```
**Symbols:**

```
ffffffff81b1b900-ffffffff81b1bb5d: xfrm6_tunnel_check_size (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int xfrm6_tunnel_check_size(struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/xfrm/xfrm_output.c (0)
Location: net/xfrm/xfrm_output.c:816
Inline: False
Direct callers:
  - net/xfrm/xfrm_output.c:xfrm_inner_extract_output
```
**Symbols:**

```
ffffffff81be0180-ffffffff81be03e9: xfrm6_tunnel_check_size (STB_LOCAL)
ffffffff81d3ef12-ffffffff81d3ef52: xfrm6_tunnel_check_size.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int xfrm6_tunnel_check_size(struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/xfrm/xfrm_output.c (0)
Location: net/xfrm/xfrm_output.c:817
Inline: False
Direct callers:
  - net/xfrm/xfrm_output.c:xfrm_inner_extract_output
```
**Symbols:**

```
ffffffff81d77090-ffffffff81d772f5: xfrm6_tunnel_check_size (STB_LOCAL)
ffffffff81f0b872-ffffffff81f0b892: xfrm6_tunnel_check_size.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int xfrm6_tunnel_check_size(struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/xfrm/xfrm_output.c (0)
Location: net/xfrm/xfrm_output.c:826
Inline: False
Direct callers:
  - net/xfrm/xfrm_output.c:xfrm_inner_extract_output
```
**Symbols:**

```
ffffffff81f43910-ffffffff81f43b75: xfrm6_tunnel_check_size (STB_LOCAL)
ffffffff820b30dc-ffffffff820b30fc: xfrm6_tunnel_check_size.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int xfrm6_tunnel_check_size(struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/xfrm/xfrm_output.c (0)
Location: net/xfrm/xfrm_output.c:827
Inline: False
Direct callers:
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
```
**Symbols:**

```
ffffffff81fa30f0-ffffffff81fa3351: xfrm6_tunnel_check_size (STB_LOCAL)
ffffffff821342e0-ffffffff821342fd: xfrm6_tunnel_check_size.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int xfrm6_tunnel_check_size(struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/xfrm/xfrm_output.c (0)
Location: net/xfrm/xfrm_output.c:831
Inline: False
Direct callers:
  - net/xfrm/xfrm_output.c:xfrm_outer_mode_output
```
**Symbols:**

```
ffffffff82070770-ffffffff820709cc: xfrm6_tunnel_check_size (STB_LOCAL)
ffffffff82215ec6-ffffffff82215ee3: xfrm6_tunnel_check_size.cold (STB_LOCAL)
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
In net/ipv6/xfrm6_output.c (ffff800010d49880)
Location: net/ipv6/xfrm6_output.c:67
Inline: True
Inline callers:
  - net/ipv6/xfrm6_output.c:xfrm6_extract_output
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
In net/ipv6/xfrm6_output.c (c0e4abdc)
Location: net/ipv6/xfrm6_output.c:67
Inline: True
Inline callers:
  - net/ipv6/xfrm6_output.c:xfrm6_extract_output
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
In net/ipv6/xfrm6_output.c (c000000000e7ef20)
Location: net/ipv6/xfrm6_output.c:67
Inline: True
Inline callers:
  - net/ipv6/xfrm6_output.c:xfrm6_extract_output
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
In net/ipv6/xfrm6_output.c (ffffffe000882c8a)
Location: net/ipv6/xfrm6_output.c:67
Inline: True
Inline callers:
  - net/ipv6/xfrm6_output.c:xfrm6_extract_output
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
In net/ipv6/xfrm6_output.c (ffffffff81a1daa5)
Location: net/ipv6/xfrm6_output.c:67
Inline: True
Inline callers:
  - net/ipv6/xfrm6_output.c:xfrm6_extract_output
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
In net/ipv6/xfrm6_output.c (ffffffff819da865)
Location: net/ipv6/xfrm6_output.c:67
Inline: True
Inline callers:
  - net/ipv6/xfrm6_output.c:xfrm6_extract_output
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
In net/ipv6/xfrm6_output.c (ffffffff81a88525)
Location: net/ipv6/xfrm6_output.c:67
Inline: True
Inline callers:
  - net/ipv6/xfrm6_output.c:xfrm6_extract_output
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
In net/ipv6/xfrm6_output.c (ffffffff81a95175)
Location: net/ipv6/xfrm6_output.c:67
Inline: True
Inline callers:
  - net/ipv6/xfrm6_output.c:xfrm6_extract_output
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
