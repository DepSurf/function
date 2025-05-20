# Function: <code>nested_table_free</code>

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
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void nested_table_free(union nested_table *ntbl, unsigned int size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/rhashtable.c (ffffffff8146b1d0)
Location: lib/rhashtable.c:104
Inline: False
Direct callers:
  - lib/rhashtable.c:bucket_table_free
  - lib/rhashtable.c:nested_table_free
```
**Symbols:**

```
ffffffff8146b1d0-ffffffff8146b220: nested_table_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void nested_table_free(union nested_table *ntbl, unsigned int size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/rhashtable.c (ffffffff814974c0)
Location: lib/rhashtable.c:104
Inline: False
Direct callers:
  - lib/rhashtable.c:bucket_table_free
  - lib/rhashtable.c:nested_table_free
```
**Symbols:**

```
ffffffff814974c0-ffffffff81497510: nested_table_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void nested_table_free(union nested_table *ntbl, unsigned int size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/rhashtable.c (ffffffff814cc380)
Location: lib/rhashtable.c:68
Inline: False
Direct callers:
  - lib/rhashtable.c:bucket_table_free
  - lib/rhashtable.c:nested_table_free
```
**Symbols:**

```
ffffffff814cc380-ffffffff814cc3d0: nested_table_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void nested_table_free(union nested_table *ntbl, unsigned int size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/rhashtable.c (ffffffff814e07b0)
Location: lib/rhashtable.c:68
Inline: False
Direct callers:
  - lib/rhashtable.c:bucket_table_free
  - lib/rhashtable.c:nested_table_free
```
**Symbols:**

```
ffffffff814e07b0-ffffffff814e0800: nested_table_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void nested_table_free(union nested_table *ntbl, unsigned int size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/rhashtable.c (ffffffff8150c7c0)
Location: lib/rhashtable.c:66
Inline: False
Direct callers:
  - lib/rhashtable.c:bucket_table_free
  - lib/rhashtable.c:nested_table_free
```
**Symbols:**

```
ffffffff8150c7c0-ffffffff8150c811: nested_table_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void nested_table_free(union nested_table *ntbl, unsigned int size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/rhashtable.c (ffffffff8152a610)
Location: lib/rhashtable.c:66
Inline: False
Direct callers:
  - lib/rhashtable.c:bucket_table_free
  - lib/rhashtable.c:nested_table_free
```
**Symbols:**

```
ffffffff8152a610-ffffffff8152a661: nested_table_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In lib/rhashtable.c (ffffffff8158e5d0)
Location: lib/rhashtable.c:75
Inline: True
Direct callers:
  - lib/rhashtable.c:bucket_table_free
```
**Symbols:**

```
ffffffff8158e5d0-ffffffff8158e6b4: nested_table_free.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In lib/rhashtable.c (ffffffff815ab140)
Location: lib/rhashtable.c:75
Inline: True
Direct callers:
  - lib/rhashtable.c:bucket_table_free
```
**Symbols:**

```
ffffffff815ab140-ffffffff815ab224: nested_table_free.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In lib/rhashtable.c (ffffffff815b62fc)
Location: lib/rhashtable.c:75
Inline: True
Inline callers:
  - lib/rhashtable.c:bucket_table_free
Direct callers:
  - lib/rhashtable.c:bucket_table_free
```
**Symbols:**

```
ffffffff815b61a0-ffffffff815b6284: nested_table_free.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In lib/rhashtable.c (ffffffff8161c82a)
Location: lib/rhashtable.c:75
Inline: True
Inline callers:
  - lib/rhashtable.c:bucket_table_free
Direct callers:
  - lib/rhashtable.c:bucket_table_free
```
**Symbols:**

```
ffffffff8161c6c0-ffffffff8161c7a4: nested_table_free.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In lib/rhashtable.c (ffffffff816ea048)
Location: lib/rhashtable.c:75
Inline: True
Inline callers:
  - lib/rhashtable.c:bucket_table_free
Direct callers:
  - lib/rhashtable.c:bucket_table_free
```
**Symbols:**

```
ffffffff816e9ec0-ffffffff816e9fbd: nested_table_free.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In lib/rhashtable.c (ffffffff817da258)
Location: lib/rhashtable.c:75
Inline: True
Inline callers:
  - lib/rhashtable.c:bucket_table_free
Direct callers:
  - lib/rhashtable.c:bucket_table_free
```
**Symbols:**

```
ffffffff817da0c0-ffffffff817da1bd: nested_table_free.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In lib/rhashtable.c (ffffffff818195e8)
Location: lib/rhashtable.c:75
Inline: True
Inline callers:
  - lib/rhashtable.c:bucket_table_free
Direct callers:
  - lib/rhashtable.c:bucket_table_free
```
**Symbols:**

```
ffffffff81819440-ffffffff81819545: nested_table_free.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In lib/rhashtable.c (ffffffff8185e938)
Location: lib/rhashtable.c:75
Inline: True
Inline callers:
  - lib/rhashtable.c:bucket_table_free
Direct callers:
  - lib/rhashtable.c:bucket_table_free
```
**Symbols:**

```
ffffffff8185e790-ffffffff8185e895: nested_table_free.isra.0 (STB_LOCAL)
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
void nested_table_free(union nested_table *ntbl, unsigned int size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/rhashtable.c (ffff800010635a98)
Location: lib/rhashtable.c:66
Inline: False
Direct callers:
  - lib/rhashtable.c:bucket_table_free
  - lib/rhashtable.c:nested_table_free
```
**Symbols:**

```
ffff800010635a98-ffff800010635af8: nested_table_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void nested_table_free(union nested_table *ntbl, unsigned int size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/rhashtable.c (c07db9b0)
Location: lib/rhashtable.c:66
Inline: False
Direct callers:
  - lib/rhashtable.c:bucket_table_free
  - lib/rhashtable.c:nested_table_free
```
**Symbols:**

```
c07db9b0-c07dba00: nested_table_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void nested_table_free(union nested_table *ntbl, unsigned int size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/rhashtable.c (c0000000007db500)
Location: lib/rhashtable.c:66
Inline: False
Direct callers:
  - lib/rhashtable.c:bucket_table_free
  - lib/rhashtable.c:nested_table_free
```
**Symbols:**

```
c0000000007db500-c0000000007db594: nested_table_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void nested_table_free(union nested_table *ntbl, unsigned int size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/rhashtable.c (ffffffe00046325e)
Location: lib/rhashtable.c:66
Inline: False
Direct callers:
  - lib/rhashtable.c:bucket_table_free
  - lib/rhashtable.c:nested_table_free
```
**Symbols:**

```
ffffffe00046325e-ffffffe0004632b0: nested_table_free (STB_LOCAL)
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
void nested_table_free(union nested_table *ntbl, unsigned int size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/rhashtable.c (ffffffff81522bf0)
Location: lib/rhashtable.c:66
Inline: False
Direct callers:
  - lib/rhashtable.c:bucket_table_free
  - lib/rhashtable.c:nested_table_free
```
**Symbols:**

```
ffffffff81522bf0-ffffffff81522c41: nested_table_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void nested_table_free(union nested_table *ntbl, unsigned int size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/rhashtable.c (ffffffff81512ed0)
Location: lib/rhashtable.c:66
Inline: False
Direct callers:
  - lib/rhashtable.c:bucket_table_free
  - lib/rhashtable.c:nested_table_free
```
**Symbols:**

```
ffffffff81512ed0-ffffffff81512f21: nested_table_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void nested_table_free(union nested_table *ntbl, unsigned int size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/rhashtable.c (ffffffff8151ec80)
Location: lib/rhashtable.c:66
Inline: False
Direct callers:
  - lib/rhashtable.c:bucket_table_free
  - lib/rhashtable.c:nested_table_free
```
**Symbols:**

```
ffffffff8151ec80-ffffffff8151ecd1: nested_table_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void nested_table_free(union nested_table *ntbl, unsigned int size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/rhashtable.c (ffffffff81538620)
Location: lib/rhashtable.c:66
Inline: False
Direct callers:
  - lib/rhashtable.c:bucket_table_free
  - lib/rhashtable.c:nested_table_free
```
**Symbols:**

```
ffffffff81538620-ffffffff81538671: nested_table_free (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
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
