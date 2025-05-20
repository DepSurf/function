# Function: <code>ip_route_input</code>

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
In net/ipv4/route.c (ffffffff817573c2)
Location: include/net/route.h:180
Inline: True
Inline callers:
  - net/ipv4/route.c:inet_rtm_getroute
```
```
In net/ipv4/ip_options.c (ffffffff8175b3ef)
Location: include/net/route.h:180
Inline: True
Inline callers:
  - net/ipv4/ip_options.c:ip_options_rcv_srr
```
```
In net/ipv4/icmp.c (ffffffff8178e350)
Location: include/net/route.h:180
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_route_lookup
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
In net/ipv4/route.c (ffffffff817c3666)
Location: include/net/route.h:180
Inline: True
Inline callers:
  - net/ipv4/route.c:inet_rtm_getroute
```
```
In net/ipv4/ip_options.c (ffffffff817c76f4)
Location: include/net/route.h:180
Inline: True
Inline callers:
  - net/ipv4/ip_options.c:ip_options_rcv_srr
```
```
In net/ipv4/icmp.c (ffffffff817fb956)
Location: include/net/route.h:180
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_route_lookup
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
In net/ipv4/route.c (ffffffff817f2c89)
Location: include/net/route.h:179
Inline: True
Inline callers:
  - net/ipv4/route.c:inet_rtm_getroute
```
```
In net/ipv4/ip_options.c (ffffffff817f71e4)
Location: include/net/route.h:179
Inline: True
Inline callers:
  - net/ipv4/ip_options.c:ip_options_rcv_srr
```
```
In net/ipv4/icmp.c (ffffffff8182c85d)
Location: include/net/route.h:179
Inline: True
Inline callers:
  - net/ipv4/icmp.c:icmp_route_lookup
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
In net/ipv4/ip_options.c (ffffffff818175bf)
Location: include/net/route.h:185
Inline: True
Inline callers:
  - net/ipv4/ip_options.c:ip_options_rcv_srr
```
```
In net/ipv4/icmp.c (ffffffff8184dc3e)
Location: include/net/route.h:185
Inline: True
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
In net/ipv4/ip_options.c (ffffffff8189677f)
Location: include/net/route.h:187
Inline: True
Inline callers:
  - net/ipv4/ip_options.c:ip_options_rcv_srr
```
```
In net/ipv4/icmp.c (ffffffff818cd94e)
Location: include/net/route.h:187
Inline: True
```
```
In net/ipv6/seg6_local.c (ffffffff8194fb59)
Location: include/net/route.h:187
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:input_action_end_dx4
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
In net/ipv4/ip_options.c (ffffffff818eaa68)
Location: include/net/route.h:186
Inline: True
Inline callers:
  - net/ipv4/ip_options.c:ip_options_rcv_srr
```
```
In net/ipv4/icmp.c (ffffffff81923d5b)
Location: include/net/route.h:186
Inline: True
```
```
In net/ipv6/seg6_local.c (ffffffff819a89fb)
Location: include/net/route.h:186
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:input_action_end_dx4
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
In net/ipv4/ip_options.c (ffffffff819177e0)
Location: include/net/route.h:186
Inline: True
Inline callers:
  - net/ipv4/ip_options.c:ip_options_rcv_srr
```
```
In net/ipv4/icmp.c (ffffffff81952b45)
Location: include/net/route.h:186
Inline: True
```
```
In net/ipv6/seg6_local.c (ffffffff819df525)
Location: include/net/route.h:186
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:input_action_end_dx4
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
In net/ipv4/ip_options.c (ffffffff81979ee8)
Location: include/net/route.h:187
Inline: True
Inline callers:
  - net/ipv4/ip_options.c:ip_options_rcv_srr
```
```
In net/ipv4/icmp.c (ffffffff819b73bc)
Location: include/net/route.h:187
Inline: True
```
```
In net/ipv6/seg6_local.c (ffffffff81a4e0e9)
Location: include/net/route.h:187
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:input_action_end_dx4
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
In net/ipv4/ip_options.c (ffffffff819b0848)
Location: include/net/route.h:188
Inline: True
Inline callers:
  - net/ipv4/ip_options.c:ip_options_rcv_srr
```
```
In net/ipv4/icmp.c (ffffffff819ee0bc)
Location: include/net/route.h:188
Inline: True
```
```
In net/ipv6/seg6_local.c (ffffffff81a84d3a)
Location: include/net/route.h:188
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:input_action_end_dx4
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
In net/ipv4/ip_options.c (ffffffff81a9a6d8)
Location: include/net/route.h:198
Inline: True
Inline callers:
  - net/ipv4/ip_options.c:ip_options_rcv_srr
```
```
In net/ipv4/icmp.c (ffffffff81adbe80)
Location: include/net/route.h:198
Inline: True
```
```
In net/ipv6/seg6_local.c (ffffffff81b800c0)
Location: include/net/route.h:198
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:input_action_end_dx4
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
In net/ipv4/ip_options.c (ffffffff81aa4636)
Location: include/net/route.h:198
Inline: True
Inline callers:
  - net/ipv4/ip_options.c:ip_options_rcv_srr
```
```
In net/ipv4/icmp.c (ffffffff81ae89ad)
Location: include/net/route.h:198
Inline: True
```
```
In net/ipv6/seg6_local.c (ffffffff81b8f261)
Location: include/net/route.h:198
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:input_action_end_dt4
  - net/ipv6/seg6_local.c:input_action_end_dx4
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
In net/ipv4/ip_options.c (ffffffff81a8f72a)
Location: include/net/route.h:198
Inline: True
Inline callers:
  - net/ipv4/ip_options.c:ip_options_rcv_srr
```
```
In net/ipv4/icmp.c (ffffffff81ad3c5a)
Location: include/net/route.h:198
Inline: True
```
```
In net/ipv6/seg6_local.c (ffffffff81b7ec21)
Location: include/net/route.h:198
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:input_action_end_dt4
  - net/ipv6/seg6_local.c:input_action_end_dx4
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
In net/ipv4/ip_options.c (ffffffff81b4a96a)
Location: include/net/route.h:198
Inline: True
Inline callers:
  - net/ipv4/ip_options.c:ip_options_rcv_srr
```
```
In net/ipv4/icmp.c (ffffffff81b9291a)
Location: include/net/route.h:198
Inline: True
```
```
In net/ipv6/seg6_local.c (ffffffff81c4a386)
Location: include/net/route.h:198
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:input_action_end_dt4
  - net/ipv6/seg6_local.c:input_action_end_dx4_finish
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
In net/ipv4/ip_options.c (ffffffff81cd77b4)
Location: include/net/route.h:212
Inline: True
Inline callers:
  - net/ipv4/ip_options.c:ip_options_rcv_srr
```
```
In net/ipv4/icmp.c (ffffffff81d23f49)
Location: include/net/route.h:212
Inline: True
```
```
In net/ipv6/seg6_local.c (ffffffff81de9a55)
Location: include/net/route.h:212
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:input_action_end_dt4
  - net/ipv6/seg6_local.c:input_action_end_dx4_finish
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
In net/ipv4/ip_options.c (ffffffff81e97e36)
Location: include/net/route.h:208
Inline: True
Inline callers:
  - net/ipv4/ip_options.c:ip_options_rcv_srr
```
```
In net/ipv4/icmp.c (ffffffff81eeb5d9)
Location: include/net/route.h:208
Inline: True
```
```
In net/ipv6/seg6_local.c (ffffffff81fbd195)
Location: include/net/route.h:208
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:input_action_end_dt4
  - net/ipv6/seg6_local.c:input_action_end_dx4_finish
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
In net/ipv4/ip_options.c (ffffffff81ef6692)
Location: include/net/route.h:202
Inline: True
Inline callers:
  - net/ipv4/ip_options.c:ip_options_rcv_srr
```
```
In net/ipv4/icmp.c (ffffffff81f4af1c)
Location: include/net/route.h:202
Inline: True
```
```
In net/ipv6/seg6_local.c (ffffffff8201df45)
Location: include/net/route.h:202
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:input_action_end_dt4
  - net/ipv6/seg6_local.c:input_action_end_dx4_finish
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
In net/ipv4/ip_options.c (ffffffff81fba622)
Location: include/net/route.h:196
Inline: True
Inline callers:
  - net/ipv4/ip_options.c:ip_options_rcv_srr
```
```
In net/ipv4/icmp.c (ffffffff82011034)
Location: include/net/route.h:196
Inline: True
```
```
In net/ipv6/seg6_local.c (ffffffff820ecf25)
Location: include/net/route.h:196
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:input_action_end_dt4
  - net/ipv6/seg6_local.c:input_action_end_dx4_finish
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
In net/ipv4/ip_options.c (ffff800010c60e34)
Location: include/net/route.h:188
Inline: True
Inline callers:
  - net/ipv4/ip_options.c:ip_options_rcv_srr
```
```
In net/ipv4/icmp.c (ffff800010ca3c60)
Location: include/net/route.h:188
Inline: True
```
```
In net/ipv6/seg6_local.c (ffff800010d50dc8)
Location: include/net/route.h:188
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:input_action_end_dx4
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
In net/ipv4/ip_options.c (c0d70810)
Location: include/net/route.h:188
Inline: True
Inline callers:
  - net/ipv4/ip_options.c:ip_options_rcv_srr
```
```
In net/ipv4/icmp.c (c0db08e4)
Location: include/net/route.h:188
Inline: True
```
```
In net/ipv6/seg6_local.c (c0e51934)
Location: include/net/route.h:188
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:input_action_end_dx4
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
In net/ipv4/ip_options.c (c000000000d640f0)
Location: include/net/route.h:188
Inline: True
Inline callers:
  - net/ipv4/ip_options.c:ip_options_rcv_srr
```
```
In net/ipv4/icmp.c (c000000000db761c)
Location: include/net/route.h:188
Inline: True
```
```
In net/ipv6/seg6_local.c (c000000000e88c54)
Location: include/net/route.h:188
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:input_action_end_dx4
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
In net/ipv4/ip_options.c (ffffffe0007c903c)
Location: include/net/route.h:188
Inline: True
Inline callers:
  - net/ipv4/ip_options.c:ip_options_rcv_srr
```
```
In net/ipv4/icmp.c (ffffffe0007ffb18)
Location: include/net/route.h:188
Inline: True
```
```
In net/ipv6/seg6_local.c (ffffffe0008890de)
Location: include/net/route.h:188
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:input_action_end_dx4
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
In net/ipv4/ip_options.c (ffffffff819506b8)
Location: include/net/route.h:188
Inline: True
Inline callers:
  - net/ipv4/ip_options.c:ip_options_rcv_srr
```
```
In net/ipv4/icmp.c (ffffffff8198de5c)
Location: include/net/route.h:188
Inline: True
```
```
In net/ipv6/seg6_local.c (ffffffff81a243ca)
Location: include/net/route.h:188
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:input_action_end_dx4
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
In net/ipv4/ip_options.c (ffffffff8190a1a8)
Location: include/net/route.h:188
Inline: True
Inline callers:
  - net/ipv4/ip_options.c:ip_options_rcv_srr
```
```
In net/ipv4/icmp.c (ffffffff8194791c)
Location: include/net/route.h:188
Inline: True
```
```
In net/ipv6/seg6_local.c (ffffffff819e118a)
Location: include/net/route.h:188
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:input_action_end_dx4
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
In net/ipv4/ip_options.c (ffffffff819bae88)
Location: include/net/route.h:188
Inline: True
Inline callers:
  - net/ipv4/ip_options.c:ip_options_rcv_srr
```
```
In net/ipv4/icmp.c (ffffffff819f86fc)
Location: include/net/route.h:188
Inline: True
```
```
In net/ipv6/seg6_local.c (ffffffff81a8ee4a)
Location: include/net/route.h:188
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:input_action_end_dx4
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
In net/ipv4/ip_options.c (ffffffff819c478c)
Location: include/net/route.h:188
Inline: True
Inline callers:
  - net/ipv4/ip_options.c:ip_options_rcv_srr
```
```
In net/ipv4/icmp.c (ffffffff81a02a3f)
Location: include/net/route.h:188
Inline: True
```
```
In net/ipv6/seg6_local.c (ffffffff81a9bba9)
Location: include/net/route.h:188
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:input_action_end_dx4
```
</details>
</li>
</ul>

## Differences
