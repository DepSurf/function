# Function: <code>inet_frag_reasm_finish</code>

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
void inet_frag_reasm_finish(struct inet_frag_queue *q, struct sk_buff *head, void *reasm_data, bool try_coalesce);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_fragment.c (ffffffff819cf070)
Location: net/ipv4/inet_fragment.c:477
Inline: False
Direct callers:
  - net/ipv4/ip_fragment.c:ip_frag_queue
  - net/ipv6/reassembly.c:ip6_frag_reasm
```
**Symbols:**

```
ffffffff819cf070-ffffffff819cf283: inet_frag_reasm_finish (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void inet_frag_reasm_finish(struct inet_frag_queue *q, struct sk_buff *head, void *reasm_data, bool try_coalesce);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_fragment.c (ffffffff81a05c10)
Location: net/ipv4/inet_fragment.c:477
Inline: False
Direct callers:
  - net/ipv4/ip_fragment.c:ip_frag_queue
  - net/ipv6/reassembly.c:ip6_frag_reasm
```
**Symbols:**

```
ffffffff81a05c10-ffffffff81a05e23: inet_frag_reasm_finish (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void inet_frag_reasm_finish(struct inet_frag_queue *q, struct sk_buff *head, void *reasm_data, bool try_coalesce);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_fragment.c (ffffffff81af5320)
Location: net/ipv4/inet_fragment.c:477
Inline: False
Direct callers:
  - net/ipv4/ip_fragment.c:ip_frag_reasm
  - net/ipv6/reassembly.c:ip6_frag_reasm
```
**Symbols:**

```
ffffffff81af5320-ffffffff81af5533: inet_frag_reasm_finish (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void inet_frag_reasm_finish(struct inet_frag_queue *q, struct sk_buff *head, void *reasm_data, bool try_coalesce);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_fragment.c (ffffffff81b02080)
Location: net/ipv4/inet_fragment.c:508
Inline: False
Direct callers:
  - net/ipv4/ip_fragment.c:ip_frag_reasm
  - net/ipv6/reassembly.c:ip6_frag_reasm
```
**Symbols:**

```
ffffffff81b02080-ffffffff81b02293: inet_frag_reasm_finish (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void inet_frag_reasm_finish(struct inet_frag_queue *q, struct sk_buff *head, void *reasm_data, bool try_coalesce);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_fragment.c (ffffffff81aed990)
Location: net/ipv4/inet_fragment.c:508
Inline: False
```
**Symbols:**

```
ffffffff81aed990-ffffffff81aedba1: inet_frag_reasm_finish (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void inet_frag_reasm_finish(struct inet_frag_queue *q, struct sk_buff *head, void *reasm_data, bool try_coalesce);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/inet_fragment.c (0)
Location: net/ipv4/inet_fragment.c:510
Inline: False
```
**Symbols:**

```
ffffffff81d3dae4-ffffffff81d3daff: inet_frag_reasm_finish.cold (STB_LOCAL)
ffffffff81badd50-ffffffff81badf5a: inet_frag_reasm_finish (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void inet_frag_reasm_finish(struct inet_frag_queue *q, struct sk_buff *head, void *reasm_data, bool try_coalesce);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/inet_fragment.c (0)
Location: net/ipv4/inet_fragment.c:510
Inline: False
```
**Symbols:**

```
ffffffff81f0a3cd-ffffffff81f0a3f1: inet_frag_reasm_finish.cold (STB_LOCAL)
ffffffff81d40df0-ffffffff81d41079: inet_frag_reasm_finish (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void inet_frag_reasm_finish(struct inet_frag_queue *q, struct sk_buff *head, void *reasm_data, bool try_coalesce);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/inet_fragment.c (0)
Location: net/ipv4/inet_fragment.c:516
Inline: False
```
**Symbols:**

```
ffffffff820b1c96-ffffffff820b1cba: inet_frag_reasm_finish.cold (STB_LOCAL)
ffffffff81f09b80-ffffffff81f09e09: inet_frag_reasm_finish (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void inet_frag_reasm_finish(struct inet_frag_queue *q, struct sk_buff *head, void *reasm_data, bool try_coalesce);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/inet_fragment.c (0)
Location: net/ipv4/inet_fragment.c:516
Inline: False
```
**Symbols:**

```
ffffffff82132ece-ffffffff82132ef2: inet_frag_reasm_finish.cold (STB_LOCAL)
ffffffff81f69690-ffffffff81f69916: inet_frag_reasm_finish (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void inet_frag_reasm_finish(struct inet_frag_queue *q, struct sk_buff *head, void *reasm_data, bool try_coalesce);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/ipv4/inet_fragment.c (0)
Location: net/ipv4/inet_fragment.c:516
Inline: False
```
**Symbols:**

```
ffffffff822148af-ffffffff822148d3: inet_frag_reasm_finish.cold (STB_LOCAL)
ffffffff8202fd10-ffffffff8202ff96: inet_frag_reasm_finish (STB_GLOBAL)
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
void inet_frag_reasm_finish(struct inet_frag_queue *q, struct sk_buff *head, void *reasm_data, bool try_coalesce);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_fragment.c (ffff800010cbebd0)
Location: net/ipv4/inet_fragment.c:477
Inline: False
Direct callers:
  - net/ipv4/ip_fragment.c:ip_frag_queue
  - net/ipv6/reassembly.c:ip6_frag_reasm
```
**Symbols:**

```
ffff800010cbebd0-ffff800010cbedac: inet_frag_reasm_finish (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void inet_frag_reasm_finish(struct inet_frag_queue *q, struct sk_buff *head, void *reasm_data, bool try_coalesce);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_fragment.c (c0dca33c)
Location: net/ipv4/inet_fragment.c:477
Inline: False
Direct callers:
  - net/ipv4/ip_fragment.c:ip_frag_queue
  - net/ipv6/reassembly.c:ip6_frag_reasm
```
**Symbols:**

```
c0dca33c-c0dca544: inet_frag_reasm_finish (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void inet_frag_reasm_finish(struct inet_frag_queue *q, struct sk_buff *head, void *reasm_data, bool try_coalesce);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_fragment.c (c000000000dd92c0)
Location: net/ipv4/inet_fragment.c:477
Inline: False
Direct callers:
  - net/ipv4/ip_fragment.c:ip_frag_queue
  - net/ipv6/reassembly.c:ip6_frag_reasm
```
**Symbols:**

```
c000000000dd92c0-c000000000dd9564: inet_frag_reasm_finish (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void inet_frag_reasm_finish(struct inet_frag_queue *q, struct sk_buff *head, void *reasm_data, bool try_coalesce);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_fragment.c (ffffffe000814974)
Location: net/ipv4/inet_fragment.c:477
Inline: False
Direct callers:
  - net/ipv4/ip_fragment.c:ip_frag_queue
  - net/ipv6/reassembly.c:ip6_frag_reasm
```
**Symbols:**

```
ffffffe000814974-ffffffe000814b0c: inet_frag_reasm_finish (STB_GLOBAL)
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
void inet_frag_reasm_finish(struct inet_frag_queue *q, struct sk_buff *head, void *reasm_data, bool try_coalesce);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_fragment.c (ffffffff819a59b0)
Location: net/ipv4/inet_fragment.c:477
Inline: False
Direct callers:
  - net/ipv4/ip_fragment.c:ip_frag_queue
  - net/ipv6/reassembly.c:ip6_frag_reasm
```
**Symbols:**

```
ffffffff819a59b0-ffffffff819a5bc3: inet_frag_reasm_finish (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void inet_frag_reasm_finish(struct inet_frag_queue *q, struct sk_buff *head, void *reasm_data, bool try_coalesce);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_fragment.c (ffffffff8195f470)
Location: net/ipv4/inet_fragment.c:477
Inline: False
Direct callers:
  - net/ipv4/ip_fragment.c:ip_frag_queue
  - net/ipv6/reassembly.c:ip6_frag_reasm
```
**Symbols:**

```
ffffffff8195f470-ffffffff8195f683: inet_frag_reasm_finish (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void inet_frag_reasm_finish(struct inet_frag_queue *q, struct sk_buff *head, void *reasm_data, bool try_coalesce);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_fragment.c (ffffffff81a10250)
Location: net/ipv4/inet_fragment.c:477
Inline: False
Direct callers:
  - net/ipv4/ip_fragment.c:ip_frag_queue
  - net/ipv6/reassembly.c:ip6_frag_reasm
  - net/ipv6/netfilter/nf_conntrack_reasm.c:nf_ct_frag6_queue
```
**Symbols:**

```
ffffffff81a10250-ffffffff81a10463: inet_frag_reasm_finish (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void inet_frag_reasm_finish(struct inet_frag_queue *q, struct sk_buff *head, void *reasm_data, bool try_coalesce);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/ipv4/inet_fragment.c (ffffffff81a1aaa0)
Location: net/ipv4/inet_fragment.c:477
Inline: False
Direct callers:
  - net/ipv4/ip_fragment.c:ip_frag_queue
  - net/ipv6/reassembly.c:ip6_frag_reasm
```
**Symbols:**

```
ffffffff81a1aaa0-ffffffff81a1acb3: inet_frag_reasm_finish (STB_GLOBAL)
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
