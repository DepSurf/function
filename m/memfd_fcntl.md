# Function: <code>memfd_fcntl</code>

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
long int memfd_fcntl(struct file *file, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memfd.c (ffffffff81294090)
Location: mm/memfd.c:237
Inline: False
Direct callers:
  - fs/fcntl.c:do_fcntl
```
**Symbols:**

```
ffffffff81294090-ffffffff8129457c: memfd_fcntl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
long int memfd_fcntl(struct file *file, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memfd.c (ffffffff812a8d50)
Location: mm/memfd.c:218
Inline: False
Direct callers:
  - fs/fcntl.c:do_fcntl
  - drivers/dma-buf/udmabuf.c:udmabuf_create
```
**Symbols:**

```
ffffffff812a8d50-ffffffff812a9297: memfd_fcntl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
long int memfd_fcntl(struct file *file, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memfd.c (ffffffff812c5890)
Location: mm/memfd.c:219
Inline: False
Direct callers:
  - fs/fcntl.c:do_fcntl
  - drivers/dma-buf/udmabuf.c:udmabuf_create
```
**Symbols:**

```
ffffffff812c5890-ffffffff812c59bb: memfd_fcntl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
long int memfd_fcntl(struct file *file, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memfd.c (ffffffff812d72a0)
Location: mm/memfd.c:221
Inline: False
Direct callers:
  - fs/fcntl.c:do_fcntl
  - drivers/dma-buf/udmabuf.c:udmabuf_create
```
**Symbols:**

```
ffffffff812d72a0-ffffffff812d73cb: memfd_fcntl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
long int memfd_fcntl(struct file *file, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memfd.c (ffffffff8130c210)
Location: mm/memfd.c:221
Inline: False
Direct callers:
  - fs/fcntl.c:do_fcntl
  - drivers/dma-buf/udmabuf.c:udmabuf_create
```
**Symbols:**

```
ffffffff8130c210-ffffffff8130c33b: memfd_fcntl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
long int memfd_fcntl(struct file *file, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memfd.c (ffffffff813180d0)
Location: mm/memfd.c:221
Inline: False
Direct callers:
  - fs/fcntl.c:do_fcntl
  - drivers/dma-buf/udmabuf.c:udmabuf_create
```
**Symbols:**

```
ffffffff813180d0-ffffffff81318280: memfd_fcntl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
long int memfd_fcntl(struct file *file, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memfd.c (ffffffff8131e2c0)
Location: mm/memfd.c:221
Inline: False
Direct callers:
  - fs/fcntl.c:do_fcntl
  - drivers/dma-buf/udmabuf.c:udmabuf_create
```
**Symbols:**

```
ffffffff8131e2c0-ffffffff8131e46d: memfd_fcntl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
long int memfd_fcntl(struct file *file, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memfd.c (ffffffff8136b690)
Location: mm/memfd.c:237
Inline: False
Direct callers:
  - fs/fcntl.c:do_fcntl
  - drivers/dma-buf/udmabuf.c:udmabuf_create
```
**Symbols:**

```
ffffffff8136b690-ffffffff8136b843: memfd_fcntl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
long int memfd_fcntl(struct file *file, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memfd.c (ffffffff813e97e0)
Location: mm/memfd.c:237
Inline: False
Direct callers:
  - fs/fcntl.c:do_fcntl
  - drivers/dma-buf/udmabuf.c:udmabuf_create
```
**Symbols:**

```
ffffffff813e97e0-ffffffff813e99c1: memfd_fcntl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
long int memfd_fcntl(struct file *file, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memfd.c (ffffffff81471800)
Location: mm/memfd.c:237
Inline: False
Direct callers:
  - fs/fcntl.c:do_fcntl
  - drivers/dma-buf/udmabuf.c:udmabuf_create
```
**Symbols:**

```
ffffffff81471800-ffffffff814719e1: memfd_fcntl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
long int memfd_fcntl(struct file *file, unsigned int cmd, unsigned int arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memfd.c (ffffffff814a6160)
Location: mm/memfd.c:246
Inline: False
Direct callers:
  - fs/fcntl.c:do_fcntl
  - drivers/dma-buf/udmabuf.c:udmabuf_create
```
**Symbols:**

```
ffffffff814a6160-ffffffff814a633a: memfd_fcntl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
long int memfd_fcntl(struct file *file, unsigned int cmd, unsigned int arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memfd.c (ffffffff814d70b0)
Location: mm/memfd.c:246
Inline: False
Direct callers:
  - fs/fcntl.c:do_fcntl
  - drivers/dma-buf/udmabuf.c:udmabuf_create
```
**Symbols:**

```
ffffffff814d70b0-ffffffff814d728a: memfd_fcntl (STB_GLOBAL)
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
long int memfd_fcntl(struct file *file, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memfd.c (ffff80001037c478)
Location: mm/memfd.c:221
Inline: False
Direct callers:
  - fs/fcntl.c:do_fcntl
  - drivers/dma-buf/udmabuf.c:udmabuf_create
```
**Symbols:**

```
ffff80001037c478-ffff80001037c618: memfd_fcntl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
long int memfd_fcntl(struct file *file, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memfd.c (c0566db0)
Location: mm/memfd.c:221
Inline: False
Direct callers:
  - fs/fcntl.c:do_fcntl
  - drivers/dma-buf/udmabuf.c:udmabuf_create
```
**Symbols:**

```
c0566db0-c0566f50: memfd_fcntl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
long int memfd_fcntl(struct file *file, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memfd.c (c000000000471650)
Location: mm/memfd.c:221
Inline: False
Direct callers:
  - fs/fcntl.c:do_fcntl
  - drivers/dma-buf/udmabuf.c:udmabuf_create
```
**Symbols:**

```
c000000000471650-c000000000471874: memfd_fcntl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
long int memfd_fcntl(struct file *file, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memfd.c (ffffffe000252868)
Location: mm/memfd.c:221
Inline: False
Direct callers:
  - fs/fcntl.c:__se_sys_fcntl
  - drivers/dma-buf/udmabuf.c:udmabuf_create
```
**Symbols:**

```
ffffffe000252868-ffffffe000252984: memfd_fcntl (STB_GLOBAL)
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
long int memfd_fcntl(struct file *file, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memfd.c (ffffffff812cf880)
Location: mm/memfd.c:221
Inline: False
Direct callers:
  - fs/fcntl.c:do_fcntl
  - drivers/dma-buf/udmabuf.c:udmabuf_create
```
**Symbols:**

```
ffffffff812cf880-ffffffff812cf9ab: memfd_fcntl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
long int memfd_fcntl(struct file *file, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memfd.c (ffffffff812c0500)
Location: mm/memfd.c:221
Inline: False
Direct callers:
  - fs/fcntl.c:do_fcntl
  - drivers/dma-buf/udmabuf.c:udmabuf_create
```
**Symbols:**

```
ffffffff812c0500-ffffffff812c062b: memfd_fcntl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
long int memfd_fcntl(struct file *file, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memfd.c (ffffffff812cd690)
Location: mm/memfd.c:221
Inline: False
Direct callers:
  - fs/fcntl.c:do_fcntl
  - drivers/dma-buf/udmabuf.c:udmabuf_create
```
**Symbols:**

```
ffffffff812cd690-ffffffff812cd7bb: memfd_fcntl (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
long int memfd_fcntl(struct file *file, unsigned int cmd, long unsigned int arg);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/memfd.c (ffffffff812de4a0)
Location: mm/memfd.c:221
Inline: False
Direct callers:
  - fs/fcntl.c:do_fcntl
  - drivers/dma-buf/udmabuf.c:udmabuf_create
```
**Symbols:**

```
ffffffff812de4a0-ffffffff812de5cb: memfd_fcntl (STB_GLOBAL)
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
<details>
<summary>Changed between <code>6.2</code> and <code>6.5</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>long unsigned int arg</code> ➡️ <code>unsigned int arg</code>
</li>
</ul>
</details>
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
