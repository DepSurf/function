# Function: <code>inet_port_requires_bind_service</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
In <code>4.8</code>: Absent ⚠️
</li>
<li>
In <code>4.10</code>: Absent ⚠️
</li>
<li>
In <code>4.13</code>: Absent ⚠️
</li>
<li>
In <code>4.15</code>: Absent ⚠️
</li>
<li>
In <code>4.18</code>: Absent ⚠️
</li>
<li>
In <code>5.0</code>: Absent ⚠️
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff814b1490)
Location: include/net/ip.h:354
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_socket_bind
```
```
In net/ipv4/af_inet.c (ffffffff81ae4544)
Location: include/net/ip.h:354
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:__inet_bind
```
```
In net/ipv6/af_inet6.c (ffffffff81b2add8)
Location: include/net/ip.h:354
Inline: True
Inline callers:
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
In security/selinux/hooks.c (ffffffff814ce6b0)
Location: include/net/ip.h:351
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_socket_bind
```
```
In net/ipv4/af_inet.c (ffffffff81af1474)
Location: include/net/ip.h:351
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:__inet_bind
```
```
In net/ipv6/af_inet6.c (ffffffff81b3977c)
Location: include/net/ip.h:351
Inline: True
Inline callers:
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
In security/selinux/hooks.c (ffffffff814d4e00)
Location: include/net/ip.h:352
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_socket_bind
```
```
In net/ipv4/af_inet.c (ffffffff81adcc31)
Location: include/net/ip.h:352
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:__inet_bind
```
```
In net/ipv6/af_inet6.c (ffffffff81b27467)
Location: include/net/ip.h:352
Inline: True
Inline callers:
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
In security/selinux/hooks.c (ffffffff8152daa0)
Location: include/net/ip.h:352
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_socket_bind
```
```
In net/ipv4/af_inet.c (ffffffff81b9c021)
Location: include/net/ip.h:352
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:__inet_bind
```
```
In net/ipv6/af_inet6.c (ffffffff81bed3a1)
Location: include/net/ip.h:352
Inline: True
Inline callers:
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
In security/selinux/hooks.c (ffffffff815c448d)
Location: include/net/ip.h:358
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_socket_bind
```
```
In net/ipv4/af_inet.c (ffffffff81d2df51)
Location: include/net/ip.h:358
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:__inet_bind
```
```
In net/ipv6/af_inet6.c (ffffffff81d858a3)
Location: include/net/ip.h:358
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:__inet6_bind
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
In security/selinux/hooks.c (ffffffff81670f3d)
Location: include/net/ip.h:358
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_socket_bind
```
```
In net/ipv4/af_inet.c (ffffffff81ef5e81)
Location: include/net/ip.h:358
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:__inet_bind
```
```
In net/ipv6/af_inet6.c (ffffffff81f53366)
Location: include/net/ip.h:358
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:__inet6_bind
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
In security/selinux/hooks.c (ffffffff816a962a)
Location: include/net/ip.h:367
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_socket_bind
```
```
In net/ipv4/af_inet.c (ffffffff81f556e1)
Location: include/net/ip.h:367
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:__inet_bind
```
```
In net/ipv6/af_inet6.c (ffffffff81fb2d8f)
Location: include/net/ip.h:367
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:__inet6_bind
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
In security/selinux/hooks.c (ffffffff816e6db5)
Location: include/net/ip.h:374
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_socket_bind
```
```
In security/apparmor/af_inet.c (ffffffff81762ebc)
Location: include/net/ip.h:374
Inline: True
Inline callers:
  - security/apparmor/af_inet.c:aa_inet_bind_perm
```
```
In net/ipv4/af_inet.c (ffffffff8201bb6b)
Location: include/net/ip.h:374
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:__inet_bind
```
```
In net/ipv6/af_inet6.c (ffffffff82080575)
Location: include/net/ip.h:374
Inline: True
Inline callers:
  - net/ipv6/af_inet6.c:__inet6_bind
```
</details>
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
