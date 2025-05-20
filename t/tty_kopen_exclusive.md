# Function: <code>tty_kopen_exclusive</code>

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
<summary>In <code>5.13</code>: ✅</summary>

```c
struct tty_struct *tty_kopen_exclusive(dev_t device);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff81737fa0)
Location: drivers/tty/tty_io.c:2022
Inline: False
```
**Symbols:**

```
ffffffff81737fa0-ffffffff81737fb2: tty_kopen_exclusive (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct tty_struct *tty_kopen_exclusive(dev_t device);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff817b8a40)
Location: drivers/tty/tty_io.c:2018
Inline: False
```
**Symbols:**

```
ffffffff817b8a40-ffffffff817b8a52: tty_kopen_exclusive (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct tty_struct *tty_kopen_exclusive(dev_t device);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff818f4a10)
Location: drivers/tty/tty_io.c:2005
Inline: False
```
**Symbols:**

```
ffffffff818f4a10-ffffffff818f4a2a: tty_kopen_exclusive (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct tty_struct *tty_kopen_exclusive(dev_t device);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff81a4d9e0)
Location: drivers/tty/tty_io.c:2000
Inline: False
```
**Symbols:**

```
ffffffff81a4d9e0-ffffffff81a4d9fa: tty_kopen_exclusive (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct tty_struct *tty_kopen_exclusive(dev_t device);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff81a97cb0)
Location: drivers/tty/tty_io.c:2009
Inline: False
```
**Symbols:**

```
ffffffff81a97cb0-ffffffff81a97cca: tty_kopen_exclusive (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct tty_struct *tty_kopen_exclusive(dev_t device);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/tty_io.c (ffffffff81aea6f0)
Location: drivers/tty/tty_io.c:2007
Inline: False
```
**Symbols:**

```
ffffffff81aea6f0-ffffffff81aea70a: tty_kopen_exclusive (STB_GLOBAL)
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
