# Function: <code>dst_allfrag</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_output.c (ffffffff81775123)
Location: include/net/dst.h:234
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_sync_mss
  - net/ipv4/tcp_output.c:tcp_sync_mss
  - net/ipv4/tcp_output.c:tcp_mss_to_mtu
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_connect
```
```
In net/ipv6/ip6_output.c (ffffffff817c5858)
Location: include/net/dst.h:234
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_setup_cork
  - net/ipv6/ip6_output.c:ip6_fragment
```
```
In net/ipv6/xfrm6_output.c (ffffffff817fd0dc)
Location: include/net/dst.h:234
Inline: True
Inline callers:
  - net/ipv6/xfrm6_output.c:__xfrm6_output
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_output.c (ffffffff817e4d54)
Location: include/net/dst.h:231
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_sync_mss
  - net/ipv4/tcp_output.c:tcp_sync_mss
  - net/ipv4/tcp_output.c:tcp_mss_to_mtu
```
```
In net/ipv6/ip6_output.c (ffffffff8183297a)
Location: include/net/dst.h:231
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_setup_cork
  - net/ipv6/ip6_output.c:ip6_fragment
```
```
In net/ipv6/xfrm6_output.c (ffffffff8186ca0c)
Location: include/net/dst.h:231
Inline: True
Inline callers:
  - net/ipv6/xfrm6_output.c:__xfrm6_output
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_output.c (ffffffff818151a5)
Location: include/net/dst.h:231
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_sync_mss
  - net/ipv4/tcp_output.c:tcp_sync_mss
  - net/ipv4/tcp_output.c:tcp_mss_to_mtu
```
```
In net/ipv6/ip6_output.c (ffffffff81864402)
Location: include/net/dst.h:231
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_setup_cork
  - net/ipv6/ip6_output.c:ip6_fragment
```
```
In net/ipv6/xfrm6_output.c (ffffffff8189f7fc)
Location: include/net/dst.h:231
Inline: True
Inline callers:
  - net/ipv6/xfrm6_output.c:__xfrm6_output
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_output.c (ffffffff81835478)
Location: include/net/dst.h:235
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_sync_mss
  - net/ipv4/tcp_output.c:tcp_sync_mss
  - net/ipv4/tcp_output.c:tcp_mtup_init
```
```
In net/ipv6/ip6_output.c (ffffffff81889a03)
Location: include/net/dst.h:235
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_setup_cork
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_finish_output
```
```
In net/ipv6/xfrm6_output.c (ffffffff818c5da1)
Location: include/net/dst.h:235
Inline: True
Inline callers:
  - net/ipv6/xfrm6_output.c:__xfrm6_output
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_output.c (ffffffff818b5009)
Location: include/net/dst.h:237
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_sync_mss
  - net/ipv4/tcp_output.c:tcp_sync_mss
  - net/ipv4/tcp_output.c:tcp_mss_to_mtu
```
```
In net/ipv6/ip6_output.c (ffffffff8190a00d)
Location: include/net/dst.h:237
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_setup_cork
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_finish_output
```
```
In net/ipv6/xfrm6_output.c (ffffffff81949133)
Location: include/net/dst.h:237
Inline: True
Inline callers:
  - net/ipv6/xfrm6_output.c:__xfrm6_output
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_output.c (ffffffff8190a50f)
Location: include/net/dst.h:220
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_sync_mss
  - net/ipv4/tcp_output.c:tcp_sync_mss
  - net/ipv4/tcp_output.c:tcp_mss_to_mtu
```
```
In net/ipv6/ip6_output.c (ffffffff819613ba)
Location: include/net/dst.h:220
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_setup_cork
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_finish_output
```
```
In net/ipv6/xfrm6_output.c (ffffffff819a21dd)
Location: include/net/dst.h:220
Inline: True
Inline callers:
  - net/ipv6/xfrm6_output.c:__xfrm6_output
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_output.c (ffffffff8193878a)
Location: include/net/dst.h:220
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_connect
  - net/ipv4/tcp_output.c:tcp_sync_mss
  - net/ipv4/tcp_output.c:tcp_sync_mss
  - net/ipv4/tcp_output.c:tcp_mss_to_mtu
```
```
In net/ipv6/ip6_output.c (ffffffff81995c94)
Location: include/net/dst.h:220
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_setup_cork
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_finish_output
```
```
In net/ipv6/xfrm6_output.c (ffffffff819d8e3a)
Location: include/net/dst.h:220
Inline: True
Inline callers:
  - net/ipv6/xfrm6_output.c:__xfrm6_output
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_output.c (ffffffff8199b349)
Location: include/net/dst.h:209
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_syn_data
  - net/ipv4/tcp_output.c:tcp_sync_mss
  - net/ipv4/tcp_output.c:tcp_sync_mss
  - net/ipv4/tcp_output.c:tcp_mss_to_mtu
```
```
In net/ipv6/ip6_output.c (ffffffff81a019da)
Location: include/net/dst.h:209
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_setup_cork
  - net/ipv6/ip6_output.c:ip6_fragment
```
```
In net/ipv6/xfrm6_output.c (ffffffff81a476b6)
Location: include/net/dst.h:209
Inline: True
Inline callers:
  - net/ipv6/xfrm6_output.c:__xfrm6_output
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_output.c (ffffffff819d1c86)
Location: include/net/dst.h:209
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_syn_data
  - net/ipv4/tcp_output.c:tcp_mtu_probe
  - net/ipv4/tcp_output.c:tcp_mtu_probe
  - net/ipv4/tcp_output.c:tcp_sync_mss
  - net/ipv4/tcp_output.c:tcp_sync_mss
  - net/ipv4/tcp_output.c:tcp_mtup_init
```
```
In net/ipv6/ip6_output.c (ffffffff81a3859b)
Location: include/net/dst.h:209
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_setup_cork
  - net/ipv6/ip6_output.c:ip6_fragment
```
```
In net/ipv6/xfrm6_output.c (ffffffff81a7e236)
Location: include/net/dst.h:209
Inline: True
Inline callers:
  - net/ipv6/xfrm6_output.c:__xfrm6_output
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_output.c (ffffffff81abe9cd)
Location: include/net/dst.h:208
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_syn_data
  - net/ipv4/tcp_output.c:tcp_sync_mss
  - net/ipv4/tcp_output.c:tcp_sync_mss
  - net/ipv4/tcp_output.c:tcp_mtup_init
```
```
In net/ipv6/ip6_output.c (ffffffff81b2e433)
Location: include/net/dst.h:208
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_setup_cork
  - net/ipv6/ip6_output.c:ip6_fragment
```
```
In net/ipv6/xfrm6_output.c (ffffffff81b78f15)
Location: include/net/dst.h:208
Inline: True
Inline callers:
  - net/ipv6/xfrm6_output.c:__xfrm6_output
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_output.c (ffffffff81aca32d)
Location: include/net/dst.h:208
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_syn_data
  - net/ipv4/tcp_output.c:tcp_sync_mss
  - net/ipv4/tcp_output.c:tcp_sync_mss
  - net/ipv4/tcp_output.c:tcp_mtup_init
```
```
In net/ipv6/ip6_output.c (ffffffff81b3ce83)
Location: include/net/dst.h:208
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_setup_cork
  - net/ipv6/ip6_output.c:ip6_fragment
```
```
In net/ipv6/xfrm6_output.c (ffffffff81b87e95)
Location: include/net/dst.h:208
Inline: True
Inline callers:
  - net/ipv6/xfrm6_output.c:__xfrm6_output
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_output.c (ffffffff81ab51aa)
Location: include/net/dst.h:211
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_syn_data
  - net/ipv4/tcp_output.c:tcp_sync_mss
  - net/ipv4/tcp_output.c:tcp_sync_mss
  - net/ipv4/tcp_output.c:tcp_mtup_init
```
```
In net/ipv6/ip6_output.c (ffffffff81b2a2e3)
Location: include/net/dst.h:211
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_setup_cork
  - net/ipv6/ip6_output.c:ip6_fragment
```
```
In net/ipv6/xfrm6_output.c (ffffffff81b76b42)
Location: include/net/dst.h:211
Inline: True
Inline callers:
  - net/ipv6/xfrm6_output.c:__xfrm6_output
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_output.c (ffffffff81b7219a)
Location: include/net/dst.h:211
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_syn_data
  - net/ipv4/tcp_output.c:tcp_sync_mss
  - net/ipv4/tcp_output.c:tcp_sync_mss
  - net/ipv4/tcp_output.c:tcp_mtup_init
```
```
In net/ipv6/ip6_output.c (ffffffff81befebe)
Location: include/net/dst.h:211
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_setup_cork
  - net/ipv6/ip6_output.c:ip6_fragment
```
```
In net/ipv6/xfrm6_output.c (ffffffff81c415ba)
Location: include/net/dst.h:211
Inline: True
Inline callers:
  - net/ipv6/xfrm6_output.c:__xfrm6_output
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_output.c (ffffffff81d0189c)
Location: include/net/dst.h:212
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_syn_data
  - net/ipv4/tcp_output.c:tcp_sync_mss
  - net/ipv4/tcp_output.c:tcp_sync_mss
  - net/ipv4/tcp_output.c:tcp_mtup_init
```
```
In net/ipv6/ip6_output.c (ffffffff81d87f55)
Location: include/net/dst.h:212
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_setup_cork
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_finish_output
```
```
In net/ipv6/xfrm6_output.c (ffffffff81ddfcf3)
Location: include/net/dst.h:212
Inline: True
Inline callers:
  - net/ipv6/xfrm6_output.c:__xfrm6_output
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_output.c (ffffffff81ec6a0c)
Location: include/net/dst.h:212
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_syn_data
  - net/ipv4/tcp_output.c:tcp_sync_mss
  - net/ipv4/tcp_output.c:tcp_sync_mss
  - net/ipv4/tcp_output.c:tcp_mtup_init
```
```
In net/ipv6/ip6_output.c (ffffffff81f55cf1)
Location: include/net/dst.h:212
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_setup_cork
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_finish_output
```
```
In net/ipv6/xfrm6_output.c (ffffffff81fb2013)
Location: include/net/dst.h:212
Inline: True
Inline callers:
  - net/ipv6/xfrm6_output.c:__xfrm6_output
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_output.c (ffffffff81f251cd)
Location: include/net/dst.h:226
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_syn_data
  - net/ipv4/tcp_output.c:tcp_sync_mss
  - net/ipv4/tcp_output.c:tcp_sync_mss
  - net/ipv4/tcp_output.c:tcp_mtup_init
```
```
In net/ipv6/ip6_output.c (ffffffff81fb56c9)
Location: include/net/dst.h:226
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_setup_cork
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_finish_output
```
```
In net/ipv6/xfrm6_output.c (ffffffff8201272d)
Location: include/net/dst.h:226
Inline: True
Inline callers:
  - net/ipv6/xfrm6_output.c:__xfrm6_output
```
</details>
</li>
<li>
In <code>6.8</code>: Absent ⚠️
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_output.c (ffff800010c8486c)
Location: include/net/dst.h:209
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_syn_data
  - net/ipv4/tcp_output.c:tcp_mtu_probe
  - net/ipv4/tcp_output.c:tcp_mtu_probe
  - net/ipv4/tcp_output.c:tcp_sync_mss
  - net/ipv4/tcp_output.c:tcp_sync_mss
  - net/ipv4/tcp_output.c:tcp_mtup_init
```
```
In net/ipv6/ip6_output.c (ffff800010cf8b10)
Location: include/net/dst.h:209
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_setup_cork
  - net/ipv6/ip6_output.c:ip6_fragment
```
```
In net/ipv6/xfrm6_output.c (ffff800010d49644)
Location: include/net/dst.h:209
Inline: True
Inline callers:
  - net/ipv6/xfrm6_output.c:__xfrm6_output
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_output.c (c0d93b5c)
Location: include/net/dst.h:209
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_syn_data
  - net/ipv4/tcp_output.c:tcp_sync_mss
  - net/ipv4/tcp_output.c:tcp_sync_mss
  - net/ipv4/tcp_output.c:tcp_mss_to_mtu
```
```
In net/ipv6/ip6_output.c (c0e006a8)
Location: include/net/dst.h:209
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:__ip6_append_data
  - net/ipv6/ip6_output.c:ip6_setup_cork
  - net/ipv6/ip6_output.c:ip6_fragment
```
```
In net/ipv6/xfrm6_output.c (c0e4aa34)
Location: include/net/dst.h:209
Inline: True
Inline callers:
  - net/ipv6/xfrm6_output.c:__xfrm6_output
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_output.c (c000000000d90334)
Location: include/net/dst.h:209
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_syn_data
  - net/ipv4/tcp_output.c:tcp_mtu_probe
  - net/ipv4/tcp_output.c:tcp_mtu_probe
  - net/ipv4/tcp_output.c:tcp_sync_mss
  - net/ipv4/tcp_output.c:tcp_sync_mss
  - net/ipv4/tcp_output.c:tcp_mtup_init
```
```
In net/ipv6/ip6_output.c (c000000000e21cfc)
Location: include/net/dst.h:209
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_setup_cork
  - net/ipv6/ip6_output.c:ip6_fragment
```
```
In net/ipv6/xfrm6_output.c (c000000000e7ec30)
Location: include/net/dst.h:209
Inline: True
Inline callers:
  - net/ipv6/xfrm6_output.c:__xfrm6_output
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_output.c (ffffffe0007e60a8)
Location: include/net/dst.h:209
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_syn_data
  - net/ipv4/tcp_output.c:tcp_mtu_probe
  - net/ipv4/tcp_output.c:tcp_mtu_probe
  - net/ipv4/tcp_output.c:tcp_sync_mss
  - net/ipv4/tcp_output.c:tcp_sync_mss
  - net/ipv4/tcp_output.c:tcp_mtup_init
```
```
In net/ipv6/ip6_output.c (ffffffe000844830)
Location: include/net/dst.h:209
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_setup_cork
  - net/ipv6/ip6_output.c:ip6_fragment
```
```
In net/ipv6/xfrm6_output.c (ffffffe000882ad4)
Location: include/net/dst.h:209
Inline: True
Inline callers:
  - net/ipv6/xfrm6_output.c:__xfrm6_output
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_output.c (ffffffff81971af6)
Location: include/net/dst.h:209
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_syn_data
  - net/ipv4/tcp_output.c:tcp_mtu_probe
  - net/ipv4/tcp_output.c:tcp_mtu_probe
  - net/ipv4/tcp_output.c:tcp_sync_mss
  - net/ipv4/tcp_output.c:tcp_sync_mss
  - net/ipv4/tcp_output.c:tcp_mtup_init
```
```
In net/ipv6/ip6_output.c (ffffffff819d7c2b)
Location: include/net/dst.h:209
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_setup_cork
  - net/ipv6/ip6_output.c:ip6_fragment
```
```
In net/ipv6/xfrm6_output.c (ffffffff81a1d8c6)
Location: include/net/dst.h:209
Inline: True
Inline callers:
  - net/ipv6/xfrm6_output.c:__xfrm6_output
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_output.c (ffffffff8192b5c6)
Location: include/net/dst.h:209
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_syn_data
  - net/ipv4/tcp_output.c:tcp_mtu_probe
  - net/ipv4/tcp_output.c:tcp_mtu_probe
  - net/ipv4/tcp_output.c:tcp_sync_mss
  - net/ipv4/tcp_output.c:tcp_sync_mss
  - net/ipv4/tcp_output.c:tcp_mtup_init
```
```
In net/ipv6/ip6_output.c (ffffffff819949eb)
Location: include/net/dst.h:209
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_setup_cork
  - net/ipv6/ip6_output.c:ip6_fragment
```
```
In net/ipv6/xfrm6_output.c (ffffffff819da686)
Location: include/net/dst.h:209
Inline: True
Inline callers:
  - net/ipv6/xfrm6_output.c:__xfrm6_output
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_output.c (ffffffff819dc2c6)
Location: include/net/dst.h:209
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_syn_data
  - net/ipv4/tcp_output.c:tcp_mtu_probe
  - net/ipv4/tcp_output.c:tcp_mtu_probe
  - net/ipv4/tcp_output.c:tcp_sync_mss
  - net/ipv4/tcp_output.c:tcp_sync_mss
  - net/ipv4/tcp_output.c:tcp_mtup_init
```
```
In net/ipv6/ip6_output.c (ffffffff81a426ab)
Location: include/net/dst.h:209
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_setup_cork
  - net/ipv6/ip6_output.c:ip6_fragment
```
```
In net/ipv6/xfrm6_output.c (ffffffff81a88346)
Location: include/net/dst.h:209
Inline: True
Inline callers:
  - net/ipv6/xfrm6_output.c:__xfrm6_output
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_output.c (ffffffff819e5f46)
Location: include/net/dst.h:209
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_send_syn_data
  - net/ipv4/tcp_output.c:tcp_mtu_probe
  - net/ipv4/tcp_output.c:tcp_mtu_probe
  - net/ipv4/tcp_output.c:tcp_sync_mss
  - net/ipv4/tcp_output.c:tcp_sync_mss
  - net/ipv4/tcp_output.c:tcp_mtup_init
```
```
In net/ipv6/ip6_output.c (ffffffff81a4e33b)
Location: include/net/dst.h:209
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_setup_cork
  - net/ipv6/ip6_output.c:ip6_fragment
```
```
In net/ipv6/xfrm6_output.c (ffffffff81a94f96)
Location: include/net/dst.h:209
Inline: True
Inline callers:
  - net/ipv6/xfrm6_output.c:__xfrm6_output
```
</details>
</li>
</ul>

## Differences
