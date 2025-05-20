# Function: <code>extcon_dev_allocate</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
struct extcon_dev *extcon_dev_allocate(const unsigned int *supported_cable);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/extcon/extcon.c (ffffffff816eefaf)
Location: drivers/extcon/extcon.c:669
Inline: True
Inline callers:
  - drivers/extcon/extcon.c:devm_extcon_dev_allocate
```
**Symbols:**

```
ffffffff816ef800-ffffffff816ef853: extcon_dev_allocate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct extcon_dev *extcon_dev_allocate(const unsigned int *supported_cable);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/extcon/extcon.c (ffffffff817544b0)
Location: drivers/extcon/extcon.c:540
Inline: False
Direct callers:
  - drivers/extcon/devres.c:devm_extcon_dev_allocate
```
**Symbols:**

```
ffffffff817544b0-ffffffff81754503: extcon_dev_allocate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct extcon_dev *extcon_dev_allocate(const unsigned int *supported_cable);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/extcon/extcon.c (ffffffff81780a70)
Location: drivers/extcon/extcon.c:1016
Inline: False
Direct callers:
  - drivers/extcon/devres.c:devm_extcon_dev_allocate
```
**Symbols:**

```
ffffffff81780a70-ffffffff81780ac3: extcon_dev_allocate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct extcon_dev *extcon_dev_allocate(const unsigned int *supported_cable);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/extcon/extcon.c (ffffffff8179f760)
Location: drivers/extcon/extcon.c:1058
Inline: False
Direct callers:
  - drivers/extcon/devres.c:devm_extcon_dev_allocate
```
**Symbols:**

```
ffffffff8179f760-ffffffff8179f7b1: extcon_dev_allocate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct extcon_dev *extcon_dev_allocate(const unsigned int *supported_cable);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/extcon/extcon.c (ffffffff818168b0)
Location: drivers/extcon/extcon.c:1048
Inline: False
Direct callers:
  - drivers/extcon/devres.c:devm_extcon_dev_allocate
```
**Symbols:**

```
ffffffff818168b0-ffffffff81816901: extcon_dev_allocate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct extcon_dev *extcon_dev_allocate(const unsigned int *supported_cable);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/extcon/extcon.c (ffffffff81860830)
Location: drivers/extcon/extcon.c:1049
Inline: False
Direct callers:
  - drivers/extcon/devres.c:devm_extcon_dev_allocate
```
**Symbols:**

```
ffffffff81860830-ffffffff81860880: extcon_dev_allocate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct extcon_dev *extcon_dev_allocate(const unsigned int *supported_cable);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/extcon/extcon.c (ffffffff8187fff0)
Location: drivers/extcon/extcon.c:1049
Inline: False
Direct callers:
  - drivers/extcon/devres.c:devm_extcon_dev_allocate
```
**Symbols:**

```
ffffffff8187fff0-ffffffff8188003f: extcon_dev_allocate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct extcon_dev *extcon_dev_allocate(const unsigned int *supported_cable);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/extcon/extcon.c (ffffffff818ca530)
Location: drivers/extcon/extcon.c:1041
Inline: False
Direct callers:
  - drivers/extcon/devres.c:devm_extcon_dev_allocate
```
**Symbols:**

```
ffffffff818ca530-ffffffff818ca580: extcon_dev_allocate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct extcon_dev *extcon_dev_allocate(const unsigned int *supported_cable);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/extcon/extcon.c (ffffffff818fc980)
Location: drivers/extcon/extcon.c:1041
Inline: False
Direct callers:
  - drivers/extcon/devres.c:devm_extcon_dev_allocate
```
**Symbols:**

```
ffffffff818fc980-ffffffff818fc9d0: extcon_dev_allocate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct extcon_dev *extcon_dev_allocate(const unsigned int *supported_cable);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/extcon/extcon.c (ffffffff819d3630)
Location: drivers/extcon/extcon.c:1041
Inline: False
Direct callers:
  - drivers/extcon/devres.c:devm_extcon_dev_allocate
```
**Symbols:**

```
ffffffff819d3630-ffffffff819d3686: extcon_dev_allocate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct extcon_dev *extcon_dev_allocate(const unsigned int *supported_cable);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/extcon/extcon.c (ffffffff819d3200)
Location: drivers/extcon/extcon.c:1041
Inline: False
Direct callers:
  - drivers/extcon/devres.c:devm_extcon_dev_allocate
```
**Symbols:**

```
ffffffff819d3200-ffffffff819d3256: extcon_dev_allocate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct extcon_dev *extcon_dev_allocate(const unsigned int *supported_cable);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/extcon/extcon.c (ffffffff819b84b0)
Location: drivers/extcon/extcon.c:1041
Inline: False
Direct callers:
  - drivers/extcon/devres.c:devm_extcon_dev_allocate
```
**Symbols:**

```
ffffffff819b84b0-ffffffff819b8506: extcon_dev_allocate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct extcon_dev *extcon_dev_allocate(const unsigned int *supported_cable);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/extcon/extcon.c (ffffffff81a673b0)
Location: drivers/extcon/extcon.c:1041
Inline: False
Direct callers:
  - drivers/extcon/devres.c:devm_extcon_dev_allocate
```
**Symbols:**

```
ffffffff81a673b0-ffffffff81a67406: extcon_dev_allocate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct extcon_dev *extcon_dev_allocate(const unsigned int *supported_cable);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/extcon/extcon.c (ffffffff81bd8900)
Location: drivers/extcon/extcon.c:1035
Inline: False
Direct callers:
  - drivers/extcon/devres.c:devm_extcon_dev_allocate
```
**Symbols:**

```
ffffffff81bd8900-ffffffff81bd8966: extcon_dev_allocate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct extcon_dev *extcon_dev_allocate(const unsigned int *supported_cable);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/extcon/extcon.c (ffffffff81d85330)
Location: drivers/extcon/extcon.c:1045
Inline: False
Direct callers:
  - drivers/extcon/devres.c:devm_extcon_dev_allocate
```
**Symbols:**

```
ffffffff81d85330-ffffffff81d85396: extcon_dev_allocate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct extcon_dev *extcon_dev_allocate(const unsigned int *supported_cable);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/extcon/extcon.c (ffffffff81df37a0)
Location: drivers/extcon/extcon.c:1056
Inline: False
Direct callers:
  - drivers/extcon/devres.c:devm_extcon_dev_allocate
```
**Symbols:**

```
ffffffff81df37a0-ffffffff81df3806: extcon_dev_allocate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct extcon_dev *extcon_dev_allocate(const unsigned int *supported_cable);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/extcon/extcon.c (ffffffff81ea9e00)
Location: drivers/extcon/extcon.c:1056
Inline: False
Direct callers:
  - drivers/extcon/devres.c:devm_extcon_dev_allocate
```
**Symbols:**

```
ffffffff81ea9e00-ffffffff81ea9e95: extcon_dev_allocate (STB_GLOBAL)
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
struct extcon_dev *extcon_dev_allocate(const unsigned int *supported_cable);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/extcon/extcon.c (ffff800010b89c60)
Location: drivers/extcon/extcon.c:1041
Inline: False
Direct callers:
  - drivers/extcon/devres.c:devm_extcon_dev_allocate
```
**Symbols:**

```
ffff800010b89c60-ffff800010b89cb4: extcon_dev_allocate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct extcon_dev *extcon_dev_allocate(const unsigned int *supported_cable);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/extcon/extcon.c (c0c6e1a4)
Location: drivers/extcon/extcon.c:1041
Inline: False
Direct callers:
  - drivers/extcon/devres.c:devm_extcon_dev_allocate
```
**Symbols:**

```
c0c6e1a4-c0c6e200: extcon_dev_allocate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct extcon_dev *extcon_dev_allocate(const unsigned int *supported_cable);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/extcon/extcon.c (c000000000c69600)
Location: drivers/extcon/extcon.c:1041
Inline: False
Direct callers:
  - drivers/extcon/devres.c:devm_extcon_dev_allocate
```
**Symbols:**

```
c000000000c69600-c000000000c69698: extcon_dev_allocate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
struct extcon_dev *extcon_dev_allocate(const unsigned int *supported_cable);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/extcon/extcon.c (ffffffe00073226e)
Location: drivers/extcon/extcon.c:1041
Inline: False
Direct callers:
  - drivers/extcon/devres.c:devm_extcon_dev_allocate
```
**Symbols:**

```
ffffffe00073226e-ffffffe0007322c0: extcon_dev_allocate (STB_GLOBAL)
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
struct extcon_dev *extcon_dev_allocate(const unsigned int *supported_cable);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/extcon/extcon.c (ffffffff8189dcb0)
Location: drivers/extcon/extcon.c:1041
Inline: False
Direct callers:
  - drivers/extcon/devres.c:devm_extcon_dev_allocate
```
**Symbols:**

```
ffffffff8189dcb0-ffffffff8189dd00: extcon_dev_allocate (STB_GLOBAL)
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
struct extcon_dev *extcon_dev_allocate(const unsigned int *supported_cable);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/extcon/extcon.c (ffffffff818ed3a0)
Location: drivers/extcon/extcon.c:1041
Inline: False
Direct callers:
  - drivers/extcon/devres.c:devm_extcon_dev_allocate
```
**Symbols:**

```
ffffffff818ed3a0-ffffffff818ed3f0: extcon_dev_allocate (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct extcon_dev *extcon_dev_allocate(const unsigned int *supported_cable);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/extcon/extcon.c (ffffffff8190e420)
Location: drivers/extcon/extcon.c:1041
Inline: False
Direct callers:
  - drivers/extcon/devres.c:devm_extcon_dev_allocate
```
**Symbols:**

```
ffffffff8190e420-ffffffff8190e470: extcon_dev_allocate (STB_GLOBAL)
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
