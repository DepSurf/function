# Function: <code>__devm_ioremap_resource</code>

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
In <code>5.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
void *__devm_ioremap_resource(struct device *dev, const struct resource *res, enum devm_ioremap_type type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/devres.c (0)
Location: lib/devres.c:117
Inline: False
Direct callers:
  - lib/devres.c:devm_ioremap_resource_wc
```
**Symbols:**

```
ffffffff81596490-ffffffff81596578: __devm_ioremap_resource (STB_LOCAL)
ffffffff81596b50-ffffffff81596bbd: __devm_ioremap_resource.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
void *__devm_ioremap_resource(struct device *dev, const struct resource *res, enum devm_ioremap_type type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/devres.c (0)
Location: lib/devres.c:117
Inline: False
Direct callers:
  - lib/devres.c:devm_ioremap_resource_wc
```
**Symbols:**

```
ffffffff815b1f20-ffffffff815b2008: __devm_ioremap_resource (STB_LOCAL)
ffffffff81bf4039-ffffffff81bf40a6: __devm_ioremap_resource.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
void *__devm_ioremap_resource(struct device *dev, const struct resource *res, enum devm_ioremap_type type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/devres.c (0)
Location: lib/devres.c:136
Inline: False
Direct callers:
  - lib/devres.c:devm_ioremap_resource_wc
```
**Symbols:**

```
ffffffff815bcd40-ffffffff815bce4b: __devm_ioremap_resource (STB_LOCAL)
ffffffff81be5eb8-ffffffff81be5f25: __devm_ioremap_resource.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void *__devm_ioremap_resource(struct device *dev, const struct resource *res, enum devm_ioremap_type type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/devres.c (0)
Location: lib/devres.c:136
Inline: False
Direct callers:
  - lib/devres.c:devm_ioremap_resource_wc
```
**Symbols:**

```
ffffffff81624000-ffffffff81624106: __devm_ioremap_resource (STB_LOCAL)
ffffffff81cdb0eb-ffffffff81cdb176: __devm_ioremap_resource.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void *__devm_ioremap_resource(struct device *dev, const struct resource *res, enum devm_ioremap_type type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In lib/devres.c (0)
Location: lib/devres.c:136
Inline: False
Direct callers:
  - lib/devres.c:devm_ioremap_resource_wc
```
**Symbols:**

```
ffffffff816f4430-ffffffff816f454d: __devm_ioremap_resource (STB_LOCAL)
ffffffff81e93942-ffffffff81e939c2: __devm_ioremap_resource.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void *__devm_ioremap_resource(struct device *dev, const struct resource *res, enum devm_ioremap_type type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/devres.c (ffffffff817e64e0)
Location: lib/devres.c:122
Inline: False
Direct callers:
  - lib/devres.c:devm_ioremap_resource_wc
```
**Symbols:**

```
ffffffff817e64e0-ffffffff817e6666: __devm_ioremap_resource (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void *__devm_ioremap_resource(struct device *dev, const struct resource *res, enum devm_ioremap_type type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/devres.c (ffffffff818264c0)
Location: lib/devres.c:122
Inline: False
Direct callers:
  - lib/devres.c:devm_ioremap_resource_wc
```
**Symbols:**

```
ffffffff818264c0-ffffffff81826658: __devm_ioremap_resource (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void *__devm_ioremap_resource(struct device *dev, const struct resource *res, enum devm_ioremap_type type);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In lib/devres.c (ffffffff81877ed0)
Location: lib/devres.c:122
Inline: False
Direct callers:
  - lib/devres.c:devm_ioremap_resource_wc
```
**Symbols:**

```
ffffffff81877ed0-ffffffff81878068: __devm_ioremap_resource (STB_LOCAL)
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
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
