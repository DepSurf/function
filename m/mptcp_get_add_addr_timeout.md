# Function: <code>mptcp_get_add_addr_timeout</code>

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
<summary>In <code>5.11</code>: ✅</summary>

```c
unsigned int mptcp_get_add_addr_timeout(struct net *net);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/mptcp/ctrl.c (ffffffff81bc6550)
Location: net/mptcp/ctrl.c:34
Inline: False
Direct callers:
  - net/mptcp/pm_netlink.c:mptcp_pm_alloc_anno_list
  - net/mptcp/pm_netlink.c:mptcp_pm_add_timer
```
**Symbols:**

```
ffffffff81bc6550-ffffffff81bc6579: mptcp_get_add_addr_timeout (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
unsigned int mptcp_get_add_addr_timeout(struct net *net);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/mptcp/ctrl.c (ffffffff81bb70b0)
Location: net/mptcp/ctrl.c:34
Inline: False
Direct callers:
  - net/mptcp/pm_netlink.c:mptcp_pm_create_subflow_or_signal_addr
  - net/mptcp/pm_netlink.c:mptcp_pm_add_timer
```
**Symbols:**

```
ffffffff81bb70b0-ffffffff81bb70d9: mptcp_get_add_addr_timeout (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
unsigned int mptcp_get_add_addr_timeout(const struct net *net);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/mptcp/ctrl.c (ffffffff81c86340)
Location: net/mptcp/ctrl.c:41
Inline: False
Direct callers:
  - net/mptcp/pm_netlink.c:mptcp_pm_create_subflow_or_signal_addr
  - net/mptcp/pm_netlink.c:mptcp_pm_add_timer
```
**Symbols:**

```
ffffffff81c86340-ffffffff81c86369: mptcp_get_add_addr_timeout (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
unsigned int mptcp_get_add_addr_timeout(const struct net *net);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/mptcp/ctrl.c (ffffffff81e2c6f0)
Location: net/mptcp/ctrl.c:47
Inline: False
Direct callers:
  - net/mptcp/pm_netlink.c:mptcp_pm_alloc_anno_list
  - net/mptcp/pm_netlink.c:mptcp_pm_alloc_anno_list
  - net/mptcp/pm_netlink.c:mptcp_pm_add_timer
```
**Symbols:**

```
ffffffff81e2c6f0-ffffffff81e2c729: mptcp_get_add_addr_timeout (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
unsigned int mptcp_get_add_addr_timeout(const struct net *net);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/mptcp/ctrl.c (ffffffff820049a0)
Location: net/mptcp/ctrl.c:47
Inline: False
Direct callers:
  - net/mptcp/pm_netlink.c:mptcp_pm_alloc_anno_list
  - net/mptcp/pm_netlink.c:mptcp_pm_alloc_anno_list
  - net/mptcp/pm_netlink.c:mptcp_pm_add_timer
```
**Symbols:**

```
ffffffff820049a0-ffffffff820049d9: mptcp_get_add_addr_timeout (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
unsigned int mptcp_get_add_addr_timeout(const struct net *net);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/mptcp/ctrl.c (ffffffff82080b40)
Location: net/mptcp/ctrl.c:47
Inline: False
Direct callers:
  - net/mptcp/pm_netlink.c:mptcp_pm_alloc_anno_list
  - net/mptcp/pm_netlink.c:mptcp_pm_alloc_anno_list
  - net/mptcp/pm_netlink.c:mptcp_pm_add_timer
```
**Symbols:**

```
ffffffff82080b40-ffffffff82080b79: mptcp_get_add_addr_timeout (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
unsigned int mptcp_get_add_addr_timeout(const struct net *net);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/mptcp/ctrl.c (ffffffff821560a0)
Location: net/mptcp/ctrl.c:49
Inline: False
Direct callers:
  - net/mptcp/pm_netlink.c:mptcp_pm_alloc_anno_list
  - net/mptcp/pm_netlink.c:mptcp_pm_alloc_anno_list
  - net/mptcp/pm_netlink.c:mptcp_pm_add_timer
```
**Symbols:**

```
ffffffff821560a0-ffffffff821560d9: mptcp_get_add_addr_timeout (STB_GLOBAL)
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
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.13</code> and <code>5.15</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>struct net *net</code> ➡️ <code>const struct net *net</code>
</li>
</ul>
</details>
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
