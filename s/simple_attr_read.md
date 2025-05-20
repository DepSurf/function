# Function: <code>simple_attr_read</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
ssize_t simple_attr_read(struct file *file, char *buf, size_t len, loff_t *ppos);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/libfs.c (ffffffff81234410)
Location: fs/libfs.c:788
Inline: False
```
**Symbols:**

```
ffffffff81234410-ffffffff812344f8: simple_attr_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
ssize_t simple_attr_read(struct file *file, char *buf, size_t len, loff_t *ppos);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/libfs.c (ffffffff8125d2b0)
Location: fs/libfs.c:816
Inline: False
Direct callers:
  - fs/debugfs/file.c:debugfs_attr_read
```
**Symbols:**

```
ffffffff8125d2b0-ffffffff8125d397: simple_attr_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
ssize_t simple_attr_read(struct file *file, char *buf, size_t len, loff_t *ppos);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/libfs.c (ffffffff812707e0)
Location: fs/libfs.c:824
Inline: False
Direct callers:
  - fs/debugfs/file.c:debugfs_attr_read
```
**Symbols:**

```
ffffffff812707e0-ffffffff812708c7: simple_attr_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
ssize_t simple_attr_read(struct file *file, char *buf, size_t len, loff_t *ppos);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/libfs.c (ffffffff8127e1e0)
Location: fs/libfs.c:825
Inline: False
Direct callers:
  - fs/debugfs/file.c:debugfs_attr_read
```
**Symbols:**

```
ffffffff8127e1e0-ffffffff8127e2c9: simple_attr_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
ssize_t simple_attr_read(struct file *file, char *buf, size_t len, loff_t *ppos);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/libfs.c (ffffffff812a0cc0)
Location: fs/libfs.c:825
Inline: False
Direct callers:
  - fs/debugfs/file.c:debugfs_attr_read
```
**Symbols:**

```
ffffffff812a0cc0-ffffffff812a0dae: simple_attr_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
ssize_t simple_attr_read(struct file *file, char *buf, size_t len, loff_t *ppos);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/libfs.c (ffffffff812c7820)
Location: fs/libfs.c:825
Inline: False
Direct callers:
  - fs/debugfs/file.c:debugfs_attr_read
```
**Symbols:**

```
ffffffff812c7820-ffffffff812c790c: simple_attr_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
ssize_t simple_attr_read(struct file *file, char *buf, size_t len, loff_t *ppos);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/libfs.c (ffffffff812dca20)
Location: fs/libfs.c:825
Inline: False
Direct callers:
  - fs/debugfs/file.c:debugfs_attr_read
```
**Symbols:**

```
ffffffff812dca20-ffffffff812dcb0c: simple_attr_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
ssize_t simple_attr_read(struct file *file, char *buf, size_t len, loff_t *ppos);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/libfs.c (ffffffff812fb0e0)
Location: fs/libfs.c:844
Inline: False
Direct callers:
  - fs/debugfs/file.c:debugfs_attr_read
```
**Symbols:**

```
ffffffff812fb0e0-ffffffff812fb1cc: simple_attr_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
ssize_t simple_attr_read(struct file *file, char *buf, size_t len, loff_t *ppos);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/libfs.c (ffffffff8130c480)
Location: fs/libfs.c:882
Inline: False
Direct callers:
  - fs/debugfs/file.c:debugfs_attr_read
```
**Symbols:**

```
ffffffff8130c480-ffffffff8130c573: simple_attr_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
ssize_t simple_attr_read(struct file *file, char *buf, size_t len, loff_t *ppos);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/libfs.c (ffffffff81345cb0)
Location: fs/libfs.c:918
Inline: False
Direct callers:
  - fs/debugfs/file.c:debugfs_attr_read
```
**Symbols:**

```
ffffffff81345cb0-ffffffff81345da3: simple_attr_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
ssize_t simple_attr_read(struct file *file, char *buf, size_t len, loff_t *ppos);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/libfs.c (0)
Location: fs/libfs.c:920
Inline: False
Direct callers:
  - fs/debugfs/file.c:debugfs_attr_read
```
**Symbols:**

```
ffffffff81bea832-ffffffff81bea84a: simple_attr_read.cold (STB_LOCAL)
ffffffff81352160-ffffffff81352267: simple_attr_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
ssize_t simple_attr_read(struct file *file, char *buf, size_t len, loff_t *ppos);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/libfs.c (0)
Location: fs/libfs.c:923
Inline: False
Direct callers:
  - fs/debugfs/file.c:debugfs_attr_read
```
**Symbols:**

```
ffffffff81bdc891-ffffffff81bdc8a9: simple_attr_read.cold (STB_LOCAL)
ffffffff813590e0-ffffffff813591e7: simple_attr_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
ssize_t simple_attr_read(struct file *file, char *buf, size_t len, loff_t *ppos);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/libfs.c (0)
Location: fs/libfs.c:932
Inline: False
Direct callers:
  - fs/debugfs/file.c:debugfs_attr_read
```
**Symbols:**

```
ffffffff81cc4107-ffffffff81cc411f: simple_attr_read.cold (STB_LOCAL)
ffffffff813a7480-ffffffff813a7587: simple_attr_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
ssize_t simple_attr_read(struct file *file, char *buf, size_t len, loff_t *ppos);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/libfs.c (0)
Location: fs/libfs.c:959
Inline: False
Direct callers:
  - fs/debugfs/file.c:debugfs_attr_read
```
**Symbols:**

```
ffffffff81e76997-ffffffff81e769af: simple_attr_read.cold (STB_LOCAL)
ffffffff8142b4d0-ffffffff8142b5f8: simple_attr_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
ssize_t simple_attr_read(struct file *file, char *buf, size_t len, loff_t *ppos);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/libfs.c (ffffffff814b8690)
Location: fs/libfs.c:960
Inline: False
Direct callers:
  - fs/debugfs/file.c:debugfs_attr_read
```
**Symbols:**

```
ffffffff814b8690-ffffffff814b87c7: simple_attr_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
ssize_t simple_attr_read(struct file *file, char *buf, size_t len, loff_t *ppos);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/libfs.c (ffffffff814ed8a0)
Location: fs/libfs.c:955
Inline: False
Direct callers:
  - fs/debugfs/file.c:debugfs_attr_read
```
**Symbols:**

```
ffffffff814ed8a0-ffffffff814ed9da: simple_attr_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
ssize_t simple_attr_read(struct file *file, char *buf, size_t len, loff_t *ppos);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/libfs.c (ffffffff81521600)
Location: fs/libfs.c:1225
Inline: False
Direct callers:
  - fs/debugfs/file.c:debugfs_attr_read
```
**Symbols:**

```
ffffffff81521600-ffffffff8152173a: simple_attr_read (STB_GLOBAL)
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
ssize_t simple_attr_read(struct file *file, char *buf, size_t len, loff_t *ppos);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/libfs.c (ffff8000103c1d18)
Location: fs/libfs.c:882
Inline: False
Direct callers:
  - fs/debugfs/file.c:debugfs_attr_read
```
**Symbols:**

```
ffff8000103c1d18-ffff8000103c1e38: simple_attr_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
ssize_t simple_attr_read(struct file *file, char *buf, size_t len, loff_t *ppos);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/libfs.c (c059e38c)
Location: fs/libfs.c:882
Inline: False
Direct callers:
  - fs/debugfs/file.c:debugfs_attr_read
```
**Symbols:**

```
c059e38c-c059e498: simple_attr_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
ssize_t simple_attr_read(struct file *file, char *buf, size_t len, loff_t *ppos);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/libfs.c (c0000000004c0fb0)
Location: fs/libfs.c:882
Inline: False
Direct callers:
  - fs/debugfs/file.c:debugfs_attr_read
```
**Symbols:**

```
c0000000004c0fb0-c0000000004c112c: simple_attr_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
ssize_t simple_attr_read(struct file *file, char *buf, size_t len, loff_t *ppos);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/libfs.c (ffffffe000281ff6)
Location: fs/libfs.c:882
Inline: False
Direct callers:
  - fs/debugfs/file.c:debugfs_attr_read
```
**Symbols:**

```
ffffffe000281ff6-ffffffe0002820b4: simple_attr_read (STB_GLOBAL)
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
ssize_t simple_attr_read(struct file *file, char *buf, size_t len, loff_t *ppos);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/libfs.c (ffffffff81304a60)
Location: fs/libfs.c:882
Inline: False
Direct callers:
  - fs/debugfs/file.c:debugfs_attr_read
```
**Symbols:**

```
ffffffff81304a60-ffffffff81304b53: simple_attr_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
ssize_t simple_attr_read(struct file *file, char *buf, size_t len, loff_t *ppos);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/libfs.c (ffffffff812f5680)
Location: fs/libfs.c:882
Inline: False
Direct callers:
  - fs/debugfs/file.c:debugfs_attr_read
```
**Symbols:**

```
ffffffff812f5680-ffffffff812f5773: simple_attr_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
ssize_t simple_attr_read(struct file *file, char *buf, size_t len, loff_t *ppos);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/libfs.c (ffffffff81302850)
Location: fs/libfs.c:882
Inline: False
Direct callers:
  - fs/debugfs/file.c:debugfs_attr_read
```
**Symbols:**

```
ffffffff81302850-ffffffff81302943: simple_attr_read (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
ssize_t simple_attr_read(struct file *file, char *buf, size_t len, loff_t *ppos);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/libfs.c (ffffffff81314560)
Location: fs/libfs.c:882
Inline: False
Direct callers:
  - fs/debugfs/file.c:debugfs_attr_read
```
**Symbols:**

```
ffffffff81314560-ffffffff81314653: simple_attr_read (STB_GLOBAL)
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
