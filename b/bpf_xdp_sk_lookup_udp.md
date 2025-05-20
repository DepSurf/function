# Function: <code>bpf_xdp_sk_lookup_udp</code>

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
u64 bpf_xdp_sk_lookup_udp(u64 ctx, u64 tuple, u64 len, u64 netns_id, u64 flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff818d8e80)
Location: net/core/filter.c:5174
Inline: False
```
**Symbols:**

```
ffffffff818d8e80-ffffffff818d8eb7: bpf_xdp_sk_lookup_udp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
u64 bpf_xdp_sk_lookup_udp(u64 ctx, u64 tuple, u64 len, u64 netns_id, u64 flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff819270d0)
Location: net/core/filter.c:5418
Inline: False
```
**Symbols:**

```
ffffffff819270d0-ffffffff8192710b: bpf_xdp_sk_lookup_udp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
u64 bpf_xdp_sk_lookup_udp(u64 ctx, u64 tuple, u64 len, u64 netns_id, u64 flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81959770)
Location: net/core/filter.c:5426
Inline: False
```
**Symbols:**

```
ffffffff81959770-ffffffff819597ab: bpf_xdp_sk_lookup_udp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
u64 bpf_xdp_sk_lookup_udp(u64 ctx, u64 tuple, u64 len, u64 netns_id, u64 flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81a2e720)
Location: net/core/filter.c:5552
Inline: False
```
**Symbols:**

```
ffffffff81a2e720-ffffffff81a2e796: bpf_xdp_sk_lookup_udp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
u64 bpf_xdp_sk_lookup_udp(u64 ctx, u64 tuple, u64 len, u64 netns_id, u64 flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81a30530)
Location: net/core/filter.c:6104
Inline: False
```
**Symbols:**

```
ffffffff81a30530-ffffffff81a305a6: bpf_xdp_sk_lookup_udp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
u64 bpf_xdp_sk_lookup_udp(u64 ctx, u64 tuple, u64 len, u64 netns_id, u64 flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81a16b20)
Location: net/core/filter.c:6206
Inline: False
```
**Symbols:**

```
ffffffff81a16b20-ffffffff81a16b8e: bpf_xdp_sk_lookup_udp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
u64 bpf_xdp_sk_lookup_udp(u64 ctx, u64 tuple, u64 len, u64 netns_id, u64 flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/filter.c (0)
Location: net/core/filter.c:6330
Inline: False
```
**Symbols:**

```
ffffffff81d374f5-ffffffff81d3751d: bpf_xdp_sk_lookup_udp.cold (STB_LOCAL)
ffffffff81acbab0-ffffffff81acbb2b: bpf_xdp_sk_lookup_udp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
u64 bpf_xdp_sk_lookup_udp(u64 ctx, u64 tuple, u64 len, u64 netns_id, u64 flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81c48cd0)
Location: net/core/filter.c:6660
Inline: False
```
**Symbols:**

```
ffffffff81c48cd0-ffffffff81c48d1d: bpf_xdp_sk_lookup_udp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
u64 bpf_xdp_sk_lookup_udp(u64 ctx, u64 tuple, u64 len, u64 netns_id, u64 flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81dfe040)
Location: net/core/filter.c:6672
Inline: False
```
**Symbols:**

```
ffffffff81dfe040-ffffffff81dfe08d: bpf_xdp_sk_lookup_udp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
u64 bpf_xdp_sk_lookup_udp(u64 ctx, u64 tuple, u64 len, u64 netns_id, u64 flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81e6eca0)
Location: net/core/filter.c:6825
Inline: False
```
**Symbols:**

```
ffffffff81e6eca0-ffffffff81e6ecf8: bpf_xdp_sk_lookup_udp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
u64 bpf_xdp_sk_lookup_udp(u64 ctx, u64 tuple, u64 len, u64 netns_id, u64 flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81f2e300)
Location: net/core/filter.c:6915
Inline: False
```
**Symbols:**

```
ffffffff81f2e300-ffffffff81f2e358: bpf_xdp_sk_lookup_udp (STB_GLOBAL)
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
u64 bpf_xdp_sk_lookup_udp(u64 ctx, u64 tuple, u64 len, u64 netns_id, u64 flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffff800010bfaeb0)
Location: net/core/filter.c:5426
Inline: False
```
**Symbols:**

```
ffff800010bfaeb0-ffff800010bfaf1c: bpf_xdp_sk_lookup_udp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
u64 bpf_xdp_sk_lookup_udp(u64 ctx, u64 tuple, u64 len, u64 netns_id, u64 flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (c0d14890)
Location: net/core/filter.c:5426
Inline: False
```
**Symbols:**

```
c0d14890-c0d148f0: bpf_xdp_sk_lookup_udp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
u64 bpf_xdp_sk_lookup_udp(u64 ctx, u64 tuple, u64 len, u64 netns_id, u64 flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (c000000000ce3200)
Location: net/core/filter.c:5426
Inline: False
```
**Symbols:**

```
c000000000ce3200-c000000000ce3238: bpf_xdp_sk_lookup_udp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
u64 bpf_xdp_sk_lookup_udp(u64 ctx, u64 tuple, u64 len, u64 netns_id, u64 flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffe00077ca42)
Location: net/core/filter.c:5426
Inline: False
```
**Symbols:**

```
ffffffe00077ca42-ffffffe00077caa0: bpf_xdp_sk_lookup_udp (STB_GLOBAL)
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
u64 bpf_xdp_sk_lookup_udp(u64 ctx, u64 tuple, u64 len, u64 netns_id, u64 flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff818f9740)
Location: net/core/filter.c:5426
Inline: False
```
**Symbols:**

```
ffffffff818f9740-ffffffff818f977b: bpf_xdp_sk_lookup_udp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
u64 bpf_xdp_sk_lookup_udp(u64 ctx, u64 tuple, u64 len, u64 netns_id, u64 flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff818b3570)
Location: net/core/filter.c:5426
Inline: False
```
**Symbols:**

```
ffffffff818b3570-ffffffff818b35ab: bpf_xdp_sk_lookup_udp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
u64 bpf_xdp_sk_lookup_udp(u64 ctx, u64 tuple, u64 len, u64 netns_id, u64 flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff8194a770)
Location: net/core/filter.c:5426
Inline: False
```
**Symbols:**

```
ffffffff8194a770-ffffffff8194a7ab: bpf_xdp_sk_lookup_udp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
u64 bpf_xdp_sk_lookup_udp(u64 ctx, u64 tuple, u64 len, u64 netns_id, u64 flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff8196c080)
Location: net/core/filter.c:5426
Inline: False
```
**Symbols:**

```
ffffffff8196c080-ffffffff8196c0bb: bpf_xdp_sk_lookup_udp (STB_GLOBAL)
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
