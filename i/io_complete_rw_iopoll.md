# Function: <code>io_complete_rw_iopoll</code>

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
void io_complete_rw_iopoll(struct kiocb *kiocb, long int res, long int res2);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffff8132d850)
Location: fs/io_uring.c:897
Inline: False
```
**Symbols:**

```
ffffffff8132d850-ffffffff8132d8ac: io_complete_rw_iopoll (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void io_complete_rw_iopoll(struct kiocb *kiocb, long int res, long int res2);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffff81340110)
Location: fs/io_uring.c:966
Inline: False
```
**Symbols:**

```
ffffffff81340110-ffffffff81340194: io_complete_rw_iopoll (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void io_complete_rw_iopoll(struct kiocb *kiocb, long int res, long int res2);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffff8137c500)
Location: fs/io_uring.c:2024
Inline: False
```
**Symbols:**

```
ffffffff8137c500-ffffffff8137c580: io_complete_rw_iopoll (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void io_complete_rw_iopoll(struct kiocb *kiocb, long int res, long int res2);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffff8138a6a0)
Location: fs/io_uring.c:2761
Inline: False
```
**Symbols:**

```
ffffffff8138a6a0-ffffffff8138a749: io_complete_rw_iopoll (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void io_complete_rw_iopoll(struct kiocb *kiocb, long int res, long int res2);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffff8139a8b0)
Location: fs/io_uring.c:2524
Inline: False
```
**Symbols:**

```
ffffffff8139a8b0-ffffffff8139a98c: io_complete_rw_iopoll (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void io_complete_rw_iopoll(struct kiocb *kiocb, long int res, long int res2);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffff813e1290)
Location: fs/io_uring.c:2750
Inline: False
```
**Symbols:**

```
ffffffff813e1290-ffffffff813e132f: io_complete_rw_iopoll (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void io_complete_rw_iopoll(struct kiocb *kiocb, long int res);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In io_uring/io_uring.c (ffffffff816cc530)
Location: io_uring/io_uring.c:3276
Inline: True
```
**Symbols:**

```
ffffffff816cc530-ffffffff816cc593: io_complete_rw_iopoll (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void io_complete_rw_iopoll(struct kiocb *kiocb, long int res);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In io_uring/rw.c (ffffffff817a3940)
Location: io_uring/rw.c:310
Inline: False
```
**Symbols:**

```
ffffffff817a3940-ffffffff817a39ad: io_complete_rw_iopoll (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void io_complete_rw_iopoll(struct kiocb *kiocb, long int res);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In io_uring/rw.c (ffffffff817e4970)
Location: io_uring/rw.c:310
Inline: False
```
**Symbols:**

```
ffffffff817e4970-ffffffff817e49dd: io_complete_rw_iopoll (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void io_complete_rw_iopoll(struct kiocb *kiocb, long int res);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In io_uring/rw.c (ffffffff81828e30)
Location: io_uring/rw.c:335
Inline: True
Direct callers:
  - io_uring/rw.c:kiocb_done
```
**Symbols:**

```
ffffffff81828e30-ffffffff81828eb7: io_complete_rw_iopoll (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
void io_complete_rw_iopoll(struct kiocb *kiocb, long int res, long int res2);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffff800010400190)
Location: fs/io_uring.c:966
Inline: False
```
**Symbols:**

```
ffff800010400190-ffff800010400224: io_complete_rw_iopoll (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void io_complete_rw_iopoll(struct kiocb *kiocb, long int res, long int res2);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (c05d22ac)
Location: fs/io_uring.c:966
Inline: False
```
**Symbols:**

```
c05d22ac-c05d2310: io_complete_rw_iopoll (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void io_complete_rw_iopoll(struct kiocb *kiocb, long int res, long int res2);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (c0000000005096d0)
Location: fs/io_uring.c:966
Inline: False
```
**Symbols:**

```
c0000000005096d0-c0000000005097a4: io_complete_rw_iopoll (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void io_complete_rw_iopoll(struct kiocb *kiocb, long int res, long int res2);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffe0002ac852)
Location: fs/io_uring.c:966
Inline: False
```
**Symbols:**

```
ffffffe0002ac852-ffffffe0002ac8dc: io_complete_rw_iopoll (STB_LOCAL)
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
void io_complete_rw_iopoll(struct kiocb *kiocb, long int res, long int res2);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffff813386f0)
Location: fs/io_uring.c:966
Inline: False
```
**Symbols:**

```
ffffffff813386f0-ffffffff81338774: io_complete_rw_iopoll (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void io_complete_rw_iopoll(struct kiocb *kiocb, long int res, long int res2);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffff81329420)
Location: fs/io_uring.c:966
Inline: False
```
**Symbols:**

```
ffffffff81329420-ffffffff813294a4: io_complete_rw_iopoll (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void io_complete_rw_iopoll(struct kiocb *kiocb, long int res, long int res2);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffff813361c0)
Location: fs/io_uring.c:966
Inline: False
```
**Symbols:**

```
ffffffff813361c0-ffffffff81336244: io_complete_rw_iopoll (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void io_complete_rw_iopoll(struct kiocb *kiocb, long int res, long int res2);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffff81349290)
Location: fs/io_uring.c:966
Inline: False
```
**Symbols:**

```
ffffffff81349290-ffffffff81349314: io_complete_rw_iopoll (STB_LOCAL)
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
<li>
<details>
<summary>Changed between <code>5.15</code> and <code>5.19</code> ⚠️</summary>
<ul>
<li>
<b>Param removed. </b>
<code>long int res2</code>
</li>
</ul>
</details>
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
