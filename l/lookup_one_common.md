# Function: <code>lookup_one_common</code>

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
In <code>5.13</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int lookup_one_common(struct user_namespace *mnt_userns, const char *name, struct dentry *base, int len, struct qstr *this);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff81382450)
Location: fs/namei.c:2600
Inline: False
Direct callers:
  - fs/namei.c:lookup_one_len_unlocked
  - fs/namei.c:lookup_one
  - fs/namei.c:lookup_one_len
  - fs/namei.c:try_lookup_one_len
```
**Symbols:**

```
ffffffff81382450-ffffffff81382513: lookup_one_common (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int lookup_one_common(struct user_namespace *mnt_userns, const char *name, struct dentry *base, int len, struct qstr *this);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff81401960)
Location: fs/namei.c:2646
Inline: False
Direct callers:
  - fs/namei.c:lookup_one_len_unlocked
  - fs/namei.c:lookup_one
  - fs/namei.c:lookup_one_len
  - fs/namei.c:try_lookup_one_len
```
**Symbols:**

```
ffffffff81401960-ffffffff81401a36: lookup_one_common (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int lookup_one_common(struct user_namespace *mnt_userns, const char *name, struct dentry *base, int len, struct qstr *this);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff8148ba70)
Location: fs/namei.c:2625
Inline: False
Direct callers:
  - fs/namei.c:lookup_one_len_unlocked
  - fs/namei.c:lookup_one
  - fs/namei.c:lookup_one_len
  - fs/namei.c:try_lookup_one_len
```
**Symbols:**

```
ffffffff8148ba70-ffffffff8148bb46: lookup_one_common (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int lookup_one_common(struct mnt_idmap *idmap, const char *name, struct dentry *base, int len, struct qstr *this);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff814bfac0)
Location: fs/namei.c:2656
Inline: False
Direct callers:
  - fs/namei.c:lookup_one_len_unlocked
  - fs/namei.c:lookup_one
  - fs/namei.c:lookup_one_len
  - fs/namei.c:try_lookup_one_len
```
**Symbols:**

```
ffffffff814bfac0-ffffffff814bfb96: lookup_one_common (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int lookup_one_common(struct mnt_idmap *idmap, const char *name, struct dentry *base, int len, struct qstr *this);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff814f1fb0)
Location: fs/namei.c:2673
Inline: False
Direct callers:
  - fs/namei.c:lookup_one_len_unlocked
  - fs/namei.c:lookup_one
  - fs/namei.c:lookup_one_len
  - fs/namei.c:try_lookup_one_len
```
**Symbols:**

```
ffffffff814f1fb0-ffffffff814f2086: lookup_one_common (STB_LOCAL)
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
No changes between <code>5.15</code> and <code>5.19</code> ✅
</li>
<li>
No changes between <code>5.19</code> and <code>6.2</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>6.2</code> and <code>6.5</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct mnt_idmap *idmap</code>
</li>
<li>
<b>Param removed. </b>
<code>struct user_namespace *mnt_userns</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
