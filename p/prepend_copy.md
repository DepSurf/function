# Function: <code>prepend_copy</code>

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
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
bool prepend_copy(void *dst, const void *src, int len);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/d_path.c (ffffffff813b6d88)
Location: fs/d_path.c:47
Inline: True
Inline callers:
  - fs/d_path.c:simple_dname
Direct callers:
  - fs/d_path.c:__dentry_path
  - fs/d_path.c:__dentry_path
  - fs/d_path.c:simple_dname
```
**Symbols:**

```
ffffffff813b6190-ffffffff813b61d6: prepend_copy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
bool prepend_copy(void *dst, const void *src, int len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/d_path.c (ffffffff8143b730)
Location: fs/d_path.c:47
Inline: False
Direct callers:
  - fs/d_path.c:__dentry_path
  - fs/d_path.c:__dentry_path
  - fs/d_path.c:simple_dname
  - fs/d_path.c:simple_dname
```
**Symbols:**

```
ffffffff8143b730-ffffffff8143b787: prepend_copy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
bool prepend_copy(void *dst, const void *src, int len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/d_path.c (ffffffff814c9d20)
Location: fs/d_path.c:47
Inline: False
Direct callers:
  - fs/d_path.c:__dentry_path
  - fs/d_path.c:__dentry_path
  - fs/d_path.c:simple_dname
  - fs/d_path.c:simple_dname
```
**Symbols:**

```
ffffffff814c9d20-ffffffff814c9d77: prepend_copy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
bool prepend_copy(void *dst, const void *src, int len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/d_path.c (ffffffff814fff60)
Location: fs/d_path.c:48
Inline: False
Direct callers:
  - fs/d_path.c:__dentry_path
  - fs/d_path.c:__dentry_path
  - fs/d_path.c:simple_dname
  - fs/d_path.c:simple_dname
```
**Symbols:**

```
ffffffff814fff60-ffffffff814fffb7: prepend_copy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
bool prepend_copy(void *dst, const void *src, int len);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/d_path.c (ffffffff81534b80)
Location: fs/d_path.c:48
Inline: False
Direct callers:
  - fs/d_path.c:__dentry_path
  - fs/d_path.c:__dentry_path
  - fs/d_path.c:simple_dname
  - fs/d_path.c:simple_dname
```
**Symbols:**

```
ffffffff81534b80-ffffffff81534bd7: prepend_copy (STB_LOCAL)
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
