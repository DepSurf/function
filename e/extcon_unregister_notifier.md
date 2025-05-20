# Function: <code>extcon_unregister_notifier</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
int extcon_unregister_notifier(struct extcon_dev *edev, unsigned int id, struct notifier_block *nb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/extcon/extcon.c (ffffffff816ee580)
Location: drivers/extcon/extcon.c:604
Inline: False
```
**Symbols:**

```
ffffffff816ee580-ffffffff816ee63a: extcon_unregister_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int extcon_unregister_notifier(struct extcon_dev *edev, unsigned int id, struct notifier_block *nb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/extcon/extcon.c (ffffffff81753700)
Location: drivers/extcon/extcon.c:473
Inline: False
Direct callers:
  - drivers/extcon/devres.c:devm_extcon_dev_notifier_unreg
```
**Symbols:**

```
ffffffff81753700-ffffffff817537b3: extcon_unregister_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int extcon_unregister_notifier(struct extcon_dev *edev, unsigned int id, struct notifier_block *nb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/extcon/extcon.c (ffffffff8177f770)
Location: drivers/extcon/extcon.c:949
Inline: False
Direct callers:
  - drivers/extcon/devres.c:devm_extcon_dev_notifier_unreg
```
**Symbols:**

```
ffffffff8177f770-ffffffff8177f823: extcon_unregister_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
int extcon_unregister_notifier(struct extcon_dev *edev, unsigned int id, struct notifier_block *nb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/extcon/extcon.c (ffffffff8179e300)
Location: drivers/extcon/extcon.c:944
Inline: False
Direct callers:
  - drivers/extcon/devres.c:devm_extcon_dev_notifier_unreg
```
**Symbols:**

```
ffffffff8179e300-ffffffff8179e3dd: extcon_unregister_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
int extcon_unregister_notifier(struct extcon_dev *edev, unsigned int id, struct notifier_block *nb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/extcon/extcon.c (ffffffff81815460)
Location: drivers/extcon/extcon.c:935
Inline: False
Direct callers:
  - drivers/extcon/devres.c:devm_extcon_dev_notifier_unreg
```
**Symbols:**

```
ffffffff81815460-ffffffff8181553d: extcon_unregister_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
int extcon_unregister_notifier(struct extcon_dev *edev, unsigned int id, struct notifier_block *nb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/extcon/extcon.c (ffffffff8185f370)
Location: drivers/extcon/extcon.c:936
Inline: False
Direct callers:
  - drivers/extcon/devres.c:devm_extcon_dev_notifier_unreg
```
**Symbols:**

```
ffffffff8185f370-ffffffff8185f42d: extcon_unregister_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int extcon_unregister_notifier(struct extcon_dev *edev, unsigned int id, struct notifier_block *nb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/extcon/extcon.c (ffffffff8187ed10)
Location: drivers/extcon/extcon.c:936
Inline: False
Direct callers:
  - drivers/extcon/devres.c:devm_extcon_dev_notifier_unreg
```
**Symbols:**

```
ffffffff8187ed10-ffffffff8187edcd: extcon_unregister_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int extcon_unregister_notifier(struct extcon_dev *edev, unsigned int id, struct notifier_block *nb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/extcon/extcon.c (ffffffff818c9340)
Location: drivers/extcon/extcon.c:928
Inline: False
Direct callers:
  - drivers/extcon/devres.c:devm_extcon_dev_notifier_unreg
```
**Symbols:**

```
ffffffff818c9340-ffffffff818c93df: extcon_unregister_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int extcon_unregister_notifier(struct extcon_dev *edev, unsigned int id, struct notifier_block *nb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/extcon/extcon.c (ffffffff818fb790)
Location: drivers/extcon/extcon.c:928
Inline: False
Direct callers:
  - drivers/extcon/devres.c:devm_extcon_dev_notifier_unreg
```
**Symbols:**

```
ffffffff818fb790-ffffffff818fb82f: extcon_unregister_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int extcon_unregister_notifier(struct extcon_dev *edev, unsigned int id, struct notifier_block *nb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/extcon/extcon.c (ffffffff819d2280)
Location: drivers/extcon/extcon.c:928
Inline: True
Direct callers:
  - drivers/extcon/devres.c:devm_extcon_dev_notifier_unreg
```
**Symbols:**

```
ffffffff819d2280-ffffffff819d231a: extcon_unregister_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int extcon_unregister_notifier(struct extcon_dev *edev, unsigned int id, struct notifier_block *nb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/extcon/extcon.c (ffffffff819d1e60)
Location: drivers/extcon/extcon.c:928
Inline: True
Direct callers:
  - drivers/extcon/devres.c:devm_extcon_dev_notifier_unreg
```
**Symbols:**

```
ffffffff819d1e60-ffffffff819d1efa: extcon_unregister_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int extcon_unregister_notifier(struct extcon_dev *edev, unsigned int id, struct notifier_block *nb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/extcon/extcon.c (ffffffff819b7140)
Location: drivers/extcon/extcon.c:928
Inline: True
Direct callers:
  - drivers/extcon/devres.c:devm_extcon_dev_notifier_unreg
```
**Symbols:**

```
ffffffff819b7140-ffffffff819b71dc: extcon_unregister_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int extcon_unregister_notifier(struct extcon_dev *edev, unsigned int id, struct notifier_block *nb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/extcon/extcon.c (ffffffff81a65cf0)
Location: drivers/extcon/extcon.c:928
Inline: True
Direct callers:
  - drivers/extcon/devres.c:devm_extcon_dev_notifier_unreg
```
**Symbols:**

```
ffffffff81a65cf0-ffffffff81a65d8c: extcon_unregister_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
int extcon_unregister_notifier(struct extcon_dev *edev, unsigned int id, struct notifier_block *nb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/extcon/extcon.c (ffffffff81bd72b0)
Location: drivers/extcon/extcon.c:922
Inline: True
Direct callers:
  - drivers/extcon/devres.c:devm_extcon_dev_notifier_unreg
```
**Symbols:**

```
ffffffff81bd72b0-ffffffff81bd735d: extcon_unregister_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
int extcon_unregister_notifier(struct extcon_dev *edev, unsigned int id, struct notifier_block *nb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/extcon/extcon.c (ffffffff81d83b80)
Location: drivers/extcon/extcon.c:932
Inline: True
Direct callers:
  - drivers/extcon/devres.c:devm_extcon_dev_notifier_unreg
```
**Symbols:**

```
ffffffff81d83b80-ffffffff81d83c2d: extcon_unregister_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
int extcon_unregister_notifier(struct extcon_dev *edev, unsigned int id, struct notifier_block *nb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/extcon/extcon.c (ffffffff81df1f70)
Location: drivers/extcon/extcon.c:942
Inline: True
Direct callers:
  - drivers/extcon/devres.c:devm_extcon_dev_notifier_unreg
```
**Symbols:**

```
ffffffff81df1f70-ffffffff81df201d: extcon_unregister_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
int extcon_unregister_notifier(struct extcon_dev *edev, unsigned int id, struct notifier_block *nb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/extcon/extcon.c (ffffffff81ea85c0)
Location: drivers/extcon/extcon.c:942
Inline: True
Direct callers:
  - drivers/extcon/devres.c:devm_extcon_dev_notifier_unreg
```
**Symbols:**

```
ffffffff81ea85c0-ffffffff81ea866d: extcon_unregister_notifier (STB_GLOBAL)
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
int extcon_unregister_notifier(struct extcon_dev *edev, unsigned int id, struct notifier_block *nb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/extcon/extcon.c (ffff800010b887f8)
Location: drivers/extcon/extcon.c:928
Inline: False
Direct callers:
  - drivers/extcon/devres.c:devm_extcon_dev_notifier_unreg
```
**Symbols:**

```
ffff800010b887f8-ffff800010b8890c: extcon_unregister_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int extcon_unregister_notifier(struct extcon_dev *edev, unsigned int id, struct notifier_block *nb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/extcon/extcon.c (c0c6d2d4)
Location: drivers/extcon/extcon.c:928
Inline: True
Direct callers:
  - drivers/extcon/devres.c:devm_extcon_dev_notifier_unreg
```
**Symbols:**

```
c0c6d2d4-c0c6d384: extcon_unregister_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
int extcon_unregister_notifier(struct extcon_dev *edev, unsigned int id, struct notifier_block *nb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/extcon/extcon.c (c000000000c687e0)
Location: drivers/extcon/extcon.c:928
Inline: True
Direct callers:
  - drivers/extcon/devres.c:devm_extcon_dev_notifier_unreg
```
**Symbols:**

```
c000000000c687e0-c000000000c68904: extcon_unregister_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
int extcon_unregister_notifier(struct extcon_dev *edev, unsigned int id, struct notifier_block *nb);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/extcon/extcon.c (ffffffe00073198a)
Location: drivers/extcon/extcon.c:928
Inline: True
Direct callers:
  - drivers/extcon/devres.c:devm_extcon_dev_notifier_unreg
```
**Symbols:**

```
ffffffe00073198a-ffffffe000731a1e: extcon_unregister_notifier (STB_GLOBAL)
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
int extcon_unregister_notifier(struct extcon_dev *edev, unsigned int id, struct notifier_block *nb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/extcon/extcon.c (ffffffff8189cac0)
Location: drivers/extcon/extcon.c:928
Inline: False
Direct callers:
  - drivers/extcon/devres.c:devm_extcon_dev_notifier_unreg
```
**Symbols:**

```
ffffffff8189cac0-ffffffff8189cb5f: extcon_unregister_notifier (STB_GLOBAL)
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
int extcon_unregister_notifier(struct extcon_dev *edev, unsigned int id, struct notifier_block *nb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/extcon/extcon.c (ffffffff818ec1b0)
Location: drivers/extcon/extcon.c:928
Inline: False
Direct callers:
  - drivers/extcon/devres.c:devm_extcon_dev_notifier_unreg
```
**Symbols:**

```
ffffffff818ec1b0-ffffffff818ec24f: extcon_unregister_notifier (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int extcon_unregister_notifier(struct extcon_dev *edev, unsigned int id, struct notifier_block *nb);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/extcon/extcon.c (ffffffff8190d230)
Location: drivers/extcon/extcon.c:928
Inline: False
Direct callers:
  - drivers/extcon/devres.c:devm_extcon_dev_notifier_unreg
```
**Symbols:**

```
ffffffff8190d230-ffffffff8190d2cf: extcon_unregister_notifier (STB_GLOBAL)
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
