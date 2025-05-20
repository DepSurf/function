# Function: <code>bpf_internal_load_pointer_neg_helper</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
void *bpf_internal_load_pointer_neg_helper(const struct sk_buff *skb, int k, unsigned int size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff81171280)
Location: kernel/bpf/core.c:58
Inline: True
Inline callers:
  - kernel/bpf/core.c:__bpf_prog_run
  - kernel/bpf/core.c:__bpf_prog_run
  - kernel/bpf/core.c:__bpf_prog_run
```
**Symbols:**

```
ffffffff81171280-ffffffff811712f6: bpf_internal_load_pointer_neg_helper (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void *bpf_internal_load_pointer_neg_helper(const struct sk_buff *skb, int k, unsigned int size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff811802ec)
Location: kernel/bpf/core.c:59
Inline: True
Inline callers:
  - kernel/bpf/core.c:__bpf_prog_run
  - kernel/bpf/core.c:__bpf_prog_run
  - kernel/bpf/core.c:__bpf_prog_run
```
**Symbols:**

```
ffffffff8117e890-ffffffff8117e906: bpf_internal_load_pointer_neg_helper (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void *bpf_internal_load_pointer_neg_helper(const struct sk_buff *skb, int k, unsigned int size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff8118c15c)
Location: kernel/bpf/core.c:59
Inline: True
Inline callers:
  - kernel/bpf/core.c:__bpf_prog_run
  - kernel/bpf/core.c:__bpf_prog_run
  - kernel/bpf/core.c:__bpf_prog_run
```
**Symbols:**

```
ffffffff8118a4a0-ffffffff8118a516: bpf_internal_load_pointer_neg_helper (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void *bpf_internal_load_pointer_neg_helper(const struct sk_buff *skb, int k, unsigned int size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff8118fdd6)
Location: kernel/bpf/core.c:62
Inline: True
Inline callers:
  - kernel/bpf/core.c:___bpf_prog_run
  - kernel/bpf/core.c:___bpf_prog_run
  - kernel/bpf/core.c:___bpf_prog_run
```
**Symbols:**

```
ffffffff8118ebe0-ffffffff8118ec53: bpf_internal_load_pointer_neg_helper (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void *bpf_internal_load_pointer_neg_helper(const struct sk_buff *skb, int k, unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff8119d050)
Location: kernel/bpf/core.c:62
Inline: False
```
**Symbols:**

```
ffffffff8119d050-ffffffff8119d0c3: bpf_internal_load_pointer_neg_helper (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void *bpf_internal_load_pointer_neg_helper(const struct sk_buff *skb, int k, unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff811b1780)
Location: kernel/bpf/core.c:63
Inline: False
Direct callers:
  - net/core/filter.c:bpf_skb_load_helper_32_no_cache
  - net/core/filter.c:bpf_skb_load_helper_32
  - net/core/filter.c:bpf_skb_load_helper_16_no_cache
  - net/core/filter.c:bpf_skb_load_helper_16
  - net/core/filter.c:bpf_skb_load_helper_8_no_cache
  - net/core/filter.c:bpf_skb_load_helper_8
```
**Symbols:**

```
ffffffff811b1780-ffffffff811b17f6: bpf_internal_load_pointer_neg_helper (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void *bpf_internal_load_pointer_neg_helper(const struct sk_buff *skb, int k, unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff811bfe10)
Location: kernel/bpf/core.c:66
Inline: False
Direct callers:
  - net/core/filter.c:bpf_skb_load_helper_32_no_cache
  - net/core/filter.c:bpf_skb_load_helper_32
  - net/core/filter.c:bpf_skb_load_helper_16_no_cache
  - net/core/filter.c:bpf_skb_load_helper_16
  - net/core/filter.c:bpf_skb_load_helper_8_no_cache
  - net/core/filter.c:bpf_skb_load_helper_8
```
**Symbols:**

```
ffffffff811bfe10-ffffffff811bfe86: bpf_internal_load_pointer_neg_helper (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void *bpf_internal_load_pointer_neg_helper(const struct sk_buff *skb, int k, unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff811d0640)
Location: kernel/bpf/core.c:62
Inline: False
Direct callers:
  - net/core/filter.c:bpf_skb_load_helper_32_no_cache
  - net/core/filter.c:bpf_skb_load_helper_32
  - net/core/filter.c:bpf_skb_load_helper_16_no_cache
  - net/core/filter.c:bpf_skb_load_helper_16
  - net/core/filter.c:bpf_skb_load_helper_8_no_cache
  - net/core/filter.c:bpf_skb_load_helper_8
```
**Symbols:**

```
ffffffff811d0640-ffffffff811d06b6: bpf_internal_load_pointer_neg_helper (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void *bpf_internal_load_pointer_neg_helper(const struct sk_buff *skb, int k, unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff811dcbd0)
Location: kernel/bpf/core.c:62
Inline: False
Direct callers:
  - net/core/filter.c:bpf_skb_load_helper_32_no_cache
  - net/core/filter.c:bpf_skb_load_helper_32
  - net/core/filter.c:bpf_skb_load_helper_16_no_cache
  - net/core/filter.c:bpf_skb_load_helper_16
  - net/core/filter.c:bpf_skb_load_helper_8_no_cache
  - net/core/filter.c:bpf_skb_load_helper_8
```
**Symbols:**

```
ffffffff811dcbd0-ffffffff811dcc46: bpf_internal_load_pointer_neg_helper (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void *bpf_internal_load_pointer_neg_helper(const struct sk_buff *skb, int k, unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff811f95f0)
Location: kernel/bpf/core.c:63
Inline: False
Direct callers:
  - net/core/filter.c:bpf_skb_load_helper_32_no_cache
  - net/core/filter.c:bpf_skb_load_helper_32
  - net/core/filter.c:bpf_skb_load_helper_16_no_cache
  - net/core/filter.c:bpf_skb_load_helper_16
  - net/core/filter.c:bpf_skb_load_helper_8_no_cache
  - net/core/filter.c:bpf_skb_load_helper_8
```
**Symbols:**

```
ffffffff811f95f0-ffffffff811f9666: bpf_internal_load_pointer_neg_helper (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void *bpf_internal_load_pointer_neg_helper(const struct sk_buff *skb, int k, unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff811f8630)
Location: kernel/bpf/core.c:63
Inline: False
Direct callers:
  - net/core/filter.c:bpf_skb_load_helper_32_no_cache
  - net/core/filter.c:bpf_skb_load_helper_32
  - net/core/filter.c:bpf_skb_load_helper_16_no_cache
  - net/core/filter.c:bpf_skb_load_helper_16
  - net/core/filter.c:bpf_skb_load_helper_8_no_cache
  - net/core/filter.c:bpf_skb_load_helper_8
```
**Symbols:**

```
ffffffff811f8630-ffffffff811f86a6: bpf_internal_load_pointer_neg_helper (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void *bpf_internal_load_pointer_neg_helper(const struct sk_buff *skb, int k, unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff811f9420)
Location: kernel/bpf/core.c:65
Inline: False
Direct callers:
  - net/core/filter.c:bpf_skb_load_helper_32_no_cache
  - net/core/filter.c:bpf_skb_load_helper_32
  - net/core/filter.c:bpf_skb_load_helper_16_no_cache
  - net/core/filter.c:bpf_skb_load_helper_16
  - net/core/filter.c:bpf_skb_load_helper_8_no_cache
  - net/core/filter.c:bpf_skb_load_helper_8
```
**Symbols:**

```
ffffffff811f9420-ffffffff811f949b: bpf_internal_load_pointer_neg_helper (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void *bpf_internal_load_pointer_neg_helper(const struct sk_buff *skb, int k, unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff8122aab0)
Location: kernel/bpf/core.c:65
Inline: False
Direct callers:
  - net/core/filter.c:bpf_skb_load_helper_32_no_cache
  - net/core/filter.c:bpf_skb_load_helper_32
  - net/core/filter.c:bpf_skb_load_helper_16_no_cache
  - net/core/filter.c:bpf_skb_load_helper_16
  - net/core/filter.c:bpf_skb_load_helper_8_no_cache
  - net/core/filter.c:bpf_skb_load_helper_8
```
**Symbols:**

```
ffffffff8122aab0-ffffffff8122ab2b: bpf_internal_load_pointer_neg_helper (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void *bpf_internal_load_pointer_neg_helper(const struct sk_buff *skb, int k, unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff8126c3b0)
Location: kernel/bpf/core.c:67
Inline: False
Direct callers:
  - net/core/filter.c:bpf_skb_load_helper_32_no_cache
  - net/core/filter.c:bpf_skb_load_helper_32
  - net/core/filter.c:bpf_skb_load_helper_16_no_cache
  - net/core/filter.c:bpf_skb_load_helper_16
  - net/core/filter.c:bpf_skb_load_helper_8_no_cache
  - net/core/filter.c:bpf_skb_load_helper_8
```
**Symbols:**

```
ffffffff8126c3b0-ffffffff8126c45f: bpf_internal_load_pointer_neg_helper (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void *bpf_internal_load_pointer_neg_helper(const struct sk_buff *skb, int k, unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff812c13d0)
Location: kernel/bpf/core.c:72
Inline: False
Direct callers:
  - net/core/filter.c:bpf_skb_load_helper_32_no_cache
  - net/core/filter.c:bpf_skb_load_helper_32
  - net/core/filter.c:bpf_skb_load_helper_16_no_cache
  - net/core/filter.c:bpf_skb_load_helper_16
  - net/core/filter.c:bpf_skb_load_helper_8_no_cache
  - net/core/filter.c:bpf_skb_load_helper_8
```
**Symbols:**

```
ffffffff812c13d0-ffffffff812c147f: bpf_internal_load_pointer_neg_helper (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void *bpf_internal_load_pointer_neg_helper(const struct sk_buff *skb, int k, unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff812e81a0)
Location: kernel/bpf/core.c:73
Inline: False
Direct callers:
  - net/core/filter.c:bpf_skb_load_helper_32_no_cache
  - net/core/filter.c:bpf_skb_load_helper_32
  - net/core/filter.c:bpf_skb_load_helper_16_no_cache
  - net/core/filter.c:bpf_skb_load_helper_16
  - net/core/filter.c:bpf_skb_load_helper_8_no_cache
  - net/core/filter.c:bpf_skb_load_helper_8
```
**Symbols:**

```
ffffffff812e81a0-ffffffff812e8247: bpf_internal_load_pointer_neg_helper (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void *bpf_internal_load_pointer_neg_helper(const struct sk_buff *skb, int k, unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff813064f0)
Location: kernel/bpf/core.c:74
Inline: False
Direct callers:
  - net/core/filter.c:bpf_skb_load_helper_32_no_cache
  - net/core/filter.c:bpf_skb_load_helper_32
  - net/core/filter.c:bpf_skb_load_helper_16_no_cache
  - net/core/filter.c:bpf_skb_load_helper_16
  - net/core/filter.c:bpf_skb_load_helper_8_no_cache
  - net/core/filter.c:bpf_skb_load_helper_8
```
**Symbols:**

```
ffffffff813064f0-ffffffff81306597: bpf_internal_load_pointer_neg_helper (STB_GLOBAL)
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
void *bpf_internal_load_pointer_neg_helper(const struct sk_buff *skb, int k, unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffff80001025d560)
Location: kernel/bpf/core.c:62
Inline: False
Direct callers:
  - net/core/filter.c:bpf_skb_load_helper_32_no_cache
  - net/core/filter.c:bpf_skb_load_helper_32
  - net/core/filter.c:bpf_skb_load_helper_16_no_cache
  - net/core/filter.c:bpf_skb_load_helper_16
  - net/core/filter.c:bpf_skb_load_helper_8_no_cache
  - net/core/filter.c:bpf_skb_load_helper_8
```
**Symbols:**

```
ffff80001025d560-ffff80001025d604: bpf_internal_load_pointer_neg_helper (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void *bpf_internal_load_pointer_neg_helper(const struct sk_buff *skb, int k, unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (c0490e10)
Location: kernel/bpf/core.c:62
Inline: False
Direct callers:
  - net/core/filter.c:bpf_skb_load_helper_32_no_cache
  - net/core/filter.c:bpf_skb_load_helper_32
  - net/core/filter.c:bpf_skb_load_helper_16_no_cache
  - net/core/filter.c:bpf_skb_load_helper_16
  - net/core/filter.c:bpf_skb_load_helper_8_no_cache
  - net/core/filter.c:bpf_skb_load_helper_8
```
**Symbols:**

```
c0490e10-c0490e88: bpf_internal_load_pointer_neg_helper (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void *bpf_internal_load_pointer_neg_helper(const struct sk_buff *skb, int k, unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (c000000000301fb0)
Location: kernel/bpf/core.c:62
Inline: False
Direct callers:
  - net/core/filter.c:bpf_skb_load_helper_32_no_cache
  - net/core/filter.c:bpf_skb_load_helper_32
  - net/core/filter.c:bpf_skb_load_helper_16_no_cache
  - net/core/filter.c:bpf_skb_load_helper_16
  - net/core/filter.c:bpf_skb_load_helper_8_no_cache
  - net/core/filter.c:bpf_skb_load_helper_8
```
**Symbols:**

```
c000000000301fb0-c000000000302030: bpf_internal_load_pointer_neg_helper (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void *bpf_internal_load_pointer_neg_helper(const struct sk_buff *skb, int k, unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffe00019bbf6)
Location: kernel/bpf/core.c:62
Inline: False
Direct callers:
  - net/core/filter.c:bpf_skb_load_helper_32_no_cache
  - net/core/filter.c:bpf_skb_load_helper_32
  - net/core/filter.c:bpf_skb_load_helper_16_no_cache
  - net/core/filter.c:bpf_skb_load_helper_16
  - net/core/filter.c:bpf_skb_load_helper_8_no_cache
  - net/core/filter.c:bpf_skb_load_helper_8
```
**Symbols:**

```
ffffffe00019bbf6-ffffffe00019bc82: bpf_internal_load_pointer_neg_helper (STB_GLOBAL)
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
void *bpf_internal_load_pointer_neg_helper(const struct sk_buff *skb, int k, unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff811d51f0)
Location: kernel/bpf/core.c:62
Inline: False
Direct callers:
  - net/core/filter.c:bpf_skb_load_helper_32_no_cache
  - net/core/filter.c:bpf_skb_load_helper_32
  - net/core/filter.c:bpf_skb_load_helper_16_no_cache
  - net/core/filter.c:bpf_skb_load_helper_16
  - net/core/filter.c:bpf_skb_load_helper_8_no_cache
  - net/core/filter.c:bpf_skb_load_helper_8
```
**Symbols:**

```
ffffffff811d51f0-ffffffff811d5266: bpf_internal_load_pointer_neg_helper (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void *bpf_internal_load_pointer_neg_helper(const struct sk_buff *skb, int k, unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff811c7fb0)
Location: kernel/bpf/core.c:62
Inline: False
Direct callers:
  - net/core/filter.c:bpf_skb_load_helper_32_no_cache
  - net/core/filter.c:bpf_skb_load_helper_32
  - net/core/filter.c:bpf_skb_load_helper_16_no_cache
  - net/core/filter.c:bpf_skb_load_helper_16
  - net/core/filter.c:bpf_skb_load_helper_8_no_cache
  - net/core/filter.c:bpf_skb_load_helper_8
```
**Symbols:**

```
ffffffff811c7fb0-ffffffff811c8026: bpf_internal_load_pointer_neg_helper (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void *bpf_internal_load_pointer_neg_helper(const struct sk_buff *skb, int k, unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff811d2fc0)
Location: kernel/bpf/core.c:62
Inline: False
Direct callers:
  - net/core/filter.c:bpf_skb_load_helper_32_no_cache
  - net/core/filter.c:bpf_skb_load_helper_32
  - net/core/filter.c:bpf_skb_load_helper_16_no_cache
  - net/core/filter.c:bpf_skb_load_helper_16
  - net/core/filter.c:bpf_skb_load_helper_8_no_cache
  - net/core/filter.c:bpf_skb_load_helper_8
```
**Symbols:**

```
ffffffff811d2fc0-ffffffff811d3036: bpf_internal_load_pointer_neg_helper (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void *bpf_internal_load_pointer_neg_helper(const struct sk_buff *skb, int k, unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff811e12b0)
Location: kernel/bpf/core.c:62
Inline: False
Direct callers:
  - net/core/filter.c:bpf_skb_load_helper_32_no_cache
  - net/core/filter.c:bpf_skb_load_helper_32
  - net/core/filter.c:bpf_skb_load_helper_16_no_cache
  - net/core/filter.c:bpf_skb_load_helper_16
  - net/core/filter.c:bpf_skb_load_helper_8_no_cache
  - net/core/filter.c:bpf_skb_load_helper_8
```
**Symbols:**

```
ffffffff811e12b0-ffffffff811e1326: bpf_internal_load_pointer_neg_helper (STB_GLOBAL)
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
