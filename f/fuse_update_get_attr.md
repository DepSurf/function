# Function: <code>fuse_update_get_attr</code>

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
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/fuse/dir.c (ffffffff81397a6d)
Location: fs/fuse/dir.c:926
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_getattr
  - fs/fuse/dir.c:fuse_update_attributes
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
In fs/fuse/dir.c (ffffffff813c6cd4)
Location: fs/fuse/dir.c:927
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_getattr
  - fs/fuse/dir.c:fuse_update_attributes
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
In fs/fuse/dir.c (ffffffff813dfead)
Location: fs/fuse/dir.c:924
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_getattr
  - fs/fuse/dir.c:fuse_getattr
  - fs/fuse/dir.c:fuse_update_attributes
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
In fs/fuse/dir.c (ffffffff8140baac)
Location: fs/fuse/dir.c:911
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_getattr
  - fs/fuse/dir.c:fuse_getattr
  - fs/fuse/dir.c:fuse_update_attributes
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
In fs/fuse/dir.c (ffffffff8142555c)
Location: fs/fuse/dir.c:969
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_getattr
  - fs/fuse/dir.c:fuse_getattr
  - fs/fuse/dir.c:fuse_update_attributes
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/fuse/dir.c (ffffffff8147381b)
Location: fs/fuse/dir.c:969
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_getattr
  - fs/fuse/dir.c:fuse_update_attributes
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/fuse/dir.c (ffffffff8148f693)
Location: fs/fuse/dir.c:1069
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_getattr
  - fs/fuse/dir.c:fuse_update_attributes
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
In fs/fuse/dir.c (ffffffff814950b3)
Location: fs/fuse/dir.c:1086
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_getattr
  - fs/fuse/dir.c:fuse_update_attributes
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/fuse/dir.c (ffffffff814ecb43)
Location: fs/fuse/dir.c:1034
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_getattr
  - fs/fuse/dir.c:fuse_update_attributes
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/fuse/dir.c (ffffffff8157b8c2)
Location: fs/fuse/dir.c:1114
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_getattr
  - fs/fuse/dir.c:fuse_update_attributes
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/fuse/dir.c (ffffffff81621282)
Location: fs/fuse/dir.c:1137
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_getattr
  - fs/fuse/dir.c:fuse_update_attributes
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/fuse/dir.c (ffffffff816596d2)
Location: fs/fuse/dir.c:1203
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_getattr
  - fs/fuse/dir.c:fuse_update_attributes
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int fuse_update_get_attr(struct inode *inode, struct file *file, struct kstat *stat, u32 request_mask, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/dir.c (ffffffff81691180)
Location: fs/fuse/dir.c:1281
Inline: False
Direct callers:
  - fs/fuse/dir.c:fuse_getattr
  - fs/fuse/dir.c:fuse_update_attributes
```
**Symbols:**

```
ffffffff81691180-ffffffff81691305: fuse_update_get_attr (STB_LOCAL)
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
In fs/fuse/dir.c (ffff800010508d08)
Location: fs/fuse/dir.c:969
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_getattr
  - fs/fuse/dir.c:fuse_getattr
  - fs/fuse/dir.c:fuse_update_attributes
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int fuse_update_get_attr(struct inode *inode, struct file *file, struct kstat *stat, u32 request_mask, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fuse/dir.c (c06c39b8)
Location: fs/fuse/dir.c:969
Inline: True
Direct callers:
  - fs/fuse/dir.c:fuse_getattr
  - fs/fuse/dir.c:fuse_update_attributes
```
**Symbols:**

```
c06c39b8-c06c3a74: fuse_update_get_attr (STB_LOCAL)
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
In fs/fuse/dir.c (c00000000064e7e4)
Location: fs/fuse/dir.c:969
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_getattr
  - fs/fuse/dir.c:fuse_getattr
  - fs/fuse/dir.c:fuse_update_attributes
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
In fs/fuse/dir.c (ffffffe000374882)
Location: fs/fuse/dir.c:969
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_getattr
  - fs/fuse/dir.c:fuse_getattr
  - fs/fuse/dir.c:fuse_update_attributes
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
In fs/fuse/dir.c (ffffffff8141db3c)
Location: fs/fuse/dir.c:969
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_getattr
  - fs/fuse/dir.c:fuse_getattr
  - fs/fuse/dir.c:fuse_update_attributes
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
In fs/fuse/dir.c (ffffffff8140e5bc)
Location: fs/fuse/dir.c:969
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_getattr
  - fs/fuse/dir.c:fuse_getattr
  - fs/fuse/dir.c:fuse_update_attributes
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
In fs/fuse/dir.c (ffffffff81419cdc)
Location: fs/fuse/dir.c:969
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_getattr
  - fs/fuse/dir.c:fuse_getattr
  - fs/fuse/dir.c:fuse_update_attributes
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
In fs/fuse/dir.c (ffffffff81430a4c)
Location: fs/fuse/dir.c:969
Inline: True
Inline callers:
  - fs/fuse/dir.c:fuse_getattr
  - fs/fuse/dir.c:fuse_getattr
  - fs/fuse/dir.c:fuse_update_attributes
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
</ul>
<b>Arch</b>
<ul>
</ul>
