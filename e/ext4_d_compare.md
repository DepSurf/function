# Function: <code>ext4_d_compare</code>

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
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
int ext4_d_compare(const struct dentry *dentry, unsigned int len, const char *str, const struct qstr *name);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/ext4/dir.c (ffffffff81377760)
Location: fs/ext4/dir.c:667
Inline: True
```
**Symbols:**

```
ffffffff81377760-ffffffff813777df: ext4_d_compare (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int ext4_d_compare(const struct dentry *dentry, unsigned int len, const char *str, const struct qstr *name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/dir.c (ffffffff8138f9c0)
Location: fs/ext4/dir.c:674
Inline: False
```
**Symbols:**

```
ffffffff8138f9c0-ffffffff8138fa5d: ext4_d_compare (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int ext4_d_compare(const struct dentry *dentry, unsigned int len, const char *str, const struct qstr *name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/dir.c (ffffffff813daeb0)
Location: fs/ext4/dir.c:672
Inline: False
```
**Symbols:**

```
ffffffff813daeb0-ffffffff813dafcc: ext4_d_compare (STB_LOCAL)
```
</details>
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
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
int ext4_d_compare(const struct dentry *dentry, unsigned int len, const char *str, const struct qstr *name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/dir.c (ffff800010462498)
Location: fs/ext4/dir.c:674
Inline: False
```
**Symbols:**

```
ffff800010462498-ffff800010462564: ext4_d_compare (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int ext4_d_compare(const struct dentry *dentry, unsigned int len, const char *str, const struct qstr *name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/dir.c (c0622a54)
Location: fs/ext4/dir.c:674
Inline: False
```
**Symbols:**

```
c0622a54-c0622b24: ext4_d_compare (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int ext4_d_compare(const struct dentry *dentry, unsigned int len, const char *str, const struct qstr *name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/dir.c (c00000000057ef90)
Location: fs/ext4/dir.c:674
Inline: False
```
**Symbols:**

```
c00000000057ef90-c00000000057f088: ext4_d_compare (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int ext4_d_compare(const struct dentry *dentry, unsigned int len, const char *str, const struct qstr *name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/dir.c (ffffffe0002f1248)
Location: fs/ext4/dir.c:674
Inline: False
```
**Symbols:**

```
ffffffe0002f1248-ffffffe0002f12e4: ext4_d_compare (STB_LOCAL)
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
int ext4_d_compare(const struct dentry *dentry, unsigned int len, const char *str, const struct qstr *name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/dir.c (ffffffff81387fa0)
Location: fs/ext4/dir.c:674
Inline: False
```
**Symbols:**

```
ffffffff81387fa0-ffffffff8138803d: ext4_d_compare (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int ext4_d_compare(const struct dentry *dentry, unsigned int len, const char *str, const struct qstr *name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/dir.c (ffffffff81378a30)
Location: fs/ext4/dir.c:674
Inline: False
```
**Symbols:**

```
ffffffff81378a30-ffffffff81378acd: ext4_d_compare (STB_LOCAL)
```
</details>
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int ext4_d_compare(const struct dentry *dentry, unsigned int len, const char *str, const struct qstr *name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/dir.c (ffffffff813995f0)
Location: fs/ext4/dir.c:674
Inline: False
```
**Symbols:**

```
ffffffff813995f0-ffffffff8139968d: ext4_d_compare (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
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
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
