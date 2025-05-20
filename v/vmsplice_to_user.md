# Function: <code>vmsplice_to_user</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
long int vmsplice_to_user(struct file *file, const struct iovec *uiov, long unsigned int nr_segs, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/splice.c (ffffffff8123e2c0)
Location: fs/splice.c:1551
Inline: False
Direct callers:
  - fs/splice.c:compat_SyS_vmsplice
```
**Symbols:**

```
ffffffff8123e2c0-ffffffff8123e3d2: vmsplice_to_user (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
long int vmsplice_to_user(struct file *file, const struct iovec *uiov, long unsigned int nr_segs, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/splice.c (ffffffff81266390)
Location: fs/splice.c:1555
Inline: False
Direct callers:
  - fs/splice.c:compat_SyS_vmsplice
```
**Symbols:**

```
ffffffff81266390-ffffffff81266499: vmsplice_to_user (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
long int vmsplice_to_user(struct file *file, const struct iovec *uiov, long unsigned int nr_segs, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/splice.c (ffffffff81279c80)
Location: fs/splice.c:1267
Inline: False
Direct callers:
  - fs/splice.c:compat_SyS_vmsplice
```
**Symbols:**

```
ffffffff81279c80-ffffffff81279d89: vmsplice_to_user (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
long int vmsplice_to_user(struct file *file, const struct iovec *uiov, long unsigned int nr_segs, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/splice.c (ffffffff812871c0)
Location: fs/splice.c:1263
Inline: False
Direct callers:
  - fs/splice.c:compat_SyS_vmsplice
```
**Symbols:**

```
ffffffff812871c0-ffffffff812872ef: vmsplice_to_user (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
long int vmsplice_to_user(struct file *file, const struct iovec *uiov, long unsigned int nr_segs, unsigned int flags);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/splice.c (ffffffff812a99a0)
Location: fs/splice.c:1247
Inline: False
Direct callers:
  - fs/splice.c:compat_SyS_vmsplice
```
**Symbols:**

```
ffffffff812a99a0-ffffffff812a9acf: vmsplice_to_user (STB_LOCAL)
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
In fs/splice.c (ffffffff812d1334)
Location: fs/splice.c:1248
Inline: True
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
In fs/splice.c (ffffffff812e67e4)
Location: fs/splice.c:1252
Inline: True
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
In fs/splice.c (ffffffff81305446)
Location: fs/splice.c:1258
Inline: True
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
In fs/splice.c (ffffffff813184d6)
Location: fs/splice.c:1266
Inline: True
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
In fs/splice.c (ffffffff813513c1)
Location: fs/splice.c:1254
Inline: True
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
In fs/splice.c (ffffffff8135dea6)
Location: fs/splice.c:1208
Inline: True
Inline callers:
  - fs/splice.c:__do_sys_vmsplice
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
In fs/splice.c (ffffffff81364d96)
Location: fs/splice.c:1213
Inline: True
Inline callers:
  - fs/splice.c:__do_sys_vmsplice
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
In fs/splice.c (ffffffff813b31d8)
Location: fs/splice.c:1215
Inline: True
Inline callers:
  - fs/splice.c:__do_sys_vmsplice
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
In fs/splice.c (ffffffff814382fc)
Location: fs/splice.c:1211
Inline: True
Inline callers:
  - fs/splice.c:__do_sys_vmsplice
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
In fs/splice.c (ffffffff814c6797)
Location: fs/splice.c:1211
Inline: True
Inline callers:
  - fs/splice.c:__do_sys_vmsplice
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
In fs/splice.c (ffffffff814fc1c5)
Location: fs/splice.c:1443
Inline: True
Inline callers:
  - fs/splice.c:__do_sys_vmsplice
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
In fs/splice.c (ffffffff81530fa5)
Location: fs/splice.c:1506
Inline: True
Inline callers:
  - fs/splice.c:__do_sys_vmsplice
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
In fs/splice.c (ffff8000103ce5ac)
Location: fs/splice.c:1266
Inline: True
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
In fs/splice.c (c05a9da0)
Location: fs/splice.c:1266
Inline: True
Inline callers:
  - fs/splice.c:__do_sys_vmsplice
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
In fs/splice.c (c0000000004d19b0)
Location: fs/splice.c:1266
Inline: True
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
In fs/splice.c (ffffffe00028b62a)
Location: fs/splice.c:1266
Inline: True
Inline callers:
  - fs/splice.c:__do_sys_vmsplice
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
In fs/splice.c (ffffffff81310ab6)
Location: fs/splice.c:1266
Inline: True
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
In fs/splice.c (ffffffff813016c6)
Location: fs/splice.c:1266
Inline: True
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
In fs/splice.c (ffffffff8130e8a6)
Location: fs/splice.c:1266
Inline: True
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
In fs/splice.c (ffffffff813200a6)
Location: fs/splice.c:1266
Inline: True
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
</ul>
