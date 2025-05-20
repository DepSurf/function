# Function: <code>ipv6_prefix_equal</code>

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
In net/ipv6/addrconf.c (ffffffff817cb458)
Location: include/net/ipv6.h:458
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:check_cleanup_prefix_route
  - net/ipv6/addrconf.c:ipv6_chk_custom_prefix
  - net/ipv6/addrconf.c:ipv6_chk_prefix
```
```
In net/ipv6/addrlabel.c (ffffffff817d27a0)
Location: include/net/ipv6.h:458
Inline: True
Inline callers:
  - net/ipv6/addrlabel.c:__ipv6_addr_label
```
```
In net/ipv6/ip6_fib.c (ffffffff817da909)
Location: include/net/ipv6.h:458
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:fib6_add_1
  - net/ipv6/ip6_fib.c:fib6_locate_1
  - net/ipv6/ip6_fib.c:fib6_lookup_1
```
```
In net/ipv6/fib6_rules.c (ffffffff817fe532)
Location: include/net/ipv6.h:458
Inline: True
Inline callers:
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
Location: include/net/ipv6.h:490
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:ipv6_chk_prefix
  - net/ipv6/addrconf.c:ipv6_chk_custom_prefix
  - net/ipv6/addrconf.c:check_cleanup_prefix_route
```
```
In net/ipv6/addrlabel.c (ffffffff8183fece)
Location: include/net/ipv6.h:490
Inline: True
Inline callers:
  - net/ipv6/addrlabel.c:__ipv6_addr_label
```
```
In net/ipv6/ip6_fib.c (ffffffff81848d97)
Location: include/net/ipv6.h:490
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:fib6_locate_1
  - net/ipv6/ip6_fib.c:fib6_lookup_1
  - net/ipv6/ip6_fib.c:fib6_add_1
```
```
In net/ipv6/fib6_rules.c (ffffffff8186dec7)
Location: include/net/ipv6.h:490
Inline: True
Inline callers:
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
Location: include/net/ipv6.h:490
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:ipv6_chk_prefix
  - net/ipv6/addrconf.c:ipv6_chk_custom_prefix
  - net/ipv6/addrconf.c:check_cleanup_prefix_route
```
```
In net/ipv6/addrlabel.c (ffffffff81871b4e)
Location: include/net/ipv6.h:490
Inline: True
Inline callers:
  - net/ipv6/addrlabel.c:__ipv6_addr_label
```
```
In net/ipv6/ip6_fib.c (ffffffff8187abe7)
Location: include/net/ipv6.h:490
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:fib6_locate_1
  - net/ipv6/ip6_fib.c:fib6_lookup_1
  - net/ipv6/ip6_fib.c:fib6_add_1
```
```
In net/ipv6/fib6_rules.c (ffffffff818a0ca7)
Location: include/net/ipv6.h:490
Inline: True
Inline callers:
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
Location: include/net/ipv6.h:491
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_md5_do_lookup
```
```
In net/ipv6/addrconf.c (ffffffff8188d820)
Location: include/net/ipv6.h:491
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:ipv6_chk_prefix
  - net/ipv6/addrconf.c:ipv6_chk_custom_prefix
  - net/ipv6/addrconf.c:check_cleanup_prefix_route
```
```
In net/ipv6/addrlabel.c (ffffffff818968d3)
Location: include/net/ipv6.h:491
Inline: True
Inline callers:
  - net/ipv6/addrlabel.c:__ipv6_addr_label
```
```
In net/ipv6/ip6_fib.c (ffffffff818a05c7)
Location: include/net/ipv6.h:491
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:fib6_locate_1
  - net/ipv6/ip6_fib.c:fib6_lookup_1
  - net/ipv6/ip6_fib.c:fib6_add_1
```
```
In net/ipv6/fib6_rules.c (ffffffff818c7337)
Location: include/net/ipv6.h:491
Inline: True
Inline callers:
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
Location: include/net/ipv6.h:532
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_md5_do_lookup
```
```
In net/ipv6/addrconf.c (ffffffff8190faeb)
Location: include/net/ipv6.h:532
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:ipv6_chk_prefix
  - net/ipv6/addrconf.c:ipv6_chk_custom_prefix
  - net/ipv6/addrconf.c:check_cleanup_prefix_route
```
```
In net/ipv6/addrlabel.c (ffffffff81917cb3)
Location: include/net/ipv6.h:532
Inline: True
Inline callers:
  - net/ipv6/addrlabel.c:__ipv6_addr_label
```
```
In net/ipv6/ip6_fib.c (ffffffff81922618)
Location: include/net/ipv6.h:532
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:fib6_locate_1
  - net/ipv6/ip6_fib.c:fib6_lookup_1
```
```
In net/ipv6/fib6_rules.c (ffffffff8194a85a)
Location: include/net/ipv6.h:532
Inline: True
Inline callers:
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
In net/ipv4/tcp_ipv4.c (ffffffff8190f964)
Location: include/net/ipv6.h:520
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_md5_do_lookup
```
```
In net/ipv6/addrconf.c (ffffffff81966a68)
Location: include/net/ipv6.h:520
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:ipv6_chk_prefix
  - net/ipv6/addrconf.c:ipv6_chk_custom_prefix
  - net/ipv6/addrconf.c:check_cleanup_prefix_route
```
```
In net/ipv6/addrlabel.c (ffffffff8196f713)
Location: include/net/ipv6.h:520
Inline: True
Inline callers:
  - net/ipv6/addrlabel.c:__ipv6_addr_label
```
```
In net/ipv6/ip6_fib.c (ffffffff8197a9ac)
Location: include/net/ipv6.h:520
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:fib6_locate_1
  - net/ipv6/ip6_fib.c:fib6_node_lookup_1
```
```
In net/ipv6/fib6_rules.c (ffffffff819a373d)
Location: include/net/ipv6.h:520
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
In net/ipv4/tcp_ipv4.c (ffffffff8193dd7b)
Location: include/net/ipv6.h:540
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:__tcp_md5_do_lookup
```
```
In net/ipv6/addrconf.c (ffffffff8199c088)
Location: include/net/ipv6.h:540
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
In net/ipv6/addrlabel.c (ffffffff819a5323)
Location: include/net/ipv6.h:540
Inline: True
Inline callers:
  - net/ipv6/addrlabel.c:__ipv6_addr_label
```
```
In net/ipv6/ip6_fib.c (ffffffff819b067c)
Location: include/net/ipv6.h:540
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:fib6_locate_1
  - net/ipv6/ip6_fib.c:fib6_locate_1
  - net/ipv6/ip6_fib.c:fib6_node_lookup_1
  - net/ipv6/ip6_fib.c:fib6_node_lookup_1
```
```
In net/ipv6/fib6_rules.c (ffffffff819da24d)
Location: include/net/ipv6.h:540
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
In net/ipv4/tcp_ipv4.c (ffffffff819a21bd)
Location: include/net/ipv6.h:598
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:__tcp_md5_do_lookup
```
```
In net/ipv6/addrconf.c (ffffffff81a07ea9)
Location: include/net/ipv6.h:598
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
In net/ipv6/addrlabel.c (ffffffff81a117c3)
Location: include/net/ipv6.h:598
Inline: True
Inline callers:
  - net/ipv6/addrlabel.c:__ipv6_addr_label
```
```
In net/ipv6/ip6_fib.c (ffffffff81a1e7ca)
Location: include/net/ipv6.h:598
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:fib6_locate_1
  - net/ipv6/ip6_fib.c:fib6_locate_1
  - net/ipv6/ip6_fib.c:fib6_node_lookup_1
  - net/ipv6/ip6_fib.c:fib6_node_lookup_1
```
```
In net/ipv6/fib6_rules.c (ffffffff81a49233)
Location: include/net/ipv6.h:598
Inline: True
Inline callers:
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
In net/ipv4/tcp_ipv4.c (ffffffff819d8d8d)
Location: include/net/ipv6.h:598
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:__tcp_md5_do_lookup
```
```
In net/ipv6/addrconf.c (ffffffff81a3ea19)
Location: include/net/ipv6.h:598
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
In net/ipv6/addrlabel.c (ffffffff81a483e3)
Location: include/net/ipv6.h:598
Inline: True
Inline callers:
  - net/ipv6/addrlabel.c:__ipv6_addr_label
```
```
In net/ipv6/ip6_fib.c (ffffffff81a5542a)
Location: include/net/ipv6.h:598
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:fib6_locate_1
  - net/ipv6/ip6_fib.c:fib6_locate_1
  - net/ipv6/ip6_fib.c:fib6_node_lookup_1
  - net/ipv6/ip6_fib.c:fib6_node_lookup_1
```
```
In net/ipv6/fib6_rules.c (ffffffff81a7fe33)
Location: include/net/ipv6.h:598
Inline: True
Inline callers:
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
In net/ipv4/tcp_ipv4.c (ffffffff81ac57ad)
Location: include/net/ipv6.h:598
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:__tcp_md5_do_lookup
```
```
In net/ipv6/addrconf.c (ffffffff81b33f99)
Location: include/net/ipv6.h:598
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
In net/ipv6/addrlabel.c (ffffffff81b3f27f)
Location: include/net/ipv6.h:598
Inline: True
```
```
In net/ipv6/ip6_fib.c (ffffffff81b4be8b)
Location: include/net/ipv6.h:598
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:fib6_locate_1
  - net/ipv6/ip6_fib.c:fib6_locate_1
  - net/ipv6/ip6_fib.c:fib6_node_lookup_1
  - net/ipv6/ip6_fib.c:fib6_node_lookup_1
```
```
In net/ipv6/fib6_rules.c (ffffffff81b7a6f3)
Location: include/net/ipv6.h:598
Inline: True
Inline callers:
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
In net/ipv4/tcp_ipv4.c (ffffffff81ad141d)
Location: include/net/ipv6.h:598
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:__tcp_md5_do_lookup
```
```
In net/ipv6/addrconf.c (ffffffff81b42b1b)
Location: include/net/ipv6.h:598
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
In net/ipv6/addrlabel.c (ffffffff81b4dd0f)
Location: include/net/ipv6.h:598
Inline: True
```
```
In net/ipv6/ip6_fib.c (ffffffff81b5aacb)
Location: include/net/ipv6.h:598
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:fib6_locate_1
  - net/ipv6/ip6_fib.c:fib6_locate_1
  - net/ipv6/ip6_fib.c:fib6_node_lookup_1
  - net/ipv6/ip6_fib.c:fib6_node_lookup_1
```
```
In net/ipv6/fib6_rules.c (ffffffff81b89643)
Location: include/net/ipv6.h:598
Inline: True
Inline callers:
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
In net/ipv4/tcp_ipv4.c (ffffffff81abc40c)
Location: include/net/ipv6.h:599
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:__tcp_md5_do_lookup
```
```
In net/ipv6/addrconf.c (ffffffff81b309ab)
Location: include/net/ipv6.h:599
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
In net/ipv6/addrlabel.c (ffffffff81b3b7b1)
Location: include/net/ipv6.h:599
Inline: True
```
```
In net/ipv6/ip6_fib.c (ffffffff81b48b5b)
Location: include/net/ipv6.h:599
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:fib6_locate_1
  - net/ipv6/ip6_fib.c:fib6_locate_1
  - net/ipv6/ip6_fib.c:fib6_node_lookup_1
  - net/ipv6/ip6_fib.c:fib6_node_lookup_1
```
```
In net/ipv6/fib6_rules.c (ffffffff81b78488)
Location: include/net/ipv6.h:599
Inline: True
Inline callers:
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
In net/ipv4/tcp_ipv4.c (ffffffff81b79533)
Location: include/net/ipv6.h:602
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:__tcp_md5_do_lookup
```
```
In net/ipv6/addrconf.c (ffffffff81bf6eb9)
Location: include/net/ipv6.h:602
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
In net/ipv6/addrlabel.c (ffffffff81c01ffa)
Location: include/net/ipv6.h:602
Inline: True
Inline callers:
  - net/ipv6/addrlabel.c:__ipv6_addr_label
```
```
In net/ipv6/ip6_fib.c (ffffffff81c0ffa7)
Location: include/net/ipv6.h:602
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:fib6_locate_1
  - net/ipv6/ip6_fib.c:fib6_locate_1
  - net/ipv6/ip6_fib.c:fib6_node_lookup_1
  - net/ipv6/ip6_fib.c:fib6_node_lookup_1
```
```
In net/ipv6/fib6_rules.c (ffffffff81c430a2)
Location: include/net/ipv6.h:602
Inline: True
Inline callers:
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
In net/ipv4/tcp_ipv4.c (ffffffff81d0928c)
Location: include/net/ipv6.h:656
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:__tcp_md5_do_lookup
```
```
In net/ipv6/addrconf.c (ffffffff81d90275)
Location: include/net/ipv6.h:656
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
In net/ipv6/addrlabel.c (ffffffff81d9bf38)
Location: include/net/ipv6.h:656
Inline: True
Inline callers:
  - net/ipv6/addrlabel.c:__ipv6_addr_label
```
```
In net/ipv6/ip6_fib.c (ffffffff81dab223)
Location: include/net/ipv6.h:656
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:fib6_locate_1
  - net/ipv6/ip6_fib.c:fib6_locate_1
  - net/ipv6/ip6_fib.c:fib6_node_lookup_1
  - net/ipv6/ip6_fib.c:fib6_node_lookup_1
```
```
In net/ipv6/fib6_rules.c (ffffffff81de1ccf)
Location: include/net/ipv6.h:656
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
In net/ipv4/tcp_ipv4.c (ffffffff81ece44c)
Location: include/net/ipv6.h:689
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:__tcp_md5_do_lookup
```
```
In net/ipv6/addrconf.c (ffffffff81f5e715)
Location: include/net/ipv6.h:689
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
In net/ipv6/addrlabel.c (ffffffff81f6abf8)
Location: include/net/ipv6.h:689
Inline: True
Inline callers:
  - net/ipv6/addrlabel.c:__ipv6_addr_label
```
```
In net/ipv6/ip6_fib.c (ffffffff81f7ab43)
Location: include/net/ipv6.h:689
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:fib6_locate_1
  - net/ipv6/ip6_fib.c:fib6_locate_1
  - net/ipv6/ip6_fib.c:fib6_node_lookup_1
  - net/ipv6/ip6_fib.c:fib6_node_lookup_1
```
```
In net/ipv6/fib6_rules.c (ffffffff81fb41df)
Location: include/net/ipv6.h:689
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
In net/ipv4/tcp_ipv4.c (ffffffff81f2d8ac)
Location: include/net/ipv6.h:690
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:__tcp_md5_do_lookup
```
```
In net/ipv6/addrconf.c (ffffffff81fbe505)
Location: include/net/ipv6.h:690
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
In net/ipv6/addrlabel.c (ffffffff81fcac28)
Location: include/net/ipv6.h:690
Inline: True
Inline callers:
  - net/ipv6/addrlabel.c:__ipv6_addr_label
```
```
In net/ipv6/ip6_fib.c (ffffffff81fdad53)
Location: include/net/ipv6.h:690
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:fib6_locate_1
  - net/ipv6/ip6_fib.c:fib6_locate_1
  - net/ipv6/ip6_fib.c:fib6_node_lookup_1
  - net/ipv6/ip6_fib.c:fib6_node_lookup_1
```
```
In net/ipv6/fib6_rules.c (ffffffff8201497f)
Location: include/net/ipv6.h:690
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
In net/ipv4/tcp_ipv4.c (ffffffff81ff2305)
Location: include/net/ipv6.h:690
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:__tcp_md5_do_lookup
```
```
In net/ipv4/tcp_ao.c (ffffffff820553ad)
Location: include/net/ipv6.h:690
Inline: True
Inline callers:
  - net/ipv4/tcp_ao.c:tcp_ao_verify_ipv6
  - net/ipv4/tcp_ao.c:tcp_ao_verify_ipv6
  - net/ipv4/tcp_ao.c:__tcp_ao_key_cmp
  - net/ipv4/tcp_ao.c:__tcp_ao_key_cmp
```
```
In net/ipv6/addrconf.c (ffffffff8208b995)
Location: include/net/ipv6.h:690
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
In net/ipv6/addrlabel.c (ffffffff820983c8)
Location: include/net/ipv6.h:690
Inline: True
Inline callers:
  - net/ipv6/addrlabel.c:__ipv6_addr_label
```
```
In net/ipv6/ip6_fib.c (ffffffff820a87a3)
Location: include/net/ipv6.h:690
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:fib6_locate_1
  - net/ipv6/ip6_fib.c:fib6_locate_1
  - net/ipv6/ip6_fib.c:fib6_node_lookup_1
  - net/ipv6/ip6_fib.c:fib6_node_lookup_1
```
```
In net/ipv6/fib6_rules.c (ffffffff820e3abf)
Location: include/net/ipv6.h:690
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
In net/ipv4/tcp_ipv4.c (ffff800010c8b49c)
Location: include/net/ipv6.h:598
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:__tcp_md5_do_lookup
```
```
In net/ipv6/addrconf.c (ffff800010d000c4)
Location: include/net/ipv6.h:598
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
In net/ipv6/addrlabel.c (ffff800010d0b708)
Location: include/net/ipv6.h:598
Inline: True
Inline callers:
  - net/ipv6/addrlabel.c:__ipv6_addr_label
```
```
In net/ipv6/ip6_fib.c (ffff800010d19500)
Location: include/net/ipv6.h:598
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:fib6_locate_1
  - net/ipv6/ip6_fib.c:fib6_locate_1
  - net/ipv6/ip6_fib.c:fib6_node_lookup_1
  - net/ipv6/ip6_fib.c:fib6_node_lookup_1
```
```
In net/ipv6/fib6_rules.c (ffff800010d4b058)
Location: include/net/ipv6.h:598
Inline: True
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
In net/ipv4/tcp_ipv4.c (c0d99284)
Location: include/net/ipv6.h:613
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:__tcp_md5_do_lookup
```
```
In net/ipv6/addrconf.c (c0e0830c)
Location: include/net/ipv6.h:613
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:ipv6_chk_prefix
  - net/ipv6/addrconf.c:ipv6_chk_custom_prefix
  - net/ipv6/addrconf.c:check_cleanup_prefix_route
```
```
In net/ipv6/addrlabel.c (c0e112bc)
Location: include/net/ipv6.h:613
Inline: True
Inline callers:
  - net/ipv6/addrlabel.c:__ipv6_addr_label
```
```
In net/ipv6/ip6_fib.c (c0e1f83c)
Location: include/net/ipv6.h:613
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:fib6_locate_1
  - net/ipv6/ip6_fib.c:fib6_node_lookup_1
```
```
In net/ipv6/fib6_rules.c (c0e4c808)
Location: include/net/ipv6.h:613
Inline: True
Inline callers:
  - net/ipv6/fib6_rules.c:fib6_rule_match
  - net/ipv6/fib6_rules.c:fib6_rule_match
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
In net/ipv4/tcp_ipv4.c (c000000000d9a61c)
Location: include/net/ipv6.h:598
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:__tcp_md5_do_lookup
```
```
In net/ipv6/addrconf.c (c000000000e29494)
Location: include/net/ipv6.h:598
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
In net/ipv6/addrlabel.c (c000000000e35e80)
Location: include/net/ipv6.h:598
Inline: True
Inline callers:
  - net/ipv6/addrlabel.c:__ipv6_addr_label
```
```
In net/ipv6/ip6_fib.c (c000000000e475c4)
Location: include/net/ipv6.h:598
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:fib6_locate_1
  - net/ipv6/ip6_fib.c:fib6_locate_1
  - net/ipv6/ip6_fib.c:fib6_node_lookup_1
  - net/ipv6/ip6_fib.c:fib6_node_lookup_1
```
```
In net/ipv6/fib6_rules.c (c000000000e81300)
Location: include/net/ipv6.h:598
Inline: True
Inline callers:
  - net/ipv6/fib6_rules.c:fib6_rule_match
  - net/ipv6/fib6_rules.c:fib6_rule_match
  - net/ipv6/fib6_rules.c:fib6_rule_match
  - net/ipv6/fib6_rules.c:fib6_rule_match
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
In net/ipv4/tcp_ipv4.c (ffffffe0007eaee8)
Location: include/net/ipv6.h:613
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:__tcp_md5_do_lookup
```
```
In net/ipv6/addrconf.c (ffffffe00084a600)
Location: include/net/ipv6.h:613
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:ipv6_chk_prefix
  - net/ipv6/addrconf.c:ipv6_chk_custom_prefix
  - net/ipv6/addrconf.c:check_cleanup_prefix_route
```
```
In net/ipv6/addrlabel.c (ffffffe0008525c0)
Location: include/net/ipv6.h:613
Inline: True
Inline callers:
  - net/ipv6/addrlabel.c:__ipv6_addr_label
```
```
In net/ipv6/ip6_fib.c (ffffffe00085e718)
Location: include/net/ipv6.h:613
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:fib6_locate_1
  - net/ipv6/ip6_fib.c:fib6_node_lookup_1
```
```
In net/ipv6/fib6_rules.c (ffffffe0008840e6)
Location: include/net/ipv6.h:613
Inline: True
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
In net/ipv4/tcp_ipv4.c (ffffffff81978bfd)
Location: include/net/ipv6.h:598
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:__tcp_md5_do_lookup
```
```
In net/ipv6/addrconf.c (ffffffff819de0a9)
Location: include/net/ipv6.h:598
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
In net/ipv6/addrlabel.c (ffffffff819e7a73)
Location: include/net/ipv6.h:598
Inline: True
Inline callers:
  - net/ipv6/addrlabel.c:__ipv6_addr_label
```
```
In net/ipv6/ip6_fib.c (ffffffff819f4aba)
Location: include/net/ipv6.h:598
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:fib6_locate_1
  - net/ipv6/ip6_fib.c:fib6_locate_1
  - net/ipv6/ip6_fib.c:fib6_node_lookup_1
  - net/ipv6/ip6_fib.c:fib6_node_lookup_1
```
```
In net/ipv6/fib6_rules.c (ffffffff81a1f4c3)
Location: include/net/ipv6.h:598
Inline: True
Inline callers:
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
In net/ipv4/tcp_ipv4.c (ffffffff819326bd)
Location: include/net/ipv6.h:598
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:__tcp_md5_do_lookup
```
```
In net/ipv6/addrconf.c (ffffffff8199ae69)
Location: include/net/ipv6.h:598
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
In net/ipv6/addrlabel.c (ffffffff819a4833)
Location: include/net/ipv6.h:598
Inline: True
Inline callers:
  - net/ipv6/addrlabel.c:__ipv6_addr_label
```
```
In net/ipv6/ip6_fib.c (ffffffff819b187a)
Location: include/net/ipv6.h:598
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:fib6_locate_1
  - net/ipv6/ip6_fib.c:fib6_locate_1
  - net/ipv6/ip6_fib.c:fib6_node_lookup_1
  - net/ipv6/ip6_fib.c:fib6_node_lookup_1
```
```
In net/ipv6/fib6_rules.c (ffffffff819dc283)
Location: include/net/ipv6.h:598
Inline: True
Inline callers:
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
In net/ipv4/tcp_ipv4.c (ffffffff819e33cd)
Location: include/net/ipv6.h:598
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:__tcp_md5_do_lookup
```
```
In net/ipv6/addrconf.c (ffffffff81a48b29)
Location: include/net/ipv6.h:598
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
In net/ipv6/addrlabel.c (ffffffff81a524f3)
Location: include/net/ipv6.h:598
Inline: True
Inline callers:
  - net/ipv6/addrlabel.c:__ipv6_addr_label
```
```
In net/ipv6/ip6_fib.c (ffffffff81a5f53a)
Location: include/net/ipv6.h:598
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:fib6_locate_1
  - net/ipv6/ip6_fib.c:fib6_locate_1
  - net/ipv6/ip6_fib.c:fib6_node_lookup_1
  - net/ipv6/ip6_fib.c:fib6_node_lookup_1
```
```
In net/ipv6/fib6_rules.c (ffffffff81a89f43)
Location: include/net/ipv6.h:598
Inline: True
Inline callers:
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
In net/ipv4/tcp_ipv4.c (ffffffff819ed4ed)
Location: include/net/ipv6.h:598
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:__tcp_md5_do_lookup
```
```
In net/ipv6/addrconf.c (ffffffff81a54c88)
Location: include/net/ipv6.h:598
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
In net/ipv6/addrlabel.c (ffffffff81a5e4f3)
Location: include/net/ipv6.h:598
Inline: True
Inline callers:
  - net/ipv6/addrlabel.c:__ipv6_addr_label
```
```
In net/ipv6/ip6_fib.c (ffffffff81a6b9ea)
Location: include/net/ipv6.h:598
Inline: True
Inline callers:
  - net/ipv6/ip6_fib.c:fib6_locate_1
  - net/ipv6/ip6_fib.c:fib6_locate_1
  - net/ipv6/ip6_fib.c:fib6_node_lookup_1
  - net/ipv6/ip6_fib.c:fib6_node_lookup_1
```
```
In net/ipv6/fib6_rules.c (ffffffff81a96ba3)
Location: include/net/ipv6.h:598
Inline: True
Inline callers:
  - net/ipv6/fib6_rules.c:fib6_rule_match
  - net/ipv6/fib6_rules.c:fib6_rule_match
  - net/ipv6/fib6_rules.c:fib6_rule_match
  - net/ipv6/fib6_rules.c:fib6_rule_match
```
</details>
</li>
</ul>

## Differences
