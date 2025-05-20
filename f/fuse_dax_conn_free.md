# Function: <code>fuse_dax_conn_free</code>

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
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void fuse_dax_conn_free(struct fuse_conn *fc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/dax.c (ffffffff8149e060)
Location: fs/fuse/dax.c:1226
Inline: False
Direct callers:
  - fs/fuse/inode.c:fuse_fill_super_common
```
**Symbols:**

```
ffffffff8149e060-ffffffff8149e097: fuse_dax_conn_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void fuse_dax_conn_free(struct fuse_conn *fc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/dax.c (ffffffff814a4030)
Location: fs/fuse/dax.c:1226
Inline: False
Direct callers:
  - fs/fuse/inode.c:fuse_fill_super_common
```
**Symbols:**

```
ffffffff814a4030-ffffffff814a4067: fuse_dax_conn_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void fuse_dax_conn_free(struct fuse_conn *fc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/dax.c (ffffffff814fc0d0)
Location: fs/fuse/dax.c:1225
Inline: False
Direct callers:
  - fs/fuse/inode.c:fuse_fill_super_common
```
**Symbols:**

```
ffffffff814fc0d0-ffffffff814fc107: fuse_dax_conn_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void fuse_dax_conn_free(struct fuse_conn *fc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/dax.c (ffffffff8158c660)
Location: fs/fuse/dax.c:1222
Inline: False
Direct callers:
  - fs/fuse/inode.c:fuse_fill_super_common
```
**Symbols:**

```
ffffffff8158c660-ffffffff8158c69d: fuse_dax_conn_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void fuse_dax_conn_free(struct fuse_conn *fc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/dax.c (ffffffff81632f10)
Location: fs/fuse/dax.c:1222
Inline: False
Direct callers:
  - fs/fuse/inode.c:fuse_fill_super_common
```
**Symbols:**

```
ffffffff81632f10-ffffffff81632f4d: fuse_dax_conn_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void fuse_dax_conn_free(struct fuse_conn *fc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/dax.c (ffffffff8166b200)
Location: fs/fuse/dax.c:1222
Inline: False
Direct callers:
  - fs/fuse/inode.c:fuse_fill_super_common
```
**Symbols:**

```
ffffffff8166b200-ffffffff8166b23d: fuse_dax_conn_free (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void fuse_dax_conn_free(struct fuse_conn *fc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/dax.c (ffffffff816a5540)
Location: fs/fuse/dax.c:1220
Inline: False
Direct callers:
  - fs/fuse/inode.c:fuse_fill_super_common
```
**Symbols:**

```
ffffffff816a5540-ffffffff816a5588: fuse_dax_conn_free (STB_GLOBAL)
```
</details>
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
