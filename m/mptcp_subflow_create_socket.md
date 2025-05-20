# Function: <code>mptcp_subflow_create_socket</code>

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
int mptcp_subflow_create_socket(struct sock *sk, struct socket **new_sock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/mptcp/subflow.c (ffffffff81bafb30)
Location: net/mptcp/subflow.c:1028
Inline: False
Direct callers:
  - net/mptcp/protocol.c:__mptcp_socket_create
  - net/mptcp/subflow.c:__mptcp_subflow_connect
```
**Symbols:**

```
ffffffff81bafb30-ffffffff81bafcfc: mptcp_subflow_create_socket (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int mptcp_subflow_create_socket(struct sock *sk, struct socket **new_sock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/mptcp/subflow.c (ffffffff81bc3520)
Location: net/mptcp/subflow.c:1246
Inline: False
Direct callers:
  - net/mptcp/subflow.c:__mptcp_subflow_connect
```
**Symbols:**

```
ffffffff81bc3520-ffffffff81bc3804: mptcp_subflow_create_socket (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int mptcp_subflow_create_socket(struct sock *sk, struct socket **new_sock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/mptcp/subflow.c (ffffffff81bb3b90)
Location: net/mptcp/subflow.c:1379
Inline: False
Direct callers:
  - net/mptcp/subflow.c:__mptcp_subflow_connect
```
**Symbols:**

```
ffffffff81bb3b90-ffffffff81bb3ea1: mptcp_subflow_create_socket (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int mptcp_subflow_create_socket(struct sock *sk, struct socket **new_sock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/mptcp/subflow.c (ffffffff81c822e0)
Location: net/mptcp/subflow.c:1509
Inline: False
Direct callers:
  - net/mptcp/subflow.c:__mptcp_subflow_connect
```
**Symbols:**

```
ffffffff81c822e0-ffffffff81c825e3: mptcp_subflow_create_socket (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int mptcp_subflow_create_socket(struct sock *sk, struct socket **new_sock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/mptcp/subflow.c (ffffffff81e28000)
Location: net/mptcp/subflow.c:1598
Inline: False
Direct callers:
  - net/mptcp/subflow.c:__mptcp_subflow_connect
```
**Symbols:**

```
ffffffff81e28000-ffffffff81e28303: mptcp_subflow_create_socket (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int mptcp_subflow_create_socket(struct sock *sk, short unsigned int family, struct socket **new_sock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/mptcp/subflow.c (ffffffff81ffff60)
Location: net/mptcp/subflow.c:1672
Inline: False
Direct callers:
  - net/mptcp/subflow.c:__mptcp_subflow_connect
```
**Symbols:**

```
ffffffff81ffff60-ffffffff82000265: mptcp_subflow_create_socket (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int mptcp_subflow_create_socket(struct sock *sk, short unsigned int family, struct socket **new_sock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/mptcp/subflow.c (ffffffff8207c100)
Location: net/mptcp/subflow.c:1653
Inline: False
Direct callers:
  - net/mptcp/subflow.c:__mptcp_subflow_connect
```
**Symbols:**

```
ffffffff8207c100-ffffffff8207c437: mptcp_subflow_create_socket (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int mptcp_subflow_create_socket(struct sock *sk, short unsigned int family, struct socket **new_sock);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/mptcp/subflow.c (ffffffff821515d0)
Location: net/mptcp/subflow.c:1649
Inline: False
Direct callers:
  - net/mptcp/subflow.c:__mptcp_subflow_connect
```
**Symbols:**

```
ffffffff821515d0-ffffffff8215191e: mptcp_subflow_create_socket (STB_GLOBAL)
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
<details>
<summary>Changed between <code>5.19</code> and <code>6.2</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>short unsigned int family</code>
</li>
<li>
<b>Param reordered. </b>
<code>sk, new_sock</code> ➡️ <code>sk, family, new_sock</code>
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
