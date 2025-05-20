# Function: <code>memcpy_to_page</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void memcpy_to_page(struct page *page, size_t offset, char *from, size_t len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffffffff813fbe00)
Location: lib/iov_iter.c:372
Inline: False
Direct callers:
  - lib/iov_iter.c:copy_to_iter
  - lib/iov_iter.c:copy_to_iter
```
**Symbols:**

```
ffffffff813fbe00-ffffffff813fbe71: memcpy_to_page (STB_LOCAL)
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
In lib/iov_iter.c (ffffffff81444ad1)
Location: lib/iov_iter.c:345
Inline: True
Inline callers:
  - lib/iov_iter.c:copy_to_iter
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void memcpy_to_page(struct page *page, size_t offset, const char *from, size_t len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffffffff81460310)
Location: lib/iov_iter.c:437
Inline: False
Direct callers:
  - lib/iov_iter.c:copy_to_iter
  - lib/iov_iter.c:copy_to_iter
```
**Symbols:**

```
ffffffff81460310-ffffffff81460374: memcpy_to_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void memcpy_to_page(struct page *page, size_t offset, const char *from, size_t len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffffffff81464c40)
Location: lib/iov_iter.c:457
Inline: False
Direct callers:
  - lib/iov_iter.c:_copy_to_iter
  - lib/iov_iter.c:_copy_to_iter
```
**Symbols:**

```
ffffffff81464c40-ffffffff81464c86: memcpy_to_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void memcpy_to_page(struct page *page, size_t offset, const char *from, size_t len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffffffff81490bc0)
Location: lib/iov_iter.c:457
Inline: False
Direct callers:
  - lib/iov_iter.c:_copy_to_iter
  - lib/iov_iter.c:_copy_to_iter
```
**Symbols:**

```
ffffffff81490bc0-ffffffff81490c06: memcpy_to_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void memcpy_to_page(struct page *page, size_t offset, const char *from, size_t len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffffffff814c5970)
Location: lib/iov_iter.c:457
Inline: False
Direct callers:
  - lib/iov_iter.c:_copy_to_iter
  - lib/iov_iter.c:_copy_to_iter
```
**Symbols:**

```
ffffffff814c5970-ffffffff814c59b6: memcpy_to_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void memcpy_to_page(struct page *page, size_t offset, const char *from, size_t len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffffffff814da150)
Location: lib/iov_iter.c:463
Inline: False
Direct callers:
  - lib/iov_iter.c:_copy_to_iter
  - lib/iov_iter.c:_copy_to_iter
```
**Symbols:**

```
ffffffff814da150-ffffffff814da196: memcpy_to_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void memcpy_to_page(struct page *page, size_t offset, const char *from, size_t len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffffffff81505960)
Location: lib/iov_iter.c:464
Inline: False
Direct callers:
  - lib/iov_iter.c:_copy_to_iter
  - lib/iov_iter.c:_copy_to_iter
```
**Symbols:**

```
ffffffff81505960-ffffffff815059a6: memcpy_to_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void memcpy_to_page(struct page *page, size_t offset, const char *from, size_t len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffffffff81523910)
Location: lib/iov_iter.c:464
Inline: False
Direct callers:
  - lib/iov_iter.c:_copy_to_iter
  - lib/iov_iter.c:_copy_to_iter
```
**Symbols:**

```
ffffffff81523910-ffffffff81523956: memcpy_to_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void memcpy_to_page(struct page *page, size_t offset, const char *from, size_t len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffffffff81587880)
Location: lib/iov_iter.c:469
Inline: False
Direct callers:
  - lib/iov_iter.c:_copy_to_iter
  - lib/iov_iter.c:copy_pipe_to_iter
```
**Symbols:**

```
ffffffff81587880-ffffffff815878c9: memcpy_to_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void memcpy_to_page(struct page *page, size_t offset, const char *from, size_t len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffffffff815a5330)
Location: lib/iov_iter.c:476
Inline: False
Direct callers:
  - lib/iov_iter.c:_copy_to_iter
  - lib/iov_iter.c:copy_pipe_to_iter
```
**Symbols:**

```
ffffffff815a5330-ffffffff815a5379: memcpy_to_page (STB_LOCAL)
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
In fs/ext4/verity.c (ffffffff8145db4e)
Location: include/linux/highmem.h:325
Inline: True
```
```
In lib/iov_iter.c (ffffffff815b0f75)
Location: include/linux/highmem.h:325
Inline: True
Inline callers:
  - lib/iov_iter.c:_copy_to_iter
  - lib/iov_iter.c:_copy_to_iter
  - lib/iov_iter.c:_copy_to_iter
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
In fs/ext4/verity.c (ffffffff814b300e)
Location: include/linux/highmem.h:311
Inline: True
```
```
In block/bio.c (ffffffff815c70e4)
Location: include/linux/highmem.h:311
Inline: True
Inline callers:
  - block/bio.c:bio_copy_data_iter
```
```
In lib/iov_iter.c (ffffffff81618b1f)
Location: include/linux/highmem.h:311
Inline: True
Inline callers:
  - lib/iov_iter.c:_copy_to_iter
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
In fs/ext4/verity.c (ffffffff8153bd20)
Location: include/linux/highmem.h:382
Inline: True
```
```
In lib/iov_iter.c (ffffffff816e1cec)
Location: include/linux/highmem.h:382
Inline: True
Inline callers:
  - lib/iov_iter.c:copy_pipe_to_iter
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/hyperv/hv_init.c (ffffffff81044ce0)
Location: include/linux/highmem.h:397
Inline: True
Direct callers:
  - arch/x86/hyperv/hv_init.c:hyperv_init
```
```
In kernel/dma/swiotlb.c (0)
Location: include/linux/highmem.h:397
Inline: False
```
```
In fs/exec.c (ffffffff814854fa)
Location: include/linux/highmem.h:397
Inline: True
Inline callers:
  - fs/exec.c:copy_string_kernel
```
```
In fs/ext4/verity.c (ffffffff815da3b0)
Location: include/linux/highmem.h:397
Inline: True
```
```
In lib/iov_iter.c (ffffffff817d1f44)
Location: include/linux/highmem.h:397
Inline: True
Inline callers:
  - lib/iov_iter.c:copy_pipe_to_iter
```
```
In drivers/base/firmware_loader/sysfs.c (ffffffff81b1309e)
Location: include/linux/highmem.h:397
Inline: True
Inline callers:
  - drivers/base/firmware_loader/sysfs.c:firmware_rw
```
**Symbols:**

```
ffffffff81044ce0-ffffffff81044d34: memcpy_to_page.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/hyperv/hv_init.c (ffffffff81044e20)
Location: include/linux/highmem.h:421
Inline: True
Direct callers:
  - arch/x86/hyperv/hv_init.c:hyperv_init
```
```
In kernel/dma/swiotlb.c (0)
Location: include/linux/highmem.h:421
Inline: False
```
```
In fs/exec.c (ffffffff814ba55a)
Location: include/linux/highmem.h:421
Inline: True
Inline callers:
  - fs/exec.c:copy_string_kernel
```
```
In fs/ext4/verity.c (ffffffff816120ed)
Location: include/linux/highmem.h:421
Inline: True
```
```
In drivers/base/firmware_loader/sysfs.c (ffffffff81b613ae)
Location: include/linux/highmem.h:421
Inline: True
Inline callers:
  - drivers/base/firmware_loader/sysfs.c:firmware_rw
```
**Symbols:**

```
ffffffff81044e20-ffffffff81044e74: memcpy_to_page.constprop.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate, Selective Inline, Transformation ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/hyperv/hv_init.c (ffffffff8104b350)
Location: include/linux/highmem.h:421
Inline: True
Direct callers:
  - arch/x86/hyperv/hv_init.c:hyperv_init
```
```
In kernel/dma/swiotlb.c (0)
Location: include/linux/highmem.h:421
Inline: False
```
```
In fs/exec.c (ffffffff814ecada)
Location: include/linux/highmem.h:421
Inline: True
Inline callers:
  - fs/exec.c:copy_string_kernel
```
```
In fs/ext4/verity.c (ffffffff8164ae8d)
Location: include/linux/highmem.h:421
Inline: True
```
```
In drivers/base/firmware_loader/sysfs.c (ffffffff81bb4e3e)
Location: include/linux/highmem.h:421
Inline: True
Inline callers:
  - drivers/base/firmware_loader/sysfs.c:firmware_rw
```
**Symbols:**

```
ffffffff8104b350-ffffffff8104b3a4: memcpy_to_page.constprop.0 (STB_LOCAL)
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
void memcpy_to_page(struct page *page, size_t offset, const char *from, size_t len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffff80001062d870)
Location: lib/iov_iter.c:464
Inline: False
Direct callers:
  - lib/iov_iter.c:_copy_to_iter
  - lib/iov_iter.c:_copy_to_iter
```
**Symbols:**

```
ffff80001062d870-ffff80001062d8d0: memcpy_to_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void memcpy_to_page(struct page *page, size_t offset, const char *from, size_t len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (c07d4428)
Location: lib/iov_iter.c:464
Inline: False
Direct callers:
  - lib/iov_iter.c:_copy_to_iter
  - lib/iov_iter.c:_copy_to_iter
```
**Symbols:**

```
c07d4428-c07d4464: memcpy_to_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void memcpy_to_page(struct page *page, size_t offset, const char *from, size_t len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (c0000000007d0b70)
Location: lib/iov_iter.c:464
Inline: False
Direct callers:
  - lib/iov_iter.c:_copy_to_iter
  - lib/iov_iter.c:_copy_to_iter
```
**Symbols:**

```
c0000000007d0b70-c0000000007d0bec: memcpy_to_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void memcpy_to_page(struct page *page, size_t offset, const char *from, size_t len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffffffe00045d3c6)
Location: lib/iov_iter.c:464
Inline: False
Direct callers:
  - lib/iov_iter.c:_copy_to_iter
  - lib/iov_iter.c:_copy_to_iter
```
**Symbols:**

```
ffffffe00045d3c6-ffffffe00045d41c: memcpy_to_page (STB_LOCAL)
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
void memcpy_to_page(struct page *page, size_t offset, const char *from, size_t len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffffffff8151bef0)
Location: lib/iov_iter.c:464
Inline: False
Direct callers:
  - lib/iov_iter.c:_copy_to_iter
  - lib/iov_iter.c:_copy_to_iter
```
**Symbols:**

```
ffffffff8151bef0-ffffffff8151bf36: memcpy_to_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void memcpy_to_page(struct page *page, size_t offset, const char *from, size_t len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffffffff8150c1e0)
Location: lib/iov_iter.c:464
Inline: False
Direct callers:
  - lib/iov_iter.c:_copy_to_iter
  - lib/iov_iter.c:_copy_to_iter
```
**Symbols:**

```
ffffffff8150c1e0-ffffffff8150c226: memcpy_to_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void memcpy_to_page(struct page *page, size_t offset, const char *from, size_t len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffffffff81517f80)
Location: lib/iov_iter.c:464
Inline: False
Direct callers:
  - lib/iov_iter.c:_copy_to_iter
  - lib/iov_iter.c:_copy_to_iter
```
**Symbols:**

```
ffffffff81517f80-ffffffff81517fc6: memcpy_to_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void memcpy_to_page(struct page *page, size_t offset, const char *from, size_t len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/iov_iter.c (ffffffff815316d0)
Location: lib/iov_iter.c:464
Inline: False
Direct callers:
  - lib/iov_iter.c:_copy_to_iter
  - lib/iov_iter.c:_copy_to_iter
```
**Symbols:**

```
ffffffff815316d0-ffffffff8153172e: memcpy_to_page (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
