# Function: <code>mptcp_sync_mss</code>

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
<summary>In <code>5.8</code>: ✅</summary>

```c
unsigned int mptcp_sync_mss(struct sock *sk, u32 pmtu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/mptcp/protocol.c (ffffffff81ba9cb0)
Location: net/mptcp/protocol.c:1173
Inline: False
```
**Symbols:**

```
ffffffff81ba9cb0-ffffffff81ba9cbd: mptcp_sync_mss (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
unsigned int mptcp_sync_mss(struct sock *sk, u32 pmtu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/mptcp/protocol.c (ffffffff81bb9c80)
Location: net/mptcp/protocol.c:2165
Inline: False
```
**Symbols:**

```
ffffffff81bb9c80-ffffffff81bb9c8d: mptcp_sync_mss (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
unsigned int mptcp_sync_mss(struct sock *sk, u32 pmtu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/mptcp/protocol.c (ffffffff81ba8f60)
Location: net/mptcp/protocol.c:2230
Inline: False
```
**Symbols:**

```
ffffffff81ba8f60-ffffffff81ba8f6d: mptcp_sync_mss (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
unsigned int mptcp_sync_mss(struct sock *sk, u32 pmtu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/mptcp/protocol.c (ffffffff81c76d20)
Location: net/mptcp/protocol.c:2295
Inline: False
```
**Symbols:**

```
ffffffff81c76d20-ffffffff81c76d2d: mptcp_sync_mss (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
unsigned int mptcp_sync_mss(struct sock *sk, u32 pmtu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/mptcp/protocol.c (ffffffff81e1b760)
Location: net/mptcp/protocol.c:2385
Inline: False
```
**Symbols:**

```
ffffffff81e1b760-ffffffff81e1b771: mptcp_sync_mss (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
unsigned int mptcp_sync_mss(struct sock *sk, u32 pmtu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/mptcp/protocol.c (ffffffff81ff2d80)
Location: net/mptcp/protocol.c:2398
Inline: False
```
**Symbols:**

```
ffffffff81ff2d80-ffffffff81ff2d91: mptcp_sync_mss (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
unsigned int mptcp_sync_mss(struct sock *sk, u32 pmtu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/mptcp/protocol.c (ffffffff8206f000)
Location: net/mptcp/protocol.c:2407
Inline: False
```
**Symbols:**

```
ffffffff8206f000-ffffffff8206f011: mptcp_sync_mss (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
unsigned int mptcp_sync_mss(struct sock *sk, u32 pmtu);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/mptcp/protocol.c (ffffffff821430e0)
Location: net/mptcp/protocol.c:2492
Inline: False
```
**Symbols:**

```
ffffffff821430e0-ffffffff821430f1: mptcp_sync_mss (STB_LOCAL)
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
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
