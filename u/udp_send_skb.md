# Function: <code>udp_send_skb</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int udp_send_skb(struct sk_buff *skb, struct flowi4 *fl4);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/udp.c (ffffffff81786930)
Location: net/ipv4/udp.c:799
Inline: False
Direct callers:
  - net/ipv4/udp.c:udp_push_pending_frames
  - net/ipv4/udp.c:udp_sendmsg
```
**Symbols:**

```
ffffffff81786930-ffffffff81786b92: udp_send_skb (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int udp_send_skb(struct sk_buff *skb, struct flowi4 *fl4);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/udp.c (ffffffff817f3980)
Location: net/ipv4/udp.c:792
Inline: False
Direct callers:
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/udp.c:udp_push_pending_frames
```
**Symbols:**

```
ffffffff817f3980-ffffffff817f3bde: udp_send_skb (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int udp_send_skb(struct sk_buff *skb, struct flowi4 *fl4);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/udp.c (ffffffff81824770)
Location: net/ipv4/udp.c:794
Inline: False
Direct callers:
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/udp.c:udp_push_pending_frames
```
**Symbols:**

```
ffffffff81824770-ffffffff818249ce: udp_send_skb (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int udp_send_skb(struct sk_buff *skb, struct flowi4 *fl4);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/udp.c (ffffffff81845480)
Location: net/ipv4/udp.c:782
Inline: False
Direct callers:
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/udp.c:udp_push_pending_frames
```
**Symbols:**

```
ffffffff81845480-ffffffff8184571a: udp_send_skb (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int udp_send_skb(struct sk_buff *skb, struct flowi4 *fl4);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/udp.c (ffffffff818c4f10)
Location: net/ipv4/udp.c:786
Inline: False
Direct callers:
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/udp.c:udp_push_pending_frames
```
**Symbols:**

```
ffffffff818c4f10-ffffffff818c517b: udp_send_skb (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv4/udp.c (ffffffff8191b330)
Location: net/ipv4/udp.c:758
Inline: True
Direct callers:
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/udp.c:udp_push_pending_frames
```
**Symbols:**

```
ffffffff8191b330-ffffffff8191b68e: udp_send_skb.isra.41 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv4/udp.c (ffffffff819498b0)
Location: net/ipv4/udp.c:827
Inline: True
Direct callers:
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/udp.c:udp_push_pending_frames
```
**Symbols:**

```
ffffffff819498b0-ffffffff81949c11: udp_send_skb.isra.50 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv4/udp.c (ffffffff819adf30)
Location: net/ipv4/udp.c:814
Inline: True
Direct callers:
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/udp.c:udp_push_pending_frames
```
**Symbols:**

```
ffffffff819adf30-ffffffff819ae2a2: udp_send_skb.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv4/udp.c (ffffffff819e4c40)
Location: net/ipv4/udp.c:814
Inline: True
Direct callers:
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/udp.c:udp_push_pending_frames
```
**Symbols:**

```
ffffffff819e4c40-ffffffff819e4fba: udp_send_skb.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int udp_send_skb(struct sk_buff *skb, struct flowi4 *fl4, struct inet_cork *cork);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/udp.c (ffffffff81ad1d70)
Location: net/ipv4/udp.c:820
Inline: False
Direct callers:
  - net/ipv4/udp.c:udp_sendpage
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/udp.c:udp_sendmsg
```
**Symbols:**

```
ffffffff81ad1d70-ffffffff81ad20f0: udp_send_skb (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int udp_send_skb(struct sk_buff *skb, struct flowi4 *fl4, struct inet_cork *cork);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/udp.c (ffffffff81addeb0)
Location: net/ipv4/udp.c:870
Inline: False
Direct callers:
  - net/ipv4/udp.c:udp_sendpage
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/udp.c:udp_sendmsg
```
**Symbols:**

```
ffffffff81addeb0-ffffffff81ade230: udp_send_skb (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int udp_send_skb(struct sk_buff *skb, struct flowi4 *fl4, struct inet_cork *cork);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/udp.c (ffffffff81ac8ec0)
Location: net/ipv4/udp.c:889
Inline: False
Direct callers:
  - net/ipv4/udp.c:udp_sendpage
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/udp.c:udp_sendmsg
```
**Symbols:**

```
ffffffff81ac8ec0-ffffffff81ac9247: udp_send_skb (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int udp_send_skb(struct sk_buff *skb, struct flowi4 *fl4, struct inet_cork *cork);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/udp.c (ffffffff81b87750)
Location: net/ipv4/udp.c:890
Inline: False
Direct callers:
  - net/ipv4/udp.c:udp_sendpage
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/udp.c:udp_sendmsg
```
**Symbols:**

```
ffffffff81b87750-ffffffff81b87ad5: udp_send_skb (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int udp_send_skb(struct sk_buff *skb, struct flowi4 *fl4, struct inet_cork *cork);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/udp.c (ffffffff81d185c0)
Location: net/ipv4/udp.c:890
Inline: False
Direct callers:
  - net/ipv4/udp.c:udp_sendpage
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/udp.c:udp_sendmsg
```
**Symbols:**

```
ffffffff81d185c0-ffffffff81d1893a: udp_send_skb (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int udp_send_skb(struct sk_buff *skb, struct flowi4 *fl4, struct inet_cork *cork);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/udp.c (ffffffff81edef20)
Location: net/ipv4/udp.c:901
Inline: False
Direct callers:
  - net/ipv4/udp.c:udp_sendpage
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/udp.c:udp_sendmsg
```
**Symbols:**

```
ffffffff81edef20-ffffffff81edf29a: udp_send_skb (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int udp_send_skb(struct sk_buff *skb, struct flowi4 *fl4, struct inet_cork *cork);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/udp.c (ffffffff81f3e360)
Location: net/ipv4/udp.c:916
Inline: False
Direct callers:
  - net/ipv4/udp.c:udp_splice_eof
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/udp.c:udp_sendmsg
```
**Symbols:**

```
ffffffff81f3e360-ffffffff81f3e6d8: udp_send_skb (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int udp_send_skb(struct sk_buff *skb, struct flowi4 *fl4, struct inet_cork *cork);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/udp.c (ffffffff82004600)
Location: net/ipv4/udp.c:886
Inline: False
Direct callers:
  - net/ipv4/udp.c:udp_splice_eof
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/udp.c:udp_sendmsg
```
**Symbols:**

```
ffffffff82004600-ffffffff8200497c: udp_send_skb (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv4/udp.c (ffff800010c9cc68)
Location: net/ipv4/udp.c:814
Inline: True
Direct callers:
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/udp.c:udp_push_pending_frames
```
**Symbols:**

```
ffff800010c9cc68-ffff800010c9cfc0: udp_send_skb.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int udp_send_skb(struct sk_buff *skb, struct flowi4 *fl4, struct inet_cork *cork);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/udp.c (c0da7048)
Location: net/ipv4/udp.c:814
Inline: False
Direct callers:
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/udp.c:udp_push_pending_frames
```
**Symbols:**

```
c0da7048-c0da7394: udp_send_skb (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv4/udp.c (c000000000daf700)
Location: net/ipv4/udp.c:814
Inline: True
Direct callers:
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/udp.c:udp_push_pending_frames
```
**Symbols:**

```
c000000000daf700-c000000000dafb54: udp_send_skb.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv4/udp.c (ffffffe0007f7894)
Location: net/ipv4/udp.c:814
Inline: True
Direct callers:
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/udp.c:udp_push_pending_frames
```
**Symbols:**

```
ffffffe0007f7894-ffffffe0007f7bfe: udp_send_skb.isra.0 (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv4/udp.c (ffffffff81984ab0)
Location: net/ipv4/udp.c:814
Inline: True
Direct callers:
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/udp.c:udp_push_pending_frames
```
**Symbols:**

```
ffffffff81984ab0-ffffffff81984e2a: udp_send_skb.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv4/udp.c (ffffffff8193e570)
Location: net/ipv4/udp.c:814
Inline: True
Direct callers:
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/udp.c:udp_push_pending_frames
```
**Symbols:**

```
ffffffff8193e570-ffffffff8193e8ea: udp_send_skb.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv4/udp.c (ffffffff819ef280)
Location: net/ipv4/udp.c:814
Inline: True
Direct callers:
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/udp.c:udp_push_pending_frames
```
**Symbols:**

```
ffffffff819ef280-ffffffff819ef5fa: udp_send_skb.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In net/ipv4/udp.c (ffffffff819f9a70)
Location: net/ipv4/udp.c:814
Inline: True
Direct callers:
  - net/ipv4/udp.c:udp_sendmsg
  - net/ipv4/udp.c:udp_push_pending_frames
```
**Symbols:**

```
ffffffff819f9a70-ffffffff819f9dea: udp_send_skb.isra.0 (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
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
<b>Arch</b>
<ul>
</ul>
