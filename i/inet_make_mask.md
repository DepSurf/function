# Function: <code>inet_make_mask</code>

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
In net/ipv4/devinet.c (ffffffff81791b07)
Location: include/linux/inetdevice.h:245
Inline: True
Inline callers:
  - net/ipv4/devinet.c:inet_rtm_newaddr
  - net/ipv4/devinet.c:devinet_ioctl
```
```
In net/ipv4/fib_trie.c (ffffffff8179f02f)
Location: include/linux/inetdevice.h:245
Inline: True
Inline callers:
  - net/ipv4/fib_trie.c:fib_route_seq_show
```
```
In net/ipv4/fib_rules.c (ffffffff817a6c8b)
Location: include/linux/inetdevice.h:245
Inline: True
Inline callers:
  - net/ipv4/fib_rules.c:fib4_rule_configure
  - net/ipv4/fib_rules.c:fib4_rule_configure
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
In net/ipv4/devinet.c (ffffffff817ff3e1)
Location: include/linux/inetdevice.h:245
Inline: True
Inline callers:
  - net/ipv4/devinet.c:devinet_ioctl
  - net/ipv4/devinet.c:inet_rtm_newaddr
```
```
In net/ipv4/fib_trie.c (ffffffff8180cbf1)
Location: include/linux/inetdevice.h:245
Inline: True
Inline callers:
  - net/ipv4/fib_trie.c:fib_route_seq_show
```
```
In net/ipv4/fib_rules.c (ffffffff81814991)
Location: include/linux/inetdevice.h:245
Inline: True
Inline callers:
  - net/ipv4/fib_rules.c:fib4_rule_configure
  - net/ipv4/fib_rules.c:fib4_rule_configure
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
In net/ipv4/devinet.c (ffffffff81830341)
Location: include/linux/inetdevice.h:245
Inline: True
Inline callers:
  - net/ipv4/devinet.c:devinet_ioctl
  - net/ipv4/devinet.c:inet_rtm_newaddr
```
```
In net/ipv4/fib_trie.c (ffffffff8183de6e)
Location: include/linux/inetdevice.h:245
Inline: True
Inline callers:
  - net/ipv4/fib_trie.c:fib_route_seq_show
```
```
In net/ipv4/fib_rules.c (ffffffff81846130)
Location: include/linux/inetdevice.h:245
Inline: True
Inline callers:
  - net/ipv4/fib_rules.c:fib4_rule_configure
  - net/ipv4/fib_rules.c:fib4_rule_configure
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
In net/ipv4/tcp_ipv4.c (ffffffff81838a20)
Location: include/linux/inetdevice.h:253
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_md5_do_lookup
```
```
In net/ipv4/devinet.c (ffffffff81851840)
Location: include/linux/inetdevice.h:253
Inline: True
Inline callers:
  - net/ipv4/devinet.c:devinet_ioctl
  - net/ipv4/devinet.c:inet_rtm_newaddr
```
```
In net/ipv4/fib_trie.c (ffffffff8185f659)
Location: include/linux/inetdevice.h:253
Inline: True
Inline callers:
  - net/ipv4/fib_trie.c:fib_route_seq_show
```
```
In net/ipv4/fib_rules.c (ffffffff81867cfa)
Location: include/linux/inetdevice.h:253
Inline: True
Inline callers:
  - net/ipv4/fib_rules.c:fib4_rule_configure
  - net/ipv4/fib_rules.c:fib4_rule_configure
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
In net/ipv4/tcp_ipv4.c (ffffffff818b8170)
Location: include/linux/inetdevice.h:256
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_md5_do_lookup
```
```
In net/ipv4/devinet.c (ffffffff818d161a)
Location: include/linux/inetdevice.h:256
Inline: True
Inline callers:
  - net/ipv4/devinet.c:devinet_ioctl
  - net/ipv4/devinet.c:inet_rtm_newaddr
```
```
In net/ipv4/fib_trie.c (ffffffff818df6c9)
Location: include/linux/inetdevice.h:256
Inline: True
Inline callers:
  - net/ipv4/fib_trie.c:fib_route_seq_show
```
```
In net/ipv4/fib_rules.c (ffffffff818e7deb)
Location: include/linux/inetdevice.h:256
Inline: True
Inline callers:
  - net/ipv4/fib_rules.c:fib4_rule_configure
  - net/ipv4/fib_rules.c:fib4_rule_configure
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
In net/ipv4/tcp_ipv4.c (ffffffff8190f938)
Location: include/linux/inetdevice.h:257
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_md5_do_lookup
```
```
In net/ipv4/devinet.c (ffffffff819279fc)
Location: include/linux/inetdevice.h:257
Inline: True
Inline callers:
  - net/ipv4/devinet.c:devinet_ioctl
  - net/ipv4/devinet.c:inet_rtm_newaddr
```
```
In net/ipv4/fib_trie.c (ffffffff81935f5f)
Location: include/linux/inetdevice.h:257
Inline: True
Inline callers:
  - net/ipv4/fib_trie.c:fib_route_seq_show
```
```
In net/ipv4/fib_rules.c (ffffffff8193ea11)
Location: include/linux/inetdevice.h:257
Inline: True
Inline callers:
  - net/ipv4/fib_rules.c:fib4_rule_configure
  - net/ipv4/fib_rules.c:fib4_rule_configure
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
In net/ipv4/tcp_ipv4.c (ffffffff8193dd58)
Location: include/linux/inetdevice.h:260
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:__tcp_md5_do_lookup
```
```
In net/ipv4/devinet.c (ffffffff81956da1)
Location: include/linux/inetdevice.h:260
Inline: True
Inline callers:
  - net/ipv4/devinet.c:devinet_ioctl
  - net/ipv4/devinet.c:devinet_ioctl
  - net/ipv4/devinet.c:inet_rtm_newaddr
  - net/ipv4/devinet.c:inet_rtm_newaddr
```
```
In net/ipv4/fib_trie.c (ffffffff8196595f)
Location: include/linux/inetdevice.h:260
Inline: True
Inline callers:
  - net/ipv4/fib_trie.c:fib_route_seq_show
```
```
In net/ipv4/fib_rules.c (ffffffff8196e8c1)
Location: include/linux/inetdevice.h:260
Inline: True
Inline callers:
  - net/ipv4/fib_rules.c:fib4_rule_configure
  - net/ipv4/fib_rules.c:fib4_rule_configure
  - net/ipv4/fib_rules.c:fib4_rule_configure
  - net/ipv4/fib_rules.c:fib4_rule_configure
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
In net/ipv4/tcp_ipv4.c (ffffffff819a2178)
Location: include/linux/inetdevice.h:273
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:__tcp_md5_do_lookup
```
```
In net/ipv4/devinet.c (ffffffff819bb89d)
Location: include/linux/inetdevice.h:273
Inline: True
Inline callers:
  - net/ipv4/devinet.c:devinet_ioctl
  - net/ipv4/devinet.c:devinet_ioctl
  - net/ipv4/devinet.c:inet_rtm_newaddr
  - net/ipv4/devinet.c:inet_rtm_newaddr
```
```
In net/ipv4/fib_trie.c (ffffffff819cb980)
Location: include/linux/inetdevice.h:273
Inline: True
Inline callers:
  - net/ipv4/fib_trie.c:fib_route_seq_show
```
```
In net/ipv4/fib_rules.c (ffffffff819d80e9)
Location: include/linux/inetdevice.h:273
Inline: True
Inline callers:
  - net/ipv4/fib_rules.c:fib4_rule_configure
  - net/ipv4/fib_rules.c:fib4_rule_configure
  - net/ipv4/fib_rules.c:fib4_rule_configure
  - net/ipv4/fib_rules.c:fib4_rule_configure
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
In net/ipv4/tcp_ipv4.c (ffffffff819d8d48)
Location: include/linux/inetdevice.h:273
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:__tcp_md5_do_lookup
```
```
In net/ipv4/devinet.c (ffffffff819f258d)
Location: include/linux/inetdevice.h:273
Inline: True
Inline callers:
  - net/ipv4/devinet.c:devinet_ioctl
  - net/ipv4/devinet.c:devinet_ioctl
  - net/ipv4/devinet.c:inet_rtm_newaddr
  - net/ipv4/devinet.c:inet_rtm_newaddr
```
```
In net/ipv4/fib_trie.c (ffffffff81a024d0)
Location: include/linux/inetdevice.h:273
Inline: True
Inline callers:
  - net/ipv4/fib_trie.c:fib_route_seq_show
```
```
In net/ipv4/fib_rules.c (ffffffff81a0ebd9)
Location: include/linux/inetdevice.h:273
Inline: True
Inline callers:
  - net/ipv4/fib_rules.c:fib4_rule_configure
  - net/ipv4/fib_rules.c:fib4_rule_configure
  - net/ipv4/fib_rules.c:fib4_rule_configure
  - net/ipv4/fib_rules.c:fib4_rule_configure
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
In net/ipv4/tcp_ipv4.c (ffffffff81ac579a)
Location: include/linux/inetdevice.h:273
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:__tcp_md5_do_lookup
```
```
In net/ipv4/devinet.c (ffffffff81ae06cb)
Location: include/linux/inetdevice.h:273
Inline: True
Inline callers:
  - net/ipv4/devinet.c:devinet_ioctl
  - net/ipv4/devinet.c:rtm_to_ifaddr
  - net/ipv4/devinet.c:rtm_to_ifaddr
```
```
In net/ipv4/fib_trie.c (ffffffff81af1e39)
Location: include/linux/inetdevice.h:273
Inline: True
Inline callers:
  - net/ipv4/fib_trie.c:fib_route_seq_show
```
```
In net/ipv4/fib_rules.c (ffffffff81aff999)
Location: include/linux/inetdevice.h:273
Inline: True
Inline callers:
  - net/ipv4/fib_rules.c:fib4_rule_configure
  - net/ipv4/fib_rules.c:fib4_rule_configure
  - net/ipv4/fib_rules.c:fib4_rule_configure
  - net/ipv4/fib_rules.c:fib4_rule_configure
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
In net/ipv4/tcp_ipv4.c (ffffffff81ad140a)
Location: include/linux/inetdevice.h:273
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:__tcp_md5_do_lookup
```
```
In net/ipv4/devinet.c (ffffffff81aed54b)
Location: include/linux/inetdevice.h:273
Inline: True
Inline callers:
  - net/ipv4/devinet.c:devinet_ioctl
  - net/ipv4/devinet.c:rtm_to_ifaddr
  - net/ipv4/devinet.c:rtm_to_ifaddr
```
```
In net/ipv4/fib_trie.c (ffffffff81afefc9)
Location: include/linux/inetdevice.h:273
Inline: True
Inline callers:
  - net/ipv4/fib_trie.c:fib_route_seq_show
```
```
In net/ipv4/fib_rules.c (ffffffff81b0da19)
Location: include/linux/inetdevice.h:273
Inline: True
Inline callers:
  - net/ipv4/fib_rules.c:fib4_rule_configure
  - net/ipv4/fib_rules.c:fib4_rule_configure
  - net/ipv4/fib_rules.c:fib4_rule_configure
  - net/ipv4/fib_rules.c:fib4_rule_configure
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
In net/ipv4/tcp_ipv4.c (ffffffff81abc3f9)
Location: include/linux/inetdevice.h:273
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:__tcp_md5_do_lookup
```
```
In net/ipv4/devinet.c (ffffffff81ad8fa5)
Location: include/linux/inetdevice.h:273
Inline: True
Inline callers:
  - net/ipv4/devinet.c:devinet_ioctl
  - net/ipv4/devinet.c:devinet_ioctl
  - net/ipv4/devinet.c:rtm_to_ifaddr
  - net/ipv4/devinet.c:rtm_to_ifaddr
```
```
In net/ipv4/fib_trie.c (ffffffff81aea502)
Location: include/linux/inetdevice.h:273
Inline: True
Inline callers:
  - net/ipv4/fib_trie.c:fib_route_seq_show
```
```
In net/ipv4/fib_rules.c (ffffffff81afb809)
Location: include/linux/inetdevice.h:273
Inline: True
Inline callers:
  - net/ipv4/fib_rules.c:fib4_rule_configure
  - net/ipv4/fib_rules.c:fib4_rule_configure
  - net/ipv4/fib_rules.c:fib4_rule_configure
  - net/ipv4/fib_rules.c:fib4_rule_configure
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
In net/ipv4/tcp_ipv4.c (ffffffff81b794fc)
Location: include/linux/inetdevice.h:282
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:__tcp_md5_do_lookup
```
```
In net/ipv4/devinet.c (ffffffff81b9798c)
Location: include/linux/inetdevice.h:282
Inline: True
Inline callers:
  - net/ipv4/devinet.c:devinet_ioctl
  - net/ipv4/devinet.c:devinet_ioctl
  - net/ipv4/devinet.c:rtm_to_ifaddr
  - net/ipv4/devinet.c:rtm_to_ifaddr
```
```
In net/ipv4/fib_trie.c (ffffffff81baa651)
Location: include/linux/inetdevice.h:282
Inline: True
Inline callers:
  - net/ipv4/fib_trie.c:fib_route_seq_show
```
```
In net/ipv4/fib_rules.c (ffffffff81bbcc99)
Location: include/linux/inetdevice.h:282
Inline: True
Inline callers:
  - net/ipv4/fib_rules.c:fib4_rule_configure
  - net/ipv4/fib_rules.c:fib4_rule_configure
  - net/ipv4/fib_rules.c:fib4_rule_configure
  - net/ipv4/fib_rules.c:fib4_rule_configure
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
In net/ipv4/tcp_ipv4.c (ffffffff81d09259)
Location: include/linux/inetdevice.h:287
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:__tcp_md5_do_lookup
```
```
In net/ipv4/devinet.c (ffffffff81d299f5)
Location: include/linux/inetdevice.h:287
Inline: True
Inline callers:
  - net/ipv4/devinet.c:devinet_ioctl
  - net/ipv4/devinet.c:devinet_ioctl
```
```
In net/ipv4/fib_trie.c (ffffffff81d3d2cf)
Location: include/linux/inetdevice.h:287
Inline: True
Inline callers:
  - net/ipv4/fib_trie.c:fib_route_seq_show
```
```
In net/ipv4/fib_rules.c (ffffffff81d512e0)
Location: include/linux/inetdevice.h:287
Inline: True
Inline callers:
  - net/ipv4/fib_rules.c:fib4_rule_configure
  - net/ipv4/fib_rules.c:fib4_rule_configure
  - net/ipv4/fib_rules.c:fib4_rule_configure
  - net/ipv4/fib_rules.c:fib4_rule_configure
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
In net/ipv4/tcp_ipv4.c (ffffffff81ece419)
Location: include/linux/inetdevice.h:287
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:__tcp_md5_do_lookup
```
```
In net/ipv4/devinet.c (ffffffff81ef13ae)
Location: include/linux/inetdevice.h:287
Inline: True
Inline callers:
  - net/ipv4/devinet.c:devinet_ioctl
  - net/ipv4/devinet.c:devinet_ioctl
```
```
In net/ipv4/fib_trie.c (ffffffff81f05f7f)
Location: include/linux/inetdevice.h:287
Inline: True
Inline callers:
  - net/ipv4/fib_trie.c:fib_route_seq_show
```
```
In net/ipv4/fib_rules.c (ffffffff81f1b140)
Location: include/linux/inetdevice.h:287
Inline: True
Inline callers:
  - net/ipv4/fib_rules.c:fib4_rule_configure
  - net/ipv4/fib_rules.c:fib4_rule_configure
  - net/ipv4/fib_rules.c:fib4_rule_configure
  - net/ipv4/fib_rules.c:fib4_rule_configure
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
In net/ipv4/tcp_ipv4.c (ffffffff81f2d879)
Location: include/linux/inetdevice.h:287
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:__tcp_md5_do_lookup
```
```
In net/ipv4/devinet.c (ffffffff81f50df4)
Location: include/linux/inetdevice.h:287
Inline: True
Inline callers:
  - net/ipv4/devinet.c:devinet_ioctl
  - net/ipv4/devinet.c:devinet_ioctl
```
```
In net/ipv4/fib_trie.c (ffffffff81f659df)
Location: include/linux/inetdevice.h:287
Inline: True
Inline callers:
  - net/ipv4/fib_trie.c:fib_route_seq_show
```
```
In net/ipv4/fib_rules.c (ffffffff81f7adae)
Location: include/linux/inetdevice.h:287
Inline: True
Inline callers:
  - net/ipv4/fib_rules.c:fib4_rule_configure
  - net/ipv4/fib_rules.c:fib4_rule_configure
  - net/ipv4/fib_rules.c:fib4_rule_configure
  - net/ipv4/fib_rules.c:fib4_rule_configure
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
In net/ipv4/tcp_ipv4.c (ffffffff81ff237f)
Location: include/linux/inetdevice.h:287
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:__tcp_md5_do_lookup
```
```
In net/ipv4/devinet.c (ffffffff82017074)
Location: include/linux/inetdevice.h:287
Inline: True
Inline callers:
  - net/ipv4/devinet.c:devinet_ioctl
  - net/ipv4/devinet.c:devinet_ioctl
```
```
In net/ipv4/fib_trie.c (ffffffff8202bfb6)
Location: include/linux/inetdevice.h:287
Inline: True
Inline callers:
  - net/ipv4/fib_trie.c:fib_route_seq_show
```
```
In net/ipv4/fib_rules.c (ffffffff820414ae)
Location: include/linux/inetdevice.h:287
Inline: True
Inline callers:
  - net/ipv4/fib_rules.c:fib4_rule_configure
  - net/ipv4/fib_rules.c:fib4_rule_configure
  - net/ipv4/fib_rules.c:fib4_rule_configure
  - net/ipv4/fib_rules.c:fib4_rule_configure
```
```
In net/ipv4/tcp_ao.c (ffffffff82055cc7)
Location: include/linux/inetdevice.h:287
Inline: True
Inline callers:
  - net/ipv4/tcp_ao.c:tcp_ao_copy_mkts_to_user
  - net/ipv4/tcp_ao.c:tcp_ao_copy_mkts_to_user
  - net/ipv4/tcp_ao.c:tcp_ao_copy_mkts_to_user
  - net/ipv4/tcp_ao.c:tcp_ao_copy_mkts_to_user
  - net/ipv4/tcp_ao.c:tcp_ao_add_cmd
  - net/ipv4/tcp_ao.c:tcp_ao_add_cmd
  - net/ipv4/tcp_ao.c:tcp_ao_verify_ipv6
  - net/ipv4/tcp_ao.c:tcp_ao_verify_ipv6
  - net/ipv4/tcp_ao.c:__tcp_ao_key_cmp
  - net/ipv4/tcp_ao.c:__tcp_ao_key_cmp
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
In net/ipv4/tcp_ipv4.c (ffff800010c8b488)
Location: include/linux/inetdevice.h:273
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:__tcp_md5_do_lookup
```
```
In net/ipv4/devinet.c (ffff800010ca8830)
Location: include/linux/inetdevice.h:273
Inline: True
Inline callers:
  - net/ipv4/devinet.c:devinet_ioctl
  - net/ipv4/devinet.c:devinet_ioctl
  - net/ipv4/devinet.c:inet_rtm_newaddr
```
```
In net/ipv4/fib_trie.c (ffff800010cbae64)
Location: include/linux/inetdevice.h:273
Inline: True
Inline callers:
  - net/ipv4/fib_trie.c:fib_route_seq_show
```
```
In net/ipv4/fib_rules.c (ffff800010cc8a04)
Location: include/linux/inetdevice.h:273
Inline: True
Inline callers:
  - net/ipv4/fib_rules.c:fib4_rule_configure
  - net/ipv4/fib_rules.c:fib4_rule_configure
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
In net/ipv4/tcp_ipv4.c (c0d99244)
Location: include/linux/inetdevice.h:273
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:__tcp_md5_do_lookup
```
```
In net/ipv4/devinet.c (c0db4d44)
Location: include/linux/inetdevice.h:273
Inline: True
Inline callers:
  - net/ipv4/devinet.c:devinet_ioctl
  - net/ipv4/devinet.c:devinet_ioctl
  - net/ipv4/devinet.c:inet_rtm_newaddr
  - net/ipv4/devinet.c:inet_rtm_newaddr
```
```
In net/ipv4/fib_trie.c (c0dc6754)
Location: include/linux/inetdevice.h:273
Inline: True
Inline callers:
  - net/ipv4/fib_trie.c:fib_route_seq_show
```
```
In net/ipv4/fib_rules.c (c0dd3dd8)
Location: include/linux/inetdevice.h:273
Inline: True
Inline callers:
  - net/ipv4/fib_rules.c:fib4_rule_configure
  - net/ipv4/fib_rules.c:fib4_rule_configure
  - net/ipv4/fib_rules.c:fib4_rule_configure
  - net/ipv4/fib_rules.c:fib4_rule_configure
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
In net/ipv4/tcp_ipv4.c (c000000000d9a5b0)
Location: include/linux/inetdevice.h:273
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:__tcp_md5_do_lookup
```
```
In net/ipv4/devinet.c (c000000000dbd748)
Location: include/linux/inetdevice.h:273
Inline: True
Inline callers:
  - net/ipv4/devinet.c:devinet_ioctl
  - net/ipv4/devinet.c:devinet_ioctl
  - net/ipv4/devinet.c:inet_rtm_newaddr
  - net/ipv4/devinet.c:inet_rtm_newaddr
```
```
In net/ipv4/fib_trie.c (c000000000dd44b0)
Location: include/linux/inetdevice.h:273
Inline: True
Inline callers:
  - net/ipv4/fib_trie.c:fib_route_seq_show
```
```
In net/ipv4/fib_rules.c (c000000000de5e0c)
Location: include/linux/inetdevice.h:273
Inline: True
Inline callers:
  - net/ipv4/fib_rules.c:fib4_rule_configure
  - net/ipv4/fib_rules.c:fib4_rule_configure
  - net/ipv4/fib_rules.c:fib4_rule_configure
  - net/ipv4/fib_rules.c:fib4_rule_configure
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
In net/ipv4/tcp_ipv4.c (ffffffe0007eaefc)
Location: include/linux/inetdevice.h:273
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:__tcp_md5_do_lookup
```
```
In net/ipv4/devinet.c (ffffffe0008035b8)
Location: include/linux/inetdevice.h:273
Inline: True
Inline callers:
  - net/ipv4/devinet.c:devinet_ioctl
  - net/ipv4/devinet.c:devinet_ioctl
  - net/ipv4/devinet.c:inet_rtm_newaddr
  - net/ipv4/devinet.c:inet_rtm_newaddr
```
```
In net/ipv4/fib_trie.c (ffffffe000811592)
Location: include/linux/inetdevice.h:273
Inline: True
Inline callers:
  - net/ipv4/fib_trie.c:fib_route_seq_show
```
```
In net/ipv4/fib_rules.c (ffffffe00081cc54)
Location: include/linux/inetdevice.h:273
Inline: True
Inline callers:
  - net/ipv4/fib_rules.c:fib4_rule_configure
  - net/ipv4/fib_rules.c:fib4_rule_configure
  - net/ipv4/fib_rules.c:fib4_rule_configure
  - net/ipv4/fib_rules.c:fib4_rule_configure
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
In net/ipv4/tcp_ipv4.c (ffffffff81978bb8)
Location: include/linux/inetdevice.h:273
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:__tcp_md5_do_lookup
```
```
In net/ipv4/devinet.c (ffffffff8199232d)
Location: include/linux/inetdevice.h:273
Inline: True
Inline callers:
  - net/ipv4/devinet.c:devinet_ioctl
  - net/ipv4/devinet.c:devinet_ioctl
  - net/ipv4/devinet.c:inet_rtm_newaddr
  - net/ipv4/devinet.c:inet_rtm_newaddr
```
```
In net/ipv4/fib_trie.c (ffffffff819a2270)
Location: include/linux/inetdevice.h:273
Inline: True
Inline callers:
  - net/ipv4/fib_trie.c:fib_route_seq_show
```
```
In net/ipv4/fib_rules.c (ffffffff819ae979)
Location: include/linux/inetdevice.h:273
Inline: True
Inline callers:
  - net/ipv4/fib_rules.c:fib4_rule_configure
  - net/ipv4/fib_rules.c:fib4_rule_configure
  - net/ipv4/fib_rules.c:fib4_rule_configure
  - net/ipv4/fib_rules.c:fib4_rule_configure
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
In drivers/net/vxlan.c (ffffffff8176ef19)
Location: include/linux/inetdevice.h:273
Inline: True
Inline callers:
  - drivers/net/vxlan.c:vxlan_nl2conf
  - drivers/net/vxlan.c:vxlan_nl2conf
  - drivers/net/vxlan.c:vxlan_nl2conf
  - drivers/net/vxlan.c:vxlan_nl2conf
  - drivers/net/vxlan.c:vxlan_fan_find_map
  - drivers/net/vxlan.c:vxlan_fan_find_map
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81932678)
Location: include/linux/inetdevice.h:273
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:__tcp_md5_do_lookup
```
```
In net/ipv4/devinet.c (ffffffff8194bded)
Location: include/linux/inetdevice.h:273
Inline: True
Inline callers:
  - net/ipv4/devinet.c:devinet_ioctl
  - net/ipv4/devinet.c:devinet_ioctl
  - net/ipv4/devinet.c:inet_rtm_newaddr
  - net/ipv4/devinet.c:inet_rtm_newaddr
```
```
In net/ipv4/fib_trie.c (ffffffff8195bd30)
Location: include/linux/inetdevice.h:273
Inline: True
Inline callers:
  - net/ipv4/fib_trie.c:fib_route_seq_show
```
```
In net/ipv4/fib_rules.c (ffffffff8196afa9)
Location: include/linux/inetdevice.h:273
Inline: True
Inline callers:
  - net/ipv4/fib_rules.c:fib4_rule_configure
  - net/ipv4/fib_rules.c:fib4_rule_configure
  - net/ipv4/fib_rules.c:fib4_rule_configure
  - net/ipv4/fib_rules.c:fib4_rule_configure
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
In net/ipv4/tcp_ipv4.c (ffffffff819e3388)
Location: include/linux/inetdevice.h:273
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:__tcp_md5_do_lookup
```
```
In net/ipv4/devinet.c (ffffffff819fcbcd)
Location: include/linux/inetdevice.h:273
Inline: True
Inline callers:
  - net/ipv4/devinet.c:devinet_ioctl
  - net/ipv4/devinet.c:devinet_ioctl
  - net/ipv4/devinet.c:inet_rtm_newaddr
  - net/ipv4/devinet.c:inet_rtm_newaddr
```
```
In net/ipv4/fib_trie.c (ffffffff81a0cb10)
Location: include/linux/inetdevice.h:273
Inline: True
Inline callers:
  - net/ipv4/fib_trie.c:fib_route_seq_show
```
```
In net/ipv4/fib_rules.c (ffffffff81a19219)
Location: include/linux/inetdevice.h:273
Inline: True
Inline callers:
  - net/ipv4/fib_rules.c:fib4_rule_configure
  - net/ipv4/fib_rules.c:fib4_rule_configure
  - net/ipv4/fib_rules.c:fib4_rule_configure
  - net/ipv4/fib_rules.c:fib4_rule_configure
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
In net/ipv4/tcp_ipv4.c (ffffffff819ed4a8)
Location: include/linux/inetdevice.h:273
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:__tcp_md5_do_lookup
```
```
In net/ipv4/devinet.c (ffffffff81a06f5d)
Location: include/linux/inetdevice.h:273
Inline: True
Inline callers:
  - net/ipv4/devinet.c:devinet_ioctl
  - net/ipv4/devinet.c:devinet_ioctl
  - net/ipv4/devinet.c:inet_rtm_newaddr
  - net/ipv4/devinet.c:inet_rtm_newaddr
```
```
In net/ipv4/fib_trie.c (ffffffff81a172e0)
Location: include/linux/inetdevice.h:273
Inline: True
Inline callers:
  - net/ipv4/fib_trie.c:fib_route_seq_show
```
```
In net/ipv4/fib_rules.c (ffffffff81a23cb9)
Location: include/linux/inetdevice.h:273
Inline: True
Inline callers:
  - net/ipv4/fib_rules.c:fib4_rule_configure
  - net/ipv4/fib_rules.c:fib4_rule_configure
  - net/ipv4/fib_rules.c:fib4_rule_configure
  - net/ipv4/fib_rules.c:fib4_rule_configure
```
</details>
</li>
</ul>

## Differences
