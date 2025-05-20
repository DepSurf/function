# Function: <code>__mptcp_clean_una</code>

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
void __mptcp_clean_una(struct sock *sk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/mptcp/protocol.c (ffffffff81bbc950)
Location: net/mptcp/protocol.c:990
Inline: False
Direct callers:
  - net/mptcp/protocol.c:mptcp_release_cb
  - net/mptcp/protocol.c:__mptcp_data_acked
  - net/mptcp/protocol.c:mptcp_worker
```
**Symbols:**

```
ffffffff81bbc950-ffffffff81bbccc9: __mptcp_clean_una (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void __mptcp_clean_una(struct sock *sk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/mptcp/protocol.c (ffffffff81bac100)
Location: net/mptcp/protocol.c:1033
Inline: False
Direct callers:
  - net/mptcp/protocol.c:mptcp_release_cb
  - net/mptcp/protocol.c:__mptcp_data_acked
  - net/mptcp/protocol.c:__mptcp_retrans
```
**Symbols:**

```
ffffffff81bac100-ffffffff81bac544: __mptcp_clean_una (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void __mptcp_clean_una(struct sock *sk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/mptcp/protocol.c (0)
Location: net/mptcp/protocol.c:1050
Inline: False
Direct callers:
  - net/mptcp/protocol.c:mptcp_release_cb
  - net/mptcp/protocol.c:__mptcp_data_acked
  - net/mptcp/protocol.c:__mptcp_retrans
```
**Symbols:**

```
ffffffff81c79840-ffffffff81c79ce2: __mptcp_clean_una (STB_LOCAL)
ffffffff81d4345f-ffffffff81d434ed: __mptcp_clean_una.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void __mptcp_clean_una(struct sock *sk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/mptcp/protocol.c (0)
Location: net/mptcp/protocol.c:1009
Inline: False
Direct callers:
  - net/mptcp/protocol.c:mptcp_release_cb
  - net/mptcp/protocol.c:__mptcp_data_acked
  - net/mptcp/protocol.c:__mptcp_retrans
  - net/mptcp/protocol.c:__mptcp_retransmit_pending_data
```
**Symbols:**

```
ffffffff81e1da80-ffffffff81e1de64: __mptcp_clean_una (STB_LOCAL)
ffffffff81f0fee0-ffffffff81f0ff8f: __mptcp_clean_una.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void __mptcp_clean_una(struct sock *sk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/mptcp/protocol.c (0)
Location: net/mptcp/protocol.c:982
Inline: False
Direct callers:
  - net/mptcp/protocol.c:mptcp_release_cb
  - net/mptcp/protocol.c:__mptcp_data_acked
  - net/mptcp/protocol.c:__mptcp_retrans
  - net/mptcp/protocol.c:__mptcp_retransmit_pending_data
```
**Symbols:**

```
ffffffff81ff4fa0-ffffffff81ff52b8: __mptcp_clean_una (STB_LOCAL)
ffffffff820b61e2-ffffffff820b623a: __mptcp_clean_una.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void __mptcp_clean_una(struct sock *sk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/mptcp/protocol.c (0)
Location: net/mptcp/protocol.c:959
Inline: False
Direct callers:
  - net/mptcp/protocol.c:mptcp_release_cb
  - net/mptcp/protocol.c:__mptcp_data_acked
  - net/mptcp/protocol.c:__mptcp_retrans
  - net/mptcp/protocol.c:__mptcp_retransmit_pending_data
```
**Symbols:**

```
ffffffff820717c0-ffffffff82071ab4: __mptcp_clean_una (STB_LOCAL)
ffffffff821377a4-ffffffff821377fc: __mptcp_clean_una.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void __mptcp_clean_una(struct sock *sk);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/mptcp/protocol.c (0)
Location: net/mptcp/protocol.c:988
Inline: False
Direct callers:
  - net/mptcp/protocol.c:mptcp_release_cb
  - net/mptcp/protocol.c:__mptcp_data_acked
  - net/mptcp/protocol.c:__mptcp_retrans
  - net/mptcp/protocol.c:__mptcp_retransmit_pending_data
```
**Symbols:**

```
ffffffff82145940-ffffffff82145c34: __mptcp_clean_una (STB_LOCAL)
ffffffff82219569-ffffffff822195c1: __mptcp_clean_una.cold (STB_LOCAL)
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
