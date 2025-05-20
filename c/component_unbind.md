# Function: <code>component_unbind</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/base/component.c (ffffffff81545c10)
Location: drivers/base/component.c:353
Inline: True
Direct callers:
  - drivers/base/component.c:component_unbind_all
  - drivers/base/component.c:component_bind_all
```
**Symbols:**

```
ffffffff81545c10-ffffffff81545c6f: component_unbind.isra.3 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/base/component.c (ffffffff815976d0)
Location: drivers/base/component.c:356
Inline: True
Direct callers:
  - drivers/base/component.c:component_bind_all
  - drivers/base/component.c:component_unbind_all
```
**Symbols:**

```
ffffffff815976d0-ffffffff8159772f: component_unbind.isra.8 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/base/component.c (ffffffff815c5220)
Location: drivers/base/component.c:356
Inline: True
Direct callers:
  - drivers/base/component.c:component_bind_all
  - drivers/base/component.c:component_unbind_all
```
**Symbols:**

```
ffffffff815c5220-ffffffff815c527f: component_unbind.isra.10 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/base/component.c (ffffffff815d9e30)
Location: drivers/base/component.c:356
Inline: True
Direct callers:
  - drivers/base/component.c:component_bind_all
  - drivers/base/component.c:component_unbind_all
```
**Symbols:**

```
ffffffff815d9e30-ffffffff815d9e68: component_unbind.isra.7 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/base/component.c (ffffffff81640ba0)
Location: drivers/base/component.c:356
Inline: True
Direct callers:
  - drivers/base/component.c:component_bind_all
  - drivers/base/component.c:component_unbind_all
```
**Symbols:**

```
ffffffff81640ba0-ffffffff81640bde: component_unbind.isra.7 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/base/component.c (ffffffff8167bea0)
Location: drivers/base/component.c:431
Inline: True
Direct callers:
  - drivers/base/component.c:component_bind_all
  - drivers/base/component.c:component_unbind_all
```
**Symbols:**

```
ffffffff8167bea0-ffffffff8167bede: component_unbind.isra.10 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/base/component.c (ffffffff8169bc20)
Location: drivers/base/component.c:421
Inline: True
Direct callers:
  - drivers/base/component.c:component_bind_all
  - drivers/base/component.c:component_unbind_all
```
**Symbols:**

```
ffffffff8169bc20-ffffffff8169bc5e: component_unbind.isra.10 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/base/component.c (0)
Location: drivers/base/component.c:527
Inline: True
Direct callers:
  - drivers/base/component.c:component_bind_all
  - drivers/base/component.c:component_unbind_all
```
**Symbols:**

```
ffffffff816d4730-ffffffff816d477d: component_unbind.isra.0 (STB_LOCAL)
ffffffff816d4d51-ffffffff816d4d74: component_unbind.isra.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/base/component.c (ffffffff816f85f0)
Location: drivers/base/component.c:527
Inline: True
Direct callers:
  - drivers/base/component.c:component_bind_all
  - drivers/base/component.c:component_unbind_all
```
**Symbols:**

```
ffffffff816f85f0-ffffffff816f8635: component_unbind.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void component_unbind(struct component *component, struct master *master, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/component.c (ffffffff817b0c30)
Location: drivers/base/component.c:527
Inline: False
Direct callers:
  - drivers/base/component.c:component_bind_all
  - drivers/base/component.c:component_unbind_all
```
**Symbols:**

```
ffffffff817b0c30-ffffffff817b0c82: component_unbind (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void component_unbind(struct component *component, struct master *master, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/component.c (ffffffff817c5580)
Location: drivers/base/component.c:527
Inline: False
Direct callers:
  - drivers/base/component.c:component_bind_all
  - drivers/base/component.c:component_unbind_all
```
**Symbols:**

```
ffffffff817c5580-ffffffff817c55d2: component_unbind (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void component_unbind(struct component *component, struct master *master, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/component.c (ffffffff817a88d0)
Location: drivers/base/component.c:524
Inline: False
Direct callers:
  - drivers/base/component.c:component_bind_all
  - drivers/base/component.c:component_unbind_all
```
**Symbols:**

```
ffffffff817a88d0-ffffffff817a8922: component_unbind (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void component_unbind(struct component *component, struct master *master, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/component.c (0)
Location: drivers/base/component.c:519
Inline: False
Direct callers:
  - drivers/base/component.c:component_bind_all
  - drivers/base/component.c:component_unbind_all
```
**Symbols:**

```
ffffffff81831c60-ffffffff81831cd0: component_unbind (STB_LOCAL)
ffffffff81d0240a-ffffffff81d02427: component_unbind.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void component_unbind(struct component *component, struct aggregate_device *adev, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/component.c (0)
Location: drivers/base/component.c:572
Inline: False
Direct callers:
  - drivers/base/component.c:component_bind_all
  - drivers/base/component.c:component_unbind_all
```
**Symbols:**

```
ffffffff81973280-ffffffff819732f8: component_unbind (STB_LOCAL)
ffffffff81eca99c-ffffffff81eca9b9: component_unbind.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void component_unbind(struct component *component, struct aggregate_device *adev, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/component.c (0)
Location: drivers/base/component.c:572
Inline: False
Direct callers:
  - drivers/base/component.c:component_bind_all
  - drivers/base/component.c:component_unbind_all
```
**Symbols:**

```
ffffffff81ade6e0-ffffffff81ade758: component_unbind (STB_LOCAL)
ffffffff82098234-ffffffff82098251: component_unbind.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void component_unbind(struct component *component, struct aggregate_device *adev, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/component.c (0)
Location: drivers/base/component.c:572
Inline: False
Direct callers:
  - drivers/base/component.c:component_bind_all
  - drivers/base/component.c:component_unbind_all
```
**Symbols:**

```
ffffffff81b2c960-ffffffff81b2c9d8: component_unbind (STB_LOCAL)
ffffffff82119260-ffffffff8211927d: component_unbind.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void component_unbind(struct component *component, struct aggregate_device *adev, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/component.c (0)
Location: drivers/base/component.c:572
Inline: False
Direct callers:
  - drivers/base/component.c:component_bind_all
  - drivers/base/component.c:component_unbind_all
```
**Symbols:**

```
ffffffff81b84100-ffffffff81b84178: component_unbind (STB_LOCAL)
ffffffff821f7223-ffffffff821f7240: component_unbind.cold (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/base/component.c (ffff8000108e22c8)
Location: drivers/base/component.c:527
Inline: True
Direct callers:
  - drivers/base/component.c:component_bind_all
  - drivers/base/component.c:component_unbind_all
```
**Symbols:**

```
ffff8000108e22c8-ffff8000108e2334: component_unbind.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void component_unbind(struct component *component, struct master *master, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/component.c (c09d0904)
Location: drivers/base/component.c:527
Inline: False
Direct callers:
  - drivers/base/component.c:component_bind_all
  - drivers/base/component.c:component_unbind_all
```
**Symbols:**

```
c09d0904-c09d0978: component_unbind (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/base/component.c (c000000000976670)
Location: drivers/base/component.c:527
Inline: True
Direct callers:
  - drivers/base/component.c:component_bind_all
  - drivers/base/component.c:component_unbind_all
```
**Symbols:**

```
c000000000976670-c0000000009766ec: component_unbind.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/base/component.c (ffffffe000577548)
Location: drivers/base/component.c:527
Inline: True
Direct callers:
  - drivers/base/component.c:component_bind_all
  - drivers/base/component.c:component_unbind_all
```
**Symbols:**

```
ffffffe000577548-ffffffe00057759c: component_unbind.isra.0 (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/base/component.c (ffffffff816bdde0)
Location: drivers/base/component.c:527
Inline: True
Direct callers:
  - drivers/base/component.c:component_bind_all
  - drivers/base/component.c:component_unbind_all
```
**Symbols:**

```
ffffffff816bdde0-ffffffff816bde25: component_unbind.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/base/component.c (ffffffff81699090)
Location: drivers/base/component.c:527
Inline: True
Direct callers:
  - drivers/base/component.c:component_bind_all
  - drivers/base/component.c:component_unbind_all
```
**Symbols:**

```
ffffffff81699090-ffffffff816990d5: component_unbind.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/base/component.c (ffffffff816ec2b0)
Location: drivers/base/component.c:527
Inline: True
Direct callers:
  - drivers/base/component.c:component_bind_all
  - drivers/base/component.c:component_unbind_all
```
**Symbols:**

```
ffffffff816ec2b0-ffffffff816ec2f5: component_unbind.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/base/component.c (ffffffff81706af0)
Location: drivers/base/component.c:527
Inline: True
Direct callers:
  - drivers/base/component.c:component_bind_all
  - drivers/base/component.c:component_unbind_all
```
**Symbols:**

```
ffffffff81706af0-ffffffff81706b35: component_unbind.isra.0 (STB_LOCAL)
```
</details>
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
<details>
<summary>Changed between <code>5.15</code> and <code>5.19</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct aggregate_device *adev</code>
</li>
<li>
<b>Param removed. </b>
<code>struct master *master</code>
</li>
</ul>
</details>
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
