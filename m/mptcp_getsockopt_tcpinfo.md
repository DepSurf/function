# Function: <code>mptcp_getsockopt_tcpinfo</code>

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
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int mptcp_getsockopt_tcpinfo(struct mptcp_sock *msk, char *optval, int *optlen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/mptcp/sockopt.c (ffffffff81e33b80)
Location: net/mptcp/sockopt.c:977
Inline: False
Direct callers:
  - net/mptcp/sockopt.c:mptcp_getsockopt
```
**Symbols:**

```
ffffffff81e33b80-ffffffff81e33d8b: mptcp_getsockopt_tcpinfo (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int mptcp_getsockopt_tcpinfo(struct mptcp_sock *msk, char *optval, int *optlen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/mptcp/sockopt.c (ffffffff8200bcb0)
Location: net/mptcp/sockopt.c:994
Inline: False
Direct callers:
  - net/mptcp/sockopt.c:mptcp_getsockopt
```
**Symbols:**

```
ffffffff8200bcb0-ffffffff8200bebb: mptcp_getsockopt_tcpinfo (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int mptcp_getsockopt_tcpinfo(struct mptcp_sock *msk, char *optval, int *optlen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/mptcp/sockopt.c (ffffffff820881a0)
Location: net/mptcp/sockopt.c:1022
Inline: False
Direct callers:
  - net/mptcp/sockopt.c:mptcp_getsockopt
```
**Symbols:**

```
ffffffff820881a0-ffffffff820883ab: mptcp_getsockopt_tcpinfo (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int mptcp_getsockopt_tcpinfo(struct mptcp_sock *msk, char *optval, int *optlen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/mptcp/sockopt.c (ffffffff8215dd90)
Location: net/mptcp/sockopt.c:1038
Inline: False
Direct callers:
  - net/mptcp/sockopt.c:mptcp_getsockopt
```
**Symbols:**

```
ffffffff8215dd90-ffffffff8215df9b: mptcp_getsockopt_tcpinfo (STB_LOCAL)
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
