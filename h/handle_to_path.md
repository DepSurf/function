# Function: <code>handle_to_path</code>

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
In fs/fhandle.c (ffffffff81270235)
Location: fs/fhandle.c:166
Inline: True
Inline callers:
  - fs/fhandle.c:do_handle_open
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/fhandle.c (ffffffff8129ba68)
Location: fs/fhandle.c:166
Inline: True
Inline callers:
  - fs/fhandle.c:do_handle_open
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/fhandle.c (ffffffff812b0628)
Location: fs/fhandle.c:166
Inline: True
Inline callers:
  - fs/fhandle.c:do_handle_open
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/fhandle.c (ffffffff812bdabf)
Location: fs/fhandle.c:167
Inline: True
Inline callers:
  - fs/fhandle.c:do_handle_open
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/fhandle.c (ffffffff812e11af)
Location: fs/fhandle.c:168
Inline: True
Inline callers:
  - fs/fhandle.c:do_handle_open
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/fhandle.c (ffffffff8130d3d3)
Location: fs/fhandle.c:167
Inline: True
Inline callers:
  - fs/fhandle.c:do_handle_open
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/fhandle.c (ffffffff81322fc3)
Location: fs/fhandle.c:167
Inline: True
Inline callers:
  - fs/fhandle.c:do_handle_open
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/fhandle.c (ffffffff8134a9d3)
Location: fs/fhandle.c:167
Inline: True
Inline callers:
  - fs/fhandle.c:do_handle_open
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/fhandle.c (ffffffff81362bd3)
Location: fs/fhandle.c:167
Inline: True
Inline callers:
  - fs/fhandle.c:do_handle_open
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int handle_to_path(int mountdirfd, struct file_handle *ufh, struct path *path);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fhandle.c (ffffffff813a8720)
Location: fs/fhandle.c:167
Inline: False
Direct callers:
  - fs/fhandle.c:do_handle_open
```
**Symbols:**

```
ffffffff813a8720-ffffffff813a8935: handle_to_path (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int handle_to_path(int mountdirfd, struct file_handle *ufh, struct path *path);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fhandle.c (ffffffff813b9a70)
Location: fs/fhandle.c:167
Inline: False
Direct callers:
  - fs/fhandle.c:do_handle_open
```
**Symbols:**

```
ffffffff813b9a70-ffffffff813b9c85: handle_to_path (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int handle_to_path(int mountdirfd, struct file_handle *ufh, struct path *path);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fhandle.c (ffffffff813c0bd0)
Location: fs/fhandle.c:167
Inline: False
Direct callers:
  - fs/fhandle.c:do_handle_open
```
**Symbols:**

```
ffffffff813c0bd0-ffffffff813c0de2: handle_to_path (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int handle_to_path(int mountdirfd, struct file_handle *ufh, struct path *path);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fhandle.c (ffffffff81410c90)
Location: fs/fhandle.c:167
Inline: False
Direct callers:
  - fs/fhandle.c:do_handle_open
```
**Symbols:**

```
ffffffff81410c90-ffffffff81410ea2: handle_to_path (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int handle_to_path(int mountdirfd, struct file_handle *ufh, struct path *path);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fhandle.c (ffffffff81486640)
Location: fs/fhandle.c:167
Inline: False
Direct callers:
  - fs/fhandle.c:do_handle_open
```
**Symbols:**

```
ffffffff81486640-ffffffff81486861: handle_to_path (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int handle_to_path(int mountdirfd, struct file_handle *ufh, struct path *path);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fhandle.c (ffffffff81519f90)
Location: fs/fhandle.c:167
Inline: False
Direct callers:
  - fs/fhandle.c:do_handle_open
```
**Symbols:**

```
ffffffff81519f90-ffffffff8151a1b1: handle_to_path (STB_LOCAL)
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
In fs/fhandle.c (ffffffff81551913)
Location: fs/fhandle.c:174
Inline: True
Inline callers:
  - fs/fhandle.c:do_handle_open
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int handle_to_path(int mountdirfd, struct file_handle *ufh, struct path *path);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fhandle.c (ffffffff81587810)
Location: fs/fhandle.c:170
Inline: False
Direct callers:
  - fs/fhandle.c:do_handle_open
```
**Symbols:**

```
ffffffff81587810-ffffffff81587a41: handle_to_path (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/fhandle.c (ffff800010429444)
Location: fs/fhandle.c:167
Inline: True
Inline callers:
  - fs/fhandle.c:do_handle_open
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/fhandle.c (c05f2148)
Location: fs/fhandle.c:167
Inline: True
Inline callers:
  - fs/fhandle.c:__se_sys_open_by_handle_at
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/fhandle.c (c000000000539924)
Location: fs/fhandle.c:167
Inline: True
Inline callers:
  - fs/fhandle.c:do_handle_open
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/fhandle.c (ffffffe0002c744a)
Location: fs/fhandle.c:167
Inline: True
Inline callers:
  - fs/fhandle.c:__se_sys_open_by_handle_at
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/fhandle.c (ffffffff8135b1b3)
Location: fs/fhandle.c:167
Inline: True
Inline callers:
  - fs/fhandle.c:do_handle_open
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/fhandle.c (ffffffff8134be53)
Location: fs/fhandle.c:167
Inline: True
Inline callers:
  - fs/fhandle.c:do_handle_open
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/fhandle.c (ffffffff81358c83)
Location: fs/fhandle.c:167
Inline: True
Inline callers:
  - fs/fhandle.c:do_handle_open
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/fhandle.c (ffffffff8136c383)
Location: fs/fhandle.c:167
Inline: True
Inline callers:
  - fs/fhandle.c:do_handle_open
```
</details>
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
</ul>
