# Function: <code>sgx_encl_free_epc_page</code>

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
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void sgx_encl_free_epc_page(struct sgx_epc_page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/sgx/encl.c (ffffffff81066a00)
Location: arch/x86/kernel/cpu/sgx/encl.c:747
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_alloc_va_page
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_release
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_release
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_release
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_eldu
  - arch/x86/kernel/cpu/sgx/ioctl.c:sgx_encl_add_page
  - arch/x86/kernel/cpu/sgx/ioctl.c:sgx_encl_add_page
  - arch/x86/kernel/cpu/sgx/ioctl.c:sgx_encl_create
  - arch/x86/kernel/cpu/sgx/ioctl.c:sgx_encl_create
  - arch/x86/kernel/cpu/sgx/main.c:sgx_reclaim_pages
```
**Symbols:**

```
ffffffff81066a00-ffffffff81066a69: sgx_encl_free_epc_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void sgx_encl_free_epc_page(struct sgx_epc_page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/sgx/encl.c (0)
Location: arch/x86/kernel/cpu/sgx/encl.c:788
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_alloc_va_page
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_release
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_release
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_release
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_eldu
  - arch/x86/kernel/cpu/sgx/ioctl.c:sgx_encl_add_page
  - arch/x86/kernel/cpu/sgx/ioctl.c:sgx_encl_add_page
  - arch/x86/kernel/cpu/sgx/ioctl.c:sgx_encl_create
  - arch/x86/kernel/cpu/sgx/ioctl.c:sgx_encl_create
  - arch/x86/kernel/cpu/sgx/main.c:sgx_reclaim_pages
```
**Symbols:**

```
ffffffff81c9ce06-ffffffff81c9ce20: sgx_encl_free_epc_page.cold (STB_LOCAL)
ffffffff81070c80-ffffffff81070d22: sgx_encl_free_epc_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void sgx_encl_free_epc_page(struct sgx_epc_page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/sgx/encl.c (0)
Location: arch/x86/kernel/cpu/sgx/encl.c:984
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_alloc_va_page
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_release
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_release
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_release
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_eldu
  - arch/x86/kernel/cpu/sgx/ioctl.c:sgx_encl_add_page
  - arch/x86/kernel/cpu/sgx/ioctl.c:sgx_encl_add_page
  - arch/x86/kernel/cpu/sgx/ioctl.c:sgx_encl_create
  - arch/x86/kernel/cpu/sgx/ioctl.c:sgx_encl_create
  - arch/x86/kernel/cpu/sgx/main.c:sgx_reclaim_pages
```
**Symbols:**

```
ffffffff81e4c199-ffffffff81e4c1bb: sgx_encl_free_epc_page.cold (STB_LOCAL)
ffffffff8107ec20-ffffffff8107ecf1: sgx_encl_free_epc_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void sgx_encl_free_epc_page(struct sgx_epc_page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/sgx/encl.c (0)
Location: arch/x86/kernel/cpu/sgx/encl.c:1292
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_alloc_va_page
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_release
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_release
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_release
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_eaug_page
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_eldu
  - arch/x86/kernel/cpu/sgx/ioctl.c:sgx_encl_remove_pages
  - arch/x86/kernel/cpu/sgx/ioctl.c:sgx_encl_add_page
  - arch/x86/kernel/cpu/sgx/ioctl.c:sgx_encl_add_page
  - arch/x86/kernel/cpu/sgx/ioctl.c:sgx_encl_create
  - arch/x86/kernel/cpu/sgx/ioctl.c:sgx_encl_create
  - arch/x86/kernel/cpu/sgx/main.c:sgx_reclaim_pages
```
**Symbols:**

```
ffffffff8205378e-ffffffff820537b0: sgx_encl_free_epc_page.cold (STB_LOCAL)
ffffffff810904a0-ffffffff81090571: sgx_encl_free_epc_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void sgx_encl_free_epc_page(struct sgx_epc_page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/sgx/encl.c (0)
Location: arch/x86/kernel/cpu/sgx/encl.c:1294
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_alloc_va_page
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_release
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_release
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_release
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_eaug_page
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_eldu
  - arch/x86/kernel/cpu/sgx/ioctl.c:sgx_encl_remove_pages
  - arch/x86/kernel/cpu/sgx/ioctl.c:sgx_encl_add_page
  - arch/x86/kernel/cpu/sgx/ioctl.c:sgx_encl_add_page
  - arch/x86/kernel/cpu/sgx/ioctl.c:sgx_encl_create
  - arch/x86/kernel/cpu/sgx/ioctl.c:sgx_encl_create
  - arch/x86/kernel/cpu/sgx/main.c:sgx_reclaim_pages
```
**Symbols:**

```
ffffffff820d1d81-ffffffff820d1d9b: sgx_encl_free_epc_page.cold (STB_LOCAL)
ffffffff810933d0-ffffffff81093484: sgx_encl_free_epc_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void sgx_encl_free_epc_page(struct sgx_epc_page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/sgx/encl.c (0)
Location: arch/x86/kernel/cpu/sgx/encl.c:1314
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_alloc_va_page
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_release
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_release
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_release
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_eaug_page
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_eldu
  - arch/x86/kernel/cpu/sgx/ioctl.c:sgx_encl_remove_pages
  - arch/x86/kernel/cpu/sgx/ioctl.c:sgx_encl_add_page
  - arch/x86/kernel/cpu/sgx/ioctl.c:sgx_encl_add_page
  - arch/x86/kernel/cpu/sgx/ioctl.c:sgx_encl_create
  - arch/x86/kernel/cpu/sgx/ioctl.c:sgx_encl_create
  - arch/x86/kernel/cpu/sgx/main.c:sgx_reclaim_pages
```
**Symbols:**

```
ffffffff821ac9e5-ffffffff821ac9ff: sgx_encl_free_epc_page.cold (STB_LOCAL)
ffffffff8109a840-ffffffff8109a8f4: sgx_encl_free_epc_page (STB_GLOBAL)
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
