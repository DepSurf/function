# Function: <code>tty_ldisc_lock</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int tty_ldisc_lock(struct tty_struct *tty, long unsigned int timeout);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_ldisc.c (ffffffff81824320)
Location: drivers/tty/tty_ldisc.c:326
Inline: False
Direct callers:
  - drivers/tty/tty_ldisc.c:tty_set_ldisc
  - drivers/tty/tty_ldisc.c:tty_ldisc_hangup
```
**Symbols:**

```
ffffffff81824320-ffffffff8182434e: tty_ldisc_lock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int tty_ldisc_lock(struct tty_struct *tty, long unsigned int timeout);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_ldisc.c (ffffffff8153aa30)
Location: drivers/tty/tty_ldisc.c:336
Inline: False
Direct callers:
  - drivers/tty/tty_ldisc.c:tty_ldisc_hangup
  - drivers/tty/tty_ldisc.c:tty_set_ldisc
```
**Symbols:**

```
ffffffff8153aa30-ffffffff8153aa5e: tty_ldisc_lock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int tty_ldisc_lock(struct tty_struct *tty, long unsigned int timeout);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_ldisc.c (ffffffff815670f0)
Location: drivers/tty/tty_ldisc.c:336
Inline: False
Direct callers:
  - drivers/tty/tty_ldisc.c:tty_ldisc_hangup
  - drivers/tty/tty_ldisc.c:tty_set_ldisc
```
**Symbols:**

```
ffffffff815670f0-ffffffff8156711e: tty_ldisc_lock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int tty_ldisc_lock(struct tty_struct *tty, long unsigned int timeout);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_ldisc.c (ffffffff8157a6c0)
Location: drivers/tty/tty_ldisc.c:339
Inline: False
Direct callers:
  - drivers/tty/tty_ldisc.c:tty_ldisc_hangup
  - drivers/tty/tty_ldisc.c:tty_set_ldisc
```
**Symbols:**

```
ffffffff8157a6c0-ffffffff8157a6ee: tty_ldisc_lock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int tty_ldisc_lock(struct tty_struct *tty, long unsigned int timeout);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_ldisc.c (ffffffff815df510)
Location: drivers/tty/tty_ldisc.c:340
Inline: False
Direct callers:
  - drivers/tty/tty_ldisc.c:tty_ldisc_hangup
  - drivers/tty/tty_ldisc.c:tty_set_ldisc
```
**Symbols:**

```
ffffffff815df510-ffffffff815df53e: tty_ldisc_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int tty_ldisc_lock(struct tty_struct *tty, long unsigned int timeout);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_ldisc.c (ffffffff81618800)
Location: drivers/tty/tty_ldisc.c:326
Inline: False
Direct callers:
  - drivers/tty/tty_ldisc.c:tty_ldisc_hangup
  - drivers/tty/tty_ldisc.c:tty_set_ldisc
```
**Symbols:**

```
ffffffff81618800-ffffffff8161882e: tty_ldisc_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int tty_ldisc_lock(struct tty_struct *tty, long unsigned int timeout);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_ldisc.c (ffffffff816359d0)
Location: drivers/tty/tty_ldisc.c:326
Inline: False
Direct callers:
  - drivers/tty/tty_io.c:tty_reopen
  - drivers/tty/tty_ldisc.c:tty_ldisc_hangup
  - drivers/tty/tty_ldisc.c:tty_set_ldisc
```
**Symbols:**

```
ffffffff816359d0-ffffffff81635a3a: tty_ldisc_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int tty_ldisc_lock(struct tty_struct *tty, long unsigned int timeout);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_ldisc.c (ffffffff81669b60)
Location: drivers/tty/tty_ldisc.c:335
Inline: False
Direct callers:
  - drivers/tty/tty_io.c:tty_reopen
  - drivers/tty/tty_ldisc.c:tty_ldisc_hangup
  - drivers/tty/tty_ldisc.c:tty_set_ldisc
```
**Symbols:**

```
ffffffff81669b60-ffffffff81669bca: tty_ldisc_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int tty_ldisc_lock(struct tty_struct *tty, long unsigned int timeout);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_ldisc.c (ffffffff8168c290)
Location: drivers/tty/tty_ldisc.c:335
Inline: False
Direct callers:
  - drivers/tty/tty_io.c:tty_reopen
  - drivers/tty/tty_ldisc.c:tty_ldisc_hangup
  - drivers/tty/tty_ldisc.c:tty_set_ldisc
```
**Symbols:**

```
ffffffff8168c290-ffffffff8168c2fa: tty_ldisc_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int tty_ldisc_lock(struct tty_struct *tty, long unsigned int timeout);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_ldisc.c (ffffffff8173e2c0)
Location: drivers/tty/tty_ldisc.c:330
Inline: False
Direct callers:
  - drivers/tty/tty_io.c:tty_reopen
  - drivers/tty/tty_ldisc.c:tty_ldisc_hangup
  - drivers/tty/tty_ldisc.c:tty_set_ldisc
```
**Symbols:**

```
ffffffff8173e2c0-ffffffff8173e32a: tty_ldisc_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int tty_ldisc_lock(struct tty_struct *tty, long unsigned int timeout);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_ldisc.c (ffffffff8175a220)
Location: drivers/tty/tty_ldisc.c:329
Inline: False
Direct callers:
  - drivers/tty/tty_io.c:tty_reopen
  - drivers/tty/tty_ldisc.c:tty_ldisc_hangup
  - drivers/tty/tty_ldisc.c:tty_set_ldisc
```
**Symbols:**

```
ffffffff8175a220-ffffffff8175a28a: tty_ldisc_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int tty_ldisc_lock(struct tty_struct *tty, long unsigned int timeout);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_ldisc.c (ffffffff8173e0e0)
Location: drivers/tty/tty_ldisc.c:330
Inline: False
Direct callers:
  - drivers/tty/tty_io.c:tty_reopen
  - drivers/tty/tty_ldisc.c:tty_ldisc_hangup
  - drivers/tty/tty_ldisc.c:tty_set_ldisc
```
**Symbols:**

```
ffffffff8173e0e0-ffffffff8173e14a: tty_ldisc_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int tty_ldisc_lock(struct tty_struct *tty, long unsigned int timeout);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_ldisc.c (ffffffff817be6d0)
Location: drivers/tty/tty_ldisc.c:315
Inline: False
Direct callers:
  - drivers/tty/tty_io.c:tty_reopen
  - drivers/tty/tty_ldisc.c:tty_ldisc_hangup
  - drivers/tty/tty_ldisc.c:tty_set_ldisc
```
**Symbols:**

```
ffffffff817be6d0-ffffffff817be73a: tty_ldisc_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int tty_ldisc_lock(struct tty_struct *tty, long unsigned int timeout);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_ldisc.c (ffffffff818faab0)
Location: drivers/tty/tty_ldisc.c:305
Inline: False
Direct callers:
  - drivers/tty/tty_io.c:tty_reopen
  - drivers/tty/tty_ldisc.c:tty_ldisc_hangup
  - drivers/tty/tty_ldisc.c:tty_set_ldisc
```
**Symbols:**

```
ffffffff818faab0-ffffffff818fab26: tty_ldisc_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int tty_ldisc_lock(struct tty_struct *tty, long unsigned int timeout);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_ldisc.c (ffffffff81a53c40)
Location: drivers/tty/tty_ldisc.c:305
Inline: False
Direct callers:
  - drivers/tty/tty_io.c:tty_reopen
  - drivers/tty/tty_ldisc.c:tty_ldisc_hangup
  - drivers/tty/tty_ldisc.c:tty_set_ldisc
```
**Symbols:**

```
ffffffff81a53c40-ffffffff81a53cb6: tty_ldisc_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int tty_ldisc_lock(struct tty_struct *tty, long unsigned int timeout);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_ldisc.c (ffffffff81a9e050)
Location: drivers/tty/tty_ldisc.c:304
Inline: False
Direct callers:
  - drivers/tty/tty_io.c:tty_reopen
  - drivers/tty/tty_ldisc.c:tty_ldisc_hangup
  - drivers/tty/tty_ldisc.c:tty_set_ldisc
```
**Symbols:**

```
ffffffff81a9e050-ffffffff81a9e0c6: tty_ldisc_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int tty_ldisc_lock(struct tty_struct *tty, long unsigned int timeout);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_ldisc.c (ffffffff81af0b70)
Location: drivers/tty/tty_ldisc.c:304
Inline: False
Direct callers:
  - drivers/tty/tty_io.c:tty_reopen
  - drivers/tty/tty_ldisc.c:tty_ldisc_hangup
  - drivers/tty/tty_ldisc.c:tty_set_ldisc
```
**Symbols:**

```
ffffffff81af0b70-ffffffff81af0be6: tty_ldisc_lock (STB_GLOBAL)
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
int tty_ldisc_lock(struct tty_struct *tty, long unsigned int timeout);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_ldisc.c (ffff80001085c710)
Location: drivers/tty/tty_ldisc.c:335
Inline: False
Direct callers:
  - drivers/tty/tty_io.c:tty_reopen
  - drivers/tty/tty_ldisc.c:tty_ldisc_hangup
  - drivers/tty/tty_ldisc.c:tty_set_ldisc
```
**Symbols:**

```
ffff80001085c710-ffff80001085c7d4: tty_ldisc_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int tty_ldisc_lock(struct tty_struct *tty, long unsigned int timeout);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_ldisc.c (c09647dc)
Location: drivers/tty/tty_ldisc.c:335
Inline: False
Direct callers:
  - drivers/tty/tty_io.c:tty_reopen
  - drivers/tty/tty_ldisc.c:tty_ldisc_hangup
  - drivers/tty/tty_ldisc.c:tty_set_ldisc
```
**Symbols:**

```
c09647dc-c0964860: tty_ldisc_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int tty_ldisc_lock(struct tty_struct *tty, long unsigned int timeout);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_ldisc.c (c0000000008fb700)
Location: drivers/tty/tty_ldisc.c:335
Inline: False
Direct callers:
  - drivers/tty/tty_io.c:tty_reopen
  - drivers/tty/tty_ldisc.c:tty_ldisc_hangup
  - drivers/tty/tty_ldisc.c:tty_set_ldisc
```
**Symbols:**

```
c0000000008fb700-c0000000008fb7d8: tty_ldisc_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int tty_ldisc_lock(struct tty_struct *tty, long unsigned int timeout);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_ldisc.c (ffffffe0005358de)
Location: drivers/tty/tty_ldisc.c:335
Inline: False
Direct callers:
  - drivers/tty/tty_io.c:tty_reopen
  - drivers/tty/tty_ldisc.c:tty_ldisc_hangup
  - drivers/tty/tty_ldisc.c:tty_set_ldisc
```
**Symbols:**

```
ffffffe0005358de-ffffffe000535956: tty_ldisc_lock (STB_GLOBAL)
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
int tty_ldisc_lock(struct tty_struct *tty, long unsigned int timeout);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_ldisc.c (ffffffff81651d10)
Location: drivers/tty/tty_ldisc.c:335
Inline: False
Direct callers:
  - drivers/tty/tty_io.c:tty_reopen
  - drivers/tty/tty_ldisc.c:tty_ldisc_hangup
  - drivers/tty/tty_ldisc.c:tty_set_ldisc
```
**Symbols:**

```
ffffffff81651d10-ffffffff81651d7a: tty_ldisc_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int tty_ldisc_lock(struct tty_struct *tty, long unsigned int timeout);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_ldisc.c (ffffffff81632150)
Location: drivers/tty/tty_ldisc.c:335
Inline: False
Direct callers:
  - drivers/tty/tty_io.c:tty_reopen
  - drivers/tty/tty_ldisc.c:tty_ldisc_hangup
  - drivers/tty/tty_ldisc.c:tty_set_ldisc
```
**Symbols:**

```
ffffffff81632150-ffffffff816321ba: tty_ldisc_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int tty_ldisc_lock(struct tty_struct *tty, long unsigned int timeout);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_ldisc.c (ffffffff816800d0)
Location: drivers/tty/tty_ldisc.c:335
Inline: False
Direct callers:
  - drivers/tty/tty_io.c:tty_reopen
  - drivers/tty/tty_ldisc.c:tty_ldisc_hangup
  - drivers/tty/tty_ldisc.c:tty_set_ldisc
```
**Symbols:**

```
ffffffff816800d0-ffffffff8168013a: tty_ldisc_lock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int tty_ldisc_lock(struct tty_struct *tty, long unsigned int timeout);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_ldisc.c (ffffffff8169a720)
Location: drivers/tty/tty_ldisc.c:335
Inline: False
Direct callers:
  - drivers/tty/tty_io.c:tty_reopen
  - drivers/tty/tty_ldisc.c:tty_ldisc_hangup
  - drivers/tty/tty_ldisc.c:tty_set_ldisc
```
**Symbols:**

```
ffffffff8169a720-ffffffff8169a78a: tty_ldisc_lock (STB_GLOBAL)
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
