# Function: <code>page_pool_destroy</code>

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
void page_pool_destroy(struct page_pool *pool);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/page_pool.c (ffffffff818bdbc0)
Location: net/core/page_pool.c:296
Inline: False
```
**Symbols:**

```
ffffffff818bdbc0-ffffffff818bdc08: page_pool_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void page_pool_destroy(struct page_pool *pool);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/core/page_pool.c (ffffffff818e4fa0)
Location: net/core/page_pool.c:296
Inline: False
```
**Symbols:**

```
ffffffff818e4fa0-ffffffff818e4fe8: page_pool_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void page_pool_destroy(struct page_pool *pool);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/page_pool.c (ffffffff81967790)
Location: net/core/page_pool.c:412
Inline: True
Direct callers:
  - net/core/xdp.c:xdp_rxq_info_unreg_mem_model
```
**Symbols:**

```
ffffffff81967790-ffffffff8196783d: page_pool_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void page_pool_destroy(struct page_pool *pool);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/page_pool.c (ffffffff81a3ace0)
Location: net/core/page_pool.c:508
Inline: True
Direct callers:
  - net/core/xdp.c:xdp_rxq_info_unreg_mem_model
```
**Symbols:**

```
ffffffff81a3ace0-ffffffff81a3adb8: page_pool_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void page_pool_destroy(struct page_pool *pool);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/page_pool.c (ffffffff81a3d100)
Location: net/core/page_pool.c:558
Inline: True
Direct callers:
  - drivers/net/xen-netfront.c:xennet_create_page_pool
  - drivers/net/xen-netfront.c:xennet_disconnect_backend
  - net/core/xdp.c:xdp_rxq_info_unreg_mem_model
```
**Symbols:**

```
ffffffff81a3d100-ffffffff81a3d1d8: page_pool_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void page_pool_destroy(struct page_pool *pool);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/page_pool.c (ffffffff81a23f20)
Location: net/core/page_pool.c:591
Inline: True
Direct callers:
  - drivers/net/xen-netfront.c:xennet_create_queues
  - drivers/net/xen-netfront.c:xennet_disconnect_backend
  - net/core/xdp.c:xdp_rxq_info_unreg_mem_model
```
**Symbols:**

```
ffffffff81a23f20-ffffffff81a23ff8: page_pool_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void page_pool_destroy(struct page_pool *pool);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/page_pool.c (ffffffff81ad8f50)
Location: net/core/page_pool.c:700
Inline: True
Direct callers:
  - drivers/net/xen-netfront.c:xennet_disconnect_backend
```
**Symbols:**

```
ffffffff81ad8f50-ffffffff81ad90db: page_pool_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void page_pool_destroy(struct page_pool *pool);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/page_pool.c (ffffffff81c5a0d0)
Location: net/core/page_pool.c:839
Inline: True
Direct callers:
  - drivers/net/xen-netfront.c:xennet_disconnect_backend
  - net/core/xdp.c:xdp_unreg_mem_model
  - net/bpf/test_run.c:bpf_test_run_xdp_live
  - net/bpf/test_run.c:bpf_test_run_xdp_live
```
**Symbols:**

```
ffffffff81c5a0d0-ffffffff81c5a2e8: page_pool_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void page_pool_destroy(struct page_pool *pool);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/page_pool.c (ffffffff81e0fb90)
Location: net/core/page_pool.c:840
Inline: True
Direct callers:
  - drivers/net/xen-netfront.c:xennet_disconnect_backend
  - net/core/xdp.c:xdp_unreg_mem_model
  - net/bpf/test_run.c:bpf_test_run_xdp_live
  - net/bpf/test_run.c:bpf_test_run_xdp_live
```
**Symbols:**

```
ffffffff81e0fb90-ffffffff81e0fda8: page_pool_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void page_pool_destroy(struct page_pool *pool);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/page_pool.c (ffffffff81e833d0)
Location: net/core/page_pool.c:881
Inline: True
Direct callers:
  - drivers/net/xen-netfront.c:xennet_disconnect_backend
  - net/core/xdp.c:xdp_unreg_mem_model
  - net/bpf/test_run.c:bpf_test_run_xdp_live
  - net/bpf/test_run.c:bpf_test_run_xdp_live
```
**Symbols:**

```
ffffffff81e833d0-ffffffff81e835f0: page_pool_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void page_pool_destroy(struct page_pool *pool);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/page_pool.c (ffffffff81f44c30)
Location: net/core/page_pool.c:952
Inline: True
Direct callers:
  - drivers/net/xen-netfront.c:xennet_disconnect_backend
  - net/core/xdp.c:xdp_unreg_mem_model
  - net/bpf/test_run.c:bpf_test_run_xdp_live
  - net/bpf/test_run.c:bpf_test_run_xdp_live
```
**Symbols:**

```
ffffffff81f44c30-ffffffff81f44dc5: page_pool_destroy (STB_GLOBAL)
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
void page_pool_destroy(struct page_pool *pool);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/page_pool.c (ffff800010c0cd60)
Location: net/core/page_pool.c:412
Inline: True
Direct callers:
  - net/core/xdp.c:xdp_rxq_info_unreg_mem_model
```
**Symbols:**

```
ffff800010c0cd60-ffff800010c0ce18: page_pool_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void page_pool_destroy(struct page_pool *pool);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/page_pool.c (c0d25428)
Location: net/core/page_pool.c:412
Inline: True
Direct callers:
  - drivers/net/ethernet/ti/cpsw.c:cpsw_destroy_xdp_rxqs
  - net/core/xdp.c:xdp_rxq_info_unreg_mem_model
```
**Symbols:**

```
c0d25428-c0d254f4: page_pool_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void page_pool_destroy(struct page_pool *pool);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/page_pool.c (c000000000cf87d0)
Location: net/core/page_pool.c:412
Inline: True
Direct callers:
  - net/core/xdp.c:xdp_rxq_info_unreg_mem_model
```
**Symbols:**

```
c000000000cf87d0-c000000000cf88fc: page_pool_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void page_pool_destroy(struct page_pool *pool);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/page_pool.c (ffffffe000789e42)
Location: net/core/page_pool.c:412
Inline: True
Direct callers:
  - net/core/xdp.c:xdp_rxq_info_unreg_mem_model
```
**Symbols:**

```
ffffffe000789e42-ffffffe000789f00: page_pool_destroy (STB_GLOBAL)
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
void page_pool_destroy(struct page_pool *pool);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/page_pool.c (ffffffff81907760)
Location: net/core/page_pool.c:412
Inline: True
Direct callers:
  - net/core/xdp.c:xdp_rxq_info_unreg_mem_model
```
**Symbols:**

```
ffffffff81907760-ffffffff8190780d: page_pool_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void page_pool_destroy(struct page_pool *pool);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/page_pool.c (ffffffff818c1570)
Location: net/core/page_pool.c:412
Inline: True
Direct callers:
  - net/core/xdp.c:xdp_rxq_info_unreg_mem_model
```
**Symbols:**

```
ffffffff818c1570-ffffffff818c161d: page_pool_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void page_pool_destroy(struct page_pool *pool);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/page_pool.c (ffffffff81958790)
Location: net/core/page_pool.c:412
Inline: True
Direct callers:
  - net/core/xdp.c:xdp_rxq_info_unreg_mem_model
```
**Symbols:**

```
ffffffff81958790-ffffffff8195883d: page_pool_destroy (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void page_pool_destroy(struct page_pool *pool);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In net/core/page_pool.c (ffffffff8197a8d0)
Location: net/core/page_pool.c:412
Inline: True
Direct callers:
  - net/core/xdp.c:xdp_rxq_info_unreg_mem_model
```
**Symbols:**

```
ffffffff8197a8d0-ffffffff8197a97d: page_pool_destroy (STB_GLOBAL)
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
