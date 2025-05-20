# Function: <code>ZSTD_initStaticDStream</code>

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
ZSTD_DStream *ZSTD_initStaticDStream(void *workspace, size_t workspaceSize);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/decompress/zstd_decompress.c (ffffffff81753640)
Location: lib/zstd/decompress/zstd_decompress.c:1444
Inline: False
Direct callers:
  - lib/zstd/zstd_decompress_module.c:zstd_init_dstream
```
**Symbols:**

```
ffffffff81753640-ffffffff81753767: ZSTD_initStaticDStream (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
ZSTD_DStream *ZSTD_initStaticDStream(void *workspace, size_t workspaceSize);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/decompress/zstd_decompress.c (ffffffff81877be0)
Location: lib/zstd/decompress/zstd_decompress.c:1490
Inline: False
Direct callers:
  - lib/zstd/zstd_decompress_module.c:zstd_init_dstream
```
**Symbols:**

```
ffffffff81877be0-ffffffff81877bf8: ZSTD_initStaticDStream (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
ZSTD_DStream *ZSTD_initStaticDStream(void *workspace, size_t workspaceSize);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/decompress/zstd_decompress.c (ffffffff818b8990)
Location: lib/zstd/decompress/zstd_decompress.c:1509
Inline: False
Direct callers:
  - lib/zstd/zstd_decompress_module.c:zstd_init_dstream
```
**Symbols:**

```
ffffffff818b8990-ffffffff818b89a8: ZSTD_initStaticDStream (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
ZSTD_DStream *ZSTD_initStaticDStream(void *workspace, size_t workspaceSize);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/decompress/zstd_decompress.c (ffffffff8190a550)
Location: lib/zstd/decompress/zstd_decompress.c:1509
Inline: False
Direct callers:
  - lib/zstd/zstd_decompress_module.c:zstd_init_dstream
```
**Symbols:**

```
ffffffff8190a550-ffffffff8190a568: ZSTD_initStaticDStream (STB_GLOBAL)
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
