# Function: <code>isa_register_driver</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
int isa_register_driver(struct isa_driver *isa_driver, unsigned int ndev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/isa.c (ffffffff815b2510)
Location: drivers/base/isa.c:114
Inline: False
```
**Symbols:**

```
ffffffff815b2510-ffffffff815b2677: isa_register_driver (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
int isa_register_driver(struct isa_driver *isa_driver, unsigned int ndev);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/isa.c (ffffffff815e1810)
Location: drivers/base/isa.c:114
Inline: False
```
**Symbols:**

```
ffffffff815e1810-ffffffff815e1977: isa_register_driver (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int isa_register_driver(struct isa_driver *isa_driver, unsigned int ndev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/isa.c (ffffffff815f6580)
Location: drivers/base/isa.c:114
Inline: True
```
**Symbols:**

```
ffffffff815f6580-ffffffff815f66dd: isa_register_driver (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int isa_register_driver(struct isa_driver *isa_driver, unsigned int ndev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/isa.c (ffffffff8165e4e0)
Location: drivers/base/isa.c:114
Inline: True
```
**Symbols:**

```
ffffffff8165e4e0-ffffffff8165e63d: isa_register_driver (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
int isa_register_driver(struct isa_driver *isa_driver, unsigned int ndev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/isa.c (ffffffff81699a20)
Location: drivers/base/isa.c:115
Inline: True
```
**Symbols:**

```
ffffffff81699a20-ffffffff81699b8a: isa_register_driver (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int isa_register_driver(struct isa_driver *isa_driver, unsigned int ndev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/isa.c (ffffffff816ba280)
Location: drivers/base/isa.c:115
Inline: True
```
**Symbols:**

```
ffffffff816ba280-ffffffff816ba3d8: isa_register_driver (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
int isa_register_driver(struct isa_driver *isa_driver, unsigned int ndev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/isa.c (ffffffff816f4550)
Location: drivers/base/isa.c:115
Inline: True
```
**Symbols:**

```
ffffffff816f4550-ffffffff816f46b1: isa_register_driver (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int isa_register_driver(struct isa_driver *isa_driver, unsigned int ndev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/isa.c (ffffffff81718950)
Location: drivers/base/isa.c:115
Inline: True
```
**Symbols:**

```
ffffffff81718950-ffffffff81718ab1: isa_register_driver (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
int isa_register_driver(struct isa_driver *isa_driver, unsigned int ndev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/base/isa.c (ffffffff817d4530)
Location: drivers/base/isa.c:115
Inline: True
```
**Symbols:**

```
ffffffff817d4530-ffffffff817d4694: isa_register_driver.part.0 (STB_LOCAL)
ffffffff817d46a0-ffffffff817d46e4: isa_register_driver (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

```c
int isa_register_driver(struct isa_driver *isa_driver, unsigned int ndev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/base/isa.c (ffffffff817e8ef0)
Location: drivers/base/isa.c:115
Inline: True
```
**Symbols:**

```
ffffffff817e8ef0-ffffffff817e9054: isa_register_driver.part.0 (STB_LOCAL)
ffffffff817e9060-ffffffff817e90a4: isa_register_driver (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int isa_register_driver(struct isa_driver *isa_driver, unsigned int ndev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/isa.c (ffffffff817cd6f0)
Location: drivers/base/isa.c:115
Inline: True
```
**Symbols:**

```
ffffffff817cd6f0-ffffffff817cd874: isa_register_driver (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int isa_register_driver(struct isa_driver *isa_driver, unsigned int ndev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/isa.c (ffffffff81857ee0)
Location: drivers/base/isa.c:113
Inline: True
```
**Symbols:**

```
ffffffff81857ee0-ffffffff81858064: isa_register_driver (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
int isa_register_driver(struct isa_driver *isa_driver, unsigned int ndev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/isa.c (ffffffff8199e550)
Location: drivers/base/isa.c:113
Inline: True
```
**Symbols:**

```
ffffffff8199e550-ffffffff8199e6e0: isa_register_driver (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
int isa_register_driver(struct isa_driver *isa_driver, unsigned int ndev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/isa.c (ffffffff81b0fea0)
Location: drivers/base/isa.c:113
Inline: True
```
**Symbols:**

```
ffffffff81b0fea0-ffffffff81b10030: isa_register_driver (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
int isa_register_driver(struct isa_driver *isa_driver, unsigned int ndev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/isa.c (ffffffff81b5df70)
Location: drivers/base/isa.c:113
Inline: True
```
**Symbols:**

```
ffffffff81b5df70-ffffffff81b5e0e5: isa_register_driver (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
int isa_register_driver(struct isa_driver *isa_driver, unsigned int ndev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/isa.c (ffffffff81bb1850)
Location: drivers/base/isa.c:113
Inline: True
```
**Symbols:**

```
ffffffff81bb1850-ffffffff81bb19fb: isa_register_driver (STB_GLOBAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>arm64</code>: Absent ⚠️
</li>
<li>
In <code>armhf</code>: Absent ⚠️
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
int isa_register_driver(struct isa_driver *isa_driver, unsigned int ndev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/isa.c (ffffffff816dec80)
Location: drivers/base/isa.c:115
Inline: True
```
**Symbols:**

```
ffffffff816dec80-ffffffff816dede1: isa_register_driver (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int isa_register_driver(struct isa_driver *isa_driver, unsigned int ndev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/isa.c (ffffffff816b92c0)
Location: drivers/base/isa.c:115
Inline: True
```
**Symbols:**

```
ffffffff816b92c0-ffffffff816b9421: isa_register_driver (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int isa_register_driver(struct isa_driver *isa_driver, unsigned int ndev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/isa.c (ffffffff8170c610)
Location: drivers/base/isa.c:115
Inline: True
```
**Symbols:**

```
ffffffff8170c610-ffffffff8170c771: isa_register_driver (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int isa_register_driver(struct isa_driver *isa_driver, unsigned int ndev);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/isa.c (ffffffff81726fc0)
Location: drivers/base/isa.c:115
Inline: True
```
**Symbols:**

```
ffffffff81726fc0-ffffffff81727121: isa_register_driver (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
