# Function: <code>mptcp_pending_data_fin</code>

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
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/mptcp/protocol.c (ffffffff81bbe8d9)
Location: net/mptcp/protocol.c:381
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_data_ready
  - net/mptcp/protocol.c:mptcp_data_ready
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/mptcp/protocol.c (ffffffff81bae723)
Location: net/mptcp/protocol.c:377
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_data_ready
  - net/mptcp/protocol.c:mptcp_data_ready
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
bool mptcp_pending_data_fin(struct sock *sk, u64 *seq);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/mptcp/protocol.c (ffffffff81c77763)
Location: net/mptcp/protocol.c:386
Inline: True
Direct callers:
  - net/mptcp/protocol.c:mptcp_data_ready
```
**Symbols:**

```
ffffffff81c77710-ffffffff81c7777e: mptcp_pending_data_fin (STB_LOCAL)
ffffffff81d43271-ffffffff81d432ad: mptcp_pending_data_fin.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
bool mptcp_pending_data_fin(struct sock *sk, u64 *seq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/mptcp/protocol.c (0)
Location: net/mptcp/protocol.c:450
Inline: False
Direct callers:
  - net/mptcp/protocol.c:mptcp_data_ready
```
**Symbols:**

```
ffffffff81e1c530-ffffffff81e1c5a8: mptcp_pending_data_fin (STB_LOCAL)
ffffffff81f0fc9e-ffffffff81f0fcda: mptcp_pending_data_fin.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
bool mptcp_pending_data_fin(struct sock *sk, u64 *seq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/mptcp/protocol.c (0)
Location: net/mptcp/protocol.c:442
Inline: False
Direct callers:
  - net/mptcp/protocol.c:mptcp_data_ready
```
**Symbols:**

```
ffffffff81ff3c30-ffffffff81ff3ca8: mptcp_pending_data_fin (STB_LOCAL)
ffffffff820b6044-ffffffff820b6080: mptcp_pending_data_fin.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

```c
bool mptcp_pending_data_fin(struct sock *sk, u64 *seq);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/mptcp/protocol.c (ffffffff82071535)
Location: net/mptcp/protocol.c:456
Inline: True
Direct callers:
  - net/mptcp/protocol.c:mptcp_data_ready
```
**Symbols:**

```
ffffffff82070110-ffffffff82070183: mptcp_pending_data_fin (STB_LOCAL)
ffffffff821375b6-ffffffff821375e7: mptcp_pending_data_fin.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
bool mptcp_pending_data_fin(struct sock *sk, u64 *seq);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/mptcp/protocol.c (ffffffff82146a85)
Location: net/mptcp/protocol.c:444
Inline: True
Direct callers:
  - net/mptcp/protocol.c:mptcp_data_ready
```
**Symbols:**

```
ffffffff821440b0-ffffffff82144123: mptcp_pending_data_fin (STB_LOCAL)
ffffffff82219441-ffffffff82219472: mptcp_pending_data_fin.cold (STB_LOCAL)
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
