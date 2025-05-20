# Function: <code>may_setattr</code>

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
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int may_setattr(struct user_namespace *mnt_userns, struct inode *inode, unsigned int ia_valid);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/attr.c (ffffffff813978e0)
Location: fs/attr.c:252
Inline: True
Direct callers:
  - fs/attr.c:notify_change
```
**Symbols:**

```
ffffffff813978e0-ffffffff81397945: may_setattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int may_setattr(struct user_namespace *mnt_userns, struct inode *inode, unsigned int ia_valid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/attr.c (ffffffff81419790)
Location: fs/attr.c:268
Inline: False
Direct callers:
  - fs/attr.c:notify_change
```
**Symbols:**

```
ffffffff81419790-ffffffff81419804: may_setattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int may_setattr(struct user_namespace *mnt_userns, struct inode *inode, unsigned int ia_valid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/attr.c (ffffffff814a5250)
Location: fs/attr.c:325
Inline: False
Direct callers:
  - fs/attr.c:notify_change
```
**Symbols:**

```
ffffffff814a5250-ffffffff814a52c4: may_setattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int may_setattr(struct mnt_idmap *idmap, struct inode *inode, unsigned int ia_valid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/attr.c (ffffffff814da680)
Location: fs/attr.c:326
Inline: False
Direct callers:
  - fs/attr.c:notify_change
```
**Symbols:**

```
ffffffff814da680-ffffffff814da6f4: may_setattr (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int may_setattr(struct mnt_idmap *idmap, struct inode *inode, unsigned int ia_valid);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/attr.c (ffffffff8150cc20)
Location: fs/attr.c:326
Inline: False
Direct callers:
  - fs/attr.c:notify_change
```
**Symbols:**

```
ffffffff8150cc20-ffffffff8150cc94: may_setattr (STB_GLOBAL)
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
<b>Param added. </b>
<code>struct mnt_idmap *idmap</code>
</li>
<li>
<b>Param removed. </b>
<code>struct user_namespace *mnt_userns</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
