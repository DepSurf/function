# Function: <code>open_port</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int open_port(struct inode *inode, struct file *filp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/mem.c (ffffffff81511060)
Location: drivers/char/mem.c:723
Inline: False
```
**Symbols:**

```
ffffffff81511060-ffffffff8151107d: open_port (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int open_port(struct inode *inode, struct file *filp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/mem.c (ffffffff815635e0)
Location: drivers/char/mem.c:742
Inline: False
```
**Symbols:**

```
ffffffff815635e0-ffffffff815635fd: open_port (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int open_port(struct inode *inode, struct file *filp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/mem.c (ffffffff8158fd40)
Location: drivers/char/mem.c:748
Inline: False
```
**Symbols:**

```
ffffffff8158fd40-ffffffff8158fd5d: open_port (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int open_port(struct inode *inode, struct file *filp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/mem.c (ffffffff815a3e10)
Location: drivers/char/mem.c:769
Inline: False
```
**Symbols:**

```
ffffffff815a3e10-ffffffff815a3e3d: open_port (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int open_port(struct inode *inode, struct file *filp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/mem.c (ffffffff8160a6f0)
Location: drivers/char/mem.c:785
Inline: False
```
**Symbols:**

```
ffffffff8160a6f0-ffffffff8160a739: open_port (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int open_port(struct inode *inode, struct file *filp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/mem.c (ffffffff81644040)
Location: drivers/char/mem.c:786
Inline: False
```
**Symbols:**

```
ffffffff81644040-ffffffff81644089: open_port (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int open_port(struct inode *inode, struct file *filp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/mem.c (ffffffff81662310)
Location: drivers/char/mem.c:787
Inline: False
```
**Symbols:**

```
ffffffff81662310-ffffffff81662359: open_port (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int open_port(struct inode *inode, struct file *filp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/mem.c (ffffffff81697ed0)
Location: drivers/char/mem.c:787
Inline: False
```
**Symbols:**

```
ffffffff81697ed0-ffffffff81697f19: open_port (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int open_port(struct inode *inode, struct file *filp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/mem.c (ffffffff816baa50)
Location: drivers/char/mem.c:808
Inline: False
```
**Symbols:**

```
ffffffff816baa50-ffffffff816baa7a: open_port (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int open_port(struct inode *inode, struct file *filp);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/char/mem.c (ffffffff8176efb0)
Location: drivers/char/mem.c:848
Inline: True
```
**Symbols:**

```
ffffffff8176efb0-ffffffff8176f014: open_port (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int open_port(struct inode *inode, struct file *filp);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/char/mem.c (ffffffff817898b0)
Location: drivers/char/mem.c:875
Inline: True
```
**Symbols:**

```
ffffffff817898b0-ffffffff81789914: open_port (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int open_port(struct inode *inode, struct file *filp);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/char/mem.c (ffffffff8176d150)
Location: drivers/char/mem.c:614
Inline: True
```
**Symbols:**

```
ffffffff8176d150-ffffffff8176d1b8: open_port (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int open_port(struct inode *inode, struct file *filp);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/char/mem.c (ffffffff817f2920)
Location: drivers/char/mem.c:613
Inline: True
```
**Symbols:**

```
ffffffff817f2920-ffffffff817f2988: open_port (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
int open_port(struct inode *inode, struct file *filp);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/char/mem.c (ffffffff81933370)
Location: drivers/char/mem.c:617
Inline: True
```
**Symbols:**

```
ffffffff81933370-ffffffff819333e6: open_port (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
int open_port(struct inode *inode, struct file *filp);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/char/mem.c (ffffffff81a920f0)
Location: drivers/char/mem.c:622
Inline: True
```
**Symbols:**

```
ffffffff81a920f0-ffffffff81a92166: open_port (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
int open_port(struct inode *inode, struct file *filp);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/char/mem.c (ffffffff81add990)
Location: drivers/char/mem.c:615
Inline: True
```
**Symbols:**

```
ffffffff81add990-ffffffff81adda06: open_port (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
int open_port(struct inode *inode, struct file *filp);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/char/mem.c (ffffffff81b30d80)
Location: drivers/char/mem.c:603
Inline: True
```
**Symbols:**

```
ffffffff81b30d80-ffffffff81b30df6: open_port (STB_LOCAL)
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
int open_port(struct inode *inode, struct file *filp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/mem.c (ffff8000108aadd8)
Location: drivers/char/mem.c:808
Inline: False
```
**Symbols:**

```
ffff8000108aadd8-ffff8000108aae10: open_port (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int open_port(struct inode *inode, struct file *filp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/mem.c (c09a7130)
Location: drivers/char/mem.c:808
Inline: False
```
**Symbols:**

```
c09a7130-c09a7168: open_port (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int open_port(struct inode *inode, struct file *filp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/mem.c (c000000000942550)
Location: drivers/char/mem.c:808
Inline: False
```
**Symbols:**

```
c000000000942550-c0000000009425a8: open_port (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int open_port(struct inode *inode, struct file *filp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/mem.c (ffffffe00055fe6a)
Location: drivers/char/mem.c:808
Inline: False
```
**Symbols:**

```
ffffffe00055fe6a-ffffffe00055fe9e: open_port (STB_LOCAL)
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
int open_port(struct inode *inode, struct file *filp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/mem.c (ffffffff816804b0)
Location: drivers/char/mem.c:808
Inline: False
```
**Symbols:**

```
ffffffff816804b0-ffffffff816804da: open_port (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int open_port(struct inode *inode, struct file *filp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/mem.c (ffffffff8165e180)
Location: drivers/char/mem.c:808
Inline: False
```
**Symbols:**

```
ffffffff8165e180-ffffffff8165e1aa: open_port (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int open_port(struct inode *inode, struct file *filp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/mem.c (ffffffff816ae890)
Location: drivers/char/mem.c:808
Inline: False
```
**Symbols:**

```
ffffffff816ae890-ffffffff816ae8ba: open_port (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int open_port(struct inode *inode, struct file *filp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/char/mem.c (ffffffff816c8ce0)
Location: drivers/char/mem.c:808
Inline: False
```
**Symbols:**

```
ffffffff816c8ce0-ffffffff816c8d0a: open_port (STB_LOCAL)
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
