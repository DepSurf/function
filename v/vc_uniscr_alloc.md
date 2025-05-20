# Function: <code>vc_uniscr_alloc</code>

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
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct uni_screen *vc_uniscr_alloc(unsigned int cols, unsigned int rows);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/vt.c (ffffffff816439d0)
Location: drivers/tty/vt/vt.c:348
Inline: False
Direct callers:
  - drivers/tty/vt/vt.c:vc_do_resize
  - drivers/tty/vt/vt.c:vc_uniscr_check
```
**Symbols:**

```
ffffffff816439d0-ffffffff81643a2d: vc_uniscr_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct uni_screen *vc_uniscr_alloc(unsigned int cols, unsigned int rows);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/vt.c (ffffffff8167a660)
Location: drivers/tty/vt/vt.c:348
Inline: False
Direct callers:
  - drivers/tty/vt/vt.c:vc_do_resize
  - drivers/tty/vt/vt.c:vc_uniscr_check
```
**Symbols:**

```
ffffffff8167a660-ffffffff8167a6bd: vc_uniscr_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct uni_screen *vc_uniscr_alloc(unsigned int cols, unsigned int rows);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/vt.c (ffffffff8169ce50)
Location: drivers/tty/vt/vt.c:348
Inline: False
Direct callers:
  - drivers/tty/vt/vt.c:vc_do_resize
  - drivers/tty/vt/vt.c:vc_uniscr_check
```
**Symbols:**

```
ffffffff8169ce50-ffffffff8169cead: vc_uniscr_alloc (STB_LOCAL)
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
In drivers/tty/vt/vt.c (ffffffff8174f6f4)
Location: drivers/tty/vt/vt.c:349
Inline: True
Inline callers:
  - drivers/tty/vt/vt.c:vc_do_resize
  - drivers/tty/vt/vt.c:vc_uniscr_check
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
In drivers/tty/vt/vt.c (ffffffff8176b834)
Location: drivers/tty/vt/vt.c:342
Inline: True
Inline callers:
  - drivers/tty/vt/vt.c:vc_do_resize
  - drivers/tty/vt/vt.c:vc_uniscr_check
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
In drivers/tty/vt/vt.c (ffffffff8174e75b)
Location: drivers/tty/vt/vt.c:342
Inline: True
Inline callers:
  - drivers/tty/vt/vt.c:vc_do_resize
  - drivers/tty/vt/vt.c:vc_uniscr_check
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
In drivers/tty/vt/vt.c (ffffffff817d058d)
Location: drivers/tty/vt/vt.c:338
Inline: True
Inline callers:
  - drivers/tty/vt/vt.c:vc_do_resize
  - drivers/tty/vt/vt.c:vc_uniscr_check
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
In drivers/tty/vt/vt.c (ffffffff8190e43b)
Location: drivers/tty/vt/vt.c:338
Inline: True
Inline callers:
  - drivers/tty/vt/vt.c:vc_do_resize
  - drivers/tty/vt/vt.c:vc_uniscr_check
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
In drivers/tty/vt/vt.c (ffffffff81a69459)
Location: drivers/tty/vt/vt.c:338
Inline: True
Inline callers:
  - drivers/tty/vt/vt.c:vc_do_resize
  - drivers/tty/vt/vt.c:vc_uniscr_check
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/vt.c (ffffffff81ab3b37)
Location: drivers/tty/vt/vt.c:328
Inline: True
Inline callers:
  - drivers/tty/vt/vt.c:vc_do_resize
  - drivers/tty/vt/vt.c:vc_uniscr_check
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/vt.c (ffffffff81b06817)
Location: drivers/tty/vt/vt.c:327
Inline: True
Inline callers:
  - drivers/tty/vt/vt.c:vc_do_resize
  - drivers/tty/vt/vt.c:vc_uniscr_check
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
struct uni_screen *vc_uniscr_alloc(unsigned int cols, unsigned int rows);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/vt.c (ffff8000108730e8)
Location: drivers/tty/vt/vt.c:348
Inline: False
Direct callers:
  - drivers/tty/vt/vt.c:vc_do_resize
  - drivers/tty/vt/vt.c:vc_uniscr_check
```
**Symbols:**

```
ffff8000108730e8-ffff800010873150: vc_uniscr_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct uni_screen *vc_uniscr_alloc(unsigned int cols, unsigned int rows);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/vt.c (c0977478)
Location: drivers/tty/vt/vt.c:348
Inline: False
Direct callers:
  - drivers/tty/vt/vt.c:vc_do_resize
  - drivers/tty/vt/vt.c:vc_uniscr_check
```
**Symbols:**

```
c0977478-c09774dc: vc_uniscr_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct uni_screen *vc_uniscr_alloc(unsigned int cols, unsigned int rows);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/vt.c (c0000000009159f0)
Location: drivers/tty/vt/vt.c:348
Inline: False
Direct callers:
  - drivers/tty/vt/vt.c:vc_do_resize
  - drivers/tty/vt/vt.c:vc_uniscr_check
```
**Symbols:**

```
c0000000009159f0-c000000000915a98: vc_uniscr_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct uni_screen *vc_uniscr_alloc(unsigned int cols, unsigned int rows);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/vt.c (ffffffe00054585a)
Location: drivers/tty/vt/vt.c:348
Inline: False
Direct callers:
  - drivers/tty/vt/vt.c:vc_do_resize
  - drivers/tty/vt/vt.c:vc_uniscr_check
```
**Symbols:**

```
ffffffe00054585a-ffffffe0005458ca: vc_uniscr_alloc (STB_LOCAL)
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
struct uni_screen *vc_uniscr_alloc(unsigned int cols, unsigned int rows);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/vt.c (ffffffff816628b0)
Location: drivers/tty/vt/vt.c:348
Inline: False
Direct callers:
  - drivers/tty/vt/vt.c:vc_do_resize
  - drivers/tty/vt/vt.c:vc_uniscr_check
```
**Symbols:**

```
ffffffff816628b0-ffffffff8166290d: vc_uniscr_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct uni_screen *vc_uniscr_alloc(unsigned int cols, unsigned int rows);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/vt.c (ffffffff81642c30)
Location: drivers/tty/vt/vt.c:348
Inline: False
Direct callers:
  - drivers/tty/vt/vt.c:vc_do_resize
  - drivers/tty/vt/vt.c:vc_uniscr_check
```
**Symbols:**

```
ffffffff81642c30-ffffffff81642c8d: vc_uniscr_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct uni_screen *vc_uniscr_alloc(unsigned int cols, unsigned int rows);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/vt.c (ffffffff81690c90)
Location: drivers/tty/vt/vt.c:348
Inline: False
Direct callers:
  - drivers/tty/vt/vt.c:vc_do_resize
  - drivers/tty/vt/vt.c:vc_uniscr_check
```
**Symbols:**

```
ffffffff81690c90-ffffffff81690ced: vc_uniscr_alloc (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct uni_screen *vc_uniscr_alloc(unsigned int cols, unsigned int rows);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/vt.c (ffffffff816ab280)
Location: drivers/tty/vt/vt.c:348
Inline: False
Direct callers:
  - drivers/tty/vt/vt.c:vc_do_resize
  - drivers/tty/vt/vt.c:vc_uniscr_check
```
**Symbols:**

```
ffffffff816ab280-ffffffff816ab2dd: vc_uniscr_alloc (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
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
