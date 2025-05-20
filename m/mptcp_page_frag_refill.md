# Function: <code>mptcp_page_frag_refill</code>

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
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
bool mptcp_page_frag_refill(struct sock *sk, struct page_frag *pfrag);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/mptcp/protocol.c (ffffffff81baa580)
Location: net/mptcp/protocol.c:503
Inline: True
Direct callers:
  - net/mptcp/protocol.c:mptcp_sendmsg
  - net/mptcp/protocol.c:mptcp_sendmsg
```
**Symbols:**

```
ffffffff81baa580-ffffffff81baa5f7: mptcp_page_frag_refill (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/mptcp/protocol.c (ffffffff81bbfa87)
Location: net/mptcp/protocol.c:1073
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_sendmsg
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
In net/mptcp/protocol.c (ffffffff81baf682)
Location: net/mptcp/protocol.c:1125
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_sendmsg
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/mptcp/protocol.c (ffffffff81c7d33b)
Location: net/mptcp/protocol.c:1154
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_sendmsg
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/mptcp/protocol.c (ffffffff81e2297c)
Location: net/mptcp/protocol.c:1113
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_sendmsg
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/mptcp/protocol.c (ffffffff81ffb671)
Location: net/mptcp/protocol.c:1080
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_sendmsg
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/mptcp/protocol.c (ffffffff820779fa)
Location: net/mptcp/protocol.c:1051
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_sendmsg
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/mptcp/protocol.c (ffffffff8214ca6a)
Location: net/mptcp/protocol.c:1081
Inline: True
Inline callers:
  - net/mptcp/protocol.c:mptcp_sendmsg
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
</ul>
