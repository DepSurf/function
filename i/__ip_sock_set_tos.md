# Function: <code>__ip_sock_set_tos</code>

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
<summary>In <code>5.8</code>: ✅</summary>

```c
void __ip_sock_set_tos(struct sock *sk, int val);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_sockglue.c (ffffffff81a9f800)
Location: net/ipv4/ip_sockglue.c:563
Inline: False
Direct callers:
  - net/ipv4/ip_sockglue.c:ip_sock_set_tos
```
**Symbols:**

```
ffffffff81a9f800-ffffffff81a9f869: __ip_sock_set_tos (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void __ip_sock_set_tos(struct sock *sk, int val);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_sockglue.c (ffffffff81aa9750)
Location: net/ipv4/ip_sockglue.c:579
Inline: False
Direct callers:
  - net/ipv4/ip_sockglue.c:ip_sock_set_tos
```
**Symbols:**

```
ffffffff81aa9750-ffffffff81aa97b9: __ip_sock_set_tos (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void __ip_sock_set_tos(struct sock *sk, int val);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_sockglue.c (ffffffff81a94920)
Location: net/ipv4/ip_sockglue.c:579
Inline: False
Direct callers:
  - net/ipv4/ip_sockglue.c:ip_sock_set_tos
```
**Symbols:**

```
ffffffff81a94920-ffffffff81a94989: __ip_sock_set_tos (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void __ip_sock_set_tos(struct sock *sk, int val);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_sockglue.c (ffffffff81b4fda0)
Location: net/ipv4/ip_sockglue.c:579
Inline: False
Direct callers:
  - net/ipv4/ip_sockglue.c:ip_sock_set_tos
```
**Symbols:**

```
ffffffff81b4fda0-ffffffff81b4fe0a: __ip_sock_set_tos (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void __ip_sock_set_tos(struct sock *sk, int val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_sockglue.c (ffffffff81cdfdb0)
Location: net/ipv4/ip_sockglue.c:581
Inline: False
Direct callers:
  - net/ipv4/ip_sockglue.c:ip_sock_set_tos
  - net/mptcp/sockopt.c:sync_socket_options
  - net/mptcp/sockopt.c:mptcp_setsockopt_v4
```
**Symbols:**

```
ffffffff81cdfdb0-ffffffff81cdfe31: __ip_sock_set_tos (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void __ip_sock_set_tos(struct sock *sk, int val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_sockglue.c (ffffffff81ea0170)
Location: net/ipv4/ip_sockglue.c:582
Inline: False
Direct callers:
  - net/ipv4/ip_sockglue.c:do_ip_setsockopt
  - net/ipv4/ip_sockglue.c:ip_sock_set_tos
  - net/mptcp/sockopt.c:sync_socket_options
  - net/mptcp/sockopt.c:mptcp_setsockopt_v4
```
**Symbols:**

```
ffffffff81ea0170-ffffffff81ea01f1: __ip_sock_set_tos (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void __ip_sock_set_tos(struct sock *sk, int val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_sockglue.c (ffffffff81efe9c0)
Location: net/ipv4/ip_sockglue.c:589
Inline: False
Direct callers:
  - net/ipv4/ip_sockglue.c:do_ip_setsockopt
  - net/ipv4/ip_sockglue.c:ip_sock_set_tos
  - net/mptcp/sockopt.c:sync_socket_options
  - net/mptcp/sockopt.c:mptcp_setsockopt_v4
```
**Symbols:**

```
ffffffff81efe9c0-ffffffff81efea41: __ip_sock_set_tos (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void __ip_sock_set_tos(struct sock *sk, int val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/ip_sockglue.c (ffffffff81fc2bf0)
Location: net/ipv4/ip_sockglue.c:586
Inline: False
Direct callers:
  - net/ipv4/ip_sockglue.c:do_ip_setsockopt
  - net/mptcp/sockopt.c:mptcp_setsockopt
```
**Symbols:**

```
ffffffff81fc2bf0-ffffffff81fc2c71: __ip_sock_set_tos (STB_GLOBAL)
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
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
<li>
No changes between <code>5.15</code> and <code>5.19</code> ✅
</li>
<li>
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
