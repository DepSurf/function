# Function: <code>sgx_alloc_va_page</code>

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
struct sgx_epc_page *sgx_alloc_va_page();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/sgx/encl.c (ffffffff81066b10)
Location: arch/x86/kernel/cpu/sgx/encl.c:685
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/sgx/ioctl.c:sgx_encl_grow
```
**Symbols:**

```
ffffffff81066b10-ffffffff81066baa: sgx_alloc_va_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct sgx_epc_page *sgx_alloc_va_page();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/sgx/encl.c (ffffffff81067230)
Location: arch/x86/kernel/cpu/sgx/encl.c:677
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/sgx/ioctl.c:sgx_encl_grow
```
**Symbols:**

```
ffffffff81067230-ffffffff810672c8: sgx_alloc_va_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
struct sgx_epc_page *sgx_alloc_va_page();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/sgx/encl.c (0)
Location: arch/x86/kernel/cpu/sgx/encl.c:718
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/sgx/ioctl.c:sgx_encl_grow
```
**Symbols:**

```
ffffffff81c9ce20-ffffffff81c9ce3a: sgx_alloc_va_page.cold (STB_LOCAL)
ffffffff81071570-ffffffff8107163e: sgx_alloc_va_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
struct sgx_epc_page *sgx_alloc_va_page();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/sgx/encl.c (0)
Location: arch/x86/kernel/cpu/sgx/encl.c:914
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/sgx/ioctl.c:sgx_encl_grow
```
**Symbols:**

```
ffffffff81e4c1bb-ffffffff81e4c1d5: sgx_alloc_va_page.cold (STB_LOCAL)
ffffffff8107f500-ffffffff8107f5e6: sgx_alloc_va_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
struct sgx_epc_page *sgx_alloc_va_page(bool reclaim);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/sgx/encl.c (0)
Location: arch/x86/kernel/cpu/sgx/encl.c:1222
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/sgx/ioctl.c:sgx_encl_grow
```
**Symbols:**

```
ffffffff820537b0-ffffffff820537ca: sgx_alloc_va_page.cold (STB_LOCAL)
ffffffff81091370-ffffffff81091455: sgx_alloc_va_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
struct sgx_epc_page *sgx_alloc_va_page(bool reclaim);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/sgx/encl.c (0)
Location: arch/x86/kernel/cpu/sgx/encl.c:1224
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/sgx/ioctl.c:sgx_encl_grow
```
**Symbols:**

```
ffffffff820d1d9b-ffffffff820d1db5: sgx_alloc_va_page.cold (STB_LOCAL)
ffffffff810942b0-ffffffff81094395: sgx_alloc_va_page (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
struct sgx_epc_page *sgx_alloc_va_page(bool reclaim);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/sgx/encl.c (0)
Location: arch/x86/kernel/cpu/sgx/encl.c:1244
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/sgx/ioctl.c:sgx_encl_grow
```
**Symbols:**

```
ffffffff821ac9ff-ffffffff821aca19: sgx_alloc_va_page.cold (STB_LOCAL)
ffffffff8109b790-ffffffff8109b875: sgx_alloc_va_page (STB_GLOBAL)
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
<details>
<summary>Changed between <code>5.19</code> and <code>6.2</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>bool reclaim</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
