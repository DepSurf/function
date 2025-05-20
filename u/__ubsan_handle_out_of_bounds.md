# Function: <code>__ubsan_handle_out_of_bounds</code>

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
void __ubsan_handle_out_of_bounds(void *_data, void *index);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/ubsan.c (0)
Location: lib/ubsan.c:278
Inline: False
```
**Symbols:**

```
ffffffff81cde9a7-ffffffff81cde9f0: __ubsan_handle_out_of_bounds.cold (STB_LOCAL)
ffffffff81659980-ffffffff816599bc: __ubsan_handle_out_of_bounds (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void __ubsan_handle_out_of_bounds(void *_data, void *index);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/ubsan.c (0)
Location: lib/ubsan.c:270
Inline: False
```
**Symbols:**

```
ffffffff81ea4e46-ffffffff81ea4e8d: __ubsan_handle_out_of_bounds.cold (STB_LOCAL)
ffffffff81771f80-ffffffff81771feb: __ubsan_handle_out_of_bounds (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void __ubsan_handle_out_of_bounds(void *_data, void *index);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/ubsan.c (ffffffff818a1fb0)
Location: lib/ubsan.c:269
Inline: False
```
**Symbols:**

```
ffffffff818a1fb0-ffffffff818a20b8: __ubsan_handle_out_of_bounds (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void __ubsan_handle_out_of_bounds(void *_data, void *index);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/ubsan.c (ffffffff818e43e0)
Location: lib/ubsan.c:335
Inline: False
```
**Symbols:**

```
ffffffff818e43e0-ffffffff818e44e8: __ubsan_handle_out_of_bounds (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void __ubsan_handle_out_of_bounds(void *_data, void *index);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/ubsan.c (ffffffff8192b3e0)
Location: lib/ubsan.c:334
Inline: False
```
**Symbols:**

```
ffffffff8192b3e0-ffffffff8192b4e8: __ubsan_handle_out_of_bounds (STB_GLOBAL)
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
