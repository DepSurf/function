# Function: <code>mptcp_sendmsg_frag</code>

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
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/mptcp/protocol.c (ffffffff81baa600)
Location: net/mptcp/protocol.c:531
Inline: True
Direct callers:
  - net/mptcp/protocol.c:mptcp_worker
  - net/mptcp/protocol.c:mptcp_sendmsg
```
**Symbols:**

```
ffffffff81baa600-ffffffff81baac0d: mptcp_sendmsg_frag.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int mptcp_sendmsg_frag(struct sock *sk, struct sock *ssk, struct mptcp_data_frag *dfrag, struct mptcp_sendmsg_info *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/mptcp/protocol.c (ffffffff81bba010)
Location: net/mptcp/protocol.c:1249
Inline: False
Direct callers:
  - net/mptcp/protocol.c:mptcp_worker
  - net/mptcp/protocol.c:__mptcp_subflow_push_pending
  - net/mptcp/protocol.c:__mptcp_push_pending
```
**Symbols:**

```
ffffffff81bba010-ffffffff81bba3c1: mptcp_sendmsg_frag (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int mptcp_sendmsg_frag(struct sock *sk, struct sock *ssk, struct mptcp_data_frag *dfrag, struct mptcp_sendmsg_info *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/mptcp/protocol.c (ffffffff81ba93c0)
Location: net/mptcp/protocol.c:1301
Inline: False
Direct callers:
  - net/mptcp/protocol.c:__mptcp_retrans
  - net/mptcp/protocol.c:__mptcp_subflow_push_pending
  - net/mptcp/protocol.c:__mptcp_push_pending
```
**Symbols:**

```
ffffffff81ba93c0-ffffffff81ba9773: mptcp_sendmsg_frag (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int mptcp_sendmsg_frag(struct sock *sk, struct sock *ssk, struct mptcp_data_frag *dfrag, struct mptcp_sendmsg_info *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/mptcp/protocol.c (0)
Location: net/mptcp/protocol.c:1285
Inline: False
Direct callers:
  - net/mptcp/protocol.c:__mptcp_retrans
  - net/mptcp/protocol.c:__mptcp_subflow_push_pending
  - net/mptcp/protocol.c:__mptcp_push_pending
```
**Symbols:**

```
ffffffff81c789b0-ffffffff81c78db8: mptcp_sendmsg_frag (STB_LOCAL)
ffffffff81d433d9-ffffffff81d43432: mptcp_sendmsg_frag.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int mptcp_sendmsg_frag(struct sock *sk, struct sock *ssk, struct mptcp_data_frag *dfrag, struct mptcp_sendmsg_info *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/mptcp/protocol.c (0)
Location: net/mptcp/protocol.c:1257
Inline: False
Direct callers:
  - net/mptcp/protocol.c:__mptcp_retrans
  - net/mptcp/protocol.c:__mptcp_subflow_push_pending
  - net/mptcp/protocol.c:__mptcp_push_pending
```
**Symbols:**

```
ffffffff81e1ee20-ffffffff81e1f817: mptcp_sendmsg_frag (STB_LOCAL)
ffffffff81f1004a-ffffffff81f100e4: mptcp_sendmsg_frag.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int mptcp_sendmsg_frag(struct sock *sk, struct sock *ssk, struct mptcp_data_frag *dfrag, struct mptcp_sendmsg_info *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/mptcp/protocol.c (0)
Location: net/mptcp/protocol.c:1218
Inline: False
Direct callers:
  - net/mptcp/protocol.c:__mptcp_retrans
  - net/mptcp/protocol.c:__mptcp_subflow_push_pending
  - net/mptcp/protocol.c:__mptcp_push_pending
```
**Symbols:**

```
ffffffff81ff59e0-ffffffff81ff631d: mptcp_sendmsg_frag (STB_LOCAL)
ffffffff820b62fd-ffffffff820b6397: mptcp_sendmsg_frag.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int mptcp_sendmsg_frag(struct sock *sk, struct sock *ssk, struct mptcp_data_frag *dfrag, struct mptcp_sendmsg_info *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/mptcp/protocol.c (0)
Location: net/mptcp/protocol.c:1189
Inline: False
Direct callers:
  - net/mptcp/protocol.c:__mptcp_retrans
  - net/mptcp/protocol.c:__mptcp_subflow_push_pending
  - net/mptcp/protocol.c:__mptcp_push_pending
```
**Symbols:**

```
ffffffff82071ad0-ffffffff820724f1: mptcp_sendmsg_frag (STB_LOCAL)
ffffffff821377fc-ffffffff8213788f: mptcp_sendmsg_frag.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int mptcp_sendmsg_frag(struct sock *sk, struct sock *ssk, struct mptcp_data_frag *dfrag, struct mptcp_sendmsg_info *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/mptcp/protocol.c (0)
Location: net/mptcp/protocol.c:1221
Inline: False
Direct callers:
  - net/mptcp/protocol.c:__mptcp_retrans
  - net/mptcp/protocol.c:__subflow_push_pending
```
**Symbols:**

```
ffffffff82145c50-ffffffff82146694: mptcp_sendmsg_frag (STB_LOCAL)
ffffffff822195c1-ffffffff82219654: mptcp_sendmsg_frag.cold (STB_LOCAL)
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
