# Function: <code>devm_remove_action</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
void devm_remove_action(struct device *dev, void (*action)(void *), void *data);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/devres.c (ffffffff81550140)
Location: drivers/base/devres.c:736
Inline: True
```
**Symbols:**

```
ffffffff81550140-ffffffff815501b1: devm_remove_action (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void devm_remove_action(struct device *dev, void (*action)(void *), void *data);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/devres.c (ffffffff815a1f40)
Location: drivers/base/devres.c:736
Inline: True
```
**Symbols:**

```
ffffffff815a1f40-ffffffff815a1fb1: devm_remove_action (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void devm_remove_action(struct device *dev, void (*action)(void *), void *data);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/devres.c (ffffffff815d0660)
Location: drivers/base/devres.c:737
Inline: True
```
**Symbols:**

```
ffffffff815d0660-ffffffff815d06d1: devm_remove_action (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void devm_remove_action(struct device *dev, void (*action)(void *), void *data);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/devres.c (ffffffff815e4e00)
Location: drivers/base/devres.c:737
Inline: True
```
**Symbols:**

```
ffffffff815e4e00-ffffffff815e4e62: devm_remove_action (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void devm_remove_action(struct device *dev, void (*action)(void *), void *data);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/devres.c (ffffffff8164c0e0)
Location: drivers/base/devres.c:737
Inline: True
Direct callers:
  - mm/hmm.c:hmm_devmem_ref_kill
  - mm/hmm.c:hmm_devmem_ref_exit
```
**Symbols:**

```
ffffffff8164c0e0-ffffffff8164c142: devm_remove_action (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void devm_remove_action(struct device *dev, void (*action)(void *), void *data);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/devres.c (ffffffff81687700)
Location: drivers/base/devres.c:741
Inline: True
Direct callers:
  - mm/hmm.c:hmm_devmem_ref_kill
  - mm/hmm.c:hmm_devmem_ref_exit
```
**Symbols:**

```
ffffffff81687700-ffffffff81687759: devm_remove_action (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void devm_remove_action(struct device *dev, void (*action)(void *), void *data);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/devres.c (ffffffff816a7670)
Location: drivers/base/devres.c:749
Inline: True
```
**Symbols:**

```
ffffffff816a7670-ffffffff816a76c9: devm_remove_action (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

```c
void devm_remove_action(struct device *dev, void (*action)(void *), void *data);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/base/devres.c (ffffffff816e0977)
Location: drivers/base/devres.c:749
Inline: True
```
**Symbols:**

```
ffffffff816e0977-ffffffff816e098a: devm_remove_action.cold (STB_LOCAL)
ffffffff816e0770-ffffffff816e07d2: devm_remove_action (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void devm_remove_action(struct device *dev, void (*action)(void *), void *data);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/devres.c (ffffffff81704990)
Location: drivers/base/devres.c:749
Inline: True
```
**Symbols:**

```
ffffffff81704990-ffffffff817049f2: devm_remove_action (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void devm_remove_action(struct device *dev, void (*action)(void *), void *data);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/devres.c (ffffffff817bee40)
Location: drivers/base/devres.c:749
Inline: True
```
**Symbols:**

```
ffffffff817bee40-ffffffff817beeff: devm_remove_action (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void devm_remove_action(struct device *dev, void (*action)(void *), void *data);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/devres.c (ffffffff817d3a90)
Location: drivers/base/devres.c:765
Inline: True
```
**Symbols:**

```
ffffffff817d3a90-ffffffff817d3b4f: devm_remove_action (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void devm_remove_action(struct device *dev, void (*action)(void *), void *data);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/devres.c (ffffffff817b74a0)
Location: drivers/base/devres.c:765
Inline: True
```
**Symbols:**

```
ffffffff817b74a0-ffffffff817b755f: devm_remove_action (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void devm_remove_action(struct device *dev, void (*action)(void *), void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/devres.c (ffffffff81840e20)
Location: drivers/base/devres.c:754
Inline: False
```
**Symbols:**

```
ffffffff81840e20-ffffffff81840e8e: devm_remove_action (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void devm_remove_action(struct device *dev, void (*action)(void *), void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/devres.c (ffffffff81984190)
Location: drivers/base/devres.c:754
Inline: False
```
**Symbols:**

```
ffffffff81984190-ffffffff8198420c: devm_remove_action (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void devm_remove_action(struct device *dev, void (*action)(void *), void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/devres.c (ffffffff81af22a0)
Location: drivers/base/devres.c:759
Inline: False
```
**Symbols:**

```
ffffffff81af22a0-ffffffff81af231c: devm_remove_action (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void devm_remove_action(struct device *dev, void (*action)(void *), void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/devres.c (ffffffff81b40450)
Location: drivers/base/devres.c:760
Inline: False
```
**Symbols:**

```
ffffffff81b40450-ffffffff81b404cc: devm_remove_action (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void devm_remove_action(struct device *dev, void (*action)(void *), void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/devres.c (ffffffff81b982f0)
Location: drivers/base/devres.c:760
Inline: False
```
**Symbols:**

```
ffffffff81b982f0-ffffffff81b9836c: devm_remove_action (STB_GLOBAL)
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
void devm_remove_action(struct device *dev, void (*action)(void *), void *data);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/devres.c (ffff8000108f0730)
Location: drivers/base/devres.c:749
Inline: True
```
**Symbols:**

```
ffff8000108f0730-ffff8000108f07bc: devm_remove_action (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void devm_remove_action(struct device *dev, void (*action)(void *), void *data);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/devres.c (c09ddaf0)
Location: drivers/base/devres.c:749
Inline: True
```
**Symbols:**

```
c09ddaf0-c09ddb8c: devm_remove_action (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void devm_remove_action(struct device *dev, void (*action)(void *), void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/devres.c (c000000000989b80)
Location: drivers/base/devres.c:749
Inline: False
```
**Symbols:**

```
c000000000989b80-c000000000989c0c: devm_remove_action (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void devm_remove_action(struct device *dev, void (*action)(void *), void *data);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/devres.c (ffffffe000582d3a)
Location: drivers/base/devres.c:749
Inline: True
```
**Symbols:**

```
ffffffe000582d3a-ffffffe000582da6: devm_remove_action (STB_GLOBAL)
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
void devm_remove_action(struct device *dev, void (*action)(void *), void *data);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/devres.c (ffffffff816ca0e0)
Location: drivers/base/devres.c:749
Inline: True
```
**Symbols:**

```
ffffffff816ca0e0-ffffffff816ca142: devm_remove_action (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void devm_remove_action(struct device *dev, void (*action)(void *), void *data);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/devres.c (ffffffff816a5410)
Location: drivers/base/devres.c:749
Inline: True
```
**Symbols:**

```
ffffffff816a5410-ffffffff816a5472: devm_remove_action (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void devm_remove_action(struct device *dev, void (*action)(void *), void *data);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/devres.c (ffffffff816f8650)
Location: drivers/base/devres.c:749
Inline: True
```
**Symbols:**

```
ffffffff816f8650-ffffffff816f86b2: devm_remove_action (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void devm_remove_action(struct device *dev, void (*action)(void *), void *data);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/devres.c (ffffffff81712ef0)
Location: drivers/base/devres.c:749
Inline: True
```
**Symbols:**

```
ffffffff81712ef0-ffffffff81712f52: devm_remove_action (STB_GLOBAL)
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
