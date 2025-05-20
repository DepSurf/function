# Function: <code>psy_register_thermal</code>

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
In drivers/power/power_supply_core.c (ffffffff8167f52e)
Location: drivers/power/power_supply_core.c:581
Inline: True
Inline callers:
  - drivers/power/power_supply_core.c:__power_supply_register
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
In drivers/power/power_supply_core.c (ffffffff816e03a4)
Location: drivers/power/power_supply_core.c:585
Inline: True
Inline callers:
  - drivers/power/power_supply_core.c:__power_supply_register
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
In drivers/power/supply/power_supply_core.c (ffffffff81710814)
Location: drivers/power/supply/power_supply_core.c:585
Inline: True
Inline callers:
  - drivers/power/supply/power_supply_core.c:__power_supply_register
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
In drivers/power/supply/power_supply_core.c (ffffffff81728b50)
Location: drivers/power/supply/power_supply_core.c:674
Inline: True
Inline callers:
  - drivers/power/supply/power_supply_core.c:__power_supply_register
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
In drivers/power/supply/power_supply_core.c (ffffffff8179a2cf)
Location: drivers/power/supply/power_supply_core.c:712
Inline: True
Inline callers:
  - drivers/power/supply/power_supply_core.c:__power_supply_register
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
In drivers/power/supply/power_supply_core.c (ffffffff817e1742)
Location: drivers/power/supply/power_supply_core.c:719
Inline: True
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
In drivers/power/supply/power_supply_core.c (ffffffff8180ce86)
Location: drivers/power/supply/power_supply_core.c:857
Inline: True
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
In drivers/power/supply/power_supply_core.c (ffffffff8184ead0)
Location: drivers/power/supply/power_supply_core.c:867
Inline: True
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
In drivers/power/supply/power_supply_core.c (ffffffff81880500)
Location: drivers/power/supply/power_supply_core.c:867
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/power/supply/power_supply_core.c (ffffffff8194e9cd)
Location: drivers/power/supply/power_supply_core.c:940
Inline: True
Inline callers:
  - drivers/power/supply/power_supply_core.c:__power_supply_register
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int psy_register_thermal(struct power_supply *psy);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/power/supply/power_supply_core.c (ffffffff819540b0)
Location: drivers/power/supply/power_supply_core.c:959
Inline: False
Direct callers:
  - drivers/power/supply/power_supply_core.c:__power_supply_register
```
**Symbols:**

```
ffffffff819540b0-ffffffff8195414f: psy_register_thermal (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/power/supply/power_supply_core.c (ffffffff81938249)
Location: drivers/power/supply/power_supply_core.c:959
Inline: True
Inline callers:
  - drivers/power/supply/power_supply_core.c:__power_supply_register
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/power/supply/power_supply_core.c (ffffffff819dc699)
Location: drivers/power/supply/power_supply_core.c:982
Inline: True
Inline callers:
  - drivers/power/supply/power_supply_core.c:__power_supply_register
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/power/supply/power_supply_core.c (ffffffff81b40760)
Location: drivers/power/supply/power_supply_core.c:1156
Inline: True
Inline callers:
  - drivers/power/supply/power_supply_core.c:__power_supply_register
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/power/supply/power_supply_core.c (ffffffff81cd6df2)
Location: drivers/power/supply/power_supply_core.c:1160
Inline: True
Inline callers:
  - drivers/power/supply/power_supply_core.c:__power_supply_register
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/power/supply/power_supply_core.c (ffffffff81d3efc9)
Location: drivers/power/supply/power_supply_core.c:1299
Inline: True
Inline callers:
  - drivers/power/supply/power_supply_core.c:__power_supply_register
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/power/supply/power_supply_core.c (ffffffff81df596e)
Location: drivers/power/supply/power_supply_core.c:1299
Inline: True
Inline callers:
  - drivers/power/supply/power_supply_core.c:__power_supply_register
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
In drivers/power/supply/power_supply_core.c (ffff800010acc0a4)
Location: drivers/power/supply/power_supply_core.c:867
Inline: True
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
In drivers/power/supply/power_supply_core.c (c0bad07c)
Location: drivers/power/supply/power_supply_core.c:867
Inline: True
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
In drivers/power/supply/power_supply_core.c (c000000000baebbc)
Location: drivers/power/supply/power_supply_core.c:867
Inline: True
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
In drivers/power/supply/power_supply_core.c (ffffffe0006c9934)
Location: drivers/power/supply/power_supply_core.c:867
Inline: True
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
In drivers/power/supply/power_supply_core.c (ffffffff81828a70)
Location: drivers/power/supply/power_supply_core.c:867
Inline: True
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
In drivers/power/supply/power_supply_core.c (ffffffff817f0100)
Location: drivers/power/supply/power_supply_core.c:867
Inline: True
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
In drivers/power/supply/power_supply_core.c (ffffffff818759b0)
Location: drivers/power/supply/power_supply_core.c:867
Inline: True
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
In drivers/power/supply/power_supply_core.c (ffffffff81891350)
Location: drivers/power/supply/power_supply_core.c:867
Inline: True
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
</ul>
