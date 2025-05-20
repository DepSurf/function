# Function: <code>console_trylock</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
int console_trylock();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/printk/printk.c (ffffffff810d7170)
Location: kernel/printk/printk.c:2159
Inline: True
Direct callers:
  - kernel/printk/printk.c:vprintk_emit
  - kernel/printk/printk.c:console_flush_on_panic
  - drivers/video/console/fbcon.c:fb_flashcursor
```
**Symbols:**

```
ffffffff810d7170-ffffffff810d71ca: console_trylock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
int console_trylock();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/printk/printk.c (ffffffff810dc120)
Location: kernel/printk/printk.c:2229
Inline: True
Direct callers:
  - kernel/printk/printk.c:console_flush_on_panic
  - kernel/printk/printk.c:console_unlock
  - kernel/printk/printk.c:vprintk_emit
  - drivers/video/console/fbcon.c:fb_flashcursor
```
**Symbols:**

```
ffffffff810dc120-ffffffff810dc17a: console_trylock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
int console_trylock();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/printk/printk.c (ffffffff810e3060)
Location: kernel/printk/printk.c:2106
Inline: True
Direct callers:
  - kernel/printk/printk.c:console_flush_on_panic
  - kernel/printk/printk.c:console_unlock
  - kernel/printk/printk.c:vprintk_emit
  - drivers/video/console/fbcon.c:fb_flashcursor
```
**Symbols:**

```
ffffffff810e3060-ffffffff810e30ba: console_trylock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline, Transformation ⚠️</summary>

```c
int console_trylock();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/printk/printk.c (ffffffff810e29e2)
Location: kernel/printk/printk.c:2075
Inline: True
Inline callers:
  - kernel/printk/printk.c:console_unlock
  - kernel/printk/printk.c:vprintk_emit
Direct callers:
  - kernel/printk/printk.c:console_flush_on_panic
  - kernel/printk/printk.c:console_unlock
  - kernel/printk/printk.c:vprintk_emit
  - drivers/video/console/fbcon.c:fb_flashcursor
```
**Symbols:**

```
ffffffff810e2670-ffffffff810e26a6: console_trylock.part.20 (STB_LOCAL)
ffffffff810e2700-ffffffff810e271f: console_trylock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
int console_trylock();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/printk/printk.c (ffffffff810ea87e)
Location: kernel/printk/printk.c:2063
Inline: True
Inline callers:
  - kernel/printk/printk.c:console_unlock
  - kernel/printk/printk.c:vprintk_emit
Direct callers:
  - kernel/printk/printk.c:console_flush_on_panic
  - kernel/printk/printk.c:console_unlock
  - kernel/printk/printk.c:vprintk_emit
  - drivers/video/fbdev/core/fbcon.c:fb_flashcursor
```
**Symbols:**

```
ffffffff810ea450-ffffffff810ea486: console_trylock.part.20 (STB_LOCAL)
ffffffff810ea5c0-ffffffff810ea5df: console_trylock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

```c
int console_trylock();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/printk/printk.c (ffffffff810f2cd8)
Location: kernel/printk/printk.c:2237
Inline: True
Inline callers:
  - kernel/printk/printk.c:console_unlock
  - kernel/printk/printk.c:vprintk_emit
Direct callers:
  - kernel/printk/printk.c:console_flush_on_panic
  - kernel/printk/printk.c:console_unlock
  - kernel/printk/printk.c:vprintk_emit
  - drivers/video/fbdev/core/fbcon.c:fb_flashcursor
```
**Symbols:**

```
ffffffff810f2600-ffffffff810f2636: console_trylock.part.19 (STB_LOCAL)
ffffffff810f2690-ffffffff810f26af: console_trylock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

```c
int console_trylock();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/printk/printk.c (ffffffff810fe325)
Location: kernel/printk/printk.c:2240
Inline: True
Inline callers:
  - kernel/printk/printk.c:console_unlock
  - kernel/printk/printk.c:vprintk_emit
Direct callers:
  - kernel/printk/printk.c:console_flush_on_panic
  - kernel/printk/printk.c:console_unlock
  - kernel/printk/printk.c:vprintk_emit
  - drivers/video/fbdev/core/fbcon.c:fb_flashcursor
```
**Symbols:**

```
ffffffff810fdc40-ffffffff810fdc76: console_trylock.part.19 (STB_LOCAL)
ffffffff810fdcd0-ffffffff810fdcef: console_trylock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

```c
int console_trylock();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/printk/printk.c (ffffffff81106a61)
Location: kernel/printk/printk.c:2295
Inline: True
Inline callers:
  - kernel/printk/printk.c:console_unlock
  - kernel/printk/printk.c:vprintk_emit
Direct callers:
  - kernel/printk/printk.c:console_flush_on_panic
  - kernel/printk/printk.c:console_unlock
  - kernel/printk/printk.c:vprintk_emit
  - drivers/video/fbdev/core/fbcon.c:fb_flashcursor
```
**Symbols:**

```
ffffffff81106370-ffffffff811063a6: console_trylock.part.0 (STB_LOCAL)
ffffffff81106400-ffffffff8110641f: console_trylock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

```c
int console_trylock();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/printk/printk.c (ffffffff81112df1)
Location: kernel/printk/printk.c:2305
Inline: True
Inline callers:
  - kernel/printk/printk.c:console_unlock
  - kernel/printk/printk.c:vprintk_emit
Direct callers:
  - kernel/printk/printk.c:console_flush_on_panic
  - kernel/printk/printk.c:console_unlock
  - kernel/printk/printk.c:vprintk_emit
  - drivers/video/fbdev/core/fbcon.c:fb_flashcursor
```
**Symbols:**

```
ffffffff81112700-ffffffff81112736: console_trylock.part.0 (STB_LOCAL)
ffffffff81112790-ffffffff811127af: console_trylock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int console_trylock();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/printk/printk.c (ffffffff8111e8f0)
Location: kernel/printk/printk.c:2325
Inline: True
Direct callers:
  - kernel/printk/printk.c:console_flush_on_panic
  - kernel/printk/printk.c:console_unlock
  - kernel/printk/printk.c:console_trylock_spinning
  - drivers/video/fbdev/core/fbcon.c:fb_flashcursor
```
**Symbols:**

```
ffffffff8111e8f0-ffffffff8111e9a5: console_trylock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int console_trylock();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/printk/printk.c (ffffffff81119340)
Location: kernel/printk/printk.c:2409
Inline: True
Direct callers:
  - kernel/printk/printk.c:console_flush_on_panic
  - kernel/printk/printk.c:console_unlock
  - kernel/printk/printk.c:console_trylock_spinning
  - drivers/video/fbdev/core/fbcon.c:fb_flashcursor
```
**Symbols:**

```
ffffffff81119340-ffffffff811193f5: console_trylock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int console_trylock();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/printk/printk.c (ffffffff81119f90)
Location: kernel/printk/printk.c:2478
Inline: True
Direct callers:
  - kernel/printk/printk.c:console_flush_on_panic
  - kernel/printk/printk.c:console_unlock
  - kernel/printk/printk.c:vprintk_emit
  - drivers/video/fbdev/core/fbcon.c:fb_flashcursor
```
**Symbols:**

```
ffffffff81119f90-ffffffff8111a045: console_trylock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int console_trylock();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/printk/printk.c (ffffffff8113a660)
Location: kernel/printk/printk.c:2539
Inline: True
Direct callers:
  - kernel/printk/printk.c:console_flush_on_panic
  - kernel/printk/printk.c:console_unlock
  - kernel/printk/printk.c:vprintk_emit
  - drivers/video/fbdev/core/fbcon.c:fb_flashcursor
```
**Symbols:**

```
ffffffff8113a660-ffffffff8113a715: console_trylock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
int console_trylock();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/printk/printk.c (ffffffff8115f245)
Location: kernel/printk/printk.c:2584
Inline: True
Inline callers:
  - kernel/printk/printk.c:console_flush_on_panic
  - kernel/printk/printk.c:console_unlock
  - kernel/printk/printk.c:console_trylock_spinning
```
**Symbols:**

```
ffffffff8115c020-ffffffff8115c068: console_trylock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
int console_trylock();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/printk/printk.c (ffffffff81192385)
Location: kernel/printk/printk.c:2674
Inline: True
Inline callers:
  - kernel/printk/printk.c:console_flush_on_panic
  - kernel/printk/printk.c:console_unlock
  - kernel/printk/printk.c:console_trylock_spinning
```
**Symbols:**

```
ffffffff8118ea90-ffffffff8118ead8: console_trylock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
int console_trylock();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/printk/printk.c (ffffffff811a3c25)
Location: kernel/printk/printk.c:2616
Inline: True
Inline callers:
  - kernel/printk/printk.c:console_flush_on_panic
  - kernel/printk/printk.c:console_unlock
  - kernel/printk/printk.c:console_trylock_spinning
```
**Symbols:**

```
ffffffff811a0560-ffffffff811a05a8: console_trylock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
int console_trylock();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/printk/printk.c (ffffffff811b1fd7)
Location: kernel/printk/printk.c:2654
Inline: True
Inline callers:
  - kernel/printk/printk.c:console_unlock
  - kernel/printk/printk.c:console_trylock_spinning
```
**Symbols:**

```
ffffffff811af580-ffffffff811af5e2: console_trylock (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline, Transformation ⚠️</summary>

```c
int console_trylock();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/printk/printk.c (ffff80001017420c)
Location: kernel/printk/printk.c:2305
Inline: True
Inline callers:
  - kernel/printk/printk.c:console_unlock
  - kernel/printk/printk.c:vprintk_emit
Direct callers:
  - kernel/printk/printk.c:console_flush_on_panic
  - kernel/printk/printk.c:console_unlock
  - kernel/printk/printk.c:vprintk_emit
  - drivers/video/fbdev/core/fbcon.c:fb_flashcursor
```
**Symbols:**

```
ffff800010172c58-ffff800010172c9c: console_trylock.part.0 (STB_LOCAL)
ffff800010172d08-ffff800010172d34: console_trylock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int console_trylock();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/printk/printk.c (c03c55c4)
Location: kernel/printk/printk.c:2305
Inline: True
Direct callers:
  - kernel/printk/printk.c:console_flush_on_panic
  - kernel/printk/printk.c:console_unlock
  - kernel/printk/printk.c:vprintk_emit
  - drivers/video/fbdev/core/fbcon.c:fb_flashcursor
```
**Symbols:**

```
c03c55c4-c03c562c: console_trylock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline, Transformation ⚠️</summary>

```c
int console_trylock();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/printk/printk.c (c0000000001cd02c)
Location: kernel/printk/printk.c:2305
Inline: True
Inline callers:
  - kernel/printk/printk.c:console_unlock
  - kernel/printk/printk.c:vprintk_emit
Direct callers:
  - kernel/printk/printk.c:console_flush_on_panic
  - kernel/printk/printk.c:console_unlock
  - kernel/printk/printk.c:vprintk_emit
  - drivers/video/fbdev/core/fbcon.c:fb_flashcursor
```
**Symbols:**

```
c0000000001cc250-c0000000001cc2b4: console_trylock.part.0 (STB_LOCAL)
c0000000001cc2c0-c0000000001cc314: console_trylock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline, Transformation ⚠️</summary>

```c
int console_trylock();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/printk/printk.c (ffffffe00010f624)
Location: kernel/printk/printk.c:2305
Inline: True
Inline callers:
  - kernel/printk/printk.c:console_unlock
  - kernel/printk/printk.c:vprintk_emit
Direct callers:
  - kernel/printk/printk.c:console_flush_on_panic
  - kernel/printk/printk.c:console_unlock
  - kernel/printk/printk.c:vprintk_emit
  - drivers/video/fbdev/core/fbcon.c:fb_flashcursor
```
**Symbols:**

```
ffffffe00010ec9c-ffffffe00010ece6: console_trylock.part.0 (STB_LOCAL)
ffffffe00010ece6-ffffffe00010ed16: console_trylock (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

```c
int console_trylock();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/printk/printk.c (ffffffff8110b3d1)
Location: kernel/printk/printk.c:2305
Inline: True
Inline callers:
  - kernel/printk/printk.c:console_unlock
  - kernel/printk/printk.c:vprintk_emit
Direct callers:
  - kernel/printk/printk.c:console_flush_on_panic
  - kernel/printk/printk.c:console_unlock
  - kernel/printk/printk.c:vprintk_emit
  - drivers/video/fbdev/core/fbcon.c:fb_flashcursor
```
**Symbols:**

```
ffffffff8110ace0-ffffffff8110ad16: console_trylock.part.0 (STB_LOCAL)
ffffffff8110ad70-ffffffff8110ad8f: console_trylock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

```c
int console_trylock();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/printk/printk.c (ffffffff810fc236)
Location: kernel/printk/printk.c:2305
Inline: True
Inline callers:
  - kernel/printk/printk.c:console_unlock
  - kernel/printk/printk.c:vprintk_emit
Direct callers:
  - kernel/printk/printk.c:console_flush_on_panic
  - kernel/printk/printk.c:console_unlock
  - kernel/printk/printk.c:vprintk_emit
  - drivers/video/fbdev/core/fbcon.c:fb_flashcursor
```
**Symbols:**

```
ffffffff810fb710-ffffffff810fb746: console_trylock.part.0 (STB_LOCAL)
ffffffff810fb750-ffffffff810fb76f: console_trylock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

```c
int console_trylock();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/printk/printk.c (ffffffff811092c1)
Location: kernel/printk/printk.c:2305
Inline: True
Inline callers:
  - kernel/printk/printk.c:console_unlock
  - kernel/printk/printk.c:vprintk_emit
Direct callers:
  - kernel/printk/printk.c:console_flush_on_panic
  - kernel/printk/printk.c:console_unlock
  - kernel/printk/printk.c:vprintk_emit
  - drivers/video/fbdev/core/fbcon.c:fb_flashcursor
```
**Symbols:**

```
ffffffff81108bd0-ffffffff81108c06: console_trylock.part.0 (STB_LOCAL)
ffffffff81108c60-ffffffff81108c7f: console_trylock (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

```c
int console_trylock();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/printk/printk.c (ffffffff8111651c)
Location: kernel/printk/printk.c:2305
Inline: True
Inline callers:
  - kernel/printk/printk.c:vprintk_emit
Direct callers:
  - kernel/printk/printk.c:console_flush_on_panic
  - kernel/printk/printk.c:vprintk_emit
  - drivers/video/fbdev/core/fbcon.c:fb_flashcursor
```
**Symbols:**

```
ffffffff81114200-ffffffff81114236: console_trylock.part.0 (STB_LOCAL)
ffffffff81114290-ffffffff811142af: console_trylock (STB_GLOBAL)
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
