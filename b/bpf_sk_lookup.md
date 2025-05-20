# Function: <code>bpf_sk_lookup</code>

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
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff818d90a5)
Location: net/core/filter.c:5106
Inline: True
Inline callers:
  - net/core/filter.c:bpf_sk_lookup_udp
  - net/core/filter.c:bpf_sk_lookup_tcp
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct sock *bpf_sk_lookup(struct sk_buff *skb, struct bpf_sock_tuple *tuple, u32 len, u8 proto, u64 netns_id, u64 flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81926ee0)
Location: net/core/filter.c:5329
Inline: False
Direct callers:
  - net/core/filter.c:bpf_sk_lookup_udp
  - net/core/filter.c:bpf_sk_lookup_tcp
```
**Symbols:**

```
ffffffff81926ee0-ffffffff81926f69: bpf_sk_lookup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct sock *bpf_sk_lookup(struct sk_buff *skb, struct bpf_sock_tuple *tuple, u32 len, u8 proto, u64 netns_id, u64 flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff819595a0)
Location: net/core/filter.c:5337
Inline: False
Direct callers:
  - net/core/filter.c:bpf_sk_lookup_udp
  - net/core/filter.c:bpf_sk_lookup_tcp
```
**Symbols:**

```
ffffffff819595a0-ffffffff81959619: bpf_sk_lookup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81a2e455)
Location: net/core/filter.c:5464
Inline: True
Inline callers:
  - net/core/filter.c:bpf_sk_lookup_udp
  - net/core/filter.c:bpf_sk_lookup_tcp
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81a2f9c9)
Location: net/core/filter.c:6016
Inline: True
Inline callers:
  - net/core/filter.c:bpf_sk_lookup_udp
  - net/core/filter.c:bpf_sk_lookup_tcp
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81a16aa9)
Location: net/core/filter.c:6118
Inline: True
Inline callers:
  - net/core/filter.c:bpf_sk_lookup_udp
  - net/core/filter.c:bpf_sk_lookup_tcp
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81acbe29)
Location: net/core/filter.c:6242
Inline: True
Inline callers:
  - net/core/filter.c:bpf_sk_lookup_udp
  - net/core/filter.c:bpf_sk_lookup_tcp
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
struct sock *bpf_sk_lookup(struct sk_buff *skb, struct bpf_sock_tuple *tuple, u32 len, u8 proto, u64 netns_id, u64 flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/filter.c (0)
Location: net/core/filter.c:6561
Inline: False
Direct callers:
  - net/core/filter.c:bpf_sk_lookup_udp
  - net/core/filter.c:bpf_sk_lookup_tcp
```
**Symbols:**

```
ffffffff81c49450-ffffffff81c49571: bpf_sk_lookup (STB_LOCAL)
ffffffff81f03f70-ffffffff81f03fab: bpf_sk_lookup.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
struct sock *bpf_sk_lookup(struct sk_buff *skb, struct bpf_sock_tuple *tuple, u32 len, u8 proto, u64 netns_id, u64 flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/filter.c (0)
Location: net/core/filter.c:6573
Inline: False
Direct callers:
  - net/core/filter.c:bpf_sk_lookup_udp
  - net/core/filter.c:bpf_sk_lookup_tcp
```
**Symbols:**

```
ffffffff81dfe420-ffffffff81dfe541: bpf_sk_lookup (STB_LOCAL)
ffffffff820ac741-ffffffff820ac77c: bpf_sk_lookup.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
struct sock *bpf_sk_lookup(struct sk_buff *skb, struct bpf_sock_tuple *tuple, u32 len, u8 proto, u64 netns_id, u64 flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/filter.c (0)
Location: net/core/filter.c:6654
Inline: False
Direct callers:
  - net/core/filter.c:bpf_sk_lookup_udp
  - net/core/filter.c:bpf_sk_lookup_tcp
```
**Symbols:**

```
ffffffff81e6f3e0-ffffffff81e6f4eb: bpf_sk_lookup (STB_LOCAL)
ffffffff8212dd0d-ffffffff8212dd42: bpf_sk_lookup.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
struct sock *bpf_sk_lookup(struct sk_buff *skb, struct bpf_sock_tuple *tuple, u32 len, u8 proto, u64 netns_id, u64 flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/filter.c (0)
Location: net/core/filter.c:6744
Inline: False
Direct callers:
  - net/core/filter.c:bpf_sk_lookup_udp
  - net/core/filter.c:bpf_sk_lookup_tcp
```
**Symbols:**

```
ffffffff81f2ea20-ffffffff81f2eb2b: bpf_sk_lookup (STB_LOCAL)
ffffffff8220fa73-ffffffff8220faa8: bpf_sk_lookup.cold (STB_LOCAL)
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
struct sock *bpf_sk_lookup(struct sk_buff *skb, struct bpf_sock_tuple *tuple, u32 len, u8 proto, u64 netns_id, u64 flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffff800010bfab30)
Location: net/core/filter.c:5337
Inline: False
Direct callers:
  - net/core/filter.c:bpf_sk_lookup_udp
  - net/core/filter.c:bpf_sk_lookup_tcp
```
**Symbols:**

```
ffff800010bfab30-ffff800010bfabf4: bpf_sk_lookup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct sock *bpf_sk_lookup(struct sk_buff *skb, struct bpf_sock_tuple *tuple, u32 len, u8 proto, u64 netns_id, u64 flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (c0d145f0)
Location: net/core/filter.c:5337
Inline: False
Direct callers:
  - net/core/filter.c:bpf_sk_lookup_udp
  - net/core/filter.c:bpf_sk_lookup_tcp
```
**Symbols:**

```
c0d145f0-c0d14678: bpf_sk_lookup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct sock *bpf_sk_lookup(struct sk_buff *skb, struct bpf_sock_tuple *tuple, u32 len, u8 proto, u64 netns_id, u64 flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (c000000000ce2f50)
Location: net/core/filter.c:5337
Inline: False
Direct callers:
  - net/core/filter.c:bpf_sk_lookup_udp
  - net/core/filter.c:bpf_sk_lookup_tcp
```
**Symbols:**

```
c000000000ce2f50-c000000000ce3010: bpf_sk_lookup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct sock *bpf_sk_lookup(struct sk_buff *skb, struct bpf_sock_tuple *tuple, u32 len, u8 proto, u64 netns_id, u64 flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffe00077c772)
Location: net/core/filter.c:5337
Inline: False
Direct callers:
  - net/core/filter.c:bpf_sk_lookup_udp
  - net/core/filter.c:bpf_sk_lookup_tcp
```
**Symbols:**

```
ffffffe00077c772-ffffffe00077c80e: bpf_sk_lookup (STB_LOCAL)
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
struct sock *bpf_sk_lookup(struct sk_buff *skb, struct bpf_sock_tuple *tuple, u32 len, u8 proto, u64 netns_id, u64 flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff818f9570)
Location: net/core/filter.c:5337
Inline: False
Direct callers:
  - net/core/filter.c:bpf_sk_lookup_udp
  - net/core/filter.c:bpf_sk_lookup_tcp
```
**Symbols:**

```
ffffffff818f9570-ffffffff818f95e9: bpf_sk_lookup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct sock *bpf_sk_lookup(struct sk_buff *skb, struct bpf_sock_tuple *tuple, u32 len, u8 proto, u64 netns_id, u64 flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff818b33a0)
Location: net/core/filter.c:5337
Inline: False
Direct callers:
  - net/core/filter.c:bpf_sk_lookup_udp
  - net/core/filter.c:bpf_sk_lookup_tcp
```
**Symbols:**

```
ffffffff818b33a0-ffffffff818b3419: bpf_sk_lookup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct sock *bpf_sk_lookup(struct sk_buff *skb, struct bpf_sock_tuple *tuple, u32 len, u8 proto, u64 netns_id, u64 flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff8194a5a0)
Location: net/core/filter.c:5337
Inline: False
Direct callers:
  - net/core/filter.c:bpf_sk_lookup_udp
  - net/core/filter.c:bpf_sk_lookup_tcp
```
**Symbols:**

```
ffffffff8194a5a0-ffffffff8194a619: bpf_sk_lookup (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct sock *bpf_sk_lookup(struct sk_buff *skb, struct bpf_sock_tuple *tuple, u32 len, u8 proto, u64 netns_id, u64 flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff8196beb0)
Location: net/core/filter.c:5337
Inline: False
Direct callers:
  - net/core/filter.c:bpf_sk_lookup_udp
  - net/core/filter.c:bpf_sk_lookup_tcp
```
**Symbols:**

```
ffffffff8196beb0-ffffffff8196bf29: bpf_sk_lookup (STB_LOCAL)
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
