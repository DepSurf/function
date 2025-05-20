# Function: <code>save_screen</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
void save_screen(struct vc_data *vc);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/vt.c (ffffffff814f7050)
Location: drivers/tty/vt/vt.c:641
Inline: True
Inline callers:
  - drivers/tty/vt/vt.c:redraw_screen
  - drivers/tty/vt/vt.c:do_blank_screen
  - drivers/tty/vt/vt.c:do_blank_screen
Direct callers:
  - drivers/tty/vt/vt.c:con_init
  - drivers/tty/vt/vt.c:do_bind_con_driver
```
**Symbols:**

```
ffffffff814f7050-ffffffff814f7099: save_screen (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void save_screen(struct vc_data *vc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/vt.c (ffffffff81547ca0)
Location: drivers/tty/vt/vt.c:635
Inline: False
Direct callers:
  - drivers/tty/vt/vt.c:do_blank_screen
  - drivers/tty/vt/vt.c:do_blank_screen
  - drivers/tty/vt/vt.c:do_bind_con_driver
  - drivers/tty/vt/vt.c:con_init
  - drivers/tty/vt/vt.c:redraw_screen
```
**Symbols:**

```
ffffffff81547ca0-ffffffff81547cee: save_screen (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void save_screen(struct vc_data *vc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/vt.c (ffffffff815745a0)
Location: drivers/tty/vt/vt.c:624
Inline: False
Direct callers:
  - drivers/tty/vt/vt.c:do_blank_screen
  - drivers/tty/vt/vt.c:do_blank_screen
  - drivers/tty/vt/vt.c:do_bind_con_driver
  - drivers/tty/vt/vt.c:con_init
  - drivers/tty/vt/vt.c:redraw_screen
```
**Symbols:**

```
ffffffff815745a0-ffffffff815745ee: save_screen (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void save_screen(struct vc_data *vc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/vt.c (ffffffff81588480)
Location: drivers/tty/vt/vt.c:624
Inline: False
Direct callers:
  - drivers/tty/vt/vt.c:do_blank_screen
  - drivers/tty/vt/vt.c:do_blank_screen
  - drivers/tty/vt/vt.c:do_bind_con_driver
  - drivers/tty/vt/vt.c:con_init
  - drivers/tty/vt/vt.c:redraw_screen
```
**Symbols:**

```
ffffffff81588480-ffffffff815884bf: save_screen (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void save_screen(struct vc_data *vc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/vt.c (ffffffff815ecfb0)
Location: drivers/tty/vt/vt.c:626
Inline: False
Direct callers:
  - drivers/tty/vt/vt.c:do_blank_screen
  - drivers/tty/vt/vt.c:do_blank_screen
  - drivers/tty/vt/vt.c:do_bind_con_driver
  - drivers/tty/vt/vt.c:con_init
  - drivers/tty/vt/vt.c:redraw_screen
```
**Symbols:**

```
ffffffff815ecfb0-ffffffff815ecff2: save_screen (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void save_screen(struct vc_data *vc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/vt.c (ffffffff816263c0)
Location: drivers/tty/vt/vt.c:626
Inline: False
Direct callers:
  - drivers/tty/vt/vt.c:do_blank_screen
  - drivers/tty/vt/vt.c:do_blank_screen
  - drivers/tty/vt/vt.c:do_bind_con_driver
  - drivers/tty/vt/vt.c:con_init
  - drivers/tty/vt/vt.c:redraw_screen
```
**Symbols:**

```
ffffffff816263c0-ffffffff816263fa: save_screen (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void save_screen(struct vc_data *vc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/vt.c (ffffffff816438b0)
Location: drivers/tty/vt/vt.c:930
Inline: False
Direct callers:
  - drivers/tty/vt/vt.c:do_blank_screen
  - drivers/tty/vt/vt.c:do_blank_screen
  - drivers/tty/vt/vt.c:do_bind_con_driver
  - drivers/tty/vt/vt.c:con_init
  - drivers/tty/vt/vt.c:redraw_screen
```
**Symbols:**

```
ffffffff816438b0-ffffffff816438fa: save_screen (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void save_screen(struct vc_data *vc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/tty/vt/vt.c (0)
Location: drivers/tty/vt/vt.c:930
Inline: False
Direct callers:
  - drivers/tty/vt/vt.c:do_blank_screen
  - drivers/tty/vt/vt.c:do_blank_screen
  - drivers/tty/vt/vt.c:do_bind_con_driver
  - drivers/tty/vt/vt.c:con_init
  - drivers/tty/vt/vt.c:redraw_screen
```
**Symbols:**

```
ffffffff81677cc0-ffffffff81677d0b: save_screen (STB_LOCAL)
ffffffff8167f003-ffffffff8167f016: save_screen.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void save_screen(struct vc_data *vc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/vt.c (ffffffff8169a450)
Location: drivers/tty/vt/vt.c:931
Inline: False
Direct callers:
  - drivers/tty/vt/vt.c:do_blank_screen
  - drivers/tty/vt/vt.c:do_blank_screen
  - drivers/tty/vt/vt.c:do_bind_con_driver
  - drivers/tty/vt/vt.c:con_init
  - drivers/tty/vt/vt.c:redraw_screen
```
**Symbols:**

```
ffffffff8169a450-ffffffff8169a49a: save_screen (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void save_screen(struct vc_data *vc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/vt.c (ffffffff8174ca80)
Location: drivers/tty/vt/vt.c:937
Inline: False
Direct callers:
  - drivers/tty/vt/vt.c:do_blank_screen
  - drivers/tty/vt/vt.c:do_blank_screen
  - drivers/tty/vt/vt.c:con_init
  - drivers/tty/vt/vt.c:redraw_screen
```
**Symbols:**

```
ffffffff8174ca80-ffffffff8174caca: save_screen (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void save_screen(struct vc_data *vc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/vt.c (ffffffff817680b0)
Location: drivers/tty/vt/vt.c:943
Inline: False
Direct callers:
  - drivers/tty/vt/vt.c:do_blank_screen
  - drivers/tty/vt/vt.c:do_blank_screen
  - drivers/tty/vt/vt.c:con_init
  - drivers/tty/vt/vt.c:redraw_screen
```
**Symbols:**

```
ffffffff817680b0-ffffffff817680fa: save_screen (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void save_screen(struct vc_data *vc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/vt.c (ffffffff8174bcd0)
Location: drivers/tty/vt/vt.c:943
Inline: False
Direct callers:
  - drivers/tty/vt/vt.c:do_blank_screen
  - drivers/tty/vt/vt.c:do_blank_screen
  - drivers/tty/vt/vt.c:con_init
  - drivers/tty/vt/vt.c:redraw_screen
```
**Symbols:**

```
ffffffff8174bcd0-ffffffff8174bd1a: save_screen (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void save_screen(struct vc_data *vc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/vt.c (ffffffff817cd870)
Location: drivers/tty/vt/vt.c:939
Inline: False
Direct callers:
  - drivers/tty/vt/vt.c:do_blank_screen
  - drivers/tty/vt/vt.c:do_blank_screen
  - drivers/tty/vt/vt.c:con_init
  - drivers/tty/vt/vt.c:redraw_screen
```
**Symbols:**

```
ffffffff817cd870-ffffffff817cd8ba: save_screen (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void save_screen(struct vc_data *vc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/vt.c (ffffffff8190b480)
Location: drivers/tty/vt/vt.c:939
Inline: False
Direct callers:
  - drivers/tty/vt/vt.c:do_blank_screen
  - drivers/tty/vt/vt.c:do_blank_screen
  - drivers/tty/vt/vt.c:con_init
  - drivers/tty/vt/vt.c:redraw_screen
```
**Symbols:**

```
ffffffff8190b480-ffffffff8190b4d2: save_screen (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void save_screen(struct vc_data *vc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/vt.c (ffffffff81a65d40)
Location: drivers/tty/vt/vt.c:939
Inline: False
Direct callers:
  - drivers/tty/vt/vt.c:do_blank_screen
  - drivers/tty/vt/vt.c:do_blank_screen
  - drivers/tty/vt/vt.c:con_init
  - drivers/tty/vt/vt.c:redraw_screen
```
**Symbols:**

```
ffffffff81a65d40-ffffffff81a65d92: save_screen (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void save_screen(struct vc_data *vc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/vt.c (ffffffff81ab0430)
Location: drivers/tty/vt/vt.c:888
Inline: False
Direct callers:
  - drivers/tty/vt/vt.c:do_blank_screen
  - drivers/tty/vt/vt.c:do_blank_screen
  - drivers/tty/vt/vt.c:con_init
  - drivers/tty/vt/vt.c:redraw_screen
```
**Symbols:**

```
ffffffff81ab0430-ffffffff81ab0482: save_screen (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void save_screen(struct vc_data *vc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/vt.c (ffffffff81b030e0)
Location: drivers/tty/vt/vt.c:887
Inline: False
Direct callers:
  - drivers/tty/vt/vt.c:do_blank_screen
  - drivers/tty/vt/vt.c:do_blank_screen
  - drivers/tty/vt/vt.c:con_init
  - drivers/tty/vt/vt.c:redraw_screen
```
**Symbols:**

```
ffffffff81b030e0-ffffffff81b03132: save_screen (STB_LOCAL)
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
void save_screen(struct vc_data *vc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/vt.c (ffff800010871778)
Location: drivers/tty/vt/vt.c:931
Inline: False
Direct callers:
  - drivers/tty/vt/vt.c:do_blank_screen
  - drivers/tty/vt/vt.c:do_blank_screen
  - drivers/tty/vt/vt.c:do_bind_con_driver
  - drivers/tty/vt/vt.c:con_init
  - drivers/tty/vt/vt.c:redraw_screen
```
**Symbols:**

```
ffff800010871778-ffff8000108717d8: save_screen (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void save_screen(struct vc_data *vc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/vt.c (c09746e0)
Location: drivers/tty/vt/vt.c:931
Inline: False
Direct callers:
  - drivers/tty/vt/vt.c:do_blank_screen
  - drivers/tty/vt/vt.c:do_blank_screen
  - drivers/tty/vt/vt.c:do_bind_con_driver
  - drivers/tty/vt/vt.c:con_init
  - drivers/tty/vt/vt.c:redraw_screen
```
**Symbols:**

```
c09746e0-c0974758: save_screen (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void save_screen(struct vc_data *vc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/vt.c (c0000000009119e0)
Location: drivers/tty/vt/vt.c:931
Inline: False
Direct callers:
  - drivers/tty/vt/vt.c:do_blank_screen
  - drivers/tty/vt/vt.c:do_blank_screen
  - drivers/tty/vt/vt.c:do_bind_con_driver
  - drivers/tty/vt/vt.c:con_init
  - drivers/tty/vt/vt.c:redraw_screen
```
**Symbols:**

```
c0000000009119e0-c000000000911a78: save_screen (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void save_screen(struct vc_data *vc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/vt.c (ffffffe000543704)
Location: drivers/tty/vt/vt.c:931
Inline: False
Direct callers:
  - drivers/tty/vt/vt.c:do_blank_screen
  - drivers/tty/vt/vt.c:do_blank_screen
  - drivers/tty/vt/vt.c:do_bind_con_driver
  - drivers/tty/vt/vt.c:con_init
  - drivers/tty/vt/vt.c:redraw_screen
```
**Symbols:**

```
ffffffe000543704-ffffffe000543754: save_screen (STB_LOCAL)
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
void save_screen(struct vc_data *vc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/vt.c (ffffffff8165feb0)
Location: drivers/tty/vt/vt.c:931
Inline: False
Direct callers:
  - drivers/tty/vt/vt.c:do_blank_screen
  - drivers/tty/vt/vt.c:do_blank_screen
  - drivers/tty/vt/vt.c:do_bind_con_driver
  - drivers/tty/vt/vt.c:con_init
  - drivers/tty/vt/vt.c:redraw_screen
```
**Symbols:**

```
ffffffff8165feb0-ffffffff8165fefa: save_screen (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void save_screen(struct vc_data *vc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/vt.c (ffffffff81640230)
Location: drivers/tty/vt/vt.c:931
Inline: False
Direct callers:
  - drivers/tty/vt/vt.c:do_blank_screen
  - drivers/tty/vt/vt.c:do_blank_screen
  - drivers/tty/vt/vt.c:do_bind_con_driver
  - drivers/tty/vt/vt.c:con_init
  - drivers/tty/vt/vt.c:redraw_screen
```
**Symbols:**

```
ffffffff81640230-ffffffff8164027a: save_screen (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void save_screen(struct vc_data *vc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/vt.c (ffffffff8168e290)
Location: drivers/tty/vt/vt.c:931
Inline: False
Direct callers:
  - drivers/tty/vt/vt.c:do_blank_screen
  - drivers/tty/vt/vt.c:do_blank_screen
  - drivers/tty/vt/vt.c:do_bind_con_driver
  - drivers/tty/vt/vt.c:con_init
  - drivers/tty/vt/vt.c:redraw_screen
```
**Symbols:**

```
ffffffff8168e290-ffffffff8168e2da: save_screen (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void save_screen(struct vc_data *vc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/vt.c (ffffffff816a8890)
Location: drivers/tty/vt/vt.c:931
Inline: False
Direct callers:
  - drivers/tty/vt/vt.c:do_blank_screen
  - drivers/tty/vt/vt.c:do_blank_screen
  - drivers/tty/vt/vt.c:do_bind_con_driver
  - drivers/tty/vt/vt.c:con_init
  - drivers/tty/vt/vt.c:redraw_screen
```
**Symbols:**

```
ffffffff816a8890-ffffffff816a88da: save_screen (STB_LOCAL)
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
