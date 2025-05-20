# Function: <code>build_skb_around</code>

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
struct sk_buff *build_skb_around(struct sk_buff *skb, void *data, unsigned int frag_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff818e5970)
Location: net/core/skbuff.c:343
Inline: False
Direct callers:
  - kernel/bpf/cpumap.c:cpu_map_kthread_run
```
**Symbols:**

```
ffffffff818e5970-ffffffff818e59f4: build_skb_around (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct sk_buff *build_skb_around(struct sk_buff *skb, void *data, unsigned int frag_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff81917ac0)
Location: net/core/skbuff.c:343
Inline: False
Direct callers:
  - kernel/bpf/cpumap.c:cpu_map_kthread_run
```
**Symbols:**

```
ffffffff81917ac0-ffffffff81917b44: build_skb_around (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct sk_buff *build_skb_around(struct sk_buff *skb, void *data, unsigned int frag_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff819eba50)
Location: net/core/skbuff.c:344
Inline: False
```
**Symbols:**

```
ffffffff819eba50-ffffffff819ebad4: build_skb_around (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct sk_buff *build_skb_around(struct sk_buff *skb, void *data, unsigned int frag_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff819eb8f0)
Location: net/core/skbuff.c:349
Inline: False
Direct callers:
  - kernel/bpf/cpumap.c:cpu_map_build_skb
```
**Symbols:**

```
ffffffff819eb8f0-ffffffff819eb974: build_skb_around (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
struct sk_buff *build_skb_around(struct sk_buff *skb, void *data, unsigned int frag_size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff819d2400)
Location: net/core/skbuff.c:273
Inline: True
Direct callers:
  - net/core/xdp.c:__xdp_build_skb_from_frame
```
**Symbols:**

```
ffffffff819d2400-ffffffff819d248e: build_skb_around (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
struct sk_buff *build_skb_around(struct sk_buff *skb, void *data, unsigned int frag_size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff81a82080)
Location: net/core/skbuff.c:275
Inline: True
Direct callers:
  - net/core/xdp.c:__xdp_build_skb_from_frame
```
**Symbols:**

```
ffffffff81a82080-ffffffff81a8210d: build_skb_around (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct sk_buff *build_skb_around(struct sk_buff *skb, void *data, unsigned int frag_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff81bf67a0)
Location: net/core/skbuff.c:273
Inline: False
Direct callers:
  - net/core/xdp.c:__xdp_build_skb_from_frame
```
**Symbols:**

```
ffffffff81bf67a0-ffffffff81bf6883: build_skb_around (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct sk_buff *build_skb_around(struct sk_buff *skb, void *data, unsigned int frag_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff81da5aa0)
Location: net/core/skbuff.c:411
Inline: False
Direct callers:
  - net/core/xdp.c:__xdp_build_skb_from_frame
```
**Symbols:**

```
ffffffff81da5aa0-ffffffff81da5b83: build_skb_around (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct sk_buff *build_skb_around(struct sk_buff *skb, void *data, unsigned int frag_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff81e14640)
Location: net/core/skbuff.c:479
Inline: False
Direct callers:
  - net/core/xdp.c:__xdp_build_skb_from_frame
```
**Symbols:**

```
ffffffff81e14640-ffffffff81e14723: build_skb_around (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct sk_buff *build_skb_around(struct sk_buff *skb, void *data, unsigned int frag_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff81ed1d20)
Location: net/core/skbuff.c:480
Inline: False
Direct callers:
  - net/core/xdp.c:__xdp_build_skb_from_frame
```
**Symbols:**

```
ffffffff81ed1d20-ffffffff81ed1dfd: build_skb_around (STB_GLOBAL)
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
struct sk_buff *build_skb_around(struct sk_buff *skb, void *data, unsigned int frag_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffff800010bb0e70)
Location: net/core/skbuff.c:343
Inline: False
Direct callers:
  - kernel/bpf/cpumap.c:cpu_map_kthread_run
```
**Symbols:**

```
ffff800010bb0e70-ffff800010bb0f30: build_skb_around (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct sk_buff *build_skb_around(struct sk_buff *skb, void *data, unsigned int frag_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (c0cce1c0)
Location: net/core/skbuff.c:343
Inline: False
Direct callers:
  - kernel/bpf/cpumap.c:cpu_map_kthread_run
```
**Symbols:**

```
c0cce1c0-c0cce248: build_skb_around (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct sk_buff *build_skb_around(struct sk_buff *skb, void *data, unsigned int frag_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (c000000000c87210)
Location: net/core/skbuff.c:343
Inline: False
Direct callers:
  - kernel/bpf/cpumap.c:cpu_map_kthread_run
```
**Symbols:**

```
c000000000c87210-c000000000c87318: build_skb_around (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct sk_buff *build_skb_around(struct sk_buff *skb, void *data, unsigned int frag_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffe000741a24)
Location: net/core/skbuff.c:343
Inline: False
Direct callers:
  - kernel/bpf/cpumap.c:cpu_map_kthread_run
```
**Symbols:**

```
ffffffe000741a24-ffffffe000741b46: build_skb_around (STB_GLOBAL)
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
struct sk_buff *build_skb_around(struct sk_buff *skb, void *data, unsigned int frag_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff818b7ac0)
Location: net/core/skbuff.c:343
Inline: False
Direct callers:
  - kernel/bpf/cpumap.c:cpu_map_kthread_run
```
**Symbols:**

```
ffffffff818b7ac0-ffffffff818b7b44: build_skb_around (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct sk_buff *build_skb_around(struct sk_buff *skb, void *data, unsigned int frag_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff81871a10)
Location: net/core/skbuff.c:343
Inline: False
Direct callers:
  - kernel/bpf/cpumap.c:cpu_map_kthread_run
```
**Symbols:**

```
ffffffff81871a10-ffffffff81871a94: build_skb_around (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct sk_buff *build_skb_around(struct sk_buff *skb, void *data, unsigned int frag_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff81908ac0)
Location: net/core/skbuff.c:343
Inline: False
Direct callers:
  - kernel/bpf/cpumap.c:cpu_map_kthread_run
```
**Symbols:**

```
ffffffff81908ac0-ffffffff81908b44: build_skb_around (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct sk_buff *build_skb_around(struct sk_buff *skb, void *data, unsigned int frag_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/skbuff.c (ffffffff81929b70)
Location: net/core/skbuff.c:343
Inline: False
Direct callers:
  - kernel/bpf/cpumap.c:cpu_map_kthread_run
```
**Symbols:**

```
ffffffff81929b70-ffffffff81929bf4: build_skb_around (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
