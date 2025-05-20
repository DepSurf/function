# Function: <code>ip_dst_mtu_maybe_forward</code>

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
In net/ipv4/ip_forward.c (ffffffff8175a843)
Location: include/net/ip.h:307
Inline: True
Inline callers:
  - net/ipv4/ip_forward.c:ip_forward
```
```
In net/ipv4/ip_output.c (ffffffff8175ca7f)
Location: include/net/ip.h:307
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_do_fragment
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
In net/ipv4/ip_forward.c (ffffffff817c6c01)
Location: include/net/ip.h:304
Inline: True
Inline callers:
  - net/ipv4/ip_forward.c:ip_forward
```
```
In net/ipv4/ip_output.c (ffffffff817c986b)
Location: include/net/ip.h:304
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_do_fragment
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
In net/ipv4/ip_forward.c (ffffffff817f6702)
Location: include/net/ip.h:333
Inline: True
Inline callers:
  - net/ipv4/ip_forward.c:ip_forward
```
```
In net/ipv4/ip_output.c (ffffffff817f97f4)
Location: include/net/ip.h:333
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_do_fragment
  - net/ipv4/ip_output.c:ip_finish_output
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
In net/ipv4/ip_forward.c (ffffffff81816b18)
Location: include/net/ip.h:345
Inline: True
Inline callers:
  - net/ipv4/ip_forward.c:ip_forward
```
```
In net/ipv4/ip_output.c (ffffffff81819c04)
Location: include/net/ip.h:345
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_do_fragment
  - net/ipv4/ip_output.c:ip_finish_output
```
```
In net/ipv4/xfrm4_output.c (ffffffff818725a4)
Location: include/net/ip.h:345
Inline: True
Inline callers:
  - net/ipv4/xfrm4_output.c:xfrm4_extract_output
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
In net/ipv4/ip_forward.c (ffffffff81895cd8)
Location: include/net/ip.h:356
Inline: True
Inline callers:
  - net/ipv4/ip_forward.c:ip_forward
```
```
In net/ipv4/ip_output.c (ffffffff81898239)
Location: include/net/ip.h:356
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_do_fragment
  - net/ipv4/ip_output.c:ip_finish_output
```
```
In net/ipv4/xfrm4_output.c (ffffffff818f2f9a)
Location: include/net/ip.h:356
Inline: True
Inline callers:
  - net/ipv4/xfrm4_output.c:xfrm4_extract_output
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
In net/ipv4/ip_forward.c (ffffffff818e9f95)
Location: include/net/ip.h:375
Inline: True
Inline callers:
  - net/ipv4/ip_forward.c:ip_forward
```
```
In net/ipv4/ip_output.c (ffffffff818ec207)
Location: include/net/ip.h:375
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_do_fragment
  - net/ipv4/ip_output.c:ip_finish_output
```
```
In net/ipv4/xfrm4_output.c (ffffffff819498dd)
Location: include/net/ip.h:375
Inline: True
Inline callers:
  - net/ipv4/xfrm4_output.c:xfrm4_extract_output
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
In net/ipv4/ip_forward.c (ffffffff819173b7)
Location: include/net/ip.h:399
Inline: True
Inline callers:
  - net/ipv4/ip_forward.c:ip_forward
```
```
In net/ipv4/ip_output.c (ffffffff819193a7)
Location: include/net/ip.h:399
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_do_fragment
  - net/ipv4/ip_output.c:ip_finish_output
```
```
In net/ipv4/xfrm4_output.c (ffffffff8197b59a)
Location: include/net/ip.h:399
Inline: True
Inline callers:
  - net/ipv4/xfrm4_output.c:xfrm4_extract_output
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
In net/ipv4/ip_forward.c (ffffffff819792f5)
Location: include/net/ip.h:437
Inline: True
Inline callers:
  - net/ipv4/ip_forward.c:ip_forward
```
```
In net/ipv4/ip_output.c (ffffffff8197b718)
Location: include/net/ip.h:437
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_do_fragment
```
```
In net/ipv4/xfrm4_output.c (ffffffff819e4ad0)
Location: include/net/ip.h:437
Inline: True
Inline callers:
  - net/ipv4/xfrm4_output.c:xfrm4_extract_output
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
In net/ipv4/ip_forward.c (ffffffff819afc65)
Location: include/net/ip.h:438
Inline: True
Inline callers:
  - net/ipv4/ip_forward.c:ip_forward
```
```
In net/ipv4/ip_output.c (ffffffff819b1fa1)
Location: include/net/ip.h:438
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_do_fragment
```
```
In net/ipv4/xfrm4_output.c (ffffffff81a1baf0)
Location: include/net/ip.h:438
Inline: True
Inline callers:
  - net/ipv4/xfrm4_output.c:xfrm4_extract_output
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
In net/ipv4/ip_forward.c (ffffffff81a99b35)
Location: include/net/ip.h:438
Inline: True
Inline callers:
  - net/ipv4/ip_forward.c:ip_forward
```
```
In net/ipv4/ip_output.c (ffffffff81a9c81e)
Location: include/net/ip.h:438
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_do_fragment
```
```
In net/xfrm/xfrm_output.c (ffffffff81b1fa3d)
Location: include/net/ip.h:438
Inline: True
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
In net/ipv4/ip_forward.c (ffffffff81aa3a85)
Location: include/net/ip.h:435
Inline: True
Inline callers:
  - net/ipv4/ip_forward.c:ip_forward
```
```
In net/ipv4/ip_output.c (ffffffff81aa6688)
Location: include/net/ip.h:435
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_do_fragment
```
```
In net/xfrm/xfrm_output.c (ffffffff81b2e319)
Location: include/net/ip.h:435
Inline: True
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
In net/ipv4/ip_forward.c (ffffffff81a8eb6b)
Location: include/net/ip.h:436
Inline: True
Inline callers:
  - net/ipv4/ip_forward.c:ip_forward
```
```
In net/ipv4/ip_output.c (ffffffff81a90abb)
Location: include/net/ip.h:436
Inline: True
```
```
In net/xfrm/xfrm_output.c (ffffffff81b1bd6e)
Location: include/net/ip.h:436
Inline: True
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
In net/ipv4/route.c (ffffffff81b42625)
Location: include/net/ip.h:436
Inline: True
Inline callers:
  - net/ipv4/route.c:ipv4_default_advmss
  - net/ipv4/route.c:__ip_rt_update_pmtu
```
```
In net/ipv4/ip_forward.c (ffffffff81b49d84)
Location: include/net/ip.h:436
Inline: True
Inline callers:
  - net/ipv4/ip_forward.c:ip_forward
```
```
In net/ipv4/ip_output.c (ffffffff81b4bc5b)
Location: include/net/ip.h:436
Inline: True
```
```
In net/xfrm/xfrm_output.c (ffffffff81be008d)
Location: include/net/ip.h:436
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:ip_skb_dst_mtu
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
In net/ipv4/route.c (ffffffff81ccf577)
Location: include/net/ip.h:442
Inline: True
Inline callers:
  - net/ipv4/route.c:ipv4_default_advmss
  - net/ipv4/route.c:__ip_rt_update_pmtu
```
```
In net/ipv4/ip_forward.c (ffffffff81cd72b8)
Location: include/net/ip.h:442
Inline: True
Inline callers:
  - net/ipv4/ip_forward.c:ip_forward
```
```
In net/ipv4/ip_output.c (ffffffff81cd936d)
Location: include/net/ip.h:442
Inline: True
```
```
In net/xfrm/xfrm_output.c (ffffffff81d774c1)
Location: include/net/ip.h:442
Inline: True
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
In net/ipv4/route.c (ffffffff81e8f767)
Location: include/net/ip.h:442
Inline: True
Inline callers:
  - net/ipv4/route.c:ipv4_default_advmss
  - net/ipv4/route.c:__ip_rt_update_pmtu
```
```
In net/ipv4/ip_forward.c (ffffffff81e978d9)
Location: include/net/ip.h:442
Inline: True
Inline callers:
  - net/ipv4/ip_forward.c:ip_forward
```
```
In net/ipv4/ip_output.c (ffffffff81e99abd)
Location: include/net/ip.h:442
Inline: True
```
```
In net/xfrm/xfrm_output.c (ffffffff81f43d51)
Location: include/net/ip.h:442
Inline: True
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
In net/ipv4/route.c (ffffffff81eede67)
Location: include/net/ip.h:451
Inline: True
Inline callers:
  - net/ipv4/route.c:ipv4_default_advmss
  - net/ipv4/route.c:__ip_rt_update_pmtu
```
```
In net/ipv4/ip_forward.c (ffffffff81ef6119)
Location: include/net/ip.h:451
Inline: True
Inline callers:
  - net/ipv4/ip_forward.c:ip_forward
```
```
In net/ipv4/ip_output.c (ffffffff81ef8424)
Location: include/net/ip.h:451
Inline: True
```
```
In net/xfrm/xfrm_output.c (ffffffff81fa352f)
Location: include/net/ip.h:451
Inline: True
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
In net/ipv4/route.c (ffffffff81fb1fc7)
Location: include/net/ip.h:461
Inline: True
Inline callers:
  - net/ipv4/route.c:ipv4_default_advmss
  - net/ipv4/route.c:__ip_rt_update_pmtu
```
```
In net/ipv4/ip_forward.c (ffffffff81fba0b5)
Location: include/net/ip.h:461
Inline: True
Inline callers:
  - net/ipv4/ip_forward.c:ip_forward
```
```
In net/ipv4/ip_output.c (ffffffff81fbc343)
Location: include/net/ip.h:461
Inline: True
```
```
In net/xfrm/xfrm_output.c (ffffffff8207047a)
Location: include/net/ip.h:461
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:ip_skb_dst_mtu
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
In net/ipv4/ip_forward.c (ffff800010c60318)
Location: include/net/ip.h:438
Inline: True
Inline callers:
  - net/ipv4/ip_forward.c:ip_forward
```
```
In net/ipv4/ip_output.c (ffff800010c63d24)
Location: include/net/ip.h:438
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_do_fragment
```
```
In net/ipv4/xfrm4_output.c (ffff800010cd7d90)
Location: include/net/ip.h:438
Inline: True
Inline callers:
  - net/ipv4/xfrm4_output.c:xfrm4_extract_output
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
In net/ipv4/ip_forward.c (c0d6fc7c)
Location: include/net/ip.h:438
Inline: True
Inline callers:
  - net/ipv4/ip_forward.c:ip_forward
```
```
In net/ipv4/ip_output.c (c0d71ffc)
Location: include/net/ip.h:438
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_do_fragment
```
```
In net/ipv4/xfrm4_output.c (c0de1854)
Location: include/net/ip.h:438
Inline: True
Inline callers:
  - net/ipv4/xfrm4_output.c:xfrm4_extract_output
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
In net/ipv4/ip_forward.c (c000000000d63230)
Location: include/net/ip.h:438
Inline: True
Inline callers:
  - net/ipv4/ip_forward.c:ip_forward
```
```
In net/ipv4/ip_output.c (c000000000d65ee0)
Location: include/net/ip.h:438
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_do_fragment
```
```
In net/ipv4/xfrm4_output.c (c000000000df7e20)
Location: include/net/ip.h:438
Inline: True
Inline callers:
  - net/ipv4/xfrm4_output.c:xfrm4_extract_output
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
In net/ipv4/ip_forward.c (ffffffe0007c85b2)
Location: include/net/ip.h:438
Inline: True
Inline callers:
  - net/ipv4/ip_forward.c:ip_forward
```
```
In net/ipv4/ip_output.c (ffffffe0007ca5de)
Location: include/net/ip.h:438
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_do_fragment
```
```
In net/ipv4/xfrm4_output.c (ffffffe00082836c)
Location: include/net/ip.h:438
Inline: True
Inline callers:
  - net/ipv4/xfrm4_output.c:xfrm4_extract_output
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
In net/ipv4/ip_forward.c (ffffffff8194fad5)
Location: include/net/ip.h:438
Inline: True
Inline callers:
  - net/ipv4/ip_forward.c:ip_forward
```
```
In net/ipv4/ip_output.c (ffffffff81951e11)
Location: include/net/ip.h:438
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_do_fragment
```
```
In net/ipv4/xfrm4_output.c (ffffffff819bb180)
Location: include/net/ip.h:438
Inline: True
Inline callers:
  - net/ipv4/xfrm4_output.c:xfrm4_extract_output
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
In net/ipv4/ip_forward.c (ffffffff819095c5)
Location: include/net/ip.h:438
Inline: True
Inline callers:
  - net/ipv4/ip_forward.c:ip_forward
```
```
In net/ipv4/ip_output.c (ffffffff8190b901)
Location: include/net/ip.h:438
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_do_fragment
```
```
In net/ipv4/xfrm4_output.c (ffffffff81977f70)
Location: include/net/ip.h:438
Inline: True
Inline callers:
  - net/ipv4/xfrm4_output.c:xfrm4_extract_output
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
In net/ipv4/ip_forward.c (ffffffff819ba2a5)
Location: include/net/ip.h:438
Inline: True
Inline callers:
  - net/ipv4/ip_forward.c:ip_forward
```
```
In net/ipv4/ip_output.c (ffffffff819bc5e1)
Location: include/net/ip.h:438
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_do_fragment
```
```
In net/ipv4/xfrm4_output.c (ffffffff81a25c00)
Location: include/net/ip.h:438
Inline: True
Inline callers:
  - net/ipv4/xfrm4_output.c:xfrm4_extract_output
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
In net/ipv4/ip_forward.c (ffffffff819c3b95)
Location: include/net/ip.h:438
Inline: True
Inline callers:
  - net/ipv4/ip_forward.c:ip_forward
```
```
In net/ipv4/ip_output.c (ffffffff819c5ef1)
Location: include/net/ip.h:438
Inline: True
Inline callers:
  - net/ipv4/ip_output.c:ip_do_fragment
```
```
In net/ipv4/xfrm4_output.c (ffffffff81a310a0)
Location: include/net/ip.h:438
Inline: True
Inline callers:
  - net/ipv4/xfrm4_output.c:xfrm4_extract_output
```
</details>
</li>
</ul>

## Differences
