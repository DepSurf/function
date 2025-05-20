# Function: <code>save_cur</code>

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
In drivers/tty/vt/vt.c (ffffffff814f8820)
Location: drivers/tty/vt/vt.c:1663
Inline: True
Inline callers:
  - drivers/tty/vt/vt.c:reset_terminal
  - drivers/tty/vt/vt.c:vc_do_resize
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
In drivers/tty/vt/vt.c (ffffffff8154c096)
Location: drivers/tty/vt/vt.c:1661
Inline: True
Inline callers:
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:reset_terminal
  - drivers/tty/vt/vt.c:vc_do_resize
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
In drivers/tty/vt/vt.c (ffffffff815788c8)
Location: drivers/tty/vt/vt.c:1660
Inline: True
Inline callers:
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:reset_terminal
  - drivers/tty/vt/vt.c:vc_do_resize
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
In drivers/tty/vt/vt.c (ffffffff8158c6f4)
Location: drivers/tty/vt/vt.c:1669
Inline: True
Inline callers:
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:reset_terminal
  - drivers/tty/vt/vt.c:vc_do_resize
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
In drivers/tty/vt/vt.c (ffffffff815f11aa)
Location: drivers/tty/vt/vt.c:1675
Inline: True
Inline callers:
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:reset_terminal
  - drivers/tty/vt/vt.c:vc_do_resize
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
In drivers/tty/vt/vt.c (ffffffff8162a6b5)
Location: drivers/tty/vt/vt.c:1673
Inline: True
Inline callers:
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:reset_terminal
  - drivers/tty/vt/vt.c:vc_do_resize
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
In drivers/tty/vt/vt.c (ffffffff81648490)
Location: drivers/tty/vt/vt.c:2001
Inline: True
Inline callers:
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:reset_terminal
  - drivers/tty/vt/vt.c:vc_do_resize
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
In drivers/tty/vt/vt.c (ffffffff8167d34e)
Location: drivers/tty/vt/vt.c:2011
Inline: True
Inline callers:
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:reset_terminal
  - drivers/tty/vt/vt.c:vc_do_resize
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
In drivers/tty/vt/vt.c (ffffffff8169fb4b)
Location: drivers/tty/vt/vt.c:2035
Inline: True
Inline callers:
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:reset_terminal
  - drivers/tty/vt/vt.c:vc_do_resize
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void save_cur(struct vc_data *vc);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/vt.c (ffffffff8174e8dd)
Location: drivers/tty/vt/vt.c:2046
Inline: True
Inline callers:
  - drivers/tty/vt/vt.c:reset_terminal
  - drivers/tty/vt/vt.c:vc_do_resize
Direct callers:
  - drivers/tty/vt/vt.c:do_con_trol
```
**Symbols:**

```
ffffffff8174c720-ffffffff8174c7b9: save_cur (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void save_cur(struct vc_data *vc);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/vt.c (ffffffff8176a55b)
Location: drivers/tty/vt/vt.c:2054
Inline: True
Inline callers:
  - drivers/tty/vt/vt.c:reset_terminal
  - drivers/tty/vt/vt.c:vc_do_resize
Direct callers:
  - drivers/tty/vt/vt.c:do_con_trol
```
**Symbols:**

```
ffffffff817682c0-ffffffff817682f3: save_cur (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void save_cur(struct vc_data *vc);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/vt.c (ffffffff8174e12b)
Location: drivers/tty/vt/vt.c:2054
Inline: True
Inline callers:
  - drivers/tty/vt/vt.c:reset_terminal
  - drivers/tty/vt/vt.c:vc_do_resize
Direct callers:
  - drivers/tty/vt/vt.c:do_con_trol
```
**Symbols:**

```
ffffffff8174bee0-ffffffff8174bf13: save_cur (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void save_cur(struct vc_data *vc);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/vt.c (ffffffff817d0f3b)
Location: drivers/tty/vt/vt.c:2060
Inline: True
Inline callers:
  - drivers/tty/vt/vt.c:reset_terminal
  - drivers/tty/vt/vt.c:vc_do_resize
Direct callers:
  - drivers/tty/vt/vt.c:do_con_trol
```
**Symbols:**

```
ffffffff817cd9b0-ffffffff817cd9e3: save_cur (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void save_cur(struct vc_data *vc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/vt.c (ffffffff8190b5f0)
Location: drivers/tty/vt/vt.c:2060
Inline: False
Direct callers:
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:reset_terminal
  - drivers/tty/vt/vt.c:vc_do_resize
```
**Symbols:**

```
ffffffff8190b5f0-ffffffff8190b62f: save_cur (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void save_cur(struct vc_data *vc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/vt.c (ffffffff81a66b30)
Location: drivers/tty/vt/vt.c:2060
Inline: False
Direct callers:
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:reset_terminal
  - drivers/tty/vt/vt.c:vc_do_resize
```
**Symbols:**

```
ffffffff81a66b30-ffffffff81a66b6f: save_cur (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void save_cur(struct vc_data *vc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/vt.c (ffffffff81ab1340)
Location: drivers/tty/vt/vt.c:2015
Inline: False
Direct callers:
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:reset_terminal
  - drivers/tty/vt/vt.c:vc_do_resize
```
**Symbols:**

```
ffffffff81ab1340-ffffffff81ab137f: save_cur (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void save_cur(struct vc_data *vc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/vt.c (ffffffff81b03fa0)
Location: drivers/tty/vt/vt.c:2014
Inline: False
Direct callers:
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:reset_terminal
  - drivers/tty/vt/vt.c:vc_do_resize
```
**Symbols:**

```
ffffffff81b03fa0-ffffffff81b03fdf: save_cur (STB_LOCAL)
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
In drivers/tty/vt/vt.c (ffff8000108777e8)
Location: drivers/tty/vt/vt.c:2035
Inline: True
Inline callers:
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:reset_terminal
  - drivers/tty/vt/vt.c:vc_do_resize
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
In drivers/tty/vt/vt.c (c097a10c)
Location: drivers/tty/vt/vt.c:2035
Inline: True
Inline callers:
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:reset_terminal
  - drivers/tty/vt/vt.c:vc_do_resize
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
In drivers/tty/vt/vt.c (c0000000009191f4)
Location: drivers/tty/vt/vt.c:2035
Inline: True
Inline callers:
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:reset_terminal
  - drivers/tty/vt/vt.c:vc_do_resize
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
In drivers/tty/vt/vt.c (ffffffe000548604)
Location: drivers/tty/vt/vt.c:2035
Inline: True
Inline callers:
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:reset_terminal
  - drivers/tty/vt/vt.c:vc_do_resize
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
In drivers/tty/vt/vt.c (ffffffff816655ab)
Location: drivers/tty/vt/vt.c:2035
Inline: True
Inline callers:
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:reset_terminal
  - drivers/tty/vt/vt.c:vc_do_resize
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
In drivers/tty/vt/vt.c (ffffffff8164592b)
Location: drivers/tty/vt/vt.c:2035
Inline: True
Inline callers:
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:reset_terminal
  - drivers/tty/vt/vt.c:vc_do_resize
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
In drivers/tty/vt/vt.c (ffffffff8169398b)
Location: drivers/tty/vt/vt.c:2035
Inline: True
Inline callers:
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:reset_terminal
  - drivers/tty/vt/vt.c:vc_do_resize
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
In drivers/tty/vt/vt.c (ffffffff816adf6b)
Location: drivers/tty/vt/vt.c:2035
Inline: True
Inline callers:
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:reset_terminal
  - drivers/tty/vt/vt.c:vc_do_resize
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
