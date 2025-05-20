# Function: <code>ZSTD_reset_matchState</code>

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
size_t ZSTD_reset_matchState(ZSTD_matchState_t *ms, ZSTD_cwksp *ws, const ZSTD_compressionParameters *cParams, const ZSTD_compResetPolicy_e crp, const ZSTD_indexResetPolicy_e forceResetIndex, const ZSTD_resetTarget_e forWho);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/zstd/compress/zstd_compress.c (0)
Location: lib/zstd/compress/zstd_compress.c:1484
Inline: False
Direct callers:
  - lib/zstd/compress/zstd_compress.c:ZSTD_initCDict_internal
  - lib/zstd/compress/zstd_compress.c:ZSTD_resetCCtx_internal
```
**Symbols:**

```
ffffffff81713730-ffffffff81713d36: ZSTD_reset_matchState (STB_LOCAL)
ffffffff81e970c5-ffffffff81e9711d: ZSTD_reset_matchState.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
size_t ZSTD_reset_matchState(ZSTD_matchState_t *ms, ZSTD_cwksp *ws, const ZSTD_compressionParameters *cParams, const ZSTD_paramSwitch_e useRowMatchFinder, const ZSTD_compResetPolicy_e crp, const ZSTD_indexResetPolicy_e forceResetIndex, const ZSTD_resetTarget_e forWho);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/zstd/compress/zstd_compress.c (0)
Location: lib/zstd/compress/zstd_compress.c:1642
Inline: False
Direct callers:
  - lib/zstd/compress/zstd_compress.c:ZSTD_initCDict_internal
  - lib/zstd/compress/zstd_compress.c:ZSTD_resetCCtx_internal
```
**Symbols:**

```
ffffffff81806db0-ffffffff81807776: ZSTD_reset_matchState (STB_LOCAL)
ffffffff8207dc44-ffffffff8207dca5: ZSTD_reset_matchState.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
size_t ZSTD_reset_matchState(ZSTD_matchState_t *ms, ZSTD_cwksp *ws, const ZSTD_compressionParameters *cParams, const ZSTD_paramSwitch_e useRowMatchFinder, const ZSTD_compResetPolicy_e crp, const ZSTD_indexResetPolicy_e forceResetIndex, const ZSTD_resetTarget_e forWho);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/zstd/compress/zstd_compress.c (0)
Location: lib/zstd/compress/zstd_compress.c:1642
Inline: False
Direct callers:
  - lib/zstd/compress/zstd_compress.c:ZSTD_initCDict_internal
  - lib/zstd/compress/zstd_compress.c:ZSTD_resetCCtx_internal
```
**Symbols:**

```
ffffffff81847790-ffffffff81848156: ZSTD_reset_matchState (STB_LOCAL)
ffffffff820fe1f7-ffffffff820fe258: ZSTD_reset_matchState.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
size_t ZSTD_reset_matchState(ZSTD_matchState_t *ms, ZSTD_cwksp *ws, const ZSTD_compressionParameters *cParams, const ZSTD_paramSwitch_e useRowMatchFinder, const ZSTD_compResetPolicy_e crp, const ZSTD_indexResetPolicy_e forceResetIndex, const ZSTD_resetTarget_e forWho);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/zstd/compress/zstd_compress.c (0)
Location: lib/zstd/compress/zstd_compress.c:1642
Inline: False
Direct callers:
  - lib/zstd/compress/zstd_compress.c:ZSTD_initCDict_internal
  - lib/zstd/compress/zstd_compress.c:ZSTD_resetCCtx_internal
```
**Symbols:**

```
ffffffff81899350-ffffffff81899d16: ZSTD_reset_matchState (STB_LOCAL)
ffffffff821dc364-ffffffff821dc3c5: ZSTD_reset_matchState.cold (STB_LOCAL)
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
<details>
<summary>Changed between <code>5.19</code> and <code>6.2</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>const ZSTD_paramSwitch_e useRowMatchFinder</code>
</li>
<li>
<b>Param reordered. </b>
<code>ms, ws, cParams, crp, forceResetIndex, forWho</code> ➡️ <code>ms, ws, cParams, useRowMatchFinder, crp, forceResetIndex, forWho</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
