# Function: <code>set_selection_kernel</code>

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
In <code>4.13</code>: Absent ⚠️
</li>
<li>
In <code>4.15</code>: Absent ⚠️
</li>
<li>
In <code>4.18</code>: Absent ⚠️
</li>
<li>
In <code>5.0</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int set_selection_kernel(struct tiocl_selection *v, struct tty_struct *tty);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/tty/vt/selection.c (0)
Location: drivers/tty/vt/selection.c:180
Inline: False
Direct callers:
  - drivers/tty/vt/selection.c:set_selection_user
```
**Symbols:**

```
ffffffff816729c6-ffffffff816729e1: set_selection_kernel.cold (STB_LOCAL)
ffffffff816722b0-ffffffff816728da: set_selection_kernel (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int set_selection_kernel(struct tiocl_selection *v, struct tty_struct *tty);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/selection.c (ffffffff81694ff0)
Location: drivers/tty/vt/selection.c:348
Inline: False
Direct callers:
  - drivers/tty/vt/selection.c:set_selection_user
```
**Symbols:**

```
ffffffff81694ff0-ffffffff8169503c: set_selection_kernel (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int set_selection_kernel(struct tiocl_selection *v, struct tty_struct *tty);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/selection.c (ffffffff81747bc7)
Location: drivers/tty/vt/selection.c:353
Inline: True
Inline callers:
  - drivers/tty/vt/selection.c:set_selection_user
```
**Symbols:**

```
ffffffff81747a90-ffffffff81747aef: set_selection_kernel (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int set_selection_kernel(struct tiocl_selection *v, struct tty_struct *tty);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/selection.c (ffffffff81763517)
Location: drivers/tty/vt/selection.c:353
Inline: True
Inline callers:
  - drivers/tty/vt/selection.c:set_selection_user
```
**Symbols:**

```
ffffffff817633e0-ffffffff8176343f: set_selection_kernel (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int set_selection_kernel(struct tiocl_selection *v, struct tty_struct *tty);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/selection.c (ffffffff81746f70)
Location: drivers/tty/vt/selection.c:353
Inline: False
Direct callers:
  - drivers/tty/vt/selection.c:set_selection_user
```
**Symbols:**

```
ffffffff81746f70-ffffffff817470de: set_selection_kernel (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int set_selection_kernel(struct tiocl_selection *v, struct tty_struct *tty);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/selection.c (ffffffff817c7fc0)
Location: drivers/tty/vt/selection.c:353
Inline: False
Direct callers:
  - drivers/tty/vt/selection.c:set_selection_user
```
**Symbols:**

```
ffffffff817c7fc0-ffffffff817c814c: set_selection_kernel (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int set_selection_kernel(struct tiocl_selection *v, struct tty_struct *tty);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/selection.c (ffffffff81905160)
Location: drivers/tty/vt/selection.c:353
Inline: False
Direct callers:
  - drivers/tty/vt/selection.c:set_selection_user
```
**Symbols:**

```
ffffffff81905160-ffffffff819052f4: set_selection_kernel (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int set_selection_kernel(struct tiocl_selection *v, struct tty_struct *tty);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/selection.c (ffffffff81a5f2c0)
Location: drivers/tty/vt/selection.c:354
Inline: False
Direct callers:
  - drivers/tty/vt/selection.c:set_selection_user
```
**Symbols:**

```
ffffffff81a5f2c0-ffffffff81a5f454: set_selection_kernel (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int set_selection_kernel(struct tiocl_selection *v, struct tty_struct *tty);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/selection.c (ffffffff81aa9980)
Location: drivers/tty/vt/selection.c:354
Inline: False
Direct callers:
  - drivers/tty/vt/selection.c:set_selection_user
```
**Symbols:**

```
ffffffff81aa9980-ffffffff81aa9b1f: set_selection_kernel (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int set_selection_kernel(struct tiocl_selection *v, struct tty_struct *tty);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/selection.c (ffffffff81afc440)
Location: drivers/tty/vt/selection.c:354
Inline: False
Direct callers:
  - drivers/tty/vt/selection.c:set_selection_user
```
**Symbols:**

```
ffffffff81afc440-ffffffff81afc5df: set_selection_kernel (STB_GLOBAL)
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
int set_selection_kernel(struct tiocl_selection *v, struct tty_struct *tty);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/selection.c (ffff800010869360)
Location: drivers/tty/vt/selection.c:348
Inline: False
Direct callers:
  - drivers/tty/vt/selection.c:set_selection_user
```
**Symbols:**

```
ffff800010869360-ffff8000108693c4: set_selection_kernel (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int set_selection_kernel(struct tiocl_selection *v, struct tty_struct *tty);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/selection.c (c096e654)
Location: drivers/tty/vt/selection.c:348
Inline: False
Direct callers:
  - drivers/tty/vt/selection.c:set_selection_user
```
**Symbols:**

```
c096e654-c096e6a8: set_selection_kernel (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int set_selection_kernel(struct tiocl_selection *v, struct tty_struct *tty);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/selection.c (c000000000909160)
Location: drivers/tty/vt/selection.c:348
Inline: False
Direct callers:
  - drivers/tty/vt/selection.c:set_selection_user
```
**Symbols:**

```
c000000000909160-c0000000009091e8: set_selection_kernel (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int set_selection_kernel(struct tiocl_selection *v, struct tty_struct *tty);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/selection.c (ffffffe00053e17c)
Location: drivers/tty/vt/selection.c:348
Inline: False
Direct callers:
  - drivers/tty/vt/selection.c:set_selection_user
```
**Symbols:**

```
ffffffe00053e17c-ffffffe00053e1e2: set_selection_kernel (STB_GLOBAL)
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
int set_selection_kernel(struct tiocl_selection *v, struct tty_struct *tty);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/selection.c (ffffffff8165aa70)
Location: drivers/tty/vt/selection.c:348
Inline: False
Direct callers:
  - drivers/tty/vt/selection.c:set_selection_user
```
**Symbols:**

```
ffffffff8165aa70-ffffffff8165aabc: set_selection_kernel (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int set_selection_kernel(struct tiocl_selection *v, struct tty_struct *tty);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/selection.c (ffffffff8163adf0)
Location: drivers/tty/vt/selection.c:348
Inline: False
Direct callers:
  - drivers/tty/vt/selection.c:set_selection_user
```
**Symbols:**

```
ffffffff8163adf0-ffffffff8163ae3c: set_selection_kernel (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int set_selection_kernel(struct tiocl_selection *v, struct tty_struct *tty);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/selection.c (ffffffff81688e30)
Location: drivers/tty/vt/selection.c:348
Inline: False
Direct callers:
  - drivers/tty/vt/selection.c:set_selection_user
```
**Symbols:**

```
ffffffff81688e30-ffffffff81688e7c: set_selection_kernel (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int set_selection_kernel(struct tiocl_selection *v, struct tty_struct *tty);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/selection.c (ffffffff816a3420)
Location: drivers/tty/vt/selection.c:348
Inline: False
Direct callers:
  - drivers/tty/vt/selection.c:set_selection_user
```
**Symbols:**

```
ffffffff816a3420-ffffffff816a346c: set_selection_kernel (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
