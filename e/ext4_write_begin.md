# Function: <code>ext4_write_begin</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int ext4_write_begin(struct file *file, struct address_space *mapping, loff_t pos, unsigned int len, unsigned int flags, struct page **pagep, void **fsdata);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff8129d010)
Location: fs/ext4/inode.c:1001
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_da_write_begin
```
**Symbols:**

```
ffffffff8129d010-ffffffff8129d41b: ext4_write_begin (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int ext4_write_begin(struct file *file, struct address_space *mapping, loff_t pos, unsigned int len, unsigned int flags, struct page **pagep, void **fsdata);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff812caad0)
Location: fs/ext4/inode.c:1166
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_da_write_begin
```
**Symbols:**

```
ffffffff812caad0-ffffffff812cb04f: ext4_write_begin (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int ext4_write_begin(struct file *file, struct address_space *mapping, loff_t pos, unsigned int len, unsigned int flags, struct page **pagep, void **fsdata);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff812e0770)
Location: fs/ext4/inode.c:1180
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_da_write_begin
```
**Symbols:**

```
ffffffff812e0770-ffffffff812e0d10: ext4_write_begin (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int ext4_write_begin(struct file *file, struct address_space *mapping, loff_t pos, unsigned int len, unsigned int flags, struct page **pagep, void **fsdata);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff81304b90)
Location: fs/ext4/inode.c:1230
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_da_write_begin
```
**Symbols:**

```
ffffffff81304b90-ffffffff81305080: ext4_write_begin (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int ext4_write_begin(struct file *file, struct address_space *mapping, loff_t pos, unsigned int len, unsigned int flags, struct page **pagep, void **fsdata);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff813295a0)
Location: fs/ext4/inode.c:1240
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_da_write_begin
```
**Symbols:**

```
ffffffff813295a0-ffffffff81329b46: ext4_write_begin (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int ext4_write_begin(struct file *file, struct address_space *mapping, loff_t pos, unsigned int len, unsigned int flags, struct page **pagep, void **fsdata);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff81357910)
Location: fs/ext4/inode.c:1241
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_da_write_begin
```
**Symbols:**

```
ffffffff81357910-ffffffff81357eca: ext4_write_begin (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int ext4_write_begin(struct file *file, struct address_space *mapping, loff_t pos, unsigned int len, unsigned int flags, struct page **pagep, void **fsdata);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff8136fc40)
Location: fs/ext4/inode.c:1241
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_da_write_begin
```
**Symbols:**

```
ffffffff8136fc40-ffffffff813701fa: ext4_write_begin (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int ext4_write_begin(struct file *file, struct address_space *mapping, loff_t pos, unsigned int len, unsigned int flags, struct page **pagep, void **fsdata);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff81399190)
Location: fs/ext4/inode.c:1257
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_da_write_begin
```
**Symbols:**

```
ffffffff81399190-ffffffff8139972f: ext4_write_begin (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int ext4_write_begin(struct file *file, struct address_space *mapping, loff_t pos, unsigned int len, unsigned int flags, struct page **pagep, void **fsdata);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff813b1c10)
Location: fs/ext4/inode.c:1266
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_da_write_begin
```
**Symbols:**

```
ffffffff813b1c10-ffffffff813b21dd: ext4_write_begin (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int ext4_write_begin(struct file *file, struct address_space *mapping, loff_t pos, unsigned int len, unsigned int flags, struct page **pagep, void **fsdata);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff813fd8c0)
Location: fs/ext4/inode.c:1115
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_da_write_begin
```
**Symbols:**

```
ffffffff813fd8c0-ffffffff813fde3e: ext4_write_begin (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int ext4_write_begin(struct file *file, struct address_space *mapping, loff_t pos, unsigned int len, unsigned int flags, struct page **pagep, void **fsdata);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff81410040)
Location: fs/ext4/inode.c:1132
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_da_write_begin
```
**Symbols:**

```
ffffffff81410040-ffffffff8141058f: ext4_write_begin (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int ext4_write_begin(struct file *file, struct address_space *mapping, loff_t pos, unsigned int len, unsigned int flags, struct page **pagep, void **fsdata);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff81416400)
Location: fs/ext4/inode.c:1131
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_da_write_begin
```
**Symbols:**

```
ffffffff81416400-ffffffff8141694f: ext4_write_begin (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int ext4_write_begin(struct file *file, struct address_space *mapping, loff_t pos, unsigned int len, unsigned int flags, struct page **pagep, void **fsdata);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff81469980)
Location: fs/ext4/inode.c:1133
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_da_write_begin
```
**Symbols:**

```
ffffffff81469980-ffffffff81469ecb: ext4_write_begin (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int ext4_write_begin(struct file *file, struct address_space *mapping, loff_t pos, unsigned int len, struct page **pagep, void **fsdata);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff814e9790)
Location: fs/ext4/inode.c:1146
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_da_write_begin
```
**Symbols:**

```
ffffffff814e9790-ffffffff814e9de6: ext4_write_begin (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int ext4_write_begin(struct file *file, struct address_space *mapping, loff_t pos, unsigned int len, struct page **pagep, void **fsdata);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff815832b0)
Location: fs/ext4/inode.c:1152
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_da_write_begin
```
**Symbols:**

```
ffffffff815832b0-ffffffff815838fe: ext4_write_begin (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int ext4_write_begin(struct file *file, struct address_space *mapping, loff_t pos, unsigned int len, struct page **pagep, void **fsdata);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff815b9e70)
Location: fs/ext4/inode.c:1105
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_da_write_begin
```
**Symbols:**

```
ffffffff815b9e70-ffffffff815ba2e9: ext4_write_begin (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int ext4_write_begin(struct file *file, struct address_space *mapping, loff_t pos, unsigned int len, struct page **pagep, void **fsdata);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff815f2be0)
Location: fs/ext4/inode.c:1117
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_da_write_begin
```
**Symbols:**

```
ffffffff815f2be0-ffffffff815f3059: ext4_write_begin (STB_LOCAL)
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
int ext4_write_begin(struct file *file, struct address_space *mapping, loff_t pos, unsigned int len, unsigned int flags, struct page **pagep, void **fsdata);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffff800010486560)
Location: fs/ext4/inode.c:1266
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_da_write_begin
```
**Symbols:**

```
ffff800010486560-ffff800010486b00: ext4_write_begin (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int ext4_write_begin(struct file *file, struct address_space *mapping, loff_t pos, unsigned int len, unsigned int flags, struct page **pagep, void **fsdata);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (c0648420)
Location: fs/ext4/inode.c:1266
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_da_write_begin
```
**Symbols:**

```
c0648420-c0648a3c: ext4_write_begin (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int ext4_write_begin(struct file *file, struct address_space *mapping, loff_t pos, unsigned int len, unsigned int flags, struct page **pagep, void **fsdata);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (c0000000005ac290)
Location: fs/ext4/inode.c:1266
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_da_write_begin
```
**Symbols:**

```
c0000000005ac290-c0000000005acafc: ext4_write_begin (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int ext4_write_begin(struct file *file, struct address_space *mapping, loff_t pos, unsigned int len, unsigned int flags, struct page **pagep, void **fsdata);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffe00030e586)
Location: fs/ext4/inode.c:1266
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_da_write_begin
```
**Symbols:**

```
ffffffe00030e586-ffffffe00030ea34: ext4_write_begin (STB_LOCAL)
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
int ext4_write_begin(struct file *file, struct address_space *mapping, loff_t pos, unsigned int len, unsigned int flags, struct page **pagep, void **fsdata);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff813aa1f0)
Location: fs/ext4/inode.c:1266
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_da_write_begin
```
**Symbols:**

```
ffffffff813aa1f0-ffffffff813aa7bd: ext4_write_begin (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int ext4_write_begin(struct file *file, struct address_space *mapping, loff_t pos, unsigned int len, unsigned int flags, struct page **pagep, void **fsdata);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff8139ac80)
Location: fs/ext4/inode.c:1266
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_da_write_begin
```
**Symbols:**

```
ffffffff8139ac80-ffffffff8139b24d: ext4_write_begin (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int ext4_write_begin(struct file *file, struct address_space *mapping, loff_t pos, unsigned int len, unsigned int flags, struct page **pagep, void **fsdata);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff813a7a50)
Location: fs/ext4/inode.c:1266
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_da_write_begin
```
**Symbols:**

```
ffffffff813a7a50-ffffffff813a801d: ext4_write_begin (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int ext4_write_begin(struct file *file, struct address_space *mapping, loff_t pos, unsigned int len, unsigned int flags, struct page **pagep, void **fsdata);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff813bc2b0)
Location: fs/ext4/inode.c:1266
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_da_write_begin
```
**Symbols:**

```
ffffffff813bc2b0-ffffffff813bc891: ext4_write_begin (STB_LOCAL)
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
<details>
<summary>Changed between <code>5.15</code> and <code>5.19</code> ⚠️</summary>
<ul>
<li>
<b>Param removed. </b>
<code>unsigned int flags</code>
</li>
<li>
<b>Param reordered. </b>
<code>file, mapping, pos, len, flags, pagep, fsdata</code> ➡️ <code>file, mapping, pos, len, pagep, fsdata</code>
</li>
</ul>
</details>
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
