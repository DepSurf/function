# Function: <code>FSE_count_parallel_wksp</code>

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
size_t FSE_count_parallel_wksp(unsigned int *count, unsigned int *maxSymbolValuePtr, const void *source, size_t sourceSize, unsigned int checkMax, const unsigned int * workSpace);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/zstd/fse_compress.c (ffffffff815ac7bc)
Location: lib/zstd/fse_compress.c:357
Inline: True
Inline callers:
  - lib/zstd/fse_compress.c:FSE_count_wksp
Direct callers:
  - lib/zstd/fse_compress.c:FSE_count_wksp
```
**Symbols:**

```
ffffffff815aba80-ffffffff815abce6: FSE_count_parallel_wksp (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
size_t FSE_count_parallel_wksp(unsigned int *count, unsigned int *maxSymbolValuePtr, const void *source, size_t sourceSize, unsigned int checkMax, const unsigned int * workSpace);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In lib/zstd/fse_compress.c (ffffffff815c82c1)
Location: lib/zstd/fse_compress.c:357
Inline: True
Inline callers:
  - lib/zstd/fse_compress.c:FSE_count_wksp
Direct callers:
  - lib/zstd/fse_compress.c:FSE_count_wksp
```
**Symbols:**

```
ffffffff815c7580-ffffffff815c77eb: FSE_count_parallel_wksp (STB_LOCAL)
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
