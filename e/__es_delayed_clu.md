# Function: <code>__es_delayed_clu</code>

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
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/extents_status.c (ffffffff8135b5cd)
Location: fs/ext4/extents_status.c:1630
Inline: True
Inline callers:
  - fs/ext4/extents_status.c:ext4_es_delayed_clu
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
In fs/ext4/extents_status.c (ffffffff81384618)
Location: fs/ext4/extents_status.c:1629
Inline: True
Inline callers:
  - fs/ext4/extents_status.c:ext4_es_delayed_clu
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
In fs/ext4/extents_status.c (ffffffff8139d298)
Location: fs/ext4/extents_status.c:2020
Inline: True
Inline callers:
  - fs/ext4/extents_status.c:ext4_es_delayed_clu
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
unsigned int __es_delayed_clu(struct inode *inode, ext4_lblk_t start, ext4_lblk_t end);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents_status.c (ffffffff813e6e20)
Location: fs/ext4/extents_status.c:2020
Inline: False
Direct callers:
  - fs/ext4/extents_status.c:ext4_es_delayed_clu
```
**Symbols:**

```
ffffffff813e6e20-ffffffff813e6ee0: __es_delayed_clu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
unsigned int __es_delayed_clu(struct inode *inode, ext4_lblk_t start, ext4_lblk_t end);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents_status.c (ffffffff813f90e0)
Location: fs/ext4/extents_status.c:2044
Inline: False
Direct callers:
  - fs/ext4/extents_status.c:ext4_es_delayed_clu
```
**Symbols:**

```
ffffffff813f90e0-ffffffff813f91a0: __es_delayed_clu (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/ext4/extents_status.c (ffffffff81401046)
Location: fs/ext4/extents_status.c:2042
Inline: True
Inline callers:
  - fs/ext4/extents_status.c:ext4_es_delayed_clu
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
unsigned int __es_delayed_clu(struct inode *inode, ext4_lblk_t start, ext4_lblk_t end);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/extents_status.c (0)
Location: fs/ext4/extents_status.c:2042
Inline: False
Direct callers:
  - fs/ext4/extents_status.c:ext4_es_delayed_clu
```
**Symbols:**

```
ffffffff81451320-ffffffff81451435: __es_delayed_clu (STB_LOCAL)
ffffffff81cc9b42-ffffffff81cc9bf8: __es_delayed_clu.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
unsigned int __es_delayed_clu(struct inode *inode, ext4_lblk_t start, ext4_lblk_t end);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/extents_status.c (0)
Location: fs/ext4/extents_status.c:2042
Inline: False
Direct callers:
  - fs/ext4/extents_status.c:ext4_es_delayed_clu
```
**Symbols:**

```
ffffffff814cea90-ffffffff814cebb8: __es_delayed_clu (STB_LOCAL)
ffffffff81e7c83c-ffffffff81e7c8f2: __es_delayed_clu.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
unsigned int __es_delayed_clu(struct inode *inode, ext4_lblk_t start, ext4_lblk_t end);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/extents_status.c (0)
Location: fs/ext4/extents_status.c:2039
Inline: False
Direct callers:
  - fs/ext4/extents_status.c:ext4_es_delayed_clu
```
**Symbols:**

```
ffffffff81567300-ffffffff81567428: __es_delayed_clu (STB_LOCAL)
ffffffff8206ce68-ffffffff8206cf1e: __es_delayed_clu.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
unsigned int __es_delayed_clu(struct inode *inode, ext4_lblk_t start, ext4_lblk_t end);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/extents_status.c (0)
Location: fs/ext4/extents_status.c:2086
Inline: False
Direct callers:
  - fs/ext4/extents_status.c:ext4_es_delayed_clu
```
**Symbols:**

```
ffffffff8159f4d0-ffffffff8159f5f8: __es_delayed_clu (STB_LOCAL)
ffffffff820ecbf0-ffffffff820ecca6: __es_delayed_clu.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
unsigned int __es_delayed_clu(struct inode *inode, ext4_lblk_t start, ext4_lblk_t end);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/ext4/extents_status.c (0)
Location: fs/ext4/extents_status.c:2147
Inline: False
Direct callers:
  - fs/ext4/extents_status.c:ext4_es_delayed_clu
```
**Symbols:**

```
ffffffff815d8020-ffffffff815d8148: __es_delayed_clu (STB_LOCAL)
ffffffff821c9e0e-ffffffff821c9ec4: __es_delayed_clu.cold (STB_LOCAL)
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
In fs/ext4/extents_status.c (ffff8000104704bc)
Location: fs/ext4/extents_status.c:2020
Inline: True
Inline callers:
  - fs/ext4/extents_status.c:ext4_es_delayed_clu
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
In fs/ext4/extents_status.c (c06318e4)
Location: fs/ext4/extents_status.c:2020
Inline: True
Inline callers:
  - fs/ext4/extents_status.c:ext4_es_delayed_clu
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
In fs/ext4/extents_status.c (c000000000590b18)
Location: fs/ext4/extents_status.c:2020
Inline: True
Inline callers:
  - fs/ext4/extents_status.c:ext4_es_delayed_clu
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
In fs/ext4/extents_status.c (ffffffe0002fcba4)
Location: fs/ext4/extents_status.c:2020
Inline: True
Inline callers:
  - fs/ext4/extents_status.c:ext4_es_delayed_clu
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
In fs/ext4/extents_status.c (ffffffff81395878)
Location: fs/ext4/extents_status.c:2020
Inline: True
Inline callers:
  - fs/ext4/extents_status.c:ext4_es_delayed_clu
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
In fs/ext4/extents_status.c (ffffffff81386308)
Location: fs/ext4/extents_status.c:2020
Inline: True
Inline callers:
  - fs/ext4/extents_status.c:ext4_es_delayed_clu
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
In fs/ext4/extents_status.c (ffffffff813931d8)
Location: fs/ext4/extents_status.c:2020
Inline: True
Inline callers:
  - fs/ext4/extents_status.c:ext4_es_delayed_clu
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
In fs/ext4/extents_status.c (ffffffff813a7268)
Location: fs/ext4/extents_status.c:2020
Inline: True
Inline callers:
  - fs/ext4/extents_status.c:ext4_es_delayed_clu
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
