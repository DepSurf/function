# Function: <code>setattr_should_drop_sgid</code>

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
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
int setattr_should_drop_sgid(struct user_namespace *mnt_userns, const struct inode *inode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/attr.c (ffffffff814a53cd)
Location: fs/attr.c:36
Inline: True
Inline callers:
  - fs/attr.c:setattr_should_drop_suidgid
Direct callers:
  - fs/open.c:chown_common
```
**Symbols:**

```
ffffffff814a5fc0-ffffffff814a6053: setattr_should_drop_sgid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
int setattr_should_drop_sgid(struct mnt_idmap *idmap, const struct inode *inode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/attr.c (ffffffff814daf89)
Location: fs/attr.c:37
Inline: True
Inline callers:
  - fs/attr.c:setattr_should_drop_suidgid
Direct callers:
  - fs/open.c:chown_common
```
**Symbols:**

```
ffffffff814da4d0-ffffffff814da539: setattr_should_drop_sgid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
int setattr_should_drop_sgid(struct mnt_idmap *idmap, const struct inode *inode);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/attr.c (ffffffff8150d549)
Location: fs/attr.c:37
Inline: True
Inline callers:
  - fs/attr.c:setattr_should_drop_suidgid
Direct callers:
  - fs/open.c:chown_common
```
**Symbols:**

```
ffffffff8150ca60-ffffffff8150cac9: setattr_should_drop_sgid (STB_GLOBAL)
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
