# Function: <code>apply_paravirt</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline, Transformation ⚠️</summary>

```c
void apply_paravirt(struct paravirt_patch_site *start, struct paravirt_patch_site *end);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/alternative.c (ffffffff810365b0)
Location: arch/x86/kernel/alternative.c:581
Inline: True
Inline callers:
  - arch/x86/kernel/alternative.c:alternative_instructions
Direct callers:
  - arch/x86/kernel/alternative.c:alternative_instructions
  - arch/x86/kernel/module.c:module_finalize
```
**Symbols:**

```
ffffffff810365b0-ffffffff810366f6: apply_paravirt.part.2 (STB_LOCAL)
ffffffff81036700-ffffffff8103671b: apply_paravirt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
void apply_paravirt(struct paravirt_patch_site *start, struct paravirt_patch_site *end);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/alternative.c (ffffffff81f90d98)
Location: arch/x86/kernel/alternative.c:582
Inline: True
Inline callers:
  - arch/x86/kernel/alternative.c:alternative_instructions
Direct callers:
  - arch/x86/kernel/alternative.c:alternative_instructions
  - arch/x86/kernel/module.c:module_finalize
```
**Symbols:**

```
ffffffff810357a0-ffffffff810358e2: apply_paravirt.part.2 (STB_LOCAL)
ffffffff810358f0-ffffffff8103590b: apply_paravirt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline, Transformation ⚠️</summary>

```c
void apply_paravirt(struct paravirt_patch_site *start, struct paravirt_patch_site *end);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/alternative.c (ffffffff81fcc135)
Location: arch/x86/kernel/alternative.c:588
Inline: True
Inline callers:
  - arch/x86/kernel/alternative.c:alternative_instructions
Direct callers:
  - arch/x86/kernel/alternative.c:alternative_instructions
  - arch/x86/kernel/livepatch.c:arch_klp_init_object_loaded
  - arch/x86/kernel/module.c:module_finalize
```
**Symbols:**

```
ffffffff810354d0-ffffffff81035612: apply_paravirt.part.4 (STB_LOCAL)
ffffffff81035620-ffffffff8103563b: apply_paravirt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline, Transformation ⚠️</summary>

```c
void apply_paravirt(struct paravirt_patch_site *start, struct paravirt_patch_site *end);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/alternative.c (ffffffff820ac89f)
Location: arch/x86/kernel/alternative.c:593
Inline: True
Inline callers:
  - arch/x86/kernel/alternative.c:alternative_instructions
Direct callers:
  - arch/x86/kernel/alternative.c:alternative_instructions
  - arch/x86/kernel/livepatch.c:arch_klp_init_object_loaded
  - arch/x86/kernel/module.c:module_finalize
```
**Symbols:**

```
ffffffff81033480-ffffffff810335d3: apply_paravirt.part.4 (STB_LOCAL)
ffffffff810335e0-ffffffff810335fc: apply_paravirt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void apply_paravirt(struct paravirt_patch_site *start, struct paravirt_patch_site *end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/alternative.c (ffffffff810357d0)
Location: arch/x86/kernel/alternative.c:585
Inline: False
Direct callers:
  - arch/x86/kernel/alternative.c:alternative_instructions
  - arch/x86/kernel/livepatch.c:arch_klp_init_object_loaded
  - arch/x86/kernel/module.c:module_finalize
```
**Symbols:**

```
ffffffff810357d0-ffffffff81035925: apply_paravirt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void apply_paravirt(struct paravirt_patch_site *start, struct paravirt_patch_site *end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/alternative.c (ffffffff81036740)
Location: arch/x86/kernel/alternative.c:585
Inline: False
Direct callers:
  - arch/x86/kernel/alternative.c:alternative_instructions
  - arch/x86/kernel/livepatch.c:arch_klp_init_object_loaded
  - arch/x86/kernel/module.c:module_finalize
```
**Symbols:**

```
ffffffff81036740-ffffffff81036892: apply_paravirt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void apply_paravirt(struct paravirt_patch_site *start, struct paravirt_patch_site *end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/alternative.c (ffffffff81037940)
Location: arch/x86/kernel/alternative.c:589
Inline: False
Direct callers:
  - arch/x86/kernel/alternative.c:alternative_instructions
  - arch/x86/kernel/livepatch.c:arch_klp_init_object_loaded
  - arch/x86/kernel/module.c:module_finalize
```
**Symbols:**

```
ffffffff81037940-ffffffff81037a98: apply_paravirt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void apply_paravirt(struct paravirt_patch_site *start, struct paravirt_patch_site *end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/alternative.c (ffffffff8103a200)
Location: arch/x86/kernel/alternative.c:593
Inline: False
Direct callers:
  - arch/x86/kernel/alternative.c:alternative_instructions
  - arch/x86/kernel/livepatch.c:arch_klp_init_object_loaded
  - arch/x86/kernel/module.c:module_finalize
```
**Symbols:**

```
ffffffff8103a200-ffffffff8103a32f: apply_paravirt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void apply_paravirt(struct paravirt_patch_site *start, struct paravirt_patch_site *end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/alternative.c (ffffffff8103a9e0)
Location: arch/x86/kernel/alternative.c:593
Inline: False
Direct callers:
  - arch/x86/kernel/alternative.c:alternative_instructions
  - arch/x86/kernel/livepatch.c:arch_klp_init_object_loaded
  - arch/x86/kernel/module.c:module_finalize
```
**Symbols:**

```
ffffffff8103a9e0-ffffffff8103ab0f: apply_paravirt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void apply_paravirt(struct paravirt_patch_site *start, struct paravirt_patch_site *end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/alternative.c (ffffffff8103d800)
Location: arch/x86/kernel/alternative.c:593
Inline: False
Direct callers:
  - arch/x86/kernel/alternative.c:alternative_instructions
  - arch/x86/kernel/module.c:module_finalize
```
**Symbols:**

```
ffffffff8103d800-ffffffff8103d92f: apply_paravirt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void apply_paravirt(struct paravirt_patch_site *start, struct paravirt_patch_site *end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/alternative.c (ffffffff8103dcf0)
Location: arch/x86/kernel/alternative.c:596
Inline: False
Direct callers:
  - arch/x86/kernel/alternative.c:alternative_instructions
  - arch/x86/kernel/module.c:module_finalize
```
**Symbols:**

```
ffffffff8103dcf0-ffffffff8103de1f: apply_paravirt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void apply_paravirt(struct paravirt_patch_site *start, struct paravirt_patch_site *end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/alternative.c (ffffffff8103f710)
Location: arch/x86/kernel/alternative.c:492
Inline: False
Direct callers:
  - arch/x86/kernel/alternative.c:alternative_instructions
  - arch/x86/kernel/module.c:module_finalize
```
**Symbols:**

```
ffffffff8103f710-ffffffff8103f834: apply_paravirt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void apply_paravirt(struct paravirt_patch_site *start, struct paravirt_patch_site *end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/alternative.c (ffffffff81045520)
Location: arch/x86/kernel/alternative.c:492
Inline: False
Direct callers:
  - arch/x86/kernel/alternative.c:alternative_instructions
  - arch/x86/kernel/module.c:module_finalize
```
**Symbols:**

```
ffffffff81045520-ffffffff81045644: apply_paravirt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void apply_paravirt(struct paravirt_patch_site *start, struct paravirt_patch_site *end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/alternative.c (ffffffff8104dcc0)
Location: arch/x86/kernel/alternative.c:776
Inline: False
Direct callers:
  - arch/x86/kernel/alternative.c:alternative_instructions
  - arch/x86/kernel/module.c:module_finalize
```
**Symbols:**

```
ffffffff8104dcc0-ffffffff8104df4b: apply_paravirt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void apply_paravirt(struct paravirt_patch_site *start, struct paravirt_patch_site *end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/alternative.c (ffffffff8105aab0)
Location: arch/x86/kernel/alternative.c:1230
Inline: False
Direct callers:
  - arch/x86/kernel/alternative.c:alternative_instructions
  - arch/x86/kernel/module.c:module_finalize
```
**Symbols:**

```
ffffffff8105aab0-ffffffff8105ad3b: apply_paravirt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void apply_paravirt(struct paravirt_patch_site *start, struct paravirt_patch_site *end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/alternative.c (ffffffff8105bff0)
Location: arch/x86/kernel/alternative.c:1421
Inline: False
Direct callers:
  - arch/x86/kernel/alternative.c:alternative_instructions
  - arch/x86/kernel/module.c:module_finalize
```
**Symbols:**

```
ffffffff8105bff0-ffffffff8105c27b: apply_paravirt (STB_GLOBAL)
```
</details>
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
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
void apply_paravirt(struct paravirt_patch_site *start, struct paravirt_patch_site *end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/alternative.c (ffffffff8103ab40)
Location: arch/x86/kernel/alternative.c:593
Inline: False
Direct callers:
  - arch/x86/kernel/alternative.c:alternative_instructions
  - arch/x86/kernel/livepatch.c:arch_klp_init_object_loaded
  - arch/x86/kernel/module.c:module_finalize
```
**Symbols:**

```
ffffffff8103ab40-ffffffff8103ac6f: apply_paravirt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void apply_paravirt(struct paravirt_patch_site *start, struct paravirt_patch_site *end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/alternative.c (ffffffff8102a350)
Location: arch/x86/kernel/alternative.c:593
Inline: False
Direct callers:
  - arch/x86/kernel/alternative.c:alternative_instructions
  - arch/x86/kernel/livepatch.c:arch_klp_init_object_loaded
  - arch/x86/kernel/module.c:module_finalize
```
**Symbols:**

```
ffffffff8102a350-ffffffff8102a47f: apply_paravirt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void apply_paravirt(struct paravirt_patch_site *start, struct paravirt_patch_site *end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/alternative.c (ffffffff8103a9a0)
Location: arch/x86/kernel/alternative.c:593
Inline: False
Direct callers:
  - arch/x86/kernel/alternative.c:alternative_instructions
  - arch/x86/kernel/livepatch.c:arch_klp_init_object_loaded
  - arch/x86/kernel/module.c:module_finalize
```
**Symbols:**

```
ffffffff8103a9a0-ffffffff8103aacf: apply_paravirt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void apply_paravirt(struct paravirt_patch_site *start, struct paravirt_patch_site *end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/alternative.c (ffffffff8103b9a0)
Location: arch/x86/kernel/alternative.c:593
Inline: False
Direct callers:
  - arch/x86/kernel/alternative.c:alternative_instructions
  - arch/x86/kernel/livepatch.c:arch_klp_init_object_loaded
  - arch/x86/kernel/module.c:module_finalize
```
**Symbols:**

```
ffffffff8103b9a0-ffffffff8103bacf: apply_paravirt (STB_GLOBAL)
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
