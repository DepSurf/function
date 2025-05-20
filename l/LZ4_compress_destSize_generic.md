# Function: <code>LZ4_compress_destSize_generic</code>

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
int LZ4_compress_destSize_generic(const LZ4_stream_t_internal * ctx, const const char * src, const char * dst, const int * srcSizePtr, const int targetDstSize, const tableType_t tableType);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/lz4/lz4_compress.c (ffffffff815a5d70)
Location: lib/lz4/lz4_compress.c:522
Inline: False
Direct callers:
  - lib/lz4/lz4_compress.c:LZ4_compress_destSize
```
**Symbols:**

```
ffffffff815a5d70-ffffffff815a68a2: LZ4_compress_destSize_generic (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int LZ4_compress_destSize_generic(const LZ4_stream_t_internal * ctx, const const char * src, const char * dst, const int * srcSizePtr, const int targetDstSize, const tableType_t tableType);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/lz4/lz4_compress.c (ffffffff815c1870)
Location: lib/lz4/lz4_compress.c:522
Inline: False
Direct callers:
  - lib/lz4/lz4_compress.c:LZ4_compress_destSize
```
**Symbols:**

```
ffffffff815c1870-ffffffff815c23a7: LZ4_compress_destSize_generic (STB_LOCAL)
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
</ul>
