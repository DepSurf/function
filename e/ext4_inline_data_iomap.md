# Function: <code>ext4_inline_data_iomap</code>

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
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int ext4_inline_data_iomap(struct inode *inode, struct iomap *iomap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inline.c (ffffffff81320b30)
Location: fs/ext4/inline.c:1821
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_iomap_begin
```
**Symbols:**

```
ffffffff81320b30-ffffffff81320c32: ext4_inline_data_iomap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int ext4_inline_data_iomap(struct inode *inode, struct iomap *iomap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inline.c (ffffffff8134ec90)
Location: fs/ext4/inline.c:1826
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_iomap_begin
```
**Symbols:**

```
ffffffff8134ec90-ffffffff8134ed8b: ext4_inline_data_iomap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int ext4_inline_data_iomap(struct inode *inode, struct iomap *iomap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inline.c (ffffffff81366e10)
Location: fs/ext4/inline.c:1829
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_iomap_begin
```
**Symbols:**

```
ffffffff81366e10-ffffffff81366f0b: ext4_inline_data_iomap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int ext4_inline_data_iomap(struct inode *inode, struct iomap *iomap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inline.c (ffffffff813901c0)
Location: fs/ext4/inline.c:1826
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_iomap_begin
```
**Symbols:**

```
ffffffff813901c0-ffffffff813902bb: ext4_inline_data_iomap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int ext4_inline_data_iomap(struct inode *inode, struct iomap *iomap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inline.c (ffffffff813a8c20)
Location: fs/ext4/inline.c:1826
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_iomap_begin
```
**Symbols:**

```
ffffffff813a8c20-ffffffff813a8d1b: ext4_inline_data_iomap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int ext4_inline_data_iomap(struct inode *inode, struct iomap *iomap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inline.c (ffffffff813f4cc0)
Location: fs/ext4/inline.c:1829
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_iomap_begin_report
```
**Symbols:**

```
ffffffff813f4cc0-ffffffff813f4db5: ext4_inline_data_iomap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int ext4_inline_data_iomap(struct inode *inode, struct iomap *iomap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inline.c (ffffffff81407430)
Location: fs/ext4/inline.c:1829
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_iomap_begin_report
```
**Symbols:**

```
ffffffff81407430-ffffffff81407525: ext4_inline_data_iomap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int ext4_inline_data_iomap(struct inode *inode, struct iomap *iomap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inline.c (ffffffff8140d8a0)
Location: fs/ext4/inline.c:1840
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_iomap_begin_report
```
**Symbols:**

```
ffffffff8140d8a0-ffffffff8140d997: ext4_inline_data_iomap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int ext4_inline_data_iomap(struct inode *inode, struct iomap *iomap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/inline.c (0)
Location: fs/ext4/inline.c:1858
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_iomap_begin_report
```
**Symbols:**

```
ffffffff81cca6cb-ffffffff81cca6ed: ext4_inline_data_iomap.cold (STB_LOCAL)
ffffffff81460740-ffffffff81460840: ext4_inline_data_iomap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int ext4_inline_data_iomap(struct inode *inode, struct iomap *iomap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/inline.c (0)
Location: fs/ext4/inline.c:1882
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_iomap_begin_report
  - fs/ext4/inode.c:ext4_iomap_begin_report
```
**Symbols:**

```
ffffffff81e7d402-ffffffff81e7d424: ext4_inline_data_iomap.cold (STB_LOCAL)
ffffffff814df090-ffffffff814df1be: ext4_inline_data_iomap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int ext4_inline_data_iomap(struct inode *inode, struct iomap *iomap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/inline.c (0)
Location: fs/ext4/inline.c:1881
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_iomap_begin_report
  - fs/ext4/inode.c:ext4_iomap_begin_report
```
**Symbols:**

```
ffffffff8206d96f-ffffffff8206d991: ext4_inline_data_iomap.cold (STB_LOCAL)
ffffffff81578180-ffffffff815782ae: ext4_inline_data_iomap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int ext4_inline_data_iomap(struct inode *inode, struct iomap *iomap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/inline.c (0)
Location: fs/ext4/inline.c:1864
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_iomap_begin_report
  - fs/ext4/inode.c:ext4_iomap_begin_report
```
**Symbols:**

```
ffffffff820ed670-ffffffff820ed692: ext4_inline_data_iomap.cold (STB_LOCAL)
ffffffff815af6a0-ffffffff815af7ce: ext4_inline_data_iomap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int ext4_inline_data_iomap(struct inode *inode, struct iomap *iomap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/inline.c (0)
Location: fs/ext4/inline.c:1863
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_iomap_begin_report
  - fs/ext4/inode.c:ext4_iomap_begin_report
```
**Symbols:**

```
ffffffff821ca787-ffffffff821ca7a9: ext4_inline_data_iomap.cold (STB_LOCAL)
ffffffff815e8460-ffffffff815e858e: ext4_inline_data_iomap (STB_GLOBAL)
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
int ext4_inline_data_iomap(struct inode *inode, struct iomap *iomap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inline.c (ffff80001047c578)
Location: fs/ext4/inline.c:1826
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_iomap_begin
```
**Symbols:**

```
ffff80001047c578-ffff80001047c684: ext4_inline_data_iomap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int ext4_inline_data_iomap(struct inode *inode, struct iomap *iomap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inline.c (c063df14)
Location: fs/ext4/inline.c:1826
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_iomap_begin
```
**Symbols:**

```
c063df14-c063e0ac: ext4_inline_data_iomap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int ext4_inline_data_iomap(struct inode *inode, struct iomap *iomap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inline.c (c00000000059fee0)
Location: fs/ext4/inline.c:1826
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_iomap_begin
```
**Symbols:**

```
c00000000059fee0-c0000000005a002c: ext4_inline_data_iomap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int ext4_inline_data_iomap(struct inode *inode, struct iomap *iomap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inline.c (ffffffe0003065a8)
Location: fs/ext4/inline.c:1826
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_iomap_begin
```
**Symbols:**

```
ffffffe0003065a8-ffffffe000306666: ext4_inline_data_iomap (STB_GLOBAL)
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
int ext4_inline_data_iomap(struct inode *inode, struct iomap *iomap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inline.c (ffffffff813a1200)
Location: fs/ext4/inline.c:1826
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_iomap_begin
```
**Symbols:**

```
ffffffff813a1200-ffffffff813a12fb: ext4_inline_data_iomap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int ext4_inline_data_iomap(struct inode *inode, struct iomap *iomap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inline.c (ffffffff81391c90)
Location: fs/ext4/inline.c:1826
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_iomap_begin
```
**Symbols:**

```
ffffffff81391c90-ffffffff81391d8b: ext4_inline_data_iomap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int ext4_inline_data_iomap(struct inode *inode, struct iomap *iomap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inline.c (ffffffff8139ea60)
Location: fs/ext4/inline.c:1826
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_iomap_begin
```
**Symbols:**

```
ffffffff8139ea60-ffffffff8139eb5b: ext4_inline_data_iomap (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int ext4_inline_data_iomap(struct inode *inode, struct iomap *iomap);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/inline.c (ffffffff813b2fd0)
Location: fs/ext4/inline.c:1826
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_iomap_begin
```
**Symbols:**

```
ffffffff813b2fd0-ffffffff813b30cb: ext4_inline_data_iomap (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
