# Function: <code>before64</code>

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
In net/mptcp/protocol.c (ffffffff81bab2a3)
Location: net/mptcp/protocol.h:448
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_clean_una
  - net/mptcp/protocol.c:mptcp_clean_una
```
```
In net/mptcp/subflow.c (ffffffff81baf60a)
Location: net/mptcp/protocol.h:448
Inline: True
Inline callers:
  - net/mptcp/subflow.c:subflow_check_data_avail
```
```
In net/mptcp/options.c (ffffffff81bb14a8)
Location: net/mptcp/protocol.h:448
Inline: True
Inline callers:
  - net/mptcp/options.c:mptcp_incoming_options
  - net/mptcp/options.c:mptcp_incoming_options
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
In net/mptcp/protocol.c (ffffffff81bba19e)
Location: net/mptcp/protocol.h:101
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_sendmsg_frag
  - net/mptcp/protocol.c:__mptcp_clean_una
  - net/mptcp/protocol.c:__mptcp_clean_una
  - net/mptcp/protocol.c:__mptcp_ofo_queue
  - net/mptcp/protocol.c:__mptcp_ofo_queue
  - net/mptcp/protocol.c:__mptcp_move_skb
  - net/mptcp/protocol.c:mptcp_data_queue_ofo
  - net/mptcp/protocol.c:mptcp_data_queue_ofo
  - net/mptcp/protocol.c:mptcp_data_queue_ofo
  - net/mptcp/protocol.c:mptcp_data_queue_ofo
  - net/mptcp/protocol.c:mptcp_data_queue_ofo
  - net/mptcp/protocol.c:mptcp_data_queue_ofo
  - net/mptcp/protocol.c:mptcp_data_queue_ofo
```
```
In net/mptcp/subflow.c (ffffffff81bc22a9)
Location: net/mptcp/protocol.h:101
Inline: True
Inline callers:
  - net/mptcp/subflow.c:subflow_check_data_avail
```
```
In net/mptcp/options.c (ffffffff81bc587e)
Location: net/mptcp/protocol.h:101
Inline: True
Inline callers:
  - net/mptcp/options.c:mptcp_write_options
  - net/mptcp/options.c:ack_update_msk
  - net/mptcp/options.c:ack_update_msk
  - net/mptcp/options.c:ack_update_msk
  - net/mptcp/options.c:ack_update_msk
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
In net/mptcp/protocol.c (ffffffff81ba954e)
Location: net/mptcp/protocol.h:114
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_sendmsg_frag
  - net/mptcp/protocol.c:__mptcp_clean_una
  - net/mptcp/protocol.c:__mptcp_clean_una
  - net/mptcp/protocol.c:__mptcp_ofo_queue
  - net/mptcp/protocol.c:__mptcp_ofo_queue
  - net/mptcp/protocol.c:__mptcp_move_skb
  - net/mptcp/protocol.c:mptcp_data_queue_ofo
  - net/mptcp/protocol.c:mptcp_data_queue_ofo
  - net/mptcp/protocol.c:mptcp_data_queue_ofo
  - net/mptcp/protocol.c:mptcp_data_queue_ofo
  - net/mptcp/protocol.c:mptcp_data_queue_ofo
  - net/mptcp/protocol.c:mptcp_data_queue_ofo
  - net/mptcp/protocol.c:mptcp_data_queue_ofo
```
```
In net/mptcp/subflow.c (ffffffff81bb2d24)
Location: net/mptcp/protocol.h:114
Inline: True
Inline callers:
  - net/mptcp/subflow.c:subflow_check_data_avail
```
```
In net/mptcp/options.c (ffffffff81bb6401)
Location: net/mptcp/protocol.h:114
Inline: True
Inline callers:
  - net/mptcp/options.c:mptcp_write_options
  - net/mptcp/options.c:mptcp_incoming_options
  - net/mptcp/options.c:mptcp_incoming_options
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
In net/mptcp/protocol.c (ffffffff81c7c581)
Location: net/mptcp/protocol.h:127
Inline: True
Inline callers:
  - net/mptcp/protocol.c:__mptcp_subflow_push_pending
  - net/mptcp/protocol.c:__mptcp_push_pending
  - net/mptcp/protocol.c:mptcp_sendmsg_frag
  - net/mptcp/protocol.c:__mptcp_clean_una
  - net/mptcp/protocol.c:__mptcp_clean_una
  - net/mptcp/protocol.c:__mptcp_clean_una
  - net/mptcp/protocol.c:__mptcp_ofo_queue
  - net/mptcp/protocol.c:__mptcp_ofo_queue
  - net/mptcp/protocol.c:__mptcp_move_skb
  - net/mptcp/protocol.c:mptcp_data_queue_ofo
  - net/mptcp/protocol.c:mptcp_data_queue_ofo
  - net/mptcp/protocol.c:mptcp_data_queue_ofo
  - net/mptcp/protocol.c:mptcp_data_queue_ofo
  - net/mptcp/protocol.c:mptcp_data_queue_ofo
  - net/mptcp/protocol.c:mptcp_data_queue_ofo
  - net/mptcp/protocol.c:mptcp_data_queue_ofo
```
```
In net/mptcp/subflow.c (ffffffff81c812bd)
Location: net/mptcp/protocol.h:127
Inline: True
Inline callers:
  - net/mptcp/subflow.c:subflow_check_data_avail
```
```
In net/mptcp/options.c (ffffffff81c85012)
Location: net/mptcp/protocol.h:127
Inline: True
Inline callers:
  - net/mptcp/options.c:mptcp_write_options
  - net/mptcp/options.c:mptcp_incoming_options
  - net/mptcp/options.c:mptcp_incoming_options
  - net/mptcp/options.c:mptcp_incoming_options
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
In net/mptcp/protocol.c (ffffffff81e21916)
Location: net/mptcp/protocol.h:130
Inline: True
Inline callers:
  - net/mptcp/protocol.c:__mptcp_subflow_push_pending
  - net/mptcp/protocol.c:__mptcp_push_pending
  - net/mptcp/protocol.c:__mptcp_clean_una
  - net/mptcp/protocol.c:__mptcp_clean_una
  - net/mptcp/protocol.c:__mptcp_clean_una
  - net/mptcp/protocol.c:__mptcp_ofo_queue
  - net/mptcp/protocol.c:__mptcp_ofo_queue
  - net/mptcp/protocol.c:__mptcp_move_skb
  - net/mptcp/protocol.c:mptcp_data_queue_ofo
  - net/mptcp/protocol.c:mptcp_data_queue_ofo
  - net/mptcp/protocol.c:mptcp_data_queue_ofo
  - net/mptcp/protocol.c:mptcp_data_queue_ofo
  - net/mptcp/protocol.c:mptcp_data_queue_ofo
  - net/mptcp/protocol.c:mptcp_data_queue_ofo
  - net/mptcp/protocol.c:mptcp_data_queue_ofo
```
```
In net/mptcp/subflow.c (ffffffff81e26cfb)
Location: net/mptcp/protocol.h:130
Inline: True
Inline callers:
  - net/mptcp/subflow.c:subflow_check_data_avail
```
```
In net/mptcp/options.c (ffffffff81e2b0a5)
Location: net/mptcp/protocol.h:130
Inline: True
Inline callers:
  - net/mptcp/options.c:mptcp_write_options
  - net/mptcp/options.c:mptcp_write_options
  - net/mptcp/options.c:ack_update_msk
  - net/mptcp/options.c:ack_update_msk
  - net/mptcp/options.c:ack_update_msk
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
In net/mptcp/protocol.c (ffffffff81ff8df0)
Location: net/mptcp/protocol.h:138
Inline: True
Inline callers:
  - net/mptcp/protocol.c:__mptcp_subflow_push_pending
  - net/mptcp/protocol.c:__mptcp_push_pending
  - net/mptcp/protocol.c:__mptcp_clean_una
  - net/mptcp/protocol.c:__mptcp_clean_una
  - net/mptcp/protocol.c:__mptcp_clean_una
  - net/mptcp/protocol.c:__mptcp_ofo_queue
  - net/mptcp/protocol.c:__mptcp_ofo_queue
  - net/mptcp/protocol.c:__mptcp_move_skb
  - net/mptcp/protocol.c:mptcp_data_queue_ofo
  - net/mptcp/protocol.c:mptcp_data_queue_ofo
  - net/mptcp/protocol.c:mptcp_data_queue_ofo
  - net/mptcp/protocol.c:mptcp_data_queue_ofo
  - net/mptcp/protocol.c:mptcp_data_queue_ofo
  - net/mptcp/protocol.c:mptcp_data_queue_ofo
  - net/mptcp/protocol.c:mptcp_data_queue_ofo
```
```
In net/mptcp/subflow.c (ffffffff81ffe46e)
Location: net/mptcp/protocol.h:138
Inline: True
Inline callers:
  - net/mptcp/subflow.c:subflow_check_data_avail
```
```
In net/mptcp/options.c (ffffffff82003255)
Location: net/mptcp/protocol.h:138
Inline: True
Inline callers:
  - net/mptcp/options.c:mptcp_write_options
  - net/mptcp/options.c:mptcp_write_options
  - net/mptcp/options.c:ack_update_msk
  - net/mptcp/options.c:ack_update_msk
  - net/mptcp/options.c:ack_update_msk
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
In net/mptcp/protocol.c (ffffffff820752cb)
Location: net/mptcp/protocol.h:137
Inline: True
Inline callers:
  - net/mptcp/protocol.c:__mptcp_subflow_push_pending
  - net/mptcp/protocol.c:__mptcp_push_pending
  - net/mptcp/protocol.c:__mptcp_clean_una
  - net/mptcp/protocol.c:__mptcp_clean_una
  - net/mptcp/protocol.c:__mptcp_clean_una
  - net/mptcp/protocol.c:__mptcp_ofo_queue
  - net/mptcp/protocol.c:__mptcp_ofo_queue
  - net/mptcp/protocol.c:__mptcp_move_skb
  - net/mptcp/protocol.c:mptcp_data_queue_ofo
  - net/mptcp/protocol.c:mptcp_data_queue_ofo
  - net/mptcp/protocol.c:mptcp_data_queue_ofo
  - net/mptcp/protocol.c:mptcp_data_queue_ofo
  - net/mptcp/protocol.c:mptcp_data_queue_ofo
  - net/mptcp/protocol.c:mptcp_data_queue_ofo
  - net/mptcp/protocol.c:mptcp_data_queue_ofo
```
```
In net/mptcp/subflow.c (ffffffff8207a53e)
Location: net/mptcp/protocol.h:137
Inline: True
Inline callers:
  - net/mptcp/subflow.c:subflow_check_data_avail
```
```
In net/mptcp/options.c (ffffffff8207f3e5)
Location: net/mptcp/protocol.h:137
Inline: True
Inline callers:
  - net/mptcp/options.c:mptcp_write_options
  - net/mptcp/options.c:mptcp_write_options
  - net/mptcp/options.c:ack_update_msk
  - net/mptcp/options.c:ack_update_msk
  - net/mptcp/options.c:ack_update_msk
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
In net/mptcp/protocol.c (ffffffff8214920a)
Location: net/mptcp/protocol.h:139
Inline: True
Inline callers:
  - net/mptcp/protocol.c:__subflow_push_pending
  - net/mptcp/protocol.c:__mptcp_clean_una
  - net/mptcp/protocol.c:__mptcp_clean_una
  - net/mptcp/protocol.c:__mptcp_clean_una
  - net/mptcp/protocol.c:__mptcp_ofo_queue
  - net/mptcp/protocol.c:__mptcp_ofo_queue
  - net/mptcp/protocol.c:__mptcp_move_skb
  - net/mptcp/protocol.c:mptcp_data_queue_ofo
  - net/mptcp/protocol.c:mptcp_data_queue_ofo
  - net/mptcp/protocol.c:mptcp_data_queue_ofo
  - net/mptcp/protocol.c:mptcp_data_queue_ofo
  - net/mptcp/protocol.c:mptcp_data_queue_ofo
  - net/mptcp/protocol.c:mptcp_data_queue_ofo
  - net/mptcp/protocol.c:mptcp_data_queue_ofo
```
```
In net/mptcp/subflow.c (ffffffff8214f9af)
Location: net/mptcp/protocol.h:139
Inline: True
Inline callers:
  - net/mptcp/subflow.c:subflow_check_data_avail
```
```
In net/mptcp/options.c (ffffffff821548d5)
Location: net/mptcp/protocol.h:139
Inline: True
Inline callers:
  - net/mptcp/options.c:mptcp_write_options
  - net/mptcp/options.c:mptcp_write_options
  - net/mptcp/options.c:ack_update_msk
  - net/mptcp/options.c:ack_update_msk
  - net/mptcp/options.c:ack_update_msk
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
