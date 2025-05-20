# Function: <code>serio_unregister_driver</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void serio_unregister_driver(struct serio_driver *drv);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/input/serio/serio.c (ffffffff81664200)
Location: drivers/input/serio/serio.c:869
Inline: False
Direct callers:
  - drivers/input/keyboard/atkbd.c:atkbd_exit
```
**Symbols:**

```
ffffffff81664200-ffffffff8166428d: serio_unregister_driver (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void serio_unregister_driver(struct serio_driver *drv);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/input/serio/serio.c (ffffffff816c4400)
Location: drivers/input/serio/serio.c:869
Inline: False
Direct callers:
  - drivers/input/keyboard/atkbd.c:atkbd_exit
```
**Symbols:**

```
ffffffff816c4400-ffffffff816c4495: serio_unregister_driver (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void serio_unregister_driver(struct serio_driver *drv);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/input/serio/serio.c (ffffffff816f23c0)
Location: drivers/input/serio/serio.c:869
Inline: False
Direct callers:
  - drivers/input/keyboard/atkbd.c:atkbd_exit
```
**Symbols:**

```
ffffffff816f23c0-ffffffff816f2455: serio_unregister_driver (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void serio_unregister_driver(struct serio_driver *drv);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/input/serio/serio.c (ffffffff81707cc0)
Location: drivers/input/serio/serio.c:869
Inline: False
Direct callers:
  - drivers/input/keyboard/atkbd.c:atkbd_exit
```
**Symbols:**

```
ffffffff81707cc0-ffffffff81707d5e: serio_unregister_driver (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void serio_unregister_driver(struct serio_driver *drv);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/input/serio/serio.c (ffffffff81778eb0)
Location: drivers/input/serio/serio.c:869
Inline: False
Direct callers:
  - drivers/input/keyboard/atkbd.c:atkbd_exit
```
**Symbols:**

```
ffffffff81778eb0-ffffffff81778f4e: serio_unregister_driver (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void serio_unregister_driver(struct serio_driver *drv);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/input/serio/serio.c (ffffffff817b9b70)
Location: drivers/input/serio/serio.c:869
Inline: False
Direct callers:
  - drivers/input/keyboard/atkbd.c:atkbd_exit
```
**Symbols:**

```
ffffffff817b9b70-ffffffff817b9c0e: serio_unregister_driver (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void serio_unregister_driver(struct serio_driver *drv);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/input/serio/serio.c (ffffffff817e0f80)
Location: drivers/input/serio/serio.c:865
Inline: False
Direct callers:
  - drivers/input/keyboard/atkbd.c:atkbd_exit
```
**Symbols:**

```
ffffffff817e0f80-ffffffff817e101e: serio_unregister_driver (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void serio_unregister_driver(struct serio_driver *drv);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/input/serio/serio.c (ffffffff81821850)
Location: drivers/input/serio/serio.c:853
Inline: False
Direct callers:
  - drivers/input/keyboard/atkbd.c:atkbd_exit
```
**Symbols:**

```
ffffffff81821850-ffffffff818218dc: serio_unregister_driver (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void serio_unregister_driver(struct serio_driver *drv);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/input/serio/serio.c (ffffffff81852cc0)
Location: drivers/input/serio/serio.c:853
Inline: False
Direct callers:
  - drivers/input/keyboard/atkbd.c:atkbd_exit
```
**Symbols:**

```
ffffffff81852cc0-ffffffff81852d4c: serio_unregister_driver (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
void serio_unregister_driver(struct serio_driver *drv);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/input/serio/serio.c (0)
Location: drivers/input/serio/serio.c:853
Inline: False
Direct callers:
  - drivers/input/keyboard/atkbd.c:atkbd_exit
```
**Symbols:**

```
ffffffff8192554c-ffffffff8192556b: serio_unregister_driver.cold (STB_LOCAL)
ffffffff81925120-ffffffff819251c6: serio_unregister_driver (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
void serio_unregister_driver(struct serio_driver *drv);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/input/serio/serio.c (0)
Location: drivers/input/serio/serio.c:853
Inline: False
Direct callers:
  - drivers/input/keyboard/atkbd.c:atkbd_exit
```
**Symbols:**

```
ffffffff81c22a17-ffffffff81c22a36: serio_unregister_driver.cold (STB_LOCAL)
ffffffff8192ced0-ffffffff8192cf76: serio_unregister_driver (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
void serio_unregister_driver(struct serio_driver *drv);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/input/serio/serio.c (0)
Location: drivers/input/serio/serio.c:853
Inline: False
Direct callers:
  - drivers/input/keyboard/atkbd.c:atkbd_exit
```
**Symbols:**

```
ffffffff81c14bd8-ffffffff81c14bf7: serio_unregister_driver.cold (STB_LOCAL)
ffffffff8190ff80-ffffffff81910026: serio_unregister_driver (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void serio_unregister_driver(struct serio_driver *drv);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/input/serio/serio.c (0)
Location: drivers/input/serio/serio.c:852
Inline: False
Direct callers:
  - drivers/input/keyboard/atkbd.c:atkbd_exit
```
**Symbols:**

```
ffffffff81d22245-ffffffff81d22264: serio_unregister_driver.cold (STB_LOCAL)
ffffffff819b0e70-ffffffff819b0f16: serio_unregister_driver (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void serio_unregister_driver(struct serio_driver *drv);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/input/serio/serio.c (0)
Location: drivers/input/serio/serio.c:852
Inline: False
Direct callers:
  - drivers/input/keyboard/atkbd.c:atkbd_exit
```
**Symbols:**

```
ffffffff81eeded4-ffffffff81eedef3: serio_unregister_driver.cold (STB_LOCAL)
ffffffff81b0fd10-ffffffff81b0fdc7: serio_unregister_driver (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void serio_unregister_driver(struct serio_driver *drv);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/input/serio/serio.c (ffffffff81ca02e0)
Location: drivers/input/serio/serio.c:849
Inline: False
Direct callers:
  - drivers/input/keyboard/atkbd.c:atkbd_exit
```
**Symbols:**

```
ffffffff81ca02e0-ffffffff81ca03ae: serio_unregister_driver (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void serio_unregister_driver(struct serio_driver *drv);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/input/serio/serio.c (ffffffff81d07620)
Location: drivers/input/serio/serio.c:849
Inline: False
Direct callers:
  - drivers/input/keyboard/atkbd.c:atkbd_exit
```
**Symbols:**

```
ffffffff81d07620-ffffffff81d076ee: serio_unregister_driver (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void serio_unregister_driver(struct serio_driver *drv);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/input/serio/serio.c (ffffffff81dbd250)
Location: drivers/input/serio/serio.c:849
Inline: False
Direct callers:
  - drivers/input/keyboard/atkbd.c:atkbd_exit
```
**Symbols:**

```
ffffffff81dbd250-ffffffff81dbd31e: serio_unregister_driver (STB_GLOBAL)
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
void serio_unregister_driver(struct serio_driver *drv);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/input/serio/serio.c (ffff800010a93118)
Location: drivers/input/serio/serio.c:853
Inline: False
Direct callers:
  - drivers/input/keyboard/atkbd.c:atkbd_exit
```
**Symbols:**

```
ffff800010a93118-ffff800010a931c8: serio_unregister_driver (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void serio_unregister_driver(struct serio_driver *drv);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/input/serio/serio.c (c0b76180)
Location: drivers/input/serio/serio.c:853
Inline: False
Direct callers:
  - drivers/input/keyboard/atkbd.c:atkbd_exit
```
**Symbols:**

```
c0b76180-c0b76224: serio_unregister_driver (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void serio_unregister_driver(struct serio_driver *drv);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/input/serio/serio.c (c000000000b6f320)
Location: drivers/input/serio/serio.c:853
Inline: False
Direct callers:
  - drivers/input/keyboard/atkbd.c:atkbd_exit
```
**Symbols:**

```
c000000000b6f320-c000000000b6f418: serio_unregister_driver (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void serio_unregister_driver(struct serio_driver *drv);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/input/serio/serio.c (ffffffe0006a557c)
Location: drivers/input/serio/serio.c:853
Inline: False
Direct callers:
  - drivers/input/keyboard/atkbd.c:atkbd_exit
```
**Symbols:**

```
ffffffe0006a557c-ffffffe0006a5636: serio_unregister_driver (STB_GLOBAL)
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
void serio_unregister_driver(struct serio_driver *drv);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/input/serio/serio.c (ffffffff81807da0)
Location: drivers/input/serio/serio.c:853
Inline: False
Direct callers:
  - drivers/input/keyboard/atkbd.c:atkbd_exit
```
**Symbols:**

```
ffffffff81807da0-ffffffff81807e2c: serio_unregister_driver (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void serio_unregister_driver(struct serio_driver *drv);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/input/serio/serio.c (ffffffff817cf490)
Location: drivers/input/serio/serio.c:853
Inline: False
Direct callers:
  - drivers/input/keyboard/atkbd.c:atkbd_exit
```
**Symbols:**

```
ffffffff817cf490-ffffffff817cf51c: serio_unregister_driver (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void serio_unregister_driver(struct serio_driver *drv);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/input/serio/serio.c (ffffffff81846e50)
Location: drivers/input/serio/serio.c:853
Inline: False
Direct callers:
  - drivers/input/keyboard/atkbd.c:atkbd_exit
```
**Symbols:**

```
ffffffff81846e50-ffffffff81846edc: serio_unregister_driver (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void serio_unregister_driver(struct serio_driver *drv);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/input/serio/serio.c (ffffffff81862020)
Location: drivers/input/serio/serio.c:853
Inline: False
Direct callers:
  - drivers/input/keyboard/atkbd.c:atkbd_exit
```
**Symbols:**

```
ffffffff81862020-ffffffff818620ac: serio_unregister_driver (STB_GLOBAL)
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
