# Function: <code>e820_all_mapped</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int e820_all_mapped(u64 start, u64 end, unsigned int type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/e820.c (ffffffff81f67a2d)
Location: arch/x86/kernel/e820.c:80
Inline: False
Direct callers:
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/platform/efi/quirks.c:efi_reserve_boot_services
```
**Symbols:**

```
ffffffff81f67a2d-ffffffff81f67a8d: e820_all_mapped (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int e820_all_mapped(u64 start, u64 end, unsigned int type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/e820.c (ffffffff81f8f8d3)
Location: arch/x86/kernel/e820.c:80
Inline: False
Direct callers:
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/platform/efi/quirks.c:efi_reserve_boot_services
```
**Symbols:**

```
ffffffff81f8f8d3-ffffffff81f8f935: e820_all_mapped (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int e820_all_mapped(u64 start, u64 end, unsigned int type);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/e820.c (ffffffff81fcacaa)
Location: arch/x86/kernel/e820.c:82
Inline: False
Direct callers:
  - arch/x86/kernel/setup.c:setup_arch
  - arch/x86/platform/efi/quirks.c:efi_reserve_boot_services
```
**Symbols:**

```
ffffffff81fcacaa-ffffffff81fcad08: e820_all_mapped (STB_GLOBAL)
```
</details>
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
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
</ul>
