# Function: <code>__ubsan_handle_shift_out_of_bounds</code>

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
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void __ubsan_handle_shift_out_of_bounds(void *_data, void *lhs, void *rhs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/ubsan.c (0)
Location: lib/ubsan.c:295
Inline: False
```
**Symbols:**

```
ffffffff81cdeb5c-ffffffff81cdec4b: __ubsan_handle_shift_out_of_bounds.cold (STB_LOCAL)
ffffffff81659a30-ffffffff81659a83: __ubsan_handle_shift_out_of_bounds (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void __ubsan_handle_shift_out_of_bounds(void *_data, void *lhs, void *rhs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/ubsan.c (0)
Location: lib/ubsan.c:287
Inline: False
```
**Symbols:**

```
ffffffff81ea5013-ffffffff81ea5102: __ubsan_handle_shift_out_of_bounds.cold (STB_LOCAL)
ffffffff817720c0-ffffffff8177217c: __ubsan_handle_shift_out_of_bounds (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void __ubsan_handle_shift_out_of_bounds(void *_data, void *lhs, void *rhs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/ubsan.c (ffffffff818a2450)
Location: lib/ubsan.c:286
Inline: False
```
**Symbols:**

```
ffffffff818a2450-ffffffff818a27b0: __ubsan_handle_shift_out_of_bounds (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void __ubsan_handle_shift_out_of_bounds(void *_data, void *lhs, void *rhs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/ubsan.c (ffffffff818e49a0)
Location: lib/ubsan.c:352
Inline: False
```
**Symbols:**

```
ffffffff818e49a0-ffffffff818e4d05: __ubsan_handle_shift_out_of_bounds (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void __ubsan_handle_shift_out_of_bounds(void *_data, void *lhs, void *rhs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/ubsan.c (ffffffff8192b9a0)
Location: lib/ubsan.c:351
Inline: False
```
**Symbols:**

```
ffffffff8192b9a0-ffffffff8192bd05: __ubsan_handle_shift_out_of_bounds (STB_GLOBAL)
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
