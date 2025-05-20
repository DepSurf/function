# Function: <code>mptcp_expand_seq</code>

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
In net/mptcp/subflow.c (ffffffff81bb2864)
Location: net/mptcp/protocol.h:607
Inline: True
Inline callers:
  - net/mptcp/subflow.c:get_mapping_status
```
```
In net/mptcp/options.c (ffffffff81bb5b0e)
Location: net/mptcp/protocol.h:607
Inline: True
Inline callers:
  - net/mptcp/options.c:mptcp_incoming_options
  - net/mptcp/options.c:mptcp_incoming_options
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
In net/mptcp/subflow.c (ffffffff81c80d26)
Location: net/mptcp/protocol.h:659
Inline: True
Inline callers:
  - net/mptcp/subflow.c:get_mapping_status
```
```
In net/mptcp/options.c (ffffffff81c84879)
Location: net/mptcp/protocol.h:659
Inline: True
Inline callers:
  - net/mptcp/options.c:mptcp_incoming_options
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
In net/mptcp/subflow.c (ffffffff81e26710)
Location: net/mptcp/protocol.h:687
Inline: True
Inline callers:
  - net/mptcp/subflow.c:get_mapping_status
```
```
In net/mptcp/options.c (ffffffff81e29b7a)
Location: net/mptcp/protocol.h:687
Inline: True
Inline callers:
  - net/mptcp/options.c:ack_update_msk
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
In net/mptcp/subflow.c (ffffffff81ffde46)
Location: net/mptcp/protocol.h:709
Inline: True
Inline callers:
  - net/mptcp/subflow.c:get_mapping_status
```
```
In net/mptcp/options.c (ffffffff82001c7a)
Location: net/mptcp/protocol.h:709
Inline: True
Inline callers:
  - net/mptcp/options.c:ack_update_msk
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
In net/mptcp/subflow.c (ffffffff8207a026)
Location: net/mptcp/protocol.h:718
Inline: True
Inline callers:
  - net/mptcp/subflow.c:get_mapping_status
```
```
In net/mptcp/options.c (ffffffff8207e13a)
Location: net/mptcp/protocol.h:718
Inline: True
Inline callers:
  - net/mptcp/options.c:ack_update_msk
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
In net/mptcp/subflow.c (ffffffff8214f486)
Location: net/mptcp/protocol.h:776
Inline: True
Inline callers:
  - net/mptcp/subflow.c:get_mapping_status
```
```
In net/mptcp/options.c (ffffffff8215362a)
Location: net/mptcp/protocol.h:776
Inline: True
Inline callers:
  - net/mptcp/options.c:ack_update_msk
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
