# Function: <code>extcon_dev_unregister</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void extcon_dev_unregister(struct extcon_dev *edev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/extcon/extcon.c (ffffffff816ee6b0)
Location: drivers/extcon/extcon.c:978
Inline: False
Direct callers:
  - drivers/extcon/extcon.c:devm_extcon_dev_unreg
```
**Symbols:**

```
ffffffff816ee6b0-ffffffff816ee829: extcon_dev_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void extcon_dev_unregister(struct extcon_dev *edev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/extcon/extcon.c (ffffffff817537d0)
Location: drivers/extcon/extcon.c:789
Inline: False
Direct callers:
  - drivers/extcon/devres.c:devm_extcon_dev_unreg
```
**Symbols:**

```
ffffffff817537d0-ffffffff81753949: extcon_dev_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void extcon_dev_unregister(struct extcon_dev *edev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/extcon/extcon.c (ffffffff8177f840)
Location: drivers/extcon/extcon.c:1265
Inline: False
Direct callers:
  - drivers/extcon/devres.c:devm_extcon_dev_unreg
```
**Symbols:**

```
ffffffff8177f840-ffffffff8177f9bd: extcon_dev_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void extcon_dev_unregister(struct extcon_dev *edev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/extcon/extcon.c (ffffffff8179ecd0)
Location: drivers/extcon/extcon.c:1304
Inline: True
Direct callers:
  - drivers/extcon/devres.c:devm_extcon_dev_unreg
```
**Symbols:**

```
ffffffff8179ecd0-ffffffff8179ee48: extcon_dev_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void extcon_dev_unregister(struct extcon_dev *edev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/extcon/extcon.c (ffffffff81815e30)
Location: drivers/extcon/extcon.c:1299
Inline: True
Direct callers:
  - drivers/extcon/devres.c:devm_extcon_dev_unreg
```
**Symbols:**

```
ffffffff81815e30-ffffffff81815fa8: extcon_dev_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void extcon_dev_unregister(struct extcon_dev *edev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/extcon/extcon.c (ffffffff8185fcf0)
Location: drivers/extcon/extcon.c:1304
Inline: True
Direct callers:
  - drivers/extcon/devres.c:devm_extcon_dev_unreg
```
**Symbols:**

```
ffffffff8185fcf0-ffffffff8185fe78: extcon_dev_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void extcon_dev_unregister(struct extcon_dev *edev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/extcon/extcon.c (ffffffff8187f690)
Location: drivers/extcon/extcon.c:1297
Inline: True
Direct callers:
  - drivers/extcon/devres.c:devm_extcon_dev_unreg
```
**Symbols:**

```
ffffffff8187f690-ffffffff8187f818: extcon_dev_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

```c
void extcon_dev_unregister(struct extcon_dev *edev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/extcon/extcon.c (ffffffff818c9cca)
Location: drivers/extcon/extcon.c:1289
Inline: True
Direct callers:
  - drivers/extcon/devres.c:devm_extcon_dev_unreg
```
**Symbols:**

```
ffffffff818ca597-ffffffff818ca5ba: extcon_dev_unregister.cold (STB_LOCAL)
ffffffff818c9cb0-ffffffff818c9e07: extcon_dev_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

```c
void extcon_dev_unregister(struct extcon_dev *edev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/extcon/extcon.c (ffffffff818fc11a)
Location: drivers/extcon/extcon.c:1289
Inline: True
Direct callers:
  - drivers/extcon/devres.c:devm_extcon_dev_unreg
```
**Symbols:**

```
ffffffff818fc9e7-ffffffff818fca0a: extcon_dev_unregister.cold (STB_LOCAL)
ffffffff818fc100-ffffffff818fc257: extcon_dev_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
void extcon_dev_unregister(struct extcon_dev *edev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/extcon/extcon.c (ffffffff819d24b0)
Location: drivers/extcon/extcon.c:1289
Inline: True
Direct callers:
  - drivers/extcon/devres.c:devm_extcon_dev_unreg
```
**Symbols:**

```
ffffffff819d2360-ffffffff819d24ad: extcon_dev_unregister.part.0 (STB_LOCAL)
ffffffff819d3686-ffffffff819d36a9: extcon_dev_unregister.part.0.cold (STB_LOCAL)
ffffffff819d24b0-ffffffff819d24c6: extcon_dev_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

```c
void extcon_dev_unregister(struct extcon_dev *edev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/extcon/extcon.c (ffffffff819d2090)
Location: drivers/extcon/extcon.c:1290
Inline: True
Direct callers:
  - drivers/extcon/devres.c:devm_extcon_dev_unreg
```
**Symbols:**

```
ffffffff819d1f40-ffffffff819d208d: extcon_dev_unregister.part.0 (STB_LOCAL)
ffffffff81c2f604-ffffffff81c2f627: extcon_dev_unregister.part.0.cold (STB_LOCAL)
ffffffff819d2090-ffffffff819d20a6: extcon_dev_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

```c
void extcon_dev_unregister(struct extcon_dev *edev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/extcon/extcon.c (ffffffff819b723a)
Location: drivers/extcon/extcon.c:1290
Inline: True
Direct callers:
  - drivers/extcon/devres.c:devm_extcon_dev_unreg
```
**Symbols:**

```
ffffffff81c218c9-ffffffff81c218ec: extcon_dev_unregister.cold (STB_LOCAL)
ffffffff819b7220-ffffffff819b7377: extcon_dev_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
void extcon_dev_unregister(struct extcon_dev *edev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/extcon/extcon.c (ffffffff81a65dea)
Location: drivers/extcon/extcon.c:1290
Inline: True
Direct callers:
  - drivers/extcon/devres.c:devm_extcon_dev_unreg
```
**Symbols:**

```
ffffffff81d334cb-ffffffff81d334ee: extcon_dev_unregister.cold (STB_LOCAL)
ffffffff81a65dd0-ffffffff81a65f27: extcon_dev_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

```c
void extcon_dev_unregister(struct extcon_dev *edev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/extcon/extcon.c (ffffffff81bd737a)
Location: drivers/extcon/extcon.c:1288
Inline: True
Direct callers:
  - drivers/extcon/devres.c:devm_extcon_dev_unreg
```
**Symbols:**

```
ffffffff81eff9b6-ffffffff81eff9d9: extcon_dev_unregister.cold (STB_LOCAL)
ffffffff81bd7360-ffffffff81bd74da: extcon_dev_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void extcon_dev_unregister(struct extcon_dev *edev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/extcon/extcon.c (ffffffff81d83c40)
Location: drivers/extcon/extcon.c:1298
Inline: True
Direct callers:
  - drivers/extcon/devres.c:devm_extcon_dev_unreg
```
**Symbols:**

```
ffffffff81d83c40-ffffffff81d83deb: extcon_dev_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void extcon_dev_unregister(struct extcon_dev *edev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/extcon/extcon.c (ffffffff81df2030)
Location: drivers/extcon/extcon.c:1359
Inline: True
Direct callers:
  - drivers/extcon/devres.c:devm_extcon_dev_unreg
```
**Symbols:**

```
ffffffff81df2030-ffffffff81df21d1: extcon_dev_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void extcon_dev_unregister(struct extcon_dev *edev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/extcon/extcon.c (ffffffff81ea8680)
Location: drivers/extcon/extcon.c:1358
Inline: True
Direct callers:
  - drivers/extcon/devres.c:devm_extcon_dev_unreg
```
**Symbols:**

```
ffffffff81ea8680-ffffffff81ea8821: extcon_dev_unregister (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
void extcon_dev_unregister(struct extcon_dev *edev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/extcon/extcon.c (ffff800010b882a0)
Location: drivers/extcon/extcon.c:1289
Inline: True
Direct callers:
  - drivers/extcon/devres.c:devm_extcon_dev_unreg
```
**Symbols:**

```
ffff800010b882a0-ffff800010b883fc: extcon_dev_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void extcon_dev_unregister(struct extcon_dev *edev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/extcon/extcon.c (c0c6d3d4)
Location: drivers/extcon/extcon.c:1289
Inline: True
Direct callers:
  - drivers/extcon/devres.c:devm_extcon_dev_unreg
```
**Symbols:**

```
c0c6d3d4-c0c6d528: extcon_dev_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void extcon_dev_unregister(struct extcon_dev *edev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/extcon/extcon.c (c000000000c689a0)
Location: drivers/extcon/extcon.c:1289
Inline: True
Direct callers:
  - drivers/extcon/devres.c:devm_extcon_dev_unreg
```
**Symbols:**

```
c000000000c689a0-c000000000c68ba0: extcon_dev_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void extcon_dev_unregister(struct extcon_dev *edev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/extcon/extcon.c (ffffffe000731a76)
Location: drivers/extcon/extcon.c:1289
Inline: True
Direct callers:
  - drivers/extcon/devres.c:devm_extcon_dev_unreg
```
**Symbols:**

```
ffffffe000731a76-ffffffe000731bb8: extcon_dev_unregister (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

```c
void extcon_dev_unregister(struct extcon_dev *edev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/extcon/extcon.c (ffffffff8189d44a)
Location: drivers/extcon/extcon.c:1289
Inline: True
Direct callers:
  - drivers/extcon/devres.c:devm_extcon_dev_unreg
```
**Symbols:**

```
ffffffff8189dd17-ffffffff8189dd3a: extcon_dev_unregister.cold (STB_LOCAL)
ffffffff8189d430-ffffffff8189d587: extcon_dev_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

```c
void extcon_dev_unregister(struct extcon_dev *edev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/extcon/extcon.c (ffffffff818ecb3a)
Location: drivers/extcon/extcon.c:1289
Inline: True
Direct callers:
  - drivers/extcon/devres.c:devm_extcon_dev_unreg
```
**Symbols:**

```
ffffffff818ed407-ffffffff818ed42a: extcon_dev_unregister.cold (STB_LOCAL)
ffffffff818ecb20-ffffffff818ecc77: extcon_dev_unregister (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

```c
void extcon_dev_unregister(struct extcon_dev *edev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/extcon/extcon.c (ffffffff8190dbba)
Location: drivers/extcon/extcon.c:1289
Inline: True
Direct callers:
  - drivers/extcon/devres.c:devm_extcon_dev_unreg
```
**Symbols:**

```
ffffffff8190e487-ffffffff8190e4aa: extcon_dev_unregister.cold (STB_LOCAL)
ffffffff8190dba0-ffffffff8190dcf7: extcon_dev_unregister (STB_GLOBAL)
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
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
