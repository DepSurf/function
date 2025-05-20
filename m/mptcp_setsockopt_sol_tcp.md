# Function: <code>mptcp_setsockopt_sol_tcp</code>

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
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/mptcp/sockopt.c (ffffffff81bbc899)
Location: net/mptcp/sockopt.c:556
Inline: True
Inline callers:
  - net/mptcp/sockopt.c:mptcp_setsockopt
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
In net/mptcp/sockopt.c (ffffffff81c8c690)
Location: net/mptcp/sockopt.c:598
Inline: True
Inline callers:
  - net/mptcp/sockopt.c:mptcp_setsockopt
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int mptcp_setsockopt_sol_tcp(struct mptcp_sock *msk, int optname, sockptr_t optval, unsigned int optlen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/mptcp/sockopt.c (ffffffff81e34220)
Location: net/mptcp/sockopt.c:771
Inline: False
Direct callers:
  - net/mptcp/sockopt.c:mptcp_setsockopt
```
**Symbols:**

```
ffffffff81e34220-ffffffff81e3456a: mptcp_setsockopt_sol_tcp (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int mptcp_setsockopt_sol_tcp(struct mptcp_sock *msk, int optname, sockptr_t optval, unsigned int optlen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/mptcp/sockopt.c (ffffffff8200d2c0)
Location: net/mptcp/sockopt.c:780
Inline: False
Direct callers:
  - net/mptcp/sockopt.c:mptcp_setsockopt
```
**Symbols:**

```
ffffffff8200d2c0-ffffffff8200d690: mptcp_setsockopt_sol_tcp (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int mptcp_setsockopt_sol_tcp(struct mptcp_sock *msk, int optname, sockptr_t optval, unsigned int optlen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/mptcp/sockopt.c (ffffffff82089c50)
Location: net/mptcp/sockopt.c:784
Inline: False
Direct callers:
  - net/mptcp/sockopt.c:mptcp_setsockopt
```
**Symbols:**

```
ffffffff82089c50-ffffffff8208a012: mptcp_setsockopt_sol_tcp (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int mptcp_setsockopt_sol_tcp(struct mptcp_sock *msk, int optname, sockptr_t optval, unsigned int optlen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/mptcp/sockopt.c (ffffffff8215f740)
Location: net/mptcp/sockopt.c:799
Inline: False
Direct callers:
  - net/mptcp/sockopt.c:mptcp_setsockopt
```
**Symbols:**

```
ffffffff8215f740-ffffffff8215fb00: mptcp_setsockopt_sol_tcp (STB_LOCAL)
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
