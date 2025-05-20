# Function: <code>ZSTD_optLdm_processMatchCandidate</code>

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
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In lib/zstd/compress/zstd_opt.c (ffffffff81747106)
Location: lib/zstd/compress/zstd_opt.c:895
Inline: True
Inline callers:
  - lib/zstd/compress/zstd_opt.c:ZSTD_compressBlock_opt_generic
  - lib/zstd/compress/zstd_opt.c:ZSTD_compressBlock_opt_generic
Direct callers:
  - lib/zstd/compress/zstd_opt.c:ZSTD_compressBlock_opt_generic
  - lib/zstd/compress/zstd_opt.c:ZSTD_compressBlock_opt_generic
```
**Symbols:**

```
ffffffff81744880-ffffffff8174495f: ZSTD_optLdm_processMatchCandidate.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void ZSTD_optLdm_processMatchCandidate(ZSTD_optLdm_t *optLdm, ZSTD_match_t *matches, U32 *nbMatches, U32 currPosInBlock, U32 remainingBytes);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/zstd/compress/zstd_opt.c (ffffffff8185e300)
Location: lib/zstd/compress/zstd_opt.c:987
Inline: True
Direct callers:
  - lib/zstd/compress/zstd_opt.c:ZSTD_compressBlock_opt2
  - lib/zstd/compress/zstd_opt.c:ZSTD_compressBlock_opt2
  - lib/zstd/compress/zstd_opt.c:ZSTD_compressBlock_opt0
  - lib/zstd/compress/zstd_opt.c:ZSTD_compressBlock_opt0
```
**Symbols:**

```
ffffffff8185e300-ffffffff8185e3e1: ZSTD_optLdm_processMatchCandidate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void ZSTD_optLdm_processMatchCandidate(ZSTD_optLdm_t *optLdm, ZSTD_match_t *matches, U32 *nbMatches, U32 currPosInBlock, U32 remainingBytes);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/zstd/compress/zstd_opt.c (ffffffff8189eeb0)
Location: lib/zstd/compress/zstd_opt.c:987
Inline: True
Direct callers:
  - lib/zstd/compress/zstd_opt.c:ZSTD_compressBlock_opt2
  - lib/zstd/compress/zstd_opt.c:ZSTD_compressBlock_opt2
  - lib/zstd/compress/zstd_opt.c:ZSTD_compressBlock_opt0
  - lib/zstd/compress/zstd_opt.c:ZSTD_compressBlock_opt0
```
**Symbols:**

```
ffffffff8189eeb0-ffffffff8189ef91: ZSTD_optLdm_processMatchCandidate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void ZSTD_optLdm_processMatchCandidate(ZSTD_optLdm_t *optLdm, ZSTD_match_t *matches, U32 *nbMatches, U32 currPosInBlock, U32 remainingBytes);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/zstd/compress/zstd_opt.c (ffffffff818f0a70)
Location: lib/zstd/compress/zstd_opt.c:987
Inline: True
Direct callers:
  - lib/zstd/compress/zstd_opt.c:ZSTD_compressBlock_opt2
  - lib/zstd/compress/zstd_opt.c:ZSTD_compressBlock_opt2
  - lib/zstd/compress/zstd_opt.c:ZSTD_compressBlock_opt0
  - lib/zstd/compress/zstd_opt.c:ZSTD_compressBlock_opt0
```
**Symbols:**

```
ffffffff818f0a70-ffffffff818f0b51: ZSTD_optLdm_processMatchCandidate (STB_LOCAL)
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
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
