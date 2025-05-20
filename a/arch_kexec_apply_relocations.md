# Function: <code>arch_kexec_apply_relocations</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int arch_kexec_apply_relocations(const Elf64_Ehdr *ehdr, Elf64_Shdr *sechdrs, unsigned int relsec);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kexec_file.c (ffffffff8110e820)
Location: kernel/kexec_file.c:129
Inline: False
Direct callers:
  - kernel/kexec_file.c:kexec_load_purgatory
```
**Symbols:**

```
ffffffff8110e820-ffffffff8110e83c: arch_kexec_apply_relocations (STB_WEAK)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int arch_kexec_apply_relocations(const Elf64_Ehdr *ehdr, Elf64_Shdr *sechdrs, unsigned int relsec);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kexec_file.c (ffffffff81115ec0)
Location: kernel/kexec_file.c:73
Inline: False
Direct callers:
  - kernel/kexec_file.c:kexec_load_purgatory
```
**Symbols:**

```
ffffffff81115ec0-ffffffff81115edc: arch_kexec_apply_relocations (STB_WEAK)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int arch_kexec_apply_relocations(const Elf64_Ehdr *ehdr, Elf64_Shdr *sechdrs, unsigned int relsec);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kexec_file.c (ffffffff8111d5e0)
Location: kernel/kexec_file.c:74
Inline: False
Direct callers:
  - kernel/kexec_file.c:kexec_load_purgatory
```
**Symbols:**

```
ffffffff8111d5e0-ffffffff8111d5fc: arch_kexec_apply_relocations (STB_WEAK)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int arch_kexec_apply_relocations(const Elf64_Ehdr *ehdr, Elf64_Shdr *sechdrs, unsigned int relsec);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kexec_file.c (ffffffff8111f1e0)
Location: kernel/kexec_file.c:67
Inline: False
Direct callers:
  - kernel/kexec_file.c:kexec_load_purgatory
```
**Symbols:**

```
ffffffff8111f1e0-ffffffff8111f1fc: arch_kexec_apply_relocations (STB_WEAK)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int arch_kexec_apply_relocations(const Elf64_Ehdr *ehdr, Elf64_Shdr *sechdrs, unsigned int relsec);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kexec_file.c (ffffffff8112a980)
Location: kernel/kexec_file.c:67
Inline: False
Direct callers:
  - kernel/kexec_file.c:kexec_load_purgatory
```
**Symbols:**

```
ffffffff8112a980-ffffffff8112a99c: arch_kexec_apply_relocations (STB_WEAK)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int arch_kexec_apply_relocations(struct purgatory_info *pi, Elf64_Shdr *section, const Elf64_Shdr *relsec, const Elf64_Shdr *symtab);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kexec_file.c (ffffffff8113a2a8)
Location: kernel/kexec_file.c:140
Inline: False
Direct callers:
  - kernel/kexec_file.c:kexec_load_purgatory
```
**Symbols:**

```
ffffffff8113a2a8-ffffffff8113a2c4: arch_kexec_apply_relocations (STB_WEAK)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int arch_kexec_apply_relocations(struct purgatory_info *pi, Elf64_Shdr *section, const Elf64_Shdr *relsec, const Elf64_Shdr *symtab);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kexec_file.c (ffffffff81145b78)
Location: kernel/kexec_file.c:139
Inline: False
Direct callers:
  - kernel/kexec_file.c:kexec_load_purgatory
```
**Symbols:**

```
ffffffff81145b78-ffffffff81145b94: arch_kexec_apply_relocations (STB_WEAK)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int arch_kexec_apply_relocations(struct purgatory_info *pi, Elf64_Shdr *section, const Elf64_Shdr *relsec, const Elf64_Shdr *symtab);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kexec_file.c (ffffffff81150f0a)
Location: kernel/kexec_file.c:137
Inline: False
Direct callers:
  - kernel/kexec_file.c:kexec_load_purgatory
```
**Symbols:**

```
ffffffff81150f0a-ffffffff81150f26: arch_kexec_apply_relocations (STB_WEAK)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int arch_kexec_apply_relocations(struct purgatory_info *pi, Elf64_Shdr *section, const Elf64_Shdr *relsec, const Elf64_Shdr *symtab);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kexec_file.c (ffffffff8115cb9a)
Location: kernel/kexec_file.c:137
Inline: False
Direct callers:
  - kernel/kexec_file.c:kexec_load_purgatory
```
**Symbols:**

```
ffffffff8115cb9a-ffffffff8115cbb6: arch_kexec_apply_relocations (STB_WEAK)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int arch_kexec_apply_relocations(struct purgatory_info *pi, Elf64_Shdr *section, const Elf64_Shdr *relsec, const Elf64_Shdr *symtab);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kexec_file.c (ffffffff8116d8da)
Location: kernel/kexec_file.c:137
Inline: False
Direct callers:
  - kernel/kexec_file.c:kexec_apply_relocations
```
**Symbols:**

```
ffffffff8116d8da-ffffffff8116d8f6: arch_kexec_apply_relocations (STB_WEAK)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int arch_kexec_apply_relocations(struct purgatory_info *pi, Elf64_Shdr *section, const Elf64_Shdr *relsec, const Elf64_Shdr *symtab);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kexec_file.c (ffffffff81be4610)
Location: kernel/kexec_file.c:138
Inline: False
Direct callers:
  - kernel/kexec_file.c:kexec_apply_relocations
```
**Symbols:**

```
ffffffff81be4610-ffffffff81be462c: arch_kexec_apply_relocations (STB_WEAK)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int arch_kexec_apply_relocations(struct purgatory_info *pi, Elf64_Shdr *section, const Elf64_Shdr *relsec, const Elf64_Shdr *symtab);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kexec_file.c (ffffffff81bd6431)
Location: kernel/kexec_file.c:138
Inline: False
Direct callers:
  - kernel/kexec_file.c:kexec_load_purgatory
```
**Symbols:**

```
ffffffff81bd6431-ffffffff81bd644d: arch_kexec_apply_relocations (STB_WEAK)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int arch_kexec_apply_relocations(struct purgatory_info *pi, Elf64_Shdr *section, const Elf64_Shdr *relsec, const Elf64_Shdr *symtab);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kexec_file.c (ffffffff81cb2d1e)
Location: kernel/kexec_file.c:138
Inline: False
Direct callers:
  - kernel/kexec_file.c:kexec_load_purgatory
```
**Symbols:**

```
ffffffff81cb2d1e-ffffffff81cb2d3a: arch_kexec_apply_relocations (STB_WEAK)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/kexec_file.c (ffffffff81e63b6a)
Location: include/linux/kexec.h:289
Inline: True
Inline callers:
  - kernel/kexec_file.c:kexec_load_purgatory
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/kexec_file.c (ffffffff812017ce)
Location: include/linux/kexec.h:286
Inline: True
Inline callers:
  - kernel/kexec_file.c:kexec_load_purgatory
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/kexec_file.c (ffffffff81216b9c)
Location: include/linux/kexec.h:278
Inline: True
Inline callers:
  - kernel/kexec_file.c:kexec_load_purgatory
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/kexec_file.c (ffffffff8122ea7c)
Location: include/linux/kexec.h:260
Inline: True
Inline callers:
  - kernel/kexec_file.c:kexec_load_purgatory
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
int arch_kexec_apply_relocations(struct purgatory_info *pi, Elf64_Shdr *section, const Elf64_Shdr *relsec, const Elf64_Shdr *symtab);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kexec_file.c (ffff8000101cb780)
Location: kernel/kexec_file.c:137
Inline: False
```
**Symbols:**

```
ffff8000101cb780-ffff8000101cb7a8: arch_kexec_apply_relocations (STB_WEAK)
```
</details>
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int arch_kexec_apply_relocations(struct purgatory_info *pi, Elf64_Shdr *section, const Elf64_Shdr *relsec, const Elf64_Shdr *symtab);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kexec_file.c (c0000000002356fc)
Location: kernel/kexec_file.c:137
Inline: False
Direct callers:
  - kernel/kexec_file.c:kexec_load_purgatory
```
**Symbols:**

```
c0000000002356fc-c00000000023573c: arch_kexec_apply_relocations (STB_WEAK)
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
<summary>In <code>aws</code>: ✅</summary>

```c
int arch_kexec_apply_relocations(struct purgatory_info *pi, Elf64_Shdr *section, const Elf64_Shdr *relsec, const Elf64_Shdr *symtab);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kexec_file.c (ffffffff811551ba)
Location: kernel/kexec_file.c:137
Inline: False
Direct callers:
  - kernel/kexec_file.c:kexec_load_purgatory
```
**Symbols:**

```
ffffffff811551ba-ffffffff811551d6: arch_kexec_apply_relocations (STB_WEAK)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int arch_kexec_apply_relocations(struct purgatory_info *pi, Elf64_Shdr *section, const Elf64_Shdr *relsec, const Elf64_Shdr *symtab);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kexec_file.c (ffffffff811484da)
Location: kernel/kexec_file.c:137
Inline: False
Direct callers:
  - kernel/kexec_file.c:kexec_load_purgatory
```
**Symbols:**

```
ffffffff811484da-ffffffff811484f6: arch_kexec_apply_relocations (STB_WEAK)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int arch_kexec_apply_relocations(struct purgatory_info *pi, Elf64_Shdr *section, const Elf64_Shdr *relsec, const Elf64_Shdr *symtab);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kexec_file.c (ffffffff81152f9a)
Location: kernel/kexec_file.c:137
Inline: False
Direct callers:
  - kernel/kexec_file.c:kexec_load_purgatory
```
**Symbols:**

```
ffffffff81152f9a-ffffffff81152fb6: arch_kexec_apply_relocations (STB_WEAK)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int arch_kexec_apply_relocations(struct purgatory_info *pi, Elf64_Shdr *section, const Elf64_Shdr *relsec, const Elf64_Shdr *symtab);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kexec_file.c (ffffffff8115fe8a)
Location: kernel/kexec_file.c:137
Inline: False
Direct callers:
  - kernel/kexec_file.c:kexec_load_purgatory
```
**Symbols:**

```
ffffffff8115fe8a-ffffffff8115fea6: arch_kexec_apply_relocations (STB_WEAK)
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
<details>
<summary>Changed between <code>4.15</code> and <code>4.18</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct purgatory_info *pi</code>
</li>
<li>
<b>Param added. </b>
<code>Elf64_Shdr *section</code>
</li>
<li>
<b>Param added. </b>
<code>const Elf64_Shdr *symtab</code>
</li>
<li>
<b>Param removed. </b>
<code>const Elf64_Ehdr *ehdr</code>
</li>
<li>
<b>Param removed. </b>
<code>Elf64_Shdr *sechdrs</code>
</li>
<li>
<b>Param type changed. </b>
<code>unsigned int relsec</code> ➡️ <code>const Elf64_Shdr *relsec</code>
</li>
</ul>
</details>
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
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
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
