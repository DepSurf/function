# Function: <code>efi_crash_gracefully_on_page_fault</code>

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
In <code>5.0</code>: Absent ⚠️
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
void efi_crash_gracefully_on_page_fault(long unsigned int phys_addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/platform/efi/quirks.c (0)
Location: arch/x86/platform/efi/quirks.c:702
Inline: False
Direct callers:
  - arch/x86/mm/fault.c:page_fault_oops
```
**Symbols:**

```
ffffffff81bcc487-ffffffff81bcc49a: efi_crash_gracefully_on_page_fault.cold (STB_LOCAL)
ffffffff810970d0-ffffffff810971ae: efi_crash_gracefully_on_page_fault (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void efi_crash_gracefully_on_page_fault(long unsigned int phys_addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/platform/efi/quirks.c (0)
Location: arch/x86/platform/efi/quirks.c:703
Inline: False
Direct callers:
  - arch/x86/mm/fault.c:page_fault_oops
```
**Symbols:**

```
ffffffff81ca25da-ffffffff81ca25ed: efi_crash_gracefully_on_page_fault.cold (STB_LOCAL)
ffffffff810a7040-ffffffff810a710b: efi_crash_gracefully_on_page_fault (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void efi_crash_gracefully_on_page_fault(long unsigned int phys_addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/platform/efi/quirks.c (0)
Location: arch/x86/platform/efi/quirks.c:703
Inline: False
Direct callers:
  - arch/x86/mm/fault.c:page_fault_oops
```
**Symbols:**

```
ffffffff81e51e35-ffffffff81e51e48: efi_crash_gracefully_on_page_fault.cold (STB_LOCAL)
ffffffff810bc380-ffffffff810bc472: efi_crash_gracefully_on_page_fault (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void efi_crash_gracefully_on_page_fault(long unsigned int phys_addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/platform/efi/quirks.c (ffffffff810d77d0)
Location: arch/x86/platform/efi/quirks.c:703
Inline: False
Direct callers:
  - arch/x86/mm/fault.c:page_fault_oops
```
**Symbols:**

```
ffffffff810d77d0-ffffffff810d78dd: efi_crash_gracefully_on_page_fault (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void efi_crash_gracefully_on_page_fault(long unsigned int phys_addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/platform/efi/quirks.c (ffffffff810e2d60)
Location: arch/x86/platform/efi/quirks.c:711
Inline: False
Direct callers:
  - arch/x86/mm/fault.c:page_fault_oops
```
**Symbols:**

```
ffffffff810e2d60-ffffffff810e2e6d: efi_crash_gracefully_on_page_fault (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void efi_crash_gracefully_on_page_fault(long unsigned int phys_addr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/platform/efi/quirks.c (ffffffff810eb5e0)
Location: arch/x86/platform/efi/quirks.c:711
Inline: False
Direct callers:
  - arch/x86/mm/fault.c:page_fault_oops
```
**Symbols:**

```
ffffffff810eb5e0-ffffffff810eb6b1: efi_crash_gracefully_on_page_fault (STB_GLOBAL)
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
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
