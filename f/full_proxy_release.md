# Function: <code>full_proxy_release</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
int full_proxy_release(struct inode *inode, struct file *filp);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/debugfs/file.c (ffffffff81353eb0)
Location: fs/debugfs/file.c:193
Inline: True
```
**Symbols:**

```
ffffffff81353eb0-ffffffff81353f26: full_proxy_release (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
int full_proxy_release(struct inode *inode, struct file *filp);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/debugfs/file.c (ffffffff8136a160)
Location: fs/debugfs/file.c:190
Inline: True
```
**Symbols:**

```
ffffffff8136a160-ffffffff8136a1e3: full_proxy_release (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int full_proxy_release(struct inode *inode, struct file *filp);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/debugfs/file.c (ffffffff8137e7d0)
Location: fs/debugfs/file.c:190
Inline: True
```
**Symbols:**

```
ffffffff8137e7d0-ffffffff8137e853: full_proxy_release (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int full_proxy_release(struct inode *inode, struct file *filp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/debugfs/file.c (ffffffff813a37a0)
Location: fs/debugfs/file.c:229
Inline: False
```
**Symbols:**

```
ffffffff813a37a0-ffffffff813a384a: full_proxy_release (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int full_proxy_release(struct inode *inode, struct file *filp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/debugfs/file.c (ffffffff813d29b0)
Location: fs/debugfs/file.c:249
Inline: False
```
**Symbols:**

```
ffffffff813d29b0-ffffffff813d2a5a: full_proxy_release (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int full_proxy_release(struct inode *inode, struct file *filp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/debugfs/file.c (ffffffff813ed0a0)
Location: fs/debugfs/file.c:250
Inline: False
```
**Symbols:**

```
ffffffff813ed0a0-ffffffff813ed14a: full_proxy_release (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int full_proxy_release(struct inode *inode, struct file *filp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/debugfs/file.c (0)
Location: fs/debugfs/file.c:250
Inline: False
```
**Symbols:**

```
ffffffff81419240-ffffffff814192df: full_proxy_release (STB_LOCAL)
ffffffff81419752-ffffffff81419767: full_proxy_release.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int full_proxy_release(struct inode *inode, struct file *filp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/debugfs/file.c (ffffffff81433120)
Location: fs/debugfs/file.c:253
Inline: False
```
**Symbols:**

```
ffffffff81433120-ffffffff814331d0: full_proxy_release (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int full_proxy_release(struct inode *inode, struct file *filp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/debugfs/file.c (ffffffff81482d10)
Location: fs/debugfs/file.c:259
Inline: False
```
**Symbols:**

```
ffffffff81482d10-ffffffff81482daa: full_proxy_release (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int full_proxy_release(struct inode *inode, struct file *filp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/debugfs/file.c (ffffffff814a03a0)
Location: fs/debugfs/file.c:259
Inline: False
```
**Symbols:**

```
ffffffff814a03a0-ffffffff814a043a: full_proxy_release (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int full_proxy_release(struct inode *inode, struct file *filp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/debugfs/file.c (ffffffff814a6470)
Location: fs/debugfs/file.c:259
Inline: False
```
**Symbols:**

```
ffffffff814a6470-ffffffff814a650a: full_proxy_release (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int full_proxy_release(struct inode *inode, struct file *filp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/debugfs/file.c (ffffffff814fd540)
Location: fs/debugfs/file.c:261
Inline: False
```
**Symbols:**

```
ffffffff814fd540-ffffffff814fd5da: full_proxy_release (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int full_proxy_release(struct inode *inode, struct file *filp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/debugfs/file.c (ffffffff8158de60)
Location: fs/debugfs/file.c:261
Inline: False
```
**Symbols:**

```
ffffffff8158de60-ffffffff8158df02: full_proxy_release (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int full_proxy_release(struct inode *inode, struct file *filp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/debugfs/file.c (ffffffff81634c40)
Location: fs/debugfs/file.c:261
Inline: False
```
**Symbols:**

```
ffffffff81634c40-ffffffff81634ce2: full_proxy_release (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int full_proxy_release(struct inode *inode, struct file *filp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/debugfs/file.c (ffffffff8166cf50)
Location: fs/debugfs/file.c:261
Inline: False
```
**Symbols:**

```
ffffffff8166cf50-ffffffff8166cffe: full_proxy_release (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int full_proxy_release(struct inode *inode, struct file *filp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/debugfs/file.c (ffffffff816a7690)
Location: fs/debugfs/file.c:353
Inline: False
```
**Symbols:**

```
ffffffff816a7690-ffffffff816a7741: full_proxy_release (STB_LOCAL)
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
int full_proxy_release(struct inode *inode, struct file *filp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/debugfs/file.c (ffff8000105189a8)
Location: fs/debugfs/file.c:253
Inline: False
```
**Symbols:**

```
ffff8000105189a8-ffff800010518a60: full_proxy_release (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int full_proxy_release(struct inode *inode, struct file *filp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/debugfs/file.c (c06d2bb0)
Location: fs/debugfs/file.c:253
Inline: False
```
**Symbols:**

```
c06d2bb0-c06d2c64: full_proxy_release (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int full_proxy_release(struct inode *inode, struct file *filp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/debugfs/file.c (c000000000661cd0)
Location: fs/debugfs/file.c:253
Inline: False
```
**Symbols:**

```
c000000000661cd0-c000000000661ddc: full_proxy_release (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int full_proxy_release(struct inode *inode, struct file *filp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/debugfs/file.c (ffffffe000381e2a)
Location: fs/debugfs/file.c:253
Inline: False
```
**Symbols:**

```
ffffffe000381e2a-ffffffe000381eca: full_proxy_release (STB_LOCAL)
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
int full_proxy_release(struct inode *inode, struct file *filp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/debugfs/file.c (ffffffff8142b700)
Location: fs/debugfs/file.c:253
Inline: False
```
**Symbols:**

```
ffffffff8142b700-ffffffff8142b7b0: full_proxy_release (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int full_proxy_release(struct inode *inode, struct file *filp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/debugfs/file.c (ffffffff8141c180)
Location: fs/debugfs/file.c:253
Inline: False
```
**Symbols:**

```
ffffffff8141c180-ffffffff8141c230: full_proxy_release (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int full_proxy_release(struct inode *inode, struct file *filp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/debugfs/file.c (ffffffff814278a0)
Location: fs/debugfs/file.c:253
Inline: False
```
**Symbols:**

```
ffffffff814278a0-ffffffff81427950: full_proxy_release (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int full_proxy_release(struct inode *inode, struct file *filp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/debugfs/file.c (ffffffff8143e760)
Location: fs/debugfs/file.c:253
Inline: False
```
**Symbols:**

```
ffffffff8143e760-ffffffff8143e810: full_proxy_release (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
