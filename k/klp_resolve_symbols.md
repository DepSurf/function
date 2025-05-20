# Function: <code>klp_resolve_symbols</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/livepatch/core.c (ffffffff810ef4b0)
Location: kernel/livepatch/core.c:209
Inline: True
Direct callers:
  - kernel/livepatch/core.c:klp_write_object_relocations
```
**Symbols:**

```
ffffffff810ef4b0-ffffffff810ef63e: klp_resolve_symbols.isra.12 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/livepatch/core.c (ffffffff810f6620)
Location: kernel/livepatch/core.c:209
Inline: True
```
**Symbols:**

```
ffffffff810f6620-ffffffff810f67ae: klp_resolve_symbols.isra.14 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/livepatch/core.c (ffffffff810f7c80)
Location: kernel/livepatch/core.c:181
Inline: True
```
**Symbols:**

```
ffffffff810f7c80-ffffffff810f7e0e: klp_resolve_symbols.isra.12 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/livepatch/core.c (ffffffff81101f30)
Location: kernel/livepatch/core.c:176
Inline: True
```
**Symbols:**

```
ffffffff81101f30-ffffffff811020be: klp_resolve_symbols.isra.12 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/livepatch/core.c (0)
Location: kernel/livepatch/core.c:176
Inline: True
```
**Symbols:**

```
ffffffff8110a330-ffffffff8110a496: klp_resolve_symbols.isra.15 (STB_LOCAL)
ffffffff8110ad39-ffffffff8110ad77: klp_resolve_symbols.isra.15.cold.20 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/livepatch/core.c (0)
Location: kernel/livepatch/core.c:176
Inline: True
```
**Symbols:**

```
ffffffff81115b00-ffffffff81115c66: klp_resolve_symbols.isra.15 (STB_LOCAL)
ffffffff81116529-ffffffff81116567: klp_resolve_symbols.isra.15.cold.20 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/livepatch/core.c (0)
Location: kernel/livepatch/core.c:193
Inline: True
```
**Symbols:**

```
ffffffff8111f700-ffffffff8111f83c: klp_resolve_symbols.isra.0 (STB_LOCAL)
ffffffff81120533-ffffffff8112056b: klp_resolve_symbols.isra.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/livepatch/core.c (0)
Location: kernel/livepatch/core.c:193
Inline: True
```
**Symbols:**

```
ffffffff8112be50-ffffffff8112bf8c: klp_resolve_symbols.isra.0 (STB_LOCAL)
ffffffff8112cc3c-ffffffff8112cc74: klp_resolve_symbols.isra.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int klp_resolve_symbols(Elf64_Shdr *sechdrs, const char *strtab, unsigned int symndx, Elf64_Shdr *relasec, const char *sec_objname);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/livepatch/core.c (0)
Location: kernel/livepatch/core.c:194
Inline: False
Direct callers:
  - kernel/livepatch/core.c:klp_apply_section_relocs
```
**Symbols:**

```
ffffffff81139d30-ffffffff81139eb8: klp_resolve_symbols (STB_LOCAL)
ffffffff8113b248-ffffffff8113b29d: klp_resolve_symbols.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int klp_resolve_symbols(Elf64_Shdr *sechdrs, const char *strtab, unsigned int symndx, Elf64_Shdr *relasec, const char *sec_objname);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/livepatch/core.c (0)
Location: kernel/livepatch/core.c:194
Inline: False
Direct callers:
  - kernel/livepatch/core.c:klp_apply_section_relocs
```
**Symbols:**

```
ffffffff81134820-ffffffff811349a8: klp_resolve_symbols (STB_LOCAL)
ffffffff81be2f57-ffffffff81be2fac: klp_resolve_symbols.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int klp_resolve_symbols(Elf64_Shdr *sechdrs, const char *strtab, unsigned int symndx, Elf64_Shdr *relasec, const char *sec_objname);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/livepatch/core.c (0)
Location: kernel/livepatch/core.c:193
Inline: False
Direct callers:
  - kernel/livepatch/core.c:klp_apply_section_relocs
```
**Symbols:**

```
ffffffff81135700-ffffffff8113587e: klp_resolve_symbols (STB_LOCAL)
ffffffff81bd4dfd-ffffffff81bd4e55: klp_resolve_symbols.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int klp_resolve_symbols(Elf64_Shdr *sechdrs, const char *strtab, unsigned int symndx, Elf64_Shdr *relasec, const char *sec_objname);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/livepatch/core.c (0)
Location: kernel/livepatch/core.c:193
Inline: False
Direct callers:
  - kernel/livepatch/core.c:klp_apply_section_relocs
```
**Symbols:**

```
ffffffff811581e0-ffffffff8115835e: klp_resolve_symbols (STB_LOCAL)
ffffffff81caf7ea-ffffffff81caf842: klp_resolve_symbols.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int klp_resolve_symbols(Elf64_Shdr *sechdrs, const char *strtab, unsigned int symndx, Elf64_Shdr *relasec, const char *sec_objname);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/livepatch/core.c (0)
Location: kernel/livepatch/core.c:193
Inline: False
Direct callers:
  - kernel/livepatch/core.c:klp_apply_section_relocs
```
**Symbols:**

```
ffffffff81181660-ffffffff81181816: klp_resolve_symbols (STB_LOCAL)
ffffffff81e60494-ffffffff81e604dc: klp_resolve_symbols.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int klp_resolve_symbols(Elf64_Shdr *sechdrs, const char *strtab, unsigned int symndx, Elf64_Shdr *relasec, const char *sec_objname);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/livepatch/core.c (ffffffff811bbfb0)
Location: kernel/livepatch/core.c:200
Inline: False
Direct callers:
  - kernel/livepatch/core.c:klp_apply_section_relocs
```
**Symbols:**

```
ffffffff811bbfb0-ffffffff811bc1a7: klp_resolve_symbols (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int klp_resolve_symbols(Elf64_Shdr *sechdrs, const char *strtab, unsigned int symndx, Elf64_Shdr *relasec, const char *sec_objname);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/livepatch/core.c (ffffffff811ce950)
Location: kernel/livepatch/core.c:192
Inline: False
Direct callers:
  - kernel/livepatch/core.c:klp_write_section_relocs
```
**Symbols:**

```
ffffffff811ce950-ffffffff811ceb47: klp_resolve_symbols (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int klp_resolve_symbols(Elf64_Shdr *sechdrs, const char *strtab, unsigned int symndx, Elf64_Shdr *relasec, const char *sec_objname);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/livepatch/core.c (ffffffff811e3530)
Location: kernel/livepatch/core.c:192
Inline: False
Direct callers:
  - kernel/livepatch/core.c:klp_write_section_relocs
```
**Symbols:**

```
ffffffff811e3530-ffffffff811e3727: klp_resolve_symbols (STB_LOCAL)
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
<details>
<summary>In <code>ppc64el</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/livepatch/core.c (c0000000001efbb0)
Location: kernel/livepatch/core.c:193
Inline: True
```
**Symbols:**

```
c0000000001efbb0-c0000000001efe18: klp_resolve_symbols.isra.0 (STB_LOCAL)
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
<details>
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/livepatch/core.c (0)
Location: kernel/livepatch/core.c:193
Inline: True
```
**Symbols:**

```
ffffffff81124430-ffffffff8112456c: klp_resolve_symbols.isra.0 (STB_LOCAL)
ffffffff8112521c-ffffffff81125254: klp_resolve_symbols.isra.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/livepatch/core.c (0)
Location: kernel/livepatch/core.c:193
Inline: True
```
**Symbols:**

```
ffffffff81116e90-ffffffff81116fcc: klp_resolve_symbols.isra.0 (STB_LOCAL)
ffffffff81117c7c-ffffffff81117cb4: klp_resolve_symbols.isra.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/livepatch/core.c (0)
Location: kernel/livepatch/core.c:193
Inline: True
```
**Symbols:**

```
ffffffff81122320-ffffffff8112245c: klp_resolve_symbols.isra.0 (STB_LOCAL)
ffffffff8112310c-ffffffff81123144: klp_resolve_symbols.isra.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/livepatch/core.c (0)
Location: kernel/livepatch/core.c:193
Inline: True
```
**Symbols:**

```
ffffffff8112e930-ffffffff8112ea6c: klp_resolve_symbols.isra.0 (STB_LOCAL)
ffffffff8112f71c-ffffffff8112f754: klp_resolve_symbols.isra.0.cold (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
