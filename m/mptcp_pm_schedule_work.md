# Function: <code>mptcp_pm_schedule_work</code>

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
bool mptcp_pm_schedule_work(struct mptcp_sock *msk, enum mptcp_pm_status new_status);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/mptcp/pm.c (ffffffff81bb2240)
Location: net/mptcp/pm.c:72
Inline: False
Direct callers:
  - net/mptcp/pm.c:mptcp_pm_add_addr_received
  - net/mptcp/pm.c:mptcp_pm_subflow_established
  - net/mptcp/pm.c:mptcp_pm_fully_established
```
**Symbols:**

```
ffffffff81bb2240-ffffffff81bb232c: mptcp_pm_schedule_work (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
bool mptcp_pm_schedule_work(struct mptcp_sock *msk, enum mptcp_pm_status new_status);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/mptcp/pm.c (ffffffff81bc6580)
Location: net/mptcp/pm.c:106
Inline: True
Direct callers:
  - net/mptcp/pm.c:mptcp_pm_rm_addr_received
  - net/mptcp/pm.c:mptcp_pm_add_addr_received
  - net/mptcp/pm.c:mptcp_pm_add_addr_received
  - net/mptcp/pm.c:mptcp_pm_subflow_established
  - net/mptcp/pm.c:mptcp_pm_fully_established
```
**Symbols:**

```
ffffffff81bc6580-ffffffff81bc6603: mptcp_pm_schedule_work (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
bool mptcp_pm_schedule_work(struct mptcp_sock *msk, enum mptcp_pm_status new_status);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/mptcp/pm.c (ffffffff81bb70e0)
Location: net/mptcp/pm.c:111
Inline: True
Direct callers:
  - net/mptcp/pm.c:mptcp_pm_rm_addr_received
  - net/mptcp/pm.c:mptcp_pm_add_addr_echoed
  - net/mptcp/pm.c:mptcp_pm_add_addr_received
  - net/mptcp/pm.c:mptcp_pm_add_addr_received
  - net/mptcp/pm.c:mptcp_pm_subflow_established
  - net/mptcp/pm.c:mptcp_pm_fully_established
```
**Symbols:**

```
ffffffff81bb70e0-ffffffff81bb7163: mptcp_pm_schedule_work (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
bool mptcp_pm_schedule_work(struct mptcp_sock *msk, enum mptcp_pm_status new_status);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/mptcp/pm.c (ffffffff81c86400)
Location: net/mptcp/pm.c:113
Inline: True
Direct callers:
  - net/mptcp/pm.c:mptcp_pm_rm_addr_received
  - net/mptcp/pm.c:mptcp_pm_add_addr_echoed
  - net/mptcp/pm.c:mptcp_pm_add_addr_received
  - net/mptcp/pm.c:mptcp_pm_add_addr_received
  - net/mptcp/pm.c:mptcp_pm_subflow_established
  - net/mptcp/pm.c:mptcp_pm_fully_established
```
**Symbols:**

```
ffffffff81c86400-ffffffff81c86480: mptcp_pm_schedule_work (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
bool mptcp_pm_schedule_work(struct mptcp_sock *msk, enum mptcp_pm_status new_status);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/mptcp/pm.c (ffffffff81e2c830)
Location: net/mptcp/pm.c:116
Inline: True
Direct callers:
  - net/mptcp/pm.c:mptcp_pm_rm_addr_received
  - net/mptcp/pm.c:mptcp_pm_add_addr_echoed
  - net/mptcp/pm.c:mptcp_pm_add_addr_received
  - net/mptcp/pm.c:mptcp_pm_add_addr_received
  - net/mptcp/pm.c:mptcp_pm_subflow_check_next
  - net/mptcp/pm.c:mptcp_pm_subflow_established
  - net/mptcp/pm.c:mptcp_pm_fully_established
```
**Symbols:**

```
ffffffff81e2c830-ffffffff81e2c8b8: mptcp_pm_schedule_work (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
bool mptcp_pm_schedule_work(struct mptcp_sock *msk, enum mptcp_pm_status new_status);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/mptcp/pm.c (ffffffff82004b30)
Location: net/mptcp/pm.c:116
Inline: True
Direct callers:
  - net/mptcp/pm.c:mptcp_pm_rm_addr_received
  - net/mptcp/pm.c:mptcp_pm_add_addr_echoed
  - net/mptcp/pm.c:mptcp_pm_add_addr_received
  - net/mptcp/pm.c:mptcp_pm_add_addr_received
  - net/mptcp/pm.c:mptcp_pm_subflow_check_next
  - net/mptcp/pm.c:mptcp_pm_subflow_established
  - net/mptcp/pm.c:mptcp_pm_fully_established
```
**Symbols:**

```
ffffffff82004b30-ffffffff82004bb8: mptcp_pm_schedule_work (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
bool mptcp_pm_schedule_work(struct mptcp_sock *msk, enum mptcp_pm_status new_status);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/mptcp/pm.c (ffffffff82080cd0)
Location: net/mptcp/pm.c:125
Inline: True
Direct callers:
  - net/mptcp/pm.c:mptcp_pm_rm_addr_received
  - net/mptcp/pm.c:mptcp_pm_add_addr_echoed
  - net/mptcp/pm.c:mptcp_pm_add_addr_received
  - net/mptcp/pm.c:mptcp_pm_add_addr_received
  - net/mptcp/pm.c:mptcp_pm_subflow_check_next
  - net/mptcp/pm.c:mptcp_pm_subflow_established
  - net/mptcp/pm.c:mptcp_pm_fully_established
```
**Symbols:**

```
ffffffff82080cd0-ffffffff82080d58: mptcp_pm_schedule_work (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
bool mptcp_pm_schedule_work(struct mptcp_sock *msk, enum mptcp_pm_status new_status);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/mptcp/pm.c (ffffffff821562f0)
Location: net/mptcp/pm.c:125
Inline: True
Direct callers:
  - net/mptcp/pm.c:mptcp_pm_rm_addr_received
  - net/mptcp/pm.c:mptcp_pm_add_addr_echoed
  - net/mptcp/pm.c:mptcp_pm_add_addr_received
  - net/mptcp/pm.c:mptcp_pm_add_addr_received
  - net/mptcp/pm.c:mptcp_pm_subflow_check_next
  - net/mptcp/pm.c:mptcp_pm_subflow_established
  - net/mptcp/pm.c:mptcp_pm_fully_established
```
**Symbols:**

```
ffffffff821562f0-ffffffff82156378: mptcp_pm_schedule_work (STB_LOCAL)
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
