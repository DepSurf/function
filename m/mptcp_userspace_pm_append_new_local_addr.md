# Function: <code>mptcp_userspace_pm_append_new_local_addr</code>

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
int mptcp_userspace_pm_append_new_local_addr(struct mptcp_sock *msk, struct mptcp_pm_addr_entry *entry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/mptcp/pm_userspace.c (ffffffff81e35200)
Location: net/mptcp/pm_userspace.c:28
Inline: False
Direct callers:
  - net/mptcp/pm_userspace.c:mptcp_nl_cmd_announce
  - net/mptcp/pm_userspace.c:mptcp_userspace_pm_get_local_id
```
**Symbols:**

```
ffffffff81e35200-ffffffff81e353c5: mptcp_userspace_pm_append_new_local_addr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int mptcp_userspace_pm_append_new_local_addr(struct mptcp_sock *msk, struct mptcp_pm_addr_entry *entry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/mptcp/pm_userspace.c (ffffffff8200dea0)
Location: net/mptcp/pm_userspace.c:28
Inline: False
Direct callers:
  - net/mptcp/pm_userspace.c:mptcp_nl_cmd_announce
  - net/mptcp/pm_userspace.c:mptcp_userspace_pm_get_local_id
```
**Symbols:**

```
ffffffff8200dea0-ffffffff8200e04d: mptcp_userspace_pm_append_new_local_addr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int mptcp_userspace_pm_append_new_local_addr(struct mptcp_sock *msk, struct mptcp_pm_addr_entry *entry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/mptcp/pm_userspace.c (ffffffff8208a780)
Location: net/mptcp/pm_userspace.c:28
Inline: False
Direct callers:
  - net/mptcp/pm_userspace.c:mptcp_nl_cmd_sf_create
  - net/mptcp/pm_userspace.c:mptcp_nl_cmd_announce
  - net/mptcp/pm_userspace.c:mptcp_userspace_pm_get_local_id
```
**Symbols:**

```
ffffffff8208a780-ffffffff8208a930: mptcp_userspace_pm_append_new_local_addr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int mptcp_userspace_pm_append_new_local_addr(struct mptcp_sock *msk, struct mptcp_pm_addr_entry *entry, bool needs_id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/mptcp/pm_userspace.c (ffffffff82160330)
Location: net/mptcp/pm_userspace.c:28
Inline: False
Direct callers:
  - net/mptcp/pm_userspace.c:mptcp_pm_nl_subflow_create_doit
  - net/mptcp/pm_userspace.c:mptcp_pm_nl_announce_doit
  - net/mptcp/pm_userspace.c:mptcp_userspace_pm_get_local_id
```
**Symbols:**

```
ffffffff82160330-ffffffff821604f5: mptcp_userspace_pm_append_new_local_addr (STB_LOCAL)
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
<details>
<summary>Changed between <code>6.5</code> and <code>6.8</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>bool needs_id</code>
</li>
</ul>
</details>
</li>
</ul>
