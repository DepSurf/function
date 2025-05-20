# Function: <code>phy_state_machine</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void phy_state_machine(struct work_struct *work);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy.c (ffffffff815eaaa0)
Location: drivers/net/phy/phy.c:810
Inline: False
```
**Symbols:**

```
ffffffff815eaaa0-ffffffff815eaf26: phy_state_machine (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void phy_state_machine(struct work_struct *work);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy.c (ffffffff816493f0)
Location: drivers/net/phy/phy.c:900
Inline: False
```
**Symbols:**

```
ffffffff816493f0-ffffffff81649899: phy_state_machine (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void phy_state_machine(struct work_struct *work);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy.c (ffffffff8167a690)
Location: drivers/net/phy/phy.c:964
Inline: False
```
**Symbols:**

```
ffffffff8167a690-ffffffff8167ab73: phy_state_machine (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void phy_state_machine(struct work_struct *work);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy.c (ffffffff8168f070)
Location: drivers/net/phy/phy.c:1032
Inline: False
```
**Symbols:**

```
ffffffff8168f070-ffffffff8168f561: phy_state_machine (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void phy_state_machine(struct work_struct *work);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy.c (ffffffff816f8ac0)
Location: drivers/net/phy/phy.c:857
Inline: False
```
**Symbols:**

```
ffffffff816f8ac0-ffffffff816f8ff9: phy_state_machine (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void phy_state_machine(struct work_struct *work);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy.c (ffffffff81735c20)
Location: drivers/net/phy/phy.c:843
Inline: False
```
**Symbols:**

```
ffffffff81735c20-ffffffff8173614f: phy_state_machine (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void phy_state_machine(struct work_struct *work);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy.c (ffffffff81758eb0)
Location: drivers/net/phy/phy.c:912
Inline: False
```
**Symbols:**

```
ffffffff81758eb0-ffffffff81759107: phy_state_machine (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
void phy_state_machine(struct work_struct *work);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/net/phy/phy.c (0)
Location: drivers/net/phy/phy.c:913
Inline: False
```
**Symbols:**

```
ffffffff81795be6-ffffffff81795bf3: phy_state_machine.cold (STB_LOCAL)
ffffffff817958b0-ffffffff81795a77: phy_state_machine (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void phy_state_machine(struct work_struct *work);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy.c (ffffffff817b93d0)
Location: drivers/net/phy/phy.c:894
Inline: False
```
**Symbols:**

```
ffffffff817b93d0-ffffffff817b9573: phy_state_machine (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
void phy_state_machine(struct work_struct *work);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/net/phy/phy.c (0)
Location: drivers/net/phy/phy.c:1019
Inline: False
Direct callers:
  - drivers/net/phy/phy.c:phy_stop
```
**Symbols:**

```
ffffffff81880b1b-ffffffff81880b2f: phy_state_machine.cold (STB_LOCAL)
ffffffff81880730-ffffffff818809bd: phy_state_machine (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
void phy_state_machine(struct work_struct *work);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/net/phy/phy.c (0)
Location: drivers/net/phy/phy.c:1078
Inline: False
Direct callers:
  - drivers/net/phy/phy.c:phy_stop
```
**Symbols:**

```
ffffffff81c19027-ffffffff81c1903b: phy_state_machine.cold (STB_LOCAL)
ffffffff8188eef0-ffffffff8188f17d: phy_state_machine (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
void phy_state_machine(struct work_struct *work);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/net/phy/phy.c (0)
Location: drivers/net/phy/phy.c:1079
Inline: False
Direct callers:
  - drivers/net/phy/phy.c:phy_stop
```
**Symbols:**

```
ffffffff81c0ae55-ffffffff81c0ae69: phy_state_machine.cold (STB_LOCAL)
ffffffff81871830-ffffffff81871abd: phy_state_machine (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void phy_state_machine(struct work_struct *work);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/net/phy/phy.c (0)
Location: drivers/net/phy/phy.c:1105
Inline: False
Direct callers:
  - drivers/net/phy/phy.c:phy_stop
```
**Symbols:**

```
ffffffff81d101df-ffffffff81d1020e: phy_state_machine.cold (STB_LOCAL)
ffffffff81901f10-ffffffff819021cf: phy_state_machine (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void phy_state_machine(struct work_struct *work);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/net/phy/phy.c (0)
Location: drivers/net/phy/phy.c:1137
Inline: False
Direct callers:
  - drivers/net/phy/phy.c:phy_stop
```
**Symbols:**

```
ffffffff81edaf1c-ffffffff81edaf4b: phy_state_machine.cold (STB_LOCAL)
ffffffff81a53e00-ffffffff81a540e5: phy_state_machine (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void phy_state_machine(struct work_struct *work);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/net/phy/phy.c (0)
Location: drivers/net/phy/phy.c:1166
Inline: False
Direct callers:
  - drivers/net/phy/phy.c:phy_stop
```
**Symbols:**

```
ffffffff8209d4a9-ffffffff8209d4c4: phy_state_machine.cold (STB_LOCAL)
ffffffff81bdd5f0-ffffffff81bdd8f1: phy_state_machine (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void phy_state_machine(struct work_struct *work);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/net/phy/phy.c (0)
Location: drivers/net/phy/phy.c:1404
Inline: False
Direct callers:
  - drivers/net/phy/phy.c:phy_stop
```
**Symbols:**

```
ffffffff8211e37a-ffffffff8211e395: phy_state_machine.cold (STB_LOCAL)
ffffffff81c342e0-ffffffff81c345ac: phy_state_machine (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void phy_state_machine(struct work_struct *work);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy.c (ffffffff81ce95a0)
Location: drivers/net/phy/phy.c:1470
Inline: False
```
**Symbols:**

```
ffffffff81ce95a0-ffffffff81ce9600: phy_state_machine (STB_GLOBAL)
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
void phy_state_machine(struct work_struct *work);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy.c (ffff8000109d1b30)
Location: drivers/net/phy/phy.c:894
Inline: False
```
**Symbols:**

```
ffff8000109d1b30-ffff8000109d1cf4: phy_state_machine (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void phy_state_machine(struct work_struct *work);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy.c (c0ab9d08)
Location: drivers/net/phy/phy.c:894
Inline: False
```
**Symbols:**

```
c0ab9d08-c0ab9ed4: phy_state_machine (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void phy_state_machine(struct work_struct *work);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy.c (c000000000a91720)
Location: drivers/net/phy/phy.c:894
Inline: False
```
**Symbols:**

```
c000000000a91720-c000000000a91994: phy_state_machine (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void phy_state_machine(struct work_struct *work);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy.c (ffffffe00061e4e8)
Location: drivers/net/phy/phy.c:894
Inline: False
```
**Symbols:**

```
ffffffe00061e4e8-ffffffe00061e696: phy_state_machine (STB_GLOBAL)
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
void phy_state_machine(struct work_struct *work);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy.c (ffffffff8177dea0)
Location: drivers/net/phy/phy.c:894
Inline: False
```
**Symbols:**

```
ffffffff8177dea0-ffffffff8177e043: phy_state_machine (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void phy_state_machine(struct work_struct *work);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy.c (ffffffff8175dc60)
Location: drivers/net/phy/phy.c:894
Inline: False
```
**Symbols:**

```
ffffffff8175dc60-ffffffff8175dde2: phy_state_machine (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void phy_state_machine(struct work_struct *work);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy.c (ffffffff817ae250)
Location: drivers/net/phy/phy.c:894
Inline: False
```
**Symbols:**

```
ffffffff817ae250-ffffffff817ae3f3: phy_state_machine (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void phy_state_machine(struct work_struct *work);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/net/phy/phy.c (ffffffff817c81e0)
Location: drivers/net/phy/phy.c:894
Inline: False
```
**Symbols:**

```
ffffffff817c81e0-ffffffff817c8383: phy_state_machine (STB_GLOBAL)
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
