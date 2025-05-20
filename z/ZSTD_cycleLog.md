# Function: <code>ZSTD_cycleLog</code>

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
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In lib/zstd/compress.c (ffffffff815b1644)
Location: lib/zstd/compress.c:168
Inline: True
Inline callers:
  - lib/zstd/compress.c:ZSTD_getParams
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
In lib/zstd/compress.c (ffffffff815cc039)
Location: lib/zstd/compress.c:168
Inline: True
Inline callers:
  - lib/zstd/compress.c:ZSTD_getParams
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
U32 ZSTD_cycleLog(U32 hashLog, ZSTD_strategy strat);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/zstd/compress/zstd_compress.c (ffffffff8171175f)
Location: lib/zstd/compress/zstd_compress.c:1082
Inline: True
Inline callers:
  - lib/zstd/compress/zstd_compress.c:ZSTD_adjustCParams_internal
```
**Symbols:**

```
ffffffff817164a0-ffffffff817164c1: ZSTD_cycleLog (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
U32 ZSTD_cycleLog(U32 hashLog, ZSTD_strategy strat);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/zstd/compress/zstd_compress.c (ffffffff8180671d)
Location: lib/zstd/compress/zstd_compress.c:1199
Inline: True
Inline callers:
  - lib/zstd/compress/zstd_compress.c:ZSTD_overflowCorrectIfNeeded
  - lib/zstd/compress/zstd_compress.c:ZSTD_adjustCParams_internal
```
**Symbols:**

```
ffffffff8180a4a0-ffffffff8180a4c1: ZSTD_cycleLog (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
U32 ZSTD_cycleLog(U32 hashLog, ZSTD_strategy strat);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/zstd/compress/zstd_compress.c (ffffffff818470ed)
Location: lib/zstd/compress/zstd_compress.c:1199
Inline: True
Inline callers:
  - lib/zstd/compress/zstd_compress.c:ZSTD_overflowCorrectIfNeeded
  - lib/zstd/compress/zstd_compress.c:ZSTD_adjustCParams_internal
```
**Symbols:**

```
ffffffff8184af50-ffffffff8184af71: ZSTD_cycleLog (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
U32 ZSTD_cycleLog(U32 hashLog, ZSTD_strategy strat);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/zstd/compress/zstd_compress.c (ffffffff81898cad)
Location: lib/zstd/compress/zstd_compress.c:1199
Inline: True
Inline callers:
  - lib/zstd/compress/zstd_compress.c:ZSTD_overflowCorrectIfNeeded
  - lib/zstd/compress/zstd_compress.c:ZSTD_adjustCParams_internal
```
**Symbols:**

```
ffffffff8189cb10-ffffffff8189cb31: ZSTD_cycleLog (STB_GLOBAL)
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
