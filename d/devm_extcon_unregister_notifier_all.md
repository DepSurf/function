# Function: <code>devm_extcon_unregister_notifier_all</code>

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
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void devm_extcon_unregister_notifier_all(struct device *dev, struct extcon_dev *edev, struct notifier_block *nb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/extcon/devres.c (ffffffff8179fb70)
Location: drivers/extcon/devres.c:270
Inline: True
```
**Symbols:**

```
ffffffff8179fb70-ffffffff8179fb99: devm_extcon_unregister_notifier_all (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void devm_extcon_unregister_notifier_all(struct device *dev, struct extcon_dev *edev, struct notifier_block *nb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/extcon/devres.c (ffffffff81816cc0)
Location: drivers/extcon/devres.c:268
Inline: True
```
**Symbols:**

```
ffffffff81816cc0-ffffffff81816ce9: devm_extcon_unregister_notifier_all (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void devm_extcon_unregister_notifier_all(struct device *dev, struct extcon_dev *edev, struct notifier_block *nb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/extcon/devres.c (ffffffff81860c40)
Location: drivers/extcon/devres.c:268
Inline: True
```
**Symbols:**

```
ffffffff81860c40-ffffffff81860c69: devm_extcon_unregister_notifier_all (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void devm_extcon_unregister_notifier_all(struct device *dev, struct extcon_dev *edev, struct notifier_block *nb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/extcon/devres.c (ffffffff818803f0)
Location: drivers/extcon/devres.c:268
Inline: True
```
**Symbols:**

```
ffffffff818803f0-ffffffff81880419: devm_extcon_unregister_notifier_all (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

```c
void devm_extcon_unregister_notifier_all(struct device *dev, struct extcon_dev *edev, struct notifier_block *nb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/extcon/devres.c (ffffffff818ca9e8)
Location: drivers/extcon/devres.c:260
Inline: True
```
**Symbols:**

```
ffffffff818ca9e8-ffffffff818ca9fb: devm_extcon_unregister_notifier_all.cold (STB_LOCAL)
ffffffff818ca970-ffffffff818ca999: devm_extcon_unregister_notifier_all (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void devm_extcon_unregister_notifier_all(struct device *dev, struct extcon_dev *edev, struct notifier_block *nb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/extcon/devres.c (ffffffff818fcdc0)
Location: drivers/extcon/devres.c:260
Inline: True
```
**Symbols:**

```
ffffffff818fcdc0-ffffffff818fcde9: devm_extcon_unregister_notifier_all (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void devm_extcon_unregister_notifier_all(struct device *dev, struct extcon_dev *edev, struct notifier_block *nb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/extcon/devres.c (ffffffff819d3a60)
Location: drivers/extcon/devres.c:260
Inline: True
```
**Symbols:**

```
ffffffff819d3a60-ffffffff819d3a89: devm_extcon_unregister_notifier_all (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void devm_extcon_unregister_notifier_all(struct device *dev, struct extcon_dev *edev, struct notifier_block *nb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/extcon/devres.c (ffffffff819d35e0)
Location: drivers/extcon/devres.c:260
Inline: True
```
**Symbols:**

```
ffffffff819d35e0-ffffffff819d3609: devm_extcon_unregister_notifier_all (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void devm_extcon_unregister_notifier_all(struct device *dev, struct extcon_dev *edev, struct notifier_block *nb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/extcon/devres.c (ffffffff819b8890)
Location: drivers/extcon/devres.c:260
Inline: True
```
**Symbols:**

```
ffffffff819b8890-ffffffff819b88b9: devm_extcon_unregister_notifier_all (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void devm_extcon_unregister_notifier_all(struct device *dev, struct extcon_dev *edev, struct notifier_block *nb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/extcon/devres.c (ffffffff81a67580)
Location: drivers/extcon/devres.c:260
Inline: False
```
**Symbols:**

```
ffffffff81a67580-ffffffff81a675a9: devm_extcon_unregister_notifier_all (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void devm_extcon_unregister_notifier_all(struct device *dev, struct extcon_dev *edev, struct notifier_block *nb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/extcon/devres.c (ffffffff81bd8b50)
Location: drivers/extcon/devres.c:260
Inline: False
```
**Symbols:**

```
ffffffff81bd8b50-ffffffff81bd8b95: devm_extcon_unregister_notifier_all (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void devm_extcon_unregister_notifier_all(struct device *dev, struct extcon_dev *edev, struct notifier_block *nb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/extcon/devres.c (ffffffff81d855f0)
Location: drivers/extcon/devres.c:260
Inline: False
```
**Symbols:**

```
ffffffff81d855f0-ffffffff81d85635: devm_extcon_unregister_notifier_all (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void devm_extcon_unregister_notifier_all(struct device *dev, struct extcon_dev *edev, struct notifier_block *nb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/extcon/devres.c (ffffffff81df3a60)
Location: drivers/extcon/devres.c:260
Inline: False
```
**Symbols:**

```
ffffffff81df3a60-ffffffff81df3aa5: devm_extcon_unregister_notifier_all (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void devm_extcon_unregister_notifier_all(struct device *dev, struct extcon_dev *edev, struct notifier_block *nb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/extcon/devres.c (ffffffff81eaa0f0)
Location: drivers/extcon/devres.c:260
Inline: False
```
**Symbols:**

```
ffffffff81eaa0f0-ffffffff81eaa135: devm_extcon_unregister_notifier_all (STB_GLOBAL)
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
void devm_extcon_unregister_notifier_all(struct device *dev, struct extcon_dev *edev, struct notifier_block *nb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/extcon/devres.c (ffff800010b8a300)
Location: drivers/extcon/devres.c:260
Inline: True
```
**Symbols:**

```
ffff800010b8a300-ffff800010b8a358: devm_extcon_unregister_notifier_all (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void devm_extcon_unregister_notifier_all(struct device *dev, struct extcon_dev *edev, struct notifier_block *nb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/extcon/devres.c (c0c6e608)
Location: drivers/extcon/devres.c:260
Inline: True
```
**Symbols:**

```
c0c6e608-c0c6e658: devm_extcon_unregister_notifier_all (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void devm_extcon_unregister_notifier_all(struct device *dev, struct extcon_dev *edev, struct notifier_block *nb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/extcon/devres.c (c000000000c69940)
Location: drivers/extcon/devres.c:260
Inline: False
```
**Symbols:**

```
c000000000c69940-c000000000c69998: devm_extcon_unregister_notifier_all (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void devm_extcon_unregister_notifier_all(struct device *dev, struct extcon_dev *edev, struct notifier_block *nb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/extcon/devres.c (ffffffe0007326f4)
Location: drivers/extcon/devres.c:260
Inline: True
```
**Symbols:**

```
ffffffe0007326f4-ffffffe000732746: devm_extcon_unregister_notifier_all (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
void devm_extcon_unregister_notifier_all(struct device *dev, struct extcon_dev *edev, struct notifier_block *nb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/extcon/devres.c (ffffffff8189e0f0)
Location: drivers/extcon/devres.c:260
Inline: True
```
**Symbols:**

```
ffffffff8189e0f0-ffffffff8189e119: devm_extcon_unregister_notifier_all (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void devm_extcon_unregister_notifier_all(struct device *dev, struct extcon_dev *edev, struct notifier_block *nb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/extcon/devres.c (ffffffff818ed7e0)
Location: drivers/extcon/devres.c:260
Inline: True
```
**Symbols:**

```
ffffffff818ed7e0-ffffffff818ed809: devm_extcon_unregister_notifier_all (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void devm_extcon_unregister_notifier_all(struct device *dev, struct extcon_dev *edev, struct notifier_block *nb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/extcon/devres.c (ffffffff8190e860)
Location: drivers/extcon/devres.c:260
Inline: True
```
**Symbols:**

```
ffffffff8190e860-ffffffff8190e889: devm_extcon_unregister_notifier_all (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
