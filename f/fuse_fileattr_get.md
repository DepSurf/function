# Function: <code>fuse_fileattr_get</code>

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
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int fuse_fileattr_get(struct dentry *dentry, struct fileattr *fa);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/ioctl.c (ffffffff814a2030)
Location: fs/fuse/ioctl.c:419
Inline: False
```
**Symbols:**

```
ffffffff814a2030-ffffffff814a216a: fuse_fileattr_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int fuse_fileattr_get(struct dentry *dentry, struct fileattr *fa);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/ioctl.c (ffffffff814fa0d0)
Location: fs/fuse/ioctl.c:422
Inline: False
```
**Symbols:**

```
ffffffff814fa0d0-ffffffff814fa20a: fuse_fileattr_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int fuse_fileattr_get(struct dentry *dentry, struct fileattr *fa);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/ioctl.c (ffffffff8158a350)
Location: fs/fuse/ioctl.c:433
Inline: False
```
**Symbols:**

```
ffffffff8158a350-ffffffff8158a4ba: fuse_fileattr_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int fuse_fileattr_get(struct dentry *dentry, struct fileattr *fa);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/ioctl.c (ffffffff81630ac0)
Location: fs/fuse/ioctl.c:439
Inline: False
```
**Symbols:**

```
ffffffff81630ac0-ffffffff81630bf6: fuse_fileattr_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int fuse_fileattr_get(struct dentry *dentry, struct fileattr *fa);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/ioctl.c (ffffffff81668cf0)
Location: fs/fuse/ioctl.c:444
Inline: False
```
**Symbols:**

```
ffffffff81668cf0-ffffffff81668e24: fuse_fileattr_get (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int fuse_fileattr_get(struct dentry *dentry, struct fileattr *fa);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/ioctl.c (ffffffff816a2ff0)
Location: fs/fuse/ioctl.c:444
Inline: False
```
**Symbols:**

```
ffffffff816a2ff0-ffffffff816a3124: fuse_fileattr_get (STB_GLOBAL)
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
