# Function: <code>__tcp_sock_set_cork</code>

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
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv4/tcp.c (ffffffff81aa8398)
Location: net/ipv4/tcp.c:2872
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sock_set_cork
Direct callers:
  - net/ipv4/tcp.c:tcp_sock_set_cork
```
**Symbols:**

```
ffffffff81aa8300-ffffffff81aa8372: __tcp_sock_set_cork.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv4/tcp.c (ffffffff81ab2908)
Location: net/ipv4/tcp.c:3130
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sock_set_cork
Direct callers:
  - net/ipv4/tcp.c:tcp_sock_set_cork
```
**Symbols:**

```
ffffffff81ab2870-ffffffff81ab28e2: __tcp_sock_set_cork.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv4/tcp.c (ffffffff81a9dc18)
Location: net/ipv4/tcp.c:3184
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sock_set_cork
Direct callers:
  - net/ipv4/tcp.c:tcp_sock_set_cork
```
**Symbols:**

```
ffffffff81a9db80-ffffffff81a9dbf2: __tcp_sock_set_cork.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv4/tcp.c (ffffffff81b59638)
Location: net/ipv4/tcp.c:3208
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sock_set_cork
Direct callers:
  - net/ipv4/tcp.c:tcp_sock_set_cork
```
**Symbols:**

```
ffffffff81b595a0-ffffffff81b59612: __tcp_sock_set_cork.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

```c
void __tcp_sock_set_cork(struct sock *sk, bool on);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv4/tcp.c (ffffffff81ce80a9)
Location: net/ipv4/tcp.c:3226
Inline: True
Inline callers:
  - net/ipv4/tcp.c:tcp_sock_set_cork
Direct callers:
  - net/ipv4/tcp.c:tcp_sock_set_cork
  - net/mptcp/sockopt.c:sync_socket_options
  - net/mptcp/sockopt.c:mptcp_setsockopt_sol_tcp
```
**Symbols:**

```
ffffffff81ce8000-ffffffff81ce8081: __tcp_sock_set_cork.part.0 (STB_LOCAL)
ffffffff81cef0c0-ffffffff81cef15d: __tcp_sock_set_cork (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

```c
void __tcp_sock_set_cork(struct sock *sk, bool on);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv4/tcp.c (ffffffff81eb2b07)
Location: net/ipv4/tcp.c:3325
Inline: True
Inline callers:
  - net/ipv4/tcp.c:do_tcp_setsockopt
  - net/ipv4/tcp.c:tcp_sock_set_cork
Direct callers:
  - net/ipv4/tcp.c:do_tcp_setsockopt
  - net/ipv4/tcp.c:tcp_sock_set_cork
  - net/mptcp/sockopt.c:sync_socket_options
  - net/mptcp/sockopt.c:mptcp_setsockopt_sol_tcp
```
**Symbols:**

```
ffffffff81eab940-ffffffff81eab9c1: __tcp_sock_set_cork.part.0 (STB_LOCAL)
ffffffff81eb2380-ffffffff81eb241d: __tcp_sock_set_cork (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

```c
void __tcp_sock_set_cork(struct sock *sk, bool on);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv4/tcp.c (ffffffff81f11649)
Location: net/ipv4/tcp.c:3217
Inline: True
Inline callers:
  - net/ipv4/tcp.c:do_tcp_setsockopt
  - net/ipv4/tcp.c:tcp_sock_set_cork
Direct callers:
  - net/ipv4/tcp.c:do_tcp_setsockopt
  - net/ipv4/tcp.c:tcp_sock_set_cork
  - net/mptcp/sockopt.c:sync_socket_options
  - net/mptcp/sockopt.c:mptcp_setsockopt_sol_tcp
```
**Symbols:**

```
ffffffff81f0a110-ffffffff81f0a189: __tcp_sock_set_cork.part.0 (STB_LOCAL)
ffffffff81f10a70-ffffffff81f10b05: __tcp_sock_set_cork (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
void __tcp_sock_set_cork(struct sock *sk, bool on);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv4/tcp.c (ffffffff81fd59af)
Location: net/ipv4/tcp.c:3223
Inline: True
Inline callers:
  - net/ipv4/tcp.c:do_tcp_setsockopt
  - net/ipv4/tcp.c:tcp_sock_set_cork
Direct callers:
  - net/ipv4/tcp.c:do_tcp_setsockopt
  - net/ipv4/tcp.c:tcp_sock_set_cork
  - net/mptcp/sockopt.c:mptcp_setsockopt_sol_tcp
```
**Symbols:**

```
ffffffff81fce220-ffffffff81fce299: __tcp_sock_set_cork.part.0 (STB_LOCAL)
ffffffff81fd4c50-ffffffff81fd4ce5: __tcp_sock_set_cork (STB_GLOBAL)
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
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
