# Function: <code>ex_get_fixup_type</code>

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
<summary>In <code>5.19</code>: ✅</summary>

```c
int ex_get_fixup_type(long unsigned int ip);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/extable.c (ffffffff810ac1c0)
Location: arch/x86/mm/extable.c:145
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/severity.c:error_context
```
**Symbols:**

```
ffffffff810ac1c0-ffffffff810ac1e5: ex_get_fixup_type (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int ex_get_fixup_type(long unsigned int ip);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/extable.c (ffffffff810c61a0)
Location: arch/x86/mm/extable.c:198
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/severity.c:error_context
```
**Symbols:**

```
ffffffff810c61a0-ffffffff810c61c5: ex_get_fixup_type (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int ex_get_fixup_type(long unsigned int ip);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/extable.c (ffffffff810c9910)
Location: arch/x86/mm/extable.c:226
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/severity.c:error_context
```
**Symbols:**

```
ffffffff810c9910-ffffffff810c9935: ex_get_fixup_type (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int ex_get_fixup_type(long unsigned int ip);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In arch/x86/mm/extable.c (ffffffff810d1d70)
Location: arch/x86/mm/extable.c:226
Inline: False
Direct callers:
  - arch/x86/kernel/cpu/mce/severity.c:error_context
```
**Symbols:**

```
ffffffff810d1d70-ffffffff810d1d95: ex_get_fixup_type (STB_GLOBAL)
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
