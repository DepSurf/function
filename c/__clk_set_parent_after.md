# Function: <code>__clk_set_parent_after</code>

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
In drivers/clk/clk.c (ffffffff816e6ca0)
Location: drivers/clk/clk.c:1176
Inline: True
Inline callers:
  - drivers/clk/clk.c:clk_core_set_parent
  - drivers/clk/clk.c:clk_core_set_parent
  - drivers/clk/clk.c:clk_change_rate
Direct callers:
  - drivers/clk/clk.c:clk_core_set_parent
  - drivers/clk/clk.c:clk_core_set_parent
  - drivers/clk/clk.c:clk_change_rate
```
**Symbols:**

```
ffffffff816e6ca0-ffffffff816e6ce3: __clk_set_parent_after.isra.19.part.20 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
void __clk_set_parent_after(struct clk_core *core, struct clk_core *parent, struct clk_core *old_parent);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffff8174ae60)
Location: drivers/clk/clk.c:1214
Inline: False
Direct callers:
  - drivers/clk/clk.c:clk_core_set_parent
  - drivers/clk/clk.c:clk_core_set_parent
  - drivers/clk/clk.c:clk_change_rate
```
**Symbols:**

```
ffffffff8174ae60-ffffffff8174aeb3: __clk_set_parent_after (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void __clk_set_parent_after(struct clk_core *core, struct clk_core *parent, struct clk_core *old_parent);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffff815336e0)
Location: drivers/clk/clk.c:1214
Inline: False
Direct callers:
  - drivers/clk/clk.c:clk_register
  - drivers/clk/clk.c:clk_core_set_parent
  - drivers/clk/clk.c:clk_core_set_parent
  - drivers/clk/clk.c:clk_change_rate
```
**Symbols:**

```
ffffffff815336e0-ffffffff81533733: __clk_set_parent_after (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void __clk_set_parent_after(struct clk_core *core, struct clk_core *parent, struct clk_core *old_parent);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffff81545f30)
Location: drivers/clk/clk.c:1216
Inline: False
Direct callers:
  - drivers/clk/clk.c:clk_register
  - drivers/clk/clk.c:clk_change_rate
```
**Symbols:**

```
ffffffff81545f30-ffffffff81545f83: __clk_set_parent_after (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void __clk_set_parent_after(struct clk_core *core, struct clk_core *parent, struct clk_core *old_parent);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffff815a8a90)
Location: drivers/clk/clk.c:1293
Inline: False
Direct callers:
  - drivers/clk/clk.c:clk_register
  - drivers/clk/clk.c:clk_change_rate
```
**Symbols:**

```
ffffffff815a8a90-ffffffff815a8ae6: __clk_set_parent_after (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void __clk_set_parent_after(struct clk_core *core, struct clk_core *parent, struct clk_core *old_parent);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffff815e1ed0)
Location: drivers/clk/clk.c:1502
Inline: False
Direct callers:
  - drivers/clk/clk.c:clk_register
  - drivers/clk/clk.c:clk_change_rate
```
**Symbols:**

```
ffffffff815e1ed0-ffffffff815e1f28: __clk_set_parent_after (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void __clk_set_parent_after(struct clk_core *core, struct clk_core *parent, struct clk_core *old_parent);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffff815fc080)
Location: drivers/clk/clk.c:1618
Inline: False
Direct callers:
  - drivers/clk/clk.c:clk_register
  - drivers/clk/clk.c:clk_change_rate
```
**Symbols:**

```
ffffffff815fc080-ffffffff815fc0d8: __clk_set_parent_after (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void __clk_set_parent_after(struct clk_core *core, struct clk_core *parent, struct clk_core *old_parent);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffff8162ece0)
Location: drivers/clk/clk.c:1754
Inline: False
Direct callers:
  - drivers/clk/clk.c:__clk_core_init
  - drivers/clk/clk.c:clk_change_rate
```
**Symbols:**

```
ffffffff8162ece0-ffffffff8162ed38: __clk_set_parent_after (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void __clk_set_parent_after(struct clk_core *core, struct clk_core *parent, struct clk_core *old_parent);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffff81650810)
Location: drivers/clk/clk.c:1762
Inline: False
Direct callers:
  - drivers/clk/clk.c:__clk_core_init
  - drivers/clk/clk.c:clk_change_rate
```
**Symbols:**

```
ffffffff81650810-ffffffff81650868: __clk_set_parent_after (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void __clk_set_parent_after(struct clk_core *core, struct clk_core *parent, struct clk_core *old_parent);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffff816ffc20)
Location: drivers/clk/clk.c:1783
Inline: True
Direct callers:
  - drivers/clk/clk.c:clk_core_reparent_orphans_nolock
  - drivers/clk/clk.c:clk_change_rate
```
**Symbols:**

```
ffffffff816ffc20-ffffffff816ffcf7: __clk_set_parent_after (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void __clk_set_parent_after(struct clk_core *core, struct clk_core *parent, struct clk_core *old_parent);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffff8171cf70)
Location: drivers/clk/clk.c:1792
Inline: True
Direct callers:
  - drivers/clk/clk.c:clk_core_reparent_orphans_nolock
  - drivers/clk/clk.c:clk_change_rate
```
**Symbols:**

```
ffffffff8171cf70-ffffffff8171d047: __clk_set_parent_after (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void __clk_set_parent_after(struct clk_core *core, struct clk_core *parent, struct clk_core *old_parent);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffff816fd5c0)
Location: drivers/clk/clk.c:1813
Inline: True
Direct callers:
  - drivers/clk/clk.c:__clk_core_init
  - drivers/clk/clk.c:clk_change_rate
```
**Symbols:**

```
ffffffff816fd5c0-ffffffff816fd697: __clk_set_parent_after (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void __clk_set_parent_after(struct clk_core *core, struct clk_core *parent, struct clk_core *old_parent);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffff81778a50)
Location: drivers/clk/clk.c:1813
Inline: True
Direct callers:
  - drivers/clk/clk.c:__clk_core_init
  - drivers/clk/clk.c:clk_change_rate
```
**Symbols:**

```
ffffffff81778a50-ffffffff81778b27: __clk_set_parent_after (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void __clk_set_parent_after(struct clk_core *core, struct clk_core *parent, struct clk_core *old_parent);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffff818aef30)
Location: drivers/clk/clk.c:1827
Inline: True
Direct callers:
  - drivers/clk/clk.c:__clk_core_init
  - drivers/clk/clk.c:clk_change_rate
```
**Symbols:**

```
ffffffff818aef30-ffffffff818af01f: __clk_set_parent_after (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void __clk_set_parent_after(struct clk_core *core, struct clk_core *parent, struct clk_core *old_parent);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffff819faa50)
Location: drivers/clk/clk.c:2007
Inline: True
Direct callers:
  - drivers/clk/clk.c:__clk_core_init
  - drivers/clk/clk.c:clk_change_rate
```
**Symbols:**

```
ffffffff819faa50-ffffffff819fab3f: __clk_set_parent_after (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void __clk_set_parent_after(struct clk_core *core, struct clk_core *parent, struct clk_core *old_parent);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffff81a43980)
Location: drivers/clk/clk.c:2052
Inline: True
Direct callers:
  - drivers/clk/clk.c:__clk_core_init
  - drivers/clk/clk.c:clk_change_rate
```
**Symbols:**

```
ffffffff81a43980-ffffffff81a43a6f: __clk_set_parent_after (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void __clk_set_parent_after(struct clk_core *core, struct clk_core *parent, struct clk_core *old_parent);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffff81a8f490)
Location: drivers/clk/clk.c:2052
Inline: True
Direct callers:
  - drivers/clk/clk.c:__clk_core_init
  - drivers/clk/clk.c:clk_change_rate
```
**Symbols:**

```
ffffffff81a8f490-ffffffff81a8f57f: __clk_set_parent_after (STB_LOCAL)
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
void __clk_set_parent_after(struct clk_core *core, struct clk_core *parent, struct clk_core *old_parent);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffff8000107c0b10)
Location: drivers/clk/clk.c:1762
Inline: False
Direct callers:
  - drivers/clk/clk.c:clk_core_reparent_orphans_nolock
  - drivers/clk/clk.c:clk_change_rate
```
**Symbols:**

```
ffff8000107c0b10-ffff8000107c0b8c: __clk_set_parent_after (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void __clk_set_parent_after(struct clk_core *core, struct clk_core *parent, struct clk_core *old_parent);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (c08ec104)
Location: drivers/clk/clk.c:1762
Inline: False
Direct callers:
  - drivers/clk/clk.c:clk_core_reparent_orphans_nolock
  - drivers/clk/clk.c:clk_change_rate
```
**Symbols:**

```
c08ec104-c08ec160: __clk_set_parent_after (STB_LOCAL)
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
void __clk_set_parent_after(struct clk_core *core, struct clk_core *parent, struct clk_core *old_parent);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffe00050ec64)
Location: drivers/clk/clk.c:1762
Inline: False
Direct callers:
  - drivers/clk/clk.c:clk_core_reparent_orphans_nolock
  - drivers/clk/clk.c:clk_change_rate
```
**Symbols:**

```
ffffffe00050ec64-ffffffe00050ece0: __clk_set_parent_after (STB_LOCAL)
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
void __clk_set_parent_after(struct clk_core *core, struct clk_core *parent, struct clk_core *old_parent);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffff81616870)
Location: drivers/clk/clk.c:1762
Inline: False
Direct callers:
  - drivers/clk/clk.c:__clk_core_init
  - drivers/clk/clk.c:clk_change_rate
```
**Symbols:**

```
ffffffff81616870-ffffffff816168c8: __clk_set_parent_after (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void __clk_set_parent_after(struct clk_core *core, struct clk_core *parent, struct clk_core *old_parent);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffff8160ada0)
Location: drivers/clk/clk.c:1762
Inline: False
Direct callers:
  - drivers/clk/clk.c:__clk_core_init
  - drivers/clk/clk.c:clk_change_rate
```
**Symbols:**

```
ffffffff8160ada0-ffffffff8160adf8: __clk_set_parent_after (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void __clk_set_parent_after(struct clk_core *core, struct clk_core *parent, struct clk_core *old_parent);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffff81644650)
Location: drivers/clk/clk.c:1762
Inline: False
Direct callers:
  - drivers/clk/clk.c:__clk_core_init
  - drivers/clk/clk.c:clk_change_rate
```
**Symbols:**

```
ffffffff81644650-ffffffff816446a8: __clk_set_parent_after (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void __clk_set_parent_after(struct clk_core *core, struct clk_core *parent, struct clk_core *old_parent);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffff8165eb00)
Location: drivers/clk/clk.c:1762
Inline: False
Direct callers:
  - drivers/clk/clk.c:__clk_core_init
  - drivers/clk/clk.c:clk_change_rate
```
**Symbols:**

```
ffffffff8165eb00-ffffffff8165eb58: __clk_set_parent_after (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
