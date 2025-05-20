# Function: <code>skb_ext_put</code>

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
<details>
<summary>In <code>5.0</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff8189e553)
Location: include/linux/skbuff.h:3939
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_release_head_state
```
```
In net/ipv4/ip_output.c (ffffffff81918fcf)
Location: include/linux/skbuff.h:3939
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_copy_metadata
```
```
In net/ipv6/ip6_output.c (ffffffff819958d0)
Location: include/linux/skbuff.h:3939
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_copy_metadata
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
In net/core/skbuff.c (ffffffff818e8dc7)
Location: include/linux/skbuff.h:4046
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_release_head_state
```
```
In net/ipv4/ip_output.c (ffffffff8197b0fb)
Location: include/linux/skbuff.h:4046
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_copy_metadata
```
```
In net/ipv6/ip6_output.c (ffffffff81a01188)
Location: include/linux/skbuff.h:4046
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_copy_metadata
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
In net/core/skbuff.c (ffffffff8191af23)
Location: include/linux/skbuff.h:4118
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_release_head_state
```
```
In net/core/dev.c (ffffffff8192c416)
Location: include/linux/skbuff.h:4118
Inline: True
Inline callers:
  - net/core/dev.c:napi_skb_free_stolen_head
```
```
In net/ipv4/ip_output.c (ffffffff819b1a6b)
Location: include/linux/skbuff.h:4118
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_copy_metadata
```
```
In net/ipv6/ip6_output.c (ffffffff81a37d64)
Location: include/linux/skbuff.h:4118
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_copy_metadata
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
In net/core/skbuff.c (ffffffff819f4495)
Location: include/linux/skbuff.h:4158
Inline: True
Inline callers:
  - net/core/skbuff.c:__skb_ext_set
  - net/core/skbuff.c:skb_release_head_state
```
```
In net/core/dev.c (ffffffff81a00e67)
Location: include/linux/skbuff.h:4158
Inline: True
Inline callers:
  - net/core/dev.c:napi_skb_free_stolen_head
```
```
In net/ipv4/ip_output.c (ffffffff81a9c2ab)
Location: include/linux/skbuff.h:4158
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_copy_metadata
```
```
In net/ipv4/tcp_input.c (ffffffff81ab22a3)
Location: include/linux/skbuff.h:4158
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_collapse
```
```
In net/ipv6/ip6_output.c (ffffffff81b2dd38)
Location: include/linux/skbuff.h:4158
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_copy_metadata
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
In net/core/skbuff.c (ffffffff819f44b5)
Location: include/linux/skbuff.h:4187
Inline: True
Inline callers:
  - net/core/skbuff.c:__skb_ext_set
  - net/core/skbuff.c:skb_release_head_state
```
```
In net/core/dev.c (ffffffff81a01277)
Location: include/linux/skbuff.h:4187
Inline: True
Inline callers:
  - net/core/dev.c:napi_skb_free_stolen_head
```
```
In net/ipv4/ip_output.c (ffffffff81aa610b)
Location: include/linux/skbuff.h:4187
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_copy_metadata
```
```
In net/ipv4/tcp_input.c (ffffffff81abd269)
Location: include/linux/skbuff.h:4187
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_collapse
```
```
In net/ipv4/tcp_output.c (ffffffff81acafab)
Location: include/linux/skbuff.h:4187
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_mtu_probe
  - net/ipv4/tcp_output.c:tso_fragment
  - net/ipv4/tcp_output.c:tcp_fragment
```
```
In net/ipv6/ip6_output.c (ffffffff81b3c788)
Location: include/linux/skbuff.h:4187
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_copy_metadata
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
In net/core/skbuff.c (ffffffff819da673)
Location: include/linux/skbuff.h:4251
Inline: True
Inline callers:
  - net/core/skbuff.c:__skb_ext_set
  - net/core/skbuff.c:napi_skb_free_stolen_head
  - net/core/skbuff.c:skb_release_head_state
```
```
In net/ipv4/ip_output.c (ffffffff81a912cb)
Location: include/linux/skbuff.h:4251
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_copy_metadata
```
```
In net/ipv4/tcp_input.c (ffffffff81aa8095)
Location: include/linux/skbuff.h:4251
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_collapse
```
```
In net/ipv4/tcp_output.c (ffffffff81ab5f91)
Location: include/linux/skbuff.h:4251
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_mtu_probe
  - net/ipv4/tcp_output.c:tso_fragment
  - net/ipv4/tcp_output.c:tcp_fragment
```
```
In net/ipv6/ip6_output.c (ffffffff81b29be8)
Location: include/linux/skbuff.h:4251
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_copy_metadata
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
In net/core/skbuff.c (ffffffff81a8a760)
Location: include/linux/skbuff.h:4289
Inline: True
Inline callers:
  - net/core/skbuff.c:__skb_ext_set
  - net/core/skbuff.c:napi_skb_free_stolen_head
  - net/core/skbuff.c:skb_release_head_state
```
```
In net/ipv4/ip_output.c (ffffffff81b4c681)
Location: include/linux/skbuff.h:4289
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_copy_metadata
```
```
In net/ipv4/tcp_input.c (ffffffff81b645b3)
Location: include/linux/skbuff.h:4289
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_collapse
```
```
In net/ipv4/tcp_output.c (ffffffff81b72fe1)
Location: include/linux/skbuff.h:4289
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_mtu_probe
  - net/ipv4/tcp_output.c:tso_fragment
  - net/ipv4/tcp_output.c:tcp_fragment
```
```
In net/ipv6/ip6_output.c (ffffffff81bef7bc)
Location: include/linux/skbuff.h:4289
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_copy_metadata
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
In net/core/skbuff.c (ffffffff81bffbd0)
Location: include/linux/skbuff.h:4711
Inline: True
Inline callers:
  - net/core/skbuff.c:__skb_ext_set
  - net/core/skbuff.c:__skb_ext_set
  - net/core/skbuff.c:napi_skb_free_stolen_head
  - net/core/skbuff.c:napi_skb_free_stolen_head
  - net/core/skbuff.c:skb_release_head_state
  - net/core/skbuff.c:skb_release_head_state
```
```
In net/ipv4/ip_output.c (ffffffff81cd9d07)
Location: include/linux/skbuff.h:4711
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_copy_metadata
```
```
In net/ipv4/tcp_input.c (ffffffff81cf338e)
Location: include/linux/skbuff.h:4711
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_collapse
```
```
In net/ipv4/tcp_output.c (ffffffff81d026f8)
Location: include/linux/skbuff.h:4711
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_mtu_probe
  - net/ipv4/tcp_output.c:tso_fragment
  - net/ipv4/tcp_output.c:tcp_fragment
```
```
In net/ipv6/ip6_output.c (ffffffff81d882da)
Location: include/linux/skbuff.h:4711
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_copy_metadata
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
In net/core/skbuff.c (ffffffff81daef50)
Location: include/linux/skbuff.h:4607
Inline: True
Inline callers:
  - net/core/skbuff.c:__skb_ext_set
  - net/core/skbuff.c:__skb_ext_set
  - net/core/skbuff.c:napi_skb_free_stolen_head
  - net/core/skbuff.c:napi_skb_free_stolen_head
  - net/core/skbuff.c:skb_release_head_state
  - net/core/skbuff.c:skb_release_head_state
```
```
In net/ipv4/ip_output.c (ffffffff81e9a497)
Location: include/linux/skbuff.h:4607
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_copy_metadata
```
```
In net/ipv4/tcp_input.c (ffffffff81eb79be)
Location: include/linux/skbuff.h:4607
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_collapse
```
```
In net/ipv4/tcp_output.c (ffffffff81ec78d8)
Location: include/linux/skbuff.h:4607
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_mtu_probe
  - net/ipv4/tcp_output.c:tso_fragment
  - net/ipv4/tcp_output.c:tcp_fragment
```
```
In net/ipv6/ip6_output.c (ffffffff81f5608a)
Location: include/linux/skbuff.h:4607
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_copy_metadata
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
In net/core/skbuff.c (ffffffff81e1f140)
Location: include/linux/skbuff.h:4639
Inline: True
Inline callers:
  - net/core/skbuff.c:__skb_ext_set
  - net/core/skbuff.c:__skb_ext_set
  - net/core/skbuff.c:napi_skb_free_stolen_head
  - net/core/skbuff.c:napi_skb_free_stolen_head
  - net/core/skbuff.c:skb_release_head_state
  - net/core/skbuff.c:skb_release_head_state
```
```
In net/ipv4/ip_output.c (ffffffff81ef8df1)
Location: include/linux/skbuff.h:4639
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_copy_metadata
```
```
In net/ipv4/tcp_input.c (ffffffff81f160a4)
Location: include/linux/skbuff.h:4639
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_collapse
```
```
In net/ipv4/tcp_output.c (ffffffff81f2678d)
Location: include/linux/skbuff.h:4639
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_mtu_probe
  - net/ipv4/tcp_output.c:tcp_fragment
```
```
In net/ipv6/ip6_output.c (ffffffff81fb5a56)
Location: include/linux/skbuff.h:4639
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_copy_metadata
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff81edc7a0)
Location: include/linux/skbuff.h:4679
Inline: True
Inline callers:
  - net/core/skbuff.c:__skb_ext_set
  - net/core/skbuff.c:__skb_ext_set
  - net/core/skbuff.c:napi_skb_free_stolen_head
  - net/core/skbuff.c:napi_skb_free_stolen_head
  - net/core/skbuff.c:skb_release_head_state
  - net/core/skbuff.c:skb_release_head_state
```
```
In net/ipv4/ip_output.c (ffffffff81fbcd11)
Location: include/linux/skbuff.h:4679
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_copy_metadata
```
```
In net/ipv4/tcp_input.c (ffffffff81fda43d)
Location: include/linux/skbuff.h:4679
Inline: True
Inline callers:
  - net/ipv4/tcp_input.c:tcp_collapse
```
```
In net/ipv4/tcp_output.c (ffffffff81feb16d)
Location: include/linux/skbuff.h:4679
Inline: True
Inline callers:
  - net/ipv4/tcp_output.c:tcp_write_xmit
  - net/ipv4/tcp_output.c:tcp_mtu_probe
  - net/ipv4/tcp_output.c:tcp_fragment
```
```
In net/ipv6/ip6_output.c (ffffffff82083126)
Location: include/linux/skbuff.h:4679
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_copy_metadata
```
</details>
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
In net/core/skbuff.c (ffff800010bb52c0)
Location: include/linux/skbuff.h:4118
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_release_head_state
```
```
In net/core/dev.c (ffff800010bc8a18)
Location: include/linux/skbuff.h:4118
Inline: True
Inline callers:
  - net/core/dev.c:napi_skb_free_stolen_head
```
```
In net/ipv4/ip_output.c (ffff800010c62430)
Location: include/linux/skbuff.h:4118
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_copy_metadata
```
```
In net/ipv6/ip6_output.c (ffff800010cf84d8)
Location: include/linux/skbuff.h:4118
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_copy_metadata
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
In net/core/skbuff.c (c0cd23b8)
Location: include/linux/skbuff.h:4118
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_release_head_state
```
```
In net/core/dev.c (c0ce4b20)
Location: include/linux/skbuff.h:4118
Inline: True
Inline callers:
  - net/core/dev.c:napi_skb_free_stolen_head
```
```
In net/ipv4/ip_output.c (c0d71c44)
Location: include/linux/skbuff.h:4118
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_copy_metadata
```
```
In net/ipv6/ip6_output.c (c0dffc48)
Location: include/linux/skbuff.h:4118
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_copy_metadata
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
In net/core/skbuff.c (c000000000c8c31c)
Location: include/linux/skbuff.h:4118
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_release_head_state
```
```
In net/core/dev.c (c000000000ca519c)
Location: include/linux/skbuff.h:4118
Inline: True
Inline callers:
  - net/core/dev.c:napi_skb_free_stolen_head
```
```
In net/ipv4/ip_output.c (c000000000d656f8)
Location: include/linux/skbuff.h:4118
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_copy_metadata
```
```
In net/ipv6/ip6_output.c (c000000000e204b8)
Location: include/linux/skbuff.h:4118
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_copy_metadata
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
In net/core/skbuff.c (ffffffe00074536a)
Location: include/linux/skbuff.h:4118
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_release_head_state
```
```
In net/core/dev.c (ffffffe000755216)
Location: include/linux/skbuff.h:4118
Inline: True
Inline callers:
  - net/core/dev.c:napi_skb_free_stolen_head
```
```
In net/ipv4/ip_output.c (ffffffe0007c9fb6)
Location: include/linux/skbuff.h:4118
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_copy_metadata
```
```
In net/ipv6/ip6_output.c (ffffffe0008442a2)
Location: include/linux/skbuff.h:4118
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_copy_metadata
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
In net/core/skbuff.c (ffffffff818baf23)
Location: include/linux/skbuff.h:4118
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_release_head_state
```
```
In net/core/dev.c (ffffffff818cc416)
Location: include/linux/skbuff.h:4118
Inline: True
Inline callers:
  - net/core/dev.c:napi_skb_free_stolen_head
```
```
In net/ipv4/ip_output.c (ffffffff819518db)
Location: include/linux/skbuff.h:4118
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_copy_metadata
```
```
In net/ipv6/ip6_output.c (ffffffff819d73f4)
Location: include/linux/skbuff.h:4118
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_copy_metadata
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
In net/core/skbuff.c (ffffffff81874e63)
Location: include/linux/skbuff.h:4118
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_release_head_state
```
```
In net/core/dev.c (ffffffff818864a6)
Location: include/linux/skbuff.h:4118
Inline: True
Inline callers:
  - net/core/dev.c:napi_skb_free_stolen_head
```
```
In net/ipv4/ip_output.c (ffffffff8190b3cb)
Location: include/linux/skbuff.h:4118
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_copy_metadata
```
```
In net/ipv6/ip6_output.c (ffffffff819941b4)
Location: include/linux/skbuff.h:4118
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_copy_metadata
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
In net/core/skbuff.c (ffffffff8190bf23)
Location: include/linux/skbuff.h:4118
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_release_head_state
```
```
In net/core/dev.c (ffffffff8191d416)
Location: include/linux/skbuff.h:4118
Inline: True
Inline callers:
  - net/core/dev.c:napi_skb_free_stolen_head
```
```
In net/ipv4/ip_output.c (ffffffff819bc0ab)
Location: include/linux/skbuff.h:4118
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_copy_metadata
```
```
In net/ipv6/ip6_output.c (ffffffff81a41e74)
Location: include/linux/skbuff.h:4118
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_copy_metadata
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
In net/core/skbuff.c (ffffffff8192d043)
Location: include/linux/skbuff.h:4118
Inline: True
Inline callers:
  - net/core/skbuff.c:skb_release_head_state
```
```
In net/core/dev.c (ffffffff8193e936)
Location: include/linux/skbuff.h:4118
Inline: True
Inline callers:
  - net/core/dev.c:napi_skb_free_stolen_head
```
```
In net/ipv4/ip_output.c (ffffffff819c59bb)
Location: include/linux/skbuff.h:4118
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_copy_metadata
```
```
In net/ipv6/ip6_output.c (ffffffff81a4db04)
Location: include/linux/skbuff.h:4118
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_copy_metadata
```
</details>
</li>
</ul>

## Differences
