# Function: <code>sync_socket_options</code>

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
<summary>In <code>5.13</code>: ✅</summary>

```c
void sync_socket_options(struct mptcp_sock *msk, struct sock *ssk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/mptcp/sockopt.c (ffffffff81bbbf90)
Location: net/mptcp/sockopt.c:669
Inline: False
Direct callers:
  - net/mptcp/sockopt.c:mptcp_sockopt_sync_all
  - net/mptcp/sockopt.c:mptcp_sockopt_sync
```
**Symbols:**

```
ffffffff81bbbf90-ffffffff81bbc11f: sync_socket_options (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void sync_socket_options(struct mptcp_sock *msk, struct sock *ssk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/mptcp/sockopt.c (ffffffff81c8bb30)
Location: net/mptcp/sockopt.c:711
Inline: False
Direct callers:
  - net/mptcp/sockopt.c:mptcp_sockopt_sync_all
  - net/mptcp/sockopt.c:mptcp_sockopt_sync
```
**Symbols:**

```
ffffffff81c8bb30-ffffffff81c8bcbf: sync_socket_options (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void sync_socket_options(struct mptcp_sock *msk, struct sock *ssk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/mptcp/sockopt.c (ffffffff81e331a0)
Location: net/mptcp/sockopt.c:1229
Inline: False
Direct callers:
  - net/mptcp/sockopt.c:mptcp_sockopt_sync_locked
  - net/mptcp/sockopt.c:mptcp_sockopt_sync
```
**Symbols:**

```
ffffffff81e331a0-ffffffff81e333b6: sync_socket_options (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void sync_socket_options(struct mptcp_sock *msk, struct sock *ssk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/mptcp/sockopt.c (ffffffff8200c8a0)
Location: net/mptcp/sockopt.c:1250
Inline: False
Direct callers:
  - net/mptcp/sockopt.c:mptcp_sockopt_sync_locked
  - net/mptcp/sockopt.c:mptcp_sockopt_sync
```
**Symbols:**

```
ffffffff8200c8a0-ffffffff8200cac2: sync_socket_options (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void sync_socket_options(struct mptcp_sock *msk, struct sock *ssk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/mptcp/sockopt.c (ffffffff820891e0)
Location: net/mptcp/sockopt.c:1399
Inline: False
Direct callers:
  - net/mptcp/sockopt.c:mptcp_sockopt_sync_locked
  - net/mptcp/sockopt.c:mptcp_sockopt_sync
```
**Symbols:**

```
ffffffff820891e0-ffffffff82089417: sync_socket_options (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/mptcp/sockopt.c (ffffffff8215ec70)
Location: net/mptcp/sockopt.c:1421
Inline: True
Direct callers:
  - net/mptcp/sockopt.c:mptcp_sockopt_sync_locked
```
**Symbols:**

```
ffffffff8215ec70-ffffffff8215ef04: sync_socket_options.constprop.0 (STB_LOCAL)
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
