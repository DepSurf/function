# Function: <code>lookup_slow</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff812194a9)
Location: fs/namei.c:1626
Inline: True
Inline callers:
  - fs/namei.c:walk_component
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct dentry *lookup_slow(const struct qstr *name, struct dentry *dir, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff8123f410)
Location: fs/namei.c:1626
Inline: False
Direct callers:
  - fs/namei.c:path_mountpoint
  - fs/namei.c:lookup_one_len_unlocked
  - fs/namei.c:walk_component
```
**Symbols:**

```
ffffffff8123f410-ffffffff8123f56e: lookup_slow (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct dentry *lookup_slow(const struct qstr *name, struct dentry *dir, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff812521e0)
Location: fs/namei.c:1622
Inline: False
Direct callers:
  - fs/namei.c:path_mountpoint
  - fs/namei.c:lookup_one_len_unlocked
  - fs/namei.c:walk_component
```
**Symbols:**

```
ffffffff812521e0-ffffffff8125233e: lookup_slow (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct dentry *lookup_slow(const struct qstr *name, struct dentry *dir, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff8125e360)
Location: fs/namei.c:1625
Inline: False
Direct callers:
  - fs/namei.c:path_mountpoint
  - fs/namei.c:lookup_one_len_unlocked
  - fs/namei.c:walk_component
```
**Symbols:**

```
ffffffff8125e360-ffffffff8125e4be: lookup_slow (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct dentry *lookup_slow(const struct qstr *name, struct dentry *dir, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff81280730)
Location: fs/namei.c:1623
Inline: False
Direct callers:
  - fs/namei.c:path_mountpoint
  - fs/namei.c:lookup_one_len_unlocked
  - fs/namei.c:walk_component
```
**Symbols:**

```
ffffffff81280730-ffffffff8128089e: lookup_slow (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct dentry *lookup_slow(const struct qstr *name, struct dentry *dir, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff812a7170)
Location: fs/namei.c:1640
Inline: False
Direct callers:
  - fs/namei.c:path_mountpoint
  - fs/namei.c:lookup_one_len_unlocked
  - fs/namei.c:walk_component
```
**Symbols:**

```
ffffffff812a7170-ffffffff812a71c1: lookup_slow (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct dentry *lookup_slow(const struct qstr *name, struct dentry *dir, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff812bc390)
Location: fs/namei.c:1681
Inline: False
Direct callers:
  - fs/namei.c:path_mountpoint
  - fs/namei.c:lookup_one_len_unlocked
  - fs/namei.c:walk_component
```
**Symbols:**

```
ffffffff812bc390-ffffffff812bc3e1: lookup_slow (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct dentry *lookup_slow(const struct qstr *name, struct dentry *dir, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff812d8e30)
Location: fs/namei.c:1679
Inline: False
Direct callers:
  - fs/namei.c:path_mountpoint
  - fs/namei.c:lookup_one_len_unlocked
  - fs/namei.c:walk_component
```
**Symbols:**

```
ffffffff812d8e30-ffffffff812d8e83: lookup_slow (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct dentry *lookup_slow(const struct qstr *name, struct dentry *dir, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff812ea940)
Location: fs/namei.c:1674
Inline: False
Direct callers:
  - fs/namei.c:path_mountpoint
  - fs/namei.c:lookup_one_len_unlocked
  - fs/namei.c:walk_component
```
**Symbols:**

```
ffffffff812ea940-ffffffff812ea993: lookup_slow (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff8132406e)
Location: fs/namei.c:1554
Inline: True
Inline callers:
  - fs/namei.c:lookup_one_len_unlocked
  - fs/namei.c:walk_component
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff8132f66e)
Location: fs/namei.c:1554
Inline: True
Inline callers:
  - fs/namei.c:lookup_one_len_unlocked
  - fs/namei.c:walk_component
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff81334d2e)
Location: fs/namei.c:1639
Inline: True
Inline callers:
  - fs/namei.c:lookup_one_len_unlocked
  - fs/namei.c:walk_component
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff8138273d)
Location: fs/namei.c:1667
Inline: True
Inline callers:
  - fs/namei.c:lookup_one_len_unlocked
  - fs/namei.c:walk_component
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff81401e3a)
Location: fs/namei.c:1713
Inline: True
Inline callers:
  - fs/namei.c:lookup_one_len_unlocked
  - fs/namei.c:walk_component
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff8148bfba)
Location: fs/namei.c:1695
Inline: True
Inline callers:
  - fs/namei.c:lookup_one_len_unlocked
  - fs/namei.c:walk_component
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff814c185a)
Location: fs/namei.c:1700
Inline: True
Inline callers:
  - fs/namei.c:lookup_one_len_unlocked
  - fs/namei.c:walk_component
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff814f3d1a)
Location: fs/namei.c:1703
Inline: True
Inline callers:
  - fs/namei.c:lookup_one_len_unlocked
  - fs/namei.c:walk_component
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
struct dentry *lookup_slow(const struct qstr *name, struct dentry *dir, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffff800010393fd8)
Location: fs/namei.c:1674
Inline: False
Direct callers:
  - fs/namei.c:path_mountpoint
  - fs/namei.c:lookup_one_len_unlocked
  - fs/namei.c:walk_component
```
**Symbols:**

```
ffff800010393fd8-ffff800010394040: lookup_slow (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct dentry *lookup_slow(const struct qstr *name, struct dentry *dir, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (c057a94c)
Location: fs/namei.c:1674
Inline: False
Direct callers:
  - fs/namei.c:path_mountpoint
  - fs/namei.c:lookup_one_len_unlocked
  - fs/namei.c:walk_component
```
**Symbols:**

```
c057a94c-c057a9a0: lookup_slow (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct dentry *lookup_slow(const struct qstr *name, struct dentry *dir, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (c00000000048d870)
Location: fs/namei.c:1674
Inline: False
Direct callers:
  - fs/namei.c:path_mountpoint
  - fs/namei.c:lookup_one_len_unlocked
  - fs/namei.c:walk_component
```
**Symbols:**

```
c00000000048d870-c00000000048d8fc: lookup_slow (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct dentry *lookup_slow(const struct qstr *name, struct dentry *dir, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffe000262c38)
Location: fs/namei.c:1674
Inline: False
Direct callers:
  - fs/namei.c:path_mountpoint
  - fs/namei.c:lookup_one_len_unlocked
  - fs/namei.c:walk_component
```
**Symbols:**

```
ffffffe000262c38-ffffffe000262c96: lookup_slow (STB_LOCAL)
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
struct dentry *lookup_slow(const struct qstr *name, struct dentry *dir, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff812e2f20)
Location: fs/namei.c:1674
Inline: False
Direct callers:
  - fs/namei.c:path_mountpoint
  - fs/namei.c:lookup_one_len_unlocked
  - fs/namei.c:walk_component
```
**Symbols:**

```
ffffffff812e2f20-ffffffff812e2f73: lookup_slow (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct dentry *lookup_slow(const struct qstr *name, struct dentry *dir, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff812d3b60)
Location: fs/namei.c:1674
Inline: False
Direct callers:
  - fs/namei.c:path_mountpoint
  - fs/namei.c:lookup_one_len_unlocked
  - fs/namei.c:walk_component
```
**Symbols:**

```
ffffffff812d3b60-ffffffff812d3bb3: lookup_slow (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct dentry *lookup_slow(const struct qstr *name, struct dentry *dir, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff812e0d30)
Location: fs/namei.c:1674
Inline: False
Direct callers:
  - fs/namei.c:path_mountpoint
  - fs/namei.c:lookup_one_len_unlocked
  - fs/namei.c:walk_component
```
**Symbols:**

```
ffffffff812e0d30-ffffffff812e0d83: lookup_slow (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct dentry *lookup_slow(const struct qstr *name, struct dentry *dir, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff812f2580)
Location: fs/namei.c:1674
Inline: False
Direct callers:
  - fs/namei.c:path_mountpoint
  - fs/namei.c:lookup_one_len_unlocked
  - fs/namei.c:walk_component
```
**Symbols:**

```
ffffffff812f2580-ffffffff812f25d3: lookup_slow (STB_LOCAL)
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
