# Function: <code>mptcp_check_for_eof</code>

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
void mptcp_check_for_eof(struct mptcp_sock *msk);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/mptcp/protocol.c (ffffffff81babb40)
Location: net/mptcp/protocol.c:377
Inline: True
Direct callers:
  - net/mptcp/protocol.c:mptcp_worker
  - net/mptcp/protocol.c:mptcp_recvmsg
```
**Symbols:**

```
ffffffff81babb40-ffffffff81babba4: mptcp_check_for_eof (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void mptcp_check_for_eof(struct mptcp_sock *msk);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/mptcp/protocol.c (ffffffff81bbbd30)
Location: net/mptcp/protocol.c:781
Inline: True
Direct callers:
  - net/mptcp/protocol.c:mptcp_worker
  - net/mptcp/protocol.c:mptcp_recvmsg
```
**Symbols:**

```
ffffffff81bbbd30-ffffffff81bbbe06: mptcp_check_for_eof (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void mptcp_check_for_eof(struct mptcp_sock *msk);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/mptcp/protocol.c (ffffffff81baaeb0)
Location: net/mptcp/protocol.c:814
Inline: True
Direct callers:
  - net/mptcp/protocol.c:mptcp_worker
  - net/mptcp/protocol.c:mptcp_recvmsg
```
**Symbols:**

```
ffffffff81baaeb0-ffffffff81baaf7d: mptcp_check_for_eof (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void mptcp_check_for_eof(struct mptcp_sock *msk);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/mptcp/protocol.c (ffffffff81c77f20)
Location: net/mptcp/protocol.c:833
Inline: True
Direct callers:
  - net/mptcp/protocol.c:mptcp_worker
  - net/mptcp/protocol.c:mptcp_recvmsg
```
**Symbols:**

```
ffffffff81c77f20-ffffffff81c77fdc: mptcp_check_for_eof (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void mptcp_check_for_eof(struct mptcp_sock *msk);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/mptcp/protocol.c (ffffffff81e1ca00)
Location: net/mptcp/protocol.c:894
Inline: True
Direct callers:
  - net/mptcp/protocol.c:mptcp_worker
  - net/mptcp/protocol.c:mptcp_recvmsg
```
**Symbols:**

```
ffffffff81e1ca00-ffffffff81e1caca: mptcp_check_for_eof (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void mptcp_check_for_eof(struct mptcp_sock *msk);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/mptcp/protocol.c (ffffffff81ff41f0)
Location: net/mptcp/protocol.c:886
Inline: True
Direct callers:
  - net/mptcp/protocol.c:mptcp_worker
  - net/mptcp/protocol.c:mptcp_recvmsg
```
**Symbols:**

```
ffffffff81ff41f0-ffffffff81ff42ba: mptcp_check_for_eof (STB_LOCAL)
```
</details>
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
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
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
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
</ul>
