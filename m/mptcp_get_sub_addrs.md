# Function: <code>mptcp_get_sub_addrs</code>

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
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/mptcp/sockopt.c (ffffffff81e3394a)
Location: net/mptcp/sockopt.c:1030
Inline: True
Inline callers:
  - net/mptcp/sockopt.c:mptcp_getsockopt_subflow_addrs
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/mptcp/sockopt.c (ffffffff8200ba6a)
Location: net/mptcp/sockopt.c:1047
Inline: True
Inline callers:
  - net/mptcp/sockopt.c:mptcp_getsockopt_subflow_addrs
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void mptcp_get_sub_addrs(const struct sock *sk, struct mptcp_subflow_addrs *a);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/mptcp/sockopt.c (0)
Location: net/mptcp/sockopt.c:1075
Inline: False
Direct callers:
  - net/mptcp/sockopt.c:mptcp_getsockopt_full_info
  - net/mptcp/sockopt.c:mptcp_getsockopt_subflow_addrs
```
**Symbols:**

```
ffffffff82087d70-ffffffff82087ecd: mptcp_get_sub_addrs (STB_LOCAL)
ffffffff82138205-ffffffff8213821e: mptcp_get_sub_addrs.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void mptcp_get_sub_addrs(const struct sock *sk, struct mptcp_subflow_addrs *a);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/mptcp/sockopt.c (0)
Location: net/mptcp/sockopt.c:1091
Inline: False
Direct callers:
  - net/mptcp/sockopt.c:mptcp_getsockopt_full_info
  - net/mptcp/sockopt.c:mptcp_getsockopt_subflow_addrs
```
**Symbols:**

```
ffffffff8215d7c0-ffffffff8215d91d: mptcp_get_sub_addrs (STB_LOCAL)
ffffffff8221a025-ffffffff8221a03e: mptcp_get_sub_addrs.cold (STB_LOCAL)
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
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
