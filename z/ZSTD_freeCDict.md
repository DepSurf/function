# Function: <code>ZSTD_freeCDict</code>

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
size_t ZSTD_freeCDict(ZSTD_CDict *cdict);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/compress.c (ffffffff815cbdb0)
Location: lib/zstd/compress.c:2899
Inline: False
Direct callers:
  - lib/zstd/compress.c:ZSTD_freeCStream
```
**Symbols:**

```
ffffffff815cbdb0-ffffffff815cbe6d: ZSTD_freeCDict (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
size_t ZSTD_freeCDict(ZSTD_CDict *cdict);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/compress.c (ffffffff815e98d0)
Location: lib/zstd/compress.c:2899
Inline: False
Direct callers:
  - lib/zstd/compress.c:ZSTD_freeCStream
```
**Symbols:**

```
ffffffff815e98d0-ffffffff815e9992: ZSTD_freeCDict (STB_GLOBAL)
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
<summary>In <code>5.19</code>: ✅</summary>

```c
size_t ZSTD_freeCDict(ZSTD_CDict *cdict);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/compress/zstd_compress.c (ffffffff8171a120)
Location: lib/zstd/compress/zstd_compress.c:3758
Inline: False
Direct callers:
  - lib/zstd/compress/zstd_compress.c:ZSTD_createCDict_advanced2
  - lib/zstd/compress/zstd_compress.c:ZSTD_clearAllDicts
```
**Symbols:**

```
ffffffff8171a120-ffffffff8171a245: ZSTD_freeCDict (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
size_t ZSTD_freeCDict(ZSTD_CDict *cdict);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/compress/zstd_compress.c (ffffffff8180f780)
Location: lib/zstd/compress/zstd_compress.c:4847
Inline: False
Direct callers:
  - lib/zstd/compress/zstd_compress.c:ZSTD_createCDict_advanced2
  - lib/zstd/compress/zstd_compress.c:ZSTD_clearAllDicts
```
**Symbols:**

```
ffffffff8180f780-ffffffff8180f8a5: ZSTD_freeCDict (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
size_t ZSTD_freeCDict(ZSTD_CDict *cdict);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/compress/zstd_compress.c (ffffffff81850270)
Location: lib/zstd/compress/zstd_compress.c:4847
Inline: False
Direct callers:
  - lib/zstd/compress/zstd_compress.c:ZSTD_createCDict_advanced2
  - lib/zstd/compress/zstd_compress.c:ZSTD_clearAllDicts
```
**Symbols:**

```
ffffffff81850270-ffffffff81850393: ZSTD_freeCDict (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
size_t ZSTD_freeCDict(ZSTD_CDict *cdict);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/compress/zstd_compress.c (ffffffff818a1e30)
Location: lib/zstd/compress/zstd_compress.c:4847
Inline: False
Direct callers:
  - lib/zstd/compress/zstd_compress.c:ZSTD_createCDict_advanced2
  - lib/zstd/compress/zstd_compress.c:ZSTD_clearAllDicts
```
**Symbols:**

```
ffffffff818a1e30-ffffffff818a1f53: ZSTD_freeCDict (STB_GLOBAL)
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
