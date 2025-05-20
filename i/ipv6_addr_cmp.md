# Function: <code>ipv6_addr_cmp</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/netlabel/netlabel_addrlist.c (ffffffff8180d0d6)
Location: include/net/ipv6.h:366
Inline: True
Inline callers:
  - net/netlabel/netlabel_addrlist.c:netlbl_af6list_add
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/netlabel/netlabel_addrlist.c (ffffffff8187f4c3)
Location: include/net/ipv6.h:383
Inline: True
Inline callers:
  - net/netlabel/netlabel_addrlist.c:netlbl_af6list_add
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/netlabel/netlabel_addrlist.c (ffffffff818b3d73)
Location: include/net/ipv6.h:383
Inline: True
Inline callers:
  - net/netlabel/netlabel_addrlist.c:netlbl_af6list_add
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/netlabel/netlabel_addrlist.c (ffffffff818da706)
Location: include/net/ipv6.h:384
Inline: True
Inline callers:
  - net/netlabel/netlabel_addrlist.c:netlbl_af6list_add
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/netlabel/netlabel_addrlist.c (ffffffff819602e6)
Location: include/net/ipv6.h:425
Inline: True
Inline callers:
  - net/netlabel/netlabel_addrlist.c:netlbl_af6list_add
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/netlabel/netlabel_addrlist.c (ffffffff819b9ad3)
Location: include/net/ipv6.h:413
Inline: True
Inline callers:
  - net/netlabel/netlabel_addrlist.c:netlbl_af6list_add
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/netlabel/netlabel_addrlist.c (ffffffff819f0da3)
Location: include/net/ipv6.h:433
Inline: True
Inline callers:
  - net/netlabel/netlabel_addrlist.c:netlbl_af6list_add
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Duplicate, Selective Inline ⚠️</summary>

```c
int ipv6_addr_cmp(const struct in6_addr *a1, const struct in6_addr *a2);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_semantics.c (ffffffff819c894e)
Location: include/net/ipv6.h:491
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_nh_match
  - net/ipv4/fib_semantics.c:fib_get_nhs
Direct callers:
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_nh_match
```
```
In net/netlabel/netlabel_addrlist.c (ffffffff81a60069)
Location: include/net/ipv6.h:491
Inline: True
Inline callers:
  - net/netlabel/netlabel_addrlist.c:netlbl_af6list_add
```
**Symbols:**

```
ffffffff819c7370-ffffffff819c7380: ipv6_addr_cmp (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Duplicate, Selective Inline ⚠️</summary>

```c
int ipv6_addr_cmp(const struct in6_addr *a1, const struct in6_addr *a2);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_semantics.c (ffffffff819ff515)
Location: include/net/ipv6.h:491
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_nh_match
  - net/ipv4/fib_semantics.c:fib_get_nhs
Direct callers:
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_nh_match
```
```
In net/netlabel/netlabel_addrlist.c (ffffffff81a96c99)
Location: include/net/ipv6.h:491
Inline: True
Inline callers:
  - net/netlabel/netlabel_addrlist.c:netlbl_af6list_add
```
**Symbols:**

```
ffffffff819fdf20-ffffffff819fdf30: ipv6_addr_cmp (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Selective Inline ⚠️</summary>

```c
int ipv6_addr_cmp(const struct in6_addr *a1, const struct in6_addr *a2);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_semantics.c (ffffffff81aeea7e)
Location: include/net/ipv6.h:491
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_nh_match
  - net/ipv4/fib_semantics.c:fib_get_nhs
  - net/ipv4/fib_semantics.c:fib_find_info
Direct callers:
  - net/ipv4/fib_semantics.c:fib_nh_match
```
```
In net/netlabel/netlabel_addrlist.c (ffffffff81b92469)
Location: include/net/ipv6.h:491
Inline: True
Inline callers:
  - net/netlabel/netlabel_addrlist.c:netlbl_af6list_add
```
```
In net/mptcp/pm_netlink.c (ffffffff81bb425c)
Location: include/net/ipv6.h:491
Inline: True
Inline callers:
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_get_local_id
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_append_new_local_addr
  - net/mptcp/pm_netlink.c:lookup_subflow_by_saddr
```
**Symbols:**

```
ffffffff81aeca30-ffffffff81aeca40: ipv6_addr_cmp (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Selective Inline ⚠️</summary>

```c
int ipv6_addr_cmp(const struct in6_addr *a1, const struct in6_addr *a2);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_semantics.c (ffffffff81afb9de)
Location: include/net/ipv6.h:491
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_nh_match
  - net/ipv4/fib_semantics.c:fib_get_nhs
  - net/ipv4/fib_semantics.c:fib_find_info
Direct callers:
  - net/ipv4/fib_semantics.c:fib_nh_match
```
```
In net/netlabel/netlabel_addrlist.c (ffffffff81ba20d9)
Location: include/net/ipv6.h:491
Inline: True
Inline callers:
  - net/netlabel/netlabel_addrlist.c:netlbl_af6list_add
```
```
In net/mptcp/pm_netlink.c (ffffffff81bc8447)
Location: include/net/ipv6.h:491
Inline: True
Inline callers:
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_append_new_local_addr
  - net/mptcp/pm_netlink.c:mptcp_pm_alloc_anno_list
  - net/mptcp/pm_netlink.c:mptcp_pm_del_add_timer
  - net/mptcp/pm_netlink.c:lookup_subflow_by_saddr
```
**Symbols:**

```
ffffffff81af98f0-ffffffff81af9900: ipv6_addr_cmp (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Selective Inline ⚠️</summary>

```c
int ipv6_addr_cmp(const struct in6_addr *a1, const struct in6_addr *a2);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_semantics.c (ffffffff81ae7140)
Location: include/net/ipv6.h:492
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_nh_match
  - net/ipv4/fib_semantics.c:fib_get_nhs
  - net/ipv4/fib_semantics.c:fib_find_info
Direct callers:
  - net/ipv4/fib_semantics.c:fib_nh_match
```
```
In net/netlabel/netlabel_addrlist.c (ffffffff81b911b9)
Location: include/net/ipv6.h:492
Inline: True
Inline callers:
  - net/netlabel/netlabel_addrlist.c:netlbl_af6list_add
```
```
In net/mptcp/pm_netlink.c (ffffffff81bb80d4)
Location: include/net/ipv6.h:492
Inline: True
Inline callers:
  - net/mptcp/pm_netlink.c:addresses_equal
```
**Symbols:**

```
ffffffff81ae4ff0-ffffffff81ae5000: ipv6_addr_cmp (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Selective Inline ⚠️</summary>

```c
int ipv6_addr_cmp(const struct in6_addr *a1, const struct in6_addr *a2);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_semantics.c (ffffffff81ba6e51)
Location: include/net/ipv6.h:495
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_nh_match
  - net/ipv4/fib_semantics.c:fib_get_nhs
  - net/ipv4/fib_semantics.c:fib_find_info
Direct callers:
  - net/ipv4/fib_semantics.c:fib_nh_match
```
```
In net/netlabel/netlabel_addrlist.c (ffffffff81c5d959)
Location: include/net/ipv6.h:495
Inline: True
Inline callers:
  - net/netlabel/netlabel_addrlist.c:netlbl_af6list_add
```
```
In net/mptcp/pm_netlink.c (ffffffff81c87754)
Location: include/net/ipv6.h:495
Inline: True
Inline callers:
  - net/mptcp/pm_netlink.c:addresses_equal
```
**Symbols:**

```
ffffffff81ba4920-ffffffff81ba4930: ipv6_addr_cmp (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Selective Inline ⚠️</summary>

```c
int ipv6_addr_cmp(const struct in6_addr *a1, const struct in6_addr *a2);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_semantics.c (ffffffff81d39715)
Location: include/net/ipv6.h:549
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_nh_match
  - net/ipv4/fib_semantics.c:fib_get_nhs
  - net/ipv4/fib_semantics.c:fib_find_info
Direct callers:
  - net/ipv4/fib_semantics.c:fib_nh_match
```
```
In net/netlabel/netlabel_addrlist.c (ffffffff81dff9e9)
Location: include/net/ipv6.h:549
Inline: True
Inline callers:
  - net/netlabel/netlabel_addrlist.c:netlbl_af6list_add
```
```
In net/mptcp/pm_netlink.c (ffffffff81e2f39a)
Location: include/net/ipv6.h:549
Inline: True
Inline callers:
  - net/mptcp/pm_netlink.c:mptcp_addresses_equal
```
**Symbols:**

```
ffffffff81d37290-ffffffff81d372aa: ipv6_addr_cmp (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Selective Inline ⚠️</summary>

```c
int ipv6_addr_cmp(const struct in6_addr *a1, const struct in6_addr *a2);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_semantics.c (ffffffff81f02038)
Location: include/net/ipv6.h:582
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_nh_match
  - net/ipv4/fib_semantics.c:fib_get_nhs
  - net/ipv4/fib_semantics.c:fib_find_info
Direct callers:
  - net/ipv4/fib_semantics.c:fib_nh_match
```
```
In net/netlabel/netlabel_addrlist.c (ffffffff81fd4769)
Location: include/net/ipv6.h:582
Inline: True
Inline callers:
  - net/netlabel/netlabel_addrlist.c:netlbl_af6list_add
```
```
In net/mptcp/pm_netlink.c (ffffffff82007a9a)
Location: include/net/ipv6.h:582
Inline: True
Inline callers:
  - net/mptcp/pm_netlink.c:mptcp_addresses_equal
```
**Symbols:**

```
ffffffff81eff9a0-ffffffff81eff9ba: ipv6_addr_cmp (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Selective Inline ⚠️</summary>

```c
int ipv6_addr_cmp(const struct in6_addr *a1, const struct in6_addr *a2);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_semantics.c (ffffffff81f61a98)
Location: include/net/ipv6.h:583
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_nh_match
  - net/ipv4/fib_semantics.c:fib_get_nhs
  - net/ipv4/fib_semantics.c:fib_find_info
Direct callers:
  - net/ipv4/fib_semantics.c:fib_nh_match
```
```
In net/netlabel/netlabel_addrlist.c (ffffffff820503b9)
Location: include/net/ipv6.h:583
Inline: True
Inline callers:
  - net/netlabel/netlabel_addrlist.c:netlbl_af6list_add
```
```
In net/mptcp/pm_netlink.c (ffffffff82083e1a)
Location: include/net/ipv6.h:583
Inline: True
Inline callers:
  - net/mptcp/pm_netlink.c:mptcp_addresses_equal
```
**Symbols:**

```
ffffffff81f5f420-ffffffff81f5f43a: ipv6_addr_cmp (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate, Selective Inline ⚠️</summary>

```c
int ipv6_addr_cmp(const struct in6_addr *a1, const struct in6_addr *a2);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_semantics.c (ffffffff82028068)
Location: include/net/ipv6.h:583
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_nh_match
  - net/ipv4/fib_semantics.c:fib_get_nhs
  - net/ipv4/fib_semantics.c:fib_find_info
Direct callers:
  - net/ipv4/fib_semantics.c:fib_nh_match
```
```
In net/ipv4/tcp_ao.c (ffffffff8205572f)
Location: include/net/ipv6.h:583
Inline: True
Inline callers:
  - net/ipv4/tcp_ao.c:tcp_ao_copy_mkts_to_user
  - net/ipv4/tcp_ao.c:tcp_ao_verify_ipv6
```
```
In net/netlabel/netlabel_addrlist.c (ffffffff82122a69)
Location: include/net/ipv6.h:583
Inline: True
Inline callers:
  - net/netlabel/netlabel_addrlist.c:netlbl_af6list_add
```
```
In net/mptcp/pm_netlink.c (ffffffff8215945a)
Location: include/net/ipv6.h:583
Inline: True
Inline callers:
  - net/mptcp/pm_netlink.c:mptcp_addresses_equal
```
**Symbols:**

```
ffffffff820259f0-ffffffff82025a0a: ipv6_addr_cmp (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Duplicate, Selective Inline ⚠️</summary>

```c
int ipv6_addr_cmp(const struct in6_addr *a1, const struct in6_addr *a2);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_semantics.c (ffff800010cb7a18)
Location: include/net/ipv6.h:491
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_nh_match
  - net/ipv4/fib_semantics.c:fib_get_nhs
Direct callers:
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_nh_match
```
```
In net/netlabel/netlabel_addrlist.c (ffff800010d66160)
Location: include/net/ipv6.h:491
Inline: True
Inline callers:
  - net/netlabel/netlabel_addrlist.c:netlbl_af6list_add
```
**Symbols:**

```
ffff800010cb6078-ffff800010cb6090: ipv6_addr_cmp (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Duplicate, Selective Inline ⚠️</summary>

```c
int ipv6_addr_cmp(const struct in6_addr *a1, const struct in6_addr *a2);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_semantics.c (c0dc2b74)
Location: include/net/ipv6.h:491
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_nh_match
Direct callers:
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_nh_match
```
```
In net/netlabel/netlabel_addrlist.c (c0e64a08)
Location: include/net/ipv6.h:491
Inline: True
Inline callers:
  - net/netlabel/netlabel_addrlist.c:netlbl_af6list_add
```
**Symbols:**

```
c0dc1b54-c0dc1b6c: ipv6_addr_cmp (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Duplicate, Selective Inline ⚠️</summary>

```c
int ipv6_addr_cmp(const struct in6_addr *a1, const struct in6_addr *a2);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_semantics.c (c000000000dd0120)
Location: include/net/ipv6.h:491
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_nh_match
  - net/ipv4/fib_semantics.c:fib_get_nhs
Direct callers:
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_nh_match
```
```
In net/netlabel/netlabel_addrlist.c (c000000000ea2200)
Location: include/net/ipv6.h:491
Inline: True
Inline callers:
  - net/netlabel/netlabel_addrlist.c:netlbl_af6list_add
```
**Symbols:**

```
c000000000dcdf30-c000000000dcdf88: ipv6_addr_cmp (STB_LOCAL)
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
In net/ipv4/fib_semantics.c (ffffffe00080fb98)
Location: include/net/ipv6.h:491
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_nh_match
  - net/ipv4/fib_semantics.c:fib_nh_match
  - net/ipv4/fib_semantics.c:fib_get_nhs
```
```
In net/netlabel/netlabel_addrlist.c (ffffffe000899c84)
Location: include/net/ipv6.h:491
Inline: True
Inline callers:
  - net/netlabel/netlabel_addrlist.c:netlbl_af6list_add
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Duplicate, Selective Inline ⚠️</summary>

```c
int ipv6_addr_cmp(const struct in6_addr *a1, const struct in6_addr *a2);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_semantics.c (ffffffff8199f2b5)
Location: include/net/ipv6.h:491
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_nh_match
  - net/ipv4/fib_semantics.c:fib_get_nhs
Direct callers:
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_nh_match
```
```
In net/netlabel/netlabel_addrlist.c (ffffffff81a36029)
Location: include/net/ipv6.h:491
Inline: True
Inline callers:
  - net/netlabel/netlabel_addrlist.c:netlbl_af6list_add
```
**Symbols:**

```
ffffffff8199dcc0-ffffffff8199dcd0: ipv6_addr_cmp (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Duplicate, Selective Inline ⚠️</summary>

```c
int ipv6_addr_cmp(const struct in6_addr *a1, const struct in6_addr *a2);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_semantics.c (ffffffff81958d75)
Location: include/net/ipv6.h:491
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_nh_match
  - net/ipv4/fib_semantics.c:fib_get_nhs
Direct callers:
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_nh_match
```
```
In net/netlabel/netlabel_addrlist.c (ffffffff819f2c49)
Location: include/net/ipv6.h:491
Inline: True
Inline callers:
  - net/netlabel/netlabel_addrlist.c:netlbl_af6list_add
```
**Symbols:**

```
ffffffff81957780-ffffffff81957790: ipv6_addr_cmp (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Duplicate, Selective Inline ⚠️</summary>

```c
int ipv6_addr_cmp(const struct in6_addr *a1, const struct in6_addr *a2);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_semantics.c (ffffffff81a09b55)
Location: include/net/ipv6.h:491
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_nh_match
  - net/ipv4/fib_semantics.c:fib_get_nhs
Direct callers:
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_nh_match
```
```
In net/netlabel/netlabel_addrlist.c (ffffffff81aa1ed9)
Location: include/net/ipv6.h:491
Inline: True
Inline callers:
  - net/netlabel/netlabel_addrlist.c:netlbl_af6list_add
```
**Symbols:**

```
ffffffff81a08560-ffffffff81a08570: ipv6_addr_cmp (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Duplicate, Selective Inline ⚠️</summary>

```c
int ipv6_addr_cmp(const struct in6_addr *a1, const struct in6_addr *a2);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/ipv4/fib_semantics.c (ffffffff81a14305)
Location: include/net/ipv6.h:491
Inline: True
Inline callers:
  - net/ipv4/fib_semantics.c:fib_nh_match
  - net/ipv4/fib_semantics.c:fib_get_nhs
Direct callers:
  - net/ipv4/fib_semantics.c:fib_create_info
  - net/ipv4/fib_semantics.c:fib_nh_match
```
```
In net/netlabel/netlabel_addrlist.c (ffffffff81aae249)
Location: include/net/ipv6.h:491
Inline: True
Inline callers:
  - net/netlabel/netlabel_addrlist.c:netlbl_af6list_add
```
**Symbols:**

```
ffffffff81a12cb0-ffffffff81a12cc0: ipv6_addr_cmp (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
