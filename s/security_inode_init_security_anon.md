# Function: <code>security_inode_init_security_anon</code>

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
<summary>In <code>5.13</code>: ✅</summary>

```c
int security_inode_init_security_anon(struct inode *inode, const struct qstr *name, const struct inode *context_inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff814cd1e0)
Location: security/security.c:1277
Inline: False
Direct callers:
  - fs/anon_inodes.c:__anon_inode_getfile
```
**Symbols:**

```
ffffffff814cd1e0-ffffffff814cd22e: security_inode_init_security_anon (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int security_inode_init_security_anon(struct inode *inode, const struct qstr *name, const struct inode *context_inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff81526360)
Location: security/security.c:1277
Inline: False
Direct callers:
  - fs/anon_inodes.c:__anon_inode_getfile
```
**Symbols:**

```
ffffffff81526360-ffffffff815263ae: security_inode_init_security_anon (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int security_inode_init_security_anon(struct inode *inode, const struct qstr *name, const struct inode *context_inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff815ba7d0)
Location: security/security.c:1297
Inline: False
Direct callers:
  - fs/anon_inodes.c:__anon_inode_getfile
```
**Symbols:**

```
ffffffff815ba7d0-ffffffff815ba83d: security_inode_init_security_anon (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int security_inode_init_security_anon(struct inode *inode, const struct qstr *name, const struct inode *context_inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff816661b0)
Location: security/security.c:1295
Inline: False
Direct callers:
  - fs/anon_inodes.c:__anon_inode_getfile
```
**Symbols:**

```
ffffffff816661b0-ffffffff8166621d: security_inode_init_security_anon (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int security_inode_init_security_anon(struct inode *inode, const struct qstr *name, const struct inode *context_inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff8169e7a0)
Location: security/security.c:1803
Inline: False
Direct callers:
  - fs/anon_inodes.c:__anon_inode_getfile
```
**Symbols:**

```
ffffffff8169e7a0-ffffffff8169e80d: security_inode_init_security_anon (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int security_inode_init_security_anon(struct inode *inode, const struct qstr *name, const struct inode *context_inode);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/security.c (ffffffff816db0f0)
Location: security/security.c:1876
Inline: False
Direct callers:
  - fs/anon_inodes.c:__anon_inode_getfile
```
**Symbols:**

```
ffffffff816db0f0-ffffffff816db15d: security_inode_init_security_anon (STB_GLOBAL)
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
