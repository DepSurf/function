# Function: <code>arch_kexec_apply_relocations_add</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int arch_kexec_apply_relocations_add(const Elf64_Ehdr *ehdr, Elf64_Shdr *sechdrs, unsigned int relsec);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/machine_kexec_64.c (ffffffff8105c0c0)
Location: arch/x86/kernel/machine_kexec_64.c:408
Inline: False
Direct callers:
  - kernel/kexec_file.c:kexec_load_purgatory
```
**Symbols:**

```
ffffffff8105c0c0-ffffffff8105c398: arch_kexec_apply_relocations_add (STB_WEAK)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int arch_kexec_apply_relocations_add(const Elf64_Ehdr *ehdr, Elf64_Shdr *sechdrs, unsigned int relsec);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/machine_kexec_64.c (ffffffff8105c230)
Location: arch/x86/kernel/machine_kexec_64.c:410
Inline: False
Direct callers:
  - kernel/kexec_file.c:kexec_load_purgatory
```
**Symbols:**

```
ffffffff8105c230-ffffffff8105c509: arch_kexec_apply_relocations_add (STB_WEAK)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int arch_kexec_apply_relocations_add(const Elf64_Ehdr *ehdr, Elf64_Shdr *sechdrs, unsigned int relsec);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/machine_kexec_64.c (ffffffff8105f1b0)
Location: arch/x86/kernel/machine_kexec_64.c:411
Inline: False
Direct callers:
  - kernel/kexec_file.c:kexec_load_purgatory
```
**Symbols:**

```
ffffffff8105f1b0-ffffffff8105f489: arch_kexec_apply_relocations_add (STB_WEAK)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int arch_kexec_apply_relocations_add(const Elf64_Ehdr *ehdr, Elf64_Shdr *sechdrs, unsigned int relsec);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/machine_kexec_64.c (ffffffff8105e890)
Location: arch/x86/kernel/machine_kexec_64.c:429
Inline: False
Direct callers:
  - kernel/kexec_file.c:kexec_load_purgatory
```
**Symbols:**

```
ffffffff8105e890-ffffffff8105eb54: arch_kexec_apply_relocations_add (STB_WEAK)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int arch_kexec_apply_relocations_add(const Elf64_Ehdr *ehdr, Elf64_Shdr *sechdrs, unsigned int relsec);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/machine_kexec_64.c (ffffffff810625d0)
Location: arch/x86/kernel/machine_kexec_64.c:431
Inline: False
Direct callers:
  - kernel/kexec_file.c:kexec_load_purgatory
```
**Symbols:**

```
ffffffff810625d0-ffffffff8106289a: arch_kexec_apply_relocations_add (STB_WEAK)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
int arch_kexec_apply_relocations_add(struct purgatory_info *pi, Elf64_Shdr *section, const Elf64_Shdr *relsec, const Elf64_Shdr *symtabsec);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/machine_kexec_64.c (ffffffff8113a28c)
Location: arch/x86/kernel/machine_kexec_64.c:396
Inline: False
Direct callers:
  - kernel/kexec_file.c:kexec_load_purgatory
```
**Symbols:**

```
ffffffff81065860-ffffffff810658df: arch_kexec_apply_relocations_add.cold.8 (STB_LOCAL)
ffffffff810655c0-ffffffff810657f9: arch_kexec_apply_relocations_add (STB_WEAK)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
int arch_kexec_apply_relocations_add(struct purgatory_info *pi, Elf64_Shdr *section, const Elf64_Shdr *relsec, const Elf64_Shdr *symtabsec);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/machine_kexec_64.c (ffffffff81145b5c)
Location: arch/x86/kernel/machine_kexec_64.c:396
Inline: False
Direct callers:
  - kernel/kexec_file.c:kexec_load_purgatory
```
**Symbols:**

```
ffffffff8106b530-ffffffff8106b599: arch_kexec_apply_relocations_add.cold.8 (STB_LOCAL)
ffffffff8106b230-ffffffff8106b4c4: arch_kexec_apply_relocations_add (STB_WEAK)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int arch_kexec_apply_relocations_add(struct purgatory_info *pi, Elf64_Shdr *section, const Elf64_Shdr *relsec, const Elf64_Shdr *symtabsec);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/machine_kexec_64.c (ffffffff81150eee)
Location: arch/x86/kernel/machine_kexec_64.c:494
Inline: False
Direct callers:
  - kernel/kexec_file.c:kexec_load_purgatory
```
**Symbols:**

```
ffffffff8106f06d-ffffffff8106f0d4: arch_kexec_apply_relocations_add.cold (STB_LOCAL)
ffffffff8106ed30-ffffffff8106efb8: arch_kexec_apply_relocations_add (STB_WEAK)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int arch_kexec_apply_relocations_add(struct purgatory_info *pi, Elf64_Shdr *section, const Elf64_Shdr *relsec, const Elf64_Shdr *symtabsec);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/machine_kexec_64.c (ffffffff8115cb7e)
Location: arch/x86/kernel/machine_kexec_64.c:494
Inline: False
Direct callers:
  - kernel/kexec_file.c:kexec_load_purgatory
```
**Symbols:**

```
ffffffff8107061d-ffffffff81070684: arch_kexec_apply_relocations_add.cold (STB_LOCAL)
ffffffff810702e0-ffffffff81070568: arch_kexec_apply_relocations_add (STB_WEAK)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int arch_kexec_apply_relocations_add(struct purgatory_info *pi, Elf64_Shdr *section, const Elf64_Shdr *relsec, const Elf64_Shdr *symtabsec);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/machine_kexec_64.c (ffffffff8116d8be)
Location: arch/x86/kernel/machine_kexec_64.c:427
Inline: False
Direct callers:
  - kernel/kexec_file.c:kexec_apply_relocations
```
**Symbols:**

```
ffffffff8107796d-ffffffff810779d4: arch_kexec_apply_relocations_add.cold (STB_LOCAL)
ffffffff81077630-ffffffff810778b8: arch_kexec_apply_relocations_add (STB_WEAK)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int arch_kexec_apply_relocations_add(struct purgatory_info *pi, Elf64_Shdr *section, const Elf64_Shdr *relsec, const Elf64_Shdr *symtabsec);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/machine_kexec_64.c (ffffffff81be45f4)
Location: arch/x86/kernel/machine_kexec_64.c:427
Inline: False
Direct callers:
  - kernel/kexec_file.c:kexec_apply_relocations
```
**Symbols:**

```
ffffffff81bd7a05-ffffffff81bd7a6c: arch_kexec_apply_relocations_add.cold (STB_LOCAL)
ffffffff81077c60-ffffffff81077ee8: arch_kexec_apply_relocations_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int arch_kexec_apply_relocations_add(struct purgatory_info *pi, Elf64_Shdr *section, const Elf64_Shdr *relsec, const Elf64_Shdr *symtabsec);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/machine_kexec_64.c (ffffffff81bd6415)
Location: arch/x86/kernel/machine_kexec_64.c:427
Inline: False
Direct callers:
  - kernel/kexec_file.c:kexec_load_purgatory
```
**Symbols:**

```
ffffffff81bc99bb-ffffffff81bc9a22: arch_kexec_apply_relocations_add.cold (STB_LOCAL)
ffffffff810786f0-ffffffff81078978: arch_kexec_apply_relocations_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int arch_kexec_apply_relocations_add(struct purgatory_info *pi, Elf64_Shdr *section, const Elf64_Shdr *relsec, const Elf64_Shdr *symtabsec);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/machine_kexec_64.c (ffffffff81cb2d02)
Location: arch/x86/kernel/machine_kexec_64.c:398
Inline: False
Direct callers:
  - kernel/kexec_file.c:kexec_load_purgatory
```
**Symbols:**

```
ffffffff81c9e85b-ffffffff81c9e8c2: arch_kexec_apply_relocations_add.cold (STB_LOCAL)
ffffffff81085f40-ffffffff810861c8: arch_kexec_apply_relocations_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int arch_kexec_apply_relocations_add(struct purgatory_info *pi, Elf64_Shdr *section, const Elf64_Shdr *relsec, const Elf64_Shdr *symtabsec);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/machine_kexec_64.c (0)
Location: arch/x86/kernel/machine_kexec_64.c:398
Inline: False
Direct callers:
  - kernel/kexec_file.c:kexec_load_purgatory
```
**Symbols:**

```
ffffffff81e4dcc9-ffffffff81e4dd26: arch_kexec_apply_relocations_add.cold (STB_LOCAL)
ffffffff810962f0-ffffffff81096582: arch_kexec_apply_relocations_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int arch_kexec_apply_relocations_add(struct purgatory_info *pi, Elf64_Shdr *section, const Elf64_Shdr *relsec, const Elf64_Shdr *symtabsec);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/machine_kexec_64.c (ffffffff810abfa0)
Location: arch/x86/kernel/machine_kexec_64.c:398
Inline: False
Direct callers:
  - kernel/kexec_file.c:kexec_load_purgatory
```
**Symbols:**

```
ffffffff810abfa0-ffffffff810ac282: arch_kexec_apply_relocations_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int arch_kexec_apply_relocations_add(struct purgatory_info *pi, Elf64_Shdr *section, const Elf64_Shdr *relsec, const Elf64_Shdr *symtabsec);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/machine_kexec_64.c (ffffffff810afad0)
Location: arch/x86/kernel/machine_kexec_64.c:387
Inline: False
Direct callers:
  - kernel/kexec_file.c:kexec_load_purgatory
```
**Symbols:**

```
ffffffff810afad0-ffffffff810afdb9: arch_kexec_apply_relocations_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int arch_kexec_apply_relocations_add(struct purgatory_info *pi, Elf64_Shdr *section, const Elf64_Shdr *relsec, const Elf64_Shdr *symtabsec);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/machine_kexec_64.c (ffffffff810b6660)
Location: arch/x86/kernel/machine_kexec_64.c:384
Inline: False
Direct callers:
  - kernel/kexec_file.c:kexec_load_purgatory
```
**Symbols:**

```
ffffffff810b6660-ffffffff810b6949: arch_kexec_apply_relocations_add (STB_GLOBAL)
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
int arch_kexec_apply_relocations_add(struct purgatory_info *pi, Elf64_Shdr *section, const Elf64_Shdr *relsec, const Elf64_Shdr *symtab);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kexec_file.c (ffff8000101cb758)
Location: kernel/kexec_file.c:120
Inline: False
```
**Symbols:**

```
ffff8000101cb758-ffff8000101cb780: arch_kexec_apply_relocations_add (STB_WEAK)
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
int arch_kexec_apply_relocations_add(struct purgatory_info *pi, Elf64_Shdr *section, const Elf64_Shdr *relsec, const Elf64_Shdr *symtab);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/kexec_file.c (c0000000002356bc)
Location: kernel/kexec_file.c:120
Inline: False
Direct callers:
  - kernel/kexec_file.c:kexec_load_purgatory
```
**Symbols:**

```
c0000000002356bc-c0000000002356fc: arch_kexec_apply_relocations_add (STB_WEAK)
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
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
int arch_kexec_apply_relocations_add(struct purgatory_info *pi, Elf64_Shdr *section, const Elf64_Shdr *relsec, const Elf64_Shdr *symtabsec);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/machine_kexec_64.c (ffffffff8115519e)
Location: arch/x86/kernel/machine_kexec_64.c:494
Inline: False
Direct callers:
  - kernel/kexec_file.c:kexec_load_purgatory
```
**Symbols:**

```
ffffffff8106f5bd-ffffffff8106f624: arch_kexec_apply_relocations_add.cold (STB_LOCAL)
ffffffff8106f280-ffffffff8106f508: arch_kexec_apply_relocations_add (STB_WEAK)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int arch_kexec_apply_relocations_add(struct purgatory_info *pi, Elf64_Shdr *section, const Elf64_Shdr *relsec, const Elf64_Shdr *symtabsec);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/machine_kexec_64.c (ffffffff811484be)
Location: arch/x86/kernel/machine_kexec_64.c:494
Inline: False
Direct callers:
  - kernel/kexec_file.c:kexec_load_purgatory
```
**Symbols:**

```
ffffffff8105f98d-ffffffff8105f9f4: arch_kexec_apply_relocations_add.cold (STB_LOCAL)
ffffffff8105f650-ffffffff8105f8d8: arch_kexec_apply_relocations_add (STB_WEAK)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int arch_kexec_apply_relocations_add(struct purgatory_info *pi, Elf64_Shdr *section, const Elf64_Shdr *relsec, const Elf64_Shdr *symtabsec);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/machine_kexec_64.c (ffffffff81152f7e)
Location: arch/x86/kernel/machine_kexec_64.c:494
Inline: False
Direct callers:
  - kernel/kexec_file.c:kexec_load_purgatory
```
**Symbols:**

```
ffffffff8106fa6d-ffffffff8106fad4: arch_kexec_apply_relocations_add.cold (STB_LOCAL)
ffffffff8106f730-ffffffff8106f9b8: arch_kexec_apply_relocations_add (STB_WEAK)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int arch_kexec_apply_relocations_add(struct purgatory_info *pi, Elf64_Shdr *section, const Elf64_Shdr *relsec, const Elf64_Shdr *symtabsec);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/machine_kexec_64.c (ffffffff8115fe6e)
Location: arch/x86/kernel/machine_kexec_64.c:494
Inline: False
Direct callers:
  - kernel/kexec_file.c:kexec_load_purgatory
```
**Symbols:**

```
ffffffff81071ced-ffffffff81071d54: arch_kexec_apply_relocations_add.cold (STB_LOCAL)
ffffffff810719b0-ffffffff81071c38: arch_kexec_apply_relocations_add (STB_WEAK)
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
<code>const Elf64_Shdr *symtabsec</code>
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
<details>
<summary>Changed between <code>amd64</code> and <code>arm64</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>const Elf64_Shdr *symtab</code>
</li>
<li>
<b>Param removed. </b>
<code>const Elf64_Shdr *symtabsec</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>amd64</code> and <code>ppc64el</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>const Elf64_Shdr *symtab</code>
</li>
<li>
<b>Param removed. </b>
<code>const Elf64_Shdr *symtabsec</code>
</li>
</ul>
</details>
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
