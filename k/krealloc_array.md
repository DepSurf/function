# Function: <code>krealloc_array</code>

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
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/pinctrl-utils.c (ffffffff81628bf4)
Location: include/linux/slab.h:603
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-utils.c:pinctrl_utils_reserve_map
```
```
In drivers/dma-buf/sync_file.c (ffffffff8183bd34)
Location: include/linux/slab.h:603
Inline: True
```
```
In drivers/edac/ghes_edac.c (ffffffff8198ffb1)
Location: include/linux/slab.h:603
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/pinctrl/pinctrl-utils.c (ffffffff8160c6d4)
Location: include/linux/slab.h:607
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-utils.c:pinctrl_utils_reserve_map
```
```
In drivers/dma-buf/sync_file.c (ffffffff8181effc)
Location: include/linux/slab.h:607
Inline: True
```
```
In drivers/edac/ghes_edac.c (ffffffff81974541)
Location: include/linux/slab.h:607
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff81235106)
Location: include/linux/slab.h:642
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:realloc_array
```
```
In drivers/pinctrl/pinctrl-utils.c (ffffffff8167b3d4)
Location: include/linux/slab.h:642
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-utils.c:pinctrl_utils_reserve_map
```
```
In drivers/dma-buf/sync_file.c (ffffffff818a969c)
Location: include/linux/slab.h:642
Inline: True
```
```
In drivers/edac/ghes_edac.c (ffffffff81a1d241)
Location: include/linux/slab.h:642
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/bpf/verifier.c (ffffffff81278d36)
Location: include/linux/slab.h:650
Inline: True
Inline callers:
  - kernel/bpf/verifier.c:realloc_array
```
```
In drivers/pinctrl/pinctrl-utils.c (ffffffff81796b4f)
Location: include/linux/slab.h:650
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-utils.c:pinctrl_utils_reserve_map
```
```
In drivers/dma-buf/dma-resv.c (ffffffff819f14f0)
Location: include/linux/slab.h:650
Inline: True
Inline callers:
  - drivers/dma-buf/dma-resv.c:dma_resv_get_fences
```
```
In drivers/edac/ghes_edac.c (ffffffff81b864c1)
Location: include/linux/slab.h:650
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/bpf_trace.c (ffffffff812a6730)
Location: include/linux/slab.h:646
Inline: True
Inline callers:
  - kernel/trace/bpf_trace.c:module_callback
```
```
In drivers/pinctrl/pinctrl-utils.c (ffffffff818ac3df)
Location: include/linux/slab.h:646
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-utils.c:pinctrl_utils_reserve_map
```
```
In drivers/dma-buf/dma-resv.c (ffffffff81b6f150)
Location: include/linux/slab.h:646
Inline: True
Inline callers:
  - drivers/dma-buf/dma-resv.c:dma_resv_get_fences
```
```
In drivers/edac/ghes_edac.c (ffffffff81d25941)
Location: include/linux/slab.h:646
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/bpf_trace.c (ffffffff812ca5bc)
Location: include/linux/slab.h:629
Inline: True
Inline callers:
  - kernel/trace/bpf_trace.c:get_modules_for_addrs
```
```
In drivers/pinctrl/pinctrl-utils.c (ffffffff818ef364)
Location: include/linux/slab.h:629
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-utils.c:pinctrl_utils_reserve_map
```
```
In drivers/dma-buf/dma-resv.c (ffffffff81bc2a20)
Location: include/linux/slab.h:629
Inline: True
Inline callers:
  - drivers/dma-buf/dma-resv.c:dma_resv_get_fences
```
```
In drivers/edac/ghes_edac.c (ffffffff81d8eb61)
Location: include/linux/slab.h:629
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/bpf_trace.c (ffffffff812e785c)
Location: include/linux/slab.h:637
Inline: True
Inline callers:
  - kernel/trace/bpf_trace.c:get_modules_for_addrs
```
```
In drivers/pinctrl/pinctrl-utils.c (ffffffff81936b24)
Location: include/linux/slab.h:637
Inline: True
Inline callers:
  - drivers/pinctrl/pinctrl-utils.c:pinctrl_utils_reserve_map
```
```
In drivers/dma-buf/dma-resv.c (ffffffff81c171b0)
Location: include/linux/slab.h:637
Inline: True
Inline callers:
  - drivers/dma-buf/dma-resv.c:dma_resv_get_fences
```
```
In drivers/gpu/drm/drm_atomic.c (ffffffff81c78e8e)
Location: include/linux/slab.h:637
Inline: True
Inline callers:
  - drivers/gpu/drm/drm_atomic.c:drm_atomic_get_connector_state
```
```
In drivers/edac/ghes_edac.c (ffffffff81e46471)
Location: include/linux/slab.h:637
Inline: True
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
