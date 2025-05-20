# Function: <code>do_last</code>

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
In fs/namei.c (ffffffff8121a9d9)
Location: fs/namei.c:3021
Inline: True
Inline callers:
  - fs/namei.c:path_openat
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
In fs/namei.c (ffffffff81241d89)
Location: fs/namei.c:3211
Inline: True
Inline callers:
  - fs/namei.c:path_openat
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
In fs/namei.c (ffffffff81254c6a)
Location: fs/namei.c:3175
Inline: True
Inline callers:
  - fs/namei.c:path_openat
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
In fs/namei.c (ffffffff81260cbf)
Location: fs/namei.c:3223
Inline: True
Inline callers:
  - fs/namei.c:path_openat
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
In fs/namei.c (ffffffff812833c4)
Location: fs/namei.c:3221
Inline: True
Inline callers:
  - fs/namei.c:path_openat
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
In fs/namei.c (ffffffff812aa57f)
Location: fs/namei.c:3243
Inline: True
Inline callers:
  - fs/namei.c:path_openat
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
In fs/namei.c (ffffffff812bf70b)
Location: fs/namei.c:3257
Inline: True
Inline callers:
  - fs/namei.c:path_openat
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int do_last(struct nameidata *nd, struct file *file, const struct open_flags *op);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In fs/namei.c (0)
Location: fs/namei.c:3255
Inline: False
Direct callers:
  - fs/namei.c:path_openat
```
**Symbols:**

```
ffffffff812dc940-ffffffff812dd269: do_last (STB_LOCAL)
ffffffff812dfd34-ffffffff812dfd4c: do_last.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int do_last(struct nameidata *nd, struct file *file, const struct open_flags *op);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff812ee480)
Location: fs/namei.c:3248
Inline: False
Direct callers:
  - fs/namei.c:path_openat
```
**Symbols:**

```
ffffffff812ee480-ffffffff812eed7d: do_last (STB_LOCAL)
```
</details>
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
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
int do_last(struct nameidata *nd, struct file *file, const struct open_flags *op);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffff800010397c60)
Location: fs/namei.c:3248
Inline: False
Direct callers:
  - fs/namei.c:path_openat
```
**Symbols:**

```
ffff800010397c60-ffff80001039853c: do_last (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int do_last(struct nameidata *nd, struct file *file, const struct open_flags *op);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (c057e22c)
Location: fs/namei.c:3248
Inline: False
Direct callers:
  - fs/namei.c:path_openat
```
**Symbols:**

```
c057e22c-c057ebc8: do_last (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int do_last(struct nameidata *nd, struct file *file, const struct open_flags *op);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (c000000000491c30)
Location: fs/namei.c:3248
Inline: False
Direct callers:
  - fs/namei.c:path_openat
```
**Symbols:**

```
c000000000491c30-c00000000049275c: do_last (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int do_last(struct nameidata *nd, struct file *file, const struct open_flags *op);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffe000265b4c)
Location: fs/namei.c:3248
Inline: False
Direct callers:
  - fs/namei.c:path_openat
```
**Symbols:**

```
ffffffe000265b4c-ffffffe000266234: do_last (STB_LOCAL)
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
int do_last(struct nameidata *nd, struct file *file, const struct open_flags *op);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff812e6a60)
Location: fs/namei.c:3248
Inline: False
Direct callers:
  - fs/namei.c:path_openat
```
**Symbols:**

```
ffffffff812e6a60-ffffffff812e735d: do_last (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int do_last(struct nameidata *nd, struct file *file, const struct open_flags *op);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff812d76a0)
Location: fs/namei.c:3248
Inline: False
Direct callers:
  - fs/namei.c:path_openat
```
**Symbols:**

```
ffffffff812d76a0-ffffffff812d7f9d: do_last (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int do_last(struct nameidata *nd, struct file *file, const struct open_flags *op);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff812e4870)
Location: fs/namei.c:3248
Inline: False
Direct callers:
  - fs/namei.c:path_openat
```
**Symbols:**

```
ffffffff812e4870-ffffffff812e516d: do_last (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int do_last(struct nameidata *nd, struct file *file, const struct open_flags *op);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namei.c (ffffffff812f57f0)
Location: fs/namei.c:3248
Inline: False
Direct callers:
  - fs/namei.c:path_openat
```
**Symbols:**

```
ffffffff812f57f0-ffffffff812f60ed: do_last (STB_LOCAL)
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
