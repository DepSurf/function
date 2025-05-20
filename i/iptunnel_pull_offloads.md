# Function: <code>iptunnel_pull_offloads</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_tunnel_core.c (ffffffff81812861)
Location: include/net/ip_tunnels.h:385
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:__iptunnel_pull_header
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
In net/ipv4/ip_tunnel_core.c (ffffffff81843d61)
Location: include/net/ip_tunnels.h:406
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:__iptunnel_pull_header
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
In net/ipv4/ip_tunnel_core.c (ffffffff818655f1)
Location: include/net/ip_tunnels.h:408
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:__iptunnel_pull_header
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
In net/ipv4/ip_tunnel_core.c (ffffffff818e5741)
Location: include/net/ip_tunnels.h:415
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:__iptunnel_pull_header
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
In net/ipv4/ip_tunnel_core.c (ffffffff8193bfe4)
Location: include/net/ip_tunnels.h:447
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:__iptunnel_pull_header
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
In net/ipv4/ip_tunnel_core.c (ffffffff8196bcf9)
Location: include/net/ip_tunnels.h:449
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:__iptunnel_pull_header
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_tunnel_core.c (ffffffff819d2a49)
Location: include/net/ip_tunnels.h:450
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:__iptunnel_pull_header
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
In net/ipv4/ip_tunnel_core.c (ffffffff81a095b9)
Location: include/net/ip_tunnels.h:450
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:__iptunnel_pull_header
```
```
In net/ipv6/seg6_local.c (ffffffff81a84b9a)
Location: include/net/ip_tunnels.h:450
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:decap_and_validate
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
In net/ipv4/ip_tunnel_core.c (ffffffff81af8ed9)
Location: include/net/ip_tunnels.h:454
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:__iptunnel_pull_header
```
```
In net/ipv6/seg6_local.c (ffffffff81b7fc2a)
Location: include/net/ip_tunnels.h:454
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:decap_and_validate
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
In net/ipv4/ip_tunnel_core.c (ffffffff81b06ec9)
Location: include/net/ip_tunnels.h:454
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:__iptunnel_pull_header
```
```
In net/ipv6/seg6_local.c (ffffffff81b8ef5a)
Location: include/net/ip_tunnels.h:454
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:decap_and_validate
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
In net/ipv4/ip_tunnel_core.c (ffffffff81af2621)
Location: include/net/ip_tunnels.h:454
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:__iptunnel_pull_header
```
```
In net/ipv6/seg6_local.c (ffffffff81b7df9a)
Location: include/net/ip_tunnels.h:454
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:decap_and_validate
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
In net/ipv4/ip_tunnel_core.c (ffffffff81bb2b31)
Location: include/net/ip_tunnels.h:455
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:__iptunnel_pull_header
```
```
In net/ipv6/seg6_local.c (ffffffff81c48e0a)
Location: include/net/ip_tunnels.h:455
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:decap_and_validate
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
In net/ipv4/ip_tunnel_core.c (ffffffff81d462f1)
Location: include/net/ip_tunnels.h:466
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:__iptunnel_pull_header
```
```
In net/ipv6/seg6_local.c (ffffffff81de8513)
Location: include/net/ip_tunnels.h:466
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:decap_and_validate
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
In net/ipv4/ip_tunnel_core.c (ffffffff81f0f6e4)
Location: include/net/ip_tunnels.h:478
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:__iptunnel_pull_header
```
```
In net/ipv6/seg6_local.c (ffffffff81fbb4de)
Location: include/net/ip_tunnels.h:478
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:decap_and_validate
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
In net/ipv4/ip_tunnel_core.c (ffffffff81f6f3d4)
Location: include/net/ip_tunnels.h:487
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:__iptunnel_pull_header
```
```
In net/ipv6/seg6_local.c (ffffffff8201bb9e)
Location: include/net/ip_tunnels.h:487
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:decap_and_validate
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
In net/ipv4/ip_tunnel_core.c (ffffffff82035b04)
Location: include/net/ip_tunnels.h:471
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:__iptunnel_pull_header
```
```
In net/ipv6/seg6_local.c (ffffffff820eab5e)
Location: include/net/ip_tunnels.h:471
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:decap_and_validate
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
In net/ipv4/ip_tunnel_core.c (ffff800010cc295c)
Location: include/net/ip_tunnels.h:450
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:__iptunnel_pull_header
```
```
In net/ipv6/seg6_local.c (ffff800010d50c48)
Location: include/net/ip_tunnels.h:450
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:decap_and_validate
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
In net/ipv4/ip_tunnel_core.c (c0dce1ac)
Location: include/net/ip_tunnels.h:450
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:__iptunnel_pull_header
```
```
In net/ipv6/seg6_local.c (c0e51798)
Location: include/net/ip_tunnels.h:450
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:decap_and_validate
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
In net/ipv4/ip_tunnel_core.c (c000000000dde1d4)
Location: include/net/ip_tunnels.h:450
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:__iptunnel_pull_header
```
```
In net/ipv6/seg6_local.c (c000000000e88a4c)
Location: include/net/ip_tunnels.h:450
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:decap_and_validate
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
In net/ipv4/ip_tunnel_core.c (ffffffe000817dc0)
Location: include/net/ip_tunnels.h:450
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:__iptunnel_pull_header
```
```
In net/ipv6/seg6_local.c (ffffffe000888f96)
Location: include/net/ip_tunnels.h:450
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:decap_and_validate
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
In net/ipv4/ip_tunnel_core.c (ffffffff819a9359)
Location: include/net/ip_tunnels.h:450
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:__iptunnel_pull_header
```
```
In net/ipv6/seg6_local.c (ffffffff81a2422a)
Location: include/net/ip_tunnels.h:450
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:decap_and_validate
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
In net/ipv4/ip_tunnel_core.c (ffffffff81962e19)
Location: include/net/ip_tunnels.h:450
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:__iptunnel_pull_header
```
```
In net/ipv6/seg6_local.c (ffffffff819e0fea)
Location: include/net/ip_tunnels.h:450
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:decap_and_validate
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
In net/ipv4/ip_tunnel_core.c (ffffffff81a13bf9)
Location: include/net/ip_tunnels.h:450
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:__iptunnel_pull_header
```
```
In net/ipv6/seg6_local.c (ffffffff81a8ecaa)
Location: include/net/ip_tunnels.h:450
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:decap_and_validate
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
In net/ipv4/ip_tunnel_core.c (ffffffff81a1e5d9)
Location: include/net/ip_tunnels.h:450
Inline: True
Inline callers:
  - net/ipv4/ip_tunnel_core.c:__iptunnel_pull_header
```
```
In net/ipv6/seg6_local.c (ffffffff81a9ba1a)
Location: include/net/ip_tunnels.h:450
Inline: True
Inline callers:
  - net/ipv6/seg6_local.c:decap_and_validate
```
</details>
</li>
</ul>

## Differences
