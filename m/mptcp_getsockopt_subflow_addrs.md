# Function: <code>mptcp_getsockopt_subflow_addrs</code>

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
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int mptcp_getsockopt_subflow_addrs(struct mptcp_sock *msk, char *optval, int *optlen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/mptcp/sockopt.c (0)
Location: net/mptcp/sockopt.c:1069
Inline: False
Direct callers:
  - net/mptcp/sockopt.c:mptcp_getsockopt
```
**Symbols:**

```
ffffffff81e33860-ffffffff81e33b7f: mptcp_getsockopt_subflow_addrs (STB_LOCAL)
ffffffff81f10bf7-ffffffff81f10c2d: mptcp_getsockopt_subflow_addrs.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int mptcp_getsockopt_subflow_addrs(struct mptcp_sock *msk, char *optval, int *optlen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/mptcp/sockopt.c (0)
Location: net/mptcp/sockopt.c:1086
Inline: False
Direct callers:
  - net/mptcp/sockopt.c:mptcp_getsockopt
```
**Symbols:**

```
ffffffff8200b980-ffffffff8200bc9f: mptcp_getsockopt_subflow_addrs (STB_LOCAL)
ffffffff820b6eb3-ffffffff820b6ee9: mptcp_getsockopt_subflow_addrs.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int mptcp_getsockopt_subflow_addrs(struct mptcp_sock *msk, char *optval, int *optlen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/mptcp/sockopt.c (ffffffff82087f80)
Location: net/mptcp/sockopt.c:1114
Inline: False
Direct callers:
  - net/mptcp/sockopt.c:mptcp_getsockopt
```
**Symbols:**

```
ffffffff82087f80-ffffffff8208818b: mptcp_getsockopt_subflow_addrs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int mptcp_getsockopt_subflow_addrs(struct mptcp_sock *msk, char *optval, int *optlen);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/mptcp/sockopt.c (ffffffff8215db70)
Location: net/mptcp/sockopt.c:1130
Inline: False
Direct callers:
  - net/mptcp/sockopt.c:mptcp_getsockopt
```
**Symbols:**

```
ffffffff8215db70-ffffffff8215dd7b: mptcp_getsockopt_subflow_addrs (STB_LOCAL)
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
