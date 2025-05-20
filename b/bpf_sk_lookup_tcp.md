# Function: <code>bpf_sk_lookup_tcp</code>

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
<summary>In <code>5.0</code>: ✅</summary>

```c
u64 bpf_sk_lookup_tcp(u64 skb, u64 tuple, u64 len, u64 netns_id, u64 flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff818d8f60)
Location: net/core/filter.c:5124
Inline: False
```
**Symbols:**

```
ffffffff818d8f60-ffffffff818d8fa1: bpf_sk_lookup_tcp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
u64 bpf_sk_lookup_tcp(u64 skb, u64 tuple, u64 len, u64 netns_id, u64 flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81926f70)
Location: net/core/filter.c:5366
Inline: False
```
**Symbols:**

```
ffffffff81926f70-ffffffff81926f8b: bpf_sk_lookup_tcp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
u64 bpf_sk_lookup_tcp(u64 skb, u64 tuple, u64 len, u64 netns_id, u64 flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81959620)
Location: net/core/filter.c:5373
Inline: False
```
**Symbols:**

```
ffffffff81959620-ffffffff8195963b: bpf_sk_lookup_tcp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
u64 bpf_sk_lookup_tcp(u64 skb, u64 tuple, u64 len, u64 netns_id, u64 flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81a2e5b0)
Location: net/core/filter.c:5500
Inline: False
```
**Symbols:**

```
ffffffff81a2e5b0-ffffffff81a2e631: bpf_sk_lookup_tcp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
u64 bpf_sk_lookup_tcp(u64 skb, u64 tuple, u64 len, u64 netns_id, u64 flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81a2fb20)
Location: net/core/filter.c:6052
Inline: False
```
**Symbols:**

```
ffffffff81a2fb20-ffffffff81a2fba1: bpf_sk_lookup_tcp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
u64 bpf_sk_lookup_tcp(u64 skb, u64 tuple, u64 len, u64 netns_id, u64 flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81a16be0)
Location: net/core/filter.c:6154
Inline: False
```
**Symbols:**

```
ffffffff81a16be0-ffffffff81a16c59: bpf_sk_lookup_tcp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
u64 bpf_sk_lookup_tcp(u64 skb, u64 tuple, u64 len, u64 netns_id, u64 flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/filter.c (0)
Location: net/core/filter.c:6278
Inline: False
```
**Symbols:**

```
ffffffff81d37545-ffffffff81d3756d: bpf_sk_lookup_tcp.cold (STB_LOCAL)
ffffffff81acbd90-ffffffff81acbe16: bpf_sk_lookup_tcp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
u64 bpf_sk_lookup_tcp(u64 skb, u64 tuple, u64 len, u64 netns_id, u64 flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81c49580)
Location: net/core/filter.c:6608
Inline: False
```
**Symbols:**

```
ffffffff81c49580-ffffffff81c495ad: bpf_sk_lookup_tcp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
u64 bpf_sk_lookup_tcp(u64 skb, u64 tuple, u64 len, u64 netns_id, u64 flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81dfe560)
Location: net/core/filter.c:6620
Inline: False
```
**Symbols:**

```
ffffffff81dfe560-ffffffff81dfe58d: bpf_sk_lookup_tcp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
u64 bpf_sk_lookup_tcp(u64 skb, u64 tuple, u64 len, u64 netns_id, u64 flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81e6f500)
Location: net/core/filter.c:6701
Inline: False
```
**Symbols:**

```
ffffffff81e6f500-ffffffff81e6f52d: bpf_sk_lookup_tcp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
u64 bpf_sk_lookup_tcp(u64 skb, u64 tuple, u64 len, u64 netns_id, u64 flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81f2eb40)
Location: net/core/filter.c:6791
Inline: False
```
**Symbols:**

```
ffffffff81f2eb40-ffffffff81f2eb6d: bpf_sk_lookup_tcp (STB_GLOBAL)
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
u64 bpf_sk_lookup_tcp(u64 skb, u64 tuple, u64 len, u64 netns_id, u64 flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffff800010bfabf8)
Location: net/core/filter.c:5373
Inline: False
```
**Symbols:**

```
ffff800010bfabf8-ffff800010bfac58: bpf_sk_lookup_tcp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
u64 bpf_sk_lookup_tcp(u64 skb, u64 tuple, u64 len, u64 netns_id, u64 flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (c0d14678)
Location: net/core/filter.c:5373
Inline: False
```
**Symbols:**

```
c0d14678-c0d146bc: bpf_sk_lookup_tcp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
u64 bpf_sk_lookup_tcp(u64 skb, u64 tuple, u64 len, u64 netns_id, u64 flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (c000000000ce3010)
Location: net/core/filter.c:5373
Inline: False
```
**Symbols:**

```
c000000000ce3010-c000000000ce3038: bpf_sk_lookup_tcp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
u64 bpf_sk_lookup_tcp(u64 skb, u64 tuple, u64 len, u64 netns_id, u64 flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffe00077c80e)
Location: net/core/filter.c:5373
Inline: False
```
**Symbols:**

```
ffffffe00077c80e-ffffffe00077c85c: bpf_sk_lookup_tcp (STB_GLOBAL)
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
u64 bpf_sk_lookup_tcp(u64 skb, u64 tuple, u64 len, u64 netns_id, u64 flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff818f95f0)
Location: net/core/filter.c:5373
Inline: False
```
**Symbols:**

```
ffffffff818f95f0-ffffffff818f960b: bpf_sk_lookup_tcp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
u64 bpf_sk_lookup_tcp(u64 skb, u64 tuple, u64 len, u64 netns_id, u64 flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff818b3420)
Location: net/core/filter.c:5373
Inline: False
```
**Symbols:**

```
ffffffff818b3420-ffffffff818b343b: bpf_sk_lookup_tcp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
u64 bpf_sk_lookup_tcp(u64 skb, u64 tuple, u64 len, u64 netns_id, u64 flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff8194a620)
Location: net/core/filter.c:5373
Inline: False
```
**Symbols:**

```
ffffffff8194a620-ffffffff8194a63b: bpf_sk_lookup_tcp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
u64 bpf_sk_lookup_tcp(u64 skb, u64 tuple, u64 len, u64 netns_id, u64 flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff8196bf30)
Location: net/core/filter.c:5373
Inline: False
```
**Symbols:**

```
ffffffff8196bf30-ffffffff8196bf4b: bpf_sk_lookup_tcp (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
