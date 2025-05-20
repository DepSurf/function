# Function: <code>set_console</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int set_console(int nr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/vt.c (ffffffff814fa5e0)
Location: drivers/tty/vt/vt.c:2486
Inline: False
Direct callers:
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_move_to_console
  - drivers/tty/vt/keyboard.c:k_cons
  - drivers/tty/vt/keyboard.c:fn_lastcons
  - drivers/tty/vt/keyboard.c:fn_inc_console
  - drivers/tty/vt/keyboard.c:fn_dec_console
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:do_con_trol
```
**Symbols:**

```
ffffffff814fa5e0-ffffffff814fa654: set_console (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int set_console(int nr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/vt.c (ffffffff8154b230)
Location: drivers/tty/vt/vt.c:2485
Inline: False
Direct callers:
  - drivers/tty/vt/vt_ioctl.c:vt_move_to_console
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/keyboard.c:k_cons
  - drivers/tty/vt/keyboard.c:fn_inc_console
  - drivers/tty/vt/keyboard.c:fn_dec_console
  - drivers/tty/vt/keyboard.c:fn_lastcons
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:do_con_trol
```
**Symbols:**

```
ffffffff8154b230-ffffffff8154b2a8: set_console (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int set_console(int nr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/vt.c (ffffffff81577a60)
Location: drivers/tty/vt/vt.c:2484
Inline: False
Direct callers:
  - drivers/tty/vt/vt_ioctl.c:vt_move_to_console
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/keyboard.c:k_cons
  - drivers/tty/vt/keyboard.c:fn_inc_console
  - drivers/tty/vt/keyboard.c:fn_dec_console
  - drivers/tty/vt/keyboard.c:fn_lastcons
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:do_con_trol
```
**Symbols:**

```
ffffffff81577a60-ffffffff81577ad8: set_console (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int set_console(int nr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/vt.c (ffffffff8158b960)
Location: drivers/tty/vt/vt.c:2493
Inline: False
Direct callers:
  - drivers/tty/vt/vt_ioctl.c:vt_move_to_console
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/keyboard.c:k_cons
  - drivers/tty/vt/keyboard.c:fn_inc_console
  - drivers/tty/vt/keyboard.c:fn_dec_console
  - drivers/tty/vt/keyboard.c:fn_lastcons
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:do_con_trol
```
**Symbols:**

```
ffffffff8158b960-ffffffff8158b9d4: set_console (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int set_console(int nr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/vt.c (ffffffff815f0400)
Location: drivers/tty/vt/vt.c:2497
Inline: False
Direct callers:
  - drivers/tty/vt/vt_ioctl.c:vt_move_to_console
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/keyboard.c:k_cons
  - drivers/tty/vt/keyboard.c:fn_inc_console
  - drivers/tty/vt/keyboard.c:fn_dec_console
  - drivers/tty/vt/keyboard.c:fn_lastcons
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:do_con_trol
```
**Symbols:**

```
ffffffff815f0400-ffffffff815f0474: set_console (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
int set_console(int nr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/vt.c (ffffffff816298c0)
Location: drivers/tty/vt/vt.c:2495
Inline: True
Direct callers:
  - drivers/tty/vt/vt_ioctl.c:vt_move_to_console
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/keyboard.c:k_cons
  - drivers/tty/vt/keyboard.c:fn_inc_console
  - drivers/tty/vt/keyboard.c:fn_dec_console
  - drivers/tty/vt/keyboard.c:fn_lastcons
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:do_con_trol
```
**Symbols:**

```
ffffffff816298c0-ffffffff81629934: set_console (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int set_console(int nr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/vt.c (ffffffff81647580)
Location: drivers/tty/vt/vt.c:2827
Inline: True
Direct callers:
  - drivers/tty/vt/vt_ioctl.c:vt_move_to_console
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/keyboard.c:k_cons
  - drivers/tty/vt/keyboard.c:fn_inc_console
  - drivers/tty/vt/keyboard.c:fn_dec_console
  - drivers/tty/vt/keyboard.c:fn_lastcons
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:do_con_trol
```
**Symbols:**

```
ffffffff81647580-ffffffff816475f4: set_console (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
int set_console(int nr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/vt.c (ffffffff8167bc10)
Location: drivers/tty/vt/vt.c:2862
Inline: True
Direct callers:
  - drivers/tty/vt/vt_ioctl.c:vt_move_to_console
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/keyboard.c:k_cons
  - drivers/tty/vt/keyboard.c:fn_inc_console
  - drivers/tty/vt/keyboard.c:fn_dec_console
  - drivers/tty/vt/keyboard.c:fn_lastcons
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:do_con_trol
```
**Symbols:**

```
ffffffff8167bc10-ffffffff8167bc85: set_console (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int set_console(int nr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/vt.c (ffffffff8169e430)
Location: drivers/tty/vt/vt.c:2886
Inline: True
Direct callers:
  - drivers/tty/vt/vt_ioctl.c:vt_move_to_console
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/keyboard.c:k_cons
  - drivers/tty/vt/keyboard.c:fn_inc_console
  - drivers/tty/vt/keyboard.c:fn_dec_console
  - drivers/tty/vt/keyboard.c:fn_lastcons
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:do_con_trol
```
**Symbols:**

```
ffffffff8169e430-ffffffff8169e4a5: set_console (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int set_console(int nr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/vt.c (ffffffff817512b0)
Location: drivers/tty/vt/vt.c:2895
Inline: False
Direct callers:
  - drivers/tty/vt/vt_ioctl.c:vt_move_to_console
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/keyboard.c:k_cons
  - drivers/tty/vt/keyboard.c:fn_inc_console
  - drivers/tty/vt/keyboard.c:fn_dec_console
  - drivers/tty/vt/keyboard.c:fn_lastcons
  - drivers/tty/vt/vt.c:setterm_command
```
**Symbols:**

```
ffffffff817512b0-ffffffff81751325: set_console (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int set_console(int nr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/vt.c (ffffffff8176cd00)
Location: drivers/tty/vt/vt.c:2984
Inline: False
Direct callers:
  - drivers/tty/vt/vt_ioctl.c:vt_move_to_console
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_setactivate
  - drivers/tty/vt/keyboard.c:k_cons
  - drivers/tty/vt/keyboard.c:fn_inc_console
  - drivers/tty/vt/keyboard.c:fn_dec_console
  - drivers/tty/vt/keyboard.c:fn_lastcons
  - drivers/tty/vt/vt.c:setterm_command
```
**Symbols:**

```
ffffffff8176cd00-ffffffff8176cd75: set_console (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int set_console(int nr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/vt.c (ffffffff81750890)
Location: drivers/tty/vt/vt.c:2984
Inline: False
Direct callers:
  - drivers/tty/vt/vt_ioctl.c:vt_move_to_console
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/keyboard.c:k_cons
  - drivers/tty/vt/keyboard.c:fn_inc_console
  - drivers/tty/vt/keyboard.c:fn_dec_console
  - drivers/tty/vt/keyboard.c:fn_lastcons
```
**Symbols:**

```
ffffffff81750890-ffffffff81750905: set_console (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int set_console(int nr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/tty/vt/vt.c (0)
Location: drivers/tty/vt/vt.c:3013
Inline: False
Direct callers:
  - drivers/tty/vt/vt_ioctl.c:vt_move_to_console
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/keyboard.c:k_cons
  - drivers/tty/vt/keyboard.c:fn_inc_console
  - drivers/tty/vt/keyboard.c:fn_dec_console
  - drivers/tty/vt/keyboard.c:fn_lastcons
```
**Symbols:**

```
ffffffff81cf977c-ffffffff81cf9791: set_console.cold (STB_LOCAL)
ffffffff817d31f0-ffffffff817d32c0: set_console (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int set_console(int nr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/tty/vt/vt.c (0)
Location: drivers/tty/vt/vt.c:3013
Inline: False
Direct callers:
  - drivers/tty/vt/vt_ioctl.c:vt_move_to_console
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/keyboard.c:k_cons
  - drivers/tty/vt/keyboard.c:fn_inc_console
  - drivers/tty/vt/keyboard.c:fn_dec_console
  - drivers/tty/vt/keyboard.c:fn_lastcons
```
**Symbols:**

```
ffffffff81ec199e-ffffffff81ec19b3: set_console.cold (STB_LOCAL)
ffffffff819111e0-ffffffff819112c8: set_console (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int set_console(int nr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/tty/vt/vt.c (0)
Location: drivers/tty/vt/vt.c:3013
Inline: False
Direct callers:
  - drivers/tty/vt/vt_ioctl.c:vt_move_to_console
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/keyboard.c:k_cons
  - drivers/tty/vt/keyboard.c:fn_inc_console
  - drivers/tty/vt/keyboard.c:fn_dec_console
  - drivers/tty/vt/keyboard.c:fn_lastcons
```
**Symbols:**

```
ffffffff82095a9c-ffffffff82095ab1: set_console.cold (STB_LOCAL)
ffffffff81a6c100-ffffffff81a6c1e8: set_console (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int set_console(int nr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/tty/vt/vt.c (0)
Location: drivers/tty/vt/vt.c:2967
Inline: False
Direct callers:
  - drivers/tty/vt/vt_ioctl.c:vt_move_to_console
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/keyboard.c:k_cons
  - drivers/tty/vt/keyboard.c:fn_inc_console
  - drivers/tty/vt/keyboard.c:fn_dec_console
  - drivers/tty/vt/keyboard.c:fn_lastcons
```
**Symbols:**

```
ffffffff821168dc-ffffffff821168f1: set_console.cold (STB_LOCAL)
ffffffff81ab6820-ffffffff81ab6908: set_console (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int set_console(int nr);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/tty/vt/vt.c (0)
Location: drivers/tty/vt/vt.c:2966
Inline: False
Direct callers:
  - drivers/tty/vt/vt_ioctl.c:vt_move_to_console
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/keyboard.c:k_cons
  - drivers/tty/vt/keyboard.c:fn_inc_console
  - drivers/tty/vt/keyboard.c:fn_dec_console
  - drivers/tty/vt/keyboard.c:fn_lastcons
```
**Symbols:**

```
ffffffff821f4630-ffffffff821f4645: set_console.cold (STB_LOCAL)
ffffffff81b09500-ffffffff81b095e8: set_console (STB_GLOBAL)
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
int set_console(int nr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/vt.c (ffff800010875c18)
Location: drivers/tty/vt/vt.c:2886
Inline: True
Direct callers:
  - drivers/tty/vt/vt_ioctl.c:vt_move_to_console
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/keyboard.c:k_cons
  - drivers/tty/vt/keyboard.c:fn_inc_console
  - drivers/tty/vt/keyboard.c:fn_dec_console
  - drivers/tty/vt/keyboard.c:fn_lastcons
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:do_con_trol
```
**Symbols:**

```
ffff800010875c18-ffff800010875cb8: set_console (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int set_console(int nr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/vt.c (c09789fc)
Location: drivers/tty/vt/vt.c:2886
Inline: True
Direct callers:
  - drivers/tty/vt/vt_ioctl.c:vt_move_to_console
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/keyboard.c:k_cons
  - drivers/tty/vt/keyboard.c:fn_inc_console
  - drivers/tty/vt/keyboard.c:fn_dec_console
  - drivers/tty/vt/keyboard.c:fn_lastcons
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:do_con_trol
```
**Symbols:**

```
c09789fc-c0978aa0: set_console (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
int set_console(int nr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/vt.c (c000000000917790)
Location: drivers/tty/vt/vt.c:2886
Inline: True
Direct callers:
  - drivers/tty/vt/vt_ioctl.c:vt_move_to_console
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/keyboard.c:k_cons
  - drivers/tty/vt/keyboard.c:fn_inc_console
  - drivers/tty/vt/keyboard.c:fn_dec_console
  - drivers/tty/vt/keyboard.c:fn_lastcons
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:do_con_trol
```
**Symbols:**

```
c000000000917790-c000000000917868: set_console (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
int set_console(int nr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/vt.c (ffffffe0005472d0)
Location: drivers/tty/vt/vt.c:2886
Inline: True
Direct callers:
  - drivers/tty/vt/vt_ioctl.c:vt_move_to_console
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/keyboard.c:k_cons
  - drivers/tty/vt/keyboard.c:fn_inc_console
  - drivers/tty/vt/keyboard.c:fn_dec_console
  - drivers/tty/vt/keyboard.c:fn_lastcons
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:do_con_trol
```
**Symbols:**

```
ffffffe0005472d0-ffffffe00054736e: set_console (STB_GLOBAL)
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
int set_console(int nr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/vt.c (ffffffff81663e90)
Location: drivers/tty/vt/vt.c:2886
Inline: True
Direct callers:
  - drivers/tty/vt/vt_ioctl.c:vt_move_to_console
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/keyboard.c:k_cons
  - drivers/tty/vt/keyboard.c:fn_inc_console
  - drivers/tty/vt/keyboard.c:fn_dec_console
  - drivers/tty/vt/keyboard.c:fn_lastcons
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:do_con_trol
```
**Symbols:**

```
ffffffff81663e90-ffffffff81663f05: set_console (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int set_console(int nr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/vt.c (ffffffff81644210)
Location: drivers/tty/vt/vt.c:2886
Inline: True
Direct callers:
  - drivers/tty/vt/vt_ioctl.c:vt_move_to_console
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/keyboard.c:k_cons
  - drivers/tty/vt/keyboard.c:fn_inc_console
  - drivers/tty/vt/keyboard.c:fn_dec_console
  - drivers/tty/vt/keyboard.c:fn_lastcons
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:do_con_trol
```
**Symbols:**

```
ffffffff81644210-ffffffff81644285: set_console (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int set_console(int nr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/vt.c (ffffffff81692270)
Location: drivers/tty/vt/vt.c:2886
Inline: True
Direct callers:
  - drivers/tty/vt/vt_ioctl.c:vt_move_to_console
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/keyboard.c:k_cons
  - drivers/tty/vt/keyboard.c:fn_inc_console
  - drivers/tty/vt/keyboard.c:fn_dec_console
  - drivers/tty/vt/keyboard.c:fn_lastcons
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:do_con_trol
```
**Symbols:**

```
ffffffff81692270-ffffffff816922e5: set_console (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int set_console(int nr);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/vt.c (ffffffff816ac860)
Location: drivers/tty/vt/vt.c:2886
Inline: True
Direct callers:
  - drivers/tty/vt/vt_ioctl.c:vt_move_to_console
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/vt_ioctl.c:vt_ioctl
  - drivers/tty/vt/keyboard.c:k_cons
  - drivers/tty/vt/keyboard.c:fn_inc_console
  - drivers/tty/vt/keyboard.c:fn_dec_console
  - drivers/tty/vt/keyboard.c:fn_lastcons
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:do_con_trol
```
**Symbols:**

```
ffffffff816ac860-ffffffff816ac8d5: set_console (STB_GLOBAL)
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
