# Function: <code>kmalloc_size_roundup</code>

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
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

```c
size_t kmalloc_size_roundup(size_t size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/slab_common.c (ffffffff813a2105)
Location: mm/slab_common.c:744
Inline: True
Direct callers:
  - kernel/bpf/verifier.c:push_jmp_history
  - kernel/bpf/verifier.c:realloc_array
  - kernel/bpf/verifier.c:copy_array
  - fs/coredump.c:cn_vprintf
  - drivers/base/devres.c:devm_krealloc
  - drivers/base/devres.c:devm_krealloc
  - drivers/base/devres.c:devm_kmalloc
  - drivers/base/devres.c:__devres_alloc_node
  - drivers/dma-buf/dma-resv.c:dma_resv_list_alloc
  - net/core/skbuff.c:pskb_carve_inside_nonlinear
  - net/core/skbuff.c:pskb_carve_inside_header
  - net/core/skbuff.c:pskb_expand_head
  - net/core/skbuff.c:__alloc_skb
```
**Symbols:**

```
ffffffff82063430-ffffffff8206344f: kmalloc_size_roundup.cold (STB_LOCAL)
ffffffff813a20e0-ffffffff813a218b: kmalloc_size_roundup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

```c
size_t kmalloc_size_roundup(size_t size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/slab_common.c (ffffffff813d4bca)
Location: mm/slab_common.c:741
Inline: True
Direct callers:
  - kernel/bpf/verifier.c:push_jmp_history
  - kernel/bpf/verifier.c:realloc_array
  - kernel/bpf/verifier.c:copy_array
  - fs/coredump.c:cn_vprintf
  - security/tomoyo/audit.c:tomoyo_write_log2
  - security/tomoyo/audit.c:tomoyo_write_log2
  - security/tomoyo/audit.c:tomoyo_init_log
  - security/tomoyo/common.c:tomoyo_supervisor
  - drivers/base/devres.c:devm_krealloc
  - drivers/base/devres.c:devm_krealloc
  - drivers/base/devres.c:devm_kmalloc
  - drivers/base/devres.c:__devres_alloc_node
  - drivers/dma-buf/dma-resv.c:dma_resv_list_alloc
  - net/core/skbuff.c:kmalloc_reserve
```
**Symbols:**

```
ffffffff820e2a71-ffffffff820e2a90: kmalloc_size_roundup.cold (STB_LOCAL)
ffffffff813d4ba0-ffffffff813d4cb4: kmalloc_size_roundup (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
size_t kmalloc_size_roundup(size_t size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/slab_common.c (0)
Location: mm/slab_common.c:695
Inline: False
Direct callers:
  - kernel/bpf/verifier.c:push_jmp_history
  - kernel/bpf/verifier.c:realloc_array
  - kernel/bpf/verifier.c:copy_array
  - fs/coredump.c:cn_vprintf
  - security/tomoyo/audit.c:tomoyo_write_log2
  - security/tomoyo/audit.c:tomoyo_write_log2
  - security/tomoyo/audit.c:tomoyo_init_log
  - security/tomoyo/common.c:tomoyo_supervisor
  - drivers/base/devres.c:devm_krealloc
  - drivers/base/devres.c:devm_krealloc
  - drivers/base/devres.c:devm_kmalloc
  - drivers/base/devres.c:__devres_alloc_node
  - drivers/dma-buf/dma-resv.c:dma_resv_list_alloc
  - net/core/skbuff.c:kmalloc_reserve
```
**Symbols:**

```
ffffffff821bf442-ffffffff821bf461: kmalloc_size_roundup.cold (STB_LOCAL)
ffffffff813fec10-ffffffff813fed24: kmalloc_size_roundup (STB_GLOBAL)
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
<b>Regular</b>
<ul>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
