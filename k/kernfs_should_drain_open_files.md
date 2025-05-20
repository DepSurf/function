# Function: <code>kernfs_should_drain_open_files</code>

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
In <code>5.19</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
bool kernfs_should_drain_open_files(struct kernfs_node *kn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/file.c (ffffffff8154d890)
Location: fs/kernfs/file.c:813
Inline: False
Direct callers:
  - fs/kernfs/dir.c:kernfs_drain
  - fs/kernfs/dir.c:kernfs_drain
  - fs/kernfs/dir.c:kernfs_drain
```
**Symbols:**

```
ffffffff8154d890-ffffffff8154d8d6: kernfs_should_drain_open_files (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
bool kernfs_should_drain_open_files(struct kernfs_node *kn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/file.c (ffffffff81585530)
Location: fs/kernfs/file.c:813
Inline: False
Direct callers:
  - fs/kernfs/dir.c:kernfs_drain
  - fs/kernfs/dir.c:kernfs_drain
  - fs/kernfs/dir.c:kernfs_drain
```
**Symbols:**

```
ffffffff81585530-ffffffff81585576: kernfs_should_drain_open_files (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
bool kernfs_should_drain_open_files(struct kernfs_node *kn);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/kernfs/file.c (ffffffff815bdfe0)
Location: fs/kernfs/file.c:764
Inline: False
Direct callers:
  - fs/kernfs/dir.c:kernfs_drain
  - fs/kernfs/dir.c:kernfs_drain
  - fs/kernfs/dir.c:kernfs_drain
```
**Symbols:**

```
ffffffff815bdfe0-ffffffff815be026: kernfs_should_drain_open_files (STB_GLOBAL)
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
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
