# Function: <code>blkdev_iopoll</code>

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
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int blkdev_iopoll(struct kiocb *kiocb, bool wait);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffffffff813124f0)
Location: fs/block_dev.c:290
Inline: False
```
**Symbols:**

```
ffffffff813124f0-ffffffff81312523: blkdev_iopoll (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int blkdev_iopoll(struct kiocb *kiocb, bool wait);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffffffff81325440)
Location: fs/block_dev.c:290
Inline: False
```
**Symbols:**

```
ffffffff81325440-ffffffff81325473: blkdev_iopoll (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int blkdev_iopoll(struct kiocb *kiocb, bool wait);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffffffff8135ec70)
Location: fs/block_dev.c:289
Inline: False
```
**Symbols:**

```
ffffffff8135ec70-ffffffff8135eca3: blkdev_iopoll (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int blkdev_iopoll(struct kiocb *kiocb, bool wait);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffffffff8136c460)
Location: fs/block_dev.c:321
Inline: False
```
**Symbols:**

```
ffffffff8136c460-ffffffff8136c490: blkdev_iopoll (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int blkdev_iopoll(struct kiocb *kiocb, bool wait);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffffffff81372d90)
Location: fs/block_dev.c:322
Inline: False
```
**Symbols:**

```
ffffffff81372d90-ffffffff81372dc0: blkdev_iopoll (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int blkdev_iopoll(struct kiocb *kiocb, bool wait);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/fops.c (ffffffff815c5200)
Location: block/fops.c:144
Inline: False
```
**Symbols:**

```
ffffffff815c5200-ffffffff815c5240: blkdev_iopoll (STB_LOCAL)
```
</details>
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
<summary>In <code>arm64</code>: ✅</summary>

```c
int blkdev_iopoll(struct kiocb *kiocb, bool wait);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffff8000103dfa90)
Location: fs/block_dev.c:290
Inline: False
```
**Symbols:**

```
ffff8000103dfa90-ffff8000103dfad8: blkdev_iopoll (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int blkdev_iopoll(struct kiocb *kiocb, bool wait);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (c05b7e6c)
Location: fs/block_dev.c:290
Inline: False
```
**Symbols:**

```
c05b7e6c-c05b7ea4: blkdev_iopoll (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int blkdev_iopoll(struct kiocb *kiocb, bool wait);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (c0000000004e4c50)
Location: fs/block_dev.c:290
Inline: False
```
**Symbols:**

```
c0000000004e4c50-c0000000004e4ca0: blkdev_iopoll (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int blkdev_iopoll(struct kiocb *kiocb, bool wait);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffffffe000296814)
Location: fs/block_dev.c:290
Inline: False
```
**Symbols:**

```
ffffffe000296814-ffffffe000296856: blkdev_iopoll (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
int blkdev_iopoll(struct kiocb *kiocb, bool wait);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffffffff8131da20)
Location: fs/block_dev.c:290
Inline: False
```
**Symbols:**

```
ffffffff8131da20-ffffffff8131da53: blkdev_iopoll (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int blkdev_iopoll(struct kiocb *kiocb, bool wait);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffffffff8130e5c0)
Location: fs/block_dev.c:290
Inline: False
```
**Symbols:**

```
ffffffff8130e5c0-ffffffff8130e5f3: blkdev_iopoll (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int blkdev_iopoll(struct kiocb *kiocb, bool wait);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffffffff8131b4f0)
Location: fs/block_dev.c:290
Inline: False
```
**Symbols:**

```
ffffffff8131b4f0-ffffffff8131b523: blkdev_iopoll (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int blkdev_iopoll(struct kiocb *kiocb, bool wait);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/block_dev.c (ffffffff8132d2d0)
Location: fs/block_dev.c:290
Inline: False
```
**Symbols:**

```
ffffffff8132d2d0-ffffffff8132d303: blkdev_iopoll (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
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
