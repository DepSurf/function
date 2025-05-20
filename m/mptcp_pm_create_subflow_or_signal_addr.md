# Function: <code>mptcp_pm_create_subflow_or_signal_addr</code>

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
void mptcp_pm_create_subflow_or_signal_addr(struct mptcp_sock *msk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/mptcp/pm_netlink.c (ffffffff81bb3c90)
Location: net/mptcp/pm_netlink.c:172
Inline: False
```
**Symbols:**

```
ffffffff81bb3c90-ffffffff81bb3fd1: mptcp_pm_create_subflow_or_signal_addr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void mptcp_pm_create_subflow_or_signal_addr(struct mptcp_sock *msk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/mptcp/pm_netlink.c (ffffffff81bc8010)
Location: net/mptcp/pm_netlink.c:313
Inline: False
```
**Symbols:**

```
ffffffff81bc8010-ffffffff81bc8398: mptcp_pm_create_subflow_or_signal_addr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void mptcp_pm_create_subflow_or_signal_addr(struct mptcp_sock *msk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/mptcp/pm_netlink.c (ffffffff81bba420)
Location: net/mptcp/pm_netlink.c:413
Inline: False
Direct callers:
  - net/mptcp/pm_netlink.c:mptcp_nl_cmd_add_addr
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_work
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_work
```
**Symbols:**

```
ffffffff81bba420-ffffffff81bba833: mptcp_pm_create_subflow_or_signal_addr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void mptcp_pm_create_subflow_or_signal_addr(struct mptcp_sock *msk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/mptcp/pm_netlink.c (0)
Location: net/mptcp/pm_netlink.c:474
Inline: False
Direct callers:
  - net/mptcp/pm_netlink.c:mptcp_nl_cmd_add_addr
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_work
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_work
```
**Symbols:**

```
ffffffff81c89d50-ffffffff81c8a18d: mptcp_pm_create_subflow_or_signal_addr (STB_LOCAL)
ffffffff81d4403b-ffffffff81d44050: mptcp_pm_create_subflow_or_signal_addr.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void mptcp_pm_create_subflow_or_signal_addr(struct mptcp_sock *msk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/mptcp/pm_netlink.c (0)
Location: net/mptcp/pm_netlink.c:509
Inline: False
Direct callers:
  - net/mptcp/pm_netlink.c:mptcp_nl_cmd_set_flags
  - net/mptcp/pm_netlink.c:mptcp_nl_cmd_add_addr
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_work
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_work
```
**Symbols:**

```
ffffffff81e30150-ffffffff81e309fb: mptcp_pm_create_subflow_or_signal_addr (STB_LOCAL)
ffffffff81f10b53-ffffffff81f10b84: mptcp_pm_create_subflow_or_signal_addr.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void mptcp_pm_create_subflow_or_signal_addr(struct mptcp_sock *msk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/mptcp/pm_netlink.c (0)
Location: net/mptcp/pm_netlink.c:525
Inline: False
Direct callers:
  - net/mptcp/pm_netlink.c:mptcp_nl_cmd_set_flags
  - net/mptcp/pm_netlink.c:mptcp_nl_cmd_add_addr
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_work
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_work
```
**Symbols:**

```
ffffffff82008910-ffffffff8200903f: mptcp_pm_create_subflow_or_signal_addr (STB_LOCAL)
ffffffff820b6e4e-ffffffff820b6e62: mptcp_pm_create_subflow_or_signal_addr.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void mptcp_pm_create_subflow_or_signal_addr(struct mptcp_sock *msk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/mptcp/pm_netlink.c (0)
Location: net/mptcp/pm_netlink.c:521
Inline: False
Direct callers:
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_set_flags
  - net/mptcp/pm_netlink.c:mptcp_nl_cmd_add_addr
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_work
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_work
```
**Symbols:**

```
ffffffff82084d90-ffffffff82085492: mptcp_pm_create_subflow_or_signal_addr (STB_LOCAL)
ffffffff821381a6-ffffffff821381bb: mptcp_pm_create_subflow_or_signal_addr.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void mptcp_pm_create_subflow_or_signal_addr(struct mptcp_sock *msk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/mptcp/pm_netlink.c (ffffffff8215a550)
Location: net/mptcp/pm_netlink.c:522
Inline: False
Direct callers:
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_set_flags
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_add_addr_doit
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_work
  - net/mptcp/pm_netlink.c:mptcp_pm_nl_work
```
**Symbols:**

```
ffffffff8215a550-ffffffff8215aa37: mptcp_pm_create_subflow_or_signal_addr (STB_LOCAL)
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
