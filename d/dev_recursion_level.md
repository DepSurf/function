# Function: <code>dev_recursion_level</code>

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
In net/core/sock.c (ffffffff817014b5)
Location: include/linux/netdevice.h:2300
Inline: True
```
```
In net/ipv6/ip6_output.c (ffffffff817c7174)
Location: include/linux/netdevice.h:2300
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fragment
```
```
In net/ipv6/xfrm6_output.c (ffffffff817fd0fd)
Location: include/linux/netdevice.h:2300
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
In net/core/sock.c (ffffffff817685b5)
Location: include/linux/netdevice.h:2437
Inline: True
```
```
In net/ipv6/ip6_output.c (ffffffff81834254)
Location: include/linux/netdevice.h:2437
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fragment
```
```
In net/ipv6/xfrm6_output.c (ffffffff8186ca2d)
Location: include/linux/netdevice.h:2437
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
In net/core/sock.c (ffffffff81795605)
Location: include/linux/netdevice.h:2434
Inline: True
```
```
In net/ipv6/ip6_output.c (ffffffff81865cb4)
Location: include/linux/netdevice.h:2434
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fragment
```
```
In net/ipv6/xfrm6_output.c (ffffffff8189f81d)
Location: include/linux/netdevice.h:2434
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
In net/core/sock.c (ffffffff817b3278)
Location: include/linux/netdevice.h:2449
Inline: True
```
```
In net/ipv6/ip6_output.c (ffffffff8188a463)
Location: include/linux/netdevice.h:2449
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_finish_output
```
```
In net/ipv6/xfrm6_output.c (ffffffff818c6021)
Location: include/linux/netdevice.h:2449
Inline: True
Inline callers:
  - net/ipv6/xfrm6_output.c:xfrm6_extract_output
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
In net/core/sock.c (ffffffff8182b558)
Location: include/linux/netdevice.h:2474
Inline: True
```
```
In net/ipv6/ip6_output.c (ffffffff8190b663)
Location: include/linux/netdevice.h:2474
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_finish_output
```
```
In net/ipv6/xfrm6_output.c (ffffffff819493c5)
Location: include/linux/netdevice.h:2474
Inline: True
Inline callers:
  - net/ipv6/xfrm6_output.c:xfrm6_extract_output
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
In net/core/sock.c (ffffffff81875a85)
Location: include/linux/netdevice.h:2560
Inline: True
```
```
In net/ipv6/ip6_output.c (ffffffff81962af4)
Location: include/linux/netdevice.h:2560
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_finish_output
```
```
In net/ipv6/xfrm6_output.c (ffffffff819a2241)
Location: include/linux/netdevice.h:2560
Inline: True
Inline callers:
  - net/ipv6/xfrm6_output.c:__xfrm6_output
  - net/ipv6/xfrm6_output.c:xfrm6_extract_output
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
In net/core/sock.c (ffffffff81896275)
Location: include/linux/netdevice.h:2654
Inline: True
```
```
In net/ipv6/ip6_output.c (ffffffff81997ae1)
Location: include/linux/netdevice.h:2654
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_finish_output
```
```
In net/ipv6/xfrm6_output.c (ffffffff819d8e9e)
Location: include/linux/netdevice.h:2654
Inline: True
Inline callers:
  - net/ipv6/xfrm6_output.c:__xfrm6_output
  - net/ipv6/xfrm6_output.c:xfrm6_extract_output
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
In net/core/sock.c (ffffffff818e0a05)
Location: include/linux/netdevice.h:3028
Inline: True
```
```
In net/ipv6/ip6_output.c (ffffffff81a03bb4)
Location: include/linux/netdevice.h:3028
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fragment
```
```
In net/ipv6/xfrm6_output.c (ffffffff81a47710)
Location: include/linux/netdevice.h:3028
Inline: True
Inline callers:
  - net/ipv6/xfrm6_output.c:__xfrm6_output
  - net/ipv6/xfrm6_output.c:xfrm6_extract_output
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
In net/core/sock.c (ffffffff819128d5)
Location: include/linux/netdevice.h:3041
Inline: True
```
```
In net/ipv6/ip6_output.c (ffffffff81a3a783)
Location: include/linux/netdevice.h:3041
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fragment
```
```
In net/ipv6/xfrm6_output.c (ffffffff81a7e290)
Location: include/linux/netdevice.h:3041
Inline: True
Inline callers:
  - net/ipv6/xfrm6_output.c:__xfrm6_output
  - net/ipv6/xfrm6_output.c:xfrm6_extract_output
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
In net/core/sock.c (ffffffff819e4775)
Location: include/linux/netdevice.h:3155
Inline: True
```
```
In net/xfrm/xfrm_output.c (ffffffff81b1f064)
Location: include/linux/netdevice.h:3155
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm6_tunnel_check_size
```
```
In net/ipv6/ip6_output.c (ffffffff81b2fd61)
Location: include/linux/netdevice.h:3155
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fragment
```
```
In net/ipv6/xfrm6_output.c (ffffffff81b78fa6)
Location: include/linux/netdevice.h:3155
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
In net/core/sock.c (ffffffff819e4005)
Location: include/linux/netdevice.h:3309
Inline: True
```
```
In net/xfrm/xfrm_output.c (ffffffff81b2d924)
Location: include/linux/netdevice.h:3309
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm6_tunnel_check_size
```
```
In net/ipv6/ip6_output.c (ffffffff81b3e801)
Location: include/linux/netdevice.h:3309
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fragment
```
```
In net/ipv6/xfrm6_output.c (ffffffff81b87f26)
Location: include/linux/netdevice.h:3309
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
In net/core/sock.c (ffffffff819ca095)
Location: include/linux/netdevice.h:3376
Inline: True
```
```
In net/xfrm/xfrm_output.c (ffffffff81b1b987)
Location: include/linux/netdevice.h:3376
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm6_tunnel_check_size
```
```
In net/ipv6/ip6_output.c (ffffffff81b2b5a1)
Location: include/linux/netdevice.h:3376
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fragment
```
```
In net/ipv6/xfrm6_output.c (ffffffff81b76b96)
Location: include/linux/netdevice.h:3376
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
In net/core/sock.c (ffffffff81a795d5)
Location: include/linux/netdevice.h:3388
Inline: True
```
```
In net/xfrm/xfrm_output.c (ffffffff81be0206)
Location: include/linux/netdevice.h:3388
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm6_tunnel_check_size
```
```
In net/ipv6/ip6_output.c (ffffffff81bf16d8)
Location: include/linux/netdevice.h:3388
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fragment
```
```
In net/ipv6/xfrm6_output.c (ffffffff81c415f8)
Location: include/linux/netdevice.h:3388
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
In net/core/sock.c (ffffffff81becde5)
Location: include/linux/netdevice.h:3179
Inline: True
```
```
In net/xfrm/xfrm_output.c (ffffffff81d77117)
Location: include/linux/netdevice.h:3179
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm6_tunnel_check_size
```
```
In net/ipv6/ip6_output.c (ffffffff81d8a03e)
Location: include/linux/netdevice.h:3179
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_finish_output
```
```
In net/ipv6/xfrm6_output.c (ffffffff81ddfe14)
Location: include/linux/netdevice.h:3179
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
In net/core/sock.c (ffffffff81d9a825)
Location: include/linux/netdevice.h:3204
Inline: True
```
```
In net/xfrm/xfrm_output.c (ffffffff81f43997)
Location: include/linux/netdevice.h:3204
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm6_tunnel_check_size
```
```
In net/ipv6/ip6_output.c (ffffffff81f57fce)
Location: include/linux/netdevice.h:3204
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_finish_output
```
```
In net/ipv6/xfrm6_output.c (ffffffff81fb2134)
Location: include/linux/netdevice.h:3204
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
In net/core/sock.c (ffffffff81e09085)
Location: include/linux/netdevice.h:3267
Inline: True
```
```
In net/xfrm/xfrm_output.c (ffffffff81fa3171)
Location: include/linux/netdevice.h:3267
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm6_tunnel_check_size
```
```
In net/ipv6/ip6_output.c (ffffffff81fb7bae)
Location: include/linux/netdevice.h:3267
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_finish_output
```
```
In net/ipv6/xfrm6_output.c (ffffffff82012841)
Location: include/linux/netdevice.h:3267
Inline: True
Inline callers:
  - net/ipv6/xfrm6_output.c:__xfrm6_output
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
In net/core/sock.c (ffffffff81ec3f75)
Location: include/linux/netdevice.h:3346
Inline: True
```
```
In net/xfrm/xfrm_output.c (ffffffff820707f1)
Location: include/linux/netdevice.h:3346
Inline: True
Inline callers:
  - net/xfrm/xfrm_output.c:xfrm6_tunnel_check_size
```
```
In net/ipv6/ip6_output.c (ffffffff820851ee)
Location: include/linux/netdevice.h:3346
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_finish_output
```
```
In net/ipv6/xfrm6_output.c (ffffffff820e19ac)
Location: include/linux/netdevice.h:3346
Inline: True
Inline callers:
  - net/ipv6/xfrm6_output.c:__xfrm6_output
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
In net/core/sock.c (ffff800010bab2e8)
Location: include/linux/netdevice.h:3041
Inline: True
```
```
In net/ipv6/ip6_output.c (ffff800010cfb840)
Location: include/linux/netdevice.h:3041
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fragment
```
```
In net/ipv6/xfrm6_output.c (ffff800010d496b4)
Location: include/linux/netdevice.h:3041
Inline: True
Inline callers:
  - net/ipv6/xfrm6_output.c:__xfrm6_output
  - net/ipv6/xfrm6_output.c:xfrm6_extract_output
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
In net/core/sock.c (c0cc8cc0)
Location: include/linux/netdevice.h:3041
Inline: True
```
```
In net/ipv6/ip6_output.c (c0e02730)
Location: include/linux/netdevice.h:3041
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fragment
```
```
In net/ipv6/xfrm6_output.c (c0e4aa88)
Location: include/linux/netdevice.h:3041
Inline: True
Inline callers:
  - net/ipv6/xfrm6_output.c:__xfrm6_output
  - net/ipv6/xfrm6_output.c:xfrm6_extract_output
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
In net/core/sock.c (c000000000c80100)
Location: include/linux/netdevice.h:3041
Inline: True
```
```
In net/ipv6/ip6_output.c (c000000000e22f2c)
Location: include/linux/netdevice.h:3041
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fragment
```
```
In net/ipv6/xfrm6_output.c (c000000000e7ed4c)
Location: include/linux/netdevice.h:3041
Inline: True
Inline callers:
  - net/ipv6/xfrm6_output.c:__xfrm6_output
  - net/ipv6/xfrm6_output.c:xfrm6_extract_output
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
In net/core/sock.c (ffffffe00073d9fc)
Location: include/linux/netdevice.h:3041
Inline: True
```
```
In net/ipv6/ip6_output.c (ffffffe0008461f0)
Location: include/linux/netdevice.h:3041
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fragment
```
```
In net/ipv6/xfrm6_output.c (ffffffe000882b2a)
Location: include/linux/netdevice.h:3041
Inline: True
Inline callers:
  - net/ipv6/xfrm6_output.c:__xfrm6_output
  - net/ipv6/xfrm6_output.c:xfrm6_extract_output
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
In net/core/sock.c (ffffffff818b28d5)
Location: include/linux/netdevice.h:3041
Inline: True
```
```
In net/ipv6/ip6_output.c (ffffffff819d9e13)
Location: include/linux/netdevice.h:3041
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fragment
```
```
In net/ipv6/xfrm6_output.c (ffffffff81a1d920)
Location: include/linux/netdevice.h:3041
Inline: True
Inline callers:
  - net/ipv6/xfrm6_output.c:__xfrm6_output
  - net/ipv6/xfrm6_output.c:xfrm6_extract_output
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
In net/core/sock.c (ffffffff8186c825)
Location: include/linux/netdevice.h:3041
Inline: True
```
```
In net/ipv6/ip6_output.c (ffffffff81996bd3)
Location: include/linux/netdevice.h:3041
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fragment
```
```
In net/ipv6/xfrm6_output.c (ffffffff819da6e0)
Location: include/linux/netdevice.h:3041
Inline: True
Inline callers:
  - net/ipv6/xfrm6_output.c:__xfrm6_output
  - net/ipv6/xfrm6_output.c:xfrm6_extract_output
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
In net/core/sock.c (ffffffff819038d5)
Location: include/linux/netdevice.h:3041
Inline: True
```
```
In net/ipv6/ip6_output.c (ffffffff81a44893)
Location: include/linux/netdevice.h:3041
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fragment
```
```
In net/ipv6/xfrm6_output.c (ffffffff81a883a0)
Location: include/linux/netdevice.h:3041
Inline: True
Inline callers:
  - net/ipv6/xfrm6_output.c:__xfrm6_output
  - net/ipv6/xfrm6_output.c:xfrm6_extract_output
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
In net/core/sock.c (ffffffff819248d5)
Location: include/linux/netdevice.h:3041
Inline: True
```
```
In net/ipv6/ip6_output.c (ffffffff81a50553)
Location: include/linux/netdevice.h:3041
Inline: True
Inline callers:
  - net/ipv6/ip6_output.c:ip6_fragment
  - net/ipv6/ip6_output.c:ip6_fragment
```
```
In net/ipv6/xfrm6_output.c (ffffffff81a94ff0)
Location: include/linux/netdevice.h:3041
Inline: True
Inline callers:
  - net/ipv6/xfrm6_output.c:__xfrm6_output
  - net/ipv6/xfrm6_output.c:xfrm6_extract_output
```
</details>
</li>
</ul>

## Differences
