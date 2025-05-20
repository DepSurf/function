# Function: <code>mptcp_copy_inaddrs</code>

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
void mptcp_copy_inaddrs(struct sock *msk, const struct sock *ssk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/mptcp/protocol.c (ffffffff81ba9cc0)
Location: net/mptcp/protocol.c:1388
Inline: False
Direct callers:
  - net/mptcp/protocol.c:mptcp_listen
  - net/mptcp/protocol.c:mptcp_stream_connect
  - net/mptcp/protocol.c:mptcp_bind
  - net/mptcp/protocol.c:mptcp_accept
```
**Symbols:**

```
ffffffff81ba9cc0-ffffffff81ba9d9c: mptcp_copy_inaddrs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void mptcp_copy_inaddrs(struct sock *msk, const struct sock *ssk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/mptcp/protocol.c (ffffffff81bb9c90)
Location: net/mptcp/protocol.c:2623
Inline: False
Direct callers:
  - net/mptcp/protocol.c:mptcp_stream_accept
  - net/mptcp/protocol.c:mptcp_listen
  - net/mptcp/protocol.c:mptcp_stream_connect
  - net/mptcp/protocol.c:mptcp_bind
```
**Symbols:**

```
ffffffff81bb9c90-ffffffff81bb9d6c: mptcp_copy_inaddrs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void mptcp_copy_inaddrs(struct sock *msk, const struct sock *ssk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/mptcp/protocol.c (ffffffff81ba8f70)
Location: net/mptcp/protocol.c:2698
Inline: False
Direct callers:
  - net/mptcp/protocol.c:mptcp_stream_accept
  - net/mptcp/protocol.c:mptcp_listen
  - net/mptcp/protocol.c:mptcp_stream_connect
  - net/mptcp/protocol.c:mptcp_bind
```
**Symbols:**

```
ffffffff81ba8f70-ffffffff81ba904f: mptcp_copy_inaddrs (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void mptcp_copy_inaddrs(struct sock *msk, const struct sock *ssk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/mptcp/protocol.c (0)
Location: net/mptcp/protocol.c:2755
Inline: False
Direct callers:
  - net/mptcp/protocol.c:mptcp_stream_accept
  - net/mptcp/protocol.c:mptcp_listen
  - net/mptcp/protocol.c:mptcp_stream_connect
  - net/mptcp/protocol.c:mptcp_bind
```
**Symbols:**

```
ffffffff81c779c0-ffffffff81c77ad9: mptcp_copy_inaddrs (STB_LOCAL)
ffffffff81d432ad-ffffffff81d432f1: mptcp_copy_inaddrs.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void mptcp_copy_inaddrs(struct sock *msk, const struct sock *ssk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/mptcp/protocol.c (0)
Location: net/mptcp/protocol.c:2890
Inline: False
Direct callers:
  - net/mptcp/protocol.c:mptcp_stream_accept
  - net/mptcp/protocol.c:mptcp_listen
  - net/mptcp/protocol.c:mptcp_stream_connect
  - net/mptcp/protocol.c:mptcp_bind
```
**Symbols:**

```
ffffffff81e1cc70-ffffffff81e1cd97: mptcp_copy_inaddrs (STB_LOCAL)
ffffffff81f0fd87-ffffffff81f0fdcb: mptcp_copy_inaddrs.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void mptcp_copy_inaddrs(struct sock *msk, const struct sock *ssk);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/mptcp/protocol.c (0)
Location: net/mptcp/protocol.c:2978
Inline: False
Direct callers:
  - net/mptcp/protocol.c:mptcp_listen
  - net/mptcp/protocol.c:mptcp_bind
  - net/mptcp/protocol.c:mptcp_connect
  - net/mptcp/subflow.c:subflow_syn_recv_sock
  - net/mptcp/subflow.c:subflow_syn_recv_sock
```
**Symbols:**

```
ffffffff820b668f-ffffffff820b66d3: mptcp_copy_inaddrs.cold (STB_LOCAL)
ffffffff81ffa990-ffffffff81ffaab7: mptcp_copy_inaddrs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void mptcp_copy_inaddrs(struct sock *msk, const struct sock *ssk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/mptcp/protocol.c (0)
Location: net/mptcp/protocol.c:3005
Inline: False
Direct callers:
  - net/mptcp/protocol.c:mptcp_listen
  - net/mptcp/protocol.c:mptcp_bind
  - net/mptcp/protocol.c:mptcp_connect
  - net/mptcp/protocol.c:mptcp_sk_clone_init
```
**Symbols:**

```
ffffffff820708c0-ffffffff820709e0: mptcp_copy_inaddrs (STB_LOCAL)
ffffffff82137678-ffffffff821376aa: mptcp_copy_inaddrs.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void mptcp_copy_inaddrs(struct sock *msk, const struct sock *ssk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/mptcp/protocol.c (0)
Location: net/mptcp/protocol.c:3103
Inline: False
Direct callers:
  - net/mptcp/protocol.c:mptcp_listen
  - net/mptcp/protocol.c:mptcp_bind
  - net/mptcp/protocol.c:mptcp_connect
  - net/mptcp/protocol.c:mptcp_sk_clone_init
```
**Symbols:**

```
ffffffff82144f10-ffffffff82145030: mptcp_copy_inaddrs (STB_LOCAL)
ffffffff82219503-ffffffff82219535: mptcp_copy_inaddrs.cold (STB_LOCAL)
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
