# Function: <code>io_uring_mmap</code>

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
int io_uring_mmap(struct file *file, struct vm_area_struct *vma);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffff8132df90)
Location: fs/io_uring.c:3141
Inline: False
```
**Symbols:**

```
ffffffff8132df90-ffffffff8132e065: io_uring_mmap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int io_uring_mmap(struct file *file, struct vm_area_struct *vma);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffff813411d0)
Location: fs/io_uring.c:3696
Inline: False
```
**Symbols:**

```
ffffffff813411d0-ffffffff8134129e: io_uring_mmap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int io_uring_mmap(struct file *file, struct vm_area_struct *vma);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffff8137c2c0)
Location: fs/io_uring.c:7851
Inline: False
```
**Symbols:**

```
ffffffff8137c2c0-ffffffff8137c3d1: io_uring_mmap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int io_uring_mmap(struct file *file, struct vm_area_struct *vma);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffff8138a490)
Location: fs/io_uring.c:9248
Inline: False
```
**Symbols:**

```
ffffffff8138a490-ffffffff8138a5a1: io_uring_mmap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int io_uring_mmap(struct file *file, struct vm_area_struct *vma);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffff81391550)
Location: fs/io_uring.c:9229
Inline: False
```
**Symbols:**

```
ffffffff81391550-ffffffff8139165f: io_uring_mmap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int io_uring_mmap(struct file *file, struct vm_area_struct *vma);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/io_uring.c (0)
Location: fs/io_uring.c:9905
Inline: False
```
**Symbols:**

```
ffffffff813df340-ffffffff813df47f: io_uring_mmap (STB_LOCAL)
ffffffff81cc58dc-ffffffff81cc58fd: io_uring_mmap.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int io_uring_mmap(struct file *file, struct vm_area_struct *vma);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In io_uring/io_uring.c (ffffffff81e909ee)
Location: io_uring/io_uring.c:11434
Inline: False
```
**Symbols:**

```
ffffffff81e909ee-ffffffff81e90b18: io_uring_mmap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int io_uring_mmap(struct file *file, struct vm_area_struct *vma);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In io_uring/io_uring.c (0)
Location: io_uring/io_uring.c:3196
Inline: False
```
**Symbols:**

```
ffffffff81789b60-ffffffff81789d38: io_uring_mmap (STB_LOCAL)
ffffffff8207751b-ffffffff82077543: io_uring_mmap.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int io_uring_mmap(struct file *file, struct vm_area_struct *vma);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In io_uring/io_uring.c (ffffffff817c9af0)
Location: io_uring/io_uring.c:3439
Inline: False
```
**Symbols:**

```
ffffffff817c9af0-ffffffff817c9b72: io_uring_mmap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int io_uring_mmap(struct file *file, struct vm_area_struct *vma);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In io_uring/io_uring.c (ffffffff8180f670)
Location: io_uring/io_uring.c:3462
Inline: False
```
**Symbols:**

```
ffffffff8180f670-ffffffff8180f6f2: io_uring_mmap (STB_LOCAL)
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
int io_uring_mmap(struct file *file, struct vm_area_struct *vma);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffff8000104002f0)
Location: fs/io_uring.c:3696
Inline: False
```
**Symbols:**

```
ffff8000104002f0-ffff8000104003fc: io_uring_mmap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int io_uring_mmap(struct file *file, struct vm_area_struct *vma);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (c05d2684)
Location: fs/io_uring.c:3696
Inline: False
```
**Symbols:**

```
c05d2684-c05d2758: io_uring_mmap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int io_uring_mmap(struct file *file, struct vm_area_struct *vma);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (c000000000509a20)
Location: fs/io_uring.c:3696
Inline: False
```
**Symbols:**

```
c000000000509a20-c000000000509b18: io_uring_mmap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int io_uring_mmap(struct file *file, struct vm_area_struct *vma);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffe0002aca6a)
Location: fs/io_uring.c:3696
Inline: False
```
**Symbols:**

```
ffffffe0002aca6a-ffffffe0002acb14: io_uring_mmap (STB_LOCAL)
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
int io_uring_mmap(struct file *file, struct vm_area_struct *vma);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffff813397b0)
Location: fs/io_uring.c:3696
Inline: False
```
**Symbols:**

```
ffffffff813397b0-ffffffff8133987e: io_uring_mmap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int io_uring_mmap(struct file *file, struct vm_area_struct *vma);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffff8132a4e0)
Location: fs/io_uring.c:3696
Inline: False
```
**Symbols:**

```
ffffffff8132a4e0-ffffffff8132a5ae: io_uring_mmap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int io_uring_mmap(struct file *file, struct vm_area_struct *vma);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffff81337280)
Location: fs/io_uring.c:3696
Inline: False
```
**Symbols:**

```
ffffffff81337280-ffffffff8133734e: io_uring_mmap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int io_uring_mmap(struct file *file, struct vm_area_struct *vma);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/io_uring.c (ffffffff8134a340)
Location: fs/io_uring.c:3696
Inline: False
```
**Symbols:**

```
ffffffff8134a340-ffffffff8134a40e: io_uring_mmap (STB_LOCAL)
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
