# Function: <code>mptcp_get_ext</code>

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
In net/mptcp/subflow.c (ffffffff81baf130)
Location: net/mptcp/protocol.h:443
Inline: True
Inline callers:
  - net/mptcp/subflow.c:get_mapping_status
```
```
In net/mptcp/options.c (ffffffff81bb0a81)
Location: net/mptcp/protocol.h:443
Inline: True
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
In net/mptcp/subflow.c (ffffffff81bc1d66)
Location: net/mptcp/protocol.h:624
Inline: True
Inline callers:
  - net/mptcp/subflow.c:get_mapping_status
```
```
In net/mptcp/options.c (ffffffff81bc4900)
Location: net/mptcp/protocol.h:624
Inline: True
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
In net/mptcp/subflow.c (ffffffff81bb26c6)
Location: net/mptcp/protocol.h:779
Inline: True
Inline callers:
  - net/mptcp/subflow.c:get_mapping_status
```
```
In net/mptcp/options.c (ffffffff81bb5005)
Location: net/mptcp/protocol.h:779
Inline: True
Inline callers:
  - net/mptcp/options.c:mptcp_get_reset_option
  - net/mptcp/options.c:mptcp_get_reset_option
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
In net/mptcp/protocol.c (ffffffff81c778d5)
Location: net/mptcp/protocol.h:833
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_update_data_checksum
```
```
In net/mptcp/subflow.c (ffffffff81c80ba5)
Location: net/mptcp/protocol.h:833
Inline: True
Inline callers:
  - net/mptcp/subflow.c:get_mapping_status
```
```
In net/mptcp/options.c (ffffffff81c83845)
Location: net/mptcp/protocol.h:833
Inline: True
Inline callers:
  - net/mptcp/options.c:mptcp_get_reset_option
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
In net/mptcp/protocol.c (ffffffff81e1cb45)
Location: net/mptcp/protocol.h:913
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_update_data_checksum
```
```
In net/mptcp/subflow.c (ffffffff81e265f8)
Location: net/mptcp/protocol.h:913
Inline: True
Inline callers:
  - net/mptcp/subflow.c:get_mapping_status
```
```
In net/mptcp/options.c (ffffffff81e29815)
Location: net/mptcp/protocol.h:913
Inline: True
Inline callers:
  - net/mptcp/options.c:mptcp_get_reset_option
  - net/mptcp/options.c:mptcp_established_options
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
In net/mptcp/protocol.c (ffffffff81ff3fd5)
Location: net/mptcp/protocol.h:945
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_update_data_checksum
```
```
In net/mptcp/subflow.c (ffffffff81ffdd28)
Location: net/mptcp/protocol.h:945
Inline: True
Inline callers:
  - net/mptcp/subflow.c:get_mapping_status
```
```
In net/mptcp/options.c (ffffffff820018f5)
Location: net/mptcp/protocol.h:945
Inline: True
Inline callers:
  - net/mptcp/options.c:mptcp_get_reset_option
  - net/mptcp/options.c:mptcp_established_options
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
In net/mptcp/protocol.c (ffffffff820705e5)
Location: net/mptcp/protocol.h:958
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_update_data_checksum
```
```
In net/mptcp/subflow.c (ffffffff82079f08)
Location: net/mptcp/protocol.h:958
Inline: True
Inline callers:
  - net/mptcp/subflow.c:get_mapping_status
```
```
In net/mptcp/options.c (ffffffff8207ddb5)
Location: net/mptcp/protocol.h:958
Inline: True
Inline callers:
  - net/mptcp/options.c:mptcp_get_reset_option
  - net/mptcp/options.c:mptcp_established_options
  - net/mptcp/options.c:mptcp_established_options_dss
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
In net/mptcp/protocol.c (ffffffff82145e11)
Location: net/mptcp/protocol.h:1061
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_sendmsg_frag
  - net/mptcp/protocol.c:mptcp_sendmsg_frag
  - net/mptcp/protocol.c:mptcp_update_data_checksum
```
```
In net/mptcp/subflow.c (ffffffff8214f368)
Location: net/mptcp/protocol.h:1061
Inline: True
Inline callers:
  - net/mptcp/subflow.c:get_mapping_status
```
```
In net/mptcp/options.c (ffffffff82152ff5)
Location: net/mptcp/protocol.h:1061
Inline: True
Inline callers:
  - net/mptcp/options.c:mptcp_get_reset_option
  - net/mptcp/options.c:mptcp_established_options
  - net/mptcp/options.c:mptcp_established_options_dss
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
