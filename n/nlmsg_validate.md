# Function: <code>nlmsg_validate</code>

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
In net/ipv4/fib_frontend.c (ffffffff81799ce5)
Location: include/net/netlink.h:401
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
In net/ipv4/fib_frontend.c (ffffffff818079c5)
Location: include/net/netlink.h:412
Inline: True
```
```
In net/ipv4/ipmr.c (ffffffff81817775)
Location: include/net/netlink.h:412
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_route
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
In net/ipv4/fib_frontend.c (ffffffff81838a65)
Location: include/net/netlink.h:412
Inline: True
```
```
In net/ipv4/ipmr.c (ffffffff81848fe5)
Location: include/net/netlink.h:412
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_route
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
In net/ipv4/fib_frontend.c (ffffffff81859d25)
Location: include/net/netlink.h:419
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:rtm_to_fib_config
```
```
In net/ipv4/ipmr.c (ffffffff8186c6b9)
Location: include/net/netlink.h:419
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_route
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
In net/ipv4/fib_frontend.c (ffffffff818d9c25)
Location: include/net/netlink.h:425
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:rtm_to_fib_config
```
```
In net/ipv4/ipmr.c (ffffffff818ecf99)
Location: include/net/netlink.h:425
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_route
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
In net/ipv4/fib_frontend.c (ffffffff819306b5)
Location: include/net/netlink.h:425
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:rtm_to_fib_config
```
```
In net/ipv4/ipmr.c (ffffffff81942f22)
Location: include/net/netlink.h:425
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_route
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
In net/ipv4/fib_frontend.c (ffffffff8195fac5)
Location: include/net/netlink.h:568
Inline: True
Inline callers:
  - net/ipv4/fib_frontend.c:rtm_to_fib_config
```
```
In net/ipv4/ipmr.c (ffffffff81972ff2)
Location: include/net/netlink.h:568
Inline: True
Inline callers:
  - net/ipv4/ipmr.c:ipmr_rtm_route
```
</details>
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
