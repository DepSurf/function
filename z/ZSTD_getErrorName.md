# Function: <code>ZSTD_getErrorName</code>

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
const char *ZSTD_getErrorName(size_t code);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/common/zstd_common.c (ffffffff8170d360)
Location: lib/zstd/common/zstd_common.c:41
Inline: False
Direct callers:
  - lib/zstd/zstd_decompress_module.c:zstd_get_error_name
```
**Symbols:**

```
ffffffff8170d360-ffffffff8170d387: ZSTD_getErrorName (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
const char *ZSTD_getErrorName(size_t code);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/common/zstd_common.c (ffffffff81887960)
Location: lib/zstd/common/zstd_common.c:41
Inline: False
Direct callers:
  - lib/zstd/zstd_decompress_module.c:zstd_get_error_name
```
**Symbols:**

```
ffffffff81887960-ffffffff81887987: ZSTD_getErrorName (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
const char *ZSTD_getErrorName(size_t code);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/common/zstd_common.c (ffffffff818c9ce0)
Location: lib/zstd/common/zstd_common.c:41
Inline: False
Direct callers:
  - lib/zstd/zstd_decompress_module.c:zstd_get_error_name
```
**Symbols:**

```
ffffffff818c9ce0-ffffffff818c9d07: ZSTD_getErrorName (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
const char *ZSTD_getErrorName(size_t code);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/common/zstd_common.c (ffffffff8191b8a0)
Location: lib/zstd/common/zstd_common.c:41
Inline: False
Direct callers:
  - lib/zstd/zstd_decompress_module.c:zstd_get_error_name
```
**Symbols:**

```
ffffffff8191b8a0-ffffffff8191b8c7: ZSTD_getErrorName (STB_GLOBAL)
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
