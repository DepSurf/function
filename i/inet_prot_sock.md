# Function: <code>inet_prot_sock</code>

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
<details>
<summary>In <code>4.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (0)
Location: include/net/ip.h:268
Inline: True
```
```
In net/ipv4/af_inet.c (0)
Location: include/net/ip.h:268
Inline: True
```
```
In net/ipv6/af_inet6.c (0)
Location: include/net/ip.h:268
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
In security/selinux/hooks.c (0)
Location: include/net/ip.h:279
Inline: True
```
```
In net/ipv4/af_inet.c (0)
Location: include/net/ip.h:279
Inline: True
```
```
In net/ipv6/af_inet6.c (0)
Location: include/net/ip.h:279
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
In security/selinux/hooks.c (0)
Location: include/net/ip.h:291
Inline: True
```
```
In net/ipv4/af_inet.c (0)
Location: include/net/ip.h:291
Inline: True
```
```
In net/ipv6/af_inet6.c (0)
Location: include/net/ip.h:291
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
In security/selinux/hooks.c (0)
Location: include/net/ip.h:315
Inline: True
```
```
In net/ipv4/af_inet.c (0)
Location: include/net/ip.h:315
Inline: True
```
```
In net/ipv6/af_inet6.c (0)
Location: include/net/ip.h:315
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
In security/selinux/hooks.c (0)
Location: include/net/ip.h:353
Inline: True
```
```
In net/ipv4/af_inet.c (0)
Location: include/net/ip.h:353
Inline: True
```
```
In net/ipv6/af_inet6.c (0)
Location: include/net/ip.h:353
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
In security/selinux/hooks.c (0)
Location: include/net/ip.h:354
Inline: True
```
```
In net/ipv4/af_inet.c (0)
Location: include/net/ip.h:354
Inline: True
```
```
In net/ipv6/af_inet6.c (0)
Location: include/net/ip.h:354
Inline: True
```
</details>
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
<details>
<summary>In <code>arm64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (0)
Location: include/net/ip.h:354
Inline: True
```
```
In net/ipv4/af_inet.c (0)
Location: include/net/ip.h:354
Inline: True
```
```
In net/ipv6/af_inet6.c (0)
Location: include/net/ip.h:354
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
In security/selinux/hooks.c (c070142c)
Location: include/net/ip.h:354
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_socket_bind
```
```
In net/ipv4/af_inet.c (c0db8e44)
Location: include/net/ip.h:354
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:__inet_bind
```
```
In net/ipv6/af_inet6.c (c0dfd0d4)
Location: include/net/ip.h:354
Inline: True
Inline callers:
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
In security/selinux/hooks.c (c0000000006a36c4)
Location: include/net/ip.h:354
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_socket_bind
```
```
In net/ipv4/af_inet.c (c000000000dc2744)
Location: include/net/ip.h:354
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:__inet_bind
```
```
In net/ipv6/af_inet6.c (c000000000e1cd30)
Location: include/net/ip.h:354
Inline: True
Inline callers:
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
In security/selinux/hooks.c (ffffffe0003a5e18)
Location: include/net/ip.h:354
Inline: True
Inline callers:
  - security/selinux/hooks.c:selinux_socket_bind
```
```
In net/ipv4/af_inet.c (ffffffe0008068b8)
Location: include/net/ip.h:354
Inline: True
Inline callers:
  - net/ipv4/af_inet.c:__inet_bind
```
```
In net/ipv6/af_inet6.c (ffffffe000841ea8)
Location: include/net/ip.h:354
Inline: True
Inline callers:
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
In security/selinux/hooks.c (0)
Location: include/net/ip.h:354
Inline: True
```
```
In net/ipv4/af_inet.c (0)
Location: include/net/ip.h:354
Inline: True
```
```
In net/ipv6/af_inet6.c (0)
Location: include/net/ip.h:354
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
In security/selinux/hooks.c (0)
Location: include/net/ip.h:354
Inline: True
```
```
In net/ipv4/af_inet.c (0)
Location: include/net/ip.h:354
Inline: True
```
```
In net/ipv6/af_inet6.c (0)
Location: include/net/ip.h:354
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
In security/selinux/hooks.c (0)
Location: include/net/ip.h:354
Inline: True
```
```
In net/ipv4/af_inet.c (0)
Location: include/net/ip.h:354
Inline: True
```
```
In net/ipv6/af_inet6.c (0)
Location: include/net/ip.h:354
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
In security/selinux/hooks.c (0)
Location: include/net/ip.h:354
Inline: True
```
```
In net/ipv4/af_inet.c (0)
Location: include/net/ip.h:354
Inline: True
```
```
In net/ipv6/af_inet6.c (0)
Location: include/net/ip.h:354
Inline: True
```
</details>
</li>
</ul>

## Differences
