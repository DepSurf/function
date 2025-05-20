# Function: <code>skb_gso_validate_mtu</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
bool skb_gso_validate_mtu(const struct sk_buff *skb, unsigned int mtu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff8176bfa0)
Location: net/core/skbuff.c:4389
Inline: False
Direct callers:
  - net/ipv4/ip_forward.c:ip_forward
  - net/ipv6/ip6_output.c:ip6_forward
```
**Symbols:**

```
ffffffff8176bfa0-ffffffff8176c030: skb_gso_validate_mtu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
bool skb_gso_validate_mtu(const struct sk_buff *skb, unsigned int mtu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff81799180)
Location: net/core/skbuff.c:4433
Inline: False
Direct callers:
  - net/ipv4/ip_forward.c:ip_forward
  - net/ipv4/ip_output.c:ip_finish_output
  - net/ipv6/ip6_output.c:ip6_forward
```
**Symbols:**

```
ffffffff81799180-ffffffff81799210: skb_gso_validate_mtu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
bool skb_gso_validate_mtu(const struct sk_buff *skb, unsigned int mtu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff817b7750)
Location: net/core/skbuff.c:4527
Inline: False
Direct callers:
  - net/ipv4/ip_forward.c:ip_forward
  - net/ipv4/ip_output.c:ip_finish_output
  - net/xfrm/xfrm_device.c:xfrm_dev_offload_ok
  - net/ipv6/ip6_output.c:ip6_forward
```
**Symbols:**

```
ffffffff817b7750-ffffffff817b77f5: skb_gso_validate_mtu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
bool skb_gso_validate_mtu(const struct sk_buff *skb, unsigned int mtu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff8182fe10)
Location: net/core/skbuff.c:4960
Inline: False
Direct callers:
  - net/ipv4/ip_forward.c:ip_forward
  - net/ipv4/ip_output.c:ip_finish_output
  - net/xfrm/xfrm_device.c:xfrm_dev_offload_ok
  - net/ipv6/ip6_output.c:ip6_forward
```
**Symbols:**

```
ffffffff8182fe10-ffffffff8182fe96: skb_gso_validate_mtu (STB_GLOBAL)
```
</details>
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
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
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
In <code>azure</code>: Absent ⚠️
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
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
</ul>
