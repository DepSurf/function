# Function: <code>zstd_init_cstream</code>

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
zstd_cstream *zstd_init_cstream(const zstd_parameters *parameters, long long unsigned int pledged_src_size, void *workspace, size_t workspace_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/zstd_compress_module.c (ffffffff817093c0)
Location: lib/zstd/zstd_compress_module.c:110
Inline: False
```
**Symbols:**

```
ffffffff817093c0-ffffffff8170945d: zstd_init_cstream (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
zstd_cstream *zstd_init_cstream(const zstd_parameters *parameters, long long unsigned int pledged_src_size, void *workspace, size_t workspace_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/zstd_compress_module.c (ffffffff817fc250)
Location: lib/zstd/zstd_compress_module.c:110
Inline: False
```
**Symbols:**

```
ffffffff817fc250-ffffffff817fc2ed: zstd_init_cstream (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
zstd_cstream *zstd_init_cstream(const zstd_parameters *parameters, long long unsigned int pledged_src_size, void *workspace, size_t workspace_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/zstd_compress_module.c (ffffffff8183cc40)
Location: lib/zstd/zstd_compress_module.c:110
Inline: False
```
**Symbols:**

```
ffffffff8183cc40-ffffffff8183ccdd: zstd_init_cstream (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
zstd_cstream *zstd_init_cstream(const zstd_parameters *parameters, long long unsigned int pledged_src_size, void *workspace, size_t workspace_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/zstd_compress_module.c (ffffffff8188e800)
Location: lib/zstd/zstd_compress_module.c:110
Inline: False
```
**Symbols:**

```
ffffffff8188e800-ffffffff8188e89d: zstd_init_cstream (STB_GLOBAL)
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
