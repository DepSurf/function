# Function: <code>ioc_qos_write</code>

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
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
ssize_t ioc_qos_write(struct kernfs_open_file *of, char *input, size_t nbytes, loff_t off);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-iocost.c (ffffffff81512410)
Location: block/blk-iocost.c:2182
Inline: False
```
**Symbols:**

```
ffffffff81512410-ffffffff815127ea: ioc_qos_write (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
ssize_t ioc_qos_write(struct kernfs_open_file *of, char *input, size_t nbytes, loff_t off);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-iocost.c (ffffffff815738f0)
Location: block/blk-iocost.c:2248
Inline: False
```
**Symbols:**

```
ffffffff815738f0-ffffffff81573d22: ioc_qos_write (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
ssize_t ioc_qos_write(struct kernfs_open_file *of, char *input, size_t nbytes, loff_t off);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-iocost.c (ffffffff815906f0)
Location: block/blk-iocost.c:3152
Inline: False
```
**Symbols:**

```
ffffffff815906f0-ffffffff81590b2a: ioc_qos_write (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
ssize_t ioc_qos_write(struct kernfs_open_file *of, char *input, size_t nbytes, loff_t off);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-iocost.c (ffffffff815974a0)
Location: block/blk-iocost.c:3159
Inline: False
```
**Symbols:**

```
ffffffff815974a0-ffffffff81597883: ioc_qos_write (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
ssize_t ioc_qos_write(struct kernfs_open_file *of, char *input, size_t nbytes, loff_t off);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/blk-iocost.c (0)
Location: block/blk-iocost.c:3161
Inline: False
```
**Symbols:**

```
ffffffff815feb20-ffffffff815fef91: ioc_qos_write (STB_LOCAL)
ffffffff81cd9f13-ffffffff81cd9f27: ioc_qos_write.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
ssize_t ioc_qos_write(struct kernfs_open_file *of, char *input, size_t nbytes, loff_t off);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/blk-iocost.c (0)
Location: block/blk-iocost.c:3169
Inline: False
```
**Symbols:**

```
ffffffff816aeb10-ffffffff816aeff2: ioc_qos_write (STB_LOCAL)
ffffffff81e8d8b6-ffffffff81e8d8ca: ioc_qos_write.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
ssize_t ioc_qos_write(struct kernfs_open_file *of, char *input, size_t nbytes, loff_t off);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/blk-iocost.c (0)
Location: block/blk-iocost.c:3177
Inline: False
```
**Symbols:**

```
ffffffff8176d480-ffffffff8176d9ba: ioc_qos_write (STB_LOCAL)
ffffffff82076e4f-ffffffff82076e63: ioc_qos_write.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
ssize_t ioc_qos_write(struct kernfs_open_file *of, char *input, size_t nbytes, loff_t off);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/blk-iocost.c (0)
Location: block/blk-iocost.c:3198
Inline: False
```
**Symbols:**

```
ffffffff817ad2f0-ffffffff817ad928: ioc_qos_write (STB_LOCAL)
ffffffff820f6cab-ffffffff820f6ce7: ioc_qos_write.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
ssize_t ioc_qos_write(struct kernfs_open_file *of, char *input, size_t nbytes, loff_t off);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In block/blk-iocost.c (0)
Location: block/blk-iocost.c:3205
Inline: False
```
**Symbols:**

```
ffffffff817f1100-ffffffff817f173e: ioc_qos_write (STB_LOCAL)
ffffffff821d40f9-ffffffff821d4135: ioc_qos_write.cold (STB_LOCAL)
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
ssize_t ioc_qos_write(struct kernfs_open_file *of, char *input, size_t nbytes, loff_t off);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-iocost.c (ffff8000106166a0)
Location: block/blk-iocost.c:2182
Inline: False
```
**Symbols:**

```
ffff8000106166a0-ffff800010616b2c: ioc_qos_write (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
ssize_t ioc_qos_write(struct kernfs_open_file *of, char *input, size_t nbytes, loff_t off);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-iocost.c (c07c0308)
Location: block/blk-iocost.c:2182
Inline: False
```
**Symbols:**

```
c07c0308-c07c07a8: ioc_qos_write (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
ssize_t ioc_qos_write(struct kernfs_open_file *of, char *input, size_t nbytes, loff_t off);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-iocost.c (c0000000007b5b60)
Location: block/blk-iocost.c:2182
Inline: False
```
**Symbols:**

```
c0000000007b5b60-c0000000007b6188: ioc_qos_write (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
ssize_t ioc_qos_write(struct kernfs_open_file *of, char *input, size_t nbytes, loff_t off);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-iocost.c (ffffffe00044cf96)
Location: block/blk-iocost.c:2182
Inline: False
```
**Symbols:**

```
ffffffe00044cf96-ffffffe00044d362: ioc_qos_write (STB_LOCAL)
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
ssize_t ioc_qos_write(struct kernfs_open_file *of, char *input, size_t nbytes, loff_t off);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-iocost.c (ffffffff8150a9f0)
Location: block/blk-iocost.c:2182
Inline: False
```
**Symbols:**

```
ffffffff8150a9f0-ffffffff8150adca: ioc_qos_write (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
ssize_t ioc_qos_write(struct kernfs_open_file *of, char *input, size_t nbytes, loff_t off);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-iocost.c (ffffffff814fae60)
Location: block/blk-iocost.c:2182
Inline: False
```
**Symbols:**

```
ffffffff814fae60-ffffffff814fb22e: ioc_qos_write (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
ssize_t ioc_qos_write(struct kernfs_open_file *of, char *input, size_t nbytes, loff_t off);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-iocost.c (ffffffff81506a80)
Location: block/blk-iocost.c:2182
Inline: False
```
**Symbols:**

```
ffffffff81506a80-ffffffff81506e5a: ioc_qos_write (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
ssize_t ioc_qos_write(struct kernfs_open_file *of, char *input, size_t nbytes, loff_t off);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/blk-iocost.c (ffffffff8151fd50)
Location: block/blk-iocost.c:2182
Inline: False
```
**Symbols:**

```
ffffffff8151fd50-ffffffff81520118: ioc_qos_write (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
