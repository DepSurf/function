# Function: <code>ubsan_type_mismatch_common</code>

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
void ubsan_type_mismatch_common(struct type_mismatch_data_common *data, long unsigned int ptr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/ubsan.c (0)
Location: lib/ubsan.c:235
Inline: False
Direct callers:
  - lib/ubsan.c:__ubsan_handle_type_mismatch_v1
  - lib/ubsan.c:__ubsan_handle_type_mismatch
```
**Symbols:**

```
ffffffff81659a90-ffffffff81659b32: ubsan_type_mismatch_common (STB_LOCAL)
ffffffff81cdec4b-ffffffff81cded18: ubsan_type_mismatch_common.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void ubsan_type_mismatch_common(struct type_mismatch_data_common *data, long unsigned int ptr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/ubsan.c (0)
Location: lib/ubsan.c:227
Inline: False
Direct callers:
  - lib/ubsan.c:__ubsan_handle_type_mismatch_v1
  - lib/ubsan.c:__ubsan_handle_type_mismatch
```
**Symbols:**

```
ffffffff81772180-ffffffff81772230: ubsan_type_mismatch_common (STB_LOCAL)
ffffffff81ea5102-ffffffff81ea51cf: ubsan_type_mismatch_common.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void ubsan_type_mismatch_common(struct type_mismatch_data_common *data, long unsigned int ptr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/ubsan.c (ffffffff818a27c0)
Location: lib/ubsan.c:226
Inline: False
Direct callers:
  - lib/ubsan.c:__ubsan_handle_type_mismatch_v1
  - lib/ubsan.c:__ubsan_handle_type_mismatch
```
**Symbols:**

```
ffffffff818a27c0-ffffffff818a2a06: ubsan_type_mismatch_common (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void ubsan_type_mismatch_common(struct type_mismatch_data_common *data, long unsigned int ptr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/ubsan.c (ffffffff818e4d20)
Location: lib/ubsan.c:292
Inline: False
Direct callers:
  - lib/ubsan.c:__ubsan_handle_type_mismatch_v1
  - lib/ubsan.c:__ubsan_handle_type_mismatch
```
**Symbols:**

```
ffffffff818e4d20-ffffffff818e4f66: ubsan_type_mismatch_common (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void ubsan_type_mismatch_common(struct type_mismatch_data_common *data, long unsigned int ptr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/ubsan.c (ffffffff8192bd20)
Location: lib/ubsan.c:291
Inline: False
Direct callers:
  - lib/ubsan.c:__ubsan_handle_type_mismatch_v1
  - lib/ubsan.c:__ubsan_handle_type_mismatch
```
**Symbols:**

```
ffffffff8192bd20-ffffffff8192bf66: ubsan_type_mismatch_common (STB_LOCAL)
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
