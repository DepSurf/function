# Function: <code>modules_open</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int modules_open(struct inode *inode, struct file *file);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffffffff81105880)
Location: kernel/module.c:3950
Inline: False
```
**Symbols:**

```
ffffffff81105880-ffffffff8110589a: modules_open (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int modules_open(struct inode *inode, struct file *file);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffffffff8110d150)
Location: kernel/module.c:4121
Inline: False
```
**Symbols:**

```
ffffffff8110d150-ffffffff8110d16a: modules_open (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int modules_open(struct inode *inode, struct file *file);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffffffff81114bc0)
Location: kernel/module.c:4142
Inline: False
```
**Symbols:**

```
ffffffff81114bc0-ffffffff81114bda: modules_open (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int modules_open(struct inode *inode, struct file *file);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffffffff81115b30)
Location: kernel/module.c:4187
Inline: False
```
**Symbols:**

```
ffffffff81115b30-ffffffff81115b4a: modules_open (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int modules_open(struct inode *inode, struct file *file);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffffffff81121c30)
Location: kernel/module.c:4218
Inline: True
```
**Symbols:**

```
ffffffff81121c30-ffffffff81121c79: modules_open (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
int modules_open(struct inode *inode, struct file *file);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffffffff8112f720)
Location: kernel/module.c:4255
Inline: True
```
**Symbols:**

```
ffffffff8112f720-ffffffff8112f770: modules_open (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int modules_open(struct inode *inode, struct file *file);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffffffff8113afd0)
Location: kernel/module.c:4293
Inline: True
```
**Symbols:**

```
ffffffff8113afd0-ffffffff8113b020: modules_open (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
int modules_open(struct inode *inode, struct file *file);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffffffff811465f0)
Location: kernel/module.c:4321
Inline: True
```
**Symbols:**

```
ffffffff811465f0-ffffffff81146641: modules_open (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int modules_open(struct inode *inode, struct file *file);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffffffff811521d0)
Location: kernel/module.c:4388
Inline: True
```
**Symbols:**

```
ffffffff811521d0-ffffffff81152221: modules_open (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int modules_open(struct inode *inode, struct file *file);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffffffff811622a0)
Location: kernel/module.c:4395
Inline: True
```
**Symbols:**

```
ffffffff811622a0-ffffffff811622fe: modules_open (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int modules_open(struct inode *inode, struct file *file);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffffffff8115e300)
Location: kernel/module.c:4627
Inline: True
```
**Symbols:**

```
ffffffff8115e300-ffffffff8115e35e: modules_open (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int modules_open(struct inode *inode, struct file *file);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffffffff8115f320)
Location: kernel/module.c:4566
Inline: True
```
**Symbols:**

```
ffffffff8115f320-ffffffff8115f37e: modules_open (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int modules_open(struct inode *inode, struct file *file);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffffffff81184750)
Location: kernel/module.c:4589
Inline: True
```
**Symbols:**

```
ffffffff81184750-ffffffff811847ae: modules_open (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
int modules_open(struct inode *inode, struct file *file);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/module/procfs.c (ffffffff81192090)
Location: kernel/module/procfs.c:120
Inline: True
```
**Symbols:**

```
ffffffff81192090-ffffffff811920fd: modules_open (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
int modules_open(struct inode *inode, struct file *file);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/module/procfs.c (ffffffff811cf7d0)
Location: kernel/module/procfs.c:120
Inline: True
```
**Symbols:**

```
ffffffff811cf7d0-ffffffff811cf83d: modules_open (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
int modules_open(struct inode *inode, struct file *file);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/module/procfs.c (ffffffff811e3970)
Location: kernel/module/procfs.c:126
Inline: True
```
**Symbols:**

```
ffffffff811e3970-ffffffff811e39da: modules_open (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
int modules_open(struct inode *inode, struct file *file);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/module/procfs.c (ffffffff811f96d0)
Location: kernel/module/procfs.c:126
Inline: True
```
**Symbols:**

```
ffffffff811f96d0-ffffffff811f973a: modules_open (STB_LOCAL)
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
int modules_open(struct inode *inode, struct file *file);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffff8000101c0e88)
Location: kernel/module.c:4388
Inline: True
```
**Symbols:**

```
ffff8000101c0e88-ffff8000101c0ef4: modules_open (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int modules_open(struct inode *inode, struct file *file);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/module.c (c040855c)
Location: kernel/module.c:4388
Inline: True
```
**Symbols:**

```
c040855c-c04085b4: modules_open (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
int modules_open(struct inode *inode, struct file *file);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/module.c (c000000000227860)
Location: kernel/module.c:4388
Inline: True
```
**Symbols:**

```
c000000000227860-c0000000002278f8: modules_open (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
int modules_open(struct inode *inode, struct file *file);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffffffe000143320)
Location: kernel/module.c:4388
Inline: True
```
**Symbols:**

```
ffffffe000143320-ffffffe000143380: modules_open (STB_LOCAL)
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
int modules_open(struct inode *inode, struct file *file);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffffffff8114a7f0)
Location: kernel/module.c:4388
Inline: True
```
**Symbols:**

```
ffffffff8114a7f0-ffffffff8114a841: modules_open (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int modules_open(struct inode *inode, struct file *file);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffffffff8113daa0)
Location: kernel/module.c:4388
Inline: True
```
**Symbols:**

```
ffffffff8113daa0-ffffffff8113daf1: modules_open (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int modules_open(struct inode *inode, struct file *file);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffffffff811486a0)
Location: kernel/module.c:4388
Inline: True
```
**Symbols:**

```
ffffffff811486a0-ffffffff811486f1: modules_open (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int modules_open(struct inode *inode, struct file *file);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffffffff81155310)
Location: kernel/module.c:4388
Inline: True
```
**Symbols:**

```
ffffffff81155310-ffffffff81155361: modules_open (STB_LOCAL)
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
