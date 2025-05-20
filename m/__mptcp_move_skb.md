# Function: <code>__mptcp_move_skb</code>

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
void __mptcp_move_skb(struct mptcp_sock *msk, struct sock *ssk, struct sk_buff *skb, unsigned int offset, size_t copy_len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/mptcp/protocol.c (ffffffff81bab580)
Location: net/mptcp/protocol.c:142
Inline: False
Direct callers:
  - net/mptcp/protocol.c:__mptcp_move_skbs_from_subflow
```
**Symbols:**

```
ffffffff81bab580-ffffffff81bab745: __mptcp_move_skb (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
bool __mptcp_move_skb(struct mptcp_sock *msk, struct sock *ssk, struct sk_buff *skb, unsigned int offset, size_t copy_len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/mptcp/protocol.c (ffffffff81bbd100)
Location: net/mptcp/protocol.c:274
Inline: False
Direct callers:
  - net/mptcp/protocol.c:__mptcp_move_skbs_from_subflow
```
**Symbols:**

```
ffffffff81bbd100-ffffffff81bbd3e0: __mptcp_move_skb (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
bool __mptcp_move_skb(struct mptcp_sock *msk, struct sock *ssk, struct sk_buff *skb, unsigned int offset, size_t copy_len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/mptcp/protocol.c (ffffffff81bac950)
Location: net/mptcp/protocol.c:268
Inline: False
Direct callers:
  - net/mptcp/protocol.c:__mptcp_move_skbs_from_subflow
```
**Symbols:**

```
ffffffff81bac950-ffffffff81bacbf0: __mptcp_move_skb (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
bool __mptcp_move_skb(struct mptcp_sock *msk, struct sock *ssk, struct sk_buff *skb, unsigned int offset, size_t copy_len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/mptcp/protocol.c (ffffffff81c792d0)
Location: net/mptcp/protocol.c:273
Inline: False
Direct callers:
  - net/mptcp/protocol.c:__mptcp_move_skbs_from_subflow
```
**Symbols:**

```
ffffffff81c792d0-ffffffff81c79595: __mptcp_move_skb (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
bool __mptcp_move_skb(struct mptcp_sock *msk, struct sock *ssk, struct sk_buff *skb, unsigned int offset, size_t copy_len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/mptcp/protocol.c (ffffffff81e1e260)
Location: net/mptcp/protocol.c:344
Inline: False
Direct callers:
  - net/mptcp/protocol.c:__mptcp_move_skbs_from_subflow
```
**Symbols:**

```
ffffffff81e1e260-ffffffff81e1e4ec: __mptcp_move_skb (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
bool __mptcp_move_skb(struct mptcp_sock *msk, struct sock *ssk, struct sk_buff *skb, unsigned int offset, size_t copy_len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/mptcp/protocol.c (ffffffff81ff6cb0)
Location: net/mptcp/protocol.c:336
Inline: False
Direct callers:
  - net/mptcp/protocol.c:__mptcp_move_skbs_from_subflow
```
**Symbols:**

```
ffffffff81ff6cb0-ffffffff81ff6f06: __mptcp_move_skb (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
bool __mptcp_move_skb(struct mptcp_sock *msk, struct sock *ssk, struct sk_buff *skb, unsigned int offset, size_t copy_len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/mptcp/protocol.c (ffffffff82073390)
Location: net/mptcp/protocol.c:350
Inline: False
Direct callers:
  - net/mptcp/protocol.c:__mptcp_move_skbs_from_subflow
```
**Symbols:**

```
ffffffff82073390-ffffffff820735f0: __mptcp_move_skb (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
bool __mptcp_move_skb(struct mptcp_sock *msk, struct sock *ssk, struct sk_buff *skb, unsigned int offset, size_t copy_len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/mptcp/protocol.c (ffffffff821475e0)
Location: net/mptcp/protocol.c:338
Inline: False
Direct callers:
  - net/mptcp/protocol.c:__mptcp_move_skbs_from_subflow
```
**Symbols:**

```
ffffffff821475e0-ffffffff82147848: __mptcp_move_skb (STB_LOCAL)
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
<details>
<summary>Changed between <code>5.8</code> and <code>5.11</code> ⚠️</summary>
<ul>
<li>
<b>Return type changed. </b>
<code>void</code> ➡️ <code>bool</code>
</li>
</ul>
</details>
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
