# Function: <code>strncpy_from_sockptr</code>

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
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp.c (ffffffff81ab94a2)
Location: include/linux/sockptr.h:94
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp.c (ffffffff81aa4731)
Location: include/linux/sockptr.h:94
Inline: True
```
```
In net/mptcp/sockopt.c (ffffffff81bbbcb3)
Location: include/linux/sockptr.h:94
Inline: True
Inline callers:
  - net/mptcp/sockopt.c:mptcp_setsockopt_sol_tcp_congestion
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff81231a27)
Location: include/linux/sockptr.h:94
Inline: True
Inline callers:
  - kernel/bpf/syscall.c:bpf_prog_load
```
```
In net/ipv4/tcp.c (ffffffff81b60952)
Location: include/linux/sockptr.h:94
Inline: True
```
```
In net/mptcp/sockopt.c (ffffffff81c8b833)
Location: include/linux/sockptr.h:94
Inline: True
Inline callers:
  - net/mptcp/sockopt.c:mptcp_setsockopt_sol_tcp_congestion
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp.c (ffffffff81cef43a)
Location: include/linux/sockptr.h:94
Inline: True
```
```
In net/mptcp/sockopt.c (ffffffff81e32eb4)
Location: include/linux/sockptr.h:94
Inline: True
Inline callers:
  - net/mptcp/sockopt.c:mptcp_setsockopt_sol_tcp_congestion
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp.c (ffffffff81eb27ab)
Location: include/linux/sockptr.h:99
Inline: True
Inline callers:
  - net/ipv4/tcp.c:do_tcp_setsockopt
  - net/ipv4/tcp.c:do_tcp_setsockopt
```
```
In net/mptcp/sockopt.c (ffffffff8200bf24)
Location: include/linux/sockptr.h:99
Inline: True
Inline callers:
  - net/mptcp/sockopt.c:mptcp_setsockopt_sol_tcp_congestion
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp.c (ffffffff81f10fcb)
Location: include/linux/sockptr.h:99
Inline: True
Inline callers:
  - net/ipv4/tcp.c:do_tcp_setsockopt
  - net/ipv4/tcp.c:do_tcp_setsockopt
```
```
In net/mptcp/sockopt.c (ffffffff82088414)
Location: include/linux/sockptr.h:99
Inline: True
Inline callers:
  - net/mptcp/sockopt.c:mptcp_setsockopt_sol_tcp_congestion
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/ipv4/tcp.c (ffffffff81fd5247)
Location: include/linux/sockptr.h:122
Inline: True
Inline callers:
  - net/ipv4/tcp.c:do_tcp_setsockopt
  - net/ipv4/tcp.c:do_tcp_setsockopt
```
```
In net/mptcp/sockopt.c (ffffffff8215e004)
Location: include/linux/sockptr.h:122
Inline: True
Inline callers:
  - net/mptcp/sockopt.c:mptcp_setsockopt_sol_tcp_congestion
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
