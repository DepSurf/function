# Function: <code>inet_reset_saddr</code>

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
In net/ipv4/tcp.c (ffffffff81768328)
Location: include/net/ip.h:457
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_disconnect
```
```
In net/ipv4/udp.c (ffffffff81786ca0)
Location: include/net/ip.h:457
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_disconnect
```
```
In net/ipv6/af_inet6.c (ffffffff817c2e69)
Location: include/net/ip.h:457
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:inet6_bind
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
In net/ipv4/tcp.c (ffffffff817d4c09)
Location: include/net/ip.h:453
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_disconnect
```
```
In net/ipv4/udp.c (ffffffff817f3ce0)
Location: include/net/ip.h:453
Inline: True
Inline callers:
  - net/ipv4/udp.c:udp_disconnect
```
```
In net/ipv6/af_inet6.c (ffffffff8182fed8)
Location: include/net/ip.h:453
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:inet6_bind
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
In net/ipv4/tcp.c (ffffffff8180491c)
Location: include/net/ip.h:482
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_disconnect
```
```
In net/ipv4/udp.c (ffffffff81824ac0)
Location: include/net/ip.h:482
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp_disconnect
```
```
In net/ipv6/af_inet6.c (ffffffff81861958)
Location: include/net/ip.h:482
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:inet6_bind
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
In net/ipv4/tcp.c (ffffffff81824c6e)
Location: include/net/ip.h:494
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_disconnect
```
```
In net/ipv4/udp.c (ffffffff8184581a)
Location: include/net/ip.h:494
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp_disconnect
```
```
In net/ipv6/af_inet6.c (ffffffff8188604d)
Location: include/net/ip.h:494
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:inet6_bind
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
In net/ipv4/tcp.c (ffffffff818a6a94)
Location: include/net/ip.h:505
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_disconnect
```
```
In net/ipv4/udp.c (ffffffff818c5280)
Location: include/net/ip.h:505
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp_disconnect
```
```
In net/ipv6/af_inet6.c (ffffffff81907250)
Location: include/net/ip.h:505
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:inet6_bind
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
In net/ipv4/tcp.c (ffffffff818fbb8f)
Location: include/net/ip.h:527
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_disconnect
```
```
In net/ipv4/udp.c (ffffffff8191ac50)
Location: include/net/ip.h:527
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp_disconnect
```
```
In net/ipv6/af_inet6.c (ffffffff8195edf0)
Location: include/net/ip.h:527
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:__inet6_bind
  - net/ipv6/af_inet6.c:__inet6_bind
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
In net/ipv4/tcp.c (ffffffff81929b18)
Location: include/net/ip.h:579
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_disconnect
```
```
In net/ipv4/udp.c (ffffffff81949412)
Location: include/net/ip.h:579
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp_disconnect
```
```
In net/ipv6/af_inet6.c (ffffffff81993966)
Location: include/net/ip.h:579
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:__inet6_bind
  - net/ipv6/af_inet6.c:__inet6_bind
  - net/ipv6/af_inet6.c:__inet6_bind
  - net/ipv6/af_inet6.c:__inet6_bind
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
In net/ipv4/tcp.c (ffffffff8198cd1d)
Location: include/net/ip.h:617
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_disconnect
```
```
In net/ipv4/udp.c (ffffffff819ada62)
Location: include/net/ip.h:617
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp_disconnect
```
```
In net/ipv6/af_inet6.c (ffffffff819ff3fa)
Location: include/net/ip.h:617
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:__inet6_bind
  - net/ipv6/af_inet6.c:__inet6_bind
  - net/ipv6/af_inet6.c:__inet6_bind
  - net/ipv6/af_inet6.c:__inet6_bind
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
In net/ipv4/tcp.c (ffffffff819c36bc)
Location: include/net/ip.h:618
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_disconnect
```
```
In net/ipv4/udp.c (ffffffff819e4747)
Location: include/net/ip.h:618
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp_disconnect
```
```
In net/ipv6/af_inet6.c (ffffffff81a35ffa)
Location: include/net/ip.h:618
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:__inet6_bind
  - net/ipv6/af_inet6.c:__inet6_bind
  - net/ipv6/af_inet6.c:__inet6_bind
  - net/ipv6/af_inet6.c:__inet6_bind
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
In net/ipv4/tcp.c (ffffffff81aaedc0)
Location: include/net/ip.h:618
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_disconnect
```
```
In net/ipv4/udp.c (ffffffff81ad21fa)
Location: include/net/ip.h:618
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp_disconnect
```
```
In net/ipv6/af_inet6.c (ffffffff81b2b104)
Location: include/net/ip.h:618
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:__inet6_bind
  - net/ipv6/af_inet6.c:__inet6_bind
  - net/ipv6/af_inet6.c:__inet6_bind
  - net/ipv6/af_inet6.c:__inet6_bind
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
In net/ipv4/tcp.c (ffffffff81ab901e)
Location: include/net/ip.h:621
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_disconnect
```
```
In net/ipv4/udp.c (ffffffff81ade337)
Location: include/net/ip.h:621
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp_disconnect
```
```
In net/ipv6/af_inet6.c (ffffffff81b39b3a)
Location: include/net/ip.h:621
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:__inet6_bind
  - net/ipv6/af_inet6.c:__inet6_bind
  - net/ipv6/af_inet6.c:__inet6_bind
  - net/ipv6/af_inet6.c:__inet6_bind
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
In net/ipv4/tcp.c (ffffffff81aa42d1)
Location: include/net/ip.h:625
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_disconnect
```
```
In net/ipv4/udp.c (ffffffff81ac9957)
Location: include/net/ip.h:625
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp_disconnect
```
```
In net/ipv6/af_inet6.c (ffffffff81b27818)
Location: include/net/ip.h:625
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:__inet6_bind
  - net/ipv6/af_inet6.c:__inet6_bind
  - net/ipv6/af_inet6.c:__inet6_bind
  - net/ipv6/af_inet6.c:__inet6_bind
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
In net/ipv4/tcp.c (ffffffff81b604a6)
Location: include/net/ip.h:638
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_disconnect
```
```
In net/ipv4/udp.c (ffffffff81b881cb)
Location: include/net/ip.h:638
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp_disconnect
```
```
In net/ipv6/af_inet6.c (ffffffff81bed752)
Location: include/net/ip.h:638
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:__inet6_bind
  - net/ipv6/af_inet6.c:__inet6_bind
  - net/ipv6/af_inet6.c:__inet6_bind
  - net/ipv6/af_inet6.c:__inet6_bind
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
In net/ipv4/tcp.c (ffffffff81ceedd2)
Location: include/net/ip.h:635
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_disconnect
```
```
In net/ipv4/udp.c (ffffffff81d196a7)
Location: include/net/ip.h:635
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp_disconnect
```
```
In net/ipv6/af_inet6.c (ffffffff81d85be5)
Location: include/net/ip.h:635
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:__inet6_bind
  - net/ipv6/af_inet6.c:__inet6_bind
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

```c
void inet_reset_saddr(struct sock *sk);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv4/inet_hashtables.c (ffffffff81ea4c85)
Location: include/net/ip.h:635
Inline: True
Inline callers:
  - net/ipv4/inet_hashtables.c:__inet_bhash2_update_saddr
  - net/ipv4/inet_hashtables.c:__inet_bhash2_update_saddr
Direct callers:
  - net/ipv4/inet_hashtables.c:__inet_bhash2_update_saddr
```
```
In net/ipv4/udp.c (ffffffff81ee0037)
Location: include/net/ip.h:635
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp_disconnect
```
```
In net/ipv6/af_inet6.c (ffffffff81f536c6)
Location: include/net/ip.h:635
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:__inet6_bind
  - net/ipv6/af_inet6.c:__inet6_bind
```
**Symbols:**

```
ffffffff81ea2530-ffffffff81ea25ba: inet_reset_saddr (STB_LOCAL)
ffffffff820ae552-ffffffff820ae572: inet_reset_saddr.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

```c
void inet_reset_saddr(struct sock *sk);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv4/inet_hashtables.c (0)
Location: include/net/ip.h:655
Inline: False
Direct callers:
  - net/ipv4/inet_hashtables.c:__inet_bhash2_update_saddr
  - net/ipv4/inet_hashtables.c:__inet_bhash2_update_saddr
  - net/ipv4/inet_hashtables.c:__inet_bhash2_update_saddr
```
```
In net/ipv4/udp.c (0)
Location: include/net/ip.h:655
Inline: True
Direct callers:
  - net/ipv4/udp.c:__udp_disconnect
```
```
In net/ipv6/af_inet6.c (0)
Location: include/net/ip.h:655
Inline: False
Direct callers:
  - net/ipv6/af_inet6.c:__inet6_bind
  - net/ipv6/af_inet6.c:__inet6_bind
```
**Symbols:**

```
ffffffff81f00d50-ffffffff81f00dd8: inet_reset_saddr (STB_LOCAL)
ffffffff8212fa63-ffffffff8212fa7c: inet_reset_saddr.cold (STB_LOCAL)
ffffffff81f3f3e0-ffffffff81f3f468: inet_reset_saddr.constprop.0 (STB_LOCAL)
ffffffff8213150a-ffffffff82131523: inet_reset_saddr.constprop.0.cold (STB_LOCAL)
ffffffff81fb2b40-ffffffff81fb2bc8: inet_reset_saddr (STB_LOCAL)
ffffffff8213449d-ffffffff821344b6: inet_reset_saddr.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

```c
void inet_reset_saddr(struct sock *sk);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv4/inet_hashtables.c (0)
Location: include/net/ip.h:665
Inline: False
Direct callers:
  - net/ipv4/inet_hashtables.c:__inet_bhash2_update_saddr
  - net/ipv4/inet_hashtables.c:__inet_bhash2_update_saddr
  - net/ipv4/inet_hashtables.c:__inet_bhash2_update_saddr
```
```
In net/ipv4/udp.c (ffffffff820078d3)
Location: include/net/ip.h:665
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp_disconnect
```
```
In net/ipv6/af_inet6.c (0)
Location: include/net/ip.h:665
Inline: False
Direct callers:
  - net/ipv6/af_inet6.c:__inet6_bind
  - net/ipv6/af_inet6.c:__inet6_bind
```
**Symbols:**

```
ffffffff81fc4fd0-ffffffff81fc5058: inet_reset_saddr (STB_LOCAL)
ffffffff822117f6-ffffffff8221180f: inet_reset_saddr.cold (STB_LOCAL)
ffffffff82080320-ffffffff820803a8: inet_reset_saddr (STB_LOCAL)
ffffffff82216066-ffffffff8221607f: inet_reset_saddr.cold (STB_LOCAL)
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
In net/ipv4/tcp.c (ffff800010c76280)
Location: include/net/ip.h:618
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_disconnect
```
```
In net/ipv4/udp.c (ffff800010c997b8)
Location: include/net/ip.h:618
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp_disconnect
```
```
In net/ipv6/af_inet6.c (ffff800010cf69ec)
Location: include/net/ip.h:618
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:__inet6_bind
  - net/ipv6/af_inet6.c:__inet6_bind
  - net/ipv6/af_inet6.c:__inet6_bind
  - net/ipv6/af_inet6.c:__inet6_bind
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
In net/ipv4/tcp.c (c0d849c4)
Location: include/net/ip.h:618
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_disconnect
```
```
In net/ipv4/udp.c (c0da9888)
Location: include/net/ip.h:618
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp_disconnect
```
```
In net/ipv6/af_inet6.c (c0dfd348)
Location: include/net/ip.h:618
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:__inet6_bind
  - net/ipv6/af_inet6.c:__inet6_bind
  - net/ipv6/af_inet6.c:__inet6_bind
  - net/ipv6/af_inet6.c:__inet6_bind
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
In net/ipv4/tcp.c (c000000000d7dd50)
Location: include/net/ip.h:618
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_disconnect
```
```
In net/ipv4/udp.c (c000000000daac10)
Location: include/net/ip.h:618
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp_disconnect
```
```
In net/ipv6/af_inet6.c (c000000000e1d08c)
Location: include/net/ip.h:618
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:__inet6_bind
  - net/ipv6/af_inet6.c:__inet6_bind
  - net/ipv6/af_inet6.c:__inet6_bind
  - net/ipv6/af_inet6.c:__inet6_bind
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
In net/ipv4/tcp.c (ffffffe0007d9416)
Location: include/net/ip.h:618
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_disconnect
```
```
In net/ipv4/udp.c (ffffffe0007f703c)
Location: include/net/ip.h:618
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp_disconnect
```
```
In net/ipv6/af_inet6.c (ffffffe0008420a2)
Location: include/net/ip.h:618
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:__inet6_bind
  - net/ipv6/af_inet6.c:__inet6_bind
  - net/ipv6/af_inet6.c:__inet6_bind
  - net/ipv6/af_inet6.c:__inet6_bind
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
In net/ipv4/tcp.c (ffffffff8196352c)
Location: include/net/ip.h:618
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_disconnect
```
```
In net/ipv4/udp.c (ffffffff819845b7)
Location: include/net/ip.h:618
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp_disconnect
```
```
In net/ipv6/af_inet6.c (ffffffff819d568a)
Location: include/net/ip.h:618
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:__inet6_bind
  - net/ipv6/af_inet6.c:__inet6_bind
  - net/ipv6/af_inet6.c:__inet6_bind
  - net/ipv6/af_inet6.c:__inet6_bind
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
In net/ipv4/tcp.c (ffffffff8191d01c)
Location: include/net/ip.h:618
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_disconnect
```
```
In net/ipv4/udp.c (ffffffff8193e077)
Location: include/net/ip.h:618
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp_disconnect
```
```
In net/ipv6/af_inet6.c (ffffffff8199244a)
Location: include/net/ip.h:618
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:__inet6_bind
  - net/ipv6/af_inet6.c:__inet6_bind
  - net/ipv6/af_inet6.c:__inet6_bind
  - net/ipv6/af_inet6.c:__inet6_bind
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
In net/ipv4/tcp.c (ffffffff819cdcfc)
Location: include/net/ip.h:618
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_disconnect
```
```
In net/ipv4/udp.c (ffffffff819eed87)
Location: include/net/ip.h:618
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp_disconnect
```
```
In net/ipv6/af_inet6.c (ffffffff81a4010a)
Location: include/net/ip.h:618
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:__inet6_bind
  - net/ipv6/af_inet6.c:__inet6_bind
  - net/ipv6/af_inet6.c:__inet6_bind
  - net/ipv6/af_inet6.c:__inet6_bind
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
In net/ipv4/tcp.c (ffffffff819d788c)
Location: include/net/ip.h:618
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_disconnect
```
```
In net/ipv4/udp.c (ffffffff819f8ef7)
Location: include/net/ip.h:618
Inline: True
Inline callers:
  - net/ipv4/udp.c:__udp_disconnect
```
```
In net/ipv6/af_inet6.c (ffffffff81a4bc9d)
Location: include/net/ip.h:618
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:__inet6_bind
  - net/ipv6/af_inet6.c:__inet6_bind
  - net/ipv6/af_inet6.c:__inet6_bind
  - net/ipv6/af_inet6.c:__inet6_bind
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
