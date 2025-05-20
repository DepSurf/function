# Function: <code>ipv4_is_zeronet</code>

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
In net/ipv4/route.c (ffffffff81755810)
Location: include/linux/in.h:63
Inline: True
```
```
In net/ipv4/devinet.c (ffffffff817925c1)
Location: include/linux/in.h:63
Inline: True
Inline callers:
  - net/ipv4/devinet.c:devinet_ioctl
```
```
In net/ipv4/fib_frontend.c (0)
Location: include/linux/in.h:63
Inline: True
```
```
In net/ipv6/addrconf.c (ffffffff817c91d1)
Location: include/linux/in.h:63
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:__ipv6_isatap_ifid
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
In net/ipv4/route.c (ffffffff817c19ab)
Location: include/linux/in.h:63
Inline: True
```
```
In net/ipv4/devinet.c (ffffffff817ff3c8)
Location: include/linux/in.h:63
Inline: True
Inline callers:
  - net/ipv4/devinet.c:devinet_ioctl
```
```
In net/ipv4/fib_frontend.c (0)
Location: include/linux/in.h:63
Inline: True
```
```
In net/ipv6/addrconf.c (ffffffff818363b1)
Location: include/linux/in.h:63
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:__ipv6_isatap_ifid
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
In net/ipv4/route.c (ffffffff817f1faa)
Location: include/linux/in.h:63
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_route_input_noref
  - net/ipv4/route.c:ip_route_input_noref
```
```
In net/ipv4/devinet.c (ffffffff81830328)
Location: include/linux/in.h:63
Inline: True
Inline callers:
  - net/ipv4/devinet.c:devinet_ioctl
```
```
In net/ipv4/fib_frontend.c (0)
Location: include/linux/in.h:63
Inline: True
```
```
In net/ipv6/addrconf.c (ffffffff81867ec1)
Location: include/linux/in.h:63
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:__ipv6_isatap_ifid
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
In net/ipv4/route.c (0)
Location: include/linux/in.h:63
Inline: True
```
```
In net/ipv4/devinet.c (0)
Location: include/linux/in.h:63
Inline: True
```
```
In net/ipv4/fib_frontend.c (0)
Location: include/linux/in.h:63
Inline: True
```
```
In net/ipv6/addrconf.c (ffffffff8188c7b1)
Location: include/linux/in.h:63
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:__ipv6_isatap_ifid
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
In net/ipv4/route.c (0)
Location: include/linux/in.h:63
Inline: True
```
```
In net/ipv4/devinet.c (0)
Location: include/linux/in.h:63
Inline: True
```
```
In net/ipv4/fib_frontend.c (0)
Location: include/linux/in.h:63
Inline: True
```
```
In net/ipv6/addrconf.c (ffffffff8190db41)
Location: include/linux/in.h:63
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:__ipv6_isatap_ifid
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
In net/ipv4/route.c (ffffffff818e58fb)
Location: include/linux/in.h:63
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:__ip_do_redirect
```
```
In net/ipv4/devinet.c (ffffffff81927972)
Location: include/linux/in.h:63
Inline: True
Inline callers:
  - net/ipv4/devinet.c:devinet_ioctl
  - net/ipv4/devinet.c:devinet_ioctl
  - net/ipv4/devinet.c:devinet_ioctl
```
```
In net/ipv4/fib_frontend.c (ffffffff819329ee)
Location: include/linux/in.h:63
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:fib_del_ifaddr
  - net/ipv4/fib_frontend.c:fib_del_ifaddr
  - net/ipv4/fib_frontend.c:fib_modify_prefix_metric
  - net/ipv4/fib_frontend.c:fib_add_ifaddr
  - net/ipv4/fib_frontend.c:fib_compute_spec_dst
  - net/ipv4/fib_frontend.c:inet_addr_type_dev_table
  - net/ipv4/fib_frontend.c:inet_dev_addr_type
  - net/ipv4/fib_frontend.c:inet_addr_type
```
```
In net/ipv6/addrconf.c (ffffffff81964e11)
Location: include/linux/in.h:63
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:__ipv6_isatap_ifid
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
In net/ipv4/route.c (ffffffff8191280b)
Location: include/linux/in.h:63
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:__ip_do_redirect
```
```
In net/ipv4/devinet.c (ffffffff81956d09)
Location: include/linux/in.h:63
Inline: True
Inline callers:
  - net/ipv4/devinet.c:devinet_ioctl
  - net/ipv4/devinet.c:devinet_ioctl
  - net/ipv4/devinet.c:devinet_ioctl
```
```
In net/ipv4/fib_frontend.c (ffffffff8196227e)
Location: include/linux/in.h:63
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:fib_del_ifaddr
  - net/ipv4/fib_frontend.c:fib_del_ifaddr
  - net/ipv4/fib_frontend.c:fib_modify_prefix_metric
  - net/ipv4/fib_frontend.c:fib_add_ifaddr
  - net/ipv4/fib_frontend.c:fib_compute_spec_dst
  - net/ipv4/fib_frontend.c:inet_addr_type_dev_table
  - net/ipv4/fib_frontend.c:inet_dev_addr_type
  - net/ipv4/fib_frontend.c:inet_addr_type
```
```
In net/ipv6/addrconf.c (ffffffff8199a291)
Location: include/linux/in.h:63
Inline: True
Inline callers:
  - net/ipv6/addrconf.c:__ipv6_isatap_ifid
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
In net/ipv4/route.c (0)
Location: include/linux/in.h:64
Inline: True
```
```
In net/ipv4/devinet.c (0)
Location: include/linux/in.h:64
Inline: True
```
```
In net/ipv4/fib_frontend.c (0)
Location: include/linux/in.h:64
Inline: True
```
```
In net/ipv6/addrconf.c (0)
Location: include/linux/in.h:64
Inline: True
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
In net/ipv4/route.c (0)
Location: include/linux/in.h:64
Inline: True
```
```
In net/ipv4/devinet.c (0)
Location: include/linux/in.h:64
Inline: True
```
```
In net/ipv4/fib_frontend.c (0)
Location: include/linux/in.h:64
Inline: True
```
```
In net/ipv6/addrconf.c (0)
Location: include/linux/in.h:64
Inline: True
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
In net/ipv4/route.c (0)
Location: include/linux/in.h:64
Inline: True
```
```
In net/ipv4/devinet.c (0)
Location: include/linux/in.h:64
Inline: True
```
```
In net/ipv4/fib_frontend.c (0)
Location: include/linux/in.h:64
Inline: True
```
```
In net/ipv6/addrconf.c (0)
Location: include/linux/in.h:64
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
In net/ipv4/route.c (0)
Location: include/linux/in.h:64
Inline: True
```
```
In net/ipv4/devinet.c (0)
Location: include/linux/in.h:64
Inline: True
```
```
In net/ipv4/fib_frontend.c (0)
Location: include/linux/in.h:64
Inline: True
```
```
In net/ipv4/ip_tunnel_core.c (0)
Location: include/linux/in.h:64
Inline: True
```
```
In net/ipv6/addrconf.c (0)
Location: include/linux/in.h:64
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
In net/ipv4/route.c (0)
Location: include/linux/in.h:64
Inline: True
```
```
In net/ipv4/devinet.c (0)
Location: include/linux/in.h:64
Inline: True
```
```
In net/ipv4/fib_frontend.c (0)
Location: include/linux/in.h:64
Inline: True
```
```
In net/ipv4/ip_tunnel_core.c (0)
Location: include/linux/in.h:64
Inline: True
```
```
In net/ipv6/addrconf.c (0)
Location: include/linux/in.h:64
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
In net/ipv4/route.c (0)
Location: include/linux/in.h:64
Inline: True
```
```
In net/ipv4/devinet.c (0)
Location: include/linux/in.h:64
Inline: True
```
```
In net/ipv4/fib_frontend.c (0)
Location: include/linux/in.h:64
Inline: True
```
```
In net/ipv4/ip_tunnel_core.c (0)
Location: include/linux/in.h:64
Inline: True
```
```
In net/ipv6/addrconf.c (0)
Location: include/linux/in.h:64
Inline: True
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
In net/ipv4/route.c (0)
Location: include/linux/in.h:64
Inline: True
```
```
In net/ipv4/devinet.c (0)
Location: include/linux/in.h:64
Inline: True
```
```
In net/ipv4/fib_frontend.c (0)
Location: include/linux/in.h:64
Inline: True
```
```
In net/ipv4/ip_tunnel_core.c (0)
Location: include/linux/in.h:64
Inline: True
```
```
In net/ipv6/addrconf.c (0)
Location: include/linux/in.h:64
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
In net/ipv4/route.c (0)
Location: include/linux/in.h:64
Inline: True
```
```
In net/ipv4/devinet.c (0)
Location: include/linux/in.h:64
Inline: True
```
```
In net/ipv4/fib_frontend.c (0)
Location: include/linux/in.h:64
Inline: True
```
```
In net/ipv4/ip_tunnel_core.c (0)
Location: include/linux/in.h:64
Inline: True
```
```
In net/ipv6/addrconf.c (0)
Location: include/linux/in.h:64
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
In net/core/rtnetlink.c (0)
Location: include/linux/in.h:64
Inline: True
```
```
In net/ipv4/route.c (0)
Location: include/linux/in.h:64
Inline: True
```
```
In net/ipv4/devinet.c (0)
Location: include/linux/in.h:64
Inline: True
```
```
In net/ipv4/fib_frontend.c (0)
Location: include/linux/in.h:64
Inline: True
```
```
In net/ipv4/ip_tunnel_core.c (0)
Location: include/linux/in.h:64
Inline: True
```
```
In net/ipv6/addrconf.c (0)
Location: include/linux/in.h:64
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
In net/core/rtnetlink.c (0)
Location: include/linux/in.h:64
Inline: True
```
```
In net/ipv4/route.c (0)
Location: include/linux/in.h:64
Inline: True
```
```
In net/ipv4/devinet.c (0)
Location: include/linux/in.h:64
Inline: True
```
```
In net/ipv4/fib_frontend.c (0)
Location: include/linux/in.h:64
Inline: True
```
```
In net/ipv4/ip_tunnel_core.c (0)
Location: include/linux/in.h:64
Inline: True
```
```
In net/ipv6/addrconf.c (0)
Location: include/linux/in.h:64
Inline: True
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
In net/ipv4/route.c (0)
Location: include/linux/in.h:64
Inline: True
```
```
In net/ipv4/devinet.c (0)
Location: include/linux/in.h:64
Inline: True
```
```
In net/ipv4/fib_frontend.c (0)
Location: include/linux/in.h:64
Inline: True
```
```
In net/ipv6/addrconf.c (0)
Location: include/linux/in.h:64
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
In net/ipv4/route.c (0)
Location: include/linux/in.h:64
Inline: True
```
```
In net/ipv4/devinet.c (0)
Location: include/linux/in.h:64
Inline: True
```
```
In net/ipv4/fib_frontend.c (0)
Location: include/linux/in.h:64
Inline: True
```
```
In net/ipv6/addrconf.c (0)
Location: include/linux/in.h:64
Inline: True
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
In net/ipv4/route.c (0)
Location: include/linux/in.h:64
Inline: True
```
```
In net/ipv4/devinet.c (0)
Location: include/linux/in.h:64
Inline: True
```
```
In net/ipv4/fib_frontend.c (0)
Location: include/linux/in.h:64
Inline: True
```
```
In net/ipv6/addrconf.c (0)
Location: include/linux/in.h:64
Inline: True
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
In net/ipv4/route.c (0)
Location: include/linux/in.h:64
Inline: True
```
```
In net/ipv4/devinet.c (0)
Location: include/linux/in.h:64
Inline: True
```
```
In net/ipv4/fib_frontend.c (0)
Location: include/linux/in.h:64
Inline: True
```
```
In net/ipv6/addrconf.c (0)
Location: include/linux/in.h:64
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
In net/ipv4/route.c (0)
Location: include/linux/in.h:64
Inline: True
```
```
In net/ipv4/devinet.c (0)
Location: include/linux/in.h:64
Inline: True
```
```
In net/ipv4/fib_frontend.c (0)
Location: include/linux/in.h:64
Inline: True
```
```
In net/ipv6/addrconf.c (0)
Location: include/linux/in.h:64
Inline: True
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
In net/ipv4/route.c (0)
Location: include/linux/in.h:64
Inline: True
```
```
In net/ipv4/devinet.c (0)
Location: include/linux/in.h:64
Inline: True
```
```
In net/ipv4/fib_frontend.c (0)
Location: include/linux/in.h:64
Inline: True
```
```
In net/ipv6/addrconf.c (0)
Location: include/linux/in.h:64
Inline: True
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
In net/ipv4/route.c (0)
Location: include/linux/in.h:64
Inline: True
```
```
In net/ipv4/devinet.c (0)
Location: include/linux/in.h:64
Inline: True
```
```
In net/ipv4/fib_frontend.c (0)
Location: include/linux/in.h:64
Inline: True
```
```
In net/ipv6/addrconf.c (0)
Location: include/linux/in.h:64
Inline: True
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
In net/ipv4/route.c (0)
Location: include/linux/in.h:64
Inline: True
```
```
In net/ipv4/devinet.c (0)
Location: include/linux/in.h:64
Inline: True
```
```
In net/ipv4/fib_frontend.c (0)
Location: include/linux/in.h:64
Inline: True
```
```
In net/ipv6/addrconf.c (0)
Location: include/linux/in.h:64
Inline: True
```
</details>
</li>
</ul>

## Differences
