# Function: <code>zstd_compress_bound</code>

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
size_t zstd_compress_bound(size_t src_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/zstd_compress_module.c (ffffffff817090f0)
Location: lib/zstd/zstd_compress_module.c:69
Inline: False
Direct callers:
  - security/apparmor/policy_unpack.c:compress_zstd
```
**Symbols:**

```
ffffffff817090f0-ffffffff81709106: zstd_compress_bound (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
size_t zstd_compress_bound(size_t src_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/zstd_compress_module.c (ffffffff817fbea0)
Location: lib/zstd/zstd_compress_module.c:69
Inline: False
Direct callers:
  - security/apparmor/policy_unpack.c:compress_zstd
```
**Symbols:**

```
ffffffff817fbea0-ffffffff817fbeb6: zstd_compress_bound (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
size_t zstd_compress_bound(size_t src_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/zstd_compress_module.c (ffffffff8183c890)
Location: lib/zstd/zstd_compress_module.c:69
Inline: False
Direct callers:
  - security/apparmor/policy_unpack.c:compress_zstd
```
**Symbols:**

```
ffffffff8183c890-ffffffff8183c8a6: zstd_compress_bound (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
size_t zstd_compress_bound(size_t src_size);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/zstd/zstd_compress_module.c (ffffffff8188e450)
Location: lib/zstd/zstd_compress_module.c:69
Inline: False
Direct callers:
  - security/apparmor/policy_unpack.c:compress_zstd
```
**Symbols:**

```
ffffffff8188e450-ffffffff8188e466: zstd_compress_bound (STB_GLOBAL)
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
