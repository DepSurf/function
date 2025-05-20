# Function: <code>ZSTD_crossEntropyCost</code>

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
In <code>5.15</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
size_t ZSTD_crossEntropyCost(const short int *norm, unsigned int accuracyLog, const unsigned int *count, const unsigned int max);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/zstd/compress/zstd_compress_sequences.c (0)
Location: lib/zstd/compress/zstd_compress_sequences.c:137
Inline: False
Direct callers:
  - lib/zstd/compress/zstd_compress_sequences.c:ZSTD_selectEncodingType
```
**Symbols:**

```
ffffffff81e98a32-ffffffff81e98a65: ZSTD_crossEntropyCost.cold (STB_LOCAL)
ffffffff8171f190-ffffffff8171f255: ZSTD_crossEntropyCost (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
size_t ZSTD_crossEntropyCost(const short int *norm, unsigned int accuracyLog, const unsigned int *count, const unsigned int max);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/zstd/compress/zstd_compress_sequences.c (0)
Location: lib/zstd/compress/zstd_compress_sequences.c:139
Inline: False
Direct callers:
  - lib/zstd/compress/zstd_compress_sequences.c:ZSTD_selectEncodingType
```
**Symbols:**

```
ffffffff8207f725-ffffffff8207f758: ZSTD_crossEntropyCost.cold (STB_LOCAL)
ffffffff81814aa0-ffffffff81814b65: ZSTD_crossEntropyCost (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
size_t ZSTD_crossEntropyCost(const short int *norm, unsigned int accuracyLog, const unsigned int *count, const unsigned int max);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/zstd/compress/zstd_compress_sequences.c (0)
Location: lib/zstd/compress/zstd_compress_sequences.c:139
Inline: False
Direct callers:
  - lib/zstd/compress/zstd_compress_sequences.c:ZSTD_selectEncodingType
```
**Symbols:**

```
ffffffff820ffa26-ffffffff820ffa59: ZSTD_crossEntropyCost.cold (STB_LOCAL)
ffffffff818551a0-ffffffff81855265: ZSTD_crossEntropyCost (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
size_t ZSTD_crossEntropyCost(const short int *norm, unsigned int accuracyLog, const unsigned int *count, const unsigned int max);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/zstd/compress/zstd_compress_sequences.c (0)
Location: lib/zstd/compress/zstd_compress_sequences.c:139
Inline: False
Direct callers:
  - lib/zstd/compress/zstd_compress_sequences.c:ZSTD_selectEncodingType
```
**Symbols:**

```
ffffffff821ddb93-ffffffff821ddbc6: ZSTD_crossEntropyCost.cold (STB_LOCAL)
ffffffff818a6d60-ffffffff818a6e25: ZSTD_crossEntropyCost (STB_GLOBAL)
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
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
