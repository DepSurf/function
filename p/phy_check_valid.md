# Function: <code>phy_check_valid</code>

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
In drivers/net/phy/phy.c (ffffffff815ea7e3)
Location: drivers/net/phy/phy.c:272
Inline: True
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
In drivers/net/phy/phy.c (ffffffff81649150)
Location: drivers/net/phy/phy.c:272
Inline: True
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
In drivers/net/phy/phy.c (ffffffff8167a2f0)
Location: drivers/net/phy/phy.c:309
Inline: True
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
In drivers/net/phy/phy.c (ffffffff8168e327)
Location: drivers/net/phy/phy.c:368
Inline: True
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
In drivers/net/phy/phy.c (ffffffff816f7e06)
Location: drivers/net/phy/phy.c:209
Inline: True
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
In drivers/net/phy/phy.c (ffffffff817351e4)
Location: drivers/net/phy/phy.c:209
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
In drivers/net/phy/phy.c (ffffffff81758db6)
Location: drivers/net/phy/phy.c:213
Inline: True
Inline callers:
  - drivers/net/phy/phy.c:phy_init_eee
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
In drivers/net/phy/phy.c (ffffffff81794a5b)
Location: drivers/net/phy/phy.c:225
Inline: True
Inline callers:
  - drivers/net/phy/phy.c:phy_init_eee
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
In drivers/net/phy/phy.c (ffffffff817b85fb)
Location: drivers/net/phy/phy.c:225
Inline: True
Inline callers:
  - drivers/net/phy/phy.c:phy_init_eee
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
In drivers/net/phy/phy.c (ffffffff8187fe99)
Location: drivers/net/phy/phy.c:233
Inline: True
Inline callers:
  - drivers/net/phy/phy.c:phy_init_eee
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
In drivers/net/phy/phy.c (ffffffff8188e749)
Location: drivers/net/phy/phy.c:216
Inline: True
Inline callers:
  - drivers/net/phy/phy.c:phy_init_eee
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
In drivers/net/phy/phy.c (ffffffff8187100a)
Location: drivers/net/phy/phy.c:216
Inline: True
Inline callers:
  - drivers/net/phy/phy.c:phy_init_eee
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
In drivers/net/phy/phy.c (ffffffff819016ea)
Location: drivers/net/phy/phy.c:216
Inline: True
Inline callers:
  - drivers/net/phy/phy.c:phy_init_eee
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
In drivers/net/phy/phy.c (ffffffff81a5303b)
Location: drivers/net/phy/phy.c:217
Inline: True
Inline callers:
  - drivers/net/phy/phy.c:phy_init_eee
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
In drivers/net/phy/phy.c (ffffffff81bdc19b)
Location: drivers/net/phy/phy.c:245
Inline: True
Inline callers:
  - drivers/net/phy/phy.c:phy_init_eee
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
bool phy_check_valid(int speed, int duplex, long unsigned int *features);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy.c (ffffffff81c31ff0)
Location: drivers/net/phy/phy.c:258
Inline: False
Direct callers:
  - drivers/net/phy/phy-c45.c:genphy_c45_eee_is_active
```
**Symbols:**

```
ffffffff81c31ff0-ffffffff81c32017: phy_check_valid (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
bool phy_check_valid(int speed, int duplex, long unsigned int *features);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy.c (ffffffff81ce6ce0)
Location: drivers/net/phy/phy.c:258
Inline: False
Direct callers:
  - drivers/net/phy/phy-c45.c:genphy_c45_eee_is_active
```
**Symbols:**

```
ffffffff81ce6ce0-ffffffff81ce6d07: phy_check_valid (STB_GLOBAL)
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
In drivers/net/phy/phy.c (ffff8000109d1a28)
Location: drivers/net/phy/phy.c:225
Inline: True
Inline callers:
  - drivers/net/phy/phy.c:phy_init_eee
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
In drivers/net/phy/phy.c (c0ab9c0c)
Location: drivers/net/phy/phy.c:225
Inline: True
Inline callers:
  - drivers/net/phy/phy.c:phy_init_eee
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
In drivers/net/phy/phy.c (c000000000a90c90)
Location: drivers/net/phy/phy.c:225
Inline: True
Inline callers:
  - drivers/net/phy/phy.c:phy_init_eee
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
In drivers/net/phy/phy.c (ffffffe00061e408)
Location: drivers/net/phy/phy.c:225
Inline: True
Inline callers:
  - drivers/net/phy/phy.c:phy_init_eee
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
In drivers/net/phy/phy.c (ffffffff8177d0cb)
Location: drivers/net/phy/phy.c:225
Inline: True
Inline callers:
  - drivers/net/phy/phy.c:phy_init_eee
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
In drivers/net/phy/phy.c (ffffffff8175ce7b)
Location: drivers/net/phy/phy.c:225
Inline: True
Inline callers:
  - drivers/net/phy/phy.c:phy_init_eee
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
In drivers/net/phy/phy.c (ffffffff817ad47b)
Location: drivers/net/phy/phy.c:225
Inline: True
Inline callers:
  - drivers/net/phy/phy.c:phy_init_eee
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
In drivers/net/phy/phy.c (ffffffff817c740b)
Location: drivers/net/phy/phy.c:225
Inline: True
Inline callers:
  - drivers/net/phy/phy.c:phy_init_eee
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
