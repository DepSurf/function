# Function: <code>ZSTD_createDStream_advanced</code>

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
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In lib/zstd/decompress.c (ffffffff814b8d94)
Location: lib/zstd/decompress.c:2191
Inline: True
Inline callers:
  - lib/zstd/decompress.c:ZSTD_initDStream
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In lib/zstd/decompress.c (ffffffff814eb690)
Location: lib/zstd/decompress.c:2191
Inline: True
Inline callers:
  - lib/zstd/decompress.c:ZSTD_initDStream
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In lib/zstd/decompress.c (ffffffff814ff3e0)
Location: lib/zstd/decompress.c:2191
Inline: True
Inline callers:
  - lib/zstd/decompress.c:ZSTD_initDStream
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In lib/zstd/decompress.c (ffffffff8152d590)
Location: lib/zstd/decompress.c:2192
Inline: True
Inline callers:
  - lib/zstd/decompress.c:ZSTD_initDStream
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In lib/zstd/decompress.c (ffffffff8154e420)
Location: lib/zstd/decompress.c:2192
Inline: True
Inline callers:
  - lib/zstd/decompress.c:ZSTD_initDStream
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In lib/zstd/decompress.c (ffffffff815d8bd0)
Location: lib/zstd/decompress.c:2192
Inline: True
Inline callers:
  - lib/zstd/decompress.c:ZSTD_initDStream
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In lib/zstd/decompress.c (ffffffff815f6805)
Location: lib/zstd/decompress.c:2192
Inline: True
Inline callers:
  - lib/zstd/decompress.c:ZSTD_initDStream
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In lib/zstd/decompress.c (ffffffff815d7f95)
Location: lib/zstd/decompress.c:2192
Inline: True
Inline callers:
  - lib/zstd/decompress.c:ZSTD_initDStream
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In lib/zstd/decompress.c (ffffffff81643245)
Location: lib/zstd/decompress.c:2192
Inline: True
Inline callers:
  - lib/zstd/decompress.c:ZSTD_initDStream
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
ZSTD_DStream *ZSTD_createDStream_advanced(ZSTD_customMem customMem);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/zstd/decompress/zstd_decompress.c (ffffffff817535c5)
Location: lib/zstd/decompress/zstd_decompress.c:1449
Inline: True
Inline callers:
  - lib/zstd/decompress/zstd_decompress.c:ZSTD_createDStream
```
**Symbols:**

```
ffffffff81753770-ffffffff81753804: ZSTD_createDStream_advanced (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
ZSTD_DStream *ZSTD_createDStream_advanced(ZSTD_customMem customMem);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/decompress/zstd_decompress.c (0)
Location: lib/zstd/decompress/zstd_decompress.c:1495
Inline: False
```
**Symbols:**

```
ffffffff81877c10-ffffffff81877ca4: ZSTD_createDStream_advanced (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
ZSTD_DStream *ZSTD_createDStream_advanced(ZSTD_customMem customMem);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/decompress/zstd_decompress.c (0)
Location: lib/zstd/decompress/zstd_decompress.c:1514
Inline: False
```
**Symbols:**

```
ffffffff818b89c0-ffffffff818b8a52: ZSTD_createDStream_advanced (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
ZSTD_DStream *ZSTD_createDStream_advanced(ZSTD_customMem customMem);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/decompress/zstd_decompress.c (0)
Location: lib/zstd/decompress/zstd_decompress.c:1514
Inline: False
```
**Symbols:**

```
ffffffff8190a580-ffffffff8190a612: ZSTD_createDStream_advanced (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In lib/zstd/decompress.c (ffff80001065a574)
Location: lib/zstd/decompress.c:2192
Inline: True
Inline callers:
  - lib/zstd/decompress.c:ZSTD_initDStream
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In lib/zstd/decompress.c (c0803b90)
Location: lib/zstd/decompress.c:2192
Inline: True
Inline callers:
  - lib/zstd/decompress.c:ZSTD_initDStream
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In lib/zstd/decompress.c (c00000000080b324)
Location: lib/zstd/decompress.c:2192
Inline: True
Inline callers:
  - lib/zstd/decompress.c:ZSTD_initDStream
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In lib/zstd/decompress.c (ffffffe000487ebe)
Location: lib/zstd/decompress.c:2192
Inline: True
Inline callers:
  - lib/zstd/decompress.c:ZSTD_initDStream
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In lib/zstd/decompress.c (ffffffff81546a00)
Location: lib/zstd/decompress.c:2192
Inline: True
Inline callers:
  - lib/zstd/decompress.c:ZSTD_initDStream
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In lib/zstd/decompress.c (ffffffff81536ce0)
Location: lib/zstd/decompress.c:2192
Inline: True
Inline callers:
  - lib/zstd/decompress.c:ZSTD_initDStream
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In lib/zstd/decompress.c (ffffffff81542740)
Location: lib/zstd/decompress.c:2192
Inline: True
Inline callers:
  - lib/zstd/decompress.c:ZSTD_initDStream
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In lib/zstd/decompress.c (ffffffff8155c570)
Location: lib/zstd/decompress.c:2192
Inline: True
Inline callers:
  - lib/zstd/decompress.c:ZSTD_initDStream
```
</details>
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
