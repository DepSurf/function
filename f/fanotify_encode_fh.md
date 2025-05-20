# Function: <code>fanotify_encode_fh</code>

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
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
void fanotify_encode_fh(struct fanotify_fh *fh, struct inode *inode, gfp_t gfp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/notify/fanotify/fanotify.c (0)
Location: fs/notify/fanotify/fanotify.c:280
Inline: False
Direct callers:
  - fs/notify/fanotify/fanotify.c:fanotify_alloc_event
  - fs/notify/fanotify/fanotify.c:fanotify_alloc_event
```
**Symbols:**

```
ffffffff8136a190-ffffffff8136a2e4: fanotify_encode_fh (STB_LOCAL)
ffffffff8136ae92-ffffffff8136aeac: fanotify_encode_fh.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int fanotify_encode_fh(struct fanotify_fh *fh, struct inode *inode, unsigned int fh_len, gfp_t gfp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/notify/fanotify/fanotify.c (0)
Location: fs/notify/fanotify/fanotify.c:331
Inline: False
Direct callers:
  - fs/notify/fanotify/fanotify.c:fanotify_alloc_event
  - fs/notify/fanotify/fanotify.c:fanotify_alloc_name_event
  - fs/notify/fanotify/fanotify.c:fanotify_alloc_name_event
```
**Symbols:**

```
ffffffff81377510-ffffffff81377685: fanotify_encode_fh (STB_LOCAL)
ffffffff81beabf0-ffffffff81beac0a: fanotify_encode_fh.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int fanotify_encode_fh(struct fanotify_fh *fh, struct inode *inode, unsigned int fh_len, unsigned int *hash, gfp_t gfp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/notify/fanotify/fanotify.c (0)
Location: fs/notify/fanotify/fanotify.c:361
Inline: False
Direct callers:
  - fs/notify/fanotify/fanotify.c:fanotify_alloc_event
  - fs/notify/fanotify/fanotify.c:fanotify_alloc_name_event
  - fs/notify/fanotify/fanotify.c:fanotify_alloc_name_event
```
**Symbols:**

```
ffffffff8137de50-ffffffff8137e004: fanotify_encode_fh (STB_LOCAL)
ffffffff81bdcc1d-ffffffff81bdcc37: fanotify_encode_fh.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int fanotify_encode_fh(struct fanotify_fh *fh, struct inode *inode, unsigned int fh_len, unsigned int *hash, gfp_t gfp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/notify/fanotify/fanotify.c (0)
Location: fs/notify/fanotify/fanotify.c:361
Inline: False
Direct callers:
  - fs/notify/fanotify/fanotify.c:fanotify_alloc_event
  - fs/notify/fanotify/fanotify.c:fanotify_alloc_name_event
  - fs/notify/fanotify/fanotify.c:fanotify_alloc_name_event
```
**Symbols:**

```
ffffffff813cad90-ffffffff813caf44: fanotify_encode_fh (STB_LOCAL)
ffffffff81cc55b7-ffffffff81cc55d1: fanotify_encode_fh.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int fanotify_encode_fh(struct fanotify_fh *fh, struct inode *inode, unsigned int fh_len, unsigned int *hash, gfp_t gfp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/notify/fanotify/fanotify.c (0)
Location: fs/notify/fanotify/fanotify.c:399
Inline: False
Direct callers:
  - fs/notify/fanotify/fanotify.c:fanotify_alloc_event
  - fs/notify/fanotify/fanotify.c:fanotify_alloc_event
```
**Symbols:**

```
ffffffff81452be0-ffffffff81452de4: fanotify_encode_fh (STB_LOCAL)
ffffffff81e77f91-ffffffff81e77faa: fanotify_encode_fh.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int fanotify_encode_fh(struct fanotify_fh *fh, struct inode *inode, unsigned int fh_len, unsigned int *hash, gfp_t gfp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/fanotify/fanotify.c (ffffffff814e18c0)
Location: fs/notify/fanotify/fanotify.c:402
Inline: False
Direct callers:
  - fs/notify/fanotify/fanotify.c:fanotify_alloc_event
  - fs/notify/fanotify/fanotify.c:fanotify_alloc_event
```
**Symbols:**

```
ffffffff814e18c0-ffffffff814e1ad3: fanotify_encode_fh (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int fanotify_encode_fh(struct fanotify_fh *fh, struct inode *inode, unsigned int fh_len, unsigned int *hash, gfp_t gfp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/fanotify/fanotify.c (ffffffff81518180)
Location: fs/notify/fanotify/fanotify.c:403
Inline: False
Direct callers:
  - fs/notify/fanotify/fanotify.c:fanotify_alloc_event
  - fs/notify/fanotify/fanotify.c:fanotify_alloc_event
```
**Symbols:**

```
ffffffff81518180-ffffffff81518392: fanotify_encode_fh (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int fanotify_encode_fh(struct fanotify_fh *fh, struct inode *inode, unsigned int fh_len, unsigned int *hash, gfp_t gfp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/notify/fanotify/fanotify.c (ffffffff8154c560)
Location: fs/notify/fanotify/fanotify.c:397
Inline: False
Direct callers:
  - fs/notify/fanotify/fanotify.c:fanotify_alloc_event
  - fs/notify/fanotify/fanotify.c:fanotify_alloc_event
```
**Symbols:**

```
ffffffff8154c560-ffffffff8154c772: fanotify_encode_fh (STB_LOCAL)
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
<details>
<summary>Changed between <code>5.8</code> and <code>5.11</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>unsigned int fh_len</code>
</li>
<li>
<b>Param reordered. </b>
<code>fh, inode, gfp</code> ➡️ <code>fh, inode, fh_len, gfp</code>
</li>
<li>
<b>Return type changed. </b>
<code>void</code> ➡️ <code>int</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.11</code> and <code>5.13</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>unsigned int *hash</code>
</li>
<li>
<b>Param reordered. </b>
<code>fh, inode, fh_len, gfp</code> ➡️ <code>fh, inode, fh_len, hash, gfp</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
<li>
No changes between <code>5.15</code> and <code>5.19</code> ✅
</li>
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
