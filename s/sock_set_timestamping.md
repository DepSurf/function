# Function: <code>sock_set_timestamping</code>

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
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int sock_set_timestamping(struct sock *sk, int optname, struct so_timestamping timestamping);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/sock.c (0)
Location: net/core/sock.c:853
Inline: False
Direct callers:
  - net/core/sock.c:sock_setsockopt
  - net/mptcp/sockopt.c:mptcp_setsockopt_sol_socket
```
**Symbols:**

```
ffffffff81d34bbd-ffffffff81d34bf4: sock_set_timestamping.cold (STB_LOCAL)
ffffffff81a7dcc0-ffffffff81a7dea7: sock_set_timestamping (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int sock_set_timestamping(struct sock *sk, int optname, struct so_timestamping timestamping);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/sock.c (0)
Location: net/core/sock.c:893
Inline: False
Direct callers:
  - net/core/sock.c:sock_setsockopt
  - net/mptcp/sockopt.c:mptcp_setsockopt_sol_socket
```
**Symbols:**

```
ffffffff81f010ba-ffffffff81f010f1: sock_set_timestamping.cold (STB_LOCAL)
ffffffff81bf0540-ffffffff81bf0775: sock_set_timestamping (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int sock_set_timestamping(struct sock *sk, int optname, struct so_timestamping timestamping);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/sock.c (0)
Location: net/core/sock.c:895
Inline: False
Direct callers:
  - net/core/sock.c:sk_setsockopt
  - net/mptcp/sockopt.c:mptcp_setsockopt_sol_socket
```
**Symbols:**

```
ffffffff820aabd6-ffffffff820aabf0: sock_set_timestamping.cold (STB_LOCAL)
ffffffff81d9e760-ffffffff81d9e991: sock_set_timestamping (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int sock_set_timestamping(struct sock *sk, int optname, struct so_timestamping timestamping);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/sock.c (0)
Location: net/core/sock.c:901
Inline: False
Direct callers:
  - net/core/sock.c:sk_setsockopt
  - net/mptcp/sockopt.c:mptcp_setsockopt_sol_socket
```
**Symbols:**

```
ffffffff8212c0ea-ffffffff8212c103: sock_set_timestamping.cold (STB_LOCAL)
ffffffff81e0cf70-ffffffff81e0d19c: sock_set_timestamping (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int sock_set_timestamping(struct sock *sk, int optname, struct so_timestamping timestamping);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/sock.c (0)
Location: net/core/sock.c:897
Inline: False
Direct callers:
  - net/core/sock.c:sk_setsockopt
  - net/mptcp/sockopt.c:mptcp_setsockopt_sol_socket
```
**Symbols:**

```
ffffffff8220dd79-ffffffff8220dd92: sock_set_timestamping.cold (STB_LOCAL)
ffffffff81ec9900-ffffffff81ec9b3c: sock_set_timestamping (STB_GLOBAL)
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
