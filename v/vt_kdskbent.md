# Function: <code>vt_kdskbent</code>

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
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int vt_kdskbent(unsigned char kbdmode, unsigned char idx, unsigned char map, short unsigned int val);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/keyboard.c (ffffffff81763b00)
Location: drivers/tty/vt/keyboard.c:1922
Inline: False
Direct callers:
  - drivers/tty/vt/keyboard.c:vt_do_kdsk_ioctl
```
**Symbols:**

```
ffffffff81763b00-ffffffff81763d6f: vt_kdskbent (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int vt_kdskbent(unsigned char kbdmode, unsigned char idx, unsigned char map, short unsigned int val);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/keyboard.c (ffffffff81748810)
Location: drivers/tty/vt/keyboard.c:1932
Inline: False
Direct callers:
  - drivers/tty/vt/keyboard.c:vt_do_kdsk_ioctl
```
**Symbols:**

```
ffffffff81748810-ffffffff81748a7f: vt_kdskbent (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int vt_kdskbent(unsigned char kbdmode, unsigned char idx, unsigned char map, short unsigned int val);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/keyboard.c (ffffffff817c94a0)
Location: drivers/tty/vt/keyboard.c:1932
Inline: False
Direct callers:
  - drivers/tty/vt/keyboard.c:vt_do_kdsk_ioctl
```
**Symbols:**

```
ffffffff817c94a0-ffffffff817c973b: vt_kdskbent (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int vt_kdskbent(unsigned char kbdmode, unsigned char idx, unsigned char map, short unsigned int val);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/keyboard.c (ffffffff81906a40)
Location: drivers/tty/vt/keyboard.c:1944
Inline: False
Direct callers:
  - drivers/tty/vt/keyboard.c:vt_do_kdsk_ioctl
```
**Symbols:**

```
ffffffff81906a40-ffffffff81906cb4: vt_kdskbent (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int vt_kdskbent(unsigned char kbdmode, unsigned char idx, unsigned char map, short unsigned int val);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/keyboard.c (ffffffff81a5ff60)
Location: drivers/tty/vt/keyboard.c:1944
Inline: False
Direct callers:
  - drivers/tty/vt/keyboard.c:vt_do_kdsk_ioctl
```
**Symbols:**

```
ffffffff81a5ff60-ffffffff81a601d4: vt_kdskbent (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int vt_kdskbent(unsigned char kbdmode, unsigned char idx, unsigned char map, short unsigned int val);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/keyboard.c (ffffffff81aaa610)
Location: drivers/tty/vt/keyboard.c:1944
Inline: False
Direct callers:
  - drivers/tty/vt/keyboard.c:vt_do_kdsk_ioctl
```
**Symbols:**

```
ffffffff81aaa610-ffffffff81aaa8a3: vt_kdskbent (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int vt_kdskbent(unsigned char kbdmode, unsigned char idx, unsigned char map, short unsigned int val);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/keyboard.c (ffffffff81afd070)
Location: drivers/tty/vt/keyboard.c:1942
Inline: False
Direct callers:
  - drivers/tty/vt/keyboard.c:vt_do_kdsk_ioctl
```
**Symbols:**

```
ffffffff81afd070-ffffffff81afd332: vt_kdskbent (STB_LOCAL)
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
