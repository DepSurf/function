# Function: <code>kernfs_unlink_open_file</code>

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
In <code>5.15</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void kernfs_unlink_open_file(struct kernfs_node *kn, struct kernfs_open_file *of);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/file.c (ffffffff814b5380)
Location: fs/kernfs/file.c:567
Inline: False
Direct callers:
  - fs/kernfs/file.c:kernfs_fop_release
  - fs/kernfs/file.c:kernfs_fop_open
```
**Symbols:**

```
ffffffff814b5380-ffffffff814b542c: kernfs_unlink_open_file (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void kernfs_unlink_open_file(struct kernfs_node *kn, struct kernfs_open_file *of, bool open_failed);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/file.c (ffffffff8154c420)
Location: fs/kernfs/file.c:605
Inline: False
Direct callers:
  - fs/kernfs/file.c:kernfs_fop_release
  - fs/kernfs/file.c:kernfs_fop_open
```
**Symbols:**

```
ffffffff8154c420-ffffffff8154c506: kernfs_unlink_open_file (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void kernfs_unlink_open_file(struct kernfs_node *kn, struct kernfs_open_file *of, bool open_failed);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/file.c (ffffffff815840e0)
Location: fs/kernfs/file.c:605
Inline: False
Direct callers:
  - fs/kernfs/file.c:kernfs_fop_release
  - fs/kernfs/file.c:kernfs_fop_open
```
**Symbols:**

```
ffffffff815840e0-ffffffff815841c7: kernfs_unlink_open_file (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void kernfs_unlink_open_file(struct kernfs_node *kn, struct kernfs_open_file *of, bool open_failed);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/file.c (ffffffff815bcbc0)
Location: fs/kernfs/file.c:556
Inline: False
Direct callers:
  - fs/kernfs/file.c:kernfs_fop_release
  - fs/kernfs/file.c:kernfs_fop_open
```
**Symbols:**

```
ffffffff815bcbc0-ffffffff815bcca7: kernfs_unlink_open_file (STB_LOCAL)
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
<details>
<summary>Changed between <code>5.19</code> and <code>6.2</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>bool open_failed</code>
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
