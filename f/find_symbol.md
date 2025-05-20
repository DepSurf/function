# Function: <code>find_symbol</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
const struct kernel_symbol *find_symbol(const char *name, struct module **owner, const long unsigned int **crc, bool gplok, bool warn);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffffffff81105c80)
Location: kernel/module.c:559
Inline: True
Direct callers:
  - kernel/module.c:__symbol_get
  - kernel/module.c:layout_and_allocate
  - kernel/module.c:load_module
```
**Symbols:**

```
ffffffff81105c80-ffffffff81105d31: find_symbol (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
const struct kernel_symbol *find_symbol(const char *name, struct module **owner, const long unsigned int **crc, bool gplok, bool warn);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffffffff8110d570)
Location: kernel/module.c:561
Inline: True
Direct callers:
  - kernel/module.c:load_module
  - kernel/module.c:layout_and_allocate
  - kernel/module.c:__symbol_get
```
**Symbols:**

```
ffffffff8110d570-ffffffff8110d619: find_symbol (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
const struct kernel_symbol *find_symbol(const char *name, struct module **owner, const s32 **crc, bool gplok, bool warn);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffffffff81114f50)
Location: kernel/module.c:564
Inline: True
Direct callers:
  - kernel/module.c:load_module
  - kernel/module.c:__symbol_get
```
**Symbols:**

```
ffffffff81114f50-ffffffff81114ff9: find_symbol (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
const struct kernel_symbol *find_symbol(const char *name, struct module **owner, const s32 **crc, bool gplok, bool warn);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffffffff81115ea0)
Location: kernel/module.c:568
Inline: True
Direct callers:
  - kernel/module.c:load_module
  - kernel/module.c:__symbol_get
```
**Symbols:**

```
ffffffff81115ea0-ffffffff81115f49: find_symbol (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
const struct kernel_symbol *find_symbol(const char *name, struct module **owner, const s32 **crc, bool gplok, bool warn);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffffffff81121430)
Location: kernel/module.c:578
Inline: True
Direct callers:
  - kernel/module.c:load_module
  - kernel/module.c:__symbol_get
```
**Symbols:**

```
ffffffff81121430-ffffffff811214d9: find_symbol (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
const struct kernel_symbol *find_symbol(const char *name, struct module **owner, const s32 **crc, bool gplok, bool warn);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffffffff8112ef10)
Location: kernel/module.c:577
Inline: True
Direct callers:
  - kernel/module.c:load_module
  - kernel/module.c:__symbol_get
```
**Symbols:**

```
ffffffff8112ef10-ffffffff8112efb9: find_symbol (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
const struct kernel_symbol *find_symbol(const char *name, struct module **owner, const s32 **crc, bool gplok, bool warn);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffffffff8113a8a0)
Location: kernel/module.c:578
Inline: True
Direct callers:
  - kernel/module.c:load_module
  - kernel/module.c:__symbol_get
```
**Symbols:**

```
ffffffff8113a8a0-ffffffff8113a949: find_symbol (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
const struct kernel_symbol *find_symbol(const char *name, struct module **owner, const s32 **crc, bool gplok, bool warn);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffffffff81145fe0)
Location: kernel/module.c:574
Inline: True
Direct callers:
  - kernel/module.c:load_module
  - kernel/module.c:__symbol_get
```
**Symbols:**

```
ffffffff81145fe0-ffffffff81146088: find_symbol (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
const struct kernel_symbol *find_symbol(const char *name, struct module **owner, const s32 **crc, bool gplok, bool warn);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffffffff81151d50)
Location: kernel/module.c:585
Inline: True
Direct callers:
  - kernel/module.c:load_module
  - kernel/module.c:__symbol_get
  - kernel/module.c:resolve_symbol
```
**Symbols:**

```
ffffffff81151d50-ffffffff81151df8: find_symbol (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
const struct kernel_symbol *find_symbol(const char *name, struct module **owner, const s32 **crc, bool gplok, bool warn);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffffffff81163340)
Location: kernel/module.c:588
Inline: True
Direct callers:
  - kernel/module.c:verify_exported_symbols
  - kernel/module.c:__symbol_get
  - kernel/module.c:resolve_symbol
```
**Symbols:**

```
ffffffff81163340-ffffffff81163412: find_symbol (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
const struct kernel_symbol *find_symbol(const char *name, struct module **owner, const s32 **crc, enum mod_license *license, bool gplok, bool warn);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffffffff811611c1)
Location: kernel/module.c:622
Inline: True
Inline callers:
  - kernel/module.c:__symbol_get
Direct callers:
  - kernel/module.c:load_module
  - kernel/module.c:verify_exported_symbols
  - kernel/module.c:resolve_symbol
```
**Symbols:**

```
ffffffff8115eba0-ffffffff8115ec53: find_symbol (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
bool find_symbol(struct find_symbol_arg *fsa);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffffffff8115e5c0)
Location: kernel/module.c:516
Inline: False
Direct callers:
  - kernel/module.c:load_module
  - kernel/module.c:complete_formation
  - kernel/module.c:__symbol_get
  - kernel/module.c:resolve_symbol
```
**Symbols:**

```
ffffffff8115e5c0-ffffffff8115e715: find_symbol (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
bool find_symbol(struct find_symbol_arg *fsa);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffffffff81184050)
Location: kernel/module.c:517
Inline: False
Direct callers:
  - kernel/module.c:load_module
  - kernel/module.c:complete_formation
  - kernel/module.c:__symbol_get
  - kernel/module.c:resolve_symbol
  - kernel/module.c:__symbol_put
```
**Symbols:**

```
ffffffff81184050-ffffffff811841a2: find_symbol (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
bool find_symbol(struct find_symbol_arg *fsa);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/module/main.c (ffffffff8118cf10)
Location: kernel/module/main.c:297
Inline: False
Direct callers:
  - kernel/module/main.c:load_module
  - kernel/module/main.c:__symbol_get
  - kernel/module/main.c:resolve_symbol
  - kernel/module/main.c:__symbol_put
  - kernel/module/version.c:check_modstruct_version
```
**Symbols:**

```
ffffffff8118cf10-ffffffff8118d06e: find_symbol (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
bool find_symbol(struct find_symbol_arg *fsa);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/module/main.c (ffffffff811c9900)
Location: kernel/module/main.c:295
Inline: False
Direct callers:
  - kernel/module/main.c:load_module
  - kernel/module/main.c:__symbol_get
  - kernel/module/main.c:resolve_symbol
  - kernel/module/main.c:__symbol_put
  - kernel/module/version.c:check_modstruct_version
```
**Symbols:**

```
ffffffff811c9900-ffffffff811c9a5e: find_symbol (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
bool find_symbol(struct find_symbol_arg *fsa);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/module/main.c (ffffffff811dc930)
Location: kernel/module/main.c:302
Inline: False
Direct callers:
  - kernel/module/main.c:load_module
  - kernel/module/main.c:__symbol_get
  - kernel/module/main.c:resolve_symbol
  - kernel/module/main.c:__symbol_put
  - kernel/module/version.c:check_modstruct_version
```
**Symbols:**

```
ffffffff811dc930-ffffffff811dca8e: find_symbol (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
bool find_symbol(struct find_symbol_arg *fsa);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/module/main.c (ffffffff811f2780)
Location: kernel/module/main.c:302
Inline: False
Direct callers:
  - kernel/module/main.c:load_module
  - kernel/module/main.c:__symbol_get
  - kernel/module/main.c:resolve_symbol
  - kernel/module/main.c:__symbol_put
  - kernel/module/version.c:check_modstruct_version
```
**Symbols:**

```
ffffffff811f2780-ffffffff811f28de: find_symbol (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
const struct kernel_symbol *find_symbol(const char *name, struct module **owner, const s32 **crc, bool gplok, bool warn);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffff8000101c0c68)
Location: kernel/module.c:585
Inline: True
Direct callers:
  - kernel/module.c:load_module
  - kernel/module.c:__symbol_get
  - kernel/module.c:resolve_symbol
```
**Symbols:**

```
ffff8000101c0c68-ffff8000101c0d40: find_symbol (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Collision, Selective Inline ⚠️</summary>

```c
Elf32_Sym *find_symbol(struct elfinfo *lib, const char *symname);
```

**Collision:** Static-Global Collision

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In arch/arm/kernel/vdso.c (c1506c7c)
Location: arch/arm/kernel/vdso.c:136
Inline: False
Direct callers:
  - arch/arm/kernel/vdso.c:vdso_init
  - arch/arm/kernel/vdso.c:vdso_init
```
```
In kernel/module.c (c04080bc)
Location: kernel/module.c:585
Inline: True
Direct callers:
  - kernel/module.c:load_module
  - kernel/module.c:__symbol_get
  - kernel/module.c:resolve_symbol
```
**Symbols:**

```
c1506c7c-c1506d70: find_symbol (STB_LOCAL)
c04080bc-c0408194: find_symbol (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
const struct kernel_symbol *find_symbol(const char *name, struct module **owner, const s32 **crc, bool gplok, bool warn);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/module.c (c000000000226e60)
Location: kernel/module.c:585
Inline: True
Direct callers:
  - kernel/module.c:load_module
  - kernel/module.c:__symbol_get
  - kernel/module.c:resolve_symbol
```
**Symbols:**

```
c000000000226e60-c000000000226f60: find_symbol (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
const struct kernel_symbol *find_symbol(const char *name, struct module **owner, const s32 **crc, bool gplok, bool warn);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffffffe000142ee8)
Location: kernel/module.c:585
Inline: True
Direct callers:
  - kernel/module.c:load_module
  - kernel/module.c:__symbol_get
  - kernel/module.c:resolve_symbol
```
**Symbols:**

```
ffffffe000142ee8-ffffffe000142f90: find_symbol (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
const struct kernel_symbol *find_symbol(const char *name, struct module **owner, const s32 **crc, bool gplok, bool warn);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffffffff8114a370)
Location: kernel/module.c:585
Inline: True
Direct callers:
  - kernel/module.c:load_module
  - kernel/module.c:__symbol_get
  - kernel/module.c:resolve_symbol
```
**Symbols:**

```
ffffffff8114a370-ffffffff8114a418: find_symbol (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
const struct kernel_symbol *find_symbol(const char *name, struct module **owner, const s32 **crc, bool gplok, bool warn);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffffffff8113d620)
Location: kernel/module.c:585
Inline: True
Direct callers:
  - kernel/module.c:load_module
  - kernel/module.c:__symbol_get
  - kernel/module.c:resolve_symbol
```
**Symbols:**

```
ffffffff8113d620-ffffffff8113d6c8: find_symbol (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
const struct kernel_symbol *find_symbol(const char *name, struct module **owner, const s32 **crc, bool gplok, bool warn);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffffffff81148220)
Location: kernel/module.c:585
Inline: True
Direct callers:
  - kernel/module.c:load_module
  - kernel/module.c:__symbol_get
  - kernel/module.c:resolve_symbol
```
**Symbols:**

```
ffffffff81148220-ffffffff811482c8: find_symbol (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
const struct kernel_symbol *find_symbol(const char *name, struct module **owner, const s32 **crc, bool gplok, bool warn);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffffffff81154e70)
Location: kernel/module.c:585
Inline: True
Direct callers:
  - kernel/module.c:load_module
  - kernel/module.c:__symbol_get
  - kernel/module.c:resolve_symbol
```
**Symbols:**

```
ffffffff81154e70-ffffffff81154f18: find_symbol (STB_GLOBAL)
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
<details>
<summary>Changed between <code>4.8</code> and <code>4.10</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>const long unsigned int **crc</code> ➡️ <code>const s32 **crc</code>
</li>
</ul>
</details>
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
<details>
<summary>Changed between <code>5.8</code> and <code>5.11</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>enum mod_license *license</code>
</li>
<li>
<b>Param reordered. </b>
<code>name, owner, crc, gplok, warn</code> ➡️ <code>name, owner, crc, license, gplok, warn</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.11</code> and <code>5.13</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct find_symbol_arg *fsa</code>
</li>
<li>
<b>Param removed. </b>
<code>const char *name</code>
</li>
<li>
<b>Param removed. </b>
<code>struct module **owner</code>
</li>
<li>
<b>Param removed. </b>
<code>const s32 **crc</code>
</li>
<li>
<b>Param removed. </b>
<code>enum mod_license *license</code>
</li>
<li>
<b>Param removed. </b>
<code>bool gplok</code>
</li>
<li>
<b>Param removed. </b>
<code>bool warn</code>
</li>
<li>
<b>Return type changed. </b>
<code>const struct kernel_symbol *</code> ➡️ <code>bool</code>
</li>
</ul>
</details>
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
<details>
<summary>Changed between <code>amd64</code> and <code>armhf</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct elfinfo *lib</code>
</li>
<li>
<b>Param added. </b>
<code>const char *symname</code>
</li>
<li>
<b>Param removed. </b>
<code>const char *name</code>
</li>
<li>
<b>Param removed. </b>
<code>struct module **owner</code>
</li>
<li>
<b>Param removed. </b>
<code>const s32 **crc</code>
</li>
<li>
<b>Param removed. </b>
<code>bool gplok</code>
</li>
<li>
<b>Param removed. </b>
<code>bool warn</code>
</li>
<li>
<b>Return type changed. </b>
<code>const struct kernel_symbol *</code> ➡️ <code>Elf32_Sym *</code>
</li>
</ul>
</details>
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
