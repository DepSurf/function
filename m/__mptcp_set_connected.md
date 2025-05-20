# Function: <code>__mptcp_set_connected</code>

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
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void __mptcp_set_connected(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/mptcp/subflow.c (ffffffff81bb144b)
Location: net/mptcp/subflow.c:369
Inline: True
Inline callers:
  - net/mptcp/subflow.c:mptcp_set_connected
  - net/mptcp/subflow.c:mptcp_set_connected
Direct callers:
  - net/mptcp/protocol.c:mptcp_release_cb
```
**Symbols:**

```
ffffffff81bb34f0-ffffffff81bb3526: __mptcp_set_connected (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void __mptcp_set_connected(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/mptcp/subflow.c (ffffffff81c7f5fb)
Location: net/mptcp/subflow.c:377
Inline: True
Inline callers:
  - net/mptcp/subflow.c:mptcp_set_connected
  - net/mptcp/subflow.c:mptcp_set_connected
Direct callers:
  - net/mptcp/protocol.c:mptcp_release_cb
```
**Symbols:**

```
ffffffff81c81c00-ffffffff81c81c36: __mptcp_set_connected (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void __mptcp_set_connected(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/mptcp/subflow.c (ffffffff81e24ba8)
Location: net/mptcp/subflow.c:377
Inline: True
Inline callers:
  - net/mptcp/subflow.c:mptcp_set_connected
  - net/mptcp/subflow.c:mptcp_set_connected
Direct callers:
  - net/mptcp/protocol.c:mptcp_release_cb
```
**Symbols:**

```
ffffffff81e27760-ffffffff81e277aa: __mptcp_set_connected (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void __mptcp_set_connected(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/mptcp/subflow.c (ffffffff81ffc708)
Location: net/mptcp/subflow.c:417
Inline: True
Inline callers:
  - net/mptcp/subflow.c:mptcp_set_connected
  - net/mptcp/subflow.c:mptcp_set_connected
Direct callers:
  - net/mptcp/protocol.c:mptcp_release_cb
```
**Symbols:**

```
ffffffff81ffef20-ffffffff81ffef6a: __mptcp_set_connected (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void __mptcp_set_connected(struct sock *sk);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/mptcp/subflow.c (ffffffff82078a48)
Location: net/mptcp/subflow.c:422
Inline: True
Inline callers:
  - net/mptcp/subflow.c:mptcp_set_connected
  - net/mptcp/subflow.c:mptcp_set_connected
Direct callers:
  - net/mptcp/protocol.c:mptcp_release_cb
```
**Symbols:**

```
ffffffff8207b000-ffffffff8207b04a: __mptcp_set_connected (STB_GLOBAL)
```
</details>
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
</ul>
