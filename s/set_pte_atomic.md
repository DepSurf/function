# Function: <code>set_pte_atomic</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pageattr.c (ffffffff8106de8d)
Location: arch/x86/include/asm/paravirt.h:639
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:__change_page_attr
  - arch/x86/mm/pageattr.c:__change_page_attr
  - arch/x86/mm/pageattr.c:__change_page_attr
```
```
In arch/x86/mm/kmmio.c (ffffffff81073058)
Location: arch/x86/include/asm/paravirt.h:639
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
In arch/x86/mm/pageattr.c (ffffffff8106db59)
Location: arch/x86/include/asm/paravirt.h:612
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:__change_page_attr
  - arch/x86/mm/pageattr.c:__change_page_attr
  - arch/x86/mm/pageattr.c:__change_page_attr
```
```
In arch/x86/mm/kmmio.c (ffffffff8107461d)
Location: arch/x86/include/asm/paravirt.h:612
Inline: True
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
In arch/x86/mm/pageattr.c (ffffffff810717e5)
Location: arch/x86/include/asm/paravirt.h:603
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:__change_page_attr
  - arch/x86/mm/pageattr.c:__change_page_attr
  - arch/x86/mm/pageattr.c:__change_page_attr
```
```
In arch/x86/mm/kmmio.c (ffffffff8107819d)
Location: arch/x86/include/asm/paravirt.h:603
Inline: True
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
In arch/x86/mm/pageattr.c (ffffffff81070fcd)
Location: arch/x86/include/asm/paravirt.h:650
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:__change_page_attr
  - arch/x86/mm/pageattr.c:__change_page_attr
  - arch/x86/mm/pageattr.c:__change_page_attr
```
```
In arch/x86/mm/kmmio.c (ffffffff81076a0e)
Location: arch/x86/include/asm/paravirt.h:650
Inline: True
Inline callers:
  - arch/x86/mm/kmmio.c:clear_page_presence
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
In arch/x86/mm/pageattr.c (ffffffff81076715)
Location: arch/x86/include/asm/paravirt.h:614
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:__change_page_attr
  - arch/x86/mm/pageattr.c:__change_page_attr
  - arch/x86/mm/pageattr.c:__change_page_attr
```
```
In arch/x86/mm/kmmio.c (ffffffff8107cdbf)
Location: arch/x86/include/asm/paravirt.h:614
Inline: True
```
```
In arch/x86/mm/mem_encrypt.c (ffffffff826c5fba)
Location: arch/x86/include/asm/paravirt.h:614
Inline: True
Inline callers:
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
In arch/x86/mm/pageattr.c (ffffffff810790a5)
Location: arch/x86/include/asm/paravirt.h:619
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:__change_page_attr
  - arch/x86/mm/pageattr.c:__change_page_attr
  - arch/x86/mm/pageattr.c:__change_page_attr
```
```
In arch/x86/mm/kmmio.c (ffffffff8107fd77)
Location: arch/x86/include/asm/paravirt.h:619
Inline: True
```
```
In arch/x86/mm/mem_encrypt.c (ffffffff826efd8d)
Location: arch/x86/include/asm/paravirt.h:619
Inline: True
Inline callers:
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
In arch/x86/mm/pageattr.c (ffffffff8107f9bc)
Location: arch/x86/include/asm/paravirt.h:597
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:__change_page_attr
  - arch/x86/mm/pageattr.c:__change_page_attr
  - arch/x86/mm/pageattr.c:__change_page_attr
```
```
In arch/x86/mm/kmmio.c (ffffffff810868b7)
Location: arch/x86/include/asm/paravirt.h:597
Inline: True
```
```
In arch/x86/mm/mem_encrypt.c (ffffffff828a6a4a)
Location: arch/x86/include/asm/paravirt.h:597
Inline: True
Inline callers:
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
In arch/x86/mm/pageattr.c (ffffffff810833b7)
Location: arch/x86/include/asm/paravirt.h:598
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:__change_page_attr
  - arch/x86/mm/pageattr.c:__change_page_attr
  - arch/x86/mm/pageattr.c:__split_large_page
```
```
In arch/x86/mm/kmmio.c (ffffffff8108a4c7)
Location: arch/x86/include/asm/paravirt.h:598
Inline: True
```
```
In arch/x86/mm/mem_encrypt.c (ffffffff828bf0f4)
Location: arch/x86/include/asm/paravirt.h:598
Inline: True
Inline callers:
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
In arch/x86/mm/pageattr.c (ffffffff81084487)
Location: arch/x86/include/asm/paravirt.h:586
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:__change_page_attr
  - arch/x86/mm/pageattr.c:__change_page_attr
  - arch/x86/mm/pageattr.c:__split_large_page
```
```
In arch/x86/mm/kmmio.c (ffffffff8108b137)
Location: arch/x86/include/asm/paravirt.h:586
Inline: True
```
```
In arch/x86/mm/mem_encrypt.c (ffffffff828c556f)
Location: arch/x86/include/asm/paravirt.h:586
Inline: True
Inline callers:
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
In arch/x86/mm/pat/set_memory.c (ffffffff8108e224)
Location: arch/x86/include/asm/paravirt.h:600
Inline: True
Inline callers:
  - arch/x86/mm/pat/set_memory.c:__change_page_attr
  - arch/x86/mm/pat/set_memory.c:__split_large_page
  - arch/x86/mm/pat/set_memory.c:__should_split_large_page
```
```
In arch/x86/mm/kmmio.c (ffffffff810925f9)
Location: arch/x86/include/asm/paravirt.h:600
Inline: True
Inline callers:
  - arch/x86/mm/kmmio.c:clear_page_presence
```
```
In arch/x86/mm/mem_encrypt.c (ffffffff82ce877f)
Location: arch/x86/include/asm/paravirt.h:600
Inline: True
Inline callers:
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
In arch/x86/mm/pat/set_memory.c (ffffffff8108e0f4)
Location: arch/x86/include/asm/paravirt.h:499
Inline: True
Inline callers:
  - arch/x86/mm/pat/set_memory.c:__change_page_attr
  - arch/x86/mm/pat/set_memory.c:__split_large_page
  - arch/x86/mm/pat/set_memory.c:__should_split_large_page
```
```
In arch/x86/mm/kmmio.c (ffffffff81091c85)
Location: arch/x86/include/asm/paravirt.h:499
Inline: True
Inline callers:
  - arch/x86/mm/kmmio.c:clear_page_presence
```
```
In arch/x86/mm/mem_encrypt.c (ffffffff82fd6192)
Location: arch/x86/include/asm/paravirt.h:499
Inline: True
Inline callers:
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
In arch/x86/mm/pat/set_memory.c (ffffffff8108ecb7)
Location: arch/x86/include/asm/paravirt.h:530
Inline: True
Inline callers:
  - arch/x86/mm/pat/set_memory.c:__change_page_attr
  - arch/x86/mm/pat/set_memory.c:__split_large_page
  - arch/x86/mm/pat/set_memory.c:__should_split_large_page
```
```
In arch/x86/mm/kmmio.c (ffffffff81092539)
Location: arch/x86/include/asm/paravirt.h:530
Inline: True
Inline callers:
  - arch/x86/mm/kmmio.c:clear_pte_presence
```
```
In arch/x86/mm/mem_encrypt.c (ffffffff831e0bed)
Location: arch/x86/include/asm/paravirt.h:530
Inline: True
Inline callers:
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
In arch/x86/mm/pat/set_memory.c (ffffffff8109e76a)
Location: arch/x86/include/asm/paravirt.h:530
Inline: True
Inline callers:
  - arch/x86/mm/pat/set_memory.c:__change_page_attr
  - arch/x86/mm/pat/set_memory.c:__split_large_page
  - arch/x86/mm/pat/set_memory.c:__should_split_large_page
```
```
In arch/x86/mm/kmmio.c (ffffffff810a2329)
Location: arch/x86/include/asm/paravirt.h:530
Inline: True
Inline callers:
  - arch/x86/mm/kmmio.c:clear_pte_presence
```
```
In arch/x86/mm/mem_encrypt.c (ffffffff832c42c5)
Location: arch/x86/include/asm/paravirt.h:530
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt.c:__set_clr_pte_enc
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
In arch/x86/mm/pat/set_memory.c (ffffffff810b214d)
Location: arch/x86/include/asm/paravirt.h:536
Inline: True
Inline callers:
  - arch/x86/mm/pat/set_memory.c:__change_page_attr
  - arch/x86/mm/pat/set_memory.c:__split_large_page
  - arch/x86/mm/pat/set_memory.c:__should_split_large_page
```
```
In arch/x86/mm/kmmio.c (ffffffff810b68e0)
Location: arch/x86/include/asm/paravirt.h:536
Inline: True
Inline callers:
  - arch/x86/mm/kmmio.c:clear_pte_presence
```
```
In arch/x86/mm/mem_encrypt_amd.c (ffffffff83476c2a)
Location: arch/x86/include/asm/paravirt.h:536
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt_amd.c:__set_clr_pte_enc
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
In arch/x86/mm/pat/set_memory.c (ffffffff810cc9d7)
Location: arch/x86/include/asm/paravirt.h:536
Inline: True
Inline callers:
  - arch/x86/mm/pat/set_memory.c:__change_page_attr
  - arch/x86/mm/pat/set_memory.c:__split_large_page
  - arch/x86/mm/pat/set_memory.c:__should_split_large_page
```
```
In arch/x86/mm/kmmio.c (ffffffff810d1b29)
Location: arch/x86/include/asm/paravirt.h:536
Inline: True
Inline callers:
  - arch/x86/mm/kmmio.c:clear_pte_presence
```
```
In arch/x86/mm/mem_encrypt_amd.c (ffffffff83e9fe0d)
Location: arch/x86/include/asm/paravirt.h:536
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt_amd.c:__set_clr_pte_enc
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
In arch/x86/mm/pat/set_memory.c (ffffffff810cfff7)
Location: arch/x86/include/asm/paravirt.h:531
Inline: True
Inline callers:
  - arch/x86/mm/pat/set_memory.c:__change_page_attr
  - arch/x86/mm/pat/set_memory.c:__split_large_page
  - arch/x86/mm/pat/set_memory.c:__should_split_large_page
```
```
In arch/x86/mm/kmmio.c (ffffffff810d4fd9)
Location: arch/x86/include/asm/paravirt.h:531
Inline: True
Inline callers:
  - arch/x86/mm/kmmio.c:clear_pte_presence
```
```
In arch/x86/mm/mem_encrypt_amd.c (ffffffff836c3fb4)
Location: arch/x86/include/asm/paravirt.h:531
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt_amd.c:__set_clr_pte_enc
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
In arch/x86/mm/pat/set_memory.c (ffffffff810d86d7)
Location: arch/x86/include/asm/paravirt.h:529
Inline: True
Inline callers:
  - arch/x86/mm/pat/set_memory.c:__change_page_attr
  - arch/x86/mm/pat/set_memory.c:__split_large_page
  - arch/x86/mm/pat/set_memory.c:__should_split_large_page
```
```
In arch/x86/mm/kmmio.c (ffffffff810dd779)
Location: arch/x86/include/asm/paravirt.h:529
Inline: True
Inline callers:
  - arch/x86/mm/kmmio.c:clear_pte_presence
```
```
In arch/x86/mm/mem_encrypt_amd.c (ffffffff838f4c34)
Location: arch/x86/include/asm/paravirt.h:529
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt_amd.c:__set_clr_pte_enc
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
In arch/x86/mm/pageattr.c (ffffffff81083487)
Location: arch/x86/include/asm/paravirt.h:586
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:__change_page_attr
  - arch/x86/mm/pageattr.c:__change_page_attr
  - arch/x86/mm/pageattr.c:__split_large_page
```
```
In arch/x86/mm/kmmio.c (ffffffff8108a0f7)
Location: arch/x86/include/asm/paravirt.h:586
Inline: True
```
```
In arch/x86/mm/mem_encrypt.c (ffffffff828b0507)
Location: arch/x86/include/asm/paravirt.h:586
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt.c:__set_clr_pte_enc
```
</details>
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>gcp</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/mm/pageattr.c (ffffffff81083437)
Location: arch/x86/include/asm/paravirt.h:586
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:__change_page_attr
  - arch/x86/mm/pageattr.c:__change_page_attr
  - arch/x86/mm/pageattr.c:__split_large_page
```
```
In arch/x86/mm/kmmio.c (ffffffff8108a0a7)
Location: arch/x86/include/asm/paravirt.h:586
Inline: True
```
```
In arch/x86/mm/mem_encrypt.c (ffffffff828c3406)
Location: arch/x86/include/asm/paravirt.h:586
Inline: True
Inline callers:
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
In arch/x86/mm/pageattr.c (ffffffff81085689)
Location: arch/x86/include/asm/paravirt.h:586
Inline: True
Inline callers:
  - arch/x86/mm/pageattr.c:__change_page_attr
  - arch/x86/mm/pageattr.c:__change_page_attr
  - arch/x86/mm/pageattr.c:__split_large_page
```
```
In arch/x86/mm/kmmio.c (ffffffff8108c347)
Location: arch/x86/include/asm/paravirt.h:586
Inline: True
```
```
In arch/x86/mm/mem_encrypt.c (ffffffff828c65ac)
Location: arch/x86/include/asm/paravirt.h:586
Inline: True
Inline callers:
  - arch/x86/mm/mem_encrypt.c:__set_clr_pte_enc
```
</details>
</li>
</ul>

## Differences
