# Function: <code>alternatives_smp_module_add</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void alternatives_smp_module_add(struct module *mod, char *name, void *locks, void *locks_end, void *text, void *text_end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/alternative.c (ffffffff81036940)
Location: arch/x86/kernel/alternative.c:483
Inline: False
Direct callers:
  - arch/x86/kernel/alternative.c:alternative_instructions
  - arch/x86/kernel/module.c:module_finalize
```
**Symbols:**

```
ffffffff81036940-ffffffff81036ac2: alternatives_smp_module_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void alternatives_smp_module_add(struct module *mod, char *name, void *locks, void *locks_end, void *text, void *text_end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/alternative.c (ffffffff81035b40)
Location: arch/x86/kernel/alternative.c:484
Inline: False
Direct callers:
  - arch/x86/kernel/alternative.c:alternative_instructions
  - arch/x86/kernel/module.c:module_finalize
```
**Symbols:**

```
ffffffff81035b40-ffffffff81035cc2: alternatives_smp_module_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void alternatives_smp_module_add(struct module *mod, char *name, void *locks, void *locks_end, void *text, void *text_end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/alternative.c (ffffffff81035870)
Location: arch/x86/kernel/alternative.c:490
Inline: False
Direct callers:
  - arch/x86/kernel/alternative.c:alternative_instructions
  - arch/x86/kernel/module.c:module_finalize
```
**Symbols:**

```
ffffffff81035870-ffffffff810359f3: alternatives_smp_module_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void alternatives_smp_module_add(struct module *mod, char *name, void *locks, void *locks_end, void *text, void *text_end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/alternative.c (ffffffff81033810)
Location: arch/x86/kernel/alternative.c:495
Inline: False
Direct callers:
  - arch/x86/kernel/alternative.c:alternative_instructions
  - arch/x86/kernel/module.c:module_finalize
```
**Symbols:**

```
ffffffff81033810-ffffffff810339af: alternatives_smp_module_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void alternatives_smp_module_add(struct module *mod, char *name, void *locks, void *locks_end, void *text, void *text_end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/alternative.c (ffffffff81035b70)
Location: arch/x86/kernel/alternative.c:482
Inline: False
Direct callers:
  - arch/x86/kernel/alternative.c:alternative_instructions
  - arch/x86/kernel/module.c:module_finalize
```
**Symbols:**

```
ffffffff81035b70-ffffffff81035cfa: alternatives_smp_module_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
void alternatives_smp_module_add(struct module *mod, char *name, void *locks, void *locks_end, void *text, void *text_end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/alternative.c (0)
Location: arch/x86/kernel/alternative.c:482
Inline: False
Direct callers:
  - arch/x86/kernel/alternative.c:alternative_instructions
  - arch/x86/kernel/module.c:module_finalize
```
**Symbols:**

```
ffffffff810370a2-ffffffff810370d1: alternatives_smp_module_add.cold.9 (STB_LOCAL)
ffffffff81036af0-ffffffff81036c44: alternatives_smp_module_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
void alternatives_smp_module_add(struct module *mod, char *name, void *locks, void *locks_end, void *text, void *text_end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/alternative.c (0)
Location: arch/x86/kernel/alternative.c:486
Inline: False
Direct callers:
  - arch/x86/kernel/alternative.c:alternative_instructions
  - arch/x86/kernel/module.c:module_finalize
```
**Symbols:**

```
ffffffff810382b2-ffffffff810382e1: alternatives_smp_module_add.cold.8 (STB_LOCAL)
ffffffff81037d00-ffffffff81037e54: alternatives_smp_module_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void alternatives_smp_module_add(struct module *mod, char *name, void *locks, void *locks_end, void *text, void *text_end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/alternative.c (0)
Location: arch/x86/kernel/alternative.c:490
Inline: False
Direct callers:
  - arch/x86/kernel/alternative.c:alternative_instructions
  - arch/x86/kernel/module.c:module_finalize
```
**Symbols:**

```
ffffffff8103a59b-ffffffff8103a5ca: alternatives_smp_module_add.cold (STB_LOCAL)
ffffffff81039b90-ffffffff81039cde: alternatives_smp_module_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
void alternatives_smp_module_add(struct module *mod, char *name, void *locks, void *locks_end, void *text, void *text_end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/alternative.c (0)
Location: arch/x86/kernel/alternative.c:490
Inline: False
Direct callers:
  - arch/x86/kernel/alternative.c:alternative_instructions
  - arch/x86/kernel/module.c:module_finalize
```
**Symbols:**

```
ffffffff8103ad68-ffffffff8103ad97: alternatives_smp_module_add.cold (STB_LOCAL)
ffffffff8103a370-ffffffff8103a4be: alternatives_smp_module_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
void alternatives_smp_module_add(struct module *mod, char *name, void *locks, void *locks_end, void *text, void *text_end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/alternative.c (0)
Location: arch/x86/kernel/alternative.c:490
Inline: False
Direct callers:
  - arch/x86/kernel/alternative.c:alternative_instructions
  - arch/x86/kernel/module.c:module_finalize
```
**Symbols:**

```
ffffffff8103d9ee-ffffffff8103da1d: alternatives_smp_module_add.cold (STB_LOCAL)
ffffffff8103d1d0-ffffffff8103d30d: alternatives_smp_module_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
void alternatives_smp_module_add(struct module *mod, char *name, void *locks, void *locks_end, void *text, void *text_end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/alternative.c (0)
Location: arch/x86/kernel/alternative.c:493
Inline: False
Direct callers:
  - arch/x86/kernel/alternative.c:alternative_instructions
  - arch/x86/kernel/module.c:module_finalize
```
**Symbols:**

```
ffffffff81bd3f14-ffffffff81bd3f3c: alternatives_smp_module_add.cold (STB_LOCAL)
ffffffff8103d6b0-ffffffff8103d7ed: alternatives_smp_module_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
void alternatives_smp_module_add(struct module *mod, char *name, void *locks, void *locks_end, void *text, void *text_end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/alternative.c (0)
Location: arch/x86/kernel/alternative.c:389
Inline: False
Direct callers:
  - arch/x86/kernel/alternative.c:alternative_instructions
  - arch/x86/kernel/module.c:module_finalize
```
**Symbols:**

```
ffffffff81bc63f5-ffffffff81bc641d: alternatives_smp_module_add.cold (STB_LOCAL)
ffffffff8103f060-ffffffff8103f19d: alternatives_smp_module_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void alternatives_smp_module_add(struct module *mod, char *name, void *locks, void *locks_end, void *text, void *text_end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/alternative.c (0)
Location: arch/x86/kernel/alternative.c:389
Inline: False
Direct callers:
  - arch/x86/kernel/alternative.c:alternative_instructions
  - arch/x86/kernel/module.c:module_finalize
```
**Symbols:**

```
ffffffff81c99425-ffffffff81c99468: alternatives_smp_module_add.cold (STB_LOCAL)
ffffffff81044e00-ffffffff81044f47: alternatives_smp_module_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void alternatives_smp_module_add(struct module *mod, char *name, void *locks, void *locks_end, void *text, void *text_end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/alternative.c (0)
Location: arch/x86/kernel/alternative.c:673
Inline: False
Direct callers:
  - arch/x86/kernel/alternative.c:alternative_instructions
  - arch/x86/kernel/module.c:module_finalize
```
**Symbols:**

```
ffffffff81e48a32-ffffffff81e48a75: alternatives_smp_module_add.cold (STB_LOCAL)
ffffffff8104d390-ffffffff8104d4ed: alternatives_smp_module_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void alternatives_smp_module_add(struct module *mod, char *name, void *locks, void *locks_end, void *text, void *text_end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/alternative.c (0)
Location: arch/x86/kernel/alternative.c:1127
Inline: False
Direct callers:
  - arch/x86/kernel/alternative.c:alternative_instructions
  - arch/x86/kernel/module.c:module_finalize
```
**Symbols:**

```
ffffffff82052405-ffffffff82052420: alternatives_smp_module_add.cold (STB_LOCAL)
ffffffff81059840-ffffffff810599c1: alternatives_smp_module_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void alternatives_smp_module_add(struct module *mod, char *name, void *locks, void *locks_end, void *text, void *text_end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/alternative.c (0)
Location: arch/x86/kernel/alternative.c:1304
Inline: False
Direct callers:
  - arch/x86/kernel/alternative.c:alternative_instructions
  - arch/x86/kernel/module.c:module_finalize
```
**Symbols:**

```
ffffffff820d08fe-ffffffff820d0919: alternatives_smp_module_add.cold (STB_LOCAL)
ffffffff8105adf0-ffffffff8105af70: alternatives_smp_module_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void alternatives_smp_module_add(struct module *mod, char *name, void *locks, void *locks_end, void *text, void *text_end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/alternative.c (0)
Location: arch/x86/kernel/alternative.c:1454
Inline: False
Direct callers:
  - arch/x86/kernel/alternative.c:alternative_instructions
  - arch/x86/kernel/module.c:module_finalize
```
**Symbols:**

```
ffffffff821ab427-ffffffff821ab442: alternatives_smp_module_add.cold (STB_LOCAL)
ffffffff810620b0-ffffffff81062267: alternatives_smp_module_add (STB_GLOBAL)
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
void alternatives_smp_module_add(struct module *mod, char *name, void *locks, void *locks_end, void *text, void *text_end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/alternative.c (0)
Location: arch/x86/kernel/alternative.c:490
Inline: False
Direct callers:
  - arch/x86/kernel/alternative.c:alternative_instructions
  - arch/x86/kernel/module.c:module_finalize
```
**Symbols:**

```
ffffffff8103aec8-ffffffff8103aef7: alternatives_smp_module_add.cold (STB_LOCAL)
ffffffff8103a4d0-ffffffff8103a61e: alternatives_smp_module_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
void alternatives_smp_module_add(struct module *mod, char *name, void *locks, void *locks_end, void *text, void *text_end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/alternative.c (0)
Location: arch/x86/kernel/alternative.c:490
Inline: False
Direct callers:
  - arch/x86/kernel/alternative.c:alternative_instructions
  - arch/x86/kernel/module.c:module_finalize
```
**Symbols:**

```
ffffffff8102a6d8-ffffffff8102a707: alternatives_smp_module_add.cold (STB_LOCAL)
ffffffff81029d00-ffffffff81029e4e: alternatives_smp_module_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
void alternatives_smp_module_add(struct module *mod, char *name, void *locks, void *locks_end, void *text, void *text_end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/alternative.c (0)
Location: arch/x86/kernel/alternative.c:490
Inline: False
Direct callers:
  - arch/x86/kernel/alternative.c:alternative_instructions
  - arch/x86/kernel/module.c:module_finalize
```
**Symbols:**

```
ffffffff8103ad28-ffffffff8103ad57: alternatives_smp_module_add.cold (STB_LOCAL)
ffffffff8103a330-ffffffff8103a47e: alternatives_smp_module_add (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
void alternatives_smp_module_add(struct module *mod, char *name, void *locks, void *locks_end, void *text, void *text_end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/alternative.c (0)
Location: arch/x86/kernel/alternative.c:490
Inline: False
Direct callers:
  - arch/x86/kernel/alternative.c:alternative_instructions
  - arch/x86/kernel/module.c:module_finalize
```
**Symbols:**

```
ffffffff8103bd28-ffffffff8103bd57: alternatives_smp_module_add.cold (STB_LOCAL)
ffffffff8103b330-ffffffff8103b47e: alternatives_smp_module_add (STB_GLOBAL)
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
