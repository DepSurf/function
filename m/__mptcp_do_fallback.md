# Function: <code>__mptcp_do_fallback</code>

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
<summary>In <code>5.11</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/mptcp/protocol.c (ffffffff81bbbc58)
Location: net/mptcp/protocol.h:644
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_stream_connect
  - net/mptcp/protocol.c:mptcp_stream_connect
```
```
In net/mptcp/subflow.c (ffffffff81bc3152)
Location: net/mptcp/protocol.h:644
Inline: True
Inline callers:
  - net/mptcp/subflow.c:subflow_state_change
  - net/mptcp/subflow.c:subflow_state_change
  - net/mptcp/subflow.c:subflow_check_data_avail
  - net/mptcp/subflow.c:subflow_check_data_avail
  - net/mptcp/subflow.c:subflow_finish_connect
  - net/mptcp/subflow.c:subflow_finish_connect
```
```
In net/mptcp/options.c (ffffffff81bc4659)
Location: net/mptcp/protocol.h:644
Inline: True
Inline callers:
  - net/mptcp/options.c:check_fully_established
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
In net/mptcp/protocol.c (ffffffff81bab898)
Location: net/mptcp/protocol.h:799
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_stream_connect
  - net/mptcp/protocol.c:mptcp_stream_connect
```
```
In net/mptcp/subflow.c (ffffffff81bb38a6)
Location: net/mptcp/protocol.h:799
Inline: True
Inline callers:
  - net/mptcp/subflow.c:subflow_state_change
  - net/mptcp/subflow.c:subflow_state_change
  - net/mptcp/subflow.c:subflow_check_data_avail
  - net/mptcp/subflow.c:subflow_check_data_avail
  - net/mptcp/subflow.c:subflow_finish_connect
  - net/mptcp/subflow.c:subflow_finish_connect
```
```
In net/mptcp/options.c (ffffffff81bb4d56)
Location: net/mptcp/protocol.h:799
Inline: True
Inline callers:
  - net/mptcp/options.c:check_fully_established
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
In net/mptcp/protocol.c (ffffffff81c79df5)
Location: net/mptcp/protocol.h:853
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_stream_connect
  - net/mptcp/protocol.c:mptcp_stream_connect
```
```
In net/mptcp/subflow.c (ffffffff81c81ff6)
Location: net/mptcp/protocol.h:853
Inline: True
Inline callers:
  - net/mptcp/subflow.c:subflow_state_change
  - net/mptcp/subflow.c:subflow_state_change
  - net/mptcp/subflow.c:subflow_check_data_avail
  - net/mptcp/subflow.c:subflow_check_data_avail
  - net/mptcp/subflow.c:subflow_finish_connect
  - net/mptcp/subflow.c:subflow_finish_connect
```
```
In net/mptcp/options.c (ffffffff81c8374e)
Location: net/mptcp/protocol.h:853
Inline: True
Inline callers:
  - net/mptcp/options.c:check_fully_established
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
In net/mptcp/protocol.c (ffffffff81e23d86)
Location: net/mptcp/protocol.h:933
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_stream_connect
  - net/mptcp/protocol.c:mptcp_stream_connect
  - net/mptcp/protocol.c:mptcp_stream_connect
  - net/mptcp/protocol.c:mptcp_stream_connect
  - net/mptcp/protocol.c:mptcp_sendmsg_frag
  - net/mptcp/protocol.c:mptcp_sendmsg_frag
```
```
In net/mptcp/subflow.c (ffffffff81e27cfb)
Location: net/mptcp/protocol.h:933
Inline: True
Inline callers:
  - net/mptcp/subflow.c:subflow_state_change
  - net/mptcp/subflow.c:subflow_check_data_avail
  - net/mptcp/subflow.c:subflow_finish_connect
```
```
In net/mptcp/options.c (ffffffff81e29653)
Location: net/mptcp/protocol.h:933
Inline: True
Inline callers:
  - net/mptcp/options.c:check_fully_established
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
In net/mptcp/protocol.c (ffffffff81ffad3f)
Location: net/mptcp/protocol.h:965
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_connect
  - net/mptcp/protocol.c:mptcp_connect
  - net/mptcp/protocol.c:mptcp_connect
  - net/mptcp/protocol.c:mptcp_connect
  - net/mptcp/protocol.c:mptcp_sendmsg_frag
  - net/mptcp/protocol.c:mptcp_sendmsg_frag
```
```
In net/mptcp/subflow.c (ffffffff81fffc2b)
Location: net/mptcp/protocol.h:965
Inline: True
Inline callers:
  - net/mptcp/subflow.c:subflow_state_change
  - net/mptcp/subflow.c:subflow_check_data_avail
  - net/mptcp/subflow.c:subflow_finish_connect
```
```
In net/mptcp/options.c (ffffffff82001704)
Location: net/mptcp/protocol.h:965
Inline: True
Inline callers:
  - net/mptcp/options.c:check_fully_established
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
In net/mptcp/protocol.c (ffffffff82072d85)
Location: net/mptcp/protocol.h:978
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_connect
  - net/mptcp/protocol.c:mptcp_connect
  - net/mptcp/protocol.c:mptcp_connect
  - net/mptcp/protocol.c:mptcp_connect
  - net/mptcp/protocol.c:mptcp_sendmsg_frag
  - net/mptcp/protocol.c:mptcp_sendmsg_frag
```
```
In net/mptcp/subflow.c (ffffffff8207bbe5)
Location: net/mptcp/protocol.h:978
Inline: True
Inline callers:
  - net/mptcp/subflow.c:subflow_state_change
  - net/mptcp/subflow.c:subflow_check_data_avail
  - net/mptcp/subflow.c:subflow_finish_connect
```
```
In net/mptcp/options.c (ffffffff8207d89c)
Location: net/mptcp/protocol.h:978
Inline: True
Inline callers:
  - net/mptcp/options.c:check_fully_established
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
In net/mptcp/protocol.c (ffffffff82146ef5)
Location: net/mptcp/protocol.h:1081
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_connect
  - net/mptcp/protocol.c:mptcp_connect
  - net/mptcp/protocol.c:mptcp_connect
  - net/mptcp/protocol.c:mptcp_connect
  - net/mptcp/protocol.c:mptcp_sendmsg_frag
  - net/mptcp/protocol.c:mptcp_sendmsg_frag
```
```
In net/mptcp/subflow.c (ffffffff82150fc3)
Location: net/mptcp/protocol.h:1081
Inline: True
Inline callers:
  - net/mptcp/subflow.c:subflow_state_change
  - net/mptcp/subflow.c:subflow_check_data_avail
  - net/mptcp/subflow.c:subflow_finish_connect
```
```
In net/mptcp/options.c (ffffffff821531b9)
Location: net/mptcp/protocol.h:1081
Inline: True
Inline callers:
  - net/mptcp/options.c:check_fully_established
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
