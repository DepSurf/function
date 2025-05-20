# Function: <code>fuse_get_req_for_background</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
struct fuse_req *fuse_get_req_for_background(struct fuse_conn *fc, unsigned int npages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/dev.c (ffffffff8130fa60)
Location: fs/fuse/dev.c:208
Inline: False
Direct callers:
  - fs/fuse/file.c:fuse_readpages
  - fs/fuse/file.c:fuse_readpages_fill
  - fs/fuse/file.c:fuse_direct_io
  - fs/fuse/file.c:fuse_direct_io
```
**Symbols:**

```
ffffffff8130fa60-ffffffff8130fa75: fuse_get_req_for_background (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct fuse_req *fuse_get_req_for_background(struct fuse_conn *fc, unsigned int npages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/dev.c (ffffffff813435c0)
Location: fs/fuse/dev.c:188
Inline: False
Direct callers:
  - fs/fuse/file.c:fuse_direct_io
  - fs/fuse/file.c:fuse_direct_io
  - fs/fuse/file.c:fuse_readpages
  - fs/fuse/file.c:fuse_readpages_fill
```
**Symbols:**

```
ffffffff813435c0-ffffffff813435d5: fuse_get_req_for_background (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct fuse_req *fuse_get_req_for_background(struct fuse_conn *fc, unsigned int npages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/dev.c (ffffffff81359bd0)
Location: fs/fuse/dev.c:188
Inline: False
Direct callers:
  - fs/fuse/file.c:fuse_direct_io
  - fs/fuse/file.c:fuse_direct_io
  - fs/fuse/file.c:fuse_readpages
  - fs/fuse/file.c:fuse_readpages_fill
```
**Symbols:**

```
ffffffff81359bd0-ffffffff81359be5: fuse_get_req_for_background (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct fuse_req *fuse_get_req_for_background(struct fuse_conn *fc, unsigned int npages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/dev.c (ffffffff8136e3a0)
Location: fs/fuse/dev.c:188
Inline: False
Direct callers:
  - fs/fuse/file.c:fuse_direct_io
  - fs/fuse/file.c:fuse_direct_io
  - fs/fuse/file.c:fuse_readpages
  - fs/fuse/file.c:fuse_readpages_fill
```
**Symbols:**

```
ffffffff8136e3a0-ffffffff8136e3b5: fuse_get_req_for_background (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct fuse_req *fuse_get_req_for_background(struct fuse_conn *fc, unsigned int npages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/dev.c (ffffffff81392fb0)
Location: fs/fuse/dev.c:188
Inline: False
Direct callers:
  - fs/fuse/file.c:fuse_direct_io
  - fs/fuse/file.c:fuse_direct_io
  - fs/fuse/file.c:fuse_readpages
  - fs/fuse/file.c:fuse_readpages_fill
```
**Symbols:**

```
ffffffff81392fb0-ffffffff81392fc5: fuse_get_req_for_background (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct fuse_req *fuse_get_req_for_background(struct fuse_conn *fc, unsigned int npages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/dev.c (ffffffff813c17a0)
Location: fs/fuse/dev.c:198
Inline: False
Direct callers:
  - fs/fuse/file.c:fuse_direct_io
  - fs/fuse/file.c:fuse_direct_io
  - fs/fuse/file.c:fuse_readpages
  - fs/fuse/file.c:fuse_readpages_fill
```
**Symbols:**

```
ffffffff813c17a0-ffffffff813c17b5: fuse_get_req_for_background (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct fuse_req *fuse_get_req_for_background(struct fuse_conn *fc, unsigned int npages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/dev.c (ffffffff813dae70)
Location: fs/fuse/dev.c:238
Inline: False
Direct callers:
  - fs/fuse/file.c:fuse_direct_io
  - fs/fuse/file.c:fuse_direct_io
  - fs/fuse/file.c:fuse_readpages
  - fs/fuse/file.c:fuse_readpages_fill
```
**Symbols:**

```
ffffffff813dae70-ffffffff813dae85: fuse_get_req_for_background (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct fuse_req *fuse_get_req_for_background(struct fuse_conn *fc, unsigned int npages);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/dev.c (ffffffff81406a50)
Location: fs/fuse/dev.c:238
Inline: False
Direct callers:
  - fs/fuse/file.c:fuse_direct_io
  - fs/fuse/file.c:fuse_direct_io
  - fs/fuse/file.c:fuse_readpages
  - fs/fuse/file.c:fuse_readpages_fill
```
**Symbols:**

```
ffffffff81406a50-ffffffff81406a65: fuse_get_req_for_background (STB_GLOBAL)
```
</details>
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
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
</ul>
