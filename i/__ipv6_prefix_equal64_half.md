# Function: <code>__ipv6_prefix_equal64_half</code>

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
In net/ipv6/addrconf.c (ffffffff817cb48b)
Location: include/net/ipv6.h:449
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:check_cleanup_prefix_route
  - net/ipv6/addrconf.c:check_cleanup_prefix_route
  - net/ipv6/addrconf.c:ipv6_chk_custom_prefix
  - net/ipv6/addrconf.c:ipv6_chk_custom_prefix
  - net/ipv6/addrconf.c:ipv6_chk_prefix
  - net/ipv6/addrconf.c:ipv6_chk_prefix
```
```
In net/ipv6/addrlabel.c (ffffffff817d27a0)
Location: include/net/ipv6.h:449
Inline: True
Inline callers:
  - net/ipv6/addrlabel.c:__ipv6_addr_label
  - net/ipv6/addrlabel.c:__ipv6_addr_label
```
```
In net/ipv6/ip6_fib.c (ffffffff817da909)
Location: include/net/ipv6.h:449
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:fib6_add_1
  - net/ipv6/ip6_fib.c:fib6_add_1
  - net/ipv6/ip6_fib.c:fib6_locate_1
  - net/ipv6/ip6_fib.c:fib6_locate_1
  - net/ipv6/ip6_fib.c:fib6_lookup_1
  - net/ipv6/ip6_fib.c:fib6_lookup_1
```
```
In net/ipv6/fib6_rules.c (ffffffff817fe55f)
Location: include/net/ipv6.h:449
Inline: True
Inline callers:
  - net/ipv6/fib6_rules.c:fib6_rule_action
  - net/ipv6/fib6_rules.c:fib6_rule_action
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
In net/ipv6/addrconf.c (ffffffff818386b9)
Location: include/net/ipv6.h:481
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:ipv6_chk_prefix
  - net/ipv6/addrconf.c:ipv6_chk_prefix
  - net/ipv6/addrconf.c:ipv6_chk_custom_prefix
  - net/ipv6/addrconf.c:ipv6_chk_custom_prefix
  - net/ipv6/addrconf.c:check_cleanup_prefix_route
  - net/ipv6/addrconf.c:check_cleanup_prefix_route
```
```
In net/ipv6/addrlabel.c (ffffffff8183fece)
Location: include/net/ipv6.h:481
Inline: True
Inline callers:
  - net/ipv6/addrlabel.c:__ipv6_addr_label
  - net/ipv6/addrlabel.c:__ipv6_addr_label
```
```
In net/ipv6/ip6_fib.c (ffffffff81848da7)
Location: include/net/ipv6.h:481
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:fib6_locate_1
  - net/ipv6/ip6_fib.c:fib6_locate_1
  - net/ipv6/ip6_fib.c:fib6_lookup_1
  - net/ipv6/ip6_fib.c:fib6_lookup_1
  - net/ipv6/ip6_fib.c:fib6_add_1
  - net/ipv6/ip6_fib.c:fib6_add_1
```
```
In net/ipv6/fib6_rules.c (ffffffff8186def4)
Location: include/net/ipv6.h:481
Inline: True
Inline callers:
  - net/ipv6/fib6_rules.c:fib6_rule_action
  - net/ipv6/fib6_rules.c:fib6_rule_action
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
In net/ipv6/addrconf.c (ffffffff8186a1e9)
Location: include/net/ipv6.h:481
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:ipv6_chk_prefix
  - net/ipv6/addrconf.c:ipv6_chk_prefix
  - net/ipv6/addrconf.c:ipv6_chk_custom_prefix
  - net/ipv6/addrconf.c:ipv6_chk_custom_prefix
  - net/ipv6/addrconf.c:check_cleanup_prefix_route
  - net/ipv6/addrconf.c:check_cleanup_prefix_route
```
```
In net/ipv6/addrlabel.c (ffffffff81871b4e)
Location: include/net/ipv6.h:481
Inline: True
Inline callers:
  - net/ipv6/addrlabel.c:__ipv6_addr_label
  - net/ipv6/addrlabel.c:__ipv6_addr_label
```
```
In net/ipv6/ip6_fib.c (ffffffff8187abf7)
Location: include/net/ipv6.h:481
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:fib6_locate_1
  - net/ipv6/ip6_fib.c:fib6_locate_1
  - net/ipv6/ip6_fib.c:fib6_lookup_1
  - net/ipv6/ip6_fib.c:fib6_lookup_1
  - net/ipv6/ip6_fib.c:fib6_add_1
  - net/ipv6/ip6_fib.c:fib6_add_1
```
```
In net/ipv6/fib6_rules.c (ffffffff818a0cd4)
Location: include/net/ipv6.h:481
Inline: True
Inline callers:
  - net/ipv6/fib6_rules.c:fib6_rule_action
  - net/ipv6/fib6_rules.c:fib6_rule_action
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
In net/ipv4/tcp_ipv4.c (ffffffff81838a13)
Location: include/net/ipv6.h:482
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_md5_do_lookup
  - net/ipv4/tcp_ipv4.c:tcp_md5_do_lookup
```
```
In net/ipv6/addrconf.c (ffffffff8188d820)
Location: include/net/ipv6.h:482
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:ipv6_chk_prefix
  - net/ipv6/addrconf.c:ipv6_chk_prefix
  - net/ipv6/addrconf.c:ipv6_chk_custom_prefix
  - net/ipv6/addrconf.c:ipv6_chk_custom_prefix
  - net/ipv6/addrconf.c:check_cleanup_prefix_route
  - net/ipv6/addrconf.c:check_cleanup_prefix_route
```
```
In net/ipv6/addrlabel.c (ffffffff818968d3)
Location: include/net/ipv6.h:482
Inline: True
Inline callers:
  - net/ipv6/addrlabel.c:__ipv6_addr_label
  - net/ipv6/addrlabel.c:__ipv6_addr_label
```
```
In net/ipv6/ip6_fib.c (ffffffff818a05d7)
Location: include/net/ipv6.h:482
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:fib6_locate_1
  - net/ipv6/ip6_fib.c:fib6_locate_1
  - net/ipv6/ip6_fib.c:fib6_lookup_1
  - net/ipv6/ip6_fib.c:fib6_lookup_1
  - net/ipv6/ip6_fib.c:fib6_add_1
  - net/ipv6/ip6_fib.c:fib6_add_1
```
```
In net/ipv6/fib6_rules.c (ffffffff818c7362)
Location: include/net/ipv6.h:482
Inline: True
Inline callers:
  - net/ipv6/fib6_rules.c:fib6_rule_action
  - net/ipv6/fib6_rules.c:fib6_rule_action
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
In net/ipv4/tcp_ipv4.c (ffffffff818b8163)
Location: include/net/ipv6.h:523
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_md5_do_lookup
  - net/ipv4/tcp_ipv4.c:tcp_md5_do_lookup
```
```
In net/ipv6/addrconf.c (ffffffff8190faeb)
Location: include/net/ipv6.h:523
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:ipv6_chk_prefix
  - net/ipv6/addrconf.c:ipv6_chk_prefix
  - net/ipv6/addrconf.c:ipv6_chk_custom_prefix
  - net/ipv6/addrconf.c:ipv6_chk_custom_prefix
  - net/ipv6/addrconf.c:check_cleanup_prefix_route
  - net/ipv6/addrconf.c:check_cleanup_prefix_route
```
```
In net/ipv6/addrlabel.c (ffffffff81917cb3)
Location: include/net/ipv6.h:523
Inline: True
Inline callers:
  - net/ipv6/addrlabel.c:__ipv6_addr_label
  - net/ipv6/addrlabel.c:__ipv6_addr_label
```
```
In net/ipv6/ip6_fib.c (ffffffff81922618)
Location: include/net/ipv6.h:523
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:fib6_locate_1
  - net/ipv6/ip6_fib.c:fib6_locate_1
  - net/ipv6/ip6_fib.c:fib6_lookup_1
  - net/ipv6/ip6_fib.c:fib6_lookup_1
```
```
In net/ipv6/fib6_rules.c (ffffffff8194a885)
Location: include/net/ipv6.h:523
Inline: True
Inline callers:
  - net/ipv6/fib6_rules.c:fib6_rule_action
  - net/ipv6/fib6_rules.c:fib6_rule_action
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
In net/ipv4/tcp_ipv4.c (ffffffff8190f969)
Location: include/net/ipv6.h:511
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_md5_do_lookup
  - net/ipv4/tcp_ipv4.c:tcp_md5_do_lookup
```
```
In net/ipv6/addrconf.c (ffffffff81966a6d)
Location: include/net/ipv6.h:511
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:ipv6_chk_prefix
  - net/ipv6/addrconf.c:ipv6_chk_prefix
  - net/ipv6/addrconf.c:ipv6_chk_custom_prefix
  - net/ipv6/addrconf.c:ipv6_chk_custom_prefix
  - net/ipv6/addrconf.c:check_cleanup_prefix_route
  - net/ipv6/addrconf.c:check_cleanup_prefix_route
```
```
In net/ipv6/addrlabel.c (ffffffff8196f718)
Location: include/net/ipv6.h:511
Inline: True
Inline callers:
  - net/ipv6/addrlabel.c:__ipv6_addr_label
  - net/ipv6/addrlabel.c:__ipv6_addr_label
```
```
In net/ipv6/ip6_fib.c (ffffffff8197a9d3)
Location: include/net/ipv6.h:511
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:fib6_locate_1
  - net/ipv6/ip6_fib.c:fib6_locate_1
  - net/ipv6/ip6_fib.c:fib6_node_lookup_1
  - net/ipv6/ip6_fib.c:fib6_node_lookup_1
```
```
In net/ipv6/fib6_rules.c (ffffffff819a3757)
Location: include/net/ipv6.h:511
Inline: True
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
In net/ipv4/tcp_ipv4.c (ffffffff8193dd80)
Location: include/net/ipv6.h:531
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:__tcp_md5_do_lookup
  - net/ipv4/tcp_ipv4.c:__tcp_md5_do_lookup
  - net/ipv4/tcp_ipv4.c:__tcp_md5_do_lookup
  - net/ipv4/tcp_ipv4.c:__tcp_md5_do_lookup
```
```
In net/ipv6/addrconf.c (ffffffff8199c08d)
Location: include/net/ipv6.h:531
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:ipv6_chk_prefix
  - net/ipv6/addrconf.c:ipv6_chk_prefix
  - net/ipv6/addrconf.c:ipv6_chk_prefix
  - net/ipv6/addrconf.c:ipv6_chk_prefix
  - net/ipv6/addrconf.c:ipv6_chk_custom_prefix
  - net/ipv6/addrconf.c:ipv6_chk_custom_prefix
  - net/ipv6/addrconf.c:ipv6_chk_custom_prefix
  - net/ipv6/addrconf.c:ipv6_chk_custom_prefix
  - net/ipv6/addrconf.c:check_cleanup_prefix_route
  - net/ipv6/addrconf.c:check_cleanup_prefix_route
  - net/ipv6/addrconf.c:check_cleanup_prefix_route
  - net/ipv6/addrconf.c:check_cleanup_prefix_route
```
```
In net/ipv6/addrlabel.c (ffffffff819a5328)
Location: include/net/ipv6.h:531
Inline: True
Inline callers:
  - net/ipv6/addrlabel.c:__ipv6_addr_label
  - net/ipv6/addrlabel.c:__ipv6_addr_label
  - net/ipv6/addrlabel.c:__ipv6_addr_label
  - net/ipv6/addrlabel.c:__ipv6_addr_label
```
```
In net/ipv6/ip6_fib.c (ffffffff819b06a3)
Location: include/net/ipv6.h:531
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:fib6_locate_1
  - net/ipv6/ip6_fib.c:fib6_locate_1
  - net/ipv6/ip6_fib.c:fib6_locate_1
  - net/ipv6/ip6_fib.c:fib6_locate_1
  - net/ipv6/ip6_fib.c:fib6_node_lookup_1
  - net/ipv6/ip6_fib.c:fib6_node_lookup_1
  - net/ipv6/ip6_fib.c:fib6_node_lookup_1
  - net/ipv6/ip6_fib.c:fib6_node_lookup_1
```
```
In net/ipv6/fib6_rules.c (ffffffff819da267)
Location: include/net/ipv6.h:531
Inline: True
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
In net/ipv4/tcp_ipv4.c (ffffffff819a21f5)
Location: include/net/ipv6.h:589
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:__tcp_md5_do_lookup
  - net/ipv4/tcp_ipv4.c:__tcp_md5_do_lookup
  - net/ipv4/tcp_ipv4.c:__tcp_md5_do_lookup
  - net/ipv4/tcp_ipv4.c:__tcp_md5_do_lookup
```
```
In net/ipv6/addrconf.c (ffffffff81a07eae)
Location: include/net/ipv6.h:589
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:ipv6_chk_prefix
  - net/ipv6/addrconf.c:ipv6_chk_prefix
  - net/ipv6/addrconf.c:ipv6_chk_prefix
  - net/ipv6/addrconf.c:ipv6_chk_prefix
  - net/ipv6/addrconf.c:ipv6_chk_custom_prefix
  - net/ipv6/addrconf.c:ipv6_chk_custom_prefix
  - net/ipv6/addrconf.c:ipv6_chk_custom_prefix
  - net/ipv6/addrconf.c:ipv6_chk_custom_prefix
  - net/ipv6/addrconf.c:check_cleanup_prefix_route
  - net/ipv6/addrconf.c:check_cleanup_prefix_route
  - net/ipv6/addrconf.c:check_cleanup_prefix_route
  - net/ipv6/addrconf.c:check_cleanup_prefix_route
```
```
In net/ipv6/addrlabel.c (ffffffff81a117c8)
Location: include/net/ipv6.h:589
Inline: True
Inline callers:
  - net/ipv6/addrlabel.c:__ipv6_addr_label
  - net/ipv6/addrlabel.c:__ipv6_addr_label
  - net/ipv6/addrlabel.c:__ipv6_addr_label
  - net/ipv6/addrlabel.c:__ipv6_addr_label
```
```
In net/ipv6/ip6_fib.c (ffffffff81a1e7f3)
Location: include/net/ipv6.h:589
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:fib6_locate_1
  - net/ipv6/ip6_fib.c:fib6_locate_1
  - net/ipv6/ip6_fib.c:fib6_locate_1
  - net/ipv6/ip6_fib.c:fib6_locate_1
  - net/ipv6/ip6_fib.c:fib6_node_lookup_1
  - net/ipv6/ip6_fib.c:fib6_node_lookup_1
  - net/ipv6/ip6_fib.c:fib6_node_lookup_1
  - net/ipv6/ip6_fib.c:fib6_node_lookup_1
```
```
In net/ipv6/fib6_rules.c (ffffffff81a4924f)
Location: include/net/ipv6.h:589
Inline: True
Inline callers:
  - net/ipv6/fib6_rules.c:fib6_rule_match
  - net/ipv6/fib6_rules.c:fib6_rule_match
  - net/ipv6/fib6_rules.c:fib6_rule_match
  - net/ipv6/fib6_rules.c:fib6_rule_match
  - net/ipv6/fib6_rules.c:fib6_rule_match
  - net/ipv6/fib6_rules.c:fib6_rule_match
  - net/ipv6/fib6_rules.c:fib6_rule_match
  - net/ipv6/fib6_rules.c:fib6_rule_match
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
In net/ipv4/tcp_ipv4.c (ffffffff819d8dc5)
Location: include/net/ipv6.h:589
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:__tcp_md5_do_lookup
  - net/ipv4/tcp_ipv4.c:__tcp_md5_do_lookup
  - net/ipv4/tcp_ipv4.c:__tcp_md5_do_lookup
  - net/ipv4/tcp_ipv4.c:__tcp_md5_do_lookup
```
```
In net/ipv6/addrconf.c (ffffffff81a3ea1e)
Location: include/net/ipv6.h:589
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:ipv6_chk_prefix
  - net/ipv6/addrconf.c:ipv6_chk_prefix
  - net/ipv6/addrconf.c:ipv6_chk_prefix
  - net/ipv6/addrconf.c:ipv6_chk_prefix
  - net/ipv6/addrconf.c:ipv6_chk_custom_prefix
  - net/ipv6/addrconf.c:ipv6_chk_custom_prefix
  - net/ipv6/addrconf.c:ipv6_chk_custom_prefix
  - net/ipv6/addrconf.c:ipv6_chk_custom_prefix
  - net/ipv6/addrconf.c:check_cleanup_prefix_route
  - net/ipv6/addrconf.c:check_cleanup_prefix_route
  - net/ipv6/addrconf.c:check_cleanup_prefix_route
  - net/ipv6/addrconf.c:check_cleanup_prefix_route
```
```
In net/ipv6/addrlabel.c (ffffffff81a483e8)
Location: include/net/ipv6.h:589
Inline: True
Inline callers:
  - net/ipv6/addrlabel.c:__ipv6_addr_label
  - net/ipv6/addrlabel.c:__ipv6_addr_label
  - net/ipv6/addrlabel.c:__ipv6_addr_label
  - net/ipv6/addrlabel.c:__ipv6_addr_label
```
```
In net/ipv6/ip6_fib.c (ffffffff81a55453)
Location: include/net/ipv6.h:589
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:fib6_locate_1
  - net/ipv6/ip6_fib.c:fib6_locate_1
  - net/ipv6/ip6_fib.c:fib6_locate_1
  - net/ipv6/ip6_fib.c:fib6_locate_1
  - net/ipv6/ip6_fib.c:fib6_node_lookup_1
  - net/ipv6/ip6_fib.c:fib6_node_lookup_1
  - net/ipv6/ip6_fib.c:fib6_node_lookup_1
  - net/ipv6/ip6_fib.c:fib6_node_lookup_1
```
```
In net/ipv6/fib6_rules.c (ffffffff81a7fe4f)
Location: include/net/ipv6.h:589
Inline: True
Inline callers:
  - net/ipv6/fib6_rules.c:fib6_rule_match
  - net/ipv6/fib6_rules.c:fib6_rule_match
  - net/ipv6/fib6_rules.c:fib6_rule_match
  - net/ipv6/fib6_rules.c:fib6_rule_match
  - net/ipv6/fib6_rules.c:fib6_rule_match
  - net/ipv6/fib6_rules.c:fib6_rule_match
  - net/ipv6/fib6_rules.c:fib6_rule_match
  - net/ipv6/fib6_rules.c:fib6_rule_match
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
In net/ipv4/tcp_ipv4.c (ffffffff81ac5803)
Location: include/net/ipv6.h:589
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:__tcp_md5_do_lookup
  - net/ipv4/tcp_ipv4.c:__tcp_md5_do_lookup
  - net/ipv4/tcp_ipv4.c:__tcp_md5_do_lookup
  - net/ipv4/tcp_ipv4.c:__tcp_md5_do_lookup
```
```
In net/ipv6/addrconf.c (ffffffff81b33f9e)
Location: include/net/ipv6.h:589
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:ipv6_chk_prefix
  - net/ipv6/addrconf.c:ipv6_chk_prefix
  - net/ipv6/addrconf.c:ipv6_chk_prefix
  - net/ipv6/addrconf.c:ipv6_chk_prefix
  - net/ipv6/addrconf.c:ipv6_chk_custom_prefix
  - net/ipv6/addrconf.c:ipv6_chk_custom_prefix
  - net/ipv6/addrconf.c:ipv6_chk_custom_prefix
  - net/ipv6/addrconf.c:ipv6_chk_custom_prefix
  - net/ipv6/addrconf.c:check_cleanup_prefix_route
  - net/ipv6/addrconf.c:check_cleanup_prefix_route
  - net/ipv6/addrconf.c:check_cleanup_prefix_route
  - net/ipv6/addrconf.c:check_cleanup_prefix_route
```
```
In net/ipv6/addrlabel.c (ffffffff81b3f284)
Location: include/net/ipv6.h:589
Inline: True
```
```
In net/ipv6/ip6_fib.c (ffffffff81b4beb5)
Location: include/net/ipv6.h:589
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:fib6_locate_1
  - net/ipv6/ip6_fib.c:fib6_locate_1
  - net/ipv6/ip6_fib.c:fib6_locate_1
  - net/ipv6/ip6_fib.c:fib6_locate_1
  - net/ipv6/ip6_fib.c:fib6_node_lookup_1
  - net/ipv6/ip6_fib.c:fib6_node_lookup_1
  - net/ipv6/ip6_fib.c:fib6_node_lookup_1
  - net/ipv6/ip6_fib.c:fib6_node_lookup_1
```
```
In net/ipv6/fib6_rules.c (ffffffff81b7a714)
Location: include/net/ipv6.h:589
Inline: True
Inline callers:
  - net/ipv6/fib6_rules.c:fib6_rule_match
  - net/ipv6/fib6_rules.c:fib6_rule_match
  - net/ipv6/fib6_rules.c:fib6_rule_match
  - net/ipv6/fib6_rules.c:fib6_rule_match
  - net/ipv6/fib6_rules.c:fib6_rule_match
  - net/ipv6/fib6_rules.c:fib6_rule_match
  - net/ipv6/fib6_rules.c:fib6_rule_match
  - net/ipv6/fib6_rules.c:fib6_rule_match
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
In net/ipv4/tcp_ipv4.c (ffffffff81ad1473)
Location: include/net/ipv6.h:589
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:__tcp_md5_do_lookup
  - net/ipv4/tcp_ipv4.c:__tcp_md5_do_lookup
  - net/ipv4/tcp_ipv4.c:__tcp_md5_do_lookup
  - net/ipv4/tcp_ipv4.c:__tcp_md5_do_lookup
```
```
In net/ipv6/addrconf.c (ffffffff81b42b20)
Location: include/net/ipv6.h:589
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:ipv6_chk_prefix
  - net/ipv6/addrconf.c:ipv6_chk_prefix
  - net/ipv6/addrconf.c:ipv6_chk_prefix
  - net/ipv6/addrconf.c:ipv6_chk_prefix
  - net/ipv6/addrconf.c:ipv6_chk_custom_prefix
  - net/ipv6/addrconf.c:ipv6_chk_custom_prefix
  - net/ipv6/addrconf.c:ipv6_chk_custom_prefix
  - net/ipv6/addrconf.c:ipv6_chk_custom_prefix
  - net/ipv6/addrconf.c:check_cleanup_prefix_route
  - net/ipv6/addrconf.c:check_cleanup_prefix_route
  - net/ipv6/addrconf.c:check_cleanup_prefix_route
  - net/ipv6/addrconf.c:check_cleanup_prefix_route
```
```
In net/ipv6/addrlabel.c (ffffffff81b4dd14)
Location: include/net/ipv6.h:589
Inline: True
```
```
In net/ipv6/ip6_fib.c (ffffffff81b5aaf5)
Location: include/net/ipv6.h:589
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:fib6_locate_1
  - net/ipv6/ip6_fib.c:fib6_locate_1
  - net/ipv6/ip6_fib.c:fib6_locate_1
  - net/ipv6/ip6_fib.c:fib6_locate_1
  - net/ipv6/ip6_fib.c:fib6_node_lookup_1
  - net/ipv6/ip6_fib.c:fib6_node_lookup_1
  - net/ipv6/ip6_fib.c:fib6_node_lookup_1
  - net/ipv6/ip6_fib.c:fib6_node_lookup_1
```
```
In net/ipv6/fib6_rules.c (ffffffff81b89664)
Location: include/net/ipv6.h:589
Inline: True
Inline callers:
  - net/ipv6/fib6_rules.c:fib6_rule_match
  - net/ipv6/fib6_rules.c:fib6_rule_match
  - net/ipv6/fib6_rules.c:fib6_rule_match
  - net/ipv6/fib6_rules.c:fib6_rule_match
  - net/ipv6/fib6_rules.c:fib6_rule_match
  - net/ipv6/fib6_rules.c:fib6_rule_match
  - net/ipv6/fib6_rules.c:fib6_rule_match
  - net/ipv6/fib6_rules.c:fib6_rule_match
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
In net/ipv4/tcp_ipv4.c (ffffffff81abc462)
Location: include/net/ipv6.h:590
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:__tcp_md5_do_lookup
  - net/ipv4/tcp_ipv4.c:__tcp_md5_do_lookup
  - net/ipv4/tcp_ipv4.c:__tcp_md5_do_lookup
  - net/ipv4/tcp_ipv4.c:__tcp_md5_do_lookup
```
```
In net/ipv6/addrconf.c (ffffffff81b309b0)
Location: include/net/ipv6.h:590
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:ipv6_chk_prefix
  - net/ipv6/addrconf.c:ipv6_chk_prefix
  - net/ipv6/addrconf.c:ipv6_chk_prefix
  - net/ipv6/addrconf.c:ipv6_chk_prefix
  - net/ipv6/addrconf.c:ipv6_chk_custom_prefix
  - net/ipv6/addrconf.c:ipv6_chk_custom_prefix
  - net/ipv6/addrconf.c:ipv6_chk_custom_prefix
  - net/ipv6/addrconf.c:ipv6_chk_custom_prefix
  - net/ipv6/addrconf.c:check_cleanup_prefix_route
  - net/ipv6/addrconf.c:check_cleanup_prefix_route
  - net/ipv6/addrconf.c:check_cleanup_prefix_route
  - net/ipv6/addrconf.c:check_cleanup_prefix_route
```
```
In net/ipv6/addrlabel.c (ffffffff81b3b7b6)
Location: include/net/ipv6.h:590
Inline: True
```
```
In net/ipv6/ip6_fib.c (ffffffff81b48b82)
Location: include/net/ipv6.h:590
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:fib6_locate_1
  - net/ipv6/ip6_fib.c:fib6_locate_1
  - net/ipv6/ip6_fib.c:fib6_locate_1
  - net/ipv6/ip6_fib.c:fib6_locate_1
  - net/ipv6/ip6_fib.c:fib6_node_lookup_1
  - net/ipv6/ip6_fib.c:fib6_node_lookup_1
  - net/ipv6/ip6_fib.c:fib6_node_lookup_1
  - net/ipv6/ip6_fib.c:fib6_node_lookup_1
```
```
In net/ipv6/fib6_rules.c (ffffffff81b784a9)
Location: include/net/ipv6.h:590
Inline: True
Inline callers:
  - net/ipv6/fib6_rules.c:fib6_rule_match
  - net/ipv6/fib6_rules.c:fib6_rule_match
  - net/ipv6/fib6_rules.c:fib6_rule_match
  - net/ipv6/fib6_rules.c:fib6_rule_match
  - net/ipv6/fib6_rules.c:fib6_rule_match
  - net/ipv6/fib6_rules.c:fib6_rule_match
  - net/ipv6/fib6_rules.c:fib6_rule_match
  - net/ipv6/fib6_rules.c:fib6_rule_match
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
In net/ipv4/tcp_ipv4.c (ffffffff81b79573)
Location: include/net/ipv6.h:593
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:__tcp_md5_do_lookup
  - net/ipv4/tcp_ipv4.c:__tcp_md5_do_lookup
  - net/ipv4/tcp_ipv4.c:__tcp_md5_do_lookup
  - net/ipv4/tcp_ipv4.c:__tcp_md5_do_lookup
```
```
In net/ipv6/addrconf.c (ffffffff81bf6ebe)
Location: include/net/ipv6.h:593
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:ipv6_chk_prefix
  - net/ipv6/addrconf.c:ipv6_chk_prefix
  - net/ipv6/addrconf.c:ipv6_chk_prefix
  - net/ipv6/addrconf.c:ipv6_chk_prefix
  - net/ipv6/addrconf.c:ipv6_chk_custom_prefix
  - net/ipv6/addrconf.c:ipv6_chk_custom_prefix
  - net/ipv6/addrconf.c:ipv6_chk_custom_prefix
  - net/ipv6/addrconf.c:ipv6_chk_custom_prefix
  - net/ipv6/addrconf.c:check_cleanup_prefix_route
  - net/ipv6/addrconf.c:check_cleanup_prefix_route
  - net/ipv6/addrconf.c:check_cleanup_prefix_route
  - net/ipv6/addrconf.c:check_cleanup_prefix_route
```
```
In net/ipv6/addrlabel.c (ffffffff81c01fff)
Location: include/net/ipv6.h:593
Inline: True
Inline callers:
  - net/ipv6/addrlabel.c:__ipv6_addr_label
  - net/ipv6/addrlabel.c:__ipv6_addr_label
  - net/ipv6/addrlabel.c:__ipv6_addr_label
  - net/ipv6/addrlabel.c:__ipv6_addr_label
```
```
In net/ipv6/ip6_fib.c (ffffffff81c0ffd4)
Location: include/net/ipv6.h:593
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:fib6_locate_1
  - net/ipv6/ip6_fib.c:fib6_locate_1
  - net/ipv6/ip6_fib.c:fib6_locate_1
  - net/ipv6/ip6_fib.c:fib6_locate_1
  - net/ipv6/ip6_fib.c:fib6_node_lookup_1
  - net/ipv6/ip6_fib.c:fib6_node_lookup_1
  - net/ipv6/ip6_fib.c:fib6_node_lookup_1
  - net/ipv6/ip6_fib.c:fib6_node_lookup_1
```
```
In net/ipv6/fib6_rules.c (ffffffff81c430bb)
Location: include/net/ipv6.h:593
Inline: True
Inline callers:
  - net/ipv6/fib6_rules.c:fib6_rule_match
  - net/ipv6/fib6_rules.c:fib6_rule_match
  - net/ipv6/fib6_rules.c:fib6_rule_match
  - net/ipv6/fib6_rules.c:fib6_rule_match
  - net/ipv6/fib6_rules.c:fib6_rule_match
  - net/ipv6/fib6_rules.c:fib6_rule_match
  - net/ipv6/fib6_rules.c:fib6_rule_match
  - net/ipv6/fib6_rules.c:fib6_rule_match
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
In net/ipv4/tcp_ipv4.c (ffffffff81d0929a)
Location: include/net/ipv6.h:647
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:__tcp_md5_do_lookup
  - net/ipv4/tcp_ipv4.c:__tcp_md5_do_lookup
```
```
In net/ipv6/addrconf.c (ffffffff81d9027a)
Location: include/net/ipv6.h:647
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:ipv6_chk_prefix
  - net/ipv6/addrconf.c:ipv6_chk_prefix
  - net/ipv6/addrconf.c:ipv6_chk_custom_prefix
  - net/ipv6/addrconf.c:ipv6_chk_custom_prefix
  - net/ipv6/addrconf.c:check_cleanup_prefix_route
  - net/ipv6/addrconf.c:check_cleanup_prefix_route
```
```
In net/ipv6/addrlabel.c (ffffffff81d9bf72)
Location: include/net/ipv6.h:647
Inline: True
Inline callers:
  - net/ipv6/addrlabel.c:__ipv6_addr_label
  - net/ipv6/addrlabel.c:__ipv6_addr_label
```
```
In net/ipv6/ip6_fib.c (ffffffff81dab293)
Location: include/net/ipv6.h:647
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:fib6_locate_1
  - net/ipv6/ip6_fib.c:fib6_locate_1
  - net/ipv6/ip6_fib.c:fib6_node_lookup_1
  - net/ipv6/ip6_fib.c:fib6_node_lookup_1
```
```
In net/ipv6/fib6_rules.c (ffffffff81de1cec)
Location: include/net/ipv6.h:647
Inline: True
Inline callers:
  - net/ipv6/fib6_rules.c:fib6_rule_match
  - net/ipv6/fib6_rules.c:fib6_rule_match
  - net/ipv6/fib6_rules.c:fib6_rule_match
  - net/ipv6/fib6_rules.c:fib6_rule_match
  - net/ipv6/fib6_rules.c:fib6_rule_saddr
  - net/ipv6/fib6_rules.c:fib6_rule_saddr
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
In net/ipv4/tcp_ipv4.c (ffffffff81ece45a)
Location: include/net/ipv6.h:680
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:__tcp_md5_do_lookup
  - net/ipv4/tcp_ipv4.c:__tcp_md5_do_lookup
```
```
In net/ipv6/addrconf.c (ffffffff81f5e71a)
Location: include/net/ipv6.h:680
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:ipv6_chk_prefix
  - net/ipv6/addrconf.c:ipv6_chk_prefix
  - net/ipv6/addrconf.c:ipv6_chk_custom_prefix
  - net/ipv6/addrconf.c:ipv6_chk_custom_prefix
  - net/ipv6/addrconf.c:check_cleanup_prefix_route
  - net/ipv6/addrconf.c:check_cleanup_prefix_route
```
```
In net/ipv6/addrlabel.c (ffffffff81f6ac32)
Location: include/net/ipv6.h:680
Inline: True
Inline callers:
  - net/ipv6/addrlabel.c:__ipv6_addr_label
  - net/ipv6/addrlabel.c:__ipv6_addr_label
```
```
In net/ipv6/ip6_fib.c (ffffffff81f7abb3)
Location: include/net/ipv6.h:680
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:fib6_locate_1
  - net/ipv6/ip6_fib.c:fib6_locate_1
  - net/ipv6/ip6_fib.c:fib6_node_lookup_1
  - net/ipv6/ip6_fib.c:fib6_node_lookup_1
```
```
In net/ipv6/fib6_rules.c (ffffffff81fb41fc)
Location: include/net/ipv6.h:680
Inline: True
Inline callers:
  - net/ipv6/fib6_rules.c:fib6_rule_match
  - net/ipv6/fib6_rules.c:fib6_rule_match
  - net/ipv6/fib6_rules.c:fib6_rule_match
  - net/ipv6/fib6_rules.c:fib6_rule_match
  - net/ipv6/fib6_rules.c:fib6_rule_saddr
  - net/ipv6/fib6_rules.c:fib6_rule_saddr
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
In net/ipv4/tcp_ipv4.c (ffffffff81f2d8ba)
Location: include/net/ipv6.h:681
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:__tcp_md5_do_lookup
  - net/ipv4/tcp_ipv4.c:__tcp_md5_do_lookup
```
```
In net/ipv6/addrconf.c (ffffffff81fbe50a)
Location: include/net/ipv6.h:681
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:ipv6_chk_prefix
  - net/ipv6/addrconf.c:ipv6_chk_prefix
  - net/ipv6/addrconf.c:ipv6_chk_custom_prefix
  - net/ipv6/addrconf.c:ipv6_chk_custom_prefix
  - net/ipv6/addrconf.c:check_cleanup_prefix_route
  - net/ipv6/addrconf.c:check_cleanup_prefix_route
```
```
In net/ipv6/addrlabel.c (ffffffff81fcac62)
Location: include/net/ipv6.h:681
Inline: True
Inline callers:
  - net/ipv6/addrlabel.c:__ipv6_addr_label
  - net/ipv6/addrlabel.c:__ipv6_addr_label
```
```
In net/ipv6/ip6_fib.c (ffffffff81fdadc3)
Location: include/net/ipv6.h:681
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:fib6_locate_1
  - net/ipv6/ip6_fib.c:fib6_locate_1
  - net/ipv6/ip6_fib.c:fib6_node_lookup_1
  - net/ipv6/ip6_fib.c:fib6_node_lookup_1
```
```
In net/ipv6/fib6_rules.c (ffffffff8201499c)
Location: include/net/ipv6.h:681
Inline: True
Inline callers:
  - net/ipv6/fib6_rules.c:fib6_rule_match
  - net/ipv6/fib6_rules.c:fib6_rule_match
  - net/ipv6/fib6_rules.c:fib6_rule_match
  - net/ipv6/fib6_rules.c:fib6_rule_match
  - net/ipv6/fib6_rules.c:fib6_rule_saddr
  - net/ipv6/fib6_rules.c:fib6_rule_saddr
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
In net/ipv4/tcp_ipv4.c (ffffffff81ff2317)
Location: include/net/ipv6.h:681
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:__tcp_md5_do_lookup
  - net/ipv4/tcp_ipv4.c:__tcp_md5_do_lookup
```
```
In net/ipv4/tcp_ao.c (ffffffff820553bc)
Location: include/net/ipv6.h:681
Inline: True
Inline callers:
  - net/ipv4/tcp_ao.c:tcp_ao_verify_ipv6
  - net/ipv4/tcp_ao.c:tcp_ao_verify_ipv6
  - net/ipv4/tcp_ao.c:__tcp_ao_key_cmp
  - net/ipv4/tcp_ao.c:__tcp_ao_key_cmp
```
```
In net/ipv6/addrconf.c (ffffffff8208b99a)
Location: include/net/ipv6.h:681
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:ipv6_chk_prefix
  - net/ipv6/addrconf.c:ipv6_chk_prefix
  - net/ipv6/addrconf.c:ipv6_chk_custom_prefix
  - net/ipv6/addrconf.c:ipv6_chk_custom_prefix
  - net/ipv6/addrconf.c:check_cleanup_prefix_route
  - net/ipv6/addrconf.c:check_cleanup_prefix_route
```
```
In net/ipv6/addrlabel.c (ffffffff82098402)
Location: include/net/ipv6.h:681
Inline: True
Inline callers:
  - net/ipv6/addrlabel.c:__ipv6_addr_label
  - net/ipv6/addrlabel.c:__ipv6_addr_label
```
```
In net/ipv6/ip6_fib.c (ffffffff820a8813)
Location: include/net/ipv6.h:681
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:fib6_locate_1
  - net/ipv6/ip6_fib.c:fib6_locate_1
  - net/ipv6/ip6_fib.c:fib6_node_lookup_1
  - net/ipv6/ip6_fib.c:fib6_node_lookup_1
```
```
In net/ipv6/fib6_rules.c (ffffffff820e3adc)
Location: include/net/ipv6.h:681
Inline: True
Inline callers:
  - net/ipv6/fib6_rules.c:fib6_rule_match
  - net/ipv6/fib6_rules.c:fib6_rule_match
  - net/ipv6/fib6_rules.c:fib6_rule_match
  - net/ipv6/fib6_rules.c:fib6_rule_match
  - net/ipv6/fib6_rules.c:fib6_rule_saddr
  - net/ipv6/fib6_rules.c:fib6_rule_saddr
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
In net/ipv4/tcp_ipv4.c (ffff800010c8b4a4)
Location: include/net/ipv6.h:589
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:__tcp_md5_do_lookup
  - net/ipv4/tcp_ipv4.c:__tcp_md5_do_lookup
  - net/ipv4/tcp_ipv4.c:__tcp_md5_do_lookup
  - net/ipv4/tcp_ipv4.c:__tcp_md5_do_lookup
```
```
In net/ipv6/addrconf.c (ffff800010d000c0)
Location: include/net/ipv6.h:589
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:ipv6_chk_prefix
  - net/ipv6/addrconf.c:ipv6_chk_prefix
  - net/ipv6/addrconf.c:ipv6_chk_prefix
  - net/ipv6/addrconf.c:ipv6_chk_prefix
  - net/ipv6/addrconf.c:ipv6_chk_custom_prefix
  - net/ipv6/addrconf.c:ipv6_chk_custom_prefix
  - net/ipv6/addrconf.c:ipv6_chk_custom_prefix
  - net/ipv6/addrconf.c:ipv6_chk_custom_prefix
  - net/ipv6/addrconf.c:check_cleanup_prefix_route
  - net/ipv6/addrconf.c:check_cleanup_prefix_route
  - net/ipv6/addrconf.c:check_cleanup_prefix_route
  - net/ipv6/addrconf.c:check_cleanup_prefix_route
```
```
In net/ipv6/addrlabel.c (ffff800010d0b710)
Location: include/net/ipv6.h:589
Inline: True
Inline callers:
  - net/ipv6/addrlabel.c:__ipv6_addr_label
  - net/ipv6/addrlabel.c:__ipv6_addr_label
  - net/ipv6/addrlabel.c:__ipv6_addr_label
  - net/ipv6/addrlabel.c:__ipv6_addr_label
```
```
In net/ipv6/ip6_fib.c (ffff800010d19534)
Location: include/net/ipv6.h:589
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:fib6_locate_1
  - net/ipv6/ip6_fib.c:fib6_locate_1
  - net/ipv6/ip6_fib.c:fib6_locate_1
  - net/ipv6/ip6_fib.c:fib6_locate_1
  - net/ipv6/ip6_fib.c:fib6_node_lookup_1
  - net/ipv6/ip6_fib.c:fib6_node_lookup_1
  - net/ipv6/ip6_fib.c:fib6_node_lookup_1
  - net/ipv6/ip6_fib.c:fib6_node_lookup_1
```
```
In net/ipv6/fib6_rules.c (ffff800010d4b060)
Location: include/net/ipv6.h:589
Inline: True
```
</details>
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp_ipv4.c (c000000000d9a710)
Location: include/net/ipv6.h:589
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:__tcp_md5_do_lookup
  - net/ipv4/tcp_ipv4.c:__tcp_md5_do_lookup
  - net/ipv4/tcp_ipv4.c:__tcp_md5_do_lookup
  - net/ipv4/tcp_ipv4.c:__tcp_md5_do_lookup
```
```
In net/ipv6/addrconf.c (c000000000e29490)
Location: include/net/ipv6.h:589
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:ipv6_chk_prefix
  - net/ipv6/addrconf.c:ipv6_chk_prefix
  - net/ipv6/addrconf.c:ipv6_chk_prefix
  - net/ipv6/addrconf.c:ipv6_chk_prefix
  - net/ipv6/addrconf.c:ipv6_chk_custom_prefix
  - net/ipv6/addrconf.c:ipv6_chk_custom_prefix
  - net/ipv6/addrconf.c:ipv6_chk_custom_prefix
  - net/ipv6/addrconf.c:ipv6_chk_custom_prefix
  - net/ipv6/addrconf.c:check_cleanup_prefix_route
  - net/ipv6/addrconf.c:check_cleanup_prefix_route
  - net/ipv6/addrconf.c:check_cleanup_prefix_route
  - net/ipv6/addrconf.c:check_cleanup_prefix_route
```
```
In net/ipv6/addrlabel.c (c000000000e35e88)
Location: include/net/ipv6.h:589
Inline: True
Inline callers:
  - net/ipv6/addrlabel.c:__ipv6_addr_label
  - net/ipv6/addrlabel.c:__ipv6_addr_label
  - net/ipv6/addrlabel.c:__ipv6_addr_label
  - net/ipv6/addrlabel.c:__ipv6_addr_label
```
```
In net/ipv6/ip6_fib.c (c000000000e47600)
Location: include/net/ipv6.h:589
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:fib6_locate_1
  - net/ipv6/ip6_fib.c:fib6_locate_1
  - net/ipv6/ip6_fib.c:fib6_locate_1
  - net/ipv6/ip6_fib.c:fib6_locate_1
  - net/ipv6/ip6_fib.c:fib6_node_lookup_1
  - net/ipv6/ip6_fib.c:fib6_node_lookup_1
  - net/ipv6/ip6_fib.c:fib6_node_lookup_1
  - net/ipv6/ip6_fib.c:fib6_node_lookup_1
```
```
In net/ipv6/fib6_rules.c (c000000000e81310)
Location: include/net/ipv6.h:589
Inline: True
Inline callers:
  - net/ipv6/fib6_rules.c:fib6_rule_match
  - net/ipv6/fib6_rules.c:fib6_rule_match
  - net/ipv6/fib6_rules.c:fib6_rule_match
  - net/ipv6/fib6_rules.c:fib6_rule_match
  - net/ipv6/fib6_rules.c:fib6_rule_match
  - net/ipv6/fib6_rules.c:fib6_rule_match
  - net/ipv6/fib6_rules.c:fib6_rule_match
  - net/ipv6/fib6_rules.c:fib6_rule_match
```
</details>
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
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
In net/ipv4/tcp_ipv4.c (ffffffff81978c35)
Location: include/net/ipv6.h:589
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:__tcp_md5_do_lookup
  - net/ipv4/tcp_ipv4.c:__tcp_md5_do_lookup
  - net/ipv4/tcp_ipv4.c:__tcp_md5_do_lookup
  - net/ipv4/tcp_ipv4.c:__tcp_md5_do_lookup
```
```
In net/ipv6/addrconf.c (ffffffff819de0ae)
Location: include/net/ipv6.h:589
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:ipv6_chk_prefix
  - net/ipv6/addrconf.c:ipv6_chk_prefix
  - net/ipv6/addrconf.c:ipv6_chk_prefix
  - net/ipv6/addrconf.c:ipv6_chk_prefix
  - net/ipv6/addrconf.c:ipv6_chk_custom_prefix
  - net/ipv6/addrconf.c:ipv6_chk_custom_prefix
  - net/ipv6/addrconf.c:ipv6_chk_custom_prefix
  - net/ipv6/addrconf.c:ipv6_chk_custom_prefix
  - net/ipv6/addrconf.c:check_cleanup_prefix_route
  - net/ipv6/addrconf.c:check_cleanup_prefix_route
  - net/ipv6/addrconf.c:check_cleanup_prefix_route
  - net/ipv6/addrconf.c:check_cleanup_prefix_route
```
```
In net/ipv6/addrlabel.c (ffffffff819e7a78)
Location: include/net/ipv6.h:589
Inline: True
Inline callers:
  - net/ipv6/addrlabel.c:__ipv6_addr_label
  - net/ipv6/addrlabel.c:__ipv6_addr_label
  - net/ipv6/addrlabel.c:__ipv6_addr_label
  - net/ipv6/addrlabel.c:__ipv6_addr_label
```
```
In net/ipv6/ip6_fib.c (ffffffff819f4ae3)
Location: include/net/ipv6.h:589
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:fib6_locate_1
  - net/ipv6/ip6_fib.c:fib6_locate_1
  - net/ipv6/ip6_fib.c:fib6_locate_1
  - net/ipv6/ip6_fib.c:fib6_locate_1
  - net/ipv6/ip6_fib.c:fib6_node_lookup_1
  - net/ipv6/ip6_fib.c:fib6_node_lookup_1
  - net/ipv6/ip6_fib.c:fib6_node_lookup_1
  - net/ipv6/ip6_fib.c:fib6_node_lookup_1
```
```
In net/ipv6/fib6_rules.c (ffffffff81a1f4df)
Location: include/net/ipv6.h:589
Inline: True
Inline callers:
  - net/ipv6/fib6_rules.c:fib6_rule_match
  - net/ipv6/fib6_rules.c:fib6_rule_match
  - net/ipv6/fib6_rules.c:fib6_rule_match
  - net/ipv6/fib6_rules.c:fib6_rule_match
  - net/ipv6/fib6_rules.c:fib6_rule_match
  - net/ipv6/fib6_rules.c:fib6_rule_match
  - net/ipv6/fib6_rules.c:fib6_rule_match
  - net/ipv6/fib6_rules.c:fib6_rule_match
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
In net/ipv4/tcp_ipv4.c (ffffffff819326f5)
Location: include/net/ipv6.h:589
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:__tcp_md5_do_lookup
  - net/ipv4/tcp_ipv4.c:__tcp_md5_do_lookup
  - net/ipv4/tcp_ipv4.c:__tcp_md5_do_lookup
  - net/ipv4/tcp_ipv4.c:__tcp_md5_do_lookup
```
```
In net/ipv6/addrconf.c (ffffffff8199ae6e)
Location: include/net/ipv6.h:589
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:ipv6_chk_prefix
  - net/ipv6/addrconf.c:ipv6_chk_prefix
  - net/ipv6/addrconf.c:ipv6_chk_prefix
  - net/ipv6/addrconf.c:ipv6_chk_prefix
  - net/ipv6/addrconf.c:ipv6_chk_custom_prefix
  - net/ipv6/addrconf.c:ipv6_chk_custom_prefix
  - net/ipv6/addrconf.c:ipv6_chk_custom_prefix
  - net/ipv6/addrconf.c:ipv6_chk_custom_prefix
  - net/ipv6/addrconf.c:check_cleanup_prefix_route
  - net/ipv6/addrconf.c:check_cleanup_prefix_route
  - net/ipv6/addrconf.c:check_cleanup_prefix_route
  - net/ipv6/addrconf.c:check_cleanup_prefix_route
```
```
In net/ipv6/addrlabel.c (ffffffff819a4838)
Location: include/net/ipv6.h:589
Inline: True
Inline callers:
  - net/ipv6/addrlabel.c:__ipv6_addr_label
  - net/ipv6/addrlabel.c:__ipv6_addr_label
  - net/ipv6/addrlabel.c:__ipv6_addr_label
  - net/ipv6/addrlabel.c:__ipv6_addr_label
```
```
In net/ipv6/ip6_fib.c (ffffffff819b18a3)
Location: include/net/ipv6.h:589
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:fib6_locate_1
  - net/ipv6/ip6_fib.c:fib6_locate_1
  - net/ipv6/ip6_fib.c:fib6_locate_1
  - net/ipv6/ip6_fib.c:fib6_locate_1
  - net/ipv6/ip6_fib.c:fib6_node_lookup_1
  - net/ipv6/ip6_fib.c:fib6_node_lookup_1
  - net/ipv6/ip6_fib.c:fib6_node_lookup_1
  - net/ipv6/ip6_fib.c:fib6_node_lookup_1
```
```
In net/ipv6/fib6_rules.c (ffffffff819dc29f)
Location: include/net/ipv6.h:589
Inline: True
Inline callers:
  - net/ipv6/fib6_rules.c:fib6_rule_match
  - net/ipv6/fib6_rules.c:fib6_rule_match
  - net/ipv6/fib6_rules.c:fib6_rule_match
  - net/ipv6/fib6_rules.c:fib6_rule_match
  - net/ipv6/fib6_rules.c:fib6_rule_match
  - net/ipv6/fib6_rules.c:fib6_rule_match
  - net/ipv6/fib6_rules.c:fib6_rule_match
  - net/ipv6/fib6_rules.c:fib6_rule_match
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
In net/ipv4/tcp_ipv4.c (ffffffff819e3405)
Location: include/net/ipv6.h:589
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:__tcp_md5_do_lookup
  - net/ipv4/tcp_ipv4.c:__tcp_md5_do_lookup
  - net/ipv4/tcp_ipv4.c:__tcp_md5_do_lookup
  - net/ipv4/tcp_ipv4.c:__tcp_md5_do_lookup
```
```
In net/ipv6/addrconf.c (ffffffff81a48b2e)
Location: include/net/ipv6.h:589
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:ipv6_chk_prefix
  - net/ipv6/addrconf.c:ipv6_chk_prefix
  - net/ipv6/addrconf.c:ipv6_chk_prefix
  - net/ipv6/addrconf.c:ipv6_chk_prefix
  - net/ipv6/addrconf.c:ipv6_chk_custom_prefix
  - net/ipv6/addrconf.c:ipv6_chk_custom_prefix
  - net/ipv6/addrconf.c:ipv6_chk_custom_prefix
  - net/ipv6/addrconf.c:ipv6_chk_custom_prefix
  - net/ipv6/addrconf.c:check_cleanup_prefix_route
  - net/ipv6/addrconf.c:check_cleanup_prefix_route
  - net/ipv6/addrconf.c:check_cleanup_prefix_route
  - net/ipv6/addrconf.c:check_cleanup_prefix_route
```
```
In net/ipv6/addrlabel.c (ffffffff81a524f8)
Location: include/net/ipv6.h:589
Inline: True
Inline callers:
  - net/ipv6/addrlabel.c:__ipv6_addr_label
  - net/ipv6/addrlabel.c:__ipv6_addr_label
  - net/ipv6/addrlabel.c:__ipv6_addr_label
  - net/ipv6/addrlabel.c:__ipv6_addr_label
```
```
In net/ipv6/ip6_fib.c (ffffffff81a5f563)
Location: include/net/ipv6.h:589
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:fib6_locate_1
  - net/ipv6/ip6_fib.c:fib6_locate_1
  - net/ipv6/ip6_fib.c:fib6_locate_1
  - net/ipv6/ip6_fib.c:fib6_locate_1
  - net/ipv6/ip6_fib.c:fib6_node_lookup_1
  - net/ipv6/ip6_fib.c:fib6_node_lookup_1
  - net/ipv6/ip6_fib.c:fib6_node_lookup_1
  - net/ipv6/ip6_fib.c:fib6_node_lookup_1
```
```
In net/ipv6/fib6_rules.c (ffffffff81a89f5f)
Location: include/net/ipv6.h:589
Inline: True
Inline callers:
  - net/ipv6/fib6_rules.c:fib6_rule_match
  - net/ipv6/fib6_rules.c:fib6_rule_match
  - net/ipv6/fib6_rules.c:fib6_rule_match
  - net/ipv6/fib6_rules.c:fib6_rule_match
  - net/ipv6/fib6_rules.c:fib6_rule_match
  - net/ipv6/fib6_rules.c:fib6_rule_match
  - net/ipv6/fib6_rules.c:fib6_rule_match
  - net/ipv6/fib6_rules.c:fib6_rule_match
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
In net/ipv4/tcp_ipv4.c (ffffffff819ed525)
Location: include/net/ipv6.h:589
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:__tcp_md5_do_lookup
  - net/ipv4/tcp_ipv4.c:__tcp_md5_do_lookup
  - net/ipv4/tcp_ipv4.c:__tcp_md5_do_lookup
  - net/ipv4/tcp_ipv4.c:__tcp_md5_do_lookup
```
```
In net/ipv6/addrconf.c (ffffffff81a54c8d)
Location: include/net/ipv6.h:589
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:ipv6_chk_prefix
  - net/ipv6/addrconf.c:ipv6_chk_prefix
  - net/ipv6/addrconf.c:ipv6_chk_prefix
  - net/ipv6/addrconf.c:ipv6_chk_prefix
  - net/ipv6/addrconf.c:ipv6_chk_custom_prefix
  - net/ipv6/addrconf.c:ipv6_chk_custom_prefix
  - net/ipv6/addrconf.c:ipv6_chk_custom_prefix
  - net/ipv6/addrconf.c:ipv6_chk_custom_prefix
  - net/ipv6/addrconf.c:check_cleanup_prefix_route
  - net/ipv6/addrconf.c:check_cleanup_prefix_route
  - net/ipv6/addrconf.c:check_cleanup_prefix_route
  - net/ipv6/addrconf.c:check_cleanup_prefix_route
```
```
In net/ipv6/addrlabel.c (ffffffff81a5e4f8)
Location: include/net/ipv6.h:589
Inline: True
Inline callers:
  - net/ipv6/addrlabel.c:__ipv6_addr_label
  - net/ipv6/addrlabel.c:__ipv6_addr_label
  - net/ipv6/addrlabel.c:__ipv6_addr_label
  - net/ipv6/addrlabel.c:__ipv6_addr_label
```
```
In net/ipv6/ip6_fib.c (ffffffff81a6ba13)
Location: include/net/ipv6.h:589
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:fib6_locate_1
  - net/ipv6/ip6_fib.c:fib6_locate_1
  - net/ipv6/ip6_fib.c:fib6_locate_1
  - net/ipv6/ip6_fib.c:fib6_locate_1
  - net/ipv6/ip6_fib.c:fib6_node_lookup_1
  - net/ipv6/ip6_fib.c:fib6_node_lookup_1
  - net/ipv6/ip6_fib.c:fib6_node_lookup_1
  - net/ipv6/ip6_fib.c:fib6_node_lookup_1
```
```
In net/ipv6/fib6_rules.c (ffffffff81a96bbf)
Location: include/net/ipv6.h:589
Inline: True
Inline callers:
  - net/ipv6/fib6_rules.c:fib6_rule_match
  - net/ipv6/fib6_rules.c:fib6_rule_match
  - net/ipv6/fib6_rules.c:fib6_rule_match
  - net/ipv6/fib6_rules.c:fib6_rule_match
  - net/ipv6/fib6_rules.c:fib6_rule_match
  - net/ipv6/fib6_rules.c:fib6_rule_match
  - net/ipv6/fib6_rules.c:fib6_rule_match
  - net/ipv6/fib6_rules.c:fib6_rule_match
```
</details>
</li>
</ul>

## Differences
