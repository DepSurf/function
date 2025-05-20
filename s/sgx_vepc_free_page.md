# Function: <code>sgx_vepc_free_page</code>

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
int sgx_vepc_free_page(struct sgx_epc_page *epc_page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/sgx/virt.c (ffffffff81069510)
Location: arch/x86/kernel/cpu/sgx/virt.c:114
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/sgx/virt.c:sgx_vepc_release
  - arch/x86/kernel/cpu/sgx/virt.c:sgx_vepc_release
  - arch/x86/kernel/cpu/sgx/virt.c:sgx_vepc_release
```
**Symbols:**

```
ffffffff81069510-ffffffff81069589: sgx_vepc_free_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int sgx_vepc_free_page(struct sgx_epc_page *epc_page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/sgx/virt.c (0)
Location: arch/x86/kernel/cpu/sgx/virt.c:114
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/sgx/virt.c:sgx_vepc_release
  - arch/x86/kernel/cpu/sgx/virt.c:sgx_vepc_release
  - arch/x86/kernel/cpu/sgx/virt.c:sgx_vepc_release
```
**Symbols:**

```
ffffffff81073c30-ffffffff81073cdc: sgx_vepc_free_page (STB_LOCAL)
ffffffff81c9cec5-ffffffff81c9ced9: sgx_vepc_free_page.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int sgx_vepc_free_page(struct sgx_epc_page *epc_page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/sgx/virt.c (0)
Location: arch/x86/kernel/cpu/sgx/virt.c:128
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/sgx/virt.c:sgx_vepc_release
  - arch/x86/kernel/cpu/sgx/virt.c:sgx_vepc_release
  - arch/x86/kernel/cpu/sgx/virt.c:sgx_vepc_release
```
**Symbols:**

```
ffffffff810826a0-ffffffff81082760: sgx_vepc_free_page (STB_LOCAL)
ffffffff81e4c259-ffffffff81e4c26e: sgx_vepc_free_page.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int sgx_vepc_free_page(struct sgx_epc_page *epc_page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/sgx/virt.c (0)
Location: arch/x86/kernel/cpu/sgx/virt.c:128
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/sgx/virt.c:sgx_vepc_release
  - arch/x86/kernel/cpu/sgx/virt.c:sgx_vepc_release
  - arch/x86/kernel/cpu/sgx/virt.c:sgx_vepc_release
```
**Symbols:**

```
ffffffff81095120-ffffffff810951e0: sgx_vepc_free_page (STB_LOCAL)
ffffffff820538cb-ffffffff820538e0: sgx_vepc_free_page.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int sgx_vepc_free_page(struct sgx_epc_page *epc_page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/sgx/virt.c (0)
Location: arch/x86/kernel/cpu/sgx/virt.c:128
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/sgx/virt.c:sgx_vepc_release
  - arch/x86/kernel/cpu/sgx/virt.c:sgx_vepc_release
  - arch/x86/kernel/cpu/sgx/virt.c:sgx_vepc_release
```
**Symbols:**

```
ffffffff810980a0-ffffffff81098160: sgx_vepc_free_page (STB_LOCAL)
ffffffff820d1eb7-ffffffff820d1ecc: sgx_vepc_free_page.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int sgx_vepc_free_page(struct sgx_epc_page *epc_page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/sgx/virt.c (0)
Location: arch/x86/kernel/cpu/sgx/virt.c:128
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/sgx/virt.c:sgx_vepc_release
  - arch/x86/kernel/cpu/sgx/virt.c:sgx_vepc_release
  - arch/x86/kernel/cpu/sgx/virt.c:sgx_vepc_release
```
**Symbols:**

```
ffffffff8109f640-ffffffff8109f700: sgx_vepc_free_page (STB_LOCAL)
ffffffff821acb1b-ffffffff821acb30: sgx_vepc_free_page.cold (STB_LOCAL)
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
