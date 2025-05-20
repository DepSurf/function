# Function: <code>bpf_prog_array_alloc</code>

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
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
struct bpf_prog_array *bpf_prog_array_alloc(u32 prog_cnt, gfp_t flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff8119e209)
Location: kernel/bpf/core.c:1443
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_prog_array_copy
Direct callers:
  - kernel/bpf/cgroup.c:compute_effective_progs
```
**Symbols:**

```
ffffffff8119dff0-ffffffff8119e01d: bpf_prog_array_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
struct bpf_prog_array *bpf_prog_array_alloc(u32 prog_cnt, gfp_t flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff811b298e)
Location: kernel/bpf/core.c:1541
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_prog_array_copy
Direct callers:
  - kernel/bpf/cgroup.c:compute_effective_progs
```
**Symbols:**

```
ffffffff811b2720-ffffffff811b274d: bpf_prog_array_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
struct bpf_prog_array *bpf_prog_array_alloc(u32 prog_cnt, gfp_t flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff811c14f5)
Location: kernel/bpf/core.c:1791
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_prog_array_copy
  - kernel/bpf/core.c:bpf_prog_array_copy
Direct callers:
  - kernel/bpf/cgroup.c:compute_effective_progs
```
**Symbols:**

```
ffffffff811c1260-ffffffff811c1291: bpf_prog_array_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
struct bpf_prog_array *bpf_prog_array_alloc(u32 prog_cnt, gfp_t flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff811d1c4a)
Location: kernel/bpf/core.c:1786
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_prog_array_copy
  - kernel/bpf/core.c:bpf_prog_array_copy
Direct callers:
  - kernel/bpf/cgroup.c:compute_effective_progs
```
**Symbols:**

```
ffffffff811d19b0-ffffffff811d19e1: bpf_prog_array_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
struct bpf_prog_array *bpf_prog_array_alloc(u32 prog_cnt, gfp_t flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff811de1ea)
Location: kernel/bpf/core.c:1786
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_prog_array_copy
  - kernel/bpf/core.c:bpf_prog_array_copy
Direct callers:
  - kernel/bpf/cgroup.c:compute_effective_progs
```
**Symbols:**

```
ffffffff811ddf30-ffffffff811ddf61: bpf_prog_array_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
struct bpf_prog_array *bpf_prog_array_alloc(u32 prog_cnt, gfp_t flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff811facaa)
Location: kernel/bpf/core.c:1864
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_prog_array_copy
  - kernel/bpf/core.c:bpf_prog_array_copy
Direct callers:
  - kernel/bpf/net_namespace.c:netns_bpf_link_create
  - kernel/bpf/net_namespace.c:netns_bpf_prog_attach
  - kernel/bpf/cgroup.c:compute_effective_progs
```
**Symbols:**

```
ffffffff811fa9f0-ffffffff811faa21: bpf_prog_array_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
struct bpf_prog_array *bpf_prog_array_alloc(u32 prog_cnt, gfp_t flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff811f9f9a)
Location: kernel/bpf/core.c:1866
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_prog_array_copy
  - kernel/bpf/core.c:bpf_prog_array_copy
Direct callers:
  - kernel/bpf/net_namespace.c:netns_bpf_link_create
  - kernel/bpf/net_namespace.c:netns_bpf_prog_attach
  - kernel/bpf/net_namespace.c:bpf_netns_link_release
  - kernel/bpf/cgroup.c:compute_effective_progs
```
**Symbols:**

```
ffffffff811f9c40-ffffffff811f9c71: bpf_prog_array_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
struct bpf_prog_array *bpf_prog_array_alloc(u32 prog_cnt, gfp_t flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff811faf0a)
Location: kernel/bpf/core.c:1962
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_prog_array_copy
  - kernel/bpf/core.c:bpf_prog_array_copy
Direct callers:
  - kernel/bpf/net_namespace.c:netns_bpf_link_create
  - kernel/bpf/net_namespace.c:netns_bpf_prog_attach
  - kernel/bpf/net_namespace.c:bpf_netns_link_release
  - kernel/bpf/cgroup.c:compute_effective_progs
  - net/bpf/test_run.c:bpf_prog_test_run_sk_lookup
```
**Symbols:**

```
ffffffff811fabb0-ffffffff811fabe1: bpf_prog_array_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
struct bpf_prog_array *bpf_prog_array_alloc(u32 prog_cnt, gfp_t flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff8122c61e)
Location: kernel/bpf/core.c:1975
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_prog_array_copy
  - kernel/bpf/core.c:bpf_prog_array_copy
Direct callers:
  - kernel/bpf/net_namespace.c:netns_bpf_link_create
  - kernel/bpf/net_namespace.c:netns_bpf_prog_attach
  - kernel/bpf/net_namespace.c:bpf_netns_link_release
  - kernel/bpf/cgroup.c:compute_effective_progs
  - net/bpf/test_run.c:bpf_prog_test_run_sk_lookup
```
**Symbols:**

```
ffffffff8122c2c0-ffffffff8122c2f1: bpf_prog_array_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
struct bpf_prog_array *bpf_prog_array_alloc(u32 prog_cnt, gfp_t flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff8126e2ae)
Location: kernel/bpf/core.c:2261
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_prog_array_copy
  - kernel/bpf/core.c:bpf_prog_array_copy
Direct callers:
  - kernel/bpf/net_namespace.c:netns_bpf_link_create
  - kernel/bpf/net_namespace.c:netns_bpf_prog_attach
  - kernel/bpf/net_namespace.c:bpf_netns_link_release
  - kernel/bpf/cgroup.c:compute_effective_progs
  - net/bpf/test_run.c:bpf_prog_test_run_sk_lookup
```
**Symbols:**

```
ffffffff8126ded0-ffffffff8126df11: bpf_prog_array_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
struct bpf_prog_array *bpf_prog_array_alloc(u32 prog_cnt, gfp_t flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff812c38fe)
Location: kernel/bpf/core.c:2234
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_prog_array_copy
  - kernel/bpf/core.c:bpf_prog_array_copy
Direct callers:
  - kernel/bpf/net_namespace.c:netns_bpf_link_create
  - kernel/bpf/net_namespace.c:netns_bpf_prog_attach
  - kernel/bpf/net_namespace.c:bpf_netns_link_release
  - kernel/bpf/cgroup.c:compute_effective_progs
  - net/bpf/test_run.c:bpf_prog_test_run_sk_lookup
```
**Symbols:**

```
ffffffff812c3450-ffffffff812c3491: bpf_prog_array_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
struct bpf_prog_array *bpf_prog_array_alloc(u32 prog_cnt, gfp_t flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff812ea74e)
Location: kernel/bpf/core.c:2251
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_prog_array_copy
  - kernel/bpf/core.c:bpf_prog_array_copy
Direct callers:
  - kernel/bpf/net_namespace.c:netns_bpf_link_create
  - kernel/bpf/net_namespace.c:netns_bpf_prog_attach
  - kernel/bpf/net_namespace.c:bpf_netns_link_release
  - kernel/bpf/cgroup.c:compute_effective_progs
  - net/bpf/test_run.c:bpf_prog_test_run_sk_lookup
```
**Symbols:**

```
ffffffff812ea2a0-ffffffff812ea2e1: bpf_prog_array_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
struct bpf_prog_array *bpf_prog_array_alloc(u32 prog_cnt, gfp_t flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff81308a5e)
Location: kernel/bpf/core.c:2427
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_prog_array_copy
  - kernel/bpf/core.c:bpf_prog_array_copy
Direct callers:
  - kernel/bpf/net_namespace.c:netns_bpf_link_create
  - kernel/bpf/net_namespace.c:netns_bpf_prog_attach
  - kernel/bpf/net_namespace.c:bpf_netns_link_release
  - kernel/bpf/cgroup.c:compute_effective_progs
  - net/bpf/test_run.c:bpf_prog_test_run_sk_lookup
```
**Symbols:**

```
ffffffff813085b0-ffffffff813085f1: bpf_prog_array_alloc (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
struct bpf_prog_array *bpf_prog_array_alloc(u32 prog_cnt, gfp_t flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffff80001025f3b4)
Location: kernel/bpf/core.c:1786
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_prog_array_copy
  - kernel/bpf/core.c:bpf_prog_array_copy
Direct callers:
  - kernel/bpf/cgroup.c:compute_effective_progs
```
**Symbols:**

```
ffff80001025ef00-ffff80001025ef5c: bpf_prog_array_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
struct bpf_prog_array *bpf_prog_array_alloc(u32 prog_cnt, gfp_t flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (c04927e4)
Location: kernel/bpf/core.c:1786
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_prog_array_copy
  - kernel/bpf/core.c:bpf_prog_array_copy
Direct callers:
  - kernel/bpf/cgroup.c:compute_effective_progs
```
**Symbols:**

```
c049245c-c049249c: bpf_prog_array_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
struct bpf_prog_array *bpf_prog_array_alloc(u32 prog_cnt, gfp_t flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (c0000000003042ec)
Location: kernel/bpf/core.c:1786
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_prog_array_copy
  - kernel/bpf/core.c:bpf_prog_array_copy
Direct callers:
  - kernel/bpf/cgroup.c:compute_effective_progs
```
**Symbols:**

```
c000000000303ec0-c000000000303f2c: bpf_prog_array_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
struct bpf_prog_array *bpf_prog_array_alloc(u32 prog_cnt, gfp_t flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffe00019d31c)
Location: kernel/bpf/core.c:1786
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_prog_array_copy
  - kernel/bpf/core.c:bpf_prog_array_copy
Direct callers:
  - kernel/bpf/cgroup.c:compute_effective_progs
```
**Symbols:**

```
ffffffe00019d06a-ffffffe00019d0c4: bpf_prog_array_alloc (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
struct bpf_prog_array *bpf_prog_array_alloc(u32 prog_cnt, gfp_t flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff811d680a)
Location: kernel/bpf/core.c:1786
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_prog_array_copy
  - kernel/bpf/core.c:bpf_prog_array_copy
Direct callers:
  - kernel/bpf/cgroup.c:compute_effective_progs
```
**Symbols:**

```
ffffffff811d6550-ffffffff811d6581: bpf_prog_array_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
struct bpf_prog_array *bpf_prog_array_alloc(u32 prog_cnt, gfp_t flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff811c95ca)
Location: kernel/bpf/core.c:1786
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_prog_array_copy
  - kernel/bpf/core.c:bpf_prog_array_copy
Direct callers:
  - kernel/bpf/cgroup.c:compute_effective_progs
```
**Symbols:**

```
ffffffff811c9310-ffffffff811c9341: bpf_prog_array_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
struct bpf_prog_array *bpf_prog_array_alloc(u32 prog_cnt, gfp_t flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff811d45da)
Location: kernel/bpf/core.c:1786
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_prog_array_copy
  - kernel/bpf/core.c:bpf_prog_array_copy
Direct callers:
  - kernel/bpf/cgroup.c:compute_effective_progs
```
**Symbols:**

```
ffffffff811d4320-ffffffff811d4351: bpf_prog_array_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
struct bpf_prog_array *bpf_prog_array_alloc(u32 prog_cnt, gfp_t flags);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffff811e28fa)
Location: kernel/bpf/core.c:1786
Inline: True
Inline callers:
  - kernel/bpf/core.c:bpf_prog_array_copy
  - kernel/bpf/core.c:bpf_prog_array_copy
Direct callers:
  - kernel/bpf/cgroup.c:compute_effective_progs
```
**Symbols:**

```
ffffffff811e2640-ffffffff811e2671: bpf_prog_array_alloc (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
