# Function: <code>__ubsan_handle_load_invalid_value</code>

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
void __ubsan_handle_load_invalid_value(void *_data, void *val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/ubsan.c (0)
Location: lib/ubsan.c:347
Inline: False
```
**Symbols:**

```
ffffffff81cde95e-ffffffff81cde9a7: __ubsan_handle_load_invalid_value.cold (STB_LOCAL)
ffffffff81659940-ffffffff8165997c: __ubsan_handle_load_invalid_value (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void __ubsan_handle_load_invalid_value(void *_data, void *val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/ubsan.c (0)
Location: lib/ubsan.c:339
Inline: False
```
**Symbols:**

```
ffffffff81ea4dff-ffffffff81ea4e46: __ubsan_handle_load_invalid_value.cold (STB_LOCAL)
ffffffff81771f10-ffffffff81771f7b: __ubsan_handle_load_invalid_value (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void __ubsan_handle_load_invalid_value(void *_data, void *val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/ubsan.c (ffffffff818a1e90)
Location: lib/ubsan.c:338
Inline: False
```
**Symbols:**

```
ffffffff818a1e90-ffffffff818a1f98: __ubsan_handle_load_invalid_value (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void __ubsan_handle_load_invalid_value(void *_data, void *val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/ubsan.c (ffffffff818e4870)
Location: lib/ubsan.c:404
Inline: False
```
**Symbols:**

```
ffffffff818e4870-ffffffff818e4985: __ubsan_handle_load_invalid_value (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void __ubsan_handle_load_invalid_value(void *_data, void *val);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/ubsan.c (ffffffff8192b870)
Location: lib/ubsan.c:403
Inline: False
```
**Symbols:**

```
ffffffff8192b870-ffffffff8192b985: __ubsan_handle_load_invalid_value (STB_GLOBAL)
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
