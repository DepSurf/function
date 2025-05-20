# Function: <code>skb_segment_list</code>

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
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
struct sk_buff *skb_segment_list(struct sk_buff *skb, netdev_features_t features, unsigned int offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/skbuff.c (0)
Location: net/core/skbuff.c:3640
Inline: False
Direct callers:
  - net/ipv4/udp_offload.c:__udp_gso_segment
```
**Symbols:**

```
ffffffff819f4a9d-ffffffff819f4ac6: skb_segment_list.cold (STB_LOCAL)
ffffffff819f16d0-ffffffff819f19c4: skb_segment_list (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
struct sk_buff *skb_segment_list(struct sk_buff *skb, netdev_features_t features, unsigned int offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/skbuff.c (0)
Location: net/core/skbuff.c:3690
Inline: False
Direct callers:
  - net/ipv4/udp_offload.c:__udp_gso_segment
```
**Symbols:**

```
ffffffff81c30a2e-ffffffff81c30a5a: skb_segment_list.cold (STB_LOCAL)
ffffffff819f1ba0-ffffffff819f1f20: skb_segment_list (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
struct sk_buff *skb_segment_list(struct sk_buff *skb, netdev_features_t features, unsigned int offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/skbuff.c (0)
Location: net/core/skbuff.c:3775
Inline: False
Direct callers:
  - net/ipv4/udp_offload.c:__udp_gso_segment
```
**Symbols:**

```
ffffffff81c22d03-ffffffff81c22d2f: skb_segment_list.cold (STB_LOCAL)
ffffffff819d7a40-ffffffff819d7dc6: skb_segment_list (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
struct sk_buff *skb_segment_list(struct sk_buff *skb, netdev_features_t features, unsigned int offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/skbuff.c (0)
Location: net/core/skbuff.c:3835
Inline: False
Direct callers:
  - net/ipv4/udp_offload.c:__udp_gso_segment
```
**Symbols:**

```
ffffffff81d3538a-ffffffff81d353b6: skb_segment_list.cold (STB_LOCAL)
ffffffff81a87890-ffffffff81a87c16: skb_segment_list (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
struct sk_buff *skb_segment_list(struct sk_buff *skb, netdev_features_t features, unsigned int offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/skbuff.c (0)
Location: net/core/skbuff.c:3885
Inline: False
Direct callers:
  - net/ipv4/udp_offload.c:__udp_gso_segment
```
**Symbols:**

```
ffffffff81f018af-ffffffff81f018d8: skb_segment_list.cold (STB_LOCAL)
ffffffff81bfcc30-ffffffff81bfd054: skb_segment_list (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct sk_buff *skb_segment_list(struct sk_buff *skb, netdev_features_t features, unsigned int offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff81dac660)
Location: net/core/skbuff.c:4087
Inline: False
Direct callers:
  - net/ipv4/udp_offload.c:__udp_gso_segment
```
**Symbols:**

```
ffffffff81dac660-ffffffff81dacac4: skb_segment_list (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct sk_buff *skb_segment_list(struct sk_buff *skb, netdev_features_t features, unsigned int offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff81e1c450)
Location: net/core/skbuff.c:4256
Inline: False
Direct callers:
  - net/ipv4/udp_offload.c:__udp_gso_segment
```
**Symbols:**

```
ffffffff81e1c450-ffffffff81e1c8fc: skb_segment_list (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct sk_buff *skb_segment_list(struct sk_buff *skb, netdev_features_t features, unsigned int offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff81ed9b50)
Location: net/core/skbuff.c:4378
Inline: False
Direct callers:
  - net/ipv4/udp_offload.c:__udp_gso_segment
```
**Symbols:**

```
ffffffff81ed9b50-ffffffff81ed9ffc: skb_segment_list (STB_GLOBAL)
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
