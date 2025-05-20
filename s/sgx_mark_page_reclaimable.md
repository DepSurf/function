# Function: <code>sgx_mark_page_reclaimable</code>

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
void sgx_mark_page_reclaimable(struct sgx_epc_page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/sgx/main.c (ffffffff81068640)
Location: arch/x86/kernel/cpu/sgx/main.c:510
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_load_page
  - arch/x86/kernel/cpu/sgx/ioctl.c:sgx_encl_add_page
```
**Symbols:**

```
ffffffff81068640-ffffffff81068692: sgx_mark_page_reclaimable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void sgx_mark_page_reclaimable(struct sgx_epc_page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/sgx/main.c (ffffffff810691c0)
Location: arch/x86/kernel/cpu/sgx/main.c:524
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_load_page
  - arch/x86/kernel/cpu/sgx/ioctl.c:sgx_encl_add_page
```
**Symbols:**

```
ffffffff810691c0-ffffffff81069212: sgx_mark_page_reclaimable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void sgx_mark_page_reclaimable(struct sgx_epc_page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/sgx/main.c (ffffffff81073500)
Location: arch/x86/kernel/cpu/sgx/main.c:524
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_load_page
  - arch/x86/kernel/cpu/sgx/ioctl.c:sgx_encl_add_page
```
**Symbols:**

```
ffffffff81073500-ffffffff81073552: sgx_mark_page_reclaimable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void sgx_mark_page_reclaimable(struct sgx_epc_page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/sgx/main.c (ffffffff81081380)
Location: arch/x86/kernel/cpu/sgx/main.c:548
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_load_page
  - arch/x86/kernel/cpu/sgx/ioctl.c:sgx_encl_add_page
```
**Symbols:**

```
ffffffff81081380-ffffffff810813db: sgx_mark_page_reclaimable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void sgx_mark_page_reclaimable(struct sgx_epc_page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/sgx/main.c (ffffffff81093c30)
Location: arch/x86/kernel/cpu/sgx/main.c:506
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_eaug_page
  - arch/x86/kernel/cpu/sgx/encl.c:__sgx_encl_load_page
  - arch/x86/kernel/cpu/sgx/ioctl.c:sgx_enclave_modify_types
  - arch/x86/kernel/cpu/sgx/ioctl.c:sgx_encl_add_page
```
**Symbols:**

```
ffffffff81093c30-ffffffff81093c8b: sgx_mark_page_reclaimable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void sgx_mark_page_reclaimable(struct sgx_epc_page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/sgx/main.c (ffffffff81096bc0)
Location: arch/x86/kernel/cpu/sgx/main.c:506
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_eaug_page
  - arch/x86/kernel/cpu/sgx/encl.c:__sgx_encl_load_page
  - arch/x86/kernel/cpu/sgx/ioctl.c:sgx_enclave_modify_types
  - arch/x86/kernel/cpu/sgx/ioctl.c:sgx_encl_add_page
```
**Symbols:**

```
ffffffff81096bc0-ffffffff81096c1b: sgx_mark_page_reclaimable (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void sgx_mark_page_reclaimable(struct sgx_epc_page *page);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/sgx/main.c (ffffffff8109e130)
Location: arch/x86/kernel/cpu/sgx/main.c:506
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_eaug_page
  - arch/x86/kernel/cpu/sgx/encl.c:__sgx_encl_load_page
  - arch/x86/kernel/cpu/sgx/ioctl.c:sgx_enclave_modify_types
  - arch/x86/kernel/cpu/sgx/ioctl.c:sgx_encl_add_page
```
**Symbols:**

```
ffffffff8109e130-ffffffff8109e18b: sgx_mark_page_reclaimable (STB_GLOBAL)
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
