# Function: <code>__xas_prev</code>

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
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void *__xas_prev(struct xa_state *xas);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/xarray.c (ffffffff81a171f0)
Location: lib/xarray.c:972
Inline: False
Direct callers:
  - mm/filemap.c:page_cache_prev_miss
```
**Symbols:**

```
ffffffff81a171f0-ffffffff81a172c0: __xas_prev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void *__xas_prev(struct xa_state *xas);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/xarray.c (ffffffff81a86e80)
Location: lib/xarray.c:991
Inline: False
Direct callers:
  - mm/filemap.c:page_cache_prev_miss
```
**Symbols:**

```
ffffffff81a86e80-ffffffff81a86f50: __xas_prev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void *__xas_prev(struct xa_state *xas);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/xarray.c (ffffffff81abe0f0)
Location: lib/xarray.c:994
Inline: False
Direct callers:
  - mm/filemap.c:page_cache_prev_miss
```
**Symbols:**

```
ffffffff81abe0f0-ffffffff81abe1c1: __xas_prev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void *__xas_prev(struct xa_state *xas);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/xarray.c (ffffffff815fa930)
Location: lib/xarray.c:994
Inline: False
Direct callers:
  - mm/filemap.c:page_cache_prev_miss
```
**Symbols:**

```
ffffffff815fa930-ffffffff815faa0b: __xas_prev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void *__xas_prev(struct xa_state *xas);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/xarray.c (ffffffff8161f130)
Location: lib/xarray.c:1144
Inline: False
Direct callers:
  - mm/filemap.c:page_cache_prev_miss
```
**Symbols:**

```
ffffffff8161f130-ffffffff8161f20b: __xas_prev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void *__xas_prev(struct xa_state *xas);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/xarray.c (ffffffff81602780)
Location: lib/xarray.c:1145
Inline: False
Direct callers:
  - mm/filemap.c:page_cache_prev_miss
```
**Symbols:**

```
ffffffff81602780-ffffffff81602852: __xas_prev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void *__xas_prev(struct xa_state *xas);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/xarray.c (0)
Location: lib/xarray.c:1145
Inline: False
Direct callers:
  - mm/filemap.c:page_cache_prev_miss
```
**Symbols:**

```
ffffffff81cdfeb9-ffffffff81cdff0d: __xas_prev.cold (STB_LOCAL)
ffffffff81670b00-ffffffff81670c51: __xas_prev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void *__xas_prev(struct xa_state *xas);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/xarray.c (0)
Location: lib/xarray.c:1152
Inline: False
Direct callers:
  - mm/filemap.c:page_cache_prev_miss
```
**Symbols:**

```
ffffffff81ea656b-ffffffff81ea65bf: __xas_prev.cold (STB_LOCAL)
ffffffff8178b2a0-ffffffff8178b3ea: __xas_prev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void *__xas_prev(struct xa_state *xas);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/xarray.c (0)
Location: lib/xarray.c:1152
Inline: False
Direct callers:
  - mm/filemap.c:page_cache_prev_miss
```
**Symbols:**

```
ffffffff820b7fb6-ffffffff820b800a: __xas_prev.cold (STB_LOCAL)
ffffffff82049750-ffffffff8204989a: __xas_prev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void *__xas_prev(struct xa_state *xas);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/xarray.c (0)
Location: lib/xarray.c:1150
Inline: False
Direct callers:
  - mm/filemap.c:page_cache_prev_miss
```
**Symbols:**

```
ffffffff821393cb-ffffffff8213941f: __xas_prev.cold (STB_LOCAL)
ffffffff820c81b0-ffffffff820c82fa: __xas_prev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void *__xas_prev(struct xa_state *xas);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/xarray.c (0)
Location: lib/xarray.c:1150
Inline: False
Direct callers:
  - mm/filemap.c:page_cache_prev_miss
```
**Symbols:**

```
ffffffff8221b170-ffffffff8221b1c4: __xas_prev.cold (STB_LOCAL)
ffffffff821a2b30-ffffffff821a2c7a: __xas_prev (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
void *__xas_prev(struct xa_state *xas);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/xarray.c (ffff800010d99360)
Location: lib/xarray.c:994
Inline: False
Direct callers:
  - mm/filemap.c:page_cache_prev_miss
```
**Symbols:**

```
ffff800010d99360-ffff800010d99460: __xas_prev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void *__xas_prev(struct xa_state *xas);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/xarray.c (c0e95ddc)
Location: lib/xarray.c:994
Inline: False
Direct callers:
  - mm/filemap.c:page_cache_prev_miss
```
**Symbols:**

```
c0e95ddc-c0e95eec: __xas_prev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void *__xas_prev(struct xa_state *xas);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/xarray.c (c000000000edf0c0)
Location: lib/xarray.c:994
Inline: False
Direct callers:
  - mm/filemap.c:page_cache_prev_miss
```
**Symbols:**

```
c000000000edf0c0-c000000000edf1d0: __xas_prev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void *__xas_prev(struct xa_state *xas);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/xarray.c (ffffffe0008c2388)
Location: lib/xarray.c:994
Inline: False
Direct callers:
  - mm/filemap.c:page_cache_prev_miss
```
**Symbols:**

```
ffffffe0008c2388-ffffffe0008c2448: __xas_prev (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
void *__xas_prev(struct xa_state *xas);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/xarray.c (ffffffff81a5cf40)
Location: lib/xarray.c:994
Inline: False
Direct callers:
  - mm/filemap.c:page_cache_prev_miss
```
**Symbols:**

```
ffffffff81a5cf40-ffffffff81a5d011: __xas_prev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void *__xas_prev(struct xa_state *xas);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/xarray.c (ffffffff81a1a010)
Location: lib/xarray.c:994
Inline: False
Direct callers:
  - mm/filemap.c:page_cache_prev_miss
```
**Symbols:**

```
ffffffff81a1a010-ffffffff81a1a0e1: __xas_prev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void *__xas_prev(struct xa_state *xas);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/xarray.c (ffffffff81ac9330)
Location: lib/xarray.c:994
Inline: False
Direct callers:
  - mm/filemap.c:page_cache_prev_miss
```
**Symbols:**

```
ffffffff81ac9330-ffffffff81ac9401: __xas_prev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void *__xas_prev(struct xa_state *xas);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/xarray.c (ffffffff81ad5800)
Location: lib/xarray.c:994
Inline: False
Direct callers:
  - mm/filemap.c:page_cache_prev_miss
```
**Symbols:**

```
ffffffff81ad5800-ffffffff81ad58d1: __xas_prev (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
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
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
