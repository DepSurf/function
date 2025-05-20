# Function: <code>ZSTD_getErrorCode</code>

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
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/squashfs/zstd_wrapper.c (ffffffff81375bee)
Location: include/linux/zstd.h:106
Inline: True
Inline callers:
  - fs/squashfs/zstd_wrapper.c:zstd_uncompress
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/squashfs/zstd_wrapper.c (ffffffff813a460d)
Location: include/linux/zstd.h:106
Inline: True
Inline callers:
  - fs/squashfs/zstd_wrapper.c:zstd_uncompress
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/squashfs/zstd_wrapper.c (ffffffff813bd40d)
Location: include/linux/zstd.h:106
Inline: True
Inline callers:
  - fs/squashfs/zstd_wrapper.c:zstd_uncompress
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/squashfs/zstd_wrapper.c (ffffffff813e7ccc)
Location: include/linux/zstd.h:106
Inline: True
Inline callers:
  - fs/squashfs/zstd_wrapper.c:zstd_uncompress
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/squashfs/zstd_wrapper.c (ffffffff81401d4c)
Location: include/linux/zstd.h:106
Inline: True
Inline callers:
  - fs/squashfs/zstd_wrapper.c:zstd_uncompress
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/squashfs/zstd_wrapper.c (ffffffff8144fa03)
Location: include/linux/zstd.h:106
Inline: True
Inline callers:
  - fs/squashfs/zstd_wrapper.c:zstd_uncompress
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/squashfs/zstd_wrapper.c (ffffffff81bed6a9)
Location: include/linux/zstd.h:106
Inline: True
Inline callers:
  - fs/squashfs/zstd_wrapper.c:zstd_uncompress
```
```
In lib/decompress_unzstd.c (ffffffff82ffa512)
Location: include/linux/zstd.h:106
Inline: True
Inline callers:
  - lib/decompress_unzstd.c:handle_zstd_error
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/squashfs/zstd_wrapper.c (ffffffff81bdf7ac)
Location: include/linux/zstd.h:106
Inline: True
Inline callers:
  - fs/squashfs/zstd_wrapper.c:zstd_uncompress
```
```
In lib/decompress_unzstd.c (ffffffff8320511e)
Location: include/linux/zstd.h:106
Inline: True
Inline callers:
  - lib/decompress_unzstd.c:handle_zstd_error
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/squashfs/zstd_wrapper.c (ffffffff81ccf35d)
Location: include/linux/zstd.h:106
Inline: True
Inline callers:
  - fs/squashfs/zstd_wrapper.c:zstd_uncompress
```
```
In lib/decompress_unzstd.c (ffffffff832ecdf8)
Location: include/linux/zstd.h:106
Inline: True
Inline callers:
  - lib/decompress_unzstd.c:handle_zstd_error
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
ZSTD_ErrorCode ZSTD_getErrorCode(size_t code);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/common/zstd_common.c (ffffffff8170d390)
Location: lib/zstd/common/zstd_common.c:45
Inline: False
Direct callers:
  - lib/zstd/zstd_decompress_module.c:zstd_get_error_code
  - lib/zstd/decompress/zstd_decompress.c:ZSTD_decompressMultiFrame
```
**Symbols:**

```
ffffffff8170d390-ffffffff8170d3b0: ZSTD_getErrorCode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
ZSTD_ErrorCode ZSTD_getErrorCode(size_t code);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/common/zstd_common.c (ffffffff818879a0)
Location: lib/zstd/common/zstd_common.c:45
Inline: False
Direct callers:
  - lib/zstd/zstd_decompress_module.c:zstd_get_error_code
  - lib/zstd/decompress/zstd_decompress.c:ZSTD_decompressMultiFrame
```
**Symbols:**

```
ffffffff818879a0-ffffffff818879c0: ZSTD_getErrorCode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
ZSTD_ErrorCode ZSTD_getErrorCode(size_t code);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/common/zstd_common.c (ffffffff818c9d20)
Location: lib/zstd/common/zstd_common.c:45
Inline: False
Direct callers:
  - lib/zstd/zstd_decompress_module.c:zstd_get_error_code
  - lib/zstd/decompress/zstd_decompress.c:ZSTD_decompressMultiFrame
```
**Symbols:**

```
ffffffff818c9d20-ffffffff818c9d40: ZSTD_getErrorCode (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
ZSTD_ErrorCode ZSTD_getErrorCode(size_t code);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/common/zstd_common.c (ffffffff8191b8e0)
Location: lib/zstd/common/zstd_common.c:45
Inline: False
Direct callers:
  - lib/zstd/zstd_decompress_module.c:zstd_get_error_code
  - lib/zstd/decompress/zstd_decompress.c:ZSTD_decompressMultiFrame
```
**Symbols:**

```
ffffffff8191b8e0-ffffffff8191b900: ZSTD_getErrorCode (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/squashfs/zstd_wrapper.c (ffff8000104dff90)
Location: include/linux/zstd.h:106
Inline: True
Inline callers:
  - fs/squashfs/zstd_wrapper.c:zstd_uncompress
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/squashfs/zstd_wrapper.c (c06a1938)
Location: include/linux/zstd.h:106
Inline: True
Inline callers:
  - fs/squashfs/zstd_wrapper.c:zstd_uncompress
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/squashfs/zstd_wrapper.c (c00000000061c700)
Location: include/linux/zstd.h:106
Inline: True
Inline callers:
  - fs/squashfs/zstd_wrapper.c:zstd_uncompress
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/squashfs/zstd_wrapper.c (ffffffe000354288)
Location: include/linux/zstd.h:106
Inline: True
Inline callers:
  - fs/squashfs/zstd_wrapper.c:zstd_uncompress
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/squashfs/zstd_wrapper.c (ffffffff813fa32c)
Location: include/linux/zstd.h:106
Inline: True
Inline callers:
  - fs/squashfs/zstd_wrapper.c:zstd_uncompress
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/squashfs/zstd_wrapper.c (ffffffff813eadac)
Location: include/linux/zstd.h:106
Inline: True
Inline callers:
  - fs/squashfs/zstd_wrapper.c:zstd_uncompress
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/squashfs/zstd_wrapper.c (ffffffff813f76ac)
Location: include/linux/zstd.h:106
Inline: True
Inline callers:
  - fs/squashfs/zstd_wrapper.c:zstd_uncompress
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/squashfs/zstd_wrapper.c (ffffffff8140d33c)
Location: include/linux/zstd.h:106
Inline: True
Inline callers:
  - fs/squashfs/zstd_wrapper.c:zstd_uncompress
```
</details>
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
