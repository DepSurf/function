# Function: <code>mptcp_subflow_get_map_offset</code>

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
In net/mptcp/protocol.c (ffffffff81bab7d4)
Location: net/mptcp/protocol.h:325
Inline: True
Inline callers:
  - net/mptcp/protocol.c:__mptcp_move_skbs_from_subflow
  - net/mptcp/protocol.c:__mptcp_move_skbs_from_subflow
```
```
In net/mptcp/subflow.c (ffffffff81baf821)
Location: net/mptcp/protocol.h:325
Inline: True
Inline callers:
  - net/mptcp/subflow.c:mptcp_subflow_data_available
  - net/mptcp/subflow.c:subflow_check_data_avail
  - net/mptcp/subflow.c:subflow_check_data_avail
  - net/mptcp/subflow.c:get_mapping_status
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
In net/mptcp/protocol.c (ffffffff81bbd450)
Location: net/mptcp/protocol.h:438
Inline: True
Inline callers:
  - net/mptcp/protocol.c:__mptcp_move_skbs_from_subflow
  - net/mptcp/protocol.c:__mptcp_move_skb
```
```
In net/mptcp/subflow.c (ffffffff81bc301e)
Location: net/mptcp/protocol.h:438
Inline: True
Inline callers:
  - net/mptcp/subflow.c:mptcp_subflow_data_available
  - net/mptcp/subflow.c:subflow_check_data_avail
  - net/mptcp/subflow.c:mptcp_subflow_discard_data
  - net/mptcp/subflow.c:get_mapping_status
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
In net/mptcp/protocol.c (ffffffff81bacc6b)
Location: net/mptcp/protocol.h:456
Inline: True
Inline callers:
  - net/mptcp/protocol.c:__mptcp_move_skbs_from_subflow
  - net/mptcp/protocol.c:__mptcp_move_skb
```
```
In net/mptcp/subflow.c (ffffffff81bb357e)
Location: net/mptcp/protocol.h:456
Inline: True
Inline callers:
  - net/mptcp/subflow.c:mptcp_subflow_data_available
  - net/mptcp/subflow.c:subflow_check_data_avail
  - net/mptcp/subflow.c:subflow_check_data_avail
  - net/mptcp/subflow.c:get_mapping_status
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
In net/mptcp/protocol.c (ffffffff81c7961b)
Location: net/mptcp/protocol.h:486
Inline: True
Inline callers:
  - net/mptcp/protocol.c:__mptcp_move_skbs_from_subflow
  - net/mptcp/protocol.c:__mptcp_move_skb
```
```
In net/mptcp/subflow.c (ffffffff81c81c8e)
Location: net/mptcp/protocol.h:486
Inline: True
Inline callers:
  - net/mptcp/subflow.c:mptcp_subflow_data_available
  - net/mptcp/subflow.c:subflow_check_data_avail
  - net/mptcp/subflow.c:subflow_check_data_avail
  - net/mptcp/subflow.c:get_mapping_status
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
In net/mptcp/protocol.c (ffffffff81e1e586)
Location: net/mptcp/protocol.h:526
Inline: True
Inline callers:
  - net/mptcp/protocol.c:__mptcp_move_skbs_from_subflow
  - net/mptcp/protocol.c:__mptcp_move_skb
```
```
In net/mptcp/subflow.c (ffffffff81e2780d)
Location: net/mptcp/protocol.h:526
Inline: True
Inline callers:
  - net/mptcp/subflow.c:mptcp_subflow_data_available
  - net/mptcp/subflow.c:subflow_check_data_avail
  - net/mptcp/subflow.c:subflow_check_data_avail
  - net/mptcp/subflow.c:get_mapping_status
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
In net/mptcp/protocol.c (ffffffff81ff6fb6)
Location: net/mptcp/protocol.h:544
Inline: True
Inline callers:
  - net/mptcp/protocol.c:__mptcp_move_skbs_from_subflow
  - net/mptcp/protocol.c:__mptcp_move_skb
```
```
In net/mptcp/subflow.c (ffffffff81fff6cd)
Location: net/mptcp/protocol.h:544
Inline: True
Inline callers:
  - net/mptcp/subflow.c:mptcp_subflow_data_available
  - net/mptcp/subflow.c:subflow_check_data_avail
  - net/mptcp/subflow.c:subflow_check_data_avail
  - net/mptcp/subflow.c:get_mapping_status
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
In net/mptcp/protocol.c (ffffffff82073681)
Location: net/mptcp/protocol.h:549
Inline: True
Inline callers:
  - net/mptcp/protocol.c:__mptcp_move_skbs_from_subflow
  - net/mptcp/protocol.c:__mptcp_move_skb
```
```
In net/mptcp/subflow.c (ffffffff8207b79d)
Location: net/mptcp/protocol.h:549
Inline: True
Inline callers:
  - net/mptcp/subflow.c:mptcp_subflow_data_available
  - net/mptcp/subflow.c:subflow_check_data_avail
  - net/mptcp/subflow.c:subflow_check_data_avail
  - net/mptcp/subflow.c:get_mapping_status
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
In net/mptcp/protocol.c (ffffffff821478e1)
Location: net/mptcp/protocol.h:562
Inline: True
Inline callers:
  - net/mptcp/protocol.c:__mptcp_move_skbs_from_subflow
  - net/mptcp/protocol.c:__mptcp_move_skb
```
```
In net/mptcp/subflow.c (ffffffff82150e2d)
Location: net/mptcp/protocol.h:562
Inline: True
Inline callers:
  - net/mptcp/subflow.c:mptcp_subflow_data_available
  - net/mptcp/subflow.c:subflow_check_data_avail
  - net/mptcp/subflow.c:subflow_check_data_avail
  - net/mptcp/subflow.c:get_mapping_status
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
