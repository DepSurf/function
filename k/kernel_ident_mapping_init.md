# Function: <code>kernel_ident_mapping_init</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int kernel_ident_mapping_init(struct x86_mapping_info *info, pgd_t *pgd_page, long unsigned int addr, long unsigned int end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff81069340)
Location: arch/x86/mm/init_64.c:98
Inline: False
Direct callers:
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec_prepare
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec_prepare
  - arch/x86/power/hibernate_64.c:swsusp_arch_resume
```
**Symbols:**

```
ffffffff81069340-ffffffff8106946d: kernel_ident_mapping_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int kernel_ident_mapping_init(struct x86_mapping_info *info, pgd_t *pgd_page, long unsigned int pstart, long unsigned int pend);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff810690e0)
Location: arch/x86/mm/ident_map.c:48
Inline: False
Direct callers:
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec_prepare
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec_prepare
  - arch/x86/power/hibernate_64.c:swsusp_arch_resume
```
**Symbols:**

```
ffffffff810690e0-ffffffff81069200: kernel_ident_mapping_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int kernel_ident_mapping_init(struct x86_mapping_info *info, pgd_t *pgd_page, long unsigned int pstart, long unsigned int pend);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff8106cd30)
Location: arch/x86/mm/ident_map.c:48
Inline: False
Direct callers:
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec_prepare
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec_prepare
  - arch/x86/power/hibernate_64.c:swsusp_arch_resume
```
**Symbols:**

```
ffffffff8106cd30-ffffffff8106ce50: kernel_ident_mapping_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int kernel_ident_mapping_init(struct x86_mapping_info *info, pgd_t *pgd_page, long unsigned int pstart, long unsigned int pend);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff8106c310)
Location: arch/x86/mm/ident_map.c:88
Inline: False
Direct callers:
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec_prepare
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec_prepare
  - arch/x86/power/hibernate_64.c:swsusp_arch_resume
```
**Symbols:**

```
ffffffff8106c310-ffffffff8106c489: kernel_ident_mapping_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int kernel_ident_mapping_init(struct x86_mapping_info *info, pgd_t *pgd_page, long unsigned int pstart, long unsigned int pend);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff81070d90)
Location: arch/x86/mm/ident_map.c:89
Inline: False
Direct callers:
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec_prepare
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec_prepare
  - arch/x86/power/hibernate_64.c:swsusp_arch_resume
```
**Symbols:**

```
ffffffff81070d90-ffffffff81070f4b: kernel_ident_mapping_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int kernel_ident_mapping_init(struct x86_mapping_info *info, pgd_t *pgd_page, long unsigned int pstart, long unsigned int pend);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff81073cb0)
Location: arch/x86/mm/ident_map.c:89
Inline: False
Direct callers:
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec_prepare
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec_prepare
  - arch/x86/power/hibernate_64.c:swsusp_arch_resume
```
**Symbols:**

```
ffffffff81073cb0-ffffffff81073e50: kernel_ident_mapping_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int kernel_ident_mapping_init(struct x86_mapping_info *info, pgd_t *pgd_page, long unsigned int pstart, long unsigned int pend);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff81079ba0)
Location: arch/x86/mm/ident_map.c:89
Inline: False
Direct callers:
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec_prepare
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec_prepare
  - arch/x86/power/hibernate_64.c:swsusp_arch_resume
```
**Symbols:**

```
ffffffff81079ba0-ffffffff81079d40: kernel_ident_mapping_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int kernel_ident_mapping_init(struct x86_mapping_info *info, pgd_t *pgd_page, long unsigned int pstart, long unsigned int pend);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff8107d8c0)
Location: arch/x86/mm/ident_map.c:89
Inline: False
Direct callers:
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec_prepare
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec_prepare
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec_prepare
  - arch/x86/kernel/machine_kexec_64.c:mem_region_callback
  - arch/x86/power/hibernate_64.c:swsusp_arch_resume
```
**Symbols:**

```
ffffffff8107d8c0-ffffffff8107da63: kernel_ident_mapping_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int kernel_ident_mapping_init(struct x86_mapping_info *info, pgd_t *pgd_page, long unsigned int pstart, long unsigned int pend);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff8107e950)
Location: arch/x86/mm/ident_map.c:89
Inline: False
Direct callers:
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec_prepare
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec_prepare
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec_prepare
  - arch/x86/kernel/machine_kexec_64.c:mem_region_callback
  - arch/x86/power/hibernate_64.c:swsusp_arch_resume
```
**Symbols:**

```
ffffffff8107e950-ffffffff8107eaf3: kernel_ident_mapping_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int kernel_ident_mapping_init(struct x86_mapping_info *info, pgd_t *pgd_page, long unsigned int pstart, long unsigned int pend);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff810851a0)
Location: arch/x86/mm/ident_map.c:89
Inline: False
Direct callers:
  - arch/x86/kernel/machine_kexec_64.c:init_pgtable
  - arch/x86/kernel/machine_kexec_64.c:init_pgtable
  - arch/x86/kernel/machine_kexec_64.c:init_pgtable
  - arch/x86/kernel/machine_kexec_64.c:mem_region_callback
  - arch/x86/power/hibernate_64.c:set_up_temporary_mappings
```
**Symbols:**

```
ffffffff810851a0-ffffffff810853ea: kernel_ident_mapping_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int kernel_ident_mapping_init(struct x86_mapping_info *info, pgd_t *pgd_page, long unsigned int pstart, long unsigned int pend);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff81086280)
Location: arch/x86/mm/ident_map.c:97
Inline: False
Direct callers:
  - arch/x86/kernel/machine_kexec_64.c:init_pgtable
  - arch/x86/kernel/machine_kexec_64.c:init_pgtable
  - arch/x86/kernel/machine_kexec_64.c:init_pgtable
  - arch/x86/kernel/machine_kexec_64.c:mem_region_callback
  - arch/x86/power/hibernate_64.c:set_up_temporary_mappings
```
**Symbols:**

```
ffffffff81086280-ffffffff810864ca: kernel_ident_mapping_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int kernel_ident_mapping_init(struct x86_mapping_info *info, pgd_t *pgd_page, long unsigned int pstart, long unsigned int pend);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff81087030)
Location: arch/x86/mm/ident_map.c:97
Inline: False
Direct callers:
  - arch/x86/kernel/machine_kexec_64.c:init_pgtable
  - arch/x86/kernel/machine_kexec_64.c:init_pgtable
  - arch/x86/kernel/machine_kexec_64.c:init_pgtable
  - arch/x86/kernel/machine_kexec_64.c:mem_region_callback
  - arch/x86/power/hibernate_64.c:swsusp_arch_resume
```
**Symbols:**

```
ffffffff81087030-ffffffff81087262: kernel_ident_mapping_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int kernel_ident_mapping_init(struct x86_mapping_info *info, pgd_t *pgd_page, long unsigned int pstart, long unsigned int pend);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/mm/init_64.c (0)
Location: arch/x86/mm/ident_map.c:97
Inline: False
Direct callers:
  - arch/x86/kernel/machine_kexec_64.c:init_pgtable
  - arch/x86/kernel/machine_kexec_64.c:init_pgtable
  - arch/x86/kernel/machine_kexec_64.c:init_pgtable
  - arch/x86/kernel/machine_kexec_64.c:mem_region_callback
  - arch/x86/power/hibernate_64.c:swsusp_arch_resume
```
**Symbols:**

```
ffffffff81ca071e-ffffffff81ca0795: kernel_ident_mapping_init.cold (STB_LOCAL)
ffffffff81096340-ffffffff81096583: kernel_ident_mapping_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int kernel_ident_mapping_init(struct x86_mapping_info *info, pgd_t *pgd_page, long unsigned int pstart, long unsigned int pend);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/mm/init_64.c (0)
Location: arch/x86/mm/ident_map.c:97
Inline: False
Direct callers:
  - arch/x86/kernel/machine_kexec_64.c:init_pgtable
  - arch/x86/kernel/machine_kexec_64.c:init_pgtable
  - arch/x86/kernel/machine_kexec_64.c:init_pgtable
  - arch/x86/kernel/machine_kexec_64.c:mem_region_callback
  - arch/x86/power/hibernate_64.c:swsusp_arch_resume
```
**Symbols:**

```
ffffffff81e4fc46-ffffffff81e4fcb2: kernel_ident_mapping_init.cold (STB_LOCAL)
ffffffff810a8be0-ffffffff810a8e46: kernel_ident_mapping_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int kernel_ident_mapping_init(struct x86_mapping_info *info, pgd_t *pgd_page, long unsigned int pstart, long unsigned int pend);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/mm/init_64.c (0)
Location: arch/x86/mm/ident_map.c:97
Inline: False
Direct callers:
  - arch/x86/kernel/machine_kexec_64.c:init_pgtable
  - arch/x86/kernel/machine_kexec_64.c:init_pgtable
  - arch/x86/kernel/machine_kexec_64.c:init_pgtable
  - arch/x86/kernel/machine_kexec_64.c:mem_region_callback
  - arch/x86/power/hibernate_64.c:swsusp_arch_resume
```
**Symbols:**

```
ffffffff820548fb-ffffffff82054961: kernel_ident_mapping_init.cold (STB_LOCAL)
ffffffff810c2260-ffffffff810c24cc: kernel_ident_mapping_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int kernel_ident_mapping_init(struct x86_mapping_info *info, pgd_t *pgd_page, long unsigned int pstart, long unsigned int pend);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/mm/init_64.c (0)
Location: arch/x86/mm/ident_map.c:97
Inline: False
Direct callers:
  - arch/x86/kernel/machine_kexec_64.c:init_pgtable
  - arch/x86/kernel/machine_kexec_64.c:init_pgtable
  - arch/x86/kernel/machine_kexec_64.c:init_pgtable
  - arch/x86/kernel/machine_kexec_64.c:mem_region_callback
  - arch/x86/power/hibernate_64.c:swsusp_arch_resume
```
**Symbols:**

```
ffffffff820d2f09-ffffffff820d2f6f: kernel_ident_mapping_init.cold (STB_LOCAL)
ffffffff810c5940-ffffffff810c5bac: kernel_ident_mapping_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int kernel_ident_mapping_init(struct x86_mapping_info *info, pgd_t *pgd_page, long unsigned int pstart, long unsigned int pend);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/mm/init_64.c (0)
Location: arch/x86/mm/ident_map.c:110
Inline: False
Direct callers:
  - arch/x86/kernel/machine_kexec_64.c:init_pgtable
  - arch/x86/kernel/machine_kexec_64.c:init_pgtable
  - arch/x86/kernel/machine_kexec_64.c:init_pgtable
  - arch/x86/kernel/machine_kexec_64.c:mem_region_callback
  - arch/x86/power/hibernate_64.c:swsusp_arch_resume
```
**Symbols:**

```
ffffffff821add77-ffffffff821adddd: kernel_ident_mapping_init.cold (STB_LOCAL)
ffffffff810cdd90-ffffffff810cdffc: kernel_ident_mapping_init (STB_GLOBAL)
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
int kernel_ident_mapping_init(struct x86_mapping_info *info, pgd_t *pgd_page, long unsigned int pstart, long unsigned int pend);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff8107d950)
Location: arch/x86/mm/ident_map.c:89
Inline: False
Direct callers:
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec_prepare
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec_prepare
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec_prepare
  - arch/x86/kernel/machine_kexec_64.c:mem_region_callback
  - arch/x86/power/hibernate_64.c:swsusp_arch_resume
```
**Symbols:**

```
ffffffff8107d950-ffffffff8107daf3: kernel_ident_mapping_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int kernel_ident_mapping_init(struct x86_mapping_info *info, pgd_t *pgd_page, long unsigned int pstart, long unsigned int pend);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff8106cc70)
Location: arch/x86/mm/ident_map.c:89
Inline: False
Direct callers:
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec_prepare
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec_prepare
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec_prepare
  - arch/x86/kernel/machine_kexec_64.c:mem_region_callback
  - arch/x86/power/hibernate_64.c:swsusp_arch_resume
```
**Symbols:**

```
ffffffff8106cc70-ffffffff8106cdf2: kernel_ident_mapping_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int kernel_ident_mapping_init(struct x86_mapping_info *info, pgd_t *pgd_page, long unsigned int pstart, long unsigned int pend);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff8107d900)
Location: arch/x86/mm/ident_map.c:89
Inline: False
Direct callers:
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec_prepare
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec_prepare
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec_prepare
  - arch/x86/kernel/machine_kexec_64.c:mem_region_callback
  - arch/x86/power/hibernate_64.c:swsusp_arch_resume
```
**Symbols:**

```
ffffffff8107d900-ffffffff8107daa3: kernel_ident_mapping_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int kernel_ident_mapping_init(struct x86_mapping_info *info, pgd_t *pgd_page, long unsigned int pstart, long unsigned int pend);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/init_64.c (ffffffff8107f9f0)
Location: arch/x86/mm/ident_map.c:89
Inline: False
Direct callers:
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec_prepare
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec_prepare
  - arch/x86/kernel/machine_kexec_64.c:machine_kexec_prepare
  - arch/x86/kernel/machine_kexec_64.c:mem_region_callback
  - arch/x86/power/hibernate_64.c:swsusp_arch_resume
```
**Symbols:**

```
ffffffff8107f9f0-ffffffff8107fb93: kernel_ident_mapping_init (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Changed between <code>4.4</code> and <code>4.8</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>long unsigned int pstart</code>
</li>
<li>
<b>Param added. </b>
<code>long unsigned int pend</code>
</li>
<li>
<b>Param removed. </b>
<code>long unsigned int addr</code>
</li>
<li>
<b>Param removed. </b>
<code>long unsigned int end</code>
</li>
</ul>
</details>
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
