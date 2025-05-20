# Function: <code>ZSTD_maxCLevel</code>

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
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int ZSTD_maxCLevel();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/compress.c (ffffffff815af440)
Location: lib/zstd/compress.c:3295
Inline: False
```
**Symbols:**

```
ffffffff815af440-ffffffff815af446: ZSTD_maxCLevel (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int ZSTD_maxCLevel();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/compress.c (ffffffff815cb0b0)
Location: lib/zstd/compress.c:3295
Inline: False
```
**Symbols:**

```
ffffffff815cb0b0-ffffffff815cb0c0: ZSTD_maxCLevel (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
int ZSTD_maxCLevel();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/zstd/compress/zstd_compress.c (ffffffff8171c790)
Location: lib/zstd/compress/zstd_compress.c:4866
Inline: True
Direct callers:
  - lib/zstd/zstd_compress_module.c:zstd_max_clevel
```
**Symbols:**

```
ffffffff8171c790-ffffffff8171c7a4: ZSTD_maxCLevel (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
int ZSTD_maxCLevel();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/zstd/compress/zstd_compress.c (ffffffff81812030)
Location: lib/zstd/compress/zstd_compress.c:5986
Inline: True
Direct callers:
  - lib/zstd/zstd_compress_module.c:zstd_max_clevel
```
**Symbols:**

```
ffffffff81812030-ffffffff81812044: ZSTD_maxCLevel (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
int ZSTD_maxCLevel();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/zstd/compress/zstd_compress.c (ffffffff81852b30)
Location: lib/zstd/compress/zstd_compress.c:5986
Inline: True
Direct callers:
  - lib/zstd/zstd_compress_module.c:zstd_max_clevel
```
**Symbols:**

```
ffffffff81852b30-ffffffff81852b44: ZSTD_maxCLevel (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
int ZSTD_maxCLevel();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/zstd/compress/zstd_compress.c (ffffffff818a46f0)
Location: lib/zstd/compress/zstd_compress.c:5986
Inline: True
Direct callers:
  - lib/zstd/zstd_compress_module.c:zstd_max_clevel
```
**Symbols:**

```
ffffffff818a46f0-ffffffff818a4704: ZSTD_maxCLevel (STB_GLOBAL)
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
No changes between <code>5.8</code> and <code>5.11</code> ✅
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
