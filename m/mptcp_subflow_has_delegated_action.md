# Function: <code>mptcp_subflow_has_delegated_action</code>

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
<summary>In <code>5.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/mptcp/protocol.c (ffffffff81bb0aab)
Location: net/mptcp/protocol.h:519
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_napi_poll
```
```
In net/mptcp/subflow.c (ffffffff81bb0f54)
Location: net/mptcp/protocol.h:519
Inline: True
Inline callers:
  - net/mptcp/subflow.c:tcp_release_cb_override
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/mptcp/protocol.c (ffffffff81c7eb6b)
Location: net/mptcp/protocol.h:549
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_napi_poll
```
```
In net/mptcp/subflow.c (ffffffff81c7f034)
Location: net/mptcp/protocol.h:549
Inline: True
Inline callers:
  - net/mptcp/subflow.c:tcp_release_cb_override
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/mptcp/protocol.c (ffffffff81e24318)
Location: net/mptcp/protocol.h:580
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_napi_poll
```
```
In net/mptcp/subflow.c (ffffffff81e24904)
Location: net/mptcp/protocol.h:580
Inline: True
Inline callers:
  - net/mptcp/subflow.c:tcp_release_cb_override
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
In net/mptcp/protocol.c (ffffffff81ffbdf8)
Location: net/mptcp/protocol.h:598
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_napi_poll
```
```
In net/mptcp/subflow.c (ffffffff81ffc484)
Location: net/mptcp/protocol.h:598
Inline: True
Inline callers:
  - net/mptcp/subflow.c:tcp_release_cb_override
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
In net/mptcp/protocol.c (ffffffff820781c8)
Location: net/mptcp/protocol.h:603
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_napi_poll
```
```
In net/mptcp/subflow.c (ffffffff820787d4)
Location: net/mptcp/protocol.h:603
Inline: True
Inline callers:
  - net/mptcp/subflow.c:tcp_release_cb_override
```
</details>
</li>
<li>
In <code>6.8</code>: Absent ⚠️
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
