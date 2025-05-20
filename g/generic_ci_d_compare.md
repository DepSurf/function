# Function: <code>generic_ci_d_compare</code>

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
int generic_ci_d_compare(const struct dentry *dentry, unsigned int len, const char *str, const struct qstr *name);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/libfs.c (ffffffff81351a00)
Location: fs/libfs.c:1391
Inline: False
```
**Symbols:**

```
ffffffff81351a00-ffffffff81351b58: generic_ci_d_compare (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int generic_ci_d_compare(const struct dentry *dentry, unsigned int len, const char *str, const struct qstr *name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/libfs.c (ffffffff81358720)
Location: fs/libfs.c:1391
Inline: False
```
**Symbols:**

```
ffffffff81358720-ffffffff81358878: generic_ci_d_compare (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int generic_ci_d_compare(const struct dentry *dentry, unsigned int len, const char *str, const struct qstr *name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/libfs.c (ffffffff813a6d60)
Location: fs/libfs.c:1375
Inline: False
```
**Symbols:**

```
ffffffff813a6d60-ffffffff813a6eec: generic_ci_d_compare (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int generic_ci_d_compare(const struct dentry *dentry, unsigned int len, const char *str, const struct qstr *name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/libfs.c (ffffffff8142ba20)
Location: fs/libfs.c:1391
Inline: False
```
**Symbols:**

```
ffffffff8142ba20-ffffffff8142bbd5: generic_ci_d_compare (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int generic_ci_d_compare(const struct dentry *dentry, unsigned int len, const char *str, const struct qstr *name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/libfs.c (ffffffff814b8b30)
Location: fs/libfs.c:1408
Inline: False
```
**Symbols:**

```
ffffffff814b8b30-ffffffff814b8ce5: generic_ci_d_compare (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int generic_ci_d_compare(const struct dentry *dentry, unsigned int len, const char *str, const struct qstr *name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/libfs.c (ffffffff814edd40)
Location: fs/libfs.c:1403
Inline: False
```
**Symbols:**

```
ffffffff814edd40-ffffffff814edef5: generic_ci_d_compare (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int generic_ci_d_compare(const struct dentry *dentry, unsigned int len, const char *str, const struct qstr *name);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/libfs.c (ffffffff815219e0)
Location: fs/libfs.c:1704
Inline: False
```
**Symbols:**

```
ffffffff815219e0-ffffffff81521b9c: generic_ci_d_compare (STB_LOCAL)
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
