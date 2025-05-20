# Function: <code>of_phy_provider_unregister</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void of_phy_provider_unregister(struct phy_provider *phy_provider);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/phy/phy-core.c (ffffffff8141bd80)
Location: drivers/phy/phy-core.c:884
Inline: False
Direct callers:
  - drivers/phy/phy-core.c:devm_phy_provider_release
```
**Symbols:**

```
ffffffff8141bd80-ffffffff8141bde5: of_phy_provider_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void of_phy_provider_unregister(struct phy_provider *phy_provider);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/phy/phy-core.c (ffffffff814643e0)
Location: drivers/phy/phy-core.c:936
Inline: False
Direct callers:
  - drivers/phy/phy-core.c:devm_phy_provider_release
```
**Symbols:**

```
ffffffff814643e0-ffffffff81464445: of_phy_provider_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void of_phy_provider_unregister(struct phy_provider *phy_provider);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/phy/phy-core.c (ffffffff814836e0)
Location: drivers/phy/phy-core.c:951
Inline: False
Direct callers:
  - drivers/phy/phy-core.c:devm_phy_provider_release
```
**Symbols:**

```
ffffffff814836e0-ffffffff81483745: of_phy_provider_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void of_phy_provider_unregister(struct phy_provider *phy_provider);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/phy/phy-core.c (ffffffff8148ccd0)
Location: drivers/phy/phy-core.c:951
Inline: False
Direct callers:
  - drivers/phy/phy-core.c:devm_phy_provider_release
```
**Symbols:**

```
ffffffff8148ccd0-ffffffff8148cd32: of_phy_provider_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void of_phy_provider_unregister(struct phy_provider *phy_provider);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/phy/phy-core.c (ffffffff814c8da0)
Location: drivers/phy/phy-core.c:970
Inline: False
Direct callers:
  - drivers/phy/phy-core.c:devm_phy_provider_release
```
**Symbols:**

```
ffffffff814c8da0-ffffffff814c8e02: of_phy_provider_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

```c
void of_phy_provider_unregister(struct phy_provider *phy_provider);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/phy/phy-core.c (ffffffff814fa358)
Location: drivers/phy/phy-core.c:990
Inline: True
Inline callers:
  - drivers/phy/phy-core.c:devm_phy_provider_release
Direct callers:
  - drivers/phy/phy-core.c:devm_phy_provider_release
```
**Symbols:**

```
ffffffff814fa2d0-ffffffff814fa327: of_phy_provider_unregister.part.16 (STB_LOCAL)
ffffffff814fa330-ffffffff814fa34a: of_phy_provider_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

```c
void of_phy_provider_unregister(struct phy_provider *phy_provider);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/phy/phy-core.c (ffffffff8150efc8)
Location: drivers/phy/phy-core.c:1054
Inline: True
Inline callers:
  - drivers/phy/phy-core.c:devm_phy_provider_release
Direct callers:
  - drivers/phy/phy-core.c:devm_phy_provider_release
```
**Symbols:**

```
ffffffff8150ef40-ffffffff8150ef97: of_phy_provider_unregister.part.17 (STB_LOCAL)
ffffffff8150efa0-ffffffff8150efba: of_phy_provider_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void of_phy_provider_unregister(struct phy_provider *phy_provider);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/phy/phy-core.c (ffffffff8153cfa0)
Location: drivers/phy/phy-core.c:1061
Inline: False
Direct callers:
  - drivers/phy/phy-core.c:devm_phy_provider_release
```
**Symbols:**

```
ffffffff8153cfa0-ffffffff8153d005: of_phy_provider_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void of_phy_provider_unregister(struct phy_provider *phy_provider);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/phy/phy-core.c (ffffffff8155ddb0)
Location: drivers/phy/phy-core.c:1071
Inline: False
Direct callers:
  - drivers/phy/phy-core.c:devm_phy_provider_release
```
**Symbols:**

```
ffffffff8155ddb0-ffffffff8155de15: of_phy_provider_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void of_phy_provider_unregister(struct phy_provider *phy_provider);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/phy/phy-core.c (ffffffff81600c6e)
Location: drivers/phy/phy-core.c:1104
Inline: True
Inline callers:
  - drivers/phy/phy-core.c:devm_phy_provider_release
```
**Symbols:**

```
ffffffff815ffe20-ffffffff815ffe87: of_phy_provider_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void of_phy_provider_unregister(struct phy_provider *phy_provider);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/phy/phy-core.c (ffffffff81625b5e)
Location: drivers/phy/phy-core.c:1105
Inline: True
Inline callers:
  - drivers/phy/phy-core.c:devm_phy_provider_release
```
**Symbols:**

```
ffffffff81624d10-ffffffff81624d77: of_phy_provider_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void of_phy_provider_unregister(struct phy_provider *phy_provider);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/phy/phy-core.c (ffffffff8160961e)
Location: drivers/phy/phy-core.c:1135
Inline: True
Inline callers:
  - drivers/phy/phy-core.c:devm_phy_provider_release
```
**Symbols:**

```
ffffffff816086c0-ffffffff81608727: of_phy_provider_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void of_phy_provider_unregister(struct phy_provider *phy_provider);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/phy/phy-core.c (ffffffff8167829e)
Location: drivers/phy/phy-core.c:1137
Inline: True
Inline callers:
  - drivers/phy/phy-core.c:devm_phy_provider_release
```
**Symbols:**

```
ffffffff81677300-ffffffff81677367: of_phy_provider_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void of_phy_provider_unregister(struct phy_provider *phy_provider);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/phy/phy-core.c (ffffffff8179355d)
Location: drivers/phy/phy-core.c:1175
Inline: True
Inline callers:
  - drivers/phy/phy-core.c:devm_phy_provider_release
```
**Symbols:**

```
ffffffff81792370-ffffffff817923e6: of_phy_provider_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void of_phy_provider_unregister(struct phy_provider *phy_provider);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/phy/phy-core.c (ffffffff818a819d)
Location: drivers/phy/phy-core.c:1175
Inline: True
Inline callers:
  - drivers/phy/phy-core.c:devm_phy_provider_release
```
**Symbols:**

```
ffffffff818a6d80-ffffffff818a6df6: of_phy_provider_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void of_phy_provider_unregister(struct phy_provider *phy_provider);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/phy/phy-core.c (ffffffff818eb08d)
Location: drivers/phy/phy-core.c:1188
Inline: True
Inline callers:
  - drivers/phy/phy-core.c:devm_phy_provider_release
```
**Symbols:**

```
ffffffff818e9bf0-ffffffff818e9c66: of_phy_provider_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void of_phy_provider_unregister(struct phy_provider *phy_provider);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/phy/phy-core.c (ffffffff819325cd)
Location: drivers/phy/phy-core.c:1188
Inline: True
Inline callers:
  - drivers/phy/phy-core.c:devm_phy_provider_release
```
**Symbols:**

```
ffffffff81931090-ffffffff81931106: of_phy_provider_unregister (STB_GLOBAL)
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
void of_phy_provider_unregister(struct phy_provider *phy_provider);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/phy/phy-core.c (ffff800010686498)
Location: drivers/phy/phy-core.c:1071
Inline: False
Direct callers:
  - drivers/phy/phy-core.c:devm_phy_provider_release
```
**Symbols:**

```
ffff800010686498-ffff80001068650c: of_phy_provider_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void of_phy_provider_unregister(struct phy_provider *phy_provider);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/phy/phy-core.c (c082a488)
Location: drivers/phy/phy-core.c:1071
Inline: False
Direct callers:
  - drivers/phy/phy-core.c:devm_phy_provider_release
```
**Symbols:**

```
c082a488-c082a4f0: of_phy_provider_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void of_phy_provider_unregister(struct phy_provider *phy_provider);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/phy/phy-core.c (c0000000008212e0)
Location: drivers/phy/phy-core.c:1071
Inline: False
Direct callers:
  - drivers/phy/phy-core.c:devm_phy_provider_release
```
**Symbols:**

```
c0000000008212e0-c0000000008213a4: of_phy_provider_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void of_phy_provider_unregister(struct phy_provider *phy_provider);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/phy/phy-core.c (ffffffe00049636a)
Location: drivers/phy/phy-core.c:1071
Inline: False
Direct callers:
  - drivers/phy/phy-core.c:devm_phy_provider_release
```
**Symbols:**

```
ffffffe00049636a-ffffffe0004963d8: of_phy_provider_unregister (STB_GLOBAL)
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
void of_phy_provider_unregister(struct phy_provider *phy_provider);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/phy/phy-core.c (ffffffff815563a0)
Location: drivers/phy/phy-core.c:1071
Inline: False
Direct callers:
  - drivers/phy/phy-core.c:devm_phy_provider_release
```
**Symbols:**

```
ffffffff815563a0-ffffffff81556405: of_phy_provider_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void of_phy_provider_unregister(struct phy_provider *phy_provider);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/phy/phy-core.c (ffffffff81546860)
Location: drivers/phy/phy-core.c:1071
Inline: False
Direct callers:
  - drivers/phy/phy-core.c:devm_phy_provider_release
```
**Symbols:**

```
ffffffff81546860-ffffffff815468c5: of_phy_provider_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void of_phy_provider_unregister(struct phy_provider *phy_provider);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/phy/phy-core.c (ffffffff815520e0)
Location: drivers/phy/phy-core.c:1071
Inline: False
Direct callers:
  - drivers/phy/phy-core.c:devm_phy_provider_release
```
**Symbols:**

```
ffffffff815520e0-ffffffff81552145: of_phy_provider_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void of_phy_provider_unregister(struct phy_provider *phy_provider);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/phy/phy-core.c (ffffffff8156bf70)
Location: drivers/phy/phy-core.c:1071
Inline: False
Direct callers:
  - drivers/phy/phy-core.c:devm_phy_provider_release
```
**Symbols:**

```
ffffffff8156bf70-ffffffff8156bfd5: of_phy_provider_unregister (STB_GLOBAL)
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
