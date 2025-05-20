# Function: <code>ipv6_addr_prefix</code>

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
In net/ipv6/addrconf.c (ffffffff817c990f)
Location: include/net/ipv6.h:390
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_join_anycast
  - net/ipv6/addrconf.c:addrconf_leave_anycast
```
```
In net/ipv6/addrlabel.c (ffffffff817d28cb)
Location: include/net/ipv6.h:390
Inline: True
Inline callers:
  - net/ipv6/addrlabel.c:ip6addrlbl_add
  - net/ipv6/addrlabel.c:ip6addrlbl_newdel
```
```
In net/ipv6/route.c (ffffffff817d60c4)
Location: include/net/ipv6.h:390
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_route_info_create
  - net/ipv6/route.c:ip6_route_info_create
  - net/ipv6/route.c:rt6_route_rcv
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
In net/ipv6/addrconf.c (ffffffff81836c8f)
Location: include/net/ipv6.h:407
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_leave_anycast
  - net/ipv6/addrconf.c:addrconf_join_anycast
```
```
In net/ipv6/addrlabel.c (ffffffff818406bf)
Location: include/net/ipv6.h:407
Inline: True
Inline callers:
  - net/ipv6/addrlabel.c:ip6addrlbl_newdel
  - net/ipv6/addrlabel.c:ip6addrlbl_add
```
```
In net/ipv6/route.c (ffffffff81844678)
Location: include/net/ipv6.h:407
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_route_info_create
  - net/ipv6/route.c:ip6_route_info_create
  - net/ipv6/route.c:rt6_route_rcv
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
In net/ipv6/addrconf.c (ffffffff8186884f)
Location: include/net/ipv6.h:407
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_leave_anycast
  - net/ipv6/addrconf.c:addrconf_join_anycast
```
```
In net/ipv6/addrlabel.c (ffffffff8187233f)
Location: include/net/ipv6.h:407
Inline: True
Inline callers:
  - net/ipv6/addrlabel.c:ip6addrlbl_newdel
  - net/ipv6/addrlabel.c:ip6addrlbl_add
```
```
In net/ipv6/route.c (ffffffff818763f4)
Location: include/net/ipv6.h:407
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_route_info_create
  - net/ipv6/route.c:ip6_route_info_create
  - net/ipv6/route.c:rt6_route_rcv
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
In net/ipv6/addrconf.c (ffffffff8188cef2)
Location: include/net/ipv6.h:408
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_leave_anycast
  - net/ipv6/addrconf.c:addrconf_join_anycast
```
```
In net/ipv6/addrlabel.c (ffffffff818970a7)
Location: include/net/ipv6.h:408
Inline: True
Inline callers:
  - net/ipv6/addrlabel.c:ip6addrlbl_newdel
  - net/ipv6/addrlabel.c:ip6addrlbl_add
```
```
In net/ipv6/route.c (ffffffff8189bb0a)
Location: include/net/ipv6.h:408
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_route_info_create
  - net/ipv6/route.c:ip6_route_info_create
  - net/ipv6/route.c:rt6_route_rcv
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
In net/ipv6/addrconf.c (ffffffff8190fd12)
Location: include/net/ipv6.h:449
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_leave_anycast
  - net/ipv6/addrconf.c:addrconf_join_anycast
```
```
In net/ipv6/addrlabel.c (ffffffff819185e6)
Location: include/net/ipv6.h:449
Inline: True
Inline callers:
  - net/ipv6/addrlabel.c:ip6addrlbl_newdel
  - net/ipv6/addrlabel.c:ip6addrlbl_add
```
```
In net/ipv6/route.c (ffffffff8191e7b0)
Location: include/net/ipv6.h:449
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_route_info_create
  - net/ipv6/route.c:ip6_route_info_create
  - net/ipv6/route.c:rt6_route_rcv
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
In net/ipv6/addrconf.c (ffffffff819652ff)
Location: include/net/ipv6.h:437
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_leave_anycast
  - net/ipv6/addrconf.c:addrconf_join_anycast
```
```
In net/ipv6/addrlabel.c (ffffffff8196fe2c)
Location: include/net/ipv6.h:437
Inline: True
Inline callers:
  - net/ipv6/addrlabel.c:ip6addrlbl_newdel
  - net/ipv6/addrlabel.c:ip6addrlbl_add
```
```
In net/ipv6/route.c (ffffffff81976c27)
Location: include/net/ipv6.h:437
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_route_info_create
  - net/ipv6/route.c:ip6_route_info_create
  - net/ipv6/route.c:rt6_route_rcv
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
In net/ipv6/addrconf.c (ffffffff8199c2cf)
Location: include/net/ipv6.h:457
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_leave_anycast
  - net/ipv6/addrconf.c:addrconf_join_anycast
```
```
In net/ipv6/addrlabel.c (ffffffff819a5a4c)
Location: include/net/ipv6.h:457
Inline: True
Inline callers:
  - net/ipv6/addrlabel.c:ip6addrlbl_newdel
  - net/ipv6/addrlabel.c:ip6addrlbl_add
```
```
In net/ipv6/route.c (ffffffff819ac814)
Location: include/net/ipv6.h:457
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_route_info_create
  - net/ipv6/route.c:ip6_route_info_create
  - net/ipv6/route.c:rt6_route_rcv
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
In net/ipv6/addrconf.c (ffffffff81a066ff)
Location: include/net/ipv6.h:515
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_leave_anycast
  - net/ipv6/addrconf.c:addrconf_join_anycast
```
```
In net/ipv6/addrlabel.c (ffffffff81a11fc1)
Location: include/net/ipv6.h:515
Inline: True
Inline callers:
  - net/ipv6/addrlabel.c:ip6addrlbl_newdel
  - net/ipv6/addrlabel.c:ip6addrlbl_add
```
```
In net/ipv6/route.c (ffffffff81a1b0c7)
Location: include/net/ipv6.h:515
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_route_info_create
  - net/ipv6/route.c:ip6_route_info_create
  - net/ipv6/route.c:rt6_route_rcv
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
In net/ipv6/addrconf.c (ffffffff81a3d26f)
Location: include/net/ipv6.h:515
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_leave_anycast
  - net/ipv6/addrconf.c:addrconf_join_anycast
```
```
In net/ipv6/addrlabel.c (ffffffff81a48be1)
Location: include/net/ipv6.h:515
Inline: True
Inline callers:
  - net/ipv6/addrlabel.c:ip6addrlbl_newdel
  - net/ipv6/addrlabel.c:ip6addrlbl_add
```
```
In net/ipv6/route.c (ffffffff81a51d47)
Location: include/net/ipv6.h:515
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_route_info_create
  - net/ipv6/route.c:ip6_route_info_create
  - net/ipv6/route.c:rt6_route_rcv
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
In net/ipv6/addrconf.c (ffffffff81b32887)
Location: include/net/ipv6.h:515
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_leave_anycast
  - net/ipv6/addrconf.c:dev_forward_change
```
```
In net/ipv6/addrlabel.c (ffffffff81b3f603)
Location: include/net/ipv6.h:515
Inline: True
Inline callers:
  - net/ipv6/addrlabel.c:ip6addrlbl_del
  - net/ipv6/addrlabel.c:ip6addrlbl_add
```
```
In net/ipv6/route.c (ffffffff81b49417)
Location: include/net/ipv6.h:515
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_route_info_create
  - net/ipv6/route.c:ip6_route_info_create
  - net/ipv6/route.c:rt6_route_rcv
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
In net/ipv6/addrconf.c (ffffffff81b42fc7)
Location: include/net/ipv6.h:515
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_leave_anycast
  - net/ipv6/addrconf.c:dev_forward_change
```
```
In net/ipv6/addrlabel.c (ffffffff81b4e0a3)
Location: include/net/ipv6.h:515
Inline: True
Inline callers:
  - net/ipv6/addrlabel.c:ip6addrlbl_del
  - net/ipv6/addrlabel.c:ip6addrlbl_add
```
```
In net/ipv6/route.c (ffffffff81b5802a)
Location: include/net/ipv6.h:515
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_route_info_create
  - net/ipv6/route.c:ip6_route_info_create
  - net/ipv6/route.c:rt6_route_rcv
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
In net/ipv6/addrconf.c (ffffffff81b2f1c2)
Location: include/net/ipv6.h:516
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_leave_anycast
  - net/ipv6/addrconf.c:addrconf_join_anycast
```
```
In net/ipv6/addrlabel.c (ffffffff81b3c053)
Location: include/net/ipv6.h:516
Inline: True
Inline callers:
  - net/ipv6/addrlabel.c:ip6addrlbl_newdel
  - net/ipv6/addrlabel.c:ip6addrlbl_add
```
```
In net/ipv6/route.c (ffffffff81b45cc4)
Location: include/net/ipv6.h:516
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_route_info_create
  - net/ipv6/route.c:ip6_route_info_create
  - net/ipv6/route.c:rt6_route_rcv
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
In net/ipv6/addrconf.c (ffffffff81bf54f2)
Location: include/net/ipv6.h:519
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_leave_anycast
  - net/ipv6/addrconf.c:addrconf_join_anycast
```
```
In net/ipv6/addrlabel.c (ffffffff81c02943)
Location: include/net/ipv6.h:519
Inline: True
Inline callers:
  - net/ipv6/addrlabel.c:ip6addrlbl_newdel
  - net/ipv6/addrlabel.c:ip6addrlbl_add
```
```
In net/ipv6/route.c (ffffffff81c0ce1f)
Location: include/net/ipv6.h:519
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_route_info_create
  - net/ipv6/route.c:ip6_route_info_create
  - net/ipv6/route.c:rt6_route_rcv
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
In net/ipv6/addrconf.c (ffffffff81d91613)
Location: include/net/ipv6.h:573
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:__ipv6_ifa_notify
  - net/ipv6/addrconf.c:addrconf_leave_anycast
  - net/ipv6/addrconf.c:dev_forward_change
```
```
In net/ipv6/addrlabel.c (ffffffff81d9c570)
Location: include/net/ipv6.h:573
Inline: True
Inline callers:
  - net/ipv6/addrlabel.c:ip6addrlbl_newdel
  - net/ipv6/addrlabel.c:ip6addrlbl_alloc
```
```
In net/ipv6/route.c (ffffffff81da7e9d)
Location: include/net/ipv6.h:573
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_route_info_create
  - net/ipv6/route.c:ip6_route_info_create
  - net/ipv6/route.c:rt6_route_rcv
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
In net/ipv6/addrconf.c (ffffffff81f5c8c6)
Location: include/net/ipv6.h:606
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_leave_anycast
  - net/ipv6/addrconf.c:dev_forward_change
```
```
In net/ipv6/addrlabel.c (ffffffff81f6b260)
Location: include/net/ipv6.h:606
Inline: True
Inline callers:
  - net/ipv6/addrlabel.c:ip6addrlbl_newdel
  - net/ipv6/addrlabel.c:ip6addrlbl_alloc
```
```
In net/ipv6/route.c (ffffffff81f774ed)
Location: include/net/ipv6.h:606
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_route_info_create
  - net/ipv6/route.c:ip6_route_info_create
  - net/ipv6/route.c:rt6_route_rcv
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
In net/ipv6/addrconf.c (ffffffff81fbfa91)
Location: include/net/ipv6.h:607
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:__ipv6_ifa_notify
  - net/ipv6/addrconf.c:dev_forward_change
  - net/ipv6/addrconf.c:dev_forward_change
```
```
In net/ipv6/addrlabel.c (ffffffff81fcb3fd)
Location: include/net/ipv6.h:607
Inline: True
Inline callers:
  - net/ipv6/addrlabel.c:ip6addrlbl_newdel
  - net/ipv6/addrlabel.c:ip6addrlbl_alloc
```
```
In net/ipv6/route.c (ffffffff81fd748a)
Location: include/net/ipv6.h:607
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_route_info_create
  - net/ipv6/route.c:ip6_route_info_create
  - net/ipv6/route.c:rt6_route_rcv
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
In net/ipv4/tcp_ao.c (ffffffff8205566e)
Location: include/net/ipv6.h:607
Inline: True
Inline callers:
  - net/ipv4/tcp_ao.c:tcp_ao_copy_mkts_to_user
  - net/ipv4/tcp_ao.c:tcp_ao_verify_ipv6
```
```
In net/ipv6/addrconf.c (ffffffff8208cf31)
Location: include/net/ipv6.h:607
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:__ipv6_ifa_notify
  - net/ipv6/addrconf.c:dev_forward_change
  - net/ipv6/addrconf.c:dev_forward_change
```
```
In net/ipv6/addrlabel.c (ffffffff82098bdd)
Location: include/net/ipv6.h:607
Inline: True
Inline callers:
  - net/ipv6/addrlabel.c:ip6addrlbl_newdel
  - net/ipv6/addrlabel.c:ip6addrlbl_alloc
```
```
In net/ipv6/route.c (ffffffff820a4e0a)
Location: include/net/ipv6.h:607
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_route_info_create
  - net/ipv6/route.c:ip6_route_info_create
  - net/ipv6/route.c:rt6_route_rcv
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
In net/ipv6/addrconf.c (ffff800010cfe494)
Location: include/net/ipv6.h:515
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_leave_anycast
  - net/ipv6/addrconf.c:addrconf_join_anycast
```
```
In net/ipv6/addrlabel.c (ffff800010d0c00c)
Location: include/net/ipv6.h:515
Inline: True
Inline callers:
  - net/ipv6/addrlabel.c:ip6addrlbl_newdel
  - net/ipv6/addrlabel.c:ip6addrlbl_add
```
```
In net/ipv6/route.c (ffff800010d15c78)
Location: include/net/ipv6.h:515
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_route_info_create
  - net/ipv6/route.c:ip6_route_info_create
  - net/ipv6/route.c:rt6_route_rcv
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
In net/ipv6/addrconf.c (c0e067ac)
Location: include/net/ipv6.h:515
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_leave_anycast
  - net/ipv6/addrconf.c:addrconf_join_anycast
```
```
In net/ipv6/addrlabel.c (c0e11dc0)
Location: include/net/ipv6.h:515
Inline: True
Inline callers:
  - net/ipv6/addrlabel.c:ip6addrlbl_newdel
  - net/ipv6/addrlabel.c:ip6addrlbl_add
```
```
In net/ipv6/route.c (c0e1b9b8)
Location: include/net/ipv6.h:515
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_route_info_create
  - net/ipv6/route.c:ip6_route_info_create
  - net/ipv6/route.c:rt6_route_rcv
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
In net/ipv6/addrconf.c (c000000000e26fb0)
Location: include/net/ipv6.h:515
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_leave_anycast
  - net/ipv6/addrconf.c:addrconf_join_anycast
```
```
In net/ipv6/addrlabel.c (c000000000e36958)
Location: include/net/ipv6.h:515
Inline: True
Inline callers:
  - net/ipv6/addrlabel.c:ip6addrlbl_newdel
  - net/ipv6/addrlabel.c:ip6addrlbl_add
```
```
In net/ipv6/route.c (c000000000e42fdc)
Location: include/net/ipv6.h:515
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_route_info_create
  - net/ipv6/route.c:ip6_route_info_create
  - net/ipv6/route.c:rt6_route_rcv
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
In net/ipv6/addrconf.c (ffffffe000848e56)
Location: include/net/ipv6.h:515
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_leave_anycast
  - net/ipv6/addrconf.c:addrconf_join_anycast
```
```
In net/ipv6/addrlabel.c (ffffffe000852f02)
Location: include/net/ipv6.h:515
Inline: True
Inline callers:
  - net/ipv6/addrlabel.c:ip6addrlbl_newdel
  - net/ipv6/addrlabel.c:ip6addrlbl_add
```
```
In net/ipv6/route.c (ffffffe00085b250)
Location: include/net/ipv6.h:515
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_route_info_create
  - net/ipv6/route.c:ip6_route_info_create
  - net/ipv6/route.c:rt6_route_rcv
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
In net/ipv6/addrconf.c (ffffffff819dc8ff)
Location: include/net/ipv6.h:515
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_leave_anycast
  - net/ipv6/addrconf.c:addrconf_join_anycast
```
```
In net/ipv6/addrlabel.c (ffffffff819e8271)
Location: include/net/ipv6.h:515
Inline: True
Inline callers:
  - net/ipv6/addrlabel.c:ip6addrlbl_newdel
  - net/ipv6/addrlabel.c:ip6addrlbl_add
```
```
In net/ipv6/route.c (ffffffff819f13d7)
Location: include/net/ipv6.h:515
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_route_info_create
  - net/ipv6/route.c:ip6_route_info_create
  - net/ipv6/route.c:rt6_route_rcv
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
In net/ipv6/addrconf.c (ffffffff819996bf)
Location: include/net/ipv6.h:515
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_leave_anycast
  - net/ipv6/addrconf.c:addrconf_join_anycast
```
```
In net/ipv6/addrlabel.c (ffffffff819a5031)
Location: include/net/ipv6.h:515
Inline: True
Inline callers:
  - net/ipv6/addrlabel.c:ip6addrlbl_newdel
  - net/ipv6/addrlabel.c:ip6addrlbl_add
```
```
In net/ipv6/route.c (ffffffff819ae197)
Location: include/net/ipv6.h:515
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_route_info_create
  - net/ipv6/route.c:ip6_route_info_create
  - net/ipv6/route.c:rt6_route_rcv
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
In net/ipv6/addrconf.c (ffffffff81a4737f)
Location: include/net/ipv6.h:515
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_leave_anycast
  - net/ipv6/addrconf.c:addrconf_join_anycast
```
```
In net/ipv6/addrlabel.c (ffffffff81a52cf1)
Location: include/net/ipv6.h:515
Inline: True
Inline callers:
  - net/ipv6/addrlabel.c:ip6addrlbl_newdel
  - net/ipv6/addrlabel.c:ip6addrlbl_add
```
```
In net/ipv6/route.c (ffffffff81a5be57)
Location: include/net/ipv6.h:515
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_route_info_create
  - net/ipv6/route.c:ip6_route_info_create
  - net/ipv6/route.c:rt6_route_rcv
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
In net/ipv6/addrconf.c (ffffffff81a5312f)
Location: include/net/ipv6.h:515
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_leave_anycast
  - net/ipv6/addrconf.c:addrconf_join_anycast
```
```
In net/ipv6/addrlabel.c (ffffffff81a5ec6d)
Location: include/net/ipv6.h:515
Inline: True
Inline callers:
  - net/ipv6/addrlabel.c:ip6addrlbl_newdel
  - net/ipv6/addrlabel.c:ip6addrlbl_add
```
```
In net/ipv6/route.c (ffffffff81a681c7)
Location: include/net/ipv6.h:515
Inline: True
Inline callers:
  - net/ipv6/route.c:ip6_route_info_create
  - net/ipv6/route.c:ip6_route_info_create
  - net/ipv6/route.c:rt6_route_rcv
```
</details>
</li>
</ul>

## Differences
