# Function: <code>bpf_lwt_push_ip_encap</code>

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
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int bpf_lwt_push_ip_encap(struct sk_buff *skb, void *hdr, u32 len, bool ingress);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/lwt_bpf.c (ffffffff81943580)
Location: net/core/lwt_bpf.c:589
Inline: False
Direct callers:
  - net/core/filter.c:bpf_lwt_xmit_push_encap
  - net/core/filter.c:bpf_lwt_in_push_encap
```
**Symbols:**

```
ffffffff81943580-ffffffff81943ad7: bpf_lwt_push_ip_encap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int bpf_lwt_push_ip_encap(struct sk_buff *skb, void *hdr, u32 len, bool ingress);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/lwt_bpf.c (ffffffff81978550)
Location: net/core/lwt_bpf.c:592
Inline: False
Direct callers:
  - net/core/filter.c:bpf_lwt_xmit_push_encap
  - net/core/filter.c:bpf_lwt_in_push_encap
```
**Symbols:**

```
ffffffff81978550-ffffffff81978ac8: bpf_lwt_push_ip_encap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int bpf_lwt_push_ip_encap(struct sk_buff *skb, void *hdr, u32 len, bool ingress);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/lwt_bpf.c (ffffffff81a4d470)
Location: net/core/lwt_bpf.c:592
Inline: False
Direct callers:
  - net/core/filter.c:bpf_lwt_xmit_push_encap
  - net/core/filter.c:bpf_lwt_in_push_encap
```
**Symbols:**

```
ffffffff81a4d470-ffffffff81a4d856: bpf_lwt_push_ip_encap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int bpf_lwt_push_ip_encap(struct sk_buff *skb, void *hdr, u32 len, bool ingress);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/lwt_bpf.c (ffffffff81a53130)
Location: net/core/lwt_bpf.c:592
Inline: False
Direct callers:
  - net/core/filter.c:bpf_lwt_xmit_push_encap
  - net/core/filter.c:bpf_lwt_in_push_encap
```
**Symbols:**

```
ffffffff81a53130-ffffffff81a53511: bpf_lwt_push_ip_encap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int bpf_lwt_push_ip_encap(struct sk_buff *skb, void *hdr, u32 len, bool ingress);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/lwt_bpf.c (ffffffff81a38960)
Location: net/core/lwt_bpf.c:592
Inline: False
Direct callers:
  - net/core/filter.c:bpf_lwt_xmit_push_encap
  - net/core/filter.c:bpf_lwt_in_push_encap
```
**Symbols:**

```
ffffffff81a38960-ffffffff81a38e33: bpf_lwt_push_ip_encap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int bpf_lwt_push_ip_encap(struct sk_buff *skb, void *hdr, u32 len, bool ingress);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/lwt_bpf.c (ffffffff81aee840)
Location: net/core/lwt_bpf.c:592
Inline: False
Direct callers:
  - net/core/filter.c:bpf_lwt_xmit_push_encap
  - net/core/filter.c:bpf_lwt_in_push_encap
```
**Symbols:**

```
ffffffff81aee840-ffffffff81aeed51: bpf_lwt_push_ip_encap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int bpf_lwt_push_ip_encap(struct sk_buff *skb, void *hdr, u32 len, bool ingress);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/lwt_bpf.c (ffffffff81c717a0)
Location: net/core/lwt_bpf.c:592
Inline: False
Direct callers:
  - net/core/filter.c:bpf_lwt_xmit_push_encap
  - net/core/filter.c:bpf_lwt_in_push_encap
```
**Symbols:**

```
ffffffff81c717a0-ffffffff81c71ce4: bpf_lwt_push_ip_encap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int bpf_lwt_push_ip_encap(struct sk_buff *skb, void *hdr, u32 len, bool ingress);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/lwt_bpf.c (ffffffff81e29890)
Location: net/core/lwt_bpf.c:592
Inline: False
Direct callers:
  - net/core/filter.c:bpf_lwt_xmit_push_encap
  - net/core/filter.c:bpf_lwt_in_push_encap
```
**Symbols:**

```
ffffffff81e29890-ffffffff81e29dd4: bpf_lwt_push_ip_encap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int bpf_lwt_push_ip_encap(struct sk_buff *skb, void *hdr, u32 len, bool ingress);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/lwt_bpf.c (ffffffff81e9eed0)
Location: net/core/lwt_bpf.c:591
Inline: False
Direct callers:
  - net/core/filter.c:bpf_lwt_xmit_push_encap
  - net/core/filter.c:bpf_lwt_in_push_encap
```
**Symbols:**

```
ffffffff81e9eed0-ffffffff81e9f417: bpf_lwt_push_ip_encap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int bpf_lwt_push_ip_encap(struct sk_buff *skb, void *hdr, u32 len, bool ingress);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/lwt_bpf.c (ffffffff81f61640)
Location: net/core/lwt_bpf.c:591
Inline: False
Direct callers:
  - net/core/filter.c:bpf_lwt_xmit_push_encap
  - net/core/filter.c:bpf_lwt_in_push_encap
```
**Symbols:**

```
ffffffff81f61640-ffffffff81f61b84: bpf_lwt_push_ip_encap (STB_GLOBAL)
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
int bpf_lwt_push_ip_encap(struct sk_buff *skb, void *hdr, u32 len, bool ingress);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/lwt_bpf.c (ffff800010c1f210)
Location: net/core/lwt_bpf.c:592
Inline: False
Direct callers:
  - net/core/filter.c:bpf_lwt_xmit_push_encap
  - net/core/filter.c:bpf_lwt_in_push_encap
```
**Symbols:**

```
ffff800010c1f210-ffff800010c1f6c8: bpf_lwt_push_ip_encap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int bpf_lwt_push_ip_encap(struct sk_buff *skb, void *hdr, u32 len, bool ingress);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/lwt_bpf.c (c0d36db4)
Location: net/core/lwt_bpf.c:592
Inline: False
Direct callers:
  - net/core/filter.c:bpf_lwt_xmit_push_encap
  - net/core/filter.c:bpf_lwt_in_push_encap
```
**Symbols:**

```
c0d36db4-c0d372f0: bpf_lwt_push_ip_encap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int bpf_lwt_push_ip_encap(struct sk_buff *skb, void *hdr, u32 len, bool ingress);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/lwt_bpf.c (c000000000d11080)
Location: net/core/lwt_bpf.c:592
Inline: False
Direct callers:
  - net/core/filter.c:bpf_lwt_xmit_push_encap
  - net/core/filter.c:bpf_lwt_in_push_encap
```
**Symbols:**

```
c000000000d11080-c000000000d11654: bpf_lwt_push_ip_encap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int bpf_lwt_push_ip_encap(struct sk_buff *skb, void *hdr, u32 len, bool ingress);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/lwt_bpf.c (ffffffe000798994)
Location: net/core/lwt_bpf.c:592
Inline: False
Direct callers:
  - net/core/filter.c:bpf_lwt_xmit_push_encap
  - net/core/filter.c:bpf_lwt_in_push_encap
```
**Symbols:**

```
ffffffe000798994-ffffffe000798d62: bpf_lwt_push_ip_encap (STB_GLOBAL)
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
int bpf_lwt_push_ip_encap(struct sk_buff *skb, void *hdr, u32 len, bool ingress);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/lwt_bpf.c (ffffffff819183c0)
Location: net/core/lwt_bpf.c:592
Inline: False
Direct callers:
  - net/core/filter.c:bpf_lwt_xmit_push_encap
  - net/core/filter.c:bpf_lwt_in_push_encap
```
**Symbols:**

```
ffffffff819183c0-ffffffff81918938: bpf_lwt_push_ip_encap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int bpf_lwt_push_ip_encap(struct sk_buff *skb, void *hdr, u32 len, bool ingress);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/lwt_bpf.c (ffffffff818d2170)
Location: net/core/lwt_bpf.c:592
Inline: False
Direct callers:
  - net/core/filter.c:bpf_lwt_xmit_push_encap
  - net/core/filter.c:bpf_lwt_in_push_encap
```
**Symbols:**

```
ffffffff818d2170-ffffffff818d26e8: bpf_lwt_push_ip_encap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int bpf_lwt_push_ip_encap(struct sk_buff *skb, void *hdr, u32 len, bool ingress);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/lwt_bpf.c (ffffffff81969550)
Location: net/core/lwt_bpf.c:592
Inline: False
Direct callers:
  - net/core/filter.c:bpf_lwt_xmit_push_encap
  - net/core/filter.c:bpf_lwt_in_push_encap
```
**Symbols:**

```
ffffffff81969550-ffffffff81969ac8: bpf_lwt_push_ip_encap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int bpf_lwt_push_ip_encap(struct sk_buff *skb, void *hdr, u32 len, bool ingress);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/lwt_bpf.c (ffffffff8198b930)
Location: net/core/lwt_bpf.c:592
Inline: False
Direct callers:
  - net/core/filter.c:bpf_lwt_xmit_push_encap
  - net/core/filter.c:bpf_lwt_in_push_encap
```
**Symbols:**

```
ffffffff8198b930-ffffffff8198bea8: bpf_lwt_push_ip_encap (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
