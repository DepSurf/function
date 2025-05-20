# Function: <code>efi_query_variable_store</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
efi_status_t efi_query_variable_store(u32 attributes, long unsigned int size);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/platform/efi/quirks.c (ffffffff81078d00)
Location: arch/x86/platform/efi/quirks.c:63
Inline: True
```
**Symbols:**

```
ffffffff81078d00-ffffffff81078e78: efi_query_variable_store (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
efi_status_t efi_query_variable_store(u32 attributes, long unsigned int size, bool nonblocking);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/platform/efi/quirks.c (ffffffff8107a1f0)
Location: arch/x86/platform/efi/quirks.c:93
Inline: True
```
**Symbols:**

```
ffffffff8107a1f0-ffffffff8107a3a3: efi_query_variable_store (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
efi_status_t efi_query_variable_store(u32 attributes, long unsigned int size, bool nonblocking);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/platform/efi/quirks.c (ffffffff8107dfd0)
Location: arch/x86/platform/efi/quirks.c:93
Inline: True
```
**Symbols:**

```
ffffffff8107dfd0-ffffffff8107e183: efi_query_variable_store (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
efi_status_t efi_query_variable_store(u32 attributes, long unsigned int size, bool nonblocking);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/platform/efi/quirks.c (ffffffff8107c3c0)
Location: arch/x86/platform/efi/quirks.c:149
Inline: True
```
**Symbols:**

```
ffffffff8107c3c0-ffffffff8107c540: efi_query_variable_store (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
efi_status_t efi_query_variable_store(u32 attributes, long unsigned int size, bool nonblocking);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/platform/efi/quirks.c (ffffffff81082ac0)
Location: arch/x86/platform/efi/quirks.c:149
Inline: True
```
**Symbols:**

```
ffffffff81082ac0-ffffffff81082c58: efi_query_variable_store (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
efi_status_t efi_query_variable_store(u32 attributes, long unsigned int size, bool nonblocking);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/platform/efi/quirks.c (ffffffff81086180)
Location: arch/x86/platform/efi/quirks.c:150
Inline: True
```
**Symbols:**

```
ffffffff81086180-ffffffff8108631b: efi_query_variable_store (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
efi_status_t efi_query_variable_store(u32 attributes, long unsigned int size, bool nonblocking);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/platform/efi/quirks.c (ffffffff8108cf20)
Location: arch/x86/platform/efi/quirks.c:149
Inline: True
```
**Symbols:**

```
ffffffff8108cf20-ffffffff8108d0bb: efi_query_variable_store (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
efi_status_t efi_query_variable_store(u32 attributes, long unsigned int size, bool nonblocking);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/platform/efi/quirks.c (ffffffff81090de0)
Location: arch/x86/platform/efi/quirks.c:150
Inline: True
```
**Symbols:**

```
ffffffff81090de0-ffffffff81090f6b: efi_query_variable_store (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
efi_status_t efi_query_variable_store(u32 attributes, long unsigned int size, bool nonblocking);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/platform/efi/quirks.c (ffffffff81091ae0)
Location: arch/x86/platform/efi/quirks.c:150
Inline: True
```
**Symbols:**

```
ffffffff81091ae0-ffffffff81091c6b: efi_query_variable_store (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
efi_status_t efi_query_variable_store(u32 attributes, long unsigned int size, bool nonblocking);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/platform/efi/quirks.c (ffffffff81097350)
Location: arch/x86/platform/efi/quirks.c:151
Inline: True
```
**Symbols:**

```
ffffffff81097350-ffffffff81097490: efi_query_variable_store.part.0 (STB_LOCAL)
ffffffff81097490-ffffffff81097515: efi_query_variable_store (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

```c
efi_status_t efi_query_variable_store(u32 attributes, long unsigned int size, bool nonblocking);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/platform/efi/quirks.c (ffffffff810965a0)
Location: arch/x86/platform/efi/quirks.c:151
Inline: True
```
**Symbols:**

```
ffffffff810965a0-ffffffff810966e0: efi_query_variable_store.part.0 (STB_LOCAL)
ffffffff810966e0-ffffffff81096765: efi_query_variable_store (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

```c
efi_status_t efi_query_variable_store(u32 attributes, long unsigned int size, bool nonblocking);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/platform/efi/quirks.c (ffffffff81096e80)
Location: arch/x86/platform/efi/quirks.c:151
Inline: True
```
**Symbols:**

```
ffffffff81096e80-ffffffff81096fd1: efi_query_variable_store.part.0 (STB_LOCAL)
ffffffff81096fe0-ffffffff81097065: efi_query_variable_store (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
efi_status_t efi_query_variable_store(u32 attributes, long unsigned int size, bool nonblocking);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/platform/efi/quirks.c (ffffffff810a6f50)
Location: arch/x86/platform/efi/quirks.c:151
Inline: True
```
**Symbols:**

```
ffffffff810a6de0-ffffffff810a6f42: efi_query_variable_store.part.0 (STB_LOCAL)
ffffffff81ca259d-ffffffff81ca25ba: efi_query_variable_store.part.0.cold (STB_LOCAL)
ffffffff810a6f50-ffffffff810a6fd5: efi_query_variable_store (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
efi_status_t efi_query_variable_store(u32 attributes, long unsigned int size, bool nonblocking);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/platform/efi/quirks.c (0)
Location: arch/x86/platform/efi/quirks.c:151
Inline: False
```
**Symbols:**

```
ffffffff81e51df6-ffffffff81e51e0b: efi_query_variable_store.cold (STB_LOCAL)
ffffffff810bc110-ffffffff810bc30b: efi_query_variable_store (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
efi_status_t efi_query_variable_store(u32 attributes, long unsigned int size, bool nonblocking);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/platform/efi/quirks.c (0)
Location: arch/x86/platform/efi/quirks.c:151
Inline: False
```
**Symbols:**

```
ffffffff82055490-ffffffff820554a5: efi_query_variable_store.cold (STB_LOCAL)
ffffffff810d7530-ffffffff810d772b: efi_query_variable_store (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
efi_status_t efi_query_variable_store(u32 attributes, long unsigned int size, bool nonblocking);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/platform/efi/quirks.c (0)
Location: arch/x86/platform/efi/quirks.c:159
Inline: False
```
**Symbols:**

```
ffffffff820d3ac4-ffffffff820d3ad9: efi_query_variable_store.cold (STB_LOCAL)
ffffffff810e2ac0-ffffffff810e2cbb: efi_query_variable_store (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
efi_status_t efi_query_variable_store(u32 attributes, long unsigned int size, bool nonblocking);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/platform/efi/quirks.c (0)
Location: arch/x86/platform/efi/quirks.c:159
Inline: False
```
**Symbols:**

```
ffffffff821ae932-ffffffff821ae947: efi_query_variable_store.cold (STB_LOCAL)
ffffffff810eb340-ffffffff810eb53b: efi_query_variable_store (STB_GLOBAL)
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
efi_status_t efi_query_variable_store(u32 attributes, long unsigned int size, bool nonblocking);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/efi.c (ffff800010b5a7a8)
Location: include/linux/efi.h:1053
Inline: False
```
**Symbols:**

```
ffff800010b5a7a8-ffff800010b5a7b0: efi_query_variable_store (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
efi_status_t efi_query_variable_store(u32 attributes, long unsigned int size, bool nonblocking);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/efi.c (c0c3b3bc)
Location: include/linux/efi.h:1053
Inline: False
```
**Symbols:**

```
c0c3b3bc-c0c3b3d0: efi_query_variable_store (STB_LOCAL)
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
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
efi_status_t efi_query_variable_store(u32 attributes, long unsigned int size, bool nonblocking);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/platform/efi/quirks.c (ffffffff81090aa0)
Location: arch/x86/platform/efi/quirks.c:150
Inline: True
```
**Symbols:**

```
ffffffff81090aa0-ffffffff81090c2b: efi_query_variable_store (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
efi_status_t efi_query_variable_store(u32 attributes, long unsigned int size, bool nonblocking);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/platform/efi/quirks.c (ffffffff8107f5b0)
Location: arch/x86/platform/efi/quirks.c:150
Inline: True
```
**Symbols:**

```
ffffffff8107f5b0-ffffffff8107f73b: efi_query_variable_store (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
efi_status_t efi_query_variable_store(u32 attributes, long unsigned int size, bool nonblocking);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/platform/efi/quirks.c (ffffffff81090a50)
Location: arch/x86/platform/efi/quirks.c:150
Inline: True
```
**Symbols:**

```
ffffffff81090a50-ffffffff81090bdb: efi_query_variable_store (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
efi_status_t efi_query_variable_store(u32 attributes, long unsigned int size, bool nonblocking);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/x86/platform/efi/quirks.c (ffffffff81092e30)
Location: arch/x86/platform/efi/quirks.c:150
Inline: True
```
**Symbols:**

```
ffffffff81092e30-ffffffff81092fbb: efi_query_variable_store (STB_GLOBAL)
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
<code>bool nonblocking</code>
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
