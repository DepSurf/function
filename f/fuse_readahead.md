# Function: <code>fuse_readahead</code>

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
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void fuse_readahead(struct readahead_control *rac);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (ffffffff81477e10)
Location: fs/fuse/file.c:935
Inline: False
```
**Symbols:**

```
ffffffff81477e10-ffffffff81477f33: fuse_readahead (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void fuse_readahead(struct readahead_control *rac);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (ffffffff81492ae0)
Location: fs/fuse/file.c:958
Inline: False
```
**Symbols:**

```
ffffffff81492ae0-ffffffff81492c01: fuse_readahead (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void fuse_readahead(struct readahead_control *rac);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (ffffffff81497540)
Location: fs/fuse/file.c:953
Inline: False
```
**Symbols:**

```
ffffffff81497540-ffffffff814977c3: fuse_readahead (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void fuse_readahead(struct readahead_control *rac);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (ffffffff814eeec0)
Location: fs/fuse/file.c:957
Inline: False
```
**Symbols:**

```
ffffffff814eeec0-ffffffff814ef3d5: fuse_readahead (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void fuse_readahead(struct readahead_control *rac);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (ffffffff8157ebf0)
Location: fs/fuse/file.c:967
Inline: False
```
**Symbols:**

```
ffffffff8157ebf0-ffffffff8157f14c: fuse_readahead (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void fuse_readahead(struct readahead_control *rac);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (ffffffff816248b0)
Location: fs/fuse/file.c:967
Inline: False
```
**Symbols:**

```
ffffffff816248b0-ffffffff81624e0d: fuse_readahead (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void fuse_readahead(struct readahead_control *rac);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (ffffffff8165cc90)
Location: fs/fuse/file.c:968
Inline: False
```
**Symbols:**

```
ffffffff8165cc90-ffffffff8165d18d: fuse_readahead (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void fuse_readahead(struct readahead_control *rac);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fuse/file.c (ffffffff816969f0)
Location: fs/fuse/file.c:969
Inline: False
```
**Symbols:**

```
ffffffff816969f0-ffffffff81696eea: fuse_readahead (STB_LOCAL)
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
