# Function: <code>pty_set_lock</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
int pty_set_lock(struct tty_struct *tty, int *arg);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/pty.c (ffffffff814ec4a0)
Location: drivers/tty/pty.c:152
Inline: True
```
**Symbols:**

```
ffffffff814ec4a0-ffffffff814ec4d8: pty_set_lock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
int pty_set_lock(struct tty_struct *tty, int *arg);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/pty.c (ffffffff8153d4f0)
Location: drivers/tty/pty.c:152
Inline: True
```
**Symbols:**

```
ffffffff8153d4f0-ffffffff8153d528: pty_set_lock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
int pty_set_lock(struct tty_struct *tty, int *arg);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/pty.c (ffffffff81569b40)
Location: drivers/tty/pty.c:152
Inline: True
```
**Symbols:**

```
ffffffff81569b40-ffffffff81569b78: pty_set_lock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int pty_set_lock(struct tty_struct *tty, int *arg);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/pty.c (ffffffff8157e220)
Location: drivers/tty/pty.c:155
Inline: True
```
**Symbols:**

```
ffffffff8157e220-ffffffff8157e258: pty_set_lock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int pty_set_lock(struct tty_struct *tty, int *arg);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/pty.c (ffffffff815e2aa0)
Location: drivers/tty/pty.c:156
Inline: True
```
**Symbols:**

```
ffffffff815e2aa0-ffffffff815e2ad8: pty_set_lock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
int pty_set_lock(struct tty_struct *tty, int *arg);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/pty.c (ffffffff8161bd70)
Location: drivers/tty/pty.c:159
Inline: True
```
**Symbols:**

```
ffffffff8161bd70-ffffffff8161bda8: pty_set_lock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int pty_set_lock(struct tty_struct *tty, int *arg);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/pty.c (ffffffff81638ff0)
Location: drivers/tty/pty.c:160
Inline: True
```
**Symbols:**

```
ffffffff81638ff0-ffffffff81639024: pty_set_lock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
int pty_set_lock(struct tty_struct *tty, int *arg);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/pty.c (ffffffff8166d2d0)
Location: drivers/tty/pty.c:160
Inline: True
Direct callers:
  - drivers/tty/pty.c:pty_unix98_ioctl
  - drivers/tty/pty.c:pty_bsd_ioctl
```
**Symbols:**

```
ffffffff8166d2d0-ffffffff8166d304: pty_set_lock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int pty_set_lock(struct tty_struct *tty, int *arg);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/pty.c (ffffffff8168f940)
Location: drivers/tty/pty.c:160
Inline: True
Direct callers:
  - drivers/tty/pty.c:pty_unix98_ioctl
  - drivers/tty/pty.c:pty_bsd_ioctl
```
**Symbols:**

```
ffffffff8168f940-ffffffff8168f974: pty_set_lock (STB_LOCAL)
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
In drivers/tty/pty.c (ffffffff817428af)
Location: drivers/tty/pty.c:160
Inline: True
Inline callers:
  - drivers/tty/pty.c:pty_unix98_ioctl
  - drivers/tty/pty.c:pty_bsd_ioctl
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
In drivers/tty/pty.c (ffffffff8175e74f)
Location: drivers/tty/pty.c:160
Inline: True
Inline callers:
  - drivers/tty/pty.c:pty_unix98_ioctl
  - drivers/tty/pty.c:pty_bsd_ioctl
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int pty_set_lock(struct tty_struct *tty, int *arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/pty.c (ffffffff81741dd0)
Location: drivers/tty/pty.c:160
Inline: False
Direct callers:
  - drivers/tty/pty.c:pty_unix98_ioctl
  - drivers/tty/pty.c:pty_bsd_compat_ioctl
```
**Symbols:**

```
ffffffff81741dd0-ffffffff81741e04: pty_set_lock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int pty_set_lock(struct tty_struct *tty, int *arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/pty.c (ffffffff817c2890)
Location: drivers/tty/pty.c:147
Inline: False
Direct callers:
  - drivers/tty/pty.c:pty_unix98_ioctl
  - drivers/tty/pty.c:pty_bsd_ioctl
```
**Symbols:**

```
ffffffff817c2890-ffffffff817c28c4: pty_set_lock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int pty_set_lock(struct tty_struct *tty, int *arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/pty.c (ffffffff818fecf0)
Location: drivers/tty/pty.c:137
Inline: False
Direct callers:
  - drivers/tty/pty.c:pty_unix98_ioctl
  - drivers/tty/pty.c:pty_bsd_ioctl
```
**Symbols:**

```
ffffffff818fecf0-ffffffff818fed42: pty_set_lock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int pty_set_lock(struct tty_struct *tty, int *arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/pty.c (ffffffff81a58510)
Location: drivers/tty/pty.c:137
Inline: False
Direct callers:
  - drivers/tty/pty.c:pty_unix98_ioctl
  - drivers/tty/pty.c:pty_bsd_ioctl
```
**Symbols:**

```
ffffffff81a58510-ffffffff81a58562: pty_set_lock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int pty_set_lock(struct tty_struct *tty, int *arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/pty.c (ffffffff81aa2b30)
Location: drivers/tty/pty.c:137
Inline: False
Direct callers:
  - drivers/tty/pty.c:pty_unix98_ioctl
  - drivers/tty/pty.c:pty_bsd_ioctl
```
**Symbols:**

```
ffffffff81aa2b30-ffffffff81aa2b82: pty_set_lock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int pty_set_lock(struct tty_struct *tty, int *arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/pty.c (ffffffff81af54a0)
Location: drivers/tty/pty.c:137
Inline: False
Direct callers:
  - drivers/tty/pty.c:pty_unix98_ioctl
  - drivers/tty/pty.c:pty_bsd_ioctl
```
**Symbols:**

```
ffffffff81af54a0-ffffffff81af54f2: pty_set_lock (STB_LOCAL)
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
int pty_set_lock(struct tty_struct *tty, int *arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/pty.c (ffff800010862288)
Location: drivers/tty/pty.c:160
Inline: False
Direct callers:
  - drivers/tty/pty.c:pty_bsd_ioctl
```
**Symbols:**

```
ffff800010862288-ffff80001086245c: pty_set_lock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int pty_set_lock(struct tty_struct *tty, int *arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/pty.c (c09684d4)
Location: drivers/tty/pty.c:160
Inline: False
Direct callers:
  - drivers/tty/pty.c:pty_bsd_ioctl
```
**Symbols:**

```
c09684d4-c096855c: pty_set_lock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int pty_set_lock(struct tty_struct *tty, int *arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/pty.c (c000000000901550)
Location: drivers/tty/pty.c:160
Inline: False
Direct callers:
  - drivers/tty/pty.c:pty_bsd_ioctl
```
**Symbols:**

```
c000000000901550-c000000000901638: pty_set_lock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int pty_set_lock(struct tty_struct *tty, int *arg);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/pty.c (ffffffe000538bea)
Location: drivers/tty/pty.c:160
Inline: False
Direct callers:
  - drivers/tty/pty.c:pty_bsd_ioctl
```
**Symbols:**

```
ffffffe000538bea-ffffffe000538c6a: pty_set_lock (STB_LOCAL)
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
int pty_set_lock(struct tty_struct *tty, int *arg);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/pty.c (ffffffff816553c0)
Location: drivers/tty/pty.c:160
Inline: True
Direct callers:
  - drivers/tty/pty.c:pty_unix98_ioctl
  - drivers/tty/pty.c:pty_bsd_ioctl
```
**Symbols:**

```
ffffffff816553c0-ffffffff816553f4: pty_set_lock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int pty_set_lock(struct tty_struct *tty, int *arg);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/pty.c (ffffffff81635770)
Location: drivers/tty/pty.c:160
Inline: True
Direct callers:
  - drivers/tty/pty.c:pty_unix98_ioctl
  - drivers/tty/pty.c:pty_bsd_ioctl
```
**Symbols:**

```
ffffffff81635770-ffffffff816357a4: pty_set_lock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int pty_set_lock(struct tty_struct *tty, int *arg);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/pty.c (ffffffff81683780)
Location: drivers/tty/pty.c:160
Inline: True
Direct callers:
  - drivers/tty/pty.c:pty_unix98_ioctl
  - drivers/tty/pty.c:pty_bsd_ioctl
```
**Symbols:**

```
ffffffff81683780-ffffffff816837b4: pty_set_lock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int pty_set_lock(struct tty_struct *tty, int *arg);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/pty.c (ffffffff8169deb0)
Location: drivers/tty/pty.c:160
Inline: True
Direct callers:
  - drivers/tty/pty.c:pty_unix98_ioctl
  - drivers/tty/pty.c:pty_bsd_ioctl
```
**Symbols:**

```
ffffffff8169deb0-ffffffff8169dee4: pty_set_lock (STB_LOCAL)
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
