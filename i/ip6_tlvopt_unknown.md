# Function: <code>ip6_tlvopt_unknown</code>

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
In net/ipv6/exthdrs.c (ffffffff817f2cba)
Location: net/ipv6/exthdrs.c:71
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ip6_parse_tlv
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
In net/ipv6/exthdrs.c (ffffffff81861a32)
Location: net/ipv6/exthdrs.c:72
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ip6_parse_tlv
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
In net/ipv6/exthdrs.c (ffffffff818939a2)
Location: net/ipv6/exthdrs.c:77
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ip6_parse_tlv
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
In net/ipv6/exthdrs.c (ffffffff818b9efb)
Location: net/ipv6/exthdrs.c:77
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ip6_parse_tlv
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
In net/ipv6/exthdrs.c (ffffffff8193ce8b)
Location: net/ipv6/exthdrs.c:77
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ip6_parse_tlv
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
In net/ipv6/exthdrs.c (ffffffff81995ec7)
Location: net/ipv6/exthdrs.c:77
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ip6_parse_tlv
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
In net/ipv6/exthdrs.c (ffffffff819cc7d1)
Location: net/ipv6/exthdrs.c:77
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ip6_parse_tlv
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
In net/ipv6/exthdrs.c (ffffffff81a3b39f)
Location: net/ipv6/exthdrs.c:73
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ip6_parse_tlv
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
In net/ipv6/exthdrs.c (ffffffff81a7201f)
Location: net/ipv6/exthdrs.c:73
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ip6_parse_tlv
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
In net/ipv6/exthdrs.c (ffffffff81b6b91b)
Location: net/ipv6/exthdrs.c:74
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ip6_parse_tlv
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
In net/ipv6/exthdrs.c (ffffffff81b7a3ab)
Location: net/ipv6/exthdrs.c:74
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ip6_parse_tlv
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
In net/ipv6/exthdrs.c (ffffffff81b68eee)
Location: net/ipv6/exthdrs.c:74
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ip6_parse_tlv
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
bool ip6_tlvopt_unknown(struct sk_buff *skb, int optoff, bool disallow_unknowns);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/exthdrs.c (ffffffff81c30a70)
Location: net/ipv6/exthdrs.c:64
Inline: False
Direct callers:
  - net/ipv6/exthdrs.c:ip6_parse_tlv
  - net/ipv6/exthdrs.c:ip6_parse_tlv
```
**Symbols:**

```
ffffffff81c30a70-ffffffff81c30ae6: ip6_tlvopt_unknown (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
bool ip6_tlvopt_unknown(struct sk_buff *skb, int optoff, bool disallow_unknowns);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/exthdrs.c (ffffffff81dce2e0)
Location: net/ipv6/exthdrs.c:64
Inline: False
Direct callers:
  - net/ipv6/exthdrs.c:ip6_parse_tlv
```
**Symbols:**

```
ffffffff81dce2e0-ffffffff81dce364: ip6_tlvopt_unknown (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
bool ip6_tlvopt_unknown(struct sk_buff *skb, int optoff, bool disallow_unknowns);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/exthdrs.c (ffffffff81f9f430)
Location: net/ipv6/exthdrs.c:64
Inline: False
Direct callers:
  - net/ipv6/exthdrs.c:ip6_parse_tlv
```
**Symbols:**

```
ffffffff81f9f430-ffffffff81f9f4b4: ip6_tlvopt_unknown (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
bool ip6_tlvopt_unknown(struct sk_buff *skb, int optoff, bool disallow_unknowns);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/exthdrs.c (ffffffff81ffff90)
Location: net/ipv6/exthdrs.c:64
Inline: False
Direct callers:
  - net/ipv6/exthdrs.c:ip6_parse_tlv
```
**Symbols:**

```
ffffffff81ffff90-ffffffff82000018: ip6_tlvopt_unknown (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
bool ip6_tlvopt_unknown(struct sk_buff *skb, int optoff, bool disallow_unknowns);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/exthdrs.c (ffffffff820ced20)
Location: net/ipv6/exthdrs.c:64
Inline: False
Direct callers:
  - net/ipv6/exthdrs.c:ip6_parse_tlv
```
**Symbols:**

```
ffffffff820ced20-ffffffff820ceda8: ip6_tlvopt_unknown (STB_LOCAL)
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
In net/ipv6/exthdrs.c (ffff800010d3aa04)
Location: net/ipv6/exthdrs.c:73
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ip6_parse_tlv
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
In net/ipv6/exthdrs.c (c0e3cf44)
Location: net/ipv6/exthdrs.c:73
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ip6_parse_tlv
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
In net/ipv6/exthdrs.c (c000000000e6de30)
Location: net/ipv6/exthdrs.c:73
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ip6_parse_tlv
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
In net/ipv6/exthdrs.c (ffffffe000877548)
Location: net/ipv6/exthdrs.c:73
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ip6_parse_tlv
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
In net/ipv6/exthdrs.c (ffffffff81a116af)
Location: net/ipv6/exthdrs.c:73
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ip6_parse_tlv
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
In net/ipv6/exthdrs.c (ffffffff819ce46f)
Location: net/ipv6/exthdrs.c:73
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ip6_parse_tlv
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
In net/ipv6/exthdrs.c (ffffffff81a7c12f)
Location: net/ipv6/exthdrs.c:73
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ip6_parse_tlv
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
In net/ipv6/exthdrs.c (ffffffff81a8897f)
Location: net/ipv6/exthdrs.c:73
Inline: True
Inline callers:
  - net/ipv6/exthdrs.c:ip6_parse_tlv
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
