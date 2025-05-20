# Function: <code>generic_ci_d_hash</code>

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
int generic_ci_d_hash(const struct dentry *dentry, struct qstr *str);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/libfs.c (ffffffff81351b60)
Location: fs/libfs.c:1438
Inline: False
```
**Symbols:**

```
ffffffff81351b60-ffffffff81351bbf: generic_ci_d_hash (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int generic_ci_d_hash(const struct dentry *dentry, struct qstr *str);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/libfs.c (ffffffff81358880)
Location: fs/libfs.c:1437
Inline: False
```
**Symbols:**

```
ffffffff81358880-ffffffff813588dc: generic_ci_d_hash (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int generic_ci_d_hash(const struct dentry *dentry, struct qstr *str);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/libfs.c (ffffffff813a6ef0)
Location: fs/libfs.c:1421
Inline: False
```
**Symbols:**

```
ffffffff813a6ef0-ffffffff813a6f4c: generic_ci_d_hash (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int generic_ci_d_hash(const struct dentry *dentry, struct qstr *str);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/libfs.c (ffffffff8142bbe0)
Location: fs/libfs.c:1437
Inline: False
```
**Symbols:**

```
ffffffff8142bbe0-ffffffff8142bc48: generic_ci_d_hash (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int generic_ci_d_hash(const struct dentry *dentry, struct qstr *str);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/libfs.c (ffffffff814b8d00)
Location: fs/libfs.c:1454
Inline: False
```
**Symbols:**

```
ffffffff814b8d00-ffffffff814b8d68: generic_ci_d_hash (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int generic_ci_d_hash(const struct dentry *dentry, struct qstr *str);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/libfs.c (ffffffff814edf10)
Location: fs/libfs.c:1449
Inline: False
```
**Symbols:**

```
ffffffff814edf10-ffffffff814edf78: generic_ci_d_hash (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int generic_ci_d_hash(const struct dentry *dentry, struct qstr *str);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/libfs.c (ffffffff81521bb0)
Location: fs/libfs.c:1750
Inline: False
```
**Symbols:**

```
ffffffff81521bb0-ffffffff81521c0a: generic_ci_d_hash (STB_LOCAL)
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
