# Function: <code>scr_memmovew</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void scr_memmovew(u16 *d, const u16 *s, unsigned int count);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/video/console/vgacon.c (ffffffff8145e6d2)
Location: include/linux/vt_buffer.h:45
Inline: True
```
```
In drivers/tty/vt/vt.c (ffffffff814f76a0)
Location: include/linux/vt_buffer.h:45
Inline: True
Inline callers:
  - drivers/tty/vt/vt.c:insert_char
  - drivers/tty/vt/vt.c:scrup
Direct callers:
  - drivers/tty/vt/vt.c:scrdown
```
**Symbols:**

```
ffffffff814f76a0-ffffffff814f76fa: scr_memmovew (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Duplicate, Selective Inline ⚠️</summary>

```c
void scr_memmovew(u16 *d, const u16 *s, unsigned int count);
```

**Collision:** Static Duplication

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/video/console/vgacon.c (ffffffff814ac912)
Location: include/linux/vt_buffer.h:45
Inline: True
```
```
In drivers/tty/vt/vt.c (ffffffff8154a1e3)
Location: include/linux/vt_buffer.h:45
Inline: True
Inline callers:
  - drivers/tty/vt/vt.c:insert_char
  - drivers/tty/vt/vt.c:scrup
Direct callers:
  - drivers/tty/vt/vt.c:scrdown
```
**Symbols:**

```
ffffffff81548530-ffffffff8154858f: scr_memmovew (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/video/console/vgacon.c (ffffffff814ce4a6)
Location: include/linux/vt_buffer.h:45
Inline: True
```
```
In drivers/tty/vt/vt.c (ffffffff81576b73)
Location: include/linux/vt_buffer.h:45
Inline: True
Inline callers:
  - drivers/tty/vt/vt.c:insert_char
  - drivers/tty/vt/vt.c:con_scroll
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/video/console/vgacon.c (ffffffff814da3a6)
Location: include/linux/vt_buffer.h:45
Inline: True
```
```
In drivers/tty/vt/vt.c (ffffffff8158aa79)
Location: include/linux/vt_buffer.h:45
Inline: True
Inline callers:
  - drivers/tty/vt/vt.c:insert_char
  - drivers/tty/vt/vt.c:con_scroll
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/video/console/vgacon.c (ffffffff8151a576)
Location: include/linux/vt_buffer.h:55
Inline: True
```
```
In drivers/tty/vt/vt.c (ffffffff815ef04e)
Location: include/linux/vt_buffer.h:55
Inline: True
Inline callers:
  - drivers/tty/vt/vt.c:insert_char
  - drivers/tty/vt/vt.c:con_scroll
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/video/console/vgacon.c (ffffffff8155012f)
Location: include/linux/vt_buffer.h:55
Inline: True
```
```
In drivers/tty/vt/vt.c (ffffffff81628323)
Location: include/linux/vt_buffer.h:55
Inline: True
Inline callers:
  - drivers/tty/vt/vt.c:insert_char
  - drivers/tty/vt/vt.c:con_scroll
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/video/console/vgacon.c (ffffffff815679db)
Location: include/linux/vt_buffer.h:55
Inline: True
```
```
In drivers/tty/vt/vt.c (ffffffff81645b1e)
Location: include/linux/vt_buffer.h:55
Inline: True
Inline callers:
  - drivers/tty/vt/vt.c:insert_char
  - drivers/tty/vt/vt.c:con_scroll
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/video/console/vgacon.c (ffffffff81598337)
Location: include/linux/vt_buffer.h:55
Inline: True
```
```
In drivers/tty/vt/vt.c (ffffffff8167a0a0)
Location: include/linux/vt_buffer.h:55
Inline: True
Inline callers:
  - drivers/tty/vt/vt.c:insert_char
  - drivers/tty/vt/vt.c:con_scroll
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/video/console/vgacon.c (ffffffff815b96d7)
Location: include/linux/vt_buffer.h:55
Inline: True
```
```
In drivers/tty/vt/vt.c (ffffffff8169c890)
Location: include/linux/vt_buffer.h:55
Inline: True
Inline callers:
  - drivers/tty/vt/vt.c:insert_char
  - drivers/tty/vt/vt.c:con_scroll
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/video/console/vgacon.c (ffffffff8166354c)
Location: include/linux/vt_buffer.h:55
Inline: True
```
```
In drivers/tty/vt/vt.c (ffffffff8174dea0)
Location: include/linux/vt_buffer.h:55
Inline: True
Inline callers:
  - drivers/tty/vt/vt.c:insert_char
  - drivers/tty/vt/vt.c:con_scroll
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/video/console/vgacon.c (ffffffff816841cf)
Location: include/linux/vt_buffer.h:55
Inline: True
```
```
In drivers/tty/vt/vt.c (ffffffff8176945f)
Location: include/linux/vt_buffer.h:55
Inline: True
Inline callers:
  - drivers/tty/vt/vt.c:insert_char
  - drivers/tty/vt/vt.c:con_scroll
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/video/console/vgacon.c (ffffffff816670df)
Location: include/linux/vt_buffer.h:55
Inline: True
```
```
In drivers/tty/vt/vt.c (ffffffff8174d051)
Location: include/linux/vt_buffer.h:55
Inline: True
Inline callers:
  - drivers/tty/vt/vt.c:insert_char
  - drivers/tty/vt/vt.c:con_scroll
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/video/console/vgacon.c (ffffffff816d9f63)
Location: include/linux/vt_buffer.h:55
Inline: True
```
```
In drivers/tty/vt/vt.c (ffffffff817cf021)
Location: include/linux/vt_buffer.h:55
Inline: True
Inline callers:
  - drivers/tty/vt/vt.c:insert_char
  - drivers/tty/vt/vt.c:con_scroll
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/video/console/vgacon.c (ffffffff8180326b)
Location: include/linux/vt_buffer.h:55
Inline: True
Inline callers:
  - drivers/video/console/vgacon.c:vgacon_scroll
```
```
In drivers/tty/vt/vt.c (ffffffff8190d171)
Location: include/linux/vt_buffer.h:55
Inline: True
Inline callers:
  - drivers/tty/vt/vt.c:insert_char
  - drivers/tty/vt/vt.c:con_scroll
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/video/console/vgacon.c (ffffffff819319eb)
Location: include/linux/vt_buffer.h:55
Inline: True
Inline callers:
  - drivers/video/console/vgacon.c:vgacon_scroll
```
```
In drivers/tty/vt/vt.c (ffffffff81a67e3f)
Location: include/linux/vt_buffer.h:55
Inline: True
Inline callers:
  - drivers/tty/vt/vt.c:insert_char
  - drivers/tty/vt/vt.c:con_scroll
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/video/console/vgacon.c (ffffffff81975e5b)
Location: include/linux/vt_buffer.h:55
Inline: True
Inline callers:
  - drivers/video/console/vgacon.c:vgacon_scroll
```
```
In drivers/tty/vt/vt.c (ffffffff81ab251f)
Location: include/linux/vt_buffer.h:55
Inline: True
Inline callers:
  - drivers/tty/vt/vt.c:insert_char
  - drivers/tty/vt/vt.c:con_scroll
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/video/console/vgacon.c (ffffffff819bfecb)
Location: include/linux/vt_buffer.h:55
Inline: True
Inline callers:
  - drivers/video/console/vgacon.c:vgacon_scroll
```
```
In drivers/tty/vt/vt.c (ffffffff81b051ff)
Location: include/linux/vt_buffer.h:55
Inline: True
Inline callers:
  - drivers/tty/vt/vt.c:insert_char
  - drivers/tty/vt/vt.c:con_scroll
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/vt.c (ffff8000108740f4)
Location: include/linux/vt_buffer.h:55
Inline: True
Inline callers:
  - drivers/tty/vt/vt.c:insert_char
  - drivers/tty/vt/vt.c:con_scroll
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/vt.c (c0976ee8)
Location: include/linux/vt_buffer.h:55
Inline: True
Inline callers:
  - drivers/tty/vt/vt.c:insert_char
  - drivers/tty/vt/vt.c:con_scroll
```
</details>
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/video/console/vgacon.c (ffffffe0004f1a5e)
Location: include/linux/vt_buffer.h:55
Inline: True
```
```
In drivers/tty/vt/vt.c (ffffffe000543eb8)
Location: include/linux/vt_buffer.h:55
Inline: True
Inline callers:
  - drivers/tty/vt/vt.c:insert_char
  - drivers/tty/vt/vt.c:con_scroll
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/video/console/vgacon.c (ffffffff815ad827)
Location: include/linux/vt_buffer.h:55
Inline: True
```
```
In drivers/tty/vt/vt.c (ffffffff816622f0)
Location: include/linux/vt_buffer.h:55
Inline: True
Inline callers:
  - drivers/tty/vt/vt.c:insert_char
  - drivers/tty/vt/vt.c:con_scroll
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/video/console/vgacon.c (ffffffff8159c9c7)
Location: include/linux/vt_buffer.h:55
Inline: True
```
```
In drivers/tty/vt/vt.c (ffffffff81642670)
Location: include/linux/vt_buffer.h:55
Inline: True
Inline callers:
  - drivers/tty/vt/vt.c:insert_char
  - drivers/tty/vt/vt.c:con_scroll
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/video/console/vgacon.c (ffffffff815addb7)
Location: include/linux/vt_buffer.h:55
Inline: True
```
```
In drivers/tty/vt/vt.c (ffffffff816906d0)
Location: include/linux/vt_buffer.h:55
Inline: True
Inline callers:
  - drivers/tty/vt/vt.c:insert_char
  - drivers/tty/vt/vt.c:con_scroll
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Duplicate, Full Inline ⚠️</summary>

**Collision:** Static Duplication

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/video/console/vgacon.c (ffffffff815c7867)
Location: include/linux/vt_buffer.h:55
Inline: True
```
```
In drivers/tty/vt/vt.c (ffffffff816aacc0)
Location: include/linux/vt_buffer.h:55
Inline: True
Inline callers:
  - drivers/tty/vt/vt.c:insert_char
  - drivers/tty/vt/vt.c:con_scroll
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
</ul>
