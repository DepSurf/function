# Function: <code>__skb_ext_set</code>

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
void *__skb_ext_set(struct sk_buff *skb, enum skb_ext_id id, struct skb_ext *ext);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff819f4490)
Location: net/core/skbuff.c:6148
Inline: False
```
**Symbols:**

```
ffffffff819f4490-ffffffff819f44fb: __skb_ext_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void *__skb_ext_set(struct sk_buff *skb, enum skb_ext_id id, struct skb_ext *ext);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff819f44b0)
Location: net/core/skbuff.c:6285
Inline: False
Direct callers:
  - net/mptcp/protocol.c:__mptcp_alloc_tx_skb
  - net/mptcp/protocol.c:__mptcp_do_alloc_tx_skb
```
**Symbols:**

```
ffffffff819f44b0-ffffffff819f451b: __skb_ext_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void *__skb_ext_set(struct sk_buff *skb, enum skb_ext_id id, struct skb_ext *ext);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff819da660)
Location: net/core/skbuff.c:6373
Inline: False
Direct callers:
  - net/mptcp/protocol.c:__mptcp_alloc_tx_skb
  - net/mptcp/protocol.c:__mptcp_do_alloc_tx_skb
```
**Symbols:**

```
ffffffff819da660-ffffffff819da6cb: __skb_ext_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void *__skb_ext_set(struct sk_buff *skb, enum skb_ext_id id, struct skb_ext *ext);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/skbuff.c (0)
Location: net/core/skbuff.c:6448
Inline: False
Direct callers:
  - net/mptcp/protocol.c:mptcp_alloc_tx_skb
  - net/mptcp/protocol.c:mptcp_alloc_tx_skb
```
**Symbols:**

```
ffffffff81d35444-ffffffff81d3545d: __skb_ext_set.cold (STB_LOCAL)
ffffffff81a8a750-ffffffff81a8a816: __skb_ext_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void *__skb_ext_set(struct sk_buff *skb, enum skb_ext_id id, struct skb_ext *ext);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/skbuff.c (0)
Location: net/core/skbuff.c:6361
Inline: False
Direct callers:
  - net/mptcp/protocol.c:mptcp_sendmsg_frag
```
**Symbols:**

```
ffffffff81f01960-ffffffff81f01979: __skb_ext_set.cold (STB_LOCAL)
ffffffff81bffbc0-ffffffff81bffc92: __skb_ext_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void *__skb_ext_set(struct sk_buff *skb, enum skb_ext_id id, struct skb_ext *ext);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/skbuff.c (0)
Location: net/core/skbuff.c:6562
Inline: False
Direct callers:
  - net/mptcp/protocol.c:mptcp_sendmsg_frag
```
**Symbols:**

```
ffffffff820aada0-ffffffff820aadb9: __skb_ext_set.cold (STB_LOCAL)
ffffffff81daef40-ffffffff81daf012: __skb_ext_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void *__skb_ext_set(struct sk_buff *skb, enum skb_ext_id id, struct skb_ext *ext);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/skbuff.c (0)
Location: net/core/skbuff.c:6607
Inline: False
Direct callers:
  - net/mptcp/protocol.c:mptcp_sendmsg_frag
```
**Symbols:**

```
ffffffff8212c3a2-ffffffff8212c3bb: __skb_ext_set.cold (STB_LOCAL)
ffffffff81e1f130-ffffffff81e1f202: __skb_ext_set (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void *__skb_ext_set(struct sk_buff *skb, enum skb_ext_id id, struct skb_ext *ext);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/skbuff.c (0)
Location: net/core/skbuff.c:6754
Inline: False
Direct callers:
  - net/mptcp/protocol.c:mptcp_sendmsg_frag
```
**Symbols:**

```
ffffffff8220e078-ffffffff8220e091: __skb_ext_set.cold (STB_LOCAL)
ffffffff81edc790-ffffffff81edc862: __skb_ext_set (STB_GLOBAL)
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
