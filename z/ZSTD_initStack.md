# Function: <code>ZSTD_initStack</code>

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
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
ZSTD_customMem ZSTD_initStack(void *workspace, size_t workspaceSize);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/zstd_common.c (ffffffff814ba3f0)
Location: lib/zstd/zstd_common.c:35
Inline: False
Direct callers:
  - lib/zstd/decompress.c:ZSTD_initDStream
  - lib/zstd/decompress.c:ZSTD_initDDict
  - lib/zstd/decompress.c:ZSTD_initDCtx
```
**Symbols:**

```
ffffffff814ba3f0-ffffffff814ba44b: ZSTD_initStack (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
ZSTD_customMem ZSTD_initStack(void *workspace, size_t workspaceSize);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/zstd_common.c (ffffffff814eccb0)
Location: lib/zstd/zstd_common.c:35
Inline: False
Direct callers:
  - lib/zstd/decompress.c:ZSTD_initDStream
  - lib/zstd/decompress.c:ZSTD_initDDict
  - lib/zstd/decompress.c:ZSTD_initDCtx
```
**Symbols:**

```
ffffffff814eccb0-ffffffff814ecd05: ZSTD_initStack (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
ZSTD_customMem ZSTD_initStack(void *workspace, size_t workspaceSize);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/zstd_common.c (ffffffff81500a50)
Location: lib/zstd/zstd_common.c:35
Inline: False
Direct callers:
  - lib/zstd/decompress.c:ZSTD_initDStream
  - lib/zstd/decompress.c:ZSTD_initDDict
  - lib/zstd/decompress.c:ZSTD_initDCtx
```
**Symbols:**

```
ffffffff81500a50-ffffffff81500aa5: ZSTD_initStack (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
ZSTD_customMem ZSTD_initStack(void *workspace, size_t workspaceSize);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/zstd_common.c (ffffffff8152ebb0)
Location: lib/zstd/zstd_common.c:35
Inline: False
Direct callers:
  - lib/zstd/decompress.c:ZSTD_initDStream
  - lib/zstd/decompress.c:ZSTD_initDDict
  - lib/zstd/decompress.c:ZSTD_initDCtx
```
**Symbols:**

```
ffffffff8152ebb0-ffffffff8152ec05: ZSTD_initStack (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
ZSTD_customMem ZSTD_initStack(void *workspace, size_t workspaceSize);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/zstd_common.c (ffffffff8154fa40)
Location: lib/zstd/zstd_common.c:35
Inline: False
Direct callers:
  - lib/zstd/decompress.c:ZSTD_initDStream
  - lib/zstd/decompress.c:ZSTD_initDDict
  - lib/zstd/decompress.c:ZSTD_initDCtx
```
**Symbols:**

```
ffffffff8154fa40-ffffffff8154fa95: ZSTD_initStack (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
ZSTD_customMem ZSTD_initStack(void *workspace, size_t workspaceSize);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/zstd_common.c (ffffffff815cd9b0)
Location: lib/zstd/zstd_common.c:35
Inline: False
Direct callers:
  - lib/zstd/compress.c:ZSTD_initCStream_usingCDict
  - lib/zstd/compress.c:ZSTD_initCDict
  - lib/zstd/compress.c:ZSTD_initCCtx
  - lib/zstd/decompress.c:ZSTD_initDStream
  - lib/zstd/decompress.c:ZSTD_initDDict
  - lib/zstd/decompress.c:ZSTD_initDCtx
```
**Symbols:**

```
ffffffff815cd9b0-ffffffff815cda05: ZSTD_initStack (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
ZSTD_customMem ZSTD_initStack(void *workspace, size_t workspaceSize);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/zstd_common.c (ffffffff815eb560)
Location: lib/zstd/zstd_common.c:35
Inline: False
Direct callers:
  - lib/zstd/compress.c:ZSTD_initCStream_usingCDict
  - lib/zstd/compress.c:ZSTD_initCDict
  - lib/zstd/compress.c:ZSTD_initCCtx
  - lib/zstd/decompress.c:ZSTD_initDStream
  - lib/zstd/decompress.c:ZSTD_initDDict
  - lib/zstd/decompress.c:ZSTD_initDCtx
```
**Symbols:**

```
ffffffff815eb560-ffffffff815eb5c0: ZSTD_initStack (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
ZSTD_customMem ZSTD_initStack(void *workspace, size_t workspaceSize);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/zstd_common.c (ffffffff815d9670)
Location: lib/zstd/zstd_common.c:35
Inline: False
Direct callers:
  - lib/zstd/decompress.c:ZSTD_initDStream
  - lib/zstd/decompress.c:ZSTD_initDDict
  - lib/zstd/decompress.c:ZSTD_initDCtx
```
**Symbols:**

```
ffffffff815d9670-ffffffff815d96d0: ZSTD_initStack (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
ZSTD_customMem ZSTD_initStack(void *workspace, size_t workspaceSize);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/zstd_common.c (ffffffff81644970)
Location: lib/zstd/zstd_common.c:35
Inline: False
Direct callers:
  - lib/zstd/decompress.c:ZSTD_initDStream
  - lib/zstd/decompress.c:ZSTD_initDDict
  - lib/zstd/decompress.c:ZSTD_initDCtx
```
**Symbols:**

```
ffffffff81644970-ffffffff816449d0: ZSTD_initStack (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
ZSTD_customMem ZSTD_initStack(void *workspace, size_t workspaceSize);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/zstd_common.c (ffff80001065ba60)
Location: lib/zstd/zstd_common.c:35
Inline: False
Direct callers:
  - lib/zstd/decompress.c:ZSTD_initDStream
  - lib/zstd/decompress.c:ZSTD_initDDict
  - lib/zstd/decompress.c:ZSTD_initDCtx
```
**Symbols:**

```
ffff80001065ba60-ffff80001065bab0: ZSTD_initStack (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
ZSTD_customMem ZSTD_initStack(void *workspace, size_t workspaceSize);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/zstd_common.c (c08050d0)
Location: lib/zstd/zstd_common.c:35
Inline: False
Direct callers:
  - lib/zstd/decompress.c:ZSTD_initDStream
  - lib/zstd/decompress.c:ZSTD_initDDict
  - lib/zstd/decompress.c:ZSTD_initDCtx
```
**Symbols:**

```
c08050d0-c0805138: ZSTD_initStack (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
ZSTD_customMem ZSTD_initStack(void *workspace, size_t workspaceSize);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/zstd_common.c (c00000000080d038)
Location: lib/zstd/zstd_common.c:35
Inline: False
Direct callers:
  - lib/zstd/decompress.c:ZSTD_initDStream
  - lib/zstd/decompress.c:ZSTD_initDDict
  - lib/zstd/decompress.c:ZSTD_initDCtx
```
**Symbols:**

```
c00000000080d038-c00000000080d0b0: ZSTD_initStack (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
ZSTD_customMem ZSTD_initStack(void *workspace, size_t workspaceSize);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/zstd_common.c (ffffffe00048991e)
Location: lib/zstd/zstd_common.c:35
Inline: False
Direct callers:
  - lib/zstd/decompress.c:ZSTD_initDStream
  - lib/zstd/decompress.c:ZSTD_initDDict
  - lib/zstd/decompress.c:ZSTD_initDCtx
```
**Symbols:**

```
ffffffe00048991e-ffffffe00048996e: ZSTD_initStack (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
ZSTD_customMem ZSTD_initStack(void *workspace, size_t workspaceSize);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/zstd_common.c (ffffffff81548020)
Location: lib/zstd/zstd_common.c:35
Inline: False
Direct callers:
  - lib/zstd/decompress.c:ZSTD_initDStream
  - lib/zstd/decompress.c:ZSTD_initDDict
  - lib/zstd/decompress.c:ZSTD_initDCtx
```
**Symbols:**

```
ffffffff81548020-ffffffff81548075: ZSTD_initStack (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
ZSTD_customMem ZSTD_initStack(void *workspace, size_t workspaceSize);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/zstd_common.c (ffffffff81538300)
Location: lib/zstd/zstd_common.c:35
Inline: False
Direct callers:
  - lib/zstd/decompress.c:ZSTD_initDStream
  - lib/zstd/decompress.c:ZSTD_initDDict
  - lib/zstd/decompress.c:ZSTD_initDCtx
```
**Symbols:**

```
ffffffff81538300-ffffffff81538355: ZSTD_initStack (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
ZSTD_customMem ZSTD_initStack(void *workspace, size_t workspaceSize);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/zstd_common.c (ffffffff81543d60)
Location: lib/zstd/zstd_common.c:35
Inline: False
Direct callers:
  - lib/zstd/decompress.c:ZSTD_initDStream
  - lib/zstd/decompress.c:ZSTD_initDDict
  - lib/zstd/decompress.c:ZSTD_initDCtx
```
**Symbols:**

```
ffffffff81543d60-ffffffff81543db5: ZSTD_initStack (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
ZSTD_customMem ZSTD_initStack(void *workspace, size_t workspaceSize);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/zstd_common.c (ffffffff8155db90)
Location: lib/zstd/zstd_common.c:35
Inline: False
Direct callers:
  - lib/zstd/decompress.c:ZSTD_initDStream
  - lib/zstd/decompress.c:ZSTD_initDDict
  - lib/zstd/decompress.c:ZSTD_initDCtx
```
**Symbols:**

```
ffffffff8155db90-ffffffff8155dbe5: ZSTD_initStack (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
