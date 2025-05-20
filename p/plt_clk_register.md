# Function: <code>plt_clk_register</code>

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
In drivers/clk/x86/clk-pmc-atom.c (ffffffff8154bcac)
Location: drivers/clk/x86/clk-pmc-atom.c:166
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
In drivers/clk/x86/clk-pmc-atom.c (ffffffff815af23c)
Location: drivers/clk/x86/clk-pmc-atom.c:166
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
In drivers/clk/x86/clk-pmc-atom.c (ffffffff815e7455)
Location: drivers/clk/x86/clk-pmc-atom.c:166
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
In drivers/clk/x86/clk-pmc-atom.c (ffffffff81601885)
Location: drivers/clk/x86/clk-pmc-atom.c:167
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
In drivers/clk/x86/clk-pmc-atom.c (ffffffff816341cb)
Location: drivers/clk/x86/clk-pmc-atom.c:160
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
In drivers/clk/x86/clk-pmc-atom.c (ffffffff81655efb)
Location: drivers/clk/x86/clk-pmc-atom.c:160
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
struct clk_plt *plt_clk_register(struct platform_device *pdev, int id, const struct pmc_clk_data *pmc_data, const char **parent_names, int num_parents);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/x86/clk-pmc-atom.c (ffffffff81705b30)
Location: drivers/clk/x86/clk-pmc-atom.c:160
Inline: False
Direct callers:
  - drivers/clk/x86/clk-pmc-atom.c:plt_clk_probe
```
**Symbols:**

```
ffffffff81705b30-ffffffff81705c72: plt_clk_register (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct clk_plt *plt_clk_register(struct platform_device *pdev, int id, const struct pmc_clk_data *pmc_data, const char **parent_names, int num_parents);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/x86/clk-pmc-atom.c (ffffffff81722dd0)
Location: drivers/clk/x86/clk-pmc-atom.c:160
Inline: False
Direct callers:
  - drivers/clk/x86/clk-pmc-atom.c:plt_clk_probe
```
**Symbols:**

```
ffffffff81722dd0-ffffffff81722f12: plt_clk_register (STB_LOCAL)
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
In drivers/clk/x86/clk-pmc-atom.c (ffffffff8170448b)
Location: drivers/clk/x86/clk-pmc-atom.c:160
Inline: True
Inline callers:
  - drivers/clk/x86/clk-pmc-atom.c:plt_clk_probe
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
In drivers/clk/x86/clk-pmc-atom.c (ffffffff8177fab6)
Location: drivers/clk/x86/clk-pmc-atom.c:160
Inline: True
Inline callers:
  - drivers/clk/x86/clk-pmc-atom.c:plt_clk_probe
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
In drivers/clk/x86/clk-pmc-atom.c (ffffffff818b61f8)
Location: drivers/clk/x86/clk-pmc-atom.c:160
Inline: True
Inline callers:
  - drivers/clk/x86/clk-pmc-atom.c:plt_clk_probe
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
In drivers/clk/x86/clk-pmc-atom.c (ffffffff81a036b8)
Location: drivers/clk/x86/clk-pmc-atom.c:160
Inline: True
Inline callers:
  - drivers/clk/x86/clk-pmc-atom.c:plt_clk_probe
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
In drivers/clk/x86/clk-pmc-atom.c (ffffffff81a4c508)
Location: drivers/clk/x86/clk-pmc-atom.c:160
Inline: True
Inline callers:
  - drivers/clk/x86/clk-pmc-atom.c:plt_clk_probe
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
In drivers/clk/x86/clk-pmc-atom.c (ffffffff81a98158)
Location: drivers/clk/x86/clk-pmc-atom.c:160
Inline: True
Inline callers:
  - drivers/clk/x86/clk-pmc-atom.c:plt_clk_probe
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
In drivers/clk/x86/clk-pmc-atom.c (ffffffff8161bf5b)
Location: drivers/clk/x86/clk-pmc-atom.c:160
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
In drivers/clk/x86/clk-pmc-atom.c (ffffffff8161048b)
Location: drivers/clk/x86/clk-pmc-atom.c:160
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
In drivers/clk/x86/clk-pmc-atom.c (ffffffff81649d3b)
Location: drivers/clk/x86/clk-pmc-atom.c:160
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
In drivers/clk/x86/clk-pmc-atom.c (ffffffff816642cb)
Location: drivers/clk/x86/clk-pmc-atom.c:160
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
</ul>
