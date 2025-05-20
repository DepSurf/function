# Function: <code>LZ4_resetStream</code>

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
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void LZ4_resetStream(LZ4_stream_t *LZ4_stream);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/lz4/lz4_compress.c (ffffffff815a695e)
Location: lib/lz4/lz4_compress.c:770
Inline: True
Inline callers:
  - lib/lz4/lz4_compress.c:LZ4_loadDict
  - lib/lz4/lz4_compress.c:LZ4_compress_destSize
  - lib/lz4/lz4_compress.c:LZ4_compress_fast_extState
```
**Symbols:**

```
ffffffff815a8870-ffffffff815a8882: LZ4_resetStream (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void LZ4_resetStream(LZ4_stream_t *LZ4_stream);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/lz4/lz4_compress.c (ffffffff815c2463)
Location: lib/lz4/lz4_compress.c:770
Inline: True
Inline callers:
  - lib/lz4/lz4_compress.c:LZ4_loadDict
  - lib/lz4/lz4_compress.c:LZ4_compress_destSize
  - lib/lz4/lz4_compress.c:LZ4_compress_fast_extState
```
**Symbols:**

```
ffffffff815c4370-ffffffff815c4387: LZ4_resetStream (STB_GLOBAL)
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
