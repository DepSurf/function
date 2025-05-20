# Function: <code>apply_fineibt</code>

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
In <code>5.19</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void apply_fineibt(s32 *start_retpoline, s32 *end_retpoline, s32 *start_cfi, s32 *end_cfi);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/alternative.c (ffffffff81059820)
Location: arch/x86/kernel/alternative.c:1068
Inline: False
Direct callers:
  - arch/x86/kernel/module.c:module_finalize
  - arch/x86/kernel/module.c:module_finalize
  - arch/x86/kernel/module.c:module_finalize
```
**Symbols:**

```
ffffffff81059820-ffffffff8105982f: apply_fineibt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void apply_fineibt(s32 *start_retpoline, s32 *end_retpoline, s32 *start_cfi, s32 *end_cfi);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/alternative.c (ffffffff8105add0)
Location: arch/x86/kernel/alternative.c:1245
Inline: False
Direct callers:
  - arch/x86/kernel/module.c:module_finalize
  - arch/x86/kernel/module.c:module_finalize
  - arch/x86/kernel/module.c:module_finalize
```
**Symbols:**

```
ffffffff8105add0-ffffffff8105addf: apply_fineibt (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void apply_fineibt(s32 *start_retpoline, s32 *end_retpoline, s32 *start_cfi, s32 *end_cfi);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/kernel/alternative.c (ffffffff81062090)
Location: arch/x86/kernel/alternative.c:1395
Inline: False
Direct callers:
  - arch/x86/kernel/module.c:module_finalize
  - arch/x86/kernel/module.c:module_finalize
  - arch/x86/kernel/module.c:module_finalize
```
**Symbols:**

```
ffffffff81062090-ffffffff8106209f: apply_fineibt (STB_GLOBAL)
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
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
