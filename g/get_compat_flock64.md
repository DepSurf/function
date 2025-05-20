# Function: <code>get_compat_flock64</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int get_compat_flock64(struct flock *kfl, struct compat_flock64 *ufl);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/compat.c (ffffffff812631e0)
Location: fs/compat.c:375
Inline: False
```
**Symbols:**

```
ffffffff812631e0-ffffffff81263267: get_compat_flock64 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int get_compat_flock64(struct flock *kfl, struct compat_flock64 *ufl);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/compat.c (ffffffff8128f430)
Location: fs/compat.c:375
Inline: False
```
**Symbols:**

```
ffffffff8128f430-ffffffff8128f4b3: get_compat_flock64 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int get_compat_flock64(struct flock *kfl, struct compat_flock64 *ufl);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/compat.c (ffffffff812a4420)
Location: fs/compat.c:361
Inline: False
```
**Symbols:**

```
ffffffff812a4420-ffffffff812a44a3: get_compat_flock64 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int get_compat_flock64(struct flock *kfl, const struct compat_flock64 *ufl);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fcntl.c (ffffffff81265850)
Location: fs/fcntl.c:543
Inline: False
Direct callers:
  - fs/fcntl.c:compat_SyS_fcntl
  - fs/fcntl.c:compat_SyS_fcntl
```
**Symbols:**

```
ffffffff81265850-ffffffff812658cc: get_compat_flock64 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int get_compat_flock64(struct flock *kfl, const struct compat_flock64 *ufl);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fcntl.c (ffffffff81287fa0)
Location: fs/fcntl.c:544
Inline: False
Direct callers:
  - fs/fcntl.c:compat_SyS_fcntl
  - fs/fcntl.c:compat_SyS_fcntl
```
**Symbols:**

```
ffffffff81287fa0-ffffffff8128801c: get_compat_flock64 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int get_compat_flock64(struct flock *kfl, const struct compat_flock64 *ufl);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fcntl.c (ffffffff812ae2d0)
Location: fs/fcntl.c:544
Inline: False
Direct callers:
  - fs/fcntl.c:do_compat_fcntl64
  - fs/fcntl.c:do_compat_fcntl64
```
**Symbols:**

```
ffffffff812ae2d0-ffffffff812ae342: get_compat_flock64 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int get_compat_flock64(struct flock *kfl, const struct compat_flock64 *ufl);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fcntl.c (ffffffff812c33e0)
Location: fs/fcntl.c:544
Inline: False
Direct callers:
  - fs/fcntl.c:do_compat_fcntl64
  - fs/fcntl.c:do_compat_fcntl64
```
**Symbols:**

```
ffffffff812c33e0-ffffffff812c3452: get_compat_flock64 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int get_compat_flock64(struct flock *kfl, const struct compat_flock64 *ufl);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fcntl.c (ffffffff812dfdf0)
Location: fs/fcntl.c:544
Inline: False
Direct callers:
  - fs/fcntl.c:do_compat_fcntl64
  - fs/fcntl.c:do_compat_fcntl64
  - fs/fcntl.c:do_compat_fcntl64
  - fs/fcntl.c:do_compat_fcntl64
```
**Symbols:**

```
ffffffff812dfdf0-ffffffff812dfe62: get_compat_flock64 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int get_compat_flock64(struct flock *kfl, const struct compat_flock64 *ufl);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fcntl.c (ffffffff812f1890)
Location: fs/fcntl.c:544
Inline: False
Direct callers:
  - fs/fcntl.c:do_compat_fcntl64
  - fs/fcntl.c:do_compat_fcntl64
  - fs/fcntl.c:do_compat_fcntl64
  - fs/fcntl.c:do_compat_fcntl64
```
**Symbols:**

```
ffffffff812f1890-ffffffff812f1902: get_compat_flock64 (STB_LOCAL)
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
In fs/fcntl.c (ffffffff8132a6fd)
Location: fs/fcntl.c:544
Inline: True
Inline callers:
  - fs/fcntl.c:do_compat_fcntl64
  - fs/fcntl.c:do_compat_fcntl64
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
In fs/fcntl.c (ffffffff81335c6d)
Location: fs/fcntl.c:544
Inline: True
Inline callers:
  - fs/fcntl.c:do_compat_fcntl64
  - fs/fcntl.c:do_compat_fcntl64
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
In fs/fcntl.c (ffffffff8133bdfd)
Location: fs/fcntl.c:549
Inline: True
Inline callers:
  - fs/fcntl.c:do_compat_fcntl64
  - fs/fcntl.c:do_compat_fcntl64
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
In fs/fcntl.c (ffffffff81389a7d)
Location: fs/fcntl.c:553
Inline: True
Inline callers:
  - fs/fcntl.c:do_compat_fcntl64
  - fs/fcntl.c:do_compat_fcntl64
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
In fs/fcntl.c (ffffffff8140ab22)
Location: fs/fcntl.c:531
Inline: True
Inline callers:
  - fs/fcntl.c:do_compat_fcntl64
  - fs/fcntl.c:do_compat_fcntl64
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
In fs/fcntl.c (ffffffff81495392)
Location: fs/fcntl.c:532
Inline: True
Inline callers:
  - fs/fcntl.c:do_compat_fcntl64
  - fs/fcntl.c:do_compat_fcntl64
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
In fs/fcntl.c (ffffffff814ca39d)
Location: fs/fcntl.c:533
Inline: True
Inline callers:
  - fs/fcntl.c:do_compat_fcntl64
  - fs/fcntl.c:do_compat_fcntl64
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
In fs/fcntl.c (ffffffff814fcc6d)
Location: fs/fcntl.c:534
Inline: True
Inline callers:
  - fs/fcntl.c:do_compat_fcntl64
  - fs/fcntl.c:do_compat_fcntl64
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
int get_compat_flock64(struct flock *kfl, const struct compat_flock64 *ufl);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fcntl.c (ffff80001039b9b8)
Location: fs/fcntl.c:544
Inline: False
Direct callers:
  - fs/fcntl.c:do_compat_fcntl64
  - fs/fcntl.c:do_compat_fcntl64
  - fs/fcntl.c:do_compat_fcntl64
  - fs/fcntl.c:do_compat_fcntl64
```
**Symbols:**

```
ffff80001039b9b8-ffff80001039ba4c: get_compat_flock64 (STB_LOCAL)
```
</details>
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int get_compat_flock64(struct flock *kfl, const struct compat_flock64 *ufl);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fcntl.c (c000000000496560)
Location: fs/fcntl.c:544
Inline: False
Direct callers:
  - fs/fcntl.c:do_compat_fcntl64
  - fs/fcntl.c:do_compat_fcntl64
```
**Symbols:**

```
c000000000496560-c000000000496600: get_compat_flock64 (STB_LOCAL)
```
</details>
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
int get_compat_flock64(struct flock *kfl, const struct compat_flock64 *ufl);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fcntl.c (ffffffff812e9e70)
Location: fs/fcntl.c:544
Inline: False
Direct callers:
  - fs/fcntl.c:do_compat_fcntl64
  - fs/fcntl.c:do_compat_fcntl64
  - fs/fcntl.c:do_compat_fcntl64
  - fs/fcntl.c:do_compat_fcntl64
```
**Symbols:**

```
ffffffff812e9e70-ffffffff812e9ee2: get_compat_flock64 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int get_compat_flock64(struct flock *kfl, const struct compat_flock64 *ufl);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fcntl.c (ffffffff812dac10)
Location: fs/fcntl.c:544
Inline: False
Direct callers:
  - fs/fcntl.c:do_compat_fcntl64
  - fs/fcntl.c:do_compat_fcntl64
  - fs/fcntl.c:do_compat_fcntl64
  - fs/fcntl.c:do_compat_fcntl64
```
**Symbols:**

```
ffffffff812dac10-ffffffff812dac82: get_compat_flock64 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int get_compat_flock64(struct flock *kfl, const struct compat_flock64 *ufl);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fcntl.c (ffffffff812e7c80)
Location: fs/fcntl.c:544
Inline: False
Direct callers:
  - fs/fcntl.c:do_compat_fcntl64
  - fs/fcntl.c:do_compat_fcntl64
  - fs/fcntl.c:do_compat_fcntl64
  - fs/fcntl.c:do_compat_fcntl64
```
**Symbols:**

```
ffffffff812e7c80-ffffffff812e7cf2: get_compat_flock64 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int get_compat_flock64(struct flock *kfl, const struct compat_flock64 *ufl);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fcntl.c (ffffffff812f8ee0)
Location: fs/fcntl.c:544
Inline: False
Direct callers:
  - fs/fcntl.c:do_compat_fcntl64
  - fs/fcntl.c:do_compat_fcntl64
  - fs/fcntl.c:do_compat_fcntl64
  - fs/fcntl.c:do_compat_fcntl64
```
**Symbols:**

```
ffffffff812f8ee0-ffffffff812f8f52: get_compat_flock64 (STB_LOCAL)
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
<details>
<summary>Changed between <code>4.10</code> and <code>4.13</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>struct compat_flock64 *ufl</code> ➡️ <code>const struct compat_flock64 *ufl</code>
</li>
</ul>
</details>
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
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
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
