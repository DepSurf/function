# Function: <code>ZSTD_cParam_getBounds</code>

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
ZSTD_bounds ZSTD_cParam_getBounds(ZSTD_cParameter param);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/compress/zstd_compress.c (ffffffff817155a0)
Location: lib/zstd/compress/zstd_compress.c:304
Inline: False
Direct callers:
  - lib/zstd/compress/zstd_compress.c:ZSTD_adjustCParams
  - lib/zstd/compress/zstd_compress.c:ZSTD_adjustCParams
  - lib/zstd/compress/zstd_compress.c:ZSTD_adjustCParams
  - lib/zstd/compress/zstd_compress.c:ZSTD_adjustCParams
  - lib/zstd/compress/zstd_compress.c:ZSTD_adjustCParams
  - lib/zstd/compress/zstd_compress.c:ZSTD_adjustCParams
  - lib/zstd/compress/zstd_compress.c:ZSTD_adjustCParams
  - lib/zstd/compress/zstd_compress.c:ZSTD_checkCParams
  - lib/zstd/compress/zstd_compress.c:ZSTD_checkCParams
  - lib/zstd/compress/zstd_compress.c:ZSTD_checkCParams
  - lib/zstd/compress/zstd_compress.c:ZSTD_checkCParams
  - lib/zstd/compress/zstd_compress.c:ZSTD_checkCParams
  - lib/zstd/compress/zstd_compress.c:ZSTD_checkCParams
  - lib/zstd/compress/zstd_compress.c:ZSTD_checkCParams
  - lib/zstd/compress/zstd_compress.c:ZSTD_CCtxParams_setParameter
  - lib/zstd/compress/zstd_compress.c:ZSTD_CCtxParams_setParameter
  - lib/zstd/compress/zstd_compress.c:ZSTD_CCtxParams_setParameter
  - lib/zstd/compress/zstd_compress.c:ZSTD_CCtxParams_setParameter
  - lib/zstd/compress/zstd_compress.c:ZSTD_CCtxParams_setParameter
  - lib/zstd/compress/zstd_compress.c:ZSTD_CCtxParams_setParameter
  - lib/zstd/compress/zstd_compress.c:ZSTD_CCtxParams_setParameter
  - lib/zstd/compress/zstd_compress.c:ZSTD_CCtxParams_setParameter
  - lib/zstd/compress/zstd_compress.c:ZSTD_CCtxParams_setParameter
  - lib/zstd/compress/zstd_compress.c:ZSTD_CCtxParams_setParameter
  - lib/zstd/compress/zstd_compress.c:ZSTD_CCtxParams_setParameter
  - lib/zstd/compress/zstd_compress.c:ZSTD_CCtxParams_setParameter
  - lib/zstd/compress/zstd_compress.c:ZSTD_CCtxParams_setParameter
  - lib/zstd/compress/zstd_compress.c:ZSTD_CCtxParams_setParameter
  - lib/zstd/compress/zstd_compress.c:ZSTD_CCtxParams_setParameter
  - lib/zstd/compress/zstd_compress.c:ZSTD_CCtxParams_setParameter
  - lib/zstd/compress/zstd_compress.c:ZSTD_CCtxParams_setParameter
  - lib/zstd/compress/zstd_compress.c:ZSTD_CCtxParams_setParameter
  - lib/zstd/compress/zstd_compress.c:ZSTD_CCtxParams_setParameter
  - lib/zstd/compress/zstd_compress.c:ZSTD_CCtxParams_setParameter
  - lib/zstd/compress/zstd_compress.c:ZSTD_CCtxParams_setParameter
```
**Symbols:**

```
ffffffff817155a0-ffffffff817157e0: ZSTD_cParam_getBounds (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
ZSTD_bounds ZSTD_cParam_getBounds(ZSTD_cParameter param);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/compress/zstd_compress.c (ffffffff81809420)
Location: lib/zstd/compress/zstd_compress.c:376
Inline: False
Direct callers:
  - lib/zstd/compress/zstd_compress.c:ZSTD_adjustCParams
  - lib/zstd/compress/zstd_compress.c:ZSTD_adjustCParams
  - lib/zstd/compress/zstd_compress.c:ZSTD_adjustCParams
  - lib/zstd/compress/zstd_compress.c:ZSTD_adjustCParams
  - lib/zstd/compress/zstd_compress.c:ZSTD_adjustCParams
  - lib/zstd/compress/zstd_compress.c:ZSTD_adjustCParams
  - lib/zstd/compress/zstd_compress.c:ZSTD_adjustCParams
  - lib/zstd/compress/zstd_compress.c:ZSTD_checkCParams
  - lib/zstd/compress/zstd_compress.c:ZSTD_checkCParams
  - lib/zstd/compress/zstd_compress.c:ZSTD_checkCParams
  - lib/zstd/compress/zstd_compress.c:ZSTD_checkCParams
  - lib/zstd/compress/zstd_compress.c:ZSTD_checkCParams
  - lib/zstd/compress/zstd_compress.c:ZSTD_checkCParams
  - lib/zstd/compress/zstd_compress.c:ZSTD_checkCParams
  - lib/zstd/compress/zstd_compress.c:ZSTD_CCtxParams_setParameter
  - lib/zstd/compress/zstd_compress.c:ZSTD_CCtxParams_setParameter
  - lib/zstd/compress/zstd_compress.c:ZSTD_CCtxParams_setParameter
  - lib/zstd/compress/zstd_compress.c:ZSTD_CCtxParams_setParameter
  - lib/zstd/compress/zstd_compress.c:ZSTD_CCtxParams_setParameter
  - lib/zstd/compress/zstd_compress.c:ZSTD_CCtxParams_setParameter
  - lib/zstd/compress/zstd_compress.c:ZSTD_CCtxParams_setParameter
  - lib/zstd/compress/zstd_compress.c:ZSTD_CCtxParams_setParameter
  - lib/zstd/compress/zstd_compress.c:ZSTD_CCtxParams_setParameter
  - lib/zstd/compress/zstd_compress.c:ZSTD_CCtxParams_setParameter
  - lib/zstd/compress/zstd_compress.c:ZSTD_CCtxParams_setParameter
  - lib/zstd/compress/zstd_compress.c:ZSTD_CCtxParams_setParameter
  - lib/zstd/compress/zstd_compress.c:ZSTD_CCtxParams_setParameter
  - lib/zstd/compress/zstd_compress.c:ZSTD_CCtxParams_setParameter
  - lib/zstd/compress/zstd_compress.c:ZSTD_CCtxParams_setParameter
  - lib/zstd/compress/zstd_compress.c:ZSTD_CCtxParams_setParameter
  - lib/zstd/compress/zstd_compress.c:ZSTD_CCtxParams_setParameter
  - lib/zstd/compress/zstd_compress.c:ZSTD_CCtxParams_setParameter
  - lib/zstd/compress/zstd_compress.c:ZSTD_CCtxParams_setParameter
  - lib/zstd/compress/zstd_compress.c:ZSTD_CCtxParams_setParameter
  - lib/zstd/compress/zstd_compress.c:ZSTD_CCtxParams_setParameter
  - lib/zstd/compress/zstd_compress.c:ZSTD_CCtxParams_setParameter
  - lib/zstd/compress/zstd_compress.c:ZSTD_CCtxParams_setParameter
  - lib/zstd/compress/zstd_compress.c:ZSTD_CCtxParams_setParameter
```
**Symbols:**

```
ffffffff81809420-ffffffff81809691: ZSTD_cParam_getBounds (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
ZSTD_bounds ZSTD_cParam_getBounds(ZSTD_cParameter param);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/compress/zstd_compress.c (ffffffff81849e10)
Location: lib/zstd/compress/zstd_compress.c:376
Inline: False
Direct callers:
  - lib/zstd/compress/zstd_compress.c:ZSTD_adjustCParams
  - lib/zstd/compress/zstd_compress.c:ZSTD_adjustCParams
  - lib/zstd/compress/zstd_compress.c:ZSTD_adjustCParams
  - lib/zstd/compress/zstd_compress.c:ZSTD_adjustCParams
  - lib/zstd/compress/zstd_compress.c:ZSTD_adjustCParams
  - lib/zstd/compress/zstd_compress.c:ZSTD_adjustCParams
  - lib/zstd/compress/zstd_compress.c:ZSTD_adjustCParams
  - lib/zstd/compress/zstd_compress.c:ZSTD_checkCParams
  - lib/zstd/compress/zstd_compress.c:ZSTD_checkCParams
  - lib/zstd/compress/zstd_compress.c:ZSTD_checkCParams
  - lib/zstd/compress/zstd_compress.c:ZSTD_checkCParams
  - lib/zstd/compress/zstd_compress.c:ZSTD_checkCParams
  - lib/zstd/compress/zstd_compress.c:ZSTD_checkCParams
  - lib/zstd/compress/zstd_compress.c:ZSTD_checkCParams
  - lib/zstd/compress/zstd_compress.c:ZSTD_CCtxParams_setParameter
  - lib/zstd/compress/zstd_compress.c:ZSTD_CCtxParams_setParameter
  - lib/zstd/compress/zstd_compress.c:ZSTD_CCtxParams_setParameter
  - lib/zstd/compress/zstd_compress.c:ZSTD_CCtxParams_setParameter
  - lib/zstd/compress/zstd_compress.c:ZSTD_CCtxParams_setParameter
  - lib/zstd/compress/zstd_compress.c:ZSTD_CCtxParams_setParameter
  - lib/zstd/compress/zstd_compress.c:ZSTD_CCtxParams_setParameter
  - lib/zstd/compress/zstd_compress.c:ZSTD_CCtxParams_setParameter
  - lib/zstd/compress/zstd_compress.c:ZSTD_CCtxParams_setParameter
  - lib/zstd/compress/zstd_compress.c:ZSTD_CCtxParams_setParameter
  - lib/zstd/compress/zstd_compress.c:ZSTD_CCtxParams_setParameter
  - lib/zstd/compress/zstd_compress.c:ZSTD_CCtxParams_setParameter
  - lib/zstd/compress/zstd_compress.c:ZSTD_CCtxParams_setParameter
  - lib/zstd/compress/zstd_compress.c:ZSTD_CCtxParams_setParameter
  - lib/zstd/compress/zstd_compress.c:ZSTD_CCtxParams_setParameter
  - lib/zstd/compress/zstd_compress.c:ZSTD_CCtxParams_setParameter
  - lib/zstd/compress/zstd_compress.c:ZSTD_CCtxParams_setParameter
  - lib/zstd/compress/zstd_compress.c:ZSTD_CCtxParams_setParameter
  - lib/zstd/compress/zstd_compress.c:ZSTD_CCtxParams_setParameter
  - lib/zstd/compress/zstd_compress.c:ZSTD_CCtxParams_setParameter
  - lib/zstd/compress/zstd_compress.c:ZSTD_CCtxParams_setParameter
  - lib/zstd/compress/zstd_compress.c:ZSTD_CCtxParams_setParameter
  - lib/zstd/compress/zstd_compress.c:ZSTD_CCtxParams_setParameter
  - lib/zstd/compress/zstd_compress.c:ZSTD_CCtxParams_setParameter
```
**Symbols:**

```
ffffffff81849e10-ffffffff8184a09c: ZSTD_cParam_getBounds (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
ZSTD_bounds ZSTD_cParam_getBounds(ZSTD_cParameter param);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/compress/zstd_compress.c (ffffffff8189b9d0)
Location: lib/zstd/compress/zstd_compress.c:376
Inline: False
Direct callers:
  - lib/zstd/compress/zstd_compress.c:ZSTD_adjustCParams
  - lib/zstd/compress/zstd_compress.c:ZSTD_adjustCParams
  - lib/zstd/compress/zstd_compress.c:ZSTD_adjustCParams
  - lib/zstd/compress/zstd_compress.c:ZSTD_adjustCParams
  - lib/zstd/compress/zstd_compress.c:ZSTD_adjustCParams
  - lib/zstd/compress/zstd_compress.c:ZSTD_adjustCParams
  - lib/zstd/compress/zstd_compress.c:ZSTD_adjustCParams
  - lib/zstd/compress/zstd_compress.c:ZSTD_checkCParams
  - lib/zstd/compress/zstd_compress.c:ZSTD_checkCParams
  - lib/zstd/compress/zstd_compress.c:ZSTD_checkCParams
  - lib/zstd/compress/zstd_compress.c:ZSTD_checkCParams
  - lib/zstd/compress/zstd_compress.c:ZSTD_checkCParams
  - lib/zstd/compress/zstd_compress.c:ZSTD_checkCParams
  - lib/zstd/compress/zstd_compress.c:ZSTD_checkCParams
  - lib/zstd/compress/zstd_compress.c:ZSTD_CCtxParams_setParameter
  - lib/zstd/compress/zstd_compress.c:ZSTD_CCtxParams_setParameter
  - lib/zstd/compress/zstd_compress.c:ZSTD_CCtxParams_setParameter
  - lib/zstd/compress/zstd_compress.c:ZSTD_CCtxParams_setParameter
  - lib/zstd/compress/zstd_compress.c:ZSTD_CCtxParams_setParameter
  - lib/zstd/compress/zstd_compress.c:ZSTD_CCtxParams_setParameter
  - lib/zstd/compress/zstd_compress.c:ZSTD_CCtxParams_setParameter
  - lib/zstd/compress/zstd_compress.c:ZSTD_CCtxParams_setParameter
  - lib/zstd/compress/zstd_compress.c:ZSTD_CCtxParams_setParameter
  - lib/zstd/compress/zstd_compress.c:ZSTD_CCtxParams_setParameter
  - lib/zstd/compress/zstd_compress.c:ZSTD_CCtxParams_setParameter
  - lib/zstd/compress/zstd_compress.c:ZSTD_CCtxParams_setParameter
  - lib/zstd/compress/zstd_compress.c:ZSTD_CCtxParams_setParameter
  - lib/zstd/compress/zstd_compress.c:ZSTD_CCtxParams_setParameter
  - lib/zstd/compress/zstd_compress.c:ZSTD_CCtxParams_setParameter
  - lib/zstd/compress/zstd_compress.c:ZSTD_CCtxParams_setParameter
  - lib/zstd/compress/zstd_compress.c:ZSTD_CCtxParams_setParameter
  - lib/zstd/compress/zstd_compress.c:ZSTD_CCtxParams_setParameter
  - lib/zstd/compress/zstd_compress.c:ZSTD_CCtxParams_setParameter
  - lib/zstd/compress/zstd_compress.c:ZSTD_CCtxParams_setParameter
  - lib/zstd/compress/zstd_compress.c:ZSTD_CCtxParams_setParameter
  - lib/zstd/compress/zstd_compress.c:ZSTD_CCtxParams_setParameter
  - lib/zstd/compress/zstd_compress.c:ZSTD_CCtxParams_setParameter
  - lib/zstd/compress/zstd_compress.c:ZSTD_CCtxParams_setParameter
```
**Symbols:**

```
ffffffff8189b9d0-ffffffff8189bc5c: ZSTD_cParam_getBounds (STB_GLOBAL)
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
