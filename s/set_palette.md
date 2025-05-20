# Function: <code>set_palette</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
void set_palette(struct vc_data *vc);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/vt.c (ffffffff814f79b0)
Location: drivers/tty/vt/vt.c:3995
Inline: True
Direct callers:
  - drivers/tty/vt/vt.c:redraw_screen
  - drivers/tty/vt/vt.c:con_set_cmap
  - drivers/tty/vt/vt.c:reset_palette
  - drivers/tty/vt/vt.c:do_con_trol
```
**Symbols:**

```
ffffffff814f79b0-ffffffff814f7a06: set_palette (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void set_palette(struct vc_data *vc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/vt.c (ffffffff81547db0)
Location: drivers/tty/vt/vt.c:3994
Inline: False
Direct callers:
  - drivers/tty/vt/vt.c:reset_palette
  - drivers/tty/vt/vt.c:con_set_cmap
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:redraw_screen
```
**Symbols:**

```
ffffffff81547db0-ffffffff81547e0e: set_palette (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void set_palette(struct vc_data *vc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/vt.c (ffffffff815746b0)
Location: drivers/tty/vt/vt.c:3989
Inline: False
Direct callers:
  - drivers/tty/vt/vt.c:reset_palette
  - drivers/tty/vt/vt.c:con_set_cmap
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:redraw_screen
```
**Symbols:**

```
ffffffff815746b0-ffffffff8157470e: set_palette (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void set_palette(struct vc_data *vc);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/vt.c (ffffffff815891a0)
Location: drivers/tty/vt/vt.c:3998
Inline: True
Direct callers:
  - drivers/tty/vt/vt.c:reset_palette
  - drivers/tty/vt/vt.c:con_set_cmap
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:redraw_screen
```
**Symbols:**

```
ffffffff815891a0-ffffffff815891ef: set_palette (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void set_palette(struct vc_data *vc);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/vt.c (ffffffff815edcc0)
Location: drivers/tty/vt/vt.c:4001
Inline: True
Direct callers:
  - drivers/tty/vt/vt.c:reset_palette
  - drivers/tty/vt/vt.c:con_set_cmap
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:redraw_screen
```
**Symbols:**

```
ffffffff815edcc0-ffffffff815edd12: set_palette (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void set_palette(struct vc_data *vc);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/vt.c (ffffffff81627180)
Location: drivers/tty/vt/vt.c:3999
Inline: True
Direct callers:
  - drivers/tty/vt/vt.c:reset_palette
  - drivers/tty/vt/vt.c:con_set_cmap
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:redraw_screen
```
**Symbols:**

```
ffffffff81627180-ffffffff816271ca: set_palette (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void set_palette(struct vc_data *vc);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/vt.c (ffffffff81644d20)
Location: drivers/tty/vt/vt.c:4313
Inline: True
Direct callers:
  - drivers/tty/vt/vt.c:reset_palette
  - drivers/tty/vt/vt.c:con_set_cmap
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:redraw_screen
```
**Symbols:**

```
ffffffff81644d20-ffffffff81644d7a: set_palette (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

```c
void set_palette(struct vc_data *vc);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/tty/vt/vt.c (ffffffff81679123)
Location: drivers/tty/vt/vt.c:4369
Inline: True
Direct callers:
  - drivers/tty/vt/vt.c:reset_palette
  - drivers/tty/vt/vt.c:con_set_cmap
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:redraw_screen
```
**Symbols:**

```
ffffffff81679100-ffffffff8167915d: set_palette (STB_LOCAL)
ffffffff8167f075-ffffffff8167f088: set_palette.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void set_palette(struct vc_data *vc);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/vt.c (ffffffff8169b380)
Location: drivers/tty/vt/vt.c:4400
Inline: True
Direct callers:
  - drivers/tty/vt/vt.c:reset_palette
  - drivers/tty/vt/vt.c:con_set_cmap
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:redraw_screen
```
**Symbols:**

```
ffffffff8169b380-ffffffff8169b3db: set_palette (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void set_palette(struct vc_data *vc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/vt.c (ffffffff8174cad0)
Location: drivers/tty/vt/vt.c:4410
Inline: False
Direct callers:
  - drivers/tty/vt/vt.c:reset_palette
  - drivers/tty/vt/vt.c:con_set_cmap
  - drivers/tty/vt/vt.c:do_unblank_screen
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:redraw_screen
```
**Symbols:**

```
ffffffff8174cad0-ffffffff8174cb2d: set_palette (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void set_palette(struct vc_data *vc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/vt.c (ffffffff81768100)
Location: drivers/tty/vt/vt.c:4498
Inline: False
Direct callers:
  - drivers/tty/vt/vt.c:reset_palette
  - drivers/tty/vt/vt.c:con_set_cmap
  - drivers/tty/vt/vt.c:do_unblank_screen
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:redraw_screen
```
**Symbols:**

```
ffffffff81768100-ffffffff8176815a: set_palette (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void set_palette(struct vc_data *vc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/vt.c (ffffffff8174bd20)
Location: drivers/tty/vt/vt.c:4498
Inline: False
Direct callers:
  - drivers/tty/vt/vt.c:reset_palette
  - drivers/tty/vt/vt.c:con_set_cmap
  - drivers/tty/vt/vt.c:do_unblank_screen
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:redraw_screen
```
**Symbols:**

```
ffffffff8174bd20-ffffffff8174bd7a: set_palette (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void set_palette(struct vc_data *vc);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/vt.c (ffffffff817ce4b0)
Location: drivers/tty/vt/vt.c:4503
Inline: True
Direct callers:
  - drivers/tty/vt/vt.c:reset_palette
  - drivers/tty/vt/vt.c:con_set_cmap
  - drivers/tty/vt/vt.c:do_unblank_screen
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:redraw_screen
```
**Symbols:**

```
ffffffff817ce4b0-ffffffff817ce50a: set_palette (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void set_palette(struct vc_data *vc);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/vt.c (ffffffff8190c190)
Location: drivers/tty/vt/vt.c:4503
Inline: True
Direct callers:
  - drivers/tty/vt/vt.c:reset_palette
  - drivers/tty/vt/vt.c:con_set_cmap
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:redraw_screen
```
**Symbols:**

```
ffffffff8190c190-ffffffff8190c1f0: set_palette (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void set_palette(struct vc_data *vc);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/vt.c (ffffffff81a66d30)
Location: drivers/tty/vt/vt.c:4502
Inline: True
Direct callers:
  - drivers/tty/vt/vt.c:reset_palette
  - drivers/tty/vt/vt.c:con_set_cmap
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:redraw_screen
```
**Symbols:**

```
ffffffff81a66d30-ffffffff81a66d90: set_palette (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void set_palette(struct vc_data *vc);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/vt.c (ffffffff81ab1550)
Location: drivers/tty/vt/vt.c:4450
Inline: True
Direct callers:
  - drivers/tty/vt/vt.c:reset_palette
  - drivers/tty/vt/vt.c:con_set_cmap
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:redraw_screen
```
**Symbols:**

```
ffffffff81ab1550-ffffffff81ab15b0: set_palette (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void set_palette(struct vc_data *vc);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/vt.c (ffffffff81b041b0)
Location: drivers/tty/vt/vt.c:4447
Inline: True
Direct callers:
  - drivers/tty/vt/vt.c:reset_palette
  - drivers/tty/vt/vt.c:con_set_cmap
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:redraw_screen
```
**Symbols:**

```
ffffffff81b041b0-ffffffff81b04210: set_palette (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
void set_palette(struct vc_data *vc);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/vt.c (ffff800010872888)
Location: drivers/tty/vt/vt.c:4400
Inline: True
Direct callers:
  - drivers/tty/vt/vt.c:reset_palette
  - drivers/tty/vt/vt.c:con_set_cmap
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:redraw_screen
```
**Symbols:**

```
ffff800010872888-ffff8000108728fc: set_palette (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void set_palette(struct vc_data *vc);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/vt.c (c097579c)
Location: drivers/tty/vt/vt.c:4400
Inline: True
Direct callers:
  - drivers/tty/vt/vt.c:reset_palette
  - drivers/tty/vt/vt.c:con_set_cmap
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:redraw_screen
```
**Symbols:**

```
c097579c-c0975828: set_palette (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void set_palette(struct vc_data *vc);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/vt.c (c0000000009133e0)
Location: drivers/tty/vt/vt.c:4400
Inline: True
Direct callers:
  - drivers/tty/vt/vt.c:reset_palette
  - drivers/tty/vt/vt.c:con_set_cmap
  - drivers/tty/vt/vt.c:do_unblank_screen
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:redraw_screen
```
**Symbols:**

```
c0000000009133e0-c0000000009134bc: set_palette (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void set_palette(struct vc_data *vc);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/vt.c (ffffffe00054461e)
Location: drivers/tty/vt/vt.c:4400
Inline: True
Direct callers:
  - drivers/tty/vt/vt.c:reset_palette
  - drivers/tty/vt/vt.c:con_set_cmap
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:redraw_screen
```
**Symbols:**

```
ffffffe00054461e-ffffffe000544680: set_palette (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
void set_palette(struct vc_data *vc);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/vt.c (ffffffff81660de0)
Location: drivers/tty/vt/vt.c:4400
Inline: True
Direct callers:
  - drivers/tty/vt/vt.c:reset_palette
  - drivers/tty/vt/vt.c:con_set_cmap
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:redraw_screen
```
**Symbols:**

```
ffffffff81660de0-ffffffff81660e3b: set_palette (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void set_palette(struct vc_data *vc);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/vt.c (ffffffff81641160)
Location: drivers/tty/vt/vt.c:4400
Inline: True
Direct callers:
  - drivers/tty/vt/vt.c:reset_palette
  - drivers/tty/vt/vt.c:con_set_cmap
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:redraw_screen
```
**Symbols:**

```
ffffffff81641160-ffffffff816411bb: set_palette (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void set_palette(struct vc_data *vc);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/vt.c (ffffffff8168f1c0)
Location: drivers/tty/vt/vt.c:4400
Inline: True
Direct callers:
  - drivers/tty/vt/vt.c:reset_palette
  - drivers/tty/vt/vt.c:con_set_cmap
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:redraw_screen
```
**Symbols:**

```
ffffffff8168f1c0-ffffffff8168f21b: set_palette (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void set_palette(struct vc_data *vc);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/vt.c (ffffffff816a97c0)
Location: drivers/tty/vt/vt.c:4400
Inline: True
Direct callers:
  - drivers/tty/vt/vt.c:reset_palette
  - drivers/tty/vt/vt.c:con_set_cmap
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:redraw_screen
```
**Symbols:**

```
ffffffff816a97c0-ffffffff816a981b: set_palette (STB_LOCAL)
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
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
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
