# Function: <code>bpf_push_seg6_encap</code>

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
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int bpf_push_seg6_encap(struct sk_buff *skb, u32 type, void *hdr, u32 len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff818b2170)
Location: net/core/filter.c:4482
Inline: False
Direct callers:
  - net/core/filter.c:bpf_lwt_seg6_action
  - net/core/filter.c:bpf_lwt_seg6_action
  - net/core/filter.c:bpf_lwt_push_encap
```
**Symbols:**

```
ffffffff818b2170-ffffffff818b2289: bpf_push_seg6_encap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int bpf_push_seg6_encap(struct sk_buff *skb, u32 type, void *hdr, u32 len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff818d6ce0)
Location: net/core/filter.c:4767
Inline: False
Direct callers:
  - net/core/filter.c:bpf_lwt_seg6_action
  - net/core/filter.c:bpf_lwt_push_encap
```
**Symbols:**

```
ffffffff818d6ce0-ffffffff818d6df3: bpf_push_seg6_encap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int bpf_push_seg6_encap(struct sk_buff *skb, u32 type, void *hdr, u32 len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81924550)
Location: net/core/filter.c:4912
Inline: False
Direct callers:
  - net/core/filter.c:bpf_lwt_seg6_action
  - net/core/filter.c:bpf_lwt_in_push_encap
```
**Symbols:**

```
ffffffff81924550-ffffffff8192467c: bpf_push_seg6_encap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int bpf_push_seg6_encap(struct sk_buff *skb, u32 type, void *hdr, u32 len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81956860)
Location: net/core/filter.c:4921
Inline: False
Direct callers:
  - net/core/filter.c:bpf_lwt_seg6_action
  - net/core/filter.c:bpf_lwt_in_push_encap
```
**Symbols:**

```
ffffffff81956860-ffffffff8195698c: bpf_push_seg6_encap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int bpf_push_seg6_encap(struct sk_buff *skb, u32 type, void *hdr, u32 len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81a2f4d0)
Location: net/core/filter.c:5048
Inline: False
Direct callers:
  - net/core/filter.c:bpf_lwt_seg6_action
  - net/core/filter.c:bpf_lwt_in_push_encap
```
**Symbols:**

```
ffffffff81a2f4d0-ffffffff81a2f5fe: bpf_push_seg6_encap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int bpf_push_seg6_encap(struct sk_buff *skb, u32 type, void *hdr, u32 len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81a317e0)
Location: net/core/filter.c:5600
Inline: False
Direct callers:
  - net/core/filter.c:bpf_lwt_seg6_action
  - net/core/filter.c:bpf_lwt_in_push_encap
```
**Symbols:**

```
ffffffff81a317e0-ffffffff81a3190e: bpf_push_seg6_encap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int bpf_push_seg6_encap(struct sk_buff *skb, u32 type, void *hdr, u32 len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81a18640)
Location: net/core/filter.c:5702
Inline: False
Direct callers:
  - net/core/filter.c:bpf_lwt_seg6_action
  - net/core/filter.c:bpf_lwt_in_push_encap
```
**Symbols:**

```
ffffffff81a18640-ffffffff81a1876e: bpf_push_seg6_encap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int bpf_push_seg6_encap(struct sk_buff *skb, u32 type, void *hdr, u32 len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81ac9b30)
Location: net/core/filter.c:5826
Inline: False
Direct callers:
  - net/core/filter.c:bpf_lwt_seg6_action
  - net/core/filter.c:bpf_lwt_in_push_encap
```
**Symbols:**

```
ffffffff81ac9b30-ffffffff81ac9c5e: bpf_push_seg6_encap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int bpf_push_seg6_encap(struct sk_buff *skb, u32 type, void *hdr, u32 len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81c46690)
Location: net/core/filter.c:6135
Inline: False
Direct callers:
  - net/core/filter.c:bpf_lwt_seg6_action
  - net/core/filter.c:bpf_lwt_in_push_encap
```
**Symbols:**

```
ffffffff81c46690-ffffffff81c4678d: bpf_push_seg6_encap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int bpf_push_seg6_encap(struct sk_buff *skb, u32 type, void *hdr, u32 len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81dfab90)
Location: net/core/filter.c:6149
Inline: False
Direct callers:
  - net/core/filter.c:bpf_lwt_seg6_action
  - net/core/filter.c:bpf_lwt_in_push_encap
```
**Symbols:**

```
ffffffff81dfab90-ffffffff81dfac8d: bpf_push_seg6_encap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int bpf_push_seg6_encap(struct sk_buff *skb, u32 type, void *hdr, u32 len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81e6bd90)
Location: net/core/filter.c:6228
Inline: False
Direct callers:
  - net/core/filter.c:bpf_lwt_seg6_action
  - net/core/filter.c:bpf_lwt_in_push_encap
```
**Symbols:**

```
ffffffff81e6bd90-ffffffff81e6be8d: bpf_push_seg6_encap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int bpf_push_seg6_encap(struct sk_buff *skb, u32 type, void *hdr, u32 len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81f2b680)
Location: net/core/filter.c:6318
Inline: False
Direct callers:
  - net/core/filter.c:bpf_lwt_seg6_action
  - net/core/filter.c:bpf_lwt_in_push_encap
```
**Symbols:**

```
ffffffff81f2b680-ffffffff81f2b77d: bpf_push_seg6_encap (STB_LOCAL)
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
int bpf_push_seg6_encap(struct sk_buff *skb, u32 type, void *hdr, u32 len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffff800010bf8150)
Location: net/core/filter.c:4921
Inline: False
Direct callers:
  - net/core/filter.c:bpf_lwt_seg6_action
  - net/core/filter.c:bpf_lwt_seg6_action
  - net/core/filter.c:bpf_lwt_in_push_encap
```
**Symbols:**

```
ffff800010bf8150-ffff800010bf826c: bpf_push_seg6_encap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int bpf_push_seg6_encap(struct sk_buff *skb, u32 type, void *hdr, u32 len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (c0d11bec)
Location: net/core/filter.c:4921
Inline: False
Direct callers:
  - net/core/filter.c:bpf_lwt_seg6_action
  - net/core/filter.c:bpf_lwt_seg6_action
  - net/core/filter.c:bpf_lwt_in_push_encap
```
**Symbols:**

```
c0d11bec-c0d11d0c: bpf_push_seg6_encap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int bpf_push_seg6_encap(struct sk_buff *skb, u32 type, void *hdr, u32 len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (c000000000cdeb80)
Location: net/core/filter.c:4921
Inline: False
Direct callers:
  - net/core/filter.c:bpf_lwt_seg6_action
  - net/core/filter.c:bpf_lwt_seg6_action
  - net/core/filter.c:bpf_lwt_in_push_encap
```
**Symbols:**

```
c000000000cdeb80-c000000000cdecf8: bpf_push_seg6_encap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int bpf_push_seg6_encap(struct sk_buff *skb, u32 type, void *hdr, u32 len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffe000779e34)
Location: net/core/filter.c:4921
Inline: False
Direct callers:
  - net/core/filter.c:bpf_lwt_seg6_action
  - net/core/filter.c:bpf_lwt_seg6_action
  - net/core/filter.c:bpf_lwt_in_push_encap
```
**Symbols:**

```
ffffffe000779e34-ffffffe000779f30: bpf_push_seg6_encap (STB_LOCAL)
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
int bpf_push_seg6_encap(struct sk_buff *skb, u32 type, void *hdr, u32 len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff818f6830)
Location: net/core/filter.c:4921
Inline: False
Direct callers:
  - net/core/filter.c:bpf_lwt_seg6_action
  - net/core/filter.c:bpf_lwt_in_push_encap
```
**Symbols:**

```
ffffffff818f6830-ffffffff818f695c: bpf_push_seg6_encap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int bpf_push_seg6_encap(struct sk_buff *skb, u32 type, void *hdr, u32 len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff818b0660)
Location: net/core/filter.c:4921
Inline: False
Direct callers:
  - net/core/filter.c:bpf_lwt_seg6_action
  - net/core/filter.c:bpf_lwt_in_push_encap
```
**Symbols:**

```
ffffffff818b0660-ffffffff818b078c: bpf_push_seg6_encap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int bpf_push_seg6_encap(struct sk_buff *skb, u32 type, void *hdr, u32 len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81947860)
Location: net/core/filter.c:4921
Inline: False
Direct callers:
  - net/core/filter.c:bpf_lwt_seg6_action
  - net/core/filter.c:bpf_lwt_in_push_encap
```
**Symbols:**

```
ffffffff81947860-ffffffff8194798c: bpf_push_seg6_encap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int bpf_push_seg6_encap(struct sk_buff *skb, u32 type, void *hdr, u32 len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81969170)
Location: net/core/filter.c:4921
Inline: False
Direct callers:
  - net/core/filter.c:bpf_lwt_seg6_action
  - net/core/filter.c:bpf_lwt_in_push_encap
```
**Symbols:**

```
ffffffff81969170-ffffffff8196929c: bpf_push_seg6_encap (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
