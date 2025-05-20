# Function: <code>nla_find</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct nlattr *nla_find(const struct nlattr *head, int len, int attrtype);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/nlattr.c (ffffffff81415590)
Location: lib/nlattr.c:222
Inline: False
Direct callers:
  - net/core/neighbour.c:neigh_delete
  - net/core/rtnetlink.c:rtnl_bridge_setlink
  - net/core/rtnetlink.c:rtnl_bridge_dellink
  - net/core/rtnetlink.c:rtnl_bridge_getlink
  - net/core/filter.c:__skb_get_nlattr_nest
  - net/core/filter.c:__skb_get_nlattr
  - net/ipv4/fib_semantics.c:fib_nh_match
  - net/ipv4/fib_semantics.c:fib_nh_match
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv6/route.c:ip6_route_multipath_del
  - net/ipv6/route.c:ip6_route_multipath_add
  - net/ipv6/route.c:ip6_route_multipath_add
  - net/ipv6/route.c:ip6_route_multipath_add
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std
```
**Symbols:**

```
ffffffff81415590-ffffffff814155db: nla_find (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct nlattr *nla_find(const struct nlattr *head, int len, int attrtype);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/nlattr.c (ffffffff8145d290)
Location: lib/nlattr.c:222
Inline: False
Direct callers:
  - net/core/neighbour.c:neigh_delete
  - net/core/rtnetlink.c:rtnl_bridge_dellink
  - net/core/rtnetlink.c:rtnl_bridge_setlink
  - net/core/rtnetlink.c:rtnl_bridge_getlink
  - net/core/filter.c:__skb_get_nlattr_nest
  - net/core/filter.c:__skb_get_nlattr
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_nh_match
  - net/ipv4/fib_semantics.c:fib_nh_match
  - net/ipv6/route.c:ip6_route_multipath_del
  - net/ipv6/route.c:ip6_route_multipath_add
  - net/ipv6/route.c:ip6_route_multipath_add
  - net/ipv6/route.c:ip6_route_multipath_add
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std
  - net/switchdev/switchdev.c:switchdev_port_bridge_dellink
  - net/switchdev/switchdev.c:switchdev_port_bridge_setlink
  - net/switchdev/switchdev.c:switchdev_port_bridge_setlink
```
**Symbols:**

```
ffffffff8145d290-ffffffff8145d2f1: nla_find (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct nlattr *nla_find(const struct nlattr *head, int len, int attrtype);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/nlattr.c (ffffffff8147bd80)
Location: lib/nlattr.c:222
Inline: False
Direct callers:
  - net/core/neighbour.c:neigh_delete
  - net/core/rtnetlink.c:rtnl_bridge_dellink
  - net/core/rtnetlink.c:rtnl_bridge_setlink
  - net/core/rtnetlink.c:rtnl_bridge_getlink
  - net/core/filter.c:__skb_get_nlattr_nest
  - net/core/filter.c:__skb_get_nlattr
  - net/core/lwtunnel.c:lwtunnel_valid_encap_type_attr
  - net/core/lwtunnel.c:lwtunnel_valid_encap_type_attr
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_nh_match
  - net/ipv4/fib_semantics.c:fib_nh_match
  - net/ipv6/route.c:ip6_route_multipath_del
  - net/ipv6/route.c:ip6_route_multipath_add
  - net/ipv6/route.c:ip6_route_multipath_add
  - net/ipv6/route.c:ip6_route_multipath_add
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std
  - net/switchdev/switchdev.c:switchdev_port_bridge_dellink
  - net/switchdev/switchdev.c:switchdev_port_bridge_setlink
  - net/switchdev/switchdev.c:switchdev_port_bridge_setlink
```
**Symbols:**

```
ffffffff8147bd80-ffffffff8147bddf: nla_find (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct nlattr *nla_find(const struct nlattr *head, int len, int attrtype);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/nlattr.c (ffffffff814850d0)
Location: lib/nlattr.c:230
Inline: False
Direct callers:
  - net/core/neighbour.c:neigh_delete
  - net/core/rtnetlink.c:rtnl_bridge_dellink
  - net/core/rtnetlink.c:rtnl_bridge_setlink
  - net/core/rtnetlink.c:rtnl_bridge_getlink
  - net/core/filter.c:__skb_get_nlattr_nest
  - net/core/filter.c:__skb_get_nlattr
  - net/core/lwtunnel.c:lwtunnel_valid_encap_type_attr
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_nh_match
  - net/ipv4/fib_semantics.c:fib_nh_match
  - net/ipv6/route.c:ip6_route_multipath_del
  - net/ipv6/route.c:ip6_route_multipath_add
  - net/ipv6/route.c:ip6_route_multipath_add
  - net/ipv6/route.c:ip6_route_multipath_add
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add
  - net/switchdev/switchdev.c:switchdev_port_bridge_dellink
  - net/switchdev/switchdev.c:switchdev_port_bridge_setlink
  - net/switchdev/switchdev.c:switchdev_port_bridge_setlink
```
**Symbols:**

```
ffffffff814850d0-ffffffff8148510c: nla_find (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct nlattr *nla_find(const struct nlattr *head, int len, int attrtype);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/nlattr.c (ffffffff814c1140)
Location: lib/nlattr.c:284
Inline: False
Direct callers:
  - net/core/neighbour.c:neigh_delete
  - net/core/rtnetlink.c:rtnl_bridge_dellink
  - net/core/rtnetlink.c:rtnl_bridge_setlink
  - net/core/rtnetlink.c:rtnl_bridge_getlink
  - net/core/filter.c:__skb_get_nlattr_nest
  - net/core/filter.c:__skb_get_nlattr
  - net/core/lwtunnel.c:lwtunnel_valid_encap_type_attr
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_nh_match
  - net/ipv4/fib_semantics.c:fib_nh_match
  - net/ipv6/route.c:ip6_route_multipath_del
  - net/ipv6/route.c:ip6_route_multipath_add
  - net/ipv6/route.c:ip6_route_multipath_add
  - net/ipv6/route.c:ip6_route_multipath_add
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add
```
**Symbols:**

```
ffffffff814c1140-ffffffff814c117c: nla_find (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
struct nlattr *nla_find(const struct nlattr *head, int len, int attrtype);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/nlattr.c (ffffffff814f2680)
Location: lib/nlattr.c:284
Inline: True
Direct callers:
  - net/core/neighbour.c:neigh_delete
  - net/core/rtnetlink.c:rtnl_bridge_dellink
  - net/core/rtnetlink.c:rtnl_bridge_setlink
  - net/core/rtnetlink.c:rtnl_bridge_getlink
  - net/core/filter.c:bpf_skb_get_nlattr_nest
  - net/core/filter.c:bpf_skb_get_nlattr
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_nh_match
  - net/ipv4/fib_semantics.c:fib_nh_match
  - net/ipv6/route.c:ip6_route_multipath_del
  - net/ipv6/route.c:ip6_route_multipath_add
  - net/ipv6/route.c:ip6_route_multipath_add
  - net/ipv6/route.c:ip6_route_multipath_add
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std
```
**Symbols:**

```
ffffffff814f2680-ffffffff814f26c3: nla_find (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
struct nlattr *nla_find(const struct nlattr *head, int len, int attrtype);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/nlattr.c (ffffffff815063a0)
Location: lib/nlattr.c:459
Inline: True
Direct callers:
  - net/core/neighbour.c:neigh_delete
  - net/core/rtnetlink.c:rtnl_bridge_dellink
  - net/core/rtnetlink.c:rtnl_bridge_setlink
  - net/core/filter.c:bpf_skb_get_nlattr_nest
  - net/core/filter.c:bpf_skb_get_nlattr
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_nh_match
  - net/ipv4/fib_semantics.c:fib_nh_match
  - net/ipv6/route.c:ip6_route_multipath_del
  - net/ipv6/route.c:ip6_route_multipath_add
  - net/ipv6/route.c:ip6_route_multipath_add
  - net/ipv6/route.c:ip6_route_multipath_add
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add
```
**Symbols:**

```
ffffffff815063a0-ffffffff815063e3: nla_find (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct nlattr *nla_find(const struct nlattr *head, int len, int attrtype);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/nlattr.c (ffffffff81534140)
Location: lib/nlattr.c:491
Inline: False
Direct callers:
  - net/core/neighbour.c:neigh_delete
  - net/core/rtnetlink.c:rtnl_bridge_dellink
  - net/core/rtnetlink.c:rtnl_bridge_setlink
  - net/core/filter.c:bpf_skb_get_nlattr_nest
  - net/core/filter.c:bpf_skb_get_nlattr
  - net/core/lwtunnel.c:lwtunnel_valid_encap_type_attr
  - net/ipv4/fib_semantics.c:fib_nh_match
  - net/ipv4/fib_semantics.c:fib_nh_match
  - net/ipv4/fib_semantics.c:fib_nh_match
  - net/ipv4/fib_semantics.c:fib_get_nhs
  - net/ipv4/fib_semantics.c:fib_get_nhs
  - net/ipv4/fib_semantics.c:fib_get_nhs
  - net/ipv4/fib_semantics.c:fib_get_nhs
  - net/ipv4/fib_semantics.c:fib_get_nhs
  - net/ipv6/route.c:ip6_route_multipath_del
  - net/ipv6/route.c:ip6_route_multipath_add
  - net/ipv6/route.c:ip6_route_multipath_add
  - net/ipv6/route.c:ip6_route_multipath_add
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std
```
**Symbols:**

```
ffffffff81534140-ffffffff81534174: nla_find (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct nlattr *nla_find(const struct nlattr *head, int len, int attrtype);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/nlattr.c (ffffffff81554f80)
Location: lib/nlattr.c:491
Inline: False
Direct callers:
  - net/core/neighbour.c:neigh_delete
  - net/core/rtnetlink.c:rtnl_bridge_dellink
  - net/core/rtnetlink.c:rtnl_bridge_setlink
  - net/core/filter.c:bpf_skb_get_nlattr_nest
  - net/core/filter.c:bpf_skb_get_nlattr
  - net/core/lwtunnel.c:lwtunnel_valid_encap_type_attr
  - net/ipv4/fib_semantics.c:fib_nh_match
  - net/ipv4/fib_semantics.c:fib_nh_match
  - net/ipv4/fib_semantics.c:fib_nh_match
  - net/ipv4/fib_semantics.c:fib_get_nhs
  - net/ipv4/fib_semantics.c:fib_get_nhs
  - net/ipv4/fib_semantics.c:fib_get_nhs
  - net/ipv4/fib_semantics.c:fib_get_nhs
  - net/ipv4/fib_semantics.c:fib_get_nhs
  - net/ipv6/route.c:ip6_route_multipath_del
  - net/ipv6/route.c:ip6_route_multipath_add
  - net/ipv6/route.c:ip6_route_multipath_add
  - net/ipv6/route.c:ip6_route_multipath_add
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std
```
**Symbols:**

```
ffffffff81554f80-ffffffff81554fb4: nla_find (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct nlattr *nla_find(const struct nlattr *head, int len, int attrtype);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/nlattr.c (ffffffff815de4c0)
Location: lib/nlattr.c:643
Inline: False
Direct callers:
  - net/core/neighbour.c:neigh_delete
  - net/core/rtnetlink.c:rtnl_bridge_dellink
  - net/core/rtnetlink.c:rtnl_bridge_setlink
  - net/core/filter.c:bpf_skb_get_nlattr_nest
  - net/core/filter.c:bpf_skb_get_nlattr
  - net/core/lwtunnel.c:lwtunnel_valid_encap_type_attr
  - net/ipv4/fib_semantics.c:fib_nh_match
  - net/ipv4/fib_semantics.c:fib_nh_match
  - net/ipv4/fib_semantics.c:fib_nh_match
  - net/ipv4/fib_semantics.c:fib_get_nhs
  - net/ipv4/fib_semantics.c:fib_get_nhs
  - net/ipv4/fib_semantics.c:fib_get_nhs
  - net/ipv4/fib_semantics.c:fib_get_nhs
  - net/ipv4/fib_semantics.c:fib_get_nhs
  - net/ipv6/route.c:ip6_route_multipath_del
  - net/ipv6/route.c:ip6_route_multipath_add
  - net/ipv6/route.c:ip6_route_multipath_add
  - net/ipv6/route.c:ip6_route_multipath_add
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std
```
**Symbols:**

```
ffffffff815de4c0-ffffffff815de4f4: nla_find (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct nlattr *nla_find(const struct nlattr *head, int len, int attrtype);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/nlattr.c (ffffffff815fbb40)
Location: lib/nlattr.c:698
Inline: False
Direct callers:
  - net/core/neighbour.c:neigh_delete
  - net/core/rtnetlink.c:rtnl_bridge_dellink
  - net/core/rtnetlink.c:rtnl_bridge_setlink
  - net/core/filter.c:bpf_skb_get_nlattr_nest
  - net/core/filter.c:bpf_skb_get_nlattr
  - net/core/lwtunnel.c:lwtunnel_valid_encap_type_attr
  - net/ipv4/fib_semantics.c:fib_nh_match
  - net/ipv4/fib_semantics.c:fib_nh_match
  - net/ipv4/fib_semantics.c:fib_nh_match
  - net/ipv4/fib_semantics.c:fib_get_nhs
  - net/ipv4/fib_semantics.c:fib_get_nhs
  - net/ipv4/fib_semantics.c:fib_get_nhs
  - net/ipv4/fib_semantics.c:fib_get_nhs
  - net/ipv4/fib_semantics.c:fib_get_nhs
  - net/ipv6/route.c:ip6_route_multipath_del
  - net/ipv6/route.c:ip6_route_multipath_add
  - net/ipv6/route.c:ip6_route_multipath_add
  - net/ipv6/route.c:ip6_route_multipath_add
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std
```
**Symbols:**

```
ffffffff815fbb40-ffffffff815fbb74: nla_find (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct nlattr *nla_find(const struct nlattr *head, int len, int attrtype);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/nlattr.c (ffffffff815de790)
Location: lib/nlattr.c:698
Inline: False
Direct callers:
  - net/core/neighbour.c:neigh_delete
  - net/core/rtnetlink.c:rtnl_bridge_dellink
  - net/core/rtnetlink.c:rtnl_bridge_setlink
  - net/core/filter.c:bpf_skb_get_nlattr_nest
  - net/core/filter.c:bpf_skb_get_nlattr
  - net/core/lwtunnel.c:lwtunnel_valid_encap_type_attr
  - net/ipv4/fib_semantics.c:fib_nh_match
  - net/ipv4/fib_semantics.c:fib_nh_match
  - net/ipv4/fib_semantics.c:fib_nh_match
  - net/ipv4/fib_semantics.c:fib_get_nhs
  - net/ipv4/fib_semantics.c:fib_get_nhs
  - net/ipv4/fib_semantics.c:fib_get_nhs
  - net/ipv4/fib_semantics.c:fib_get_nhs
  - net/ipv4/fib_semantics.c:fib_get_nhs
  - net/ipv6/route.c:ip6_route_multipath_del
  - net/ipv6/route.c:ip6_route_multipath_add
  - net/ipv6/route.c:ip6_route_multipath_add
  - net/ipv6/route.c:ip6_route_multipath_add
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std
```
**Symbols:**

```
ffffffff815de790-ffffffff815de7c4: nla_find (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct nlattr *nla_find(const struct nlattr *head, int len, int attrtype);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/nlattr.c (ffffffff8164a310)
Location: lib/nlattr.c:698
Inline: False
Direct callers:
  - net/core/neighbour.c:neigh_delete
  - net/core/rtnetlink.c:rtnl_bridge_dellink
  - net/core/rtnetlink.c:rtnl_bridge_setlink
  - net/core/filter.c:bpf_skb_get_nlattr_nest
  - net/core/filter.c:bpf_skb_get_nlattr
  - net/core/lwtunnel.c:lwtunnel_valid_encap_type_attr
  - net/ipv4/fib_semantics.c:fib_nh_match
  - net/ipv4/fib_semantics.c:fib_nh_match
  - net/ipv4/fib_semantics.c:fib_nh_match
  - net/ipv4/fib_semantics.c:fib_get_nhs
  - net/ipv4/fib_semantics.c:fib_get_nhs
  - net/ipv4/fib_semantics.c:fib_get_nhs
  - net/ipv4/fib_semantics.c:fib_get_nhs
  - net/ipv4/fib_semantics.c:fib_get_nhs
  - net/ipv6/route.c:ip6_route_multipath_del
  - net/ipv6/route.c:ip6_route_multipath_add
  - net/ipv6/route.c:ip6_route_multipath_add
  - net/ipv6/route.c:ip6_route_multipath_add
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std
```
**Symbols:**

```
ffffffff8164a310-ffffffff8164a344: nla_find (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct nlattr *nla_find(const struct nlattr *head, int len, int attrtype);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/nlattr.c (ffffffff81760a60)
Location: lib/nlattr.c:698
Inline: False
Direct callers:
  - net/core/neighbour.c:neigh_delete
  - net/core/rtnetlink.c:rtnl_bridge_dellink
  - net/core/rtnetlink.c:rtnl_bridge_setlink
  - net/core/filter.c:bpf_skb_get_nlattr_nest
  - net/core/filter.c:bpf_skb_get_nlattr
  - net/core/lwtunnel.c:lwtunnel_valid_encap_type_attr
  - net/ipv4/fib_semantics.c:fib_nh_match
  - net/ipv4/fib_semantics.c:fib_nh_match
  - net/ipv4/fib_semantics.c:fib_nh_match
  - net/ipv4/fib_semantics.c:fib_get_nhs
  - net/ipv4/fib_semantics.c:fib_get_nhs
  - net/ipv4/fib_semantics.c:fib_get_nhs
  - net/ipv4/fib_semantics.c:fib_get_nhs
  - net/ipv4/fib_semantics.c:fib_get_nhs
  - net/ipv6/route.c:ip6_route_multipath_del
  - net/ipv6/route.c:ip6_route_multipath_add
  - net/ipv6/route.c:ip6_route_multipath_add
  - net/ipv6/route.c:ip6_route_multipath_add
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std
```
**Symbols:**

```
ffffffff81760a60-ffffffff81760aae: nla_find (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct nlattr *nla_find(const struct nlattr *head, int len, int attrtype);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/nlattr.c (ffffffff8188f590)
Location: lib/nlattr.c:713
Inline: False
Direct callers:
  - net/core/neighbour.c:neigh_delete
  - net/core/rtnetlink.c:rtnl_bridge_dellink
  - net/core/rtnetlink.c:rtnl_bridge_setlink
  - net/core/filter.c:bpf_skb_get_nlattr_nest
  - net/core/filter.c:bpf_skb_get_nlattr
  - net/core/lwtunnel.c:lwtunnel_valid_encap_type_attr
  - net/ipv4/fib_semantics.c:fib_nh_match
  - net/ipv4/fib_semantics.c:fib_nh_match
  - net/ipv4/fib_semantics.c:fib_nh_match
  - net/ipv4/fib_semantics.c:fib_get_nhs
  - net/ipv4/fib_semantics.c:fib_get_nhs
  - net/ipv4/fib_semantics.c:fib_get_nhs
  - net/ipv4/fib_semantics.c:fib_get_nhs
  - net/ipv4/fib_semantics.c:fib_get_nhs
  - net/ipv6/route.c:ip6_route_multipath_del
  - net/ipv6/route.c:ip6_route_multipath_add
  - net/ipv6/route.c:ip6_route_multipath_add
  - net/ipv6/route.c:ip6_route_multipath_add
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std
```
**Symbols:**

```
ffffffff8188f590-ffffffff8188f5de: nla_find (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct nlattr *nla_find(const struct nlattr *head, int len, int attrtype);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/nlattr.c (ffffffff818d19d0)
Location: lib/nlattr.c:713
Inline: False
Direct callers:
  - net/core/neighbour.c:neigh_delete
  - net/core/rtnetlink.c:rtnl_bridge_dellink
  - net/core/rtnetlink.c:rtnl_bridge_setlink
  - net/core/filter.c:bpf_skb_get_nlattr_nest
  - net/core/filter.c:bpf_skb_get_nlattr
  - net/core/lwtunnel.c:lwtunnel_valid_encap_type_attr
  - net/ipv4/fib_semantics.c:fib_nh_match
  - net/ipv4/fib_semantics.c:fib_nh_match
  - net/ipv4/fib_semantics.c:fib_nh_match
  - net/ipv4/fib_semantics.c:fib_get_nhs
  - net/ipv4/fib_semantics.c:fib_get_nhs
  - net/ipv4/fib_semantics.c:fib_get_nhs
  - net/ipv4/fib_semantics.c:fib_get_nhs
  - net/ipv4/fib_semantics.c:fib_get_nhs
  - net/ipv6/route.c:ip6_route_multipath_del
  - net/ipv6/route.c:ip6_route_multipath_add
  - net/ipv6/route.c:ip6_route_multipath_add
  - net/ipv6/route.c:ip6_route_multipath_add
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std
```
**Symbols:**

```
ffffffff818d19d0-ffffffff818d1a1e: nla_find (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct nlattr *nla_find(const struct nlattr *head, int len, int attrtype);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/nlattr.c (ffffffff819239c0)
Location: lib/nlattr.c:745
Inline: False
Direct callers:
  - net/core/neighbour.c:neigh_delete
  - net/core/rtnetlink.c:rtnl_bridge_dellink
  - net/core/rtnetlink.c:rtnl_bridge_setlink
  - net/core/filter.c:bpf_skb_get_nlattr_nest
  - net/core/filter.c:bpf_skb_get_nlattr
  - net/core/lwtunnel.c:lwtunnel_valid_encap_type_attr
  - net/ipv4/fib_semantics.c:fib_nh_match
  - net/ipv4/fib_semantics.c:fib_nh_match
  - net/ipv4/fib_semantics.c:fib_nh_match
  - net/ipv4/fib_semantics.c:fib_get_nhs
  - net/ipv4/fib_semantics.c:fib_get_nhs
  - net/ipv4/fib_semantics.c:fib_get_nhs
  - net/ipv4/fib_semantics.c:fib_get_nhs
  - net/ipv4/fib_semantics.c:fib_get_nhs
  - net/ipv6/route.c:ip6_route_multipath_del
  - net/ipv6/route.c:ip6_route_multipath_add
  - net/ipv6/route.c:ip6_route_multipath_add
  - net/ipv6/route.c:ip6_route_multipath_add
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std
```
**Symbols:**

```
ffffffff819239c0-ffffffff81923a0e: nla_find (STB_GLOBAL)
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
struct nlattr *nla_find(const struct nlattr *head, int len, int attrtype);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/nlattr.c (ffff800010661308)
Location: lib/nlattr.c:491
Inline: False
Direct callers:
  - net/core/neighbour.c:neigh_delete
  - net/core/rtnetlink.c:rtnl_bridge_dellink
  - net/core/rtnetlink.c:rtnl_bridge_setlink
  - net/core/filter.c:bpf_skb_get_nlattr_nest
  - net/core/filter.c:bpf_skb_get_nlattr
  - net/core/lwtunnel.c:lwtunnel_valid_encap_type_attr
  - net/ipv4/fib_semantics.c:fib_nh_match
  - net/ipv4/fib_semantics.c:fib_nh_match
  - net/ipv4/fib_semantics.c:fib_nh_match
  - net/ipv4/fib_semantics.c:fib_get_nhs
  - net/ipv4/fib_semantics.c:fib_get_nhs
  - net/ipv4/fib_semantics.c:fib_get_nhs
  - net/ipv4/fib_semantics.c:fib_get_nhs
  - net/ipv4/fib_semantics.c:fib_get_nhs
  - net/ipv6/route.c:ip6_route_multipath_del
  - net/ipv6/route.c:ip6_route_multipath_add
  - net/ipv6/route.c:ip6_route_multipath_add
  - net/ipv6/route.c:ip6_route_multipath_add
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std
```
**Symbols:**

```
ffff800010661308-ffff800010661358: nla_find (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct nlattr *nla_find(const struct nlattr *head, int len, int attrtype);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/nlattr.c (c080a334)
Location: lib/nlattr.c:491
Inline: False
Direct callers:
  - net/core/neighbour.c:neigh_delete
  - net/core/rtnetlink.c:rtnl_bridge_dellink
  - net/core/rtnetlink.c:rtnl_bridge_setlink
  - net/core/filter.c:bpf_skb_get_nlattr_nest
  - net/core/filter.c:bpf_skb_get_nlattr
  - net/core/lwtunnel.c:lwtunnel_valid_encap_type_attr
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_nh_match
  - net/ipv4/fib_semantics.c:fib_nh_match
  - net/ipv4/fib_semantics.c:fib_nh_match
  - net/ipv6/route.c:ip6_route_multipath_del
  - net/ipv6/route.c:ip6_route_multipath_add
  - net/ipv6/route.c:ip6_route_multipath_add
  - net/ipv6/route.c:ip6_route_multipath_add
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std
```
**Symbols:**

```
c080a334-c080a38c: nla_find (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct nlattr *nla_find(const struct nlattr *head, int len, int attrtype);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/nlattr.c (c000000000815060)
Location: lib/nlattr.c:491
Inline: False
Direct callers:
  - net/core/neighbour.c:neigh_delete
  - net/core/rtnetlink.c:rtnl_bridge_dellink
  - net/core/rtnetlink.c:rtnl_bridge_setlink
  - net/core/filter.c:bpf_skb_get_nlattr_nest
  - net/core/filter.c:bpf_skb_get_nlattr
  - net/core/lwtunnel.c:lwtunnel_valid_encap_type_attr
  - net/ipv4/fib_semantics.c:fib_nh_match
  - net/ipv4/fib_semantics.c:fib_nh_match
  - net/ipv4/fib_semantics.c:fib_nh_match
  - net/ipv4/fib_semantics.c:fib_get_nhs
  - net/ipv4/fib_semantics.c:fib_get_nhs
  - net/ipv4/fib_semantics.c:fib_get_nhs
  - net/ipv4/fib_semantics.c:fib_get_nhs
  - net/ipv4/fib_semantics.c:fib_get_nhs
  - net/ipv6/route.c:ip6_route_multipath_del
  - net/ipv6/route.c:ip6_route_multipath_add
  - net/ipv6/route.c:ip6_route_multipath_add
  - net/ipv6/route.c:ip6_route_multipath_add
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std
```
**Symbols:**

```
c000000000815060-c0000000008150b8: nla_find (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct nlattr *nla_find(const struct nlattr *head, int len, int attrtype);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/nlattr.c (ffffffe00048de08)
Location: lib/nlattr.c:491
Inline: False
Direct callers:
  - net/core/neighbour.c:neigh_delete
  - net/core/rtnetlink.c:rtnl_bridge_dellink
  - net/core/rtnetlink.c:rtnl_bridge_setlink
  - net/core/filter.c:bpf_skb_get_nlattr_nest
  - net/core/filter.c:bpf_skb_get_nlattr
  - net/core/lwtunnel.c:lwtunnel_valid_encap_type_attr
  - net/ipv4/fib_semantics.c:fib_nh_match
  - net/ipv4/fib_semantics.c:fib_nh_match
  - net/ipv4/fib_semantics.c:fib_nh_match
  - net/ipv4/fib_semantics.c:fib_get_nhs
  - net/ipv4/fib_semantics.c:fib_get_nhs
  - net/ipv4/fib_semantics.c:fib_get_nhs
  - net/ipv4/fib_semantics.c:fib_get_nhs
  - net/ipv4/fib_semantics.c:fib_get_nhs
  - net/ipv6/route.c:ip6_route_multipath_del
  - net/ipv6/route.c:ip6_route_multipath_add
  - net/ipv6/route.c:ip6_route_multipath_add
  - net/ipv6/route.c:ip6_route_multipath_add
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std
```
**Symbols:**

```
ffffffe00048de08-ffffffe00048de4e: nla_find (STB_GLOBAL)
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
struct nlattr *nla_find(const struct nlattr *head, int len, int attrtype);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/nlattr.c (ffffffff8154d560)
Location: lib/nlattr.c:491
Inline: False
Direct callers:
  - net/core/neighbour.c:neigh_delete
  - net/core/rtnetlink.c:rtnl_bridge_dellink
  - net/core/rtnetlink.c:rtnl_bridge_setlink
  - net/core/filter.c:bpf_skb_get_nlattr_nest
  - net/core/filter.c:bpf_skb_get_nlattr
  - net/core/lwtunnel.c:lwtunnel_valid_encap_type_attr
  - net/ipv4/fib_semantics.c:fib_nh_match
  - net/ipv4/fib_semantics.c:fib_nh_match
  - net/ipv4/fib_semantics.c:fib_nh_match
  - net/ipv4/fib_semantics.c:fib_get_nhs
  - net/ipv4/fib_semantics.c:fib_get_nhs
  - net/ipv4/fib_semantics.c:fib_get_nhs
  - net/ipv4/fib_semantics.c:fib_get_nhs
  - net/ipv4/fib_semantics.c:fib_get_nhs
  - net/ipv6/route.c:ip6_route_multipath_del
  - net/ipv6/route.c:ip6_route_multipath_add
  - net/ipv6/route.c:ip6_route_multipath_add
  - net/ipv6/route.c:ip6_route_multipath_add
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std
```
**Symbols:**

```
ffffffff8154d560-ffffffff8154d594: nla_find (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct nlattr *nla_find(const struct nlattr *head, int len, int attrtype);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/nlattr.c (ffffffff8153d840)
Location: lib/nlattr.c:491
Inline: False
Direct callers:
  - net/core/neighbour.c:neigh_delete
  - net/core/rtnetlink.c:rtnl_bridge_dellink
  - net/core/rtnetlink.c:rtnl_bridge_setlink
  - net/core/filter.c:bpf_skb_get_nlattr_nest
  - net/core/filter.c:bpf_skb_get_nlattr
  - net/core/lwtunnel.c:lwtunnel_valid_encap_type_attr
  - net/ipv4/fib_semantics.c:fib_nh_match
  - net/ipv4/fib_semantics.c:fib_nh_match
  - net/ipv4/fib_semantics.c:fib_nh_match
  - net/ipv4/fib_semantics.c:fib_get_nhs
  - net/ipv4/fib_semantics.c:fib_get_nhs
  - net/ipv4/fib_semantics.c:fib_get_nhs
  - net/ipv4/fib_semantics.c:fib_get_nhs
  - net/ipv4/fib_semantics.c:fib_get_nhs
  - net/ipv6/route.c:ip6_route_multipath_del
  - net/ipv6/route.c:ip6_route_multipath_add
  - net/ipv6/route.c:ip6_route_multipath_add
  - net/ipv6/route.c:ip6_route_multipath_add
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std
```
**Symbols:**

```
ffffffff8153d840-ffffffff8153d874: nla_find (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct nlattr *nla_find(const struct nlattr *head, int len, int attrtype);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/nlattr.c (ffffffff815492a0)
Location: lib/nlattr.c:491
Inline: False
Direct callers:
  - net/core/neighbour.c:neigh_delete
  - net/core/rtnetlink.c:rtnl_bridge_dellink
  - net/core/rtnetlink.c:rtnl_bridge_setlink
  - net/core/filter.c:bpf_skb_get_nlattr_nest
  - net/core/filter.c:bpf_skb_get_nlattr
  - net/core/lwtunnel.c:lwtunnel_valid_encap_type_attr
  - net/ipv4/fib_semantics.c:fib_nh_match
  - net/ipv4/fib_semantics.c:fib_nh_match
  - net/ipv4/fib_semantics.c:fib_nh_match
  - net/ipv4/fib_semantics.c:fib_get_nhs
  - net/ipv4/fib_semantics.c:fib_get_nhs
  - net/ipv4/fib_semantics.c:fib_get_nhs
  - net/ipv4/fib_semantics.c:fib_get_nhs
  - net/ipv4/fib_semantics.c:fib_get_nhs
  - net/ipv6/route.c:ip6_route_multipath_del
  - net/ipv6/route.c:ip6_route_multipath_add
  - net/ipv6/route.c:ip6_route_multipath_add
  - net/ipv6/route.c:ip6_route_multipath_add
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std
```
**Symbols:**

```
ffffffff815492a0-ffffffff815492d4: nla_find (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct nlattr *nla_find(const struct nlattr *head, int len, int attrtype);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/nlattr.c (ffffffff815630f0)
Location: lib/nlattr.c:491
Inline: False
Direct callers:
  - net/core/neighbour.c:neigh_delete
  - net/core/rtnetlink.c:rtnl_bridge_dellink
  - net/core/rtnetlink.c:rtnl_bridge_setlink
  - net/core/filter.c:bpf_skb_get_nlattr_nest
  - net/core/filter.c:bpf_skb_get_nlattr
  - net/core/lwtunnel.c:lwtunnel_valid_encap_type_attr
  - net/ipv4/fib_semantics.c:fib_nh_match
  - net/ipv4/fib_semantics.c:fib_nh_match
  - net/ipv4/fib_semantics.c:fib_nh_match
  - net/ipv4/fib_semantics.c:fib_get_nhs
  - net/ipv4/fib_semantics.c:fib_get_nhs
  - net/ipv4/fib_semantics.c:fib_get_nhs
  - net/ipv4/fib_semantics.c:fib_get_nhs
  - net/ipv4/fib_semantics.c:fib_get_nhs
  - net/ipv6/route.c:ip6_route_multipath_del
  - net/ipv6/route.c:ip6_route_multipath_add
  - net/ipv6/route.c:ip6_route_multipath_add
  - net/ipv6/route.c:ip6_route_multipath_add
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std
  - net/netlabel/netlabel_cipso_v4.c:netlbl_cipsov4_add_std
```
**Symbols:**

```
ffffffff815630f0-ffffffff81563124: nla_find (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
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
