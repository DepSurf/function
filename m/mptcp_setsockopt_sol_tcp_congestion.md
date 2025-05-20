# Function: <code>mptcp_setsockopt_sol_tcp_congestion</code>

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
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int mptcp_setsockopt_sol_tcp_congestion(struct mptcp_sock *msk, sockptr_t optval, unsigned int optlen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/mptcp/sockopt.c (0)
Location: net/mptcp/sockopt.c:513
Inline: False
Direct callers:
  - net/mptcp/sockopt.c:mptcp_setsockopt
```
**Symbols:**

```
ffffffff81bbbc70-ffffffff81bbbf8a: mptcp_setsockopt_sol_tcp_congestion (STB_LOCAL)
ffffffff81c26319-ffffffff81c26331: mptcp_setsockopt_sol_tcp_congestion.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int mptcp_setsockopt_sol_tcp_congestion(struct mptcp_sock *msk, sockptr_t optval, unsigned int optlen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/mptcp/sockopt.c (0)
Location: net/mptcp/sockopt.c:555
Inline: False
Direct callers:
  - net/mptcp/sockopt.c:mptcp_setsockopt
```
**Symbols:**

```
ffffffff81c8b7f0-ffffffff81c8bb28: mptcp_setsockopt_sol_tcp_congestion (STB_LOCAL)
ffffffff81d44065-ffffffff81d4407d: mptcp_setsockopt_sol_tcp_congestion.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int mptcp_setsockopt_sol_tcp_congestion(struct mptcp_sock *msk, sockptr_t optval, unsigned int optlen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/mptcp/sockopt.c (0)
Location: net/mptcp/sockopt.c:577
Inline: False
Direct callers:
  - net/mptcp/sockopt.c:mptcp_setsockopt_sol_tcp
```
**Symbols:**

```
ffffffff81e32e60-ffffffff81e3319d: mptcp_setsockopt_sol_tcp_congestion (STB_LOCAL)
ffffffff81f10bb5-ffffffff81f10bcd: mptcp_setsockopt_sol_tcp_congestion.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int mptcp_setsockopt_sol_tcp_congestion(struct mptcp_sock *msk, sockptr_t optval, unsigned int optlen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/mptcp/sockopt.c (ffffffff8200bed0)
Location: net/mptcp/sockopt.c:578
Inline: False
Direct callers:
  - net/mptcp/sockopt.c:mptcp_setsockopt_sol_tcp
```
**Symbols:**

```
ffffffff8200bed0-ffffffff8200c20b: mptcp_setsockopt_sol_tcp_congestion (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int mptcp_setsockopt_sol_tcp_congestion(struct mptcp_sock *msk, sockptr_t optval, unsigned int optlen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/mptcp/sockopt.c (ffffffff820883c0)
Location: net/mptcp/sockopt.c:580
Inline: False
Direct callers:
  - net/mptcp/sockopt.c:mptcp_setsockopt_sol_tcp
```
**Symbols:**

```
ffffffff820883c0-ffffffff820886fb: mptcp_setsockopt_sol_tcp_congestion (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int mptcp_setsockopt_sol_tcp_congestion(struct mptcp_sock *msk, sockptr_t optval, unsigned int optlen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/mptcp/sockopt.c (ffffffff8215dfb0)
Location: net/mptcp/sockopt.c:584
Inline: False
Direct callers:
  - net/mptcp/sockopt.c:mptcp_setsockopt_sol_tcp
```
**Symbols:**

```
ffffffff8215dfb0-ffffffff8215e2eb: mptcp_setsockopt_sol_tcp_congestion (STB_LOCAL)
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
