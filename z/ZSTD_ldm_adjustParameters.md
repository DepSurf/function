# Function: <code>ZSTD_ldm_adjustParameters</code>

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
<summary>In <code>5.19</code>: ✅</summary>

```c
void ZSTD_ldm_adjustParameters(ldmParams_t *params, const ZSTD_compressionParameters *cParams);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/compress/zstd_ldm.c (ffffffff81743950)
Location: lib/zstd/compress/zstd_ldm.c:108
Inline: False
Direct callers:
  - lib/zstd/compress/zstd_compress.c:ZSTD_resetCCtx_internal
  - lib/zstd/compress/zstd_compress.c:ZSTD_makeCCtxParamsFromCParams
```
**Symbols:**

```
ffffffff81743950-ffffffff817439c1: ZSTD_ldm_adjustParameters (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void ZSTD_ldm_adjustParameters(ldmParams_t *params, const ZSTD_compressionParameters *cParams);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/compress/zstd_ldm.c (ffffffff8185d240)
Location: lib/zstd/compress/zstd_ldm.c:135
Inline: False
Direct callers:
  - lib/zstd/compress/zstd_compress.c:ZSTD_resetCCtx_internal
  - lib/zstd/compress/zstd_compress.c:ZSTD_makeCCtxParamsFromCParams
```
**Symbols:**

```
ffffffff8185d240-ffffffff8185d2b1: ZSTD_ldm_adjustParameters (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void ZSTD_ldm_adjustParameters(ldmParams_t *params, const ZSTD_compressionParameters *cParams);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/compress/zstd_ldm.c (ffffffff8189de00)
Location: lib/zstd/compress/zstd_ldm.c:135
Inline: False
Direct callers:
  - lib/zstd/compress/zstd_compress.c:ZSTD_resetCCtx_internal
  - lib/zstd/compress/zstd_compress.c:ZSTD_makeCCtxParamsFromCParams
```
**Symbols:**

```
ffffffff8189de00-ffffffff8189de71: ZSTD_ldm_adjustParameters (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void ZSTD_ldm_adjustParameters(ldmParams_t *params, const ZSTD_compressionParameters *cParams);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/compress/zstd_ldm.c (ffffffff818ef9c0)
Location: lib/zstd/compress/zstd_ldm.c:135
Inline: False
Direct callers:
  - lib/zstd/compress/zstd_compress.c:ZSTD_resetCCtx_internal
  - lib/zstd/compress/zstd_compress.c:ZSTD_makeCCtxParamsFromCParams
```
**Symbols:**

```
ffffffff818ef9c0-ffffffff818efa31: ZSTD_ldm_adjustParameters (STB_GLOBAL)
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
