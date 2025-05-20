# Function: <code>page_level_shift</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pageattr.c (0)
Location: arch/x86/include/asm/pgtable.h:862
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pageattr.c (ffffffff8106d773)
Location: arch/x86/include/asm/pgtable.h:910
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:__change_page_attr
```
```
In arch/x86/mm/kmmio.c (ffffffff81074725)
Location: arch/x86/include/asm/pgtable.h:910
Inline: True
Inline callers:
  - arch/x86/mm/kmmio.c:unregister_kmmio_probe
  - arch/x86/mm/kmmio.c:register_kmmio_probe
  - arch/x86/mm/kmmio.c:kmmio_handler
  - arch/x86/mm/kmmio.c:get_kmmio_fault_page
  - arch/x86/mm/kmmio.c:kmmio_page_list
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pageattr.c (ffffffff810713ff)
Location: arch/x86/include/asm/pgtable.h:910
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:__change_page_attr
```
```
In arch/x86/mm/kmmio.c (ffffffff810782a5)
Location: arch/x86/include/asm/pgtable.h:910
Inline: True
Inline callers:
  - arch/x86/mm/kmmio.c:unregister_kmmio_probe
  - arch/x86/mm/kmmio.c:register_kmmio_probe
  - arch/x86/mm/kmmio.c:kmmio_handler
  - arch/x86/mm/kmmio.c:get_kmmio_fault_page
  - arch/x86/mm/kmmio.c:kmmio_page_list
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pageattr.c (ffffffff81070930)
Location: arch/x86/include/asm/pgtable.h:1116
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:__change_page_attr
```
```
In arch/x86/mm/kmmio.c (ffffffff81076d05)
Location: arch/x86/include/asm/pgtable.h:1116
Inline: True
Inline callers:
  - arch/x86/mm/kmmio.c:unregister_kmmio_probe
  - arch/x86/mm/kmmio.c:register_kmmio_probe
  - arch/x86/mm/kmmio.c:kmmio_handler
  - arch/x86/mm/kmmio.c:get_kmmio_fault_page
  - arch/x86/mm/kmmio.c:kmmio_page_list
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pageattr.c (ffffffff81076131)
Location: arch/x86/include/asm/pgtable.h:1135
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:__change_page_attr
```
```
In arch/x86/mm/kmmio.c (ffffffff8107cf10)
Location: arch/x86/include/asm/pgtable.h:1135
Inline: True
Inline callers:
  - arch/x86/mm/kmmio.c:unregister_kmmio_probe
  - arch/x86/mm/kmmio.c:register_kmmio_probe
  - arch/x86/mm/kmmio.c:kmmio_handler
  - arch/x86/mm/kmmio.c:get_kmmio_fault_page
  - arch/x86/mm/kmmio.c:kmmio_page_list
```
```
In arch/x86/mm/mem_encrypt.c (ffffffff826c6055)
Location: arch/x86/include/asm/pgtable.h:1135
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt.c:early_set_memory_enc_dec
  - arch/x86/mm/mem_encrypt.c:__set_clr_pte_enc
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pageattr.c (ffffffff81078c2d)
Location: arch/x86/include/asm/pgtable.h:1201
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:__change_page_attr
```
```
In arch/x86/mm/kmmio.c (ffffffff8107ffa4)
Location: arch/x86/include/asm/pgtable.h:1201
Inline: True
Inline callers:
  - arch/x86/mm/kmmio.c:unregister_kmmio_probe
  - arch/x86/mm/kmmio.c:register_kmmio_probe
  - arch/x86/mm/kmmio.c:kmmio_handler
  - arch/x86/mm/kmmio.c:get_kmmio_fault_page
  - arch/x86/mm/kmmio.c:kmmio_page_list
```
```
In arch/x86/mm/mem_encrypt.c (ffffffff826efe29)
Location: arch/x86/include/asm/pgtable.h:1201
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt.c:early_set_memory_enc_dec
  - arch/x86/mm/mem_encrypt.c:__set_clr_pte_enc
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pageattr.c (ffffffff8107f596)
Location: arch/x86/include/asm/pgtable.h:1290
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:__change_page_attr
```
```
In arch/x86/mm/kmmio.c (ffffffff81086ae4)
Location: arch/x86/include/asm/pgtable.h:1290
Inline: True
Inline callers:
  - arch/x86/mm/kmmio.c:unregister_kmmio_probe
  - arch/x86/mm/kmmio.c:register_kmmio_probe
  - arch/x86/mm/kmmio.c:kmmio_handler
  - arch/x86/mm/kmmio.c:get_kmmio_fault_page
  - arch/x86/mm/kmmio.c:kmmio_page_list
```
```
In arch/x86/mm/mem_encrypt.c (ffffffff828a6ae6)
Location: arch/x86/include/asm/pgtable.h:1290
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt.c:early_set_memory_enc_dec
  - arch/x86/mm/mem_encrypt.c:__set_clr_pte_enc
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pageattr.c (ffffffff81083035)
Location: arch/x86/include/asm/pgtable.h:1310
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:__change_page_attr
```
```
In arch/x86/mm/kmmio.c (ffffffff8108a6e4)
Location: arch/x86/include/asm/pgtable.h:1310
Inline: True
Inline callers:
  - arch/x86/mm/kmmio.c:unregister_kmmio_probe
  - arch/x86/mm/kmmio.c:register_kmmio_probe
  - arch/x86/mm/kmmio.c:kmmio_handler
  - arch/x86/mm/kmmio.c:get_kmmio_fault_page
  - arch/x86/mm/kmmio.c:kmmio_page_list
```
```
In arch/x86/mm/mem_encrypt.c (ffffffff828bf190)
Location: arch/x86/include/asm/pgtable.h:1310
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt.c:early_set_memory_enc_dec
  - arch/x86/mm/mem_encrypt.c:__set_clr_pte_enc
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pageattr.c (ffffffff81084105)
Location: arch/x86/include/asm/pgtable.h:1310
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:__change_page_attr
```
```
In arch/x86/mm/kmmio.c (ffffffff8108b354)
Location: arch/x86/include/asm/pgtable.h:1310
Inline: True
Inline callers:
  - arch/x86/mm/kmmio.c:unregister_kmmio_probe
  - arch/x86/mm/kmmio.c:register_kmmio_probe
  - arch/x86/mm/kmmio.c:kmmio_handler
  - arch/x86/mm/kmmio.c:get_kmmio_fault_page
  - arch/x86/mm/kmmio.c:kmmio_page_list
```
```
In arch/x86/mm/mem_encrypt.c (ffffffff828c560b)
Location: arch/x86/include/asm/pgtable.h:1310
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt.c:early_set_memory_enc_dec
  - arch/x86/mm/mem_encrypt.c:__set_clr_pte_enc
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pat/set_memory.c (ffffffff8108dcd9)
Location: arch/x86/include/asm/pgtable.h:1271
Inline: True
Inline callers:
  - arch/x86/mm/pat/set_memory.c:__should_split_large_page
```
```
In arch/x86/mm/kmmio.c (ffffffff810926e4)
Location: arch/x86/include/asm/pgtable.h:1271
Inline: True
Inline callers:
  - arch/x86/mm/kmmio.c:unregister_kmmio_probe
  - arch/x86/mm/kmmio.c:register_kmmio_probe
  - arch/x86/mm/kmmio.c:add_kmmio_fault_page
  - arch/x86/mm/kmmio.c:kmmio_handler
  - arch/x86/mm/kmmio.c:get_kmmio_fault_page
  - arch/x86/mm/kmmio.c:get_kmmio_fault_page
```
```
In arch/x86/mm/mem_encrypt.c (ffffffff82ce881b)
Location: arch/x86/include/asm/pgtable.h:1271
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt.c:early_set_memory_enc_dec
  - arch/x86/mm/mem_encrypt.c:__set_clr_pte_enc
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/sev-es.c (ffffffff81083738)
Location: arch/x86/include/asm/pgtable.h:1267
Inline: True
```
```
In arch/x86/mm/pat/set_memory.c (ffffffff8108dba9)
Location: arch/x86/include/asm/pgtable.h:1267
Inline: True
Inline callers:
  - arch/x86/mm/pat/set_memory.c:__should_split_large_page
```
```
In arch/x86/mm/kmmio.c (ffffffff81091d74)
Location: arch/x86/include/asm/pgtable.h:1267
Inline: True
Inline callers:
  - arch/x86/mm/kmmio.c:unregister_kmmio_probe
  - arch/x86/mm/kmmio.c:register_kmmio_probe
  - arch/x86/mm/kmmio.c:add_kmmio_fault_page
  - arch/x86/mm/kmmio.c:kmmio_handler
  - arch/x86/mm/kmmio.c:get_kmmio_fault_page
  - arch/x86/mm/kmmio.c:get_kmmio_fault_page
```
```
In arch/x86/mm/mem_encrypt.c (ffffffff82fd622d)
Location: arch/x86/include/asm/pgtable.h:1267
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt.c:early_set_memory_enc_dec
  - arch/x86/mm/mem_encrypt.c:__set_clr_pte_enc
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/sev.c (ffffffff81083c9d)
Location: arch/x86/include/asm/pgtable.h:1267
Inline: True
```
```
In arch/x86/mm/pat/set_memory.c (ffffffff8108e7a5)
Location: arch/x86/include/asm/pgtable.h:1267
Inline: True
Inline callers:
  - arch/x86/mm/pat/set_memory.c:__should_split_large_page
```
```
In arch/x86/mm/kmmio.c (ffffffff81092884)
Location: arch/x86/include/asm/pgtable.h:1267
Inline: True
Inline callers:
  - arch/x86/mm/kmmio.c:unregister_kmmio_probe
  - arch/x86/mm/kmmio.c:register_kmmio_probe
  - arch/x86/mm/kmmio.c:register_kmmio_probe
  - arch/x86/mm/kmmio.c:kmmio_handler
  - arch/x86/mm/kmmio.c:get_kmmio_fault_page
  - arch/x86/mm/kmmio.c:get_kmmio_fault_page
```
```
In arch/x86/mm/mem_encrypt.c (ffffffff831e0c88)
Location: arch/x86/include/asm/pgtable.h:1267
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt.c:early_set_memory_enc_dec
  - arch/x86/mm/mem_encrypt.c:__set_clr_pte_enc
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/sev.c (ffffffff81092e4b)
Location: arch/x86/include/asm/pgtable.h:1238
Inline: True
```
```
In arch/x86/mm/pat/set_memory.c (ffffffff8109e28f)
Location: arch/x86/include/asm/pgtable.h:1238
Inline: True
Inline callers:
  - arch/x86/mm/pat/set_memory.c:__should_split_large_page
```
```
In arch/x86/mm/kmmio.c (ffffffff810a25a9)
Location: arch/x86/include/asm/pgtable.h:1238
Inline: True
Inline callers:
  - arch/x86/mm/kmmio.c:unregister_kmmio_probe
  - arch/x86/mm/kmmio.c:register_kmmio_probe
  - arch/x86/mm/kmmio.c:kmmio_handler
  - arch/x86/mm/kmmio.c:get_kmmio_fault_page
  - arch/x86/mm/kmmio.c:kmmio_page_list
```
```
In arch/x86/mm/mem_encrypt.c (ffffffff81ca24d6)
Location: arch/x86/include/asm/pgtable.h:1238
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt.c:page_level_size
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/coco/tdx/tdx.c (ffffffff81002b95)
Location: arch/x86/include/asm/pgtable.h:1255
Inline: True
```
```
In arch/x86/kernel/sev.c (ffffffff810a537f)
Location: arch/x86/include/asm/pgtable.h:1255
Inline: True
```
```
In arch/x86/mm/pat/set_memory.c (0)
Location: arch/x86/include/asm/pgtable.h:1255
Inline: True
```
```
In arch/x86/mm/kmmio.c (ffffffff810b6b9b)
Location: arch/x86/include/asm/pgtable.h:1255
Inline: True
Inline callers:
  - arch/x86/mm/kmmio.c:unregister_kmmio_probe
  - arch/x86/mm/kmmio.c:register_kmmio_probe
  - arch/x86/mm/kmmio.c:kmmio_handler
  - arch/x86/mm/kmmio.c:get_kmmio_fault_page
  - arch/x86/mm/kmmio.c:kmmio_page_list
```
```
In arch/x86/mm/mem_encrypt_amd.c (ffffffff810b999a)
Location: arch/x86/include/asm/pgtable.h:1255
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt_amd.c:enc_dec_hypercall
  - arch/x86/mm/mem_encrypt_amd.c:enc_dec_hypercall
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/coco/tdx/tdx.c (ffffffff810035d5)
Location: arch/x86/include/asm/pgtable.h:1273
Inline: True
```
```
In arch/x86/kernel/sev.c (ffffffff810bdb0e)
Location: arch/x86/include/asm/pgtable.h:1273
Inline: True
```
```
In arch/x86/mm/pat/set_memory.c (0)
Location: arch/x86/include/asm/pgtable.h:1273
Inline: True
```
```
In arch/x86/mm/kmmio.c (ffffffff810d2439)
Location: arch/x86/include/asm/pgtable.h:1273
Inline: True
Inline callers:
  - arch/x86/mm/kmmio.c:unregister_kmmio_probe
  - arch/x86/mm/kmmio.c:register_kmmio_probe
  - arch/x86/mm/kmmio.c:kmmio_handler
  - arch/x86/mm/kmmio.c:get_kmmio_fault_page
  - arch/x86/mm/kmmio.c:kmmio_page_list
```
```
In arch/x86/mm/mem_encrypt_amd.c (ffffffff83e9ff5f)
Location: arch/x86/include/asm/pgtable.h:1273
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt_amd.c:early_set_memory_enc_dec
  - arch/x86/mm/mem_encrypt_amd.c:early_set_memory_enc_dec
  - arch/x86/mm/mem_encrypt_amd.c:__set_clr_pte_enc
  - arch/x86/mm/mem_encrypt_amd.c:enc_dec_hypercall
  - arch/x86/mm/mem_encrypt_amd.c:enc_dec_hypercall
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/coco/tdx/tdx-shared.c (0)
Location: arch/x86/include/asm/pgtable.h:1274
Inline: True
```
```
In arch/x86/kernel/sev.c (ffffffff810c117e)
Location: arch/x86/include/asm/pgtable.h:1274
Inline: True
```
```
In arch/x86/mm/pat/set_memory.c (0)
Location: arch/x86/include/asm/pgtable.h:1274
Inline: True
```
```
In arch/x86/mm/kmmio.c (ffffffff810d58a9)
Location: arch/x86/include/asm/pgtable.h:1274
Inline: True
Inline callers:
  - arch/x86/mm/kmmio.c:unregister_kmmio_probe
  - arch/x86/mm/kmmio.c:register_kmmio_probe
  - arch/x86/mm/kmmio.c:kmmio_handler
  - arch/x86/mm/kmmio.c:get_kmmio_fault_page
  - arch/x86/mm/kmmio.c:kmmio_page_list
```
```
In arch/x86/mm/mem_encrypt_amd.c (ffffffff836c4163)
Location: arch/x86/include/asm/pgtable.h:1274
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt_amd.c:early_set_memory_enc_dec
  - arch/x86/mm/mem_encrypt_amd.c:early_set_memory_enc_dec
  - arch/x86/mm/mem_encrypt_amd.c:__set_clr_pte_enc
  - arch/x86/mm/mem_encrypt_amd.c:enc_dec_hypercall
  - arch/x86/mm/mem_encrypt_amd.c:enc_dec_hypercall
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/coco/tdx/tdx-shared.c (ffffffff81003e1b)
Location: arch/x86/include/asm/pgtable.h:1497
Inline: True
Inline callers:
  - arch/x86/coco/tdx/tdx-shared.c:try_accept_one
```
```
In arch/x86/kernel/sev.c (ffffffff810c85de)
Location: arch/x86/include/asm/pgtable.h:1497
Inline: True
```
```
In arch/x86/mm/pat/set_memory.c (0)
Location: arch/x86/include/asm/pgtable.h:1497
Inline: True
```
```
In arch/x86/mm/kmmio.c (ffffffff810de0a9)
Location: arch/x86/include/asm/pgtable.h:1497
Inline: True
Inline callers:
  - arch/x86/mm/kmmio.c:unregister_kmmio_probe
  - arch/x86/mm/kmmio.c:register_kmmio_probe
  - arch/x86/mm/kmmio.c:kmmio_handler
  - arch/x86/mm/kmmio.c:get_kmmio_fault_page
  - arch/x86/mm/kmmio.c:kmmio_page_list
```
```
In arch/x86/mm/mem_encrypt_amd.c (ffffffff838f4de3)
Location: arch/x86/include/asm/pgtable.h:1497
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt_amd.c:early_set_memory_enc_dec
  - arch/x86/mm/mem_encrypt_amd.c:early_set_memory_enc_dec
  - arch/x86/mm/mem_encrypt_amd.c:__set_clr_pte_enc
  - arch/x86/mm/mem_encrypt_amd.c:enc_dec_hypercall
  - arch/x86/mm/mem_encrypt_amd.c:enc_dec_hypercall
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
<summary>In <code>aws</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pageattr.c (ffffffff81083105)
Location: arch/x86/include/asm/pgtable.h:1310
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:__change_page_attr
```
```
In arch/x86/mm/kmmio.c (ffffffff8108a314)
Location: arch/x86/include/asm/pgtable.h:1310
Inline: True
Inline callers:
  - arch/x86/mm/kmmio.c:unregister_kmmio_probe
  - arch/x86/mm/kmmio.c:register_kmmio_probe
  - arch/x86/mm/kmmio.c:kmmio_handler
  - arch/x86/mm/kmmio.c:get_kmmio_fault_page
  - arch/x86/mm/kmmio.c:kmmio_page_list
```
```
In arch/x86/mm/mem_encrypt.c (ffffffff828b05a3)
Location: arch/x86/include/asm/pgtable.h:1310
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt.c:early_set_memory_enc_dec
  - arch/x86/mm/mem_encrypt.c:__set_clr_pte_enc
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pageattr.c (ffffffff81071d5e)
Location: arch/x86/include/asm/pgtable.h:1310
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:__change_page_attr_set_clr
```
```
In arch/x86/mm/kmmio.c (ffffffff81079004)
Location: arch/x86/include/asm/pgtable.h:1310
Inline: True
Inline callers:
  - arch/x86/mm/kmmio.c:unregister_kmmio_probe
  - arch/x86/mm/kmmio.c:register_kmmio_probe
  - arch/x86/mm/kmmio.c:kmmio_handler
  - arch/x86/mm/kmmio.c:get_kmmio_fault_page
  - arch/x86/mm/kmmio.c:kmmio_page_list
```
```
In arch/x86/mm/mem_encrypt.c (ffffffff828a8728)
Location: arch/x86/include/asm/pgtable.h:1310
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt.c:early_set_memory_enc_dec
  - arch/x86/mm/mem_encrypt.c:__set_clr_pte_enc
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pageattr.c (ffffffff810830b5)
Location: arch/x86/include/asm/pgtable.h:1310
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:__change_page_attr
```
```
In arch/x86/mm/kmmio.c (ffffffff8108a2c4)
Location: arch/x86/include/asm/pgtable.h:1310
Inline: True
Inline callers:
  - arch/x86/mm/kmmio.c:unregister_kmmio_probe
  - arch/x86/mm/kmmio.c:register_kmmio_probe
  - arch/x86/mm/kmmio.c:kmmio_handler
  - arch/x86/mm/kmmio.c:get_kmmio_fault_page
  - arch/x86/mm/kmmio.c:kmmio_page_list
```
```
In arch/x86/mm/mem_encrypt.c (ffffffff828c34a2)
Location: arch/x86/include/asm/pgtable.h:1310
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt.c:early_set_memory_enc_dec
  - arch/x86/mm/mem_encrypt.c:__set_clr_pte_enc
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pageattr.c (ffffffff810851ea)
Location: arch/x86/include/asm/pgtable.h:1310
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:__change_page_attr
```
```
In arch/x86/mm/kmmio.c (ffffffff8108c564)
Location: arch/x86/include/asm/pgtable.h:1310
Inline: True
Inline callers:
  - arch/x86/mm/kmmio.c:unregister_kmmio_probe
  - arch/x86/mm/kmmio.c:register_kmmio_probe
  - arch/x86/mm/kmmio.c:kmmio_handler
  - arch/x86/mm/kmmio.c:get_kmmio_fault_page
  - arch/x86/mm/kmmio.c:kmmio_page_list
```
```
In arch/x86/mm/mem_encrypt.c (ffffffff828c6648)
Location: arch/x86/include/asm/pgtable.h:1310
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt.c:early_set_memory_enc_dec
  - arch/x86/mm/mem_encrypt.c:__set_clr_pte_enc
```
</details>
</li>
</ul>

## Differences
