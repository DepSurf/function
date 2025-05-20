# Function: <code>clk_core_get_parent_by_index</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
struct clk_core *clk_core_get_parent_by_index(struct clk_core *core, u8 index);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffff816e5f10)
Location: drivers/clk/clk.c:348
Inline: True
Direct callers:
  - drivers/clk/clk.c:clk_hw_get_parent_by_index
  - drivers/clk/clk.c:clk_register
```
**Symbols:**

```
ffffffff816e5f10-ffffffff816e5f68: clk_core_get_parent_by_index (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: ✅</summary>

```c
struct clk_core *clk_core_get_parent_by_index(struct clk_core *core, u8 index);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffff81749b20)
Location: drivers/clk/clk.c:250
Inline: False
Direct callers:
  - drivers/clk/clk.c:__clk_init_parent
  - drivers/clk/clk.c:__clk_init_parent
  - drivers/clk/clk.c:clk_fetch_parent_index
  - drivers/clk/clk.c:clk_hw_get_parent_by_index
```
**Symbols:**

```
ffffffff81749b20-ffffffff81749b76: clk_core_get_parent_by_index (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
struct clk_core *clk_core_get_parent_by_index(struct clk_core *core, u8 index);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffff815323a0)
Location: drivers/clk/clk.c:250
Inline: False
Direct callers:
  - drivers/clk/clk.c:__clk_init_parent
  - drivers/clk/clk.c:__clk_init_parent
  - drivers/clk/clk.c:clk_fetch_parent_index
  - drivers/clk/clk.c:clk_hw_get_parent_by_index
```
**Symbols:**

```
ffffffff815323a0-ffffffff815323f6: clk_core_get_parent_by_index (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
struct clk_core *clk_core_get_parent_by_index(struct clk_core *core, u8 index);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffff81545890)
Location: drivers/clk/clk.c:250
Inline: False
Direct callers:
  - drivers/clk/clk.c:__clk_init_parent
  - drivers/clk/clk.c:clk_calc_new_rates
  - drivers/clk/clk.c:clk_hw_get_parent_by_index
```
**Symbols:**

```
ffffffff81545890-ffffffff815458eb: clk_core_get_parent_by_index (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
struct clk_core *clk_core_get_parent_by_index(struct clk_core *core, u8 index);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffff815a8e10)
Location: drivers/clk/clk.c:304
Inline: False
Direct callers:
  - drivers/clk/clk.c:__clk_init_parent
  - drivers/clk/clk.c:clk_calc_new_rates
  - drivers/clk/clk.c:clk_hw_get_parent_by_index
```
**Symbols:**

```
ffffffff815a8e10-ffffffff815a8e6b: clk_core_get_parent_by_index (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
struct clk_core *clk_core_get_parent_by_index(struct clk_core *core, u8 index);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffff815e07c0)
Location: drivers/clk/clk.c:319
Inline: False
Direct callers:
  - drivers/clk/clk.c:__clk_init_parent
  - drivers/clk/clk.c:clk_calc_new_rates
  - drivers/clk/clk.c:clk_mux_determine_rate_flags
  - drivers/clk/clk.c:clk_hw_get_parent_by_index
```
**Symbols:**

```
ffffffff815e07c0-ffffffff815e081b: clk_core_get_parent_by_index (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
struct clk_core *clk_core_get_parent_by_index(struct clk_core *core, u8 index);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffff815fa800)
Location: drivers/clk/clk.c:317
Inline: False
Direct callers:
  - drivers/clk/clk.c:__clk_init_parent
  - drivers/clk/clk.c:clk_mux_determine_rate_flags
  - drivers/clk/clk.c:clk_hw_get_parent_by_index
```
**Symbols:**

```
ffffffff815fa800-ffffffff815fa85b: clk_core_get_parent_by_index (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct clk_core *clk_core_get_parent_by_index(struct clk_core *core, u8 index);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffff8162ca50)
Location: drivers/clk/clk.c:435
Inline: False
Direct callers:
  - drivers/clk/clk.c:possible_parent_show
  - drivers/clk/clk.c:__clk_init_parent
  - drivers/clk/clk.c:clk_mux_determine_rate_flags
  - drivers/clk/clk.c:clk_hw_get_parent_by_index
```
**Symbols:**

```
ffffffff8162ca50-ffffffff8162caf5: clk_core_get_parent_by_index (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct clk_core *clk_core_get_parent_by_index(struct clk_core *core, u8 index);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffff8164df20)
Location: drivers/clk/clk.c:441
Inline: False
Direct callers:
  - drivers/clk/clk.c:possible_parent_show
  - drivers/clk/clk.c:__clk_init_parent
  - drivers/clk/clk.c:clk_mux_determine_rate_flags
  - drivers/clk/clk.c:clk_hw_get_parent_by_index
```
**Symbols:**

```
ffffffff8164df20-ffffffff8164dfc5: clk_core_get_parent_by_index (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct clk_core *clk_core_get_parent_by_index(struct clk_core *core, u8 index);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffff816fd720)
Location: drivers/clk/clk.c:445
Inline: False
Direct callers:
  - drivers/clk/clk.c:__clk_core_init
  - drivers/clk/clk.c:clk_core_reparent_orphans_nolock
  - drivers/clk/clk.c:possible_parent_show
  - drivers/clk/clk.c:clk_mux_determine_rate_flags
  - drivers/clk/clk.c:clk_hw_get_parent_by_index
```
**Symbols:**

```
ffffffff816fd720-ffffffff816fd7c4: clk_core_get_parent_by_index (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct clk_core *clk_core_get_parent_by_index(struct clk_core *core, u8 index);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffff8171a840)
Location: drivers/clk/clk.c:445
Inline: False
Direct callers:
  - drivers/clk/clk.c:__clk_core_init
  - drivers/clk/clk.c:clk_core_reparent_orphans_nolock
  - drivers/clk/clk.c:possible_parent_show
  - drivers/clk/clk.c:clk_mux_determine_rate_flags
  - drivers/clk/clk.c:clk_hw_get_parent_by_index
```
**Symbols:**

```
ffffffff8171a840-ffffffff8171a8e4: clk_core_get_parent_by_index (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
struct clk_core *clk_core_get_parent_by_index(struct clk_core *core, u8 index);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffff816fb9e0)
Location: drivers/clk/clk.c:445
Inline: False
Direct callers:
  - drivers/clk/clk.c:__clk_core_init
  - drivers/clk/clk.c:__clk_core_init
  - drivers/clk/clk.c:possible_parent_show
  - drivers/clk/clk.c:clk_mux_determine_rate_flags
  - drivers/clk/clk.c:clk_hw_get_parent_by_index
```
**Symbols:**

```
ffffffff816fb9e0-ffffffff816fba84: clk_core_get_parent_by_index (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
struct clk_core *clk_core_get_parent_by_index(struct clk_core *core, u8 index);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffff817761a0)
Location: drivers/clk/clk.c:445
Inline: False
Direct callers:
  - drivers/clk/clk.c:__clk_core_init
  - drivers/clk/clk.c:__clk_core_init
  - drivers/clk/clk.c:possible_parent_show
  - drivers/clk/clk.c:clk_mux_determine_rate_flags
  - drivers/clk/clk.c:clk_hw_get_parent_by_index
```
**Symbols:**

```
ffffffff817761a0-ffffffff81776244: clk_core_get_parent_by_index (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
struct clk_core *clk_core_get_parent_by_index(struct clk_core *core, u8 index);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffff818aca10)
Location: drivers/clk/clk.c:439
Inline: False
Direct callers:
  - drivers/clk/clk.c:__clk_core_init
  - drivers/clk/clk.c:__clk_core_init
  - drivers/clk/clk.c:possible_parent_show
  - drivers/clk/clk.c:clk_mux_determine_rate_flags
  - drivers/clk/clk.c:clk_hw_get_parent_by_index
```
**Symbols:**

```
ffffffff818aca10-ffffffff818acae8: clk_core_get_parent_by_index (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
struct clk_core *clk_core_get_parent_by_index(struct clk_core *core, u8 index);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffff819f8050)
Location: drivers/clk/clk.c:439
Inline: False
Direct callers:
  - drivers/clk/clk.c:__clk_core_init
  - drivers/clk/clk.c:__clk_core_init
  - drivers/clk/clk.c:possible_parent_show
  - drivers/clk/clk.c:clk_mux_determine_rate_flags
  - drivers/clk/clk.c:clk_core_forward_rate_req
  - drivers/clk/clk.c:clk_hw_get_parent_by_index
```
**Symbols:**

```
ffffffff819f8050-ffffffff819f8128: clk_core_get_parent_by_index (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
struct clk_core *clk_core_get_parent_by_index(struct clk_core *core, u8 index);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffff81a40900)
Location: drivers/clk/clk.c:450
Inline: False
Direct callers:
  - drivers/clk/clk.c:__clk_core_init
  - drivers/clk/clk.c:__clk_core_init
  - drivers/clk/clk.c:possible_parent_show
  - drivers/clk/clk.c:clk_mux_determine_rate_flags
  - drivers/clk/clk.c:clk_core_forward_rate_req
  - drivers/clk/clk.c:clk_hw_get_parent_by_index
```
**Symbols:**

```
ffffffff81a40900-ffffffff81a409d8: clk_core_get_parent_by_index (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct clk_core *clk_core_get_parent_by_index(struct clk_core *core, u8 index);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffff81a8c320)
Location: drivers/clk/clk.c:450
Inline: False
Direct callers:
  - drivers/clk/clk.c:__clk_core_init
  - drivers/clk/clk.c:__clk_core_init
  - drivers/clk/clk.c:possible_parent_show
  - drivers/clk/clk.c:clk_mux_determine_rate_flags
  - drivers/clk/clk.c:clk_core_forward_rate_req
  - drivers/clk/clk.c:clk_hw_get_parent_by_index
```
**Symbols:**

```
ffffffff81a8c320-ffffffff81a8c3f8: clk_core_get_parent_by_index (STB_LOCAL)
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
struct clk_core *clk_core_get_parent_by_index(struct clk_core *core, u8 index);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffff8000107bd150)
Location: drivers/clk/clk.c:441
Inline: False
Direct callers:
  - drivers/clk/clk.c:possible_parent_show
  - drivers/clk/clk.c:__clk_init_parent
  - drivers/clk/clk.c:clk_mux_determine_rate_flags
  - drivers/clk/clk.c:clk_hw_get_parent_by_index
```
**Symbols:**

```
ffff8000107bd150-ffff8000107bd220: clk_core_get_parent_by_index (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct clk_core *clk_core_get_parent_by_index(struct clk_core *core, u8 index);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (c08e921c)
Location: drivers/clk/clk.c:441
Inline: False
Direct callers:
  - drivers/clk/clk.c:possible_parent_show
  - drivers/clk/clk.c:__clk_init_parent
  - drivers/clk/clk.c:clk_mux_determine_rate_flags
  - drivers/clk/clk.c:clk_hw_get_parent_by_index
```
**Symbols:**

```
c08e921c-c08e92ec: clk_core_get_parent_by_index (STB_LOCAL)
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
struct clk_core *clk_core_get_parent_by_index(struct clk_core *core, u8 index);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffe00050c570)
Location: drivers/clk/clk.c:441
Inline: False
Direct callers:
  - drivers/clk/clk.c:possible_parent_show
  - drivers/clk/clk.c:__clk_init_parent
  - drivers/clk/clk.c:clk_mux_determine_rate_flags
  - drivers/clk/clk.c:clk_hw_get_parent_by_index
```
**Symbols:**

```
ffffffe00050c570-ffffffe00050c624: clk_core_get_parent_by_index (STB_LOCAL)
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
struct clk_core *clk_core_get_parent_by_index(struct clk_core *core, u8 index);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffff81613f80)
Location: drivers/clk/clk.c:441
Inline: False
Direct callers:
  - drivers/clk/clk.c:possible_parent_show
  - drivers/clk/clk.c:__clk_init_parent
  - drivers/clk/clk.c:clk_mux_determine_rate_flags
  - drivers/clk/clk.c:clk_hw_get_parent_by_index
```
**Symbols:**

```
ffffffff81613f80-ffffffff81614025: clk_core_get_parent_by_index (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct clk_core *clk_core_get_parent_by_index(struct clk_core *core, u8 index);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffff816084b0)
Location: drivers/clk/clk.c:441
Inline: False
Direct callers:
  - drivers/clk/clk.c:possible_parent_show
  - drivers/clk/clk.c:__clk_init_parent
  - drivers/clk/clk.c:clk_mux_determine_rate_flags
  - drivers/clk/clk.c:clk_hw_get_parent_by_index
```
**Symbols:**

```
ffffffff816084b0-ffffffff81608555: clk_core_get_parent_by_index (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct clk_core *clk_core_get_parent_by_index(struct clk_core *core, u8 index);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffff81641d60)
Location: drivers/clk/clk.c:441
Inline: False
Direct callers:
  - drivers/clk/clk.c:possible_parent_show
  - drivers/clk/clk.c:__clk_init_parent
  - drivers/clk/clk.c:clk_mux_determine_rate_flags
  - drivers/clk/clk.c:clk_hw_get_parent_by_index
```
**Symbols:**

```
ffffffff81641d60-ffffffff81641e05: clk_core_get_parent_by_index (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct clk_core *clk_core_get_parent_by_index(struct clk_core *core, u8 index);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffff8165c140)
Location: drivers/clk/clk.c:441
Inline: False
Direct callers:
  - drivers/clk/clk.c:possible_parent_show
  - drivers/clk/clk.c:__clk_init_parent
  - drivers/clk/clk.c:clk_mux_determine_rate_flags
  - drivers/clk/clk.c:clk_hw_get_parent_by_index
```
**Symbols:**

```
ffffffff8165c140-ffffffff8165c1e5: clk_core_get_parent_by_index (STB_LOCAL)
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
