# Function: <code>put_compat_flock</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int put_compat_flock(struct flock *kfl, struct compat_flock *ufl);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/compat.c (ffffffff81263150)
Location: fs/compat.c:362
Inline: False
Direct callers:
  - fs/compat.c:compat_SyS_fcntl
```
**Symbols:**

```
ffffffff81263150-ffffffff812631d5: put_compat_flock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int put_compat_flock(struct flock *kfl, struct compat_flock *ufl);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/compat.c (ffffffff8128f3a0)
Location: fs/compat.c:362
Inline: False
Direct callers:
  - fs/compat.c:compat_SyS_fcntl
```
**Symbols:**

```
ffffffff8128f3a0-ffffffff8128f421: put_compat_flock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int put_compat_flock(struct flock *kfl, struct compat_flock *ufl);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/compat.c (ffffffff812a4390)
Location: fs/compat.c:348
Inline: False
Direct callers:
  - fs/compat.c:compat_SyS_fcntl
```
**Symbols:**

```
ffffffff812a4390-ffffffff812a4411: put_compat_flock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int put_compat_flock(const struct flock *kfl, struct compat_flock *ufl);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fcntl.c (ffffffff812656d0)
Location: fs/fcntl.c:553
Inline: False
Direct callers:
  - fs/fcntl.c:compat_SyS_fcntl
```
**Symbols:**

```
ffffffff812656d0-ffffffff81265744: put_compat_flock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int put_compat_flock(const struct flock *kfl, struct compat_flock *ufl);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/fcntl.c (ffffffff81287e20)
Location: fs/fcntl.c:554
Inline: False
Direct callers:
  - fs/fcntl.c:compat_SyS_fcntl
```
**Symbols:**

```
ffffffff81287e20-ffffffff81287e94: put_compat_flock (STB_LOCAL)
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
In fs/fcntl.c (ffffffff812aef01)
Location: fs/fcntl.c:554
Inline: True
Inline callers:
  - fs/fcntl.c:do_compat_fcntl64
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
In fs/fcntl.c (ffffffff812c4003)
Location: fs/fcntl.c:554
Inline: True
Inline callers:
  - fs/fcntl.c:do_compat_fcntl64
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
In fs/fcntl.c (ffffffff812e0afa)
Location: fs/fcntl.c:554
Inline: True
Inline callers:
  - fs/fcntl.c:do_compat_fcntl64
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
In fs/fcntl.c (ffffffff812f25aa)
Location: fs/fcntl.c:554
Inline: True
Inline callers:
  - fs/fcntl.c:do_compat_fcntl64
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
In fs/fcntl.c (ffffffff8132a80b)
Location: fs/fcntl.c:554
Inline: True
Inline callers:
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
In fs/fcntl.c (ffffffff81335d7b)
Location: fs/fcntl.c:554
Inline: True
Inline callers:
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
In fs/fcntl.c (ffffffff8133bf09)
Location: fs/fcntl.c:559
Inline: True
Inline callers:
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
In fs/fcntl.c (ffffffff81389b89)
Location: fs/fcntl.c:563
Inline: True
Inline callers:
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
In fs/fcntl.c (ffffffff8140ac5e)
Location: fs/fcntl.c:541
Inline: True
Inline callers:
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
In fs/fcntl.c (ffffffff814954ce)
Location: fs/fcntl.c:542
Inline: True
Inline callers:
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
In fs/fcntl.c (ffffffff814ca4f7)
Location: fs/fcntl.c:543
Inline: True
Inline callers:
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
In fs/fcntl.c (ffffffff814fcdc7)
Location: fs/fcntl.c:544
Inline: True
Inline callers:
  - fs/fcntl.c:do_compat_fcntl64
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
In fs/fcntl.c (ffff80001039c774)
Location: fs/fcntl.c:554
Inline: True
Inline callers:
  - fs/fcntl.c:do_compat_fcntl64
```
</details>
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/fcntl.c (c0000000004974d4)
Location: fs/fcntl.c:554
Inline: True
Inline callers:
  - fs/fcntl.c:do_compat_fcntl64
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
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In fs/fcntl.c (ffffffff812eab8a)
Location: fs/fcntl.c:554
Inline: True
Inline callers:
  - fs/fcntl.c:do_compat_fcntl64
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
In fs/fcntl.c (ffffffff812db7ca)
Location: fs/fcntl.c:554
Inline: True
Inline callers:
  - fs/fcntl.c:do_compat_fcntl64
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
In fs/fcntl.c (ffffffff812e899a)
Location: fs/fcntl.c:554
Inline: True
Inline callers:
  - fs/fcntl.c:do_compat_fcntl64
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
In fs/fcntl.c (ffffffff812f996a)
Location: fs/fcntl.c:554
Inline: True
Inline callers:
  - fs/fcntl.c:do_compat_fcntl64
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
<code>struct flock *kfl</code> ➡️ <code>const struct flock *kfl</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
</ul>
