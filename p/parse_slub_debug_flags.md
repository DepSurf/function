# Function: <code>parse_slub_debug_flags</code>

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
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
char *parse_slub_debug_flags(char *str, slab_flags_t *flags, char **slabs, bool init);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/slub.c (0)
Location: mm/slub.c:1271
Inline: False
Direct callers:
  - mm/slub.c:kmem_cache_flags
  - mm/slub.c:setup_slub_debug
```
**Symbols:**

```
ffffffff812e2e90-ffffffff812e304e: parse_slub_debug_flags (STB_LOCAL)
ffffffff81be8db7-ffffffff81be8dde: parse_slub_debug_flags.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
char *parse_slub_debug_flags(char *str, slab_flags_t *flags, char **slabs, bool init);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/slub.c (0)
Location: mm/slub.c:1283
Inline: False
Direct callers:
  - mm/slub.c:kmem_cache_flags
  - mm/slub.c:setup_slub_debug
```
**Symbols:**

```
ffffffff812ea610-ffffffff812ea7d1: parse_slub_debug_flags (STB_LOCAL)
ffffffff81bdaf16-ffffffff81bdaf3d: parse_slub_debug_flags.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
char *parse_slub_debug_flags(char *str, slab_flags_t *flags, char **slabs, bool init);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/slub.c (0)
Location: mm/slub.c:1407
Inline: False
Direct callers:
  - mm/slub.c:kmem_cache_flags
  - mm/slub.c:setup_slub_debug
```
**Symbols:**

```
ffffffff81332550-ffffffff81332711: parse_slub_debug_flags (STB_LOCAL)
ffffffff81cc0a62-ffffffff81cc0a89: parse_slub_debug_flags.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
char *parse_slub_debug_flags(char *str, slab_flags_t *flags, char **slabs, bool init);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In mm/slub.c (0)
Location: mm/slub.c:1456
Inline: False
Direct callers:
  - mm/slub.c:kmem_cache_flags
  - mm/slub.c:setup_slub_debug
```
**Symbols:**

```
ffffffff813a3a30-ffffffff813a3c22: parse_slub_debug_flags (STB_LOCAL)
ffffffff81e72f24-ffffffff81e72f4b: parse_slub_debug_flags.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
char *parse_slub_debug_flags(char *str, slab_flags_t *flags, char **slabs, bool init);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff81423900)
Location: mm/slub.c:1492
Inline: False
Direct callers:
  - mm/slub.c:kmem_cache_flags
  - mm/slub.c:setup_slub_debug
```
**Symbols:**

```
ffffffff81423900-ffffffff81423b11: parse_slub_debug_flags (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
char *parse_slub_debug_flags(char *str, slab_flags_t *flags, char **slabs, bool init);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff81458c10)
Location: mm/slub.c:1505
Inline: False
Direct callers:
  - mm/slub.c:kmem_cache_flags
  - mm/slub.c:setup_slub_debug
```
**Symbols:**

```
ffffffff81458c10-ffffffff81458df5: parse_slub_debug_flags (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
char *parse_slub_debug_flags(char *str, slab_flags_t *flags, char **slabs, bool init);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/slub.c (ffffffff81453bd0)
Location: mm/slub.c:1629
Inline: False
Direct callers:
  - mm/slub.c:kmem_cache_flags
  - mm/slub.c:setup_slub_debug
```
**Symbols:**

```
ffffffff81453bd0-ffffffff81453db5: parse_slub_debug_flags (STB_LOCAL)
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
