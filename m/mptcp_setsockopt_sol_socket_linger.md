# Function: <code>mptcp_setsockopt_sol_socket_linger</code>

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
int mptcp_setsockopt_sol_socket_linger(struct mptcp_sock *msk, sockptr_t optval, unsigned int optlen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/mptcp/sockopt.c (ffffffff81bbc490)
Location: net/mptcp/sockopt.c:172
Inline: False
Direct callers:
  - net/mptcp/sockopt.c:mptcp_setsockopt_sol_socket
```
**Symbols:**

```
ffffffff81bbc490-ffffffff81bbc613: mptcp_setsockopt_sol_socket_linger (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/mptcp/sockopt.c (ffffffff81c8c440)
Location: net/mptcp/sockopt.c:247
Inline: True
Inline callers:
  - net/mptcp/sockopt.c:mptcp_setsockopt_sol_socket
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/mptcp/sockopt.c (ffffffff81e3486f)
Location: net/mptcp/sockopt.c:249
Inline: True
Inline callers:
  - net/mptcp/sockopt.c:mptcp_setsockopt_sol_socket
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int mptcp_setsockopt_sol_socket_linger(struct mptcp_sock *msk, sockptr_t optval, unsigned int optlen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/mptcp/sockopt.c (ffffffff8200cae0)
Location: net/mptcp/sockopt.c:249
Inline: False
Direct callers:
  - net/mptcp/sockopt.c:mptcp_setsockopt_sol_socket
```
**Symbols:**

```
ffffffff8200cae0-ffffffff8200cc7c: mptcp_setsockopt_sol_socket_linger (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int mptcp_setsockopt_sol_socket_linger(struct mptcp_sock *msk, sockptr_t optval, unsigned int optlen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/mptcp/sockopt.c (ffffffff82089430)
Location: net/mptcp/sockopt.c:250
Inline: False
Direct callers:
  - net/mptcp/sockopt.c:mptcp_setsockopt_sol_socket
```
**Symbols:**

```
ffffffff82089430-ffffffff820895ca: mptcp_setsockopt_sol_socket_linger (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int mptcp_setsockopt_sol_socket_linger(struct mptcp_sock *msk, sockptr_t optval, unsigned int optlen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/mptcp/sockopt.c (ffffffff8215ef20)
Location: net/mptcp/sockopt.c:251
Inline: False
Direct callers:
  - net/mptcp/sockopt.c:mptcp_setsockopt_sol_socket
```
**Symbols:**

```
ffffffff8215ef20-ffffffff8215f0ba: mptcp_setsockopt_sol_socket_linger (STB_LOCAL)
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
