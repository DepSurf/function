# Function: <code>bpf_skb_event_output</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
u64 bpf_skb_event_output(u64 r1, u64 r2, u64 flags, u64 r4, u64 meta_size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff8179ca90)
Location: net/core/filter.c:2026
Inline: False
```
**Symbols:**

```
ffffffff8179ca90-ffffffff8179caf8: bpf_skb_event_output (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
u64 bpf_skb_event_output(u64 skb, u64 map, u64 flags, u64 meta, u64 meta_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff817ca3f0)
Location: net/core/filter.c:2288
Inline: False
```
**Symbols:**

```
ffffffff817ca3f0-ffffffff817ca458: bpf_skb_event_output (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
u64 bpf_skb_event_output(u64 skb, u64 map, u64 flags, u64 meta, u64 meta_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff817e93e0)
Location: net/core/filter.c:2447
Inline: False
```
**Symbols:**

```
ffffffff817e93e0-ffffffff817e9440: bpf_skb_event_output (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
u64 bpf_skb_event_output(u64 skb, u64 map, u64 flags, u64 meta, u64 meta_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff818648e0)
Location: net/core/filter.c:2845
Inline: False
```
**Symbols:**

```
ffffffff818648e0-ffffffff81864940: bpf_skb_event_output (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
u64 bpf_skb_event_output(u64 skb, u64 map, u64 flags, u64 meta, u64 meta_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff818b1aa0)
Location: net/core/filter.c:3464
Inline: False
```
**Symbols:**

```
ffffffff818b1aa0-ffffffff818b1aff: bpf_skb_event_output (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
u64 bpf_skb_event_output(u64 skb, u64 map, u64 flags, u64 meta, u64 meta_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff818d6490)
Location: net/core/filter.c:3652
Inline: False
```
**Symbols:**

```
ffffffff818d6490-ffffffff818d64ec: bpf_skb_event_output (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
u64 bpf_skb_event_output(u64 skb, u64 map, u64 flags, u64 meta, u64 meta_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81923d10)
Location: net/core/filter.c:3789
Inline: False
```
**Symbols:**

```
ffffffff81923d10-ffffffff81923d6d: bpf_skb_event_output (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
u64 bpf_skb_event_output(u64 skb, u64 map, u64 flags, u64 meta, u64 meta_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81956020)
Location: net/core/filter.c:3796
Inline: False
```
**Symbols:**

```
ffffffff81956020-ffffffff8195607d: bpf_skb_event_output (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
u64 bpf_skb_event_output(u64 skb, u64 map, u64 flags, u64 meta, u64 meta_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81a29a60)
Location: net/core/filter.c:3755
Inline: False
```
**Symbols:**

```
ffffffff81a29a60-ffffffff81a29ac2: bpf_skb_event_output (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
u64 bpf_skb_event_output(u64 skb, u64 map, u64 flags, u64 meta, u64 meta_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81a2a3c0)
Location: net/core/filter.c:4162
Inline: False
```
**Symbols:**

```
ffffffff81a2a3c0-ffffffff81a2a422: bpf_skb_event_output (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
u64 bpf_skb_event_output(u64 skb, u64 map, u64 flags, u64 meta, u64 meta_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81a11560)
Location: net/core/filter.c:4101
Inline: False
```
**Symbols:**

```
ffffffff81a11560-ffffffff81a115c3: bpf_skb_event_output (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
u64 bpf_skb_event_output(u64 skb, u64 map, u64 flags, u64 meta, u64 meta_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81ac2a40)
Location: net/core/filter.c:4159
Inline: False
```
**Symbols:**

```
ffffffff81ac2a40-ffffffff81ac2aa3: bpf_skb_event_output (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
u64 bpf_skb_event_output(u64 skb, u64 map, u64 flags, u64 meta, u64 meta_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81c3d650)
Location: net/core/filter.c:4440
Inline: False
```
**Symbols:**

```
ffffffff81c3d650-ffffffff81c3d6ec: bpf_skb_event_output (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
u64 bpf_skb_event_output(u64 skb, u64 map, u64 flags, u64 meta, u64 meta_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81df17f0)
Location: net/core/filter.c:4454
Inline: False
```
**Symbols:**

```
ffffffff81df17f0-ffffffff81df188c: bpf_skb_event_output (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
u64 bpf_skb_event_output(u64 skb, u64 map, u64 flags, u64 meta, u64 meta_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81e63780)
Location: net/core/filter.c:4505
Inline: False
```
**Symbols:**

```
ffffffff81e63780-ffffffff81e6381c: bpf_skb_event_output (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
u64 bpf_skb_event_output(u64 skb, u64 map, u64 flags, u64 meta, u64 meta_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81f22960)
Location: net/core/filter.c:4579
Inline: False
```
**Symbols:**

```
ffffffff81f22960-ffffffff81f229fc: bpf_skb_event_output (STB_GLOBAL)
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
u64 bpf_skb_event_output(u64 skb, u64 map, u64 flags, u64 meta, u64 meta_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffff800010bf7c70)
Location: net/core/filter.c:3796
Inline: False
```
**Symbols:**

```
ffff800010bf7c70-ffff800010bf7d0c: bpf_skb_event_output (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
u64 bpf_skb_event_output(u64 skb, u64 map, u64 flags, u64 meta, u64 meta_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (c0d115b4)
Location: net/core/filter.c:3796
Inline: False
```
**Symbols:**

```
c0d115b4-c0d1165c: bpf_skb_event_output (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
u64 bpf_skb_event_output(u64 skb, u64 map, u64 flags, u64 meta, u64 meta_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (c000000000cddf20)
Location: net/core/filter.c:3796
Inline: False
```
**Symbols:**

```
c000000000cddf20-c000000000cddfa8: bpf_skb_event_output (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
u64 bpf_skb_event_output(u64 skb, u64 map, u64 flags, u64 meta, u64 meta_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffe000779784)
Location: net/core/filter.c:3796
Inline: False
```
**Symbols:**

```
ffffffe000779784-ffffffe0007797f2: bpf_skb_event_output (STB_GLOBAL)
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
u64 bpf_skb_event_output(u64 skb, u64 map, u64 flags, u64 meta, u64 meta_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff818f5ff0)
Location: net/core/filter.c:3796
Inline: False
```
**Symbols:**

```
ffffffff818f5ff0-ffffffff818f604d: bpf_skb_event_output (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
u64 bpf_skb_event_output(u64 skb, u64 map, u64 flags, u64 meta, u64 meta_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff818afe20)
Location: net/core/filter.c:3796
Inline: False
```
**Symbols:**

```
ffffffff818afe20-ffffffff818afe7d: bpf_skb_event_output (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
u64 bpf_skb_event_output(u64 skb, u64 map, u64 flags, u64 meta, u64 meta_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81947020)
Location: net/core/filter.c:3796
Inline: False
```
**Symbols:**

```
ffffffff81947020-ffffffff8194707d: bpf_skb_event_output (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
u64 bpf_skb_event_output(u64 skb, u64 map, u64 flags, u64 meta, u64 meta_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81968930)
Location: net/core/filter.c:3796
Inline: False
```
**Symbols:**

```
ffffffff81968930-ffffffff8196898d: bpf_skb_event_output (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
<code>u64 map</code>
</li>
<li>
<b>Param added. </b>
<code>u64 meta</code>
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
