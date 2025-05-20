# Function: <code>tty_paranoia_check</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
int tty_paranoia_check(struct tty_struct *tty, struct inode *inode, const char *routine);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff814e1140)
Location: drivers/tty/tty_io.c:259
Inline: True
Direct callers:
  - drivers/tty/tty_io.c:__tty_fasync
  - drivers/tty/tty_io.c:tty_compat_ioctl
  - drivers/tty/tty_io.c:tty_poll
  - drivers/tty/tty_io.c:tty_read
  - drivers/tty/tty_io.c:tty_write
  - drivers/tty/tty_io.c:tty_ioctl
  - drivers/tty/tty_io.c:tty_release
```
**Symbols:**

```
ffffffff814e1140-ffffffff814e11aa: tty_paranoia_check (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
int tty_paranoia_check(struct tty_struct *tty, struct inode *inode, const char *routine);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff81530ed0)
Location: drivers/tty/tty_io.c:259
Inline: True
Direct callers:
  - drivers/tty/tty_io.c:tty_compat_ioctl
  - drivers/tty/tty_io.c:tty_ioctl
  - drivers/tty/tty_io.c:__tty_fasync
  - drivers/tty/tty_io.c:tty_poll
  - drivers/tty/tty_io.c:tty_release
  - drivers/tty/tty_io.c:tty_write
  - drivers/tty/tty_io.c:tty_read
```
**Symbols:**

```
ffffffff81530ed0-ffffffff81530f3a: tty_paranoia_check (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
int tty_paranoia_check(struct tty_struct *tty, struct inode *inode, const char *routine);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff8155d620)
Location: drivers/tty/tty_io.c:259
Inline: True
Direct callers:
  - drivers/tty/tty_io.c:tty_compat_ioctl
  - drivers/tty/tty_io.c:tty_ioctl
  - drivers/tty/tty_io.c:__tty_fasync
  - drivers/tty/tty_io.c:tty_poll
  - drivers/tty/tty_io.c:tty_release
  - drivers/tty/tty_io.c:tty_write
  - drivers/tty/tty_io.c:tty_read
```
**Symbols:**

```
ffffffff8155d620-ffffffff8155d68a: tty_paranoia_check (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int tty_paranoia_check(struct tty_struct *tty, struct inode *inode, const char *routine);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff81572510)
Location: drivers/tty/tty_io.c:260
Inline: True
Direct callers:
  - drivers/tty/tty_io.c:tty_compat_ioctl
  - drivers/tty/tty_io.c:tty_ioctl
  - drivers/tty/tty_io.c:__tty_fasync
  - drivers/tty/tty_io.c:tty_poll
  - drivers/tty/tty_io.c:tty_release
  - drivers/tty/tty_io.c:tty_write
  - drivers/tty/tty_io.c:tty_read
```
**Symbols:**

```
ffffffff81572510-ffffffff8157257a: tty_paranoia_check (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int tty_paranoia_check(struct tty_struct *tty, struct inode *inode, const char *routine);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff815d6890)
Location: drivers/tty/tty_io.c:261
Inline: True
Direct callers:
  - drivers/tty/tty_io.c:tty_compat_ioctl
  - drivers/tty/tty_io.c:tty_ioctl
  - drivers/tty/tty_io.c:__tty_fasync
  - drivers/tty/tty_io.c:tty_poll
  - drivers/tty/tty_io.c:tty_release
  - drivers/tty/tty_io.c:tty_write
  - drivers/tty/tty_io.c:tty_read
```
**Symbols:**

```
ffffffff815d6890-ffffffff815d68fa: tty_paranoia_check (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

```c
int tty_paranoia_check(struct tty_struct *tty, struct inode *inode, const char *routine);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/tty/tty_io.c (0)
Location: drivers/tty/tty_io.c:261
Inline: True
Direct callers:
  - drivers/tty/tty_io.c:tty_compat_ioctl
  - drivers/tty/tty_io.c:tty_ioctl
  - drivers/tty/tty_io.c:__tty_fasync
  - drivers/tty/tty_io.c:tty_poll
  - drivers/tty/tty_io.c:tty_release
  - drivers/tty/tty_io.c:tty_write
  - drivers/tty/tty_io.c:tty_read
```
**Symbols:**

```
ffffffff8160f8c0-ffffffff8160f8e2: tty_paranoia_check (STB_LOCAL)
ffffffff8161306a-ffffffff816130c0: tty_paranoia_check.cold.34 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

```c
int tty_paranoia_check(struct tty_struct *tty, struct inode *inode, const char *routine);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff8163010a)
Location: drivers/tty/tty_io.c:262
Inline: True
Direct callers:
  - drivers/tty/tty_io.c:tty_compat_ioctl
  - drivers/tty/tty_io.c:tty_ioctl
  - drivers/tty/tty_io.c:__tty_fasync
  - drivers/tty/tty_io.c:tty_poll
  - drivers/tty/tty_io.c:tty_release
  - drivers/tty/tty_io.c:tty_write
  - drivers/tty/tty_io.c:tty_read
```
**Symbols:**

```
ffffffff8162c870-ffffffff8162c892: tty_paranoia_check (STB_LOCAL)
ffffffff8163010a-ffffffff81630160: tty_paranoia_check.cold.33 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

```c
int tty_paranoia_check(struct tty_struct *tty, struct inode *inode, const char *routine);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff81664036)
Location: drivers/tty/tty_io.c:262
Inline: True
Direct callers:
  - drivers/tty/tty_io.c:tty_compat_ioctl
  - drivers/tty/tty_io.c:tty_compat_ioctl
  - drivers/tty/tty_io.c:tty_ioctl
  - drivers/tty/tty_io.c:__tty_fasync
  - drivers/tty/tty_io.c:tty_poll
  - drivers/tty/tty_io.c:tty_release
  - drivers/tty/tty_io.c:tty_write
  - drivers/tty/tty_io.c:tty_read
```
**Symbols:**

```
ffffffff816607c0-ffffffff816607e2: tty_paranoia_check (STB_LOCAL)
ffffffff81664036-ffffffff81664092: tty_paranoia_check.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

```c
int tty_paranoia_check(struct tty_struct *tty, struct inode *inode, const char *routine);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff816866a6)
Location: drivers/tty/tty_io.c:262
Inline: True
Direct callers:
  - drivers/tty/tty_io.c:tty_compat_ioctl
  - drivers/tty/tty_io.c:tty_compat_ioctl
  - drivers/tty/tty_io.c:tty_ioctl
  - drivers/tty/tty_io.c:__tty_fasync
  - drivers/tty/tty_io.c:tty_poll
  - drivers/tty/tty_io.c:tty_release
  - drivers/tty/tty_io.c:tty_write
  - drivers/tty/tty_io.c:tty_read
```
**Symbols:**

```
ffffffff81682e10-ffffffff81682e32: tty_paranoia_check (STB_LOCAL)
ffffffff816866a6-ffffffff81686702: tty_paranoia_check.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
int tty_paranoia_check(struct tty_struct *tty, struct inode *inode, const char *routine);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff81736f2a)
Location: drivers/tty/tty_io.c:263
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_fasync
  - drivers/tty/tty_io.c:tty_fasync
  - drivers/tty/tty_io.c:tty_poll
  - drivers/tty/tty_io.c:tty_poll
Direct callers:
  - drivers/tty/tty_io.c:tty_compat_ioctl
  - drivers/tty/tty_io.c:tty_compat_ioctl
  - drivers/tty/tty_io.c:tty_ioctl
  - drivers/tty/tty_io.c:tty_release
  - drivers/tty/tty_io.c:tty_release
  - drivers/tty/tty_io.c:tty_write
  - drivers/tty/tty_io.c:tty_read
```
**Symbols:**

```
ffffffff817344c0-ffffffff817344e2: tty_paranoia_check (STB_LOCAL)
ffffffff81738436-ffffffff81738492: tty_paranoia_check.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

```c
int tty_paranoia_check(struct tty_struct *tty, struct inode *inode, const char *routine);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff817527ca)
Location: drivers/tty/tty_io.c:260
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_fasync
  - drivers/tty/tty_io.c:tty_fasync
  - drivers/tty/tty_io.c:tty_poll
  - drivers/tty/tty_io.c:tty_poll
Direct callers:
  - drivers/tty/tty_io.c:tty_compat_ioctl
  - drivers/tty/tty_io.c:tty_compat_ioctl
  - drivers/tty/tty_io.c:tty_ioctl
  - drivers/tty/tty_io.c:tty_release
  - drivers/tty/tty_io.c:tty_release
  - drivers/tty/tty_io.c:tty_read
```
**Symbols:**

```
ffffffff81750610-ffffffff81750632: tty_paranoia_check (STB_LOCAL)
ffffffff81c072f9-ffffffff81c07355: tty_paranoia_check.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

```c
int tty_paranoia_check(struct tty_struct *tty, struct inode *inode, const char *routine);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff8173600a)
Location: drivers/tty/tty_io.c:261
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_fasync
  - drivers/tty/tty_io.c:tty_fasync
  - drivers/tty/tty_io.c:tty_poll
  - drivers/tty/tty_io.c:tty_poll
Direct callers:
  - drivers/tty/tty_io.c:tty_compat_ioctl
  - drivers/tty/tty_io.c:tty_compat_ioctl
  - drivers/tty/tty_io.c:tty_ioctl
  - drivers/tty/tty_io.c:tty_release
  - drivers/tty/tty_io.c:tty_release
  - drivers/tty/tty_io.c:tty_read
```
**Symbols:**

```
ffffffff81734490-ffffffff817344b2: tty_paranoia_check (STB_LOCAL)
ffffffff81bf8f63-ffffffff81bf8fbf: tty_paranoia_check.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
int tty_paranoia_check(struct tty_struct *tty, struct inode *inode, const char *routine);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff817b69ca)
Location: drivers/tty/tty_io.c:260
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_fasync
  - drivers/tty/tty_io.c:tty_fasync
  - drivers/tty/tty_io.c:tty_poll
  - drivers/tty/tty_io.c:tty_poll
Direct callers:
  - drivers/tty/tty_io.c:tty_compat_ioctl
  - drivers/tty/tty_io.c:tty_compat_ioctl
  - drivers/tty/tty_io.c:tty_ioctl
  - drivers/tty/tty_io.c:tty_release
  - drivers/tty/tty_io.c:tty_release
  - drivers/tty/tty_io.c:tty_read
```
**Symbols:**

```
ffffffff817b4df0-ffffffff817b4e12: tty_paranoia_check (STB_LOCAL)
ffffffff81cf86ec-ffffffff81cf8748: tty_paranoia_check.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

```c
int tty_paranoia_check(struct tty_struct *tty, struct inode *inode, const char *routine);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff818f3a24)
Location: drivers/tty/tty_io.c:259
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_fasync
  - drivers/tty/tty_io.c:tty_poll
Direct callers:
  - drivers/tty/tty_io.c:tty_compat_ioctl
  - drivers/tty/tty_io.c:tty_compat_ioctl
  - drivers/tty/tty_io.c:tty_ioctl
  - drivers/tty/tty_io.c:tty_release
  - drivers/tty/tty_io.c:tty_release
  - drivers/tty/tty_io.c:tty_read
```
**Symbols:**

```
ffffffff818efc70-ffffffff818efc9e: tty_paranoia_check (STB_LOCAL)
ffffffff81ec07e7-ffffffff81ec0835: tty_paranoia_check.cold (STB_LOCAL)
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
In drivers/tty/tty_io.c (ffffffff81a4b558)
Location: drivers/tty/tty_io.c:258
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_compat_ioctl
  - drivers/tty/tty_io.c:tty_compat_ioctl
  - drivers/tty/tty_io.c:tty_ioctl
  - drivers/tty/tty_io.c:tty_ioctl
  - drivers/tty/tty_io.c:tty_poll
  - drivers/tty/tty_io.c:tty_poll
  - drivers/tty/tty_io.c:tty_release
  - drivers/tty/tty_io.c:tty_release
  - drivers/tty/tty_io.c:tty_read
  - drivers/tty/tty_io.c:tty_read
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
In drivers/tty/tty_io.c (ffffffff81a957ca)
Location: drivers/tty/tty_io.c:259
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_compat_ioctl
  - drivers/tty/tty_io.c:tty_compat_ioctl
  - drivers/tty/tty_io.c:tty_ioctl
  - drivers/tty/tty_io.c:tty_ioctl
  - drivers/tty/tty_io.c:tty_poll
  - drivers/tty/tty_io.c:tty_poll
  - drivers/tty/tty_io.c:tty_release
  - drivers/tty/tty_io.c:tty_release
  - drivers/tty/tty_io.c:tty_read
  - drivers/tty/tty_io.c:tty_read
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
In drivers/tty/tty_io.c (ffffffff81ae822a)
Location: drivers/tty/tty_io.c:259
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_compat_ioctl
  - drivers/tty/tty_io.c:tty_compat_ioctl
  - drivers/tty/tty_io.c:tty_ioctl
  - drivers/tty/tty_io.c:tty_ioctl
  - drivers/tty/tty_io.c:tty_poll
  - drivers/tty/tty_io.c:tty_poll
  - drivers/tty/tty_io.c:tty_release
  - drivers/tty/tty_io.c:tty_release
  - drivers/tty/tty_io.c:tty_read
  - drivers/tty/tty_io.c:tty_read
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
int tty_paranoia_check(struct tty_struct *tty, struct inode *inode, const char *routine);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffff80001084f010)
Location: drivers/tty/tty_io.c:262
Inline: True
Direct callers:
  - drivers/tty/tty_io.c:tty_compat_ioctl
  - drivers/tty/tty_io.c:tty_compat_ioctl
  - drivers/tty/tty_io.c:tty_ioctl
  - drivers/tty/tty_io.c:__tty_fasync
  - drivers/tty/tty_io.c:tty_poll
  - drivers/tty/tty_io.c:tty_release
  - drivers/tty/tty_io.c:tty_write
  - drivers/tty/tty_io.c:tty_read
```
**Symbols:**

```
ffff80001084f010-ffff80001084f0a4: tty_paranoia_check (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int tty_paranoia_check(struct tty_struct *tty, struct inode *inode, const char *routine);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (c095b228)
Location: drivers/tty/tty_io.c:262
Inline: True
Direct callers:
  - drivers/tty/tty_io.c:tty_ioctl
  - drivers/tty/tty_io.c:__tty_fasync
  - drivers/tty/tty_io.c:tty_poll
  - drivers/tty/tty_io.c:tty_release
  - drivers/tty/tty_io.c:tty_write
  - drivers/tty/tty_io.c:tty_read
```
**Symbols:**

```
c095b228-c095b2a4: tty_paranoia_check (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
int tty_paranoia_check(struct tty_struct *tty, struct inode *inode, const char *routine);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (c0000000008ee4a0)
Location: drivers/tty/tty_io.c:262
Inline: True
Direct callers:
  - drivers/tty/tty_io.c:tty_compat_ioctl
  - drivers/tty/tty_io.c:tty_compat_ioctl
  - drivers/tty/tty_io.c:tty_ioctl
  - drivers/tty/tty_io.c:__tty_fasync
  - drivers/tty/tty_io.c:tty_poll
  - drivers/tty/tty_io.c:tty_release
  - drivers/tty/tty_io.c:tty_write
  - drivers/tty/tty_io.c:tty_read
```
**Symbols:**

```
c0000000008ee4a0-c0000000008ee528: tty_paranoia_check (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
int tty_paranoia_check(struct tty_struct *tty, struct inode *inode, const char *routine);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffe00052d664)
Location: drivers/tty/tty_io.c:262
Inline: True
Direct callers:
  - drivers/tty/tty_io.c:tty_ioctl
  - drivers/tty/tty_io.c:__tty_fasync
  - drivers/tty/tty_io.c:tty_poll
  - drivers/tty/tty_io.c:tty_release
  - drivers/tty/tty_io.c:tty_write
  - drivers/tty/tty_io.c:tty_read
```
**Symbols:**

```
ffffffe00052d664-ffffffe00052d6d4: tty_paranoia_check (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

```c
int tty_paranoia_check(struct tty_struct *tty, struct inode *inode, const char *routine);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff8164c126)
Location: drivers/tty/tty_io.c:262
Inline: True
Direct callers:
  - drivers/tty/tty_io.c:tty_compat_ioctl
  - drivers/tty/tty_io.c:tty_compat_ioctl
  - drivers/tty/tty_io.c:tty_ioctl
  - drivers/tty/tty_io.c:__tty_fasync
  - drivers/tty/tty_io.c:tty_poll
  - drivers/tty/tty_io.c:tty_release
  - drivers/tty/tty_io.c:tty_write
  - drivers/tty/tty_io.c:tty_read
```
**Symbols:**

```
ffffffff81648890-ffffffff816488b2: tty_paranoia_check (STB_LOCAL)
ffffffff8164c126-ffffffff8164c182: tty_paranoia_check.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

```c
int tty_paranoia_check(struct tty_struct *tty, struct inode *inode, const char *routine);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff8162c576)
Location: drivers/tty/tty_io.c:262
Inline: True
Direct callers:
  - drivers/tty/tty_io.c:tty_compat_ioctl
  - drivers/tty/tty_io.c:tty_compat_ioctl
  - drivers/tty/tty_io.c:tty_ioctl
  - drivers/tty/tty_io.c:__tty_fasync
  - drivers/tty/tty_io.c:tty_poll
  - drivers/tty/tty_io.c:tty_release
  - drivers/tty/tty_io.c:tty_write
  - drivers/tty/tty_io.c:tty_read
```
**Symbols:**

```
ffffffff81628cf0-ffffffff81628d12: tty_paranoia_check (STB_LOCAL)
ffffffff8162c576-ffffffff8162c5d2: tty_paranoia_check.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

```c
int tty_paranoia_check(struct tty_struct *tty, struct inode *inode, const char *routine);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff8167a4e6)
Location: drivers/tty/tty_io.c:262
Inline: True
Direct callers:
  - drivers/tty/tty_io.c:tty_compat_ioctl
  - drivers/tty/tty_io.c:tty_compat_ioctl
  - drivers/tty/tty_io.c:tty_ioctl
  - drivers/tty/tty_io.c:__tty_fasync
  - drivers/tty/tty_io.c:tty_poll
  - drivers/tty/tty_io.c:tty_release
  - drivers/tty/tty_io.c:tty_write
  - drivers/tty/tty_io.c:tty_read
```
**Symbols:**

```
ffffffff81676c50-ffffffff81676c72: tty_paranoia_check (STB_LOCAL)
ffffffff8167a4e6-ffffffff8167a542: tty_paranoia_check.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

```c
int tty_paranoia_check(struct tty_struct *tty, struct inode *inode, const char *routine);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff81694b8e)
Location: drivers/tty/tty_io.c:262
Inline: True
Direct callers:
  - drivers/tty/tty_io.c:tty_compat_ioctl
  - drivers/tty/tty_io.c:tty_compat_ioctl
  - drivers/tty/tty_io.c:tty_ioctl
  - drivers/tty/tty_io.c:__tty_fasync
  - drivers/tty/tty_io.c:tty_poll
  - drivers/tty/tty_io.c:tty_release
  - drivers/tty/tty_io.c:tty_write
  - drivers/tty/tty_io.c:tty_read
```
**Symbols:**

```
ffffffff81691370-ffffffff81691392: tty_paranoia_check (STB_LOCAL)
ffffffff81694b8e-ffffffff81694bea: tty_paranoia_check.cold (STB_LOCAL)
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
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
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
