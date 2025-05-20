# Function: <code>devm_free_percpu</code>

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
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void devm_free_percpu(struct device *dev, void *pdata);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/devres.c (ffffffff815d07a0)
Location: drivers/base/devres.c:1048
Inline: True
```
**Symbols:**

```
ffffffff815d07a0-ffffffff815d07e1: devm_free_percpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void devm_free_percpu(struct device *dev, void *pdata);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/devres.c (ffffffff815e4eb0)
Location: drivers/base/devres.c:1048
Inline: True
```
**Symbols:**

```
ffffffff815e4eb0-ffffffff815e4ee2: devm_free_percpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void devm_free_percpu(struct device *dev, void *pdata);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/devres.c (ffffffff8164c190)
Location: drivers/base/devres.c:1048
Inline: True
```
**Symbols:**

```
ffffffff8164c190-ffffffff8164c1c2: devm_free_percpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void devm_free_percpu(struct device *dev, void *pdata);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/devres.c (ffffffff81687790)
Location: drivers/base/devres.c:1052
Inline: True
```
**Symbols:**

```
ffffffff81687790-ffffffff816877b9: devm_free_percpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void devm_free_percpu(struct device *dev, void *pdata);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/devres.c (ffffffff816a7710)
Location: drivers/base/devres.c:1090
Inline: True
```
**Symbols:**

```
ffffffff816a7710-ffffffff816a7739: devm_free_percpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

```c
void devm_free_percpu(struct device *dev, void *pdata);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/base/devres.c (ffffffff816e09c3)
Location: drivers/base/devres.c:1112
Inline: True
```
**Symbols:**

```
ffffffff816e09c3-ffffffff816e09d6: devm_free_percpu.cold (STB_LOCAL)
ffffffff816e08f0-ffffffff816e0922: devm_free_percpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void devm_free_percpu(struct device *dev, void *pdata);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/devres.c (ffffffff81704a50)
Location: drivers/base/devres.c:1112
Inline: True
```
**Symbols:**

```
ffffffff81704a50-ffffffff81704a82: devm_free_percpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void devm_free_percpu(struct device *dev, void *pdata);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/devres.c (ffffffff817bed90)
Location: drivers/base/devres.c:1112
Inline: True
```
**Symbols:**

```
ffffffff817bed90-ffffffff817bee38: devm_free_percpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void devm_free_percpu(struct device *dev, void *pdata);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/devres.c (ffffffff817d39e0)
Location: drivers/base/devres.c:1228
Inline: True
```
**Symbols:**

```
ffffffff817d39e0-ffffffff817d3a88: devm_free_percpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void devm_free_percpu(struct device *dev, void *pdata);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/devres.c (ffffffff817b73f0)
Location: drivers/base/devres.c:1228
Inline: True
```
**Symbols:**

```
ffffffff817b73f0-ffffffff817b7498: devm_free_percpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void devm_free_percpu(struct device *dev, void *pdata);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/devres.c (ffffffff81840de0)
Location: drivers/base/devres.c:1217
Inline: False
```
**Symbols:**

```
ffffffff81840de0-ffffffff81840e1e: devm_free_percpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void devm_free_percpu(struct device *dev, void *pdata);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/devres.c (ffffffff81984130)
Location: drivers/base/devres.c:1217
Inline: False
```
**Symbols:**

```
ffffffff81984130-ffffffff8198418a: devm_free_percpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void devm_free_percpu(struct device *dev, void *pdata);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/devres.c (ffffffff81af2230)
Location: drivers/base/devres.c:1222
Inline: False
```
**Symbols:**

```
ffffffff81af2230-ffffffff81af228a: devm_free_percpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void devm_free_percpu(struct device *dev, void *pdata);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/devres.c (ffffffff81b403e0)
Location: drivers/base/devres.c:1223
Inline: False
```
**Symbols:**

```
ffffffff81b403e0-ffffffff81b4043a: devm_free_percpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void devm_free_percpu(struct device *dev, void *pdata);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/devres.c (ffffffff81b98280)
Location: drivers/base/devres.c:1223
Inline: False
```
**Symbols:**

```
ffffffff81b98280-ffffffff81b982da: devm_free_percpu (STB_GLOBAL)
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
void devm_free_percpu(struct device *dev, void *pdata);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/devres.c (ffff8000108f0838)
Location: drivers/base/devres.c:1112
Inline: True
```
**Symbols:**

```
ffff8000108f0838-ffff8000108f0894: devm_free_percpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void devm_free_percpu(struct device *dev, void *pdata);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/devres.c (c09ddd38)
Location: drivers/base/devres.c:1112
Inline: True
```
**Symbols:**

```
c09ddd38-c09ddd8c: devm_free_percpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void devm_free_percpu(struct device *dev, void *pdata);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/devres.c (c000000000989c90)
Location: drivers/base/devres.c:1112
Inline: False
```
**Symbols:**

```
c000000000989c90-c000000000989ce4: devm_free_percpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void devm_free_percpu(struct device *dev, void *pdata);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/devres.c (ffffffe000582e0e)
Location: drivers/base/devres.c:1112
Inline: True
```
**Symbols:**

```
ffffffe000582e0e-ffffffe000582e68: devm_free_percpu (STB_GLOBAL)
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
void devm_free_percpu(struct device *dev, void *pdata);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/devres.c (ffffffff816ca1a0)
Location: drivers/base/devres.c:1112
Inline: True
```
**Symbols:**

```
ffffffff816ca1a0-ffffffff816ca1d2: devm_free_percpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void devm_free_percpu(struct device *dev, void *pdata);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/devres.c (ffffffff816a54d0)
Location: drivers/base/devres.c:1112
Inline: True
```
**Symbols:**

```
ffffffff816a54d0-ffffffff816a5502: devm_free_percpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void devm_free_percpu(struct device *dev, void *pdata);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/devres.c (ffffffff816f8710)
Location: drivers/base/devres.c:1112
Inline: True
```
**Symbols:**

```
ffffffff816f8710-ffffffff816f8742: devm_free_percpu (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void devm_free_percpu(struct device *dev, void *pdata);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/devres.c (ffffffff81712fb0)
Location: drivers/base/devres.c:1112
Inline: True
```
**Symbols:**

```
ffffffff81712fb0-ffffffff81712fe2: devm_free_percpu (STB_GLOBAL)
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
