# Function: <code>udp6_gro_receive</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct sk_buff **udp6_gro_receive(struct sk_buff **head, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/udp_offload.c (ffffffff81801920)
Location: net/ipv6/udp_offload.c:129
Inline: False
```
**Symbols:**

```
ffffffff81801920-ffffffff81801beb: udp6_gro_receive (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct sk_buff **udp6_gro_receive(struct sk_buff **head, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/udp_offload.c (ffffffff81866c80)
Location: net/ipv6/udp_offload.c:122
Inline: False
```
**Symbols:**

```
ffffffff81866c80-ffffffff81866f4d: udp6_gro_receive (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct sk_buff **udp6_gro_receive(struct sk_buff **head, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/udp_offload.c (ffffffff81899380)
Location: net/ipv6/udp_offload.c:122
Inline: False
```
**Symbols:**

```
ffffffff81899380-ffffffff8189964d: udp6_gro_receive (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct sk_buff **udp6_gro_receive(struct sk_buff **head, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/udp_offload.c (ffffffff818bf5b0)
Location: net/ipv6/udp_offload.c:126
Inline: False
```
**Symbols:**

```
ffffffff818bf5b0-ffffffff818bf841: udp6_gro_receive (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct sk_buff **udp6_gro_receive(struct sk_buff **head, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/udp_offload.c (ffffffff81942680)
Location: net/ipv6/udp_offload.c:114
Inline: False
```
**Symbols:**

```
ffffffff81942680-ffffffff81942911: udp6_gro_receive (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct sk_buff **udp6_gro_receive(struct sk_buff **head, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/udp_offload.c (ffffffff8199b4d0)
Location: net/ipv6/udp_offload.c:117
Inline: False
```
**Symbols:**

```
ffffffff8199b4d0-ffffffff8199b76c: udp6_gro_receive (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct sk_buff *udp6_gro_receive(struct list_head *head, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/udp_offload.c (ffffffff819d1e00)
Location: net/ipv6/udp_offload.c:119
Inline: False
Direct callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
```
**Symbols:**

```
ffffffff819d1e00-ffffffff819d20a4: udp6_gro_receive (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct sk_buff *udp6_gro_receive(struct list_head *head, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/udp_offload.c (ffffffff81a40be0)
Location: net/ipv6/udp_offload.c:115
Inline: False
Direct callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
```
**Symbols:**

```
ffffffff81a40be0-ffffffff81a40ec7: udp6_gro_receive (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct sk_buff *udp6_gro_receive(struct list_head *head, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/udp_offload.c (ffffffff81a77860)
Location: net/ipv6/udp_offload.c:115
Inline: False
Direct callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
```
**Symbols:**

```
ffffffff81a77860-ffffffff81a77b47: udp6_gro_receive (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct sk_buff *udp6_gro_receive(struct list_head *head, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/udp_offload.c (ffffffff81b71b80)
Location: net/ipv6/udp_offload.c:115
Inline: False
Direct callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
```
**Symbols:**

```
ffffffff81b71b80-ffffffff81b71e7d: udp6_gro_receive (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct sk_buff *udp6_gro_receive(struct list_head *head, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/udp_offload.c (ffffffff81b80830)
Location: net/ipv6/udp_offload.c:125
Inline: False
Direct callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
```
**Symbols:**

```
ffffffff81b80830-ffffffff81b80bd8: udp6_gro_receive (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct sk_buff *udp6_gro_receive(struct list_head *head, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/udp_offload.c (ffffffff81b6f450)
Location: net/ipv6/udp_offload.c:125
Inline: False
Direct callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
```
**Symbols:**

```
ffffffff81b6f450-ffffffff81b6f7f1: udp6_gro_receive (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct sk_buff *udp6_gro_receive(struct list_head *head, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/udp_offload.c (ffffffff81c37510)
Location: net/ipv6/udp_offload.c:125
Inline: False
Direct callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
```
**Symbols:**

```
ffffffff81c37510-ffffffff81c378ae: udp6_gro_receive (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct sk_buff *udp6_gro_receive(struct list_head *head, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/udp_offload.c (ffffffff81dd50a0)
Location: net/ipv6/udp_offload.c:126
Inline: False
Direct callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
```
**Symbols:**

```
ffffffff81dd50a0-ffffffff81dd5419: udp6_gro_receive (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct sk_buff *udp6_gro_receive(struct list_head *head, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/udp_offload.c (ffffffff81fa67a0)
Location: net/ipv6/udp_offload.c:128
Inline: False
Direct callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
```
**Symbols:**

```
ffffffff81fa67a0-ffffffff81fa6b25: udp6_gro_receive (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct sk_buff *udp6_gro_receive(struct list_head *head, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/udp_offload.c (ffffffff82007000)
Location: net/ipv6/udp_offload.c:131
Inline: False
Direct callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
```
**Symbols:**

```
ffffffff82007000-ffffffff82007399: udp6_gro_receive (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct sk_buff *udp6_gro_receive(struct list_head *head, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/udp_offload.c (ffffffff820d5e60)
Location: net/ipv6/udp_offload.c:131
Inline: False
Direct callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
```
**Symbols:**

```
ffffffff820d5e60-ffffffff820d61f9: udp6_gro_receive (STB_GLOBAL)
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
struct sk_buff *udp6_gro_receive(struct list_head *head, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/udp_offload.c (ffff800010d40ea8)
Location: net/ipv6/udp_offload.c:115
Inline: False
```
**Symbols:**

```
ffff800010d40ea8-ffff800010d41154: udp6_gro_receive (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct sk_buff *udp6_gro_receive(struct list_head *head, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/udp_offload.c (c0e43888)
Location: net/ipv6/udp_offload.c:115
Inline: False
```
**Symbols:**

```
c0e43888-c0e43b7c: udp6_gro_receive (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct sk_buff *udp6_gro_receive(struct list_head *head, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/udp_offload.c (c000000000e756f0)
Location: net/ipv6/udp_offload.c:115
Inline: False
```
**Symbols:**

```
c000000000e756f0-c000000000e75a68: udp6_gro_receive (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct sk_buff *udp6_gro_receive(struct list_head *head, struct sk_buff *skb);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/udp_offload.c (ffffffe00087c656)
Location: net/ipv6/udp_offload.c:115
Inline: False
```
**Symbols:**

```
ffffffe00087c656-ffffffe00087c8a4: udp6_gro_receive (STB_LOCAL)
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
struct sk_buff *udp6_gro_receive(struct list_head *head, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/udp_offload.c (ffffffff81a16ef0)
Location: net/ipv6/udp_offload.c:115
Inline: False
Direct callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
```
**Symbols:**

```
ffffffff81a16ef0-ffffffff81a171d7: udp6_gro_receive (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct sk_buff *udp6_gro_receive(struct list_head *head, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/udp_offload.c (ffffffff819d3cb0)
Location: net/ipv6/udp_offload.c:115
Inline: False
Direct callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
```
**Symbols:**

```
ffffffff819d3cb0-ffffffff819d3f97: udp6_gro_receive (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct sk_buff *udp6_gro_receive(struct list_head *head, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/udp_offload.c (ffffffff81a81970)
Location: net/ipv6/udp_offload.c:115
Inline: False
Direct callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
```
**Symbols:**

```
ffffffff81a81970-ffffffff81a81c57: udp6_gro_receive (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct sk_buff *udp6_gro_receive(struct list_head *head, struct sk_buff *skb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv6/udp_offload.c (ffffffff81a8e270)
Location: net/ipv6/udp_offload.c:115
Inline: False
Direct callers:
  - net/ipv6/ip6_offload.c:ipv6_gro_receive
```
**Symbols:**

```
ffffffff81a8e270-ffffffff81a8e557: udp6_gro_receive (STB_GLOBAL)
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
<details>
<summary>Changed between <code>4.18</code> and <code>5.0</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>struct sk_buff **head</code> ➡️ <code>struct list_head *head</code>
</li>
<li>
<b>Return type changed. </b>
<code>struct sk_buff **</code> ➡️ <code>struct sk_buff *</code>
</li>
</ul>
</details>
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
