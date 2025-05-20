# Function: <code>phy_enable_interrupts</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int phy_enable_interrupts(struct phy_device *phydev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy.c (ffffffff815e9970)
Location: drivers/net/phy/phy.c:594
Inline: False
Direct callers:
  - drivers/net/phy/phy.c:phy_start
```
**Symbols:**

```
ffffffff815e9970-ffffffff815e99af: phy_enable_interrupts (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int phy_enable_interrupts(struct phy_device *phydev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy.c (ffffffff816480c0)
Location: drivers/net/phy/phy.c:676
Inline: False
Direct callers:
  - drivers/net/phy/phy.c:phy_start
```
**Symbols:**

```
ffffffff816480c0-ffffffff8164810d: phy_enable_interrupts (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int phy_enable_interrupts(struct phy_device *phydev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy.c (ffffffff816791f0)
Location: drivers/net/phy/phy.c:731
Inline: False
Direct callers:
  - drivers/net/phy/phy.c:phy_start
```
**Symbols:**

```
ffffffff816791f0-ffffffff8167923d: phy_enable_interrupts (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int phy_enable_interrupts(struct phy_device *phydev);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy.c (ffffffff8168ded0)
Location: drivers/net/phy/phy.c:799
Inline: True
Direct callers:
  - drivers/net/phy/phy.c:phy_start
```
**Symbols:**

```
ffffffff8168ded0-ffffffff8168df1f: phy_enable_interrupts (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int phy_enable_interrupts(struct phy_device *phydev);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy.c (ffffffff816f7a30)
Location: drivers/net/phy/phy.c:713
Inline: True
Direct callers:
  - drivers/net/phy/phy.c:phy_start
```
**Symbols:**

```
ffffffff816f7a30-ffffffff816f7a85: phy_enable_interrupts (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int phy_enable_interrupts(struct phy_device *phydev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy.c (ffffffff81734990)
Location: drivers/net/phy/phy.c:704
Inline: False
Direct callers:
  - drivers/net/phy/phy.c:phy_start
```
**Symbols:**

```
ffffffff81734990-ffffffff817349e3: phy_enable_interrupts (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int phy_enable_interrupts(struct phy_device *phydev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy.c (ffffffff81757ac0)
Location: drivers/net/phy/phy.c:784
Inline: False
Direct callers:
  - drivers/net/phy/phy.c:phy_start
```
**Symbols:**

```
ffffffff81757ac0-ffffffff81757b10: phy_enable_interrupts (STB_LOCAL)
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
In drivers/net/phy/phy.c (ffffffff8179488d)
Location: drivers/net/phy/phy.c:797
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
In drivers/net/phy/phy.c (ffffffff817b842d)
Location: drivers/net/phy/phy.c:778
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
In drivers/net/phy/phy.c (ffffffff818806dd)
Location: drivers/net/phy/phy.c:890
Inline: True
Inline callers:
  - drivers/net/phy/phy.c:phy_request_interrupt
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
In drivers/net/phy/phy.c (ffffffff8188d99d)
Location: drivers/net/phy/phy.c:954
Inline: True
Inline callers:
  - drivers/net/phy/phy.c:phy_request_interrupt
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
In drivers/net/phy/phy.c (ffffffff818702dd)
Location: drivers/net/phy/phy.c:955
Inline: True
Inline callers:
  - drivers/net/phy/phy.c:phy_request_interrupt
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
In drivers/net/phy/phy.c (ffffffff819008bd)
Location: drivers/net/phy/phy.c:981
Inline: True
Inline callers:
  - drivers/net/phy/phy.c:phy_request_interrupt
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
In drivers/net/phy/phy.c (ffffffff81a5257d)
Location: drivers/net/phy/phy.c:1013
Inline: True
Inline callers:
  - drivers/net/phy/phy.c:phy_request_interrupt
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
In drivers/net/phy/phy.c (ffffffff81bdbd79)
Location: drivers/net/phy/phy.c:1042
Inline: True
Inline callers:
  - drivers/net/phy/phy.c:phy_request_interrupt
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
In drivers/net/phy/phy.c (ffffffff81c32e89)
Location: drivers/net/phy/phy.c:1276
Inline: True
Inline callers:
  - drivers/net/phy/phy.c:phy_request_interrupt
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
In drivers/net/phy/phy.c (ffffffff81ce7b79)
Location: drivers/net/phy/phy.c:1329
Inline: True
Inline callers:
  - drivers/net/phy/phy.c:phy_request_interrupt
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
In drivers/net/phy/phy.c (ffff8000109d0e24)
Location: drivers/net/phy/phy.c:778
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
In drivers/net/phy/phy.c (c0ab8e3c)
Location: drivers/net/phy/phy.c:778
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
In drivers/net/phy/phy.c (c000000000a90530)
Location: drivers/net/phy/phy.c:778
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
In drivers/net/phy/phy.c (ffffffe00061d8d6)
Location: drivers/net/phy/phy.c:778
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
In drivers/net/phy/phy.c (ffffffff8177cefd)
Location: drivers/net/phy/phy.c:778
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
In drivers/net/phy/phy.c (ffffffff8175ccad)
Location: drivers/net/phy/phy.c:778
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
In drivers/net/phy/phy.c (ffffffff817ad2ad)
Location: drivers/net/phy/phy.c:778
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
In drivers/net/phy/phy.c (ffffffff817c723d)
Location: drivers/net/phy/phy.c:778
Inline: True
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
</ul>
