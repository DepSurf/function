# Function: <code>sock_set_timestamp</code>

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
<summary>In <code>5.15</code>: ✅</summary>

```c
void sock_set_timestamp(struct sock *sk, int optname, bool valbool);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff81a7e030)
Location: net/core/sock.c:798
Inline: False
Direct callers:
  - net/core/sock.c:sock_setsockopt
  - net/mptcp/sockopt.c:mptcp_setsockopt_sol_socket_int
```
**Symbols:**

```
ffffffff81a7e030-ffffffff81a7e0e7: sock_set_timestamp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void sock_set_timestamp(struct sock *sk, int optname, bool valbool);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff81bf0440)
Location: net/core/sock.c:838
Inline: False
Direct callers:
  - net/core/sock.c:sock_setsockopt
  - net/mptcp/sockopt.c:mptcp_setsockopt_sol_socket_int
```
**Symbols:**

```
ffffffff81bf0440-ffffffff81bf053d: sock_set_timestamp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void sock_set_timestamp(struct sock *sk, int optname, bool valbool);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff81d9bf10)
Location: net/core/sock.c:840
Inline: False
Direct callers:
  - net/core/sock.c:sk_setsockopt
  - net/mptcp/sockopt.c:mptcp_setsockopt_sol_socket_int
```
**Symbols:**

```
ffffffff81d9bf10-ffffffff81d9bfab: sock_set_timestamp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void sock_set_timestamp(struct sock *sk, int optname, bool valbool);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff81e0a750)
Location: net/core/sock.c:846
Inline: False
Direct callers:
  - net/core/sock.c:sk_setsockopt
  - net/mptcp/sockopt.c:mptcp_setsockopt_sol_socket_int
```
**Symbols:**

```
ffffffff81e0a750-ffffffff81e0a7e3: sock_set_timestamp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void sock_set_timestamp(struct sock *sk, int optname, bool valbool);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/sock.c (ffffffff81ec7140)
Location: net/core/sock.c:842
Inline: False
Direct callers:
  - net/core/sock.c:sk_setsockopt
  - net/mptcp/sockopt.c:mptcp_setsockopt_sol_socket_int
```
**Symbols:**

```
ffffffff81ec7140-ffffffff81ec71d3: sock_set_timestamp (STB_GLOBAL)
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
