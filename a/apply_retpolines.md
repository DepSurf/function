# Function: <code>apply_retpolines</code>

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
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void apply_retpolines(s32 *start, s32 *end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/alternative.c (0)
Location: arch/x86/kernel/alternative.c:465
Inline: False
Direct callers:
  - arch/x86/kernel/alternative.c:alternative_instructions
  - arch/x86/kernel/module.c:module_finalize
```
**Symbols:**

```
ffffffff81e490d5-ffffffff81e49208: apply_retpolines.cold (STB_LOCAL)
ffffffff8104d8c0-ffffffff8104da36: apply_retpolines (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void apply_retpolines(s32 *start, s32 *end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/alternative.c (ffffffff8105a3e0)
Location: arch/x86/kernel/alternative.c:528
Inline: False
Direct callers:
  - arch/x86/kernel/alternative.c:alternative_instructions
  - arch/x86/kernel/module.c:module_finalize
```
**Symbols:**

```
ffffffff8105a3e0-ffffffff8105a71f: apply_retpolines (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void apply_retpolines(s32 *start, s32 *end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/alternative.c (ffffffff8105b890)
Location: arch/x86/kernel/alternative.c:642
Inline: False
Direct callers:
  - arch/x86/kernel/alternative.c:alternative_instructions
  - arch/x86/kernel/module.c:module_finalize
```
**Symbols:**

```
ffffffff8105b890-ffffffff8105bbcb: apply_retpolines (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void apply_retpolines(s32 *start, s32 *end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/alternative.c (ffffffff81062c00)
Location: arch/x86/kernel/alternative.c:727
Inline: False
Direct callers:
  - arch/x86/kernel/alternative.c:alternative_instructions
  - arch/x86/kernel/module.c:module_finalize
```
**Symbols:**

```
ffffffff81062c00-ffffffff81062f3b: apply_retpolines (STB_GLOBAL)
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
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
