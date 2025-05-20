# Function: <code>shrink_zones</code>

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
In mm/vmscan.c (ffffffff811a4d13)
Location: mm/vmscan.c:2517
Inline: True
Inline callers:
  - mm/vmscan.c:do_try_to_free_pages
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
In mm/vmscan.c (ffffffff811bb878)
Location: mm/vmscan.c:2643
Inline: True
Inline callers:
  - mm/vmscan.c:do_try_to_free_pages
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
In mm/vmscan.c (ffffffff811cbf48)
Location: mm/vmscan.c:2652
Inline: True
Inline callers:
  - mm/vmscan.c:do_try_to_free_pages
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
In mm/vmscan.c (ffffffff811d4ac2)
Location: mm/vmscan.c:2703
Inline: True
Inline callers:
  - mm/vmscan.c:do_try_to_free_pages
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
In mm/vmscan.c (ffffffff811ea006)
Location: mm/vmscan.c:2727
Inline: True
Inline callers:
  - mm/vmscan.c:do_try_to_free_pages
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
In mm/vmscan.c (ffffffff8120b789)
Location: mm/vmscan.c:2735
Inline: True
Inline callers:
  - mm/vmscan.c:do_try_to_free_pages
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
In mm/vmscan.c (ffffffff8121e45e)
Location: mm/vmscan.c:2902
Inline: True
Inline callers:
  - mm/vmscan.c:do_try_to_free_pages
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
In mm/vmscan.c (ffffffff8122daf6)
Location: mm/vmscan.c:2867
Inline: True
Inline callers:
  - mm/vmscan.c:do_try_to_free_pages
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
In mm/vmscan.c (ffffffff8123bc86)
Location: mm/vmscan.c:2953
Inline: True
Inline callers:
  - mm/vmscan.c:do_try_to_free_pages
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void shrink_zones(struct zonelist *zonelist, struct scan_control *sc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff81268fa0)
Location: mm/vmscan.c:2906
Inline: False
Direct callers:
  - mm/vmscan.c:do_try_to_free_pages
```
**Symbols:**

```
ffffffff81268fa0-ffffffff81269181: shrink_zones (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void shrink_zones(struct zonelist *zonelist, struct scan_control *sc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmscan.c (ffffffff81273a70)
Location: mm/vmscan.c:2908
Inline: False
Direct callers:
  - mm/vmscan.c:do_try_to_free_pages
```
**Symbols:**

```
ffffffff81273a70-ffffffff81273c51: shrink_zones (STB_LOCAL)
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
In mm/vmscan.c (ffffffff81279036)
Location: mm/vmscan.c:3106
Inline: True
Inline callers:
  - mm/vmscan.c:do_try_to_free_pages
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
In mm/vmscan.c (ffffffff812b6e56)
Location: mm/vmscan.c:3267
Inline: True
Inline callers:
  - mm/vmscan.c:do_try_to_free_pages
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
In mm/vmscan.c (0)
Location: mm/vmscan.c:3403
Inline: True
Direct callers:
  - mm/vmscan.c:do_try_to_free_pages
```
**Symbols:**

```
ffffffff81312d30-ffffffff81312fce: shrink_zones.constprop.0 (STB_LOCAL)
ffffffff81e6c1ad-ffffffff81e6c1d3: shrink_zones.constprop.0.cold (STB_LOCAL)
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
In mm/vmscan.c (0)
Location: mm/vmscan.c:6335
Inline: True
Direct callers:
  - mm/vmscan.c:do_try_to_free_pages
```
**Symbols:**

```
ffffffff81386180-ffffffff8138641e: shrink_zones.constprop.0 (STB_LOCAL)
ffffffff82062c41-ffffffff82062c67: shrink_zones.constprop.0.cold (STB_LOCAL)
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
In mm/vmscan.c (0)
Location: mm/vmscan.c:6698
Inline: True
Direct callers:
  - mm/vmscan.c:do_try_to_free_pages
```
**Symbols:**

```
ffffffff813b9450-ffffffff813b970e: shrink_zones.constprop.0 (STB_LOCAL)
ffffffff820e23da-ffffffff820e2400: shrink_zones.constprop.0.cold (STB_LOCAL)
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
In mm/vmscan.c (0)
Location: mm/vmscan.c:6065
Inline: True
Direct callers:
  - mm/vmscan.c:do_try_to_free_pages
```
**Symbols:**

```
ffffffff813e24a0-ffffffff813e2763: shrink_zones.constprop.0 (STB_LOCAL)
ffffffff821bed84-ffffffff821bedaa: shrink_zones.constprop.0.cold (STB_LOCAL)
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
In mm/vmscan.c (ffff8000102ccdf4)
Location: mm/vmscan.c:2953
Inline: True
Inline callers:
  - mm/vmscan.c:do_try_to_free_pages
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
In mm/vmscan.c (c04f6c40)
Location: mm/vmscan.c:2953
Inline: True
Inline callers:
  - mm/vmscan.c:do_try_to_free_pages
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
In mm/vmscan.c (c00000000038a684)
Location: mm/vmscan.c:2953
Inline: True
Inline callers:
  - mm/vmscan.c:do_try_to_free_pages
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
In mm/vmscan.c (ffffffe0001eb6cc)
Location: mm/vmscan.c:2953
Inline: True
Inline callers:
  - mm/vmscan.c:do_try_to_free_pages
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
In mm/vmscan.c (ffffffff812342d6)
Location: mm/vmscan.c:2953
Inline: True
Inline callers:
  - mm/vmscan.c:do_try_to_free_pages
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
In mm/vmscan.c (ffffffff81227346)
Location: mm/vmscan.c:2953
Inline: True
Inline callers:
  - mm/vmscan.c:do_try_to_free_pages
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
In mm/vmscan.c (ffffffff81232076)
Location: mm/vmscan.c:2953
Inline: True
Inline callers:
  - mm/vmscan.c:do_try_to_free_pages
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
In mm/vmscan.c (ffffffff812414d6)
Location: mm/vmscan.c:2953
Inline: True
Inline callers:
  - mm/vmscan.c:do_try_to_free_pages
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
