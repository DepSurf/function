# Function: <code>xsk_mmap</code>

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
int xsk_mmap(struct file *file, struct socket *sock, struct vm_area_struct *vma);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xdp/xsk.c (ffffffff819cb500)
Location: net/xdp/xsk.c:638
Inline: False
```
**Symbols:**

```
ffffffff819cb500-ffffffff819cb60f: xsk_mmap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int xsk_mmap(struct file *file, struct socket *sock, struct vm_area_struct *vma);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xdp/xsk.c (ffffffff81a04750)
Location: net/xdp/xsk.c:651
Inline: False
```
**Symbols:**

```
ffffffff81a04750-ffffffff81a0485d: xsk_mmap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int xsk_mmap(struct file *file, struct socket *sock, struct vm_area_struct *vma);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xdp/xsk.c (ffffffff81a74c30)
Location: net/xdp/xsk.c:705
Inline: False
```
**Symbols:**

```
ffffffff81a74c30-ffffffff81a74d60: xsk_mmap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int xsk_mmap(struct file *file, struct socket *sock, struct vm_area_struct *vma);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xdp/xsk.c (ffffffff81aab800)
Location: net/xdp/xsk.c:961
Inline: False
```
**Symbols:**

```
ffffffff81aab800-ffffffff81aab930: xsk_mmap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int xsk_mmap(struct file *file, struct socket *sock, struct vm_area_struct *vma);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xdp/xsk.c (ffffffff81ba7110)
Location: net/xdp/xsk.c:930
Inline: False
```
**Symbols:**

```
ffffffff81ba7110-ffffffff81ba7240: xsk_mmap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int xsk_mmap(struct file *file, struct socket *sock, struct vm_area_struct *vma);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xdp/xsk.c (ffffffff81bb6890)
Location: net/xdp/xsk.c:1166
Inline: False
```
**Symbols:**

```
ffffffff81bb6890-ffffffff81bb69b7: xsk_mmap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int xsk_mmap(struct file *file, struct socket *sock, struct vm_area_struct *vma);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xdp/xsk.c (ffffffff81ba5830)
Location: net/xdp/xsk.c:1259
Inline: False
```
**Symbols:**

```
ffffffff81ba5830-ffffffff81ba5957: xsk_mmap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int xsk_mmap(struct file *file, struct socket *sock, struct vm_area_struct *vma);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/xdp/xsk.c (0)
Location: net/xdp/xsk.c:1259
Inline: False
```
**Symbols:**

```
ffffffff81c733d0-ffffffff81c7353c: xsk_mmap (STB_LOCAL)
ffffffff81d43005-ffffffff81d4301e: xsk_mmap.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int xsk_mmap(struct file *file, struct socket *sock, struct vm_area_struct *vma);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/xdp/xsk.c (0)
Location: net/xdp/xsk.c:1288
Inline: False
```
**Symbols:**

```
ffffffff81e15f40-ffffffff81e16150: xsk_mmap (STB_LOCAL)
ffffffff81f0f900-ffffffff81f0f91a: xsk_mmap.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int xsk_mmap(struct file *file, struct socket *sock, struct vm_area_struct *vma);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In net/xdp/xsk.c (0)
Location: net/xdp/xsk.c:1298
Inline: False
```
**Symbols:**

```
ffffffff81fecf90-ffffffff81fed19d: xsk_mmap (STB_LOCAL)
ffffffff820b5c96-ffffffff820b5cb0: xsk_mmap.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int xsk_mmap(struct file *file, struct socket *sock, struct vm_area_struct *vma);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xdp/xsk.c (ffffffff82069230)
Location: net/xdp/xsk.c:1304
Inline: False
```
**Symbols:**

```
ffffffff82069230-ffffffff8206933b: xsk_mmap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int xsk_mmap(struct file *file, struct socket *sock, struct vm_area_struct *vma);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xdp/xsk.c (ffffffff8213c4c0)
Location: net/xdp/xsk.c:1590
Inline: False
```
**Symbols:**

```
ffffffff8213c4c0-ffffffff8213c5cb: xsk_mmap (STB_LOCAL)
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
int xsk_mmap(struct file *file, struct socket *sock, struct vm_area_struct *vma);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xdp/xsk.c (ffff800010d7def8)
Location: net/xdp/xsk.c:961
Inline: False
```
**Symbols:**

```
ffff800010d7def8-ffff800010d7e03c: xsk_mmap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int xsk_mmap(struct file *file, struct socket *sock, struct vm_area_struct *vma);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xdp/xsk.c (c0e78a68)
Location: net/xdp/xsk.c:961
Inline: False
```
**Symbols:**

```
c0e78a68-c0e78b84: xsk_mmap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int xsk_mmap(struct file *file, struct socket *sock, struct vm_area_struct *vma);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xdp/xsk.c (c000000000ebdaa0)
Location: net/xdp/xsk.c:961
Inline: False
```
**Symbols:**

```
c000000000ebdaa0-c000000000ebdc08: xsk_mmap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int xsk_mmap(struct file *file, struct socket *sock, struct vm_area_struct *vma);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xdp/xsk.c (ffffffe0008ab706)
Location: net/xdp/xsk.c:961
Inline: False
```
**Symbols:**

```
ffffffe0008ab706-ffffffe0008ab7d6: xsk_mmap (STB_LOCAL)
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
int xsk_mmap(struct file *file, struct socket *sock, struct vm_area_struct *vma);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xdp/xsk.c (ffffffff81a4ab90)
Location: net/xdp/xsk.c:961
Inline: False
```
**Symbols:**

```
ffffffff81a4ab90-ffffffff81a4acc0: xsk_mmap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int xsk_mmap(struct file *file, struct socket *sock, struct vm_area_struct *vma);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xdp/xsk.c (ffffffff81a07780)
Location: net/xdp/xsk.c:961
Inline: False
```
**Symbols:**

```
ffffffff81a07780-ffffffff81a078b0: xsk_mmap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int xsk_mmap(struct file *file, struct socket *sock, struct vm_area_struct *vma);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xdp/xsk.c (ffffffff81ab6a40)
Location: net/xdp/xsk.c:961
Inline: False
```
**Symbols:**

```
ffffffff81ab6a40-ffffffff81ab6b70: xsk_mmap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int xsk_mmap(struct file *file, struct socket *sock, struct vm_area_struct *vma);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In net/xdp/xsk.c (ffffffff81ac2b80)
Location: net/xdp/xsk.c:961
Inline: False
```
**Symbols:**

```
ffffffff81ac2b80-ffffffff81ac2cb0: xsk_mmap (STB_LOCAL)
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
