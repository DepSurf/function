# Function: <code>ZSTD_compressBlock_greedy_extDict</code>

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
void ZSTD_compressBlock_greedy_extDict(ZSTD_CCtx *ctx, const void *src, size_t srcSize);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/compress.c (ffffffff815b3600)
Location: lib/zstd/compress.c:2252
Inline: False
```
**Symbols:**

```
ffffffff815b3600-ffffffff815b409d: ZSTD_compressBlock_greedy_extDict (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void ZSTD_compressBlock_greedy_extDict(ZSTD_CCtx *ctx, const void *src, size_t srcSize);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/compress.c (ffffffff815cf520)
Location: lib/zstd/compress.c:2252
Inline: False
```
**Symbols:**

```
ffffffff815cf520-ffffffff815d0146: ZSTD_compressBlock_greedy_extDict (STB_GLOBAL)
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
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
size_t ZSTD_compressBlock_greedy_extDict(ZSTD_matchState_t *ms, seqStore_t *seqStore, U32 *rep, const void *src, size_t srcSize);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/zstd/compress/zstd_lazy.c (0)
Location: lib/zstd/compress/zstd_lazy.c:1385
Inline: False
```
**Symbols:**

```
ffffffff81ea1096-ffffffff81ea1594: ZSTD_compressBlock_greedy_extDict.cold (STB_LOCAL)
ffffffff8173c880-ffffffff8173db76: ZSTD_compressBlock_greedy_extDict (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
size_t ZSTD_compressBlock_greedy_extDict(ZSTD_matchState_t *ms, seqStore_t *seqStore, U32 *rep, const void *src, size_t srcSize);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/zstd/compress/zstd_lazy.c (0)
Location: lib/zstd/compress/zstd_lazy.c:2050
Inline: False
```
**Symbols:**

```
ffffffff82089d01-ffffffff82089d6f: ZSTD_compressBlock_greedy_extDict.cold (STB_LOCAL)
ffffffff818576d0-ffffffff8185810e: ZSTD_compressBlock_greedy_extDict (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
size_t ZSTD_compressBlock_greedy_extDict(ZSTD_matchState_t *ms, seqStore_t *seqStore, U32 *rep, const void *src, size_t srcSize);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/zstd/compress/zstd_lazy.c (0)
Location: lib/zstd/compress/zstd_lazy.c:2050
Inline: False
```
**Symbols:**

```
ffffffff8210a15c-ffffffff8210a1ca: ZSTD_compressBlock_greedy_extDict.cold (STB_LOCAL)
ffffffff818984a0-ffffffff81898cc7: ZSTD_compressBlock_greedy_extDict (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
size_t ZSTD_compressBlock_greedy_extDict(ZSTD_matchState_t *ms, seqStore_t *seqStore, U32 *rep, const void *src, size_t srcSize);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/zstd/compress/zstd_lazy.c (0)
Location: lib/zstd/compress/zstd_lazy.c:2050
Inline: False
```
**Symbols:**

```
ffffffff821e82c9-ffffffff821e8337: ZSTD_compressBlock_greedy_extDict.cold (STB_LOCAL)
ffffffff818ea060-ffffffff818ea887: ZSTD_compressBlock_greedy_extDict (STB_GLOBAL)
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
