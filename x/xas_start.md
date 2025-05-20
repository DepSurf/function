# Function: <code>xas_start</code>

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
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void *xas_start(struct xa_state *xas);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/xarray.c (ffffffff81a170e0)
Location: lib/xarray.c:173
Inline: True
Direct callers:
  - lib/xarray.c:xa_get_mark
  - lib/xarray.c:xas_find_conflict
  - lib/xarray.c:xas_load
```
**Symbols:**

```
ffffffff81a170e0-ffffffff81a17164: xas_start (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void *xas_start(struct xa_state *xas);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/xarray.c (ffffffff81a86d70)
Location: lib/xarray.c:178
Inline: True
Direct callers:
  - lib/xarray.c:xa_get_mark
  - lib/xarray.c:xas_find_conflict
  - lib/xarray.c:xas_load
```
**Symbols:**

```
ffffffff81a86d70-ffffffff81a86df4: xas_start (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void *xas_start(struct xa_state *xas);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/xarray.c (ffffffff81abdfe0)
Location: lib/xarray.c:179
Inline: True
Direct callers:
  - lib/xarray.c:xa_get_mark
  - lib/xarray.c:xas_find_conflict
  - lib/xarray.c:xas_load
```
**Symbols:**

```
ffffffff81abdfe0-ffffffff81abe064: xas_start (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void *xas_start(struct xa_state *xas);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/xarray.c (ffffffff815f9b10)
Location: lib/xarray.c:179
Inline: False
Direct callers:
  - lib/xarray.c:xa_get_mark
  - lib/xarray.c:xas_find_conflict
  - lib/xarray.c:xas_load
```
**Symbols:**

```
ffffffff815f9b10-ffffffff815f9b95: xas_start (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void *xas_start(struct xa_state *xas);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/xarray.c (ffffffff8161e1d0)
Location: lib/xarray.c:179
Inline: False
Direct callers:
  - lib/xarray.c:xa_get_mark
  - lib/xarray.c:xas_find_conflict
  - lib/xarray.c:xas_load
```
**Symbols:**

```
ffffffff8161e1d0-ffffffff8161e293: xas_start (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void *xas_start(struct xa_state *xas);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/xarray.c (ffffffff81601b20)
Location: lib/xarray.c:179
Inline: False
Direct callers:
  - lib/xarray.c:xa_get_mark
  - lib/xarray.c:xas_find_conflict
  - lib/xarray.c:xas_load
```
**Symbols:**

```
ffffffff81601b20-ffffffff81601bd4: xas_start (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void *xas_start(struct xa_state *xas);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/xarray.c (0)
Location: lib/xarray.c:179
Inline: False
Direct callers:
  - lib/xarray.c:xa_get_mark
  - lib/xarray.c:xas_find_conflict
  - lib/xarray.c:xas_load
```
**Symbols:**

```
ffffffff8166fb40-ffffffff8166fc52: xas_start (STB_LOCAL)
ffffffff81cdfc25-ffffffff81cdfc69: xas_start.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void *xas_start(struct xa_state *xas);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/xarray.c (0)
Location: lib/xarray.c:179
Inline: False
Direct callers:
  - lib/xarray.c:xa_get_mark
  - lib/xarray.c:xa_load
  - lib/xarray.c:xas_find_conflict
```
**Symbols:**

```
ffffffff8178a070-ffffffff8178a1a1: xas_start (STB_LOCAL)
ffffffff81ea63f7-ffffffff81ea643b: xas_start.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void *xas_start(struct xa_state *xas);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/xarray.c (0)
Location: lib/xarray.c:179
Inline: False
Direct callers:
  - lib/xarray.c:xa_get_mark
  - lib/xarray.c:xa_load
  - lib/xarray.c:xas_find_conflict
```
**Symbols:**

```
ffffffff820474b0-ffffffff820475dc: xas_start (STB_LOCAL)
ffffffff820b7c7d-ffffffff820b7cc1: xas_start.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void *xas_start(struct xa_state *xas);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/xarray.c (0)
Location: lib/xarray.c:181
Inline: False
Direct callers:
  - lib/xarray.c:xa_get_mark
  - lib/xarray.c:xa_load
  - lib/xarray.c:xas_find_conflict
```
**Symbols:**

```
ffffffff820c5b40-ffffffff820c5c6c: xas_start (STB_LOCAL)
ffffffff821390f0-ffffffff8213912a: xas_start.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void *xas_start(struct xa_state *xas);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/xarray.c (0)
Location: lib/xarray.c:181
Inline: False
Direct callers:
  - lib/xarray.c:xa_get_mark
  - lib/xarray.c:xa_load
  - lib/xarray.c:xas_find_conflict
```
**Symbols:**

```
ffffffff821a04c0-ffffffff821a05ec: xas_start (STB_LOCAL)
ffffffff8221ae95-ffffffff8221aecf: xas_start.cold (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
void *xas_start(struct xa_state *xas);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/xarray.c (ffff800010d99238)
Location: lib/xarray.c:179
Inline: True
Direct callers:
  - lib/xarray.c:xa_get_mark
  - lib/xarray.c:xas_find_conflict
  - lib/xarray.c:xas_load
```
**Symbols:**

```
ffff800010d99238-ffff800010d992cc: xas_start (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void *xas_start(struct xa_state *xas);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/xarray.c (c0e95c9c)
Location: lib/xarray.c:179
Inline: True
Direct callers:
  - lib/xarray.c:xa_get_mark
  - lib/xarray.c:xas_find_conflict
  - lib/xarray.c:xas_load
```
**Symbols:**

```
c0e95c9c-c0e95d68: xas_start (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void *xas_start(struct xa_state *xas);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/xarray.c (c000000000edef20)
Location: lib/xarray.c:179
Inline: True
Direct callers:
  - lib/xarray.c:xa_get_mark
  - lib/xarray.c:xas_find_conflict
  - lib/xarray.c:xas_load
```
**Symbols:**

```
c000000000edef20-c000000000edeff0: xas_start (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void *xas_start(struct xa_state *xas);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/xarray.c (ffffffe0008c229a)
Location: lib/xarray.c:179
Inline: True
Direct callers:
  - lib/xarray.c:xa_get_mark
  - lib/xarray.c:xas_find_conflict
  - lib/xarray.c:xas_load
```
**Symbols:**

```
ffffffe0008c229a-ffffffe0008c231e: xas_start (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
void *xas_start(struct xa_state *xas);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/xarray.c (ffffffff81a5ce30)
Location: lib/xarray.c:179
Inline: True
Direct callers:
  - lib/xarray.c:xa_get_mark
  - lib/xarray.c:xas_find_conflict
  - lib/xarray.c:xas_load
```
**Symbols:**

```
ffffffff81a5ce30-ffffffff81a5ceb4: xas_start (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void *xas_start(struct xa_state *xas);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/xarray.c (ffffffff81a19f00)
Location: lib/xarray.c:179
Inline: True
Direct callers:
  - lib/xarray.c:xa_get_mark
  - lib/xarray.c:xas_find_conflict
  - lib/xarray.c:xas_load
```
**Symbols:**

```
ffffffff81a19f00-ffffffff81a19f84: xas_start (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void *xas_start(struct xa_state *xas);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/xarray.c (ffffffff81ac9220)
Location: lib/xarray.c:179
Inline: True
Direct callers:
  - lib/xarray.c:xa_get_mark
  - lib/xarray.c:xas_find_conflict
  - lib/xarray.c:xas_load
```
**Symbols:**

```
ffffffff81ac9220-ffffffff81ac92a4: xas_start (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void *xas_start(struct xa_state *xas);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/xarray.c (ffffffff81ad56f0)
Location: lib/xarray.c:179
Inline: True
Direct callers:
  - lib/xarray.c:xa_get_mark
  - lib/xarray.c:xas_find_conflict
  - lib/xarray.c:xas_load
```
**Symbols:**

```
ffffffff81ad56f0-ffffffff81ad5774: xas_start (STB_LOCAL)
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
