# Function: <code>bsg_transport_fill_hdr</code>

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
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int bsg_transport_fill_hdr(struct request *rq, struct sg_io_v4 *hdr, fmode_t mode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bsg-lib.c (ffffffff814a66d0)
Location: block/bsg-lib.c:44
Inline: False
```
**Symbols:**

```
ffffffff814a66d0-ffffffff814a670a: bsg_transport_fill_hdr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int bsg_transport_fill_hdr(struct request *rq, struct sg_io_v4 *hdr, fmode_t mode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bsg-lib.c (ffffffff814c0600)
Location: block/bsg-lib.c:50
Inline: False
```
**Symbols:**

```
ffffffff814c0600-ffffffff814c063a: bsg_transport_fill_hdr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
int bsg_transport_fill_hdr(struct request *rq, struct sg_io_v4 *hdr, fmode_t mode);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/bsg-lib.c (ffffffff814eef70)
Location: block/bsg-lib.c:36
Inline: True
```
**Symbols:**

```
ffffffff814eef70-ffffffff814ef05c: bsg_transport_fill_hdr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int bsg_transport_fill_hdr(struct request *rq, struct sg_io_v4 *hdr, fmode_t mode);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/bsg-lib.c (ffffffff81508420)
Location: block/bsg-lib.c:36
Inline: True
```
**Symbols:**

```
ffffffff81508420-ffffffff8150850c: bsg_transport_fill_hdr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int bsg_transport_fill_hdr(struct request *rq, struct sg_io_v4 *hdr, fmode_t mode);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/bsg-lib.c (ffffffff815694c0)
Location: block/bsg-lib.c:36
Inline: True
```
**Symbols:**

```
ffffffff815694c0-ffffffff815695ac: bsg_transport_fill_hdr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int bsg_transport_fill_hdr(struct request *rq, struct sg_io_v4 *hdr, fmode_t mode);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/bsg-lib.c (ffffffff81583f40)
Location: block/bsg-lib.c:36
Inline: True
```
**Symbols:**

```
ffffffff81583f40-ffffffff8158402c: bsg_transport_fill_hdr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int bsg_transport_fill_hdr(struct request *rq, struct sg_io_v4 *hdr, fmode_t mode);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/bsg-lib.c (ffffffff8158ad40)
Location: block/bsg-lib.c:36
Inline: True
```
**Symbols:**

```
ffffffff8158ad40-ffffffff8158ae2c: bsg_transport_fill_hdr (STB_LOCAL)
```
</details>
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
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
int bsg_transport_fill_hdr(struct request *rq, struct sg_io_v4 *hdr, fmode_t mode);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/bsg-lib.c (ffff80001060af40)
Location: block/bsg-lib.c:36
Inline: True
```
**Symbols:**

```
ffff80001060af40-ffff80001060b01c: bsg_transport_fill_hdr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int bsg_transport_fill_hdr(struct request *rq, struct sg_io_v4 *hdr, fmode_t mode);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/bsg-lib.c (c07b5e9c)
Location: block/bsg-lib.c:36
Inline: True
```
**Symbols:**

```
c07b5e9c-c07b5f80: bsg_transport_fill_hdr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
int bsg_transport_fill_hdr(struct request *rq, struct sg_io_v4 *hdr, fmode_t mode);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/bsg-lib.c (c0000000007a74d0)
Location: block/bsg-lib.c:36
Inline: True
```
**Symbols:**

```
c0000000007a74d0-c0000000007a7604: bsg_transport_fill_hdr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
int bsg_transport_fill_hdr(struct request *rq, struct sg_io_v4 *hdr, fmode_t mode);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/bsg-lib.c (ffffffe000444126)
Location: block/bsg-lib.c:36
Inline: True
```
**Symbols:**

```
ffffffe000444126-ffffffe0004441fa: bsg_transport_fill_hdr (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
int bsg_transport_fill_hdr(struct request *rq, struct sg_io_v4 *hdr, fmode_t mode);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/bsg-lib.c (ffffffff81500a00)
Location: block/bsg-lib.c:36
Inline: True
```
**Symbols:**

```
ffffffff81500a00-ffffffff81500aec: bsg_transport_fill_hdr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int bsg_transport_fill_hdr(struct request *rq, struct sg_io_v4 *hdr, fmode_t mode);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/bsg-lib.c (ffffffff814f0f10)
Location: block/bsg-lib.c:36
Inline: True
```
**Symbols:**

```
ffffffff814f0f10-ffffffff814f0ffc: bsg_transport_fill_hdr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int bsg_transport_fill_hdr(struct request *rq, struct sg_io_v4 *hdr, fmode_t mode);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/bsg-lib.c (ffffffff814fca90)
Location: block/bsg-lib.c:36
Inline: True
```
**Symbols:**

```
ffffffff814fca90-ffffffff814fcb7c: bsg_transport_fill_hdr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int bsg_transport_fill_hdr(struct request *rq, struct sg_io_v4 *hdr, fmode_t mode);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/bsg-lib.c (ffffffff81515b40)
Location: block/bsg-lib.c:36
Inline: True
```
**Symbols:**

```
ffffffff81515b40-ffffffff81515c2c: bsg_transport_fill_hdr (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
