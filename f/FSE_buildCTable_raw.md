# Function: <code>FSE_buildCTable_raw</code>

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
size_t FSE_buildCTable_raw(FSE_CTable *ct, unsigned int nbBits);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/fse_compress.c (ffffffff815ace50)
Location: lib/zstd/fse_compress.c:666
Inline: False
```
**Symbols:**

```
ffffffff815ace50-ffffffff815acebd: FSE_buildCTable_raw (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
size_t FSE_buildCTable_raw(FSE_CTable *ct, unsigned int nbBits);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/fse_compress.c (ffffffff815c8990)
Location: lib/zstd/fse_compress.c:666
Inline: False
```
**Symbols:**

```
ffffffff815c8990-ffffffff815c8a07: FSE_buildCTable_raw (STB_GLOBAL)
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
size_t FSE_buildCTable_raw(FSE_CTable *ct, unsigned int nbBits);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/zstd/compress/fse_compress.c (0)
Location: lib/zstd/compress/fse_compress.c:494
Inline: False
```
**Symbols:**

```
ffffffff81e968d4-ffffffff81e96926: FSE_buildCTable_raw.cold (STB_LOCAL)
ffffffff8170ec60-ffffffff8170ed19: FSE_buildCTable_raw (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
size_t FSE_buildCTable_raw(FSE_CTable *ct, unsigned int nbBits);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/zstd/compress/fse_compress.c (0)
Location: lib/zstd/compress/fse_compress.c:537
Inline: False
```
**Symbols:**

```
ffffffff8207b6ea-ffffffff8207b73c: FSE_buildCTable_raw.cold (STB_LOCAL)
ffffffff817fdcd0-ffffffff817fdd89: FSE_buildCTable_raw (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
size_t FSE_buildCTable_raw(FSE_CTable *ct, unsigned int nbBits);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/zstd/compress/fse_compress.c (0)
Location: lib/zstd/compress/fse_compress.c:537
Inline: False
```
**Symbols:**

```
ffffffff820fbc98-ffffffff820fbcda: FSE_buildCTable_raw.cold (STB_LOCAL)
ffffffff8183e530-ffffffff8183e5e0: FSE_buildCTable_raw (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
size_t FSE_buildCTable_raw(FSE_CTable *ct, unsigned int nbBits);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/zstd/compress/fse_compress.c (0)
Location: lib/zstd/compress/fse_compress.c:537
Inline: False
```
**Symbols:**

```
ffffffff821d9e05-ffffffff821d9e47: FSE_buildCTable_raw.cold (STB_LOCAL)
ffffffff818900f0-ffffffff818901a0: FSE_buildCTable_raw (STB_GLOBAL)
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
