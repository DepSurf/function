# Function: <code>tty_set_ldisc</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int tty_set_ldisc(struct tty_struct *tty, int ldisc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_ldisc.c (ffffffff814e9c50)
Location: drivers/tty/tty_ldisc.c:521
Inline: False
Direct callers:
  - drivers/tty/tty_io.c:tty_ioctl
```
**Symbols:**

```
ffffffff814e9c50-ffffffff814ea0ad: tty_set_ldisc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int tty_set_ldisc(struct tty_struct *tty, int disc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_ldisc.c (ffffffff8153ad00)
Location: drivers/tty/tty_ldisc.c:537
Inline: False
Direct callers:
  - drivers/tty/tty_io.c:tty_ioctl
```
**Symbols:**

```
ffffffff8153ad00-ffffffff8153afc8: tty_set_ldisc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int tty_set_ldisc(struct tty_struct *tty, int disc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_ldisc.c (ffffffff815673c0)
Location: drivers/tty/tty_ldisc.c:537
Inline: False
Direct callers:
  - drivers/tty/tty_io.c:tty_ioctl
```
**Symbols:**

```
ffffffff815673c0-ffffffff81567688: tty_set_ldisc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int tty_set_ldisc(struct tty_struct *tty, int disc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_ldisc.c (ffffffff8157a9f0)
Location: drivers/tty/tty_ldisc.c:556
Inline: False
Direct callers:
  - drivers/tty/tty_io.c:tty_ioctl
```
**Symbols:**

```
ffffffff8157a9f0-ffffffff8157ac56: tty_set_ldisc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int tty_set_ldisc(struct tty_struct *tty, int disc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_ldisc.c (ffffffff815df540)
Location: drivers/tty/tty_ldisc.c:557
Inline: False
Direct callers:
  - drivers/tty/tty_io.c:tty_ioctl
```
**Symbols:**

```
ffffffff815df540-ffffffff815df7ac: tty_set_ldisc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
int tty_set_ldisc(struct tty_struct *tty, int disc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/tty/tty_ldisc.c (0)
Location: drivers/tty/tty_ldisc.c:540
Inline: False
Direct callers:
  - drivers/tty/tty_io.c:tty_ioctl
```
**Symbols:**

```
ffffffff81618db6-ffffffff81618dc5: tty_set_ldisc.cold.6 (STB_LOCAL)
ffffffff81618830-ffffffff81618a27: tty_set_ldisc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
int tty_set_ldisc(struct tty_struct *tty, int disc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/tty/tty_ldisc.c (0)
Location: drivers/tty/tty_ldisc.c:549
Inline: False
Direct callers:
  - drivers/tty/tty_io.c:tty_ioctl
```
**Symbols:**

```
ffffffff81635fc6-ffffffff81635fd5: tty_set_ldisc.cold.6 (STB_LOCAL)
ffffffff81635a70-ffffffff81635c5e: tty_set_ldisc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int tty_set_ldisc(struct tty_struct *tty, int disc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/tty/tty_ldisc.c (0)
Location: drivers/tty/tty_ldisc.c:558
Inline: False
Direct callers:
  - drivers/tty/tty_io.c:tty_ioctl
```
**Symbols:**

```
ffffffff8166a1cd-ffffffff8166a1dc: tty_set_ldisc.cold (STB_LOCAL)
ffffffff81669c00-ffffffff81669e04: tty_set_ldisc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int tty_set_ldisc(struct tty_struct *tty, int disc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/tty/tty_ldisc.c (0)
Location: drivers/tty/tty_ldisc.c:558
Inline: False
Direct callers:
  - drivers/tty/tty_io.c:tty_ioctl
```
**Symbols:**

```
ffffffff8168c8c7-ffffffff8168c8d6: tty_set_ldisc.cold (STB_LOCAL)
ffffffff8168c330-ffffffff8168c534: tty_set_ldisc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int tty_set_ldisc(struct tty_struct *tty, int disc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/tty/tty_ldisc.c (0)
Location: drivers/tty/tty_ldisc.c:553
Inline: False
Direct callers:
  - drivers/tty/tty_io.c:tty_ioctl
```
**Symbols:**

```
ffffffff8173e927-ffffffff8173e936: tty_set_ldisc.cold (STB_LOCAL)
ffffffff8173e360-ffffffff8173e564: tty_set_ldisc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int tty_set_ldisc(struct tty_struct *tty, int disc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/tty/tty_ldisc.c (0)
Location: drivers/tty/tty_ldisc.c:552
Inline: False
Direct callers:
  - drivers/tty/tty_io.c:tty_ioctl
```
**Symbols:**

```
ffffffff81c076e9-ffffffff81c076f8: tty_set_ldisc.cold (STB_LOCAL)
ffffffff8175a2c0-ffffffff8175a4c4: tty_set_ldisc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int tty_set_ldisc(struct tty_struct *tty, int disc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/tty/tty_ldisc.c (0)
Location: drivers/tty/tty_ldisc.c:556
Inline: False
Direct callers:
  - drivers/tty/tty_io.c:tty_ioctl
```
**Symbols:**

```
ffffffff81bf9353-ffffffff81bf9362: tty_set_ldisc.cold (STB_LOCAL)
ffffffff8173e180-ffffffff8173e37e: tty_set_ldisc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int tty_set_ldisc(struct tty_struct *tty, int disc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/tty/tty_ldisc.c (0)
Location: drivers/tty/tty_ldisc.c:541
Inline: False
Direct callers:
  - drivers/tty/tty_io.c:tty_ioctl
```
**Symbols:**

```
ffffffff81cf8c88-ffffffff81cf8c97: tty_set_ldisc.cold (STB_LOCAL)
ffffffff817be770-ffffffff817be96e: tty_set_ldisc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int tty_set_ldisc(struct tty_struct *tty, int disc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/tty/tty_ldisc.c (0)
Location: drivers/tty/tty_ldisc.c:520
Inline: False
Direct callers:
  - drivers/tty/tty_io.c:tty_ioctl
```
**Symbols:**

```
ffffffff81ec0da4-ffffffff81ec0db3: tty_set_ldisc.cold (STB_LOCAL)
ffffffff818fab60-ffffffff818fad3a: tty_set_ldisc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int tty_set_ldisc(struct tty_struct *tty, int disc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_ldisc.c (ffffffff81a53d10)
Location: drivers/tty/tty_ldisc.c:520
Inline: False
Direct callers:
  - drivers/tty/tty_io.c:tty_ioctl
```
**Symbols:**

```
ffffffff81a53d10-ffffffff81a53ef4: tty_set_ldisc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int tty_set_ldisc(struct tty_struct *tty, int disc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_ldisc.c (ffffffff81a9e120)
Location: drivers/tty/tty_ldisc.c:519
Inline: False
Direct callers:
  - drivers/tty/tty_io.c:tty_ioctl
```
**Symbols:**

```
ffffffff81a9e120-ffffffff81a9e3af: tty_set_ldisc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int tty_set_ldisc(struct tty_struct *tty, int disc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_ldisc.c (ffffffff81af0c40)
Location: drivers/tty/tty_ldisc.c:519
Inline: False
Direct callers:
  - drivers/tty/tty_io.c:tty_ioctl
```
**Symbols:**

```
ffffffff81af0c40-ffffffff81af0ec6: tty_set_ldisc (STB_GLOBAL)
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
int tty_set_ldisc(struct tty_struct *tty, int disc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_ldisc.c (ffff80001085c860)
Location: drivers/tty/tty_ldisc.c:558
Inline: False
Direct callers:
  - drivers/tty/tty_io.c:tty_ioctl
```
**Symbols:**

```
ffff80001085c860-ffff80001085ca54: tty_set_ldisc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int tty_set_ldisc(struct tty_struct *tty, int disc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_ldisc.c (c09648a0)
Location: drivers/tty/tty_ldisc.c:558
Inline: False
Direct callers:
  - drivers/tty/tty_io.c:tty_ioctl
```
**Symbols:**

```
c09648a0-c0964a6c: tty_set_ldisc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int tty_set_ldisc(struct tty_struct *tty, int disc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_ldisc.c (c0000000008fb850)
Location: drivers/tty/tty_ldisc.c:558
Inline: False
Direct callers:
  - drivers/tty/tty_io.c:tty_ioctl
```
**Symbols:**

```
c0000000008fb850-c0000000008fbac0: tty_set_ldisc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int tty_set_ldisc(struct tty_struct *tty, int disc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_ldisc.c (ffffffe000535956)
Location: drivers/tty/tty_ldisc.c:558
Inline: False
Direct callers:
  - drivers/tty/tty_io.c:tty_ioctl
```
**Symbols:**

```
ffffffe000535956-ffffffe000535b1e: tty_set_ldisc (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
int tty_set_ldisc(struct tty_struct *tty, int disc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/tty/tty_ldisc.c (0)
Location: drivers/tty/tty_ldisc.c:558
Inline: False
Direct callers:
  - drivers/tty/tty_io.c:tty_ioctl
```
**Symbols:**

```
ffffffff81652347-ffffffff81652356: tty_set_ldisc.cold (STB_LOCAL)
ffffffff81651db0-ffffffff81651fb4: tty_set_ldisc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int tty_set_ldisc(struct tty_struct *tty, int disc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/tty/tty_ldisc.c (0)
Location: drivers/tty/tty_ldisc.c:558
Inline: False
Direct callers:
  - drivers/tty/tty_io.c:tty_ioctl
```
**Symbols:**

```
ffffffff81632787-ffffffff81632796: tty_set_ldisc.cold (STB_LOCAL)
ffffffff816321f0-ffffffff816323f4: tty_set_ldisc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int tty_set_ldisc(struct tty_struct *tty, int disc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/tty/tty_ldisc.c (0)
Location: drivers/tty/tty_ldisc.c:558
Inline: False
Direct callers:
  - drivers/tty/tty_io.c:tty_ioctl
```
**Symbols:**

```
ffffffff81680707-ffffffff81680716: tty_set_ldisc.cold (STB_LOCAL)
ffffffff81680170-ffffffff81680374: tty_set_ldisc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int tty_set_ldisc(struct tty_struct *tty, int disc);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/tty/tty_ldisc.c (0)
Location: drivers/tty/tty_ldisc.c:558
Inline: False
Direct callers:
  - drivers/tty/tty_io.c:tty_ioctl
```
**Symbols:**

```
ffffffff8169ad57-ffffffff8169ad66: tty_set_ldisc.cold (STB_LOCAL)
ffffffff8169a7c0-ffffffff8169a9c4: tty_set_ldisc (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Changed between <code>4.4</code> and <code>4.8</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>int disc</code>
</li>
<li>
<b>Param removed. </b>
<code>int ldisc</code>
</li>
</ul>
</details>
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
