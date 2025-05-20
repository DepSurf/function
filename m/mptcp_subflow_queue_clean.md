# Function: <code>mptcp_subflow_queue_clean</code>

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
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void mptcp_subflow_queue_clean(struct sock *listener_ssk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/mptcp/subflow.c (0)
Location: net/mptcp/subflow.c:1727
Inline: False
Direct callers:
  - net/mptcp/protocol.c:__mptcp_close_ssk
```
**Symbols:**

```
ffffffff81f10706-ffffffff81f10723: mptcp_subflow_queue_clean.cold (STB_LOCAL)
ffffffff81e28730-ffffffff81e28879: mptcp_subflow_queue_clean (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void mptcp_subflow_queue_clean(struct sock *listener_sk, struct sock *listener_ssk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/mptcp/subflow.c (0)
Location: net/mptcp/subflow.c:1803
Inline: False
Direct callers:
  - net/mptcp/protocol.c:__mptcp_close_ssk
```
**Symbols:**

```
ffffffff820b6a95-ffffffff820b6ab2: mptcp_subflow_queue_clean.cold (STB_LOCAL)
ffffffff820006b0-ffffffff820008aa: mptcp_subflow_queue_clean (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void mptcp_subflow_queue_clean(struct sock *listener_sk, struct sock *listener_ssk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/mptcp/subflow.c (0)
Location: net/mptcp/subflow.c:1793
Inline: False
```
**Symbols:**

```
ffffffff82137e02-ffffffff82137e1f: mptcp_subflow_queue_clean.cold (STB_LOCAL)
ffffffff8207c8a0-ffffffff8207ca5e: mptcp_subflow_queue_clean (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void mptcp_subflow_queue_clean(struct sock *listener_sk, struct sock *listener_ssk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/mptcp/subflow.c (0)
Location: net/mptcp/subflow.c:1790
Inline: False
```
**Symbols:**

```
ffffffff82219c77-ffffffff82219c94: mptcp_subflow_queue_clean.cold (STB_LOCAL)
ffffffff82151da0-ffffffff82151f5e: mptcp_subflow_queue_clean (STB_GLOBAL)
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
<details>
<summary>Changed between <code>5.19</code> and <code>6.2</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct sock *listener_sk</code>
</li>
<li>
<b>Param reordered. </b>
<code>listener_ssk</code> ➡️ <code>listener_sk, listener_ssk</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
