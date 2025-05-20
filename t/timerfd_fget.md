# Function: <code>timerfd_fget</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int timerfd_fget(int fd, struct fd *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/timerfd.c (ffffffff81257fd0)
Location: fs/timerfd.c:363
Inline: False
Direct callers:
  - fs/timerfd.c:do_timerfd_gettime
  - fs/timerfd.c:do_timerfd_settime
```
**Symbols:**

```
ffffffff81257fd0-ffffffff81258038: timerfd_fget (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int timerfd_fget(int fd, struct fd *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/timerfd.c (ffffffff812808d0)
Location: fs/timerfd.c:363
Inline: False
Direct callers:
  - fs/timerfd.c:do_timerfd_gettime
  - fs/timerfd.c:do_timerfd_settime
```
**Symbols:**

```
ffffffff812808d0-ffffffff81280938: timerfd_fget (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int timerfd_fget(int fd, struct fd *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/timerfd.c (ffffffff81294440)
Location: fs/timerfd.c:363
Inline: False
Direct callers:
  - fs/timerfd.c:do_timerfd_gettime
  - fs/timerfd.c:do_timerfd_settime
```
**Symbols:**

```
ffffffff81294440-ffffffff812944a8: timerfd_fget (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int timerfd_fget(int fd, struct fd *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/timerfd.c (ffffffff812a1720)
Location: fs/timerfd.c:373
Inline: False
Direct callers:
  - fs/timerfd.c:do_timerfd_gettime
  - fs/timerfd.c:do_timerfd_settime
```
**Symbols:**

```
ffffffff812a1720-ffffffff812a1788: timerfd_fget (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int timerfd_fget(int fd, struct fd *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/timerfd.c (ffffffff812c4a40)
Location: fs/timerfd.c:374
Inline: False
Direct callers:
  - fs/timerfd.c:do_timerfd_gettime
  - fs/timerfd.c:do_timerfd_settime
```
**Symbols:**

```
ffffffff812c4a40-ffffffff812c4aa8: timerfd_fget (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int timerfd_fget(int fd, struct fd *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/timerfd.c (ffffffff812ed8e0)
Location: fs/timerfd.c:374
Inline: False
Direct callers:
  - fs/timerfd.c:do_timerfd_gettime
```
**Symbols:**

```
ffffffff812ed8e0-ffffffff812ed93c: timerfd_fget (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int timerfd_fget(int fd, struct fd *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/timerfd.c (ffffffff81302410)
Location: fs/timerfd.c:374
Inline: False
Direct callers:
  - fs/timerfd.c:do_timerfd_gettime
```
**Symbols:**

```
ffffffff81302410-ffffffff8130246c: timerfd_fget (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int timerfd_fget(int fd, struct fd *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/timerfd.c (ffffffff81323980)
Location: fs/timerfd.c:374
Inline: False
Direct callers:
  - fs/timerfd.c:do_timerfd_gettime
```
**Symbols:**

```
ffffffff81323980-ffffffff813239d6: timerfd_fget (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int timerfd_fget(int fd, struct fd *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/timerfd.c (ffffffff813366e0)
Location: fs/timerfd.c:374
Inline: False
Direct callers:
  - fs/timerfd.c:do_timerfd_gettime
```
**Symbols:**

```
ffffffff813366e0-ffffffff81336736: timerfd_fget (STB_LOCAL)
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
In fs/timerfd.c (ffffffff813707c5)
Location: fs/timerfd.c:377
Inline: True
Inline callers:
  - fs/timerfd.c:do_timerfd_gettime
  - fs/timerfd.c:do_timerfd_settime
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
In fs/timerfd.c (ffffffff8137e535)
Location: fs/timerfd.c:377
Inline: True
Inline callers:
  - fs/timerfd.c:do_timerfd_gettime
  - fs/timerfd.c:do_timerfd_settime
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
In fs/timerfd.c (ffffffff813851b5)
Location: fs/timerfd.c:377
Inline: True
Inline callers:
  - fs/timerfd.c:do_timerfd_gettime
  - fs/timerfd.c:do_timerfd_settime
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
In fs/timerfd.c (ffffffff813d2435)
Location: fs/timerfd.c:393
Inline: True
Inline callers:
  - fs/timerfd.c:do_timerfd_gettime
  - fs/timerfd.c:do_timerfd_settime
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
In fs/timerfd.c (ffffffff8145bfd5)
Location: fs/timerfd.c:393
Inline: True
Inline callers:
  - fs/timerfd.c:do_timerfd_gettime
  - fs/timerfd.c:do_timerfd_settime
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
In fs/timerfd.c (ffffffff814eb6a5)
Location: fs/timerfd.c:393
Inline: True
Inline callers:
  - fs/timerfd.c:do_timerfd_gettime
  - fs/timerfd.c:do_timerfd_settime
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
In fs/timerfd.c (ffffffff81522445)
Location: fs/timerfd.c:393
Inline: True
Inline callers:
  - fs/timerfd.c:do_timerfd_gettime
  - fs/timerfd.c:do_timerfd_settime
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
In fs/timerfd.c (ffffffff81556a65)
Location: fs/timerfd.c:393
Inline: True
Inline callers:
  - fs/timerfd.c:do_timerfd_gettime
  - fs/timerfd.c:do_timerfd_settime
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
int timerfd_fget(int fd, struct fd *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/timerfd.c (ffff8000103f4400)
Location: fs/timerfd.c:374
Inline: False
Direct callers:
  - fs/timerfd.c:do_timerfd_gettime
```
**Symbols:**

```
ffff8000103f4400-ffff8000103f447c: timerfd_fget (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int timerfd_fget(int fd, struct fd *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/timerfd.c (c05c9390)
Location: fs/timerfd.c:374
Inline: False
Direct callers:
  - fs/timerfd.c:do_timerfd_gettime
```
**Symbols:**

```
c05c9390-c05c9404: timerfd_fget (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int timerfd_fget(int fd, struct fd *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/timerfd.c (c0000000004fc1f0)
Location: fs/timerfd.c:374
Inline: False
Direct callers:
  - fs/timerfd.c:do_timerfd_gettime
```
**Symbols:**

```
c0000000004fc1f0-c0000000004fc298: timerfd_fget (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int timerfd_fget(int fd, struct fd *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/timerfd.c (ffffffe0002a5642)
Location: fs/timerfd.c:374
Inline: False
Direct callers:
  - fs/timerfd.c:__se_sys_timerfd_gettime
  - fs/timerfd.c:__se_sys_timerfd_settime
```
**Symbols:**

```
ffffffe0002a5642-ffffffe0002a56aa: timerfd_fget (STB_LOCAL)
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
int timerfd_fget(int fd, struct fd *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/timerfd.c (ffffffff8132ecc0)
Location: fs/timerfd.c:374
Inline: False
Direct callers:
  - fs/timerfd.c:do_timerfd_gettime
```
**Symbols:**

```
ffffffff8132ecc0-ffffffff8132ed16: timerfd_fget (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int timerfd_fget(int fd, struct fd *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/timerfd.c (ffffffff8131f900)
Location: fs/timerfd.c:374
Inline: False
Direct callers:
  - fs/timerfd.c:do_timerfd_gettime
```
**Symbols:**

```
ffffffff8131f900-ffffffff8131f956: timerfd_fget (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int timerfd_fget(int fd, struct fd *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/timerfd.c (ffffffff8132c790)
Location: fs/timerfd.c:374
Inline: False
Direct callers:
  - fs/timerfd.c:do_timerfd_gettime
```
**Symbols:**

```
ffffffff8132c790-ffffffff8132c7e6: timerfd_fget (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int timerfd_fget(int fd, struct fd *p);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/timerfd.c (ffffffff8133f1d0)
Location: fs/timerfd.c:374
Inline: False
Direct callers:
  - fs/timerfd.c:do_timerfd_gettime
```
**Symbols:**

```
ffffffff8133f1d0-ffffffff8133f226: timerfd_fget (STB_LOCAL)
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
