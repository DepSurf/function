# Function: <code>plt_clk_register_parents</code>

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
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/clk/x86/clk-pmc-atom.c (ffffffff8154bad8)
Location: drivers/clk/x86/clk-pmc-atom.c:271
Inline: True
Inline callers:
  - drivers/clk/x86/clk-pmc-atom.c:plt_clk_probe
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/clk/x86/clk-pmc-atom.c (ffffffff815af068)
Location: drivers/clk/x86/clk-pmc-atom.c:271
Inline: True
Inline callers:
  - drivers/clk/x86/clk-pmc-atom.c:plt_clk_probe
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/clk/x86/clk-pmc-atom.c (ffffffff815e7274)
Location: drivers/clk/x86/clk-pmc-atom.c:271
Inline: True
Inline callers:
  - drivers/clk/x86/clk-pmc-atom.c:plt_clk_probe
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/clk/x86/clk-pmc-atom.c (ffffffff816016a4)
Location: drivers/clk/x86/clk-pmc-atom.c:265
Inline: True
Inline callers:
  - drivers/clk/x86/clk-pmc-atom.c:plt_clk_probe
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/clk/x86/clk-pmc-atom.c (ffffffff81633fe7)
Location: drivers/clk/x86/clk-pmc-atom.c:266
Inline: True
Inline callers:
  - drivers/clk/x86/clk-pmc-atom.c:plt_clk_probe
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/clk/x86/clk-pmc-atom.c (ffffffff81655d17)
Location: drivers/clk/x86/clk-pmc-atom.c:266
Inline: True
Inline callers:
  - drivers/clk/x86/clk-pmc-atom.c:plt_clk_probe
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
const char **plt_clk_register_parents(struct platform_device *pdev, struct clk_plt_data *data, const struct pmc_clk *clks);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/x86/clk-pmc-atom.c (ffffffff81705c80)
Location: drivers/clk/x86/clk-pmc-atom.c:266
Inline: False
Direct callers:
  - drivers/clk/x86/clk-pmc-atom.c:plt_clk_probe
```
**Symbols:**

```
ffffffff81705c80-ffffffff81705ef2: plt_clk_register_parents (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
const char **plt_clk_register_parents(struct platform_device *pdev, struct clk_plt_data *data, const struct pmc_clk *clks);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/x86/clk-pmc-atom.c (ffffffff81722f20)
Location: drivers/clk/x86/clk-pmc-atom.c:266
Inline: False
Direct callers:
  - drivers/clk/x86/clk-pmc-atom.c:plt_clk_probe
```
**Symbols:**

```
ffffffff81722f20-ffffffff81723192: plt_clk_register_parents (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
const char **plt_clk_register_parents(struct platform_device *pdev, struct clk_plt_data *data, const struct pmc_clk *clks);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/x86/clk-pmc-atom.c (ffffffff81704180)
Location: drivers/clk/x86/clk-pmc-atom.c:266
Inline: False
Direct callers:
  - drivers/clk/x86/clk-pmc-atom.c:plt_clk_probe
```
**Symbols:**

```
ffffffff81704180-ffffffff817043f2: plt_clk_register_parents (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
const char **plt_clk_register_parents(struct platform_device *pdev, struct clk_plt_data *data, const struct pmc_clk *clks);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/x86/clk-pmc-atom.c (ffffffff8177f780)
Location: drivers/clk/x86/clk-pmc-atom.c:266
Inline: False
Direct callers:
  - drivers/clk/x86/clk-pmc-atom.c:plt_clk_probe
```
**Symbols:**

```
ffffffff8177f780-ffffffff8177f9f2: plt_clk_register_parents (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
const char **plt_clk_register_parents(struct platform_device *pdev, struct clk_plt_data *data, const struct pmc_clk *clks);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/x86/clk-pmc-atom.c (ffffffff818b5ed0)
Location: drivers/clk/x86/clk-pmc-atom.c:266
Inline: False
Direct callers:
  - drivers/clk/x86/clk-pmc-atom.c:plt_clk_probe
```
**Symbols:**

```
ffffffff818b5ed0-ffffffff818b6131: plt_clk_register_parents (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
const char **plt_clk_register_parents(struct platform_device *pdev, struct clk_plt_data *data, const struct pmc_clk *clks);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/x86/clk-pmc-atom.c (ffffffff81a03380)
Location: drivers/clk/x86/clk-pmc-atom.c:266
Inline: False
Direct callers:
  - drivers/clk/x86/clk-pmc-atom.c:plt_clk_probe
```
**Symbols:**

```
ffffffff81a03380-ffffffff81a035e3: plt_clk_register_parents (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
const char **plt_clk_register_parents(struct platform_device *pdev, struct clk_plt_data *data, const struct pmc_clk *clks);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/x86/clk-pmc-atom.c (ffffffff81a4c1d0)
Location: drivers/clk/x86/clk-pmc-atom.c:266
Inline: False
Direct callers:
  - drivers/clk/x86/clk-pmc-atom.c:plt_clk_probe
```
**Symbols:**

```
ffffffff81a4c1d0-ffffffff81a4c438: plt_clk_register_parents (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
const char **plt_clk_register_parents(struct platform_device *pdev, struct clk_plt_data *data, const struct pmc_clk *clks);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/x86/clk-pmc-atom.c (ffffffff81a97e20)
Location: drivers/clk/x86/clk-pmc-atom.c:266
Inline: False
Direct callers:
  - drivers/clk/x86/clk-pmc-atom.c:plt_clk_probe
```
**Symbols:**

```
ffffffff81a97e20-ffffffff81a98088: plt_clk_register_parents (STB_LOCAL)
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
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/clk/x86/clk-pmc-atom.c (ffffffff8161bd77)
Location: drivers/clk/x86/clk-pmc-atom.c:266
Inline: True
Inline callers:
  - drivers/clk/x86/clk-pmc-atom.c:plt_clk_probe
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/clk/x86/clk-pmc-atom.c (ffffffff816102a7)
Location: drivers/clk/x86/clk-pmc-atom.c:266
Inline: True
Inline callers:
  - drivers/clk/x86/clk-pmc-atom.c:plt_clk_probe
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/clk/x86/clk-pmc-atom.c (ffffffff81649b57)
Location: drivers/clk/x86/clk-pmc-atom.c:266
Inline: True
Inline callers:
  - drivers/clk/x86/clk-pmc-atom.c:plt_clk_probe
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/clk/x86/clk-pmc-atom.c (ffffffff816640e7)
Location: drivers/clk/x86/clk-pmc-atom.c:266
Inline: True
Inline callers:
  - drivers/clk/x86/clk-pmc-atom.c:plt_clk_probe
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
