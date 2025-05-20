# Function: <code>bq_xmit_all</code>

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
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int bq_xmit_all(struct bpf_dtab_netdev *obj, struct xdp_bulk_queue *bq, u32 flags, bool in_napi_ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/devmap.c (ffffffff811c97b0)
Location: kernel/bpf/devmap.c:219
Inline: False
Direct callers:
  - kernel/bpf/devmap.c:__dev_map_entry_free
  - kernel/bpf/devmap.c:dev_map_enqueue
  - kernel/bpf/devmap.c:__dev_map_flush
```
**Symbols:**

```
ffffffff811c97b0-ffffffff811c9923: bq_xmit_all (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int bq_xmit_all(struct bpf_dtab_netdev *obj, struct xdp_bulk_queue *bq, u32 flags, bool in_napi_ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/devmap.c (ffffffff811dd0b0)
Location: kernel/bpf/devmap.c:220
Inline: False
Direct callers:
  - kernel/bpf/devmap.c:__dev_map_entry_free
  - kernel/bpf/devmap.c:dev_map_enqueue
  - kernel/bpf/devmap.c:__dev_map_flush
```
**Symbols:**

```
ffffffff811dd0b0-ffffffff811dd223: bq_xmit_all (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int bq_xmit_all(struct xdp_bulk_queue *bq, u32 flags, bool in_napi_ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/devmap.c (ffffffff811f2700)
Location: kernel/bpf/devmap.c:211
Inline: False
Direct callers:
  - kernel/bpf/devmap.c:__dev_map_entry_free
  - kernel/bpf/devmap.c:dev_map_enqueue
  - kernel/bpf/devmap.c:__dev_map_flush
```
**Symbols:**

```
ffffffff811f2700-ffffffff811f28a9: bq_xmit_all (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int bq_xmit_all(struct xdp_bulk_queue *bq, u32 flags, bool in_napi_ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/devmap.c (ffffffff811fef30)
Location: kernel/bpf/devmap.c:349
Inline: False
Direct callers:
  - kernel/bpf/devmap.c:__dev_map_entry_free
  - kernel/bpf/devmap.c:dev_map_enqueue
  - kernel/bpf/devmap.c:__dev_map_flush
```
**Symbols:**

```
ffffffff811fef30-ffffffff811ff0d9: bq_xmit_all (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/bpf/devmap.c (ffffffff81226c90)
Location: kernel/bpf/devmap.c:344
Inline: True
Direct callers:
  - kernel/bpf/devmap.c:bq_enqueue
  - kernel/bpf/devmap.c:__dev_flush
```
**Symbols:**

```
ffffffff81226c90-ffffffff81226dfa: bq_xmit_all.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void bq_xmit_all(struct xdp_dev_bulk_queue *bq, u32 flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/devmap.c (ffffffff8122d820)
Location: kernel/bpf/devmap.c:330
Inline: False
Direct callers:
  - kernel/bpf/devmap.c:bq_enqueue
  - kernel/bpf/devmap.c:__dev_flush
```
**Symbols:**

```
ffffffff8122d820-ffffffff8122d956: bq_xmit_all (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void bq_xmit_all(struct xdp_dev_bulk_queue *bq, u32 flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/devmap.c (ffffffff812328e0)
Location: kernel/bpf/devmap.c:329
Inline: False
Direct callers:
  - kernel/bpf/devmap.c:bq_enqueue
  - kernel/bpf/devmap.c:__dev_flush
```
**Symbols:**

```
ffffffff812328e0-ffffffff81232a25: bq_xmit_all (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void bq_xmit_all(struct xdp_dev_bulk_queue *bq, u32 flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/devmap.c (ffffffff8126be70)
Location: kernel/bpf/devmap.c:364
Inline: False
Direct callers:
  - kernel/bpf/devmap.c:bq_enqueue
  - kernel/bpf/devmap.c:__dev_flush
```
**Symbols:**

```
ffffffff8126be70-ffffffff8126c021: bq_xmit_all (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void bq_xmit_all(struct xdp_dev_bulk_queue *bq, u32 flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/devmap.c (ffffffff812bacd0)
Location: kernel/bpf/devmap.c:365
Inline: False
Direct callers:
  - kernel/bpf/devmap.c:dev_map_enqueue
  - kernel/bpf/devmap.c:dev_xdp_enqueue
  - kernel/bpf/devmap.c:__dev_flush
```
**Symbols:**

```
ffffffff812bacd0-ffffffff812baead: bq_xmit_all (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void bq_xmit_all(struct xdp_dev_bulk_queue *bq, u32 flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/devmap.c (ffffffff8131e0d0)
Location: kernel/bpf/devmap.c:365
Inline: False
Direct callers:
  - kernel/bpf/devmap.c:bq_enqueue
  - kernel/bpf/devmap.c:__dev_flush
```
**Symbols:**

```
ffffffff8131e0d0-ffffffff8131e2ad: bq_xmit_all (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void bq_xmit_all(struct xdp_dev_bulk_queue *bq, u32 flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/devmap.c (ffffffff8134dec0)
Location: kernel/bpf/devmap.c:362
Inline: False
Direct callers:
  - kernel/bpf/devmap.c:bq_enqueue
  - kernel/bpf/devmap.c:__dev_flush
```
**Symbols:**

```
ffffffff8134dec0-ffffffff8134e09d: bq_xmit_all (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void bq_xmit_all(struct xdp_dev_bulk_queue *bq, u32 flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/devmap.c (ffffffff813753c0)
Location: kernel/bpf/devmap.c:361
Inline: False
Direct callers:
  - kernel/bpf/devmap.c:bq_enqueue
  - kernel/bpf/devmap.c:__dev_flush
```
**Symbols:**

```
ffffffff813753c0-ffffffff8137559a: bq_xmit_all (STB_LOCAL)
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
int bq_xmit_all(struct xdp_bulk_queue *bq, u32 flags, bool in_napi_ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/devmap.c (ffff8000102864b8)
Location: kernel/bpf/devmap.c:349
Inline: False
Direct callers:
  - kernel/bpf/devmap.c:__dev_map_entry_free
  - kernel/bpf/devmap.c:dev_map_enqueue
  - kernel/bpf/devmap.c:__dev_map_flush
```
**Symbols:**

```
ffff8000102864b8-ffff800010286654: bq_xmit_all (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int bq_xmit_all(struct xdp_bulk_queue *bq, u32 flags, bool in_napi_ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/devmap.c (c04b66f4)
Location: kernel/bpf/devmap.c:349
Inline: False
Direct callers:
  - kernel/bpf/devmap.c:__dev_map_entry_free
  - kernel/bpf/devmap.c:dev_map_enqueue
  - kernel/bpf/devmap.c:__dev_map_flush
```
**Symbols:**

```
c04b66f4-c04b68a8: bq_xmit_all (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int bq_xmit_all(struct xdp_bulk_queue *bq, u32 flags, bool in_napi_ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/devmap.c (c000000000331140)
Location: kernel/bpf/devmap.c:349
Inline: False
Direct callers:
  - kernel/bpf/devmap.c:__dev_map_entry_free
  - kernel/bpf/devmap.c:dev_map_enqueue
  - kernel/bpf/devmap.c:__dev_map_flush
```
**Symbols:**

```
c000000000331140-c00000000033137c: bq_xmit_all (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int bq_xmit_all(struct xdp_bulk_queue *bq, u32 flags, bool in_napi_ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/devmap.c (ffffffe0001bb2ca)
Location: kernel/bpf/devmap.c:349
Inline: False
Direct callers:
  - kernel/bpf/devmap.c:__dev_map_entry_free
  - kernel/bpf/devmap.c:dev_map_enqueue
  - kernel/bpf/devmap.c:__dev_map_flush
```
**Symbols:**

```
ffffffe0001bb2ca-ffffffe0001bb410: bq_xmit_all (STB_LOCAL)
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
int bq_xmit_all(struct xdp_bulk_queue *bq, u32 flags, bool in_napi_ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/devmap.c (ffffffff811f7550)
Location: kernel/bpf/devmap.c:349
Inline: False
Direct callers:
  - kernel/bpf/devmap.c:__dev_map_entry_free
  - kernel/bpf/devmap.c:dev_map_enqueue
  - kernel/bpf/devmap.c:__dev_map_flush
```
**Symbols:**

```
ffffffff811f7550-ffffffff811f76f9: bq_xmit_all (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int bq_xmit_all(struct xdp_bulk_queue *bq, u32 flags, bool in_napi_ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/devmap.c (ffffffff811ea2a0)
Location: kernel/bpf/devmap.c:349
Inline: False
Direct callers:
  - kernel/bpf/devmap.c:__dev_map_entry_free
  - kernel/bpf/devmap.c:dev_map_enqueue
  - kernel/bpf/devmap.c:__dev_map_flush
```
**Symbols:**

```
ffffffff811ea2a0-ffffffff811ea449: bq_xmit_all (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int bq_xmit_all(struct xdp_bulk_queue *bq, u32 flags, bool in_napi_ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/devmap.c (ffffffff811f5320)
Location: kernel/bpf/devmap.c:349
Inline: False
Direct callers:
  - kernel/bpf/devmap.c:__dev_map_entry_free
  - kernel/bpf/devmap.c:dev_map_enqueue
  - kernel/bpf/devmap.c:__dev_map_flush
```
**Symbols:**

```
ffffffff811f5320-ffffffff811f54c9: bq_xmit_all (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int bq_xmit_all(struct xdp_bulk_queue *bq, u32 flags, bool in_napi_ctx);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/devmap.c (ffffffff81203850)
Location: kernel/bpf/devmap.c:349
Inline: False
Direct callers:
  - kernel/bpf/devmap.c:__dev_map_entry_free
  - kernel/bpf/devmap.c:dev_map_enqueue
  - kernel/bpf/devmap.c:__dev_map_flush
```
**Symbols:**

```
ffffffff81203850-ffffffff81203a12: bq_xmit_all (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.0</code> and <code>5.3</code> ⚠️</summary>
<ul>
<li>
<b>Param removed. </b>
<code>struct bpf_dtab_netdev *obj</code>
</li>
<li>
<b>Param reordered. </b>
<code>obj, bq, flags, in_napi_ctx</code> ➡️ <code>bq, flags, in_napi_ctx</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
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
