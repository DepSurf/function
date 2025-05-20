# Function: <code>__skb_ext_alloc</code>

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
struct skb_ext *__skb_ext_alloc(gfp_t flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff819f4290)
Location: net/core/skbuff.c:6098
Inline: False
Direct callers:
  - net/core/skbuff.c:skb_ext_add
  - net/mptcp/protocol.c:mptcp_worker
  - net/mptcp/protocol.c:mptcp_worker
  - net/mptcp/protocol.c:mptcp_sendmsg
  - net/mptcp/protocol.c:mptcp_subflow_get_send
```
**Symbols:**

```
ffffffff819f4290-ffffffff819f42bb: __skb_ext_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct skb_ext *__skb_ext_alloc(gfp_t flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff819f42b0)
Location: net/core/skbuff.c:6235
Inline: False
Direct callers:
  - net/core/skbuff.c:skb_ext_add
  - net/mptcp/protocol.c:__mptcp_alloc_tx_skb
  - net/mptcp/protocol.c:__mptcp_do_alloc_tx_skb
```
**Symbols:**

```
ffffffff819f42b0-ffffffff819f42db: __skb_ext_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct skb_ext *__skb_ext_alloc(gfp_t flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff819da470)
Location: net/core/skbuff.c:6323
Inline: False
Direct callers:
  - net/core/skbuff.c:skb_ext_add
  - net/mptcp/protocol.c:__mptcp_alloc_tx_skb
  - net/mptcp/protocol.c:__mptcp_do_alloc_tx_skb
```
**Symbols:**

```
ffffffff819da470-ffffffff819da49b: __skb_ext_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct skb_ext *__skb_ext_alloc(gfp_t flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff81a8a480)
Location: net/core/skbuff.c:6398
Inline: False
Direct callers:
  - net/core/skbuff.c:skb_ext_add
  - net/mptcp/protocol.c:mptcp_alloc_tx_skb
  - net/mptcp/protocol.c:mptcp_alloc_tx_skb
```
**Symbols:**

```
ffffffff81a8a480-ffffffff81a8a4ab: __skb_ext_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct skb_ext *__skb_ext_alloc(gfp_t flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff81bff8d0)
Location: net/core/skbuff.c:6311
Inline: False
Direct callers:
  - net/core/skbuff.c:skb_ext_add
  - net/mptcp/protocol.c:mptcp_sendmsg_frag
```
**Symbols:**

```
ffffffff81bff8d0-ffffffff81bff903: __skb_ext_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct skb_ext *__skb_ext_alloc(gfp_t flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff81daed70)
Location: net/core/skbuff.c:6512
Inline: False
Direct callers:
  - net/core/skbuff.c:skb_ext_add
  - net/mptcp/protocol.c:mptcp_sendmsg_frag
```
**Symbols:**

```
ffffffff81daed70-ffffffff81daeda3: __skb_ext_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct skb_ext *__skb_ext_alloc(gfp_t flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff81e1ef60)
Location: net/core/skbuff.c:6557
Inline: False
Direct callers:
  - net/core/skbuff.c:skb_ext_add
  - net/mptcp/protocol.c:mptcp_sendmsg_frag
```
**Symbols:**

```
ffffffff81e1ef60-ffffffff81e1ef93: __skb_ext_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct skb_ext *__skb_ext_alloc(gfp_t flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff81edc5c0)
Location: net/core/skbuff.c:6704
Inline: False
Direct callers:
  - net/core/skbuff.c:skb_ext_add
  - net/mptcp/protocol.c:mptcp_sendmsg_frag
```
**Symbols:**

```
ffffffff81edc5c0-ffffffff81edc5f3: __skb_ext_alloc (STB_GLOBAL)
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
