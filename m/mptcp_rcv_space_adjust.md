# Function: <code>mptcp_rcv_space_adjust</code>

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
<summary>In <code>5.11</code>: ✅</summary>

```c
void mptcp_rcv_space_adjust(struct mptcp_sock *msk, int copied);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/mptcp/protocol.c (ffffffff81bba620)
Location: net/mptcp/protocol.c:1757
Inline: False
Direct callers:
  - net/mptcp/protocol.c:mptcp_recvmsg
```
**Symbols:**

```
ffffffff81bba620-ffffffff81bba884: mptcp_rcv_space_adjust (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void mptcp_rcv_space_adjust(struct mptcp_sock *msk, int copied);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/mptcp/protocol.c (ffffffff81ba98b0)
Location: net/mptcp/protocol.c:1820
Inline: False
Direct callers:
  - net/mptcp/protocol.c:mptcp_recvmsg
```
**Symbols:**

```
ffffffff81ba98b0-ffffffff81ba9b13: mptcp_rcv_space_adjust (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void mptcp_rcv_space_adjust(struct mptcp_sock *msk, int copied);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/mptcp/protocol.c (0)
Location: net/mptcp/protocol.c:1841
Inline: False
Direct callers:
  - net/mptcp/protocol.c:mptcp_recvmsg
```
**Symbols:**

```
ffffffff81c78300-ffffffff81c785ad: mptcp_rcv_space_adjust (STB_LOCAL)
ffffffff81d432f1-ffffffff81d43389: mptcp_rcv_space_adjust.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void mptcp_rcv_space_adjust(struct mptcp_sock *msk, int copied);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/mptcp/protocol.c (0)
Location: net/mptcp/protocol.c:1875
Inline: False
Direct callers:
  - net/mptcp/protocol.c:mptcp_recvmsg
```
**Symbols:**

```
ffffffff81e1d3c0-ffffffff81e1d6a7: mptcp_rcv_space_adjust (STB_LOCAL)
ffffffff81f0fdcb-ffffffff81f0fe63: mptcp_rcv_space_adjust.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void mptcp_rcv_space_adjust(struct mptcp_sock *msk, int copied);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/mptcp/protocol.c (0)
Location: net/mptcp/protocol.c:1886
Inline: False
Direct callers:
  - net/mptcp/protocol.c:mptcp_recvmsg
```
**Symbols:**

```
ffffffff81ff4970-ffffffff81ff4c57: mptcp_rcv_space_adjust (STB_LOCAL)
ffffffff820b60f1-ffffffff820b6189: mptcp_rcv_space_adjust.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void mptcp_rcv_space_adjust(struct mptcp_sock *msk, int copied);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/mptcp/protocol.c (0)
Location: net/mptcp/protocol.c:1880
Inline: False
Direct callers:
  - net/mptcp/protocol.c:mptcp_recvmsg
```
**Symbols:**

```
ffffffff82071230-ffffffff82071517: mptcp_rcv_space_adjust (STB_LOCAL)
ffffffff821376de-ffffffff82137776: mptcp_rcv_space_adjust.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void mptcp_rcv_space_adjust(struct mptcp_sock *msk, int copied);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/mptcp/protocol.c (ffffffff82144820)
Location: net/mptcp/protocol.c:1954
Inline: False
Direct callers:
  - net/mptcp/protocol.c:mptcp_recvmsg
```
**Symbols:**

```
ffffffff82144820-ffffffff82144b12: mptcp_rcv_space_adjust (STB_LOCAL)
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
