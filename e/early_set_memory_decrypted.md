# Function: <code>early_set_memory_decrypted</code>

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
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int early_set_memory_decrypted(long unsigned int vaddr, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/mem_encrypt.c (ffffffff826c6632)
Location: arch/x86/mm/mem_encrypt.c:382
Inline: False
Direct callers:
  - arch/x86/kernel/kvm.c:kvm_smp_prepare_boot_cpu
  - arch/x86/kernel/kvm.c:kvm_smp_prepare_boot_cpu
  - arch/x86/kernel/kvm.c:kvm_smp_prepare_boot_cpu
```
**Symbols:**

```
ffffffff826c6632-ffffffff826c663f: early_set_memory_decrypted (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int early_set_memory_decrypted(long unsigned int vaddr, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/mem_encrypt.c (ffffffff826efffb)
Location: arch/x86/mm/mem_encrypt.c:316
Inline: False
Direct callers:
  - arch/x86/kernel/kvm.c:kvm_smp_prepare_boot_cpu
  - arch/x86/kernel/kvm.c:kvm_smp_prepare_boot_cpu
  - arch/x86/kernel/kvm.c:kvm_smp_prepare_boot_cpu
```
**Symbols:**

```
ffffffff826efffb-ffffffff826f0008: early_set_memory_decrypted (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int early_set_memory_decrypted(long unsigned int vaddr, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/mem_encrypt.c (ffffffff828a6cb8)
Location: arch/x86/mm/mem_encrypt.c:316
Inline: False
Direct callers:
  - arch/x86/kernel/kvm.c:kvm_smp_prepare_boot_cpu
  - arch/x86/kernel/kvm.c:kvm_smp_prepare_boot_cpu
  - arch/x86/kernel/kvm.c:kvm_smp_prepare_boot_cpu
```
**Symbols:**

```
ffffffff828a6cb8-ffffffff828a6cc5: early_set_memory_decrypted (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int early_set_memory_decrypted(long unsigned int vaddr, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/mem_encrypt.c (ffffffff828bf36a)
Location: arch/x86/mm/mem_encrypt.c:321
Inline: False
Direct callers:
  - arch/x86/kernel/kvm.c:kvm_smp_prepare_boot_cpu
  - arch/x86/kernel/kvm.c:kvm_smp_prepare_boot_cpu
  - arch/x86/kernel/kvm.c:kvm_smp_prepare_boot_cpu
```
**Symbols:**

```
ffffffff828bf36a-ffffffff828bf377: early_set_memory_decrypted (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int early_set_memory_decrypted(long unsigned int vaddr, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/mem_encrypt.c (ffffffff828c57e5)
Location: arch/x86/mm/mem_encrypt.c:321
Inline: False
Direct callers:
  - arch/x86/kernel/kvm.c:kvm_smp_prepare_boot_cpu
  - arch/x86/kernel/kvm.c:kvm_smp_prepare_boot_cpu
  - arch/x86/kernel/kvm.c:kvm_smp_prepare_boot_cpu
```
**Symbols:**

```
ffffffff828c57e5-ffffffff828c57f2: early_set_memory_decrypted (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int early_set_memory_decrypted(long unsigned int vaddr, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/mem_encrypt.c (ffffffff82ce89da)
Location: arch/x86/mm/mem_encrypt.c:321
Inline: False
Direct callers:
  - arch/x86/kernel/kvm.c:sev_map_percpu_data
  - arch/x86/kernel/kvm.c:sev_map_percpu_data
  - arch/x86/kernel/kvm.c:sev_map_percpu_data
```
**Symbols:**

```
ffffffff82ce89da-ffffffff82ce89e7: early_set_memory_decrypted (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int early_set_memory_decrypted(long unsigned int vaddr, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/mem_encrypt.c (ffffffff82fd6432)
Location: arch/x86/mm/mem_encrypt.c:354
Inline: False
Direct callers:
  - arch/x86/kernel/kvm.c:sev_map_percpu_data
  - arch/x86/kernel/kvm.c:sev_map_percpu_data
  - arch/x86/kernel/kvm.c:sev_map_percpu_data
  - arch/x86/kernel/sev-es.c:sev_es_init_vc_handling
```
**Symbols:**

```
ffffffff82fd6432-ffffffff82fd643f: early_set_memory_decrypted (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int early_set_memory_decrypted(long unsigned int vaddr, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/mem_encrypt.c (ffffffff831e0e8a)
Location: arch/x86/mm/mem_encrypt.c:353
Inline: False
Direct callers:
  - arch/x86/kernel/kvm.c:kvm_smp_prepare_boot_cpu
  - arch/x86/kernel/kvm.c:kvm_smp_prepare_boot_cpu
  - arch/x86/kernel/kvm.c:kvm_smp_prepare_boot_cpu
  - arch/x86/kernel/sev.c:sev_es_init_vc_handling
```
**Symbols:**

```
ffffffff831e0e8a-ffffffff831e0e97: early_set_memory_decrypted (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int early_set_memory_decrypted(long unsigned int vaddr, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/mem_encrypt.c (ffffffff832c45a4)
Location: arch/x86/mm/mem_encrypt.c:354
Inline: False
Direct callers:
  - arch/x86/kernel/kvm.c:kvm_smp_prepare_boot_cpu
  - arch/x86/kernel/kvm.c:kvm_smp_prepare_boot_cpu
  - arch/x86/kernel/kvm.c:kvm_smp_prepare_boot_cpu
  - arch/x86/kernel/sev.c:sev_es_init_vc_handling
```
**Symbols:**

```
ffffffff832c45a4-ffffffff832c45b1: early_set_memory_decrypted (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int early_set_memory_decrypted(long unsigned int vaddr, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/mem_encrypt_amd.c (ffffffff83477015)
Location: arch/x86/mm/mem_encrypt_amd.c:472
Inline: False
Direct callers:
  - arch/x86/kernel/kvm.c:kvm_smp_prepare_boot_cpu
  - arch/x86/kernel/kvm.c:kvm_smp_prepare_boot_cpu
  - arch/x86/kernel/kvm.c:kvm_smp_prepare_boot_cpu
  - arch/x86/kernel/sev.c:sev_es_init_vc_handling
```
**Symbols:**

```
ffffffff83477015-ffffffff8347702c: early_set_memory_decrypted (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int early_set_memory_decrypted(long unsigned int vaddr, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/mem_encrypt_amd.c (ffffffff83ea0420)
Location: arch/x86/mm/mem_encrypt_amd.c:473
Inline: False
Direct callers:
  - arch/x86/kernel/kvm.c:kvm_smp_prepare_boot_cpu
  - arch/x86/kernel/kvm.c:kvm_smp_prepare_boot_cpu
  - arch/x86/kernel/kvm.c:kvm_smp_prepare_boot_cpu
  - arch/x86/kernel/sev.c:sev_es_init_vc_handling
```
**Symbols:**

```
ffffffff83ea0420-ffffffff83ea0437: early_set_memory_decrypted (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int early_set_memory_decrypted(long unsigned int vaddr, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/mem_encrypt_amd.c (ffffffff836c45a0)
Location: arch/x86/mm/mem_encrypt_amd.c:474
Inline: False
Direct callers:
  - arch/x86/kernel/kvm.c:kvm_smp_prepare_boot_cpu
  - arch/x86/kernel/kvm.c:kvm_smp_prepare_boot_cpu
  - arch/x86/kernel/kvm.c:kvm_smp_prepare_boot_cpu
  - arch/x86/kernel/sev.c:sev_es_init_vc_handling
```
**Symbols:**

```
ffffffff836c45a0-ffffffff836c45b7: early_set_memory_decrypted (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int early_set_memory_decrypted(long unsigned int vaddr, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/mem_encrypt_amd.c (ffffffff838f51a0)
Location: arch/x86/mm/mem_encrypt_amd.c:439
Inline: False
Direct callers:
  - arch/x86/kernel/kvm.c:kvm_smp_prepare_boot_cpu
  - arch/x86/kernel/kvm.c:kvm_smp_prepare_boot_cpu
  - arch/x86/kernel/kvm.c:kvm_smp_prepare_boot_cpu
  - arch/x86/kernel/sev.c:sev_es_init_vc_handling
```
**Symbols:**

```
ffffffff838f51a0-ffffffff838f51b7: early_set_memory_decrypted (STB_GLOBAL)
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
int early_set_memory_decrypted(long unsigned int vaddr, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/mem_encrypt.c (ffffffff828b077d)
Location: arch/x86/mm/mem_encrypt.c:321
Inline: False
Direct callers:
  - arch/x86/kernel/kvm.c:kvm_smp_prepare_boot_cpu
  - arch/x86/kernel/kvm.c:kvm_smp_prepare_boot_cpu
  - arch/x86/kernel/kvm.c:kvm_smp_prepare_boot_cpu
```
**Symbols:**

```
ffffffff828b077d-ffffffff828b078a: early_set_memory_decrypted (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int early_set_memory_decrypted(long unsigned int vaddr, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/mem_encrypt.c (ffffffff828a8902)
Location: arch/x86/mm/mem_encrypt.c:321
Inline: False
Direct callers:
  - arch/x86/kernel/kvm.c:kvm_smp_prepare_boot_cpu
  - arch/x86/kernel/kvm.c:kvm_smp_prepare_boot_cpu
  - arch/x86/kernel/kvm.c:kvm_smp_prepare_boot_cpu
```
**Symbols:**

```
ffffffff828a8902-ffffffff828a890f: early_set_memory_decrypted (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int early_set_memory_decrypted(long unsigned int vaddr, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/mem_encrypt.c (ffffffff828c367c)
Location: arch/x86/mm/mem_encrypt.c:321
Inline: False
Direct callers:
  - arch/x86/kernel/kvm.c:kvm_smp_prepare_boot_cpu
  - arch/x86/kernel/kvm.c:kvm_smp_prepare_boot_cpu
  - arch/x86/kernel/kvm.c:kvm_smp_prepare_boot_cpu
```
**Symbols:**

```
ffffffff828c367c-ffffffff828c3689: early_set_memory_decrypted (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int early_set_memory_decrypted(long unsigned int vaddr, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/mem_encrypt.c (ffffffff828c6822)
Location: arch/x86/mm/mem_encrypt.c:321
Inline: False
Direct callers:
  - arch/x86/kernel/kvm.c:kvm_smp_prepare_boot_cpu
  - arch/x86/kernel/kvm.c:kvm_smp_prepare_boot_cpu
  - arch/x86/kernel/kvm.c:kvm_smp_prepare_boot_cpu
```
**Symbols:**

```
ffffffff828c6822-ffffffff828c682f: early_set_memory_decrypted (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
