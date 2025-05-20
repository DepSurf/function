# Function: <code>find_section</code>

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
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void *find_section(Elf32_Ehdr *ehdr, const char *name, long unsigned int *size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/arm/kernel/vdso.c (c1506bc0)
Location: arch/arm/kernel/vdso.c:111
Inline: False
Direct callers:
  - arch/arm/kernel/vdso.c:vdso_init
  - arch/arm/kernel/vdso.c:vdso_init
```
**Symbols:**

```
c1506bc0-c1506c7c: find_section (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
const Elf64_Shdr *find_section(const Elf64_Ehdr *hdr, const Elf64_Shdr *sechdrs, const char *name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/powerpc/kernel/module.c (c00000000004e030)
Location: arch/powerpc/kernel/module.c:20
Inline: False
Direct callers:
  - arch/powerpc/kernel/module.c:module_finalize
  - arch/powerpc/kernel/module.c:module_finalize
  - arch/powerpc/kernel/module.c:module_finalize
  - arch/powerpc/kernel/module.c:module_finalize
  - arch/powerpc/kernel/module.c:module_finalize
```
**Symbols:**

```
c00000000004e030-c00000000004e2c0: find_section (STB_LOCAL)
```
</details>
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
<b>Arch</b>
<ul>
</ul>
