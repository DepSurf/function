# Function: <code>cr</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/vt.c (ffffffff814f81a9)
Location: drivers/tty/vt/vt.c:1148
Inline: True
Inline callers:
  - drivers/tty/vt/vt.c:vt_console_print
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:do_con_trol
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/vt.c (ffffffff8154a75c)
Location: drivers/tty/vt/vt.c:1152
Inline: True
Inline callers:
  - drivers/tty/vt/vt.c:vt_console_print
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:do_con_trol
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/vt.c (ffffffff81576f8c)
Location: drivers/tty/vt/vt.c:1146
Inline: True
Inline callers:
  - drivers/tty/vt/vt.c:vt_console_print
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:do_con_trol
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/vt.c (ffffffff8158aeea)
Location: drivers/tty/vt/vt.c:1154
Inline: True
Inline callers:
  - drivers/tty/vt/vt.c:vt_console_print
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:do_con_trol
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/vt.c (ffffffff815ef984)
Location: drivers/tty/vt/vt.c:1156
Inline: True
Inline callers:
  - drivers/tty/vt/vt.c:vt_console_print
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:do_con_trol
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/vt.c (ffffffff816286e5)
Location: drivers/tty/vt/vt.c:1156
Inline: True
Inline callers:
  - drivers/tty/vt/vt.c:vt_console_print
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:do_con_trol
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/vt.c (ffffffff81645f42)
Location: drivers/tty/vt/vt.c:1478
Inline: True
Inline callers:
  - drivers/tty/vt/vt.c:vt_console_print
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:do_con_trol
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/vt.c (ffffffff8167a462)
Location: drivers/tty/vt/vt.c:1487
Inline: True
Inline callers:
  - drivers/tty/vt/vt.c:vt_console_print
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:do_con_trol
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/vt.c (ffffffff8169cc52)
Location: drivers/tty/vt/vt.c:1511
Inline: True
Inline callers:
  - drivers/tty/vt/vt.c:vt_console_print
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:do_con_trol
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void cr(struct vc_data *vc);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/vt.c (ffffffff8174f30f)
Location: drivers/tty/vt/vt.c:1524
Inline: True
Inline callers:
  - drivers/tty/vt/vt.c:vt_console_print
  - drivers/tty/vt/vt.c:do_con_write
  - drivers/tty/vt/vt.c:do_con_trol
Direct callers:
  - drivers/tty/vt/vt.c:do_con_trol
```
**Symbols:**

```
ffffffff8174ca10-ffffffff8174ca7b: cr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void cr(struct vc_data *vc);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/vt.c (ffffffff8176a20f)
Location: drivers/tty/vt/vt.c:1524
Inline: True
Inline callers:
  - drivers/tty/vt/vt.c:vt_console_print
  - drivers/tty/vt/vt.c:vc_con_write_normal
  - drivers/tty/vt/vt.c:do_con_trol
Direct callers:
  - drivers/tty/vt/vt.c:do_con_trol
```
**Symbols:**

```
ffffffff81768040-ffffffff817680ab: cr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void cr(struct vc_data *vc);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/vt.c (ffffffff8174db7f)
Location: drivers/tty/vt/vt.c:1524
Inline: True
Inline callers:
  - drivers/tty/vt/vt.c:vt_console_print
  - drivers/tty/vt/vt.c:vc_con_write_normal
  - drivers/tty/vt/vt.c:do_con_trol
Direct callers:
  - drivers/tty/vt/vt.c:do_con_trol
```
**Symbols:**

```
ffffffff8174bc60-ffffffff8174bccb: cr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void cr(struct vc_data *vc);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/vt.c (ffffffff817d1fd8)
Location: drivers/tty/vt/vt.c:1530
Inline: True
Inline callers:
  - drivers/tty/vt/vt.c:vt_console_print
  - drivers/tty/vt/vt.c:vc_con_write_normal
  - drivers/tty/vt/vt.c:do_con_trol
Direct callers:
  - drivers/tty/vt/vt.c:do_con_trol
```
**Symbols:**

```
ffffffff817cd800-ffffffff817cd86b: cr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void cr(struct vc_data *vc);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/vt.c (ffffffff8190fc30)
Location: drivers/tty/vt/vt.c:1530
Inline: True
Inline callers:
  - drivers/tty/vt/vt.c:vt_console_print
  - drivers/tty/vt/vt.c:vc_con_write_normal
  - drivers/tty/vt/vt.c:do_con_trol
Direct callers:
  - drivers/tty/vt/vt.c:do_con_trol
```
**Symbols:**

```
ffffffff8190cb50-ffffffff8190cbca: cr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void cr(struct vc_data *vc);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/vt.c (ffffffff81a6a3a5)
Location: drivers/tty/vt/vt.c:1530
Inline: True
Inline callers:
  - drivers/tty/vt/vt.c:vt_console_print
  - drivers/tty/vt/vt.c:vc_con_write_normal
  - drivers/tty/vt/vt.c:do_con_trol
Direct callers:
  - drivers/tty/vt/vt.c:do_con_trol
```
**Symbols:**

```
ffffffff81a67810-ffffffff81a6788a: cr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void cr(struct vc_data *vc);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/vt.c (ffffffff81ab49e1)
Location: drivers/tty/vt/vt.c:1485
Inline: True
Inline callers:
  - drivers/tty/vt/vt.c:vt_console_print
  - drivers/tty/vt/vt.c:vc_con_write_normal
  - drivers/tty/vt/vt.c:do_con_trol
Direct callers:
  - drivers/tty/vt/vt.c:do_con_trol
```
**Symbols:**

```
ffffffff81ab1ef0-ffffffff81ab1f6a: cr (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void cr(struct vc_data *vc);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/vt.c (ffffffff81b076c1)
Location: drivers/tty/vt/vt.c:1484
Inline: True
Inline callers:
  - drivers/tty/vt/vt.c:vt_console_print
  - drivers/tty/vt/vt.c:vc_con_write_normal
  - drivers/tty/vt/vt.c:do_con_trol
Direct callers:
  - drivers/tty/vt/vt.c:do_con_trol
```
**Symbols:**

```
ffffffff81b04bd0-ffffffff81b04c4a: cr (STB_LOCAL)
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
In drivers/tty/vt/vt.c (ffff8000108744b4)
Location: drivers/tty/vt/vt.c:1511
Inline: True
Inline callers:
  - drivers/tty/vt/vt.c:vt_console_print
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:do_con_trol
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
In drivers/tty/vt/vt.c (c09771c0)
Location: drivers/tty/vt/vt.c:1511
Inline: True
Inline callers:
  - drivers/tty/vt/vt.c:vt_console_print
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:do_con_trol
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/vt.c (c0000000009156ac)
Location: drivers/tty/vt/vt.c:1511
Inline: True
Inline callers:
  - drivers/tty/vt/vt.c:vt_console_print
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:do_con_trol
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/vt.c (ffffffe000545db0)
Location: drivers/tty/vt/vt.c:1511
Inline: True
Inline callers:
  - drivers/tty/vt/vt.c:vt_console_print
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:do_con_trol
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/vt.c (ffffffff816626b2)
Location: drivers/tty/vt/vt.c:1511
Inline: True
Inline callers:
  - drivers/tty/vt/vt.c:vt_console_print
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:do_con_trol
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/vt.c (ffffffff81642a32)
Location: drivers/tty/vt/vt.c:1511
Inline: True
Inline callers:
  - drivers/tty/vt/vt.c:vt_console_print
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:do_con_trol
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/vt.c (ffffffff81690a92)
Location: drivers/tty/vt/vt.c:1511
Inline: True
Inline callers:
  - drivers/tty/vt/vt.c:vt_console_print
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:do_con_trol
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/vt.c (ffffffff816ab082)
Location: drivers/tty/vt/vt.c:1511
Inline: True
Inline callers:
  - drivers/tty/vt/vt.c:vt_console_print
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:do_con_trol
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
