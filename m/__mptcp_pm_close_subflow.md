# Function: <code>__mptcp_pm_close_subflow</code>

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
<summary>In <code>5.19</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/mptcp/subflow.c (ffffffff81e283ba)
Location: net/mptcp/protocol.h:897
Inline: True
Inline callers:
  - net/mptcp/subflow.c:__mptcp_subflow_connect
```
```
In net/mptcp/pm.c (ffffffff81e2ce8e)
Location: net/mptcp/protocol.h:897
Inline: True
Inline callers:
  - net/mptcp/pm.c:mptcp_pm_subflow_check_next
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/mptcp/subflow.c (ffffffff8200032a)
Location: net/mptcp/protocol.h:929
Inline: True
Inline callers:
  - net/mptcp/subflow.c:__mptcp_subflow_connect
```
```
In net/mptcp/pm.c (ffffffff8200525e)
Location: net/mptcp/protocol.h:929
Inline: True
Inline callers:
  - net/mptcp/pm.c:mptcp_pm_subflow_check_next
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/mptcp/subflow.c (ffffffff8207c4fa)
Location: net/mptcp/protocol.h:942
Inline: True
Inline callers:
  - net/mptcp/subflow.c:__mptcp_subflow_connect
```
```
In net/mptcp/pm.c (ffffffff82081436)
Location: net/mptcp/protocol.h:942
Inline: True
Inline callers:
  - net/mptcp/pm.c:mptcp_pm_subflow_check_next
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/mptcp/subflow.c (ffffffff821519da)
Location: net/mptcp/protocol.h:1045
Inline: True
Inline callers:
  - net/mptcp/subflow.c:__mptcp_subflow_connect
```
```
In net/mptcp/pm.c (ffffffff82156a56)
Location: net/mptcp/protocol.h:1045
Inline: True
Inline callers:
  - net/mptcp/pm.c:mptcp_pm_subflow_check_next
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
