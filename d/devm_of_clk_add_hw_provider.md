# Function: <code>devm_of_clk_add_hw_provider</code>

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
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/clk/clk-gpio.c (0)
Location: include/linux/clk-provider.h:1346
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/clk/clk-gpio.c (0)
Location: include/linux/clk-provider.h:1384
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/clk/clk-gpio.c (0)
Location: include/linux/clk-provider.h:1416
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/clk/clk-gpio.c (0)
Location: include/linux/clk-provider.h:1428
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/clk/clk-gpio.c (0)
Location: include/linux/clk-provider.h:1454
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/clk/clk-gpio.c (0)
Location: include/linux/clk-provider.h:1550
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/clk/clk-gpio.c (0)
Location: include/linux/clk-provider.h:1575
Inline: True
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/clk/clk-gpio.c (0)
Location: include/linux/clk-provider.h:1576
Inline: True
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
int devm_of_clk_add_hw_provider(struct device *dev, struct clk_hw * (*get)(struct of_phandle_args *, void *), void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffff8000107c1c30)
Location: drivers/clk/clk.c:4391
Inline: False
Direct callers:
  - drivers/clk/actions/owl-common.c:owl_clk_probe
  - drivers/clk/hisilicon/clk-hi3660-stub.c:hi3660_stub_clk_probe
  - drivers/clk/meson/meson-aoclk.c:meson_aoclkc_probe
  - drivers/clk/meson/meson-eeclk.c:meson_eeclkc_probe
```
**Symbols:**

```
ffff8000107c1c30-ffff8000107c1ce0: devm_of_clk_add_hw_provider (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
int devm_of_clk_add_hw_provider(struct device *dev, struct clk_hw * (*get)(struct of_phandle_args *, void *), void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (c08ec7e4)
Location: drivers/clk/clk.c:4391
Inline: False
Direct callers:
  - drivers/clk/actions/owl-common.c:owl_clk_probe
  - drivers/clk/hisilicon/clk-hi3660-stub.c:hi3660_stub_clk_probe
```
**Symbols:**

```
c08ec7e4-c08ec874: devm_of_clk_add_hw_provider (STB_GLOBAL)
```
</details>
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
int devm_of_clk_add_hw_provider(struct device *dev, struct clk_hw * (*get)(struct of_phandle_args *, void *), void *data);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffe00050f8c2)
Location: drivers/clk/clk.c:4391
Inline: False
Direct callers:
  - drivers/clk/sifive/fu540-prci.c:sifive_fu540_prci_probe
```
**Symbols:**

```
ffffffe00050f8c2-ffffffe00050f94e: devm_of_clk_add_hw_provider (STB_GLOBAL)
```
</details>
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
<b>Arch</b>
<ul>
</ul>
