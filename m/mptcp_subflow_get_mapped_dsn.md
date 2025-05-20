# Function: <code>mptcp_subflow_get_mapped_dsn</code>

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
<summary>In <code>5.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/mptcp/protocol.c (ffffffff81bab773)
Location: net/mptcp/protocol.h:333
Inline: True
Inline callers:
  - net/mptcp/protocol.c:__mptcp_move_skbs_from_subflow
```
```
In net/mptcp/subflow.c (ffffffff81baf5ca)
Location: net/mptcp/protocol.h:333
Inline: True
Inline callers:
  - net/mptcp/subflow.c:subflow_check_data_avail
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/mptcp/protocol.c (ffffffff81bbd1b3)
Location: net/mptcp/protocol.h:446
Inline: True
Inline callers:
  - net/mptcp/protocol.c:__mptcp_move_skb
```
```
In net/mptcp/subflow.c (ffffffff81bc2289)
Location: net/mptcp/protocol.h:446
Inline: True
Inline callers:
  - net/mptcp/subflow.c:subflow_check_data_avail
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/mptcp/protocol.c (ffffffff81baca03)
Location: net/mptcp/protocol.h:464
Inline: True
Inline callers:
  - net/mptcp/protocol.c:__mptcp_move_skb
```
```
In net/mptcp/subflow.c (ffffffff81bb2d0c)
Location: net/mptcp/protocol.h:464
Inline: True
Inline callers:
  - net/mptcp/subflow.c:subflow_check_data_avail
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
In net/mptcp/protocol.c (ffffffff81c7939f)
Location: net/mptcp/protocol.h:494
Inline: True
Inline callers:
  - net/mptcp/protocol.c:__mptcp_move_skb
```
```
In net/mptcp/subflow.c (ffffffff81c812a8)
Location: net/mptcp/protocol.h:494
Inline: True
Inline callers:
  - net/mptcp/subflow.c:subflow_check_data_avail
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
In net/mptcp/protocol.c (ffffffff81e1e316)
Location: net/mptcp/protocol.h:534
Inline: True
Inline callers:
  - net/mptcp/protocol.c:__mptcp_move_skb
```
```
In net/mptcp/subflow.c (ffffffff81e26ce3)
Location: net/mptcp/protocol.h:534
Inline: True
Inline callers:
  - net/mptcp/subflow.c:subflow_check_data_avail
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
In net/mptcp/protocol.c (ffffffff81ff6d5c)
Location: net/mptcp/protocol.h:552
Inline: True
Inline callers:
  - net/mptcp/protocol.c:__mptcp_move_skb
```
```
In net/mptcp/subflow.c (ffffffff81ffe453)
Location: net/mptcp/protocol.h:552
Inline: True
Inline callers:
  - net/mptcp/subflow.c:subflow_check_data_avail
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
In net/mptcp/protocol.c (ffffffff8207343c)
Location: net/mptcp/protocol.h:557
Inline: True
Inline callers:
  - net/mptcp/protocol.c:__mptcp_move_skb
```
```
In net/mptcp/subflow.c (ffffffff8207a523)
Location: net/mptcp/protocol.h:557
Inline: True
Inline callers:
  - net/mptcp/subflow.c:subflow_check_data_avail
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
In net/mptcp/protocol.c (ffffffff8214768c)
Location: net/mptcp/protocol.h:570
Inline: True
Inline callers:
  - net/mptcp/protocol.c:__mptcp_move_skb
```
```
In net/mptcp/subflow.c (ffffffff8214f994)
Location: net/mptcp/protocol.h:570
Inline: True
Inline callers:
  - net/mptcp/subflow.c:subflow_check_data_avail
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
