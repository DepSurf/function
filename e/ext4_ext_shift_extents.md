# Function: <code>ext4_ext_shift_extents</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int ext4_ext_shift_extents(struct inode *inode, handle_t *handle, ext4_lblk_t start, ext4_lblk_t shift, enum SHIFT_DIRECTION SHIFT);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (ffffffff812c4850)
Location: fs/ext4/extents.c:5349
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_collapse_range
  - fs/ext4/extents.c:ext4_insert_range
```
**Symbols:**

```
ffffffff812c4850-ffffffff812c4cdd: ext4_ext_shift_extents (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int ext4_ext_shift_extents(struct inode *inode, handle_t *handle, ext4_lblk_t start, ext4_lblk_t shift, enum SHIFT_DIRECTION SHIFT);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (ffffffff812f40a0)
Location: fs/ext4/extents.c:5351
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_insert_range
  - fs/ext4/extents.c:ext4_collapse_range
```
**Symbols:**

```
ffffffff812f40a0-ffffffff812f4516: ext4_ext_shift_extents (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int ext4_ext_shift_extents(struct inode *inode, handle_t *handle, ext4_lblk_t start, ext4_lblk_t shift, enum SHIFT_DIRECTION SHIFT);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (ffffffff8130a050)
Location: fs/ext4/extents.c:5327
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_insert_range
  - fs/ext4/extents.c:ext4_collapse_range
```
**Symbols:**

```
ffffffff8130a050-ffffffff8130a4ca: ext4_ext_shift_extents (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int ext4_ext_shift_extents(struct inode *inode, handle_t *handle, ext4_lblk_t start, ext4_lblk_t shift, enum SHIFT_DIRECTION SHIFT);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (ffffffff812e8730)
Location: fs/ext4/extents.c:5323
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_insert_range
  - fs/ext4/extents.c:ext4_collapse_range
```
**Symbols:**

```
ffffffff812e8730-ffffffff812e8ba6: ext4_ext_shift_extents (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int ext4_ext_shift_extents(struct inode *inode, handle_t *handle, ext4_lblk_t start, ext4_lblk_t shift, enum SHIFT_DIRECTION SHIFT);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (ffffffff8130d1d0)
Location: fs/ext4/extents.c:5326
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_insert_range
  - fs/ext4/extents.c:ext4_collapse_range
```
**Symbols:**

```
ffffffff8130d1d0-ffffffff8130d646: ext4_ext_shift_extents (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int ext4_ext_shift_extents(struct inode *inode, handle_t *handle, ext4_lblk_t start, ext4_lblk_t shift, enum SHIFT_DIRECTION SHIFT);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (ffffffff8133c3c0)
Location: fs/ext4/extents.c:5322
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_insert_range
  - fs/ext4/extents.c:ext4_collapse_range
```
**Symbols:**

```
ffffffff8133c3c0-ffffffff8133c85b: ext4_ext_shift_extents (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int ext4_ext_shift_extents(struct inode *inode, handle_t *handle, ext4_lblk_t start, ext4_lblk_t shift, enum SHIFT_DIRECTION SHIFT);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (ffffffff81353a70)
Location: fs/ext4/extents.c:5224
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_insert_range
  - fs/ext4/extents.c:ext4_collapse_range
```
**Symbols:**

```
ffffffff81353a70-ffffffff81353f0b: ext4_ext_shift_extents (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int ext4_ext_shift_extents(struct inode *inode, handle_t *handle, ext4_lblk_t start, ext4_lblk_t shift, enum SHIFT_DIRECTION SHIFT);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (ffffffff8137d5b0)
Location: fs/ext4/extents.c:5234
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_insert_range
  - fs/ext4/extents.c:ext4_collapse_range
```
**Symbols:**

```
ffffffff8137d5b0-ffffffff8137da54: ext4_ext_shift_extents (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int ext4_ext_shift_extents(struct inode *inode, handle_t *handle, ext4_lblk_t start, ext4_lblk_t shift, enum SHIFT_DIRECTION SHIFT);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (ffffffff81395cd0)
Location: fs/ext4/extents.c:5312
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_insert_range
  - fs/ext4/extents.c:ext4_collapse_range
```
**Symbols:**

```
ffffffff81395cd0-ffffffff81396174: ext4_ext_shift_extents (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int ext4_ext_shift_extents(struct inode *inode, handle_t *handle, ext4_lblk_t start, ext4_lblk_t shift, enum SHIFT_DIRECTION SHIFT);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (ffffffff813e1250)
Location: fs/ext4/extents.c:5079
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_insert_range
  - fs/ext4/extents.c:ext4_collapse_range
```
**Symbols:**

```
ffffffff813e1250-ffffffff813e1586: ext4_ext_shift_extents (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int ext4_ext_shift_extents(struct inode *inode, handle_t *handle, ext4_lblk_t start, ext4_lblk_t shift, enum SHIFT_DIRECTION SHIFT);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (ffffffff813f2ae0)
Location: fs/ext4/extents.c:5088
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_insert_range
  - fs/ext4/extents.c:ext4_collapse_range
```
**Symbols:**

```
ffffffff813f2ae0-ffffffff813f2e18: ext4_ext_shift_extents (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int ext4_ext_shift_extents(struct inode *inode, handle_t *handle, ext4_lblk_t start, ext4_lblk_t shift, enum SHIFT_DIRECTION SHIFT);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (ffffffff813f8db0)
Location: fs/ext4/extents.c:5094
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_insert_range
  - fs/ext4/extents.c:ext4_collapse_range
```
**Symbols:**

```
ffffffff813f8db0-ffffffff813f90eb: ext4_ext_shift_extents (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int ext4_ext_shift_extents(struct inode *inode, handle_t *handle, ext4_lblk_t start, ext4_lblk_t shift, enum SHIFT_DIRECTION SHIFT);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (ffffffff8144b240)
Location: fs/ext4/extents.c:5116
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_insert_range
  - fs/ext4/extents.c:ext4_collapse_range
```
**Symbols:**

```
ffffffff8144b240-ffffffff8144b582: ext4_ext_shift_extents (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int ext4_ext_shift_extents(struct inode *inode, handle_t *handle, ext4_lblk_t start, ext4_lblk_t shift, enum SHIFT_DIRECTION SHIFT);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (ffffffff814c7a80)
Location: fs/ext4/extents.c:5119
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_insert_range
  - fs/ext4/extents.c:ext4_collapse_range
```
**Symbols:**

```
ffffffff814c7a80-ffffffff814c7dda: ext4_ext_shift_extents (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int ext4_ext_shift_extents(struct inode *inode, handle_t *handle, ext4_lblk_t start, ext4_lblk_t shift, enum SHIFT_DIRECTION SHIFT);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (ffffffff81560090)
Location: fs/ext4/extents.c:5123
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_insert_range
  - fs/ext4/extents.c:ext4_collapse_range
```
**Symbols:**

```
ffffffff81560090-ffffffff8156040b: ext4_ext_shift_extents (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int ext4_ext_shift_extents(struct inode *inode, handle_t *handle, ext4_lblk_t start, ext4_lblk_t shift, enum SHIFT_DIRECTION SHIFT);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (ffffffff81597e60)
Location: fs/ext4/extents.c:5122
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_insert_range
  - fs/ext4/extents.c:ext4_collapse_range
```
**Symbols:**

```
ffffffff81597e60-ffffffff815981d7: ext4_ext_shift_extents (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int ext4_ext_shift_extents(struct inode *inode, handle_t *handle, ext4_lblk_t start, ext4_lblk_t shift, enum SHIFT_DIRECTION SHIFT);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (ffffffff815d0ca0)
Location: fs/ext4/extents.c:5157
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_insert_range
  - fs/ext4/extents.c:ext4_collapse_range
```
**Symbols:**

```
ffffffff815d0ca0-ffffffff815d1017: ext4_ext_shift_extents (STB_LOCAL)
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
int ext4_ext_shift_extents(struct inode *inode, handle_t *handle, ext4_lblk_t start, ext4_lblk_t shift, enum SHIFT_DIRECTION SHIFT);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (ffff800010468b18)
Location: fs/ext4/extents.c:5312
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_insert_range
  - fs/ext4/extents.c:ext4_collapse_range
```
**Symbols:**

```
ffff800010468b18-ffff800010468ff4: ext4_ext_shift_extents (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int ext4_ext_shift_extents(struct inode *inode, handle_t *handle, ext4_lblk_t start, ext4_lblk_t shift, enum SHIFT_DIRECTION SHIFT);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (c0629890)
Location: fs/ext4/extents.c:5312
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_insert_range
  - fs/ext4/extents.c:ext4_collapse_range
```
**Symbols:**

```
c0629890-c0629d84: ext4_ext_shift_extents (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int ext4_ext_shift_extents(struct inode *inode, handle_t *handle, ext4_lblk_t start, ext4_lblk_t shift, enum SHIFT_DIRECTION SHIFT);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (c0000000005870d0)
Location: fs/ext4/extents.c:5312
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_insert_range
  - fs/ext4/extents.c:ext4_collapse_range
```
**Symbols:**

```
c0000000005870d0-c00000000058771c: ext4_ext_shift_extents (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int ext4_ext_shift_extents(struct inode *inode, handle_t *handle, ext4_lblk_t start, ext4_lblk_t shift, enum SHIFT_DIRECTION SHIFT);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (ffffffe0002f6628)
Location: fs/ext4/extents.c:5312
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_insert_range
  - fs/ext4/extents.c:ext4_collapse_range
```
**Symbols:**

```
ffffffe0002f6628-ffffffe0002f6a18: ext4_ext_shift_extents (STB_LOCAL)
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
int ext4_ext_shift_extents(struct inode *inode, handle_t *handle, ext4_lblk_t start, ext4_lblk_t shift, enum SHIFT_DIRECTION SHIFT);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (ffffffff8138e2b0)
Location: fs/ext4/extents.c:5312
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_insert_range
  - fs/ext4/extents.c:ext4_collapse_range
```
**Symbols:**

```
ffffffff8138e2b0-ffffffff8138e754: ext4_ext_shift_extents (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int ext4_ext_shift_extents(struct inode *inode, handle_t *handle, ext4_lblk_t start, ext4_lblk_t shift, enum SHIFT_DIRECTION SHIFT);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (ffffffff8137ed40)
Location: fs/ext4/extents.c:5312
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_insert_range
  - fs/ext4/extents.c:ext4_collapse_range
```
**Symbols:**

```
ffffffff8137ed40-ffffffff8137f1e4: ext4_ext_shift_extents (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int ext4_ext_shift_extents(struct inode *inode, handle_t *handle, ext4_lblk_t start, ext4_lblk_t shift, enum SHIFT_DIRECTION SHIFT);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (ffffffff8138bc10)
Location: fs/ext4/extents.c:5312
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_insert_range
  - fs/ext4/extents.c:ext4_collapse_range
```
**Symbols:**

```
ffffffff8138bc10-ffffffff8138c0b4: ext4_ext_shift_extents (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int ext4_ext_shift_extents(struct inode *inode, handle_t *handle, ext4_lblk_t start, ext4_lblk_t shift, enum SHIFT_DIRECTION SHIFT);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents.c (ffffffff8139f960)
Location: fs/ext4/extents.c:5312
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_insert_range
  - fs/ext4/extents.c:ext4_collapse_range
```
**Symbols:**

```
ffffffff8139f960-ffffffff8139fe04: ext4_ext_shift_extents (STB_LOCAL)
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
