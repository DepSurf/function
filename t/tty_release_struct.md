# Function: <code>tty_release_struct</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
In <code>4.8</code>: Absent ⚠️
</li>
<li>
In <code>4.10</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void tty_release_struct(struct tty_struct *tty, int idx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff81572170)
Location: drivers/tty/tty_io.c:1523
Inline: False
Direct callers:
  - drivers/tty/tty_io.c:tty_release
```
**Symbols:**

```
ffffffff81572170-ffffffff815721f2: tty_release_struct (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void tty_release_struct(struct tty_struct *tty, int idx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff815d8b30)
Location: drivers/tty/tty_io.c:1575
Inline: False
Direct callers:
  - drivers/tty/tty_io.c:tty_release
  - drivers/tty/serdev/serdev-ttyport.c:ttyport_close
  - drivers/tty/serdev/serdev-ttyport.c:ttyport_open
```
**Symbols:**

```
ffffffff815d8b30-ffffffff815d8b77: tty_release_struct (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void tty_release_struct(struct tty_struct *tty, int idx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff81610f80)
Location: drivers/tty/tty_io.c:1593
Inline: False
Direct callers:
  - drivers/tty/tty_io.c:tty_release
  - drivers/tty/serdev/serdev-ttyport.c:ttyport_close
  - drivers/tty/serdev/serdev-ttyport.c:ttyport_open
```
**Symbols:**

```
ffffffff81610f80-ffffffff81610fc7: tty_release_struct (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void tty_release_struct(struct tty_struct *tty, int idx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff8162dfe0)
Location: drivers/tty/tty_io.c:1605
Inline: False
Direct callers:
  - drivers/tty/tty_io.c:tty_release
  - drivers/tty/serdev/serdev-ttyport.c:ttyport_close
  - drivers/tty/serdev/serdev-ttyport.c:ttyport_open
```
**Symbols:**

```
ffffffff8162dfe0-ffffffff8162e027: tty_release_struct (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void tty_release_struct(struct tty_struct *tty, int idx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff81661bb0)
Location: drivers/tty/tty_io.c:1607
Inline: False
Direct callers:
  - drivers/tty/tty_io.c:tty_release
  - drivers/tty/serdev/serdev-ttyport.c:ttyport_close
  - drivers/tty/serdev/serdev-ttyport.c:ttyport_open
```
**Symbols:**

```
ffffffff81661bb0-ffffffff81661bf9: tty_release_struct (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void tty_release_struct(struct tty_struct *tty, int idx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff81684220)
Location: drivers/tty/tty_io.c:1607
Inline: False
Direct callers:
  - drivers/tty/tty_io.c:tty_release
  - drivers/tty/serdev/serdev-ttyport.c:ttyport_close
  - drivers/tty/serdev/serdev-ttyport.c:ttyport_open
```
**Symbols:**

```
ffffffff81684220-ffffffff81684269: tty_release_struct (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void tty_release_struct(struct tty_struct *tty, int idx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff81735690)
Location: drivers/tty/tty_io.c:1609
Inline: False
Direct callers:
  - drivers/tty/tty_io.c:tty_release
  - drivers/tty/serdev/serdev-ttyport.c:ttyport_close
  - drivers/tty/serdev/serdev-ttyport.c:ttyport_open
```
**Symbols:**

```
ffffffff81735690-ffffffff81735718: tty_release_struct (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void tty_release_struct(struct tty_struct *tty, int idx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff81751860)
Location: drivers/tty/tty_io.c:1693
Inline: False
Direct callers:
  - drivers/tty/tty_io.c:tty_release
  - drivers/tty/serdev/serdev-ttyport.c:ttyport_close
  - drivers/tty/serdev/serdev-ttyport.c:ttyport_open
```
**Symbols:**

```
ffffffff81751860-ffffffff817518e8: tty_release_struct (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void tty_release_struct(struct tty_struct *tty, int idx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff817356f0)
Location: drivers/tty/tty_io.c:1708
Inline: False
Direct callers:
  - drivers/tty/tty_io.c:tty_release
  - drivers/tty/serdev/serdev-ttyport.c:ttyport_close
  - drivers/tty/serdev/serdev-ttyport.c:ttyport_open
```
**Symbols:**

```
ffffffff817356f0-ffffffff81735778: tty_release_struct (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void tty_release_struct(struct tty_struct *tty, int idx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff817b60b0)
Location: drivers/tty/tty_io.c:1701
Inline: False
Direct callers:
  - drivers/tty/tty_io.c:tty_release
  - drivers/tty/serdev/serdev-ttyport.c:ttyport_close
  - drivers/tty/serdev/serdev-ttyport.c:ttyport_open
```
**Symbols:**

```
ffffffff817b60b0-ffffffff817b6138: tty_release_struct (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void tty_release_struct(struct tty_struct *tty, int idx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff818f2090)
Location: drivers/tty/tty_io.c:1689
Inline: False
Direct callers:
  - drivers/tty/tty_io.c:tty_release
  - drivers/tty/serdev/serdev-ttyport.c:ttyport_close
  - drivers/tty/serdev/serdev-ttyport.c:ttyport_open
```
**Symbols:**

```
ffffffff818f2090-ffffffff818f211c: tty_release_struct (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void tty_release_struct(struct tty_struct *tty, int idx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff81a49fc0)
Location: drivers/tty/tty_io.c:1684
Inline: False
Direct callers:
  - drivers/tty/tty_io.c:tty_release
  - drivers/tty/serdev/serdev-ttyport.c:ttyport_close
  - drivers/tty/serdev/serdev-ttyport.c:ttyport_open
```
**Symbols:**

```
ffffffff81a49fc0-ffffffff81a4a04c: tty_release_struct (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void tty_release_struct(struct tty_struct *tty, int idx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff81a93f80)
Location: drivers/tty/tty_io.c:1693
Inline: False
Direct callers:
  - drivers/tty/tty_io.c:tty_release
  - drivers/tty/serdev/serdev-ttyport.c:ttyport_close
  - drivers/tty/serdev/serdev-ttyport.c:ttyport_open
```
**Symbols:**

```
ffffffff81a93f80-ffffffff81a9400c: tty_release_struct (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void tty_release_struct(struct tty_struct *tty, int idx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff81ae69f0)
Location: drivers/tty/tty_io.c:1691
Inline: False
Direct callers:
  - drivers/tty/tty_io.c:tty_release
  - drivers/tty/serdev/serdev-ttyport.c:ttyport_close
  - drivers/tty/serdev/serdev-ttyport.c:ttyport_open
```
**Symbols:**

```
ffffffff81ae69f0-ffffffff81ae6a7c: tty_release_struct (STB_GLOBAL)
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
void tty_release_struct(struct tty_struct *tty, int idx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffff80001084f460)
Location: drivers/tty/tty_io.c:1607
Inline: False
Direct callers:
  - drivers/tty/tty_io.c:tty_release
  - drivers/tty/serdev/serdev-ttyport.c:ttyport_close
  - drivers/tty/serdev/serdev-ttyport.c:ttyport_open
```
**Symbols:**

```
ffff80001084f460-ffff80001084f4c4: tty_release_struct (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void tty_release_struct(struct tty_struct *tty, int idx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (c095b7d0)
Location: drivers/tty/tty_io.c:1607
Inline: False
Direct callers:
  - drivers/tty/tty_io.c:tty_release
  - drivers/tty/serdev/serdev-ttyport.c:ttyport_close
  - drivers/tty/serdev/serdev-ttyport.c:ttyport_open
```
**Symbols:**

```
c095b7d0-c095b820: tty_release_struct (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void tty_release_struct(struct tty_struct *tty, int idx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (c0000000008edee0)
Location: drivers/tty/tty_io.c:1607
Inline: False
Direct callers:
  - drivers/tty/tty_io.c:tty_release
  - drivers/tty/serdev/serdev-ttyport.c:ttyport_close
  - drivers/tty/serdev/serdev-ttyport.c:ttyport_open
```
**Symbols:**

```
c0000000008edee0-c0000000008edf60: tty_release_struct (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void tty_release_struct(struct tty_struct *tty, int idx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffe00052d2d8)
Location: drivers/tty/tty_io.c:1607
Inline: False
Direct callers:
  - drivers/tty/tty_io.c:tty_release
  - drivers/tty/serdev/serdev-ttyport.c:ttyport_close
  - drivers/tty/serdev/serdev-ttyport.c:ttyport_open
```
**Symbols:**

```
ffffffe00052d2d8-ffffffe00052d33e: tty_release_struct (STB_GLOBAL)
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
void tty_release_struct(struct tty_struct *tty, int idx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff81649ca0)
Location: drivers/tty/tty_io.c:1607
Inline: False
Direct callers:
  - drivers/tty/tty_io.c:tty_release
  - drivers/tty/serdev/serdev-ttyport.c:ttyport_close
  - drivers/tty/serdev/serdev-ttyport.c:ttyport_open
```
**Symbols:**

```
ffffffff81649ca0-ffffffff81649ce9: tty_release_struct (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void tty_release_struct(struct tty_struct *tty, int idx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff8162a0f0)
Location: drivers/tty/tty_io.c:1607
Inline: False
Direct callers:
  - drivers/tty/tty_io.c:tty_release
```
**Symbols:**

```
ffffffff8162a0f0-ffffffff8162a139: tty_release_struct (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void tty_release_struct(struct tty_struct *tty, int idx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff81678060)
Location: drivers/tty/tty_io.c:1607
Inline: False
Direct callers:
  - drivers/tty/tty_io.c:tty_release
  - drivers/tty/serdev/serdev-ttyport.c:ttyport_close
  - drivers/tty/serdev/serdev-ttyport.c:ttyport_open
```
**Symbols:**

```
ffffffff81678060-ffffffff816780a9: tty_release_struct (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void tty_release_struct(struct tty_struct *tty, int idx);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff81693210)
Location: drivers/tty/tty_io.c:1607
Inline: False
Direct callers:
  - drivers/tty/tty_io.c:tty_release
  - drivers/tty/serdev/serdev-ttyport.c:ttyport_close
  - drivers/tty/serdev/serdev-ttyport.c:ttyport_open
```
**Symbols:**

```
ffffffff81693210-ffffffff81693259: tty_release_struct (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
