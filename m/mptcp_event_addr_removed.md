# Function: <code>mptcp_event_addr_removed</code>

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
void mptcp_event_addr_removed(const struct mptcp_sock *msk, uint8_t id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/mptcp/pm_netlink.c (ffffffff81bbb5b0)
Location: net/mptcp/pm_netlink.c:1710
Inline: False
Direct callers:
  - net/mptcp/pm.c:mptcp_pm_rm_addr_received
```
**Symbols:**

```
ffffffff81bbb5b0-ffffffff81bbb70f: mptcp_event_addr_removed (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void mptcp_event_addr_removed(const struct mptcp_sock *msk, uint8_t id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/mptcp/pm_netlink.c (ffffffff81c8b1f0)
Location: net/mptcp/pm_netlink.c:1900
Inline: False
Direct callers:
  - net/mptcp/pm.c:mptcp_pm_rm_addr_received
```
**Symbols:**

```
ffffffff81c8b1f0-ffffffff81c8b34f: mptcp_event_addr_removed (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void mptcp_event_addr_removed(const struct mptcp_sock *msk, uint8_t id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/mptcp/pm_netlink.c (ffffffff81e32730)
Location: net/mptcp/pm_netlink.c:2057
Inline: False
Direct callers:
  - net/mptcp/pm.c:mptcp_pm_rm_addr_received
```
**Symbols:**

```
ffffffff81e32730-ffffffff81e328a8: mptcp_event_addr_removed (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void mptcp_event_addr_removed(const struct mptcp_sock *msk, uint8_t id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/mptcp/pm_netlink.c (ffffffff8200aaa0)
Location: net/mptcp/pm_netlink.c:2071
Inline: False
Direct callers:
  - net/mptcp/pm.c:mptcp_pm_rm_addr_received
```
**Symbols:**

```
ffffffff8200aaa0-ffffffff8200ac18: mptcp_event_addr_removed (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void mptcp_event_addr_removed(const struct mptcp_sock *msk, uint8_t id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/mptcp/pm_netlink.c (ffffffff82086ed0)
Location: net/mptcp/pm_netlink.c:2087
Inline: False
Direct callers:
  - net/mptcp/pm.c:mptcp_pm_rm_addr_received
```
**Symbols:**

```
ffffffff82086ed0-ffffffff82087048: mptcp_event_addr_removed (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void mptcp_event_addr_removed(const struct mptcp_sock *msk, uint8_t id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/mptcp/pm_netlink.c (ffffffff8215c770)
Location: net/mptcp/pm_netlink.c:2086
Inline: False
Direct callers:
  - net/mptcp/pm.c:mptcp_pm_rm_addr_received
```
**Symbols:**

```
ffffffff8215c770-ffffffff8215c8c3: mptcp_event_addr_removed (STB_GLOBAL)
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
