# Function: <code>bpf_l4_csum_replace</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
u64 bpf_l4_csum_replace(u64 r1, u64 r2, u64 from, u64 to, u64 flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff817326a0)
Location: net/core/filter.c:1356
Inline: False
```
**Symbols:**

```
ffffffff817326a0-ffffffff81732858: bpf_l4_csum_replace (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
u64 bpf_l4_csum_replace(u64 r1, u64 r2, u64 from, u64 to, u64 flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff8179c630)
Location: net/core/filter.c:1494
Inline: False
```
**Symbols:**

```
ffffffff8179c630-ffffffff8179c79e: bpf_l4_csum_replace (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
u64 bpf_l4_csum_replace(u64 skb, u64 offset, u64 from, u64 to, u64 flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff817cb8d0)
Location: net/core/filter.c:1520
Inline: False
```
**Symbols:**

```
ffffffff817cb8d0-ffffffff817cba3e: bpf_l4_csum_replace (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
u64 bpf_l4_csum_replace(u64 skb, u64 offset, u64 from, u64 to, u64 flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff817ea9a0)
Location: net/core/filter.c:1545
Inline: False
```
**Symbols:**

```
ffffffff817ea9a0-ffffffff817eab16: bpf_l4_csum_replace (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
u64 bpf_l4_csum_replace(u64 skb, u64 offset, u64 from, u64 to, u64 flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81866b70)
Location: net/core/filter.c:1566
Inline: False
```
**Symbols:**

```
ffffffff81866b70-ffffffff81866d02: bpf_l4_csum_replace (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
u64 bpf_l4_csum_replace(u64 skb, u64 offset, u64 from, u64 to, u64 flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff818b5bb0)
Location: net/core/filter.c:1852
Inline: False
```
**Symbols:**

```
ffffffff818b5bb0-ffffffff818b5d4a: bpf_l4_csum_replace (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
u64 bpf_l4_csum_replace(u64 skb, u64 offset, u64 from, u64 to, u64 flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff818db780)
Location: net/core/filter.c:1871
Inline: False
```
**Symbols:**

```
ffffffff818db780-ffffffff818db8fc: bpf_l4_csum_replace (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
u64 bpf_l4_csum_replace(u64 skb, u64 offset, u64 from, u64 to, u64 flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81928c10)
Location: net/core/filter.c:1917
Inline: False
```
**Symbols:**

```
ffffffff81928c10-ffffffff81928d7e: bpf_l4_csum_replace (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
u64 bpf_l4_csum_replace(u64 skb, u64 offset, u64 from, u64 to, u64 flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff8195b2f0)
Location: net/core/filter.c:1917
Inline: False
```
**Symbols:**

```
ffffffff8195b2f0-ffffffff8195b45e: bpf_l4_csum_replace (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
u64 bpf_l4_csum_replace(u64 skb, u64 offset, u64 from, u64 to, u64 flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81a2fa70)
Location: net/core/filter.c:1908
Inline: False
```
**Symbols:**

```
ffffffff81a2fa70-ffffffff81a2fbde: bpf_l4_csum_replace (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
u64 bpf_l4_csum_replace(u64 skb, u64 offset, u64 from, u64 to, u64 flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81a32340)
Location: net/core/filter.c:1938
Inline: False
```
**Symbols:**

```
ffffffff81a32340-ffffffff81a324ae: bpf_l4_csum_replace (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
u64 bpf_l4_csum_replace(u64 skb, u64 offset, u64 from, u64 to, u64 flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81a19490)
Location: net/core/filter.c:1935
Inline: False
```
**Symbols:**

```
ffffffff81a19490-ffffffff81a195fe: bpf_l4_csum_replace (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
u64 bpf_l4_csum_replace(u64 skb, u64 offset, u64 from, u64 to, u64 flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81ac9f60)
Location: net/core/filter.c:1936
Inline: False
```
**Symbols:**

```
ffffffff81ac9f60-ffffffff81aca0ce: bpf_l4_csum_replace (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
u64 bpf_l4_csum_replace(u64 skb, u64 offset, u64 from, u64 to, u64 flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81c46ab0)
Location: net/core/filter.c:1937
Inline: False
```
**Symbols:**

```
ffffffff81c46ab0-ffffffff81c46c3b: bpf_l4_csum_replace (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
u64 bpf_l4_csum_replace(u64 skb, u64 offset, u64 from, u64 to, u64 flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81dfafe0)
Location: net/core/filter.c:1939
Inline: False
```
**Symbols:**

```
ffffffff81dfafe0-ffffffff81dfb16b: bpf_l4_csum_replace (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
u64 bpf_l4_csum_replace(u64 skb, u64 offset, u64 from, u64 to, u64 flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81e6cda0)
Location: net/core/filter.c:1950
Inline: False
```
**Symbols:**

```
ffffffff81e6cda0-ffffffff81e6cf14: bpf_l4_csum_replace (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
u64 bpf_l4_csum_replace(u64 skb, u64 offset, u64 from, u64 to, u64 flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81f2c610)
Location: net/core/filter.c:1957
Inline: False
```
**Symbols:**

```
ffffffff81f2c610-ffffffff81f2c784: bpf_l4_csum_replace (STB_GLOBAL)
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
u64 bpf_l4_csum_replace(u64 skb, u64 offset, u64 from, u64 to, u64 flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffff800010bfc610)
Location: net/core/filter.c:1917
Inline: False
```
**Symbols:**

```
ffff800010bfc610-ffff800010bfc7bc: bpf_l4_csum_replace (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
u64 bpf_l4_csum_replace(u64 skb, u64 offset, u64 from, u64 to, u64 flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (c0d173d0)
Location: net/core/filter.c:1917
Inline: False
```
**Symbols:**

```
c0d173d0-c0d1757c: bpf_l4_csum_replace (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
u64 bpf_l4_csum_replace(u64 skb, u64 offset, u64 from, u64 to, u64 flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (c000000000ce4f10)
Location: net/core/filter.c:1917
Inline: False
```
**Symbols:**

```
c000000000ce4f10-c000000000ce514c: bpf_l4_csum_replace (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
u64 bpf_l4_csum_replace(u64 skb, u64 offset, u64 from, u64 to, u64 flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffe00077f3e0)
Location: net/core/filter.c:1917
Inline: False
```
**Symbols:**

```
ffffffe00077f3e0-ffffffe00077f4fe: bpf_l4_csum_replace (STB_GLOBAL)
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
u64 bpf_l4_csum_replace(u64 skb, u64 offset, u64 from, u64 to, u64 flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff818fb2c0)
Location: net/core/filter.c:1917
Inline: False
```
**Symbols:**

```
ffffffff818fb2c0-ffffffff818fb42e: bpf_l4_csum_replace (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
u64 bpf_l4_csum_replace(u64 skb, u64 offset, u64 from, u64 to, u64 flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff818b50f0)
Location: net/core/filter.c:1917
Inline: False
```
**Symbols:**

```
ffffffff818b50f0-ffffffff818b525e: bpf_l4_csum_replace (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
u64 bpf_l4_csum_replace(u64 skb, u64 offset, u64 from, u64 to, u64 flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff8194c2f0)
Location: net/core/filter.c:1917
Inline: False
```
**Symbols:**

```
ffffffff8194c2f0-ffffffff8194c45e: bpf_l4_csum_replace (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
u64 bpf_l4_csum_replace(u64 skb, u64 offset, u64 from, u64 to, u64 flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff8196dcb0)
Location: net/core/filter.c:1917
Inline: False
```
**Symbols:**

```
ffffffff8196dcb0-ffffffff8196de1e: bpf_l4_csum_replace (STB_GLOBAL)
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
<details>
<summary>Changed between <code>4.8</code> and <code>4.10</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>u64 skb</code>
</li>
<li>
<b>Param added. </b>
<code>u64 offset</code>
</li>
<li>
<b>Param removed. </b>
<code>u64 r1</code>
</li>
<li>
<b>Param removed. </b>
<code>u64 r2</code>
</li>
</ul>
</details>
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
