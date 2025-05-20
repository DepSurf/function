# Function: <code>bpf_flow_dissect</code>

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
bool bpf_flow_dissect(struct bpf_prog *prog, struct bpf_flow_dissector *ctx, __be16 proto, int nhoff, int hlen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/flow_dissector.c (ffffffff818f5100)
Location: net/core/flow_dissector.c:786
Inline: False
Direct callers:
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/bpf/test_run.c:bpf_prog_test_run_flow_dissector
```
**Symbols:**

```
ffffffff818f5100-ffffffff818f5205: bpf_flow_dissect (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
bool bpf_flow_dissect(struct bpf_prog *prog, struct bpf_flow_dissector *ctx, __be16 proto, int nhoff, int hlen, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/flow_dissector.c (ffffffff81926fd0)
Location: net/core/flow_dissector.c:827
Inline: False
Direct callers:
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/bpf/test_run.c:bpf_prog_test_run_flow_dissector
```
**Symbols:**

```
ffffffff81926fd0-ffffffff819270da: bpf_flow_dissect (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
bool bpf_flow_dissect(struct bpf_prog *prog, struct bpf_flow_dissector *ctx, __be16 proto, int nhoff, int hlen, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/flow_dissector.c (ffffffff819fb470)
Location: net/core/flow_dissector.c:837
Inline: False
Direct callers:
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/bpf/test_run.c:bpf_prog_test_run_flow_dissector
```
**Symbols:**

```
ffffffff819fb470-ffffffff819fb57d: bpf_flow_dissect (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
bool bpf_flow_dissect(struct bpf_prog *prog, struct bpf_flow_dissector *ctx, __be16 proto, int nhoff, int hlen, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/flow_dissector.c (ffffffff819fb070)
Location: net/core/flow_dissector.c:854
Inline: False
Direct callers:
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/bpf/test_run.c:bpf_prog_test_run_flow_dissector
```
**Symbols:**

```
ffffffff819fb070-ffffffff819fb17a: bpf_flow_dissect (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
bool bpf_flow_dissect(struct bpf_prog *prog, struct bpf_flow_dissector *ctx, __be16 proto, int nhoff, int hlen, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/flow_dissector.c (ffffffff819e1290)
Location: net/core/flow_dissector.c:866
Inline: False
Direct callers:
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/bpf/test_run.c:bpf_prog_test_run_flow_dissector
```
**Symbols:**

```
ffffffff819e1290-ffffffff819e139b: bpf_flow_dissect (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
bool bpf_flow_dissect(struct bpf_prog *prog, struct bpf_flow_dissector *ctx, __be16 proto, int nhoff, int hlen, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/flow_dissector.c (ffffffff81a916d0)
Location: net/core/flow_dissector.c:867
Inline: False
Direct callers:
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/bpf/test_run.c:bpf_prog_test_run_flow_dissector
```
**Symbols:**

```
ffffffff81a916d0-ffffffff81a917d7: bpf_flow_dissect (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
bool bpf_flow_dissect(struct bpf_prog *prog, struct bpf_flow_dissector *ctx, __be16 proto, int nhoff, int hlen, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/flow_dissector.c (ffffffff81c07860)
Location: net/core/flow_dissector.c:869
Inline: False
Direct callers:
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/bpf/test_run.c:bpf_prog_test_run_flow_dissector
```
**Symbols:**

```
ffffffff81c07860-ffffffff81c0797d: bpf_flow_dissect (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
u32 bpf_flow_dissect(struct bpf_prog *prog, struct bpf_flow_dissector *ctx, __be16 proto, int nhoff, int hlen, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/flow_dissector.c (ffffffff81db72f0)
Location: net/core/flow_dissector.c:893
Inline: False
Direct callers:
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/bpf/test_run.c:bpf_prog_test_run_flow_dissector
```
**Symbols:**

```
ffffffff81db72f0-ffffffff81db7404: bpf_flow_dissect (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
u32 bpf_flow_dissect(struct bpf_prog *prog, struct bpf_flow_dissector *ctx, __be16 proto, int nhoff, int hlen, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/flow_dissector.c (ffffffff81e279b0)
Location: net/core/flow_dissector.c:927
Inline: False
Direct callers:
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/bpf/test_run.c:bpf_prog_test_run_flow_dissector
```
**Symbols:**

```
ffffffff81e279b0-ffffffff81e27ac4: bpf_flow_dissect (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
u32 bpf_flow_dissect(struct bpf_prog *prog, struct bpf_flow_dissector *ctx, __be16 proto, int nhoff, int hlen, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/flow_dissector.c (ffffffff81ee5960)
Location: net/core/flow_dissector.c:971
Inline: False
Direct callers:
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/bpf/test_run.c:bpf_prog_test_run_flow_dissector
```
**Symbols:**

```
ffffffff81ee5960-ffffffff81ee5a74: bpf_flow_dissect (STB_GLOBAL)
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
bool bpf_flow_dissect(struct bpf_prog *prog, struct bpf_flow_dissector *ctx, __be16 proto, int nhoff, int hlen, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/flow_dissector.c (ffff800010bc3560)
Location: net/core/flow_dissector.c:827
Inline: False
Direct callers:
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/bpf/test_run.c:bpf_prog_test_run_flow_dissector
```
**Symbols:**

```
ffff800010bc3560-ffff800010bc3680: bpf_flow_dissect (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
bool bpf_flow_dissect(struct bpf_prog *prog, struct bpf_flow_dissector *ctx, __be16 proto, int nhoff, int hlen, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/flow_dissector.c (c0cde7f8)
Location: net/core/flow_dissector.c:827
Inline: False
Direct callers:
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/bpf/test_run.c:bpf_prog_test_run_flow_dissector
```
**Symbols:**

```
c0cde7f8-c0cde948: bpf_flow_dissect (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
bool bpf_flow_dissect(struct bpf_prog *prog, struct bpf_flow_dissector *ctx, __be16 proto, int nhoff, int hlen, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/flow_dissector.c (c000000000c9d610)
Location: net/core/flow_dissector.c:827
Inline: False
Direct callers:
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/bpf/test_run.c:bpf_prog_test_run_flow_dissector
```
**Symbols:**

```
c000000000c9d610-c000000000c9d79c: bpf_flow_dissect (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
bool bpf_flow_dissect(struct bpf_prog *prog, struct bpf_flow_dissector *ctx, __be16 proto, int nhoff, int hlen, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/flow_dissector.c (ffffffe00074ffe0)
Location: net/core/flow_dissector.c:827
Inline: False
Direct callers:
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/bpf/test_run.c:bpf_prog_test_run_flow_dissector
```
**Symbols:**

```
ffffffe00074ffe0-ffffffe000750124: bpf_flow_dissect (STB_GLOBAL)
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
bool bpf_flow_dissect(struct bpf_prog *prog, struct bpf_flow_dissector *ctx, __be16 proto, int nhoff, int hlen, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/flow_dissector.c (ffffffff818c6fd0)
Location: net/core/flow_dissector.c:827
Inline: False
Direct callers:
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/bpf/test_run.c:bpf_prog_test_run_flow_dissector
```
**Symbols:**

```
ffffffff818c6fd0-ffffffff818c70da: bpf_flow_dissect (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
bool bpf_flow_dissect(struct bpf_prog *prog, struct bpf_flow_dissector *ctx, __be16 proto, int nhoff, int hlen, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/flow_dissector.c (ffffffff81880f10)
Location: net/core/flow_dissector.c:827
Inline: False
Direct callers:
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/bpf/test_run.c:bpf_prog_test_run_flow_dissector
```
**Symbols:**

```
ffffffff81880f10-ffffffff8188101a: bpf_flow_dissect (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
bool bpf_flow_dissect(struct bpf_prog *prog, struct bpf_flow_dissector *ctx, __be16 proto, int nhoff, int hlen, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/flow_dissector.c (ffffffff81917fd0)
Location: net/core/flow_dissector.c:827
Inline: False
Direct callers:
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/bpf/test_run.c:bpf_prog_test_run_flow_dissector
```
**Symbols:**

```
ffffffff81917fd0-ffffffff819180da: bpf_flow_dissect (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
bool bpf_flow_dissect(struct bpf_prog *prog, struct bpf_flow_dissector *ctx, __be16 proto, int nhoff, int hlen, unsigned int flags);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/flow_dissector.c (ffffffff81939200)
Location: net/core/flow_dissector.c:827
Inline: False
Direct callers:
  - net/core/flow_dissector.c:__skb_flow_dissect
  - net/bpf/test_run.c:bpf_prog_test_run_flow_dissector
```
**Symbols:**

```
ffffffff81939200-ffffffff81939328: bpf_flow_dissect (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Changed between <code>5.3</code> and <code>5.4</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>unsigned int flags</code>
</li>
</ul>
</details>
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
<details>
<summary>Changed between <code>5.19</code> and <code>6.2</code> ⚠️</summary>
<ul>
<li>
<b>Return type changed. </b>
<code>bool</code> ➡️ <code>u32</code>
</li>
</ul>
</details>
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
