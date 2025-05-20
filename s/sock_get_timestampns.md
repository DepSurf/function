# Function: <code>sock_get_timestampns</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int sock_get_timestampns(struct sock *sk, struct timespec *userstamp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff81704b00)
Location: net/core/sock.c:2520
Inline: False
Direct callers:
  - net/compat.c:compat_sock_get_timestampns
  - net/ipv4/af_inet.c:inet_ioctl
  - net/ipv6/af_inet6.c:inet6_ioctl
  - net/packet/af_packet.c:packet_ioctl
```
**Symbols:**

```
ffffffff81704b00-ffffffff81704bbb: sock_get_timestampns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int sock_get_timestampns(struct sock *sk, struct timespec *userstamp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff8176b6f0)
Location: net/core/sock.c:2588
Inline: False
Direct callers:
  - net/compat.c:compat_sock_get_timestampns
  - net/ipv4/af_inet.c:inet_ioctl
  - net/ipv6/af_inet6.c:inet6_ioctl
  - net/packet/af_packet.c:packet_ioctl
```
**Symbols:**

```
ffffffff8176b6f0-ffffffff8176b7ab: sock_get_timestampns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int sock_get_timestampns(struct sock *sk, struct timespec *userstamp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff817987c0)
Location: net/core/sock.c:2615
Inline: False
Direct callers:
  - net/compat.c:compat_sock_get_timestampns
  - net/ipv4/af_inet.c:inet_ioctl
  - net/ipv6/af_inet6.c:inet6_ioctl
  - net/packet/af_packet.c:packet_ioctl
```
**Symbols:**

```
ffffffff817987c0-ffffffff8179887b: sock_get_timestampns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int sock_get_timestampns(struct sock *sk, struct timespec *userstamp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff817b6350)
Location: net/core/sock.c:2782
Inline: False
Direct callers:
  - net/compat.c:compat_sock_get_timestampns
  - net/ipv4/af_inet.c:inet_ioctl
  - net/ipv6/af_inet6.c:inet6_ioctl
  - net/packet/af_packet.c:packet_ioctl
```
**Symbols:**

```
ffffffff817b6350-ffffffff817b640c: sock_get_timestampns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int sock_get_timestampns(struct sock *sk, struct timespec *userstamp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff8182e910)
Location: net/core/sock.c:2843
Inline: False
Direct callers:
  - net/compat.c:compat_sock_get_timestampns
  - net/ipv4/af_inet.c:inet_ioctl
  - net/ipv6/af_inet6.c:inet6_ioctl
  - net/packet/af_packet.c:packet_ioctl
```
**Symbols:**

```
ffffffff8182e910-ffffffff8182e9cc: sock_get_timestampns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int sock_get_timestampns(struct sock *sk, struct timespec *userstamp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff81878d90)
Location: net/core/sock.c:2918
Inline: False
Direct callers:
  - net/compat.c:compat_sock_get_timestampns
  - net/ipv4/af_inet.c:inet_ioctl
  - net/ipv6/af_inet6.c:inet6_ioctl
  - net/packet/af_packet.c:packet_ioctl
```
**Symbols:**

```
ffffffff81878d90-ffffffff81878e4b: sock_get_timestampns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int sock_get_timestampns(struct sock *sk, struct timespec *userstamp);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff81899740)
Location: net/core/sock.c:2868
Inline: False
Direct callers:
  - net/ipv4/af_inet.c:inet_ioctl
  - net/ipv6/af_inet6.c:inet6_ioctl
  - net/packet/af_packet.c:packet_ioctl
```
**Symbols:**

```
ffffffff81899740-ffffffff818997f1: sock_get_timestampns (STB_GLOBAL)
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
