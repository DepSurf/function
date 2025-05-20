# Function: <code>__f_setown</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
void __f_setown(struct file *filp, struct pid *pid, enum pid_type type, int force);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fcntl.c (ffffffff8121ebb0)
Location: fs/fcntl.c:101
Inline: True
Inline callers:
  - fs/fcntl.c:f_setown
  - fs/fcntl.c:SyS_fcntl
Direct callers:
  - fs/notify/dnotify/dnotify.c:fcntl_dirnotify
  - fs/locks.c:lease_setup
  - drivers/tty/tty_io.c:__tty_fasync
  - drivers/net/tun.c:tun_chr_fasync
```
**Symbols:**

```
ffffffff8121ebb0-ffffffff8121ebeb: __f_setown (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void __f_setown(struct file *filp, struct pid *pid, enum pid_type type, int force);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fcntl.c (ffffffff81246b58)
Location: fs/fcntl.c:105
Inline: True
Inline callers:
  - fs/fcntl.c:SyS_fcntl
  - fs/fcntl.c:f_setown
Direct callers:
  - fs/notify/dnotify/dnotify.c:fcntl_dirnotify
  - fs/locks.c:lease_setup
  - drivers/tty/tty_io.c:__tty_fasync
  - drivers/net/tun.c:tun_chr_fasync
```
**Symbols:**

```
ffffffff81246540-ffffffff8124657b: __f_setown (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void __f_setown(struct file *filp, struct pid *pid, enum pid_type type, int force);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fcntl.c (ffffffff81259b45)
Location: fs/fcntl.c:105
Inline: True
Inline callers:
  - fs/fcntl.c:SyS_fcntl
  - fs/fcntl.c:f_setown
Direct callers:
  - fs/notify/dnotify/dnotify.c:fcntl_dirnotify
  - fs/locks.c:lease_setup
  - drivers/tty/tty_io.c:__tty_fasync
  - drivers/net/tun.c:tun_chr_fasync
```
**Symbols:**

```
ffffffff81259530-ffffffff8125956b: __f_setown (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void __f_setown(struct file *filp, struct pid *pid, enum pid_type type, int force);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fcntl.c (ffffffff81265cc2)
Location: fs/fcntl.c:107
Inline: True
Inline callers:
  - fs/fcntl.c:do_fcntl
  - fs/fcntl.c:f_setown
Direct callers:
  - fs/notify/dnotify/dnotify.c:fcntl_dirnotify
  - fs/locks.c:lease_setup
  - drivers/tty/tty_io.c:__tty_fasync
  - drivers/net/tun.c:tun_chr_fasync
```
**Symbols:**

```
ffffffff81265610-ffffffff8126564b: __f_setown (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void __f_setown(struct file *filp, struct pid *pid, enum pid_type type, int force);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fcntl.c (ffffffff812885a2)
Location: fs/fcntl.c:108
Inline: True
Inline callers:
  - fs/fcntl.c:do_fcntl
  - fs/fcntl.c:f_setown
Direct callers:
  - fs/notify/dnotify/dnotify.c:fcntl_dirnotify
  - fs/locks.c:lease_setup
  - drivers/tty/tty_io.c:__tty_fasync
  - drivers/net/tun.c:tun_chr_fasync
```
**Symbols:**

```
ffffffff81288220-ffffffff8128825b: __f_setown (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void __f_setown(struct file *filp, struct pid *pid, enum pid_type type, int force);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fcntl.c (ffffffff812ae92c)
Location: fs/fcntl.c:108
Inline: True
Inline callers:
  - fs/fcntl.c:do_fcntl
  - fs/fcntl.c:f_setown
Direct callers:
  - fs/notify/dnotify/dnotify.c:fcntl_dirnotify
  - fs/locks.c:lease_setup
  - drivers/tty/tty_io.c:__tty_fasync
  - drivers/net/tun.c:tun_chr_fasync
```
**Symbols:**

```
ffffffff812ae570-ffffffff812ae5ab: __f_setown (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void __f_setown(struct file *filp, struct pid *pid, enum pid_type type, int force);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fcntl.c (ffffffff812c3a1c)
Location: fs/fcntl.c:108
Inline: True
Inline callers:
  - fs/fcntl.c:do_fcntl
  - fs/fcntl.c:f_setown
Direct callers:
  - fs/notify/dnotify/dnotify.c:fcntl_dirnotify
  - fs/locks.c:lease_setup
  - drivers/tty/tty_io.c:__tty_fasync
  - drivers/net/tun.c:tun_chr_fasync
```
**Symbols:**

```
ffffffff812c3660-ffffffff812c369b: __f_setown (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void __f_setown(struct file *filp, struct pid *pid, enum pid_type type, int force);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fcntl.c (ffffffff812e068e)
Location: fs/fcntl.c:108
Inline: True
Inline callers:
  - fs/fcntl.c:do_fcntl
  - fs/fcntl.c:f_setown
Direct callers:
  - fs/notify/dnotify/dnotify.c:fcntl_dirnotify
  - fs/locks.c:lease_setup
  - drivers/tty/tty_io.c:__tty_fasync
  - drivers/net/tun.c:tun_chr_fasync
```
**Symbols:**

```
ffffffff812e0080-ffffffff812e00bd: __f_setown (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void __f_setown(struct file *filp, struct pid *pid, enum pid_type type, int force);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fcntl.c (ffffffff812f2211)
Location: fs/fcntl.c:108
Inline: True
Inline callers:
  - fs/fcntl.c:do_fcntl
  - fs/fcntl.c:f_setown
Direct callers:
  - fs/notify/dnotify/dnotify.c:fcntl_dirnotify
  - fs/locks.c:lease_setup
  - drivers/tty/tty_io.c:__tty_fasync
  - drivers/net/tun.c:tun_chr_fasync
```
**Symbols:**

```
ffffffff812f1b20-ffffffff812f1b5d: __f_setown (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void __f_setown(struct file *filp, struct pid *pid, enum pid_type type, int force);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fcntl.c (ffffffff8132a366)
Location: fs/fcntl.c:108
Inline: True
Inline callers:
  - fs/fcntl.c:do_fcntl
  - fs/fcntl.c:f_setown
Direct callers:
  - fs/notify/dnotify/dnotify.c:fcntl_dirnotify
  - fs/locks.c:lease_setup
  - drivers/tty/tty_io.c:tty_fasync
  - drivers/net/tun.c:tun_chr_fasync
```
**Symbols:**

```
ffffffff81329d90-ffffffff81329dcd: __f_setown (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void __f_setown(struct file *filp, struct pid *pid, enum pid_type type, int force);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fcntl.c (ffffffff813358d6)
Location: fs/fcntl.c:108
Inline: True
Inline callers:
  - fs/fcntl.c:do_fcntl
  - fs/fcntl.c:f_setown
Direct callers:
  - fs/notify/dnotify/dnotify.c:fcntl_dirnotify
  - fs/locks.c:lease_setup
  - drivers/tty/tty_io.c:tty_fasync
  - drivers/net/tun.c:tun_chr_fasync
```
**Symbols:**

```
ffffffff813352f0-ffffffff8133532d: __f_setown (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void __f_setown(struct file *filp, struct pid *pid, enum pid_type type, int force);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fcntl.c (ffffffff8133bac6)
Location: fs/fcntl.c:106
Inline: True
Inline callers:
  - fs/fcntl.c:do_fcntl
  - fs/fcntl.c:f_setown
Direct callers:
  - fs/notify/dnotify/dnotify.c:fcntl_dirnotify
  - fs/locks.c:lease_setup
  - drivers/tty/tty_io.c:tty_fasync
  - drivers/net/tun.c:tun_chr_fasync
```
**Symbols:**

```
ffffffff8133b3c0-ffffffff8133b3fd: __f_setown (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void __f_setown(struct file *filp, struct pid *pid, enum pid_type type, int force);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fcntl.c (ffffffff81389744)
Location: fs/fcntl.c:109
Inline: True
Inline callers:
  - fs/fcntl.c:do_fcntl
  - fs/fcntl.c:f_setown
Direct callers:
  - fs/notify/dnotify/dnotify.c:fcntl_dirnotify
  - fs/locks.c:lease_setup
  - drivers/tty/tty_io.c:tty_fasync
  - drivers/net/tun.c:tun_chr_fasync
```
**Symbols:**

```
ffffffff81389000-ffffffff8138903d: __f_setown (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void __f_setown(struct file *filp, struct pid *pid, enum pid_type type, int force);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fcntl.c (ffffffff8140a6ea)
Location: fs/fcntl.c:105
Inline: True
Inline callers:
  - fs/fcntl.c:do_fcntl
  - fs/fcntl.c:f_setown
Direct callers:
  - fs/notify/dnotify/dnotify.c:fcntl_dirnotify
  - fs/locks.c:lease_setup
  - drivers/tty/tty_io.c:tty_fasync
  - drivers/net/tun.c:tun_chr_fasync
```
**Symbols:**

```
ffffffff81409f50-ffffffff81409f97: __f_setown (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void __f_setown(struct file *filp, struct pid *pid, enum pid_type type, int force);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fcntl.c (ffffffff81494fc2)
Location: fs/fcntl.c:106
Inline: True
Inline callers:
  - fs/fcntl.c:do_fcntl
  - fs/fcntl.c:f_setown
Direct callers:
  - fs/notify/dnotify/dnotify.c:fcntl_dirnotify
  - fs/locks.c:lease_setup
  - drivers/tty/tty_io.c:__tty_fasync
  - drivers/net/tun.c:tun_chr_fasync
```
**Symbols:**

```
ffffffff814946d0-ffffffff81494717: __f_setown (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void __f_setown(struct file *filp, struct pid *pid, enum pid_type type, int force);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fcntl.c (ffffffff814ca00b)
Location: fs/fcntl.c:107
Inline: True
Inline callers:
  - fs/fcntl.c:do_fcntl
  - fs/fcntl.c:f_setown
Direct callers:
  - fs/notify/dnotify/dnotify.c:fcntl_dirnotify
  - fs/locks.c:lease_setup
  - drivers/tty/tty_io.c:__tty_fasync
  - drivers/net/tun.c:tun_chr_fasync
```
**Symbols:**

```
ffffffff814c9730-ffffffff814c9777: __f_setown (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void __f_setown(struct file *filp, struct pid *pid, enum pid_type type, int force);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fcntl.c (ffffffff814fc8d9)
Location: fs/fcntl.c:107
Inline: True
Inline callers:
  - fs/fcntl.c:do_fcntl
  - fs/fcntl.c:f_setown
Direct callers:
  - fs/notify/dnotify/dnotify.c:fcntl_dirnotify
  - fs/locks.c:lease_setup
  - drivers/tty/tty_io.c:__tty_fasync
  - drivers/net/tun.c:tun_chr_fasync
```
**Symbols:**

```
ffffffff814fbff0-ffffffff814fc037: __f_setown (STB_GLOBAL)
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
void __f_setown(struct file *filp, struct pid *pid, enum pid_type type, int force);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fcntl.c (ffff80001039c020)
Location: fs/fcntl.c:108
Inline: True
Inline callers:
  - fs/fcntl.c:do_fcntl
  - fs/fcntl.c:f_setown
Direct callers:
  - fs/notify/dnotify/dnotify.c:fcntl_dirnotify
  - fs/locks.c:lease_setup
  - drivers/tty/tty_io.c:__tty_fasync
  - drivers/net/tun.c:tun_chr_fasync
```
**Symbols:**

```
ffff80001039b510-ffff80001039b564: __f_setown (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void __f_setown(struct file *filp, struct pid *pid, enum pid_type type, int force);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fcntl.c (c0581e9c)
Location: fs/fcntl.c:108
Inline: True
Inline callers:
  - fs/fcntl.c:do_fcntl
  - fs/fcntl.c:f_setown
Direct callers:
  - fs/notify/dnotify/dnotify.c:fcntl_dirnotify
  - fs/locks.c:lease_setup
  - drivers/tty/tty_io.c:__tty_fasync
  - drivers/net/tun.c:tun_chr_fasync
```
**Symbols:**

```
c0581758-c0581798: __f_setown (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void __f_setown(struct file *filp, struct pid *pid, enum pid_type type, int force);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fcntl.c (c000000000496e6c)
Location: fs/fcntl.c:108
Inline: True
Inline callers:
  - fs/fcntl.c:do_fcntl
  - fs/fcntl.c:f_setown
Direct callers:
  - fs/notify/dnotify/dnotify.c:fcntl_dirnotify
  - fs/locks.c:lease_setup
  - fs/locks.c:lease_setup
  - drivers/tty/tty_io.c:__tty_fasync
  - drivers/net/tun.c:tun_chr_fasync
```
**Symbols:**

```
c000000000496370-c0000000004963cc: __f_setown (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void __f_setown(struct file *filp, struct pid *pid, enum pid_type type, int force);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fcntl.c (ffffffe000268c5e)
Location: fs/fcntl.c:108
Inline: True
Inline callers:
  - fs/fcntl.c:__se_sys_fcntl
  - fs/fcntl.c:f_setown
Direct callers:
  - fs/notify/dnotify/dnotify.c:fcntl_dirnotify
  - fs/locks.c:lease_setup
  - drivers/tty/tty_io.c:__tty_fasync
  - drivers/net/tun.c:tun_chr_fasync
```
**Symbols:**

```
ffffffe000268630-ffffffe00026867c: __f_setown (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
void __f_setown(struct file *filp, struct pid *pid, enum pid_type type, int force);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fcntl.c (ffffffff812ea7f1)
Location: fs/fcntl.c:108
Inline: True
Inline callers:
  - fs/fcntl.c:do_fcntl
  - fs/fcntl.c:f_setown
Direct callers:
  - fs/notify/dnotify/dnotify.c:fcntl_dirnotify
  - fs/locks.c:lease_setup
  - drivers/tty/tty_io.c:__tty_fasync
  - drivers/net/tun.c:tun_chr_fasync
```
**Symbols:**

```
ffffffff812ea100-ffffffff812ea13d: __f_setown (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void __f_setown(struct file *filp, struct pid *pid, enum pid_type type, int force);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fcntl.c (ffffffff812db431)
Location: fs/fcntl.c:108
Inline: True
Inline callers:
  - fs/fcntl.c:do_fcntl
  - fs/fcntl.c:f_setown
Direct callers:
  - fs/notify/dnotify/dnotify.c:fcntl_dirnotify
  - fs/locks.c:lease_setup
  - drivers/tty/tty_io.c:__tty_fasync
  - drivers/net/tun.c:tun_chr_fasync
```
**Symbols:**

```
ffffffff812daad0-ffffffff812dab0d: __f_setown (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void __f_setown(struct file *filp, struct pid *pid, enum pid_type type, int force);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fcntl.c (ffffffff812e8601)
Location: fs/fcntl.c:108
Inline: True
Inline callers:
  - fs/fcntl.c:do_fcntl
  - fs/fcntl.c:f_setown
Direct callers:
  - fs/notify/dnotify/dnotify.c:fcntl_dirnotify
  - fs/locks.c:lease_setup
  - drivers/tty/tty_io.c:__tty_fasync
  - drivers/net/tun.c:tun_chr_fasync
```
**Symbols:**

```
ffffffff812e7f10-ffffffff812e7f4d: __f_setown (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void __f_setown(struct file *filp, struct pid *pid, enum pid_type type, int force);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In fs/fcntl.c (ffffffff812f95ba)
Location: fs/fcntl.c:108
Inline: True
Inline callers:
  - fs/fcntl.c:do_fcntl
  - fs/fcntl.c:f_setown
Direct callers:
  - fs/notify/dnotify/dnotify.c:fcntl_dirnotify
  - fs/locks.c:lease_setup
  - drivers/tty/tty_io.c:__tty_fasync
  - drivers/net/tun.c:tun_chr_fasync
```
**Symbols:**

```
ffffffff812f8d80-ffffffff812f8dbd: __f_setown (STB_GLOBAL)
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
