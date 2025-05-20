# Function: <code>proc_single_open</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int proc_single_open(struct inode *inode, struct file *filp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/base.c (ffffffff8127a500)
Location: fs/proc/base.c:796
Inline: False
```
**Symbols:**

```
ffffffff8127a500-ffffffff8127a51d: proc_single_open (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int proc_single_open(struct inode *inode, struct file *filp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/base.c (ffffffff812a7010)
Location: fs/proc/base.c:798
Inline: False
```
**Symbols:**

```
ffffffff812a7010-ffffffff812a702d: proc_single_open (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int proc_single_open(struct inode *inode, struct file *filp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/base.c (ffffffff812bc8f0)
Location: fs/proc/base.c:784
Inline: False
```
**Symbols:**

```
ffffffff812bc8f0-ffffffff812bc90d: proc_single_open (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int proc_single_open(struct inode *inode, struct file *filp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/base.c (ffffffff812c9ce0)
Location: fs/proc/base.c:761
Inline: False
```
**Symbols:**

```
ffffffff812c9ce0-ffffffff812c9cfd: proc_single_open (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int proc_single_open(struct inode *inode, struct file *filp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/base.c (ffffffff812ee570)
Location: fs/proc/base.c:761
Inline: False
```
**Symbols:**

```
ffffffff812ee570-ffffffff812ee58d: proc_single_open (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Collision ⚠️</summary>

```c
int proc_single_open(struct inode *inode, struct file *filp);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/base.c (ffffffff8131b590)
Location: fs/proc/base.c:729
Inline: False
```
```
In fs/proc/generic.c (ffffffff813200e0)
Location: fs/proc/generic.c:599
Inline: False
```
**Symbols:**

```
ffffffff8131b590-ffffffff8131b5ad: proc_single_open (STB_LOCAL)
ffffffff813200e0-ffffffff81320102: proc_single_open (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Collision ⚠️</summary>

```c
int proc_single_open(struct inode *inode, struct file *filp);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/base.c (ffffffff81332620)
Location: fs/proc/base.c:749
Inline: False
```
```
In fs/proc/generic.c (ffffffff813371c0)
Location: fs/proc/generic.c:601
Inline: False
```
**Symbols:**

```
ffffffff81332620-ffffffff8133263d: proc_single_open (STB_LOCAL)
ffffffff813371c0-ffffffff813371e2: proc_single_open (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Collision ⚠️</summary>

```c
int proc_single_open(struct inode *inode, struct file *filp);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/base.c (ffffffff8135a5a0)
Location: fs/proc/base.c:762
Inline: False
```
```
In fs/proc/generic.c (ffffffff8135f2e0)
Location: fs/proc/generic.c:602
Inline: False
```
**Symbols:**

```
ffffffff8135a5a0-ffffffff8135a5bd: proc_single_open (STB_LOCAL)
ffffffff8135f2e0-ffffffff8135f302: proc_single_open (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Collision ⚠️</summary>

```c
int proc_single_open(struct inode *inode, struct file *filp);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/base.c (ffffffff813727b0)
Location: fs/proc/base.c:762
Inline: False
```
```
In fs/proc/generic.c (ffffffff81377540)
Location: fs/proc/generic.c:602
Inline: False
```
**Symbols:**

```
ffffffff813727b0-ffffffff813727cd: proc_single_open (STB_LOCAL)
ffffffff81377540-ffffffff81377562: proc_single_open (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Collision ⚠️</summary>

```c
int proc_single_open(struct inode *inode, struct file *filp);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/base.c (ffffffff813bab00)
Location: fs/proc/base.c:772
Inline: False
```
```
In fs/proc/generic.c (ffffffff813c02d0)
Location: fs/proc/generic.c:614
Inline: False
```
**Symbols:**

```
ffffffff813bab00-ffffffff813bab1d: proc_single_open (STB_LOCAL)
ffffffff813c02d0-ffffffff813c02f2: proc_single_open (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Collision ⚠️</summary>

```c
int proc_single_open(struct inode *inode, struct file *filp);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/base.c (ffffffff813cc630)
Location: fs/proc/base.c:781
Inline: False
```
```
In fs/proc/generic.c (ffffffff813d2120)
Location: fs/proc/generic.c:634
Inline: False
```
**Symbols:**

```
ffffffff813cc630-ffffffff813cc64d: proc_single_open (STB_LOCAL)
ffffffff813d2120-ffffffff813d2142: proc_single_open (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Collision ⚠️</summary>

```c
int proc_single_open(struct inode *inode, struct file *filp);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/base.c (ffffffff813d35f0)
Location: fs/proc/base.c:780
Inline: False
```
```
In fs/proc/generic.c (ffffffff813d9010)
Location: fs/proc/generic.c:629
Inline: False
```
**Symbols:**

```
ffffffff813d35f0-ffffffff813d360d: proc_single_open (STB_LOCAL)
ffffffff813d9010-ffffffff813d9032: proc_single_open (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Collision ⚠️</summary>

```c
int proc_single_open(struct inode *inode, struct file *filp);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/base.c (ffffffff81424b20)
Location: fs/proc/base.c:784
Inline: False
```
```
In fs/proc/generic.c (ffffffff8142a740)
Location: fs/proc/generic.c:629
Inline: False
```
**Symbols:**

```
ffffffff81424b20-ffffffff81424b3d: proc_single_open (STB_LOCAL)
ffffffff8142a740-ffffffff8142a762: proc_single_open (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Collision ⚠️</summary>

```c
int proc_single_open(struct inode *inode, struct file *filp);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/base.c (ffffffff8149d810)
Location: fs/proc/base.c:783
Inline: False
```
```
In fs/proc/generic.c (ffffffff814a3cf0)
Location: fs/proc/generic.c:632
Inline: False
```
**Symbols:**

```
ffffffff8149d810-ffffffff8149d837: proc_single_open (STB_LOCAL)
ffffffff814a3cf0-ffffffff814a3d1c: proc_single_open (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Collision ⚠️</summary>

```c
int proc_single_open(struct inode *inode, struct file *filp);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/base.c (ffffffff81532430)
Location: fs/proc/base.c:784
Inline: False
```
```
In fs/proc/generic.c (ffffffff815390c0)
Location: fs/proc/generic.c:632
Inline: False
```
**Symbols:**

```
ffffffff81532430-ffffffff81532457: proc_single_open (STB_LOCAL)
ffffffff815390c0-ffffffff815390ec: proc_single_open (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Collision ⚠️</summary>

```c
int proc_single_open(struct inode *inode, struct file *filp);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/base.c (ffffffff8156a620)
Location: fs/proc/base.c:784
Inline: False
```
```
In fs/proc/generic.c (ffffffff81571370)
Location: fs/proc/generic.c:631
Inline: False
```
**Symbols:**

```
ffffffff8156a620-ffffffff8156a647: proc_single_open (STB_LOCAL)
ffffffff81571370-ffffffff8157139c: proc_single_open (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Collision ⚠️</summary>

```c
int proc_single_open(struct inode *inode, struct file *filp);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/base.c (ffffffff815a2d00)
Location: fs/proc/base.c:784
Inline: False
```
```
In fs/proc/generic.c (ffffffff815a9d20)
Location: fs/proc/generic.c:631
Inline: False
```
**Symbols:**

```
ffffffff815a2d00-ffffffff815a2d27: proc_single_open (STB_LOCAL)
ffffffff815a9d20-ffffffff815a9d4c: proc_single_open (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Collision ⚠️</summary>

```c
int proc_single_open(struct inode *inode, struct file *filp);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/base.c (ffff80001043cd08)
Location: fs/proc/base.c:762
Inline: False
```
```
In fs/proc/generic.c (ffff800010443150)
Location: fs/proc/generic.c:602
Inline: False
```
**Symbols:**

```
ffff80001043cd08-ffff80001043cd44: proc_single_open (STB_LOCAL)
ffff800010443150-ffff80001044318c: proc_single_open (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Collision ⚠️</summary>

```c
int proc_single_open(struct inode *inode, struct file *filp);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/base.c (c0602c04)
Location: fs/proc/base.c:762
Inline: False
```
```
In fs/proc/generic.c (c06084b8)
Location: fs/proc/generic.c:602
Inline: False
```
**Symbols:**

```
c0602c04-c0602c30: proc_single_open (STB_LOCAL)
c06084b8-c06084e4: proc_single_open (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Collision ⚠️</summary>

```c
int proc_single_open(struct inode *inode, struct file *filp);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/base.c (c000000000550b30)
Location: fs/proc/base.c:762
Inline: False
```
```
In fs/proc/generic.c (c0000000005586b0)
Location: fs/proc/generic.c:602
Inline: False
```
**Symbols:**

```
c000000000550b30-c000000000550b74: proc_single_open (STB_LOCAL)
c0000000005586b0-c0000000005586f4: proc_single_open (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Collision ⚠️</summary>

```c
int proc_single_open(struct inode *inode, struct file *filp);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/base.c (ffffffe0002d4fc2)
Location: fs/proc/base.c:762
Inline: False
```
```
In fs/proc/generic.c (ffffffe0002d9912)
Location: fs/proc/generic.c:602
Inline: False
```
**Symbols:**

```
ffffffe0002d4fc2-ffffffe0002d4ffc: proc_single_open (STB_LOCAL)
ffffffe0002d9912-ffffffe0002d994a: proc_single_open (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Collision ⚠️</summary>

```c
int proc_single_open(struct inode *inode, struct file *filp);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/base.c (ffffffff8136ad90)
Location: fs/proc/base.c:762
Inline: False
```
```
In fs/proc/generic.c (ffffffff8136fb20)
Location: fs/proc/generic.c:602
Inline: False
```
**Symbols:**

```
ffffffff8136ad90-ffffffff8136adad: proc_single_open (STB_LOCAL)
ffffffff8136fb20-ffffffff8136fb42: proc_single_open (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Collision ⚠️</summary>

```c
int proc_single_open(struct inode *inode, struct file *filp);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/base.c (ffffffff8135b820)
Location: fs/proc/base.c:762
Inline: False
```
```
In fs/proc/generic.c (ffffffff813605b0)
Location: fs/proc/generic.c:602
Inline: False
```
**Symbols:**

```
ffffffff8135b820-ffffffff8135b83d: proc_single_open (STB_LOCAL)
ffffffff813605b0-ffffffff813605d2: proc_single_open (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Collision ⚠️</summary>

```c
int proc_single_open(struct inode *inode, struct file *filp);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/base.c (ffffffff81368860)
Location: fs/proc/base.c:762
Inline: False
```
```
In fs/proc/generic.c (ffffffff8136d5f0)
Location: fs/proc/generic.c:602
Inline: False
```
**Symbols:**

```
ffffffff81368860-ffffffff8136887d: proc_single_open (STB_LOCAL)
ffffffff8136d5f0-ffffffff8136d612: proc_single_open (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Collision ⚠️</summary>

```c
int proc_single_open(struct inode *inode, struct file *filp);
```

**Collision:** Static-Static Collision

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/proc/base.c (ffffffff8137bed0)
Location: fs/proc/base.c:762
Inline: False
```
```
In fs/proc/generic.c (ffffffff81380f20)
Location: fs/proc/generic.c:602
Inline: False
```
**Symbols:**

```
ffffffff8137bed0-ffffffff8137beed: proc_single_open (STB_LOCAL)
ffffffff81380f20-ffffffff81380f42: proc_single_open (STB_LOCAL)
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
