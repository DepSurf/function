# Function: <code>zstd_compress_cctx</code>

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
size_t zstd_compress_cctx(zstd_cctx *cctx, void *dst, size_t dst_capacity, const void *src, size_t src_size, const zstd_parameters *parameters);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/zstd_compress_module.c (ffffffff81709460)
Location: lib/zstd/zstd_compress_module.c:96
Inline: False
Direct callers:
  - security/apparmor/policy_unpack.c:compress_zstd
```
**Symbols:**

```
ffffffff81709460-ffffffff81709512: zstd_compress_cctx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
size_t zstd_compress_cctx(zstd_cctx *cctx, void *dst, size_t dst_capacity, const void *src, size_t src_size, const zstd_parameters *parameters);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/zstd_compress_module.c (ffffffff817fc300)
Location: lib/zstd/zstd_compress_module.c:96
Inline: False
Direct callers:
  - security/apparmor/policy_unpack.c:compress_zstd
```
**Symbols:**

```
ffffffff817fc300-ffffffff817fc3b2: zstd_compress_cctx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
size_t zstd_compress_cctx(zstd_cctx *cctx, void *dst, size_t dst_capacity, const void *src, size_t src_size, const zstd_parameters *parameters);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/zstd_compress_module.c (ffffffff8183ccf0)
Location: lib/zstd/zstd_compress_module.c:96
Inline: False
Direct callers:
  - security/apparmor/policy_unpack.c:compress_zstd
```
**Symbols:**

```
ffffffff8183ccf0-ffffffff8183cda2: zstd_compress_cctx (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
size_t zstd_compress_cctx(zstd_cctx *cctx, void *dst, size_t dst_capacity, const void *src, size_t src_size, const zstd_parameters *parameters);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/zstd_compress_module.c (ffffffff8188e8b0)
Location: lib/zstd/zstd_compress_module.c:96
Inline: False
Direct callers:
  - security/apparmor/policy_unpack.c:compress_zstd
```
**Symbols:**

```
ffffffff8188e8b0-ffffffff8188e962: zstd_compress_cctx (STB_GLOBAL)
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
