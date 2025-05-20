# Function: <code>fat_fallocate</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
long int fat_fallocate(struct file *file, int mode, loff_t offset, loff_t len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fat/file.c (ffffffff8132e3f0)
Location: fs/fat/file.c:230
Inline: False
```
**Symbols:**

```
ffffffff8132e3f0-ffffffff8132e4db: fat_fallocate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
long int fat_fallocate(struct file *file, int mode, loff_t offset, loff_t len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fat/file.c (ffffffff81344120)
Location: fs/fat/file.c:230
Inline: False
```
**Symbols:**

```
ffffffff81344120-ffffffff8134420b: fat_fallocate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
long int fat_fallocate(struct file *file, int mode, loff_t offset, loff_t len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fat/file.c (ffffffff81358bd0)
Location: fs/fat/file.c:230
Inline: False
```
**Symbols:**

```
ffffffff81358bd0-ffffffff81358cc4: fat_fallocate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
long int fat_fallocate(struct file *file, int mode, loff_t offset, loff_t len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fat/file.c (ffffffff8137d8e0)
Location: fs/fat/file.c:230
Inline: False
```
**Symbols:**

```
ffffffff8137d8e0-ffffffff8137d9d4: fat_fallocate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
long int fat_fallocate(struct file *file, int mode, loff_t offset, loff_t len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fat/file.c (ffffffff813ac350)
Location: fs/fat/file.c:230
Inline: False
```
**Symbols:**

```
ffffffff813ac350-ffffffff813ac431: fat_fallocate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
long int fat_fallocate(struct file *file, int mode, loff_t offset, loff_t len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fat/file.c (ffffffff813c5610)
Location: fs/fat/file.c:263
Inline: False
```
**Symbols:**

```
ffffffff813c5610-ffffffff813c56f1: fat_fallocate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
long int fat_fallocate(struct file *file, int mode, loff_t offset, loff_t len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fat/file.c (ffffffff813f0140)
Location: fs/fat/file.c:270
Inline: False
```
**Symbols:**

```
ffffffff813f0140-ffffffff813f0222: fat_fallocate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
long int fat_fallocate(struct file *file, int mode, loff_t offset, loff_t len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fat/file.c (ffffffff8140a020)
Location: fs/fat/file.c:270
Inline: False
```
**Symbols:**

```
ffffffff8140a020-ffffffff8140a102: fat_fallocate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
long int fat_fallocate(struct file *file, int mode, loff_t offset, loff_t len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fat/file.c (ffffffff81457d10)
Location: fs/fat/file.c:259
Inline: False
```
**Symbols:**

```
ffffffff81457d10-ffffffff81457df1: fat_fallocate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
long int fat_fallocate(struct file *file, int mode, loff_t offset, loff_t len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fat/file.c (ffffffff81474060)
Location: fs/fat/file.c:259
Inline: False
```
**Symbols:**

```
ffffffff81474060-ffffffff81474141: fat_fallocate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
long int fat_fallocate(struct file *file, int mode, loff_t offset, loff_t len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fat/file.c (ffffffff814799d0)
Location: fs/fat/file.c:259
Inline: False
```
**Symbols:**

```
ffffffff814799d0-ffffffff81479ab2: fat_fallocate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
long int fat_fallocate(struct file *file, int mode, loff_t offset, loff_t len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/fat/file.c (0)
Location: fs/fat/file.c:259
Inline: False
```
**Symbols:**

```
ffffffff814d0fb0-ffffffff814d10a3: fat_fallocate (STB_LOCAL)
ffffffff81ccfe25-ffffffff81ccfe3f: fat_fallocate.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
long int fat_fallocate(struct file *file, int mode, loff_t offset, loff_t len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/fat/file.c (0)
Location: fs/fat/file.c:259
Inline: False
```
**Symbols:**

```
ffffffff8155db80-ffffffff8155dc75: fat_fallocate (STB_LOCAL)
ffffffff81e83083-ffffffff81e8309d: fat_fallocate.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
long int fat_fallocate(struct file *file, int mode, loff_t offset, loff_t len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/fat/file.c (0)
Location: fs/fat/file.c:260
Inline: False
```
**Symbols:**

```
ffffffff815ffc00-ffffffff815ffcf5: fat_fallocate (STB_LOCAL)
ffffffff820721f0-ffffffff8207220a: fat_fallocate.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
long int fat_fallocate(struct file *file, int mode, loff_t offset, loff_t len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/fat/file.c (0)
Location: fs/fat/file.c:260
Inline: False
```
**Symbols:**

```
ffffffff81637be0-ffffffff81637cdb: fat_fallocate (STB_LOCAL)
ffffffff820f1e13-ffffffff820f1e2d: fat_fallocate.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
long int fat_fallocate(struct file *file, int mode, loff_t offset, loff_t len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/fat/file.c (0)
Location: fs/fat/file.c:260
Inline: False
```
**Symbols:**

```
ffffffff816710d0-ffffffff816711cb: fat_fallocate (STB_LOCAL)
ffffffff821cf0f5-ffffffff821cf10f: fat_fallocate.cold (STB_LOCAL)
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
long int fat_fallocate(struct file *file, int mode, loff_t offset, loff_t len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fat/file.c (ffff8000104ea440)
Location: fs/fat/file.c:270
Inline: False
```
**Symbols:**

```
ffff8000104ea440-ffff8000104ea534: fat_fallocate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
long int fat_fallocate(struct file *file, int mode, loff_t offset, loff_t len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fat/file.c (c06a8328)
Location: fs/fat/file.c:270
Inline: False
```
**Symbols:**

```
c06a8328-c06a84c4: fat_fallocate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
long int fat_fallocate(struct file *file, int mode, loff_t offset, loff_t len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fat/file.c (c000000000628460)
Location: fs/fat/file.c:270
Inline: False
```
**Symbols:**

```
c000000000628460-c0000000006285c8: fat_fallocate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
long int fat_fallocate(struct file *file, int mode, loff_t offset, loff_t len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fat/file.c (ffffffe00035b2a4)
Location: fs/fat/file.c:270
Inline: False
```
**Symbols:**

```
ffffffe00035b2a4-ffffffe00035b37a: fat_fallocate (STB_LOCAL)
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
long int fat_fallocate(struct file *file, int mode, loff_t offset, loff_t len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fat/file.c (ffffffff81402600)
Location: fs/fat/file.c:270
Inline: False
```
**Symbols:**

```
ffffffff81402600-ffffffff814026e2: fat_fallocate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
long int fat_fallocate(struct file *file, int mode, loff_t offset, loff_t len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fat/file.c (ffffffff813f3080)
Location: fs/fat/file.c:270
Inline: False
```
**Symbols:**

```
ffffffff813f3080-ffffffff813f3162: fat_fallocate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
long int fat_fallocate(struct file *file, int mode, loff_t offset, loff_t len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fat/file.c (ffffffff813ff980)
Location: fs/fat/file.c:270
Inline: False
```
**Symbols:**

```
ffffffff813ff980-ffffffff813ffa62: fat_fallocate (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
long int fat_fallocate(struct file *file, int mode, loff_t offset, loff_t len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fat/file.c (ffffffff814155b0)
Location: fs/fat/file.c:270
Inline: False
```
**Symbols:**

```
ffffffff814155b0-ffffffff81415692: fat_fallocate (STB_LOCAL)
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
