# Function: <code>ZSTD_freeCStream</code>

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
size_t ZSTD_freeCStream(ZSTD_CStream *zcs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/compress.c (ffffffff815cbe70)
Location: lib/zstd/compress.c:3002
Inline: False
Direct callers:
  - lib/zstd/compress.c:ZSTD_createCStream_advanced
```
**Symbols:**

```
ffffffff815cbe70-ffffffff815cbf6e: ZSTD_freeCStream (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
size_t ZSTD_freeCStream(ZSTD_CStream *zcs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/compress.c (ffffffff815e99a0)
Location: lib/zstd/compress.c:3002
Inline: False
Direct callers:
  - lib/zstd/compress.c:ZSTD_createCStream_advanced
```
**Symbols:**

```
ffffffff815e99a0-ffffffff815e9aa3: ZSTD_freeCStream (STB_GLOBAL)
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
size_t ZSTD_freeCStream(ZSTD_CStream *zcs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/compress/zstd_compress.c (ffffffff8171bc00)
Location: lib/zstd/compress/zstd_compress.c:3937
Inline: False
```
**Symbols:**

```
ffffffff8171bc00-ffffffff8171bc16: ZSTD_freeCStream (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
size_t ZSTD_freeCStream(ZSTD_CStream *zcs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/compress/zstd_compress.c (ffffffff81811370)
Location: lib/zstd/compress/zstd_compress.c:5053
Inline: False
```
**Symbols:**

```
ffffffff81811370-ffffffff81811386: ZSTD_freeCStream (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
size_t ZSTD_freeCStream(ZSTD_CStream *zcs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/compress/zstd_compress.c (ffffffff81851e50)
Location: lib/zstd/compress/zstd_compress.c:5053
Inline: False
```
**Symbols:**

```
ffffffff81851e50-ffffffff81851e66: ZSTD_freeCStream (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
size_t ZSTD_freeCStream(ZSTD_CStream *zcs);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/compress/zstd_compress.c (ffffffff818a3a10)
Location: lib/zstd/compress/zstd_compress.c:5053
Inline: False
```
**Symbols:**

```
ffffffff818a3a10-ffffffff818a3a26: ZSTD_freeCStream (STB_GLOBAL)
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
