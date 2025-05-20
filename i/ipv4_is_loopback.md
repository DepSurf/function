# Function: <code>ipv4_is_loopback</code>

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
In net/ipv4/route.c (ffffffff817556ea)
Location: include/linux/in.h:42
Inline: True
```
```
In net/ipv4/arp.c (0)
Location: include/linux/in.h:42
Inline: True
```
```
In net/ipv4/devinet.c (0)
Location: include/linux/in.h:42
Inline: True
```
```
In net/ipv6/addrconf.c (0)
Location: include/linux/in.h:42
Inline: True
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
In net/ipv4/route.c (ffffffff817c25d1)
Location: include/linux/in.h:42
Inline: True
Inline callers:
  - net/ipv4/route.c:__ip_route_output_key_hash
```
```
In net/ipv4/arp.c (0)
Location: include/linux/in.h:42
Inline: True
```
```
In net/ipv4/devinet.c (0)
Location: include/linux/in.h:42
Inline: True
```
```
In net/ipv6/addrconf.c (0)
Location: include/linux/in.h:42
Inline: True
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
In net/ipv4/route.c (ffffffff817f0c83)
Location: include/linux/in.h:42
Inline: True
Inline callers:
  - net/ipv4/route.c:__ip_route_output_key_hash
  - net/ipv4/route.c:ip_route_input_noref
```
```
In net/ipv4/arp.c (0)
Location: include/linux/in.h:42
Inline: True
```
```
In net/ipv4/devinet.c (0)
Location: include/linux/in.h:42
Inline: True
```
```
In net/ipv6/addrconf.c (0)
Location: include/linux/in.h:42
Inline: True
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
In net/ipv4/route.c (ffffffff818115d9)
Location: include/linux/in.h:42
Inline: True
```
```
In net/ipv4/arp.c (0)
Location: include/linux/in.h:42
Inline: True
```
```
In net/ipv4/devinet.c (0)
Location: include/linux/in.h:42
Inline: True
```
```
In net/ipv6/addrconf.c (0)
Location: include/linux/in.h:42
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
In net/ipv4/route.c (ffffffff81890aef)
Location: include/linux/in.h:42
Inline: True
```
```
In net/ipv4/arp.c (0)
Location: include/linux/in.h:42
Inline: True
```
```
In net/ipv4/devinet.c (0)
Location: include/linux/in.h:42
Inline: True
```
```
In net/ipv6/addrconf.c (0)
Location: include/linux/in.h:42
Inline: True
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
In net/ipv4/route.c (ffffffff818e599c)
Location: include/linux/in.h:42
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
```
```
In net/ipv4/tcp_ipv4.c (ffffffff8190da54)
Location: include/linux/in.h:42
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_twsk_unique
  - net/ipv4/tcp_ipv4.c:tcp_twsk_unique
```
```
In net/ipv4/arp.c (ffffffff819226a0)
Location: include/linux/in.h:42
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_process
```
```
In net/ipv4/devinet.c (ffffffff81927aba)
Location: include/linux/in.h:42
Inline: True
Inline callers:
  - net/ipv4/devinet.c:devinet_ioctl
```
```
In net/ipv6/addrconf.c (0)
Location: include/linux/in.h:42
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
In net/ipv4/route.c (ffffffff819128ac)
Location: include/linux/in.h:42
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
```
```
In net/ipv4/tcp_ipv4.c (ffffffff8193be34)
Location: include/linux/in.h:42
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_twsk_unique
  - net/ipv4/tcp_ipv4.c:tcp_twsk_unique
```
```
In net/ipv4/arp.c (ffffffff819514be)
Location: include/linux/in.h:42
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_process
```
```
In net/ipv4/devinet.c (ffffffff81956e42)
Location: include/linux/in.h:42
Inline: True
Inline callers:
  - net/ipv4/devinet.c:devinet_ioctl
```
```
In net/ipv6/addrconf.c (0)
Location: include/linux/in.h:42
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
In net/ipv4/route.c (ffffffff81974fbf)
Location: include/linux/in.h:38
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_mc_validate_source
```
```
In net/ipv4/tcp_ipv4.c (ffffffff819a0258)
Location: include/linux/in.h:38
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_twsk_unique
  - net/ipv4/tcp_ipv4.c:tcp_twsk_unique
```
```
In net/ipv4/arp.c (ffffffff819b5d75)
Location: include/linux/in.h:38
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_process
```
```
In net/ipv4/devinet.c (ffffffff819bb945)
Location: include/linux/in.h:38
Inline: True
Inline callers:
  - net/ipv4/devinet.c:devinet_ioctl
```
```
In net/ipv6/addrconf.c (0)
Location: include/linux/in.h:38
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
In net/ipv4/route.c (ffffffff819ab9df)
Location: include/linux/in.h:38
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_mc_validate_source
```
```
In net/ipv4/tcp_ipv4.c (ffffffff819d6e18)
Location: include/linux/in.h:38
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_twsk_unique
  - net/ipv4/tcp_ipv4.c:tcp_twsk_unique
```
```
In net/ipv4/arp.c (ffffffff819eca95)
Location: include/linux/in.h:38
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_process
```
```
In net/ipv4/devinet.c (ffffffff819f2635)
Location: include/linux/in.h:38
Inline: True
Inline callers:
  - net/ipv4/devinet.c:devinet_ioctl
```
```
In net/ipv6/addrconf.c (0)
Location: include/linux/in.h:38
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
In net/ipv4/route.c (ffffffff81a93bc9)
Location: include/linux/in.h:38
Inline: True
Inline callers:
  - net/ipv4/route.c:__mkroute_output
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_route_use_hint
  - net/ipv4/route.c:ip_mc_validate_source
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81ac6cca)
Location: include/linux/in.h:38
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_twsk_unique
  - net/ipv4/tcp_ipv4.c:tcp_twsk_unique
  - net/ipv4/tcp_ipv4.c:tcp_twsk_unique
  - net/ipv4/tcp_ipv4.c:tcp_twsk_unique
```
```
In net/ipv4/arp.c (ffffffff81ada9df)
Location: include/linux/in.h:38
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_process
```
```
In net/ipv4/devinet.c (ffffffff81adfa06)
Location: include/linux/in.h:38
Inline: True
```
```
In net/ipv6/addrconf.c (0)
Location: include/linux/in.h:38
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
In net/ipv4/route.c (ffffffff81a9da78)
Location: include/linux/in.h:38
Inline: True
Inline callers:
  - net/ipv4/route.c:__mkroute_output
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_route_use_hint
  - net/ipv4/route.c:ip_mc_validate_source
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81ad1fea)
Location: include/linux/in.h:38
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_twsk_unique
  - net/ipv4/tcp_ipv4.c:tcp_twsk_unique
  - net/ipv4/tcp_ipv4.c:tcp_twsk_unique
  - net/ipv4/tcp_ipv4.c:tcp_twsk_unique
```
```
In net/ipv4/arp.c (ffffffff81ae747f)
Location: include/linux/in.h:38
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_process
```
```
In net/ipv4/devinet.c (ffffffff81aec176)
Location: include/linux/in.h:38
Inline: True
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff81b06d5b)
Location: include/linux/in.h:38
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:skb_tunnel_check_pmtu
```
```
In net/ipv6/addrconf.c (0)
Location: include/linux/in.h:38
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
In net/ipv4/route.c (ffffffff81a88a14)
Location: include/linux/in.h:38
Inline: True
Inline callers:
  - net/ipv4/route.c:__mkroute_output
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_route_use_hint
  - net/ipv4/route.c:ip_mc_validate_source
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81abd125)
Location: include/linux/in.h:38
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_twsk_unique
  - net/ipv4/tcp_ipv4.c:tcp_twsk_unique
  - net/ipv4/tcp_ipv4.c:tcp_twsk_unique
  - net/ipv4/tcp_ipv4.c:tcp_twsk_unique
```
```
In net/ipv4/arp.c (ffffffff81ad273f)
Location: include/linux/in.h:38
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_process
```
```
In net/ipv4/devinet.c (ffffffff81ad77e6)
Location: include/linux/in.h:38
Inline: True
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff81af249d)
Location: include/linux/in.h:38
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:skb_tunnel_check_pmtu
```
```
In net/ipv6/addrconf.c (0)
Location: include/linux/in.h:38
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
In net/ipv4/route.c (ffffffff81b43184)
Location: include/linux/in.h:38
Inline: True
Inline callers:
  - net/ipv4/route.c:__mkroute_output
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_route_use_hint
  - net/ipv4/route.c:ip_mc_validate_source
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81b7b245)
Location: include/linux/in.h:38
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_twsk_unique
  - net/ipv4/tcp_ipv4.c:tcp_twsk_unique
  - net/ipv4/tcp_ipv4.c:tcp_twsk_unique
  - net/ipv4/tcp_ipv4.c:tcp_twsk_unique
```
```
In net/ipv4/arp.c (ffffffff81b9138f)
Location: include/linux/in.h:38
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_process
```
```
In net/ipv4/devinet.c (ffffffff81b96d28)
Location: include/linux/in.h:38
Inline: True
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff81bb29ad)
Location: include/linux/in.h:38
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:skb_tunnel_check_pmtu
```
```
In net/ipv6/addrconf.c (0)
Location: include/linux/in.h:38
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
In net/ipv4/route.c (ffffffff81ccfc16)
Location: include/linux/in.h:38
Inline: True
Inline callers:
  - net/ipv4/route.c:__mkroute_output
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_route_use_hint
  - net/ipv4/route.c:ip_mc_validate_source
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81d0a981)
Location: include/linux/in.h:38
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_twsk_unique
  - net/ipv4/tcp_ipv4.c:tcp_twsk_unique
  - net/ipv4/tcp_ipv4.c:tcp_twsk_unique
  - net/ipv4/tcp_ipv4.c:tcp_twsk_unique
```
```
In net/ipv4/arp.c (ffffffff81d2276c)
Location: include/linux/in.h:38
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_process
```
```
In net/ipv4/devinet.c (ffffffff81d28dac)
Location: include/linux/in.h:38
Inline: True
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff81d46184)
Location: include/linux/in.h:38
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:skb_tunnel_check_pmtu
```
```
In net/ipv6/addrconf.c (0)
Location: include/linux/in.h:38
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
In net/ipv4/route.c (ffffffff81e8fe30)
Location: include/linux/in.h:38
Inline: True
Inline callers:
  - net/ipv4/route.c:__mkroute_output
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_route_use_hint
  - net/ipv4/route.c:ip_mc_validate_source
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81ed0231)
Location: include/linux/in.h:38
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_twsk_unique
  - net/ipv4/tcp_ipv4.c:tcp_twsk_unique
  - net/ipv4/tcp_ipv4.c:tcp_twsk_unique
  - net/ipv4/tcp_ipv4.c:tcp_twsk_unique
```
```
In net/ipv4/arp.c (ffffffff81ee9c39)
Location: include/linux/in.h:38
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_process
```
```
In net/ipv4/devinet.c (ffffffff81ef1472)
Location: include/linux/in.h:38
Inline: True
Inline callers:
  - net/ipv4/devinet.c:devinet_ioctl
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff81f0f564)
Location: include/linux/in.h:38
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:skb_tunnel_check_pmtu
```
```
In net/ipv6/addrconf.c (0)
Location: include/linux/in.h:38
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
In net/ipv4/route.c (ffffffff81eee543)
Location: include/linux/in.h:38
Inline: True
Inline callers:
  - net/ipv4/route.c:__mkroute_output
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_route_use_hint
  - net/ipv4/route.c:ip_mc_validate_source
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81f2eee1)
Location: include/linux/in.h:38
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_twsk_unique
  - net/ipv4/tcp_ipv4.c:tcp_twsk_unique
  - net/ipv4/tcp_ipv4.c:tcp_twsk_unique
  - net/ipv4/tcp_ipv4.c:tcp_twsk_unique
```
```
In net/ipv4/arp.c (ffffffff81f4959f)
Location: include/linux/in.h:38
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_process
```
```
In net/ipv4/devinet.c (ffffffff81f50eb2)
Location: include/linux/in.h:38
Inline: True
Inline callers:
  - net/ipv4/devinet.c:devinet_ioctl
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff81f6f254)
Location: include/linux/in.h:38
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:skb_tunnel_check_pmtu
```
```
In net/ipv6/addrconf.c (0)
Location: include/linux/in.h:38
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
In net/ipv4/route.c (ffffffff81fb26a3)
Location: include/linux/in.h:38
Inline: True
Inline callers:
  - net/ipv4/route.c:__mkroute_output
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_route_use_hint
  - net/ipv4/route.c:ip_mc_validate_source
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81ff4431)
Location: include/linux/in.h:38
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_twsk_unique
  - net/ipv4/tcp_ipv4.c:tcp_twsk_unique
  - net/ipv4/tcp_ipv4.c:tcp_twsk_unique
  - net/ipv4/tcp_ipv4.c:tcp_twsk_unique
```
```
In net/ipv4/arp.c (ffffffff8200f711)
Location: include/linux/in.h:38
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_process
```
```
In net/ipv4/devinet.c (ffffffff82017132)
Location: include/linux/in.h:38
Inline: True
Inline callers:
  - net/ipv4/devinet.c:devinet_ioctl
```
```
In net/ipv4/ip_tunnel_core.c (ffffffff82035984)
Location: include/linux/in.h:38
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:skb_tunnel_check_pmtu
```
```
In net/ipv6/addrconf.c (0)
Location: include/linux/in.h:38
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
In net/ipv4/route.c (ffff800010c5bb88)
Location: include/linux/in.h:38
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_mc_validate_source
```
```
In net/ipv4/tcp_ipv4.c (ffff800010c89e0c)
Location: include/linux/in.h:38
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_twsk_unique
  - net/ipv4/tcp_ipv4.c:tcp_twsk_unique
```
```
In net/ipv4/arp.c (ffff800010ca25bc)
Location: include/linux/in.h:38
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_process
```
```
In net/ipv4/devinet.c (ffff800010ca88ac)
Location: include/linux/in.h:38
Inline: True
Inline callers:
  - net/ipv4/devinet.c:devinet_ioctl
```
```
In net/ipv6/addrconf.c (0)
Location: include/linux/in.h:38
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
In net/ipv4/route.c (c0d6b1c4)
Location: include/linux/in.h:38
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_mc_validate_source
```
```
In net/ipv4/tcp_ipv4.c (c0d98f10)
Location: include/linux/in.h:38
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_twsk_unique
  - net/ipv4/tcp_ipv4.c:tcp_twsk_unique
```
```
In net/ipv4/arp.c (c0daf3c4)
Location: include/linux/in.h:38
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_process
```
```
In net/ipv4/devinet.c (c0db4e10)
Location: include/linux/in.h:38
Inline: True
Inline callers:
  - net/ipv4/devinet.c:devinet_ioctl
```
```
In net/ipv6/addrconf.c (0)
Location: include/linux/in.h:38
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
In net/ipv4/route.c (c000000000d5dd34)
Location: include/linux/in.h:38
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_mc_validate_source
```
```
In net/ipv4/tcp_ipv4.c (c000000000d973bc)
Location: include/linux/in.h:38
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_twsk_unique
  - net/ipv4/tcp_ipv4.c:tcp_twsk_unique
```
```
In net/ipv4/arp.c (c000000000db5ba0)
Location: include/linux/in.h:38
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_process
```
```
In net/ipv4/devinet.c (c000000000dbd810)
Location: include/linux/in.h:38
Inline: True
Inline callers:
  - net/ipv4/devinet.c:devinet_ioctl
```
```
In net/ipv6/addrconf.c (0)
Location: include/linux/in.h:38
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
In net/ipv4/route.c (ffffffe0007c4d52)
Location: include/linux/in.h:38
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_mc_validate_source
```
```
In net/ipv4/tcp_ipv4.c (ffffffe0007eabbc)
Location: include/linux/in.h:38
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_twsk_unique
  - net/ipv4/tcp_ipv4.c:tcp_twsk_unique
```
```
In net/ipv4/arp.c (ffffffe0007fe452)
Location: include/linux/in.h:38
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_process
```
```
In net/ipv4/devinet.c (ffffffe0008036a4)
Location: include/linux/in.h:38
Inline: True
Inline callers:
  - net/ipv4/devinet.c:devinet_ioctl
```
```
In net/ipv6/addrconf.c (0)
Location: include/linux/in.h:38
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
In net/ipv4/route.c (ffffffff8194b84f)
Location: include/linux/in.h:38
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_mc_validate_source
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81976c88)
Location: include/linux/in.h:38
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_twsk_unique
  - net/ipv4/tcp_ipv4.c:tcp_twsk_unique
```
```
In net/ipv4/arp.c (ffffffff8198c88f)
Location: include/linux/in.h:38
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_process
```
```
In net/ipv4/devinet.c (ffffffff819923d5)
Location: include/linux/in.h:38
Inline: True
Inline callers:
  - net/ipv4/devinet.c:devinet_ioctl
```
```
In net/ipv6/addrconf.c (0)
Location: include/linux/in.h:38
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
In drivers/net/vxlan.c (ffffffff81773fcb)
Location: include/linux/in.h:38
Inline: True
Inline callers:
  - drivers/net/vxlan.c:vxlan_xmit
```
```
In net/ipv4/route.c (ffffffff8190533f)
Location: include/linux/in.h:38
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_mc_validate_source
```
```
In net/ipv4/tcp_ipv4.c (ffffffff81930748)
Location: include/linux/in.h:38
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_twsk_unique
  - net/ipv4/tcp_ipv4.c:tcp_twsk_unique
```
```
In net/ipv4/arp.c (ffffffff8194634f)
Location: include/linux/in.h:38
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_process
```
```
In net/ipv4/devinet.c (ffffffff8194be95)
Location: include/linux/in.h:38
Inline: True
Inline callers:
  - net/ipv4/devinet.c:devinet_ioctl
```
```
In net/ipv6/addrconf.c (0)
Location: include/linux/in.h:38
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
In net/ipv4/route.c (ffffffff819b601f)
Location: include/linux/in.h:38
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_mc_validate_source
```
```
In net/ipv4/tcp_ipv4.c (ffffffff819e1458)
Location: include/linux/in.h:38
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_twsk_unique
  - net/ipv4/tcp_ipv4.c:tcp_twsk_unique
```
```
In net/ipv4/arp.c (ffffffff819f70d5)
Location: include/linux/in.h:38
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_process
```
```
In net/ipv4/devinet.c (ffffffff819fcc75)
Location: include/linux/in.h:38
Inline: True
Inline callers:
  - net/ipv4/devinet.c:devinet_ioctl
```
```
In net/ipv6/addrconf.c (0)
Location: include/linux/in.h:38
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
In net/ipv4/route.c (ffffffff819bf81f)
Location: include/linux/in.h:38
Inline: True
Inline callers:
  - net/ipv4/route.c:ip_route_output_key_hash_rcu
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_route_input_slow
  - net/ipv4/route.c:ip_mc_validate_source
```
```
In net/ipv4/tcp_ipv4.c (ffffffff819eb188)
Location: include/linux/in.h:38
Inline: True
Inline callers:
  - net/ipv4/tcp_ipv4.c:tcp_twsk_unique
  - net/ipv4/tcp_ipv4.c:tcp_twsk_unique
```
```
In net/ipv4/arp.c (ffffffff81a012f5)
Location: include/linux/in.h:38
Inline: True
Inline callers:
  - net/ipv4/arp.c:arp_process
```
```
In net/ipv4/devinet.c (ffffffff81a07005)
Location: include/linux/in.h:38
Inline: True
Inline callers:
  - net/ipv4/devinet.c:devinet_ioctl
```
```
In net/ipv6/addrconf.c (0)
Location: include/linux/in.h:38
Inline: True
```
</details>
</li>
</ul>

## Differences
