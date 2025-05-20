# Function: <code>l3mdev_fib_table</code>

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
In net/ipv4/fib_frontend.c (ffffffff8179a46f)
Location: include/net/l3mdev.h:76
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:inet_addr_type_dev_table
  - net/ipv4/fib_frontend.c:inet_dev_addr_type
```
```
In net/ipv6/addrconf.c (ffffffff817c9a1c)
Location: include/net/l3mdev.h:76
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_prefix_route
  - net/ipv6/addrconf.c:addrconf_add_mroute
  - net/ipv6/addrconf.c:addrconf_get_prefix_route
```
```
In net/ipv6/route.c (ffffffff817d81ad)
Location: include/net/l3mdev.h:76
Inline: True
Inline callers:
  - net/ipv6/route.c:rt6_add_dflt_router
  - net/ipv6/route.c:addrconf_dst_alloc
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
In net/ipv4/fib_frontend.c (ffffffff81808f88)
Location: include/net/l3mdev.h:129
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:ip_rt_ioctl
  - net/ipv4/fib_frontend.c:inet_addr_type_dev_table
  - net/ipv4/fib_frontend.c:inet_dev_addr_type
```
```
In net/ipv4/fib_semantics.c (ffffffff8180b9f8)
Location: include/net/l3mdev.h:129
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_sync_down_addr
```
```
In net/ipv6/addrconf.c (ffffffff81836bb7)
Location: include/net/l3mdev.h:129
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_add_mroute
  - net/ipv6/addrconf.c:addrconf_get_prefix_route
  - net/ipv6/addrconf.c:addrconf_prefix_route
```
```
In net/ipv6/route.c (ffffffff81846d7b)
Location: include/net/l3mdev.h:129
Inline: True
Inline callers:
  - net/ipv6/route.c:addrconf_dst_alloc
  - net/ipv6/route.c:rt6_add_dflt_router
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
In net/ipv4/fib_frontend.c (ffffffff8183a07d)
Location: include/net/l3mdev.h:106
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:ip_rt_ioctl
  - net/ipv4/fib_frontend.c:inet_addr_type_dev_table
  - net/ipv4/fib_frontend.c:inet_dev_addr_type
```
```
In net/ipv4/fib_semantics.c (ffffffff8183cb18)
Location: include/net/l3mdev.h:106
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_sync_down_addr
```
```
In net/ipv6/addrconf.c (ffffffff81868777)
Location: include/net/l3mdev.h:106
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_add_mroute
  - net/ipv6/addrconf.c:addrconf_get_prefix_route
  - net/ipv6/addrconf.c:addrconf_prefix_route
```
```
In net/ipv6/route.c (ffffffff81878b67)
Location: include/net/l3mdev.h:106
Inline: True
Inline callers:
  - net/ipv6/route.c:addrconf_dst_alloc
  - net/ipv6/route.c:rt6_add_dflt_router
  - net/ipv6/route.c:rt6_get_dflt_router
  - net/ipv6/route.c:rt6_add_route_info
  - net/ipv6/route.c:rt6_get_route_info
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
In net/ipv4/fib_frontend.c (ffffffff8185b5e3)
Location: include/net/l3mdev.h:106
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:ip_rt_ioctl
  - net/ipv4/fib_frontend.c:inet_addr_type_dev_table
  - net/ipv4/fib_frontend.c:inet_dev_addr_type
```
```
In net/ipv4/fib_semantics.c (ffffffff8185e237)
Location: include/net/l3mdev.h:106
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_sync_down_addr
```
```
In net/ipv6/addrconf.c (ffffffff8188ce07)
Location: include/net/l3mdev.h:106
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_add_mroute
  - net/ipv6/addrconf.c:addrconf_get_prefix_route
  - net/ipv6/addrconf.c:addrconf_prefix_route
```
```
In net/ipv6/route.c (ffffffff8189de40)
Location: include/net/l3mdev.h:106
Inline: True
Inline callers:
  - net/ipv6/route.c:addrconf_dst_alloc
  - net/ipv6/route.c:rt6_add_dflt_router
  - net/ipv6/route.c:rt6_get_dflt_router
  - net/ipv6/route.c:rt6_add_route_info
  - net/ipv6/route.c:rt6_get_route_info
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
In net/ipv4/fib_frontend.c (ffffffff818db4d3)
Location: include/net/l3mdev.h:106
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:ip_rt_ioctl
  - net/ipv4/fib_frontend.c:inet_addr_type_dev_table
  - net/ipv4/fib_frontend.c:inet_dev_addr_type
```
```
In net/ipv4/fib_semantics.c (ffffffff818de277)
Location: include/net/l3mdev.h:106
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_sync_down_addr
```
```
In net/ipv6/addrconf.c (ffffffff8190e197)
Location: include/net/l3mdev.h:106
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_add_mroute
  - net/ipv6/addrconf.c:addrconf_get_prefix_route
  - net/ipv6/addrconf.c:addrconf_prefix_route
```
```
In net/ipv6/route.c (ffffffff81920483)
Location: include/net/l3mdev.h:106
Inline: True
Inline callers:
  - net/ipv6/route.c:addrconf_dst_alloc
  - net/ipv6/route.c:rt6_add_dflt_router
  - net/ipv6/route.c:rt6_get_dflt_router
  - net/ipv6/route.c:rt6_add_route_info
  - net/ipv6/route.c:rt6_get_route_info
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
In net/ipv4/fib_frontend.c (ffffffff8193201c)
Location: include/net/l3mdev.h:106
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:ip_rt_ioctl
  - net/ipv4/fib_frontend.c:inet_addr_type_dev_table
  - net/ipv4/fib_frontend.c:inet_dev_addr_type
```
```
In net/ipv4/fib_semantics.c (ffffffff81934de8)
Location: include/net/l3mdev.h:106
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_sync_down_addr
```
```
In net/ipv6/addrconf.c (ffffffff81965217)
Location: include/net/l3mdev.h:106
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_add_mroute
  - net/ipv6/addrconf.c:addrconf_get_prefix_route
```
```
In net/ipv6/route.c (ffffffff819786b4)
Location: include/net/l3mdev.h:106
Inline: True
Inline callers:
  - net/ipv6/route.c:addrconf_f6i_alloc
  - net/ipv6/route.c:rt6_add_dflt_router
  - net/ipv6/route.c:rt6_get_dflt_router
  - net/ipv6/route.c:rt6_add_route_info
  - net/ipv6/route.c:rt6_get_route_info
  - net/ipv6/route.c:ip6_route_info_create
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
In net/ipv4/fib_frontend.c (ffffffff8196187c)
Location: include/net/l3mdev.h:117
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:ip_rt_ioctl
  - net/ipv4/fib_frontend.c:inet_addr_type_dev_table
  - net/ipv4/fib_frontend.c:inet_dev_addr_type
```
```
In net/ipv4/fib_semantics.c (ffffffff81964738)
Location: include/net/l3mdev.h:117
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_sync_down_addr
```
```
In net/ipv6/addrconf.c (ffffffff8199a797)
Location: include/net/l3mdev.h:117
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_add_mroute
  - net/ipv6/addrconf.c:addrconf_get_prefix_route
```
```
In net/ipv6/route.c (ffffffff819ae2b5)
Location: include/net/l3mdev.h:117
Inline: True
Inline callers:
  - net/ipv6/route.c:addrconf_f6i_alloc
  - net/ipv6/route.c:rt6_add_dflt_router
  - net/ipv6/route.c:rt6_get_dflt_router
  - net/ipv6/route.c:rt6_add_route_info
  - net/ipv6/route.c:rt6_get_route_info
  - net/ipv6/route.c:ip6_route_info_create
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
In net/ipv4/fib_frontend.c (ffffffff819c600f)
Location: include/net/l3mdev.h:113
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:ip_rt_ioctl
  - net/ipv4/fib_frontend.c:inet_addr_type_dev_table
  - net/ipv4/fib_frontend.c:inet_dev_addr_type
```
```
In net/ipv4/fib_semantics.c (ffffffff819ca3b4)
Location: include/net/l3mdev.h:113
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_sync_down_addr
```
```
In net/ipv4/nexthop.c (ffffffff819d3dad)
Location: include/net/l3mdev.h:113
Inline: True
```
```
In net/ipv6/addrconf.c (ffffffff81a06617)
Location: include/net/l3mdev.h:113
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_add_mroute
  - net/ipv6/addrconf.c:addrconf_get_prefix_route
```
```
In net/ipv6/route.c (ffffffff81a1c07f)
Location: include/net/l3mdev.h:113
Inline: True
Inline callers:
  - net/ipv6/route.c:addrconf_f6i_alloc
  - net/ipv6/route.c:rt6_add_dflt_router
  - net/ipv6/route.c:rt6_get_dflt_router
  - net/ipv6/route.c:rt6_add_route_info
  - net/ipv6/route.c:rt6_get_route_info
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
In net/ipv4/fib_frontend.c (ffffffff819fcbbf)
Location: include/net/l3mdev.h:113
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:ip_rt_ioctl
  - net/ipv4/fib_frontend.c:inet_addr_type_dev_table
  - net/ipv4/fib_frontend.c:inet_dev_addr_type
```
```
In net/ipv4/fib_semantics.c (ffffffff81a00f7b)
Location: include/net/l3mdev.h:113
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_sync_down_addr
```
```
In net/ipv4/nexthop.c (ffffffff81a0a91d)
Location: include/net/l3mdev.h:113
Inline: True
```
```
In net/ipv6/addrconf.c (ffffffff81a3d187)
Location: include/net/l3mdev.h:113
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_add_mroute
  - net/ipv6/addrconf.c:addrconf_get_prefix_route
```
```
In net/ipv6/route.c (ffffffff81a52cff)
Location: include/net/l3mdev.h:113
Inline: True
Inline callers:
  - net/ipv6/route.c:addrconf_f6i_alloc
  - net/ipv6/route.c:rt6_add_dflt_router
  - net/ipv6/route.c:rt6_get_dflt_router
  - net/ipv6/route.c:rt6_add_route_info
  - net/ipv6/route.c:rt6_get_route_info
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
In net/ipv4/fib_frontend.c (ffffffff81aec623)
Location: include/net/l3mdev.h:113
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:fib_del_ifaddr
  - net/ipv4/fib_frontend.c:fib_magic
  - net/ipv4/fib_frontend.c:rtentry_to_fib_config
  - net/ipv4/fib_frontend.c:inet_dev_addr_type
```
```
In net/ipv4/fib_semantics.c (ffffffff81aefffb)
Location: include/net/l3mdev.h:113
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_sync_down_addr
```
```
In net/ipv4/nexthop.c (ffffffff81afabf4)
Location: include/net/l3mdev.h:113
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:nh_create_ipv6
  - net/ipv4/nexthop.c:nh_create_ipv4
```
```
In net/ipv6/addrconf.c (ffffffff81b327a7)
Location: include/net/l3mdev.h:113
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_add_mroute
  - net/ipv6/addrconf.c:addrconf_get_prefix_route
  - net/ipv6/addrconf.c:addrconf_prefix_route
```
```
In net/ipv6/route.c (ffffffff81b4a36f)
Location: include/net/l3mdev.h:113
Inline: True
Inline callers:
  - net/ipv6/route.c:addrconf_f6i_alloc
  - net/ipv6/route.c:rt6_add_dflt_router
  - net/ipv6/route.c:rt6_get_dflt_router
  - net/ipv6/route.c:rt6_add_route_info
  - net/ipv6/route.c:rt6_get_route_info
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
In net/ipv4/fib_frontend.c (ffffffff81af9530)
Location: include/net/l3mdev.h:132
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:fib_del_ifaddr
  - net/ipv4/fib_frontend.c:fib_magic
  - net/ipv4/fib_frontend.c:rtentry_to_fib_config
  - net/ipv4/fib_frontend.c:inet_dev_addr_type
```
```
In net/ipv4/fib_semantics.c (ffffffff81afcf45)
Location: include/net/l3mdev.h:132
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_sync_down_addr
```
```
In net/ipv4/nexthop.c (ffffffff81b092e6)
Location: include/net/l3mdev.h:132
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:nh_create_ipv6
  - net/ipv4/nexthop.c:nh_create_ipv4
```
```
In net/ipv6/addrconf.c (ffffffff81b42649)
Location: include/net/l3mdev.h:132
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_add_mroute
  - net/ipv6/addrconf.c:addrconf_get_prefix_route
  - net/ipv6/addrconf.c:addrconf_prefix_route
```
```
In net/ipv6/route.c (ffffffff81b58fe0)
Location: include/net/l3mdev.h:132
Inline: True
Inline callers:
  - net/ipv6/route.c:addrconf_f6i_alloc
  - net/ipv6/route.c:rt6_add_dflt_router
  - net/ipv6/route.c:rt6_get_dflt_router
  - net/ipv6/route.c:rt6_add_route_info
  - net/ipv6/route.c:rt6_get_route_info
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
In net/ipv4/fib_frontend.c (ffffffff81ae4cf0)
Location: include/net/l3mdev.h:132
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:fib_del_ifaddr
  - net/ipv4/fib_frontend.c:fib_magic
  - net/ipv4/fib_frontend.c:rtentry_to_fib_config
  - net/ipv4/fib_frontend.c:inet_dev_addr_type
```
```
In net/ipv4/fib_semantics.c (ffffffff81ae8765)
Location: include/net/l3mdev.h:132
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_sync_down_addr
```
```
In net/ipv4/nexthop.c (ffffffff81af46f6)
Location: include/net/l3mdev.h:132
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:nh_create_ipv6
  - net/ipv4/nexthop.c:nh_create_ipv4
```
```
In net/ipv6/addrconf.c (ffffffff81b30599)
Location: include/net/l3mdev.h:132
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_add_mroute
  - net/ipv6/addrconf.c:addrconf_get_prefix_route
  - net/ipv6/addrconf.c:addrconf_prefix_route
```
```
In net/ipv6/route.c (ffffffff81b46ee1)
Location: include/net/l3mdev.h:132
Inline: True
Inline callers:
  - net/ipv6/route.c:addrconf_f6i_alloc
  - net/ipv6/route.c:rt6_add_dflt_router
  - net/ipv6/route.c:rt6_get_dflt_router
  - net/ipv6/route.c:rt6_add_route_info
  - net/ipv6/route.c:rt6_get_route_info
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
In net/ipv4/fib_frontend.c (ffffffff81ba4620)
Location: include/net/l3mdev.h:132
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:fib_del_ifaddr
  - net/ipv4/fib_frontend.c:fib_magic
  - net/ipv4/fib_frontend.c:rtentry_to_fib_config
  - net/ipv4/fib_frontend.c:inet_dev_addr_type
```
```
In net/ipv4/fib_semantics.c (ffffffff81ba8715)
Location: include/net/l3mdev.h:132
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_sync_down_addr
```
```
In net/ipv4/nexthop.c (ffffffff81bb4ef6)
Location: include/net/l3mdev.h:132
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:nh_create_ipv6
  - net/ipv4/nexthop.c:nh_create_ipv4
```
```
In net/ipv6/addrconf.c (ffffffff81bf6a69)
Location: include/net/l3mdev.h:132
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_add_mroute
  - net/ipv6/addrconf.c:addrconf_get_prefix_route
  - net/ipv6/addrconf.c:addrconf_prefix_route
```
```
In net/ipv6/route.c (ffffffff81c0e131)
Location: include/net/l3mdev.h:132
Inline: True
Inline callers:
  - net/ipv6/route.c:addrconf_f6i_alloc
  - net/ipv6/route.c:rt6_add_dflt_router
  - net/ipv6/route.c:rt6_get_dflt_router
  - net/ipv6/route.c:rt6_add_route_info
  - net/ipv6/route.c:rt6_get_route_info
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
In net/ipv4/fib_frontend.c (ffffffff81d36f7f)
Location: include/net/l3mdev.h:132
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:fib_del_ifaddr
  - net/ipv4/fib_frontend.c:fib_magic
  - net/ipv4/fib_frontend.c:rtentry_to_fib_config
  - net/ipv4/fib_frontend.c:inet_dev_addr_type
```
```
In net/ipv4/fib_semantics.c (ffffffff81d3b127)
Location: include/net/l3mdev.h:132
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_sync_down_addr
```
```
In net/ipv4/nexthop.c (ffffffff81d489a3)
Location: include/net/l3mdev.h:132
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:nh_create_ipv6
  - net/ipv4/nexthop.c:nh_create_ipv4
```
```
In net/ipv6/addrconf.c (ffffffff81d8fd29)
Location: include/net/l3mdev.h:132
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_add_mroute
  - net/ipv6/addrconf.c:addrconf_get_prefix_route
  - net/ipv6/addrconf.c:addrconf_prefix_route
```
```
In net/ipv6/route.c (ffffffff81da917e)
Location: include/net/l3mdev.h:132
Inline: True
Inline callers:
  - net/ipv6/route.c:addrconf_f6i_alloc
  - net/ipv6/route.c:rt6_add_dflt_router
  - net/ipv6/route.c:rt6_get_dflt_router
  - net/ipv6/route.c:rt6_add_route_info
  - net/ipv6/route.c:rt6_get_route_info
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
In net/ipv4/fib_frontend.c (ffffffff81eff642)
Location: include/net/l3mdev.h:132
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:fib_del_ifaddr
  - net/ipv4/fib_frontend.c:fib_magic
  - net/ipv4/fib_frontend.c:rtentry_to_fib_config
  - net/ipv4/fib_frontend.c:inet_dev_addr_type
```
```
In net/ipv4/fib_semantics.c (ffffffff81f03ab7)
Location: include/net/l3mdev.h:132
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_sync_down_addr
```
```
In net/ipv4/nexthop.c (ffffffff81f11f63)
Location: include/net/l3mdev.h:132
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:nh_create_ipv6
  - net/ipv4/nexthop.c:nh_create_ipv4
```
```
In net/ipv6/addrconf.c (ffffffff81f5dff9)
Location: include/net/l3mdev.h:132
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_add_mroute
  - net/ipv6/addrconf.c:addrconf_get_prefix_route
  - net/ipv6/addrconf.c:addrconf_prefix_route
```
```
In net/ipv6/route.c (ffffffff81f7889e)
Location: include/net/l3mdev.h:132
Inline: True
Inline callers:
  - net/ipv6/route.c:addrconf_f6i_alloc
  - net/ipv6/route.c:rt6_add_dflt_router
  - net/ipv6/route.c:rt6_get_dflt_router
  - net/ipv6/route.c:rt6_add_route_info
  - net/ipv6/route.c:rt6_get_route_info
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
In net/ipv4/fib_frontend.c (ffffffff81f5f0d9)
Location: include/net/l3mdev.h:132
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:fib_del_ifaddr
  - net/ipv4/fib_frontend.c:fib_magic
  - net/ipv4/fib_frontend.c:rtentry_to_fib_config
  - net/ipv4/fib_frontend.c:inet_dev_addr_type
```
```
In net/ipv4/fib_semantics.c (ffffffff81f63492)
Location: include/net/l3mdev.h:132
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_sync_down_addr
```
```
In net/ipv4/nexthop.c (ffffffff81f71c53)
Location: include/net/l3mdev.h:132
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:nh_create_ipv6
  - net/ipv4/nexthop.c:nh_create_ipv4
```
```
In net/ipv6/addrconf.c (ffffffff81fbdcf9)
Location: include/net/l3mdev.h:132
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_add_mroute
  - net/ipv6/addrconf.c:addrconf_get_prefix_route
  - net/ipv6/addrconf.c:addrconf_prefix_route
```
```
In net/ipv6/route.c (ffffffff81fd8a8e)
Location: include/net/l3mdev.h:132
Inline: True
Inline callers:
  - net/ipv6/route.c:addrconf_f6i_alloc
  - net/ipv6/route.c:rt6_add_dflt_router
  - net/ipv6/route.c:rt6_get_dflt_router
  - net/ipv6/route.c:rt6_add_route_info
  - net/ipv6/route.c:rt6_get_route_info
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
In net/ipv4/fib_frontend.c (ffffffff820256a9)
Location: include/net/l3mdev.h:132
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:fib_del_ifaddr
  - net/ipv4/fib_frontend.c:fib_magic
  - net/ipv4/fib_frontend.c:rtentry_to_fib_config
  - net/ipv4/fib_frontend.c:inet_dev_addr_type
```
```
In net/ipv4/fib_semantics.c (ffffffff82029a62)
Location: include/net/l3mdev.h:132
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_sync_down_addr
```
```
In net/ipv4/nexthop.c (ffffffff82038363)
Location: include/net/l3mdev.h:132
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:nh_create_ipv6
  - net/ipv4/nexthop.c:nh_create_ipv4
```
```
In net/ipv6/addrconf.c (ffffffff8208b149)
Location: include/net/l3mdev.h:132
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_add_mroute
  - net/ipv6/addrconf.c:addrconf_get_prefix_route
  - net/ipv6/addrconf.c:addrconf_prefix_route
```
```
In net/ipv6/route.c (ffffffff820a6413)
Location: include/net/l3mdev.h:132
Inline: True
Inline callers:
  - net/ipv6/route.c:addrconf_f6i_alloc
  - net/ipv6/route.c:rt6_add_dflt_router
  - net/ipv6/route.c:rt6_get_dflt_router
  - net/ipv6/route.c:rt6_add_route_info
  - net/ipv6/route.c:rt6_get_route_info
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
In net/ipv4/fib_frontend.c (ffff800010cb42f0)
Location: include/net/l3mdev.h:113
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:rtentry_to_fib_config
  - net/ipv4/fib_frontend.c:inet_addr_type_dev_table
  - net/ipv4/fib_frontend.c:inet_dev_addr_type
```
```
In net/ipv4/fib_semantics.c (ffff800010cb95bc)
Location: include/net/l3mdev.h:113
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_sync_down_addr
```
```
In net/ipv4/nexthop.c (ffff800010cc3ee4)
Location: include/net/l3mdev.h:113
Inline: True
```
```
In net/ipv6/addrconf.c (ffff800010cfe3c0)
Location: include/net/l3mdev.h:113
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_add_mroute
  - net/ipv6/addrconf.c:addrconf_get_prefix_route
```
```
In net/ipv6/route.c (ffff800010d16d28)
Location: include/net/l3mdev.h:113
Inline: True
Inline callers:
  - net/ipv6/route.c:addrconf_f6i_alloc
  - net/ipv6/route.c:rt6_add_dflt_router
  - net/ipv6/route.c:rt6_get_dflt_router
  - net/ipv6/route.c:rt6_add_route_info
  - net/ipv6/route.c:rt6_get_route_info
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
In net/ipv4/fib_frontend.c (c0dbeb5c)
Location: include/net/l3mdev.h:113
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:fib_magic
  - net/ipv4/fib_frontend.c:rtentry_to_fib_config
  - net/ipv4/fib_frontend.c:inet_addr_type_dev_table
  - net/ipv4/fib_frontend.c:inet_dev_addr_type
```
```
In net/ipv4/fib_semantics.c (c0dc4d54)
Location: include/net/l3mdev.h:113
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_sync_down_addr
```
```
In net/ipv4/nexthop.c (c0dcf710)
Location: include/net/l3mdev.h:113
Inline: True
Inline callers:
  - net/ipv4/nexthop.c:nexthop_create
  - net/ipv4/nexthop.c:nh_create_ipv6
```
```
In net/ipv6/addrconf.c (c0e066c4)
Location: include/net/l3mdev.h:113
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_add_mroute
  - net/ipv6/addrconf.c:addrconf_get_prefix_route
  - net/ipv6/addrconf.c:addrconf_prefix_route
```
```
In net/ipv6/route.c (c0e1c978)
Location: include/net/l3mdev.h:113
Inline: True
Inline callers:
  - net/ipv6/route.c:addrconf_f6i_alloc
  - net/ipv6/route.c:rt6_add_dflt_router
  - net/ipv6/route.c:rt6_get_dflt_router
  - net/ipv6/route.c:rt6_add_route_info
  - net/ipv6/route.c:rt6_get_route_info
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
In net/ipv4/fib_frontend.c (c000000000dcc3b4)
Location: include/net/l3mdev.h:113
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:ip_rt_ioctl
  - net/ipv4/fib_frontend.c:inet_addr_type_dev_table
  - net/ipv4/fib_frontend.c:inet_dev_addr_type
```
```
In net/ipv4/fib_semantics.c (c000000000dd23f4)
Location: include/net/l3mdev.h:113
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_sync_down_addr
```
```
In net/ipv4/nexthop.c (c000000000ddfd20)
Location: include/net/l3mdev.h:113
Inline: True
```
```
In net/ipv6/addrconf.c (c000000000e26eb4)
Location: include/net/l3mdev.h:113
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_add_mroute
  - net/ipv6/addrconf.c:addrconf_get_prefix_route
```
```
In net/ipv6/route.c (c000000000e44578)
Location: include/net/l3mdev.h:113
Inline: True
Inline callers:
  - net/ipv6/route.c:addrconf_f6i_alloc
  - net/ipv6/route.c:rt6_add_dflt_router
  - net/ipv6/route.c:rt6_get_dflt_router
  - net/ipv6/route.c:rt6_add_route_info
  - net/ipv6/route.c:rt6_get_route_info
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
In net/ipv4/fib_frontend.c (ffffffe00080bfe4)
Location: include/net/l3mdev.h:113
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:rtentry_to_fib_config
  - net/ipv4/fib_frontend.c:inet_addr_type_dev_table
  - net/ipv4/fib_frontend.c:inet_dev_addr_type
```
```
In net/ipv4/fib_semantics.c (ffffffe00081021e)
Location: include/net/l3mdev.h:113
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_sync_down_addr
```
```
In net/ipv4/nexthop.c (ffffffe000819570)
Location: include/net/l3mdev.h:113
Inline: True
```
```
In net/ipv6/addrconf.c (ffffffe000848db6)
Location: include/net/l3mdev.h:113
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_add_mroute
  - net/ipv6/addrconf.c:addrconf_get_prefix_route
  - net/ipv6/addrconf.c:addrconf_prefix_route
```
```
In net/ipv6/route.c (ffffffe00085bfde)
Location: include/net/l3mdev.h:113
Inline: True
Inline callers:
  - net/ipv6/route.c:addrconf_f6i_alloc
  - net/ipv6/route.c:rt6_add_dflt_router
  - net/ipv6/route.c:rt6_get_dflt_router
  - net/ipv6/route.c:rt6_add_route_info
  - net/ipv6/route.c:rt6_get_route_info
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
In net/ipv4/fib_frontend.c (ffffffff8199c95f)
Location: include/net/l3mdev.h:113
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:ip_rt_ioctl
  - net/ipv4/fib_frontend.c:inet_addr_type_dev_table
  - net/ipv4/fib_frontend.c:inet_dev_addr_type
```
```
In net/ipv4/fib_semantics.c (ffffffff819a0d1b)
Location: include/net/l3mdev.h:113
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_sync_down_addr
```
```
In net/ipv4/nexthop.c (ffffffff819aa6bd)
Location: include/net/l3mdev.h:113
Inline: True
```
```
In net/ipv6/addrconf.c (ffffffff819dc817)
Location: include/net/l3mdev.h:113
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_add_mroute
  - net/ipv6/addrconf.c:addrconf_get_prefix_route
```
```
In net/ipv6/route.c (ffffffff819f238f)
Location: include/net/l3mdev.h:113
Inline: True
Inline callers:
  - net/ipv6/route.c:addrconf_f6i_alloc
  - net/ipv6/route.c:rt6_add_dflt_router
  - net/ipv6/route.c:rt6_get_dflt_router
  - net/ipv6/route.c:rt6_add_route_info
  - net/ipv6/route.c:rt6_get_route_info
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
In net/ipv4/fib_frontend.c (ffffffff8195641f)
Location: include/net/l3mdev.h:113
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:ip_rt_ioctl
  - net/ipv4/fib_frontend.c:inet_addr_type_dev_table
  - net/ipv4/fib_frontend.c:inet_dev_addr_type
```
```
In net/ipv4/fib_semantics.c (ffffffff8195a7db)
Location: include/net/l3mdev.h:113
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_sync_down_addr
```
```
In net/ipv4/nexthop.c (ffffffff8196417d)
Location: include/net/l3mdev.h:113
Inline: True
```
```
In net/ipv6/addrconf.c (ffffffff819995d7)
Location: include/net/l3mdev.h:113
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_add_mroute
  - net/ipv6/addrconf.c:addrconf_get_prefix_route
```
```
In net/ipv6/route.c (ffffffff819af14f)
Location: include/net/l3mdev.h:113
Inline: True
Inline callers:
  - net/ipv6/route.c:addrconf_f6i_alloc
  - net/ipv6/route.c:rt6_add_dflt_router
  - net/ipv6/route.c:rt6_get_dflt_router
  - net/ipv6/route.c:rt6_add_route_info
  - net/ipv6/route.c:rt6_get_route_info
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
In net/ipv4/fib_frontend.c (ffffffff81a071ff)
Location: include/net/l3mdev.h:113
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:ip_rt_ioctl
  - net/ipv4/fib_frontend.c:inet_addr_type_dev_table
  - net/ipv4/fib_frontend.c:inet_dev_addr_type
```
```
In net/ipv4/fib_semantics.c (ffffffff81a0b5bb)
Location: include/net/l3mdev.h:113
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_sync_down_addr
```
```
In net/ipv4/nexthop.c (ffffffff81a14f5d)
Location: include/net/l3mdev.h:113
Inline: True
```
```
In net/ipv6/addrconf.c (ffffffff81a47297)
Location: include/net/l3mdev.h:113
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_add_mroute
  - net/ipv6/addrconf.c:addrconf_get_prefix_route
```
```
In net/ipv6/route.c (ffffffff81a5ce0f)
Location: include/net/l3mdev.h:113
Inline: True
Inline callers:
  - net/ipv6/route.c:addrconf_f6i_alloc
  - net/ipv6/route.c:rt6_add_dflt_router
  - net/ipv6/route.c:rt6_get_dflt_router
  - net/ipv6/route.c:rt6_add_route_info
  - net/ipv6/route.c:rt6_get_route_info
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
In net/ipv4/fib_frontend.c (ffffffff81a118d3)
Location: include/net/l3mdev.h:113
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:ip_rt_ioctl
  - net/ipv4/fib_frontend.c:inet_addr_type_dev_table
  - net/ipv4/fib_frontend.c:inet_dev_addr_type
```
```
In net/ipv4/fib_semantics.c (ffffffff81a15d9b)
Location: include/net/l3mdev.h:113
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_sync_down_addr
```
```
In net/ipv4/nexthop.c (ffffffff81a1f974)
Location: include/net/l3mdev.h:113
Inline: True
```
```
In net/ipv6/addrconf.c (ffffffff81a53039)
Location: include/net/l3mdev.h:113
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:addrconf_add_mroute
  - net/ipv6/addrconf.c:addrconf_get_prefix_route
```
```
In net/ipv6/route.c (ffffffff81a691dd)
Location: include/net/l3mdev.h:113
Inline: True
Inline callers:
  - net/ipv6/route.c:addrconf_f6i_alloc
  - net/ipv6/route.c:rt6_add_dflt_router
  - net/ipv6/route.c:rt6_get_dflt_router
  - net/ipv6/route.c:rt6_add_route_info
  - net/ipv6/route.c:rt6_get_route_info
```
</details>
</li>
</ul>

## Differences
