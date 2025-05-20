# Function: <code>ext4_d_hash</code>

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
<summary>In <code>5.3</code>: ✅</summary>

```c
int ext4_d_hash(const struct dentry *dentry, struct qstr *str);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/dir.c (ffffffff81377660)
Location: fs/ext4/dir.c:681
Inline: False
```
**Symbols:**

```
ffffffff81377660-ffffffff81377724: ext4_d_hash (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int ext4_d_hash(const struct dentry *dentry, struct qstr *str);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/dir.c (ffffffff8138fa60)
Location: fs/ext4/dir.c:691
Inline: False
```
**Symbols:**

```
ffffffff8138fa60-ffffffff8138fb2e: ext4_d_hash (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int ext4_d_hash(const struct dentry *dentry, struct qstr *str);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/dir.c (ffffffff813dafd0)
Location: fs/ext4/dir.c:705
Inline: False
```
**Symbols:**

```
ffffffff813dafd0-ffffffff813db09e: ext4_d_hash (STB_LOCAL)
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
int ext4_d_hash(const struct dentry *dentry, struct qstr *str);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/dir.c (ffff800010462568)
Location: fs/ext4/dir.c:691
Inline: False
```
**Symbols:**

```
ffff800010462568-ffff80001046266c: ext4_d_hash (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int ext4_d_hash(const struct dentry *dentry, struct qstr *str);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/dir.c (c0622b24)
Location: fs/ext4/dir.c:691
Inline: False
```
**Symbols:**

```
c0622b24-c0622bfc: ext4_d_hash (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int ext4_d_hash(const struct dentry *dentry, struct qstr *str);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/dir.c (c00000000057f090)
Location: fs/ext4/dir.c:691
Inline: False
```
**Symbols:**

```
c00000000057f090-c00000000057f1ec: ext4_d_hash (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int ext4_d_hash(const struct dentry *dentry, struct qstr *str);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/dir.c (ffffffe0002f12e4)
Location: fs/ext4/dir.c:691
Inline: False
```
**Symbols:**

```
ffffffe0002f12e4-ffffffe0002f139c: ext4_d_hash (STB_LOCAL)
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
int ext4_d_hash(const struct dentry *dentry, struct qstr *str);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/dir.c (ffffffff81388040)
Location: fs/ext4/dir.c:691
Inline: False
```
**Symbols:**

```
ffffffff81388040-ffffffff8138810e: ext4_d_hash (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int ext4_d_hash(const struct dentry *dentry, struct qstr *str);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/dir.c (ffffffff81378ad0)
Location: fs/ext4/dir.c:691
Inline: False
```
**Symbols:**

```
ffffffff81378ad0-ffffffff81378b9e: ext4_d_hash (STB_LOCAL)
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
int ext4_d_hash(const struct dentry *dentry, struct qstr *str);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/dir.c (ffffffff81399690)
Location: fs/ext4/dir.c:691
Inline: False
```
**Symbols:**

```
ffffffff81399690-ffffffff8139975e: ext4_d_hash (STB_LOCAL)
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
