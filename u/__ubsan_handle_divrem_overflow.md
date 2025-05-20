# Function: <code>__ubsan_handle_divrem_overflow</code>

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
void __ubsan_handle_divrem_overflow(void *_data, void *lhs, void *rhs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/ubsan.c (0)
Location: lib/ubsan.c:169
Inline: False
```
**Symbols:**

```
ffffffff81cdeace-ffffffff81cdeb5c: __ubsan_handle_divrem_overflow.cold (STB_LOCAL)
ffffffff816599f0-ffffffff81659a27: __ubsan_handle_divrem_overflow (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void __ubsan_handle_divrem_overflow(void *_data, void *lhs, void *rhs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/ubsan.c (0)
Location: lib/ubsan.c:161
Inline: False
```
**Symbols:**

```
ffffffff81ea4f89-ffffffff81ea5013: __ubsan_handle_divrem_overflow.cold (STB_LOCAL)
ffffffff81772040-ffffffff817720b2: __ubsan_handle_divrem_overflow (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void __ubsan_handle_divrem_overflow(void *_data, void *lhs, void *rhs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/ubsan.c (ffffffff818a2260)
Location: lib/ubsan.c:160
Inline: False
```
**Symbols:**

```
ffffffff818a2260-ffffffff818a2431: __ubsan_handle_divrem_overflow (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void __ubsan_handle_divrem_overflow(void *_data, void *lhs, void *rhs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/ubsan.c (ffffffff818e4690)
Location: lib/ubsan.c:226
Inline: False
```
**Symbols:**

```
ffffffff818e4690-ffffffff818e4860: __ubsan_handle_divrem_overflow (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void __ubsan_handle_divrem_overflow(void *_data, void *lhs, void *rhs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/ubsan.c (ffffffff8192b690)
Location: lib/ubsan.c:225
Inline: False
```
**Symbols:**

```
ffffffff8192b690-ffffffff8192b860: __ubsan_handle_divrem_overflow (STB_GLOBAL)
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
