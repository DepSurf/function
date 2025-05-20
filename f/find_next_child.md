# Function: <code>find_next_child</code>

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
struct dentry *find_next_child(struct dentry *parent, struct dentry *prev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/libfs.c (ffffffff81345e60)
Location: fs/libfs.c:243
Inline: False
Direct callers:
  - fs/libfs.c:simple_recursive_removal
```
**Symbols:**

```
ffffffff81345e60-ffffffff81345f1b: find_next_child (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct dentry *find_next_child(struct dentry *parent, struct dentry *prev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/libfs.c (ffffffff81352320)
Location: fs/libfs.c:245
Inline: False
Direct callers:
  - fs/libfs.c:simple_recursive_removal
```
**Symbols:**

```
ffffffff81352320-ffffffff813523e3: find_next_child (STB_LOCAL)
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
In fs/libfs.c (ffffffff81358edf)
Location: fs/libfs.c:246
Inline: True
Inline callers:
  - fs/libfs.c:simple_recursive_removal
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
In fs/libfs.c (ffffffff813a776b)
Location: fs/libfs.c:246
Inline: True
Inline callers:
  - fs/libfs.c:simple_recursive_removal
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
In fs/libfs.c (ffffffff8142c207)
Location: fs/libfs.c:246
Inline: True
Inline callers:
  - fs/libfs.c:simple_recursive_removal
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
In fs/libfs.c (ffffffff814b9917)
Location: fs/libfs.c:247
Inline: True
Inline callers:
  - fs/libfs.c:simple_recursive_removal
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
In fs/libfs.c (ffffffff814ee90b)
Location: fs/libfs.c:242
Inline: True
Inline callers:
  - fs/libfs.c:simple_recursive_removal
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
In fs/libfs.c (ffffffff815228c8)
Location: fs/libfs.c:499
Inline: True
Inline callers:
  - fs/libfs.c:simple_recursive_removal
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
</ul>
