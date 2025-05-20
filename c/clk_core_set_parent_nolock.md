# Function: <code>clk_core_set_parent_nolock</code>

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
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
int clk_core_set_parent_nolock(struct clk_core *core, struct clk_core *parent);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffff815e2b20)
Location: drivers/clk/clk.c:2195
Inline: True
Direct callers:
  - drivers/clk/clk.c:clk_unregister
```
**Symbols:**

```
ffffffff815e2b20-ffffffff815e2dab: clk_core_set_parent_nolock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
int clk_core_set_parent_nolock(struct clk_core *core, struct clk_core *parent);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffff815fc4c0)
Location: drivers/clk/clk.c:2308
Inline: True
Direct callers:
  - drivers/clk/clk.c:clk_unregister
```
**Symbols:**

```
ffffffff815fc4c0-ffffffff815fc72d: clk_core_set_parent_nolock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
int clk_core_set_parent_nolock(struct clk_core *core, struct clk_core *parent);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffff8162f110)
Location: drivers/clk/clk.c:2448
Inline: True
Direct callers:
  - drivers/clk/clk.c:clk_unregister
```
**Symbols:**

```
ffffffff8162f110-ffffffff8162f381: clk_core_set_parent_nolock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
int clk_core_set_parent_nolock(struct clk_core *core, struct clk_core *parent);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffff81650c40)
Location: drivers/clk/clk.c:2456
Inline: True
Direct callers:
  - drivers/clk/clk.c:clk_unregister
  - drivers/clk/clk.c:clk_hw_set_parent
```
**Symbols:**

```
ffffffff81650c40-ffffffff81650eb1: clk_core_set_parent_nolock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
int clk_core_set_parent_nolock(struct clk_core *core, struct clk_core *parent);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffff817004a0)
Location: drivers/clk/clk.c:2477
Inline: True
Direct callers:
  - drivers/clk/clk.c:clk_unregister
  - drivers/clk/clk.c:clk_hw_set_parent
```
**Symbols:**

```
ffffffff817004a0-ffffffff81700710: clk_core_set_parent_nolock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
int clk_core_set_parent_nolock(struct clk_core *core, struct clk_core *parent);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffff8171d9e0)
Location: drivers/clk/clk.c:2492
Inline: True
Direct callers:
  - drivers/clk/clk.c:clk_unregister
  - drivers/clk/clk.c:clk_hw_set_parent
```
**Symbols:**

```
ffffffff8171d9e0-ffffffff8171dc2f: clk_core_set_parent_nolock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
int clk_core_set_parent_nolock(struct clk_core *core, struct clk_core *parent);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffff816fea70)
Location: drivers/clk/clk.c:2505
Inline: True
Direct callers:
  - drivers/clk/clk.c:clk_unregister
  - drivers/clk/clk.c:clk_hw_set_parent
```
**Symbols:**

```
ffffffff816fea70-ffffffff816fecbf: clk_core_set_parent_nolock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
int clk_core_set_parent_nolock(struct clk_core *core, struct clk_core *parent);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/clk/clk.c (ffffffff817792a6)
Location: drivers/clk/clk.c:2505
Inline: True
Direct callers:
  - drivers/clk/clk.c:clk_unregister
  - drivers/clk/clk.c:clk_hw_set_parent
```
**Symbols:**

```
ffffffff81779260-ffffffff817794c0: clk_core_set_parent_nolock (STB_LOCAL)
ffffffff81cf31e5-ffffffff81cf31fa: clk_core_set_parent_nolock.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

```c
int clk_core_set_parent_nolock(struct clk_core *core, struct clk_core *parent);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/clk/clk.c (ffffffff818af5ba)
Location: drivers/clk/clk.c:2522
Inline: True
Direct callers:
  - drivers/clk/clk.c:clk_unregister
  - drivers/clk/clk.c:clk_hw_set_parent
```
**Symbols:**

```
ffffffff818af570-ffffffff818af837: clk_core_set_parent_nolock (STB_LOCAL)
ffffffff81ebb34a-ffffffff81ebb35f: clk_core_set_parent_nolock.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

```c
int clk_core_set_parent_nolock(struct clk_core *core, struct clk_core *parent);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/clk/clk.c (ffffffff819fb7ba)
Location: drivers/clk/clk.c:2712
Inline: True
Direct callers:
  - drivers/clk/clk.c:clk_unregister
  - drivers/clk/clk.c:clk_hw_set_parent
```
**Symbols:**

```
ffffffff819fb770-ffffffff819fba41: clk_core_set_parent_nolock (STB_LOCAL)
ffffffff82092e1f-ffffffff82092e34: clk_core_set_parent_nolock.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

```c
int clk_core_set_parent_nolock(struct clk_core *core, struct clk_core *parent);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/clk/clk.c (ffffffff81a4426a)
Location: drivers/clk/clk.c:2757
Inline: True
Direct callers:
  - drivers/clk/clk.c:clk_unregister
  - drivers/clk/clk.c:clk_hw_set_parent
```
**Symbols:**

```
ffffffff81a44220-ffffffff81a444f1: clk_core_set_parent_nolock (STB_LOCAL)
ffffffff82113b73-ffffffff82113b88: clk_core_set_parent_nolock.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

```c
int clk_core_set_parent_nolock(struct clk_core *core, struct clk_core *parent);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/clk/clk.c (ffffffff81a8fd7a)
Location: drivers/clk/clk.c:2757
Inline: True
Direct callers:
  - drivers/clk/clk.c:clk_unregister
  - drivers/clk/clk.c:clk_hw_set_parent
```
**Symbols:**

```
ffffffff81a8fd30-ffffffff81a90001: clk_core_set_parent_nolock (STB_LOCAL)
ffffffff821f14fb-ffffffff821f1510: clk_core_set_parent_nolock.cold (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
int clk_core_set_parent_nolock(struct clk_core *core, struct clk_core *parent);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffff8000107c1308)
Location: drivers/clk/clk.c:2456
Inline: True
Direct callers:
  - drivers/clk/clk.c:clk_unregister
  - drivers/clk/clk.c:clk_hw_set_parent
```
**Symbols:**

```
ffff8000107c1308-ffff8000107c15e8: clk_core_set_parent_nolock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int clk_core_set_parent_nolock(struct clk_core *core, struct clk_core *parent);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (c08edbcc)
Location: drivers/clk/clk.c:2456
Inline: True
Direct callers:
  - drivers/clk/clk.c:clk_unregister
  - drivers/clk/clk.c:clk_hw_set_parent
```
**Symbols:**

```
c08edbcc-c08edeb8: clk_core_set_parent_nolock (STB_LOCAL)
```
</details>
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
int clk_core_set_parent_nolock(struct clk_core *core, struct clk_core *parent);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffe00050f0ae)
Location: drivers/clk/clk.c:2456
Inline: True
Direct callers:
  - drivers/clk/clk.c:clk_unregister
  - drivers/clk/clk.c:clk_hw_set_parent
```
**Symbols:**

```
ffffffe00050f0ae-ffffffe00050f2f2: clk_core_set_parent_nolock (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
int clk_core_set_parent_nolock(struct clk_core *core, struct clk_core *parent);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffff81616ca0)
Location: drivers/clk/clk.c:2456
Inline: True
Direct callers:
  - drivers/clk/clk.c:clk_unregister
  - drivers/clk/clk.c:clk_hw_set_parent
```
**Symbols:**

```
ffffffff81616ca0-ffffffff81616f11: clk_core_set_parent_nolock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
int clk_core_set_parent_nolock(struct clk_core *core, struct clk_core *parent);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffff8160b1d0)
Location: drivers/clk/clk.c:2456
Inline: True
Direct callers:
  - drivers/clk/clk.c:clk_unregister
  - drivers/clk/clk.c:clk_hw_set_parent
```
**Symbols:**

```
ffffffff8160b1d0-ffffffff8160b441: clk_core_set_parent_nolock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
int clk_core_set_parent_nolock(struct clk_core *core, struct clk_core *parent);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffff81644a80)
Location: drivers/clk/clk.c:2456
Inline: True
Direct callers:
  - drivers/clk/clk.c:clk_unregister
  - drivers/clk/clk.c:clk_hw_set_parent
```
**Symbols:**

```
ffffffff81644a80-ffffffff81644cf1: clk_core_set_parent_nolock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
int clk_core_set_parent_nolock(struct clk_core *core, struct clk_core *parent);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffff8165ef70)
Location: drivers/clk/clk.c:2456
Inline: True
Direct callers:
  - drivers/clk/clk.c:clk_unregister
  - drivers/clk/clk.c:clk_hw_set_parent
```
**Symbols:**

```
ffffffff8165ef70-ffffffff8165f213: clk_core_set_parent_nolock (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
