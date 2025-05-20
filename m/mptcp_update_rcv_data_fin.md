# Function: <code>mptcp_update_rcv_data_fin</code>

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
bool mptcp_update_rcv_data_fin(struct mptcp_sock *msk, u64 data_fin_seq, bool use_64bit);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/mptcp/options.c (ffffffff81bc52c2)
Location: net/mptcp/options.c:898
Inline: True
Inline callers:
  - net/mptcp/options.c:mptcp_incoming_options
  - net/mptcp/options.c:mptcp_incoming_options
Direct callers:
  - net/mptcp/subflow.c:get_mapping_status
  - net/mptcp/subflow.c:get_mapping_status
```
**Symbols:**

```
ffffffff81bc5040-ffffffff81bc50ab: mptcp_update_rcv_data_fin (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
bool mptcp_update_rcv_data_fin(struct mptcp_sock *msk, u64 data_fin_seq, bool use_64bit);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/mptcp/options.c (ffffffff81bb5afe)
Location: net/mptcp/options.c:953
Inline: True
Inline callers:
  - net/mptcp/options.c:mptcp_incoming_options
  - net/mptcp/options.c:mptcp_incoming_options
Direct callers:
  - net/mptcp/subflow.c:get_mapping_status
  - net/mptcp/subflow.c:get_mapping_status
```
**Symbols:**

```
ffffffff81bb57e0-ffffffff81bb5860: mptcp_update_rcv_data_fin (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
bool mptcp_update_rcv_data_fin(struct mptcp_sock *msk, u64 data_fin_seq, bool use_64bit);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/mptcp/options.c (ffffffff81c84522)
Location: net/mptcp/options.c:1035
Inline: True
Direct callers:
  - net/mptcp/subflow.c:get_mapping_status
  - net/mptcp/subflow.c:get_mapping_status
  - net/mptcp/options.c:mptcp_incoming_options
```
**Symbols:**

```
ffffffff81d43e21-ffffffff81d43e3c: mptcp_update_rcv_data_fin.cold (STB_LOCAL)
ffffffff81c844f0-ffffffff81c8458f: mptcp_update_rcv_data_fin (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

```c
bool mptcp_update_rcv_data_fin(struct mptcp_sock *msk, u64 data_fin_seq, bool use_64bit);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/mptcp/options.c (ffffffff81e2a7a2)
Location: net/mptcp/options.c:1061
Inline: True
Direct callers:
  - net/mptcp/subflow.c:get_mapping_status
  - net/mptcp/subflow.c:get_mapping_status
  - net/mptcp/options.c:mptcp_incoming_options
```
**Symbols:**

```
ffffffff81f10953-ffffffff81f1096e: mptcp_update_rcv_data_fin.cold (STB_LOCAL)
ffffffff81e2a770-ffffffff81e2a816: mptcp_update_rcv_data_fin (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

```c
bool mptcp_update_rcv_data_fin(struct mptcp_sock *msk, u64 data_fin_seq, bool use_64bit);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/mptcp/options.c (ffffffff82002922)
Location: net/mptcp/options.c:1070
Inline: True
Direct callers:
  - net/mptcp/subflow.c:get_mapping_status
  - net/mptcp/subflow.c:get_mapping_status
  - net/mptcp/options.c:mptcp_incoming_options
```
**Symbols:**

```
ffffffff820b6cc2-ffffffff820b6cdd: mptcp_update_rcv_data_fin.cold (STB_LOCAL)
ffffffff820028f0-ffffffff82002996: mptcp_update_rcv_data_fin (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

```c
bool mptcp_update_rcv_data_fin(struct mptcp_sock *msk, u64 data_fin_seq, bool use_64bit);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/mptcp/options.c (ffffffff8207eb02)
Location: net/mptcp/options.c:1076
Inline: True
Direct callers:
  - net/mptcp/subflow.c:subflow_state_change
  - net/mptcp/subflow.c:get_mapping_status
  - net/mptcp/subflow.c:get_mapping_status
  - net/mptcp/options.c:mptcp_incoming_options
```
**Symbols:**

```
ffffffff82138064-ffffffff8213807f: mptcp_update_rcv_data_fin.cold (STB_LOCAL)
ffffffff8207ead0-ffffffff8207eb76: mptcp_update_rcv_data_fin (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
bool mptcp_update_rcv_data_fin(struct mptcp_sock *msk, u64 data_fin_seq, bool use_64bit);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/mptcp/options.c (ffffffff82153ff2)
Location: net/mptcp/options.c:1078
Inline: True
Direct callers:
  - net/mptcp/subflow.c:subflow_state_change
  - net/mptcp/subflow.c:get_mapping_status
  - net/mptcp/subflow.c:get_mapping_status
  - net/mptcp/options.c:mptcp_incoming_options
```
**Symbols:**

```
ffffffff82219e7a-ffffffff82219e95: mptcp_update_rcv_data_fin.cold (STB_LOCAL)
ffffffff82153fc0-ffffffff82154066: mptcp_update_rcv_data_fin (STB_GLOBAL)
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
