# Function: <code>sgx_free_epc_page</code>

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
<summary>In <code>5.11</code>: ✅</summary>

```c
void sgx_free_epc_page(struct sgx_epc_page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/sgx/main.c (ffffffff81068720)
Location: arch/x86/kernel/cpu/sgx/main.c:603
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
  - arch/x86/kernel/cpu/sgx/main.c:sgx_reclaimer_write
```
**Symbols:**

```
ffffffff81068720-ffffffff810687df: sgx_free_epc_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void sgx_free_epc_page(struct sgx_epc_page *page);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/sgx/main.c (ffffffff81068a67)
Location: arch/x86/kernel/cpu/sgx/main.c:620
Inline: True
Direct callers:
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_free_epc_page
  - arch/x86/kernel/cpu/sgx/virt.c:sgx_vepc_free_page
  - arch/x86/kernel/cpu/sgx/virt.c:sgx_vepc_fault
  - arch/x86/kernel/cpu/sgx/virt.c:sgx_vepc_fault
```
**Symbols:**

```
ffffffff81069360-ffffffff810693bd: sgx_free_epc_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void sgx_free_epc_page(struct sgx_epc_page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/sgx/main.c (ffffffff810736b0)
Location: arch/x86/kernel/cpu/sgx/main.c:620
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_free_epc_page
  - arch/x86/kernel/cpu/sgx/virt.c:sgx_vepc_free_page
  - arch/x86/kernel/cpu/sgx/virt.c:sgx_vepc_fault
  - arch/x86/kernel/cpu/sgx/virt.c:sgx_vepc_fault
```
**Symbols:**

```
ffffffff810736b0-ffffffff81073726: sgx_free_epc_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void sgx_free_epc_page(struct sgx_epc_page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/sgx/main.c (ffffffff81081470)
Location: arch/x86/kernel/cpu/sgx/main.c:644
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_free_epc_page
  - arch/x86/kernel/cpu/sgx/main.c:sgx_reclaim_pages
  - arch/x86/kernel/cpu/sgx/virt.c:sgx_vepc_free_page
  - arch/x86/kernel/cpu/sgx/virt.c:sgx_vepc_fault
  - arch/x86/kernel/cpu/sgx/virt.c:sgx_vepc_fault
```
**Symbols:**

```
ffffffff81081470-ffffffff8108152c: sgx_free_epc_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void sgx_free_epc_page(struct sgx_epc_page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/sgx/main.c (ffffffff81093d40)
Location: arch/x86/kernel/cpu/sgx/main.c:602
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_free_epc_page
  - arch/x86/kernel/cpu/sgx/main.c:sgx_reclaim_pages
  - arch/x86/kernel/cpu/sgx/virt.c:sgx_vepc_free_page
  - arch/x86/kernel/cpu/sgx/virt.c:sgx_vepc_fault
  - arch/x86/kernel/cpu/sgx/virt.c:sgx_vepc_fault
```
**Symbols:**

```
ffffffff81093d40-ffffffff81093dfc: sgx_free_epc_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void sgx_free_epc_page(struct sgx_epc_page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/sgx/main.c (ffffffff81096cd0)
Location: arch/x86/kernel/cpu/sgx/main.c:602
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_free_epc_page
  - arch/x86/kernel/cpu/sgx/main.c:sgx_reclaim_pages
  - arch/x86/kernel/cpu/sgx/virt.c:sgx_vepc_free_page
  - arch/x86/kernel/cpu/sgx/virt.c:sgx_vepc_fault
  - arch/x86/kernel/cpu/sgx/virt.c:sgx_vepc_fault
```
**Symbols:**

```
ffffffff81096cd0-ffffffff81096d90: sgx_free_epc_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void sgx_free_epc_page(struct sgx_epc_page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/sgx/main.c (ffffffff8109e240)
Location: arch/x86/kernel/cpu/sgx/main.c:602
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_free_epc_page
  - arch/x86/kernel/cpu/sgx/main.c:sgx_reclaim_pages
  - arch/x86/kernel/cpu/sgx/virt.c:sgx_vepc_free_page
  - arch/x86/kernel/cpu/sgx/virt.c:sgx_vepc_fault
  - arch/x86/kernel/cpu/sgx/virt.c:sgx_vepc_fault
```
**Symbols:**

```
ffffffff8109e240-ffffffff8109e300: sgx_free_epc_page (STB_GLOBAL)
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
