# Function: <code>skb_tunnel_check_pmtu</code>

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
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int skb_tunnel_check_pmtu(struct sk_buff *skb, struct dst_entry *encap_dst, int headroom, bool reply);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_tunnel_core.c (ffffffff81b06b50)
Location: net/ipv4/ip_tunnel_core.c:407
Inline: False
```
**Symbols:**

```
ffffffff81b06b50-ffffffff81b06e4b: skb_tunnel_check_pmtu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int skb_tunnel_check_pmtu(struct sk_buff *skb, struct dst_entry *encap_dst, int headroom, bool reply);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_tunnel_core.c (ffffffff81af2260)
Location: net/ipv4/ip_tunnel_core.c:407
Inline: False
```
**Symbols:**

```
ffffffff81af2260-ffffffff81af2598: skb_tunnel_check_pmtu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int skb_tunnel_check_pmtu(struct sk_buff *skb, struct dst_entry *encap_dst, int headroom, bool reply);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_tunnel_core.c (ffffffff81bb2770)
Location: net/ipv4/ip_tunnel_core.c:407
Inline: False
```
**Symbols:**

```
ffffffff81bb2770-ffffffff81bb2aa8: skb_tunnel_check_pmtu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int skb_tunnel_check_pmtu(struct sk_buff *skb, struct dst_entry *encap_dst, int headroom, bool reply);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_tunnel_core.c (ffffffff81d45f40)
Location: net/ipv4/ip_tunnel_core.c:407
Inline: False
```
**Symbols:**

```
ffffffff81d45f40-ffffffff81d46267: skb_tunnel_check_pmtu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int skb_tunnel_check_pmtu(struct sk_buff *skb, struct dst_entry *encap_dst, int headroom, bool reply);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_tunnel_core.c (ffffffff81f0f320)
Location: net/ipv4/ip_tunnel_core.c:407
Inline: False
```
**Symbols:**

```
ffffffff81f0f320-ffffffff81f0f647: skb_tunnel_check_pmtu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int skb_tunnel_check_pmtu(struct sk_buff *skb, struct dst_entry *encap_dst, int headroom, bool reply);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_tunnel_core.c (ffffffff81f6f010)
Location: net/ipv4/ip_tunnel_core.c:407
Inline: False
```
**Symbols:**

```
ffffffff81f6f010-ffffffff81f6f337: skb_tunnel_check_pmtu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int skb_tunnel_check_pmtu(struct sk_buff *skb, struct dst_entry *encap_dst, int headroom, bool reply);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_tunnel_core.c (ffffffff82035740)
Location: net/ipv4/ip_tunnel_core.c:407
Inline: False
```
**Symbols:**

```
ffffffff82035740-ffffffff82035a67: skb_tunnel_check_pmtu (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>aws</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/net/vxlan.c (ffffffff81772145)
Location: include/net/dst.h:531
Inline: True
Inline callers:
  - drivers/net/vxlan.c:vxlan_xmit_one
  - drivers/net/vxlan.c:vxlan_xmit_one
```
</details>
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
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
