# Function: <code>poke_blanked_console</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
void poke_blanked_console();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/vt.c (ffffffff814fa8b0)
Location: drivers/tty/vt/vt.c:3963
Inline: True
Direct callers:
  - drivers/tty/vt/selection.c:set_selection
  - drivers/tty/vt/selection.c:paste_selection
  - drivers/tty/vt/vt.c:console_callback
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:do_con_trol
```
**Symbols:**

```
ffffffff814fa8b0-ffffffff814fa96e: poke_blanked_console (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void poke_blanked_console();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/vt.c (ffffffff8154b520)
Location: drivers/tty/vt/vt.c:3962
Inline: True
Direct callers:
  - drivers/tty/vt/selection.c:paste_selection
  - drivers/tty/vt/selection.c:set_selection
  - drivers/tty/vt/vt.c:console_callback
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:do_con_trol
```
**Symbols:**

```
ffffffff8154b520-ffffffff8154b5df: poke_blanked_console (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void poke_blanked_console();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/vt.c (ffffffff81577d50)
Location: drivers/tty/vt/vt.c:3957
Inline: True
Direct callers:
  - drivers/tty/vt/selection.c:paste_selection
  - drivers/tty/vt/selection.c:set_selection
  - drivers/tty/vt/vt.c:console_callback
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:do_con_trol
```
**Symbols:**

```
ffffffff81577d50-ffffffff81577e0f: poke_blanked_console (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void poke_blanked_console();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/vt.c (ffffffff8158bc50)
Location: drivers/tty/vt/vt.c:3966
Inline: True
Direct callers:
  - drivers/tty/vt/selection.c:paste_selection
  - drivers/tty/vt/selection.c:set_selection
  - drivers/tty/vt/vt.c:console_callback
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:do_con_trol
```
**Symbols:**

```
ffffffff8158bc50-ffffffff8158bd05: poke_blanked_console (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void poke_blanked_console();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/vt.c (ffffffff815f06f0)
Location: drivers/tty/vt/vt.c:3969
Inline: True
Direct callers:
  - drivers/tty/vt/selection.c:paste_selection
  - drivers/tty/vt/selection.c:set_selection
  - drivers/tty/vt/vt.c:console_callback
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:do_con_trol
```
**Symbols:**

```
ffffffff815f06f0-ffffffff815f07a5: poke_blanked_console (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void poke_blanked_console();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/vt.c (ffffffff81629bb0)
Location: drivers/tty/vt/vt.c:3967
Inline: False
Direct callers:
  - drivers/tty/vt/selection.c:paste_selection
  - drivers/tty/vt/selection.c:set_selection
  - drivers/tty/vt/vt.c:console_callback
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:do_con_trol
```
**Symbols:**

```
ffffffff81629bb0-ffffffff81629c58: poke_blanked_console (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void poke_blanked_console();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/vt.c (ffffffff816478d0)
Location: drivers/tty/vt/vt.c:4281
Inline: False
Direct callers:
  - drivers/tty/vt/selection.c:paste_selection
  - drivers/tty/vt/selection.c:set_selection
  - drivers/tty/vt/vt.c:console_callback
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:do_con_trol
```
**Symbols:**

```
ffffffff816478d0-ffffffff81647984: poke_blanked_console (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void poke_blanked_console();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/tty/vt/vt.c (0)
Location: drivers/tty/vt/vt.c:4337
Inline: False
Direct callers:
  - drivers/tty/vt/selection.c:paste_selection
  - drivers/tty/vt/selection.c:set_selection_kernel
  - drivers/tty/vt/vt.c:console_callback
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:do_con_trol
```
**Symbols:**

```
ffffffff8167f2a2-ffffffff8167f2b5: poke_blanked_console.cold (STB_LOCAL)
ffffffff8167bf70-ffffffff8167c026: poke_blanked_console (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void poke_blanked_console();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/vt.c (ffffffff8169e780)
Location: drivers/tty/vt/vt.c:4368
Inline: True
Direct callers:
  - drivers/tty/vt/selection.c:paste_selection
  - drivers/tty/vt/selection.c:__set_selection_kernel
  - drivers/tty/vt/vt.c:console_callback
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:do_con_trol
```
**Symbols:**

```
ffffffff8169e780-ffffffff8169e834: poke_blanked_console (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void poke_blanked_console();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/vt.c (ffffffff81751610)
Location: drivers/tty/vt/vt.c:4378
Inline: False
Direct callers:
  - drivers/tty/vt/selection.c:paste_selection
  - drivers/tty/vt/selection.c:vc_selection
  - drivers/tty/vt/vt.c:console_callback
  - drivers/tty/vt/vt.c:setterm_command
  - drivers/tty/vt/vt.c:setterm_command
```
**Symbols:**

```
ffffffff81751610-ffffffff817516c4: poke_blanked_console (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void poke_blanked_console();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/vt.c (ffffffff8176d060)
Location: drivers/tty/vt/vt.c:4466
Inline: False
Direct callers:
  - drivers/tty/vt/selection.c:paste_selection
  - drivers/tty/vt/selection.c:vc_selection
  - drivers/tty/vt/vt.c:console_callback
  - drivers/tty/vt/vt.c:setterm_command
  - drivers/tty/vt/vt.c:setterm_command
```
**Symbols:**

```
ffffffff8176d060-ffffffff8176d114: poke_blanked_console (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void poke_blanked_console();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/vt.c (ffffffff81750be0)
Location: drivers/tty/vt/vt.c:4466
Inline: False
Direct callers:
  - drivers/tty/vt/selection.c:paste_selection
  - drivers/tty/vt/selection.c:set_selection_kernel
  - drivers/tty/vt/vt.c:console_callback
```
**Symbols:**

```
ffffffff81750be0-ffffffff81750c94: poke_blanked_console (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void poke_blanked_console();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/vt.c (ffffffff817d35d0)
Location: drivers/tty/vt/vt.c:4471
Inline: False
Direct callers:
  - drivers/tty/vt/selection.c:paste_selection
  - drivers/tty/vt/selection.c:set_selection_kernel
  - drivers/tty/vt/vt.c:console_callback
```
**Symbols:**

```
ffffffff817d35d0-ffffffff817d36c5: poke_blanked_console (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void poke_blanked_console();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/vt.c (ffffffff81911620)
Location: drivers/tty/vt/vt.c:4471
Inline: False
Direct callers:
  - drivers/tty/vt/selection.c:paste_selection
  - drivers/tty/vt/selection.c:set_selection_kernel
  - drivers/tty/vt/vt.c:console_callback
```
**Symbols:**

```
ffffffff81911620-ffffffff81911738: poke_blanked_console (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void poke_blanked_console();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/vt.c (ffffffff81a6c560)
Location: drivers/tty/vt/vt.c:4470
Inline: False
Direct callers:
  - drivers/tty/vt/selection.c:paste_selection
  - drivers/tty/vt/selection.c:set_selection_kernel
  - drivers/tty/vt/vt.c:console_callback
```
**Symbols:**

```
ffffffff81a6c560-ffffffff81a6c678: poke_blanked_console (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void poke_blanked_console();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/vt.c (ffffffff81ab6c80)
Location: drivers/tty/vt/vt.c:4418
Inline: False
Direct callers:
  - drivers/tty/vt/selection.c:paste_selection
  - drivers/tty/vt/selection.c:set_selection_kernel
  - drivers/tty/vt/vt.c:console_callback
```
**Symbols:**

```
ffffffff81ab6c80-ffffffff81ab6d98: poke_blanked_console (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void poke_blanked_console();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/vt.c (ffffffff81b09980)
Location: drivers/tty/vt/vt.c:4415
Inline: False
Direct callers:
  - drivers/tty/vt/selection.c:paste_selection
  - drivers/tty/vt/selection.c:set_selection_kernel
  - drivers/tty/vt/vt.c:console_callback
```
**Symbols:**

```
ffffffff81b09980-ffffffff81b09a98: poke_blanked_console (STB_GLOBAL)
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
void poke_blanked_console();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/vt.c (ffff800010876628)
Location: drivers/tty/vt/vt.c:4368
Inline: False
Direct callers:
  - drivers/tty/vt/selection.c:paste_selection
  - drivers/tty/vt/selection.c:__set_selection_kernel
  - drivers/tty/vt/vt.c:console_callback
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:do_con_trol
```
**Symbols:**

```
ffff800010876628-ffff800010876708: poke_blanked_console (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void poke_blanked_console();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/vt.c (c0978e84)
Location: drivers/tty/vt/vt.c:4368
Inline: True
Direct callers:
  - drivers/tty/vt/selection.c:paste_selection
  - drivers/tty/vt/selection.c:__set_selection_kernel
  - drivers/tty/vt/vt.c:console_callback
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:do_con_trol
```
**Symbols:**

```
c0978e84-c0978f74: poke_blanked_console (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void poke_blanked_console();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/vt.c (c000000000917f10)
Location: drivers/tty/vt/vt.c:4368
Inline: False
Direct callers:
  - drivers/tty/vt/selection.c:paste_selection
  - drivers/tty/vt/selection.c:__set_selection_kernel
  - drivers/tty/vt/vt.c:console_callback
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:do_con_trol
```
**Symbols:**

```
c000000000917f10-c00000000091805c: poke_blanked_console (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void poke_blanked_console();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/vt.c (ffffffe0005476a2)
Location: drivers/tty/vt/vt.c:4368
Inline: True
Direct callers:
  - drivers/tty/vt/selection.c:paste_selection
  - drivers/tty/vt/selection.c:__set_selection_kernel
  - drivers/tty/vt/vt.c:console_callback
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:do_con_trol
```
**Symbols:**

```
ffffffe0005476a2-ffffffe00054778a: poke_blanked_console (STB_GLOBAL)
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
void poke_blanked_console();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/vt.c (ffffffff816641e0)
Location: drivers/tty/vt/vt.c:4368
Inline: True
Direct callers:
  - drivers/tty/vt/selection.c:paste_selection
  - drivers/tty/vt/selection.c:__set_selection_kernel
  - drivers/tty/vt/vt.c:console_callback
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:do_con_trol
```
**Symbols:**

```
ffffffff816641e0-ffffffff81664294: poke_blanked_console (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void poke_blanked_console();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/vt.c (ffffffff81644560)
Location: drivers/tty/vt/vt.c:4368
Inline: True
Direct callers:
  - drivers/tty/vt/selection.c:paste_selection
  - drivers/tty/vt/selection.c:__set_selection_kernel
  - drivers/tty/vt/vt.c:console_callback
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:do_con_trol
```
**Symbols:**

```
ffffffff81644560-ffffffff81644614: poke_blanked_console (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void poke_blanked_console();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/vt.c (ffffffff816925c0)
Location: drivers/tty/vt/vt.c:4368
Inline: True
Direct callers:
  - drivers/tty/vt/selection.c:paste_selection
  - drivers/tty/vt/selection.c:__set_selection_kernel
  - drivers/tty/vt/vt.c:console_callback
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:do_con_trol
```
**Symbols:**

```
ffffffff816925c0-ffffffff81692674: poke_blanked_console (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void poke_blanked_console();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/vt.c (ffffffff816acbb0)
Location: drivers/tty/vt/vt.c:4368
Inline: True
Direct callers:
  - drivers/tty/vt/selection.c:paste_selection
  - drivers/tty/vt/selection.c:__set_selection_kernel
  - drivers/tty/vt/vt.c:console_callback
  - drivers/tty/vt/vt.c:do_con_trol
  - drivers/tty/vt/vt.c:do_con_trol
```
**Symbols:**

```
ffffffff816acbb0-ffffffff816acc5f: poke_blanked_console (STB_GLOBAL)
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
