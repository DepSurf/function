# Function: <code>mptcp_sockopt_sync_locked</code>

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
<summary>In <code>5.19</code>: ✅</summary>

```c
void mptcp_sockopt_sync_locked(struct mptcp_sock *msk, struct sock *ssk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/mptcp/sockopt.c (ffffffff81e350b0)
Location: net/mptcp/sockopt.c:1299
Inline: False
Direct callers:
  - net/mptcp/protocol.c:mptcp_finish_join
  - net/mptcp/protocol.c:mptcp_release_cb
```
**Symbols:**

```
ffffffff81e350b0-ffffffff81e350f8: mptcp_sockopt_sync_locked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void mptcp_sockopt_sync_locked(struct mptcp_sock *msk, struct sock *ssk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/mptcp/sockopt.c (ffffffff8200dd30)
Location: net/mptcp/sockopt.c:1320
Inline: False
Direct callers:
  - net/mptcp/protocol.c:mptcp_finish_join
  - net/mptcp/protocol.c:mptcp_release_cb
```
**Symbols:**

```
ffffffff8200dd30-ffffffff8200dd78: mptcp_sockopt_sync_locked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void mptcp_sockopt_sync_locked(struct mptcp_sock *msk, struct sock *ssk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/mptcp/sockopt.c (ffffffff8208a720)
Location: net/mptcp/sockopt.c:1470
Inline: False
```
**Symbols:**

```
ffffffff8208a720-ffffffff8208a768: mptcp_sockopt_sync_locked (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void mptcp_sockopt_sync_locked(struct mptcp_sock *msk, struct sock *ssk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/mptcp/sockopt.c (ffffffff821600f0)
Location: net/mptcp/sockopt.c:1474
Inline: False
Direct callers:
  - net/mptcp/subflow.c:mptcp_subflow_create_socket
```
**Symbols:**

```
ffffffff821600f0-ffffffff8216014c: mptcp_sockopt_sync_locked (STB_GLOBAL)
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
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
