# Function: <code>__devm_clk_get</code>

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
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
struct clk *__devm_clk_get(struct device *dev, const char *id, struct clk * (*get)(struct device *, const char *), int (*init)(struct clk *), void (*exit)(struct clk *));
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clk/clk-devres.c (ffffffff819f313e)
Location: drivers/clk/clk-devres.c:22
Inline: True
Inline callers:
  - drivers/clk/clk-devres.c:devm_clk_get_optional_enabled
  - drivers/clk/clk-devres.c:devm_clk_get_optional_prepared
  - drivers/clk/clk-devres.c:devm_clk_get_optional
  - drivers/clk/clk-devres.c:devm_clk_get_enabled
Direct callers:
  - drivers/clk/clk-devres.c:devm_clk_get_prepared
  - drivers/clk/clk-devres.c:devm_clk_get
```
**Symbols:**

```
ffffffff819f2930-ffffffff819f2a02: __devm_clk_get (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
struct clk *__devm_clk_get(struct device *dev, const char *id, struct clk * (*get)(struct device *, const char *), int (*init)(struct clk *), void (*exit)(struct clk *));
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clk/clk-devres.c (ffffffff81a3b7ce)
Location: drivers/clk/clk-devres.c:22
Inline: True
Inline callers:
  - drivers/clk/clk-devres.c:devm_clk_get_optional_enabled
  - drivers/clk/clk-devres.c:devm_clk_get_optional_prepared
  - drivers/clk/clk-devres.c:devm_clk_get_optional
  - drivers/clk/clk-devres.c:devm_clk_get_enabled
Direct callers:
  - drivers/clk/clk-devres.c:devm_clk_get_prepared
  - drivers/clk/clk-devres.c:devm_clk_get
```
**Symbols:**

```
ffffffff81a3afc0-ffffffff81a3b092: __devm_clk_get (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
struct clk *__devm_clk_get(struct device *dev, const char *id, struct clk * (*get)(struct device *, const char *), int (*init)(struct clk *), void (*exit)(struct clk *));
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clk/clk-devres.c (ffffffff81a8708e)
Location: drivers/clk/clk-devres.c:22
Inline: True
Inline callers:
  - drivers/clk/clk-devres.c:devm_clk_get_optional_enabled
  - drivers/clk/clk-devres.c:devm_clk_get_optional_prepared
  - drivers/clk/clk-devres.c:devm_clk_get_optional
  - drivers/clk/clk-devres.c:devm_clk_get_enabled
Direct callers:
  - drivers/clk/clk-devres.c:devm_clk_get_prepared
  - drivers/clk/clk-devres.c:devm_clk_get
```
**Symbols:**

```
ffffffff81a86880-ffffffff81a86952: __devm_clk_get (STB_LOCAL)
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
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
