# Function: <code>open_detached_copy</code>

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
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct file *open_detached_copy(struct path *path, bool recursive);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff812f2b50)
Location: fs/namespace.c:2326
Inline: False
Direct callers:
  - fs/namespace.c:__ia32_sys_open_tree
  - fs/namespace.c:__x64_sys_open_tree
```
**Symbols:**

```
ffffffff812f2b50-ffffffff812f2cf0: open_detached_copy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct file *open_detached_copy(struct path *path, bool recursive);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff81304710)
Location: fs/namespace.c:2329
Inline: False
Direct callers:
  - fs/namespace.c:__ia32_sys_open_tree
  - fs/namespace.c:__x64_sys_open_tree
```
**Symbols:**

```
ffffffff81304710-ffffffff813048b0: open_detached_copy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct file *open_detached_copy(struct path *path, bool recursive);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff8133e2f0)
Location: fs/namespace.c:2387
Inline: False
Direct callers:
  - fs/namespace.c:__ia32_sys_open_tree
  - fs/namespace.c:__x64_sys_open_tree
```
**Symbols:**

```
ffffffff8133e2f0-ffffffff8133e48c: open_detached_copy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct file *open_detached_copy(struct path *path, bool recursive);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff8134a350)
Location: fs/namespace.c:2393
Inline: False
Direct callers:
  - fs/namespace.c:__ia32_sys_open_tree
  - fs/namespace.c:__x64_sys_open_tree
```
**Symbols:**

```
ffffffff8134a350-ffffffff8134a4ec: open_detached_copy (STB_LOCAL)
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
In fs/namespace.c (ffffffff81350eae)
Location: fs/namespace.c:2422
Inline: True
Inline callers:
  - fs/namespace.c:__do_sys_open_tree
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
In fs/namespace.c (ffffffff8139f26e)
Location: fs/namespace.c:2424
Inline: True
Inline callers:
  - fs/namespace.c:__do_sys_open_tree
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct file *open_detached_copy(struct path *path, bool recursive);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff81422400)
Location: fs/namespace.c:2465
Inline: False
Direct callers:
  - fs/namespace.c:__ia32_sys_open_tree
  - fs/namespace.c:__x64_sys_open_tree
```
**Symbols:**

```
ffffffff81422400-ffffffff814225a3: open_detached_copy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct file *open_detached_copy(struct path *path, bool recursive);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff814aea60)
Location: fs/namespace.c:2570
Inline: False
Direct callers:
  - fs/namespace.c:__ia32_sys_open_tree
  - fs/namespace.c:__x64_sys_open_tree
```
**Symbols:**

```
ffffffff814aea60-ffffffff814aec03: open_detached_copy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct file *open_detached_copy(struct path *path, bool recursive);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff814e39c0)
Location: fs/namespace.c:2648
Inline: False
Direct callers:
  - fs/namespace.c:__ia32_sys_open_tree
  - fs/namespace.c:__x64_sys_open_tree
```
**Symbols:**

```
ffffffff814e39c0-ffffffff814e3b63: open_detached_copy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct file *open_detached_copy(struct path *path, bool recursive);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff81517710)
Location: fs/namespace.c:2654
Inline: False
Direct callers:
  - fs/namespace.c:__ia32_sys_open_tree
  - fs/namespace.c:__x64_sys_open_tree
```
**Symbols:**

```
ffffffff81517710-ffffffff81517898: open_detached_copy (STB_LOCAL)
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
In fs/namespace.c (ffff8000103b8250)
Location: fs/namespace.c:2329
Inline: True
Inline callers:
  - fs/namespace.c:__arm64_sys_open_tree
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
In fs/namespace.c (c0596d54)
Location: fs/namespace.c:2329
Inline: True
Inline callers:
  - fs/namespace.c:__se_sys_open_tree
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
In fs/namespace.c (c0000000004b50e0)
Location: fs/namespace.c:2329
Inline: True
Inline callers:
  - fs/namespace.c:__se_sys_open_tree
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
In fs/namespace.c (ffffffe00027b68a)
Location: fs/namespace.c:2329
Inline: True
Inline callers:
  - fs/namespace.c:__se_sys_open_tree
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
struct file *open_detached_copy(struct path *path, bool recursive);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff812fccf0)
Location: fs/namespace.c:2329
Inline: False
Direct callers:
  - fs/namespace.c:__ia32_sys_open_tree
  - fs/namespace.c:__x64_sys_open_tree
```
**Symbols:**

```
ffffffff812fccf0-ffffffff812fce90: open_detached_copy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct file *open_detached_copy(struct path *path, bool recursive);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff812ed910)
Location: fs/namespace.c:2329
Inline: False
Direct callers:
  - fs/namespace.c:__ia32_sys_open_tree
  - fs/namespace.c:__x64_sys_open_tree
```
**Symbols:**

```
ffffffff812ed910-ffffffff812edab0: open_detached_copy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct file *open_detached_copy(struct path *path, bool recursive);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff812faae0)
Location: fs/namespace.c:2329
Inline: False
Direct callers:
  - fs/namespace.c:__ia32_sys_open_tree
  - fs/namespace.c:__x64_sys_open_tree
```
**Symbols:**

```
ffffffff812faae0-ffffffff812fac80: open_detached_copy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct file *open_detached_copy(struct path *path, bool recursive);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff8130be20)
Location: fs/namespace.c:2329
Inline: False
Direct callers:
  - fs/namespace.c:__ia32_sys_open_tree
  - fs/namespace.c:__x64_sys_open_tree
```
**Symbols:**

```
ffffffff8130be20-ffffffff8130bfbe: open_detached_copy (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
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
<b>Arch</b>
<ul>
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
