# Function: <code>mptcp_pm_nl_mp_prio_send_ack</code>

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
int mptcp_pm_nl_mp_prio_send_ack(struct mptcp_sock *msk, struct mptcp_addr_info *addr, u8 bkup);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/mptcp/pm_netlink.c (ffffffff81bbad30)
Location: net/mptcp/pm_netlink.c:558
Inline: False
Direct callers:
  - net/mptcp/pm_netlink.c:mptcp_nl_cmd_set_flags
```
**Symbols:**

```
ffffffff81bbad30-ffffffff81bbaef1: mptcp_pm_nl_mp_prio_send_ack (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int mptcp_pm_nl_mp_prio_send_ack(struct mptcp_sock *msk, struct mptcp_addr_info *addr, u8 bkup);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/mptcp/pm_netlink.c (ffffffff81c8a7e0)
Location: net/mptcp/pm_netlink.c:678
Inline: False
Direct callers:
  - net/mptcp/pm_netlink.c:mptcp_nl_cmd_set_flags
```
**Symbols:**

```
ffffffff81c8a7e0-ffffffff81c8a978: mptcp_pm_nl_mp_prio_send_ack (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int mptcp_pm_nl_mp_prio_send_ack(struct mptcp_sock *msk, struct mptcp_addr_info *addr, struct mptcp_addr_info *rem, u8 bkup);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/mptcp/pm_netlink.c (ffffffff81e30e30)
Location: net/mptcp/pm_netlink.c:720
Inline: False
Direct callers:
  - net/mptcp/pm_netlink.c:mptcp_nl_cmd_set_flags
  - net/mptcp/pm_userspace.c:mptcp_userspace_pm_set_flags
```
**Symbols:**

```
ffffffff81e30e30-ffffffff81e310bb: mptcp_pm_nl_mp_prio_send_ack (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int mptcp_pm_nl_mp_prio_send_ack(struct mptcp_sock *msk, struct mptcp_addr_info *addr, struct mptcp_addr_info *rem, u8 bkup);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/mptcp/pm_netlink.c (ffffffff82009490)
Location: net/mptcp/pm_netlink.c:738
Inline: False
Direct callers:
  - net/mptcp/pm_netlink.c:mptcp_nl_cmd_set_flags
  - net/mptcp/pm_userspace.c:mptcp_userspace_pm_set_flags
```
**Symbols:**

```
ffffffff82009490-ffffffff82009682: mptcp_pm_nl_mp_prio_send_ack (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int mptcp_pm_nl_mp_prio_send_ack(struct mptcp_sock *msk, struct mptcp_addr_info *addr, struct mptcp_addr_info *rem, u8 bkup);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/mptcp/pm_netlink.c (ffffffff820858d0)
Location: net/mptcp/pm_netlink.c:741
Inline: False
Direct callers:
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_set_flags
  - net/mptcp/pm_userspace.c:mptcp_userspace_pm_set_flags
```
**Symbols:**

```
ffffffff820858d0-ffffffff82085ac2: mptcp_pm_nl_mp_prio_send_ack (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int mptcp_pm_nl_mp_prio_send_ack(struct mptcp_sock *msk, struct mptcp_addr_info *addr, struct mptcp_addr_info *rem, u8 bkup);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/mptcp/pm_netlink.c (ffffffff8215aa50)
Location: net/mptcp/pm_netlink.c:742
Inline: False
Direct callers:
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_set_flags
  - net/mptcp/pm_userspace.c:mptcp_userspace_pm_set_flags
```
**Symbols:**

```
ffffffff8215aa50-ffffffff8215ac42: mptcp_pm_nl_mp_prio_send_ack (STB_GLOBAL)
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
<code>struct mptcp_addr_info *rem</code>
</li>
<li>
<b>Param reordered. </b>
<code>msk, addr, bkup</code> ➡️ <code>msk, addr, rem, bkup</code>
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
