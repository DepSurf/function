# Function: <code>tty_kopen</code>

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
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct tty_struct *tty_kopen(dev_t device);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff815d9ef0)
Location: drivers/tty/tty_io.c:1855
Inline: False
```
**Symbols:**

```
ffffffff815d9ef0-ffffffff815da027: tty_kopen (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct tty_struct *tty_kopen(dev_t device);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff81612e90)
Location: drivers/tty/tty_io.c:1873
Inline: False
```
**Symbols:**

```
ffffffff81612e90-ffffffff81612fc8: tty_kopen (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct tty_struct *tty_kopen(dev_t device);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff8162ff30)
Location: drivers/tty/tty_io.c:1885
Inline: False
```
**Symbols:**

```
ffffffff8162ff30-ffffffff81630068: tty_kopen (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct tty_struct *tty_kopen(dev_t device);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff81663e50)
Location: drivers/tty/tty_io.c:1889
Inline: False
```
**Symbols:**

```
ffffffff81663e50-ffffffff81663f8b: tty_kopen (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct tty_struct *tty_kopen(dev_t device);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff816864c0)
Location: drivers/tty/tty_io.c:1889
Inline: False
```
**Symbols:**

```
ffffffff816864c0-ffffffff816865fb: tty_kopen (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct tty_struct *tty_kopen(dev_t device);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff81737b10)
Location: drivers/tty/tty_io.c:1889
Inline: False
```
**Symbols:**

```
ffffffff81737b10-ffffffff81737d2d: tty_kopen (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct tty_struct *tty_kopen(dev_t device);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff81753ed0)
Location: drivers/tty/tty_io.c:1973
Inline: False
```
**Symbols:**

```
ffffffff81753ed0-ffffffff817540ed: tty_kopen (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct tty_struct *tty_kopen(dev_t device, int shared);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff81737d70)
Location: drivers/tty/tty_io.c:1973
Inline: False
Direct callers:
  - drivers/tty/tty_io.c:tty_kopen_shared
  - drivers/tty/tty_io.c:tty_kopen_exclusive
```
**Symbols:**

```
ffffffff81737d70-ffffffff81737f9f: tty_kopen (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct tty_struct *tty_kopen(dev_t device, int shared);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff817b8810)
Location: drivers/tty/tty_io.c:1969
Inline: False
Direct callers:
  - drivers/tty/tty_io.c:tty_kopen_shared
  - drivers/tty/tty_io.c:tty_kopen_exclusive
```
**Symbols:**

```
ffffffff817b8810-ffffffff817b8a3f: tty_kopen (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct tty_struct *tty_kopen(dev_t device, int shared);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff818f47c0)
Location: drivers/tty/tty_io.c:1957
Inline: False
Direct callers:
  - drivers/tty/tty_io.c:tty_kopen_shared
  - drivers/tty/tty_io.c:tty_kopen_exclusive
```
**Symbols:**

```
ffffffff818f47c0-ffffffff818f4a02: tty_kopen (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct tty_struct *tty_kopen(dev_t device, int shared);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff81a4d780)
Location: drivers/tty/tty_io.c:1952
Inline: False
Direct callers:
  - drivers/tty/tty_io.c:tty_kopen_shared
  - drivers/tty/tty_io.c:tty_kopen_exclusive
```
**Symbols:**

```
ffffffff81a4d780-ffffffff81a4d9cf: tty_kopen (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct tty_struct *tty_kopen(dev_t device, int shared);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff81a97a50)
Location: drivers/tty/tty_io.c:1961
Inline: False
Direct callers:
  - drivers/tty/tty_io.c:tty_kopen_shared
  - drivers/tty/tty_io.c:tty_kopen_exclusive
```
**Symbols:**

```
ffffffff81a97a50-ffffffff81a97c9f: tty_kopen (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct tty_struct *tty_kopen(dev_t device, int shared);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff81aea490)
Location: drivers/tty/tty_io.c:1959
Inline: False
Direct callers:
  - drivers/tty/tty_io.c:tty_kopen_shared
  - drivers/tty/tty_io.c:tty_kopen_exclusive
```
**Symbols:**

```
ffffffff81aea490-ffffffff81aea6dc: tty_kopen (STB_LOCAL)
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
struct tty_struct *tty_kopen(dev_t device);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffff800010853e48)
Location: drivers/tty/tty_io.c:1889
Inline: False
```
**Symbols:**

```
ffff800010853e48-ffff800010853f6c: tty_kopen (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct tty_struct *tty_kopen(dev_t device);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (c095e36c)
Location: drivers/tty/tty_io.c:1889
Inline: False
```
**Symbols:**

```
c095e36c-c095e488: tty_kopen (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct tty_struct *tty_kopen(dev_t device);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (c0000000008f3430)
Location: drivers/tty/tty_io.c:1889
Inline: False
```
**Symbols:**

```
c0000000008f3430-c0000000008f35ac: tty_kopen (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct tty_struct *tty_kopen(dev_t device);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffe00053068a)
Location: drivers/tty/tty_io.c:1889
Inline: False
```
**Symbols:**

```
ffffffe00053068a-ffffffe000530788: tty_kopen (STB_GLOBAL)
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
struct tty_struct *tty_kopen(dev_t device);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff8164bf40)
Location: drivers/tty/tty_io.c:1889
Inline: False
```
**Symbols:**

```
ffffffff8164bf40-ffffffff8164c07b: tty_kopen (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct tty_struct *tty_kopen(dev_t device);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff8162c390)
Location: drivers/tty/tty_io.c:1889
Inline: False
```
**Symbols:**

```
ffffffff8162c390-ffffffff8162c4cb: tty_kopen (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct tty_struct *tty_kopen(dev_t device);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff8167a300)
Location: drivers/tty/tty_io.c:1889
Inline: False
```
**Symbols:**

```
ffffffff8167a300-ffffffff8167a43b: tty_kopen (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct tty_struct *tty_kopen(dev_t device);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff81694960)
Location: drivers/tty/tty_io.c:1889
Inline: False
```
**Symbols:**

```
ffffffff81694960-ffffffff81694a9b: tty_kopen (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
<details>
<summary>Changed between <code>5.11</code> and <code>5.13</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>int shared</code>
</li>
</ul>
</details>
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
