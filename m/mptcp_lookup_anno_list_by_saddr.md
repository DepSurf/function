# Function: <code>mptcp_lookup_anno_list_by_saddr</code>

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
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
struct mptcp_pm_add_entry *mptcp_lookup_anno_list_by_saddr(struct mptcp_sock *msk, struct mptcp_addr_info *addr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/mptcp/pm_netlink.c (ffffffff81bba5c5)
Location: net/mptcp/pm_netlink.c:267
Inline: True
Inline callers:
  - net/mptcp/pm_netlink.c:mptcp_pm_create_subflow_or_signal_addr
  - net/mptcp/pm_netlink.c:mptcp_pm_del_add_timer
Direct callers:
  - net/mptcp/pm.c:mptcp_pm_add_addr_echoed
```
**Symbols:**

```
ffffffff81bb9820-ffffffff81bb987c: mptcp_lookup_anno_list_by_saddr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
struct mptcp_pm_add_entry *mptcp_lookup_anno_list_by_saddr(struct mptcp_sock *msk, struct mptcp_addr_info *addr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/mptcp/pm_netlink.c (ffffffff81c89f1c)
Location: net/mptcp/pm_netlink.c:267
Inline: True
Inline callers:
  - net/mptcp/pm_netlink.c:mptcp_pm_create_subflow_or_signal_addr
  - net/mptcp/pm_netlink.c:mptcp_pm_del_add_timer
Direct callers:
  - net/mptcp/pm.c:mptcp_pm_add_addr_echoed
```
**Symbols:**

```
ffffffff81c89130-ffffffff81c8918c: mptcp_lookup_anno_list_by_saddr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
struct mptcp_pm_add_entry *mptcp_lookup_anno_list_by_saddr(const struct mptcp_sock *msk, const struct mptcp_addr_info *addr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/mptcp/pm_netlink.c (ffffffff81e2fe52)
Location: net/mptcp/pm_netlink.c:256
Inline: True
Inline callers:
  - net/mptcp/pm_netlink.c:mptcp_pm_alloc_anno_list
  - net/mptcp/pm_netlink.c:mptcp_pm_del_add_timer
Direct callers:
  - net/mptcp/pm.c:mptcp_pm_add_addr_echoed
```
**Symbols:**

```
ffffffff81e2f890-ffffffff81e2f8fd: mptcp_lookup_anno_list_by_saddr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
struct mptcp_pm_add_entry *mptcp_lookup_anno_list_by_saddr(const struct mptcp_sock *msk, const struct mptcp_addr_info *addr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/mptcp/pm_netlink.c (ffffffff82008612)
Location: net/mptcp/pm_netlink.c:256
Inline: True
Inline callers:
  - net/mptcp/pm_netlink.c:mptcp_pm_alloc_anno_list
  - net/mptcp/pm_netlink.c:mptcp_pm_del_add_timer
Direct callers:
  - net/mptcp/pm.c:mptcp_pm_add_addr_echoed
```
**Symbols:**

```
ffffffff82008000-ffffffff8200806d: mptcp_lookup_anno_list_by_saddr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
struct mptcp_pm_add_entry *mptcp_lookup_anno_list_by_saddr(const struct mptcp_sock *msk, const struct mptcp_addr_info *addr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/mptcp/pm_netlink.c (ffffffff82084a9a)
Location: net/mptcp/pm_netlink.c:244
Inline: True
Inline callers:
  - net/mptcp/pm_netlink.c:mptcp_pm_alloc_anno_list
  - net/mptcp/pm_netlink.c:mptcp_pm_del_add_timer
Direct callers:
  - net/mptcp/pm.c:mptcp_pm_add_addr_echoed
```
**Symbols:**

```
ffffffff82084400-ffffffff8208446d: mptcp_lookup_anno_list_by_saddr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
struct mptcp_pm_add_entry *mptcp_lookup_anno_list_by_saddr(const struct mptcp_sock *msk, const struct mptcp_addr_info *addr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/mptcp/pm_netlink.c (ffffffff82159e0a)
Location: net/mptcp/pm_netlink.c:245
Inline: True
Inline callers:
  - net/mptcp/pm_netlink.c:mptcp_pm_alloc_anno_list
  - net/mptcp/pm_netlink.c:mptcp_pm_del_add_timer
Direct callers:
  - net/mptcp/pm.c:mptcp_pm_add_addr_echoed
```
**Symbols:**

```
ffffffff82159b60-ffffffff82159bcd: mptcp_lookup_anno_list_by_saddr (STB_GLOBAL)
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
<b>Param type changed. </b>
<code>struct mptcp_sock *msk</code> ➡️ <code>const struct mptcp_sock *msk</code>
</li>
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
