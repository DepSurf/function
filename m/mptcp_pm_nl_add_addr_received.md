# Function: <code>mptcp_pm_nl_add_addr_received</code>

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
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void mptcp_pm_nl_add_addr_received(struct mptcp_sock *msk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/mptcp/pm_netlink.c (ffffffff81bb4000)
Location: net/mptcp/pm_netlink.c:235
Inline: False
Direct callers:
  - net/mptcp/pm.c:pm_worker
```
**Symbols:**

```
ffffffff81bb4000-ffffffff81bb4143: mptcp_pm_nl_add_addr_received (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void mptcp_pm_nl_add_addr_received(struct mptcp_sock *msk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/mptcp/pm_netlink.c (ffffffff81bc8d60)
Location: net/mptcp/pm_netlink.c:378
Inline: False
Direct callers:
  - net/mptcp/protocol.c:pm_work
```
**Symbols:**

```
ffffffff81bc8d60-ffffffff81bc8ee9: mptcp_pm_nl_add_addr_received (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void mptcp_pm_nl_add_addr_received(struct mptcp_sock *msk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/mptcp/pm_netlink.c (ffffffff81bbaad0)
Location: net/mptcp/pm_netlink.c:486
Inline: False
Direct callers:
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_work
```
**Symbols:**

```
ffffffff81bbaad0-ffffffff81bbad27: mptcp_pm_nl_add_addr_received (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void mptcp_pm_nl_add_addr_received(struct mptcp_sock *msk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/mptcp/pm_netlink.c (ffffffff81c8a410)
Location: net/mptcp/pm_netlink.c:602
Inline: False
Direct callers:
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_work
```
**Symbols:**

```
ffffffff81c8a410-ffffffff81c8a7dc: mptcp_pm_nl_add_addr_received (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void mptcp_pm_nl_add_addr_received(struct mptcp_sock *msk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/mptcp/pm_netlink.c (ffffffff81e30a00)
Location: net/mptcp/pm_netlink.c:653
Inline: False
Direct callers:
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_work
```
**Symbols:**

```
ffffffff81e30a00-ffffffff81e30e2e: mptcp_pm_nl_add_addr_received (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void mptcp_pm_nl_add_addr_received(struct mptcp_sock *msk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/mptcp/pm_netlink.c (ffffffff82009050)
Location: net/mptcp/pm_netlink.c:679
Inline: False
Direct callers:
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_work
```
**Symbols:**

```
ffffffff82009050-ffffffff8200947e: mptcp_pm_nl_add_addr_received (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void mptcp_pm_nl_add_addr_received(struct mptcp_sock *msk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/mptcp/pm_netlink.c (ffffffff820854b0)
Location: net/mptcp/pm_netlink.c:680
Inline: False
Direct callers:
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_work
```
**Symbols:**

```
ffffffff820854b0-ffffffff820858b8: mptcp_pm_nl_add_addr_received (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void mptcp_pm_nl_add_addr_received(struct mptcp_sock *msk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/mptcp/pm_netlink.c (ffffffff8215a130)
Location: net/mptcp/pm_netlink.c:681
Inline: False
Direct callers:
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_work
```
**Symbols:**

```
ffffffff8215a130-ffffffff8215a538: mptcp_pm_nl_add_addr_received (STB_LOCAL)
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
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
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
