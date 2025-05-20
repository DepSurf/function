# Function: <code>kmap_to_page</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/swap.c (ffffffff8119d675)
Location: include/linux/highmem.h:48
Inline: True
Inline callers:
  - mm/swap.c:get_kernel_pages
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/swap.c (ffffffff811b1c01)
Location: include/linux/highmem.h:48
Inline: True
Inline callers:
  - mm/swap.c:get_kernel_pages
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/swap.c (ffffffff811c2261)
Location: include/linux/highmem.h:48
Inline: True
Inline callers:
  - mm/swap.c:get_kernel_pages
```
```
In drivers/spi/spi.c (0)
Location: include/linux/highmem.h:48
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/swap.c (ffffffff811ca0df)
Location: include/linux/highmem.h:48
Inline: True
Inline callers:
  - mm/swap.c:get_kernel_pages
```
```
In drivers/spi/spi.c (0)
Location: include/linux/highmem.h:48
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/swap.c (ffffffff811def9f)
Location: include/linux/highmem.h:49
Inline: True
Inline callers:
  - mm/swap.c:get_kernel_pages
```
```
In drivers/spi/spi.c (0)
Location: include/linux/highmem.h:49
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/swap.c (ffffffff81200665)
Location: include/linux/highmem.h:49
Inline: True
Inline callers:
  - mm/swap.c:get_kernel_pages
```
```
In drivers/spi/spi.c (0)
Location: include/linux/highmem.h:49
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/swap.c (ffffffff81212fd5)
Location: include/linux/highmem.h:73
Inline: True
Inline callers:
  - mm/swap.c:get_kernel_pages
```
```
In drivers/spi/spi.c (0)
Location: include/linux/highmem.h:73
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/swap.c (ffffffff81222ddb)
Location: include/linux/highmem.h:73
Inline: True
Inline callers:
  - mm/swap.c:get_kernel_pages
```
```
In drivers/spi/spi.c (0)
Location: include/linux/highmem.h:73
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/swap.c (ffffffff81230573)
Location: include/linux/highmem.h:73
Inline: True
Inline callers:
  - mm/swap.c:get_kernel_pages
```
```
In mm/usercopy.c (ffffffff812d4001)
Location: include/linux/highmem.h:73
Inline: True
```
```
In drivers/spi/spi.c (0)
Location: include/linux/highmem.h:73
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/swap.c (ffffffff8125de61)
Location: include/linux/highmem.h:130
Inline: True
Inline callers:
  - mm/swap.c:get_kernel_pages
```
```
In mm/usercopy.c (ffffffff81309d5e)
Location: include/linux/highmem.h:130
Inline: True
```
```
In drivers/spi/spi.c (0)
Location: include/linux/highmem.h:130
Inline: False
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/swap.c (ffffffff81268261)
Location: include/linux/highmem-internal.h:142
Inline: True
Inline callers:
  - mm/swap.c:get_kernel_pages
```
```
In mm/usercopy.c (ffffffff81315b7e)
Location: include/linux/highmem-internal.h:142
Inline: True
```
```
In drivers/spi/spi.c (0)
Location: include/linux/highmem-internal.h:142
Inline: False
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
In mm/swap.c (ffffffff8126cad1)
Location: include/linux/highmem-internal.h:137
Inline: True
Inline callers:
  - mm/swap.c:get_kernel_pages
```
```
In mm/usercopy.c (ffffffff8131bd6e)
Location: include/linux/highmem-internal.h:137
Inline: True
```
```
In drivers/spi/spi.c (0)
Location: include/linux/highmem-internal.h:137
Inline: False
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
In mm/swap.c (ffffffff812a97f1)
Location: include/linux/highmem-internal.h:148
Inline: True
Inline callers:
  - mm/swap.c:get_kernel_pages
```
```
In mm/usercopy.c (ffffffff8136904e)
Location: include/linux/highmem-internal.h:148
Inline: True
```
```
In drivers/spi/spi.c (0)
Location: include/linux/highmem-internal.h:148
Inline: False
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
In mm/swap.c (ffffffff81303165)
Location: include/linux/highmem-internal.h:159
Inline: True
Inline callers:
  - mm/swap.c:get_kernel_pages
```
```
In drivers/spi/spi.c (0)
Location: include/linux/highmem-internal.h:159
Inline: False
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
In mm/swap.c (ffffffff8136e955)
Location: include/linux/highmem-internal.h:159
Inline: True
Inline callers:
  - mm/swap.c:get_kernel_pages
```
```
In drivers/spi/spi.c (0)
Location: include/linux/highmem-internal.h:159
Inline: False
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/spi/spi.c (0)
Location: include/linux/highmem-internal.h:162
Inline: False
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/spi/spi.c (0)
Location: include/linux/highmem-internal.h:162
Inline: False
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/swap.c (ffff8000102c0314)
Location: include/linux/highmem.h:73
Inline: True
Inline callers:
  - mm/swap.c:get_kernel_pages
```
```
In mm/usercopy.c (ffff80001037a088)
Location: include/linux/highmem.h:73
Inline: True
```
```
In drivers/spi/spi.c (0)
Location: include/linux/highmem.h:73
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct page *kmap_to_page(void *vaddr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/highmem.c (c0515c34)
Location: mm/highmem.c:150
Inline: False
Direct callers:
  - mm/swap.c:get_kernel_pages
  - drivers/spi/spi.c:spi_map_buf
```
**Symbols:**

```
c0515c34-c0515ca0: kmap_to_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/swap.c (c000000000378ff8)
Location: include/linux/highmem.h:73
Inline: True
Inline callers:
  - mm/swap.c:get_kernel_pages
```
```
In mm/usercopy.c (c00000000046d454)
Location: include/linux/highmem.h:73
Inline: True
```
```
In drivers/spi/spi.c (0)
Location: include/linux/highmem.h:73
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/swap.c (ffffffe0001e1d34)
Location: include/linux/highmem.h:73
Inline: True
Inline callers:
  - mm/swap.c:get_kernel_pages
```
```
In mm/usercopy.c (ffffffe000251276)
Location: include/linux/highmem.h:73
Inline: True
```
```
In drivers/spi/spi.c (0)
Location: include/linux/highmem.h:73
Inline: True
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/swap.c (ffffffff81228bc3)
Location: include/linux/highmem.h:73
Inline: True
Inline callers:
  - mm/swap.c:get_kernel_pages
```
```
In mm/usercopy.c (ffffffff812cc5e1)
Location: include/linux/highmem.h:73
Inline: True
```
```
In drivers/spi/spi.c (0)
Location: include/linux/highmem.h:73
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/swap.c (ffffffff8121bd03)
Location: include/linux/highmem.h:73
Inline: True
Inline callers:
  - mm/swap.c:get_kernel_pages
```
```
In mm/usercopy.c (ffffffff812bd451)
Location: include/linux/highmem.h:73
Inline: True
```
```
In drivers/spi/spi.c (0)
Location: include/linux/highmem.h:73
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/swap.c (ffffffff81226963)
Location: include/linux/highmem.h:73
Inline: True
Inline callers:
  - mm/swap.c:get_kernel_pages
```
```
In mm/usercopy.c (ffffffff812ca3f1)
Location: include/linux/highmem.h:73
Inline: True
```
```
In drivers/spi/spi.c (0)
Location: include/linux/highmem.h:73
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/swap.c (ffffffff81235c93)
Location: include/linux/highmem.h:73
Inline: True
Inline callers:
  - mm/swap.c:get_kernel_pages
```
```
In mm/usercopy.c (ffffffff812db0f1)
Location: include/linux/highmem.h:73
Inline: True
```
```
In drivers/spi/spi.c (0)
Location: include/linux/highmem.h:73
Inline: True
```
</details>
</li>
</ul>

## Differences
<b>Arch</b>
<ul>
</ul>
