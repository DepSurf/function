# Function: <code>ubsan_epilogue</code>

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
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void ubsan_epilogue();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/ubsan.c (ffffffff81cde769)
Location: lib/ubsan.c:149
Inline: False
Direct callers:
  - lib/ubsan.c:__ubsan_handle_alignment_assumption
  - lib/ubsan.c:__ubsan_handle_load_invalid_value
  - lib/ubsan.c:__ubsan_handle_builtin_unreachable
  - lib/ubsan.c:__ubsan_handle_shift_out_of_bounds
  - lib/ubsan.c:__ubsan_handle_out_of_bounds
  - lib/ubsan.c:ubsan_type_mismatch_common
  - lib/ubsan.c:ubsan_type_mismatch_common
  - lib/ubsan.c:ubsan_type_mismatch_common
  - lib/ubsan.c:__ubsan_handle_divrem_overflow
```
**Symbols:**

```
ffffffff81cde769-ffffffff81cde7ae: ubsan_epilogue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void ubsan_epilogue();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/ubsan.c (ffffffff81ea4b9b)
Location: lib/ubsan.c:149
Inline: False
Direct callers:
  - lib/ubsan.c:__ubsan_handle_alignment_assumption
  - lib/ubsan.c:__ubsan_handle_load_invalid_value
  - lib/ubsan.c:__ubsan_handle_builtin_unreachable
  - lib/ubsan.c:__ubsan_handle_shift_out_of_bounds
  - lib/ubsan.c:__ubsan_handle_out_of_bounds
  - lib/ubsan.c:ubsan_type_mismatch_common
  - lib/ubsan.c:ubsan_type_mismatch_common
  - lib/ubsan.c:ubsan_type_mismatch_common
  - lib/ubsan.c:__ubsan_handle_divrem_overflow
```
**Symbols:**

```
ffffffff81ea4b9b-ffffffff81ea4bde: ubsan_epilogue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void ubsan_epilogue();
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/ubsan.c (ffffffff818a21c1)
Location: lib/ubsan.c:149
Inline: True
Inline callers:
  - lib/ubsan.c:__ubsan_handle_alignment_assumption
  - lib/ubsan.c:__ubsan_handle_load_invalid_value
  - lib/ubsan.c:__ubsan_handle_shift_out_of_bounds
  - lib/ubsan.c:__ubsan_handle_out_of_bounds
  - lib/ubsan.c:ubsan_type_mismatch_common
  - lib/ubsan.c:ubsan_type_mismatch_common
  - lib/ubsan.c:__ubsan_handle_divrem_overflow
Direct callers:
  - lib/ubsan.c:__ubsan_handle_builtin_unreachable
```
**Symbols:**

```
ffffffff818a1c80-ffffffff818a1cbb: ubsan_epilogue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void ubsan_epilogue();
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/ubsan.c (ffffffff818e45f1)
Location: lib/ubsan.c:215
Inline: True
Inline callers:
  - lib/ubsan.c:__ubsan_handle_alignment_assumption
  - lib/ubsan.c:__ubsan_handle_load_invalid_value
  - lib/ubsan.c:__ubsan_handle_shift_out_of_bounds
  - lib/ubsan.c:__ubsan_handle_out_of_bounds
  - lib/ubsan.c:ubsan_type_mismatch_common
  - lib/ubsan.c:ubsan_type_mismatch_common
  - lib/ubsan.c:__ubsan_handle_divrem_overflow
Direct callers:
  - lib/ubsan.c:__ubsan_handle_builtin_unreachable
```
**Symbols:**

```
ffffffff818e41d0-ffffffff818e420b: ubsan_epilogue (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void ubsan_epilogue();
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/ubsan.c (ffffffff8192b5f1)
Location: lib/ubsan.c:215
Inline: True
Inline callers:
  - lib/ubsan.c:__ubsan_handle_alignment_assumption
  - lib/ubsan.c:__ubsan_handle_load_invalid_value
  - lib/ubsan.c:__ubsan_handle_shift_out_of_bounds
  - lib/ubsan.c:__ubsan_handle_out_of_bounds
  - lib/ubsan.c:ubsan_type_mismatch_common
  - lib/ubsan.c:ubsan_type_mismatch_common
  - lib/ubsan.c:__ubsan_handle_divrem_overflow
Direct callers:
  - lib/ubsan.c:__ubsan_handle_builtin_unreachable
```
**Symbols:**

```
ffffffff8192b1d0-ffffffff8192b20b: ubsan_epilogue (STB_LOCAL)
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
