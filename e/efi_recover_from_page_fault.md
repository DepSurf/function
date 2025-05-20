# Function: <code>efi_recover_from_page_fault</code>

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
In <code>4.10</code>: Absent ⚠️
</li>
<li>
In <code>4.13</code>: Absent ⚠️
</li>
<li>
In <code>4.15</code>: Absent ⚠️
</li>
<li>
In <code>4.18</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
void efi_recover_from_page_fault(long unsigned int phys_addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/platform/efi/quirks.c (0)
Location: arch/x86/platform/efi/quirks.c:710
Inline: False
Direct callers:
  - arch/x86/mm/fault.c:no_context
```
**Symbols:**

```
ffffffff8108d1de-ffffffff8108d1f1: efi_recover_from_page_fault.cold.3 (STB_LOCAL)
ffffffff8108d110-ffffffff8108d1de: efi_recover_from_page_fault (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void efi_recover_from_page_fault(long unsigned int phys_addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/platform/efi/quirks.c (0)
Location: arch/x86/platform/efi/quirks.c:714
Inline: False
Direct callers:
  - arch/x86/mm/fault.c:no_context
```
**Symbols:**

```
ffffffff8109109c-ffffffff810910af: efi_recover_from_page_fault.cold (STB_LOCAL)
ffffffff81090fd0-ffffffff8109109c: efi_recover_from_page_fault (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
void efi_recover_from_page_fault(long unsigned int phys_addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/platform/efi/quirks.c (0)
Location: arch/x86/platform/efi/quirks.c:712
Inline: False
Direct callers:
  - arch/x86/mm/fault.c:no_context
```
**Symbols:**

```
ffffffff81091d9c-ffffffff81091daf: efi_recover_from_page_fault.cold (STB_LOCAL)
ffffffff81091cd0-ffffffff81091d9c: efi_recover_from_page_fault (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
void efi_recover_from_page_fault(long unsigned int phys_addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/platform/efi/quirks.c (0)
Location: arch/x86/platform/efi/quirks.c:719
Inline: False
Direct callers:
  - arch/x86/mm/fault.c:no_context
```
**Symbols:**

```
ffffffff8109764c-ffffffff8109765f: efi_recover_from_page_fault.cold (STB_LOCAL)
ffffffff81097580-ffffffff8109764c: efi_recover_from_page_fault (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
void efi_recover_from_page_fault(long unsigned int phys_addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/platform/efi/quirks.c (0)
Location: arch/x86/platform/efi/quirks.c:690
Inline: False
Direct callers:
  - arch/x86/mm/fault.c:no_context
```
**Symbols:**

```
ffffffff81bda35f-ffffffff81bda372: efi_recover_from_page_fault.cold (STB_LOCAL)
ffffffff810967d0-ffffffff8109688c: efi_recover_from_page_fault (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
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
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
void efi_recover_from_page_fault(long unsigned int phys_addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/platform/efi/quirks.c (0)
Location: arch/x86/platform/efi/quirks.c:712
Inline: False
Direct callers:
  - arch/x86/mm/fault.c:no_context
```
**Symbols:**

```
ffffffff81090d5c-ffffffff81090d6f: efi_recover_from_page_fault.cold (STB_LOCAL)
ffffffff81090c90-ffffffff81090d5c: efi_recover_from_page_fault (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
void efi_recover_from_page_fault(long unsigned int phys_addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/platform/efi/quirks.c (0)
Location: arch/x86/platform/efi/quirks.c:712
Inline: False
Direct callers:
  - arch/x86/mm/fault.c:no_context
```
**Symbols:**

```
ffffffff8107f86c-ffffffff8107f87f: efi_recover_from_page_fault.cold (STB_LOCAL)
ffffffff8107f7a0-ffffffff8107f86c: efi_recover_from_page_fault (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
void efi_recover_from_page_fault(long unsigned int phys_addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/platform/efi/quirks.c (0)
Location: arch/x86/platform/efi/quirks.c:712
Inline: False
Direct callers:
  - arch/x86/mm/fault.c:no_context
```
**Symbols:**

```
ffffffff81090d0c-ffffffff81090d1f: efi_recover_from_page_fault.cold (STB_LOCAL)
ffffffff81090c40-ffffffff81090d0c: efi_recover_from_page_fault (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
void efi_recover_from_page_fault(long unsigned int phys_addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/platform/efi/quirks.c (0)
Location: arch/x86/platform/efi/quirks.c:712
Inline: False
Direct callers:
  - arch/x86/mm/fault.c:no_context
```
**Symbols:**

```
ffffffff810930fc-ffffffff8109310f: efi_recover_from_page_fault.cold (STB_LOCAL)
ffffffff81093020-ffffffff810930fc: efi_recover_from_page_fault (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
