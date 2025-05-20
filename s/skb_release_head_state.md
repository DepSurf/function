# Function: <code>skb_release_head_state</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void skb_release_head_state(struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff817053f0)
Location: net/core/skbuff.c:646
Inline: False
Direct callers:
  - net/core/skbuff.c:skb_release_all
  - net/core/skbuff.c:skb_segment
```
**Symbols:**

```
ffffffff817053f0-ffffffff81705496: skb_release_head_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void skb_release_head_state(struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff8176c060)
Location: net/core/skbuff.c:647
Inline: False
Direct callers:
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_release_all
```
**Symbols:**

```
ffffffff8176c060-ffffffff8176c0ff: skb_release_head_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void skb_release_head_state(struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff81799240)
Location: net/core/skbuff.c:647
Inline: False
Direct callers:
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_release_all
```
**Symbols:**

```
ffffffff81799240-ffffffff817992df: skb_release_head_state (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void skb_release_head_state(struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff817bb3f0)
Location: net/core/skbuff.c:646
Inline: False
Direct callers:
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_release_all
  - net/ipv4/udp.c:udp_queue_rcv_skb
```
**Symbols:**

```
ffffffff817bb3f0-ffffffff817bb48c: skb_release_head_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void skb_release_head_state(struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff81833460)
Location: net/core/skbuff.c:606
Inline: False
Direct callers:
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_release_all
```
**Symbols:**

```
ffffffff81833460-ffffffff81833512: skb_release_head_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void skb_release_head_state(struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff8187d900)
Location: net/core/skbuff.c:606
Inline: False
Direct callers:
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_release_all
```
**Symbols:**

```
ffffffff8187d900-ffffffff8187d9ba: skb_release_head_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void skb_release_head_state(struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff8189e500)
Location: net/core/skbuff.c:613
Inline: False
Direct callers:
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_release_all
```
**Symbols:**

```
ffffffff8189e500-ffffffff8189e58d: skb_release_head_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void skb_release_head_state(struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/skbuff.c (0)
Location: net/core/skbuff.c:647
Inline: False
Direct callers:
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_release_all
```
**Symbols:**

```
ffffffff818ef1e1-ffffffff818ef1f8: skb_release_head_state.cold (STB_LOCAL)
ffffffff818e8d70-ffffffff818e8df5: skb_release_head_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void skb_release_head_state(struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff8191aed0)
Location: net/core/skbuff.c:647
Inline: False
Direct callers:
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_release_all
```
**Symbols:**

```
ffffffff8191aed0-ffffffff8191af55: skb_release_head_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void skb_release_head_state(struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff819ed4b0)
Location: net/core/skbuff.c:646
Inline: False
Direct callers:
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment_list
  - net/core/skbuff.c:skb_morph
  - net/core/skbuff.c:__kfree_skb_defer
  - net/ipv4/udp.c:skb_consume_udp
```
**Symbols:**

```
ffffffff819ed4b0-ffffffff819ed53d: skb_release_head_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void skb_release_head_state(struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff819ed180)
Location: net/core/skbuff.c:660
Inline: False
Direct callers:
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment_list
  - net/core/skbuff.c:skb_morph
  - net/core/skbuff.c:__kfree_skb_defer
  - net/ipv4/udp.c:skb_consume_udp
```
**Symbols:**

```
ffffffff819ed180-ffffffff819ed20d: skb_release_head_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void skb_release_head_state(struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff819d3550)
Location: net/core/skbuff.c:708
Inline: False
Direct callers:
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment_list
  - net/core/skbuff.c:skb_morph
  - net/core/skbuff.c:__kfree_skb_defer
  - net/ipv4/udp.c:skb_consume_udp
```
**Symbols:**

```
ffffffff819d3550-ffffffff819d35dd: skb_release_head_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void skb_release_head_state(struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff81a832b0)
Location: net/core/skbuff.c:724
Inline: False
Direct callers:
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment_list
  - net/core/skbuff.c:skb_morph
  - net/core/skbuff.c:__kfree_skb_defer
  - net/ipv4/udp.c:skb_consume_udp
```
**Symbols:**

```
ffffffff81a832b0-ffffffff81a8333d: skb_release_head_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void skb_release_head_state(struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff81bf80d0)
Location: net/core/skbuff.c:724
Inline: False
Direct callers:
  - net/core/skbuff.c:skb_attempt_defer_free
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment_list
  - net/core/skbuff.c:skb_morph
  - net/core/skbuff.c:__kfree_skb_defer
  - net/ipv4/udp.c:skb_consume_udp
```
**Symbols:**

```
ffffffff81bf80d0-ffffffff81bf8195: skb_release_head_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void skb_release_head_state(struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff81da6ea0)
Location: net/core/skbuff.c:898
Inline: False
Direct callers:
  - net/core/skbuff.c:skb_attempt_defer_free
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment_list
  - net/core/skbuff.c:skb_morph
  - net/core/skbuff.c:__kfree_skb_defer
  - net/core/skbuff.c:kfree_skb_reason
  - net/ipv4/udp.c:skb_consume_udp
```
**Symbols:**

```
ffffffff81da6ea0-ffffffff81da6f47: skb_release_head_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void skb_release_head_state(struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff81e160f0)
Location: net/core/skbuff.c:989
Inline: False
Direct callers:
  - net/core/skbuff.c:skb_attempt_defer_free
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment_list
  - net/core/skbuff.c:skb_morph
  - net/core/skbuff.c:__napi_kfree_skb
  - net/core/skbuff.c:kfree_skb_list_reason
  - net/core/skbuff.c:kfree_skb_list_reason
  - net/core/skbuff.c:kfree_skb_reason
  - net/ipv4/udp.c:skb_consume_udp
```
**Symbols:**

```
ffffffff81e160f0-ffffffff81e16197: skb_release_head_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void skb_release_head_state(struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff81ed3510)
Location: net/core/skbuff.c:1075
Inline: False
Direct callers:
  - net/core/skbuff.c:skb_attempt_defer_free
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment_list
  - net/core/skbuff.c:skb_morph
  - net/core/skbuff.c:__napi_kfree_skb
  - net/core/skbuff.c:kfree_skb_list_reason
  - net/core/skbuff.c:kfree_skb_list_reason
  - net/core/skbuff.c:kfree_skb_reason
```
**Symbols:**

```
ffffffff81ed3510-ffffffff81ed35b7: skb_release_head_state (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
void skb_release_head_state(struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffff800010bb5250)
Location: net/core/skbuff.c:647
Inline: False
Direct callers:
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_release_all
```
**Symbols:**

```
ffff800010bb5250-ffff800010bb531c: skb_release_head_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void skb_release_head_state(struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (c0cd2324)
Location: net/core/skbuff.c:647
Inline: False
Direct callers:
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_release_all
```
**Symbols:**

```
c0cd2324-c0cd2404: skb_release_head_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void skb_release_head_state(struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (c000000000c8c270)
Location: net/core/skbuff.c:647
Inline: False
Direct callers:
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_release_all
  - net/ipv4/udp.c:skb_consume_udp
```
**Symbols:**

```
c000000000c8c270-c000000000c8c380: skb_release_head_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void skb_release_head_state(struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffe00074531e)
Location: net/core/skbuff.c:647
Inline: False
Direct callers:
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_release_all
  - net/ipv4/udp.c:skb_consume_udp
```
**Symbols:**

```
ffffffe00074531e-ffffffe0007453c2: skb_release_head_state (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
void skb_release_head_state(struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff818baed0)
Location: net/core/skbuff.c:647
Inline: False
Direct callers:
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_release_all
```
**Symbols:**

```
ffffffff818baed0-ffffffff818baf55: skb_release_head_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void skb_release_head_state(struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff81874e10)
Location: net/core/skbuff.c:647
Inline: False
Direct callers:
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_release_all
```
**Symbols:**

```
ffffffff81874e10-ffffffff81874e95: skb_release_head_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void skb_release_head_state(struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff8190bed0)
Location: net/core/skbuff.c:647
Inline: False
Direct callers:
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_release_all
```
**Symbols:**

```
ffffffff8190bed0-ffffffff8190bf55: skb_release_head_state (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void skb_release_head_state(struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff8192cff0)
Location: net/core/skbuff.c:647
Inline: False
Direct callers:
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_release_all
```
**Symbols:**

```
ffffffff8192cff0-ffffffff8192d075: skb_release_head_state (STB_GLOBAL)
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
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
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
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
