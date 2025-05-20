# Function: <code>__sgx_encl_load_page</code>

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
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct sgx_encl_page *__sgx_encl_load_page(struct sgx_encl *encl, struct sgx_encl_page *entry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/sgx/encl.c (ffffffff81090680)
Location: arch/x86/kernel/cpu/sgx/encl.c:238
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_vma_access
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_vma_fault
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_load_page
```
**Symbols:**

```
ffffffff81090680-ffffffff81090702: __sgx_encl_load_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct sgx_encl_page *__sgx_encl_load_page(struct sgx_encl *encl, struct sgx_encl_page *entry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/sgx/encl.c (ffffffff81093590)
Location: arch/x86/kernel/cpu/sgx/encl.c:238
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_vma_access
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_vma_fault
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_load_page
```
**Symbols:**

```
ffffffff81093590-ffffffff81093612: __sgx_encl_load_page (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct sgx_encl_page *__sgx_encl_load_page(struct sgx_encl *encl, struct sgx_encl_page *entry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/sgx/encl.c (ffffffff8109aa00)
Location: arch/x86/kernel/cpu/sgx/encl.c:253
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_vma_access
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_vma_fault
  - arch/x86/kernel/cpu/sgx/encl.c:sgx_encl_load_page
```
**Symbols:**

```
ffffffff8109aa00-ffffffff8109aa84: __sgx_encl_load_page (STB_LOCAL)
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
