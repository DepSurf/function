# Function: <code>__ubsan_handle_alignment_assumption</code>

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
void __ubsan_handle_alignment_assumption(void *_data, long unsigned int ptr, long unsigned int align, long unsigned int offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/ubsan.c (0)
Location: lib/ubsan.c:369
Inline: False
```
**Symbols:**

```
ffffffff81cde9f0-ffffffff81cdeace: __ubsan_handle_alignment_assumption.cold (STB_LOCAL)
ffffffff816599c0-ffffffff816599e4: __ubsan_handle_alignment_assumption (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void __ubsan_handle_alignment_assumption(void *_data, long unsigned int ptr, long unsigned int align, long unsigned int offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/ubsan.c (0)
Location: lib/ubsan.c:361
Inline: False
```
**Symbols:**

```
ffffffff81ea4e8d-ffffffff81ea4f89: __ubsan_handle_alignment_assumption.cold (STB_LOCAL)
ffffffff81771ff0-ffffffff8177203c: __ubsan_handle_alignment_assumption (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void __ubsan_handle_alignment_assumption(void *_data, long unsigned int ptr, long unsigned int align, long unsigned int offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/ubsan.c (ffffffff818a20d0)
Location: lib/ubsan.c:360
Inline: False
```
**Symbols:**

```
ffffffff818a20d0-ffffffff818a2249: __ubsan_handle_alignment_assumption (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void __ubsan_handle_alignment_assumption(void *_data, long unsigned int ptr, long unsigned int align, long unsigned int offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/ubsan.c (ffffffff818e4500)
Location: lib/ubsan.c:426
Inline: False
```
**Symbols:**

```
ffffffff818e4500-ffffffff818e4679: __ubsan_handle_alignment_assumption (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void __ubsan_handle_alignment_assumption(void *_data, long unsigned int ptr, long unsigned int align, long unsigned int offset);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/ubsan.c (ffffffff8192b500)
Location: lib/ubsan.c:425
Inline: False
```
**Symbols:**

```
ffffffff8192b500-ffffffff8192b679: __ubsan_handle_alignment_assumption (STB_GLOBAL)
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
