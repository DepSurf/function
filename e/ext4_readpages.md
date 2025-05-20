# Function: <code>ext4_readpages</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
int ext4_readpages(struct file *file, struct address_space *mapping, struct list_head *pages, unsigned int nr_pages);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff81296820)
Location: fs/ext4/inode.c:3008
Inline: True
```
**Symbols:**

```
ffffffff81296820-ffffffff81296855: ext4_readpages (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
int ext4_readpages(struct file *file, struct address_space *mapping, struct list_head *pages, unsigned int nr_pages);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff812c3e60)
Location: fs/ext4/inode.c:3197
Inline: True
```
**Symbols:**

```
ffffffff812c3e60-ffffffff812c3e97: ext4_readpages (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
int ext4_readpages(struct file *file, struct address_space *mapping, struct list_head *pages, unsigned int nr_pages);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff812d9510)
Location: fs/ext4/inode.c:3224
Inline: True
```
**Symbols:**

```
ffffffff812d9510-ffffffff812d9547: ext4_readpages (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int ext4_readpages(struct file *file, struct address_space *mapping, struct list_head *pages, unsigned int nr_pages);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff812fd430)
Location: fs/ext4/inode.c:3340
Inline: True
```
**Symbols:**

```
ffffffff812fd430-ffffffff812fd467: ext4_readpages (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int ext4_readpages(struct file *file, struct address_space *mapping, struct list_head *pages, unsigned int nr_pages);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff81321c70)
Location: fs/ext4/inode.c:3333
Inline: True
```
**Symbols:**

```
ffffffff81321c70-ffffffff81321ca7: ext4_readpages (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int ext4_readpages(struct file *file, struct address_space *mapping, struct list_head *pages, unsigned int nr_pages);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff8134f6e0)
Location: fs/ext4/inode.c:3334
Inline: False
```
**Symbols:**

```
ffffffff8134f6e0-ffffffff8134f716: ext4_readpages (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int ext4_readpages(struct file *file, struct address_space *mapping, struct list_head *pages, unsigned int nr_pages);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff813678c0)
Location: fs/ext4/inode.c:3366
Inline: False
```
**Symbols:**

```
ffffffff813678c0-ffffffff813678fc: ext4_readpages (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int ext4_readpages(struct file *file, struct address_space *mapping, struct list_head *pages, unsigned int nr_pages);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff81390bc0)
Location: fs/ext4/inode.c:3379
Inline: False
```
**Symbols:**

```
ffffffff81390bc0-ffffffff81390bfc: ext4_readpages (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int ext4_readpages(struct file *file, struct address_space *mapping, struct list_head *pages, unsigned int nr_pages);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff813a9580)
Location: fs/ext4/inode.c:3342
Inline: False
```
**Symbols:**

```
ffffffff813a9580-ffffffff813a95bc: ext4_readpages (STB_LOCAL)
```
</details>
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
int ext4_readpages(struct file *file, struct address_space *mapping, struct list_head *pages, unsigned int nr_pages);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffff80001047d3b0)
Location: fs/ext4/inode.c:3342
Inline: False
```
**Symbols:**

```
ffff80001047d3b0-ffff80001047d428: ext4_readpages (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int ext4_readpages(struct file *file, struct address_space *mapping, struct list_head *pages, unsigned int nr_pages);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (c063ec9c)
Location: fs/ext4/inode.c:3342
Inline: False
```
**Symbols:**

```
c063ec9c-c063ed00: ext4_readpages (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int ext4_readpages(struct file *file, struct address_space *mapping, struct list_head *pages, unsigned int nr_pages);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (c0000000005a0ff0)
Location: fs/ext4/inode.c:3342
Inline: False
```
**Symbols:**

```
c0000000005a0ff0-c0000000005a1058: ext4_readpages (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int ext4_readpages(struct file *file, struct address_space *mapping, struct list_head *pages, unsigned int nr_pages);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffe000306e6a)
Location: fs/ext4/inode.c:3342
Inline: False
```
**Symbols:**

```
ffffffe000306e6a-ffffffe000306ecc: ext4_readpages (STB_LOCAL)
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
int ext4_readpages(struct file *file, struct address_space *mapping, struct list_head *pages, unsigned int nr_pages);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff813a1b60)
Location: fs/ext4/inode.c:3342
Inline: False
```
**Symbols:**

```
ffffffff813a1b60-ffffffff813a1b9c: ext4_readpages (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int ext4_readpages(struct file *file, struct address_space *mapping, struct list_head *pages, unsigned int nr_pages);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff813925f0)
Location: fs/ext4/inode.c:3342
Inline: False
```
**Symbols:**

```
ffffffff813925f0-ffffffff8139262c: ext4_readpages (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int ext4_readpages(struct file *file, struct address_space *mapping, struct list_head *pages, unsigned int nr_pages);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff8139f3c0)
Location: fs/ext4/inode.c:3342
Inline: False
```
**Symbols:**

```
ffffffff8139f3c0-ffffffff8139f3fc: ext4_readpages (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int ext4_readpages(struct file *file, struct address_space *mapping, struct list_head *pages, unsigned int nr_pages);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inode.c (ffffffff813b3a60)
Location: fs/ext4/inode.c:3342
Inline: False
```
**Symbols:**

```
ffffffff813b3a60-ffffffff813b3a9c: ext4_readpages (STB_LOCAL)
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
