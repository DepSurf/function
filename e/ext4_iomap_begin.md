# Function: <code>ext4_iomap_begin</code>

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
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int ext4_iomap_begin(struct inode *inode, loff_t offset, loff_t length, unsigned int flags, struct iomap *iomap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff812dc490)
Location: fs/ext4/inode.c:3288
Inline: False
```
**Symbols:**

```
ffffffff812dc490-ffffffff812dc763: ext4_iomap_begin (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int ext4_iomap_begin(struct inode *inode, loff_t offset, loff_t length, unsigned int flags, struct iomap *iomap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff81300bf0)
Location: fs/ext4/inode.c:3404
Inline: False
```
**Symbols:**

```
ffffffff81300bf0-ffffffff81300ebd: ext4_iomap_begin (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int ext4_iomap_begin(struct inode *inode, loff_t offset, loff_t length, unsigned int flags, struct iomap *iomap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff81325440)
Location: fs/ext4/inode.c:3409
Inline: False
```
**Symbols:**

```
ffffffff81325440-ffffffff81325870: ext4_iomap_begin (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int ext4_iomap_begin(struct inode *inode, loff_t offset, loff_t length, unsigned int flags, struct iomap *iomap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff813536b0)
Location: fs/ext4/inode.c:3410
Inline: False
```
**Symbols:**

```
ffffffff813536b0-ffffffff81353afb: ext4_iomap_begin (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int ext4_iomap_begin(struct inode *inode, loff_t offset, loff_t length, unsigned int flags, struct iomap *iomap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff8136b7e0)
Location: fs/ext4/inode.c:3442
Inline: False
```
**Symbols:**

```
ffffffff8136b7e0-ffffffff8136bc33: ext4_iomap_begin (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int ext4_iomap_begin(struct inode *inode, loff_t offset, loff_t length, unsigned int flags, struct iomap *iomap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff81394d60)
Location: fs/ext4/inode.c:3455
Inline: False
```
**Symbols:**

```
ffffffff81394d60-ffffffff813951c3: ext4_iomap_begin (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int ext4_iomap_begin(struct inode *inode, loff_t offset, loff_t length, unsigned int flags, struct iomap *iomap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff813ad6e0)
Location: fs/ext4/inode.c:3418
Inline: False
```
**Symbols:**

```
ffffffff813ad6e0-ffffffff813adb5c: ext4_iomap_begin (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int ext4_iomap_begin(struct inode *inode, loff_t offset, loff_t length, unsigned int flags, struct iomap *iomap, struct iomap *srcmap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff813f9a00)
Location: fs/ext4/inode.c:3419
Inline: False
```
**Symbols:**

```
ffffffff813f9a00-ffffffff813f9afb: ext4_iomap_begin (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int ext4_iomap_begin(struct inode *inode, loff_t offset, loff_t length, unsigned int flags, struct iomap *iomap, struct iomap *srcmap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff8140bff0)
Location: fs/ext4/inode.c:3445
Inline: False
```
**Symbols:**

```
ffffffff8140bff0-ffffffff8140c117: ext4_iomap_begin (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int ext4_iomap_begin(struct inode *inode, loff_t offset, loff_t length, unsigned int flags, struct iomap *iomap, struct iomap *srcmap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff81412010)
Location: fs/ext4/inode.c:3444
Inline: False
```
**Symbols:**

```
ffffffff81412010-ffffffff8141229f: ext4_iomap_begin (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int ext4_iomap_begin(struct inode *inode, loff_t offset, loff_t length, unsigned int flags, struct iomap *iomap, struct iomap *srcmap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/inode.c (0)
Location: fs/ext4/inode.c:3367
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_iomap_overwrite_begin
```
**Symbols:**

```
ffffffff81464da0-ffffffff8146507f: ext4_iomap_begin (STB_LOCAL)
ffffffff81ccac7b-ffffffff81ccacee: ext4_iomap_begin.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int ext4_iomap_begin(struct inode *inode, loff_t offset, loff_t length, unsigned int flags, struct iomap *iomap, struct iomap *srcmap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/inode.c (0)
Location: fs/ext4/inode.c:3423
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_iomap_overwrite_begin
```
**Symbols:**

```
ffffffff814e4650-ffffffff814e4954: ext4_iomap_begin (STB_LOCAL)
ffffffff81e7dab9-ffffffff81e7db6a: ext4_iomap_begin.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int ext4_iomap_begin(struct inode *inode, loff_t offset, loff_t length, unsigned int flags, struct iomap *iomap, struct iomap *srcmap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/inode.c (0)
Location: fs/ext4/inode.c:3511
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_iomap_overwrite_begin
```
**Symbols:**

```
ffffffff8157dbb0-ffffffff8157deb8: ext4_iomap_begin (STB_LOCAL)
ffffffff8206e023-ffffffff8206e0d3: ext4_iomap_begin.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int ext4_iomap_begin(struct inode *inode, loff_t offset, loff_t length, unsigned int flags, struct iomap *iomap, struct iomap *srcmap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/inode.c (0)
Location: fs/ext4/inode.c:3294
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_iomap_overwrite_begin
```
**Symbols:**

```
ffffffff815b4ea0-ffffffff815b51c3: ext4_iomap_begin (STB_LOCAL)
ffffffff820edd02-ffffffff820edda5: ext4_iomap_begin.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int ext4_iomap_begin(struct inode *inode, loff_t offset, loff_t length, unsigned int flags, struct iomap *iomap, struct iomap *srcmap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/inode.c (0)
Location: fs/ext4/inode.c:3336
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_iomap_overwrite_begin
```
**Symbols:**

```
ffffffff815edc40-ffffffff815edf63: ext4_iomap_begin (STB_LOCAL)
ffffffff821cae5f-ffffffff821caf02: ext4_iomap_begin.cold (STB_LOCAL)
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
int ext4_iomap_begin(struct inode *inode, loff_t offset, loff_t length, unsigned int flags, struct iomap *iomap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffff800010481fc8)
Location: fs/ext4/inode.c:3418
Inline: False
```
**Symbols:**

```
ffff800010481fc8-ffff8000104823f0: ext4_iomap_begin (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int ext4_iomap_begin(struct inode *inode, loff_t offset, loff_t length, unsigned int flags, struct iomap *iomap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (c064324c)
Location: fs/ext4/inode.c:3418
Inline: False
```
**Symbols:**

```
c064324c-c06438d8: ext4_iomap_begin (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int ext4_iomap_begin(struct inode *inode, loff_t offset, loff_t length, unsigned int flags, struct iomap *iomap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (c0000000005a6820)
Location: fs/ext4/inode.c:3418
Inline: False
```
**Symbols:**

```
c0000000005a6820-c0000000005a6df4: ext4_iomap_begin (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int ext4_iomap_begin(struct inode *inode, loff_t offset, loff_t length, unsigned int flags, struct iomap *iomap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffe00030aa84)
Location: fs/ext4/inode.c:3418
Inline: False
```
**Symbols:**

```
ffffffe00030aa84-ffffffe00030ae1c: ext4_iomap_begin (STB_LOCAL)
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
int ext4_iomap_begin(struct inode *inode, loff_t offset, loff_t length, unsigned int flags, struct iomap *iomap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff813a5cc0)
Location: fs/ext4/inode.c:3418
Inline: False
```
**Symbols:**

```
ffffffff813a5cc0-ffffffff813a613c: ext4_iomap_begin (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int ext4_iomap_begin(struct inode *inode, loff_t offset, loff_t length, unsigned int flags, struct iomap *iomap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff81396750)
Location: fs/ext4/inode.c:3418
Inline: False
```
**Symbols:**

```
ffffffff81396750-ffffffff81396bcc: ext4_iomap_begin (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int ext4_iomap_begin(struct inode *inode, loff_t offset, loff_t length, unsigned int flags, struct iomap *iomap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff813a3520)
Location: fs/ext4/inode.c:3418
Inline: False
```
**Symbols:**

```
ffffffff813a3520-ffffffff813a399c: ext4_iomap_begin (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int ext4_iomap_begin(struct inode *inode, loff_t offset, loff_t length, unsigned int flags, struct iomap *iomap);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff813b7c10)
Location: fs/ext4/inode.c:3418
Inline: False
```
**Symbols:**

```
ffffffff813b7c10-ffffffff813b808c: ext4_iomap_begin (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
<details>
<summary>Changed between <code>5.4</code> and <code>5.8</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct iomap *srcmap</code>
</li>
</ul>
</details>
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
