# Function: <code>sgx_zap_enclave_ptes</code>

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
void sgx_zap_enclave_ptes(struct sgx_encl *encl, long unsigned int addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/sgx/encl.c (ffffffff81090260)
Location: arch/x86/kernel/cpu/sgx/encl.c:1177
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/sgx/ioctl.c:sgx_encl_remove_pages
  - arch/x86/kernel/cpu/sgx/ioctl.c:sgx_enclave_modify_types
  - arch/x86/kernel/cpu/sgx/main.c:sgx_reclaim_pages
```
**Symbols:**

```
ffffffff81090260-ffffffff810903ca: sgx_zap_enclave_ptes (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void sgx_zap_enclave_ptes(struct sgx_encl *encl, long unsigned int addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/sgx/encl.c (ffffffff81093170)
Location: arch/x86/kernel/cpu/sgx/encl.c:1179
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/sgx/ioctl.c:sgx_encl_remove_pages
  - arch/x86/kernel/cpu/sgx/ioctl.c:sgx_enclave_modify_types
  - arch/x86/kernel/cpu/sgx/main.c:sgx_reclaim_pages
```
**Symbols:**

```
ffffffff81093170-ffffffff810932f2: sgx_zap_enclave_ptes (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void sgx_zap_enclave_ptes(struct sgx_encl *encl, long unsigned int addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/cpu/sgx/encl.c (ffffffff8109a5e0)
Location: arch/x86/kernel/cpu/sgx/encl.c:1199
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/sgx/ioctl.c:sgx_encl_remove_pages
  - arch/x86/kernel/cpu/sgx/ioctl.c:sgx_enclave_modify_types
  - arch/x86/kernel/cpu/sgx/main.c:sgx_reclaim_pages
```
**Symbols:**

```
ffffffff8109a5e0-ffffffff8109a762: sgx_zap_enclave_ptes (STB_GLOBAL)
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
