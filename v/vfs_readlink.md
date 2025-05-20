# Function: <code>vfs_readlink</code>

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
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int vfs_readlink(struct dentry *dentry, char *buffer, int buflen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff812591a0)
Location: fs/namei.c:4634
Inline: False
Direct callers:
  - fs/stat.c:SyS_readlink
```
**Symbols:**

```
ffffffff812591a0-ffffffff812592b1: vfs_readlink (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int vfs_readlink(struct dentry *dentry, char *buffer, int buflen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff81265270)
Location: fs/namei.c:4700
Inline: False
Direct callers:
  - fs/stat.c:SyS_readlink
```
**Symbols:**

```
ffffffff81265270-ffffffff81265374: vfs_readlink (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int vfs_readlink(struct dentry *dentry, char *buffer, int buflen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff81287b10)
Location: fs/namei.c:4696
Inline: False
Direct callers:
  - fs/stat.c:SyS_readlink
```
**Symbols:**

```
ffffffff81287b10-ffffffff81287c20: vfs_readlink (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int vfs_readlink(struct dentry *dentry, char *buffer, int buflen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff812a6ef0)
Location: fs/namei.c:4748
Inline: False
Direct callers:
  - fs/stat.c:do_readlinkat
```
**Symbols:**

```
ffffffff812a6ef0-ffffffff812a7018: vfs_readlink (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int vfs_readlink(struct dentry *dentry, char *buffer, int buflen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff812bc110)
Location: fs/namei.c:4714
Inline: False
Direct callers:
  - fs/stat.c:do_readlinkat
```
**Symbols:**

```
ffffffff812bc110-ffffffff812bc235: vfs_readlink (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int vfs_readlink(struct dentry *dentry, char *buffer, int buflen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff812dfb20)
Location: fs/namei.c:4715
Inline: False
Direct callers:
  - fs/stat.c:do_readlinkat
```
**Symbols:**

```
ffffffff812dfb20-ffffffff812dfc41: vfs_readlink (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int vfs_readlink(struct dentry *dentry, char *buffer, int buflen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff812f1650)
Location: fs/namei.c:4710
Inline: False
Direct callers:
  - fs/stat.c:do_readlinkat
```
**Symbols:**

```
ffffffff812f1650-ffffffff812f1771: vfs_readlink (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int vfs_readlink(struct dentry *dentry, char *buffer, int buflen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff813298f0)
Location: fs/namei.c:4524
Inline: False
Direct callers:
  - fs/stat.c:do_readlinkat
```
**Symbols:**

```
ffffffff813298f0-ffffffff81329a11: vfs_readlink (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int vfs_readlink(struct dentry *dentry, char *buffer, int buflen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff81334e50)
Location: fs/namei.c:4528
Inline: False
Direct callers:
  - fs/stat.c:do_readlinkat
```
**Symbols:**

```
ffffffff81334e50-ffffffff81334f71: vfs_readlink (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int vfs_readlink(struct dentry *dentry, char *buffer, int buflen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff8133afe0)
Location: fs/namei.c:4774
Inline: False
Direct callers:
  - fs/stat.c:do_readlinkat
```
**Symbols:**

```
ffffffff8133afe0-ffffffff8133b101: vfs_readlink (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int vfs_readlink(struct dentry *dentry, char *buffer, int buflen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff81388c00)
Location: fs/namei.c:4854
Inline: False
Direct callers:
  - fs/stat.c:do_readlinkat
```
**Symbols:**

```
ffffffff81388c00-ffffffff81388d21: vfs_readlink (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int vfs_readlink(struct dentry *dentry, char *buffer, int buflen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff81409c80)
Location: fs/namei.c:4949
Inline: False
Direct callers:
  - fs/stat.c:do_readlinkat
```
**Symbols:**

```
ffffffff81409c80-ffffffff81409daa: vfs_readlink (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int vfs_readlink(struct dentry *dentry, char *buffer, int buflen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff814943c0)
Location: fs/namei.c:5005
Inline: False
Direct callers:
  - fs/stat.c:do_readlinkat
```
**Symbols:**

```
ffffffff814943c0-ffffffff814944ea: vfs_readlink (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int vfs_readlink(struct dentry *dentry, char *buffer, int buflen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff814c9430)
Location: fs/namei.c:5084
Inline: False
Direct callers:
  - fs/stat.c:do_readlinkat
```
**Symbols:**

```
ffffffff814c9430-ffffffff814c955a: vfs_readlink (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int vfs_readlink(struct dentry *dentry, char *buffer, int buflen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff814fbcf0)
Location: fs/namei.c:5116
Inline: False
Direct callers:
  - fs/stat.c:do_readlinkat
```
**Symbols:**

```
ffffffff814fbcf0-ffffffff814fbe1a: vfs_readlink (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
int vfs_readlink(struct dentry *dentry, char *buffer, int buflen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffff80001039ae90)
Location: fs/namei.c:4710
Inline: False
Direct callers:
  - fs/stat.c:do_readlinkat
```
**Symbols:**

```
ffff80001039ae90-ffff80001039b000: vfs_readlink (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int vfs_readlink(struct dentry *dentry, char *buffer, int buflen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (c05812f4)
Location: fs/namei.c:4710
Inline: False
Direct callers:
  - fs/stat.c:do_readlinkat
```
**Symbols:**

```
c05812f4-c0581430: vfs_readlink (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int vfs_readlink(struct dentry *dentry, char *buffer, int buflen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (c000000000495d10)
Location: fs/namei.c:4710
Inline: False
Direct callers:
  - fs/stat.c:do_readlinkat
```
**Symbols:**

```
c000000000495d10-c000000000495ec8: vfs_readlink (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int vfs_readlink(struct dentry *dentry, char *buffer, int buflen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffe000268444)
Location: fs/namei.c:4710
Inline: False
Direct callers:
  - fs/stat.c:do_readlinkat
```
**Symbols:**

```
ffffffe000268444-ffffffe000268546: vfs_readlink (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
int vfs_readlink(struct dentry *dentry, char *buffer, int buflen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff812e9c30)
Location: fs/namei.c:4710
Inline: False
Direct callers:
  - fs/stat.c:do_readlinkat
```
**Symbols:**

```
ffffffff812e9c30-ffffffff812e9d51: vfs_readlink (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int vfs_readlink(struct dentry *dentry, char *buffer, int buflen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff812da870)
Location: fs/namei.c:4710
Inline: False
Direct callers:
  - fs/stat.c:do_readlinkat
```
**Symbols:**

```
ffffffff812da870-ffffffff812da991: vfs_readlink (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int vfs_readlink(struct dentry *dentry, char *buffer, int buflen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff812e7a40)
Location: fs/namei.c:4710
Inline: False
Direct callers:
  - fs/stat.c:do_readlinkat
```
**Symbols:**

```
ffffffff812e7a40-ffffffff812e7b61: vfs_readlink (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int vfs_readlink(struct dentry *dentry, char *buffer, int buflen);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff812f89c0)
Location: fs/namei.c:4710
Inline: False
Direct callers:
  - fs/stat.c:do_readlinkat
```
**Symbols:**

```
ffffffff812f89c0-ffffffff812f8adb: vfs_readlink (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
