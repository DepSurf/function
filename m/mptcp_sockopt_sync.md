# Function: <code>mptcp_sockopt_sync</code>

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
void mptcp_sockopt_sync(struct mptcp_sock *msk, struct sock *ssk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/mptcp/sockopt.c (ffffffff81bbcb20)
Location: net/mptcp/sockopt.c:720
Inline: False
Direct callers:
  - net/mptcp/subflow.c:__mptcp_subflow_connect
```
**Symbols:**

```
ffffffff81bbcb20-ffffffff81bbcb9d: mptcp_sockopt_sync (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void mptcp_sockopt_sync(struct mptcp_sock *msk, struct sock *ssk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/mptcp/sockopt.c (ffffffff81c8c980)
Location: net/mptcp/sockopt.c:762
Inline: False
Direct callers:
  - net/mptcp/subflow.c:__mptcp_subflow_connect
```
**Symbols:**

```
ffffffff81c8c980-ffffffff81c8c9fd: mptcp_sockopt_sync (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void mptcp_sockopt_sync(struct mptcp_sock *msk, struct sock *ssk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/mptcp/sockopt.c (ffffffff81e35010)
Location: net/mptcp/sockopt.c:1286
Inline: False
Direct callers:
  - net/mptcp/subflow.c:__mptcp_subflow_connect
```
**Symbols:**

```
ffffffff81e35010-ffffffff81e350a2: mptcp_sockopt_sync (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void mptcp_sockopt_sync(struct mptcp_sock *msk, struct sock *ssk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/mptcp/sockopt.c (ffffffff8200dc80)
Location: net/mptcp/sockopt.c:1307
Inline: False
Direct callers:
  - net/mptcp/subflow.c:__mptcp_subflow_connect
```
**Symbols:**

```
ffffffff8200dc80-ffffffff8200dd12: mptcp_sockopt_sync (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void mptcp_sockopt_sync(struct mptcp_sock *msk, struct sock *ssk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/mptcp/sockopt.c (ffffffff8208a670)
Location: net/mptcp/sockopt.c:1457
Inline: False
Direct callers:
  - net/mptcp/subflow.c:__mptcp_subflow_connect
```
**Symbols:**

```
ffffffff8208a670-ffffffff8208a702: mptcp_sockopt_sync (STB_GLOBAL)
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
