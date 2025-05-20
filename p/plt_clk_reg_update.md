# Function: <code>plt_clk_reg_update</code>

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
<summary>In <code>4.13</code>: ✅</summary>

```c
void plt_clk_reg_update(struct clk_plt *clk, u32 mask, u32 val);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/x86/clk-pmc-atom.c (ffffffff8154b870)
Location: drivers/clk/x86/clk-pmc-atom.c:98
Inline: False
Direct callers:
  - drivers/clk/x86/clk-pmc-atom.c:plt_clk_disable
  - drivers/clk/x86/clk-pmc-atom.c:plt_clk_enable
  - drivers/clk/x86/clk-pmc-atom.c:plt_clk_set_parent
```
**Symbols:**

```
ffffffff8154b870-ffffffff8154b8bd: plt_clk_reg_update (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void plt_clk_reg_update(struct clk_plt *clk, u32 mask, u32 val);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/x86/clk-pmc-atom.c (ffffffff815aee00)
Location: drivers/clk/x86/clk-pmc-atom.c:98
Inline: False
Direct callers:
  - drivers/clk/x86/clk-pmc-atom.c:plt_clk_disable
  - drivers/clk/x86/clk-pmc-atom.c:plt_clk_enable
  - drivers/clk/x86/clk-pmc-atom.c:plt_clk_set_parent
```
**Symbols:**

```
ffffffff815aee00-ffffffff815aee4d: plt_clk_reg_update (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void plt_clk_reg_update(struct clk_plt *clk, u32 mask, u32 val);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/x86/clk-pmc-atom.c (ffffffff815e7010)
Location: drivers/clk/x86/clk-pmc-atom.c:98
Inline: False
Direct callers:
  - drivers/clk/x86/clk-pmc-atom.c:plt_clk_disable
  - drivers/clk/x86/clk-pmc-atom.c:plt_clk_enable
  - drivers/clk/x86/clk-pmc-atom.c:plt_clk_set_parent
```
**Symbols:**

```
ffffffff815e7010-ffffffff815e705d: plt_clk_reg_update (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void plt_clk_reg_update(struct clk_plt *clk, u32 mask, u32 val);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/x86/clk-pmc-atom.c (ffffffff81601440)
Location: drivers/clk/x86/clk-pmc-atom.c:99
Inline: False
Direct callers:
  - drivers/clk/x86/clk-pmc-atom.c:plt_clk_disable
  - drivers/clk/x86/clk-pmc-atom.c:plt_clk_enable
  - drivers/clk/x86/clk-pmc-atom.c:plt_clk_set_parent
```
**Symbols:**

```
ffffffff81601440-ffffffff8160148d: plt_clk_reg_update (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void plt_clk_reg_update(struct clk_plt *clk, u32 mask, u32 val);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/x86/clk-pmc-atom.c (ffffffff81633d80)
Location: drivers/clk/x86/clk-pmc-atom.c:92
Inline: False
Direct callers:
  - drivers/clk/x86/clk-pmc-atom.c:plt_clk_disable
  - drivers/clk/x86/clk-pmc-atom.c:plt_clk_enable
  - drivers/clk/x86/clk-pmc-atom.c:plt_clk_set_parent
```
**Symbols:**

```
ffffffff81633d80-ffffffff81633dcd: plt_clk_reg_update (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void plt_clk_reg_update(struct clk_plt *clk, u32 mask, u32 val);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/x86/clk-pmc-atom.c (ffffffff81655ab0)
Location: drivers/clk/x86/clk-pmc-atom.c:92
Inline: False
Direct callers:
  - drivers/clk/x86/clk-pmc-atom.c:plt_clk_disable
  - drivers/clk/x86/clk-pmc-atom.c:plt_clk_enable
  - drivers/clk/x86/clk-pmc-atom.c:plt_clk_set_parent
```
**Symbols:**

```
ffffffff81655ab0-ffffffff81655afd: plt_clk_reg_update (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/clk/x86/clk-pmc-atom.c (ffffffff81705f45)
Location: drivers/clk/x86/clk-pmc-atom.c:92
Inline: True
Inline callers:
  - drivers/clk/x86/clk-pmc-atom.c:plt_clk_disable
  - drivers/clk/x86/clk-pmc-atom.c:plt_clk_enable
  - drivers/clk/x86/clk-pmc-atom.c:plt_clk_set_parent
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
In drivers/clk/x86/clk-pmc-atom.c (ffffffff817231f3)
Location: drivers/clk/x86/clk-pmc-atom.c:92
Inline: True
Inline callers:
  - drivers/clk/x86/clk-pmc-atom.c:plt_clk_disable
  - drivers/clk/x86/clk-pmc-atom.c:plt_clk_enable
  - drivers/clk/x86/clk-pmc-atom.c:plt_clk_set_parent
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
In drivers/clk/x86/clk-pmc-atom.c (ffffffff817040c3)
Location: drivers/clk/x86/clk-pmc-atom.c:92
Inline: True
Inline callers:
  - drivers/clk/x86/clk-pmc-atom.c:plt_clk_disable
  - drivers/clk/x86/clk-pmc-atom.c:plt_clk_enable
  - drivers/clk/x86/clk-pmc-atom.c:plt_clk_set_parent
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
In drivers/clk/x86/clk-pmc-atom.c (ffffffff8177f6b3)
Location: drivers/clk/x86/clk-pmc-atom.c:92
Inline: True
Inline callers:
  - drivers/clk/x86/clk-pmc-atom.c:plt_clk_disable
  - drivers/clk/x86/clk-pmc-atom.c:plt_clk_enable
  - drivers/clk/x86/clk-pmc-atom.c:plt_clk_set_parent
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
In drivers/clk/x86/clk-pmc-atom.c (ffffffff818b5de3)
Location: drivers/clk/x86/clk-pmc-atom.c:92
Inline: True
Inline callers:
  - drivers/clk/x86/clk-pmc-atom.c:plt_clk_disable
  - drivers/clk/x86/clk-pmc-atom.c:plt_clk_enable
  - drivers/clk/x86/clk-pmc-atom.c:plt_clk_set_parent
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
In drivers/clk/x86/clk-pmc-atom.c (ffffffff81a03273)
Location: drivers/clk/x86/clk-pmc-atom.c:92
Inline: True
Inline callers:
  - drivers/clk/x86/clk-pmc-atom.c:plt_clk_disable
  - drivers/clk/x86/clk-pmc-atom.c:plt_clk_enable
  - drivers/clk/x86/clk-pmc-atom.c:plt_clk_set_parent
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
In drivers/clk/x86/clk-pmc-atom.c (ffffffff81a4c0c3)
Location: drivers/clk/x86/clk-pmc-atom.c:92
Inline: True
Inline callers:
  - drivers/clk/x86/clk-pmc-atom.c:plt_clk_disable
  - drivers/clk/x86/clk-pmc-atom.c:plt_clk_enable
  - drivers/clk/x86/clk-pmc-atom.c:plt_clk_set_parent
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
In drivers/clk/x86/clk-pmc-atom.c (ffffffff81a97d13)
Location: drivers/clk/x86/clk-pmc-atom.c:92
Inline: True
Inline callers:
  - drivers/clk/x86/clk-pmc-atom.c:plt_clk_disable
  - drivers/clk/x86/clk-pmc-atom.c:plt_clk_enable
  - drivers/clk/x86/clk-pmc-atom.c:plt_clk_set_parent
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
<summary>In <code>aws</code>: ✅</summary>

```c
void plt_clk_reg_update(struct clk_plt *clk, u32 mask, u32 val);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/x86/clk-pmc-atom.c (ffffffff8161bb10)
Location: drivers/clk/x86/clk-pmc-atom.c:92
Inline: False
Direct callers:
  - drivers/clk/x86/clk-pmc-atom.c:plt_clk_disable
  - drivers/clk/x86/clk-pmc-atom.c:plt_clk_enable
  - drivers/clk/x86/clk-pmc-atom.c:plt_clk_set_parent
```
**Symbols:**

```
ffffffff8161bb10-ffffffff8161bb5d: plt_clk_reg_update (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void plt_clk_reg_update(struct clk_plt *clk, u32 mask, u32 val);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/x86/clk-pmc-atom.c (ffffffff81610040)
Location: drivers/clk/x86/clk-pmc-atom.c:92
Inline: False
Direct callers:
  - drivers/clk/x86/clk-pmc-atom.c:plt_clk_disable
  - drivers/clk/x86/clk-pmc-atom.c:plt_clk_enable
  - drivers/clk/x86/clk-pmc-atom.c:plt_clk_set_parent
```
**Symbols:**

```
ffffffff81610040-ffffffff8161008d: plt_clk_reg_update (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void plt_clk_reg_update(struct clk_plt *clk, u32 mask, u32 val);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/x86/clk-pmc-atom.c (ffffffff816498f0)
Location: drivers/clk/x86/clk-pmc-atom.c:92
Inline: False
Direct callers:
  - drivers/clk/x86/clk-pmc-atom.c:plt_clk_disable
  - drivers/clk/x86/clk-pmc-atom.c:plt_clk_enable
  - drivers/clk/x86/clk-pmc-atom.c:plt_clk_set_parent
```
**Symbols:**

```
ffffffff816498f0-ffffffff8164993d: plt_clk_reg_update (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void plt_clk_reg_update(struct clk_plt *clk, u32 mask, u32 val);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/x86/clk-pmc-atom.c (ffffffff81663e80)
Location: drivers/clk/x86/clk-pmc-atom.c:92
Inline: False
Direct callers:
  - drivers/clk/x86/clk-pmc-atom.c:plt_clk_disable
  - drivers/clk/x86/clk-pmc-atom.c:plt_clk_enable
  - drivers/clk/x86/clk-pmc-atom.c:plt_clk_set_parent
```
**Symbols:**

```
ffffffff81663e80-ffffffff81663ecd: plt_clk_reg_update (STB_LOCAL)
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
