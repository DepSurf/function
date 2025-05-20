# Function: <code>gotoxy</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void gotoxy(struct vc_data *vc, int new_x, int new_y);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/vt.c (ffffffff814f6cd0)
Location: drivers/tty/vt/vt.c:1069
Inline: False
Direct callers:
  - drivers/tty/vt/vt.c:restore_cur
  - drivers/tty/vt/vt.c:reset_terminal
  - drivers/tty/vt/vt.c:vc_do_resize
  - drivers/tty/vt/vt.c:con_init
  - drivers/tty/vt/vt.c:set_mode
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:putconsxy
```
**Symbols:**

```
ffffffff814f6cd0-ffffffff814f6d7b: gotoxy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void gotoxy(struct vc_data *vc, int new_x, int new_y);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/vt.c (ffffffff81547810)
Location: drivers/tty/vt/vt.c:1075
Inline: False
Direct callers:
  - drivers/tty/vt/vt.c:putconsxy
  - drivers/tty/vt/vt.c:con_init
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:reset_terminal
  - drivers/tty/vt/vt.c:restore_cur
  - drivers/tty/vt/vt.c:set_mode
  - drivers/tty/vt/vt.c:vc_do_resize
```
**Symbols:**

```
ffffffff81547810-ffffffff815478bb: gotoxy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void gotoxy(struct vc_data *vc, int new_x, int new_y);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/vt.c (ffffffff81574010)
Location: drivers/tty/vt/vt.c:1069
Inline: False
Direct callers:
  - drivers/tty/vt/vt.c:putconsxy
  - drivers/tty/vt/vt.c:con_init
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:reset_terminal
  - drivers/tty/vt/vt.c:restore_cur
  - drivers/tty/vt/vt.c:set_mode
  - drivers/tty/vt/vt.c:vc_do_resize
```
**Symbols:**

```
ffffffff81574010-ffffffff815740bb: gotoxy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void gotoxy(struct vc_data *vc, int new_x, int new_y);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/vt.c (ffffffff81587fc0)
Location: drivers/tty/vt/vt.c:1077
Inline: False
Direct callers:
  - drivers/tty/vt/vt.c:putconsxy
  - drivers/tty/vt/vt.c:con_init
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:reset_terminal
  - drivers/tty/vt/vt.c:restore_cur
  - drivers/tty/vt/vt.c:set_mode
  - drivers/tty/vt/vt.c:vc_do_resize
```
**Symbols:**

```
ffffffff81587fc0-ffffffff8158806b: gotoxy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void gotoxy(struct vc_data *vc, int new_x, int new_y);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/vt.c (ffffffff815ecad0)
Location: drivers/tty/vt/vt.c:1079
Inline: False
Direct callers:
  - drivers/tty/vt/vt.c:putconsxy
  - drivers/tty/vt/vt.c:con_init
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:reset_terminal
  - drivers/tty/vt/vt.c:restore_cur
  - drivers/tty/vt/vt.c:set_mode
  - drivers/tty/vt/vt.c:vc_do_resize
```
**Symbols:**

```
ffffffff815ecad0-ffffffff815ecb7b: gotoxy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void gotoxy(struct vc_data *vc, int new_x, int new_y);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/vt.c (ffffffff81625d40)
Location: drivers/tty/vt/vt.c:1079
Inline: False
Direct callers:
  - drivers/tty/vt/vt.c:putconsxy
  - drivers/tty/vt/vt.c:con_init
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:reset_terminal
  - drivers/tty/vt/vt.c:restore_cur
  - drivers/tty/vt/vt.c:set_mode
  - drivers/tty/vt/vt.c:vc_do_resize
```
**Symbols:**

```
ffffffff81625d40-ffffffff81625dda: gotoxy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void gotoxy(struct vc_data *vc, int new_x, int new_y);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/vt.c (ffffffff81643230)
Location: drivers/tty/vt/vt.c:1401
Inline: False
Direct callers:
  - drivers/tty/vt/vt.c:putconsxy
  - drivers/tty/vt/vt.c:con_init
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:reset_terminal
  - drivers/tty/vt/vt.c:restore_cur
  - drivers/tty/vt/vt.c:set_mode
  - drivers/tty/vt/vt.c:vc_do_resize
```
**Symbols:**

```
ffffffff81643230-ffffffff816432ca: gotoxy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void gotoxy(struct vc_data *vc, int new_x, int new_y);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/vt.c (ffffffff816776f0)
Location: drivers/tty/vt/vt.c:1410
Inline: False
Direct callers:
  - drivers/tty/vt/vt.c:putconsxy
  - drivers/tty/vt/vt.c:con_init
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:reset_terminal
  - drivers/tty/vt/vt.c:restore_cur
  - drivers/tty/vt/vt.c:set_mode
  - drivers/tty/vt/vt.c:vc_do_resize
```
**Symbols:**

```
ffffffff816776f0-ffffffff8167779d: gotoxy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void gotoxy(struct vc_data *vc, int new_x, int new_y);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/vt.c (ffffffff81699e80)
Location: drivers/tty/vt/vt.c:1434
Inline: False
Direct callers:
  - drivers/tty/vt/vt.c:putconsxy
  - drivers/tty/vt/vt.c:con_init
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:reset_terminal
  - drivers/tty/vt/vt.c:restore_cur
  - drivers/tty/vt/vt.c:set_mode
  - drivers/tty/vt/vt.c:vc_do_resize
```
**Symbols:**

```
ffffffff81699e80-ffffffff81699f2d: gotoxy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void gotoxy(struct vc_data *vc, int new_x, int new_y);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/vt.c (ffffffff81753dde)
Location: drivers/tty/vt/vt.c:1447
Inline: True
Inline callers:
  - drivers/tty/vt/vt.c:putconsxy
Direct callers:
  - drivers/tty/vt/vt.c:con_init
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:reset_terminal
  - drivers/tty/vt/vt.c:restore_cur
  - drivers/tty/vt/vt.c:set_mode
  - drivers/tty/vt/vt.c:vc_do_resize
```
**Symbols:**

```
ffffffff8174c3d0-ffffffff8174c47d: gotoxy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void gotoxy(struct vc_data *vc, int new_x, int new_y);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/vt.c (ffffffff8176f25e)
Location: drivers/tty/vt/vt.c:1446
Inline: True
Inline callers:
  - drivers/tty/vt/vt.c:putconsxy
Direct callers:
  - drivers/tty/vt/vt.c:con_init
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:reset_terminal
  - drivers/tty/vt/vt.c:restore_cur
  - drivers/tty/vt/vt.c:set_mode
  - drivers/tty/vt/vt.c:vc_do_resize
```
**Symbols:**

```
ffffffff81767ac0-ffffffff81767b6d: gotoxy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void gotoxy(struct vc_data *vc, int new_x, int new_y);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/vt.c (ffffffff81752d4e)
Location: drivers/tty/vt/vt.c:1446
Inline: True
Inline callers:
  - drivers/tty/vt/vt.c:putconsxy
Direct callers:
  - drivers/tty/vt/vt.c:con_init
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:reset_terminal
  - drivers/tty/vt/vt.c:vc_do_resize
```
**Symbols:**

```
ffffffff8174b710-ffffffff8174b79b: gotoxy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void gotoxy(struct vc_data *vc, int new_x, int new_y);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/vt.c (ffffffff817d60fe)
Location: drivers/tty/vt/vt.c:1452
Inline: True
Inline callers:
  - drivers/tty/vt/vt.c:putconsxy
Direct callers:
  - drivers/tty/vt/vt.c:con_init
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:reset_terminal
  - drivers/tty/vt/vt.c:vc_do_resize
```
**Symbols:**

```
ffffffff817cd190-ffffffff817cd21b: gotoxy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void gotoxy(struct vc_data *vc, int new_x, int new_y);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/vt.c (ffffffff819140d8)
Location: drivers/tty/vt/vt.c:1452
Inline: True
Inline callers:
  - drivers/tty/vt/vt.c:putconsxy
Direct callers:
  - drivers/tty/vt/vt.c:con_init
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:reset_terminal
  - drivers/tty/vt/vt.c:vc_do_resize
```
**Symbols:**

```
ffffffff8190ad00-ffffffff8190ad9f: gotoxy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void gotoxy(struct vc_data *vc, int new_x, int new_y);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/vt.c (ffffffff81a6f138)
Location: drivers/tty/vt/vt.c:1452
Inline: True
Inline callers:
  - drivers/tty/vt/vt.c:putconsxy
Direct callers:
  - drivers/tty/vt/vt.c:con_init
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:reset_terminal
  - drivers/tty/vt/vt.c:vc_do_resize
```
**Symbols:**

```
ffffffff81a654f0-ffffffff81a6558f: gotoxy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void gotoxy(struct vc_data *vc, int new_x, int new_y);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/vt.c (ffffffff81ab98e8)
Location: drivers/tty/vt/vt.c:1407
Inline: True
Inline callers:
  - drivers/tty/vt/vt.c:putconsxy
Direct callers:
  - drivers/tty/vt/vt.c:con_init
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:reset_terminal
  - drivers/tty/vt/vt.c:vc_do_resize
```
**Symbols:**

```
ffffffff81aafbc0-ffffffff81aafc5f: gotoxy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void gotoxy(struct vc_data *vc, int new_x, int new_y);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/vt.c (ffffffff81b0c618)
Location: drivers/tty/vt/vt.c:1406
Inline: True
Inline callers:
  - drivers/tty/vt/vt.c:putconsxy
Direct callers:
  - drivers/tty/vt/vt.c:con_init
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:reset_terminal
  - drivers/tty/vt/vt.c:vc_do_resize
```
**Symbols:**

```
ffffffff81b02870-ffffffff81b0290f: gotoxy (STB_LOCAL)
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
void gotoxy(struct vc_data *vc, int new_x, int new_y);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/vt.c (ffff800010870fa8)
Location: drivers/tty/vt/vt.c:1434
Inline: False
Direct callers:
  - drivers/tty/vt/vt.c:putconsxy
  - drivers/tty/vt/vt.c:con_init
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:reset_terminal
  - drivers/tty/vt/vt.c:restore_cur
  - drivers/tty/vt/vt.c:set_mode
  - drivers/tty/vt/vt.c:vc_do_resize
```
**Symbols:**

```
ffff800010870fa8-ffff800010871084: gotoxy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void gotoxy(struct vc_data *vc, int new_x, int new_y);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/vt.c (c0974088)
Location: drivers/tty/vt/vt.c:1434
Inline: False
Direct callers:
  - drivers/tty/vt/vt.c:putconsxy
  - drivers/tty/vt/vt.c:con_init
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:reset_terminal
  - drivers/tty/vt/vt.c:restore_cur
  - drivers/tty/vt/vt.c:set_mode
  - drivers/tty/vt/vt.c:vc_do_resize
```
**Symbols:**

```
c0974088-c0974124: gotoxy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void gotoxy(struct vc_data *vc, int new_x, int new_y);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/vt.c (c0000000009110c0)
Location: drivers/tty/vt/vt.c:1434
Inline: False
Direct callers:
  - drivers/tty/vt/vt.c:putconsxy
  - drivers/tty/vt/vt.c:con_init
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:reset_terminal
  - drivers/tty/vt/vt.c:restore_cur
  - drivers/tty/vt/vt.c:set_mode
  - drivers/tty/vt/vt.c:vc_do_resize
```
**Symbols:**

```
c0000000009110c0-c0000000009111f4: gotoxy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void gotoxy(struct vc_data *vc, int new_x, int new_y);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/vt.c (ffffffe000542fd6)
Location: drivers/tty/vt/vt.c:1434
Inline: False
Direct callers:
  - drivers/tty/vt/vt.c:putconsxy
  - drivers/tty/vt/vt.c:con_init
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:reset_terminal
  - drivers/tty/vt/vt.c:restore_cur
  - drivers/tty/vt/vt.c:set_mode
  - drivers/tty/vt/vt.c:vc_do_resize
```
**Symbols:**

```
ffffffe000542fd6-ffffffe0005430a6: gotoxy (STB_LOCAL)
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
void gotoxy(struct vc_data *vc, int new_x, int new_y);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/vt.c (ffffffff8165f8e0)
Location: drivers/tty/vt/vt.c:1434
Inline: False
Direct callers:
  - drivers/tty/vt/vt.c:putconsxy
  - drivers/tty/vt/vt.c:con_init
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:reset_terminal
  - drivers/tty/vt/vt.c:restore_cur
  - drivers/tty/vt/vt.c:set_mode
  - drivers/tty/vt/vt.c:vc_do_resize
```
**Symbols:**

```
ffffffff8165f8e0-ffffffff8165f98d: gotoxy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void gotoxy(struct vc_data *vc, int new_x, int new_y);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/vt.c (ffffffff8163fc60)
Location: drivers/tty/vt/vt.c:1434
Inline: False
Direct callers:
  - drivers/tty/vt/vt.c:putconsxy
  - drivers/tty/vt/vt.c:con_init
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:reset_terminal
  - drivers/tty/vt/vt.c:restore_cur
  - drivers/tty/vt/vt.c:set_mode
  - drivers/tty/vt/vt.c:vc_do_resize
```
**Symbols:**

```
ffffffff8163fc60-ffffffff8163fd0d: gotoxy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void gotoxy(struct vc_data *vc, int new_x, int new_y);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/vt.c (ffffffff8168dcc0)
Location: drivers/tty/vt/vt.c:1434
Inline: False
Direct callers:
  - drivers/tty/vt/vt.c:putconsxy
  - drivers/tty/vt/vt.c:con_init
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:reset_terminal
  - drivers/tty/vt/vt.c:restore_cur
  - drivers/tty/vt/vt.c:set_mode
  - drivers/tty/vt/vt.c:vc_do_resize
```
**Symbols:**

```
ffffffff8168dcc0-ffffffff8168dd6d: gotoxy (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void gotoxy(struct vc_data *vc, int new_x, int new_y);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/vt.c (ffffffff816a82c0)
Location: drivers/tty/vt/vt.c:1434
Inline: False
Direct callers:
  - drivers/tty/vt/vt.c:putconsxy
  - drivers/tty/vt/vt.c:con_init
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:reset_terminal
  - drivers/tty/vt/vt.c:restore_cur
  - drivers/tty/vt/vt.c:set_mode
  - drivers/tty/vt/vt.c:vc_do_resize
```
**Symbols:**

```
ffffffff816a82c0-ffffffff816a836d: gotoxy (STB_LOCAL)
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
