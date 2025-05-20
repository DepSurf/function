# Function: <code>plt_clk_is_enabled</code>

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
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int plt_clk_is_enabled(struct clk_hw *hw);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clk/x86/clk-pmc-atom.c (ffffffff8154bd2c)
Location: drivers/clk/x86/clk-pmc-atom.c:147
Inline: True
Inline callers:
  - drivers/clk/x86/clk-pmc-atom.c:plt_clk_probe
```
**Symbols:**

```
ffffffff8154b950-ffffffff8154b96d: plt_clk_is_enabled (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int plt_clk_is_enabled(struct clk_hw *hw);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clk/x86/clk-pmc-atom.c (ffffffff815af2bc)
Location: drivers/clk/x86/clk-pmc-atom.c:147
Inline: True
Inline callers:
  - drivers/clk/x86/clk-pmc-atom.c:plt_clk_probe
```
**Symbols:**

```
ffffffff815aeee0-ffffffff815aeefd: plt_clk_is_enabled (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
int plt_clk_is_enabled(struct clk_hw *hw);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clk/x86/clk-pmc-atom.c (ffffffff815e74b9)
Location: drivers/clk/x86/clk-pmc-atom.c:147
Inline: True
Inline callers:
  - drivers/clk/x86/clk-pmc-atom.c:plt_clk_probe
```
**Symbols:**

```
ffffffff815e70f0-ffffffff815e7109: plt_clk_is_enabled (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int plt_clk_is_enabled(struct clk_hw *hw);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/x86/clk-pmc-atom.c (ffffffff81601520)
Location: drivers/clk/x86/clk-pmc-atom.c:148
Inline: False
```
**Symbols:**

```
ffffffff81601520-ffffffff81601539: plt_clk_is_enabled (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
int plt_clk_is_enabled(struct clk_hw *hw);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clk/x86/clk-pmc-atom.c (ffffffff81634246)
Location: drivers/clk/x86/clk-pmc-atom.c:141
Inline: True
Inline callers:
  - drivers/clk/x86/clk-pmc-atom.c:plt_clk_probe
```
**Symbols:**

```
ffffffff81633e60-ffffffff81633e79: plt_clk_is_enabled (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int plt_clk_is_enabled(struct clk_hw *hw);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clk/x86/clk-pmc-atom.c (ffffffff81655f76)
Location: drivers/clk/x86/clk-pmc-atom.c:141
Inline: True
Inline callers:
  - drivers/clk/x86/clk-pmc-atom.c:plt_clk_probe
```
**Symbols:**

```
ffffffff81655b90-ffffffff81655ba9: plt_clk_is_enabled (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int plt_clk_is_enabled(struct clk_hw *hw);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clk/x86/clk-pmc-atom.c (ffffffff81705c24)
Location: drivers/clk/x86/clk-pmc-atom.c:141
Inline: True
Inline callers:
  - drivers/clk/x86/clk-pmc-atom.c:plt_clk_register
```
**Symbols:**

```
ffffffff81705af0-ffffffff81705b09: plt_clk_is_enabled (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int plt_clk_is_enabled(struct clk_hw *hw);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clk/x86/clk-pmc-atom.c (ffffffff81722ec4)
Location: drivers/clk/x86/clk-pmc-atom.c:141
Inline: True
Inline callers:
  - drivers/clk/x86/clk-pmc-atom.c:plt_clk_register
```
**Symbols:**

```
ffffffff81722db0-ffffffff81722dc9: plt_clk_is_enabled (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int plt_clk_is_enabled(struct clk_hw *hw);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clk/x86/clk-pmc-atom.c (ffffffff81704515)
Location: drivers/clk/x86/clk-pmc-atom.c:141
Inline: True
Inline callers:
  - drivers/clk/x86/clk-pmc-atom.c:plt_clk_probe
```
**Symbols:**

```
ffffffff81704050-ffffffff81704069: plt_clk_is_enabled (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
int plt_clk_is_enabled(struct clk_hw *hw);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clk/x86/clk-pmc-atom.c (ffffffff8177fb32)
Location: drivers/clk/x86/clk-pmc-atom.c:141
Inline: True
Inline callers:
  - drivers/clk/x86/clk-pmc-atom.c:plt_clk_probe
```
**Symbols:**

```
ffffffff8177f640-ffffffff8177f659: plt_clk_is_enabled (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
int plt_clk_is_enabled(struct clk_hw *hw);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clk/x86/clk-pmc-atom.c (ffffffff818b6295)
Location: drivers/clk/x86/clk-pmc-atom.c:141
Inline: True
Inline callers:
  - drivers/clk/x86/clk-pmc-atom.c:plt_clk_probe
```
**Symbols:**

```
ffffffff818b5d60-ffffffff818b5d7f: plt_clk_is_enabled (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
int plt_clk_is_enabled(struct clk_hw *hw);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clk/x86/clk-pmc-atom.c (ffffffff81a03755)
Location: drivers/clk/x86/clk-pmc-atom.c:141
Inline: True
Inline callers:
  - drivers/clk/x86/clk-pmc-atom.c:plt_clk_probe
```
**Symbols:**

```
ffffffff81a031d0-ffffffff81a031ef: plt_clk_is_enabled (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
int plt_clk_is_enabled(struct clk_hw *hw);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clk/x86/clk-pmc-atom.c (ffffffff81a4c5a5)
Location: drivers/clk/x86/clk-pmc-atom.c:141
Inline: True
Inline callers:
  - drivers/clk/x86/clk-pmc-atom.c:plt_clk_probe
```
**Symbols:**

```
ffffffff81a4c020-ffffffff81a4c03f: plt_clk_is_enabled (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
int plt_clk_is_enabled(struct clk_hw *hw);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clk/x86/clk-pmc-atom.c (ffffffff81a981f5)
Location: drivers/clk/x86/clk-pmc-atom.c:141
Inline: True
Inline callers:
  - drivers/clk/x86/clk-pmc-atom.c:plt_clk_probe
```
**Symbols:**

```
ffffffff81a97c70-ffffffff81a97c8f: plt_clk_is_enabled (STB_LOCAL)
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
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
int plt_clk_is_enabled(struct clk_hw *hw);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clk/x86/clk-pmc-atom.c (ffffffff8161bfd6)
Location: drivers/clk/x86/clk-pmc-atom.c:141
Inline: True
Inline callers:
  - drivers/clk/x86/clk-pmc-atom.c:plt_clk_probe
```
**Symbols:**

```
ffffffff8161bbf0-ffffffff8161bc09: plt_clk_is_enabled (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int plt_clk_is_enabled(struct clk_hw *hw);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clk/x86/clk-pmc-atom.c (ffffffff81610506)
Location: drivers/clk/x86/clk-pmc-atom.c:141
Inline: True
Inline callers:
  - drivers/clk/x86/clk-pmc-atom.c:plt_clk_probe
```
**Symbols:**

```
ffffffff81610120-ffffffff81610139: plt_clk_is_enabled (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int plt_clk_is_enabled(struct clk_hw *hw);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clk/x86/clk-pmc-atom.c (ffffffff81649db6)
Location: drivers/clk/x86/clk-pmc-atom.c:141
Inline: True
Inline callers:
  - drivers/clk/x86/clk-pmc-atom.c:plt_clk_probe
```
**Symbols:**

```
ffffffff816499d0-ffffffff816499e9: plt_clk_is_enabled (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int plt_clk_is_enabled(struct clk_hw *hw);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clk/x86/clk-pmc-atom.c (ffffffff81664346)
Location: drivers/clk/x86/clk-pmc-atom.c:141
Inline: True
Inline callers:
  - drivers/clk/x86/clk-pmc-atom.c:plt_clk_probe
```
**Symbols:**

```
ffffffff81663f60-ffffffff81663f79: plt_clk_is_enabled (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
