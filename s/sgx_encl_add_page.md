# Function: <code>sgx_encl_add_page</code>

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
int sgx_encl_add_page(struct sgx_encl *encl, long unsigned int src, long unsigned int offset, struct sgx_secinfo *secinfo, long unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/sgx/ioctl.c (ffffffff810676e0)
Location: arch/x86/kernel/cpu/sgx/ioctl.c:289
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/sgx/ioctl.c:sgx_ioc_enclave_add_pages
```
**Symbols:**

```
ffffffff810676e0-ffffffff810679bf: sgx_encl_add_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int sgx_encl_add_page(struct sgx_encl *encl, long unsigned int src, long unsigned int offset, struct sgx_secinfo *secinfo, long unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/sgx/ioctl.c (ffffffff810677d0)
Location: arch/x86/kernel/cpu/sgx/ioctl.c:290
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/sgx/ioctl.c:sgx_ioc_enclave_add_pages
```
**Symbols:**

```
ffffffff810677d0-ffffffff81067b81: sgx_encl_add_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int sgx_encl_add_page(struct sgx_encl *encl, long unsigned int src, long unsigned int offset, struct sgx_secinfo *secinfo, long unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/sgx/ioctl.c (0)
Location: arch/x86/kernel/cpu/sgx/ioctl.c:290
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/sgx/ioctl.c:sgx_ioc_enclave_add_pages
```
**Symbols:**

```
ffffffff81071bb0-ffffffff81071fee: sgx_encl_add_page (STB_LOCAL)
ffffffff81c9ce4e-ffffffff81c9ce70: sgx_encl_add_page.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int sgx_encl_add_page(struct sgx_encl *encl, long unsigned int src, long unsigned int offset, struct sgx_secinfo *secinfo, long unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/sgx/ioctl.c (0)
Location: arch/x86/kernel/cpu/sgx/ioctl.c:290
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/sgx/ioctl.c:sgx_ioc_enclave_add_pages
```
**Symbols:**

```
ffffffff8107ff20-ffffffff810803a5: sgx_encl_add_page (STB_LOCAL)
ffffffff81e4c1e9-ffffffff81e4c203: sgx_encl_add_page.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int sgx_encl_add_page(struct sgx_encl *encl, long unsigned int src, long unsigned int offset, struct sgx_secinfo *secinfo, long unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/sgx/ioctl.c (0)
Location: arch/x86/kernel/cpu/sgx/ioctl.c:259
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/sgx/ioctl.c:sgx_ioc_enclave_add_pages
```
**Symbols:**

```
ffffffff81092870-ffffffff81092cd0: sgx_encl_add_page (STB_LOCAL)
ffffffff82053856-ffffffff82053870: sgx_encl_add_page.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int sgx_encl_add_page(struct sgx_encl *encl, long unsigned int src, long unsigned int offset, struct sgx_secinfo *secinfo, long unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/sgx/ioctl.c (0)
Location: arch/x86/kernel/cpu/sgx/ioctl.c:259
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/sgx/ioctl.c:sgx_ioc_enclave_add_pages
```
**Symbols:**

```
ffffffff810957a0-ffffffff81095c15: sgx_encl_add_page (STB_LOCAL)
ffffffff820d1e41-ffffffff820d1e5b: sgx_encl_add_page.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int sgx_encl_add_page(struct sgx_encl *encl, long unsigned int src, long unsigned int offset, struct sgx_secinfo *secinfo, long unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/cpu/sgx/ioctl.c (0)
Location: arch/x86/kernel/cpu/sgx/ioctl.c:259
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/sgx/ioctl.c:sgx_ioc_enclave_add_pages
```
**Symbols:**

```
ffffffff8109cce0-ffffffff8109d155: sgx_encl_add_page (STB_LOCAL)
ffffffff821acaa5-ffffffff821acabf: sgx_encl_add_page.cold (STB_LOCAL)
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
