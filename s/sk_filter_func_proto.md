# Function: <code>sk_filter_func_proto</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
const struct bpf_func_proto *sk_filter_func_proto(enum bpf_func_id func_id);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81732520)
Location: net/core/filter.c:1631
Inline: True
Direct callers:
  - net/core/filter.c:tc_cls_act_func_proto
```
**Symbols:**

```
ffffffff81732520-ffffffff8173258b: sk_filter_func_proto (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
const struct bpf_func_proto *sk_filter_func_proto(enum bpf_func_id func_id);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff8179d3a0)
Location: net/core/filter.c:2320
Inline: True
Direct callers:
  - net/core/filter.c:xdp_func_proto
  - net/core/filter.c:tc_cls_act_func_proto
```
**Symbols:**

```
ffffffff8179d3a0-ffffffff8179d40b: sk_filter_func_proto (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
const struct bpf_func_proto *sk_filter_func_proto(enum bpf_func_id func_id);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff817cafd0)
Location: net/core/filter.c:2601
Inline: True
Direct callers:
  - net/core/filter.c:lwt_inout_func_proto
  - net/core/filter.c:cg_skb_func_proto
  - net/core/filter.c:xdp_func_proto
  - net/core/filter.c:tc_cls_act_func_proto
```
**Symbols:**

```
ffffffff817cafd0-ffffffff817cb043: sk_filter_func_proto (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
const struct bpf_func_proto *sk_filter_func_proto(enum bpf_func_id func_id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff817ea1f0)
Location: net/core/filter.c:2919
Inline: False
```
**Symbols:**

```
ffffffff817ea1f0-ffffffff817ea226: sk_filter_func_proto (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
const struct bpf_func_proto *sk_filter_func_proto(enum bpf_func_id func_id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81865880)
Location: net/core/filter.c:3373
Inline: False
```
**Symbols:**

```
ffffffff81865880-ffffffff818658b6: sk_filter_func_proto (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
const struct bpf_func_proto *sk_filter_func_proto(enum bpf_func_id func_id, const struct bpf_prog *prog);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff818b3360)
Location: net/core/filter.c:4798
Inline: False
```
**Symbols:**

```
ffffffff818b3360-ffffffff818b33a3: sk_filter_func_proto (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
const struct bpf_func_proto *sk_filter_func_proto(enum bpf_func_id func_id, const struct bpf_prog *prog);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff818d8220)
Location: net/core/filter.c:5375
Inline: False
Direct callers:
  - net/core/filter.c:cg_skb_func_proto
```
**Symbols:**

```
ffffffff818d8220-ffffffff818d8263: sk_filter_func_proto (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
const struct bpf_func_proto *sk_filter_func_proto(enum bpf_func_id func_id, const struct bpf_prog *prog);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff819260d0)
Location: net/core/filter.c:5991
Inline: False
Direct callers:
  - net/core/filter.c:cg_skb_func_proto
```
**Symbols:**

```
ffffffff819260d0-ffffffff81926115: sk_filter_func_proto (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
const struct bpf_func_proto *sk_filter_func_proto(enum bpf_func_id func_id, const struct bpf_prog *prog);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81958730)
Location: net/core/filter.c:6068
Inline: False
Direct callers:
  - net/core/filter.c:cg_skb_func_proto
```
**Symbols:**

```
ffffffff81958730-ffffffff81958782: sk_filter_func_proto (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
const struct bpf_func_proto *sk_filter_func_proto(enum bpf_func_id func_id, const struct bpf_prog *prog);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81a30b0e)
Location: net/core/filter.c:6239
Inline: True
Inline callers:
  - net/core/filter.c:cg_skb_func_proto
```
**Symbols:**

```
ffffffff81a2a7b0-ffffffff81a2a802: sk_filter_func_proto (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
const struct bpf_func_proto *sk_filter_func_proto(enum bpf_func_id func_id, const struct bpf_prog *prog);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81a32e0e)
Location: net/core/filter.c:7028
Inline: True
Inline callers:
  - net/core/filter.c:cg_skb_func_proto
```
**Symbols:**

```
ffffffff81a2b560-ffffffff81a2b5b2: sk_filter_func_proto (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
const struct bpf_func_proto *sk_filter_func_proto(enum bpf_func_id func_id, const struct bpf_prog *prog);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81a19e6e)
Location: net/core/filter.c:7146
Inline: True
Inline callers:
  - net/core/filter.c:cg_skb_func_proto
```
**Symbols:**

```
ffffffff81a12a30-ffffffff81a12a82: sk_filter_func_proto (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
const struct bpf_func_proto *sk_filter_func_proto(enum bpf_func_id func_id, const struct bpf_prog *prog);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81acc29e)
Location: net/core/filter.c:7272
Inline: True
Inline callers:
  - net/core/filter.c:cg_skb_func_proto
```
**Symbols:**

```
ffffffff81ac35d0-ffffffff81ac3622: sk_filter_func_proto (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
const struct bpf_func_proto *sk_filter_func_proto(enum bpf_func_id func_id, const struct bpf_prog *prog);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81c48f1d)
Location: net/core/filter.c:7648
Inline: True
Inline callers:
  - net/core/filter.c:cg_skb_func_proto
```
**Symbols:**

```
ffffffff81c3e4b0-ffffffff81c3e520: sk_filter_func_proto (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
const struct bpf_func_proto *sk_filter_func_proto(enum bpf_func_id func_id, const struct bpf_prog *prog);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81df2790)
Location: net/core/filter.c:7746
Inline: True
```
**Symbols:**

```
ffffffff81df2790-ffffffff81df2800: sk_filter_func_proto (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
const struct bpf_func_proto *sk_filter_func_proto(enum bpf_func_id func_id, const struct bpf_prog *prog);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81e64710)
Location: net/core/filter.c:7904
Inline: True
```
**Symbols:**

```
ffffffff81e64710-ffffffff81e64772: sk_filter_func_proto (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
const struct bpf_func_proto *sk_filter_func_proto(enum bpf_func_id func_id, const struct bpf_prog *prog);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81f238c0)
Location: net/core/filter.c:7995
Inline: True
```
**Symbols:**

```
ffffffff81f238c0-ffffffff81f23922: sk_filter_func_proto (STB_LOCAL)
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
const struct bpf_func_proto *sk_filter_func_proto(enum bpf_func_id func_id, const struct bpf_prog *prog);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffff800010bf99a0)
Location: net/core/filter.c:6068
Inline: False
Direct callers:
  - net/core/filter.c:cg_skb_func_proto
```
**Symbols:**

```
ffff800010bf99a0-ffff800010bf9a50: sk_filter_func_proto (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
const struct bpf_func_proto *sk_filter_func_proto(enum bpf_func_id func_id, const struct bpf_prog *prog);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (c0d1329c)
Location: net/core/filter.c:6068
Inline: False
Direct callers:
  - net/core/filter.c:cg_skb_func_proto
```
**Symbols:**

```
c0d1329c-c0d13378: sk_filter_func_proto (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
const struct bpf_func_proto *sk_filter_func_proto(enum bpf_func_id func_id, const struct bpf_prog *prog);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (c000000000ce1360)
Location: net/core/filter.c:6068
Inline: False
Direct callers:
  - net/core/filter.c:cg_skb_func_proto
```
**Symbols:**

```
c000000000ce1360-c000000000ce13ec: sk_filter_func_proto (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
const struct bpf_func_proto *sk_filter_func_proto(enum bpf_func_id func_id, const struct bpf_prog *prog);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffe00077b7e0)
Location: net/core/filter.c:6068
Inline: False
Direct callers:
  - net/core/filter.c:cg_skb_func_proto
```
**Symbols:**

```
ffffffe00077b7e0-ffffffe00077b86e: sk_filter_func_proto (STB_LOCAL)
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
const struct bpf_func_proto *sk_filter_func_proto(enum bpf_func_id func_id, const struct bpf_prog *prog);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff818f8700)
Location: net/core/filter.c:6068
Inline: False
Direct callers:
  - net/core/filter.c:cg_skb_func_proto
```
**Symbols:**

```
ffffffff818f8700-ffffffff818f8752: sk_filter_func_proto (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
const struct bpf_func_proto *sk_filter_func_proto(enum bpf_func_id func_id, const struct bpf_prog *prog);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff818b2530)
Location: net/core/filter.c:6068
Inline: False
Direct callers:
  - net/core/filter.c:cg_skb_func_proto
```
**Symbols:**

```
ffffffff818b2530-ffffffff818b2582: sk_filter_func_proto (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
const struct bpf_func_proto *sk_filter_func_proto(enum bpf_func_id func_id, const struct bpf_prog *prog);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff81949730)
Location: net/core/filter.c:6068
Inline: False
Direct callers:
  - net/core/filter.c:cg_skb_func_proto
```
**Symbols:**

```
ffffffff81949730-ffffffff81949782: sk_filter_func_proto (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
const struct bpf_func_proto *sk_filter_func_proto(enum bpf_func_id func_id, const struct bpf_prog *prog);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/filter.c (ffffffff8196b040)
Location: net/core/filter.c:6068
Inline: False
Direct callers:
  - net/core/filter.c:cg_skb_func_proto
```
**Symbols:**

```
ffffffff8196b040-ffffffff8196b092: sk_filter_func_proto (STB_LOCAL)
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
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>4.15</code> and <code>4.18</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>const struct bpf_prog *prog</code>
</li>
</ul>
</details>
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
