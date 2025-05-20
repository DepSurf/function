# Function: <code>skb_gso_validate_network_len</code>

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
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
bool skb_gso_validate_network_len(const struct sk_buff *skb, unsigned int mtu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff8187a4a0)
Location: net/core/skbuff.c:5035
Inline: False
Direct callers:
  - net/ipv4/ip_forward.c:ip_forward
  - net/ipv4/ip_output.c:ip_finish_output
  - net/ipv4/xfrm4_output.c:xfrm4_extract_output
  - net/xfrm/xfrm_device.c:xfrm_dev_offload_ok
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/xfrm6_output.c:xfrm6_extract_output
```
**Symbols:**

```
ffffffff8187a4a0-ffffffff8187a524: skb_gso_validate_network_len (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
bool skb_gso_validate_network_len(const struct sk_buff *skb, unsigned int mtu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff8189b0b0)
Location: net/core/skbuff.c:5063
Inline: False
Direct callers:
  - net/ipv4/ip_forward.c:ip_forward
  - net/ipv4/ip_output.c:ip_finish_output
  - net/ipv4/xfrm4_output.c:xfrm4_extract_output
  - net/xfrm/xfrm_device.c:xfrm_dev_offload_ok
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/xfrm6_output.c:xfrm6_extract_output
```
**Symbols:**

```
ffffffff8189b0b0-ffffffff8189b12e: skb_gso_validate_network_len (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
bool skb_gso_validate_network_len(const struct sk_buff *skb, unsigned int mtu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff818e5790)
Location: net/core/skbuff.c:5248
Inline: False
Direct callers:
  - net/ipv4/ip_forward.c:ip_forward
  - net/ipv4/xfrm4_output.c:xfrm4_extract_output
  - net/xfrm/xfrm_device.c:xfrm_dev_offload_ok
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/xfrm6_output.c:xfrm6_extract_output
```
**Symbols:**

```
ffffffff818e5790-ffffffff818e581b: skb_gso_validate_network_len (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
bool skb_gso_validate_network_len(const struct sk_buff *skb, unsigned int mtu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff819178e0)
Location: net/core/skbuff.c:5260
Inline: False
Direct callers:
  - net/ipv4/ip_forward.c:ip_forward
  - net/ipv4/xfrm4_output.c:xfrm4_extract_output
  - net/xfrm/xfrm_device.c:xfrm_dev_offload_ok
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/xfrm6_output.c:xfrm6_extract_output
```
**Symbols:**

```
ffffffff819178e0-ffffffff8191796b: skb_gso_validate_network_len (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
bool skb_gso_validate_network_len(const struct sk_buff *skb, unsigned int mtu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff819ea9a0)
Location: net/core/skbuff.c:5362
Inline: False
Direct callers:
  - net/ipv4/ip_forward.c:ip_forward
  - net/ipv4/ip_output.c:ip_finish_output_gso
  - net/xfrm/xfrm_output.c:xfrm6_tunnel_check_size
  - net/xfrm/xfrm_device.c:xfrm_dev_offload_ok
  - net/ipv6/ip6_output.c:ip6_forward
```
**Symbols:**

```
ffffffff819ea9a0-ffffffff819eaa1e: skb_gso_validate_network_len (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
bool skb_gso_validate_network_len(const struct sk_buff *skb, unsigned int mtu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff819ea6e0)
Location: net/core/skbuff.c:5429
Inline: False
Direct callers:
  - net/ipv4/ip_forward.c:ip_forward
  - net/ipv4/ip_output.c:ip_finish_output_gso
  - net/ipv4/ip_tunnel_core.c:skb_tunnel_check_pmtu
  - net/xfrm/xfrm_output.c:xfrm6_tunnel_check_size
  - net/xfrm/xfrm_device.c:xfrm_dev_offload_ok
  - net/ipv6/ip6_output.c:ip6_forward
```
**Symbols:**

```
ffffffff819ea6e0-ffffffff819ea75e: skb_gso_validate_network_len (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
bool skb_gso_validate_network_len(const struct sk_buff *skb, unsigned int mtu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff819d0ca0)
Location: net/core/skbuff.c:5517
Inline: False
Direct callers:
  - net/core/filter.c:bpf_skb_check_mtu
  - net/ipv4/ip_forward.c:ip_forward
  - net/ipv4/ip_tunnel_core.c:skb_tunnel_check_pmtu
  - net/xfrm/xfrm_output.c:xfrm6_tunnel_check_size
  - net/xfrm/xfrm_device.c:xfrm_dev_offload_ok
  - net/ipv6/ip6_output.c:ip6_forward
```
**Symbols:**

```
ffffffff819d0ca0-ffffffff819d0d1d: skb_gso_validate_network_len (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
bool skb_gso_validate_network_len(const struct sk_buff *skb, unsigned int mtu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff81a804e0)
Location: net/core/skbuff.c:5592
Inline: False
Direct callers:
  - net/core/filter.c:bpf_skb_check_mtu
  - net/ipv4/ip_forward.c:ip_forward
  - net/ipv4/ip_tunnel_core.c:skb_tunnel_check_pmtu
  - net/xfrm/xfrm_output.c:xfrm6_tunnel_check_size
  - net/xfrm/xfrm_device.c:xfrm_dev_offload_ok
  - net/ipv6/ip6_output.c:ip6_forward
```
**Symbols:**

```
ffffffff81a804e0-ffffffff81a8055d: skb_gso_validate_network_len (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
bool skb_gso_validate_network_len(const struct sk_buff *skb, unsigned int mtu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff81bf4b80)
Location: net/core/skbuff.c:5513
Inline: False
Direct callers:
  - net/core/filter.c:bpf_skb_check_mtu
  - net/ipv4/ip_forward.c:ip_forward
  - net/ipv4/ip_tunnel_core.c:skb_tunnel_check_pmtu
  - net/xfrm/xfrm_output.c:xfrm6_tunnel_check_size
  - net/xfrm/xfrm_device.c:xfrm_dev_offload_ok
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_finish_output
```
**Symbols:**

```
ffffffff81bf4b80-ffffffff81bf4c21: skb_gso_validate_network_len (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
bool skb_gso_validate_network_len(const struct sk_buff *skb, unsigned int mtu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff81da2a60)
Location: net/core/skbuff.c:5715
Inline: False
Direct callers:
  - net/core/filter.c:bpf_skb_check_mtu
  - net/ipv4/ip_forward.c:ip_forward
  - net/ipv4/ip_tunnel_core.c:skb_tunnel_check_pmtu
  - net/xfrm/xfrm_output.c:xfrm6_tunnel_check_size
  - net/xfrm/xfrm_device.c:xfrm_dev_offload_ok
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_finish_output
```
**Symbols:**

```
ffffffff81da2a60-ffffffff81da2b01: skb_gso_validate_network_len (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
bool skb_gso_validate_network_len(const struct sk_buff *skb, unsigned int mtu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/gso.c (ffffffff81e7d840)
Location: net/core/gso.c:253
Inline: False
Direct callers:
  - net/core/filter.c:bpf_skb_check_mtu
  - net/ipv4/ip_forward.c:ip_forward
  - net/ipv4/ip_tunnel_core.c:skb_tunnel_check_pmtu
  - net/xfrm/xfrm_output.c:xfrm6_tunnel_check_size
  - net/xfrm/xfrm_device.c:xfrm_dev_offload_ok
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_finish_output
```
**Symbols:**

```
ffffffff81e7d840-ffffffff81e7d8e1: skb_gso_validate_network_len (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
bool skb_gso_validate_network_len(const struct sk_buff *skb, unsigned int mtu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/gso.c (ffffffff81f3e7b0)
Location: net/core/gso.c:253
Inline: False
Direct callers:
  - net/core/filter.c:bpf_skb_check_mtu
  - net/ipv4/ip_forward.c:ip_forward
  - net/ipv4/ip_tunnel_core.c:skb_tunnel_check_pmtu
  - net/xfrm/xfrm_output.c:xfrm6_tunnel_check_size
  - net/xfrm/xfrm_device.c:xfrm_dev_offload_ok
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/ip6_output.c:ip6_finish_output
```
**Symbols:**

```
ffffffff81f3e7b0-ffffffff81f3e851: skb_gso_validate_network_len (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
bool skb_gso_validate_network_len(const struct sk_buff *skb, unsigned int mtu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffff800010bb0c88)
Location: net/core/skbuff.c:5260
Inline: False
Direct callers:
  - net/ipv4/ip_forward.c:ip_forward
  - net/ipv4/xfrm4_output.c:xfrm4_extract_output
  - net/xfrm/xfrm_device.c:xfrm_dev_offload_ok
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/xfrm6_output.c:xfrm6_extract_output
```
**Symbols:**

```
ffff800010bb0c88-ffff800010bb0d34: skb_gso_validate_network_len (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
bool skb_gso_validate_network_len(const struct sk_buff *skb, unsigned int mtu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (c0cce004)
Location: net/core/skbuff.c:5260
Inline: False
Direct callers:
  - net/ipv4/ip_forward.c:ip_forward
  - net/ipv4/xfrm4_output.c:xfrm4_extract_output
  - net/xfrm/xfrm_device.c:xfrm_dev_offload_ok
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/xfrm6_output.c:xfrm6_extract_output
```
**Symbols:**

```
c0cce004-c0cce0a0: skb_gso_validate_network_len (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
bool skb_gso_validate_network_len(const struct sk_buff *skb, unsigned int mtu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (c000000000c86eb0)
Location: net/core/skbuff.c:5260
Inline: False
Direct callers:
  - net/ipv4/ip_forward.c:ip_forward
  - net/ipv4/xfrm4_output.c:xfrm4_extract_output
  - net/xfrm/xfrm_device.c:xfrm_dev_offload_ok
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/xfrm6_output.c:xfrm6_extract_output
```
**Symbols:**

```
c000000000c86eb0-c000000000c86fd4: skb_gso_validate_network_len (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
bool skb_gso_validate_network_len(const struct sk_buff *skb, unsigned int mtu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffe000741e2e)
Location: net/core/skbuff.c:5260
Inline: False
Direct callers:
  - net/ipv4/ip_forward.c:ip_forward
  - net/ipv4/xfrm4_output.c:xfrm4_extract_output
  - net/xfrm/xfrm_device.c:xfrm_dev_offload_ok
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/xfrm6_output.c:xfrm6_extract_output
```
**Symbols:**

```
ffffffe000741e2e-ffffffe000741ec6: skb_gso_validate_network_len (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
bool skb_gso_validate_network_len(const struct sk_buff *skb, unsigned int mtu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff818b78e0)
Location: net/core/skbuff.c:5260
Inline: False
Direct callers:
  - net/ipv4/ip_forward.c:ip_forward
  - net/ipv4/xfrm4_output.c:xfrm4_extract_output
  - net/xfrm/xfrm_device.c:xfrm_dev_offload_ok
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/xfrm6_output.c:xfrm6_extract_output
```
**Symbols:**

```
ffffffff818b78e0-ffffffff818b796b: skb_gso_validate_network_len (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
bool skb_gso_validate_network_len(const struct sk_buff *skb, unsigned int mtu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff81871830)
Location: net/core/skbuff.c:5260
Inline: False
Direct callers:
  - net/ipv4/ip_forward.c:ip_forward
  - net/ipv4/xfrm4_output.c:xfrm4_extract_output
  - net/xfrm/xfrm_device.c:xfrm_dev_offload_ok
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/xfrm6_output.c:xfrm6_extract_output
```
**Symbols:**

```
ffffffff81871830-ffffffff818718bb: skb_gso_validate_network_len (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
bool skb_gso_validate_network_len(const struct sk_buff *skb, unsigned int mtu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff819088e0)
Location: net/core/skbuff.c:5260
Inline: False
Direct callers:
  - net/ipv4/ip_forward.c:ip_forward
  - net/ipv4/xfrm4_output.c:xfrm4_extract_output
  - net/xfrm/xfrm_device.c:xfrm_dev_offload_ok
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/xfrm6_output.c:xfrm6_extract_output
```
**Symbols:**

```
ffffffff819088e0-ffffffff8190896b: skb_gso_validate_network_len (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
bool skb_gso_validate_network_len(const struct sk_buff *skb, unsigned int mtu);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff81929990)
Location: net/core/skbuff.c:5260
Inline: False
Direct callers:
  - net/ipv4/ip_forward.c:ip_forward
  - net/ipv4/xfrm4_output.c:xfrm4_extract_output
  - net/xfrm/xfrm_device.c:xfrm_dev_offload_ok
  - net/ipv6/ip6_output.c:ip6_forward
  - net/ipv6/xfrm6_output.c:xfrm6_extract_output
```
**Symbols:**

```
ffffffff81929990-ffffffff81929a1b: skb_gso_validate_network_len (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
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
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
