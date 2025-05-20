# Function: <code>mptcp_pm_del_add_timer</code>

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
struct mptcp_pm_add_entry *mptcp_pm_del_add_timer(struct mptcp_sock *msk, struct mptcp_addr_info *addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/mptcp/pm_netlink.c (ffffffff81bc8610)
Location: net/mptcp/pm_netlink.c:248
Inline: False
Direct callers:
  - net/mptcp/options.c:mptcp_incoming_options
```
**Symbols:**

```
ffffffff81bc8610-ffffffff81bc86d7: mptcp_pm_del_add_timer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct mptcp_pm_add_entry *mptcp_pm_del_add_timer(struct mptcp_sock *msk, struct mptcp_addr_info *addr, bool check_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/mptcp/pm_netlink.c (ffffffff81bb9960)
Location: net/mptcp/pm_netlink.c:348
Inline: False
Direct callers:
  - net/mptcp/options.c:mptcp_incoming_options
  - net/mptcp/pm_netlink.c:mptcp_nl_remove_addrs_list
```
**Symbols:**

```
ffffffff81bb9960-ffffffff81bb9a24: mptcp_pm_del_add_timer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct mptcp_pm_add_entry *mptcp_pm_del_add_timer(struct mptcp_sock *msk, struct mptcp_addr_info *addr, bool check_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/mptcp/pm_netlink.c (ffffffff81c89270)
Location: net/mptcp/pm_netlink.c:348
Inline: False
Direct callers:
  - net/mptcp/options.c:mptcp_incoming_options
  - net/mptcp/pm_netlink.c:mptcp_nl_remove_addrs_list
```
**Symbols:**

```
ffffffff81c89270-ffffffff81c89334: mptcp_pm_del_add_timer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct mptcp_pm_add_entry *mptcp_pm_del_add_timer(struct mptcp_sock *msk, const struct mptcp_addr_info *addr, bool check_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/mptcp/pm_netlink.c (ffffffff81e2fa10)
Location: net/mptcp/pm_netlink.c:337
Inline: False
Direct callers:
  - net/mptcp/options.c:mptcp_incoming_options
  - net/mptcp/pm_netlink.c:mptcp_pm_remove_addrs_and_subflows
```
**Symbols:**

```
ffffffff81e2fa10-ffffffff81e2fade: mptcp_pm_del_add_timer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct mptcp_pm_add_entry *mptcp_pm_del_add_timer(struct mptcp_sock *msk, const struct mptcp_addr_info *addr, bool check_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/mptcp/pm_netlink.c (ffffffff820081a0)
Location: net/mptcp/pm_netlink.c:337
Inline: False
Direct callers:
  - net/mptcp/options.c:mptcp_incoming_options
  - net/mptcp/pm_netlink.c:mptcp_pm_remove_addrs_and_subflows
```
**Symbols:**

```
ffffffff820081a0-ffffffff8200826e: mptcp_pm_del_add_timer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct mptcp_pm_add_entry *mptcp_pm_del_add_timer(struct mptcp_sock *msk, const struct mptcp_addr_info *addr, bool check_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/mptcp/pm_netlink.c (ffffffff820845a0)
Location: net/mptcp/pm_netlink.c:325
Inline: False
Direct callers:
  - net/mptcp/options.c:mptcp_incoming_options
  - net/mptcp/pm_netlink.c:mptcp_pm_remove_addrs_and_subflows
  - net/mptcp/pm_netlink.c:mptcp_pm_remove_addrs
```
**Symbols:**

```
ffffffff820845a0-ffffffff8208466e: mptcp_pm_del_add_timer (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct mptcp_pm_add_entry *mptcp_pm_del_add_timer(struct mptcp_sock *msk, const struct mptcp_addr_info *addr, bool check_id);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/mptcp/pm_netlink.c (ffffffff82159d00)
Location: net/mptcp/pm_netlink.c:326
Inline: False
Direct callers:
  - net/mptcp/options.c:mptcp_incoming_options
  - net/mptcp/pm_netlink.c:mptcp_pm_remove_addrs_and_subflows
  - net/mptcp/pm_netlink.c:mptcp_pm_remove_addrs
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_del_addr_doit
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_del_addr_doit
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_del_addr_doit
```
**Symbols:**

```
ffffffff82159d00-ffffffff82159dce: mptcp_pm_del_add_timer (STB_GLOBAL)
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
<details>
<summary>Changed between <code>5.11</code> and <code>5.13</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>bool check_id</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.15</code> and <code>5.19</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>struct mptcp_addr_info *addr</code> ➡️ <code>const struct mptcp_addr_info *addr</code>
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
