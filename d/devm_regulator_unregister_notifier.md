# Function: <code>devm_regulator_unregister_notifier</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void devm_regulator_unregister_notifier(struct regulator *regulator, struct notifier_block *nb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/devres.c (ffffffff814deae0)
Location: drivers/regulator/devres.c:486
Inline: False
```
**Symbols:**

```
ffffffff814deae0-ffffffff814deb49: devm_regulator_unregister_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void devm_regulator_unregister_notifier(struct regulator *regulator, struct notifier_block *nb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/regulator/devres.c (ffffffff81530130)
Location: drivers/regulator/devres.c:489
Inline: True
```
**Symbols:**

```
ffffffff81530130-ffffffff81530199: devm_regulator_unregister_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void devm_regulator_unregister_notifier(struct regulator *regulator, struct notifier_block *nb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/regulator/devres.c (ffffffff8155c780)
Location: drivers/regulator/devres.c:486
Inline: True
```
**Symbols:**

```
ffffffff8155c780-ffffffff8155c7e9: devm_regulator_unregister_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void devm_regulator_unregister_notifier(struct regulator *regulator, struct notifier_block *nb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/regulator/devres.c (ffffffff815711c0)
Location: drivers/regulator/devres.c:472
Inline: True
```
**Symbols:**

```
ffffffff815711c0-ffffffff8157121a: devm_regulator_unregister_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void devm_regulator_unregister_notifier(struct regulator *regulator, struct notifier_block *nb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/regulator/devres.c (ffffffff815d5460)
Location: drivers/regulator/devres.c:472
Inline: True
```
**Symbols:**

```
ffffffff815d5460-ffffffff815d54ba: devm_regulator_unregister_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void devm_regulator_unregister_notifier(struct regulator *regulator, struct notifier_block *nb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/regulator/devres.c (ffffffff8160e230)
Location: drivers/regulator/devres.c:472
Inline: True
```
**Symbols:**

```
ffffffff8160e230-ffffffff8160e28a: devm_regulator_unregister_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void devm_regulator_unregister_notifier(struct regulator *regulator, struct notifier_block *nb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/regulator/devres.c (ffffffff8162ad50)
Location: drivers/regulator/devres.c:472
Inline: True
```
**Symbols:**

```
ffffffff8162ad50-ffffffff8162adaa: devm_regulator_unregister_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

```c
void devm_regulator_unregister_notifier(struct regulator *regulator, struct notifier_block *nb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/regulator/devres.c (ffffffff8165e9bf)
Location: drivers/regulator/devres.c:467
Inline: True
```
**Symbols:**

```
ffffffff8165e9bf-ffffffff8165e9d2: devm_regulator_unregister_notifier.cold (STB_LOCAL)
ffffffff8165e890-ffffffff8165e8ec: devm_regulator_unregister_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void devm_regulator_unregister_notifier(struct regulator *regulator, struct notifier_block *nb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/regulator/devres.c (ffffffff81681000)
Location: drivers/regulator/devres.c:467
Inline: True
```
**Symbols:**

```
ffffffff81681000-ffffffff8168105a: devm_regulator_unregister_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void devm_regulator_unregister_notifier(struct regulator *regulator, struct notifier_block *nb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/regulator/devres.c (ffffffff81732140)
Location: drivers/regulator/devres.c:467
Inline: True
```
**Symbols:**

```
ffffffff81732140-ffffffff8173219a: devm_regulator_unregister_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void devm_regulator_unregister_notifier(struct regulator *regulator, struct notifier_block *nb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/regulator/devres.c (ffffffff8174e260)
Location: drivers/regulator/devres.c:469
Inline: True
```
**Symbols:**

```
ffffffff8174e260-ffffffff8174e2ba: devm_regulator_unregister_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void devm_regulator_unregister_notifier(struct regulator *regulator, struct notifier_block *nb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/regulator/devres.c (ffffffff81731de0)
Location: drivers/regulator/devres.c:469
Inline: True
```
**Symbols:**

```
ffffffff81731de0-ffffffff81731e3a: devm_regulator_unregister_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void devm_regulator_unregister_notifier(struct regulator *regulator, struct notifier_block *nb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/devres.c (ffffffff817b1a10)
Location: drivers/regulator/devres.c:404
Inline: False
```
**Symbols:**

```
ffffffff817b1a10-ffffffff817b1a6a: devm_regulator_unregister_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void devm_regulator_unregister_notifier(struct regulator *regulator, struct notifier_block *nb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/devres.c (ffffffff818ed1b0)
Location: drivers/regulator/devres.c:404
Inline: False
```
**Symbols:**

```
ffffffff818ed1b0-ffffffff818ed218: devm_regulator_unregister_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void devm_regulator_unregister_notifier(struct regulator *regulator, struct notifier_block *nb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/devres.c (ffffffff81a44790)
Location: drivers/regulator/devres.c:626
Inline: False
```
**Symbols:**

```
ffffffff81a44790-ffffffff81a447f8: devm_regulator_unregister_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void devm_regulator_unregister_notifier(struct regulator *regulator, struct notifier_block *nb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/devres.c (ffffffff81a8e940)
Location: drivers/regulator/devres.c:626
Inline: False
```
**Symbols:**

```
ffffffff81a8e940-ffffffff81a8e9a8: devm_regulator_unregister_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void devm_regulator_unregister_notifier(struct regulator *regulator, struct notifier_block *nb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/regulator/devres.c (ffffffff81ae11b0)
Location: drivers/regulator/devres.c:626
Inline: False
```
**Symbols:**

```
ffffffff81ae11b0-ffffffff81ae1218: devm_regulator_unregister_notifier (STB_GLOBAL)
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
void devm_regulator_unregister_notifier(struct regulator *regulator, struct notifier_block *nb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/regulator/devres.c (ffff80001084ae58)
Location: drivers/regulator/devres.c:467
Inline: True
```
**Symbols:**

```
ffff80001084ae58-ffff80001084aed8: devm_regulator_unregister_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void devm_regulator_unregister_notifier(struct regulator *regulator, struct notifier_block *nb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/regulator/devres.c (c095437c)
Location: drivers/regulator/devres.c:467
Inline: True
```
**Symbols:**

```
c095437c-c095441c: devm_regulator_unregister_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void devm_regulator_unregister_notifier(struct regulator *regulator, struct notifier_block *nb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/regulator/devres.c (c0000000008e89a0)
Location: drivers/regulator/devres.c:467
Inline: True
```
**Symbols:**

```
c0000000008e89a0-c0000000008e8a30: devm_regulator_unregister_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void devm_regulator_unregister_notifier(struct regulator *regulator, struct notifier_block *nb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/regulator/devres.c (ffffffe00052aa1a)
Location: drivers/regulator/devres.c:467
Inline: True
```
**Symbols:**

```
ffffffe00052aa1a-ffffffe00052aa6a: devm_regulator_unregister_notifier (STB_GLOBAL)
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
void devm_regulator_unregister_notifier(struct regulator *regulator, struct notifier_block *nb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/regulator/devres.c (ffffffff81646a80)
Location: drivers/regulator/devres.c:467
Inline: True
```
**Symbols:**

```
ffffffff81646a80-ffffffff81646ada: devm_regulator_unregister_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void devm_regulator_unregister_notifier(struct regulator *regulator, struct notifier_block *nb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/regulator/devres.c (ffffffff81626ee0)
Location: drivers/regulator/devres.c:467
Inline: True
```
**Symbols:**

```
ffffffff81626ee0-ffffffff81626f3a: devm_regulator_unregister_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void devm_regulator_unregister_notifier(struct regulator *regulator, struct notifier_block *nb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/regulator/devres.c (ffffffff81674e40)
Location: drivers/regulator/devres.c:467
Inline: True
```
**Symbols:**

```
ffffffff81674e40-ffffffff81674e9a: devm_regulator_unregister_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void devm_regulator_unregister_notifier(struct regulator *regulator, struct notifier_block *nb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/regulator/devres.c (ffffffff8168f4a0)
Location: drivers/regulator/devres.c:467
Inline: True
```
**Symbols:**

```
ffffffff8168f4a0-ffffffff8168f4fa: devm_regulator_unregister_notifier (STB_GLOBAL)
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
