# Function: <code>apply_returns</code>

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
void apply_returns(s32 *start, s32 *end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/alternative.c (0)
Location: arch/x86/kernel/alternative.c:538
Inline: False
Direct callers:
  - arch/x86/kernel/alternative.c:alternative_instructions
  - arch/x86/kernel/module.c:module_finalize
```
**Symbols:**

```
ffffffff81e49208-ffffffff81e49361: apply_returns.cold (STB_LOCAL)
ffffffff8104da40-ffffffff8104dcb6: apply_returns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void apply_returns(s32 *start, s32 *end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/alternative.c (0)
Location: arch/x86/kernel/alternative.c:610
Inline: False
Direct callers:
  - arch/x86/kernel/alternative.c:alternative_instructions
  - arch/x86/kernel/module.c:module_finalize
```
**Symbols:**

```
ffffffff82052434-ffffffff82052455: apply_returns.cold (STB_LOCAL)
ffffffff8105a730-ffffffff8105aa9c: apply_returns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void apply_returns(s32 *start, s32 *end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/alternative.c (0)
Location: arch/x86/kernel/alternative.c:719
Inline: False
Direct callers:
  - arch/x86/kernel/alternative.c:alternative_instructions
  - arch/x86/kernel/module.c:module_finalize
```
**Symbols:**

```
ffffffff820d092d-ffffffff820d094e: apply_returns.cold (STB_LOCAL)
ffffffff8105bbe0-ffffffff8105bfd3: apply_returns (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void apply_returns(s32 *start, s32 *end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In arch/x86/kernel/alternative.c (0)
Location: arch/x86/kernel/alternative.c:804
Inline: False
Direct callers:
  - arch/x86/kernel/alternative.c:alternative_instructions
  - arch/x86/kernel/module.c:module_finalize
```
**Symbols:**

```
ffffffff821ab456-ffffffff821ab477: apply_returns.cold (STB_LOCAL)
ffffffff81062f50-ffffffff8106333a: apply_returns (STB_GLOBAL)
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
