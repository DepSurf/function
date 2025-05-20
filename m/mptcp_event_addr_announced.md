# Function: <code>mptcp_event_addr_announced</code>

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
void mptcp_event_addr_announced(const struct mptcp_sock *msk, const struct mptcp_addr_info *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/mptcp/pm_netlink.c (ffffffff81bbb710)
Location: net/mptcp/pm_netlink.c:1741
Inline: False
Direct callers:
  - net/mptcp/pm.c:mptcp_pm_add_addr_received
```
**Symbols:**

```
ffffffff81bbb710-ffffffff81bbb8ef: mptcp_event_addr_announced (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void mptcp_event_addr_announced(const struct mptcp_sock *msk, const struct mptcp_addr_info *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/mptcp/pm_netlink.c (ffffffff81c8b350)
Location: net/mptcp/pm_netlink.c:1931
Inline: False
Direct callers:
  - net/mptcp/pm.c:mptcp_pm_add_addr_received
```
**Symbols:**

```
ffffffff81c8b350-ffffffff81c8b52f: mptcp_event_addr_announced (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void mptcp_event_addr_announced(const struct sock *ssk, const struct mptcp_addr_info *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/mptcp/pm_netlink.c (ffffffff81e328b0)
Location: net/mptcp/pm_netlink.c:2088
Inline: False
Direct callers:
  - net/mptcp/pm.c:mptcp_pm_add_addr_received
```
**Symbols:**

```
ffffffff81e328b0-ffffffff81e32ac3: mptcp_event_addr_announced (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void mptcp_event_addr_announced(const struct sock *ssk, const struct mptcp_addr_info *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/mptcp/pm_netlink.c (ffffffff8200ac30)
Location: net/mptcp/pm_netlink.c:2102
Inline: False
Direct callers:
  - net/mptcp/pm.c:mptcp_pm_add_addr_received
```
**Symbols:**

```
ffffffff8200ac30-ffffffff8200ae43: mptcp_event_addr_announced (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void mptcp_event_addr_announced(const struct sock *ssk, const struct mptcp_addr_info *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/mptcp/pm_netlink.c (ffffffff82087060)
Location: net/mptcp/pm_netlink.c:2118
Inline: False
Direct callers:
  - net/mptcp/pm.c:mptcp_pm_add_addr_received
```
**Symbols:**

```
ffffffff82087060-ffffffff82087273: mptcp_event_addr_announced (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void mptcp_event_addr_announced(const struct sock *ssk, const struct mptcp_addr_info *info);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/mptcp/pm_netlink.c (ffffffff8215c8e0)
Location: net/mptcp/pm_netlink.c:2117
Inline: False
Direct callers:
  - net/mptcp/pm.c:mptcp_pm_add_addr_received
```
**Symbols:**

```
ffffffff8215c8e0-ffffffff8215cacf: mptcp_event_addr_announced (STB_GLOBAL)
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
<details>
<summary>Changed between <code>5.15</code> and <code>5.19</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>const struct sock *ssk</code>
</li>
<li>
<b>Param removed. </b>
<code>const struct mptcp_sock *msk</code>
</li>
</ul>
</details>
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
