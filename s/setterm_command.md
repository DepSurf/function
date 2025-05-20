# Function: <code>setterm_command</code>

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
In drivers/tty/vt/vt.c (ffffffff814fbadc)
Location: drivers/tty/vt/vt.c:1554
Inline: True
Inline callers:
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
In drivers/tty/vt/vt.c (ffffffff8154c66f)
Location: drivers/tty/vt/vt.c:1552
Inline: True
Inline callers:
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
In drivers/tty/vt/vt.c (ffffffff81578eaa)
Location: drivers/tty/vt/vt.c:1551
Inline: True
Inline callers:
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
In drivers/tty/vt/vt.c (ffffffff8158cc70)
Location: drivers/tty/vt/vt.c:1560
Inline: True
Inline callers:
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
In drivers/tty/vt/vt.c (ffffffff815f1738)
Location: drivers/tty/vt/vt.c:1566
Inline: True
Inline callers:
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
In drivers/tty/vt/vt.c (ffffffff8162ac2f)
Location: drivers/tty/vt/vt.c:1564
Inline: True
Inline callers:
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
In drivers/tty/vt/vt.c (ffffffff8164881c)
Location: drivers/tty/vt/vt.c:1892
Inline: True
Inline callers:
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
In drivers/tty/vt/vt.c (ffffffff8167d181)
Location: drivers/tty/vt/vt.c:1902
Inline: True
Inline callers:
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
In drivers/tty/vt/vt.c (ffffffff8169f97e)
Location: drivers/tty/vt/vt.c:1926
Inline: True
Inline callers:
  - drivers/tty/vt/vt.c:do_con_trol
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void setterm_command(struct vc_data *vc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/vt.c (ffffffff81751850)
Location: drivers/tty/vt/vt.c:1939
Inline: False
Direct callers:
  - drivers/tty/vt/vt.c:do_con_trol
```
**Symbols:**

```
ffffffff81751850-ffffffff81751a9d: setterm_command (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void setterm_command(struct vc_data *vc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/tty/vt/vt.c (ffffffff8176d2a0)
Location: drivers/tty/vt/vt.c:1947
Inline: False
Direct callers:
  - drivers/tty/vt/vt.c:do_con_trol
```
**Symbols:**

```
ffffffff8176d2a0-ffffffff8176d4e3: setterm_command (STB_LOCAL)
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
In drivers/tty/vt/vt.c (ffffffff81750e20)
Location: drivers/tty/vt/vt.c:1947
Inline: True
Direct callers:
  - drivers/tty/vt/vt.c:do_con_trol
```
**Symbols:**

```
ffffffff81750e20-ffffffff8175105d: setterm_command.constprop.0 (STB_LOCAL)
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
Location: drivers/tty/vt/vt.c:1953
Inline: True
Direct callers:
  - drivers/tty/vt/vt.c:do_con_trol
```
**Symbols:**

```
ffffffff817d38e0-ffffffff817d3b9a: setterm_command.constprop.0 (STB_LOCAL)
ffffffff81cf9791-ffffffff81cf97a5: setterm_command.constprop.0.cold (STB_LOCAL)
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
Location: drivers/tty/vt/vt.c:1953
Inline: True
Direct callers:
  - drivers/tty/vt/vt.c:do_con_trol
```
**Symbols:**

```
ffffffff81911960-ffffffff81911c21: setterm_command.constprop.0 (STB_LOCAL)
ffffffff81ec19b3-ffffffff81ec19c8: setterm_command.constprop.0.cold (STB_LOCAL)
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
In drivers/tty/vt/vt.c (0)
Location: drivers/tty/vt/vt.c:1953
Inline: True
Direct callers:
  - drivers/tty/vt/vt.c:do_con_trol
```
**Symbols:**

```
ffffffff81a6c8c0-ffffffff81a6cb81: setterm_command.constprop.0 (STB_LOCAL)
ffffffff82095ab1-ffffffff82095ac6: setterm_command.constprop.0.cold (STB_LOCAL)
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
In drivers/tty/vt/vt.c (0)
Location: drivers/tty/vt/vt.c:1908
Inline: True
Direct callers:
  - drivers/tty/vt/vt.c:do_con_trol
```
**Symbols:**

```
ffffffff81ab6fe0-ffffffff81ab729c: setterm_command.constprop.0 (STB_LOCAL)
ffffffff821168f1-ffffffff82116906: setterm_command.constprop.0.cold (STB_LOCAL)
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
In drivers/tty/vt/vt.c (0)
Location: drivers/tty/vt/vt.c:1907
Inline: True
Direct callers:
  - drivers/tty/vt/vt.c:do_con_trol
```
**Symbols:**

```
ffffffff81b09ce0-ffffffff81b09f9c: setterm_command.constprop.0 (STB_LOCAL)
ffffffff821f4645-ffffffff821f465a: setterm_command.constprop.0.cold (STB_LOCAL)
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
In drivers/tty/vt/vt.c (ffff800010877a00)
Location: drivers/tty/vt/vt.c:1926
Inline: True
Inline callers:
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
In drivers/tty/vt/vt.c (c0979e58)
Location: drivers/tty/vt/vt.c:1926
Inline: True
Inline callers:
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
In drivers/tty/vt/vt.c (c0000000009192d4)
Location: drivers/tty/vt/vt.c:1926
Inline: True
Inline callers:
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
In drivers/tty/vt/vt.c (ffffffe00054834a)
Location: drivers/tty/vt/vt.c:1926
Inline: True
Inline callers:
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
In drivers/tty/vt/vt.c (ffffffff816653de)
Location: drivers/tty/vt/vt.c:1926
Inline: True
Inline callers:
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
In drivers/tty/vt/vt.c (ffffffff8164575e)
Location: drivers/tty/vt/vt.c:1926
Inline: True
Inline callers:
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
In drivers/tty/vt/vt.c (ffffffff816937be)
Location: drivers/tty/vt/vt.c:1926
Inline: True
Inline callers:
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
In drivers/tty/vt/vt.c (ffffffff816add9e)
Location: drivers/tty/vt/vt.c:1926
Inline: True
Inline callers:
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
</ul>
