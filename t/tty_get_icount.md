# Function: <code>tty_get_icount</code>

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
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int tty_get_icount(struct tty_struct *tty, struct serial_icounter_struct *icount);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff81736ba1)
Location: drivers/tty/tty_io.c:2601
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_ioctl
```
**Symbols:**

```
ffffffff817338f0-ffffffff81733944: tty_get_icount (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int tty_get_icount(struct tty_struct *tty, struct serial_icounter_struct *icount);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff817b757a)
Location: drivers/tty/tty_io.c:2599
Inline: True
Inline callers:
  - drivers/tty/tty_io.c:tty_ioctl
```
**Symbols:**

```
ffffffff817b4260-ffffffff817b42b4: tty_get_icount (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int tty_get_icount(struct tty_struct *tty, struct serial_icounter_struct *icount);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff818effd0)
Location: drivers/tty/tty_io.c:2572
Inline: False
Direct callers:
  - drivers/tty/tty_io.c:tty_ioctl
```
**Symbols:**

```
ffffffff818effd0-ffffffff818f003c: tty_get_icount (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int tty_get_icount(struct tty_struct *tty, struct serial_icounter_struct *icount);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff81a480d0)
Location: drivers/tty/tty_io.c:2571
Inline: False
Direct callers:
  - drivers/tty/tty_io.c:tty_ioctl
```
**Symbols:**

```
ffffffff81a480d0-ffffffff81a4813c: tty_get_icount (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int tty_get_icount(struct tty_struct *tty, struct serial_icounter_struct *icount);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff81a92550)
Location: drivers/tty/tty_io.c:2580
Inline: False
Direct callers:
  - drivers/tty/tty_io.c:tty_ioctl
```
**Symbols:**

```
ffffffff81a92550-ffffffff81a925bc: tty_get_icount (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int tty_get_icount(struct tty_struct *tty, struct serial_icounter_struct *icount);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff81ae4fa0)
Location: drivers/tty/tty_io.c:2597
Inline: False
Direct callers:
  - drivers/tty/tty_io.c:tty_ioctl
```
**Symbols:**

```
ffffffff81ae4fa0-ffffffff81ae500c: tty_get_icount (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
