# Function: <code>efi_arch_mem_reserve</code>

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
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void efi_arch_mem_reserve(phys_addr_t addr, u64 size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/platform/efi/quirks.c (ffffffff81fdda06)
Location: arch/x86/platform/efi/quirks.c:186
Inline: False
Direct callers:
  - drivers/firmware/efi/efi.c:efi_mem_reserve
```
**Symbols:**

```
ffffffff81fdda06-ffffffff81fddb83: efi_arch_mem_reserve (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void efi_arch_mem_reserve(phys_addr_t addr, u64 size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/platform/efi/quirks.c (ffffffff820be7c4)
Location: arch/x86/platform/efi/quirks.c:242
Inline: False
Direct callers:
  - drivers/firmware/efi/efi.c:efi_mem_reserve
```
**Symbols:**

```
ffffffff820be7c4-ffffffff820be952: efi_arch_mem_reserve (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void efi_arch_mem_reserve(phys_addr_t addr, u64 size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/platform/efi/quirks.c (ffffffff826c68e9)
Location: arch/x86/platform/efi/quirks.c:242
Inline: False
Direct callers:
  - drivers/firmware/efi/efi.c:efi_mem_reserve
```
**Symbols:**

```
ffffffff826c68e9-ffffffff826c6a77: efi_arch_mem_reserve (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void efi_arch_mem_reserve(phys_addr_t addr, u64 size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/platform/efi/quirks.c (ffffffff826f09f5)
Location: arch/x86/platform/efi/quirks.c:244
Inline: False
Direct callers:
  - drivers/firmware/efi/efi.c:efi_mem_reserve
```
**Symbols:**

```
ffffffff826f09f5-ffffffff826f0b6c: efi_arch_mem_reserve (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void efi_arch_mem_reserve(phys_addr_t addr, u64 size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/platform/efi/quirks.c (ffffffff828a76fd)
Location: arch/x86/platform/efi/quirks.c:243
Inline: False
Direct callers:
  - drivers/firmware/efi/efi.c:efi_mem_reserve
```
**Symbols:**

```
ffffffff828a76fd-ffffffff828a787b: efi_arch_mem_reserve (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void efi_arch_mem_reserve(phys_addr_t addr, u64 size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/platform/efi/quirks.c (ffffffff828bfdfb)
Location: arch/x86/platform/efi/quirks.c:244
Inline: False
Direct callers:
  - drivers/firmware/efi/efi.c:efi_mem_reserve
```
**Symbols:**

```
ffffffff828bfdfb-ffffffff828bff7d: efi_arch_mem_reserve (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void efi_arch_mem_reserve(phys_addr_t addr, u64 size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/platform/efi/quirks.c (ffffffff828c6279)
Location: arch/x86/platform/efi/quirks.c:244
Inline: False
Direct callers:
  - drivers/firmware/efi/efi.c:efi_mem_reserve
```
**Symbols:**

```
ffffffff828c6279-ffffffff828c641f: efi_arch_mem_reserve (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void efi_arch_mem_reserve(phys_addr_t addr, u64 size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/platform/efi/quirks.c (ffffffff82ce9313)
Location: arch/x86/platform/efi/quirks.c:245
Inline: False
Direct callers:
  - drivers/firmware/efi/efi.c:efi_mem_reserve
```
**Symbols:**

```
ffffffff82ce9313-ffffffff82ce94ad: efi_arch_mem_reserve (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void efi_arch_mem_reserve(phys_addr_t addr, u64 size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/platform/efi/quirks.c (ffffffff82fd6da1)
Location: arch/x86/platform/efi/quirks.c:245
Inline: False
Direct callers:
  - drivers/firmware/efi/efi.c:efi_mem_reserve
```
**Symbols:**

```
ffffffff82fd6da1-ffffffff82fd6f3b: efi_arch_mem_reserve (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void efi_arch_mem_reserve(phys_addr_t addr, u64 size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/platform/efi/quirks.c (ffffffff831e17dd)
Location: arch/x86/platform/efi/quirks.c:245
Inline: False
Direct callers:
  - drivers/firmware/efi/efi.c:efi_mem_reserve
```
**Symbols:**

```
ffffffff831e17dd-ffffffff831e1982: efi_arch_mem_reserve (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void efi_arch_mem_reserve(phys_addr_t addr, u64 size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/platform/efi/quirks.c (ffffffff832c50d0)
Location: arch/x86/platform/efi/quirks.c:245
Inline: False
Direct callers:
  - drivers/firmware/efi/efi.c:efi_mem_reserve
```
**Symbols:**

```
ffffffff832c50d0-ffffffff832c5290: efi_arch_mem_reserve (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void efi_arch_mem_reserve(phys_addr_t addr, u64 size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/platform/efi/quirks.c (ffffffff83477c5a)
Location: arch/x86/platform/efi/quirks.c:245
Inline: False
Direct callers:
  - drivers/firmware/efi/efi.c:efi_mem_reserve
```
**Symbols:**

```
ffffffff83477c5a-ffffffff83477e48: efi_arch_mem_reserve (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void efi_arch_mem_reserve(phys_addr_t addr, u64 size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/platform/efi/quirks.c (ffffffff83ea1960)
Location: arch/x86/platform/efi/quirks.c:245
Inline: False
Direct callers:
  - drivers/firmware/efi/efi.c:efi_mem_reserve
  - drivers/firmware/efi/efi.c:efi_mem_reserve
```
**Symbols:**

```
ffffffff83ea1960-ffffffff83ea1ba6: efi_arch_mem_reserve (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void efi_arch_mem_reserve(phys_addr_t addr, u64 size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/platform/efi/quirks.c (ffffffff836c5bc0)
Location: arch/x86/platform/efi/quirks.c:253
Inline: False
Direct callers:
  - drivers/firmware/efi/efi.c:efi_mem_reserve
  - drivers/firmware/efi/efi.c:efi_mem_reserve
```
**Symbols:**

```
ffffffff836c5bc0-ffffffff836c5e06: efi_arch_mem_reserve (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void efi_arch_mem_reserve(phys_addr_t addr, u64 size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/platform/efi/quirks.c (ffffffff838f67c0)
Location: arch/x86/platform/efi/quirks.c:253
Inline: False
Direct callers:
  - drivers/firmware/efi/efi.c:efi_mem_reserve
  - drivers/firmware/efi/efi.c:efi_mem_reserve
```
**Symbols:**

```
ffffffff838f67c0-ffffffff838f6a06: efi_arch_mem_reserve (STB_GLOBAL)
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
void efi_arch_mem_reserve(phys_addr_t addr, u64 size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/efi.c (ffff8000114a5afc)
Location: drivers/firmware/efi/efi.c:434
Inline: False
Direct callers:
  - drivers/firmware/efi/efi.c:efi_mem_reserve
```
**Symbols:**

```
ffff8000114a5afc-ffff8000114a5b14: efi_arch_mem_reserve (STB_WEAK)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void efi_arch_mem_reserve(phys_addr_t addr, u64 size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/firmware/efi/efi.c (c15a7d9c)
Location: drivers/firmware/efi/efi.c:434
Inline: False
Direct callers:
  - drivers/firmware/efi/efi.c:efi_mem_reserve
```
**Symbols:**

```
c15a7d9c-c15a7db4: efi_arch_mem_reserve (STB_WEAK)
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
void efi_arch_mem_reserve(phys_addr_t addr, u64 size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/platform/efi/quirks.c (ffffffff828b1211)
Location: arch/x86/platform/efi/quirks.c:244
Inline: False
Direct callers:
  - drivers/firmware/efi/efi.c:efi_mem_reserve
```
**Symbols:**

```
ffffffff828b1211-ffffffff828b13b7: efi_arch_mem_reserve (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void efi_arch_mem_reserve(phys_addr_t addr, u64 size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/platform/efi/quirks.c (ffffffff828a9396)
Location: arch/x86/platform/efi/quirks.c:244
Inline: False
Direct callers:
  - drivers/firmware/efi/efi.c:efi_mem_reserve
```
**Symbols:**

```
ffffffff828a9396-ffffffff828a953c: efi_arch_mem_reserve (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void efi_arch_mem_reserve(phys_addr_t addr, u64 size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/platform/efi/quirks.c (ffffffff828c4110)
Location: arch/x86/platform/efi/quirks.c:244
Inline: False
Direct callers:
  - drivers/firmware/efi/efi.c:efi_mem_reserve
```
**Symbols:**

```
ffffffff828c4110-ffffffff828c42b6: efi_arch_mem_reserve (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void efi_arch_mem_reserve(phys_addr_t addr, u64 size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/platform/efi/quirks.c (ffffffff828c72b6)
Location: arch/x86/platform/efi/quirks.c:244
Inline: False
Direct callers:
  - drivers/firmware/efi/efi.c:efi_mem_reserve
```
**Symbols:**

```
ffffffff828c72b6-ffffffff828c745c: efi_arch_mem_reserve (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
