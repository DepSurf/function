# Function: <code>get_shadow_from_swap_cache</code>

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
void *get_shadow_from_swap_cache(swp_entry_t entry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap_state.c (ffffffff812c4370)
Location: mm/swap_state.c:110
Inline: False
Direct callers:
  - mm/memory.c:do_swap_page
```
**Symbols:**

```
ffffffff812c4370-ffffffff812c4402: get_shadow_from_swap_cache (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void *get_shadow_from_swap_cache(swp_entry_t entry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap_state.c (ffffffff812cb040)
Location: mm/swap_state.c:84
Inline: False
Direct callers:
  - mm/memory.c:do_swap_page
```
**Symbols:**

```
ffffffff812cb040-ffffffff812cb085: get_shadow_from_swap_cache (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void *get_shadow_from_swap_cache(swp_entry_t entry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap_state.c (ffffffff81310000)
Location: mm/swap_state.c:84
Inline: False
Direct callers:
  - mm/memory.c:do_swap_page
```
**Symbols:**

```
ffffffff81310000-ffffffff8131006a: get_shadow_from_swap_cache (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void *get_shadow_from_swap_cache(swp_entry_t entry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap_state.c (ffffffff8137aa10)
Location: mm/swap_state.c:85
Inline: False
Direct callers:
  - mm/memory.c:do_swap_page
```
**Symbols:**

```
ffffffff8137aa10-ffffffff8137aa84: get_shadow_from_swap_cache (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void *get_shadow_from_swap_cache(swp_entry_t entry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap_state.c (ffffffff813f85c0)
Location: mm/swap_state.c:72
Inline: False
Direct callers:
  - mm/memory.c:do_swap_page
```
**Symbols:**

```
ffffffff813f85c0-ffffffff813f8634: get_shadow_from_swap_cache (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void *get_shadow_from_swap_cache(swp_entry_t entry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap_state.c (ffffffff8142b380)
Location: mm/swap_state.c:71
Inline: False
Direct callers:
  - mm/filemap.c:filemap_cachestat
  - mm/memory.c:do_swap_page
```
**Symbols:**

```
ffffffff8142b380-ffffffff8142b3f4: get_shadow_from_swap_cache (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void *get_shadow_from_swap_cache(swp_entry_t entry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/swap_state.c (ffffffff81464b70)
Location: mm/swap_state.c:71
Inline: False
Direct callers:
  - mm/filemap.c:filemap_cachestat
  - mm/memory.c:do_swap_page
```
**Symbols:**

```
ffffffff81464b70-ffffffff81464be4: get_shadow_from_swap_cache (STB_GLOBAL)
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
