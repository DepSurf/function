# Function: <code>do_bind_con_driver</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int do_bind_con_driver(const struct consw *csw, int first, int last, int deflt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/vt.c (ffffffff814f8f90)
Location: drivers/tty/vt/vt.c:3134
Inline: False
Direct callers:
  - drivers/tty/vt/vt.c:do_unbind_con_driver
  - drivers/tty/vt/vt.c:do_take_over_console
  - drivers/tty/vt/vt.c:store_bind
```
**Symbols:**

```
ffffffff814f8f90-ffffffff814f932f: do_bind_con_driver (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int do_bind_con_driver(const struct consw *csw, int first, int last, int deflt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/vt.c (ffffffff81549610)
Location: drivers/tty/vt/vt.c:3133
Inline: False
Direct callers:
  - drivers/tty/vt/vt.c:do_take_over_console
  - drivers/tty/vt/vt.c:store_bind
  - drivers/tty/vt/vt.c:do_unbind_con_driver
```
**Symbols:**

```
ffffffff81549610-ffffffff815499cf: do_bind_con_driver (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int do_bind_con_driver(const struct consw *csw, int first, int last, int deflt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/vt.c (ffffffff81576040)
Location: drivers/tty/vt/vt.c:3132
Inline: False
Direct callers:
  - drivers/tty/vt/vt.c:do_take_over_console
  - drivers/tty/vt/vt.c:store_bind
  - drivers/tty/vt/vt.c:do_unbind_con_driver
```
**Symbols:**

```
ffffffff81576040-ffffffff815763ff: do_bind_con_driver (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int do_bind_con_driver(const struct consw *csw, int first, int last, int deflt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/vt.c (ffffffff81589ed0)
Location: drivers/tty/vt/vt.c:3141
Inline: False
Direct callers:
  - drivers/tty/vt/vt.c:do_take_over_console
  - drivers/tty/vt/vt.c:store_bind
  - drivers/tty/vt/vt.c:do_unbind_con_driver
```
**Symbols:**

```
ffffffff81589ed0-ffffffff8158a2d6: do_bind_con_driver (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int do_bind_con_driver(const struct consw *csw, int first, int last, int deflt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/vt.c (ffffffff815ee470)
Location: drivers/tty/vt/vt.c:3145
Inline: False
Direct callers:
  - drivers/tty/vt/vt.c:do_take_over_console
  - drivers/tty/vt/vt.c:store_bind
  - drivers/tty/vt/vt.c:do_unbind_con_driver
```
**Symbols:**

```
ffffffff815ee470-ffffffff815ee881: do_bind_con_driver (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Transformation ⚠️</summary>

```c
int do_bind_con_driver(const struct consw *csw, int first, int last, int deflt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/tty/vt/vt.c (0)
Location: drivers/tty/vt/vt.c:3143
Inline: False
Direct callers:
  - drivers/tty/vt/vt.c:do_take_over_console
  - drivers/tty/vt/vt.c:store_bind
  - drivers/tty/vt/vt.c:do_unbind_con_driver
```
**Symbols:**

```
ffffffff81627930-ffffffff81627be1: do_bind_con_driver (STB_LOCAL)
ffffffff8162c4f3-ffffffff8162c5fe: do_bind_con_driver.cold.27 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Transformation ⚠️</summary>

```c
int do_bind_con_driver(const struct consw *csw, int first, int last, int deflt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/tty/vt/vt.c (0)
Location: drivers/tty/vt/vt.c:3458
Inline: False
Direct callers:
  - drivers/tty/vt/vt.c:do_take_over_console
  - drivers/tty/vt/vt.c:store_bind
  - drivers/tty/vt/vt.c:do_unbind_con_driver
```
**Symbols:**

```
ffffffff81645090-ffffffff81645356: do_bind_con_driver (STB_LOCAL)
ffffffff8164a623-ffffffff8164a72e: do_bind_con_driver.cold.31 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
int do_bind_con_driver(const struct consw *csw, int first, int last, int deflt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/tty/vt/vt.c (0)
Location: drivers/tty/vt/vt.c:3494
Inline: False
Direct callers:
  - drivers/tty/vt/vt.c:do_take_over_console
  - drivers/tty/vt/vt.c:store_bind
  - drivers/tty/vt/vt.c:do_unbind_con_driver
```
**Symbols:**

```
ffffffff816795d0-ffffffff81679871: do_bind_con_driver (STB_LOCAL)
ffffffff8167f0ae-ffffffff8167f1a5: do_bind_con_driver.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
int do_bind_con_driver(const struct consw *csw, int first, int last, int deflt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/tty/vt/vt.c (0)
Location: drivers/tty/vt/vt.c:3525
Inline: False
Direct callers:
  - drivers/tty/vt/vt.c:do_take_over_console
  - drivers/tty/vt/vt.c:store_bind
  - drivers/tty/vt/vt.c:do_unbind_con_driver
```
**Symbols:**

```
ffffffff8169bdc0-ffffffff8169c063: do_bind_con_driver (STB_LOCAL)
ffffffff816a1833-ffffffff816a1917: do_bind_con_driver.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/tty/vt/vt.c (0)
Location: drivers/tty/vt/vt.c:3536
Inline: True
Direct callers:
  - drivers/tty/vt/vt.c:do_take_over_console
  - drivers/tty/vt/vt.c:store_bind
  - drivers/tty/vt/vt.c:do_unbind_con_driver
```
**Symbols:**

```
ffffffff8174fc80-ffffffff8174ff23: do_bind_con_driver.isra.0 (STB_LOCAL)
ffffffff81753f71-ffffffff81754065: do_bind_con_driver.isra.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/tty/vt/vt.c (0)
Location: drivers/tty/vt/vt.c:3625
Inline: True
Direct callers:
  - drivers/tty/vt/vt.c:do_take_over_console
  - drivers/tty/vt/vt.c:store_bind
  - drivers/tty/vt/vt.c:do_unbind_con_driver
```
**Symbols:**

```
ffffffff8176b040-ffffffff8176b2e5: do_bind_con_driver.isra.0 (STB_LOCAL)
ffffffff81c0798a-ffffffff81c07a7e: do_bind_con_driver.isra.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/tty/vt/vt.c (0)
Location: drivers/tty/vt/vt.c:3625
Inline: True
Direct callers:
  - drivers/tty/vt/vt.c:do_take_over_console
  - drivers/tty/vt/vt.c:store_bind
  - drivers/tty/vt/vt.c:do_unbind_con_driver
```
**Symbols:**

```
ffffffff8174f240-ffffffff8174f4f6: do_bind_con_driver.isra.0 (STB_LOCAL)
ffffffff81bf95c4-ffffffff81bf96b8: do_bind_con_driver.isra.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/tty/vt/vt.c (0)
Location: drivers/tty/vt/vt.c:3630
Inline: True
Direct callers:
  - drivers/tty/vt/vt.c:do_take_over_console
  - drivers/tty/vt/vt.c:store_bind
  - drivers/tty/vt/vt.c:do_unbind_con_driver
```
**Symbols:**

```
ffffffff817d1420-ffffffff817d17ae: do_bind_con_driver.isra.0 (STB_LOCAL)
ffffffff81cf9667-ffffffff81cf977c: do_bind_con_driver.isra.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/tty/vt/vt.c (0)
Location: drivers/tty/vt/vt.c:3630
Inline: True
Direct callers:
  - drivers/tty/vt/vt.c:do_take_over_console
  - drivers/tty/vt/vt.c:store_bind
  - drivers/tty/vt/vt.c:do_unbind_con_driver
```
**Symbols:**

```
ffffffff8190f070-ffffffff8190f400: do_bind_con_driver.isra.0 (STB_LOCAL)
ffffffff81ec1879-ffffffff81ec199e: do_bind_con_driver.isra.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/tty/vt/vt.c (ffffffff81a688a0)
Location: drivers/tty/vt/vt.c:3629
Inline: True
Direct callers:
  - drivers/tty/vt/vt.c:do_take_over_console
  - drivers/tty/vt/vt.c:store_bind
  - drivers/tty/vt/vt.c:do_unbind_con_driver
```
**Symbols:**

```
ffffffff81a688a0-ffffffff81a68d57: do_bind_con_driver.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/tty/vt/vt.c (ffffffff81ab2f80)
Location: drivers/tty/vt/vt.c:3578
Inline: True
Direct callers:
  - drivers/tty/vt/vt.c:do_take_over_console
  - drivers/tty/vt/vt.c:store_bind
  - drivers/tty/vt/vt.c:do_unbind_con_driver
```
**Symbols:**

```
ffffffff81ab2f80-ffffffff81ab3437: do_bind_con_driver.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/tty/vt/vt.c (ffffffff81b05c60)
Location: drivers/tty/vt/vt.c:3578
Inline: True
Direct callers:
  - drivers/tty/vt/vt.c:do_take_over_console
  - drivers/tty/vt/vt.c:store_bind
  - drivers/tty/vt/vt.c:do_unbind_con_driver
```
**Symbols:**

```
ffffffff81b05c60-ffffffff81b06117: do_bind_con_driver.isra.0 (STB_LOCAL)
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
int do_bind_con_driver(const struct consw *csw, int first, int last, int deflt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/vt.c (ffff8000108734b8)
Location: drivers/tty/vt/vt.c:3525
Inline: False
Direct callers:
  - drivers/tty/vt/vt.c:do_take_over_console
  - drivers/tty/vt/vt.c:store_bind
  - drivers/tty/vt/vt.c:store_bind
  - drivers/tty/vt/vt.c:do_unbind_con_driver
```
**Symbols:**

```
ffff8000108734b8-ffff80001087385c: do_bind_con_driver (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int do_bind_con_driver(const struct consw *csw, int first, int last, int deflt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/vt.c (c0976194)
Location: drivers/tty/vt/vt.c:3525
Inline: False
Direct callers:
  - drivers/tty/vt/vt.c:do_take_over_console
  - drivers/tty/vt/vt.c:store_bind
  - drivers/tty/vt/vt.c:store_bind
  - drivers/tty/vt/vt.c:do_unbind_con_driver
```
**Symbols:**

```
c0976194-c0976548: do_bind_con_driver (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
int do_bind_con_driver(const struct consw *csw, int first, int last, int deflt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/vt.c (c0000000009140d0)
Location: drivers/tty/vt/vt.c:3525
Inline: False
Direct callers:
  - drivers/tty/vt/vt.c:do_take_over_console
  - drivers/tty/vt/vt.c:store_bind
  - drivers/tty/vt/vt.c:do_unbind_con_driver
```
**Symbols:**

```
c0000000009140d0-c000000000914590: do_bind_con_driver (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int do_bind_con_driver(const struct consw *csw, int first, int last, int deflt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/vt.c (ffffffe000544ed0)
Location: drivers/tty/vt/vt.c:3525
Inline: False
Direct callers:
  - drivers/tty/vt/vt.c:do_take_over_console
  - drivers/tty/vt/vt.c:store_bind
  - drivers/tty/vt/vt.c:do_unbind_con_driver
```
**Symbols:**

```
ffffffe000544ed0-ffffffe000545246: do_bind_con_driver (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
int do_bind_con_driver(const struct consw *csw, int first, int last, int deflt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/tty/vt/vt.c (0)
Location: drivers/tty/vt/vt.c:3525
Inline: False
Direct callers:
  - drivers/tty/vt/vt.c:do_take_over_console
  - drivers/tty/vt/vt.c:store_bind
  - drivers/tty/vt/vt.c:do_unbind_con_driver
```
**Symbols:**

```
ffffffff81661820-ffffffff81661ac3: do_bind_con_driver (STB_LOCAL)
ffffffff81667293-ffffffff81667377: do_bind_con_driver.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
int do_bind_con_driver(const struct consw *csw, int first, int last, int deflt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/tty/vt/vt.c (0)
Location: drivers/tty/vt/vt.c:3525
Inline: False
Direct callers:
  - drivers/tty/vt/vt.c:do_take_over_console
  - drivers/tty/vt/vt.c:store_bind
  - drivers/tty/vt/vt.c:do_unbind_con_driver
```
**Symbols:**

```
ffffffff81641ba0-ffffffff81641e43: do_bind_con_driver (STB_LOCAL)
ffffffff81647613-ffffffff816476f7: do_bind_con_driver.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
int do_bind_con_driver(const struct consw *csw, int first, int last, int deflt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/tty/vt/vt.c (0)
Location: drivers/tty/vt/vt.c:3525
Inline: False
Direct callers:
  - drivers/tty/vt/vt.c:do_take_over_console
  - drivers/tty/vt/vt.c:store_bind
  - drivers/tty/vt/vt.c:do_unbind_con_driver
```
**Symbols:**

```
ffffffff8168fc00-ffffffff8168fea3: do_bind_con_driver (STB_LOCAL)
ffffffff81695673-ffffffff81695757: do_bind_con_driver.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
int do_bind_con_driver(const struct consw *csw, int first, int last, int deflt);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/tty/vt/vt.c (0)
Location: drivers/tty/vt/vt.c:3525
Inline: False
Direct callers:
  - drivers/tty/vt/vt.c:do_take_over_console
  - drivers/tty/vt/vt.c:store_bind
  - drivers/tty/vt/vt.c:do_unbind_con_driver
```
**Symbols:**

```
ffffffff816aa200-ffffffff816aa4a3: do_bind_con_driver (STB_LOCAL)
ffffffff816afc43-ffffffff816afd27: do_bind_con_driver.cold (STB_LOCAL)
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
