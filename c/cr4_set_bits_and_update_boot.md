# Function: <code>cr4_set_bits_and_update_boot</code>

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
In arch/x86/xen/enlighten.c (ffffffff8101cd96)
Location: arch/x86/include/asm/tlbflush.h:80
Inline: True
```
```
In arch/x86/mm/init.c (ffffffff81f7762c)
Location: arch/x86/include/asm/tlbflush.h:80
Inline: True
Inline callers:
  - arch/x86/mm/init.c:init_mem_mapping
  - arch/x86/mm/init.c:init_mem_mapping
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
In arch/x86/xen/enlighten.c (ffffffff8101bfb6)
Location: arch/x86/include/asm/tlbflush.h:128
Inline: True
```
```
In arch/x86/mm/init.c (ffffffff81f9fd74)
Location: arch/x86/include/asm/tlbflush.h:128
Inline: True
Inline callers:
  - arch/x86/mm/init.c:init_mem_mapping
  - arch/x86/mm/init.c:init_mem_mapping
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
In arch/x86/xen/enlighten.c (ffffffff8101c7c6)
Location: arch/x86/include/asm/tlbflush.h:128
Inline: True
```
```
In arch/x86/mm/init.c (ffffffff81fdb2d6)
Location: arch/x86/include/asm/tlbflush.h:128
Inline: True
Inline callers:
  - arch/x86/mm/init.c:init_mem_mapping
  - arch/x86/mm/init.c:init_mem_mapping
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init.c (ffffffff820bc15d)
Location: arch/x86/include/asm/tlbflush.h:143
Inline: True
Inline callers:
  - arch/x86/mm/init.c:init_mem_mapping
  - arch/x86/mm/init.c:init_mem_mapping
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init.c (ffffffff826c2b3a)
Location: arch/x86/include/asm/tlbflush.h:312
Inline: True
Inline callers:
  - arch/x86/mm/init.c:init_mem_mapping
  - arch/x86/mm/init.c:init_mem_mapping
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init.c (ffffffff826ecd3b)
Location: arch/x86/include/asm/tlbflush.h:357
Inline: True
Inline callers:
  - arch/x86/mm/init.c:init_mem_mapping
  - arch/x86/mm/init.c:init_mem_mapping
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init.c (ffffffff828a38cd)
Location: arch/x86/include/asm/tlbflush.h:345
Inline: True
Inline callers:
  - arch/x86/mm/init.c:init_mem_mapping
  - arch/x86/mm/init.c:init_mem_mapping
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init.c (ffffffff828bbd6c)
Location: arch/x86/include/asm/tlbflush.h:347
Inline: True
Inline callers:
  - arch/x86/mm/init.c:init_mem_mapping
  - arch/x86/mm/init.c:init_mem_mapping
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init.c (ffffffff828c2213)
Location: arch/x86/include/asm/tlbflush.h:363
Inline: True
Inline callers:
  - arch/x86/mm/init.c:init_mem_mapping
  - arch/x86/mm/init.c:init_mem_mapping
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void cr4_set_bits_and_update_boot(long unsigned int mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init.c (ffffffff8108452b)
Location: arch/x86/mm/init.c:200
Inline: False
Direct callers:
  - arch/x86/mm/init.c:probe_page_size_mask
  - arch/x86/mm/init.c:probe_page_size_mask
```
**Symbols:**

```
ffffffff8108452b-ffffffff81084555: cr4_set_bits_and_update_boot (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void cr4_set_bits_and_update_boot(long unsigned int mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init.c (ffffffff81bd87a4)
Location: arch/x86/mm/init.c:201
Inline: False
Direct callers:
  - arch/x86/mm/init.c:probe_page_size_mask
  - arch/x86/mm/init.c:probe_page_size_mask
```
**Symbols:**

```
ffffffff81bd87a4-ffffffff81bd87ce: cr4_set_bits_and_update_boot (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void cr4_set_bits_and_update_boot(long unsigned int mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init.c (ffffffff81bca64b)
Location: arch/x86/mm/init.c:210
Inline: False
Direct callers:
  - arch/x86/mm/init.c:probe_page_size_mask
  - arch/x86/mm/init.c:probe_page_size_mask
```
**Symbols:**

```
ffffffff81bca64b-ffffffff81bca675: cr4_set_bits_and_update_boot (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void cr4_set_bits_and_update_boot(long unsigned int mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init.c (ffffffff81c9faca)
Location: arch/x86/mm/init.c:208
Inline: False
Direct callers:
  - arch/x86/mm/init.c:probe_page_size_mask
  - arch/x86/mm/init.c:probe_page_size_mask
```
**Symbols:**

```
ffffffff81c9faca-ffffffff81c9faf4: cr4_set_bits_and_update_boot (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void cr4_set_bits_and_update_boot(long unsigned int mask);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init.c (ffffffff81e4f333)
Location: arch/x86/mm/init.c:217
Inline: False
Direct callers:
  - arch/x86/mm/init.c:probe_page_size_mask
  - arch/x86/mm/init.c:probe_page_size_mask
```
**Symbols:**

```
ffffffff81e4f333-ffffffff81e4f367: cr4_set_bits_and_update_boot (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init.c (ffffffff83e9a5ed)
Location: arch/x86/mm/init.c:218
Inline: True
Inline callers:
  - arch/x86/mm/init.c:probe_page_size_mask
  - arch/x86/mm/init.c:probe_page_size_mask
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init.c (ffffffff836be00d)
Location: arch/x86/mm/init.c:219
Inline: True
Inline callers:
  - arch/x86/mm/init.c:probe_page_size_mask
  - arch/x86/mm/init.c:probe_page_size_mask
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init.c (ffffffff838eeacd)
Location: arch/x86/mm/init.c:218
Inline: True
Inline callers:
  - arch/x86/mm/init.c:probe_page_size_mask
  - arch/x86/mm/init.c:probe_page_size_mask
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
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init.c (ffffffff828ad1e9)
Location: arch/x86/include/asm/tlbflush.h:363
Inline: True
Inline callers:
  - arch/x86/mm/init.c:init_mem_mapping
  - arch/x86/mm/init.c:init_mem_mapping
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init.c (ffffffff828a54b0)
Location: arch/x86/include/asm/tlbflush.h:363
Inline: True
Inline callers:
  - arch/x86/mm/init.c:init_mem_mapping
  - arch/x86/mm/init.c:init_mem_mapping
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init.c (ffffffff828c00e8)
Location: arch/x86/include/asm/tlbflush.h:363
Inline: True
Inline callers:
  - arch/x86/mm/init.c:init_mem_mapping
  - arch/x86/mm/init.c:init_mem_mapping
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init.c (ffffffff828c3233)
Location: arch/x86/include/asm/tlbflush.h:363
Inline: True
Inline callers:
  - arch/x86/mm/init.c:init_mem_mapping
  - arch/x86/mm/init.c:init_mem_mapping
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
</ul>
