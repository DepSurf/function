# Function: <code>mptcp_schedule_work</code>

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
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
bool mptcp_schedule_work(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/mptcp/protocol.c (ffffffff81bbe710)
Location: net/mptcp/protocol.c:762
Inline: True
Direct callers:
  - net/mptcp/protocol.c:mptcp_release_cb
  - net/mptcp/protocol.c:__mptcp_data_acked
  - net/mptcp/protocol.c:mptcp_timeout_timer
  - net/mptcp/protocol.c:mptcp_retransmit_timer
  - net/mptcp/protocol.c:__mptcp_subflow_push_pending
  - net/mptcp/protocol.c:mptcp_subflow_eof
  - net/mptcp/protocol.c:mptcp_data_ready
  - net/mptcp/options.c:mptcp_incoming_options
```
**Symbols:**

```
ffffffff81bbe710-ffffffff81bbe799: mptcp_schedule_work (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
bool mptcp_schedule_work(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/mptcp/protocol.c (ffffffff81bae4c0)
Location: net/mptcp/protocol.c:795
Inline: True
Direct callers:
  - net/mptcp/protocol.c:__mptcp_data_acked
  - net/mptcp/protocol.c:mptcp_timeout_timer
  - net/mptcp/protocol.c:mptcp_retransmit_timer
  - net/mptcp/protocol.c:__mptcp_subflow_push_pending
  - net/mptcp/protocol.c:mptcp_subflow_eof
  - net/mptcp/protocol.c:__mptcp_flush_join_list
  - net/mptcp/protocol.c:mptcp_data_ready
  - net/mptcp/options.c:mptcp_incoming_options
```
**Symbols:**

```
ffffffff81bae4c0-ffffffff81bae549: mptcp_schedule_work (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
bool mptcp_schedule_work(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/mptcp/protocol.c (ffffffff81c7b7c0)
Location: net/mptcp/protocol.c:814
Inline: True
Direct callers:
  - net/mptcp/protocol.c:__mptcp_data_acked
  - net/mptcp/protocol.c:mptcp_timeout_timer
  - net/mptcp/protocol.c:mptcp_retransmit_timer
  - net/mptcp/protocol.c:__mptcp_subflow_push_pending
  - net/mptcp/protocol.c:mptcp_subflow_eof
  - net/mptcp/protocol.c:mptcp_data_ready
  - net/mptcp/options.c:mptcp_incoming_options
```
**Symbols:**

```
ffffffff81c7b7c0-ffffffff81c7b849: mptcp_schedule_work (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
bool mptcp_schedule_work(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/mptcp/protocol.c (ffffffff81e20b60)
Location: net/mptcp/protocol.c:875
Inline: True
Direct callers:
  - net/mptcp/protocol.c:__mptcp_data_acked
  - net/mptcp/protocol.c:mptcp_timeout_timer
  - net/mptcp/protocol.c:mptcp_retransmit_timer
  - net/mptcp/protocol.c:__mptcp_subflow_push_pending
  - net/mptcp/protocol.c:mptcp_subflow_eof
  - net/mptcp/protocol.c:mptcp_data_ready
  - net/mptcp/options.c:mptcp_incoming_options
```
**Symbols:**

```
ffffffff81e20b60-ffffffff81e20bf5: mptcp_schedule_work (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
bool mptcp_schedule_work(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/mptcp/protocol.c (ffffffff81ff7fa0)
Location: net/mptcp/protocol.c:867
Inline: True
Direct callers:
  - net/mptcp/protocol.c:__mptcp_data_acked
  - net/mptcp/protocol.c:mptcp_timeout_timer
  - net/mptcp/protocol.c:mptcp_retransmit_timer
  - net/mptcp/protocol.c:__mptcp_subflow_push_pending
  - net/mptcp/protocol.c:mptcp_subflow_eof
  - net/mptcp/protocol.c:mptcp_data_ready
  - net/mptcp/options.c:mptcp_incoming_options
```
**Symbols:**

```
ffffffff81ff7fa0-ffffffff81ff8035: mptcp_schedule_work (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
bool mptcp_schedule_work(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/mptcp/protocol.c (ffffffff820744d0)
Location: net/mptcp/protocol.c:888
Inline: True
Direct callers:
  - net/mptcp/protocol.c:__mptcp_data_acked
  - net/mptcp/protocol.c:mptcp_subflow_shutdown
  - net/mptcp/protocol.c:mptcp_timeout_timer
  - net/mptcp/protocol.c:mptcp_retransmit_timer
  - net/mptcp/protocol.c:__mptcp_subflow_push_pending
  - net/mptcp/protocol.c:mptcp_data_ready
  - net/mptcp/subflow.c:subflow_ulp_release
  - net/mptcp/subflow.c:subflow_state_change
  - net/mptcp/subflow.c:subflow_state_change
  - net/mptcp/subflow.c:subflow_check_data_avail
  - net/mptcp/subflow.c:get_mapping_status
  - net/mptcp/subflow.c:mptcp_subflow_reset
  - net/mptcp/options.c:mptcp_incoming_options
  - net/mptcp/options.c:mptcp_incoming_options
```
**Symbols:**

```
ffffffff820744d0-ffffffff82074565: mptcp_schedule_work (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
bool mptcp_schedule_work(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/mptcp/protocol.c (ffffffff82148870)
Location: net/mptcp/protocol.c:917
Inline: True
Direct callers:
  - net/mptcp/protocol.c:__mptcp_data_acked
  - net/mptcp/protocol.c:mptcp_subflow_shutdown
  - net/mptcp/protocol.c:mptcp_tout_timer
  - net/mptcp/protocol.c:mptcp_retransmit_timer
  - net/mptcp/protocol.c:__mptcp_subflow_push_pending
  - net/mptcp/protocol.c:mptcp_data_ready
  - net/mptcp/subflow.c:subflow_ulp_release
  - net/mptcp/subflow.c:subflow_state_change
  - net/mptcp/subflow.c:subflow_state_change
  - net/mptcp/subflow.c:subflow_check_data_avail
  - net/mptcp/subflow.c:get_mapping_status
  - net/mptcp/subflow.c:mptcp_subflow_reset
  - net/mptcp/options.c:mptcp_incoming_options
  - net/mptcp/options.c:mptcp_incoming_options
```
**Symbols:**

```
ffffffff82148870-ffffffff82148905: mptcp_schedule_work (STB_GLOBAL)
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
