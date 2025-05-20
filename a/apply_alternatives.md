# Function: <code>apply_alternatives</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void apply_alternatives(struct alt_instr *start, struct alt_instr *end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/alternative.c (ffffffff81035f20)
Location: arch/x86/kernel/alternative.c:362
Inline: False
Direct callers:
  - arch/x86/kernel/alternative.c:alternative_instructions
  - arch/x86/kernel/module.c:module_finalize
```
**Symbols:**

```
ffffffff81035f20-ffffffff810365a9: apply_alternatives (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void apply_alternatives(struct alt_instr *start, struct alt_instr *end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/alternative.c (ffffffff81035110)
Location: arch/x86/kernel/alternative.c:363
Inline: False
Direct callers:
  - arch/x86/kernel/alternative.c:alternative_instructions
  - arch/x86/kernel/module.c:module_finalize
```
**Symbols:**

```
ffffffff81035110-ffffffff8103579d: apply_alternatives (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void apply_alternatives(struct alt_instr *start, struct alt_instr *end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/alternative.c (ffffffff81034f10)
Location: arch/x86/kernel/alternative.c:369
Inline: False
Direct callers:
  - arch/x86/kernel/alternative.c:alternative_instructions
  - arch/x86/kernel/livepatch.c:arch_klp_init_object_loaded
  - arch/x86/kernel/module.c:module_finalize
```
**Symbols:**

```
ffffffff81034f10-ffffffff810354c1: apply_alternatives (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void apply_alternatives(struct alt_instr *start, struct alt_instr *end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/alternative.c (ffffffff81032f20)
Location: arch/x86/kernel/alternative.c:369
Inline: False
Direct callers:
  - arch/x86/kernel/alternative.c:alternative_instructions
  - arch/x86/kernel/livepatch.c:arch_klp_init_object_loaded
  - arch/x86/kernel/module.c:module_finalize
```
**Symbols:**

```
ffffffff81032f20-ffffffff8103347e: apply_alternatives (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void apply_alternatives(struct alt_instr *start, struct alt_instr *end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/alternative.c (ffffffff81035270)
Location: arch/x86/kernel/alternative.c:361
Inline: False
Direct callers:
  - arch/x86/kernel/alternative.c:alternative_instructions
  - arch/x86/kernel/livepatch.c:arch_klp_init_object_loaded
  - arch/x86/kernel/module.c:module_finalize
```
**Symbols:**

```
ffffffff81035270-ffffffff810357ce: apply_alternatives (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
void apply_alternatives(struct alt_instr *start, struct alt_instr *end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/alternative.c (0)
Location: arch/x86/kernel/alternative.c:361
Inline: False
Direct callers:
  - arch/x86/entry/vdso/vma.c:init_vdso_image
  - arch/x86/kernel/alternative.c:alternative_instructions
  - arch/x86/kernel/livepatch.c:arch_klp_init_object_loaded
  - arch/x86/kernel/module.c:module_finalize
```
**Symbols:**

```
ffffffff81036e64-ffffffff810370a2: apply_alternatives.cold.8 (STB_LOCAL)
ffffffff810363b0-ffffffff81036737: apply_alternatives (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
void apply_alternatives(struct alt_instr *start, struct alt_instr *end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/alternative.c (0)
Location: arch/x86/kernel/alternative.c:365
Inline: False
Direct callers:
  - arch/x86/entry/vdso/vma.c:init_vdso_image
  - arch/x86/kernel/alternative.c:alternative_instructions
  - arch/x86/kernel/livepatch.c:arch_klp_init_object_loaded
  - arch/x86/kernel/module.c:module_finalize
```
**Symbols:**

```
ffffffff81038074-ffffffff810382b2: apply_alternatives.cold.7 (STB_LOCAL)
ffffffff810375b0-ffffffff81037937: apply_alternatives (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void apply_alternatives(struct alt_instr *start, struct alt_instr *end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/alternative.c (0)
Location: arch/x86/kernel/alternative.c:369
Inline: False
Direct callers:
  - arch/x86/entry/vdso/vma.c:init_vdso_image
  - arch/x86/kernel/alternative.c:alternative_instructions
  - arch/x86/kernel/livepatch.c:arch_klp_init_object_loaded
  - arch/x86/kernel/module.c:module_finalize
```
**Symbols:**

```
ffffffff8103a68b-ffffffff8103a94f: apply_alternatives.cold (STB_LOCAL)
ffffffff81039f00-ffffffff8103a1fd: apply_alternatives (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
void apply_alternatives(struct alt_instr *start, struct alt_instr *end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/alternative.c (0)
Location: arch/x86/kernel/alternative.c:369
Inline: False
Direct callers:
  - arch/x86/entry/vdso/vma.c:init_vdso_image
  - arch/x86/kernel/alternative.c:alternative_instructions
  - arch/x86/kernel/livepatch.c:arch_klp_init_object_loaded
  - arch/x86/kernel/module.c:module_finalize
```
**Symbols:**

```
ffffffff8103ae54-ffffffff8103b118: apply_alternatives.cold (STB_LOCAL)
ffffffff8103a6e0-ffffffff8103a9dd: apply_alternatives (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
void apply_alternatives(struct alt_instr *start, struct alt_instr *end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/alternative.c (0)
Location: arch/x86/kernel/alternative.c:369
Inline: False
Direct callers:
  - arch/x86/entry/vdso/vma.c:init_vdso_image
  - arch/x86/kernel/alternative.c:alternative_instructions
  - arch/x86/kernel/module.c:module_finalize
```
**Symbols:**

```
ffffffff8103dada-ffffffff8103dd0f: apply_alternatives.cold (STB_LOCAL)
ffffffff8103d510-ffffffff8103d7f5: apply_alternatives (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
void apply_alternatives(struct alt_instr *start, struct alt_instr *end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/alternative.c (0)
Location: arch/x86/kernel/alternative.c:372
Inline: False
Direct callers:
  - arch/x86/entry/vdso/vma.c:init_vdso_image
  - arch/x86/kernel/alternative.c:alternative_instructions
  - arch/x86/kernel/module.c:module_finalize
```
**Symbols:**

```
ffffffff81bd3ff9-ffffffff81bd4205: apply_alternatives.cold (STB_LOCAL)
ffffffff8103da00-ffffffff8103dceb: apply_alternatives (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
void apply_alternatives(struct alt_instr *start, struct alt_instr *end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/alternative.c (0)
Location: arch/x86/kernel/alternative.c:261
Inline: False
Direct callers:
  - arch/x86/entry/vdso/vma.c:init_vdso_image
  - arch/x86/kernel/alternative.c:alternative_instructions
  - arch/x86/kernel/module.c:module_finalize
```
**Symbols:**

```
ffffffff81bc64da-ffffffff81bc6724: apply_alternatives.cold (STB_LOCAL)
ffffffff8103f3c0-ffffffff8103f707: apply_alternatives (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void apply_alternatives(struct alt_instr *start, struct alt_instr *end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/alternative.c (0)
Location: arch/x86/kernel/alternative.c:261
Inline: False
Direct callers:
  - arch/x86/entry/vdso/vma.c:init_vdso_image
  - arch/x86/kernel/alternative.c:alternative_instructions
  - arch/x86/kernel/module.c:module_finalize
```
**Symbols:**

```
ffffffff81c99539-ffffffff81c998b4: apply_alternatives.cold (STB_LOCAL)
ffffffff81045180-ffffffff81045517: apply_alternatives (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void apply_alternatives(struct alt_instr *start, struct alt_instr *end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/alternative.c (0)
Location: arch/x86/kernel/alternative.c:265
Inline: False
Direct callers:
  - arch/x86/entry/vdso/vma.c:init_vdso_image
  - arch/x86/kernel/alternative.c:alternative_instructions
  - arch/x86/kernel/module.c:module_finalize
```
**Symbols:**

```
ffffffff81e48b4e-ffffffff81e490d5: apply_alternatives.cold (STB_LOCAL)
ffffffff8104d780-ffffffff8104d8bd: apply_alternatives (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void apply_alternatives(struct alt_instr *start, struct alt_instr *end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/alternative.c (ffffffff81059d70)
Location: arch/x86/kernel/alternative.c:266
Inline: False
Direct callers:
  - arch/x86/entry/vdso/vma.c:init_vdso
  - arch/x86/kernel/alternative.c:alternative_instructions
  - arch/x86/kernel/module.c:module_finalize
```
**Symbols:**

```
ffffffff81059d70-ffffffff8105a3c3: apply_alternatives (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void apply_alternatives(struct alt_instr *start, struct alt_instr *end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/alternative.c (ffffffff8105b310)
Location: arch/x86/kernel/alternative.c:398
Inline: False
Direct callers:
  - arch/x86/entry/vdso/vma.c:init_vdso_image
  - arch/x86/kernel/alternative.c:alternative_instructions
  - arch/x86/kernel/module.c:module_finalize
```
**Symbols:**

```
ffffffff8105b310-ffffffff8105b87b: apply_alternatives (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void apply_alternatives(struct alt_instr *start, struct alt_instr *end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/alternative.c (ffffffff81062600)
Location: arch/x86/kernel/alternative.c:465
Inline: False
Direct callers:
  - arch/x86/entry/vdso/vma.c:init_vdso_image
  - arch/x86/kernel/alternative.c:alternative_instructions
  - arch/x86/kernel/module.c:module_finalize
```
**Symbols:**

```
ffffffff81062600-ffffffff81062be2: apply_alternatives (STB_GLOBAL)
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
<details>
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
void apply_alternatives(struct alt_instr *start, struct alt_instr *end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/alternative.c (0)
Location: arch/x86/kernel/alternative.c:369
Inline: False
Direct callers:
  - arch/x86/entry/vdso/vma.c:init_vdso_image
  - arch/x86/kernel/alternative.c:alternative_instructions
  - arch/x86/kernel/livepatch.c:arch_klp_init_object_loaded
  - arch/x86/kernel/module.c:module_finalize
```
**Symbols:**

```
ffffffff8103afb4-ffffffff8103b278: apply_alternatives.cold (STB_LOCAL)
ffffffff8103a840-ffffffff8103ab3d: apply_alternatives (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
void apply_alternatives(struct alt_instr *start, struct alt_instr *end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/alternative.c (0)
Location: arch/x86/kernel/alternative.c:369
Inline: False
Direct callers:
  - arch/x86/entry/vdso/vma.c:init_vdso_image
  - arch/x86/kernel/alternative.c:alternative_instructions
  - arch/x86/kernel/livepatch.c:arch_klp_init_object_loaded
  - arch/x86/kernel/module.c:module_finalize
```
**Symbols:**

```
ffffffff8102a7c4-ffffffff8102aa88: apply_alternatives.cold (STB_LOCAL)
ffffffff8102a050-ffffffff8102a34d: apply_alternatives (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
void apply_alternatives(struct alt_instr *start, struct alt_instr *end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/alternative.c (0)
Location: arch/x86/kernel/alternative.c:369
Inline: False
Direct callers:
  - arch/x86/entry/vdso/vma.c:init_vdso_image
  - arch/x86/kernel/alternative.c:alternative_instructions
  - arch/x86/kernel/livepatch.c:arch_klp_init_object_loaded
  - arch/x86/kernel/module.c:module_finalize
```
**Symbols:**

```
ffffffff8103ae14-ffffffff8103b0d8: apply_alternatives.cold (STB_LOCAL)
ffffffff8103a6a0-ffffffff8103a99d: apply_alternatives (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
void apply_alternatives(struct alt_instr *start, struct alt_instr *end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/alternative.c (0)
Location: arch/x86/kernel/alternative.c:369
Inline: False
Direct callers:
  - arch/x86/entry/vdso/vma.c:init_vdso_image
  - arch/x86/kernel/alternative.c:alternative_instructions
  - arch/x86/kernel/livepatch.c:arch_klp_init_object_loaded
  - arch/x86/kernel/module.c:module_finalize
```
**Symbols:**

```
ffffffff8103be14-ffffffff8103c0d8: apply_alternatives.cold (STB_LOCAL)
ffffffff8103b6a0-ffffffff8103b99d: apply_alternatives (STB_GLOBAL)
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
