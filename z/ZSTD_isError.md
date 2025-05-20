# Function: <code>ZSTD_isError</code>

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
In fs/squashfs/zstd_wrapper.c (0)
Location: include/linux/zstd.h:95
Inline: True
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
In fs/squashfs/zstd_wrapper.c (0)
Location: include/linux/zstd.h:95
Inline: True
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
In fs/squashfs/zstd_wrapper.c (0)
Location: include/linux/zstd.h:95
Inline: True
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
In fs/squashfs/zstd_wrapper.c (0)
Location: include/linux/zstd.h:95
Inline: True
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
In fs/squashfs/zstd_wrapper.c (0)
Location: include/linux/zstd.h:95
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/squashfs/zstd_wrapper.c (0)
Location: include/linux/zstd.h:95
Inline: True
```
```
In lib/zstd/compress.c (0)
Location: include/linux/zstd.h:95
Inline: True
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
In fs/squashfs/zstd_wrapper.c (0)
Location: include/linux/zstd.h:95
Inline: True
```
```
In lib/zstd/compress.c (0)
Location: include/linux/zstd.h:95
Inline: True
```
```
In lib/decompress_unzstd.c (0)
Location: include/linux/zstd.h:95
Inline: True
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
In fs/squashfs/zstd_wrapper.c (0)
Location: include/linux/zstd.h:95
Inline: True
```
```
In lib/decompress_unzstd.c (0)
Location: include/linux/zstd.h:95
Inline: True
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
In fs/squashfs/zstd_wrapper.c (0)
Location: include/linux/zstd.h:95
Inline: True
```
```
In lib/decompress_unzstd.c (0)
Location: include/linux/zstd.h:95
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
unsigned int ZSTD_isError(size_t code);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/common/zstd_common.c (ffffffff8170d340)
Location: lib/zstd/common/zstd_common.c:37
Inline: False
Direct callers:
  - lib/zstd/zstd_decompress_module.c:zstd_is_error
```
**Symbols:**

```
ffffffff8170d340-ffffffff8170d35a: ZSTD_isError (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
unsigned int ZSTD_isError(size_t code);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/common/zstd_common.c (ffffffff81887930)
Location: lib/zstd/common/zstd_common.c:37
Inline: False
Direct callers:
  - lib/zstd/zstd_decompress_module.c:zstd_is_error
```
**Symbols:**

```
ffffffff81887930-ffffffff8188794a: ZSTD_isError (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
unsigned int ZSTD_isError(size_t code);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/common/zstd_common.c (ffffffff818c9cb0)
Location: lib/zstd/common/zstd_common.c:37
Inline: False
Direct callers:
  - lib/zstd/zstd_decompress_module.c:zstd_is_error
```
**Symbols:**

```
ffffffff818c9cb0-ffffffff818c9cca: ZSTD_isError (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
unsigned int ZSTD_isError(size_t code);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/common/zstd_common.c (ffffffff8191b870)
Location: lib/zstd/common/zstd_common.c:37
Inline: False
Direct callers:
  - lib/zstd/zstd_decompress_module.c:zstd_is_error
```
**Symbols:**

```
ffffffff8191b870-ffffffff8191b88a: ZSTD_isError (STB_GLOBAL)
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
In fs/squashfs/zstd_wrapper.c (0)
Location: include/linux/zstd.h:95
Inline: True
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
In fs/squashfs/zstd_wrapper.c (0)
Location: include/linux/zstd.h:95
Inline: True
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
In fs/squashfs/zstd_wrapper.c (0)
Location: include/linux/zstd.h:95
Inline: True
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
In fs/squashfs/zstd_wrapper.c (0)
Location: include/linux/zstd.h:95
Inline: True
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
In fs/squashfs/zstd_wrapper.c (0)
Location: include/linux/zstd.h:95
Inline: True
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
In fs/squashfs/zstd_wrapper.c (0)
Location: include/linux/zstd.h:95
Inline: True
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
In fs/squashfs/zstd_wrapper.c (0)
Location: include/linux/zstd.h:95
Inline: True
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
In fs/squashfs/zstd_wrapper.c (0)
Location: include/linux/zstd.h:95
Inline: True
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
