# Function: <code>reconfigure_single</code>

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
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/super.c (ffffffff812cfdd7)
Location: fs/super.c:1367
Inline: True
Inline callers:
  - fs/super.c:mount_single
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/super.c (ffffffff812e19e7)
Location: fs/super.c:1473
Inline: True
Inline callers:
  - fs/super.c:mount_single
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/super.c (ffffffff81318cf7)
Location: fs/super.c:1473
Inline: True
Inline callers:
  - fs/super.c:mount_single
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/super.c (ffffffff81324237)
Location: fs/super.c:1422
Inline: True
Inline callers:
  - fs/super.c:mount_single
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/super.c (ffffffff8132a307)
Location: fs/super.c:1424
Inline: True
Inline callers:
  - fs/super.c:mount_single
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int reconfigure_single(struct super_block *s, int flags, void *data);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/super.c (ffffffff81377937)
Location: fs/super.c:1424
Inline: True
Inline callers:
  - fs/super.c:mount_single
Direct callers:
  - drivers/base/devtmpfs.c:public_dev_mount
```
**Symbols:**

```
ffffffff81377aa0-ffffffff81377b03: reconfigure_single (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
int reconfigure_single(struct super_block *s, int flags, void *data);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/super.c (ffffffff813f6bd5)
Location: fs/super.c:1423
Inline: True
Inline callers:
  - fs/super.c:mount_single
Direct callers:
  - drivers/base/devtmpfs.c:public_dev_mount
```
**Symbols:**

```
ffffffff813f6d70-ffffffff813f6de4: reconfigure_single (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
int reconfigure_single(struct super_block *s, int flags, void *data);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/super.c (ffffffff8147fdf5)
Location: fs/super.c:1428
Inline: True
Inline callers:
  - fs/super.c:mount_single
Direct callers:
  - drivers/base/devtmpfs.c:public_dev_mount
```
**Symbols:**

```
ffffffff8147ffc0-ffffffff81480034: reconfigure_single (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
int reconfigure_single(struct super_block *s, int flags, void *data);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/super.c (ffffffff814b4ae5)
Location: fs/super.c:1445
Inline: True
Inline callers:
  - fs/super.c:mount_single
Direct callers:
  - drivers/base/devtmpfs.c:public_dev_mount
```
**Symbols:**

```
ffffffff814b4cb0-ffffffff814b4d24: reconfigure_single (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
int reconfigure_single(struct super_block *s, int flags, void *data);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/super.c (ffffffff814e6db5)
Location: fs/super.c:1705
Inline: True
Inline callers:
  - fs/super.c:mount_single
Direct callers:
  - drivers/base/devtmpfs.c:public_dev_mount
```
**Symbols:**

```
ffffffff814e6fe0-ffffffff814e7054: reconfigure_single (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/super.c (ffff800010388e34)
Location: fs/super.c:1473
Inline: True
Inline callers:
  - fs/super.c:mount_single
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/super.c (c057140c)
Location: fs/super.c:1473
Inline: True
Inline callers:
  - fs/super.c:mount_single
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/super.c (c00000000047fd78)
Location: fs/super.c:1473
Inline: True
Inline callers:
  - fs/super.c:mount_single
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/super.c (ffffffe00025b346)
Location: fs/super.c:1473
Inline: True
Inline callers:
  - fs/super.c:mount_single
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/super.c (ffffffff812d9fc7)
Location: fs/super.c:1473
Inline: True
Inline callers:
  - fs/super.c:mount_single
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/super.c (ffffffff812cac47)
Location: fs/super.c:1473
Inline: True
Inline callers:
  - fs/super.c:mount_single
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/super.c (ffffffff812d7dd7)
Location: fs/super.c:1473
Inline: True
Inline callers:
  - fs/super.c:mount_single
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/super.c (ffffffff812e8c17)
Location: fs/super.c:1473
Inline: True
Inline callers:
  - fs/super.c:mount_single
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
