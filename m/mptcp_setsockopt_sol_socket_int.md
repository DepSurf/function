# Function: <code>mptcp_setsockopt_sol_socket_int</code>

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
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int mptcp_setsockopt_sol_socket_int(struct mptcp_sock *msk, int optname, sockptr_t optval, unsigned int optlen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/mptcp/sockopt.c (ffffffff81bbc340)
Location: net/mptcp/sockopt.c:143
Inline: False
Direct callers:
  - net/mptcp/sockopt.c:mptcp_setsockopt_sol_socket
```
**Symbols:**

```
ffffffff81bbc340-ffffffff81bbc486: mptcp_setsockopt_sol_socket_int (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int mptcp_setsockopt_sol_socket_int(struct mptcp_sock *msk, int optname, sockptr_t optval, unsigned int optlen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/mptcp/sockopt.c (ffffffff81c8bee0)
Location: net/mptcp/sockopt.c:168
Inline: False
Direct callers:
  - net/mptcp/sockopt.c:mptcp_setsockopt_sol_socket
```
**Symbols:**

```
ffffffff81c8bee0-ffffffff81c8c11b: mptcp_setsockopt_sol_socket_int (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int mptcp_setsockopt_sol_socket_int(struct mptcp_sock *msk, int optname, sockptr_t optval, unsigned int optlen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/mptcp/sockopt.c (ffffffff81e33fd0)
Location: net/mptcp/sockopt.c:170
Inline: False
Direct callers:
  - net/mptcp/sockopt.c:mptcp_setsockopt_sol_socket
```
**Symbols:**

```
ffffffff81e33fd0-ffffffff81e34219: mptcp_setsockopt_sol_socket_int (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int mptcp_setsockopt_sol_socket_int(struct mptcp_sock *msk, int optname, sockptr_t optval, unsigned int optlen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/mptcp/sockopt.c (ffffffff8200cc90)
Location: net/mptcp/sockopt.c:170
Inline: False
Direct callers:
  - net/mptcp/sockopt.c:mptcp_setsockopt_sol_socket
```
**Symbols:**

```
ffffffff8200cc90-ffffffff8200ced9: mptcp_setsockopt_sol_socket_int (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int mptcp_setsockopt_sol_socket_int(struct mptcp_sock *msk, int optname, sockptr_t optval, unsigned int optlen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/mptcp/sockopt.c (ffffffff820895e0)
Location: net/mptcp/sockopt.c:171
Inline: False
Direct callers:
  - net/mptcp/sockopt.c:mptcp_setsockopt_sol_socket
```
**Symbols:**

```
ffffffff820895e0-ffffffff8208982f: mptcp_setsockopt_sol_socket_int (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int mptcp_setsockopt_sol_socket_int(struct mptcp_sock *msk, int optname, sockptr_t optval, unsigned int optlen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/mptcp/sockopt.c (ffffffff8215f0d0)
Location: net/mptcp/sockopt.c:172
Inline: False
Direct callers:
  - net/mptcp/sockopt.c:mptcp_setsockopt_sol_socket
```
**Symbols:**

```
ffffffff8215f0d0-ffffffff8215f31f: mptcp_setsockopt_sol_socket_int (STB_LOCAL)
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
