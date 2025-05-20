# Function: <code>apply_relocate_add</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int apply_relocate_add(Elf64_Shdr *sechdrs, const char *strtab, unsigned int symindex, unsigned int relsec, struct module *me);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/module.c (ffffffff81060a60)
Location: arch/x86/kernel/module.c:139
Inline: False
Direct callers:
  - kernel/module.c:load_module
```
**Symbols:**

```
ffffffff81060a60-ffffffff81060b71: apply_relocate_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int apply_relocate_add(Elf64_Shdr *sechdrs, const char *strtab, unsigned int symindex, unsigned int relsec, struct module *me);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/module.c (ffffffff81060870)
Location: arch/x86/kernel/module.c:140
Inline: False
Direct callers:
  - kernel/livepatch/core.c:klp_write_object_relocations
  - kernel/module.c:load_module
```
**Symbols:**

```
ffffffff81060870-ffffffff81060995: apply_relocate_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int apply_relocate_add(Elf64_Shdr *sechdrs, const char *strtab, unsigned int symindex, unsigned int relsec, struct module *me);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/module.c (ffffffff81063910)
Location: arch/x86/kernel/module.c:140
Inline: False
Direct callers:
  - kernel/module.c:load_module
```
**Symbols:**

```
ffffffff81063910-ffffffff81063a35: apply_relocate_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int apply_relocate_add(Elf64_Shdr *sechdrs, const char *strtab, unsigned int symindex, unsigned int relsec, struct module *me);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/module.c (ffffffff81062870)
Location: arch/x86/kernel/module.c:140
Inline: False
Direct callers:
  - kernel/module.c:load_module
```
**Symbols:**

```
ffffffff81062870-ffffffff81062996: apply_relocate_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int apply_relocate_add(Elf64_Shdr *sechdrs, const char *strtab, unsigned int symindex, unsigned int relsec, struct module *me);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/module.c (ffffffff810669b0)
Location: arch/x86/kernel/module.c:141
Inline: False
Direct callers:
  - kernel/module.c:load_module
```
**Symbols:**

```
ffffffff810669b0-ffffffff81066b29: apply_relocate_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
int apply_relocate_add(Elf64_Shdr *sechdrs, const char *strtab, unsigned int symindex, unsigned int relsec, struct module *me);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/module.c (0)
Location: arch/x86/kernel/module.c:141
Inline: False
Direct callers:
  - kernel/module.c:load_module
```
**Symbols:**

```
ffffffff810697e0-ffffffff8106984b: apply_relocate_add.cold.2 (STB_LOCAL)
ffffffff81069560-ffffffff8106967d: apply_relocate_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
int apply_relocate_add(Elf64_Shdr *sechdrs, const char *strtab, unsigned int symindex, unsigned int relsec, struct module *me);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/module.c (0)
Location: arch/x86/kernel/module.c:141
Inline: False
Direct callers:
  - kernel/module.c:load_module
```
**Symbols:**

```
ffffffff8106f590-ffffffff8106f5e1: apply_relocate_add.cold.2 (STB_LOCAL)
ffffffff8106f2b0-ffffffff8106f426: apply_relocate_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int apply_relocate_add(Elf64_Shdr *sechdrs, const char *strtab, unsigned int symindex, unsigned int relsec, struct module *me);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/module.c (0)
Location: arch/x86/kernel/module.c:129
Inline: False
Direct callers:
  - kernel/module.c:load_module
```
**Symbols:**

```
ffffffff81073670-ffffffff810736de: apply_relocate_add.cold (STB_LOCAL)
ffffffff810733a0-ffffffff81073510: apply_relocate_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int apply_relocate_add(Elf64_Shdr *sechdrs, const char *strtab, unsigned int symindex, unsigned int relsec, struct module *me);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/module.c (0)
Location: arch/x86/kernel/module.c:129
Inline: False
Direct callers:
  - kernel/module.c:load_module
```
**Symbols:**

```
ffffffff81074630-ffffffff8107469e: apply_relocate_add.cold (STB_LOCAL)
ffffffff81074360-ffffffff810744d0: apply_relocate_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int apply_relocate_add(Elf64_Shdr *sechdrs, const char *strtab, unsigned int symindex, unsigned int relsec, struct module *me);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/module.c (ffffffff8107b680)
Location: arch/x86/kernel/module.c:220
Inline: False
Direct callers:
  - kernel/livepatch/core.c:klp_apply_section_relocs
  - kernel/module.c:apply_relocations
```
**Symbols:**

```
ffffffff8107b680-ffffffff8107b70d: apply_relocate_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int apply_relocate_add(Elf64_Shdr *sechdrs, const char *strtab, unsigned int symindex, unsigned int relsec, struct module *me);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/module.c (ffffffff8107b5e0)
Location: arch/x86/kernel/module.c:221
Inline: False
Direct callers:
  - kernel/livepatch/core.c:klp_apply_section_relocs
  - kernel/module.c:apply_relocations
```
**Symbols:**

```
ffffffff8107b5e0-ffffffff8107b66d: apply_relocate_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int apply_relocate_add(Elf64_Shdr *sechdrs, const char *strtab, unsigned int symindex, unsigned int relsec, struct module *me);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/module.c (ffffffff8107c800)
Location: arch/x86/kernel/module.c:221
Inline: False
Direct callers:
  - kernel/livepatch/core.c:klp_apply_section_relocs
  - kernel/module.c:load_module
```
**Symbols:**

```
ffffffff8107c800-ffffffff8107c88d: apply_relocate_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int apply_relocate_add(Elf64_Shdr *sechdrs, const char *strtab, unsigned int symindex, unsigned int relsec, struct module *me);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/module.c (ffffffff8108a920)
Location: arch/x86/kernel/module.c:222
Inline: False
Direct callers:
  - kernel/livepatch/core.c:klp_apply_section_relocs
  - kernel/module.c:load_module
```
**Symbols:**

```
ffffffff8108a920-ffffffff8108a9ad: apply_relocate_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int apply_relocate_add(Elf64_Shdr *sechdrs, const char *strtab, unsigned int symindex, unsigned int relsec, struct module *me);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/module.c (ffffffff8109aed0)
Location: arch/x86/kernel/module.c:222
Inline: False
Direct callers:
  - kernel/livepatch/core.c:klp_apply_section_relocs
  - kernel/module/main.c:load_module
```
**Symbols:**

```
ffffffff8109aed0-ffffffff8109af74: apply_relocate_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int apply_relocate_add(Elf64_Shdr *sechdrs, const char *strtab, unsigned int symindex, unsigned int relsec, struct module *me);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/module.c (ffffffff810b1980)
Location: arch/x86/kernel/module.c:223
Inline: False
Direct callers:
  - kernel/livepatch/core.c:klp_apply_section_relocs
  - kernel/module/main.c:load_module
```
**Symbols:**

```
ffffffff810b1980-ffffffff810b1a24: apply_relocate_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int apply_relocate_add(Elf64_Shdr *sechdrs, const char *strtab, unsigned int symindex, unsigned int relsec, struct module *me);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/module.c (ffffffff810b49c0)
Location: arch/x86/kernel/module.c:252
Inline: False
Direct callers:
  - kernel/livepatch/core.c:klp_write_section_relocs
  - kernel/module/main.c:load_module
```
**Symbols:**

```
ffffffff810b49c0-ffffffff810b4a76: apply_relocate_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int apply_relocate_add(Elf64_Shdr *sechdrs, const char *strtab, unsigned int symindex, unsigned int relsec, struct module *me);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/module.c (ffffffff810bbe20)
Location: arch/x86/kernel/module.c:252
Inline: False
Direct callers:
  - kernel/livepatch/core.c:klp_write_section_relocs
  - kernel/module/main.c:load_module
```
**Symbols:**

```
ffffffff810bbe20-ffffffff810bbed6: apply_relocate_add (STB_GLOBAL)
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
int apply_relocate_add(Elf64_Shdr *sechdrs, const char *strtab, unsigned int symindex, unsigned int relsec, struct module *me);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/arm64/kernel/module.c (ffff8000100a20d0)
Location: arch/arm64/kernel/module.c:255
Inline: False
Direct callers:
  - kernel/module.c:load_module
```
**Symbols:**

```
ffff8000100a20d0-ffff8000100a281c: apply_relocate_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/module.c (c040beac)
Location: include/linux/moduleloader.h:71
Inline: True
Inline callers:
  - kernel/module.c:load_module
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int apply_relocate_add(Elf64_Shdr *sechdrs, const char *strtab, unsigned int symindex, unsigned int relsec, struct module *me);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/powerpc/kernel/module_64.c (c00000000004f360)
Location: arch/powerpc/kernel/module_64.c:522
Inline: False
Direct callers:
  - kernel/module.c:load_module
```
**Symbols:**

```
c00000000004f360-c0000000000500b4: apply_relocate_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int apply_relocate_add(Elf64_Shdr *sechdrs, const char *strtab, unsigned int symindex, unsigned int relsec, struct module *me);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/riscv/kernel/module.c (ffffffe0000b8718)
Location: arch/riscv/kernel/module.c:296
Inline: False
Direct callers:
  - kernel/module.c:load_module
```
**Symbols:**

```
ffffffe0000b8718-ffffffe0000b8992: apply_relocate_add (STB_GLOBAL)
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
int apply_relocate_add(Elf64_Shdr *sechdrs, const char *strtab, unsigned int symindex, unsigned int relsec, struct module *me);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/module.c (0)
Location: arch/x86/kernel/module.c:129
Inline: False
Direct callers:
  - kernel/module.c:load_module
```
**Symbols:**

```
ffffffff81073630-ffffffff8107369e: apply_relocate_add.cold (STB_LOCAL)
ffffffff81073360-ffffffff810734d0: apply_relocate_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int apply_relocate_add(Elf64_Shdr *sechdrs, const char *strtab, unsigned int symindex, unsigned int relsec, struct module *me);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/module.c (0)
Location: arch/x86/kernel/module.c:129
Inline: False
Direct callers:
  - kernel/module.c:load_module
```
**Symbols:**

```
ffffffff810636b0-ffffffff8106371e: apply_relocate_add.cold (STB_LOCAL)
ffffffff810633e0-ffffffff81063550: apply_relocate_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int apply_relocate_add(Elf64_Shdr *sechdrs, const char *strtab, unsigned int symindex, unsigned int relsec, struct module *me);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/module.c (0)
Location: arch/x86/kernel/module.c:129
Inline: False
Direct callers:
  - kernel/module.c:load_module
```
**Symbols:**

```
ffffffff810735e0-ffffffff8107364e: apply_relocate_add.cold (STB_LOCAL)
ffffffff81073310-ffffffff81073480: apply_relocate_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int apply_relocate_add(Elf64_Shdr *sechdrs, const char *strtab, unsigned int symindex, unsigned int relsec, struct module *me);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/module.c (0)
Location: arch/x86/kernel/module.c:129
Inline: False
Direct callers:
  - kernel/module.c:load_module
```
**Symbols:**

```
ffffffff81075640-ffffffff810756ae: apply_relocate_add.cold (STB_LOCAL)
ffffffff81075370-ffffffff810754e0: apply_relocate_add (STB_GLOBAL)
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
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
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
