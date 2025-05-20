# Function: <code>tty_write_lock</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int tty_write_lock(struct tty_struct *tty, int ndelay);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff814df860)
Location: drivers/tty/tty_io.c:1088
Inline: False
Direct callers:
  - drivers/tty/tty_io.c:tty_write
  - drivers/tty/tty_io.c:tty_send_xchar
```
**Symbols:**

```
ffffffff814df860-ffffffff814df8a3: tty_write_lock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int tty_write_lock(struct tty_struct *tty, int ndelay);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff815308d0)
Location: drivers/tty/tty_io.c:1096
Inline: False
Direct callers:
  - drivers/tty/tty_io.c:tty_send_xchar
  - drivers/tty/tty_io.c:tty_write
```
**Symbols:**

```
ffffffff815308d0-ffffffff81530913: tty_write_lock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int tty_write_lock(struct tty_struct *tty, int ndelay);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff8155d020)
Location: drivers/tty/tty_io.c:1096
Inline: False
Direct callers:
  - drivers/tty/tty_io.c:tty_send_xchar
  - drivers/tty/tty_io.c:tty_write
```
**Symbols:**

```
ffffffff8155d020-ffffffff8155d063: tty_write_lock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int tty_write_lock(struct tty_struct *tty, int ndelay);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff81571a30)
Location: drivers/tty/tty_io.c:861
Inline: False
Direct callers:
  - drivers/tty/tty_io.c:tty_send_xchar
  - drivers/tty/tty_io.c:tty_write
```
**Symbols:**

```
ffffffff81571a30-ffffffff81571a75: tty_write_lock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int tty_write_lock(struct tty_struct *tty, int ndelay);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff815d5fa0)
Location: drivers/tty/tty_io.c:873
Inline: False
Direct callers:
  - drivers/tty/tty_io.c:tty_send_xchar
  - drivers/tty/tty_io.c:tty_write
```
**Symbols:**

```
ffffffff815d5fa0-ffffffff815d5fe5: tty_write_lock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int tty_write_lock(struct tty_struct *tty, int ndelay);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff8160efc0)
Location: drivers/tty/tty_io.c:887
Inline: False
Direct callers:
  - drivers/tty/tty_io.c:tty_send_xchar
  - drivers/tty/tty_io.c:tty_write
```
**Symbols:**

```
ffffffff8160efc0-ffffffff8160f005: tty_write_lock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int tty_write_lock(struct tty_struct *tty, int ndelay);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff8162bed0)
Location: drivers/tty/tty_io.c:883
Inline: False
Direct callers:
  - drivers/tty/tty_io.c:tty_send_xchar
  - drivers/tty/tty_io.c:tty_write
```
**Symbols:**

```
ffffffff8162bed0-ffffffff8162bf15: tty_write_lock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int tty_write_lock(struct tty_struct *tty, int ndelay);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff8165fe40)
Location: drivers/tty/tty_io.c:885
Inline: False
Direct callers:
  - drivers/tty/tty_io.c:tty_send_xchar
  - drivers/tty/tty_io.c:tty_write
```
**Symbols:**

```
ffffffff8165fe40-ffffffff8165fe83: tty_write_lock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int tty_write_lock(struct tty_struct *tty, int ndelay);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff81682490)
Location: drivers/tty/tty_io.c:885
Inline: False
Direct callers:
  - drivers/tty/tty_io.c:tty_send_xchar
  - drivers/tty/tty_io.c:tty_write
```
**Symbols:**

```
ffffffff81682490-ffffffff816824d3: tty_write_lock (STB_LOCAL)
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
In drivers/tty/tty_io.c (ffffffff81737538)
Location: drivers/tty/tty_io.c:886
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_send_xchar
  - drivers/tty/tty_io.c:do_tty_write
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
In drivers/tty/tty_io.c (ffffffff817538f8)
Location: drivers/tty/tty_io.c:949
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_send_xchar
  - drivers/tty/tty_io.c:do_tty_write
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
In drivers/tty/tty_io.c (ffffffff81737791)
Location: drivers/tty/tty_io.c:965
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_send_xchar
  - drivers/tty/tty_io.c:do_tty_write
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
In drivers/tty/tty_io.c (ffffffff817b81ed)
Location: drivers/tty/tty_io.c:959
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_send_xchar
  - drivers/tty/tty_io.c:do_tty_write
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
In drivers/tty/tty_io.c (ffffffff818f3fe8)
Location: drivers/tty/tty_io.c:948
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_send_xchar
  - drivers/tty/tty_io.c:do_tty_write
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
In drivers/tty/tty_io.c (ffffffff81a4c6a8)
Location: drivers/tty/tty_io.c:942
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_send_xchar
  - drivers/tty/tty_io.c:do_tty_write
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
int tty_write_lock(struct tty_struct *tty, int ndelay);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff81a96998)
Location: drivers/tty/tty_io.c:951
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_send_xchar
  - drivers/tty/tty_io.c:do_tty_write
Direct callers:
  - drivers/tty/tty_ioctl.c:set_termios
```
**Symbols:**

```
ffffffff81a967e0-ffffffff81a9682d: tty_write_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
int tty_write_lock(struct tty_struct *tty, bool ndelay);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff81ae9388)
Location: drivers/tty/tty_io.c:952
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_send_xchar
  - drivers/tty/tty_io.c:iterate_tty_write
Direct callers:
  - drivers/tty/tty_ioctl.c:set_termios
```
**Symbols:**

```
ffffffff81ae92a0-ffffffff81ae92ed: tty_write_lock (STB_GLOBAL)
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
int tty_write_lock(struct tty_struct *tty, int ndelay);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffff80001084e5a8)
Location: drivers/tty/tty_io.c:885
Inline: False
Direct callers:
  - drivers/tty/tty_io.c:tty_send_xchar
  - drivers/tty/tty_io.c:tty_write
```
**Symbols:**

```
ffff80001084e5a8-ffff80001084e604: tty_write_lock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int tty_write_lock(struct tty_struct *tty, int ndelay);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (c095a610)
Location: drivers/tty/tty_io.c:885
Inline: False
Direct callers:
  - drivers/tty/tty_io.c:tty_send_xchar
  - drivers/tty/tty_io.c:tty_write
```
**Symbols:**

```
c095a610-c095a670: tty_write_lock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int tty_write_lock(struct tty_struct *tty, int ndelay);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (c0000000008ed1e0)
Location: drivers/tty/tty_io.c:885
Inline: False
Direct callers:
  - drivers/tty/tty_io.c:tty_send_xchar
  - drivers/tty/tty_io.c:tty_write
```
**Symbols:**

```
c0000000008ed1e0-c0000000008ed270: tty_write_lock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int tty_write_lock(struct tty_struct *tty, int ndelay);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffe00052cbe4)
Location: drivers/tty/tty_io.c:885
Inline: False
Direct callers:
  - drivers/tty/tty_io.c:tty_send_xchar
  - drivers/tty/tty_io.c:tty_write
```
**Symbols:**

```
ffffffe00052cbe4-ffffffe00052cc36: tty_write_lock (STB_LOCAL)
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
int tty_write_lock(struct tty_struct *tty, int ndelay);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff81647f10)
Location: drivers/tty/tty_io.c:885
Inline: False
Direct callers:
  - drivers/tty/tty_io.c:tty_send_xchar
  - drivers/tty/tty_io.c:tty_write
```
**Symbols:**

```
ffffffff81647f10-ffffffff81647f53: tty_write_lock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int tty_write_lock(struct tty_struct *tty, int ndelay);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff81628370)
Location: drivers/tty/tty_io.c:885
Inline: False
Direct callers:
  - drivers/tty/tty_io.c:tty_send_xchar
  - drivers/tty/tty_io.c:tty_write
```
**Symbols:**

```
ffffffff81628370-ffffffff816283b3: tty_write_lock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int tty_write_lock(struct tty_struct *tty, int ndelay);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff816762d0)
Location: drivers/tty/tty_io.c:885
Inline: False
Direct callers:
  - drivers/tty/tty_io.c:tty_send_xchar
  - drivers/tty/tty_io.c:tty_write
```
**Symbols:**

```
ffffffff816762d0-ffffffff81676313: tty_write_lock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int tty_write_lock(struct tty_struct *tty, int ndelay);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff816909f0)
Location: drivers/tty/tty_io.c:885
Inline: False
Direct callers:
  - drivers/tty/tty_io.c:tty_send_xchar
  - drivers/tty/tty_io.c:tty_write
```
**Symbols:**

```
ffffffff816909f0-ffffffff81690a33: tty_write_lock (STB_LOCAL)
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
<details>
<summary>Changed between <code>6.5</code> and <code>6.8</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>int ndelay</code> ➡️ <code>bool ndelay</code>
</li>
</ul>
</details>
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
