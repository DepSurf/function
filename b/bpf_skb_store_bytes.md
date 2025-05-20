# Function: <code>bpf_skb_store_bytes</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
u64 bpf_skb_store_bytes(u64 r1, u64 r2, u64 r3, u64 r4, u64 flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81732860)
Location: net/core/filter.c:1254
Inline: False
```
**Symbols:**

```
ffffffff81732860-ffffffff81732ad7: bpf_skb_store_bytes (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
u64 bpf_skb_store_bytes(u64 r1, u64 r2, u64 r3, u64 r4, u64 flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff8179c910)
Location: net/core/filter.c:1376
Inline: False
```
**Symbols:**

```
ffffffff8179c910-ffffffff8179ca8b: bpf_skb_store_bytes (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
u64 bpf_skb_store_bytes(u64 skb, u64 offset, u64 from, u64 len, u64 flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff817ca120)
Location: net/core/filter.c:1387
Inline: False
```
**Symbols:**

```
ffffffff817ca120-ffffffff817ca29b: bpf_skb_store_bytes (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
u64 bpf_skb_store_bytes(u64 skb, u64 offset, u64 from, u64 len, u64 flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff817e9090)
Location: net/core/filter.c:1412
Inline: False
```
**Symbols:**

```
ffffffff817e9090-ffffffff817e9227: bpf_skb_store_bytes (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
u64 bpf_skb_store_bytes(u64 skb, u64 offset, u64 from, u64 len, u64 flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81864480)
Location: net/core/filter.c:1433
Inline: False
```
**Symbols:**

```
ffffffff81864480-ffffffff8186462f: bpf_skb_store_bytes (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
u64 bpf_skb_store_bytes(u64 skb, u64 offset, u64 from, u64 len, u64 flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff818b6870)
Location: net/core/filter.c:1645
Inline: False
```
**Symbols:**

```
ffffffff818b6870-ffffffff818b6a2d: bpf_skb_store_bytes (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
u64 bpf_skb_store_bytes(u64 skb, u64 offset, u64 from, u64 len, u64 flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff818dbcc0)
Location: net/core/filter.c:1664
Inline: False
```
**Symbols:**

```
ffffffff818dbcc0-ffffffff818dbe79: bpf_skb_store_bytes (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
u64 bpf_skb_store_bytes(u64 skb, u64 offset, u64 from, u64 len, u64 flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81928f00)
Location: net/core/filter.c:1664
Inline: False
```
**Symbols:**

```
ffffffff81928f00-ffffffff819290c2: bpf_skb_store_bytes (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
u64 bpf_skb_store_bytes(u64 skb, u64 offset, u64 from, u64 len, u64 flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff8195b5e0)
Location: net/core/filter.c:1664
Inline: False
```
**Symbols:**

```
ffffffff8195b5e0-ffffffff8195b7a2: bpf_skb_store_bytes (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
u64 bpf_skb_store_bytes(u64 skb, u64 offset, u64 from, u64 len, u64 flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81a2fbe0)
Location: net/core/filter.c:1653
Inline: False
```
**Symbols:**

```
ffffffff81a2fbe0-ffffffff81a2fd8a: bpf_skb_store_bytes (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
u64 bpf_skb_store_bytes(u64 skb, u64 offset, u64 from, u64 len, u64 flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81a324b0)
Location: net/core/filter.c:1683
Inline: False
```
**Symbols:**

```
ffffffff81a324b0-ffffffff81a3265a: bpf_skb_store_bytes (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
u64 bpf_skb_store_bytes(u64 skb, u64 offset, u64 from, u64 len, u64 flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81a19600)
Location: net/core/filter.c:1683
Inline: False
```
**Symbols:**

```
ffffffff81a19600-ffffffff81a197bc: bpf_skb_store_bytes (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
u64 bpf_skb_store_bytes(u64 skb, u64 offset, u64 from, u64 len, u64 flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81aca8a0)
Location: net/core/filter.c:1684
Inline: False
```
**Symbols:**

```
ffffffff81aca8a0-ffffffff81acaa5c: bpf_skb_store_bytes (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
u64 bpf_skb_store_bytes(u64 skb, u64 offset, u64 from, u64 len, u64 flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81c48210)
Location: net/core/filter.c:1685
Inline: False
```
**Symbols:**

```
ffffffff81c48210-ffffffff81c483ec: bpf_skb_store_bytes (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
u64 bpf_skb_store_bytes(u64 skb, u64 offset, u64 from, u64 len, u64 flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81dfd1a0)
Location: net/core/filter.c:1687
Inline: False
```
**Symbols:**

```
ffffffff81dfd1a0-ffffffff81dfd37c: bpf_skb_store_bytes (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
u64 bpf_skb_store_bytes(u64 skb, u64 offset, u64 from, u64 len, u64 flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81e6e6c0)
Location: net/core/filter.c:1687
Inline: False
```
**Symbols:**

```
ffffffff81e6e6c0-ffffffff81e6e89c: bpf_skb_store_bytes (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
u64 bpf_skb_store_bytes(u64 skb, u64 offset, u64 from, u64 len, u64 flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81f2df30)
Location: net/core/filter.c:1694
Inline: False
```
**Symbols:**

```
ffffffff81f2df30-ffffffff81f2e10c: bpf_skb_store_bytes (STB_GLOBAL)
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
u64 bpf_skb_store_bytes(u64 skb, u64 offset, u64 from, u64 len, u64 flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffff800010bfc7c0)
Location: net/core/filter.c:1664
Inline: False
```
**Symbols:**

```
ffff800010bfc7c0-ffff800010bfc994: bpf_skb_store_bytes (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
u64 bpf_skb_store_bytes(u64 skb, u64 offset, u64 from, u64 len, u64 flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (c0d177fc)
Location: net/core/filter.c:1664
Inline: False
```
**Symbols:**

```
c0d177fc-c0d179b8: bpf_skb_store_bytes (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
u64 bpf_skb_store_bytes(u64 skb, u64 offset, u64 from, u64 len, u64 flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (c000000000ce8aa0)
Location: net/core/filter.c:1664
Inline: False
```
**Symbols:**

```
c000000000ce8aa0-c000000000ce8d00: bpf_skb_store_bytes (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
u64 bpf_skb_store_bytes(u64 skb, u64 offset, u64 from, u64 len, u64 flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffe00077f4fe)
Location: net/core/filter.c:1664
Inline: False
```
**Symbols:**

```
ffffffe00077f4fe-ffffffe00077f68c: bpf_skb_store_bytes (STB_GLOBAL)
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
u64 bpf_skb_store_bytes(u64 skb, u64 offset, u64 from, u64 len, u64 flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff818fb5b0)
Location: net/core/filter.c:1664
Inline: False
```
**Symbols:**

```
ffffffff818fb5b0-ffffffff818fb772: bpf_skb_store_bytes (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
u64 bpf_skb_store_bytes(u64 skb, u64 offset, u64 from, u64 len, u64 flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff818b53e0)
Location: net/core/filter.c:1664
Inline: False
```
**Symbols:**

```
ffffffff818b53e0-ffffffff818b55a2: bpf_skb_store_bytes (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
u64 bpf_skb_store_bytes(u64 skb, u64 offset, u64 from, u64 len, u64 flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff8194c5e0)
Location: net/core/filter.c:1664
Inline: False
```
**Symbols:**

```
ffffffff8194c5e0-ffffffff8194c7a2: bpf_skb_store_bytes (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
u64 bpf_skb_store_bytes(u64 skb, u64 offset, u64 from, u64 len, u64 flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff8196dfa0)
Location: net/core/filter.c:1664
Inline: False
```
**Symbols:**

```
ffffffff8196dfa0-ffffffff8196e162: bpf_skb_store_bytes (STB_GLOBAL)
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
<b>Param added. </b>
<code>u64 from</code>
</li>
<li>
<b>Param added. </b>
<code>u64 len</code>
</li>
<li>
<b>Param removed. </b>
<code>u64 r1</code>
</li>
<li>
<b>Param removed. </b>
<code>u64 r2</code>
</li>
<li>
<b>Param removed. </b>
<code>u64 r3</code>
</li>
<li>
<b>Param removed. </b>
<code>u64 r4</code>
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
