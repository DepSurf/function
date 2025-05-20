# Function: <code>ext4_xattr_inode_read</code>

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
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int ext4_xattr_inode_read(struct inode *ea_inode, void *buf, size_t size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/xattr.c (ffffffff8133a160)
Location: fs/ext4/xattr.c:318
Inline: False
Direct callers:
  - fs/ext4/xattr.c:ext4_xattr_set_entry
  - fs/ext4/xattr.c:ext4_xattr_inode_get
```
**Symbols:**

```
ffffffff8133a160-ffffffff8133a34f: ext4_xattr_inode_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int ext4_xattr_inode_read(struct inode *ea_inode, void *buf, size_t size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/xattr.c (ffffffff8135e530)
Location: fs/ext4/xattr.c:319
Inline: False
Direct callers:
  - fs/ext4/xattr.c:ext4_xattr_set_entry
  - fs/ext4/xattr.c:ext4_xattr_inode_get
```
**Symbols:**

```
ffffffff8135e530-ffffffff8135e71f: ext4_xattr_inode_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int ext4_xattr_inode_read(struct inode *ea_inode, void *buf, size_t size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/xattr.c (ffffffff8138ce80)
Location: fs/ext4/xattr.c:340
Inline: False
Direct callers:
  - fs/ext4/xattr.c:ext4_xattr_inode_lookup_create
  - fs/ext4/xattr.c:ext4_xattr_inode_get
```
**Symbols:**

```
ffffffff8138ce80-ffffffff8138d069: ext4_xattr_inode_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int ext4_xattr_inode_read(struct inode *ea_inode, void *buf, size_t size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/xattr.c (ffffffff813a5a90)
Location: fs/ext4/xattr.c:340
Inline: False
Direct callers:
  - fs/ext4/xattr.c:ext4_xattr_inode_lookup_create
  - fs/ext4/xattr.c:ext4_xattr_inode_get
```
**Symbols:**

```
ffffffff813a5a90-ffffffff813a5c7a: ext4_xattr_inode_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int ext4_xattr_inode_read(struct inode *ea_inode, void *buf, size_t size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/xattr.c (ffffffff813d0800)
Location: fs/ext4/xattr.c:340
Inline: False
Direct callers:
  - fs/ext4/xattr.c:ext4_xattr_inode_lookup_create
  - fs/ext4/xattr.c:ext4_xattr_inode_get
```
**Symbols:**

```
ffffffff813d0800-ffffffff813d09e3: ext4_xattr_inode_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int ext4_xattr_inode_read(struct inode *ea_inode, void *buf, size_t size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/xattr.c (ffffffff813e9ed0)
Location: fs/ext4/xattr.c:340
Inline: False
Direct callers:
  - fs/ext4/xattr.c:ext4_xattr_inode_lookup_create
  - fs/ext4/xattr.c:ext4_xattr_inode_get
```
**Symbols:**

```
ffffffff813e9ed0-ffffffff813ea0b3: ext4_xattr_inode_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int ext4_xattr_inode_read(struct inode *ea_inode, void *buf, size_t size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/xattr.c (ffffffff81436230)
Location: fs/ext4/xattr.c:342
Inline: False
Direct callers:
  - fs/ext4/xattr.c:ext4_xattr_inode_cache_find
  - fs/ext4/xattr.c:ext4_xattr_inode_get
```
**Symbols:**

```
ffffffff81436230-ffffffff8143642e: ext4_xattr_inode_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int ext4_xattr_inode_read(struct inode *ea_inode, void *buf, size_t size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/xattr.c (ffffffff8144ec70)
Location: fs/ext4/xattr.c:342
Inline: False
Direct callers:
  - fs/ext4/xattr.c:ext4_xattr_inode_cache_find
  - fs/ext4/xattr.c:ext4_xattr_inode_get
```
**Symbols:**

```
ffffffff8144ec70-ffffffff8144ee4f: ext4_xattr_inode_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int ext4_xattr_inode_read(struct inode *ea_inode, void *buf, size_t size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/xattr.c (ffffffff81454610)
Location: fs/ext4/xattr.c:342
Inline: False
Direct callers:
  - fs/ext4/xattr.c:ext4_xattr_inode_cache_find
  - fs/ext4/xattr.c:ext4_xattr_inode_get
```
**Symbols:**

```
ffffffff81454610-ffffffff81454819: ext4_xattr_inode_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int ext4_xattr_inode_read(struct inode *ea_inode, void *buf, size_t size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/xattr.c (0)
Location: fs/ext4/xattr.c:342
Inline: False
Direct callers:
  - fs/ext4/xattr.c:ext4_xattr_inode_cache_find
  - fs/ext4/xattr.c:ext4_xattr_inode_get
```
**Symbols:**

```
ffffffff814a8710-ffffffff814a8920: ext4_xattr_inode_read (STB_LOCAL)
ffffffff81ccdffd-ffffffff81cce082: ext4_xattr_inode_read.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int ext4_xattr_inode_read(struct inode *ea_inode, void *buf, size_t size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/xattr.c (0)
Location: fs/ext4/xattr.c:342
Inline: False
Direct callers:
  - fs/ext4/xattr.c:ext4_xattr_inode_cache_find
  - fs/ext4/xattr.c:ext4_xattr_inode_get
```
**Symbols:**

```
ffffffff81530690-ffffffff81530883: ext4_xattr_inode_read (STB_LOCAL)
ffffffff81e81034-ffffffff81e810c7: ext4_xattr_inode_read.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int ext4_xattr_inode_read(struct inode *ea_inode, void *buf, size_t size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/xattr.c (0)
Location: fs/ext4/xattr.c:344
Inline: False
Direct callers:
  - fs/ext4/xattr.c:ext4_xattr_inode_cache_find
  - fs/ext4/xattr.c:ext4_xattr_inode_get
```
**Symbols:**

```
ffffffff815cec80-ffffffff815cee8f: ext4_xattr_inode_read (STB_LOCAL)
ffffffff82070efb-ffffffff82070f7e: ext4_xattr_inode_read.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int ext4_xattr_inode_read(struct inode *ea_inode, void *buf, size_t size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/xattr.c (0)
Location: fs/ext4/xattr.c:382
Inline: False
Direct callers:
  - fs/ext4/xattr.c:ext4_xattr_inode_cache_find
  - fs/ext4/xattr.c:ext4_xattr_inode_get
```
**Symbols:**

```
ffffffff81606560-ffffffff81606762: ext4_xattr_inode_read (STB_LOCAL)
ffffffff820f0be1-ffffffff820f0c56: ext4_xattr_inode_read.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int ext4_xattr_inode_read(struct inode *ea_inode, void *buf, size_t size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/xattr.c (0)
Location: fs/ext4/xattr.c:382
Inline: False
Direct callers:
  - fs/ext4/xattr.c:ext4_xattr_inode_cache_find
  - fs/ext4/xattr.c:ext4_xattr_inode_get
```
**Symbols:**

```
ffffffff8163f2a0-ffffffff8163f4a2: ext4_xattr_inode_read (STB_LOCAL)
ffffffff821cdd98-ffffffff821cde0d: ext4_xattr_inode_read.cold (STB_LOCAL)
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
int ext4_xattr_inode_read(struct inode *ea_inode, void *buf, size_t size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/xattr.c (ffff8000104c2238)
Location: fs/ext4/xattr.c:340
Inline: False
Direct callers:
  - fs/ext4/xattr.c:ext4_xattr_inode_lookup_create
  - fs/ext4/xattr.c:ext4_xattr_inode_get
```
**Symbols:**

```
ffff8000104c2238-ffff8000104c23e0: ext4_xattr_inode_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int ext4_xattr_inode_read(struct inode *ea_inode, void *buf, size_t size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/xattr.c (c0686f5c)
Location: fs/ext4/xattr.c:340
Inline: False
Direct callers:
  - fs/ext4/xattr.c:ext4_xattr_inode_lookup_create
  - fs/ext4/xattr.c:ext4_xattr_inode_get
```
**Symbols:**

```
c0686f5c-c068711c: ext4_xattr_inode_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int ext4_xattr_inode_read(struct inode *ea_inode, void *buf, size_t size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/xattr.c (c0000000005fa280)
Location: fs/ext4/xattr.c:340
Inline: False
Direct callers:
  - fs/ext4/xattr.c:ext4_xattr_inode_lookup_create
  - fs/ext4/xattr.c:ext4_xattr_inode_get
```
**Symbols:**

```
c0000000005fa280-c0000000005fa4e4: ext4_xattr_inode_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int ext4_xattr_inode_read(struct inode *ea_inode, void *buf, size_t size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/xattr.c (ffffffe00033d50a)
Location: fs/ext4/xattr.c:340
Inline: False
Direct callers:
  - fs/ext4/xattr.c:ext4_xattr_inode_lookup_create
  - fs/ext4/xattr.c:ext4_xattr_inode_get
```
**Symbols:**

```
ffffffe00033d50a-ffffffe00033d64c: ext4_xattr_inode_read (STB_LOCAL)
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
int ext4_xattr_inode_read(struct inode *ea_inode, void *buf, size_t size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/xattr.c (ffffffff813e24b0)
Location: fs/ext4/xattr.c:340
Inline: False
Direct callers:
  - fs/ext4/xattr.c:ext4_xattr_inode_lookup_create
  - fs/ext4/xattr.c:ext4_xattr_inode_get
```
**Symbols:**

```
ffffffff813e24b0-ffffffff813e2693: ext4_xattr_inode_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int ext4_xattr_inode_read(struct inode *ea_inode, void *buf, size_t size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/xattr.c (ffffffff813d2f30)
Location: fs/ext4/xattr.c:340
Inline: False
Direct callers:
  - fs/ext4/xattr.c:ext4_xattr_inode_lookup_create
  - fs/ext4/xattr.c:ext4_xattr_inode_get
```
**Symbols:**

```
ffffffff813d2f30-ffffffff813d3113: ext4_xattr_inode_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int ext4_xattr_inode_read(struct inode *ea_inode, void *buf, size_t size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/xattr.c (ffffffff813df830)
Location: fs/ext4/xattr.c:340
Inline: False
Direct callers:
  - fs/ext4/xattr.c:ext4_xattr_inode_lookup_create
  - fs/ext4/xattr.c:ext4_xattr_inode_get
```
**Symbols:**

```
ffffffff813df830-ffffffff813dfa13: ext4_xattr_inode_read (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int ext4_xattr_inode_read(struct inode *ea_inode, void *buf, size_t size);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/xattr.c (ffffffff813f4c50)
Location: fs/ext4/xattr.c:340
Inline: False
Direct callers:
  - fs/ext4/xattr.c:ext4_xattr_inode_lookup_create
  - fs/ext4/xattr.c:ext4_xattr_inode_get
```
**Symbols:**

```
ffffffff813f4c50-ffffffff813f4e33: ext4_xattr_inode_read (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
