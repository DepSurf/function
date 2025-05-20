# Function: <code>sock_get_timestamp</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int sock_get_timestamp(struct sock *sk, struct timeval *userstamp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff81704a40)
Location: net/core/sock.c:2504
Inline: False
Direct callers:
  - net/compat.c:compat_sock_get_timestamp
  - net/ipv4/af_inet.c:inet_ioctl
  - net/ipv6/af_inet6.c:inet6_ioctl
  - net/packet/af_packet.c:packet_ioctl
```
**Symbols:**

```
ffffffff81704a40-ffffffff81704afb: sock_get_timestamp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int sock_get_timestamp(struct sock *sk, struct timeval *userstamp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff8176b630)
Location: net/core/sock.c:2572
Inline: False
Direct callers:
  - net/compat.c:compat_sock_get_timestamp
  - net/ipv4/af_inet.c:inet_ioctl
  - net/ipv6/af_inet6.c:inet6_ioctl
  - net/packet/af_packet.c:packet_ioctl
```
**Symbols:**

```
ffffffff8176b630-ffffffff8176b6eb: sock_get_timestamp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int sock_get_timestamp(struct sock *sk, struct timeval *userstamp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff81798700)
Location: net/core/sock.c:2599
Inline: False
Direct callers:
  - net/compat.c:compat_sock_get_timestamp
  - net/ipv4/af_inet.c:inet_ioctl
  - net/ipv6/af_inet6.c:inet6_ioctl
  - net/packet/af_packet.c:packet_ioctl
```
**Symbols:**

```
ffffffff81798700-ffffffff817987bb: sock_get_timestamp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int sock_get_timestamp(struct sock *sk, struct timeval *userstamp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff817b6290)
Location: net/core/sock.c:2766
Inline: False
Direct callers:
  - net/compat.c:compat_sock_get_timestamp
  - net/ipv4/af_inet.c:inet_ioctl
  - net/ipv6/af_inet6.c:inet6_ioctl
  - net/packet/af_packet.c:packet_ioctl
```
**Symbols:**

```
ffffffff817b6290-ffffffff817b634c: sock_get_timestamp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int sock_get_timestamp(struct sock *sk, struct timeval *userstamp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff8182e850)
Location: net/core/sock.c:2827
Inline: False
Direct callers:
  - net/compat.c:compat_sock_get_timestamp
  - net/ipv4/af_inet.c:inet_ioctl
  - net/ipv6/af_inet6.c:inet6_ioctl
  - net/packet/af_packet.c:packet_ioctl
```
**Symbols:**

```
ffffffff8182e850-ffffffff8182e90c: sock_get_timestamp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int sock_get_timestamp(struct sock *sk, struct timeval *userstamp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff81878cd0)
Location: net/core/sock.c:2902
Inline: False
Direct callers:
  - net/compat.c:compat_sock_get_timestamp
  - net/ipv4/af_inet.c:inet_ioctl
  - net/ipv6/af_inet6.c:inet6_ioctl
  - net/packet/af_packet.c:packet_ioctl
```
**Symbols:**

```
ffffffff81878cd0-ffffffff81878d8b: sock_get_timestamp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int sock_get_timestamp(struct sock *sk, struct timeval *userstamp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff81899680)
Location: net/core/sock.c:2851
Inline: False
Direct callers:
  - net/ipv4/af_inet.c:inet_ioctl
  - net/ipv6/af_inet6.c:inet6_ioctl
  - net/packet/af_packet.c:packet_ioctl
```
**Symbols:**

```
ffffffff81899680-ffffffff81899731: sock_get_timestamp (STB_GLOBAL)
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
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
</ul>
