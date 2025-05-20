# Function: <code>extcon_register_notifier</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int extcon_register_notifier(struct extcon_dev *edev, unsigned int id, struct notifier_block *nb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/extcon/extcon.c (ffffffff816ee450)
Location: drivers/extcon/extcon.c:579
Inline: False
```
**Symbols:**

```
ffffffff816ee450-ffffffff816ee50a: extcon_register_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int extcon_register_notifier(struct extcon_dev *edev, unsigned int id, struct notifier_block *nb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/extcon/extcon.c (ffffffff81753580)
Location: drivers/extcon/extcon.c:427
Inline: False
Direct callers:
  - drivers/extcon/extcon.c:extcon_register_notifier
  - drivers/extcon/devres.c:devm_extcon_register_notifier
```
**Symbols:**

```
ffffffff81753580-ffffffff817536fd: extcon_register_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
int extcon_register_notifier(struct extcon_dev *edev, unsigned int id, struct notifier_block *nb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/extcon/extcon.c (ffffffff81780130)
Location: drivers/extcon/extcon.c:903
Inline: True
Direct callers:
  - drivers/extcon/devres.c:devm_extcon_register_notifier
```
**Symbols:**

```
ffffffff81780130-ffffffff817802ad: extcon_register_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int extcon_register_notifier(struct extcon_dev *edev, unsigned int id, struct notifier_block *nb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/extcon/extcon.c (ffffffff8179e1c0)
Location: drivers/extcon/extcon.c:917
Inline: False
Direct callers:
  - drivers/extcon/devres.c:devm_extcon_register_notifier
```
**Symbols:**

```
ffffffff8179e1c0-ffffffff8179e29d: extcon_register_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int extcon_register_notifier(struct extcon_dev *edev, unsigned int id, struct notifier_block *nb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/extcon/extcon.c (ffffffff81815320)
Location: drivers/extcon/extcon.c:906
Inline: False
Direct callers:
  - drivers/extcon/devres.c:devm_extcon_register_notifier
```
**Symbols:**

```
ffffffff81815320-ffffffff818153fd: extcon_register_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int extcon_register_notifier(struct extcon_dev *edev, unsigned int id, struct notifier_block *nb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/extcon/extcon.c (ffffffff8185f250)
Location: drivers/extcon/extcon.c:907
Inline: False
Direct callers:
  - drivers/extcon/devres.c:devm_extcon_register_notifier
```
**Symbols:**

```
ffffffff8185f250-ffffffff8185f30d: extcon_register_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int extcon_register_notifier(struct extcon_dev *edev, unsigned int id, struct notifier_block *nb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/extcon/extcon.c (ffffffff8187ebf0)
Location: drivers/extcon/extcon.c:907
Inline: False
Direct callers:
  - drivers/extcon/devres.c:devm_extcon_register_notifier
```
**Symbols:**

```
ffffffff8187ebf0-ffffffff8187ecad: extcon_register_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int extcon_register_notifier(struct extcon_dev *edev, unsigned int id, struct notifier_block *nb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/extcon/extcon.c (ffffffff818c9230)
Location: drivers/extcon/extcon.c:899
Inline: False
Direct callers:
  - drivers/extcon/devres.c:devm_extcon_register_notifier
```
**Symbols:**

```
ffffffff818c9230-ffffffff818c92cf: extcon_register_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int extcon_register_notifier(struct extcon_dev *edev, unsigned int id, struct notifier_block *nb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/extcon/extcon.c (ffffffff818fb680)
Location: drivers/extcon/extcon.c:899
Inline: False
Direct callers:
  - drivers/extcon/devres.c:devm_extcon_register_notifier
```
**Symbols:**

```
ffffffff818fb680-ffffffff818fb71f: extcon_register_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int extcon_register_notifier(struct extcon_dev *edev, unsigned int id, struct notifier_block *nb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/extcon/extcon.c (ffffffff819d21e0)
Location: drivers/extcon/extcon.c:899
Inline: True
Direct callers:
  - drivers/extcon/devres.c:devm_extcon_register_notifier
```
**Symbols:**

```
ffffffff819d21e0-ffffffff819d227a: extcon_register_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int extcon_register_notifier(struct extcon_dev *edev, unsigned int id, struct notifier_block *nb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/extcon/extcon.c (ffffffff819d1dc0)
Location: drivers/extcon/extcon.c:899
Inline: True
Direct callers:
  - drivers/extcon/devres.c:devm_extcon_register_notifier
```
**Symbols:**

```
ffffffff819d1dc0-ffffffff819d1e5a: extcon_register_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int extcon_register_notifier(struct extcon_dev *edev, unsigned int id, struct notifier_block *nb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/extcon/extcon.c (ffffffff819b70a0)
Location: drivers/extcon/extcon.c:899
Inline: True
Direct callers:
  - drivers/extcon/devres.c:devm_extcon_register_notifier
```
**Symbols:**

```
ffffffff819b70a0-ffffffff819b713c: extcon_register_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int extcon_register_notifier(struct extcon_dev *edev, unsigned int id, struct notifier_block *nb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/extcon/extcon.c (ffffffff81a65c50)
Location: drivers/extcon/extcon.c:899
Inline: True
Direct callers:
  - drivers/extcon/devres.c:devm_extcon_register_notifier
```
**Symbols:**

```
ffffffff81a65c50-ffffffff81a65cec: extcon_register_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
int extcon_register_notifier(struct extcon_dev *edev, unsigned int id, struct notifier_block *nb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/extcon/extcon.c (ffffffff81bd7200)
Location: drivers/extcon/extcon.c:893
Inline: True
Direct callers:
  - drivers/extcon/devres.c:devm_extcon_register_notifier
```
**Symbols:**

```
ffffffff81bd7200-ffffffff81bd72ad: extcon_register_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
int extcon_register_notifier(struct extcon_dev *edev, unsigned int id, struct notifier_block *nb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/extcon/extcon.c (ffffffff81d83ac0)
Location: drivers/extcon/extcon.c:903
Inline: True
Direct callers:
  - drivers/extcon/devres.c:devm_extcon_register_notifier
```
**Symbols:**

```
ffffffff81d83ac0-ffffffff81d83b6d: extcon_register_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
int extcon_register_notifier(struct extcon_dev *edev, unsigned int id, struct notifier_block *nb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/extcon/extcon.c (ffffffff81df1eb0)
Location: drivers/extcon/extcon.c:913
Inline: True
Direct callers:
  - drivers/extcon/devres.c:devm_extcon_register_notifier
```
**Symbols:**

```
ffffffff81df1eb0-ffffffff81df1f5d: extcon_register_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
int extcon_register_notifier(struct extcon_dev *edev, unsigned int id, struct notifier_block *nb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/extcon/extcon.c (ffffffff81ea8500)
Location: drivers/extcon/extcon.c:913
Inline: True
Direct callers:
  - drivers/extcon/devres.c:devm_extcon_register_notifier
```
**Symbols:**

```
ffffffff81ea8500-ffffffff81ea85ad: extcon_register_notifier (STB_GLOBAL)
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
int extcon_register_notifier(struct extcon_dev *edev, unsigned int id, struct notifier_block *nb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/extcon/extcon.c (ffff800010b88910)
Location: drivers/extcon/extcon.c:899
Inline: False
Direct callers:
  - drivers/extcon/devres.c:devm_extcon_register_notifier
```
**Symbols:**

```
ffff800010b88910-ffff800010b88a24: extcon_register_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int extcon_register_notifier(struct extcon_dev *edev, unsigned int id, struct notifier_block *nb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/extcon/extcon.c (c0c6d224)
Location: drivers/extcon/extcon.c:899
Inline: True
Direct callers:
  - drivers/extcon/devres.c:devm_extcon_register_notifier
```
**Symbols:**

```
c0c6d224-c0c6d2d4: extcon_register_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
int extcon_register_notifier(struct extcon_dev *edev, unsigned int id, struct notifier_block *nb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/extcon/extcon.c (c000000000c686b0)
Location: drivers/extcon/extcon.c:899
Inline: True
Direct callers:
  - drivers/extcon/devres.c:devm_extcon_register_notifier
```
**Symbols:**

```
c000000000c686b0-c000000000c687d4: extcon_register_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
int extcon_register_notifier(struct extcon_dev *edev, unsigned int id, struct notifier_block *nb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/extcon/extcon.c (ffffffe0007318f6)
Location: drivers/extcon/extcon.c:899
Inline: True
Direct callers:
  - drivers/extcon/devres.c:devm_extcon_register_notifier
```
**Symbols:**

```
ffffffe0007318f6-ffffffe00073198a: extcon_register_notifier (STB_GLOBAL)
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
int extcon_register_notifier(struct extcon_dev *edev, unsigned int id, struct notifier_block *nb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/extcon/extcon.c (ffffffff8189c9b0)
Location: drivers/extcon/extcon.c:899
Inline: False
Direct callers:
  - drivers/extcon/devres.c:devm_extcon_register_notifier
```
**Symbols:**

```
ffffffff8189c9b0-ffffffff8189ca4f: extcon_register_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int extcon_register_notifier(struct extcon_dev *edev, unsigned int id, struct notifier_block *nb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/extcon/extcon.c (ffffffff818ec0a0)
Location: drivers/extcon/extcon.c:899
Inline: False
Direct callers:
  - drivers/extcon/devres.c:devm_extcon_register_notifier
```
**Symbols:**

```
ffffffff818ec0a0-ffffffff818ec13f: extcon_register_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int extcon_register_notifier(struct extcon_dev *edev, unsigned int id, struct notifier_block *nb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/extcon/extcon.c (ffffffff8190d120)
Location: drivers/extcon/extcon.c:899
Inline: False
Direct callers:
  - drivers/extcon/devres.c:devm_extcon_register_notifier
```
**Symbols:**

```
ffffffff8190d120-ffffffff8190d1bf: extcon_register_notifier (STB_GLOBAL)
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
