# Function: <code>ext4_xattr_cmp</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/xattr.c (ffffffff812dd644)
Location: fs/ext4/xattr.c:1564
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_block_set
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/xattr.c (ffffffff8130d199)
Location: fs/ext4/xattr.c:1648
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_block_set
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/xattr.c (ffffffff8132308e)
Location: fs/ext4/xattr.c:1662
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_block_set
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/xattr.c (ffffffff8133c347)
Location: fs/ext4/xattr.c:2935
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_block_set
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/xattr.c (ffffffff8136086a)
Location: fs/ext4/xattr.c:2981
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_block_set
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/xattr.c (ffffffff8138f11d)
Location: fs/ext4/xattr.c:2995
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_block_set
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/xattr.c (ffffffff813a7a54)
Location: fs/ext4/xattr.c:3001
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_block_set
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/xattr.c (ffffffff813d1f68)
Location: fs/ext4/xattr.c:3003
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_block_set
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
In fs/ext4/xattr.c (ffffffff813eb648)
Location: fs/ext4/xattr.c:3003
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_block_set
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int ext4_xattr_cmp(struct ext4_xattr_header *header1, struct ext4_xattr_header *header2);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/xattr.c (ffffffff814359a0)
Location: fs/ext4/xattr.c:2990
Inline: False
Direct callers:
  - fs/ext4/xattr.c:ext4_xattr_block_set
```
**Symbols:**

```
ffffffff814359a0-ffffffff81435a9a: ext4_xattr_cmp (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int ext4_xattr_cmp(struct ext4_xattr_header *header1, struct ext4_xattr_header *header2);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/xattr.c (ffffffff8144e3e0)
Location: fs/ext4/xattr.c:2998
Inline: False
Direct callers:
  - fs/ext4/xattr.c:ext4_xattr_block_set
```
**Symbols:**

```
ffffffff8144e3e0-ffffffff8144e4da: ext4_xattr_cmp (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int ext4_xattr_cmp(struct ext4_xattr_header *header1, struct ext4_xattr_header *header2);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/xattr.c (ffffffff81453ef0)
Location: fs/ext4/xattr.c:2998
Inline: False
Direct callers:
  - fs/ext4/xattr.c:ext4_xattr_block_set
```
**Symbols:**

```
ffffffff81453ef0-ffffffff81453fea: ext4_xattr_cmp (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int ext4_xattr_cmp(struct ext4_xattr_header *header1, struct ext4_xattr_header *header2);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/xattr.c (ffffffff814a7f90)
Location: fs/ext4/xattr.c:2982
Inline: False
Direct callers:
  - fs/ext4/xattr.c:ext4_xattr_block_set
```
**Symbols:**

```
ffffffff814a7f90-ffffffff814a808a: ext4_xattr_cmp (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int ext4_xattr_cmp(struct ext4_xattr_header *header1, struct ext4_xattr_header *header2);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/xattr.c (ffffffff8152f8b0)
Location: fs/ext4/xattr.c:2997
Inline: False
Direct callers:
  - fs/ext4/xattr.c:ext4_xattr_block_set
```
**Symbols:**

```
ffffffff8152f8b0-ffffffff8152f9d2: ext4_xattr_cmp (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int ext4_xattr_cmp(struct ext4_xattr_header *header1, struct ext4_xattr_header *header2);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/xattr.c (ffffffff815cdb90)
Location: fs/ext4/xattr.c:3023
Inline: False
Direct callers:
  - fs/ext4/xattr.c:ext4_xattr_block_set
```
**Symbols:**

```
ffffffff815cdb90-ffffffff815cdcb2: ext4_xattr_cmp (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int ext4_xattr_cmp(struct ext4_xattr_header *header1, struct ext4_xattr_header *header2);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/xattr.c (ffffffff81605480)
Location: fs/ext4/xattr.c:3070
Inline: False
Direct callers:
  - fs/ext4/xattr.c:ext4_xattr_block_set
```
**Symbols:**

```
ffffffff81605480-ffffffff816055a2: ext4_xattr_cmp (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int ext4_xattr_cmp(struct ext4_xattr_header *header1, struct ext4_xattr_header *header2);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/xattr.c (ffffffff8163e140)
Location: fs/ext4/xattr.c:3070
Inline: False
Direct callers:
  - fs/ext4/xattr.c:ext4_xattr_block_set
```
**Symbols:**

```
ffffffff8163e140-ffffffff8163e262: ext4_xattr_cmp (STB_LOCAL)
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
In fs/ext4/xattr.c (ffff8000104c4624)
Location: fs/ext4/xattr.c:3003
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_block_set
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
In fs/ext4/xattr.c (c0688570)
Location: fs/ext4/xattr.c:3003
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_block_set
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
In fs/ext4/xattr.c (c0000000005fbebc)
Location: fs/ext4/xattr.c:3003
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_block_set
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
In fs/ext4/xattr.c (ffffffe00033ef28)
Location: fs/ext4/xattr.c:3003
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_block_set
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
In fs/ext4/xattr.c (ffffffff813e3c28)
Location: fs/ext4/xattr.c:3003
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_block_set
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
In fs/ext4/xattr.c (ffffffff813d46a8)
Location: fs/ext4/xattr.c:3003
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_block_set
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
In fs/ext4/xattr.c (ffffffff813e0fa8)
Location: fs/ext4/xattr.c:3003
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_block_set
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
In fs/ext4/xattr.c (ffffffff813f63c3)
Location: fs/ext4/xattr.c:3003
Inline: True
Inline callers:
  - fs/ext4/xattr.c:ext4_xattr_block_set
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
