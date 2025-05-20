# Function: <code>bpf_l3_csum_replace</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
u64 bpf_l3_csum_replace(u64 r1, u64 r2, u64 from, u64 to, u64 flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81732300)
Location: net/core/filter.c:1310
Inline: False
```
**Symbols:**

```
ffffffff81732300-ffffffff817324d0: bpf_l3_csum_replace (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
u64 bpf_l3_csum_replace(u64 r1, u64 r2, u64 from, u64 to, u64 flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff8179c7a0)
Location: net/core/filter.c:1449
Inline: False
```
**Symbols:**

```
ffffffff8179c7a0-ffffffff8179c90e: bpf_l3_csum_replace (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
u64 bpf_l3_csum_replace(u64 skb, u64 offset, u64 from, u64 to, u64 flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff817cba40)
Location: net/core/filter.c:1476
Inline: False
```
**Symbols:**

```
ffffffff817cba40-ffffffff817cbbae: bpf_l3_csum_replace (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
u64 bpf_l3_csum_replace(u64 skb, u64 offset, u64 from, u64 to, u64 flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff817eab20)
Location: net/core/filter.c:1501
Inline: False
```
**Symbols:**

```
ffffffff817eab20-ffffffff817eac8e: bpf_l3_csum_replace (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
u64 bpf_l3_csum_replace(u64 skb, u64 offset, u64 from, u64 to, u64 flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81866d10)
Location: net/core/filter.c:1522
Inline: False
```
**Symbols:**

```
ffffffff81866d10-ffffffff81866e9a: bpf_l3_csum_replace (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
u64 bpf_l3_csum_replace(u64 skb, u64 offset, u64 from, u64 to, u64 flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff818b66e0)
Location: net/core/filter.c:1808
Inline: False
```
**Symbols:**

```
ffffffff818b66e0-ffffffff818b686d: bpf_l3_csum_replace (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
u64 bpf_l3_csum_replace(u64 skb, u64 offset, u64 from, u64 to, u64 flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff818db900)
Location: net/core/filter.c:1827
Inline: False
```
**Symbols:**

```
ffffffff818db900-ffffffff818dba55: bpf_l3_csum_replace (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
u64 bpf_l3_csum_replace(u64 skb, u64 offset, u64 from, u64 to, u64 flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81928d80)
Location: net/core/filter.c:1873
Inline: False
```
**Symbols:**

```
ffffffff81928d80-ffffffff81928efc: bpf_l3_csum_replace (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
u64 bpf_l3_csum_replace(u64 skb, u64 offset, u64 from, u64 to, u64 flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff8195b460)
Location: net/core/filter.c:1873
Inline: False
```
**Symbols:**

```
ffffffff8195b460-ffffffff8195b5dc: bpf_l3_csum_replace (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
u64 bpf_l3_csum_replace(u64 skb, u64 offset, u64 from, u64 to, u64 flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81a2f8f0)
Location: net/core/filter.c:1864
Inline: False
```
**Symbols:**

```
ffffffff81a2f8f0-ffffffff81a2fa6c: bpf_l3_csum_replace (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
u64 bpf_l3_csum_replace(u64 skb, u64 offset, u64 from, u64 to, u64 flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81a321c0)
Location: net/core/filter.c:1894
Inline: False
```
**Symbols:**

```
ffffffff81a321c0-ffffffff81a3233c: bpf_l3_csum_replace (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
u64 bpf_l3_csum_replace(u64 skb, u64 offset, u64 from, u64 to, u64 flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81a19320)
Location: net/core/filter.c:1891
Inline: False
```
**Symbols:**

```
ffffffff81a19320-ffffffff81a19484: bpf_l3_csum_replace (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
u64 bpf_l3_csum_replace(u64 skb, u64 offset, u64 from, u64 to, u64 flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81aca0d0)
Location: net/core/filter.c:1892
Inline: False
```
**Symbols:**

```
ffffffff81aca0d0-ffffffff81aca234: bpf_l3_csum_replace (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
u64 bpf_l3_csum_replace(u64 skb, u64 offset, u64 from, u64 to, u64 flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81c46c40)
Location: net/core/filter.c:1893
Inline: False
```
**Symbols:**

```
ffffffff81c46c40-ffffffff81c46d76: bpf_l3_csum_replace (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
u64 bpf_l3_csum_replace(u64 skb, u64 offset, u64 from, u64 to, u64 flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81dfb180)
Location: net/core/filter.c:1895
Inline: False
```
**Symbols:**

```
ffffffff81dfb180-ffffffff81dfb2b6: bpf_l3_csum_replace (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
u64 bpf_l3_csum_replace(u64 skb, u64 offset, u64 from, u64 to, u64 flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81e6cf30)
Location: net/core/filter.c:1906
Inline: False
```
**Symbols:**

```
ffffffff81e6cf30-ffffffff81e6d0a3: bpf_l3_csum_replace (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
u64 bpf_l3_csum_replace(u64 skb, u64 offset, u64 from, u64 to, u64 flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81f2c7a0)
Location: net/core/filter.c:1913
Inline: False
```
**Symbols:**

```
ffffffff81f2c7a0-ffffffff81f2c913: bpf_l3_csum_replace (STB_GLOBAL)
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
u64 bpf_l3_csum_replace(u64 skb, u64 offset, u64 from, u64 to, u64 flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffff800010bfc448)
Location: net/core/filter.c:1873
Inline: False
```
**Symbols:**

```
ffff800010bfc448-ffff800010bfc60c: bpf_l3_csum_replace (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
u64 bpf_l3_csum_replace(u64 skb, u64 offset, u64 from, u64 to, u64 flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (c0d17258)
Location: net/core/filter.c:1873
Inline: False
```
**Symbols:**

```
c0d17258-c0d173d0: bpf_l3_csum_replace (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
u64 bpf_l3_csum_replace(u64 skb, u64 offset, u64 from, u64 to, u64 flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (c000000000ce4cd0)
Location: net/core/filter.c:1873
Inline: False
```
**Symbols:**

```
c000000000ce4cd0-c000000000ce4f10: bpf_l3_csum_replace (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
u64 bpf_l3_csum_replace(u64 skb, u64 offset, u64 from, u64 to, u64 flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffe00077918c)
Location: net/core/filter.c:1873
Inline: False
```
**Symbols:**

```
ffffffe00077918c-ffffffe000779302: bpf_l3_csum_replace (STB_GLOBAL)
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
u64 bpf_l3_csum_replace(u64 skb, u64 offset, u64 from, u64 to, u64 flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff818fb430)
Location: net/core/filter.c:1873
Inline: False
```
**Symbols:**

```
ffffffff818fb430-ffffffff818fb5ac: bpf_l3_csum_replace (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
u64 bpf_l3_csum_replace(u64 skb, u64 offset, u64 from, u64 to, u64 flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff818b5260)
Location: net/core/filter.c:1873
Inline: False
```
**Symbols:**

```
ffffffff818b5260-ffffffff818b53dc: bpf_l3_csum_replace (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
u64 bpf_l3_csum_replace(u64 skb, u64 offset, u64 from, u64 to, u64 flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff8194c460)
Location: net/core/filter.c:1873
Inline: False
```
**Symbols:**

```
ffffffff8194c460-ffffffff8194c5dc: bpf_l3_csum_replace (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
u64 bpf_l3_csum_replace(u64 skb, u64 offset, u64 from, u64 to, u64 flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff8196de20)
Location: net/core/filter.c:1873
Inline: False
```
**Symbols:**

```
ffffffff8196de20-ffffffff8196df9c: bpf_l3_csum_replace (STB_GLOBAL)
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
