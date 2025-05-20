# Function: <code>free_init_pages</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void free_init_pages(char *what, long unsigned int begin, long unsigned int end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init.c (ffffffff81068af0)
Location: arch/x86/mm/init.c:648
Inline: False
Direct callers:
  - arch/x86/kernel/alternative.c:alternative_instructions
  - arch/x86/mm/init.c:free_initmem
  - arch/x86/mm/init.c:free_initrd_mem
  - arch/x86/mm/init_64.c:mark_rodata_ro
  - arch/x86/mm/init_64.c:mark_rodata_ro
```
**Symbols:**

```
ffffffff81068af0-ffffffff81068b89: free_init_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void free_init_pages(char *what, long unsigned int begin, long unsigned int end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init.c (ffffffff810687e0)
Location: arch/x86/mm/init.c:663
Inline: False
Direct callers:
  - arch/x86/kernel/alternative.c:alternative_instructions
  - arch/x86/mm/init.c:free_initrd_mem
  - arch/x86/mm/init.c:free_initmem
  - arch/x86/mm/init_64.c:mark_rodata_ro
  - arch/x86/mm/init_64.c:mark_rodata_ro
```
**Symbols:**

```
ffffffff810687e0-ffffffff81068879: free_init_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void free_init_pages(char *what, long unsigned int begin, long unsigned int end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init.c (ffffffff8106c460)
Location: arch/x86/mm/init.c:663
Inline: False
Direct callers:
  - arch/x86/kernel/alternative.c:alternative_instructions
  - arch/x86/mm/init.c:free_initrd_mem
  - arch/x86/mm/init.c:free_initmem
  - arch/x86/mm/init_64.c:mark_rodata_ro
  - arch/x86/mm/init_64.c:mark_rodata_ro
```
**Symbols:**

```
ffffffff8106c460-ffffffff8106c4f9: free_init_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void free_init_pages(char *what, long unsigned int begin, long unsigned int end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init.c (ffffffff8106b860)
Location: arch/x86/mm/init.c:685
Inline: False
Direct callers:
  - arch/x86/kernel/alternative.c:alternative_instructions
  - arch/x86/mm/init.c:free_initrd_mem
  - arch/x86/mm/init.c:free_initmem
  - arch/x86/mm/init_64.c:mark_rodata_ro
  - arch/x86/mm/init_64.c:mark_rodata_ro
```
**Symbols:**

```
ffffffff8106b860-ffffffff8106b8e2: free_init_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void free_init_pages(char *what, long unsigned int begin, long unsigned int end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init.c (ffffffff810700f0)
Location: arch/x86/mm/init.c:735
Inline: False
Direct callers:
  - arch/x86/kernel/alternative.c:alternative_instructions
  - arch/x86/mm/init.c:free_initrd_mem
  - arch/x86/mm/init.c:free_initmem
  - arch/x86/mm/init_64.c:mark_rodata_ro
  - arch/x86/mm/init_64.c:mark_rodata_ro
```
**Symbols:**

```
ffffffff810700f0-ffffffff81070172: free_init_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void free_init_pages(char *what, long unsigned int begin, long unsigned int end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init.c (ffffffff81072f70)
Location: arch/x86/mm/init.c:739
Inline: False
Direct callers:
  - arch/x86/kernel/alternative.c:alternative_instructions
  - arch/x86/mm/init.c:free_initrd_mem
  - arch/x86/mm/init.c:free_kernel_image_pages
```
**Symbols:**

```
ffffffff81072f70-ffffffff81072ff2: free_init_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void free_init_pages(const char *what, long unsigned int begin, long unsigned int end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init.c (ffffffff81079000)
Location: arch/x86/mm/init.c:745
Inline: False
Direct callers:
  - arch/x86/kernel/alternative.c:alternative_instructions
  - arch/x86/mm/init.c:free_initrd_mem
  - arch/x86/mm/init.c:free_kernel_image_pages
  - arch/x86/mm/mem_encrypt.c:mem_encrypt_free_decrypted_mem
```
**Symbols:**

```
ffffffff81079000-ffffffff81079082: free_init_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void free_init_pages(const char *what, long unsigned int begin, long unsigned int end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/mm/init.c (0)
Location: arch/x86/mm/init.c:783
Inline: False
Direct callers:
  - arch/x86/kernel/alternative.c:alternative_instructions
  - arch/x86/mm/init.c:free_initrd_mem
  - arch/x86/mm/init.c:free_kernel_image_pages
  - arch/x86/mm/mem_encrypt.c:mem_encrypt_free_decrypted_mem
```
**Symbols:**

```
ffffffff8107cda3-ffffffff8107cdbc: free_init_pages.cold (STB_LOCAL)
ffffffff8107cc00-ffffffff8107cc86: free_init_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void free_init_pages(const char *what, long unsigned int begin, long unsigned int end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init.c (ffffffff8107dcb0)
Location: arch/x86/mm/init.c:783
Inline: False
Direct callers:
  - arch/x86/kernel/alternative.c:alternative_instructions
  - arch/x86/mm/init.c:free_initrd_mem
  - arch/x86/mm/init.c:free_kernel_image_pages
  - arch/x86/mm/mem_encrypt.c:mem_encrypt_free_decrypted_mem
```
**Symbols:**

```
ffffffff8107dcb0-ffffffff8107dd30: free_init_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void free_init_pages(const char *what, long unsigned int begin, long unsigned int end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init.c (ffffffff810843b0)
Location: arch/x86/mm/init.c:839
Inline: False
Direct callers:
  - arch/x86/kernel/alternative.c:alternative_instructions
  - arch/x86/mm/init.c:free_initrd_mem
  - arch/x86/mm/init.c:free_kernel_image_pages
  - arch/x86/mm/mem_encrypt.c:mem_encrypt_free_decrypted_mem
```
**Symbols:**

```
ffffffff810843b0-ffffffff81084430: free_init_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void free_init_pages(const char *what, long unsigned int begin, long unsigned int end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init.c (ffffffff81085900)
Location: arch/x86/mm/init.c:842
Inline: False
Direct callers:
  - arch/x86/kernel/alternative.c:alternative_instructions
  - arch/x86/mm/init.c:free_initrd_mem
  - arch/x86/mm/init.c:free_kernel_image_pages
  - arch/x86/mm/mem_encrypt.c:mem_encrypt_free_decrypted_mem
```
**Symbols:**

```
ffffffff81085900-ffffffff81085980: free_init_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void free_init_pages(const char *what, long unsigned int begin, long unsigned int end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init.c (ffffffff810865f0)
Location: arch/x86/mm/init.c:851
Inline: False
Direct callers:
  - arch/x86/kernel/alternative.c:alternative_instructions
  - arch/x86/mm/init.c:free_initrd_mem
  - arch/x86/mm/init.c:free_kernel_image_pages
  - arch/x86/mm/mem_encrypt.c:mem_encrypt_free_decrypted_mem
```
**Symbols:**

```
ffffffff810865f0-ffffffff81086674: free_init_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void free_init_pages(const char *what, long unsigned int begin, long unsigned int end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init.c (ffffffff81095860)
Location: arch/x86/mm/init.c:858
Inline: False
Direct callers:
  - arch/x86/kernel/alternative.c:alternative_instructions
  - arch/x86/mm/init.c:free_initrd_mem
  - arch/x86/mm/init.c:free_kernel_image_pages
  - arch/x86/mm/mem_encrypt.c:mem_encrypt_free_decrypted_mem
```
**Symbols:**

```
ffffffff81095860-ffffffff810958e4: free_init_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void free_init_pages(const char *what, long unsigned int begin, long unsigned int end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init.c (ffffffff810a7a50)
Location: arch/x86/mm/init.c:872
Inline: False
Direct callers:
  - arch/x86/kernel/alternative.c:alternative_instructions
  - arch/x86/mm/init.c:free_initrd_mem
  - arch/x86/mm/init.c:free_kernel_image_pages
  - arch/x86/mm/mem_encrypt_amd.c:mem_encrypt_free_decrypted_mem
```
**Symbols:**

```
ffffffff810a7a50-ffffffff810a7ae0: free_init_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void free_init_pages(const char *what, long unsigned int begin, long unsigned int end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init.c (ffffffff810c0ea0)
Location: arch/x86/mm/init.c:876
Inline: False
Direct callers:
  - arch/x86/kernel/alternative.c:alternative_instructions
  - arch/x86/mm/init.c:free_initrd_mem
  - arch/x86/mm/init.c:free_kernel_image_pages
  - arch/x86/mm/mem_encrypt_amd.c:mem_encrypt_free_decrypted_mem
```
**Symbols:**

```
ffffffff810c0ea0-ffffffff810c0f30: free_init_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void free_init_pages(const char *what, long unsigned int begin, long unsigned int end);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init.c (ffffffff836be88a)
Location: arch/x86/mm/init.c:901
Inline: True
Inline callers:
  - arch/x86/mm/init.c:free_initrd_mem
Direct callers:
  - arch/x86/kernel/alternative.c:alternative_instructions
  - arch/x86/mm/init.c:free_kernel_image_pages
  - arch/x86/mm/mem_encrypt_amd.c:mem_encrypt_free_decrypted_mem
```
**Symbols:**

```
ffffffff810c4580-ffffffff810c4610: free_init_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void free_init_pages(const char *what, long unsigned int begin, long unsigned int end);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init.c (ffffffff838ef32a)
Location: arch/x86/mm/init.c:891
Inline: True
Inline callers:
  - arch/x86/mm/init.c:free_initrd_mem
Direct callers:
  - arch/x86/kernel/alternative.c:alternative_instructions
  - arch/x86/mm/init.c:free_kernel_image_pages
  - arch/x86/mm/mem_encrypt_amd.c:mem_encrypt_free_decrypted_mem
```
**Symbols:**

```
ffffffff810cc9d0-ffffffff810cca60: free_init_pages (STB_GLOBAL)
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
void free_init_pages(const char *what, long unsigned int begin, long unsigned int end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init.c (ffffffff8107ccb0)
Location: arch/x86/mm/init.c:783
Inline: False
Direct callers:
  - arch/x86/kernel/alternative.c:alternative_instructions
  - arch/x86/mm/init.c:free_initrd_mem
  - arch/x86/mm/init.c:free_kernel_image_pages
  - arch/x86/mm/mem_encrypt.c:mem_encrypt_free_decrypted_mem
```
**Symbols:**

```
ffffffff8107ccb0-ffffffff8107cd30: free_init_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void free_init_pages(const char *what, long unsigned int begin, long unsigned int end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init.c (ffffffff8106c420)
Location: arch/x86/mm/init.c:783
Inline: False
Direct callers:
  - arch/x86/kernel/alternative.c:alternative_instructions
  - arch/x86/mm/init.c:free_initrd_mem
  - arch/x86/mm/init.c:free_kernel_image_pages
  - arch/x86/mm/mem_encrypt.c:mem_encrypt_free_decrypted_mem
```
**Symbols:**

```
ffffffff8106c420-ffffffff8106c4a0: free_init_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void free_init_pages(const char *what, long unsigned int begin, long unsigned int end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init.c (ffffffff8107cc60)
Location: arch/x86/mm/init.c:783
Inline: False
Direct callers:
  - arch/x86/kernel/alternative.c:alternative_instructions
  - arch/x86/mm/init.c:free_initrd_mem
  - arch/x86/mm/init.c:free_kernel_image_pages
  - arch/x86/mm/mem_encrypt.c:mem_encrypt_free_decrypted_mem
```
**Symbols:**

```
ffffffff8107cc60-ffffffff8107cce0: free_init_pages (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void free_init_pages(const char *what, long unsigned int begin, long unsigned int end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init.c (ffffffff8107ed60)
Location: arch/x86/mm/init.c:783
Inline: False
Direct callers:
  - arch/x86/kernel/alternative.c:alternative_instructions
  - arch/x86/mm/init.c:free_initrd_mem
  - arch/x86/mm/init.c:free_kernel_image_pages
  - arch/x86/mm/mem_encrypt.c:mem_encrypt_free_decrypted_mem
```
**Symbols:**

```
ffffffff8107ed60-ffffffff8107ede0: free_init_pages (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>4.18</code> and <code>5.0</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>char *what</code> ➡️ <code>const char *what</code>
</li>
</ul>
</details>
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
