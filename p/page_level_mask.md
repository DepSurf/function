# Function: <code>page_level_mask</code>

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
In arch/x86/mm/pageattr.c (ffffffff8106d96a)
Location: arch/x86/include/asm/pgtable.h:870
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:__change_page_attr
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
In arch/x86/mm/pageattr.c (0)
Location: arch/x86/include/asm/pgtable.h:918
Inline: True
```
```
In arch/x86/mm/kmmio.c (ffffffff81074c90)
Location: arch/x86/include/asm/pgtable.h:918
Inline: True
Inline callers:
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
In arch/x86/mm/pageattr.c (0)
Location: arch/x86/include/asm/pgtable.h:918
Inline: True
```
```
In arch/x86/mm/kmmio.c (ffffffff81078810)
Location: arch/x86/include/asm/pgtable.h:918
Inline: True
Inline callers:
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
In arch/x86/mm/pageattr.c (0)
Location: arch/x86/include/asm/pgtable.h:1124
Inline: True
```
```
In arch/x86/mm/kmmio.c (ffffffff81077140)
Location: arch/x86/include/asm/pgtable.h:1124
Inline: True
Inline callers:
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
In arch/x86/mm/pageattr.c (0)
Location: arch/x86/include/asm/pgtable.h:1143
Inline: True
```
```
In arch/x86/mm/kmmio.c (ffffffff8107d480)
Location: arch/x86/include/asm/pgtable.h:1143
Inline: True
Inline callers:
  - arch/x86/mm/kmmio.c:kmmio_handler
  - arch/x86/mm/kmmio.c:get_kmmio_fault_page
  - arch/x86/mm/kmmio.c:kmmio_page_list
```
```
In arch/x86/mm/mem_encrypt.c (0)
Location: arch/x86/include/asm/pgtable.h:1143
Inline: True
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
In arch/x86/mm/pageattr.c (0)
Location: arch/x86/include/asm/pgtable.h:1209
Inline: True
```
```
In arch/x86/mm/kmmio.c (ffffffff81080490)
Location: arch/x86/include/asm/pgtable.h:1209
Inline: True
Inline callers:
  - arch/x86/mm/kmmio.c:kmmio_handler
  - arch/x86/mm/kmmio.c:get_kmmio_fault_page
  - arch/x86/mm/kmmio.c:kmmio_page_list
```
```
In arch/x86/mm/mem_encrypt.c (0)
Location: arch/x86/include/asm/pgtable.h:1209
Inline: True
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
In arch/x86/mm/pageattr.c (0)
Location: arch/x86/include/asm/pgtable.h:1298
Inline: True
```
```
In arch/x86/mm/kmmio.c (ffffffff81086ff0)
Location: arch/x86/include/asm/pgtable.h:1298
Inline: True
Inline callers:
  - arch/x86/mm/kmmio.c:kmmio_handler
  - arch/x86/mm/kmmio.c:get_kmmio_fault_page
  - arch/x86/mm/kmmio.c:kmmio_page_list
```
```
In arch/x86/mm/mem_encrypt.c (0)
Location: arch/x86/include/asm/pgtable.h:1298
Inline: True
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
In arch/x86/mm/pageattr.c (0)
Location: arch/x86/include/asm/pgtable.h:1318
Inline: True
```
```
In arch/x86/mm/kmmio.c (ffffffff8108abb0)
Location: arch/x86/include/asm/pgtable.h:1318
Inline: True
Inline callers:
  - arch/x86/mm/kmmio.c:kmmio_handler
  - arch/x86/mm/kmmio.c:get_kmmio_fault_page
  - arch/x86/mm/kmmio.c:kmmio_page_list
```
```
In arch/x86/mm/mem_encrypt.c (0)
Location: arch/x86/include/asm/pgtable.h:1318
Inline: True
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
In arch/x86/mm/pageattr.c (0)
Location: arch/x86/include/asm/pgtable.h:1318
Inline: True
```
```
In arch/x86/mm/kmmio.c (ffffffff8108b820)
Location: arch/x86/include/asm/pgtable.h:1318
Inline: True
Inline callers:
  - arch/x86/mm/kmmio.c:kmmio_handler
  - arch/x86/mm/kmmio.c:get_kmmio_fault_page
  - arch/x86/mm/kmmio.c:kmmio_page_list
```
```
In arch/x86/mm/mem_encrypt.c (0)
Location: arch/x86/include/asm/pgtable.h:1318
Inline: True
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
In arch/x86/mm/pat/set_memory.c (0)
Location: arch/x86/include/asm/pgtable.h:1279
Inline: True
```
```
In arch/x86/mm/kmmio.c (ffffffff81092960)
Location: arch/x86/include/asm/pgtable.h:1279
Inline: True
Inline callers:
  - arch/x86/mm/kmmio.c:add_kmmio_fault_page
  - arch/x86/mm/kmmio.c:kmmio_handler
  - arch/x86/mm/kmmio.c:get_kmmio_fault_page
  - arch/x86/mm/kmmio.c:get_kmmio_fault_page
```
```
In arch/x86/mm/mem_encrypt.c (0)
Location: arch/x86/include/asm/pgtable.h:1279
Inline: True
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
Location: arch/x86/include/asm/pgtable.h:1275
Inline: True
```
```
In arch/x86/mm/pat/set_memory.c (0)
Location: arch/x86/include/asm/pgtable.h:1275
Inline: True
```
```
In arch/x86/mm/kmmio.c (ffffffff81091ff0)
Location: arch/x86/include/asm/pgtable.h:1275
Inline: True
Inline callers:
  - arch/x86/mm/kmmio.c:add_kmmio_fault_page
  - arch/x86/mm/kmmio.c:kmmio_handler
  - arch/x86/mm/kmmio.c:get_kmmio_fault_page
  - arch/x86/mm/kmmio.c:get_kmmio_fault_page
```
```
In arch/x86/mm/mem_encrypt.c (0)
Location: arch/x86/include/asm/pgtable.h:1275
Inline: True
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
Location: arch/x86/include/asm/pgtable.h:1275
Inline: True
```
```
In arch/x86/mm/pat/set_memory.c (ffffffff8108e7a5)
Location: arch/x86/include/asm/pgtable.h:1275
Inline: True
Inline callers:
  - arch/x86/mm/pat/set_memory.c:__should_split_large_page
```
```
In arch/x86/mm/kmmio.c (ffffffff81092ba8)
Location: arch/x86/include/asm/pgtable.h:1275
Inline: True
Inline callers:
  - arch/x86/mm/kmmio.c:register_kmmio_probe
  - arch/x86/mm/kmmio.c:kmmio_handler
  - arch/x86/mm/kmmio.c:get_kmmio_fault_page
  - arch/x86/mm/kmmio.c:get_kmmio_fault_page
```
```
In arch/x86/mm/mem_encrypt.c (ffffffff831e0c9b)
Location: arch/x86/include/asm/pgtable.h:1275
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt.c:early_set_memory_enc_dec
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
Location: arch/x86/include/asm/pgtable.h:1246
Inline: True
```
```
In arch/x86/mm/pat/set_memory.c (ffffffff8109e28f)
Location: arch/x86/include/asm/pgtable.h:1246
Inline: True
Inline callers:
  - arch/x86/mm/pat/set_memory.c:__should_split_large_page
```
```
In arch/x86/mm/kmmio.c (ffffffff810a2ae0)
Location: arch/x86/include/asm/pgtable.h:1246
Inline: True
Inline callers:
  - arch/x86/mm/kmmio.c:kmmio_handler
  - arch/x86/mm/kmmio.c:get_kmmio_fault_page
  - arch/x86/mm/kmmio.c:kmmio_page_list
```
```
In arch/x86/mm/mem_encrypt.c (ffffffff832c436d)
Location: arch/x86/include/asm/pgtable.h:1246
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt.c:early_set_memory_enc_dec
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
In arch/x86/kernel/sev.c (ffffffff810a537f)
Location: arch/x86/include/asm/pgtable.h:1263
Inline: True
```
```
In arch/x86/mm/pat/set_memory.c (ffffffff810b1bf3)
Location: arch/x86/include/asm/pgtable.h:1263
Inline: True
Inline callers:
  - arch/x86/mm/pat/set_memory.c:__should_split_large_page
```
```
In arch/x86/mm/kmmio.c (ffffffff810b7107)
Location: arch/x86/include/asm/pgtable.h:1263
Inline: True
Inline callers:
  - arch/x86/mm/kmmio.c:kmmio_handler
  - arch/x86/mm/kmmio.c:get_kmmio_fault_page
  - arch/x86/mm/kmmio.c:kmmio_page_list
```
```
In arch/x86/mm/mem_encrypt_amd.c (ffffffff83476d2f)
Location: arch/x86/include/asm/pgtable.h:1263
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt_amd.c:early_set_memory_enc_dec
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
In arch/x86/kernel/sev.c (ffffffff810bdb0e)
Location: arch/x86/include/asm/pgtable.h:1281
Inline: True
```
```
In arch/x86/mm/pat/set_memory.c (ffffffff810cc374)
Location: arch/x86/include/asm/pgtable.h:1281
Inline: True
Inline callers:
  - arch/x86/mm/pat/set_memory.c:__should_split_large_page
```
```
In arch/x86/mm/kmmio.c (ffffffff810d25d7)
Location: arch/x86/include/asm/pgtable.h:1281
Inline: True
Inline callers:
  - arch/x86/mm/kmmio.c:kmmio_handler
  - arch/x86/mm/kmmio.c:get_kmmio_fault_page
  - arch/x86/mm/kmmio.c:kmmio_page_list
```
```
In arch/x86/mm/mem_encrypt_amd.c (ffffffff83ea00fc)
Location: arch/x86/include/asm/pgtable.h:1281
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt_amd.c:early_set_memory_enc_dec
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
In arch/x86/kernel/sev.c (ffffffff810c117e)
Location: arch/x86/include/asm/pgtable.h:1282
Inline: True
```
```
In arch/x86/mm/pat/set_memory.c (ffffffff810cf994)
Location: arch/x86/include/asm/pgtable.h:1282
Inline: True
Inline callers:
  - arch/x86/mm/pat/set_memory.c:__should_split_large_page
```
```
In arch/x86/mm/kmmio.c (ffffffff810d5a47)
Location: arch/x86/include/asm/pgtable.h:1282
Inline: True
Inline callers:
  - arch/x86/mm/kmmio.c:kmmio_handler
  - arch/x86/mm/kmmio.c:get_kmmio_fault_page
  - arch/x86/mm/kmmio.c:kmmio_page_list
```
```
In arch/x86/mm/mem_encrypt_amd.c (ffffffff836c4275)
Location: arch/x86/include/asm/pgtable.h:1282
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt_amd.c:early_set_memory_enc_dec
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
In arch/x86/kernel/sev.c (ffffffff810c85de)
Location: arch/x86/include/asm/pgtable.h:1505
Inline: True
```
```
In arch/x86/mm/pat/set_memory.c (ffffffff810d8074)
Location: arch/x86/include/asm/pgtable.h:1505
Inline: True
Inline callers:
  - arch/x86/mm/pat/set_memory.c:__should_split_large_page
```
```
In arch/x86/mm/kmmio.c (ffffffff810de277)
Location: arch/x86/include/asm/pgtable.h:1505
Inline: True
Inline callers:
  - arch/x86/mm/kmmio.c:kmmio_handler
  - arch/x86/mm/kmmio.c:get_kmmio_fault_page
  - arch/x86/mm/kmmio.c:kmmio_page_list
```
```
In arch/x86/mm/mem_encrypt_amd.c (ffffffff838f4ef5)
Location: arch/x86/include/asm/pgtable.h:1505
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt_amd.c:early_set_memory_enc_dec
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
In arch/x86/mm/pageattr.c (0)
Location: arch/x86/include/asm/pgtable.h:1318
Inline: True
```
```
In arch/x86/mm/kmmio.c (ffffffff8108a7e0)
Location: arch/x86/include/asm/pgtable.h:1318
Inline: True
Inline callers:
  - arch/x86/mm/kmmio.c:kmmio_handler
  - arch/x86/mm/kmmio.c:get_kmmio_fault_page
  - arch/x86/mm/kmmio.c:kmmio_page_list
```
```
In arch/x86/mm/mem_encrypt.c (0)
Location: arch/x86/include/asm/pgtable.h:1318
Inline: True
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
In arch/x86/mm/pageattr.c (0)
Location: arch/x86/include/asm/pgtable.h:1318
Inline: True
```
```
In arch/x86/mm/kmmio.c (ffffffff81079350)
Location: arch/x86/include/asm/pgtable.h:1318
Inline: True
Inline callers:
  - arch/x86/mm/kmmio.c:kmmio_handler
  - arch/x86/mm/kmmio.c:get_kmmio_fault_page
  - arch/x86/mm/kmmio.c:kmmio_page_list
```
```
In arch/x86/mm/mem_encrypt.c (0)
Location: arch/x86/include/asm/pgtable.h:1318
Inline: True
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
In arch/x86/mm/pageattr.c (0)
Location: arch/x86/include/asm/pgtable.h:1318
Inline: True
```
```
In arch/x86/mm/kmmio.c (ffffffff8108a790)
Location: arch/x86/include/asm/pgtable.h:1318
Inline: True
Inline callers:
  - arch/x86/mm/kmmio.c:kmmio_handler
  - arch/x86/mm/kmmio.c:get_kmmio_fault_page
  - arch/x86/mm/kmmio.c:kmmio_page_list
```
```
In arch/x86/mm/mem_encrypt.c (0)
Location: arch/x86/include/asm/pgtable.h:1318
Inline: True
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
In arch/x86/mm/pageattr.c (0)
Location: arch/x86/include/asm/pgtable.h:1318
Inline: True
```
```
In arch/x86/mm/kmmio.c (ffffffff8108ca50)
Location: arch/x86/include/asm/pgtable.h:1318
Inline: True
Inline callers:
  - arch/x86/mm/kmmio.c:kmmio_handler
  - arch/x86/mm/kmmio.c:get_kmmio_fault_page
  - arch/x86/mm/kmmio.c:kmmio_page_list
```
```
In arch/x86/mm/mem_encrypt.c (0)
Location: arch/x86/include/asm/pgtable.h:1318
Inline: True
```
</details>
</li>
</ul>

## Differences
