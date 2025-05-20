# Function: <code>phy_error</code>

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
In drivers/net/phy/phy.c (ffffffff815e9ec8)
Location: drivers/net/phy/phy.c:555
Inline: True
Inline callers:
  - drivers/net/phy/phy.c:phy_disable_interrupts
  - drivers/net/phy/phy.c:phy_stop_interrupts
  - drivers/net/phy/phy.c:phy_change
  - drivers/net/phy/phy.c:phy_state_machine
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
In drivers/net/phy/phy.c (ffffffff81649717)
Location: drivers/net/phy/phy.c:637
Inline: True
Inline callers:
  - drivers/net/phy/phy.c:phy_state_machine
  - drivers/net/phy/phy.c:phy_change
  - drivers/net/phy/phy.c:phy_stop_interrupts
  - drivers/net/phy/phy.c:phy_disable_interrupts
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void phy_error(struct phy_device *phydev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy.c (ffffffff81679b90)
Location: drivers/net/phy/phy.c:695
Inline: False
Direct callers:
  - drivers/net/phy/phy.c:phy_state_machine
  - drivers/net/phy/phy.c:phy_change
  - drivers/net/phy/phy.c:phy_stop_interrupts
  - drivers/net/phy/phy.c:phy_disable_interrupts
```
**Symbols:**

```
ffffffff81679b90-ffffffff81679bcf: phy_error (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void phy_error(struct phy_device *phydev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy.c (ffffffff8168ecc0)
Location: drivers/net/phy/phy.c:763
Inline: False
Direct callers:
  - drivers/net/phy/phy.c:phy_state_machine
  - drivers/net/phy/phy.c:phy_change
  - drivers/net/phy/phy.c:phy_stop_interrupts
  - drivers/net/phy/phy.c:phy_disable_interrupts
```
**Symbols:**

```
ffffffff8168ecc0-ffffffff8168ecff: phy_error (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void phy_error(struct phy_device *phydev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy.c (ffffffff816f87b0)
Location: drivers/net/phy/phy.c:608
Inline: False
Direct callers:
  - drivers/net/phy/phy.c:phy_state_machine
  - drivers/net/phy/phy.c:phy_stop_interrupts
  - drivers/net/phy/phy.c:phy_change
  - drivers/net/phy/phy.c:phy_disable_interrupts
```
**Symbols:**

```
ffffffff816f87b0-ffffffff816f87ef: phy_error (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void phy_error(struct phy_device *phydev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy.c (ffffffff817359a0)
Location: drivers/net/phy/phy.c:611
Inline: False
Direct callers:
  - drivers/net/phy/phy.c:phy_state_machine
  - drivers/net/phy/phy.c:phy_stop_interrupts
  - drivers/net/phy/phy.c:phy_change
```
**Symbols:**

```
ffffffff817359a0-ffffffff817359df: phy_error (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void phy_error(struct phy_device *phydev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy.c (ffffffff81757be0)
Location: drivers/net/phy/phy.c:726
Inline: False
Direct callers:
  - drivers/net/phy/phy.c:phy_state_machine
  - drivers/net/phy/phy.c:phy_stop_interrupts
  - drivers/net/phy/phy.c:phy_interrupt
```
**Symbols:**

```
ffffffff81757be0-ffffffff81757c31: phy_error (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void phy_error(struct phy_device *phydev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy.c (ffffffff81795af5)
Location: drivers/net/phy/phy.c:734
Inline: False
Direct callers:
  - drivers/net/phy/phy.c:phy_state_machine
  - drivers/net/phy/phy.c:phy_interrupt
```
**Symbols:**

```
ffffffff81795af5-ffffffff81795b52: phy_error (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void phy_error(struct phy_device *phydev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy.c (ffffffff817b7f40)
Location: drivers/net/phy/phy.c:714
Inline: False
Direct callers:
  - drivers/net/phy/phy.c:phy_state_machine
  - drivers/net/phy/phy.c:phy_interrupt
```
**Symbols:**

```
ffffffff817b7f40-ffffffff817b7f91: phy_error (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void phy_error(struct phy_device *phydev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy.c (ffffffff8187f0d0)
Location: drivers/net/phy/phy.c:828
Inline: False
Direct callers:
  - drivers/net/phy/phy.c:phy_state_machine
  - drivers/net/phy/phy.c:phy_interrupt
```
**Symbols:**

```
ffffffff8187f0d0-ffffffff8187f121: phy_error (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void phy_error(struct phy_device *phydev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy.c (ffffffff8188da30)
Location: drivers/net/phy/phy.c:913
Inline: False
Direct callers:
  - drivers/net/phy/phy.c:phy_state_machine
```
**Symbols:**

```
ffffffff8188da30-ffffffff8188da81: phy_error (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void phy_error(struct phy_device *phydev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy.c (ffffffff81870370)
Location: drivers/net/phy/phy.c:914
Inline: False
Direct callers:
  - drivers/net/phy/phy.c:phy_state_machine
```
**Symbols:**

```
ffffffff81870370-ffffffff818703c1: phy_error (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void phy_error(struct phy_device *phydev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy.c (ffffffff81901fb4)
Location: drivers/net/phy/phy.c:940
Inline: True
Inline callers:
  - drivers/net/phy/phy.c:phy_state_machine
```
**Symbols:**

```
ffffffff81900950-ffffffff819009a1: phy_error (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void phy_error(struct phy_device *phydev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy.c (ffffffff81a53ea7)
Location: drivers/net/phy/phy.c:945
Inline: True
Inline callers:
  - drivers/net/phy/phy.c:phy_state_machine
```
**Symbols:**

```
ffffffff81a526c0-ffffffff81a5271f: phy_error (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void phy_error(struct phy_device *phydev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy.c (ffffffff81bdd697)
Location: drivers/net/phy/phy.c:974
Inline: True
Inline callers:
  - drivers/net/phy/phy.c:phy_state_machine
```
**Symbols:**

```
ffffffff81bdbcd0-ffffffff81bdbd2f: phy_error (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void phy_error(struct phy_device *phydev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy.c (ffffffff81c32dd0)
Location: drivers/net/phy/phy.c:1213
Inline: False
```
**Symbols:**

```
ffffffff81c32dd0-ffffffff81c32e38: phy_error (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void phy_error(struct phy_device *phydev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy.c (ffffffff81ce7ac0)
Location: drivers/net/phy/phy.c:1266
Inline: False
```
**Symbols:**

```
ffffffff81ce7ac0-ffffffff81ce7b28: phy_error (STB_GLOBAL)
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
void phy_error(struct phy_device *phydev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy.c (ffff8000109d06e8)
Location: drivers/net/phy/phy.c:714
Inline: False
Direct callers:
  - drivers/net/phy/phy.c:phy_state_machine
  - drivers/net/phy/phy.c:phy_interrupt
```
**Symbols:**

```
ffff8000109d06e8-ffff8000109d0744: phy_error (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void phy_error(struct phy_device *phydev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy.c (c0ab88ec)
Location: drivers/net/phy/phy.c:714
Inline: False
Direct callers:
  - drivers/net/phy/phy.c:phy_state_machine
  - drivers/net/phy/phy.c:phy_interrupt
```
**Symbols:**

```
c0ab88ec-c0ab8958: phy_error (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void phy_error(struct phy_device *phydev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy.c (c000000000a8fac0)
Location: drivers/net/phy/phy.c:714
Inline: False
Direct callers:
  - drivers/net/phy/phy.c:phy_state_machine
  - drivers/net/phy/phy.c:phy_interrupt
```
**Symbols:**

```
c000000000a8fac0-c000000000a8fb40: phy_error (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void phy_error(struct phy_device *phydev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy.c (ffffffe00061d362)
Location: drivers/net/phy/phy.c:714
Inline: False
Direct callers:
  - drivers/net/phy/phy.c:phy_state_machine
  - drivers/net/phy/phy.c:phy_interrupt
```
**Symbols:**

```
ffffffe00061d362-ffffffe00061d3be: phy_error (STB_LOCAL)
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
void phy_error(struct phy_device *phydev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy.c (ffffffff8177ca10)
Location: drivers/net/phy/phy.c:714
Inline: False
Direct callers:
  - drivers/net/phy/phy.c:phy_state_machine
  - drivers/net/phy/phy.c:phy_interrupt
```
**Symbols:**

```
ffffffff8177ca10-ffffffff8177ca61: phy_error (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void phy_error(struct phy_device *phydev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy.c (ffffffff8175c7c0)
Location: drivers/net/phy/phy.c:714
Inline: False
Direct callers:
  - drivers/net/phy/phy.c:phy_state_machine
  - drivers/net/phy/phy.c:phy_interrupt
```
**Symbols:**

```
ffffffff8175c7c0-ffffffff8175c811: phy_error (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void phy_error(struct phy_device *phydev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy.c (ffffffff817acdc0)
Location: drivers/net/phy/phy.c:714
Inline: False
Direct callers:
  - drivers/net/phy/phy.c:phy_state_machine
  - drivers/net/phy/phy.c:phy_interrupt
```
**Symbols:**

```
ffffffff817acdc0-ffffffff817ace11: phy_error (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void phy_error(struct phy_device *phydev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy.c (ffffffff817c6d50)
Location: drivers/net/phy/phy.c:714
Inline: False
Direct callers:
  - drivers/net/phy/phy.c:phy_state_machine
  - drivers/net/phy/phy.c:phy_interrupt
```
**Symbols:**

```
ffffffff817c6d50-ffffffff817c6da1: phy_error (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
