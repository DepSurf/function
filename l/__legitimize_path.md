# Function: <code>__legitimize_path</code>

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
bool __legitimize_path(struct path *path, unsigned int seq, unsigned int mseq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff81320ea0)
Location: fs/namei.c:608
Inline: False
Direct callers:
  - fs/namei.c:pick_link
  - fs/namei.c:choose_mountpoint
  - fs/namei.c:unlazy_walk
  - fs/namei.c:legitimize_root
  - fs/namei.c:legitimize_links
```
**Symbols:**

```
ffffffff81320ea0-ffffffff81320efb: __legitimize_path (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
bool __legitimize_path(struct path *path, unsigned int seq, unsigned int mseq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff8132c430)
Location: fs/namei.c:608
Inline: False
Direct callers:
  - fs/namei.c:pick_link
  - fs/namei.c:choose_mountpoint
  - fs/namei.c:try_to_unlazy
  - fs/namei.c:legitimize_root
  - fs/namei.c:legitimize_links
```
**Symbols:**

```
ffffffff8132c430-ffffffff8132c48b: __legitimize_path (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
bool __legitimize_path(struct path *path, unsigned int seq, unsigned int mseq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff81332470)
Location: fs/namei.c:662
Inline: False
Direct callers:
  - fs/namei.c:pick_link
  - fs/namei.c:try_to_unlazy
  - fs/namei.c:legitimize_root
```
**Symbols:**

```
ffffffff81332470-ffffffff813324cb: __legitimize_path (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
bool __legitimize_path(struct path *path, unsigned int seq, unsigned int mseq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff8137fc00)
Location: fs/namei.c:689
Inline: False
Direct callers:
  - fs/namei.c:pick_link
  - fs/namei.c:try_to_unlazy
  - fs/namei.c:legitimize_root
```
**Symbols:**

```
ffffffff8137fc00-ffffffff8137fc5b: __legitimize_path (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
bool __legitimize_path(struct path *path, unsigned int seq, unsigned int mseq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff813ffe50)
Location: fs/namei.c:690
Inline: False
Direct callers:
  - fs/namei.c:handle_dots
  - fs/namei.c:pick_link
  - fs/namei.c:try_to_unlazy_next
  - fs/namei.c:try_to_unlazy
  - fs/namei.c:try_to_unlazy
  - fs/namei.c:legitimize_links
```
**Symbols:**

```
ffffffff813ffe50-ffffffff813ffebf: __legitimize_path (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
bool __legitimize_path(struct path *path, unsigned int seq, unsigned int mseq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff81489e70)
Location: fs/namei.c:696
Inline: False
Direct callers:
  - fs/namei.c:handle_dots
  - fs/namei.c:pick_link
  - fs/namei.c:try_to_unlazy_next
  - fs/namei.c:try_to_unlazy
  - fs/namei.c:try_to_unlazy
  - fs/namei.c:legitimize_links
```
**Symbols:**

```
ffffffff81489e70-ffffffff81489edf: __legitimize_path (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
bool __legitimize_path(struct path *path, unsigned int seq, unsigned int mseq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff814bee60)
Location: fs/namei.c:699
Inline: False
Direct callers:
  - fs/namei.c:handle_dots
  - fs/namei.c:pick_link
  - fs/namei.c:try_to_unlazy_next
  - fs/namei.c:try_to_unlazy
  - fs/namei.c:try_to_unlazy
  - fs/namei.c:legitimize_links
```
**Symbols:**

```
ffffffff814bee60-ffffffff814beecf: __legitimize_path (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
bool __legitimize_path(struct path *path, unsigned int seq, unsigned int mseq);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff814f12e0)
Location: fs/namei.c:702
Inline: False
Direct callers:
  - fs/namei.c:handle_dots
  - fs/namei.c:pick_link
  - fs/namei.c:try_to_unlazy_next
  - fs/namei.c:try_to_unlazy
  - fs/namei.c:try_to_unlazy
  - fs/namei.c:legitimize_links
```
**Symbols:**

```
ffffffff814f12e0-ffffffff814f134f: __legitimize_path (STB_LOCAL)
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
