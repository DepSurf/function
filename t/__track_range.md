# Function: <code>__track_range</code>

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
int __track_range(struct inode *inode, void *arg, bool update);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/fast_commit.c (ffffffff81453e20)
Location: fs/ext4/fast_commit.c:568
Inline: False
```
**Symbols:**

```
ffffffff81453e20-ffffffff81453e9c: __track_range (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int __track_range(struct inode *inode, void *arg, bool update);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/fast_commit.c (ffffffff81459750)
Location: fs/ext4/fast_commit.c:568
Inline: False
```
**Symbols:**

```
ffffffff81459750-ffffffff814597cf: __track_range (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int __track_range(struct inode *inode, void *arg, bool update);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/fast_commit.c (ffffffff814ad850)
Location: fs/ext4/fast_commit.c:536
Inline: False
```
**Symbols:**

```
ffffffff814ad850-ffffffff814ad8bd: __track_range (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int __track_range(struct inode *inode, void *arg, bool update);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/fast_commit.c (ffffffff815359a0)
Location: fs/ext4/fast_commit.c:607
Inline: False
Direct callers:
  - fs/ext4/fast_commit.c:ext4_fc_track_range
```
**Symbols:**

```
ffffffff815359a0-ffffffff81535a31: __track_range (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int __track_range(struct inode *inode, void *arg, bool update);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/fast_commit.c (ffffffff815d3e20)
Location: fs/ext4/fast_commit.c:610
Inline: False
Direct callers:
  - fs/ext4/fast_commit.c:ext4_fc_track_range
```
**Symbols:**

```
ffffffff815d3e20-ffffffff815d3eb1: __track_range (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int __track_range(struct inode *inode, void *arg, bool update);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/fast_commit.c (ffffffff8160ba10)
Location: fs/ext4/fast_commit.c:610
Inline: False
Direct callers:
  - fs/ext4/fast_commit.c:ext4_fc_track_range
```
**Symbols:**

```
ffffffff8160ba10-ffffffff8160ba95: __track_range (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int __track_range(struct inode *inode, void *arg, bool update);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/fast_commit.c (ffffffff816447d0)
Location: fs/ext4/fast_commit.c:610
Inline: False
Direct callers:
  - fs/ext4/fast_commit.c:ext4_fc_track_range
```
**Symbols:**

```
ffffffff816447d0-ffffffff81644855: __track_range (STB_LOCAL)
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
