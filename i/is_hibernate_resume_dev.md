# Function: <code>is_hibernate_resume_dev</code>

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
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int is_hibernate_resume_dev(const struct inode *bd_inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/power/user.c (ffffffff8111c120)
Location: kernel/power/user.c:41
Inline: False
Direct callers:
  - fs/block_dev.c:blkdev_write_iter
```
**Symbols:**

```
ffffffff8111c120-ffffffff8111c14e: is_hibernate_resume_dev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int is_hibernate_resume_dev(dev_t dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/power/user.c (ffffffff81116a80)
Location: kernel/power/user.c:41
Inline: False
Direct callers:
  - fs/block_dev.c:blkdev_write_iter
```
**Symbols:**

```
ffffffff81116a80-ffffffff81116aac: is_hibernate_resume_dev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int is_hibernate_resume_dev(dev_t dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/power/user.c (ffffffff811171b0)
Location: kernel/power/user.c:41
Inline: False
Direct callers:
  - fs/block_dev.c:blkdev_write_iter
```
**Symbols:**

```
ffffffff811171b0-ffffffff811171dc: is_hibernate_resume_dev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int is_hibernate_resume_dev(dev_t dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/power/user.c (ffffffff81137540)
Location: kernel/power/user.c:41
Inline: False
Direct callers:
  - block/fops.c:blkdev_write_iter
```
**Symbols:**

```
ffffffff81137540-ffffffff8113756c: is_hibernate_resume_dev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int is_hibernate_resume_dev(dev_t dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/power/user.c (ffffffff81159b60)
Location: kernel/power/user.c:42
Inline: False
Direct callers:
  - block/fops.c:blkdev_write_iter
```
**Symbols:**

```
ffffffff81159b60-ffffffff81159b92: is_hibernate_resume_dev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int is_hibernate_resume_dev(dev_t dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/power/user.c (ffffffff8118bdf0)
Location: kernel/power/user.c:42
Inline: False
Direct callers:
  - block/fops.c:blkdev_write_iter
```
**Symbols:**

```
ffffffff8118bdf0-ffffffff8118be22: is_hibernate_resume_dev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int is_hibernate_resume_dev(dev_t dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/power/user.c (ffffffff8119d510)
Location: kernel/power/user.c:42
Inline: False
Direct callers:
  - block/fops.c:blkdev_write_iter
```
**Symbols:**

```
ffffffff8119d510-ffffffff8119d542: is_hibernate_resume_dev (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int is_hibernate_resume_dev(dev_t dev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/power/user.c (ffffffff811ac660)
Location: kernel/power/user.c:42
Inline: False
Direct callers:
  - block/fops.c:blkdev_write_iter
```
**Symbols:**

```
ffffffff811ac660-ffffffff811ac692: is_hibernate_resume_dev (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Changed between <code>5.8</code> and <code>5.11</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>dev_t dev</code>
</li>
<li>
<b>Param removed. </b>
<code>const struct inode *bd_inode</code>
</li>
</ul>
</details>
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
