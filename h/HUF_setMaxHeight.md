# Function: <code>HUF_setMaxHeight</code>

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
U32 HUF_setMaxHeight(nodeElt *huffNode, U32 lastNonNull, U32 maxNbBits);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/huf_compress.c (ffffffff815ad0a0)
Location: lib/zstd/huf_compress.c:290
Inline: False
Direct callers:
  - lib/zstd/huf_compress.c:HUF_buildCTable_wksp
```
**Symbols:**

```
ffffffff815ad0a0-ffffffff815ad487: HUF_setMaxHeight (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
U32 HUF_setMaxHeight(nodeElt *huffNode, U32 lastNonNull, U32 maxNbBits);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/huf_compress.c (ffffffff815c8c00)
Location: lib/zstd/huf_compress.c:290
Inline: False
Direct callers:
  - lib/zstd/huf_compress.c:HUF_buildCTable_wksp
```
**Symbols:**

```
ffffffff815c8c00-ffffffff815c8fec: HUF_setMaxHeight (STB_LOCAL)
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
U32 HUF_setMaxHeight(nodeElt *huffNode, U32 lastNonNull, U32 maxNbBits);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/zstd/compress/huf_compress.c (0)
Location: lib/zstd/compress/huf_compress.c:244
Inline: False
Direct callers:
  - lib/zstd/compress/huf_compress.c:HUF_buildCTable_wksp
```
**Symbols:**

```
ffffffff8170f420-ffffffff8170f999: HUF_setMaxHeight (STB_LOCAL)
ffffffff81e96926-ffffffff81e969c2: HUF_setMaxHeight.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
U32 HUF_setMaxHeight(nodeElt *huffNode, U32 lastNonNull, U32 maxNbBits);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/zstd/compress/huf_compress.c (0)
Location: lib/zstd/compress/huf_compress.c:305
Inline: False
Direct callers:
  - lib/zstd/compress/huf_compress.c:HUF_buildCTable_wksp
```
**Symbols:**

```
ffffffff817fe6e0-ffffffff817fec59: HUF_setMaxHeight (STB_LOCAL)
ffffffff8207b73c-ffffffff8207b7d8: HUF_setMaxHeight.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
U32 HUF_setMaxHeight(nodeElt *huffNode, U32 lastNonNull, U32 maxNbBits);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/zstd/compress/huf_compress.c (0)
Location: lib/zstd/compress/huf_compress.c:305
Inline: False
Direct callers:
  - lib/zstd/compress/huf_compress.c:HUF_buildCTable_wksp
```
**Symbols:**

```
ffffffff8183ef40-ffffffff8183f545: HUF_setMaxHeight (STB_LOCAL)
ffffffff820fbcda-ffffffff820fbd92: HUF_setMaxHeight.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
U32 HUF_setMaxHeight(nodeElt *huffNode, U32 lastNonNull, U32 maxNbBits);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/zstd/compress/huf_compress.c (0)
Location: lib/zstd/compress/huf_compress.c:305
Inline: False
Direct callers:
  - lib/zstd/compress/huf_compress.c:HUF_buildCTable_wksp
```
**Symbols:**

```
ffffffff81890b00-ffffffff81891105: HUF_setMaxHeight (STB_LOCAL)
ffffffff821d9e47-ffffffff821d9eff: HUF_setMaxHeight.cold (STB_LOCAL)
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
