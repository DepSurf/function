# Function: <code>alloc_clk</code>

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
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
struct clk *alloc_clk(struct clk_core *core, const char *dev_id, const char *con_id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffff8162c550)
Location: drivers/clk/clk.c:3424
Inline: False
Direct callers:
  - drivers/clk/clk.c:__clk_register
  - drivers/clk/clk.c:clk_hw_create_clk
```
**Symbols:**

```
ffffffff8162c550-ffffffff8162c5be: alloc_clk (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct clk *alloc_clk(struct clk_core *core, const char *dev_id, const char *con_id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffff8164db20)
Location: drivers/clk/clk.c:3473
Inline: False
Direct callers:
  - drivers/clk/clk.c:__clk_register
  - drivers/clk/clk.c:clk_hw_create_clk
```
**Symbols:**

```
ffffffff8164db20-ffffffff8164db8e: alloc_clk (STB_LOCAL)
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
In drivers/clk/clk.c (ffffffff81701080)
Location: drivers/clk/clk.c:3563
Inline: True
Inline callers:
  - drivers/clk/clk.c:__clk_register
  - drivers/clk/clk.c:clk_hw_create_clk
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
In drivers/clk/clk.c (ffffffff8171e5a0)
Location: drivers/clk/clk.c:3614
Inline: True
Inline callers:
  - drivers/clk/clk.c:__clk_register
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
In drivers/clk/clk.c (ffffffff816ff5f0)
Location: drivers/clk/clk.c:3623
Inline: True
Inline callers:
  - drivers/clk/clk.c:__clk_register
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
In drivers/clk/clk.c (ffffffff81779ddd)
Location: drivers/clk/clk.c:3651
Inline: True
Inline callers:
  - drivers/clk/clk.c:__clk_register
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
In drivers/clk/clk.c (ffffffff818b01e7)
Location: drivers/clk/clk.c:3723
Inline: True
Inline callers:
  - drivers/clk/clk.c:__clk_register
  - drivers/clk/clk.c:clk_hw_create_clk
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
In drivers/clk/clk.c (ffffffff819fc697)
Location: drivers/clk/clk.c:3912
Inline: True
Inline callers:
  - drivers/clk/clk.c:__clk_register
  - drivers/clk/clk.c:clk_hw_create_clk
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
In drivers/clk/clk.c (ffffffff81a45107)
Location: drivers/clk/clk.c:3964
Inline: True
Inline callers:
  - drivers/clk/clk.c:__clk_register
  - drivers/clk/clk.c:clk_hw_create_clk
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
struct clk *alloc_clk(struct clk_core *core, const char *dev_id, const char *con_id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffff81a8bbe0)
Location: drivers/clk/clk.c:4010
Inline: False
Direct callers:
  - drivers/clk/clk.c:__clk_register
  - drivers/clk/clk.c:clk_hw_create_clk
```
**Symbols:**

```
ffffffff81a8bbe0-ffffffff81a8bc85: alloc_clk (STB_LOCAL)
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
struct clk *alloc_clk(struct clk_core *core, const char *dev_id, const char *con_id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffff8000107bc7e8)
Location: drivers/clk/clk.c:3473
Inline: False
Direct callers:
  - drivers/clk/clk.c:__clk_register
```
**Symbols:**

```
ffff8000107bc7e8-ffff8000107bc864: alloc_clk (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct clk *alloc_clk(struct clk_core *core, const char *dev_id, const char *con_id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (c08e8b80)
Location: drivers/clk/clk.c:3473
Inline: False
Direct callers:
  - drivers/clk/clk.c:__clk_register
```
**Symbols:**

```
c08e8b80-c08e8bf0: alloc_clk (STB_LOCAL)
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
struct clk *alloc_clk(struct clk_core *core, const char *dev_id, const char *con_id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffe00050bd1a)
Location: drivers/clk/clk.c:3473
Inline: False
Direct callers:
  - drivers/clk/clk.c:__clk_register
```
**Symbols:**

```
ffffffe00050bd1a-ffffffe00050bd8e: alloc_clk (STB_LOCAL)
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
struct clk *alloc_clk(struct clk_core *core, const char *dev_id, const char *con_id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffff81613b80)
Location: drivers/clk/clk.c:3473
Inline: False
Direct callers:
  - drivers/clk/clk.c:__clk_register
  - drivers/clk/clk.c:clk_hw_create_clk
```
**Symbols:**

```
ffffffff81613b80-ffffffff81613bee: alloc_clk (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct clk *alloc_clk(struct clk_core *core, const char *dev_id, const char *con_id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffff816080b0)
Location: drivers/clk/clk.c:3473
Inline: False
Direct callers:
  - drivers/clk/clk.c:__clk_register
  - drivers/clk/clk.c:clk_hw_create_clk
```
**Symbols:**

```
ffffffff816080b0-ffffffff8160811e: alloc_clk (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct clk *alloc_clk(struct clk_core *core, const char *dev_id, const char *con_id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffff81641960)
Location: drivers/clk/clk.c:3473
Inline: False
Direct callers:
  - drivers/clk/clk.c:__clk_register
  - drivers/clk/clk.c:clk_hw_create_clk
```
**Symbols:**

```
ffffffff81641960-ffffffff816419ce: alloc_clk (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct clk *alloc_clk(struct clk_core *core, const char *dev_id, const char *con_id);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffff8165bd40)
Location: drivers/clk/clk.c:3473
Inline: False
Direct callers:
  - drivers/clk/clk.c:__clk_register
  - drivers/clk/clk.c:clk_hw_create_clk
```
**Symbols:**

```
ffffffff8165bd40-ffffffff8165bdae: alloc_clk (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
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
