# Function: <code>nla_put_srh</code>

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
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int nla_put_srh(struct sk_buff *skb, int attrtype, struct seg6_iptunnel_encap *tuninfo);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/seg6_iptunnel.c (ffffffff818a4780)
Location: net/ipv6/seg6_iptunnel.c:58
Inline: False
Direct callers:
  - net/ipv6/seg6_iptunnel.c:seg6_fill_encap_info
```
**Symbols:**

```
ffffffff818a4780-ffffffff818a47e9: nla_put_srh (STB_GLOBAL)
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
In net/ipv6/seg6_iptunnel.c (ffffffff818ca5ee)
Location: net/ipv6/seg6_iptunnel.c:54
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_fill_encap_info
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
In net/ipv6/seg6_iptunnel.c (ffffffff8194ddbe)
Location: net/ipv6/seg6_iptunnel.c:55
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_fill_encap_info
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
In net/ipv6/seg6_iptunnel.c (ffffffff819a7044)
Location: net/ipv6/seg6_iptunnel.c:55
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_fill_encap_info
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
In net/ipv6/seg6_iptunnel.c (ffffffff819ddba4)
Location: net/ipv6/seg6_iptunnel.c:55
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_fill_encap_info
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
In net/ipv6/seg6_iptunnel.c (ffffffff81a4c724)
Location: net/ipv6/seg6_iptunnel.c:50
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_fill_encap_info
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
In net/ipv6/seg6_iptunnel.c (ffffffff81a832f4)
Location: net/ipv6/seg6_iptunnel.c:50
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_fill_encap_info
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
In net/ipv6/seg6_iptunnel.c (ffffffff81b7df64)
Location: net/ipv6/seg6_iptunnel.c:50
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_fill_encap_info
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
In net/ipv6/seg6_iptunnel.c (ffffffff81b8cf74)
Location: net/ipv6/seg6_iptunnel.c:67
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_fill_encap_info
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
In net/ipv6/seg6_iptunnel.c (ffffffff81b7be24)
Location: net/ipv6/seg6_iptunnel.c:67
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_fill_encap_info
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
In net/ipv6/seg6_iptunnel.c (ffffffff81c46b64)
Location: net/ipv6/seg6_iptunnel.c:68
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_fill_encap_info
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
In net/ipv6/seg6_iptunnel.c (ffffffff81de5e64)
Location: net/ipv6/seg6_iptunnel.c:68
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_fill_encap_info
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
In net/ipv6/seg6_iptunnel.c (ffffffff81fb87a0)
Location: net/ipv6/seg6_iptunnel.c:70
Inline: True
Direct callers:
  - net/ipv6/seg6_iptunnel.c:seg6_fill_encap_info
```
**Symbols:**

```
ffffffff81fb87a0-ffffffff81fb881e: nla_put_srh.constprop.0 (STB_LOCAL)
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
In net/ipv6/seg6_iptunnel.c (ffffffff82018f10)
Location: net/ipv6/seg6_iptunnel.c:70
Inline: True
Direct callers:
  - net/ipv6/seg6_iptunnel.c:seg6_fill_encap_info
```
**Symbols:**

```
ffffffff82018f10-ffffffff82018f8e: nla_put_srh.constprop.0 (STB_LOCAL)
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
In net/ipv6/seg6_iptunnel.c (ffffffff820e7ee0)
Location: net/ipv6/seg6_iptunnel.c:70
Inline: True
Direct callers:
  - net/ipv6/seg6_iptunnel.c:seg6_fill_encap_info
```
**Symbols:**

```
ffffffff820e7ee0-ffffffff820e7f5e: nla_put_srh.constprop.0 (STB_LOCAL)
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
In net/ipv6/seg6_iptunnel.c (ffff800010d4f124)
Location: net/ipv6/seg6_iptunnel.c:50
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_fill_encap_info
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
In net/ipv6/seg6_iptunnel.c (c0e4fe90)
Location: net/ipv6/seg6_iptunnel.c:50
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_fill_encap_info
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
In net/ipv6/seg6_iptunnel.c (c000000000e86514)
Location: net/ipv6/seg6_iptunnel.c:50
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_fill_encap_info
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
In net/ipv6/seg6_iptunnel.c (ffffffe000887936)
Location: net/ipv6/seg6_iptunnel.c:50
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_fill_encap_info
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
In net/ipv6/seg6_iptunnel.c (ffffffff81a22984)
Location: net/ipv6/seg6_iptunnel.c:50
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_fill_encap_info
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
In net/ipv6/seg6_iptunnel.c (ffffffff819df744)
Location: net/ipv6/seg6_iptunnel.c:50
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_fill_encap_info
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
In net/ipv6/seg6_iptunnel.c (ffffffff81a8d404)
Location: net/ipv6/seg6_iptunnel.c:50
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_fill_encap_info
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
In net/ipv6/seg6_iptunnel.c (ffffffff81a9a0f4)
Location: net/ipv6/seg6_iptunnel.c:50
Inline: True
Inline callers:
  - net/ipv6/seg6_iptunnel.c:seg6_fill_encap_info
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
</ul>
