# Function: <code>loop_validate_file</code>

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
int loop_validate_file(struct file *file, struct block_device *bdev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/block/loop.c (ffffffff816a9a00)
Location: drivers/block/loop.c:667
Inline: False
Direct callers:
  - drivers/block/loop.c:lo_ioctl
  - drivers/block/loop.c:lo_ioctl
  - drivers/block/loop.c:lo_ioctl
  - drivers/block/loop.c:lo_ioctl
```
**Symbols:**

```
ffffffff816a9a00-ffffffff816a9ab8: loop_validate_file (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int loop_validate_file(struct file *file, struct block_device *bdev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/block/loop.c (ffffffff816ca640)
Location: drivers/block/loop.c:655
Inline: False
Direct callers:
  - drivers/block/loop.c:lo_ioctl
  - drivers/block/loop.c:lo_ioctl
  - drivers/block/loop.c:lo_ioctl
```
**Symbols:**

```
ffffffff816ca640-ffffffff816ca6f7: loop_validate_file (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int loop_validate_file(struct file *file, struct block_device *bdev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/block/loop.c (ffffffff81705c00)
Location: drivers/block/loop.c:655
Inline: False
Direct callers:
  - drivers/block/loop.c:lo_ioctl
  - drivers/block/loop.c:lo_ioctl
  - drivers/block/loop.c:loop_set_fd
```
**Symbols:**

```
ffffffff81705c00-ffffffff81705c99: loop_validate_file (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int loop_validate_file(struct file *file, struct block_device *bdev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/block/loop.c (ffffffff81729e50)
Location: drivers/block/loop.c:665
Inline: False
Direct callers:
  - drivers/block/loop.c:lo_ioctl
  - drivers/block/loop.c:lo_ioctl
  - drivers/block/loop.c:loop_set_fd
```
**Symbols:**

```
ffffffff81729e50-ffffffff81729ee9: loop_validate_file (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int loop_validate_file(struct file *file, struct block_device *bdev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/block/loop.c (ffffffff817e7dd0)
Location: drivers/block/loop.c:680
Inline: False
Direct callers:
  - drivers/block/loop.c:loop_configure
  - drivers/block/loop.c:loop_change_fd
  - drivers/block/loop.c:loop_change_fd
```
**Symbols:**

```
ffffffff817e7dd0-ffffffff817e7e69: loop_validate_file (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int loop_validate_file(struct file *file, struct block_device *bdev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/block/loop.c (ffffffff817fccf0)
Location: drivers/block/loop.c:678
Inline: False
Direct callers:
  - drivers/block/loop.c:loop_configure
  - drivers/block/loop.c:loop_change_fd
  - drivers/block/loop.c:loop_change_fd
```
**Symbols:**

```
ffffffff817fccf0-ffffffff817fcd8f: loop_validate_file (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int loop_validate_file(struct file *file, struct block_device *bdev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/block/loop.c (ffffffff817e1d90)
Location: drivers/block/loop.c:711
Inline: False
Direct callers:
  - drivers/block/loop.c:loop_configure
  - drivers/block/loop.c:loop_change_fd
```
**Symbols:**

```
ffffffff817e1d90-ffffffff817e1e32: loop_validate_file (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int loop_validate_file(struct file *file, struct block_device *bdev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/block/loop.c (ffffffff8186d7a0)
Location: drivers/block/loop.c:704
Inline: False
Direct callers:
  - drivers/block/loop.c:loop_configure
  - drivers/block/loop.c:loop_change_fd
```
**Symbols:**

```
ffffffff8186d7a0-ffffffff8186d842: loop_validate_file (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int loop_validate_file(struct file *file, struct block_device *bdev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/block/loop.c (ffffffff819b6ae0)
Location: drivers/block/loop.c:532
Inline: False
Direct callers:
  - drivers/block/loop.c:loop_configure
  - drivers/block/loop.c:loop_change_fd
```
**Symbols:**

```
ffffffff819b6ae0-ffffffff819b6b9a: loop_validate_file (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int loop_validate_file(struct file *file, struct block_device *bdev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/block/loop.c (ffffffff81b2bd40)
Location: drivers/block/loop.c:532
Inline: False
Direct callers:
  - drivers/block/loop.c:loop_configure
  - drivers/block/loop.c:loop_change_fd
```
**Symbols:**

```
ffffffff81b2bd40-ffffffff81b2bdfa: loop_validate_file (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int loop_validate_file(struct file *file, struct block_device *bdev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/block/loop.c (ffffffff81b7c040)
Location: drivers/block/loop.c:532
Inline: False
Direct callers:
  - drivers/block/loop.c:loop_configure
  - drivers/block/loop.c:loop_change_fd
```
**Symbols:**

```
ffffffff81b7c040-ffffffff81b7c0f7: loop_validate_file (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int loop_validate_file(struct file *file, struct block_device *bdev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/block/loop.c (ffffffff81bd0070)
Location: drivers/block/loop.c:528
Inline: False
Direct callers:
  - drivers/block/loop.c:loop_configure
  - drivers/block/loop.c:loop_change_fd
```
**Symbols:**

```
ffffffff81bd0070-ffffffff81bd0127: loop_validate_file (STB_LOCAL)
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
int loop_validate_file(struct file *file, struct block_device *bdev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/block/loop.c (ffff800010920a58)
Location: drivers/block/loop.c:665
Inline: False
Direct callers:
  - drivers/block/loop.c:lo_ioctl
  - drivers/block/loop.c:lo_ioctl
  - drivers/block/loop.c:loop_set_fd
```
**Symbols:**

```
ffff800010920a58-ffff800010920b10: loop_validate_file (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int loop_validate_file(struct file *file, struct block_device *bdev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/block/loop.c (c0a056e8)
Location: drivers/block/loop.c:665
Inline: False
Direct callers:
  - drivers/block/loop.c:lo_ioctl
  - drivers/block/loop.c:lo_ioctl
  - drivers/block/loop.c:loop_set_fd
```
**Symbols:**

```
c0a056e8-c0a0579c: loop_validate_file (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int loop_validate_file(struct file *file, struct block_device *bdev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/block/loop.c (c0000000009c48d0)
Location: drivers/block/loop.c:665
Inline: False
Direct callers:
  - drivers/block/loop.c:lo_ioctl
  - drivers/block/loop.c:lo_ioctl
  - drivers/block/loop.c:loop_set_fd
```
**Symbols:**

```
c0000000009c48d0-c0000000009c4980: loop_validate_file (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int loop_validate_file(struct file *file, struct block_device *bdev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/block/loop.c (ffffffe00059f344)
Location: drivers/block/loop.c:665
Inline: False
Direct callers:
  - drivers/block/loop.c:lo_ioctl
  - drivers/block/loop.c:lo_ioctl
  - drivers/block/loop.c:loop_set_fd
```
**Symbols:**

```
ffffffe00059f344-ffffffe00059f3d2: loop_validate_file (STB_LOCAL)
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
int loop_validate_file(struct file *file, struct block_device *bdev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/block/loop.c (ffffffff816efc30)
Location: drivers/block/loop.c:665
Inline: False
Direct callers:
  - drivers/block/loop.c:lo_ioctl
  - drivers/block/loop.c:lo_ioctl
  - drivers/block/loop.c:loop_set_fd
```
**Symbols:**

```
ffffffff816efc30-ffffffff816efcc9: loop_validate_file (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int loop_validate_file(struct file *file, struct block_device *bdev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/block/loop.c (ffffffff816c9d40)
Location: drivers/block/loop.c:665
Inline: False
Direct callers:
  - drivers/block/loop.c:lo_ioctl
  - drivers/block/loop.c:lo_ioctl
  - drivers/block/loop.c:loop_set_fd
```
**Symbols:**

```
ffffffff816c9d40-ffffffff816c9dd9: loop_validate_file (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int loop_validate_file(struct file *file, struct block_device *bdev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/block/loop.c (ffffffff8171d310)
Location: drivers/block/loop.c:665
Inline: False
Direct callers:
  - drivers/block/loop.c:lo_ioctl
  - drivers/block/loop.c:lo_ioctl
  - drivers/block/loop.c:loop_set_fd
```
**Symbols:**

```
ffffffff8171d310-ffffffff8171d3a9: loop_validate_file (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int loop_validate_file(struct file *file, struct block_device *bdev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/block/loop.c (ffffffff81738670)
Location: drivers/block/loop.c:665
Inline: False
Direct callers:
  - drivers/block/loop.c:lo_ioctl
  - drivers/block/loop.c:lo_ioctl
  - drivers/block/loop.c:loop_set_fd
```
**Symbols:**

```
ffffffff81738670-ffffffff81738709: loop_validate_file (STB_LOCAL)
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
