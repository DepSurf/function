# Function: <code>rproc_alloc</code>

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
In <code>4.13</code>: Absent ⚠️
</li>
<li>
In <code>4.15</code>: Absent ⚠️
</li>
<li>
In <code>4.18</code>: Absent ⚠️
</li>
<li>
In <code>5.0</code>: Absent ⚠️
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
struct rproc *rproc_alloc(struct device *dev, const char *name, const struct rproc_ops *ops, const char *firmware, int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/remoteproc/remoteproc_core.c (0)
Location: drivers/remoteproc/remoteproc_core.c:1989
Inline: False
```
**Symbols:**

```
ffffffff818f5651-ffffffff818f5670: rproc_alloc.cold (STB_LOCAL)
ffffffff818f4030-ffffffff818f4352: rproc_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct rproc *rproc_alloc(struct device *dev, const char *name, const struct rproc_ops *ops, const char *firmware, int len);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/remoteproc/remoteproc_core.c (ffffffff819c976c)
Location: drivers/remoteproc/remoteproc_core.c:2127
Inline: True
Inline callers:
  - drivers/remoteproc/remoteproc_core.c:devm_rproc_alloc
Direct callers:
  - drivers/remoteproc/remoteproc_core.c:devm_rproc_alloc
```
**Symbols:**

```
ffffffff819c9300-ffffffff819c95c3: rproc_alloc.part.0 (STB_LOCAL)
ffffffff819cb8ab-ffffffff819cb8c0: rproc_alloc.part.0.cold (STB_LOCAL)
ffffffff819c95d0-ffffffff819c95fa: rproc_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct rproc *rproc_alloc(struct device *dev, const char *name, const struct rproc_ops *ops, const char *firmware, int len);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/remoteproc/remoteproc_core.c (ffffffff819c92ac)
Location: drivers/remoteproc/remoteproc_core.c:2232
Inline: True
Inline callers:
  - drivers/remoteproc/remoteproc_core.c:devm_rproc_alloc
Direct callers:
  - drivers/remoteproc/remoteproc_core.c:devm_rproc_alloc
```
**Symbols:**

```
ffffffff819c8f20-ffffffff819c91e6: rproc_alloc.part.0 (STB_LOCAL)
ffffffff81c2e421-ffffffff81c2e436: rproc_alloc.part.0.cold (STB_LOCAL)
ffffffff819c91f0-ffffffff819c921a: rproc_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct rproc *rproc_alloc(struct device *dev, const char *name, const struct rproc_ops *ops, const char *firmware, int len);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/remoteproc/remoteproc_core.c (ffffffff819ae37c)
Location: drivers/remoteproc/remoteproc_core.c:2479
Inline: True
Inline callers:
  - drivers/remoteproc/remoteproc_core.c:devm_rproc_alloc
Direct callers:
  - drivers/remoteproc/remoteproc_core.c:devm_rproc_alloc
```
**Symbols:**

```
ffffffff819adff0-ffffffff819ae2bc: rproc_alloc.part.0 (STB_LOCAL)
ffffffff81c204fb-ffffffff81c20510: rproc_alloc.part.0.cold (STB_LOCAL)
ffffffff819ae2c0-ffffffff819ae2ea: rproc_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct rproc *rproc_alloc(struct device *dev, const char *name, const struct rproc_ops *ops, const char *firmware, int len);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/remoteproc/remoteproc_core.c (ffffffff81a5ca83)
Location: drivers/remoteproc/remoteproc_core.c:2508
Inline: True
Inline callers:
  - drivers/remoteproc/remoteproc_core.c:devm_rproc_alloc
Direct callers:
  - drivers/remoteproc/remoteproc_core.c:devm_rproc_alloc
```
**Symbols:**

```
ffffffff81a5c5f0-ffffffff81a5c8bc: rproc_alloc.part.0 (STB_LOCAL)
ffffffff81d31ee3-ffffffff81d31ef8: rproc_alloc.part.0.cold (STB_LOCAL)
ffffffff81a5c8c0-ffffffff81a5c8ea: rproc_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
struct rproc *rproc_alloc(struct device *dev, const char *name, const struct rproc_ops *ops, const char *firmware, int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/remoteproc/remoteproc_core.c (0)
Location: drivers/remoteproc/remoteproc_core.c:2518
Inline: False
Direct callers:
  - drivers/remoteproc/remoteproc_core.c:devm_rproc_alloc
```
**Symbols:**

```
ffffffff81efe3fd-ffffffff81efe411: rproc_alloc.cold (STB_LOCAL)
ffffffff81bcc610-ffffffff81bcc909: rproc_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct rproc *rproc_alloc(struct device *dev, const char *name, const struct rproc_ops *ops, const char *firmware, int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/remoteproc/remoteproc_core.c (ffffffff81d76d10)
Location: drivers/remoteproc/remoteproc_core.c:2442
Inline: False
Direct callers:
  - drivers/remoteproc/remoteproc_core.c:devm_rproc_alloc
```
**Symbols:**

```
ffffffff81d76d10-ffffffff81d77021: rproc_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct rproc *rproc_alloc(struct device *dev, const char *name, const struct rproc_ops *ops, const char *firmware, int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/remoteproc/remoteproc_core.c (ffffffff81de4c50)
Location: drivers/remoteproc/remoteproc_core.c:2443
Inline: False
Direct callers:
  - drivers/remoteproc/remoteproc_core.c:devm_rproc_alloc
```
**Symbols:**

```
ffffffff81de4c50-ffffffff81de4f61: rproc_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct rproc *rproc_alloc(struct device *dev, const char *name, const struct rproc_ops *ops, const char *firmware, int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/remoteproc/remoteproc_core.c (ffffffff81e9ad40)
Location: drivers/remoteproc/remoteproc_core.c:2443
Inline: False
Direct callers:
  - drivers/remoteproc/remoteproc_core.c:devm_rproc_alloc
```
**Symbols:**

```
ffffffff81e9ad40-ffffffff81e9b051: rproc_alloc (STB_GLOBAL)
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
struct rproc *rproc_alloc(struct device *dev, const char *name, const struct rproc_ops *ops, const char *firmware, int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/remoteproc/remoteproc_core.c (ffff800010b80188)
Location: drivers/remoteproc/remoteproc_core.c:1989
Inline: False
```
**Symbols:**

```
ffff800010b80188-ffff800010b80430: rproc_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct rproc *rproc_alloc(struct device *dev, const char *name, const struct rproc_ops *ops, const char *firmware, int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/remoteproc/remoteproc_core.c (c0c637ac)
Location: drivers/remoteproc/remoteproc_core.c:1989
Inline: False
```
**Symbols:**

```
c0c637ac-c0c63a50: rproc_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct rproc *rproc_alloc(struct device *dev, const char *name, const struct rproc_ops *ops, const char *firmware, int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/remoteproc/remoteproc_core.c (c000000000c5c650)
Location: drivers/remoteproc/remoteproc_core.c:1989
Inline: False
```
**Symbols:**

```
c000000000c5c650-c000000000c5c9b8: rproc_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
struct rproc *rproc_alloc(struct device *dev, const char *name, const struct rproc_ops *ops, const char *firmware, int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/remoteproc/remoteproc_core.c (0)
Location: drivers/remoteproc/remoteproc_core.c:1989
Inline: False
```
**Symbols:**

```
ffffffff81896981-ffffffff818969a0: rproc_alloc.cold (STB_LOCAL)
ffffffff81895360-ffffffff81895682: rproc_alloc (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
struct rproc *rproc_alloc(struct device *dev, const char *name, const struct rproc_ops *ops, const char *firmware, int len);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/remoteproc/remoteproc_core.c (0)
Location: drivers/remoteproc/remoteproc_core.c:1989
Inline: False
```
**Symbols:**

```
ffffffff819070e1-ffffffff81907100: rproc_alloc.cold (STB_LOCAL)
ffffffff81905ac0-ffffffff81905de2: rproc_alloc (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
