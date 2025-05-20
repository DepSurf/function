# Function: <code>bpf_dummy_read</code>

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
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
ssize_t bpf_dummy_read(struct file *filp, char *buf, size_t siz, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff8119e4f0)
Location: kernel/bpf/syscall.c:300
Inline: True
```
**Symbols:**

```
ffffffff8119e4f0-ffffffff8119e502: bpf_dummy_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
ssize_t bpf_dummy_read(struct file *filp, char *buf, size_t siz, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff811b2d60)
Location: kernel/bpf/syscall.c:349
Inline: True
```
**Symbols:**

```
ffffffff811b2d60-ffffffff811b2d72: bpf_dummy_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
ssize_t bpf_dummy_read(struct file *filp, char *buf, size_t siz, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff811c1970)
Location: kernel/bpf/syscall.c:377
Inline: True
```
**Symbols:**

```
ffffffff811c1970-ffffffff811c1982: bpf_dummy_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
ssize_t bpf_dummy_read(struct file *filp, char *buf, size_t siz, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff811d20a0)
Location: kernel/bpf/syscall.c:409
Inline: False
```
**Symbols:**

```
ffffffff811d20a0-ffffffff811d20b2: bpf_dummy_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
ssize_t bpf_dummy_read(struct file *filp, char *buf, size_t siz, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff811de640)
Location: kernel/bpf/syscall.c:412
Inline: False
```
**Symbols:**

```
ffffffff811de640-ffffffff811de652: bpf_dummy_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
ssize_t bpf_dummy_read(struct file *filp, char *buf, size_t siz, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff811fb320)
Location: kernel/bpf/syscall.c:562
Inline: True
```
**Symbols:**

```
ffffffff811fb320-ffffffff811fb332: bpf_dummy_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
ssize_t bpf_dummy_read(struct file *filp, char *buf, size_t siz, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff811fa480)
Location: kernel/bpf/syscall.c:569
Inline: True
```
**Symbols:**

```
ffffffff811fa480-ffffffff811fa492: bpf_dummy_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
ssize_t bpf_dummy_read(struct file *filp, char *buf, size_t siz, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff811fb3c0)
Location: kernel/bpf/syscall.c:570
Inline: True
```
**Symbols:**

```
ffffffff811fb3c0-ffffffff811fb3d2: bpf_dummy_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
ssize_t bpf_dummy_read(struct file *filp, char *buf, size_t siz, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff8122caa0)
Location: kernel/bpf/syscall.c:591
Inline: True
```
**Symbols:**

```
ffffffff8122caa0-ffffffff8122cab2: bpf_dummy_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
ssize_t bpf_dummy_read(struct file *filp, char *buf, size_t siz, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff8126ecf0)
Location: kernel/bpf/syscall.c:712
Inline: True
```
**Symbols:**

```
ffffffff8126ecf0-ffffffff8126ed06: bpf_dummy_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
ssize_t bpf_dummy_read(struct file *filp, char *buf, size_t siz, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff812c4510)
Location: kernel/bpf/syscall.c:812
Inline: True
```
**Symbols:**

```
ffffffff812c4510-ffffffff812c4526: bpf_dummy_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
ssize_t bpf_dummy_read(struct file *filp, char *buf, size_t siz, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff812eb510)
Location: kernel/bpf/syscall.c:811
Inline: True
```
**Symbols:**

```
ffffffff812eb510-ffffffff812eb526: bpf_dummy_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
ssize_t bpf_dummy_read(struct file *filp, char *buf, size_t siz, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff81309a60)
Location: kernel/bpf/syscall.c:841
Inline: True
```
**Symbols:**

```
ffffffff81309a60-ffffffff81309a76: bpf_dummy_read (STB_LOCAL)
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
ssize_t bpf_dummy_read(struct file *filp, char *buf, size_t siz, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffff80001025f990)
Location: kernel/bpf/syscall.c:412
Inline: True
```
**Symbols:**

```
ffff80001025f990-ffff80001025f9ac: bpf_dummy_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
ssize_t bpf_dummy_read(struct file *filp, char *buf, size_t siz, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (c0492d5c)
Location: kernel/bpf/syscall.c:412
Inline: True
```
**Symbols:**

```
c0492d5c-c0492d78: bpf_dummy_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
ssize_t bpf_dummy_read(struct file *filp, char *buf, size_t siz, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (c000000000304910)
Location: kernel/bpf/syscall.c:412
Inline: False
```
**Symbols:**

```
c000000000304910-c000000000304920: bpf_dummy_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
ssize_t bpf_dummy_read(struct file *filp, char *buf, size_t siz, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffe00019d702)
Location: kernel/bpf/syscall.c:412
Inline: True
```
**Symbols:**

```
ffffffe00019d702-ffffffe00019d71e: bpf_dummy_read (STB_LOCAL)
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
ssize_t bpf_dummy_read(struct file *filp, char *buf, size_t siz, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff811d6c60)
Location: kernel/bpf/syscall.c:412
Inline: False
```
**Symbols:**

```
ffffffff811d6c60-ffffffff811d6c72: bpf_dummy_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
ssize_t bpf_dummy_read(struct file *filp, char *buf, size_t siz, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff811c9a20)
Location: kernel/bpf/syscall.c:412
Inline: False
```
**Symbols:**

```
ffffffff811c9a20-ffffffff811c9a32: bpf_dummy_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
ssize_t bpf_dummy_read(struct file *filp, char *buf, size_t siz, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff811d4a30)
Location: kernel/bpf/syscall.c:412
Inline: False
```
**Symbols:**

```
ffffffff811d4a30-ffffffff811d4a42: bpf_dummy_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
ssize_t bpf_dummy_read(struct file *filp, char *buf, size_t siz, loff_t *ppos);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/bpf/syscall.c (ffffffff811e2d60)
Location: kernel/bpf/syscall.c:412
Inline: False
```
**Symbols:**

```
ffffffff811e2d60-ffffffff811e2d72: bpf_dummy_read (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
