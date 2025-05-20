# Function: <code>val_is_negative</code>

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
bool val_is_negative(struct type_descriptor *type, void *val);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/ubsan.c (ffffffff81cde923)
Location: lib/ubsan.c:95
Inline: False
Direct callers:
  - lib/ubsan.c:__ubsan_handle_shift_out_of_bounds
  - lib/ubsan.c:__ubsan_handle_shift_out_of_bounds
```
**Symbols:**

```
ffffffff81cde923-ffffffff81cde95e: val_is_negative (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
bool val_is_negative(struct type_descriptor *type, void *val);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/ubsan.c (ffffffff81ea4daf)
Location: lib/ubsan.c:95
Inline: False
Direct callers:
  - lib/ubsan.c:__ubsan_handle_shift_out_of_bounds
  - lib/ubsan.c:__ubsan_handle_shift_out_of_bounds
```
**Symbols:**

```
ffffffff81ea4daf-ffffffff81ea4dff: val_is_negative (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In lib/ubsan.c (ffffffff818a255b)
Location: lib/ubsan.c:95
Inline: True
Inline callers:
  - lib/ubsan.c:__ubsan_handle_shift_out_of_bounds
  - lib/ubsan.c:__ubsan_handle_shift_out_of_bounds
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In lib/ubsan.c (ffffffff818e4aab)
Location: lib/ubsan.c:161
Inline: True
Inline callers:
  - lib/ubsan.c:__ubsan_handle_shift_out_of_bounds
  - lib/ubsan.c:__ubsan_handle_shift_out_of_bounds
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In lib/ubsan.c (ffffffff8192baab)
Location: lib/ubsan.c:161
Inline: True
Inline callers:
  - lib/ubsan.c:__ubsan_handle_shift_out_of_bounds
  - lib/ubsan.c:__ubsan_handle_shift_out_of_bounds
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
</ul>
