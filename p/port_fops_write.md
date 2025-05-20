# Function: <code>port_fops_write</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
ssize_t port_fops_write(struct file *filp, const char *ubuf, size_t count, loff_t *offp);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/char/virtio_console.c (ffffffff81517b10)
Location: drivers/char/virtio_console.c:815
Inline: True
```
**Symbols:**

```
ffffffff81517b10-ffffffff81517c1f: port_fops_write (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
ssize_t port_fops_write(struct file *filp, const char *ubuf, size_t count, loff_t *offp);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/char/virtio_console.c (ffffffff8156a830)
Location: drivers/char/virtio_console.c:822
Inline: True
```
**Symbols:**

```
ffffffff8156a830-ffffffff8156a955: port_fops_write (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
ssize_t port_fops_write(struct file *filp, const char *ubuf, size_t count, loff_t *offp);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/char/virtio_console.c (ffffffff81596f60)
Location: drivers/char/virtio_console.c:821
Inline: True
```
**Symbols:**

```
ffffffff81596f60-ffffffff81597085: port_fops_write (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
ssize_t port_fops_write(struct file *filp, const char *ubuf, size_t count, loff_t *offp);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/char/virtio_console.c (ffffffff815aaf60)
Location: drivers/char/virtio_console.c:821
Inline: True
```
**Symbols:**

```
ffffffff815aaf60-ffffffff815ab08e: port_fops_write (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
ssize_t port_fops_write(struct file *filp, const char *ubuf, size_t count, loff_t *offp);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/char/virtio_console.c (ffffffff816118e0)
Location: drivers/char/virtio_console.c:818
Inline: True
```
**Symbols:**

```
ffffffff816118e0-ffffffff81611a0e: port_fops_write (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
ssize_t port_fops_write(struct file *filp, const char *ubuf, size_t count, loff_t *offp);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/char/virtio_console.c (ffffffff8164b4b0)
Location: drivers/char/virtio_console.c:817
Inline: True
```
**Symbols:**

```
ffffffff8164b4b0-ffffffff8164b5d8: port_fops_write (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
ssize_t port_fops_write(struct file *filp, const char *ubuf, size_t count, loff_t *offp);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/char/virtio_console.c (ffffffff81669620)
Location: drivers/char/virtio_console.c:817
Inline: True
```
**Symbols:**

```
ffffffff81669620-ffffffff81669748: port_fops_write (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
ssize_t port_fops_write(struct file *filp, const char *ubuf, size_t count, loff_t *offp);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/char/virtio_console.c (ffffffff8169ff80)
Location: drivers/char/virtio_console.c:804
Inline: True
```
**Symbols:**

```
ffffffff8169ff80-ffffffff816a00aa: port_fops_write (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
ssize_t port_fops_write(struct file *filp, const char *ubuf, size_t count, loff_t *offp);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/char/virtio_console.c (ffffffff816c2d30)
Location: drivers/char/virtio_console.c:804
Inline: True
```
**Symbols:**

```
ffffffff816c2d30-ffffffff816c2e5a: port_fops_write (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
ssize_t port_fops_write(struct file *filp, const char *ubuf, size_t count, loff_t *offp);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/char/virtio_console.c (ffffffff81777550)
Location: drivers/char/virtio_console.c:804
Inline: True
```
**Symbols:**

```
ffffffff81777550-ffffffff8177766e: port_fops_write.part.0.isra.0 (STB_LOCAL)
ffffffff81777670-ffffffff8177769b: port_fops_write (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

```c
ssize_t port_fops_write(struct file *filp, const char *ubuf, size_t count, loff_t *offp);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/char/virtio_console.c (ffffffff81792280)
Location: drivers/char/virtio_console.c:804
Inline: True
```
**Symbols:**

```
ffffffff81792280-ffffffff8179239e: port_fops_write.part.0.isra.0 (STB_LOCAL)
ffffffff817923a0-ffffffff817923cb: port_fops_write (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
ssize_t port_fops_write(struct file *filp, const char *ubuf, size_t count, loff_t *offp);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/char/virtio_console.c (ffffffff81774d00)
Location: drivers/char/virtio_console.c:804
Inline: True
```
**Symbols:**

```
ffffffff81774d00-ffffffff81774e25: port_fops_write (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
ssize_t port_fops_write(struct file *filp, const char *ubuf, size_t count, loff_t *offp);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/char/virtio_console.c (ffffffff817f9f30)
Location: drivers/char/virtio_console.c:804
Inline: True
```
**Symbols:**

```
ffffffff817f9f30-ffffffff817fa055: port_fops_write (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
ssize_t port_fops_write(struct file *filp, const char *ubuf, size_t count, loff_t *offp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/virtio_console.c (ffffffff81938a40)
Location: drivers/char/virtio_console.c:805
Inline: False
```
**Symbols:**

```
ffffffff81938a40-ffffffff81938b96: port_fops_write (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
ssize_t port_fops_write(struct file *filp, const char *ubuf, size_t count, loff_t *offp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/virtio_console.c (ffffffff81a98b10)
Location: drivers/char/virtio_console.c:797
Inline: False
```
**Symbols:**

```
ffffffff81a98b10-ffffffff81a98c66: port_fops_write (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
ssize_t port_fops_write(struct file *filp, const char *ubuf, size_t count, loff_t *offp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/virtio_console.c (ffffffff81ae4330)
Location: drivers/char/virtio_console.c:798
Inline: False
```
**Symbols:**

```
ffffffff81ae4330-ffffffff81ae4486: port_fops_write (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
ssize_t port_fops_write(struct file *filp, const char *ubuf, size_t count, loff_t *offp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/virtio_console.c (ffffffff81b37700)
Location: drivers/char/virtio_console.c:795
Inline: False
```
**Symbols:**

```
ffffffff81b37700-ffffffff81b37856: port_fops_write (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
ssize_t port_fops_write(struct file *filp, const char *ubuf, size_t count, loff_t *offp);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/char/virtio_console.c (ffff8000108b5b60)
Location: drivers/char/virtio_console.c:804
Inline: True
```
**Symbols:**

```
ffff8000108b5b60-ffff8000108b5de0: port_fops_write (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
ssize_t port_fops_write(struct file *filp, const char *ubuf, size_t count, loff_t *offp);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/char/virtio_console.c (c09afcb4)
Location: drivers/char/virtio_console.c:804
Inline: True
```
**Symbols:**

```
c09afcb4-c09afe34: port_fops_write (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
ssize_t port_fops_write(struct file *filp, const char *ubuf, size_t count, loff_t *offp);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/char/virtio_console.c (c00000000094f600)
Location: drivers/char/virtio_console.c:804
Inline: True
```
**Symbols:**

```
c00000000094f600-c00000000094f7b0: port_fops_write (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
ssize_t port_fops_write(struct file *filp, const char *ubuf, size_t count, loff_t *offp);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/char/virtio_console.c (ffffffe000565f3c)
Location: drivers/char/virtio_console.c:804
Inline: True
```
**Symbols:**

```
ffffffe000565f3c-ffffffe000566014: port_fops_write (STB_LOCAL)
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
ssize_t port_fops_write(struct file *filp, const char *ubuf, size_t count, loff_t *offp);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/char/virtio_console.c (ffffffff81688780)
Location: drivers/char/virtio_console.c:804
Inline: True
```
**Symbols:**

```
ffffffff81688780-ffffffff816888aa: port_fops_write (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
ssize_t port_fops_write(struct file *filp, const char *ubuf, size_t count, loff_t *offp);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/char/virtio_console.c (ffffffff81666240)
Location: drivers/char/virtio_console.c:804
Inline: True
```
**Symbols:**

```
ffffffff81666240-ffffffff8166635d: port_fops_write (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
ssize_t port_fops_write(struct file *filp, const char *ubuf, size_t count, loff_t *offp);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/char/virtio_console.c (ffffffff816b6a10)
Location: drivers/char/virtio_console.c:804
Inline: True
```
**Symbols:**

```
ffffffff816b6a10-ffffffff816b6b2d: port_fops_write (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
ssize_t port_fops_write(struct file *filp, const char *ubuf, size_t count, loff_t *offp);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/char/virtio_console.c (ffffffff816d1010)
Location: drivers/char/virtio_console.c:804
Inline: True
```
**Symbols:**

```
ffffffff816d1010-ffffffff816d113a: port_fops_write (STB_LOCAL)
```
</details>
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
