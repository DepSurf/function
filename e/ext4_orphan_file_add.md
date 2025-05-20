# Function: <code>ext4_orphan_file_add</code>

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
int ext4_orphan_file_add(handle_t *handle, struct inode *inode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/orphan.c (ffffffff814b1030)
Location: fs/ext4/orphan.c:11
Inline: False
Direct callers:
  - fs/ext4/orphan.c:ext4_orphan_add
```
**Symbols:**

```
ffffffff814b1030-ffffffff814b1202: ext4_orphan_file_add (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int ext4_orphan_file_add(handle_t *handle, struct inode *inode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/orphan.c (ffffffff81539ae0)
Location: fs/ext4/orphan.c:11
Inline: False
Direct callers:
  - fs/ext4/orphan.c:ext4_orphan_add
```
**Symbols:**

```
ffffffff81539ae0-ffffffff81539cff: ext4_orphan_file_add (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int ext4_orphan_file_add(handle_t *handle, struct inode *inode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/orphan.c (ffffffff815d8010)
Location: fs/ext4/orphan.c:11
Inline: False
Direct callers:
  - fs/ext4/orphan.c:ext4_orphan_add
```
**Symbols:**

```
ffffffff815d8010-ffffffff815d822f: ext4_orphan_file_add (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int ext4_orphan_file_add(handle_t *handle, struct inode *inode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/orphan.c (ffffffff8160fba0)
Location: fs/ext4/orphan.c:11
Inline: False
Direct callers:
  - fs/ext4/orphan.c:ext4_orphan_add
```
**Symbols:**

```
ffffffff8160fba0-ffffffff8160fdbf: ext4_orphan_file_add (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int ext4_orphan_file_add(handle_t *handle, struct inode *inode);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/ext4/orphan.c (ffffffff81648960)
Location: fs/ext4/orphan.c:11
Inline: False
Direct callers:
  - fs/ext4/orphan.c:ext4_orphan_add
```
**Symbols:**

```
ffffffff81648960-ffffffff81648b7f: ext4_orphan_file_add (STB_LOCAL)
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
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
