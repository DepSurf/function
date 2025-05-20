# Function: <code>sk_setsockopt</code>

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
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int sk_setsockopt(struct sock *sk, int level, int optname, sockptr_t optval, unsigned int optlen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff81d9e9b0)
Location: net/core/sock.c:1087
Inline: False
Direct callers:
  - net/core/sock.c:sock_setsockopt
  - net/core/filter.c:sol_socket_sockopt
  - net/ipv4/udp.c:udp_lib_setsockopt
```
**Symbols:**

```
ffffffff81d9e9b0-ffffffff81d9fdab: sk_setsockopt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int sk_setsockopt(struct sock *sk, int level, int optname, sockptr_t optval, unsigned int optlen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff81e0d1b0)
Location: net/core/sock.c:1094
Inline: False
Direct callers:
  - net/core/sock.c:sock_setsockopt
  - net/core/filter.c:sol_socket_sockopt
  - net/ipv4/udp.c:udp_lib_setsockopt
```
**Symbols:**

```
ffffffff81e0d1b0-ffffffff81e0e56e: sk_setsockopt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int sk_setsockopt(struct sock *sk, int level, int optname, sockptr_t optval, unsigned int optlen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff81ec9b50)
Location: net/core/sock.c:1090
Inline: False
Direct callers:
  - net/core/sock.c:sock_setsockopt
  - net/core/filter.c:sol_socket_sockopt
  - net/ipv4/udp.c:udp_lib_setsockopt
  - net/mptcp/sockopt.c:mptcp_setsockopt_sol_socket
```
**Symbols:**

```
ffffffff81ec9b50-ffffffff81ecaff6: sk_setsockopt (STB_GLOBAL)
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
<b>Regular</b>
<ul>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
