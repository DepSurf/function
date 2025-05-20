# Function: <code>selinux_inode_setotherxattr</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int selinux_inode_setotherxattr(struct dentry *dentry, const char *name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff81348940)
Location: security/selinux/hooks.c:2981
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_inode_removexattr
  - security/selinux/hooks.c:selinux_inode_setxattr
```
**Symbols:**

```
ffffffff81348940-ffffffff81348a0f: selinux_inode_setotherxattr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int selinux_inode_setotherxattr(struct dentry *dentry, const char *name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff8137db30)
Location: security/selinux/hooks.c:3060
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_inode_removexattr
  - security/selinux/hooks.c:selinux_inode_setxattr
```
**Symbols:**

```
ffffffff8137db30-ffffffff8137dc15: selinux_inode_setotherxattr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int selinux_inode_setotherxattr(struct dentry *dentry, const char *name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff813945c0)
Location: security/selinux/hooks.c:3093
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_inode_removexattr
  - security/selinux/hooks.c:selinux_inode_setxattr
```
**Symbols:**

```
ffffffff813945c0-ffffffff813946a5: selinux_inode_setotherxattr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int selinux_inode_setotherxattr(struct dentry *dentry, const char *name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/selinux/hooks.c (ffffffff813aa4c0)
Location: security/selinux/hooks.c:3068
Inline: False
Direct callers:
  - security/selinux/hooks.c:selinux_inode_removexattr
  - security/selinux/hooks.c:selinux_inode_setxattr
```
**Symbols:**

```
ffffffff813aa4c0-ffffffff813aa58f: selinux_inode_setotherxattr (STB_LOCAL)
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
