# Function: <code>clear_shadow_from_swap_cache</code>

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
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void clear_shadow_from_swap_cache(int type, long unsigned int begin, long unsigned int end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap_state.c (ffffffff812c4a00)
Location: mm/swap_state.c:285
Inline: False
Direct callers:
  - mm/swapfile.c:swap_range_free
```
**Symbols:**

```
ffffffff812c4a00-ffffffff812c4bc8: clear_shadow_from_swap_cache (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void clear_shadow_from_swap_cache(int type, long unsigned int begin, long unsigned int end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap_state.c (ffffffff812cb6b0)
Location: mm/swap_state.c:256
Inline: False
Direct callers:
  - mm/swapfile.c:swap_range_free
```
**Symbols:**

```
ffffffff812cb6b0-ffffffff812cb859: clear_shadow_from_swap_cache (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void clear_shadow_from_swap_cache(int type, long unsigned int begin, long unsigned int end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap_state.c (ffffffff813107a0)
Location: mm/swap_state.c:253
Inline: False
Direct callers:
  - mm/swapfile.c:swap_range_free
```
**Symbols:**

```
ffffffff813107a0-ffffffff81310976: clear_shadow_from_swap_cache (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void clear_shadow_from_swap_cache(int type, long unsigned int begin, long unsigned int end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap_state.c (ffffffff8137b4c0)
Location: mm/swap_state.c:258
Inline: False
Direct callers:
  - mm/swapfile.c:swap_range_free
```
**Symbols:**

```
ffffffff8137b4c0-ffffffff8137b6ad: clear_shadow_from_swap_cache (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void clear_shadow_from_swap_cache(int type, long unsigned int begin, long unsigned int end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap_state.c (ffffffff813f8e40)
Location: mm/swap_state.c:244
Inline: False
Direct callers:
  - mm/swapfile.c:swap_range_free
```
**Symbols:**

```
ffffffff813f8e40-ffffffff813f902d: clear_shadow_from_swap_cache (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void clear_shadow_from_swap_cache(int type, long unsigned int begin, long unsigned int end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap_state.c (ffffffff8142bc10)
Location: mm/swap_state.c:247
Inline: False
Direct callers:
  - mm/swapfile.c:swap_range_free
```
**Symbols:**

```
ffffffff8142bc10-ffffffff8142bdfb: clear_shadow_from_swap_cache (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void clear_shadow_from_swap_cache(int type, long unsigned int begin, long unsigned int end);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap_state.c (ffffffff81465370)
Location: mm/swap_state.c:247
Inline: False
Direct callers:
  - mm/swapfile.c:swap_range_free
```
**Symbols:**

```
ffffffff81465370-ffffffff8146555b: clear_shadow_from_swap_cache (STB_GLOBAL)
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
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
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
