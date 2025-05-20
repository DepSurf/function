# Function: <code>bpf_event_output</code>

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
u64 bpf_event_output(struct bpf_map *map, u64 flags, void *meta, u64 meta_size, void *ctx, u64 ctx_size, bpf_ctx_copy_t ctx_copy);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/bpf_trace.c (ffffffff81174470)
Location: kernel/trace/bpf_trace.c:344
Inline: False
Direct callers:
  - net/core/filter.c:bpf_skb_event_output
```
**Symbols:**

```
ffffffff81174470-ffffffff811745f4: bpf_event_output (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
u64 bpf_event_output(struct bpf_map *map, u64 flags, void *meta, u64 meta_size, void *ctx, u64 ctx_size, bpf_ctx_copy_t ctx_copy);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/bpf_trace.c (ffffffff8117fef0)
Location: kernel/trace/bpf_trace.c:338
Inline: False
Direct callers:
  - net/core/filter.c:bpf_xdp_event_output
  - net/core/filter.c:bpf_skb_event_output
```
**Symbols:**

```
ffffffff8117fef0-ffffffff81180072: bpf_event_output (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
u64 bpf_event_output(struct bpf_map *map, u64 flags, void *meta, u64 meta_size, void *ctx, u64 ctx_size, bpf_ctx_copy_t ctx_copy);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/bpf_trace.c (ffffffff81182d90)
Location: kernel/trace/bpf_trace.c:372
Inline: False
Direct callers:
  - net/core/filter.c:bpf_xdp_event_output
  - net/core/filter.c:bpf_skb_event_output
```
**Symbols:**

```
ffffffff81182d90-ffffffff81182f00: bpf_event_output (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
u64 bpf_event_output(struct bpf_map *map, u64 flags, void *meta, u64 meta_size, void *ctx, u64 ctx_size, bpf_ctx_copy_t ctx_copy);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/bpf_trace.c (ffffffff81190850)
Location: kernel/trace/bpf_trace.c:413
Inline: False
Direct callers:
  - net/core/filter.c:bpf_xdp_event_output
  - net/core/filter.c:bpf_skb_event_output
```
**Symbols:**

```
ffffffff81190850-ffffffff811909bc: bpf_event_output (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
u64 bpf_event_output(struct bpf_map *map, u64 flags, void *meta, u64 meta_size, void *ctx, u64 ctx_size, bpf_ctx_copy_t ctx_copy);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/bpf_trace.c (ffffffff811a59a0)
Location: kernel/trace/bpf_trace.c:436
Inline: False
Direct callers:
  - net/core/filter.c:bpf_xdp_event_output
  - net/core/filter.c:bpf_skb_event_output
```
**Symbols:**

```
ffffffff811a59a0-ffffffff811a5b0c: bpf_event_output (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
u64 bpf_event_output(struct bpf_map *map, u64 flags, void *meta, u64 meta_size, void *ctx, u64 ctx_size, bpf_ctx_copy_t ctx_copy);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/bpf_trace.c (ffffffff811b3cb0)
Location: kernel/trace/bpf_trace.c:472
Inline: False
Direct callers:
  - net/core/filter.c:bpf_sockopt_event_output
  - net/core/filter.c:bpf_xdp_event_output
  - net/core/filter.c:bpf_skb_event_output
```
**Symbols:**

```
ffffffff811b3cb0-ffffffff811b3e1c: bpf_event_output (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
u64 bpf_event_output(struct bpf_map *map, u64 flags, void *meta, u64 meta_size, void *ctx, u64 ctx_size, bpf_ctx_copy_t ctx_copy);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/bpf_trace.c (ffffffff811c2cc0)
Location: kernel/trace/bpf_trace.c:506
Inline: False
Direct callers:
  - net/core/filter.c:bpf_sockopt_event_output
  - net/core/filter.c:bpf_xdp_event_output
  - net/core/filter.c:bpf_skb_event_output
```
**Symbols:**

```
ffffffff811c2cc0-ffffffff811c2e2f: bpf_event_output (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
u64 bpf_event_output(struct bpf_map *map, u64 flags, void *meta, u64 meta_size, void *ctx, u64 ctx_size, bpf_ctx_copy_t ctx_copy);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/bpf_trace.c (ffffffff811ce430)
Location: kernel/trace/bpf_trace.c:513
Inline: False
Direct callers:
  - net/core/filter.c:bpf_sockopt_event_output
  - net/core/filter.c:bpf_xdp_event_output
  - net/core/filter.c:bpf_skb_event_output
```
**Symbols:**

```
ffffffff811ce430-ffffffff811ce5dd: bpf_event_output (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
u64 bpf_event_output(struct bpf_map *map, u64 flags, void *meta, u64 meta_size, void *ctx, u64 ctx_size, bpf_ctx_copy_t ctx_copy);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/bpf_trace.c (ffffffff811ea4e0)
Location: kernel/trace/bpf_trace.c:902
Inline: False
Direct callers:
  - kernel/bpf/helpers.c:bpf_event_output_data
  - net/core/filter.c:bpf_xdp_event_output
  - net/core/filter.c:bpf_skb_event_output
```
**Symbols:**

```
ffffffff811ea4e0-ffffffff811ea688: bpf_event_output (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
u64 bpf_event_output(struct bpf_map *map, u64 flags, void *meta, u64 meta_size, void *ctx, u64 ctx_size, bpf_ctx_copy_t ctx_copy);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/bpf_trace.c (ffffffff811e84e0)
Location: kernel/trace/bpf_trace.c:985
Inline: False
Direct callers:
  - kernel/bpf/helpers.c:bpf_event_output_data
  - net/core/filter.c:bpf_xdp_event_output
  - net/core/filter.c:bpf_skb_event_output
```
**Symbols:**

```
ffffffff811e84e0-ffffffff811e868b: bpf_event_output (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
u64 bpf_event_output(struct bpf_map *map, u64 flags, void *meta, u64 meta_size, void *ctx, u64 ctx_size, bpf_ctx_copy_t ctx_copy);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/bpf_trace.c (ffffffff811e92c0)
Location: kernel/trace/bpf_trace.c:662
Inline: False
Direct callers:
  - kernel/bpf/helpers.c:bpf_event_output_data
  - net/core/filter.c:bpf_xdp_event_output
  - net/core/filter.c:bpf_skb_event_output
```
**Symbols:**

```
ffffffff811e92c0-ffffffff811e9468: bpf_event_output (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
u64 bpf_event_output(struct bpf_map *map, u64 flags, void *meta, u64 meta_size, void *ctx, u64 ctx_size, bpf_ctx_copy_t ctx_copy);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/bpf_trace.c (ffffffff8121a790)
Location: kernel/trace/bpf_trace.c:662
Inline: False
Direct callers:
  - kernel/bpf/helpers.c:bpf_event_output_data
  - net/core/filter.c:bpf_xdp_event_output
  - net/core/filter.c:bpf_skb_event_output
```
**Symbols:**

```
ffffffff8121a790-ffffffff8121a99d: bpf_event_output (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
u64 bpf_event_output(struct bpf_map *map, u64 flags, void *meta, u64 meta_size, void *ctx, u64 ctx_size, bpf_ctx_copy_t ctx_copy);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/bpf_trace.c (ffffffff81259430)
Location: kernel/trace/bpf_trace.c:714
Inline: False
Direct callers:
  - kernel/bpf/helpers.c:bpf_event_output_data
  - net/core/filter.c:bpf_xdp_event_output
  - net/core/filter.c:bpf_skb_event_output
```
**Symbols:**

```
ffffffff81259430-ffffffff8125964c: bpf_event_output (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
u64 bpf_event_output(struct bpf_map *map, u64 flags, void *meta, u64 meta_size, void *ctx, u64 ctx_size, bpf_ctx_copy_t ctx_copy);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/bpf_trace.c (ffffffff812a9460)
Location: kernel/trace/bpf_trace.c:718
Inline: False
Direct callers:
  - kernel/bpf/helpers.c:bpf_event_output_data
  - net/core/filter.c:bpf_xdp_event_output
  - net/core/filter.c:bpf_skb_event_output
```
**Symbols:**

```
ffffffff812a9460-ffffffff812a965b: bpf_event_output (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
u64 bpf_event_output(struct bpf_map *map, u64 flags, void *meta, u64 meta_size, void *ctx, u64 ctx_size, bpf_ctx_copy_t ctx_copy);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/bpf_trace.c (ffffffff812cbc70)
Location: kernel/trace/bpf_trace.c:718
Inline: False
Direct callers:
  - kernel/bpf/helpers.c:bpf_event_output_data
  - net/core/filter.c:bpf_xdp_event_output
  - net/core/filter.c:bpf_skb_event_output
```
**Symbols:**

```
ffffffff812cbc70-ffffffff812cbede: bpf_event_output (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
u64 bpf_event_output(struct bpf_map *map, u64 flags, void *meta, u64 meta_size, void *ctx, u64 ctx_size, bpf_ctx_copy_t ctx_copy);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/bpf_trace.c (ffffffff812e8f80)
Location: kernel/trace/bpf_trace.c:718
Inline: False
Direct callers:
  - kernel/bpf/helpers.c:bpf_event_output_data
  - net/core/filter.c:bpf_xdp_event_output
  - net/core/filter.c:bpf_skb_event_output
```
**Symbols:**

```
ffffffff812e8f80-ffffffff812e91ee: bpf_event_output (STB_GLOBAL)
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
u64 bpf_event_output(struct bpf_map *map, u64 flags, void *meta, u64 meta_size, void *ctx, u64 ctx_size, bpf_ctx_copy_t ctx_copy);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/bpf_trace.c (ffff80001024e5a0)
Location: kernel/trace/bpf_trace.c:513
Inline: False
Direct callers:
  - net/core/filter.c:bpf_sockopt_event_output
  - net/core/filter.c:bpf_xdp_event_output
  - net/core/filter.c:bpf_skb_event_output
```
**Symbols:**

```
ffff80001024e5a0-ffff80001024e74c: bpf_event_output (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
u64 bpf_event_output(struct bpf_map *map, u64 flags, void *meta, u64 meta_size, void *ctx, u64 ctx_size, bpf_ctx_copy_t ctx_copy);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/bpf_trace.c (c04814e4)
Location: kernel/trace/bpf_trace.c:513
Inline: False
Direct callers:
  - net/core/filter.c:bpf_sockopt_event_output
  - net/core/filter.c:bpf_xdp_event_output
  - net/core/filter.c:bpf_skb_event_output
```
**Symbols:**

```
c04814e4-c0481738: bpf_event_output (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
u64 bpf_event_output(struct bpf_map *map, u64 flags, void *meta, u64 meta_size, void *ctx, u64 ctx_size, bpf_ctx_copy_t ctx_copy);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/bpf_trace.c (c0000000002ea710)
Location: kernel/trace/bpf_trace.c:513
Inline: False
Direct callers:
  - net/core/filter.c:bpf_sockopt_event_output
  - net/core/filter.c:bpf_xdp_event_output
  - net/core/filter.c:bpf_skb_event_output
```
**Symbols:**

```
c0000000002ea710-c0000000002ea9b0: bpf_event_output (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
u64 bpf_event_output(struct bpf_map *map, u64 flags, void *meta, u64 meta_size, void *ctx, u64 ctx_size, bpf_ctx_copy_t ctx_copy);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/core.c (ffffffe00019a568)
Location: kernel/bpf/core.c:2052
Inline: False
Direct callers:
  - net/core/filter.c:bpf_sockopt_event_output
  - net/core/filter.c:bpf_xdp_event_output
  - net/core/filter.c:bpf_skb_event_output
```
**Symbols:**

```
ffffffe00019a568-ffffffe00019a586: bpf_event_output (STB_WEAK)
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
u64 bpf_event_output(struct bpf_map *map, u64 flags, void *meta, u64 meta_size, void *ctx, u64 ctx_size, bpf_ctx_copy_t ctx_copy);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/bpf_trace.c (ffffffff811c6a50)
Location: kernel/trace/bpf_trace.c:513
Inline: False
Direct callers:
  - net/core/filter.c:bpf_sockopt_event_output
  - net/core/filter.c:bpf_xdp_event_output
  - net/core/filter.c:bpf_skb_event_output
```
**Symbols:**

```
ffffffff811c6a50-ffffffff811c6bfd: bpf_event_output (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
u64 bpf_event_output(struct bpf_map *map, u64 flags, void *meta, u64 meta_size, void *ctx, u64 ctx_size, bpf_ctx_copy_t ctx_copy);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/bpf_trace.c (ffffffff811b9830)
Location: kernel/trace/bpf_trace.c:513
Inline: False
Direct callers:
  - net/core/filter.c:bpf_sockopt_event_output
  - net/core/filter.c:bpf_xdp_event_output
  - net/core/filter.c:bpf_skb_event_output
```
**Symbols:**

```
ffffffff811b9830-ffffffff811b99dd: bpf_event_output (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
u64 bpf_event_output(struct bpf_map *map, u64 flags, void *meta, u64 meta_size, void *ctx, u64 ctx_size, bpf_ctx_copy_t ctx_copy);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/bpf_trace.c (ffffffff811c4820)
Location: kernel/trace/bpf_trace.c:513
Inline: False
Direct callers:
  - net/core/filter.c:bpf_sockopt_event_output
  - net/core/filter.c:bpf_xdp_event_output
  - net/core/filter.c:bpf_skb_event_output
```
**Symbols:**

```
ffffffff811c4820-ffffffff811c49cd: bpf_event_output (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
u64 bpf_event_output(struct bpf_map *map, u64 flags, void *meta, u64 meta_size, void *ctx, u64 ctx_size, bpf_ctx_copy_t ctx_copy);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/bpf_trace.c (ffffffff811d2a80)
Location: kernel/trace/bpf_trace.c:513
Inline: False
Direct callers:
  - net/core/filter.c:bpf_sockopt_event_output
  - net/core/filter.c:bpf_xdp_event_output
  - net/core/filter.c:bpf_skb_event_output
```
**Symbols:**

```
ffffffff811d2a80-ffffffff811d2c2d: bpf_event_output (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
