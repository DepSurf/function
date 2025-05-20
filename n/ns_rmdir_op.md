# Function: <code>ns_rmdir_op</code>

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
int ns_rmdir_op(struct inode *dir, struct dentry *dentry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/apparmorfs.c (ffffffff813ad8e0)
Location: security/apparmor/apparmorfs.c:1070
Inline: False
```
**Symbols:**

```
ffffffff813ad8e0-ffffffff813add8a: ns_rmdir_op (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int ns_rmdir_op(struct inode *dir, struct dentry *dentry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In security/apparmor/apparmorfs.c (ffffffff813c46f0)
Location: security/apparmor/apparmorfs.c:1166
Inline: False
```
**Symbols:**

```
ffffffff813c46f0-ffffffff813c4b9a: ns_rmdir_op (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int ns_rmdir_op(struct inode *dir, struct dentry *dentry);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/apparmor/apparmorfs.c (ffffffff813da1e0)
Location: security/apparmor/apparmorfs.c:1674
Inline: True
```
**Symbols:**

```
ffffffff813da1e0-ffffffff813da496: ns_rmdir_op (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int ns_rmdir_op(struct inode *dir, struct dentry *dentry);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/apparmor/apparmorfs.c (ffffffff81400510)
Location: security/apparmor/apparmorfs.c:1738
Inline: True
```
**Symbols:**

```
ffffffff81400510-ffffffff814007fc: ns_rmdir_op (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
int ns_rmdir_op(struct inode *dir, struct dentry *dentry);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/apparmor/apparmorfs.c (ffffffff81432260)
Location: security/apparmor/apparmorfs.c:1735
Inline: True
```
**Symbols:**

```
ffffffff81432260-ffffffff8143254e: ns_rmdir_op (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int ns_rmdir_op(struct inode *dir, struct dentry *dentry);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/apparmor/apparmorfs.c (ffffffff8144e400)
Location: security/apparmor/apparmorfs.c:1733
Inline: True
```
**Symbols:**

```
ffffffff8144e400-ffffffff8144e714: ns_rmdir_op (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
int ns_rmdir_op(struct inode *dir, struct dentry *dentry);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/apparmor/apparmorfs.c (ffffffff8147be40)
Location: security/apparmor/apparmorfs.c:1738
Inline: True
```
**Symbols:**

```
ffffffff8147be40-ffffffff8147c112: ns_rmdir_op (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int ns_rmdir_op(struct inode *dir, struct dentry *dentry);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/apparmor/apparmorfs.c (ffffffff81495b10)
Location: security/apparmor/apparmorfs.c:1706
Inline: True
```
**Symbols:**

```
ffffffff81495b10-ffffffff81495de2: ns_rmdir_op (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
int ns_rmdir_op(struct inode *dir, struct dentry *dentry);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/apparmor/apparmorfs.c (ffffffff814ece20)
Location: security/apparmor/apparmorfs.c:1825
Inline: True
```
**Symbols:**

```
ffffffff814ece20-ffffffff814ed09a: ns_rmdir_op.part.0 (STB_LOCAL)
ffffffff814edfd0-ffffffff814ee07a: ns_rmdir_op (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

```c
int ns_rmdir_op(struct inode *dir, struct dentry *dentry);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In security/apparmor/apparmorfs.c (ffffffff8150a8c0)
Location: security/apparmor/apparmorfs.c:1825
Inline: True
```
**Symbols:**

```
ffffffff8150a8c0-ffffffff8150ab3a: ns_rmdir_op.part.0 (STB_LOCAL)
ffffffff8150b660-ffffffff8150b70a: ns_rmdir_op (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int ns_rmdir_op(struct inode *dir, struct dentry *dentry);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/apparmor/apparmorfs.c (ffffffff81511db0)
Location: security/apparmor/apparmorfs.c:1826
Inline: True
```
**Symbols:**

```
ffffffff81511db0-ffffffff81512094: ns_rmdir_op (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int ns_rmdir_op(struct inode *dir, struct dentry *dentry);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/apparmor/apparmorfs.c (ffffffff8156f9b0)
Location: security/apparmor/apparmorfs.c:1826
Inline: True
```
**Symbols:**

```
ffffffff8156f9b0-ffffffff8156fc94: ns_rmdir_op (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
int ns_rmdir_op(struct inode *dir, struct dentry *dentry);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/apparmor/apparmorfs.c (ffffffff8160dbc0)
Location: security/apparmor/apparmorfs.c:1846
Inline: True
```
**Symbols:**

```
ffffffff8160dbc0-ffffffff8160dea9: ns_rmdir_op (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
int ns_rmdir_op(struct inode *dir, struct dentry *dentry);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/apparmor/apparmorfs.c (ffffffff816bfa10)
Location: security/apparmor/apparmorfs.c:2034
Inline: True
```
**Symbols:**

```
ffffffff816bfa10-ffffffff816bfd00: ns_rmdir_op (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
int ns_rmdir_op(struct inode *dir, struct dentry *dentry);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/apparmor/apparmorfs.c (ffffffff816f8510)
Location: security/apparmor/apparmorfs.c:2082
Inline: True
```
**Symbols:**

```
ffffffff816f8510-ffffffff816f8800: ns_rmdir_op (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
int ns_rmdir_op(struct inode *dir, struct dentry *dentry);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/apparmor/apparmorfs.c (ffffffff817352c0)
Location: security/apparmor/apparmorfs.c:2080
Inline: True
```
**Symbols:**

```
ffffffff817352c0-ffffffff817355b3: ns_rmdir_op (STB_LOCAL)
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
int ns_rmdir_op(struct inode *dir, struct dentry *dentry);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/apparmor/apparmorfs.c (ffff80001058bb78)
Location: security/apparmor/apparmorfs.c:1706
Inline: True
```
**Symbols:**

```
ffff80001058bb78-ffff80001058be18: ns_rmdir_op (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int ns_rmdir_op(struct inode *dir, struct dentry *dentry);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/apparmor/apparmorfs.c (c073c6c8)
Location: security/apparmor/apparmorfs.c:1706
Inline: True
```
**Symbols:**

```
c073c6c8-c073c994: ns_rmdir_op (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
int ns_rmdir_op(struct inode *dir, struct dentry *dentry);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/apparmor/apparmorfs.c (c0000000006fcd40)
Location: security/apparmor/apparmorfs.c:1706
Inline: True
```
**Symbols:**

```
c0000000006fcd40-c0000000006fd1a8: ns_rmdir_op (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
int ns_rmdir_op(struct inode *dir, struct dentry *dentry);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/apparmor/apparmorfs.c (ffffffe0003d9e70)
Location: security/apparmor/apparmorfs.c:1706
Inline: True
```
**Symbols:**

```
ffffffe0003d9e70-ffffffe0003da0cc: ns_rmdir_op (STB_LOCAL)
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
int ns_rmdir_op(struct inode *dir, struct dentry *dentry);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/apparmor/apparmorfs.c (ffffffff8148e0f0)
Location: security/apparmor/apparmorfs.c:1706
Inline: True
```
**Symbols:**

```
ffffffff8148e0f0-ffffffff8148e3c2: ns_rmdir_op (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int ns_rmdir_op(struct inode *dir, struct dentry *dentry);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/apparmor/apparmorfs.c (ffffffff8147eb10)
Location: security/apparmor/apparmorfs.c:1706
Inline: True
```
**Symbols:**

```
ffffffff8147eb10-ffffffff8147ede2: ns_rmdir_op (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int ns_rmdir_op(struct inode *dir, struct dentry *dentry);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/apparmor/apparmorfs.c (ffffffff8148a190)
Location: security/apparmor/apparmorfs.c:1706
Inline: True
```
**Symbols:**

```
ffffffff8148a190-ffffffff8148a462: ns_rmdir_op (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int ns_rmdir_op(struct inode *dir, struct dentry *dentry);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In security/apparmor/apparmorfs.c (ffffffff814a1e60)
Location: security/apparmor/apparmorfs.c:1706
Inline: True
```
**Symbols:**

```
ffffffff814a1e60-ffffffff814a215f: ns_rmdir_op (STB_LOCAL)
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
