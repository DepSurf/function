# Function: <code>try_to_unlazy_next</code>

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
bool try_to_unlazy_next(struct nameidata *nd, struct dentry *dentry, unsigned int seq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff81333200)
Location: fs/namei.c:779
Inline: False
Direct callers:
  - fs/namei.c:step_into
  - fs/namei.c:lookup_fast
```
**Symbols:**

```
ffffffff81333200-ffffffff813332c6: try_to_unlazy_next (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
bool try_to_unlazy_next(struct nameidata *nd, struct dentry *dentry, unsigned int seq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff81380b30)
Location: fs/namei.c:806
Inline: False
Direct callers:
  - fs/namei.c:step_into
  - fs/namei.c:lookup_fast
```
**Symbols:**

```
ffffffff81380b30-ffffffff81380bf6: try_to_unlazy_next (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
bool try_to_unlazy_next(struct nameidata *nd, struct dentry *dentry, unsigned int seq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff81400f10)
Location: fs/namei.c:800
Inline: False
Direct callers:
  - fs/namei.c:step_into
  - fs/namei.c:lookup_fast
```
**Symbols:**

```
ffffffff81400f10-ffffffff81401005: try_to_unlazy_next (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
bool try_to_unlazy_next(struct nameidata *nd, struct dentry *dentry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff8148acd0)
Location: fs/namei.c:804
Inline: False
Direct callers:
  - fs/namei.c:step_into
  - fs/namei.c:lookup_fast
```
**Symbols:**

```
ffffffff8148acd0-ffffffff8148addf: try_to_unlazy_next (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
bool try_to_unlazy_next(struct nameidata *nd, struct dentry *dentry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff814c13e0)
Location: fs/namei.c:807
Inline: False
Direct callers:
  - fs/namei.c:step_into
  - fs/namei.c:lookup_fast
```
**Symbols:**

```
ffffffff814c13e0-ffffffff814c14ef: try_to_unlazy_next (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
bool try_to_unlazy_next(struct nameidata *nd, struct dentry *dentry);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff814f38a0)
Location: fs/namei.c:810
Inline: False
Direct callers:
  - fs/namei.c:step_into
  - fs/namei.c:lookup_fast
```
**Symbols:**

```
ffffffff814f38a0-ffffffff814f39af: try_to_unlazy_next (STB_LOCAL)
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
<details>
<summary>Changed between <code>5.19</code> and <code>6.2</code> ⚠️</summary>
<ul>
<li>
<b>Param removed. </b>
<code>unsigned int seq</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
