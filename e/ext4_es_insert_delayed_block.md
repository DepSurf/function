# Function: <code>ext4_es_insert_delayed_block</code>

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
int ext4_es_insert_delayed_block(struct inode *inode, ext4_lblk_t lblk, bool allocated);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents_status.c (ffffffff8135b440)
Location: fs/ext4/extents_status.c:1576
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_da_get_block_prep
```
**Symbols:**

```
ffffffff8135b440-ffffffff8135b583: ext4_es_insert_delayed_block (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int ext4_es_insert_delayed_block(struct inode *inode, ext4_lblk_t lblk, bool allocated);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents_status.c (ffffffff81384480)
Location: fs/ext4/extents_status.c:1575
Inline: False
```
**Symbols:**

```
ffffffff81384480-ffffffff813845c4: ext4_es_insert_delayed_block (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int ext4_es_insert_delayed_block(struct inode *inode, ext4_lblk_t lblk, bool allocated);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents_status.c (ffffffff8139d100)
Location: fs/ext4/extents_status.c:1966
Inline: False
```
**Symbols:**

```
ffffffff8139d100-ffffffff8139d246: ext4_es_insert_delayed_block (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int ext4_es_insert_delayed_block(struct inode *inode, ext4_lblk_t lblk, bool allocated);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents_status.c (ffffffff813e8840)
Location: fs/ext4/extents_status.c:1966
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_insert_delayed_block
```
**Symbols:**

```
ffffffff813e8840-ffffffff813e8983: ext4_es_insert_delayed_block (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int ext4_es_insert_delayed_block(struct inode *inode, ext4_lblk_t lblk, bool allocated);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents_status.c (ffffffff813faaf0)
Location: fs/ext4/extents_status.c:1987
Inline: False
Direct callers:
  - fs/ext4/inode.c:ext4_insert_delayed_block
```
**Symbols:**

```
ffffffff813faaf0-ffffffff813fac3b: ext4_es_insert_delayed_block (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int ext4_es_insert_delayed_block(struct inode *inode, ext4_lblk_t lblk, bool allocated);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents_status.c (ffffffff81400eb0)
Location: fs/ext4/extents_status.c:1985
Inline: False
```
**Symbols:**

```
ffffffff81400eb0-ffffffff81400ffb: ext4_es_insert_delayed_block (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int ext4_es_insert_delayed_block(struct inode *inode, ext4_lblk_t lblk, bool allocated);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents_status.c (ffffffff814534d0)
Location: fs/ext4/extents_status.c:1985
Inline: False
```
**Symbols:**

```
ffffffff814534d0-ffffffff81453618: ext4_es_insert_delayed_block (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int ext4_es_insert_delayed_block(struct inode *inode, ext4_lblk_t lblk, bool allocated);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents_status.c (ffffffff814d0ab0)
Location: fs/ext4/extents_status.c:1985
Inline: False
```
**Symbols:**

```
ffffffff814d0ab0-ffffffff814d0c50: ext4_es_insert_delayed_block (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int ext4_es_insert_delayed_block(struct inode *inode, ext4_lblk_t lblk, bool allocated);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents_status.c (ffffffff815694b0)
Location: fs/ext4/extents_status.c:1982
Inline: False
```
**Symbols:**

```
ffffffff815694b0-ffffffff81569650: ext4_es_insert_delayed_block (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void ext4_es_insert_delayed_block(struct inode *inode, ext4_lblk_t lblk, bool allocated);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents_status.c (ffffffff815a1160)
Location: fs/ext4/extents_status.c:2018
Inline: False
```
**Symbols:**

```
ffffffff815a1160-ffffffff815a13b9: ext4_es_insert_delayed_block (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void ext4_es_insert_delayed_block(struct inode *inode, ext4_lblk_t lblk, bool allocated);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents_status.c (ffffffff815d9ec0)
Location: fs/ext4/extents_status.c:2064
Inline: False
```
**Symbols:**

```
ffffffff815d9ec0-ffffffff815da180: ext4_es_insert_delayed_block (STB_GLOBAL)
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
int ext4_es_insert_delayed_block(struct inode *inode, ext4_lblk_t lblk, bool allocated);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents_status.c (ffff800010470290)
Location: fs/ext4/extents_status.c:1966
Inline: False
```
**Symbols:**

```
ffff800010470290-ffff80001047044c: ext4_es_insert_delayed_block (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int ext4_es_insert_delayed_block(struct inode *inode, ext4_lblk_t lblk, bool allocated);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents_status.c (c06316fc)
Location: fs/ext4/extents_status.c:1966
Inline: False
```
**Symbols:**

```
c06316fc-c0631898: ext4_es_insert_delayed_block (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int ext4_es_insert_delayed_block(struct inode *inode, ext4_lblk_t lblk, bool allocated);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents_status.c (c0000000005908a0)
Location: fs/ext4/extents_status.c:1966
Inline: False
```
**Symbols:**

```
c0000000005908a0-c000000000590a98: ext4_es_insert_delayed_block (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int ext4_es_insert_delayed_block(struct inode *inode, ext4_lblk_t lblk, bool allocated);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents_status.c (ffffffe0002fca4c)
Location: fs/ext4/extents_status.c:1966
Inline: False
```
**Symbols:**

```
ffffffe0002fca4c-ffffffe0002fcb66: ext4_es_insert_delayed_block (STB_GLOBAL)
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
int ext4_es_insert_delayed_block(struct inode *inode, ext4_lblk_t lblk, bool allocated);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents_status.c (ffffffff813956e0)
Location: fs/ext4/extents_status.c:1966
Inline: False
```
**Symbols:**

```
ffffffff813956e0-ffffffff81395826: ext4_es_insert_delayed_block (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int ext4_es_insert_delayed_block(struct inode *inode, ext4_lblk_t lblk, bool allocated);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents_status.c (ffffffff81386170)
Location: fs/ext4/extents_status.c:1966
Inline: False
```
**Symbols:**

```
ffffffff81386170-ffffffff813862b6: ext4_es_insert_delayed_block (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int ext4_es_insert_delayed_block(struct inode *inode, ext4_lblk_t lblk, bool allocated);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents_status.c (ffffffff81393040)
Location: fs/ext4/extents_status.c:1966
Inline: False
```
**Symbols:**

```
ffffffff81393040-ffffffff81393186: ext4_es_insert_delayed_block (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int ext4_es_insert_delayed_block(struct inode *inode, ext4_lblk_t lblk, bool allocated);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/extents_status.c (ffffffff813a70b0)
Location: fs/ext4/extents_status.c:1966
Inline: False
```
**Symbols:**

```
ffffffff813a70b0-ffffffff813a7217: ext4_es_insert_delayed_block (STB_GLOBAL)
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
<details>
<summary>Changed between <code>6.2</code> and <code>6.5</code> ⚠️</summary>
<ul>
<li>
<b>Return type changed. </b>
<code>int</code> ➡️ <code>void</code>
</li>
</ul>
</details>
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
