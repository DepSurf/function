# Function: <code>__free_fdtable</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void __free_fdtable(struct fdtable *fdt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/file.c (ffffffff81229cf0)
Location: fs/file.c:47
Inline: False
Direct callers:
  - fs/file.c:free_fdtable_rcu
  - fs/file.c:expand_files
  - fs/file.c:dup_fd
  - fs/file.c:dup_fd
```
**Symbols:**

```
ffffffff81229cf0-ffffffff81229d1a: __free_fdtable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void __free_fdtable(struct fdtable *fdt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/file.c (ffffffff81252450)
Location: fs/file.c:48
Inline: False
Direct callers:
  - fs/file.c:dup_fd
  - fs/file.c:dup_fd
  - fs/file.c:expand_files
  - fs/file.c:free_fdtable_rcu
```
**Symbols:**

```
ffffffff81252450-ffffffff8125247a: __free_fdtable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void __free_fdtable(struct fdtable *fdt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/file.c (ffffffff812656c0)
Location: fs/file.c:48
Inline: False
Direct callers:
  - fs/file.c:dup_fd
  - fs/file.c:dup_fd
  - fs/file.c:expand_files
  - fs/file.c:free_fdtable_rcu
```
**Symbols:**

```
ffffffff812656c0-ffffffff812656ea: __free_fdtable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void __free_fdtable(struct fdtable *fdt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/file.c (ffffffff81272e40)
Location: fs/file.c:33
Inline: False
Direct callers:
  - fs/file.c:dup_fd
  - fs/file.c:dup_fd
  - fs/file.c:expand_files
  - fs/file.c:free_fdtable_rcu
```
**Symbols:**

```
ffffffff81272e40-ffffffff81272e6a: __free_fdtable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void __free_fdtable(struct fdtable *fdt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/file.c (ffffffff81295770)
Location: fs/file.c:34
Inline: False
Direct callers:
  - fs/file.c:dup_fd
  - fs/file.c:dup_fd
  - fs/file.c:expand_files
  - fs/file.c:free_fdtable_rcu
```
**Symbols:**

```
ffffffff81295770-ffffffff8129579a: __free_fdtable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void __free_fdtable(struct fdtable *fdt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/file.c (ffffffff812bb8f0)
Location: fs/file.c:29
Inline: False
Direct callers:
  - fs/file.c:dup_fd
  - fs/file.c:dup_fd
  - fs/file.c:free_fdtable_rcu
```
**Symbols:**

```
ffffffff812bb8f0-ffffffff812bb91a: __free_fdtable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void __free_fdtable(struct fdtable *fdt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/file.c (ffffffff812d0ae0)
Location: fs/file.c:29
Inline: False
Direct callers:
  - fs/file.c:dup_fd
  - fs/file.c:dup_fd
  - fs/file.c:free_fdtable_rcu
```
**Symbols:**

```
ffffffff812d0ae0-ffffffff812d0b0a: __free_fdtable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void __free_fdtable(struct fdtable *fdt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/file.c (ffffffff812edb10)
Location: fs/file.c:29
Inline: False
Direct callers:
  - fs/file.c:dup_fd
  - fs/file.c:dup_fd
  - fs/file.c:expand_files
  - fs/file.c:free_fdtable_rcu
```
**Symbols:**

```
ffffffff812edb10-ffffffff812edb3d: __free_fdtable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void __free_fdtable(struct fdtable *fdt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/file.c (ffffffff812ff5d0)
Location: fs/file.c:29
Inline: False
Direct callers:
  - fs/file.c:dup_fd
  - fs/file.c:dup_fd
  - fs/file.c:expand_files
  - fs/file.c:free_fdtable_rcu
```
**Symbols:**

```
ffffffff812ff5d0-ffffffff812ff5fd: __free_fdtable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/file.c (ffffffff813392cd)
Location: fs/file.c:29
Inline: True
Inline callers:
  - fs/file.c:dup_fd
  - fs/file.c:dup_fd
  - fs/file.c:expand_fdtable
  - fs/file.c:free_fdtable_rcu
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/file.c (ffffffff81344f61)
Location: fs/file.c:34
Inline: True
Inline callers:
  - fs/file.c:dup_fd
  - fs/file.c:dup_fd
  - fs/file.c:expand_fdtable
  - fs/file.c:free_fdtable_rcu
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
In fs/file.c (ffffffff8134b2ef)
Location: fs/file.c:34
Inline: True
Inline callers:
  - fs/file.c:dup_fd
  - fs/file.c:dup_fd
  - fs/file.c:expand_files
  - fs/file.c:free_fdtable_rcu
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
In fs/file.c (ffffffff8139914f)
Location: fs/file.c:34
Inline: True
Inline callers:
  - fs/file.c:dup_fd
  - fs/file.c:dup_fd
  - fs/file.c:expand_files
  - fs/file.c:free_fdtable_rcu
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
In fs/file.c (ffffffff8141ba7f)
Location: fs/file.c:34
Inline: True
Inline callers:
  - fs/file.c:dup_fd
  - fs/file.c:dup_fd
  - fs/file.c:expand_files
  - fs/file.c:free_fdtable_rcu
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
In fs/file.c (ffffffff814a7bbf)
Location: fs/file.c:34
Inline: True
Inline callers:
  - fs/file.c:dup_fd
  - fs/file.c:dup_fd
  - fs/file.c:expand_files
  - fs/file.c:free_fdtable_rcu
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
In fs/file.c (ffffffff814dcb9f)
Location: fs/file.c:34
Inline: True
Inline callers:
  - fs/file.c:dup_fd
  - fs/file.c:dup_fd
  - fs/file.c:expand_files
  - fs/file.c:free_fdtable_rcu
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
In fs/file.c (ffffffff8150f35f)
Location: fs/file.c:34
Inline: True
Inline callers:
  - fs/file.c:dup_fd
  - fs/file.c:dup_fd
  - fs/file.c:expand_files
  - fs/file.c:free_fdtable_rcu
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
void __free_fdtable(struct fdtable *fdt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/file.c (ffff8000103b0a88)
Location: fs/file.c:29
Inline: False
Direct callers:
  - fs/file.c:dup_fd
  - fs/file.c:dup_fd
  - fs/file.c:expand_files
  - fs/file.c:free_fdtable_rcu
```
**Symbols:**

```
ffff8000103b0a88-ffff8000103b0ac4: __free_fdtable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void __free_fdtable(struct fdtable *fdt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/file.c (c0590388)
Location: fs/file.c:29
Inline: False
Direct callers:
  - fs/file.c:dup_fd
  - fs/file.c:dup_fd
  - fs/file.c:expand_files
  - fs/file.c:free_fdtable_rcu
```
**Symbols:**

```
c0590388-c05903bc: __free_fdtable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void __free_fdtable(struct fdtable *fdt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/file.c (c0000000004ac480)
Location: fs/file.c:29
Inline: False
Direct callers:
  - fs/file.c:dup_fd
  - fs/file.c:dup_fd
  - fs/file.c:expand_files
  - fs/file.c:free_fdtable_rcu
```
**Symbols:**

```
c0000000004ac480-c0000000004ac4dc: __free_fdtable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void __free_fdtable(struct fdtable *fdt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/file.c (ffffffe000274eae)
Location: fs/file.c:29
Inline: False
Direct callers:
  - fs/file.c:dup_fd
  - fs/file.c:dup_fd
  - fs/file.c:expand_files
  - fs/file.c:free_fdtable_rcu
```
**Symbols:**

```
ffffffe000274eae-ffffffe000274eec: __free_fdtable (STB_LOCAL)
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
void __free_fdtable(struct fdtable *fdt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/file.c (ffffffff812f7bb0)
Location: fs/file.c:29
Inline: False
Direct callers:
  - fs/file.c:dup_fd
  - fs/file.c:dup_fd
  - fs/file.c:expand_files
  - fs/file.c:free_fdtable_rcu
```
**Symbols:**

```
ffffffff812f7bb0-ffffffff812f7bdd: __free_fdtable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void __free_fdtable(struct fdtable *fdt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/file.c (ffffffff812e87d0)
Location: fs/file.c:29
Inline: False
Direct callers:
  - fs/file.c:dup_fd
  - fs/file.c:dup_fd
  - fs/file.c:expand_files
  - fs/file.c:free_fdtable_rcu
```
**Symbols:**

```
ffffffff812e87d0-ffffffff812e87fd: __free_fdtable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void __free_fdtable(struct fdtable *fdt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/file.c (ffffffff812f59c0)
Location: fs/file.c:29
Inline: False
Direct callers:
  - fs/file.c:dup_fd
  - fs/file.c:dup_fd
  - fs/file.c:expand_files
  - fs/file.c:free_fdtable_rcu
```
**Symbols:**

```
ffffffff812f59c0-ffffffff812f59ed: __free_fdtable (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void __free_fdtable(struct fdtable *fdt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/file.c (ffffffff81306b00)
Location: fs/file.c:29
Inline: False
Direct callers:
  - fs/file.c:dup_fd
  - fs/file.c:dup_fd
  - fs/file.c:expand_files
  - fs/file.c:free_fdtable_rcu
```
**Symbols:**

```
ffffffff81306b00-ffffffff81306b2d: __free_fdtable (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
</li>
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
