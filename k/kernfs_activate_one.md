# Function: <code>kernfs_activate_one</code>

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
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void kernfs_activate_one(struct kernfs_node *kn);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/kernfs/dir.c (ffffffff8154a360)
Location: fs/kernfs/dir.c:1341
Inline: True
Direct callers:
  - fs/kernfs/dir.c:kernfs_show
  - fs/kernfs/dir.c:kernfs_activate
```
**Symbols:**

```
ffffffff8154a360-ffffffff8154a3bd: kernfs_activate_one (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void kernfs_activate_one(struct kernfs_node *kn);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/kernfs/dir.c (ffffffff81581f90)
Location: fs/kernfs/dir.c:1345
Inline: True
Direct callers:
  - fs/kernfs/dir.c:kernfs_show
  - fs/kernfs/dir.c:kernfs_activate
```
**Symbols:**

```
ffffffff81581f90-ffffffff81581fed: kernfs_activate_one (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void kernfs_activate_one(struct kernfs_node *kn);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/kernfs/dir.c (ffffffff815baa70)
Location: fs/kernfs/dir.c:1361
Inline: True
Direct callers:
  - fs/kernfs/dir.c:kernfs_show
  - fs/kernfs/dir.c:kernfs_activate
```
**Symbols:**

```
ffffffff815baa70-ffffffff815baacd: kernfs_activate_one (STB_LOCAL)
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
