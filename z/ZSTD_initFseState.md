# Function: <code>ZSTD_initFseState</code>

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
void ZSTD_initFseState(ZSTD_fseState *DStatePtr, BIT_DStream_t *bitD, const ZSTD_seqSymbol *dt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/decompress/zstd_decompress_block.c (ffffffff81755cd0)
Location: lib/zstd/decompress/zstd_decompress_block.c:900
Inline: False
```
**Symbols:**

```
ffffffff81755cd0-ffffffff81755dca: ZSTD_initFseState (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void ZSTD_initFseState(ZSTD_fseState *DStatePtr, BIT_DStream_t *bitD, const ZSTD_seqSymbol *dt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/zstd/decompress/zstd_decompress_block.c (0)
Location: lib/zstd/decompress/zstd_decompress_block.c:1138
Inline: False
```
**Symbols:**

```
ffffffff8187a590-ffffffff8187a678: ZSTD_initFseState (STB_LOCAL)
ffffffff8208b5bd-ffffffff8208b5e2: ZSTD_initFseState.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void ZSTD_initFseState(ZSTD_fseState *DStatePtr, BIT_DStream_t *bitD, const ZSTD_seqSymbol *dt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/zstd/decompress/zstd_decompress_block.c (0)
Location: lib/zstd/decompress/zstd_decompress_block.c:1138
Inline: False
```
**Symbols:**

```
ffffffff818bb3d0-ffffffff818bb4b8: ZSTD_initFseState (STB_LOCAL)
ffffffff8210b893-ffffffff8210b8b8: ZSTD_initFseState.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void ZSTD_initFseState(ZSTD_fseState *DStatePtr, BIT_DStream_t *bitD, const ZSTD_seqSymbol *dt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/zstd/decompress/zstd_decompress_block.c (0)
Location: lib/zstd/decompress/zstd_decompress_block.c:1138
Inline: False
```
**Symbols:**

```
ffffffff8190cf90-ffffffff8190d078: ZSTD_initFseState (STB_LOCAL)
ffffffff821e9a00-ffffffff821e9a25: ZSTD_initFseState.cold (STB_LOCAL)
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
