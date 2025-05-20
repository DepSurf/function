# Function: <code>klp_apply_section_relocs</code>

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
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int klp_apply_section_relocs(struct module *pmod, Elf64_Shdr *sechdrs, const char *shstrtab, const char *strtab, unsigned int symndx, unsigned int secndx, const char *objname);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/livepatch/core.c (0)
Location: kernel/livepatch/core.c:288
Inline: False
Direct callers:
  - kernel/livepatch/core.c:klp_init_object_loaded
  - kernel/module.c:apply_relocations
```
**Symbols:**

```
ffffffff8113b41b-ffffffff8113b438: klp_apply_section_relocs.cold (STB_LOCAL)
ffffffff8113a730-ffffffff8113a817: klp_apply_section_relocs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int klp_apply_section_relocs(struct module *pmod, Elf64_Shdr *sechdrs, const char *shstrtab, const char *strtab, unsigned int symndx, unsigned int secndx, const char *objname);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/livepatch/core.c (0)
Location: kernel/livepatch/core.c:288
Inline: False
Direct callers:
  - kernel/livepatch/core.c:klp_init_object_loaded
  - kernel/module.c:apply_relocations
```
**Symbols:**

```
ffffffff81be312a-ffffffff81be3147: klp_apply_section_relocs.cold (STB_LOCAL)
ffffffff81135220-ffffffff81135307: klp_apply_section_relocs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int klp_apply_section_relocs(struct module *pmod, Elf64_Shdr *sechdrs, const char *shstrtab, const char *strtab, unsigned int symndx, unsigned int secndx, const char *objname);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/livepatch/core.c (0)
Location: kernel/livepatch/core.c:287
Inline: False
Direct callers:
  - kernel/livepatch/core.c:klp_init_object_loaded
  - kernel/module.c:load_module
```
**Symbols:**

```
ffffffff81bd4ecb-ffffffff81bd4ee9: klp_apply_section_relocs.cold (STB_LOCAL)
ffffffff81136100-ffffffff811361e7: klp_apply_section_relocs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int klp_apply_section_relocs(struct module *pmod, Elf64_Shdr *sechdrs, const char *shstrtab, const char *strtab, unsigned int symndx, unsigned int secndx, const char *objname);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/livepatch/core.c (0)
Location: kernel/livepatch/core.c:287
Inline: False
Direct callers:
  - kernel/livepatch/core.c:klp_init_object_loaded
  - kernel/module.c:load_module
```
**Symbols:**

```
ffffffff81cafa2e-ffffffff81cafa4c: klp_apply_section_relocs.cold (STB_LOCAL)
ffffffff81158cb0-ffffffff81158d97: klp_apply_section_relocs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int klp_apply_section_relocs(struct module *pmod, Elf64_Shdr *sechdrs, const char *shstrtab, const char *strtab, unsigned int symndx, unsigned int secndx, const char *objname);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/livepatch/core.c (0)
Location: kernel/livepatch/core.c:287
Inline: False
Direct callers:
  - kernel/livepatch/core.c:klp_init_object_loaded
  - kernel/module/main.c:load_module
```
**Symbols:**

```
ffffffff81e606c9-ffffffff81e606e5: klp_apply_section_relocs.cold (STB_LOCAL)
ffffffff811821d0-ffffffff811822d2: klp_apply_section_relocs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int klp_apply_section_relocs(struct module *pmod, Elf64_Shdr *sechdrs, const char *shstrtab, const char *strtab, unsigned int symndx, unsigned int secndx, const char *objname);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/livepatch/core.c (ffffffff811bce30)
Location: kernel/livepatch/core.c:294
Inline: False
Direct callers:
  - kernel/livepatch/core.c:klp_init_object_loaded
  - kernel/module/main.c:load_module
```
**Symbols:**

```
ffffffff811bce30-ffffffff811bcf4b: klp_apply_section_relocs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int klp_apply_section_relocs(struct module *pmod, Elf64_Shdr *sechdrs, const char *shstrtab, const char *strtab, unsigned int symndx, unsigned int secndx, const char *objname);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/livepatch/core.c (ffffffff811d01c0)
Location: kernel/livepatch/core.c:332
Inline: False
Direct callers:
  - kernel/module/main.c:load_module
```
**Symbols:**

```
ffffffff811d01c0-ffffffff811d01e7: klp_apply_section_relocs (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int klp_apply_section_relocs(struct module *pmod, Elf64_Shdr *sechdrs, const char *shstrtab, const char *strtab, unsigned int symndx, unsigned int secndx, const char *objname);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/livepatch/core.c (ffffffff811e4e10)
Location: kernel/livepatch/core.c:332
Inline: False
Direct callers:
  - kernel/module/main.c:load_module
```
**Symbols:**

```
ffffffff811e4e10-ffffffff811e4e37: klp_apply_section_relocs (STB_GLOBAL)
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
