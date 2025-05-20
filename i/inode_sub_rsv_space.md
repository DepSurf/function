# Function: <code>inode_sub_rsv_space</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void inode_sub_rsv_space(struct inode *inode, qsize_t number);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/quota/dquot.c (ffffffff81270f00)
Location: fs/quota/dquot.c:1596
Inline: False
Direct callers:
  - fs/quota/dquot.c:__dquot_free_space
  - fs/quota/dquot.c:__dquot_free_space
```
**Symbols:**

```
ffffffff81270f00-ffffffff81270f3f: inode_sub_rsv_space (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void inode_sub_rsv_space(struct inode *inode, qsize_t number);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/quota/dquot.c (ffffffff8129d3f0)
Location: fs/quota/dquot.c:1604
Inline: False
Direct callers:
  - fs/quota/dquot.c:__dquot_free_space
  - fs/quota/dquot.c:__dquot_free_space
```
**Symbols:**

```
ffffffff8129d3f0-ffffffff8129d42f: inode_sub_rsv_space (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void inode_sub_rsv_space(struct inode *inode, qsize_t number);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/quota/dquot.c (ffffffff812b2d30)
Location: fs/quota/dquot.c:1601
Inline: False
Direct callers:
  - fs/quota/dquot.c:__dquot_free_space
  - fs/quota/dquot.c:__dquot_free_space
```
**Symbols:**

```
ffffffff812b2d30-ffffffff812b2d6f: inode_sub_rsv_space (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void inode_sub_rsv_space(struct inode *inode, qsize_t number);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/quota/dquot.c (ffffffff812c0340)
Location: fs/quota/dquot.c:1627
Inline: False
Direct callers:
  - fs/quota/dquot.c:__dquot_free_space
  - fs/quota/dquot.c:__dquot_free_space
```
**Symbols:**

```
ffffffff812c0340-ffffffff812c037f: inode_sub_rsv_space (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>4.15</code>: Absent ⚠️
</li>
<li>
In <code>4.18</code>: Absent ⚠️
</li>
<li>
In <code>5.0</code>: Absent ⚠️
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
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
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
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
</ul>
