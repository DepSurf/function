# Function: <code>selinux_inode_init_security_anon</code>

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
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int selinux_inode_init_security_anon(struct inode *inode, const struct qstr *name, const struct inode *context_inode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/hooks.c (0)
Location: security/selinux/hooks.c:3035
Inline: False
```
**Symbols:**

```
ffffffff814d3f20-ffffffff814d4032: selinux_inode_init_security_anon (STB_LOCAL)
ffffffff81be21be-ffffffff81be21d4: selinux_inode_init_security_anon.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int selinux_inode_init_security_anon(struct inode *inode, const struct qstr *name, const struct inode *context_inode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/hooks.c (0)
Location: security/selinux/hooks.c:3028
Inline: False
```
**Symbols:**

```
ffffffff8152fb90-ffffffff8152fca9: selinux_inode_init_security_anon (STB_LOCAL)
ffffffff81cd3761-ffffffff81cd379b: selinux_inode_init_security_anon.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int selinux_inode_init_security_anon(struct inode *inode, const struct qstr *name, const struct inode *context_inode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/hooks.c (0)
Location: security/selinux/hooks.c:2920
Inline: False
```
**Symbols:**

```
ffffffff815c71c0-ffffffff815c7329: selinux_inode_init_security_anon (STB_LOCAL)
ffffffff81e86879-ffffffff81e868ab: selinux_inode_init_security_anon.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int selinux_inode_init_security_anon(struct inode *inode, const struct qstr *name, const struct inode *context_inode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/hooks.c (0)
Location: security/selinux/hooks.c:2919
Inline: False
```
**Symbols:**

```
ffffffff81673fa0-ffffffff8167411c: selinux_inode_init_security_anon (STB_LOCAL)
ffffffff82073393-ffffffff820733af: selinux_inode_init_security_anon.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int selinux_inode_init_security_anon(struct inode *inode, const struct qstr *name, const struct inode *context_inode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/hooks.c (0)
Location: security/selinux/hooks.c:2919
Inline: False
```
**Symbols:**

```
ffffffff816ac7c0-ffffffff816ac92a: selinux_inode_init_security_anon (STB_LOCAL)
ffffffff820f2fc0-ffffffff820f2fdc: selinux_inode_init_security_anon.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int selinux_inode_init_security_anon(struct inode *inode, const struct qstr *name, const struct inode *context_inode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In security/selinux/hooks.c (0)
Location: security/selinux/hooks.c:2983
Inline: False
```
**Symbols:**

```
ffffffff816e9b30-ffffffff816e9c9d: selinux_inode_init_security_anon (STB_LOCAL)
ffffffff821d02d4-ffffffff821d02f0: selinux_inode_init_security_anon.cold (STB_LOCAL)
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
