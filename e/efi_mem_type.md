# Function: <code>efi_mem_type</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
u32 efi_mem_type(long unsigned int phys_addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/platform/efi/efi.c (ffffffff81078f60)
Location: arch/x86/platform/efi/efi.c:1002
Inline: False
Direct callers:
  - arch/x86/kernel/setup.c:setup_arch
```
**Symbols:**

```
ffffffff81078f60-ffffffff81078fba: efi_mem_type (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
u32 efi_mem_type(long unsigned int phys_addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/platform/efi/efi.c (ffffffff8107a410)
Location: arch/x86/platform/efi/efi.c:986
Inline: False
Direct callers:
  - arch/x86/kernel/setup.c:setup_arch
```
**Symbols:**

```
ffffffff8107a410-ffffffff8107a480: efi_mem_type (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
u32 efi_mem_type(long unsigned int phys_addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/platform/efi/efi.c (ffffffff8107e1f0)
Location: arch/x86/platform/efi/efi.c:1034
Inline: False
Direct callers:
  - arch/x86/kernel/setup.c:setup_arch
```
**Symbols:**

```
ffffffff8107e1f0-ffffffff8107e260: efi_mem_type (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
u32 efi_mem_type(long unsigned int phys_addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/platform/efi/efi.c (ffffffff8107c5a0)
Location: arch/x86/platform/efi/efi.c:1038
Inline: False
Direct callers:
  - arch/x86/kernel/setup.c:setup_arch
```
**Symbols:**

```
ffffffff8107c5a0-ffffffff8107c610: efi_mem_type (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int efi_mem_type(long unsigned int phys_addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/efi.c (ffffffff817fb8b0)
Location: drivers/firmware/efi/efi.c:851
Inline: False
Direct callers:
  - arch/x86/kernel/setup.c:setup_arch
  - drivers/firmware/efi/efi-bgrt.c:efi_bgrt_init
```
**Symbols:**

```
ffffffff817fb8b0-ffffffff817fb92c: efi_mem_type (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int efi_mem_type(long unsigned int phys_addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/efi.c (ffffffff81845020)
Location: drivers/firmware/efi/efi.c:865
Inline: False
Direct callers:
  - arch/x86/kernel/setup.c:setup_arch
  - drivers/firmware/efi/efi-bgrt.c:efi_bgrt_init
```
**Symbols:**

```
ffffffff81845020-ffffffff81845094: efi_mem_type (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int efi_mem_type(long unsigned int phys_addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/efi.c (ffffffff81871140)
Location: drivers/firmware/efi/efi.c:912
Inline: False
Direct callers:
  - arch/x86/kernel/setup.c:setup_arch
  - drivers/firmware/efi/efi-bgrt.c:efi_bgrt_init
```
**Symbols:**

```
ffffffff81871140-ffffffff818711b4: efi_mem_type (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int efi_mem_type(long unsigned int phys_addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/efi.c (ffffffff818b53d0)
Location: drivers/firmware/efi/efi.c:916
Inline: False
Direct callers:
  - arch/x86/kernel/setup.c:setup_arch
  - drivers/firmware/efi/efi-bgrt.c:efi_bgrt_init
```
**Symbols:**

```
ffffffff818b53d0-ffffffff818b543b: efi_mem_type (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int efi_mem_type(long unsigned int phys_addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/efi.c (ffffffff818e7d70)
Location: drivers/firmware/efi/efi.c:906
Inline: False
Direct callers:
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/mm/ioremap.c:__ioremap_caller
  - drivers/firmware/efi/efi-bgrt.c:efi_bgrt_init
```
**Symbols:**

```
ffffffff818e7d70-ffffffff818e7ddb: efi_mem_type (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int efi_mem_type(long unsigned int phys_addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/efi.c (ffffffff819bb070)
Location: drivers/firmware/efi/efi.c:820
Inline: False
Direct callers:
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/mm/ioremap.c:__ioremap_caller
  - drivers/firmware/efi/efi-bgrt.c:efi_bgrt_init
```
**Symbols:**

```
ffffffff819bb070-ffffffff819bb0db: efi_mem_type (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int efi_mem_type(long unsigned int phys_addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/efi.c (ffffffff819bd2d0)
Location: drivers/firmware/efi/efi.c:828
Inline: False
Direct callers:
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/mm/ioremap.c:__ioremap_caller
  - drivers/firmware/efi/efi-bgrt.c:efi_bgrt_init
```
**Symbols:**

```
ffffffff819bd2d0-ffffffff819bd33b: efi_mem_type (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int efi_mem_type(long unsigned int phys_addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/efi.c (ffffffff819a1a60)
Location: drivers/firmware/efi/efi.c:828
Inline: False
Direct callers:
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/mm/ioremap.c:__ioremap_caller
  - arch/x86/mm/ioremap.c:__ioremap_caller
  - drivers/firmware/efi/efi-bgrt.c:efi_bgrt_init
```
**Symbols:**

```
ffffffff819a1a60-ffffffff819a1acb: efi_mem_type (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int efi_mem_type(long unsigned int phys_addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/efi.c (ffffffff81a4ea20)
Location: drivers/firmware/efi/efi.c:835
Inline: False
Direct callers:
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/mm/ioremap.c:__ioremap_caller
  - arch/x86/mm/ioremap.c:__ioremap_caller
  - drivers/firmware/efi/efi-bgrt.c:efi_bgrt_init
```
**Symbols:**

```
ffffffff81a4ea20-ffffffff81a4ea8b: efi_mem_type (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int efi_mem_type(long unsigned int phys_addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/efi.c (ffffffff81bbd660)
Location: drivers/firmware/efi/efi.c:849
Inline: False
Direct callers:
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/mm/ioremap.c:memremap_should_map_decrypted
  - arch/x86/mm/ioremap.c:__ioremap_caller
  - arch/x86/mm/ioremap.c:__ioremap_caller
  - drivers/firmware/efi/efi-bgrt.c:efi_bgrt_init
```
**Symbols:**

```
ffffffff81bbd660-ffffffff81bbd701: efi_mem_type (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int efi_mem_type(long unsigned int phys_addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/efi.c (ffffffff81d63330)
Location: drivers/firmware/efi/efi.c:873
Inline: False
Direct callers:
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/mm/ioremap.c:memremap_should_map_decrypted
  - arch/x86/mm/ioremap.c:__ioremap_caller
  - arch/x86/mm/ioremap.c:__ioremap_caller
  - drivers/firmware/efi/efi-bgrt.c:efi_bgrt_init
```
**Symbols:**

```
ffffffff81d63330-ffffffff81d633d1: efi_mem_type (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int efi_mem_type(long unsigned int phys_addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/efi.c (ffffffff81dce410)
Location: drivers/firmware/efi/efi.c:940
Inline: False
Direct callers:
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/mm/ioremap.c:memremap_should_map_decrypted
  - arch/x86/mm/ioremap.c:__ioremap_caller
  - arch/x86/mm/ioremap.c:__ioremap_caller
  - drivers/firmware/efi/efi-bgrt.c:efi_bgrt_init
```
**Symbols:**

```
ffffffff81dce410-ffffffff81dce4b1: efi_mem_type (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int efi_mem_type(long unsigned int phys_addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/efi.c (ffffffff81e87110)
Location: drivers/firmware/efi/efi.c:978
Inline: False
Direct callers:
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/mm/ioremap.c:memremap_should_map_decrypted
  - arch/x86/mm/ioremap.c:__ioremap_caller
  - arch/x86/mm/ioremap.c:__ioremap_caller
  - drivers/firmware/efi/efi-bgrt.c:efi_bgrt_init
```
**Symbols:**

```
ffffffff81e87110-ffffffff81e871b1: efi_mem_type (STB_GLOBAL)
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
int efi_mem_type(long unsigned int phys_addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/efi.c (ffff800010b5ae90)
Location: drivers/firmware/efi/efi.c:906
Inline: False
Direct callers:
  - drivers/firmware/efi/efi-bgrt.c:efi_bgrt_init
```
**Symbols:**

```
ffff800010b5ae90-ffff800010b5af38: efi_mem_type (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int efi_mem_type(long unsigned int phys_addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/efi.c (c0c3ba98)
Location: drivers/firmware/efi/efi.c:906
Inline: False
```
**Symbols:**

```
c0c3ba98-c0c3bb4c: efi_mem_type (STB_GLOBAL)
```
</details>
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
int efi_mem_type(long unsigned int phys_addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/efi.c (ffffffff8188aaf0)
Location: drivers/firmware/efi/efi.c:906
Inline: False
Direct callers:
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/mm/ioremap.c:__ioremap_caller
```
**Symbols:**

```
ffffffff8188aaf0-ffffffff8188ab5b: efi_mem_type (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int efi_mem_type(long unsigned int phys_addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/efi.c (ffffffff81842470)
Location: drivers/firmware/efi/efi.c:906
Inline: False
Direct callers:
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/mm/ioremap.c:__ioremap_caller
```
**Symbols:**

```
ffffffff81842470-ffffffff818424db: efi_mem_type (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int efi_mem_type(long unsigned int phys_addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/efi.c (ffffffff818dcbd0)
Location: drivers/firmware/efi/efi.c:906
Inline: False
Direct callers:
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/mm/ioremap.c:__ioremap_caller
  - drivers/firmware/efi/efi-bgrt.c:efi_bgrt_init
```
**Symbols:**

```
ffffffff818dcbd0-ffffffff818dcc3b: efi_mem_type (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int efi_mem_type(long unsigned int phys_addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/efi.c (ffffffff818f96e0)
Location: drivers/firmware/efi/efi.c:906
Inline: False
Direct callers:
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/mm/ioremap.c:__ioremap_caller
  - drivers/firmware/efi/efi-bgrt.c:efi_bgrt_init
```
**Symbols:**

```
ffffffff818f96e0-ffffffff818f974b: efi_mem_type (STB_GLOBAL)
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
<details>
<summary>Changed between <code>4.13</code> and <code>4.15</code> ⚠️</summary>
<ul>
<li>
<b>Return type changed. </b>
<code>u32</code> ➡️ <code>int</code>
</li>
</ul>
</details>
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
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
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
