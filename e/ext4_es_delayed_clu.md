# Function: <code>ext4_es_delayed_clu</code>

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
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
unsigned int ext4_es_delayed_clu(struct inode *inode, ext4_lblk_t lblk, ext4_lblk_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents_status.c (ffffffff8135b590)
Location: fs/ext4/extents_status.c:1683
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_ext_map_blocks
```
**Symbols:**

```
ffffffff8135b590-ffffffff8135b6b0: ext4_es_delayed_clu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
unsigned int ext4_es_delayed_clu(struct inode *inode, ext4_lblk_t lblk, ext4_lblk_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/extents_status.c (0)
Location: fs/ext4/extents_status.c:1682
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_ext_map_blocks
```
**Symbols:**

```
ffffffff813848e7-ffffffff813848fa: ext4_es_delayed_clu.cold (STB_LOCAL)
ffffffff813845d0-ffffffff813846d8: ext4_es_delayed_clu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
unsigned int ext4_es_delayed_clu(struct inode *inode, ext4_lblk_t lblk, ext4_lblk_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents_status.c (ffffffff8139d250)
Location: fs/ext4/extents_status.c:2073
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_ext_map_blocks
```
**Symbols:**

```
ffffffff8139d250-ffffffff8139d35f: ext4_es_delayed_clu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
unsigned int ext4_es_delayed_clu(struct inode *inode, ext4_lblk_t lblk, ext4_lblk_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents_status.c (ffffffff813e8990)
Location: fs/ext4/extents_status.c:2073
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_ext_map_blocks
```
**Symbols:**

```
ffffffff813e8990-ffffffff813e89e7: ext4_es_delayed_clu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
unsigned int ext4_es_delayed_clu(struct inode *inode, ext4_lblk_t lblk, ext4_lblk_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents_status.c (ffffffff813fac40)
Location: fs/ext4/extents_status.c:2097
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_ext_map_blocks
```
**Symbols:**

```
ffffffff813fac40-ffffffff813fac97: ext4_es_delayed_clu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
unsigned int ext4_es_delayed_clu(struct inode *inode, ext4_lblk_t lblk, ext4_lblk_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents_status.c (ffffffff81401000)
Location: fs/ext4/extents_status.c:2095
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_ext_map_blocks
```
**Symbols:**

```
ffffffff81401000-ffffffff8140110d: ext4_es_delayed_clu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
unsigned int ext4_es_delayed_clu(struct inode *inode, ext4_lblk_t lblk, ext4_lblk_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents_status.c (ffffffff81453620)
Location: fs/ext4/extents_status.c:2095
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_ext_map_blocks
```
**Symbols:**

```
ffffffff81453620-ffffffff81453677: ext4_es_delayed_clu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
unsigned int ext4_es_delayed_clu(struct inode *inode, ext4_lblk_t lblk, ext4_lblk_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents_status.c (ffffffff814d0c50)
Location: fs/ext4/extents_status.c:2095
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_ext_map_blocks
```
**Symbols:**

```
ffffffff814d0c50-ffffffff814d0cb8: ext4_es_delayed_clu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
unsigned int ext4_es_delayed_clu(struct inode *inode, ext4_lblk_t lblk, ext4_lblk_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents_status.c (ffffffff81569660)
Location: fs/ext4/extents_status.c:2092
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_ext_map_blocks
```
**Symbols:**

```
ffffffff81569660-ffffffff815696c8: ext4_es_delayed_clu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
unsigned int ext4_es_delayed_clu(struct inode *inode, ext4_lblk_t lblk, ext4_lblk_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents_status.c (ffffffff815a13d0)
Location: fs/ext4/extents_status.c:2139
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_ext_map_blocks
```
**Symbols:**

```
ffffffff815a13d0-ffffffff815a1438: ext4_es_delayed_clu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
unsigned int ext4_es_delayed_clu(struct inode *inode, ext4_lblk_t lblk, ext4_lblk_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents_status.c (ffffffff815da190)
Location: fs/ext4/extents_status.c:2200
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_ext_map_blocks
```
**Symbols:**

```
ffffffff815da190-ffffffff815da1f8: ext4_es_delayed_clu (STB_GLOBAL)
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
unsigned int ext4_es_delayed_clu(struct inode *inode, ext4_lblk_t lblk, ext4_lblk_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents_status.c (ffff800010470450)
Location: fs/ext4/extents_status.c:2073
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_ext_map_blocks
```
**Symbols:**

```
ffff800010470450-ffff8000104705d4: ext4_es_delayed_clu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
unsigned int ext4_es_delayed_clu(struct inode *inode, ext4_lblk_t lblk, ext4_lblk_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents_status.c (c0631898)
Location: fs/ext4/extents_status.c:2073
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_ext_map_blocks
```
**Symbols:**

```
c0631898-c06319ec: ext4_es_delayed_clu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
unsigned int ext4_es_delayed_clu(struct inode *inode, ext4_lblk_t lblk, ext4_lblk_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents_status.c (c000000000590aa0)
Location: fs/ext4/extents_status.c:2073
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_ext_map_blocks
```
**Symbols:**

```
c000000000590aa0-c000000000590c20: ext4_es_delayed_clu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
unsigned int ext4_es_delayed_clu(struct inode *inode, ext4_lblk_t lblk, ext4_lblk_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents_status.c (ffffffe0002fcb66)
Location: fs/ext4/extents_status.c:2073
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_ext_map_blocks
```
**Symbols:**

```
ffffffe0002fcb66-ffffffe0002fcc5c: ext4_es_delayed_clu (STB_GLOBAL)
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
unsigned int ext4_es_delayed_clu(struct inode *inode, ext4_lblk_t lblk, ext4_lblk_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents_status.c (ffffffff81395830)
Location: fs/ext4/extents_status.c:2073
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_ext_map_blocks
```
**Symbols:**

```
ffffffff81395830-ffffffff8139593f: ext4_es_delayed_clu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
unsigned int ext4_es_delayed_clu(struct inode *inode, ext4_lblk_t lblk, ext4_lblk_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents_status.c (ffffffff813862c0)
Location: fs/ext4/extents_status.c:2073
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_ext_map_blocks
```
**Symbols:**

```
ffffffff813862c0-ffffffff813863cf: ext4_es_delayed_clu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
unsigned int ext4_es_delayed_clu(struct inode *inode, ext4_lblk_t lblk, ext4_lblk_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents_status.c (ffffffff81393190)
Location: fs/ext4/extents_status.c:2073
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_ext_map_blocks
```
**Symbols:**

```
ffffffff81393190-ffffffff8139329f: ext4_es_delayed_clu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
unsigned int ext4_es_delayed_clu(struct inode *inode, ext4_lblk_t lblk, ext4_lblk_t len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents_status.c (ffffffff813a7220)
Location: fs/ext4/extents_status.c:2073
Inline: False
Direct callers:
  - fs/ext4/extents.c:ext4_ext_map_blocks
```
**Symbols:**

```
ffffffff813a7220-ffffffff813a732c: ext4_es_delayed_clu (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
