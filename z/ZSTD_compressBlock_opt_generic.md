# Function: <code>ZSTD_compressBlock_opt_generic</code>

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
In lib/zstd/compress.c (ffffffff815c4cb3)
Location: lib/zstd/zstd_opt.h:407
Inline: True
Inline callers:
  - lib/zstd/compress.c:ZSTD_compressBlock_btopt2
  - lib/zstd/compress.c:ZSTD_compressBlock_btopt
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
In lib/zstd/compress.c (ffffffff815dd628)
Location: lib/zstd/zstd_opt.h:407
Inline: True
Inline callers:
  - lib/zstd/compress.c:ZSTD_compressBlock_btopt2
  - lib/zstd/compress.c:ZSTD_compressBlock_btopt
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
size_t ZSTD_compressBlock_opt_generic(ZSTD_matchState_t *ms, seqStore_t *seqStore, U32 *rep, const void *src, size_t srcSize, const int optLevel, const ZSTD_dictMode_e dictMode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/compress/zstd_opt.c (ffffffff81746ed0)
Location: lib/zstd/compress/zstd_opt.c:943
Inline: False
Direct callers:
  - lib/zstd/compress/zstd_opt.c:ZSTD_compressBlock_btultra_extDict
  - lib/zstd/compress/zstd_opt.c:ZSTD_compressBlock_btopt_extDict
  - lib/zstd/compress/zstd_opt.c:ZSTD_compressBlock_btultra_dictMatchState
  - lib/zstd/compress/zstd_opt.c:ZSTD_compressBlock_btopt_dictMatchState
  - lib/zstd/compress/zstd_opt.c:ZSTD_compressBlock_btultra2
  - lib/zstd/compress/zstd_opt.c:ZSTD_compressBlock_btultra2
  - lib/zstd/compress/zstd_opt.c:ZSTD_compressBlock_btultra
  - lib/zstd/compress/zstd_opt.c:ZSTD_compressBlock_btopt
```
**Symbols:**

```
ffffffff81746ed0-ffffffff8174813d: ZSTD_compressBlock_opt_generic (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In lib/zstd/compress/zstd_opt.c (ffffffff8185edeb)
Location: lib/zstd/compress/zstd_opt.c:1037
Inline: True
Inline callers:
  - lib/zstd/compress/zstd_opt.c:ZSTD_compressBlock_opt2
  - lib/zstd/compress/zstd_opt.c:ZSTD_compressBlock_opt0
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In lib/zstd/compress/zstd_opt.c (ffffffff8189f900)
Location: lib/zstd/compress/zstd_opt.c:1037
Inline: True
Inline callers:
  - lib/zstd/compress/zstd_opt.c:ZSTD_compressBlock_opt2
  - lib/zstd/compress/zstd_opt.c:ZSTD_compressBlock_opt0
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In lib/zstd/compress/zstd_opt.c (ffffffff818f14c0)
Location: lib/zstd/compress/zstd_opt.c:1037
Inline: True
Inline callers:
  - lib/zstd/compress/zstd_opt.c:ZSTD_compressBlock_opt2
  - lib/zstd/compress/zstd_opt.c:ZSTD_compressBlock_opt0
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
</ul>
