# Function: <code>__thermal_cooling_device_register</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
struct thermal_cooling_device *__thermal_cooling_device_register(struct device_node *np, char *type, void *devdata, const struct thermal_cooling_device_ops *ops);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/thermal/thermal_core.c (ffffffff81687490)
Location: drivers/thermal/thermal_core.c:1453
Inline: True
Direct callers:
  - drivers/thermal/thermal_core.c:thermal_cooling_device_register
  - drivers/thermal/thermal_core.c:thermal_of_cooling_device_register
```
**Symbols:**

```
ffffffff81687490-ffffffff8168783b: __thermal_cooling_device_register (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
struct thermal_cooling_device *__thermal_cooling_device_register(struct device_node *np, char *type, void *devdata, const struct thermal_cooling_device_ops *ops);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/thermal/thermal_core.c (ffffffff816e7f40)
Location: drivers/thermal/thermal_core.c:1459
Inline: True
Direct callers:
  - drivers/thermal/thermal_core.c:thermal_of_cooling_device_register
  - drivers/thermal/thermal_core.c:thermal_cooling_device_register
```
**Symbols:**

```
ffffffff816e7f40-ffffffff816e82df: __thermal_cooling_device_register (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
struct thermal_cooling_device *__thermal_cooling_device_register(struct device_node *np, char *type, void *devdata, const struct thermal_cooling_device_ops *ops);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/thermal/thermal_core.c (ffffffff817168b0)
Location: drivers/thermal/thermal_core.c:909
Inline: True
Direct callers:
  - drivers/thermal/thermal_core.c:thermal_of_cooling_device_register
  - drivers/thermal/thermal_core.c:thermal_cooling_device_register
```
**Symbols:**

```
ffffffff817168b0-ffffffff81716c4e: __thermal_cooling_device_register (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
struct thermal_cooling_device *__thermal_cooling_device_register(struct device_node *np, char *type, void *devdata, const struct thermal_cooling_device_ops *ops);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/thermal/thermal_core.c (ffffffff8172ec00)
Location: drivers/thermal/thermal_core.c:946
Inline: True
Direct callers:
  - drivers/thermal/thermal_core.c:thermal_of_cooling_device_register
  - drivers/thermal/thermal_core.c:thermal_cooling_device_register
```
**Symbols:**

```
ffffffff8172ec00-ffffffff8172ef8d: __thermal_cooling_device_register (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
struct thermal_cooling_device *__thermal_cooling_device_register(struct device_node *np, char *type, void *devdata, const struct thermal_cooling_device_ops *ops);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/thermal/thermal_core.c (ffffffff817a0240)
Location: drivers/thermal/thermal_core.c:942
Inline: True
Direct callers:
  - drivers/thermal/thermal_core.c:thermal_of_cooling_device_register
  - drivers/thermal/thermal_core.c:thermal_cooling_device_register
```
**Symbols:**

```
ffffffff817a0240-ffffffff817a05d3: __thermal_cooling_device_register (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct thermal_cooling_device *__thermal_cooling_device_register(struct device_node *np, char *type, void *devdata, const struct thermal_cooling_device_ops *ops);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/thermal/thermal_core.c (ffffffff817e7820)
Location: drivers/thermal/thermal_core.c:939
Inline: False
Direct callers:
  - drivers/thermal/thermal_core.c:thermal_of_cooling_device_register
  - drivers/thermal/thermal_core.c:thermal_cooling_device_register
```
**Symbols:**

```
ffffffff817e7820-ffffffff817e7bb2: __thermal_cooling_device_register (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct thermal_cooling_device *__thermal_cooling_device_register(struct device_node *np, char *type, void *devdata, const struct thermal_cooling_device_ops *ops);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/thermal/thermal_core.c (ffffffff818130c0)
Location: drivers/thermal/thermal_core.c:943
Inline: False
Direct callers:
  - drivers/thermal/thermal_core.c:thermal_of_cooling_device_register
  - drivers/thermal/thermal_core.c:thermal_cooling_device_register
```
**Symbols:**

```
ffffffff818130c0-ffffffff81813455: __thermal_cooling_device_register (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Transformation ⚠️</summary>

```c
struct thermal_cooling_device *__thermal_cooling_device_register(struct device_node *np, const char *type, void *devdata, const struct thermal_cooling_device_ops *ops);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/thermal/thermal_core.c (0)
Location: drivers/thermal/thermal_core.c:949
Inline: False
Direct callers:
  - drivers/thermal/thermal_core.c:devm_thermal_of_cooling_device_register
  - drivers/thermal/thermal_core.c:thermal_of_cooling_device_register
  - drivers/thermal/thermal_core.c:thermal_cooling_device_register
```
**Symbols:**

```
ffffffff818551f0-ffffffff81855571: __thermal_cooling_device_register (STB_LOCAL)
ffffffff81856eb3-ffffffff81856ed3: __thermal_cooling_device_register.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Transformation ⚠️</summary>

```c
struct thermal_cooling_device *__thermal_cooling_device_register(struct device_node *np, const char *type, void *devdata, const struct thermal_cooling_device_ops *ops);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/thermal/thermal_core.c (0)
Location: drivers/thermal/thermal_core.c:949
Inline: False
Direct callers:
  - drivers/thermal/thermal_core.c:devm_thermal_of_cooling_device_register
  - drivers/thermal/thermal_core.c:thermal_of_cooling_device_register
  - drivers/thermal/thermal_core.c:thermal_cooling_device_register
```
**Symbols:**

```
ffffffff81886c50-ffffffff81886fd1: __thermal_cooling_device_register (STB_LOCAL)
ffffffff81888903-ffffffff81888923: __thermal_cooling_device_register.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct thermal_cooling_device *__thermal_cooling_device_register(struct device_node *np, const char *type, void *devdata, const struct thermal_cooling_device_ops *ops);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/thermal/thermal_core.c (ffffffff81956550)
Location: drivers/thermal/thermal_core.c:937
Inline: False
Direct callers:
  - drivers/thermal/thermal_core.c:devm_thermal_of_cooling_device_register
  - drivers/thermal/thermal_core.c:thermal_of_cooling_device_register
  - drivers/thermal/thermal_core.c:thermal_cooling_device_register
```
**Symbols:**

```
ffffffff81956550-ffffffff819567ce: __thermal_cooling_device_register (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct thermal_cooling_device *__thermal_cooling_device_register(struct device_node *np, const char *type, void *devdata, const struct thermal_cooling_device_ops *ops);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/thermal/thermal_core.c (ffffffff8195a5f0)
Location: drivers/thermal/thermal_core.c:1005
Inline: False
Direct callers:
  - drivers/thermal/thermal_core.c:devm_thermal_of_cooling_device_register
  - drivers/thermal/thermal_core.c:thermal_of_cooling_device_register
  - drivers/thermal/thermal_core.c:thermal_cooling_device_register
```
**Symbols:**

```
ffffffff8195a5f0-ffffffff8195a90a: __thermal_cooling_device_register (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/thermal/thermal_core.c (ffffffff8193f699)
Location: drivers/thermal/thermal_core.c:939
Inline: True
Inline callers:
  - drivers/thermal/thermal_core.c:devm_thermal_of_cooling_device_register
  - drivers/thermal/thermal_core.c:thermal_of_cooling_device_register
  - drivers/thermal/thermal_core.c:thermal_cooling_device_register
Direct callers:
  - drivers/thermal/thermal_core.c:devm_thermal_of_cooling_device_register
  - drivers/thermal/thermal_core.c:thermal_of_cooling_device_register
  - drivers/thermal/thermal_core.c:thermal_cooling_device_register
```
**Symbols:**

```
ffffffff8193f3e0-ffffffff8193f64b: __thermal_cooling_device_register.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/thermal/thermal_core.c (ffffffff819e3f80)
Location: drivers/thermal/thermal_core.c:886
Inline: True
Inline callers:
  - drivers/thermal/thermal_core.c:devm_thermal_of_cooling_device_register
  - drivers/thermal/thermal_core.c:thermal_of_cooling_device_register
  - drivers/thermal/thermal_core.c:thermal_cooling_device_register
Direct callers:
  - drivers/thermal/thermal_core.c:devm_thermal_of_cooling_device_register
  - drivers/thermal/thermal_core.c:thermal_of_cooling_device_register
  - drivers/thermal/thermal_core.c:thermal_cooling_device_register
```
**Symbols:**

```
ffffffff819e3cc0-ffffffff819e3f2d: __thermal_cooling_device_register.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/thermal/thermal_core.c (ffffffff81b490e3)
Location: drivers/thermal/thermal_core.c:888
Inline: True
Inline callers:
  - drivers/thermal/thermal_core.c:devm_thermal_of_cooling_device_register
  - drivers/thermal/thermal_core.c:thermal_of_cooling_device_register
  - drivers/thermal/thermal_core.c:thermal_cooling_device_register
Direct callers:
  - drivers/thermal/thermal_core.c:devm_thermal_of_cooling_device_register
  - drivers/thermal/thermal_core.c:thermal_of_cooling_device_register
  - drivers/thermal/thermal_core.c:thermal_cooling_device_register
```
**Symbols:**

```
ffffffff81b48e00-ffffffff81b49081: __thermal_cooling_device_register.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/thermal/thermal_core.c (ffffffff81ce0703)
Location: drivers/thermal/thermal_core.c:875
Inline: True
Inline callers:
  - drivers/thermal/thermal_core.c:devm_thermal_of_cooling_device_register
  - drivers/thermal/thermal_core.c:thermal_of_cooling_device_register
  - drivers/thermal/thermal_core.c:thermal_cooling_device_register
Direct callers:
  - drivers/thermal/thermal_core.c:devm_thermal_of_cooling_device_register
  - drivers/thermal/thermal_core.c:thermal_of_cooling_device_register
  - drivers/thermal/thermal_core.c:thermal_cooling_device_register
```
**Symbols:**

```
ffffffff81ce03f0-ffffffff81ce069f: __thermal_cooling_device_register.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/thermal/thermal_core.c (ffffffff81d48883)
Location: drivers/thermal/thermal_core.c:828
Inline: True
Inline callers:
  - drivers/thermal/thermal_core.c:devm_thermal_of_cooling_device_register
  - drivers/thermal/thermal_core.c:thermal_of_cooling_device_register
  - drivers/thermal/thermal_core.c:thermal_cooling_device_register
Direct callers:
  - drivers/thermal/thermal_core.c:devm_thermal_of_cooling_device_register
  - drivers/thermal/thermal_core.c:thermal_of_cooling_device_register
  - drivers/thermal/thermal_core.c:thermal_cooling_device_register
```
**Symbols:**

```
ffffffff81d48530-ffffffff81d48813: __thermal_cooling_device_register.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/thermal/thermal_core.c (ffffffff81dfeb13)
Location: drivers/thermal/thermal_core.c:895
Inline: True
Inline callers:
  - drivers/thermal/thermal_core.c:devm_thermal_of_cooling_device_register
  - drivers/thermal/thermal_core.c:thermal_of_cooling_device_register
  - drivers/thermal/thermal_core.c:thermal_cooling_device_register
Direct callers:
  - drivers/thermal/thermal_core.c:devm_thermal_of_cooling_device_register
  - drivers/thermal/thermal_core.c:thermal_of_cooling_device_register
  - drivers/thermal/thermal_core.c:thermal_cooling_device_register
```
**Symbols:**

```
ffffffff81dfe7b0-ffffffff81dfeaa1: __thermal_cooling_device_register.part.0 (STB_LOCAL)
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
struct thermal_cooling_device *__thermal_cooling_device_register(struct device_node *np, const char *type, void *devdata, const struct thermal_cooling_device_ops *ops);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/thermal/thermal_core.c (ffff800010ad4ee8)
Location: drivers/thermal/thermal_core.c:949
Inline: False
Direct callers:
  - drivers/thermal/thermal_core.c:devm_thermal_of_cooling_device_register
  - drivers/thermal/thermal_core.c:thermal_of_cooling_device_register
  - drivers/thermal/thermal_core.c:thermal_cooling_device_register
```
**Symbols:**

```
ffff800010ad4ee8-ffff800010ad5274: __thermal_cooling_device_register (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct thermal_cooling_device *__thermal_cooling_device_register(struct device_node *np, const char *type, void *devdata, const struct thermal_cooling_device_ops *ops);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/thermal/thermal_core.c (c0bb4cb0)
Location: drivers/thermal/thermal_core.c:949
Inline: False
Direct callers:
  - drivers/thermal/thermal_core.c:devm_thermal_of_cooling_device_register
  - drivers/thermal/thermal_core.c:thermal_of_cooling_device_register
  - drivers/thermal/thermal_core.c:thermal_cooling_device_register
```
**Symbols:**

```
c0bb4cb0-c0bb503c: __thermal_cooling_device_register (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
struct thermal_cooling_device *__thermal_cooling_device_register(struct device_node *np, const char *type, void *devdata, const struct thermal_cooling_device_ops *ops);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/thermal/thermal_core.c (c000000000bbab30)
Location: drivers/thermal/thermal_core.c:949
Inline: False
Direct callers:
  - drivers/thermal/thermal_core.c:devm_thermal_of_cooling_device_register
  - drivers/thermal/thermal_core.c:thermal_of_cooling_device_register
  - drivers/thermal/thermal_core.c:thermal_cooling_device_register
```
**Symbols:**

```
c000000000bbab30-c000000000bbb024: __thermal_cooling_device_register (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline, Transformation ⚠️</summary>

```c
struct thermal_cooling_device *__thermal_cooling_device_register(struct device_node *np, const char *type, void *devdata, const struct thermal_cooling_device_ops *ops);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/thermal/thermal_core.c (ffffffe0006d0078)
Location: drivers/thermal/thermal_core.c:949
Inline: True
Direct callers:
  - drivers/thermal/thermal_core.c:devm_thermal_of_cooling_device_register
  - drivers/thermal/thermal_core.c:thermal_of_cooling_device_register
  - drivers/thermal/thermal_core.c:thermal_cooling_device_register
```
**Symbols:**

```
ffffffe0006d0078-ffffffe0006d0366: __thermal_cooling_device_register.part.0 (STB_LOCAL)
ffffffe0006d0366-ffffffe0006d03e2: __thermal_cooling_device_register (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Transformation ⚠️</summary>

```c
struct thermal_cooling_device *__thermal_cooling_device_register(struct device_node *np, const char *type, void *devdata, const struct thermal_cooling_device_ops *ops);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/thermal/thermal_core.c (0)
Location: drivers/thermal/thermal_core.c:949
Inline: False
Direct callers:
  - drivers/thermal/thermal_core.c:devm_thermal_of_cooling_device_register
  - drivers/thermal/thermal_core.c:thermal_of_cooling_device_register
  - drivers/thermal/thermal_core.c:thermal_cooling_device_register
```
**Symbols:**

```
ffffffff8182cad0-ffffffff8182ce51: __thermal_cooling_device_register (STB_LOCAL)
ffffffff8182e783-ffffffff8182e7a3: __thermal_cooling_device_register.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Transformation ⚠️</summary>

```c
struct thermal_cooling_device *__thermal_cooling_device_register(struct device_node *np, const char *type, void *devdata, const struct thermal_cooling_device_ops *ops);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/thermal/thermal_core.c (0)
Location: drivers/thermal/thermal_core.c:949
Inline: False
Direct callers:
  - drivers/thermal/thermal_core.c:devm_thermal_of_cooling_device_register
  - drivers/thermal/thermal_core.c:thermal_of_cooling_device_register
  - drivers/thermal/thermal_core.c:thermal_cooling_device_register
```
**Symbols:**

```
ffffffff817f4160-ffffffff817f44e1: __thermal_cooling_device_register (STB_LOCAL)
ffffffff817f5e13-ffffffff817f5e33: __thermal_cooling_device_register.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Transformation ⚠️</summary>

```c
struct thermal_cooling_device *__thermal_cooling_device_register(struct device_node *np, const char *type, void *devdata, const struct thermal_cooling_device_ops *ops);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/thermal/thermal_core.c (0)
Location: drivers/thermal/thermal_core.c:949
Inline: False
Direct callers:
  - drivers/thermal/thermal_core.c:devm_thermal_of_cooling_device_register
  - drivers/thermal/thermal_core.c:thermal_of_cooling_device_register
  - drivers/thermal/thermal_core.c:thermal_cooling_device_register
```
**Symbols:**

```
ffffffff8187c100-ffffffff8187c481: __thermal_cooling_device_register (STB_LOCAL)
ffffffff8187ddb3-ffffffff8187ddd3: __thermal_cooling_device_register.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Transformation ⚠️</summary>

```c
struct thermal_cooling_device *__thermal_cooling_device_register(struct device_node *np, const char *type, void *devdata, const struct thermal_cooling_device_ops *ops);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/thermal/thermal_core.c (0)
Location: drivers/thermal/thermal_core.c:949
Inline: False
Direct callers:
  - drivers/thermal/thermal_core.c:devm_thermal_of_cooling_device_register
  - drivers/thermal/thermal_core.c:thermal_of_cooling_device_register
  - drivers/thermal/thermal_core.c:thermal_cooling_device_register
```
**Symbols:**

```
ffffffff81897b30-ffffffff81897eb1: __thermal_cooling_device_register (STB_LOCAL)
ffffffff818997e3-ffffffff81899803: __thermal_cooling_device_register.cold (STB_LOCAL)
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
<details>
<summary>Changed between <code>5.0</code> and <code>5.3</code> ⚠️</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>char *type</code> ➡️ <code>const char *type</code>
</li>
</ul>
</details>
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
