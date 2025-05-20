# Function: <code>generic_set_encrypted_ci_d_ops</code>

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
void generic_set_encrypted_ci_d_ops(struct dentry *dentry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/libfs.c (ffffffff813511c0)
Location: fs/libfs.c:1497
Inline: False
```
**Symbols:**

```
ffffffff813511c0-ffffffff81351215: generic_set_encrypted_ci_d_ops (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void generic_set_encrypted_ci_d_ops(struct dentry *dentry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/libfs.c (ffffffff81357ed0)
Location: fs/libfs.c:1495
Inline: False
```
**Symbols:**

```
ffffffff81357ed0-ffffffff81357f25: generic_set_encrypted_ci_d_ops (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void generic_set_encrypted_ci_d_ops(struct dentry *dentry);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/libfs.c (ffffffff813a62f0)
Location: fs/libfs.c:1479
Inline: False
```
**Symbols:**

```
ffffffff813a62f0-ffffffff813a6345: generic_set_encrypted_ci_d_ops (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void generic_set_encrypted_ci_d_ops(struct dentry *dentry);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/libfs.c (ffffffff8142bc50)
Location: fs/libfs.c:1495
Inline: True
Direct callers:
  - fs/ext4/namei.c:ext4_lookup
```
**Symbols:**

```
ffffffff8142bc50-ffffffff8142bcc9: generic_set_encrypted_ci_d_ops (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void generic_set_encrypted_ci_d_ops(struct dentry *dentry);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/libfs.c (ffffffff814b8e00)
Location: fs/libfs.c:1512
Inline: True
Direct callers:
  - fs/ext4/namei.c:ext4_lookup
```
**Symbols:**

```
ffffffff814b8e00-ffffffff814b8e79: generic_set_encrypted_ci_d_ops (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void generic_set_encrypted_ci_d_ops(struct dentry *dentry);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/libfs.c (ffffffff814ee0e0)
Location: fs/libfs.c:1507
Inline: True
Direct callers:
  - fs/ext4/namei.c:ext4_lookup
```
**Symbols:**

```
ffffffff814ee0e0-ffffffff814ee159: generic_set_encrypted_ci_d_ops (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void generic_set_encrypted_ci_d_ops(struct dentry *dentry);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/libfs.c (ffffffff81521e50)
Location: fs/libfs.c:1808
Inline: True
Direct callers:
  - fs/ext4/namei.c:ext4_lookup
```
**Symbols:**

```
ffffffff81521e50-ffffffff81521ec9: generic_set_encrypted_ci_d_ops (STB_GLOBAL)
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
