# Function: <code>__ioremap_caller</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void *__ioremap_caller(resource_size_t phys_addr, long unsigned int size, enum page_cache_mode pcm, void *caller);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/ioremap.c (ffffffff8106b960)
Location: arch/x86/mm/ioremap.c:83
Inline: False
Direct callers:
  - arch/x86/mm/ioremap.c:ioremap_nocache
  - arch/x86/mm/ioremap.c:ioremap_uc
  - arch/x86/mm/ioremap.c:ioremap_wc
  - arch/x86/mm/ioremap.c:ioremap_wt
  - arch/x86/mm/ioremap.c:ioremap_prot
  - arch/x86/mm/ioremap.c:ioremap_prot
  - arch/x86/mm/ioremap.c:xlate_dev_mem_ptr
```
**Symbols:**

```
ffffffff8106b960-ffffffff8106bcd8: __ioremap_caller (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void *__ioremap_caller(resource_size_t phys_addr, long unsigned int size, enum page_cache_mode pcm, void *caller);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/ioremap.c (ffffffff8106b840)
Location: arch/x86/mm/ioremap.c:82
Inline: False
Direct callers:
  - arch/x86/mm/ioremap.c:xlate_dev_mem_ptr
  - arch/x86/mm/ioremap.c:ioremap_prot
  - arch/x86/mm/ioremap.c:ioremap_prot
  - arch/x86/mm/ioremap.c:ioremap_wt
  - arch/x86/mm/ioremap.c:ioremap_wc
  - arch/x86/mm/ioremap.c:ioremap_uc
  - arch/x86/mm/ioremap.c:ioremap_nocache
```
**Symbols:**

```
ffffffff8106b840-ffffffff8106bb8d: __ioremap_caller (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void *__ioremap_caller(resource_size_t phys_addr, long unsigned int size, enum page_cache_mode pcm, void *caller);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/ioremap.c (ffffffff8106f460)
Location: arch/x86/mm/ioremap.c:82
Inline: False
Direct callers:
  - arch/x86/mm/ioremap.c:xlate_dev_mem_ptr
  - arch/x86/mm/ioremap.c:ioremap_prot
  - arch/x86/mm/ioremap.c:ioremap_prot
  - arch/x86/mm/ioremap.c:ioremap_wt
  - arch/x86/mm/ioremap.c:ioremap_wc
  - arch/x86/mm/ioremap.c:ioremap_uc
  - arch/x86/mm/ioremap.c:ioremap_nocache
```
**Symbols:**

```
ffffffff8106f460-ffffffff8106f7ad: __ioremap_caller (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void *__ioremap_caller(resource_size_t phys_addr, long unsigned int size, enum page_cache_mode pcm, void *caller);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/ioremap.c (ffffffff8106ebb0)
Location: arch/x86/mm/ioremap.c:83
Inline: False
Direct callers:
  - arch/x86/mm/ioremap.c:xlate_dev_mem_ptr
  - arch/x86/mm/ioremap.c:ioremap_prot
  - arch/x86/mm/ioremap.c:ioremap_prot
  - arch/x86/mm/ioremap.c:ioremap_wt
  - arch/x86/mm/ioremap.c:ioremap_wc
  - arch/x86/mm/ioremap.c:ioremap_uc
  - arch/x86/mm/ioremap.c:ioremap_nocache
```
**Symbols:**

```
ffffffff8106ebb0-ffffffff8106eed4: __ioremap_caller (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void *__ioremap_caller(resource_size_t phys_addr, long unsigned int size, enum page_cache_mode pcm, void *caller);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/ioremap.c (ffffffff81073cc0)
Location: arch/x86/mm/ioremap.c:133
Inline: False
Direct callers:
  - arch/x86/mm/ioremap.c:ioremap_prot
  - arch/x86/mm/ioremap.c:ioremap_prot
  - arch/x86/mm/ioremap.c:ioremap_cache
  - arch/x86/mm/ioremap.c:ioremap_wt
  - arch/x86/mm/ioremap.c:ioremap_wc
  - arch/x86/mm/ioremap.c:ioremap_uc
  - arch/x86/mm/ioremap.c:ioremap_nocache
```
**Symbols:**

```
ffffffff81073cc0-ffffffff81073fc2: __ioremap_caller (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
void *__ioremap_caller(resource_size_t phys_addr, long unsigned int size, enum page_cache_mode pcm, void *caller);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/mm/ioremap.c (0)
Location: arch/x86/mm/ioremap.c:133
Inline: False
Direct callers:
  - arch/x86/mm/ioremap.c:ioremap_prot
  - arch/x86/mm/ioremap.c:ioremap_cache
  - arch/x86/mm/ioremap.c:ioremap_wt
  - arch/x86/mm/ioremap.c:ioremap_wc
  - arch/x86/mm/ioremap.c:ioremap_uc
  - arch/x86/mm/ioremap.c:ioremap_nocache
```
**Symbols:**

```
ffffffff81076710-ffffffff810769da: __ioremap_caller (STB_LOCAL)
ffffffff81076e02-ffffffff81076e44: __ioremap_caller.cold.15 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
void *__ioremap_caller(resource_size_t phys_addr, long unsigned int size, enum page_cache_mode pcm, void *caller, bool encrypted);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/mm/ioremap.c (0)
Location: arch/x86/mm/ioremap.c:133
Inline: False
Direct callers:
  - arch/x86/mm/ioremap.c:ioremap_prot
  - arch/x86/mm/ioremap.c:ioremap_cache
  - arch/x86/mm/ioremap.c:ioremap_encrypted
  - arch/x86/mm/ioremap.c:ioremap_wt
  - arch/x86/mm/ioremap.c:ioremap_wc
  - arch/x86/mm/ioremap.c:ioremap_uc
  - arch/x86/mm/ioremap.c:ioremap_nocache
```
**Symbols:**

```
ffffffff8107cd60-ffffffff8107d041: __ioremap_caller (STB_LOCAL)
ffffffff8107d492-ffffffff8107d4d4: __ioremap_caller.cold.15 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void *__ioremap_caller(resource_size_t phys_addr, long unsigned int size, enum page_cache_mode pcm, void *caller, bool encrypted);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/mm/ioremap.c (0)
Location: arch/x86/mm/ioremap.c:154
Inline: False
Direct callers:
  - arch/x86/mm/ioremap.c:ioremap_prot
  - arch/x86/mm/ioremap.c:ioremap_prot
  - arch/x86/mm/ioremap.c:ioremap_cache
  - arch/x86/mm/ioremap.c:ioremap_encrypted
  - arch/x86/mm/ioremap.c:ioremap_wt
  - arch/x86/mm/ioremap.c:ioremap_wc
  - arch/x86/mm/ioremap.c:ioremap_uc
  - arch/x86/mm/ioremap.c:ioremap_nocache
```
**Symbols:**

```
ffffffff810804e0-ffffffff81080796: __ioremap_caller (STB_LOCAL)
ffffffff81080d42-ffffffff81080da6: __ioremap_caller.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
void *__ioremap_caller(resource_size_t phys_addr, long unsigned int size, enum page_cache_mode pcm, void *caller, bool encrypted);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/mm/ioremap.c (0)
Location: arch/x86/mm/ioremap.c:176
Inline: False
Direct callers:
  - arch/x86/mm/ioremap.c:ioremap_prot
  - arch/x86/mm/ioremap.c:ioremap_prot
  - arch/x86/mm/ioremap.c:ioremap_cache
  - arch/x86/mm/ioremap.c:ioremap_encrypted
  - arch/x86/mm/ioremap.c:ioremap_wt
  - arch/x86/mm/ioremap.c:ioremap_wc
  - arch/x86/mm/ioremap.c:ioremap_uc
  - arch/x86/mm/ioremap.c:ioremap_nocache
```
**Symbols:**

```
ffffffff810816c0-ffffffff8108199a: __ioremap_caller (STB_LOCAL)
ffffffff81081e02-ffffffff81081e66: __ioremap_caller.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
void *__ioremap_caller(resource_size_t phys_addr, long unsigned int size, enum page_cache_mode pcm, void *caller, bool encrypted);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/mm/ioremap.c (0)
Location: arch/x86/mm/ioremap.c:176
Inline: False
Direct callers:
  - arch/x86/mm/ioremap.c:ioremap_prot
  - arch/x86/mm/ioremap.c:ioremap_cache
  - arch/x86/mm/ioremap.c:ioremap_encrypted
  - arch/x86/mm/ioremap.c:ioremap_wt
  - arch/x86/mm/ioremap.c:ioremap_wc
  - arch/x86/mm/ioremap.c:ioremap_uc
  - arch/x86/mm/ioremap.c:ioremap
```
**Symbols:**

```
ffffffff81088660-ffffffff8108894f: __ioremap_caller (STB_LOCAL)
ffffffff81088ead-ffffffff81088f11: __ioremap_caller.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
void *__ioremap_caller(resource_size_t phys_addr, long unsigned int size, enum page_cache_mode pcm, void *caller, bool encrypted);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/mm/ioremap.c (0)
Location: arch/x86/mm/ioremap.c:176
Inline: False
Direct callers:
  - arch/x86/mm/ioremap.c:ioremap_prot
  - arch/x86/mm/ioremap.c:ioremap_cache
  - arch/x86/mm/ioremap.c:ioremap_encrypted
  - arch/x86/mm/ioremap.c:ioremap_wt
  - arch/x86/mm/ioremap.c:ioremap_wc
  - arch/x86/mm/ioremap.c:ioremap_uc
  - arch/x86/mm/ioremap.c:ioremap
```
**Symbols:**

```
ffffffff810888a0-ffffffff81088b8f: __ioremap_caller (STB_LOCAL)
ffffffff81bd96d9-ffffffff81bd973d: __ioremap_caller.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
void *__ioremap_caller(resource_size_t phys_addr, long unsigned int size, enum page_cache_mode pcm, void *caller, bool encrypted);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/mm/ioremap.c (0)
Location: arch/x86/mm/ioremap.c:178
Inline: False
Direct callers:
  - arch/x86/mm/ioremap.c:ioremap_prot
  - arch/x86/mm/ioremap.c:ioremap_cache
  - arch/x86/mm/ioremap.c:ioremap_encrypted
  - arch/x86/mm/ioremap.c:ioremap_wt
  - arch/x86/mm/ioremap.c:ioremap_wc
  - arch/x86/mm/ioremap.c:ioremap_uc
  - arch/x86/mm/ioremap.c:ioremap
```
**Symbols:**

```
ffffffff81089500-ffffffff81089823: __ioremap_caller (STB_LOCAL)
ffffffff81bcb6af-ffffffff81bcb713: __ioremap_caller.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void *__ioremap_caller(resource_size_t phys_addr, long unsigned int size, enum page_cache_mode pcm, void *caller, bool encrypted);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/mm/ioremap.c (0)
Location: arch/x86/mm/ioremap.c:178
Inline: False
Direct callers:
  - arch/x86/mm/ioremap.c:ioremap_prot
  - arch/x86/mm/ioremap.c:ioremap_cache
  - arch/x86/mm/ioremap.c:ioremap_encrypted
  - arch/x86/mm/ioremap.c:ioremap_wt
  - arch/x86/mm/ioremap.c:ioremap_wc
  - arch/x86/mm/ioremap.c:ioremap_uc
  - arch/x86/mm/ioremap.c:ioremap
```
**Symbols:**

```
ffffffff81098990-ffffffff81098cc6: __ioremap_caller (STB_LOCAL)
ffffffff81ca0de7-ffffffff81ca0e81: __ioremap_caller.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void *__ioremap_caller(resource_size_t phys_addr, long unsigned int size, enum page_cache_mode pcm, void *caller, bool encrypted);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/mm/ioremap.c (0)
Location: arch/x86/mm/ioremap.c:178
Inline: False
Direct callers:
  - arch/x86/mm/ioremap.c:ioremap_prot
  - arch/x86/mm/ioremap.c:ioremap_cache
  - arch/x86/mm/ioremap.c:ioremap_encrypted
  - arch/x86/mm/ioremap.c:ioremap_wt
  - arch/x86/mm/ioremap.c:ioremap_wc
  - arch/x86/mm/ioremap.c:ioremap_uc
  - arch/x86/mm/ioremap.c:ioremap
```
**Symbols:**

```
ffffffff810ab730-ffffffff810aba89: __ioremap_caller (STB_LOCAL)
ffffffff81e5039a-ffffffff81e5042e: __ioremap_caller.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void *__ioremap_caller(resource_size_t phys_addr, long unsigned int size, enum page_cache_mode pcm, void *caller, bool encrypted);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/mm/ioremap.c (0)
Location: arch/x86/mm/ioremap.c:179
Inline: False
Direct callers:
  - arch/x86/mm/ioremap.c:ioremap_prot
  - arch/x86/mm/ioremap.c:ioremap_cache
  - arch/x86/mm/ioremap.c:ioremap_encrypted
  - arch/x86/mm/ioremap.c:ioremap_wt
  - arch/x86/mm/ioremap.c:ioremap_wc
  - arch/x86/mm/ioremap.c:ioremap_uc
  - arch/x86/mm/ioremap.c:ioremap
```
**Symbols:**

```
ffffffff810c50b0-ffffffff810c5478: __ioremap_caller (STB_LOCAL)
ffffffff82054a1d-ffffffff82054a53: __ioremap_caller.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void *__ioremap_caller(resource_size_t phys_addr, long unsigned int size, enum page_cache_mode pcm, void *caller, bool encrypted);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/mm/ioremap.c (0)
Location: arch/x86/mm/ioremap.c:184
Inline: False
Direct callers:
  - arch/x86/mm/ioremap.c:ioremap_prot
  - arch/x86/mm/ioremap.c:ioremap_cache
  - arch/x86/mm/ioremap.c:ioremap_encrypted
  - arch/x86/mm/ioremap.c:ioremap_wt
  - arch/x86/mm/ioremap.c:ioremap_wc
  - arch/x86/mm/ioremap.c:ioremap_uc
  - arch/x86/mm/ioremap.c:ioremap
```
**Symbols:**

```
ffffffff810c8840-ffffffff810c8c06: __ioremap_caller (STB_LOCAL)
ffffffff820d302b-ffffffff820d305f: __ioremap_caller.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void *__ioremap_caller(resource_size_t phys_addr, long unsigned int size, enum page_cache_mode pcm, void *caller, bool encrypted);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/mm/ioremap.c (0)
Location: arch/x86/mm/ioremap.c:184
Inline: False
Direct callers:
  - arch/x86/mm/ioremap.c:ioremap_prot
  - arch/x86/mm/ioremap.c:ioremap_cache
  - arch/x86/mm/ioremap.c:ioremap_encrypted
  - arch/x86/mm/ioremap.c:ioremap_wt
  - arch/x86/mm/ioremap.c:ioremap_wc
  - arch/x86/mm/ioremap.c:ioremap_uc
  - arch/x86/mm/ioremap.c:ioremap
```
**Symbols:**

```
ffffffff810d0f40-ffffffff810d1306: __ioremap_caller (STB_LOCAL)
ffffffff821ade99-ffffffff821adecd: __ioremap_caller.cold (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
void *__ioremap_caller(phys_addr_t phys_addr, size_t size, pgprot_t prot, void *caller);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/arm64/mm/ioremap.c (ffff8000100adde8)
Location: arch/arm64/mm/ioremap.c:21
Inline: False
Direct callers:
  - arch/arm64/mm/ioremap.c:__ioremap
```
**Symbols:**

```
ffff8000100adde8-ffff8000100adeb8: __ioremap_caller (STB_LOCAL)
```
</details>
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void *__ioremap_caller(phys_addr_t addr, long unsigned int size, pgprot_t prot, void *caller);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/powerpc/mm/ioremap_64.c (c000000000089a40)
Location: arch/powerpc/mm/ioremap_64.c:57
Inline: False
Direct callers:
  - arch/powerpc/mm/ioremap.c:ioremap_prot
  - arch/powerpc/mm/ioremap.c:ioremap_coherent
  - arch/powerpc/mm/ioremap.c:ioremap_wc
  - arch/powerpc/mm/ioremap.c:ioremap
```
**Symbols:**

```
c000000000089a40-c000000000089b78: __ioremap_caller (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In arch/riscv/mm/ioremap.c (ffffffe0000b9f7c)
Location: arch/riscv/mm/ioremap.c:23
Inline: True
Inline callers:
  - arch/riscv/mm/ioremap.c:ioremap
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
void *__ioremap_caller(resource_size_t phys_addr, long unsigned int size, enum page_cache_mode pcm, void *caller, bool encrypted);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/mm/ioremap.c (0)
Location: arch/x86/mm/ioremap.c:176
Inline: False
Direct callers:
  - arch/x86/mm/ioremap.c:ioremap_prot
  - arch/x86/mm/ioremap.c:ioremap_prot
  - arch/x86/mm/ioremap.c:ioremap_cache
  - arch/x86/mm/ioremap.c:ioremap_encrypted
  - arch/x86/mm/ioremap.c:ioremap_wt
  - arch/x86/mm/ioremap.c:ioremap_wc
  - arch/x86/mm/ioremap.c:ioremap_uc
  - arch/x86/mm/ioremap.c:ioremap_nocache
```
**Symbols:**

```
ffffffff810806c0-ffffffff8108099a: __ioremap_caller (STB_LOCAL)
ffffffff81080e02-ffffffff81080e66: __ioremap_caller.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
void *__ioremap_caller(resource_size_t phys_addr, long unsigned int size, enum page_cache_mode pcm, void *caller, bool encrypted);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/mm/ioremap.c (0)
Location: arch/x86/mm/ioremap.c:176
Inline: False
Direct callers:
  - arch/x86/mm/ioremap.c:ioremap_prot
  - arch/x86/mm/ioremap.c:ioremap_prot
  - arch/x86/mm/ioremap.c:ioremap_cache
  - arch/x86/mm/ioremap.c:ioremap_encrypted
  - arch/x86/mm/ioremap.c:ioremap_wt
  - arch/x86/mm/ioremap.c:ioremap_wc
  - arch/x86/mm/ioremap.c:ioremap_uc
  - arch/x86/mm/ioremap.c:ioremap_nocache
```
**Symbols:**

```
ffffffff8106f610-ffffffff8106f8ea: __ioremap_caller (STB_LOCAL)
ffffffff8106fd52-ffffffff8106fdb6: __ioremap_caller.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
void *__ioremap_caller(resource_size_t phys_addr, long unsigned int size, enum page_cache_mode pcm, void *caller, bool encrypted);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/mm/ioremap.c (0)
Location: arch/x86/mm/ioremap.c:176
Inline: False
Direct callers:
  - arch/x86/mm/ioremap.c:ioremap_prot
  - arch/x86/mm/ioremap.c:ioremap_prot
  - arch/x86/mm/ioremap.c:ioremap_cache
  - arch/x86/mm/ioremap.c:ioremap_encrypted
  - arch/x86/mm/ioremap.c:ioremap_wt
  - arch/x86/mm/ioremap.c:ioremap_wc
  - arch/x86/mm/ioremap.c:ioremap_uc
  - arch/x86/mm/ioremap.c:ioremap_nocache
```
**Symbols:**

```
ffffffff81080670-ffffffff8108094a: __ioremap_caller (STB_LOCAL)
ffffffff81080db2-ffffffff81080e16: __ioremap_caller.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
void *__ioremap_caller(resource_size_t phys_addr, long unsigned int size, enum page_cache_mode pcm, void *caller, bool encrypted);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/mm/ioremap.c (0)
Location: arch/x86/mm/ioremap.c:176
Inline: False
Direct callers:
  - arch/x86/mm/ioremap.c:ioremap_prot
  - arch/x86/mm/ioremap.c:ioremap_prot
  - arch/x86/mm/ioremap.c:ioremap_cache
  - arch/x86/mm/ioremap.c:ioremap_encrypted
  - arch/x86/mm/ioremap.c:ioremap_wt
  - arch/x86/mm/ioremap.c:ioremap_wc
  - arch/x86/mm/ioremap.c:ioremap_uc
  - arch/x86/mm/ioremap.c:ioremap_nocache
```
**Symbols:**

```
ffffffff81082790-ffffffff81082a6a: __ioremap_caller (STB_LOCAL)
ffffffff81082ed2-ffffffff81082f36: __ioremap_caller.cold (STB_LOCAL)
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
<b>Param added. </b>
<code>bool encrypted</code>
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
<li>
<details>
<summary>Changed between <code>amd64</code> and <code>arm64</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>pgprot_t prot</code>
</li>
<li>
<b>Param removed. </b>
<code>enum page_cache_mode pcm</code>
</li>
<li>
<b>Param removed. </b>
<code>bool encrypted</code>
</li>
<li>
<b>Param type changed. </b>
<code>resource_size_t phys_addr</code> ➡️ <code>phys_addr_t phys_addr</code>
</li>
<li>
<b>Param type changed. </b>
<code>long unsigned int size</code> ➡️ <code>size_t size</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>amd64</code> and <code>ppc64el</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>phys_addr_t addr</code>
</li>
<li>
<b>Param added. </b>
<code>pgprot_t prot</code>
</li>
<li>
<b>Param removed. </b>
<code>resource_size_t phys_addr</code>
</li>
<li>
<b>Param removed. </b>
<code>enum page_cache_mode pcm</code>
</li>
<li>
<b>Param removed. </b>
<code>bool encrypted</code>
</li>
</ul>
</details>
</li>
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
