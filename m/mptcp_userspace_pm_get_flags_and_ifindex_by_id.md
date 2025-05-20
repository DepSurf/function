# Function: <code>mptcp_userspace_pm_get_flags_and_ifindex_by_id</code>

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
int mptcp_userspace_pm_get_flags_and_ifindex_by_id(struct mptcp_sock *msk, unsigned int id, u8 *flags, int *ifindex);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/mptcp/pm_userspace.c (ffffffff81e353d0)
Location: net/mptcp/pm_userspace.c:81
Inline: False
Direct callers:
  - net/mptcp/pm_netlink.c:mptcp_pm_get_flags_and_ifindex_by_id
```
**Symbols:**

```
ffffffff81e353d0-ffffffff81e3547b: mptcp_userspace_pm_get_flags_and_ifindex_by_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int mptcp_userspace_pm_get_flags_and_ifindex_by_id(struct mptcp_sock *msk, unsigned int id, u8 *flags, int *ifindex);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/mptcp/pm_userspace.c (ffffffff8200e060)
Location: net/mptcp/pm_userspace.c:81
Inline: False
Direct callers:
  - net/mptcp/pm_netlink.c:mptcp_pm_get_flags_and_ifindex_by_id
```
**Symbols:**

```
ffffffff8200e060-ffffffff8200e10b: mptcp_userspace_pm_get_flags_and_ifindex_by_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int mptcp_userspace_pm_get_flags_and_ifindex_by_id(struct mptcp_sock *msk, unsigned int id, u8 *flags, int *ifindex);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/mptcp/pm_userspace.c (ffffffff8208ab00)
Location: net/mptcp/pm_userspace.c:108
Inline: False
Direct callers:
  - net/mptcp/pm.c:mptcp_pm_get_flags_and_ifindex_by_id
```
**Symbols:**

```
ffffffff8208ab00-ffffffff8208ab9d: mptcp_userspace_pm_get_flags_and_ifindex_by_id (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int mptcp_userspace_pm_get_flags_and_ifindex_by_id(struct mptcp_sock *msk, unsigned int id, u8 *flags, int *ifindex);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/mptcp/pm_userspace.c (ffffffff821606d0)
Location: net/mptcp/pm_userspace.c:109
Inline: False
Direct callers:
  - net/mptcp/pm.c:mptcp_pm_get_flags_and_ifindex_by_id
```
**Symbols:**

```
ffffffff821606d0-ffffffff8216076d: mptcp_userspace_pm_get_flags_and_ifindex_by_id (STB_GLOBAL)
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
