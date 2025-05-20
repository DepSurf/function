# Function: <code>gen_pool_dma_zalloc_align</code>

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
void *gen_pool_dma_zalloc_align(struct gen_pool *pool, size_t size, dma_addr_t *dma, int align);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/genalloc.c (ffffffff81516e10)
Location: lib/genalloc.c:464
Inline: False
Direct callers:
  - drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue
  - drivers/usb/host/ohci-hcd.c:td_alloc
```
**Symbols:**

```
ffffffff81516e10-ffffffff81516e50: gen_pool_dma_zalloc_align (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void *gen_pool_dma_zalloc_align(struct gen_pool *pool, size_t size, dma_addr_t *dma, int align);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/genalloc.c (ffffffff81537850)
Location: lib/genalloc.c:464
Inline: False
Direct callers:
  - drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue
  - drivers/usb/host/ohci-hcd.c:td_alloc
```
**Symbols:**

```
ffffffff81537850-ffffffff81537890: gen_pool_dma_zalloc_align (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void *gen_pool_dma_zalloc_align(struct gen_pool *pool, size_t size, dma_addr_t *dma, int align);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/genalloc.c (ffffffff8159c210)
Location: lib/genalloc.c:464
Inline: False
Direct callers:
  - drivers/usb/host/ohci-hcd.c:ed_get
  - drivers/usb/host/ohci-hcd.c:td_alloc
```
**Symbols:**

```
ffffffff8159c210-ffffffff8159c274: gen_pool_dma_zalloc_align (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void *gen_pool_dma_zalloc_align(struct gen_pool *pool, size_t size, dma_addr_t *dma, int align);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/genalloc.c (ffffffff815b7c60)
Location: lib/genalloc.c:465
Inline: False
Direct callers:
  - drivers/usb/host/ohci-hcd.c:ed_get
  - drivers/usb/host/ohci-hcd.c:td_alloc
```
**Symbols:**

```
ffffffff815b7c60-ffffffff815b7cc4: gen_pool_dma_zalloc_align (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void *gen_pool_dma_zalloc_align(struct gen_pool *pool, size_t size, dma_addr_t *dma, int align);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/genalloc.c (ffffffff815c2ad0)
Location: lib/genalloc.c:466
Inline: False
Direct callers:
  - drivers/usb/host/ohci-hcd.c:ed_get
  - drivers/usb/host/ohci-hcd.c:td_alloc
```
**Symbols:**

```
ffffffff815c2ad0-ffffffff815c2b34: gen_pool_dma_zalloc_align (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void *gen_pool_dma_zalloc_align(struct gen_pool *pool, size_t size, dma_addr_t *dma, int align);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/genalloc.c (ffffffff8162aa40)
Location: lib/genalloc.c:466
Inline: False
Direct callers:
  - drivers/usb/host/ohci-hcd.c:ed_get
  - drivers/usb/host/ohci-hcd.c:td_alloc
```
**Symbols:**

```
ffffffff8162aa40-ffffffff8162aaa4: gen_pool_dma_zalloc_align (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void *gen_pool_dma_zalloc_align(struct gen_pool *pool, size_t size, dma_addr_t *dma, int align);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/genalloc.c (ffffffff816fbf20)
Location: lib/genalloc.c:466
Inline: False
Direct callers:
  - drivers/usb/host/ohci-hcd.c:ed_get
  - drivers/usb/host/ohci-hcd.c:td_alloc
```
**Symbols:**

```
ffffffff816fbf20-ffffffff816fbf92: gen_pool_dma_zalloc_align (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void *gen_pool_dma_zalloc_align(struct gen_pool *pool, size_t size, dma_addr_t *dma, int align);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/genalloc.c (ffffffff817eec20)
Location: lib/genalloc.c:466
Inline: False
Direct callers:
  - drivers/usb/host/ohci-hcd.c:ed_get
  - drivers/usb/host/ohci-hcd.c:td_alloc
```
**Symbols:**

```
ffffffff817eec20-ffffffff817eec92: gen_pool_dma_zalloc_align (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void *gen_pool_dma_zalloc_align(struct gen_pool *pool, size_t size, dma_addr_t *dma, int align);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/genalloc.c (ffffffff8182eed0)
Location: lib/genalloc.c:464
Inline: False
Direct callers:
  - drivers/usb/host/ohci-hcd.c:ed_get
  - drivers/usb/host/ohci-hcd.c:td_alloc
```
**Symbols:**

```
ffffffff8182eed0-ffffffff8182ef1f: gen_pool_dma_zalloc_align (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void *gen_pool_dma_zalloc_align(struct gen_pool *pool, size_t size, dma_addr_t *dma, int align);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/genalloc.c (ffffffff81880ba0)
Location: lib/genalloc.c:466
Inline: False
Direct callers:
  - drivers/usb/host/ohci-hcd.c:ed_get
  - drivers/usb/host/ohci-hcd.c:td_alloc
```
**Symbols:**

```
ffffffff81880ba0-ffffffff81880bef: gen_pool_dma_zalloc_align (STB_GLOBAL)
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
void *gen_pool_dma_zalloc_align(struct gen_pool *pool, size_t size, dma_addr_t *dma, int align);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/genalloc.c (ffff800010644810)
Location: lib/genalloc.c:464
Inline: False
Direct callers:
  - drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue
  - drivers/usb/host/ohci-hcd.c:td_alloc
```
**Symbols:**

```
ffff800010644810-ffff800010644864: gen_pool_dma_zalloc_align (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void *gen_pool_dma_zalloc_align(struct gen_pool *pool, size_t size, dma_addr_t *dma, int align);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/genalloc.c (c07eb114)
Location: lib/genalloc.c:464
Inline: False
Direct callers:
  - drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue
  - drivers/usb/host/ohci-hcd.c:td_alloc
```
**Symbols:**

```
c07eb114-c07eb178: gen_pool_dma_zalloc_align (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void *gen_pool_dma_zalloc_align(struct gen_pool *pool, size_t size, dma_addr_t *dma, int align);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/genalloc.c (c0000000007f00a0)
Location: lib/genalloc.c:464
Inline: False
Direct callers:
  - drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue
  - drivers/usb/host/ohci-hcd.c:td_alloc
```
**Symbols:**

```
c0000000007f00a0-c0000000007f0104: gen_pool_dma_zalloc_align (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void *gen_pool_dma_zalloc_align(struct gen_pool *pool, size_t size, dma_addr_t *dma, int align);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/genalloc.c (ffffffe000470c70)
Location: lib/genalloc.c:464
Inline: False
Direct callers:
  - drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue
  - drivers/usb/host/ohci-hcd.c:td_alloc
```
**Symbols:**

```
ffffffe000470c70-ffffffe000470c9a: gen_pool_dma_zalloc_align (STB_GLOBAL)
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
void *gen_pool_dma_zalloc_align(struct gen_pool *pool, size_t size, dma_addr_t *dma, int align);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/genalloc.c (ffffffff8152fe30)
Location: lib/genalloc.c:464
Inline: False
Direct callers:
  - drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue
  - drivers/usb/host/ohci-hcd.c:td_alloc
```
**Symbols:**

```
ffffffff8152fe30-ffffffff8152fe70: gen_pool_dma_zalloc_align (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void *gen_pool_dma_zalloc_align(struct gen_pool *pool, size_t size, dma_addr_t *dma, int align);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/genalloc.c (ffffffff81520110)
Location: lib/genalloc.c:464
Inline: False
```
**Symbols:**

```
ffffffff81520110-ffffffff81520150: gen_pool_dma_zalloc_align (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void *gen_pool_dma_zalloc_align(struct gen_pool *pool, size_t size, dma_addr_t *dma, int align);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/genalloc.c (ffffffff8152bb70)
Location: lib/genalloc.c:464
Inline: False
Direct callers:
  - drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue
  - drivers/usb/host/ohci-hcd.c:td_alloc
```
**Symbols:**

```
ffffffff8152bb70-ffffffff8152bbb0: gen_pool_dma_zalloc_align (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void *gen_pool_dma_zalloc_align(struct gen_pool *pool, size_t size, dma_addr_t *dma, int align);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/genalloc.c (ffffffff81545970)
Location: lib/genalloc.c:464
Inline: False
Direct callers:
  - drivers/usb/host/ohci-hcd.c:ohci_urb_enqueue
  - drivers/usb/host/ohci-hcd.c:td_alloc
```
**Symbols:**

```
ffffffff81545970-ffffffff815459b0: gen_pool_dma_zalloc_align (STB_GLOBAL)
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
