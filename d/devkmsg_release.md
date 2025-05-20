# Function: <code>devkmsg_release</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int devkmsg_release(struct inode *inode, struct file *file);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/printk/printk.c (ffffffff810d68f0)
Location: kernel/printk/printk.c:821
Inline: False
```
**Symbols:**

```
ffffffff810d68f0-ffffffff810d6911: devkmsg_release (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int devkmsg_release(struct inode *inode, struct file *file);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/printk/printk.c (ffffffff810dc0c0)
Location: kernel/printk/printk.c:950
Inline: False
```
**Symbols:**

```
ffffffff810dc0c0-ffffffff810dc115: devkmsg_release (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int devkmsg_release(struct inode *inode, struct file *file);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/printk/printk.c (ffffffff810e3000)
Location: kernel/printk/printk.c:931
Inline: False
```
**Symbols:**

```
ffffffff810e3000-ffffffff810e3055: devkmsg_release (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int devkmsg_release(struct inode *inode, struct file *file);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/printk/printk.c (ffffffff810e2100)
Location: kernel/printk/printk.c:981
Inline: False
```
**Symbols:**

```
ffffffff810e2100-ffffffff810e2155: devkmsg_release (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int devkmsg_release(struct inode *inode, struct file *file);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/printk/printk.c (ffffffff810ea1e0)
Location: kernel/printk/printk.c:980
Inline: False
```
**Symbols:**

```
ffffffff810ea1e0-ffffffff810ea235: devkmsg_release (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
int devkmsg_release(struct inode *inode, struct file *file);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/printk/printk.c (0)
Location: kernel/printk/printk.c:984
Inline: False
```
**Symbols:**

```
ffffffff810f24c0-ffffffff810f24f4: devkmsg_release (STB_LOCAL)
ffffffff810f4e60-ffffffff810f4e88: devkmsg_release.cold.34 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
int devkmsg_release(struct inode *inode, struct file *file);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/printk/printk.c (0)
Location: kernel/printk/printk.c:993
Inline: False
```
**Symbols:**

```
ffffffff810fdb00-ffffffff810fdb34: devkmsg_release (STB_LOCAL)
ffffffff81100620-ffffffff81100648: devkmsg_release.cold.35 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int devkmsg_release(struct inode *inode, struct file *file);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/printk/printk.c (0)
Location: kernel/printk/printk.c:1019
Inline: False
```
**Symbols:**

```
ffffffff81105e10-ffffffff81105e4a: devkmsg_release (STB_LOCAL)
ffffffff81108e00-ffffffff81108e2a: devkmsg_release.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int devkmsg_release(struct inode *inode, struct file *file);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/printk/printk.c (0)
Location: kernel/printk/printk.c:1029
Inline: False
```
**Symbols:**

```
ffffffff811121a0-ffffffff811121da: devkmsg_release (STB_LOCAL)
ffffffff811151e0-ffffffff8111520a: devkmsg_release.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int devkmsg_release(struct inode *inode, struct file *file);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/printk/printk.c (0)
Location: kernel/printk/printk.c:1041
Inline: False
```
**Symbols:**

```
ffffffff8111d760-ffffffff8111d79c: devkmsg_release (STB_LOCAL)
ffffffff81120b62-ffffffff81120b8c: devkmsg_release.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int devkmsg_release(struct inode *inode, struct file *file);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/printk/printk.c (0)
Location: kernel/printk/printk.c:872
Inline: False
```
**Symbols:**

```
ffffffff811181d0-ffffffff8111820c: devkmsg_release (STB_LOCAL)
ffffffff81be1170-ffffffff81be119a: devkmsg_release.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int devkmsg_release(struct inode *inode, struct file *file);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/printk/printk.c (0)
Location: kernel/printk/printk.c:885
Inline: False
```
**Symbols:**

```
ffffffff81118810-ffffffff8111884c: devkmsg_release (STB_LOCAL)
ffffffff81bd31f1-ffffffff81bd321b: devkmsg_release.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int devkmsg_release(struct inode *inode, struct file *file);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/printk/printk.c (0)
Location: kernel/printk/printk.c:868
Inline: False
```
**Symbols:**

```
ffffffff81138b00-ffffffff81138b3c: devkmsg_release (STB_LOCAL)
ffffffff81cac03d-ffffffff81cac067: devkmsg_release.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int devkmsg_release(struct inode *inode, struct file *file);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/printk/printk.c (0)
Location: kernel/printk/printk.c:884
Inline: False
```
**Symbols:**

```
ffffffff8115b540-ffffffff8115b581: devkmsg_release (STB_LOCAL)
ffffffff81e5c540-ffffffff81e5c566: devkmsg_release.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int devkmsg_release(struct inode *inode, struct file *file);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/printk/printk.c (ffffffff8118d890)
Location: kernel/printk/printk.c:965
Inline: False
```
**Symbols:**

```
ffffffff8118d890-ffffffff8118d8f2: devkmsg_release (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int devkmsg_release(struct inode *inode, struct file *file);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/printk/printk.c (ffffffff8119f030)
Location: kernel/printk/printk.c:937
Inline: False
```
**Symbols:**

```
ffffffff8119f030-ffffffff8119f0a5: devkmsg_release (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int devkmsg_release(struct inode *inode, struct file *file);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/printk/printk.c (ffffffff811ae120)
Location: kernel/printk/printk.c:934
Inline: False
```
**Symbols:**

```
ffffffff811ae120-ffffffff811ae195: devkmsg_release (STB_LOCAL)
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
int devkmsg_release(struct inode *inode, struct file *file);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/printk/printk.c (ffff800010172860)
Location: kernel/printk/printk.c:1029
Inline: False
```
**Symbols:**

```
ffff800010172860-ffff8000101728c4: devkmsg_release (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int devkmsg_release(struct inode *inode, struct file *file);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/printk/printk.c (c03c4eec)
Location: kernel/printk/printk.c:1029
Inline: False
```
**Symbols:**

```
c03c4eec-c03c4f60: devkmsg_release (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int devkmsg_release(struct inode *inode, struct file *file);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/printk/printk.c (c0000000001cb790)
Location: kernel/printk/printk.c:1029
Inline: False
```
**Symbols:**

```
c0000000001cb790-c0000000001cb818: devkmsg_release (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int devkmsg_release(struct inode *inode, struct file *file);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/printk/printk.c (ffffffe00010e684)
Location: kernel/printk/printk.c:1029
Inline: False
```
**Symbols:**

```
ffffffe00010e684-ffffffe00010e6d8: devkmsg_release (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
int devkmsg_release(struct inode *inode, struct file *file);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/printk/printk.c (0)
Location: kernel/printk/printk.c:1029
Inline: False
```
**Symbols:**

```
ffffffff8110a780-ffffffff8110a7ba: devkmsg_release (STB_LOCAL)
ffffffff8110d7c0-ffffffff8110d7ea: devkmsg_release.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int devkmsg_release(struct inode *inode, struct file *file);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/printk/printk.c (0)
Location: kernel/printk/printk.c:1029
Inline: False
```
**Symbols:**

```
ffffffff810fb660-ffffffff810fb69a: devkmsg_release (STB_LOCAL)
ffffffff810fe520-ffffffff810fe54a: devkmsg_release.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int devkmsg_release(struct inode *inode, struct file *file);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/printk/printk.c (0)
Location: kernel/printk/printk.c:1029
Inline: False
```
**Symbols:**

```
ffffffff81108670-ffffffff811086aa: devkmsg_release (STB_LOCAL)
ffffffff8110b6b0-ffffffff8110b6da: devkmsg_release.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int devkmsg_release(struct inode *inode, struct file *file);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/printk/printk.c (0)
Location: kernel/printk/printk.c:1029
Inline: False
```
**Symbols:**

```
ffffffff81113a10-ffffffff81113a4a: devkmsg_release (STB_LOCAL)
ffffffff81116b70-ffffffff81116b9a: devkmsg_release.cold (STB_LOCAL)
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
