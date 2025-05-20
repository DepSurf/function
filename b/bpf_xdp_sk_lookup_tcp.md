# Function: <code>bpf_xdp_sk_lookup_tcp</code>

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
u64 bpf_xdp_sk_lookup_tcp(u64 ctx, u64 tuple, u64 len, u64 netns_id, u64 flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff818d8ec0)
Location: net/core/filter.c:5196
Inline: False
```
**Symbols:**

```
ffffffff818d8ec0-ffffffff818d8ef7: bpf_xdp_sk_lookup_tcp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
u64 bpf_xdp_sk_lookup_tcp(u64 ctx, u64 tuple, u64 len, u64 netns_id, u64 flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81927090)
Location: net/core/filter.c:5464
Inline: False
```
**Symbols:**

```
ffffffff81927090-ffffffff819270cb: bpf_xdp_sk_lookup_tcp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
u64 bpf_xdp_sk_lookup_tcp(u64 ctx, u64 tuple, u64 len, u64 netns_id, u64 flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81959730)
Location: net/core/filter.c:5472
Inline: False
```
**Symbols:**

```
ffffffff81959730-ffffffff8195976b: bpf_xdp_sk_lookup_tcp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
u64 bpf_xdp_sk_lookup_tcp(u64 ctx, u64 tuple, u64 len, u64 netns_id, u64 flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81a2e4e0)
Location: net/core/filter.c:5598
Inline: False
```
**Symbols:**

```
ffffffff81a2e4e0-ffffffff81a2e556: bpf_xdp_sk_lookup_tcp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
u64 bpf_xdp_sk_lookup_tcp(u64 ctx, u64 tuple, u64 len, u64 netns_id, u64 flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81a2fa50)
Location: net/core/filter.c:6150
Inline: False
```
**Symbols:**

```
ffffffff81a2fa50-ffffffff81a2fac6: bpf_xdp_sk_lookup_tcp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
u64 bpf_xdp_sk_lookup_tcp(u64 ctx, u64 tuple, u64 len, u64 netns_id, u64 flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81a174a0)
Location: net/core/filter.c:6252
Inline: False
```
**Symbols:**

```
ffffffff81a174a0-ffffffff81a1750e: bpf_xdp_sk_lookup_tcp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
u64 bpf_xdp_sk_lookup_tcp(u64 ctx, u64 tuple, u64 len, u64 netns_id, u64 flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/core/filter.c (0)
Location: net/core/filter.c:6376
Inline: False
```
**Symbols:**

```
ffffffff81d374cd-ffffffff81d374f5: bpf_xdp_sk_lookup_tcp.cold (STB_LOCAL)
ffffffff81acba30-ffffffff81acbaab: bpf_xdp_sk_lookup_tcp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
u64 bpf_xdp_sk_lookup_tcp(u64 ctx, u64 tuple, u64 len, u64 netns_id, u64 flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81c48c80)
Location: net/core/filter.c:6706
Inline: False
```
**Symbols:**

```
ffffffff81c48c80-ffffffff81c48ccd: bpf_xdp_sk_lookup_tcp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
u64 bpf_xdp_sk_lookup_tcp(u64 ctx, u64 tuple, u64 len, u64 netns_id, u64 flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81dfdfe0)
Location: net/core/filter.c:6718
Inline: False
```
**Symbols:**

```
ffffffff81dfdfe0-ffffffff81dfe02d: bpf_xdp_sk_lookup_tcp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
u64 bpf_xdp_sk_lookup_tcp(u64 ctx, u64 tuple, u64 len, u64 netns_id, u64 flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81e6ed10)
Location: net/core/filter.c:6873
Inline: False
```
**Symbols:**

```
ffffffff81e6ed10-ffffffff81e6ed68: bpf_xdp_sk_lookup_tcp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
u64 bpf_xdp_sk_lookup_tcp(u64 ctx, u64 tuple, u64 len, u64 netns_id, u64 flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81f2e370)
Location: net/core/filter.c:6963
Inline: False
```
**Symbols:**

```
ffffffff81f2e370-ffffffff81f2e3c8: bpf_xdp_sk_lookup_tcp (STB_GLOBAL)
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
u64 bpf_xdp_sk_lookup_tcp(u64 ctx, u64 tuple, u64 len, u64 netns_id, u64 flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffff800010bfae40)
Location: net/core/filter.c:5472
Inline: False
```
**Symbols:**

```
ffff800010bfae40-ffff800010bfaeac: bpf_xdp_sk_lookup_tcp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
u64 bpf_xdp_sk_lookup_tcp(u64 ctx, u64 tuple, u64 len, u64 netns_id, u64 flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (c0d14830)
Location: net/core/filter.c:5472
Inline: False
```
**Symbols:**

```
c0d14830-c0d14890: bpf_xdp_sk_lookup_tcp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
u64 bpf_xdp_sk_lookup_tcp(u64 ctx, u64 tuple, u64 len, u64 netns_id, u64 flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (c000000000ce31c0)
Location: net/core/filter.c:5472
Inline: False
```
**Symbols:**

```
c000000000ce31c0-c000000000ce31f8: bpf_xdp_sk_lookup_tcp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
u64 bpf_xdp_sk_lookup_tcp(u64 ctx, u64 tuple, u64 len, u64 netns_id, u64 flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffe00077c9e4)
Location: net/core/filter.c:5472
Inline: False
```
**Symbols:**

```
ffffffe00077c9e4-ffffffe00077ca42: bpf_xdp_sk_lookup_tcp (STB_GLOBAL)
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
u64 bpf_xdp_sk_lookup_tcp(u64 ctx, u64 tuple, u64 len, u64 netns_id, u64 flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff818f9700)
Location: net/core/filter.c:5472
Inline: False
```
**Symbols:**

```
ffffffff818f9700-ffffffff818f973b: bpf_xdp_sk_lookup_tcp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
u64 bpf_xdp_sk_lookup_tcp(u64 ctx, u64 tuple, u64 len, u64 netns_id, u64 flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff818b3530)
Location: net/core/filter.c:5472
Inline: False
```
**Symbols:**

```
ffffffff818b3530-ffffffff818b356b: bpf_xdp_sk_lookup_tcp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
u64 bpf_xdp_sk_lookup_tcp(u64 ctx, u64 tuple, u64 len, u64 netns_id, u64 flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff8194a730)
Location: net/core/filter.c:5472
Inline: False
```
**Symbols:**

```
ffffffff8194a730-ffffffff8194a76b: bpf_xdp_sk_lookup_tcp (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
u64 bpf_xdp_sk_lookup_tcp(u64 ctx, u64 tuple, u64 len, u64 netns_id, u64 flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff8196c040)
Location: net/core/filter.c:5472
Inline: False
```
**Symbols:**

```
ffffffff8196c040-ffffffff8196c07b: bpf_xdp_sk_lookup_tcp (STB_GLOBAL)
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
