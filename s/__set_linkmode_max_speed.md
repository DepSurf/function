# Function: <code>__set_linkmode_max_speed</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
In <code>4.8</code>: Absent ⚠️
</li>
<li>
In <code>4.10</code>: Absent ⚠️
</li>
<li>
In <code>4.13</code>: Absent ⚠️
</li>
<li>
In <code>4.15</code>: Absent ⚠️
</li>
<li>
In <code>4.18</code>: Absent ⚠️
</li>
<li>
In <code>5.0</code>: Absent ⚠️
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy-core.c (ffffffff817ba36d)
Location: drivers/net/phy/phy-core.c:210
Inline: True
Inline callers:
  - drivers/net/phy/phy-core.c:phy_speed_down_core
  - drivers/net/phy/phy-core.c:phy_set_max_speed
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
In drivers/net/phy/phy-core.c (ffffffff8188180d)
Location: drivers/net/phy/phy-core.c:218
Inline: True
Inline callers:
  - drivers/net/phy/phy-core.c:phy_speed_down_core
  - drivers/net/phy/phy-core.c:phy_set_max_speed
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy-core.c (ffffffff8188ff3d)
Location: drivers/net/phy/phy-core.c:245
Inline: True
Inline callers:
  - drivers/net/phy/phy-core.c:phy_speed_down_core
  - drivers/net/phy/phy-core.c:phy_set_max_speed
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
In drivers/net/phy/phy-core.c (ffffffff818736a8)
Location: drivers/net/phy/phy-core.c:245
Inline: True
Inline callers:
  - drivers/net/phy/phy-core.c:phy_speed_down_core
  - drivers/net/phy/phy-core.c:phy_set_max_speed
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
In drivers/net/phy/phy-core.c (ffffffff81903f6c)
Location: drivers/net/phy/phy-core.c:246
Inline: True
Inline callers:
  - drivers/net/phy/phy-core.c:phy_speed_down_core
  - drivers/net/phy/phy-core.c:phy_set_max_speed
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
In drivers/net/phy/phy-core.c (ffffffff81a569f7)
Location: drivers/net/phy/phy-core.c:247
Inline: True
Inline callers:
  - drivers/net/phy/phy-core.c:phy_speed_down_core
  - drivers/net/phy/phy-core.c:phy_set_max_speed
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void __set_linkmode_max_speed(u32 max_speed, long unsigned int *addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy-core.c (ffffffff81bdf300)
Location: drivers/net/phy/phy-core.c:330
Inline: False
Direct callers:
  - drivers/net/phy/phy-core.c:phy_speed_down_core
  - drivers/net/phy/phy-core.c:phy_set_max_speed
```
**Symbols:**

```
ffffffff81bdf300-ffffffff81bdf338: __set_linkmode_max_speed (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void __set_linkmode_max_speed(u32 max_speed, long unsigned int *addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy-core.c (ffffffff81c36bf0)
Location: drivers/net/phy/phy-core.c:333
Inline: False
Direct callers:
  - drivers/net/phy/phy-core.c:phy_speed_down_core
  - drivers/net/phy/phy-core.c:phy_set_max_speed
```
**Symbols:**

```
ffffffff81c36bf0-ffffffff81c36c28: __set_linkmode_max_speed (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void __set_linkmode_max_speed(u32 max_speed, long unsigned int *addr);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy-core.c (ffffffff81cebb70)
Location: drivers/net/phy/phy-core.c:335
Inline: False
Direct callers:
  - drivers/net/phy/phy-core.c:phy_speed_down_core
  - drivers/net/phy/phy-core.c:phy_set_max_speed
```
**Symbols:**

```
ffffffff81cebb70-ffffffff81cebba8: __set_linkmode_max_speed (STB_LOCAL)
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
In drivers/net/phy/phy-core.c (ffff8000109d371c)
Location: drivers/net/phy/phy-core.c:210
Inline: True
Inline callers:
  - drivers/net/phy/phy-core.c:phy_speed_down_core
  - drivers/net/phy/phy-core.c:of_set_phy_supported
  - drivers/net/phy/phy-core.c:phy_set_max_speed
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
In drivers/net/phy/phy-core.c (c0abb5a0)
Location: drivers/net/phy/phy-core.c:210
Inline: True
Inline callers:
  - drivers/net/phy/phy-core.c:phy_speed_down_core
  - drivers/net/phy/phy-core.c:of_set_phy_supported
  - drivers/net/phy/phy-core.c:phy_set_max_speed
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
In drivers/net/phy/phy-core.c (c000000000a93b94)
Location: drivers/net/phy/phy-core.c:210
Inline: True
Inline callers:
  - drivers/net/phy/phy-core.c:phy_speed_down_core
  - drivers/net/phy/phy-core.c:of_set_phy_supported
  - drivers/net/phy/phy-core.c:phy_set_max_speed
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
In drivers/net/phy/phy-core.c (ffffffe00061ffd2)
Location: drivers/net/phy/phy-core.c:210
Inline: True
Inline callers:
  - drivers/net/phy/phy-core.c:phy_speed_down_core
  - drivers/net/phy/phy-core.c:of_set_phy_supported
  - drivers/net/phy/phy-core.c:phy_set_max_speed
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
In drivers/net/phy/phy-core.c (ffffffff8177ee3d)
Location: drivers/net/phy/phy-core.c:210
Inline: True
Inline callers:
  - drivers/net/phy/phy-core.c:phy_speed_down_core
  - drivers/net/phy/phy-core.c:phy_set_max_speed
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
In drivers/net/phy/phy-core.c (ffffffff8175ebdd)
Location: drivers/net/phy/phy-core.c:210
Inline: True
Inline callers:
  - drivers/net/phy/phy-core.c:phy_speed_down_core
  - drivers/net/phy/phy-core.c:phy_set_max_speed
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
In drivers/net/phy/phy-core.c (ffffffff817af1ed)
Location: drivers/net/phy/phy-core.c:210
Inline: True
Inline callers:
  - drivers/net/phy/phy-core.c:phy_speed_down_core
  - drivers/net/phy/phy-core.c:phy_set_max_speed
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
In drivers/net/phy/phy-core.c (ffffffff817c917d)
Location: drivers/net/phy/phy-core.c:210
Inline: True
Inline callers:
  - drivers/net/phy/phy-core.c:phy_speed_down_core
  - drivers/net/phy/phy-core.c:phy_set_max_speed
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
