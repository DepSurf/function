# Function: <code>ext4_encrypted_get_link</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
const char *ext4_encrypted_get_link(struct dentry *dentry, struct inode *inode, struct delayed_call *done);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/symlink.c (ffffffff812edea0)
Location: fs/ext4/symlink.c:25
Inline: False
```
**Symbols:**

```
ffffffff812edea0-ffffffff812ee0ed: ext4_encrypted_get_link (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
const char *ext4_encrypted_get_link(struct dentry *dentry, struct inode *inode, struct delayed_call *done);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/symlink.c (ffffffff81303e60)
Location: fs/ext4/symlink.c:25
Inline: False
```
**Symbols:**

```
ffffffff81303e60-ffffffff813040b1: ext4_encrypted_get_link (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
const char *ext4_encrypted_get_link(struct dentry *dentry, struct inode *inode, struct delayed_call *done);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/symlink.c (ffffffff81339070)
Location: fs/ext4/symlink.c:25
Inline: False
```
**Symbols:**

```
ffffffff81339070-ffffffff81339273: ext4_encrypted_get_link (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
const char *ext4_encrypted_get_link(struct dentry *dentry, struct inode *inode, struct delayed_call *done);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/symlink.c (ffffffff8135d370)
Location: fs/ext4/symlink.c:26
Inline: False
```
**Symbols:**

```
ffffffff8135d370-ffffffff8135d5e3: ext4_encrypted_get_link (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
const char *ext4_encrypted_get_link(struct dentry *dentry, struct inode *inode, struct delayed_call *done);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/symlink.c (ffffffff8138bd80)
Location: fs/ext4/symlink.c:26
Inline: True
```
**Symbols:**

```
ffffffff8138bd80-ffffffff8138be8f: ext4_encrypted_get_link (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
const char *ext4_encrypted_get_link(struct dentry *dentry, struct inode *inode, struct delayed_call *done);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/symlink.c (ffffffff813a4910)
Location: fs/ext4/symlink.c:26
Inline: True
```
**Symbols:**

```
ffffffff813a4910-ffffffff813a4a1f: ext4_encrypted_get_link (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
const char *ext4_encrypted_get_link(struct dentry *dentry, struct inode *inode, struct delayed_call *done);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/symlink.c (ffffffff813ceaf0)
Location: fs/ext4/symlink.c:26
Inline: True
```
**Symbols:**

```
ffffffff813ceaf0-ffffffff813cebfe: ext4_encrypted_get_link (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
const char *ext4_encrypted_get_link(struct dentry *dentry, struct inode *inode, struct delayed_call *done);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/symlink.c (ffffffff813e81c0)
Location: fs/ext4/symlink.c:26
Inline: True
```
**Symbols:**

```
ffffffff813e81c0-ffffffff813e82ce: ext4_encrypted_get_link (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
const char *ext4_encrypted_get_link(struct dentry *dentry, struct inode *inode, struct delayed_call *done);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/ext4/symlink.c (ffffffff81434d30)
Location: fs/ext4/symlink.c:26
Inline: True
```
**Symbols:**

```
ffffffff81434d30-ffffffff81434e37: ext4_encrypted_get_link.part.0 (STB_LOCAL)
ffffffff81434e40-ffffffff81434e63: ext4_encrypted_get_link (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

```c
const char *ext4_encrypted_get_link(struct dentry *dentry, struct inode *inode, struct delayed_call *done);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In fs/ext4/symlink.c (ffffffff8144d810)
Location: fs/ext4/symlink.c:26
Inline: True
```
**Symbols:**

```
ffffffff8144d810-ffffffff8144d914: ext4_encrypted_get_link.part.0 (STB_LOCAL)
ffffffff8144d920-ffffffff8144d943: ext4_encrypted_get_link (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
const char *ext4_encrypted_get_link(struct dentry *dentry, struct inode *inode, struct delayed_call *done);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/symlink.c (ffffffff81453300)
Location: fs/ext4/symlink.c:26
Inline: True
```
**Symbols:**

```
ffffffff81453300-ffffffff8145340a: ext4_encrypted_get_link (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
const char *ext4_encrypted_get_link(struct dentry *dentry, struct inode *inode, struct delayed_call *done);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/symlink.c (ffffffff814a72e0)
Location: fs/ext4/symlink.c:26
Inline: True
```
**Symbols:**

```
ffffffff814a72e0-ffffffff814a73e7: ext4_encrypted_get_link (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
const char *ext4_encrypted_get_link(struct dentry *dentry, struct inode *inode, struct delayed_call *done);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/symlink.c (ffffffff8152eb20)
Location: fs/ext4/symlink.c:26
Inline: True
```
**Symbols:**

```
ffffffff8152eb20-ffffffff8152ec28: ext4_encrypted_get_link (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
const char *ext4_encrypted_get_link(struct dentry *dentry, struct inode *inode, struct delayed_call *done);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/symlink.c (ffffffff815ccc90)
Location: fs/ext4/symlink.c:26
Inline: True
```
**Symbols:**

```
ffffffff815ccc90-ffffffff815ccd98: ext4_encrypted_get_link (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
const char *ext4_encrypted_get_link(struct dentry *dentry, struct inode *inode, struct delayed_call *done);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/symlink.c (ffffffff81604780)
Location: fs/ext4/symlink.c:26
Inline: True
```
**Symbols:**

```
ffffffff81604780-ffffffff81604888: ext4_encrypted_get_link (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
const char *ext4_encrypted_get_link(struct dentry *dentry, struct inode *inode, struct delayed_call *done);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/symlink.c (ffffffff8163d440)
Location: fs/ext4/symlink.c:26
Inline: True
```
**Symbols:**

```
ffffffff8163d440-ffffffff8163d548: ext4_encrypted_get_link (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
const char *ext4_encrypted_get_link(struct dentry *dentry, struct inode *inode, struct delayed_call *done);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/symlink.c (ffff8000104c0e90)
Location: fs/ext4/symlink.c:26
Inline: True
```
**Symbols:**

```
ffff8000104c0e90-ffff8000104c0fbc: ext4_encrypted_get_link (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
const char *ext4_encrypted_get_link(struct dentry *dentry, struct inode *inode, struct delayed_call *done);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/symlink.c (c0684b24)
Location: fs/ext4/symlink.c:26
Inline: True
```
**Symbols:**

```
c0684b24-c0684c10: ext4_encrypted_get_link (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
const char *ext4_encrypted_get_link(struct dentry *dentry, struct inode *inode, struct delayed_call *done);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/symlink.c (c0000000005f7770)
Location: fs/ext4/symlink.c:26
Inline: True
```
**Symbols:**

```
c0000000005f7770-c0000000005f7968: ext4_encrypted_get_link (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
const char *ext4_encrypted_get_link(struct dentry *dentry, struct inode *inode, struct delayed_call *done);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/symlink.c (ffffffe00033c56e)
Location: fs/ext4/symlink.c:26
Inline: True
```
**Symbols:**

```
ffffffe00033c56e-ffffffe00033c64a: ext4_encrypted_get_link (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
const char *ext4_encrypted_get_link(struct dentry *dentry, struct inode *inode, struct delayed_call *done);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/symlink.c (ffffffff813e07a0)
Location: fs/ext4/symlink.c:26
Inline: True
```
**Symbols:**

```
ffffffff813e07a0-ffffffff813e08ae: ext4_encrypted_get_link (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
const char *ext4_encrypted_get_link(struct dentry *dentry, struct inode *inode, struct delayed_call *done);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/symlink.c (ffffffff813d1220)
Location: fs/ext4/symlink.c:26
Inline: True
```
**Symbols:**

```
ffffffff813d1220-ffffffff813d132e: ext4_encrypted_get_link (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
const char *ext4_encrypted_get_link(struct dentry *dentry, struct inode *inode, struct delayed_call *done);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/symlink.c (ffffffff813ddb20)
Location: fs/ext4/symlink.c:26
Inline: True
```
**Symbols:**

```
ffffffff813ddb20-ffffffff813ddc2e: ext4_encrypted_get_link (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
const char *ext4_encrypted_get_link(struct dentry *dentry, struct inode *inode, struct delayed_call *done);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/symlink.c (ffffffff813f2f40)
Location: fs/ext4/symlink.c:26
Inline: True
```
**Symbols:**

```
ffffffff813f2f40-ffffffff813f304e: ext4_encrypted_get_link (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
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
No changes between <code>6.2</code> and <code>6.5</code> ✅
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
