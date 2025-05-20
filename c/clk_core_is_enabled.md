# Function: <code>clk_core_is_enabled</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffff816e42dd)
Location: drivers/clk/clk.c:163
Inline: True
Inline callers:
  - drivers/clk/clk.c:__clk_is_enabled
  - drivers/clk/clk.c:clk_disable_unused_subtree
  - drivers/clk/clk.c:clk_hw_is_enabled
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffff8174b14b)
Location: drivers/clk/clk.c:163
Inline: True
Inline callers:
  - drivers/clk/clk.c:clk_disable_unused_subtree
  - drivers/clk/clk.c:__clk_is_enabled
  - drivers/clk/clk.c:clk_hw_is_enabled
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffff815339cb)
Location: drivers/clk/clk.c:163
Inline: True
Inline callers:
  - drivers/clk/clk.c:clk_disable_unused_subtree
  - drivers/clk/clk.c:__clk_is_enabled
  - drivers/clk/clk.c:clk_hw_is_enabled
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffff815466ff)
Location: drivers/clk/clk.c:163
Inline: True
Inline callers:
  - drivers/clk/clk.c:clk_disable_unused_subtree
  - drivers/clk/clk.c:__clk_is_enabled
  - drivers/clk/clk.c:clk_hw_is_enabled
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
bool clk_core_is_enabled(struct clk_core *core);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffff815a7aa0)
Location: drivers/clk/clk.c:192
Inline: False
Direct callers:
  - drivers/clk/clk.c:clk_disable_unused_subtree
  - drivers/clk/clk.c:clk_hw_is_enabled
```
**Symbols:**

```
ffffffff815a7aa0-ffffffff815a7b2d: clk_core_is_enabled (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
bool clk_core_is_enabled(struct clk_core *core);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffff815df720)
Location: drivers/clk/clk.c:207
Inline: False
Direct callers:
  - drivers/clk/clk.c:clk_disable_unused_subtree
  - drivers/clk/clk.c:clk_hw_is_enabled
```
**Symbols:**

```
ffffffff815df720-ffffffff815df7b3: clk_core_is_enabled (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
bool clk_core_is_enabled(struct clk_core *core);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffff815f9440)
Location: drivers/clk/clk.c:205
Inline: False
Direct callers:
  - drivers/clk/clk.c:clk_disable_unused_subtree
  - drivers/clk/clk.c:clk_hw_is_enabled
```
**Symbols:**

```
ffffffff815f9440-ffffffff815f94d3: clk_core_is_enabled (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
bool clk_core_is_enabled(struct clk_core *core);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffff8162b730)
Location: drivers/clk/clk.c:215
Inline: False
Direct callers:
  - drivers/clk/clk.c:clk_disable_unused_subtree
  - drivers/clk/clk.c:clk_hw_is_enabled
```
**Symbols:**

```
ffffffff8162b730-ffffffff8162b7c5: clk_core_is_enabled (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
bool clk_core_is_enabled(struct clk_core *core);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffff8164d2a0)
Location: drivers/clk/clk.c:221
Inline: False
Direct callers:
  - drivers/clk/clk.c:clk_disable_unused_subtree
  - drivers/clk/clk.c:clk_hw_is_enabled
```
**Symbols:**

```
ffffffff8164d2a0-ffffffff8164d335: clk_core_is_enabled (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
bool clk_core_is_enabled(struct clk_core *core);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffff816fc0b0)
Location: drivers/clk/clk.c:225
Inline: False
Direct callers:
  - drivers/clk/clk.c:clk_disable_unused_subtree
  - drivers/clk/clk.c:clk_hw_is_enabled
```
**Symbols:**

```
ffffffff816fc0b0-ffffffff816fc145: clk_core_is_enabled (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
bool clk_core_is_enabled(struct clk_core *core);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffff81718fb0)
Location: drivers/clk/clk.c:225
Inline: False
Direct callers:
  - drivers/clk/clk.c:clk_summary_show_one
  - drivers/clk/clk.c:clk_disable_unused_subtree
  - drivers/clk/clk.c:clk_hw_is_enabled
```
**Symbols:**

```
ffffffff81718fb0-ffffffff81719045: clk_core_is_enabled (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
bool clk_core_is_enabled(struct clk_core *core);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffff816fa2b0)
Location: drivers/clk/clk.c:225
Inline: False
Direct callers:
  - drivers/clk/clk.c:clk_summary_show_subtree
  - drivers/clk/clk.c:clk_disable_unused_subtree
  - drivers/clk/clk.c:clk_hw_is_enabled
```
**Symbols:**

```
ffffffff816fa2b0-ffffffff816fa345: clk_core_is_enabled (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
bool clk_core_is_enabled(struct clk_core *core);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/clk/clk.c (0)
Location: drivers/clk/clk.c:225
Inline: False
Direct callers:
  - drivers/clk/clk.c:clk_summary_show_subtree
  - drivers/clk/clk.c:clk_disable_unused_subtree
  - drivers/clk/clk.c:clk_hw_is_enabled
```
**Symbols:**

```
ffffffff81774fa0-ffffffff8177505d: clk_core_is_enabled (STB_LOCAL)
ffffffff81cf2fe6-ffffffff81cf3010: clk_core_is_enabled.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
bool clk_core_is_enabled(struct clk_core *core);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/clk/clk.c (0)
Location: drivers/clk/clk.c:218
Inline: False
Direct callers:
  - drivers/clk/clk.c:clk_summary_show_subtree
  - drivers/clk/clk.c:clk_disable_unused_subtree
  - drivers/clk/clk.c:clk_hw_is_enabled
```
**Symbols:**

```
ffffffff818aaca0-ffffffff818aad81: clk_core_is_enabled (STB_LOCAL)
ffffffff81ebb18a-ffffffff81ebb1b4: clk_core_is_enabled.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
bool clk_core_is_enabled(struct clk_core *core);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/clk/clk.c (0)
Location: drivers/clk/clk.c:218
Inline: False
Direct callers:
  - drivers/clk/clk.c:clk_summary_show_subtree
  - drivers/clk/clk.c:clk_disable_unused_subtree
  - drivers/clk/clk.c:clk_hw_is_enabled
```
**Symbols:**

```
ffffffff819f6290-ffffffff819f6371: clk_core_is_enabled (STB_LOCAL)
ffffffff82092d32-ffffffff82092d5c: clk_core_is_enabled.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
bool clk_core_is_enabled(struct clk_core *core);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/clk/clk.c (0)
Location: drivers/clk/clk.c:218
Inline: False
Direct callers:
  - drivers/clk/clk.c:clk_summary_show_subtree
  - drivers/clk/clk.c:clk_disable_unused_subtree
  - drivers/clk/clk.c:clk_hw_is_enabled
  - drivers/clk/clk.c:clk_core_is_enabled
```
**Symbols:**

```
ffffffff81a3ea10-ffffffff81a3eb09: clk_core_is_enabled (STB_LOCAL)
ffffffff82113a86-ffffffff82113ab0: clk_core_is_enabled.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
bool clk_core_is_enabled(struct clk_core *core);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/clk/clk.c (0)
Location: drivers/clk/clk.c:218
Inline: False
Direct callers:
  - drivers/clk/clk.c:clk_summary_show_one
  - drivers/clk/clk.c:clk_disable_unused_subtree
  - drivers/clk/clk.c:clk_hw_is_enabled
  - drivers/clk/clk.c:clk_core_is_enabled
```
**Symbols:**

```
ffffffff81a8a340-ffffffff81a8a439: clk_core_is_enabled (STB_LOCAL)
ffffffff821f13f9-ffffffff821f1423: clk_core_is_enabled.cold (STB_LOCAL)
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
bool clk_core_is_enabled(struct clk_core *core);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffff8000107bf768)
Location: drivers/clk/clk.c:221
Inline: False
Direct callers:
  - drivers/clk/clk.c:clk_disable_unused_subtree
  - drivers/clk/clk.c:clk_hw_is_enabled
```
**Symbols:**

```
ffff8000107bf768-ffff8000107bf840: clk_core_is_enabled (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
bool clk_core_is_enabled(struct clk_core *core);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (c08e8128)
Location: drivers/clk/clk.c:221
Inline: False
Direct callers:
  - drivers/clk/clk.c:clk_disable_unused_subtree
  - drivers/clk/clk.c:clk_hw_is_enabled
```
**Symbols:**

```
c08e8128-c08e81f0: clk_core_is_enabled (STB_LOCAL)
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
bool clk_core_is_enabled(struct clk_core *core);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffe00050b0ae)
Location: drivers/clk/clk.c:221
Inline: False
Direct callers:
  - drivers/clk/clk.c:clk_disable_unused_subtree
  - drivers/clk/clk.c:clk_hw_is_enabled
```
**Symbols:**

```
ffffffe00050b0ae-ffffffe00050b142: clk_core_is_enabled (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
bool clk_core_is_enabled(struct clk_core *core);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffff81613300)
Location: drivers/clk/clk.c:221
Inline: False
Direct callers:
  - drivers/clk/clk.c:clk_disable_unused_subtree
  - drivers/clk/clk.c:clk_hw_is_enabled
```
**Symbols:**

```
ffffffff81613300-ffffffff81613395: clk_core_is_enabled (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
bool clk_core_is_enabled(struct clk_core *core);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffff81607830)
Location: drivers/clk/clk.c:221
Inline: False
Direct callers:
  - drivers/clk/clk.c:clk_disable_unused_subtree
  - drivers/clk/clk.c:clk_hw_is_enabled
```
**Symbols:**

```
ffffffff81607830-ffffffff816078c5: clk_core_is_enabled (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
bool clk_core_is_enabled(struct clk_core *core);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffff816410e0)
Location: drivers/clk/clk.c:221
Inline: False
Direct callers:
  - drivers/clk/clk.c:clk_disable_unused_subtree
  - drivers/clk/clk.c:clk_hw_is_enabled
```
**Symbols:**

```
ffffffff816410e0-ffffffff81641175: clk_core_is_enabled (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
bool clk_core_is_enabled(struct clk_core *core);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffff8165b460)
Location: drivers/clk/clk.c:221
Inline: False
Direct callers:
  - drivers/clk/clk.c:clk_disable_unused_subtree
  - drivers/clk/clk.c:clk_hw_is_enabled
```
**Symbols:**

```
ffffffff8165b460-ffffffff8165b4f5: clk_core_is_enabled (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
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
