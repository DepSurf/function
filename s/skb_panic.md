# Function: <code>skb_panic</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void skb_panic(struct sk_buff *skb, unsigned int sz, void *addr, const char *msg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff817054c0)
Location: net/core/skbuff.c:97
Inline: False
Direct callers:
  - net/core/skbuff.c:skb_vlan_push
```
**Symbols:**

```
ffffffff817054c0-ffffffff81705526: skb_panic (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void skb_panic(struct sk_buff *skb, unsigned int sz, void *addr, const char *msg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff8176c130)
Location: net/core/skbuff.c:98
Inline: False
Direct callers:
  - net/core/skbuff.c:skb_vlan_push
```
**Symbols:**

```
ffffffff8176c130-ffffffff8176c196: skb_panic (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void skb_panic(struct sk_buff *skb, unsigned int sz, void *addr, const char *msg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff81799310)
Location: net/core/skbuff.c:98
Inline: False
Direct callers:
  - net/core/skbuff.c:skb_vlan_push
```
**Symbols:**

```
ffffffff81799310-ffffffff81799376: skb_panic (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void skb_panic(struct sk_buff *skb, unsigned int sz, void *addr, const char *msg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff817b7a90)
Location: net/core/skbuff.c:98
Inline: False
Direct callers:
  - net/core/skbuff.c:skb_vlan_push
```
**Symbols:**

```
ffffffff817b7a90-ffffffff817b7ae1: skb_panic (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void skb_panic(struct sk_buff *skb, unsigned int sz, void *addr, const char *msg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff818301b0)
Location: net/core/skbuff.c:97
Inline: False
Direct callers:
  - net/core/skbuff.c:skb_vlan_push
```
**Symbols:**

```
ffffffff818301b0-ffffffff81830201: skb_panic (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void skb_panic(struct sk_buff *skb, unsigned int sz, void *addr, const char *msg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff818833c9)
Location: net/core/skbuff.c:97
Inline: False
Direct callers:
  - net/core/skbuff.c:skb_push
```
**Symbols:**

```
ffffffff818833c9-ffffffff8188341a: skb_panic (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void skb_panic(struct sk_buff *skb, unsigned int sz, void *addr, const char *msg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff818a3e13)
Location: net/core/skbuff.c:100
Inline: False
Direct callers:
  - net/core/skbuff.c:skb_push
```
**Symbols:**

```
ffffffff818a3e13-ffffffff818a3e61: skb_panic (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void skb_panic(struct sk_buff *skb, unsigned int sz, void *addr, const char *msg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff818eeb13)
Location: net/core/skbuff.c:101
Inline: False
Direct callers:
  - net/core/skbuff.c:skb_push
```
**Symbols:**

```
ffffffff818eeb13-ffffffff818eeb61: skb_panic (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void skb_panic(struct sk_buff *skb, unsigned int sz, void *addr, const char *msg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff81920c00)
Location: net/core/skbuff.c:101
Inline: False
Direct callers:
  - net/core/skbuff.c:skb_push
```
**Symbols:**

```
ffffffff81920c00-ffffffff81920c4e: skb_panic (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void skb_panic(struct sk_buff *skb, unsigned int sz, void *addr, const char *msg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff819f4991)
Location: net/core/skbuff.c:102
Inline: False
Direct callers:
  - net/core/skbuff.c:skb_mpls_push
  - net/core/skbuff.c:skb_vlan_push
  - net/core/skbuff.c:skb_checksum_trimmed
  - net/core/skbuff.c:skb_segment_list
  - net/core/skbuff.c:skb_segment_list
  - net/core/skbuff.c:pskb_put
```
**Symbols:**

```
ffffffff819f4991-ffffffff819f49df: skb_panic (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void skb_panic(struct sk_buff *skb, unsigned int sz, void *addr, const char *msg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff81c3090a)
Location: net/core/skbuff.c:102
Inline: False
Direct callers:
  - net/core/skbuff.c:skb_mpls_push
  - net/core/skbuff.c:skb_vlan_push
  - net/core/skbuff.c:skb_checksum_trimmed
  - net/core/skbuff.c:skb_segment_list
  - net/core/skbuff.c:skb_segment_list
  - net/core/skbuff.c:pskb_put
```
**Symbols:**

```
ffffffff81c3090a-ffffffff81c30958: skb_panic (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void skb_panic(struct sk_buff *skb, unsigned int sz, void *addr, const char *msg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff81c22be6)
Location: net/core/skbuff.c:103
Inline: False
Direct callers:
  - net/core/skbuff.c:skb_mpls_push
  - net/core/skbuff.c:skb_vlan_push
  - net/core/skbuff.c:skb_checksum_trimmed
  - net/core/skbuff.c:skb_segment_list
  - net/core/skbuff.c:skb_segment_list
  - net/core/skbuff.c:pskb_put
```
**Symbols:**

```
ffffffff81c22be6-ffffffff81c22c37: skb_panic (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void skb_panic(struct sk_buff *skb, unsigned int sz, void *addr, const char *msg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff81d3506e)
Location: net/core/skbuff.c:105
Inline: False
Direct callers:
  - net/core/skbuff.c:skb_mpls_push
  - net/core/skbuff.c:skb_vlan_push
  - net/core/skbuff.c:skb_try_coalesce
  - net/core/skbuff.c:skb_checksum_trimmed
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment_list
  - net/core/skbuff.c:skb_segment_list
  - net/core/skbuff.c:skb_split
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:pskb_put
  - net/core/skbuff.c:skb_copy_expand
  - net/core/skbuff.c:__pskb_copy_fclone
  - net/core/skbuff.c:skb_copy
```
**Symbols:**

```
ffffffff81d3506e-ffffffff81d350bf: skb_panic (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void skb_panic(struct sk_buff *skb, unsigned int sz, void *addr, const char *msg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff81f01137)
Location: net/core/skbuff.c:106
Inline: False
Direct callers:
  - net/core/skbuff.c:skb_mpls_push
  - net/core/skbuff.c:skb_vlan_push
  - net/core/skbuff.c:skb_try_coalesce
  - net/core/skbuff.c:skb_checksum_trimmed
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment_list
  - net/core/skbuff.c:skb_segment_list
  - net/core/skbuff.c:skb_split
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:pskb_put
  - net/core/skbuff.c:skb_copy_expand
  - net/core/skbuff.c:__pskb_copy_fclone
  - net/core/skbuff.c:skb_copy
```
**Symbols:**

```
ffffffff81f01137-ffffffff81f01188: skb_panic (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void skb_panic(struct sk_buff *skb, unsigned int sz, void *addr, const char *msg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff81da1cf0)
Location: net/core/skbuff.c:114
Inline: False
Direct callers:
  - net/core/skbuff.c:skb_mpls_push
  - net/core/skbuff.c:skb_try_coalesce
  - net/core/skbuff.c:skb_checksum_trimmed
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment_list
  - net/core/skbuff.c:skb_segment_list
  - net/core/skbuff.c:skb_split
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:pskb_put
  - net/core/skbuff.c:skb_copy_expand
  - net/core/skbuff.c:__pskb_copy_fclone
  - net/core/skbuff.c:skb_copy
```
**Symbols:**

```
ffffffff81da1cf0-ffffffff81da1d41: skb_panic (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void skb_panic(struct sk_buff *skb, unsigned int sz, void *addr, const char *msg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff81e10540)
Location: net/core/skbuff.c:185
Inline: False
Direct callers:
  - net/core/skbuff.c:skb_mpls_push
  - net/core/skbuff.c:skb_try_coalesce
  - net/core/skbuff.c:skb_checksum_trimmed
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment_list
  - net/core/skbuff.c:skb_segment_list
  - net/core/skbuff.c:skb_split
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:pskb_put
  - net/core/skbuff.c:skb_copy_expand
  - net/core/skbuff.c:__pskb_copy_fclone
  - net/core/skbuff.c:skb_copy
```
**Symbols:**

```
ffffffff81e10540-ffffffff81e10591: skb_panic (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void skb_panic(struct sk_buff *skb, unsigned int sz, void *addr, const char *msg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff81ecd060)
Location: net/core/skbuff.c:186
Inline: False
Direct callers:
  - net/core/skbuff.c:skb_mpls_push
  - net/core/skbuff.c:skb_try_coalesce
  - net/core/skbuff.c:skb_checksum_trimmed
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment
  - net/core/skbuff.c:skb_segment_list
  - net/core/skbuff.c:skb_segment_list
  - net/core/skbuff.c:skb_split
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:skb_zerocopy
  - net/core/skbuff.c:pskb_put
  - net/core/skbuff.c:skb_copy_expand
  - net/core/skbuff.c:__pskb_copy_fclone
  - net/core/skbuff.c:skb_copy
```
**Symbols:**

```
ffffffff81ecd060-ffffffff81ecd0ba: skb_panic (STB_LOCAL)
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
void skb_panic(struct sk_buff *skb, unsigned int sz, void *addr, const char *msg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffff800010bbb9e8)
Location: net/core/skbuff.c:101
Inline: False
Direct callers:
  - net/core/skbuff.c:skb_push
```
**Symbols:**

```
ffff800010bbb9e8-ffff800010bbba5c: skb_panic (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void skb_panic(struct sk_buff *skb, unsigned int sz, void *addr, const char *msg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (c0cd7d04)
Location: net/core/skbuff.c:101
Inline: False
Direct callers:
  - net/core/skbuff.c:skb_push
```
**Symbols:**

```
c0cd7d04-c0cd7d78: skb_panic (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void skb_panic(struct sk_buff *skb, unsigned int sz, void *addr, const char *msg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (c000000000c943f8)
Location: net/core/skbuff.c:101
Inline: False
Direct callers:
  - net/core/skbuff.c:skb_push
  - net/core/skbuff.c:skb_put
```
**Symbols:**

```
c000000000c943f8-c000000000c94464: skb_panic (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void skb_panic(struct sk_buff *skb, unsigned int sz, void *addr, const char *msg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffe00074a5ac)
Location: net/core/skbuff.c:101
Inline: False
Direct callers:
  - net/core/skbuff.c:skb_push
```
**Symbols:**

```
ffffffe00074a5ac-ffffffe00074a608: skb_panic (STB_LOCAL)
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
void skb_panic(struct sk_buff *skb, unsigned int sz, void *addr, const char *msg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff818c0c00)
Location: net/core/skbuff.c:101
Inline: False
Direct callers:
  - net/core/skbuff.c:skb_push
```
**Symbols:**

```
ffffffff818c0c00-ffffffff818c0c4e: skb_panic (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void skb_panic(struct sk_buff *skb, unsigned int sz, void *addr, const char *msg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff8187ab40)
Location: net/core/skbuff.c:101
Inline: False
Direct callers:
  - net/core/skbuff.c:skb_push
```
**Symbols:**

```
ffffffff8187ab40-ffffffff8187ab8e: skb_panic (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void skb_panic(struct sk_buff *skb, unsigned int sz, void *addr, const char *msg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff81911c00)
Location: net/core/skbuff.c:101
Inline: False
Direct callers:
  - net/core/skbuff.c:skb_push
```
**Symbols:**

```
ffffffff81911c00-ffffffff81911c4e: skb_panic (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void skb_panic(struct sk_buff *skb, unsigned int sz, void *addr, const char *msg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff81932d60)
Location: net/core/skbuff.c:101
Inline: False
Direct callers:
  - net/core/skbuff.c:skb_push
```
**Symbols:**

```
ffffffff81932d60-ffffffff81932dae: skb_panic (STB_LOCAL)
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
