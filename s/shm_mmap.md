# Function: <code>shm_mmap</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int shm_mmap(struct file *file, struct vm_area_struct *vma);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/shm.c (ffffffff8132a4f0)
Location: ipc/shm.c:411
Inline: False
```
**Symbols:**

```
ffffffff8132a4f0-ffffffff8132a582: shm_mmap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int shm_mmap(struct file *file, struct vm_area_struct *vma);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/shm.c (ffffffff8135f180)
Location: ipc/shm.c:411
Inline: False
```
**Symbols:**

```
ffffffff8135f180-ffffffff8135f216: shm_mmap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int shm_mmap(struct file *file, struct vm_area_struct *vma);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/shm.c (ffffffff81375980)
Location: ipc/shm.c:413
Inline: False
```
**Symbols:**

```
ffffffff81375980-ffffffff81375a16: shm_mmap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int shm_mmap(struct file *file, struct vm_area_struct *vma);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/shm.c (ffffffff81389540)
Location: ipc/shm.c:414
Inline: False
```
**Symbols:**

```
ffffffff81389540-ffffffff813895bf: shm_mmap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int shm_mmap(struct file *file, struct vm_area_struct *vma);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/shm.c (ffffffff813ae6e0)
Location: ipc/shm.c:428
Inline: False
```
**Symbols:**

```
ffffffff813ae6e0-ffffffff813ae765: shm_mmap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int shm_mmap(struct file *file, struct vm_area_struct *vma);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/shm.c (ffffffff813de800)
Location: ipc/shm.c:469
Inline: False
```
**Symbols:**

```
ffffffff813de800-ffffffff813de885: shm_mmap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int shm_mmap(struct file *file, struct vm_area_struct *vma);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/shm.c (ffffffff813f8f00)
Location: ipc/shm.c:487
Inline: False
```
**Symbols:**

```
ffffffff813f8f00-ffffffff813f8f85: shm_mmap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int shm_mmap(struct file *file, struct vm_area_struct *vma);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In ipc/shm.c (0)
Location: ipc/shm.c:487
Inline: False
```
**Symbols:**

```
ffffffff81425480-ffffffff81425503: shm_mmap (STB_LOCAL)
ffffffff81426813-ffffffff81426826: shm_mmap.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int shm_mmap(struct file *file, struct vm_area_struct *vma);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/shm.c (ffffffff8143f1d0)
Location: ipc/shm.c:487
Inline: False
```
**Symbols:**

```
ffffffff8143f1d0-ffffffff8143f255: shm_mmap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int shm_mmap(struct file *file, struct vm_area_struct *vma);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/shm.c (ffffffff81490710)
Location: ipc/shm.c:487
Inline: False
```
**Symbols:**

```
ffffffff81490710-ffffffff81490795: shm_mmap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int shm_mmap(struct file *file, struct vm_area_struct *vma);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/shm.c (ffffffff814ade50)
Location: ipc/shm.c:487
Inline: False
```
**Symbols:**

```
ffffffff814ade50-ffffffff814aded5: shm_mmap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int shm_mmap(struct file *file, struct vm_area_struct *vma);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/shm.c (ffffffff814b3c80)
Location: ipc/shm.c:487
Inline: False
```
**Symbols:**

```
ffffffff814b3c80-ffffffff814b3d05: shm_mmap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int shm_mmap(struct file *file, struct vm_area_struct *vma);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/shm.c (ffffffff8150c2f0)
Location: ipc/shm.c:579
Inline: False
```
**Symbols:**

```
ffffffff8150c2f0-ffffffff8150c375: shm_mmap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int shm_mmap(struct file *file, struct vm_area_struct *vma);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/shm.c (ffffffff8159d700)
Location: ipc/shm.c:576
Inline: False
```
**Symbols:**

```
ffffffff8159d700-ffffffff8159d799: shm_mmap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int shm_mmap(struct file *file, struct vm_area_struct *vma);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/shm.c (ffffffff81646c80)
Location: ipc/shm.c:592
Inline: False
```
**Symbols:**

```
ffffffff81646c80-ffffffff81646d0f: shm_mmap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int shm_mmap(struct file *file, struct vm_area_struct *vma);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/shm.c (ffffffff8167f1b0)
Location: ipc/shm.c:592
Inline: False
```
**Symbols:**

```
ffffffff8167f1b0-ffffffff8167f242: shm_mmap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int shm_mmap(struct file *file, struct vm_area_struct *vma);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/shm.c (ffffffff816bb5a0)
Location: ipc/shm.c:588
Inline: False
```
**Symbols:**

```
ffffffff816bb5a0-ffffffff816bb632: shm_mmap (STB_LOCAL)
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
int shm_mmap(struct file *file, struct vm_area_struct *vma);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/shm.c (ffff800010527038)
Location: ipc/shm.c:487
Inline: False
```
**Symbols:**

```
ffff800010527038-ffff8000105270e0: shm_mmap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int shm_mmap(struct file *file, struct vm_area_struct *vma);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/shm.c (c06e0cbc)
Location: ipc/shm.c:487
Inline: False
```
**Symbols:**

```
c06e0cbc-c06e0d58: shm_mmap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int shm_mmap(struct file *file, struct vm_area_struct *vma);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/shm.c (c000000000671f50)
Location: ipc/shm.c:487
Inline: False
```
**Symbols:**

```
c000000000671f50-c000000000672028: shm_mmap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int shm_mmap(struct file *file, struct vm_area_struct *vma);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/shm.c (ffffffe00038b204)
Location: ipc/shm.c:487
Inline: False
```
**Symbols:**

```
ffffffe00038b204-ffffffe00038b28a: shm_mmap (STB_LOCAL)
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
int shm_mmap(struct file *file, struct vm_area_struct *vma);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/shm.c (ffffffff814377b0)
Location: ipc/shm.c:487
Inline: False
```
**Symbols:**

```
ffffffff814377b0-ffffffff81437835: shm_mmap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int shm_mmap(struct file *file, struct vm_area_struct *vma);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/shm.c (ffffffff81428220)
Location: ipc/shm.c:487
Inline: False
```
**Symbols:**

```
ffffffff81428220-ffffffff814282a5: shm_mmap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int shm_mmap(struct file *file, struct vm_area_struct *vma);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/shm.c (ffffffff81433950)
Location: ipc/shm.c:487
Inline: False
```
**Symbols:**

```
ffffffff81433950-ffffffff814339d5: shm_mmap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int shm_mmap(struct file *file, struct vm_area_struct *vma);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In ipc/shm.c (ffffffff8144ae80)
Location: ipc/shm.c:487
Inline: False
```
**Symbols:**

```
ffffffff8144ae80-ffffffff8144af05: shm_mmap (STB_LOCAL)
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
