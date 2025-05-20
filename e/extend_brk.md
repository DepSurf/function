# Function: <code>extend_brk</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void *extend_brk(size_t size, size_t align);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/setup.c (ffffffff81f65d15)
Location: arch/x86/kernel/setup.c:264
Inline: False
Direct callers:
  - arch/x86/xen/enlighten.c:xen_hvm_init_shared_info
  - arch/x86/mm/init.c:early_alloc_pgt_buf
  - drivers/firmware/dmi_scan.c:dmi_string
  - drivers/firmware/dmi_scan.c:dmi_decode
  - drivers/firmware/dmi_scan.c:dmi_decode
  - drivers/firmware/dmi_scan.c:dmi_decode
  - drivers/firmware/dmi_scan.c:dmi_decode
  - drivers/firmware/dmi_scan.c:dmi_decode
  - drivers/firmware/dmi_scan.c:dmi_decode
  - drivers/firmware/dmi_scan.c:dmi_memdev_walk
```
**Symbols:**

```
ffffffff81f65d15-ffffffff81f65d64: extend_brk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void *extend_brk(size_t size, size_t align);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/setup.c (ffffffff81f8db84)
Location: arch/x86/kernel/setup.c:266
Inline: False
Direct callers:
  - arch/x86/xen/enlighten.c:xen_hvm_init_shared_info
  - arch/x86/mm/init.c:early_alloc_pgt_buf
  - drivers/firmware/dmi_scan.c:dmi_decode
  - drivers/firmware/dmi_scan.c:dmi_decode
  - drivers/firmware/dmi_scan.c:dmi_decode
  - drivers/firmware/dmi_scan.c:dmi_decode
  - drivers/firmware/dmi_scan.c:dmi_decode
  - drivers/firmware/dmi_scan.c:dmi_memdev_walk
  - drivers/firmware/dmi_scan.c:dmi_string
```
**Symbols:**

```
ffffffff81f8db84-ffffffff81f8dbd0: extend_brk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void *extend_brk(size_t size, size_t align);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/setup.c (ffffffff81fc8f48)
Location: arch/x86/kernel/setup.c:266
Inline: False
Direct callers:
  - arch/x86/xen/enlighten.c:xen_hvm_init_shared_info
  - arch/x86/mm/init.c:early_alloc_pgt_buf
  - drivers/firmware/dmi_scan.c:dmi_decode
  - drivers/firmware/dmi_scan.c:dmi_decode
  - drivers/firmware/dmi_scan.c:dmi_decode
  - drivers/firmware/dmi_scan.c:dmi_decode
  - drivers/firmware/dmi_scan.c:dmi_decode
  - drivers/firmware/dmi_scan.c:dmi_memdev_walk
  - drivers/firmware/dmi_scan.c:dmi_string
```
**Symbols:**

```
ffffffff81fc8f48-ffffffff81fc8f94: extend_brk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void *extend_brk(size_t size, size_t align);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/setup.c (ffffffff820a9693)
Location: arch/x86/kernel/setup.c:270
Inline: False
Direct callers:
  - arch/x86/mm/init.c:early_alloc_pgt_buf
  - drivers/firmware/dmi_scan.c:dmi_decode
  - drivers/firmware/dmi_scan.c:dmi_decode
  - drivers/firmware/dmi_scan.c:dmi_decode
  - drivers/firmware/dmi_scan.c:dmi_decode
  - drivers/firmware/dmi_scan.c:dmi_decode
  - drivers/firmware/dmi_scan.c:dmi_memdev_walk
  - drivers/firmware/dmi_scan.c:dmi_save_dev_pciaddr
  - drivers/firmware/dmi_scan.c:dmi_string
```
**Symbols:**

```
ffffffff820a9693-ffffffff820a96e4: extend_brk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void *extend_brk(size_t size, size_t align);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/setup.c (ffffffff826b01dd)
Location: arch/x86/kernel/setup.c:255
Inline: False
Direct callers:
  - arch/x86/mm/init.c:early_alloc_pgt_buf
  - drivers/firmware/dmi_scan.c:dmi_decode
  - drivers/firmware/dmi_scan.c:dmi_decode
  - drivers/firmware/dmi_scan.c:dmi_decode
  - drivers/firmware/dmi_scan.c:dmi_decode
  - drivers/firmware/dmi_scan.c:dmi_decode
  - drivers/firmware/dmi_scan.c:dmi_memdev_walk
  - drivers/firmware/dmi_scan.c:dmi_save_dev_pciaddr
  - drivers/firmware/dmi_scan.c:dmi_string
```
**Symbols:**

```
ffffffff826b01dd-ffffffff826b022e: extend_brk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void *extend_brk(size_t size, size_t align);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/setup.c (ffffffff826d9875)
Location: arch/x86/kernel/setup.c:253
Inline: False
Direct callers:
  - arch/x86/mm/init.c:early_alloc_pgt_buf
  - drivers/firmware/dmi_scan.c:dmi_decode
  - drivers/firmware/dmi_scan.c:dmi_decode
  - drivers/firmware/dmi_scan.c:dmi_decode
  - drivers/firmware/dmi_scan.c:dmi_decode
  - drivers/firmware/dmi_scan.c:dmi_decode
  - drivers/firmware/dmi_scan.c:dmi_memdev_walk
  - drivers/firmware/dmi_scan.c:dmi_save_dev_pciaddr
  - drivers/firmware/dmi_scan.c:dmi_save_one_device
  - drivers/firmware/dmi_scan.c:dmi_string
```
**Symbols:**

```
ffffffff826d9875-ffffffff826d98c6: extend_brk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void *extend_brk(size_t size, size_t align);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/setup.c (ffffffff8288fc59)
Location: arch/x86/kernel/setup.c:253
Inline: False
Direct callers:
  - arch/x86/mm/init.c:early_alloc_pgt_buf
  - arch/x86/mm/init.c:alloc_low_pages
  - drivers/firmware/dmi_scan.c:dmi_decode
  - drivers/firmware/dmi_scan.c:dmi_decode
  - drivers/firmware/dmi_scan.c:dmi_decode
  - drivers/firmware/dmi_scan.c:dmi_decode
  - drivers/firmware/dmi_scan.c:dmi_decode
  - drivers/firmware/dmi_scan.c:dmi_memdev_walk
  - drivers/firmware/dmi_scan.c:dmi_save_dev_pciaddr
  - drivers/firmware/dmi_scan.c:dmi_save_one_device
  - drivers/firmware/dmi_scan.c:dmi_string
```
**Symbols:**

```
ffffffff8288fc59-ffffffff8288fcaa: extend_brk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void *extend_brk(size_t size, size_t align);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/setup.c (ffffffff828a7464)
Location: arch/x86/kernel/setup.c:255
Inline: False
Direct callers:
  - arch/x86/mm/init.c:early_alloc_pgt_buf
  - arch/x86/mm/init.c:alloc_low_pages
  - drivers/firmware/dmi_scan.c:dmi_setup
  - drivers/firmware/dmi_scan.c:dmi_decode
  - drivers/firmware/dmi_scan.c:dmi_decode
  - drivers/firmware/dmi_scan.c:dmi_decode
  - drivers/firmware/dmi_scan.c:dmi_decode
  - drivers/firmware/dmi_scan.c:dmi_decode
  - drivers/firmware/dmi_scan.c:dmi_save_dev_pciaddr
  - drivers/firmware/dmi_scan.c:dmi_save_one_device
  - drivers/firmware/dmi_scan.c:dmi_string
```
**Symbols:**

```
ffffffff828a7464-ffffffff828a74b8: extend_brk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void *extend_brk(size_t size, size_t align);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/setup.c (ffffffff828aa49c)
Location: arch/x86/kernel/setup.c:255
Inline: False
Direct callers:
  - arch/x86/mm/init.c:early_alloc_pgt_buf
  - arch/x86/mm/init.c:alloc_low_pages
  - drivers/firmware/dmi_scan.c:dmi_setup
  - drivers/firmware/dmi_scan.c:dmi_decode
  - drivers/firmware/dmi_scan.c:dmi_decode
  - drivers/firmware/dmi_scan.c:dmi_decode
  - drivers/firmware/dmi_scan.c:dmi_decode
  - drivers/firmware/dmi_scan.c:dmi_decode
  - drivers/firmware/dmi_scan.c:dmi_save_dev_pciaddr
  - drivers/firmware/dmi_scan.c:dmi_save_one_device
  - drivers/firmware/dmi_scan.c:dmi_string
```
**Symbols:**

```
ffffffff828aa49c-ffffffff828aa4f0: extend_brk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void *extend_brk(size_t size, size_t align);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/setup.c (ffffffff82ccf85d)
Location: arch/x86/kernel/setup.c:195
Inline: False
Direct callers:
  - arch/x86/mm/init.c:early_alloc_pgt_buf
  - arch/x86/mm/init.c:alloc_low_pages
  - drivers/firmware/dmi_scan.c:dmi_setup
  - drivers/firmware/dmi_scan.c:dmi_decode
  - drivers/firmware/dmi_scan.c:dmi_decode
  - drivers/firmware/dmi_scan.c:dmi_save_dev_pciaddr
  - drivers/firmware/dmi_scan.c:dmi_save_ipmi_device
  - drivers/firmware/dmi_scan.c:dmi_save_ipmi_device
  - drivers/firmware/dmi_scan.c:dmi_save_one_device
  - drivers/firmware/dmi_scan.c:dmi_save_release
  - drivers/firmware/dmi_scan.c:dmi_string
```
**Symbols:**

```
ffffffff82ccf85d-ffffffff82ccf8ae: extend_brk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void *extend_brk(size_t size, size_t align);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/setup.c (ffffffff82fbb689)
Location: arch/x86/kernel/setup.c:194
Inline: False
Direct callers:
  - arch/x86/mm/init.c:early_alloc_pgt_buf
  - arch/x86/mm/init.c:alloc_low_pages
  - drivers/firmware/dmi_scan.c:dmi_setup
  - drivers/firmware/dmi_scan.c:dmi_decode
  - drivers/firmware/dmi_scan.c:dmi_decode
  - drivers/firmware/dmi_scan.c:dmi_save_dev_pciaddr
  - drivers/firmware/dmi_scan.c:dmi_save_ipmi_device
  - drivers/firmware/dmi_scan.c:dmi_save_ipmi_device
  - drivers/firmware/dmi_scan.c:dmi_save_one_device
  - drivers/firmware/dmi_scan.c:dmi_save_release
  - drivers/firmware/dmi_scan.c:dmi_string
```
**Symbols:**

```
ffffffff82fbb689-ffffffff82fbb6da: extend_brk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void *extend_brk(size_t size, size_t align);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/setup.c (ffffffff831c5d34)
Location: arch/x86/kernel/setup.c:194
Inline: False
Direct callers:
  - arch/x86/mm/init.c:early_alloc_pgt_buf
  - arch/x86/mm/init.c:alloc_low_pages
  - drivers/firmware/dmi_scan.c:dmi_setup
  - drivers/firmware/dmi_scan.c:dmi_decode
  - drivers/firmware/dmi_scan.c:dmi_decode
  - drivers/firmware/dmi_scan.c:dmi_decode
  - drivers/firmware/dmi_scan.c:dmi_decode
  - drivers/firmware/dmi_scan.c:dmi_decode
  - drivers/firmware/dmi_scan.c:dmi_save_dev_pciaddr
  - drivers/firmware/dmi_scan.c:dmi_save_one_device
  - drivers/firmware/dmi_scan.c:dmi_save_release
  - drivers/firmware/dmi_scan.c:dmi_string
```
**Symbols:**

```
ffffffff831c5d34-ffffffff831c5d85: extend_brk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void *extend_brk(size_t size, size_t align);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/setup.c (ffffffff832a6ca4)
Location: arch/x86/kernel/setup.c:196
Inline: False
Direct callers:
  - arch/x86/mm/init.c:early_alloc_pgt_buf
  - arch/x86/mm/init.c:alloc_low_pages
  - drivers/firmware/dmi_scan.c:dmi_setup
  - drivers/firmware/dmi_scan.c:dmi_decode
  - drivers/firmware/dmi_scan.c:dmi_decode
  - drivers/firmware/dmi_scan.c:dmi_decode
  - drivers/firmware/dmi_scan.c:dmi_decode
  - drivers/firmware/dmi_scan.c:dmi_decode
  - drivers/firmware/dmi_scan.c:dmi_save_dev_pciaddr
  - drivers/firmware/dmi_scan.c:dmi_save_one_device
  - drivers/firmware/dmi_scan.c:dmi_save_release
  - drivers/firmware/dmi_scan.c:dmi_string
```
**Symbols:**

```
ffffffff832a6ca4-ffffffff832a6cf5: extend_brk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void *extend_brk(size_t size, size_t align);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/setup.c (ffffffff83455f4d)
Location: arch/x86/kernel/setup.c:192
Inline: False
Direct callers:
  - arch/x86/mm/init.c:early_alloc_pgt_buf
  - arch/x86/mm/init.c:alloc_low_pages
  - drivers/firmware/dmi_scan.c:dmi_setup
  - drivers/firmware/dmi_scan.c:dmi_decode
  - drivers/firmware/dmi_scan.c:dmi_decode
  - drivers/firmware/dmi_scan.c:dmi_decode
  - drivers/firmware/dmi_scan.c:dmi_decode
  - drivers/firmware/dmi_scan.c:dmi_decode
  - drivers/firmware/dmi_scan.c:dmi_save_dev_pciaddr
  - drivers/firmware/dmi_scan.c:dmi_save_one_device
  - drivers/firmware/dmi_scan.c:dmi_save_release
  - drivers/firmware/dmi_scan.c:dmi_string
```
**Symbols:**

```
ffffffff83455f4d-ffffffff83455faa: extend_brk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void *extend_brk(size_t size, size_t align);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/setup.c (ffffffff83e741e0)
Location: arch/x86/kernel/setup.c:201
Inline: False
Direct callers:
  - arch/x86/mm/init.c:early_alloc_pgt_buf
  - arch/x86/mm/init.c:alloc_low_pages
  - drivers/firmware/dmi_scan.c:dmi_setup
  - drivers/firmware/dmi_scan.c:dmi_decode
  - drivers/firmware/dmi_scan.c:dmi_decode
  - drivers/firmware/dmi_scan.c:dmi_decode
  - drivers/firmware/dmi_scan.c:dmi_save_dev_pciaddr
  - drivers/firmware/dmi_scan.c:dmi_save_ipmi_device
  - drivers/firmware/dmi_scan.c:dmi_save_ipmi_device
  - drivers/firmware/dmi_scan.c:dmi_save_one_device
  - drivers/firmware/dmi_scan.c:dmi_save_release
  - drivers/firmware/dmi_scan.c:dmi_string
```
**Symbols:**

```
ffffffff83e741e0-ffffffff83e7423d: extend_brk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void *extend_brk(size_t size, size_t align);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/setup.c (ffffffff83695cb0)
Location: arch/x86/kernel/setup.c:195
Inline: False
Direct callers:
  - arch/x86/mm/init.c:early_alloc_pgt_buf
  - arch/x86/mm/init.c:alloc_low_pages
  - drivers/firmware/dmi_scan.c:dmi_setup
  - drivers/firmware/dmi_scan.c:dmi_decode
  - drivers/firmware/dmi_scan.c:dmi_decode
  - drivers/firmware/dmi_scan.c:dmi_decode
  - drivers/firmware/dmi_scan.c:dmi_save_dev_pciaddr
  - drivers/firmware/dmi_scan.c:dmi_save_ipmi_device
  - drivers/firmware/dmi_scan.c:dmi_save_ipmi_device
  - drivers/firmware/dmi_scan.c:dmi_save_one_device
  - drivers/firmware/dmi_scan.c:dmi_save_release
  - drivers/firmware/dmi_scan.c:dmi_string
```
**Symbols:**

```
ffffffff83695cb0-ffffffff83695d0d: extend_brk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void *extend_brk(size_t size, size_t align);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/setup.c (ffffffff838c58f0)
Location: arch/x86/kernel/setup.c:194
Inline: False
Direct callers:
  - arch/x86/mm/init.c:early_alloc_pgt_buf
  - arch/x86/mm/init.c:alloc_low_pages
  - drivers/firmware/dmi_scan.c:dmi_setup
  - drivers/firmware/dmi_scan.c:dmi_decode
  - drivers/firmware/dmi_scan.c:dmi_decode
  - drivers/firmware/dmi_scan.c:dmi_decode
  - drivers/firmware/dmi_scan.c:dmi_save_dev_pciaddr
  - drivers/firmware/dmi_scan.c:dmi_save_ipmi_device
  - drivers/firmware/dmi_scan.c:dmi_save_ipmi_device
  - drivers/firmware/dmi_scan.c:dmi_save_one_device
  - drivers/firmware/dmi_scan.c:dmi_save_release
  - drivers/firmware/dmi_scan.c:dmi_string
```
**Symbols:**

```
ffffffff838c58f0-ffffffff838c594d: extend_brk (STB_GLOBAL)
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
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
void *extend_brk(size_t size, size_t align);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/setup.c (ffffffff828984ac)
Location: arch/x86/kernel/setup.c:255
Inline: False
Direct callers:
  - arch/x86/mm/init.c:early_alloc_pgt_buf
  - arch/x86/mm/init.c:alloc_low_pages
  - drivers/firmware/dmi_scan.c:dmi_setup
  - drivers/firmware/dmi_scan.c:dmi_decode
  - drivers/firmware/dmi_scan.c:dmi_decode
  - drivers/firmware/dmi_scan.c:dmi_decode
  - drivers/firmware/dmi_scan.c:dmi_decode
  - drivers/firmware/dmi_scan.c:dmi_decode
  - drivers/firmware/dmi_scan.c:dmi_save_dev_pciaddr
  - drivers/firmware/dmi_scan.c:dmi_save_one_device
  - drivers/firmware/dmi_scan.c:dmi_string
```
**Symbols:**

```
ffffffff828984ac-ffffffff82898500: extend_brk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void *extend_brk(size_t size, size_t align);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/setup.c (ffffffff828907bc)
Location: arch/x86/kernel/setup.c:255
Inline: False
Direct callers:
  - arch/x86/mm/init.c:early_alloc_pgt_buf
  - arch/x86/mm/init.c:alloc_low_pages
  - drivers/firmware/dmi_scan.c:dmi_setup
  - drivers/firmware/dmi_scan.c:dmi_decode
  - drivers/firmware/dmi_scan.c:dmi_decode
  - drivers/firmware/dmi_scan.c:dmi_decode
  - drivers/firmware/dmi_scan.c:dmi_decode
  - drivers/firmware/dmi_scan.c:dmi_decode
  - drivers/firmware/dmi_scan.c:dmi_save_dev_pciaddr
  - drivers/firmware/dmi_scan.c:dmi_save_one_device
  - drivers/firmware/dmi_scan.c:dmi_string
```
**Symbols:**

```
ffffffff828907bc-ffffffff82890810: extend_brk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void *extend_brk(size_t size, size_t align);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/setup.c (ffffffff828ab49c)
Location: arch/x86/kernel/setup.c:255
Inline: False
Direct callers:
  - arch/x86/mm/init.c:early_alloc_pgt_buf
  - arch/x86/mm/init.c:alloc_low_pages
  - drivers/firmware/dmi_scan.c:dmi_setup
  - drivers/firmware/dmi_scan.c:dmi_decode
  - drivers/firmware/dmi_scan.c:dmi_decode
  - drivers/firmware/dmi_scan.c:dmi_decode
  - drivers/firmware/dmi_scan.c:dmi_decode
  - drivers/firmware/dmi_scan.c:dmi_decode
  - drivers/firmware/dmi_scan.c:dmi_save_dev_pciaddr
  - drivers/firmware/dmi_scan.c:dmi_save_one_device
  - drivers/firmware/dmi_scan.c:dmi_string
```
**Symbols:**

```
ffffffff828ab49c-ffffffff828ab4f0: extend_brk (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void *extend_brk(size_t size, size_t align);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/setup.c (ffffffff828ab4ac)
Location: arch/x86/kernel/setup.c:255
Inline: False
Direct callers:
  - arch/x86/mm/init.c:early_alloc_pgt_buf
  - arch/x86/mm/init.c:alloc_low_pages
  - drivers/firmware/dmi_scan.c:dmi_setup
  - drivers/firmware/dmi_scan.c:dmi_decode
  - drivers/firmware/dmi_scan.c:dmi_decode
  - drivers/firmware/dmi_scan.c:dmi_decode
  - drivers/firmware/dmi_scan.c:dmi_decode
  - drivers/firmware/dmi_scan.c:dmi_decode
  - drivers/firmware/dmi_scan.c:dmi_save_dev_pciaddr
  - drivers/firmware/dmi_scan.c:dmi_save_one_device
  - drivers/firmware/dmi_scan.c:dmi_string
```
**Symbols:**

```
ffffffff828ab4ac-ffffffff828ab500: extend_brk (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
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
