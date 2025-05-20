# Function: <code>sgx_encl_shrink</code>

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
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/sgx/ioctl.c (ffffffff810678df)
Location: arch/x86/kernel/cpu/sgx/ioctl.c:45
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/ioctl.c:sgx_encl_add_page
  - arch/x86/kernel/cpu/sgx/ioctl.c:sgx_encl_add_page
  - arch/x86/kernel/cpu/sgx/ioctl.c:sgx_encl_create
  - arch/x86/kernel/cpu/sgx/ioctl.c:sgx_encl_create
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/sgx/ioctl.c (ffffffff81067a65)
Location: arch/x86/kernel/cpu/sgx/ioctl.c:46
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/ioctl.c:sgx_encl_add_page
  - arch/x86/kernel/cpu/sgx/ioctl.c:sgx_encl_add_page
  - arch/x86/kernel/cpu/sgx/ioctl.c:sgx_encl_create
  - arch/x86/kernel/cpu/sgx/ioctl.c:sgx_encl_create
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/sgx/ioctl.c (ffffffff81071e66)
Location: arch/x86/kernel/cpu/sgx/ioctl.c:46
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/ioctl.c:sgx_encl_add_page
  - arch/x86/kernel/cpu/sgx/ioctl.c:sgx_encl_add_page
  - arch/x86/kernel/cpu/sgx/ioctl.c:sgx_encl_create
  - arch/x86/kernel/cpu/sgx/ioctl.c:sgx_encl_create
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/sgx/ioctl.c (ffffffff8108017f)
Location: arch/x86/kernel/cpu/sgx/ioctl.c:46
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/ioctl.c:sgx_encl_add_page
  - arch/x86/kernel/cpu/sgx/ioctl.c:sgx_encl_add_page
  - arch/x86/kernel/cpu/sgx/ioctl.c:sgx_encl_create
  - arch/x86/kernel/cpu/sgx/ioctl.c:sgx_encl_create
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void sgx_encl_shrink(struct sgx_encl *encl, struct sgx_va_page *va_page);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/sgx/ioctl.c (ffffffff8109167b)
Location: arch/x86/kernel/cpu/sgx/ioctl.c:46
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/ioctl.c:sgx_encl_remove_pages
  - arch/x86/kernel/cpu/sgx/ioctl.c:sgx_encl_add_page
  - arch/x86/kernel/cpu/sgx/ioctl.c:sgx_encl_add_page
  - arch/x86/kernel/cpu/sgx/ioctl.c:sgx_encl_create
  - arch/x86/kernel/cpu/sgx/ioctl.c:sgx_encl_create
Direct callers:
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_eaug_page
```
**Symbols:**

```
ffffffff81092f40-ffffffff81092faa: sgx_encl_shrink (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void sgx_encl_shrink(struct sgx_encl *encl, struct sgx_va_page *va_page);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/sgx/ioctl.c (ffffffff810945bb)
Location: arch/x86/kernel/cpu/sgx/ioctl.c:46
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/ioctl.c:sgx_encl_remove_pages
  - arch/x86/kernel/cpu/sgx/ioctl.c:sgx_encl_add_page
  - arch/x86/kernel/cpu/sgx/ioctl.c:sgx_encl_add_page
  - arch/x86/kernel/cpu/sgx/ioctl.c:sgx_encl_create
  - arch/x86/kernel/cpu/sgx/ioctl.c:sgx_encl_create
Direct callers:
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_eaug_page
```
**Symbols:**

```
ffffffff81095e90-ffffffff81095efa: sgx_encl_shrink (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void sgx_encl_shrink(struct sgx_encl *encl, struct sgx_va_page *va_page);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/sgx/ioctl.c (ffffffff8109ba9b)
Location: arch/x86/kernel/cpu/sgx/ioctl.c:46
Inline: True
Inline callers:
  - arch/x86/kernel/cpu/sgx/ioctl.c:sgx_encl_remove_pages
  - arch/x86/kernel/cpu/sgx/ioctl.c:sgx_encl_add_page
  - arch/x86/kernel/cpu/sgx/ioctl.c:sgx_encl_add_page
  - arch/x86/kernel/cpu/sgx/ioctl.c:sgx_encl_create
  - arch/x86/kernel/cpu/sgx/ioctl.c:sgx_encl_create
Direct callers:
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_eaug_page
```
**Symbols:**

```
ffffffff8109d3d0-ffffffff8109d43a: sgx_encl_shrink (STB_GLOBAL)
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
