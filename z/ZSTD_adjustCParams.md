# Function: <code>ZSTD_adjustCParams</code>

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
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
ZSTD_compressionParameters ZSTD_adjustCParams(ZSTD_compressionParameters cPar, long long unsigned int srcSize, size_t dictSize);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/zstd/compress.c (ffffffff815b14fb)
Location: lib/zstd/compress.c:180
Inline: True
Inline callers:
  - lib/zstd/compress.c:ZSTD_getParams
```
**Symbols:**

```
ffffffff815af480-ffffffff815af51f: ZSTD_adjustCParams (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
ZSTD_compressionParameters ZSTD_adjustCParams(ZSTD_compressionParameters cPar, long long unsigned int srcSize, size_t dictSize);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/zstd/compress.c (ffffffff815cbef0)
Location: lib/zstd/compress.c:180
Inline: True
Inline callers:
  - lib/zstd/compress.c:ZSTD_getParams
```
**Symbols:**

```
ffffffff815cb100-ffffffff815cb1a4: ZSTD_adjustCParams (STB_GLOBAL)
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
ZSTD_compressionParameters ZSTD_adjustCParams(ZSTD_compressionParameters cPar, long long unsigned int srcSize, size_t dictSize);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/compress/zstd_compress.c (ffffffff817164d0)
Location: lib/zstd/compress/zstd_compress.c:1190
Inline: False
```
**Symbols:**

```
ffffffff817164d0-ffffffff817166f5: ZSTD_adjustCParams (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
ZSTD_compressionParameters ZSTD_adjustCParams(ZSTD_compressionParameters cPar, long long unsigned int srcSize, size_t dictSize);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/compress/zstd_compress.c (ffffffff8180a4e0)
Location: lib/zstd/compress/zstd_compress.c:1307
Inline: False
```
**Symbols:**

```
ffffffff8180a4e0-ffffffff8180a705: ZSTD_adjustCParams (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
ZSTD_compressionParameters ZSTD_adjustCParams(ZSTD_compressionParameters cPar, long long unsigned int srcSize, size_t dictSize);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/compress/zstd_compress.c (ffffffff8184af90)
Location: lib/zstd/compress/zstd_compress.c:1307
Inline: False
```
**Symbols:**

```
ffffffff8184af90-ffffffff8184b1b5: ZSTD_adjustCParams (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
ZSTD_compressionParameters ZSTD_adjustCParams(ZSTD_compressionParameters cPar, long long unsigned int srcSize, size_t dictSize);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/compress/zstd_compress.c (ffffffff8189cb50)
Location: lib/zstd/compress/zstd_compress.c:1307
Inline: False
```
**Symbols:**

```
ffffffff8189cb50-ffffffff8189cd75: ZSTD_adjustCParams (STB_GLOBAL)
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
