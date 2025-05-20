# Function: <code>clk_core_get</code>

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
struct clk_core *clk_core_get(struct clk_core *core, u8 p_index);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffff8162b5c0)
Location: drivers/clk/clk.c:382
Inline: False
Direct callers:
  - drivers/clk/clk.c:clk_core_get_parent_by_index
```
**Symbols:**

```
ffffffff8162b5c0-ffffffff8162b61f: clk_core_get (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
struct clk_core *clk_core_get(struct clk_core *core, u8 p_index);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffff8164d100)
Location: drivers/clk/clk.c:388
Inline: False
Direct callers:
  - drivers/clk/clk.c:clk_core_get_parent_by_index
```
**Symbols:**

```
ffffffff8164d100-ffffffff8164d15f: clk_core_get (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/clk/clk.c (ffffffff816fce20)
Location: drivers/clk/clk.c:392
Inline: True
Direct callers:
  - drivers/clk/clk.c:clk_core_get_parent_by_index
```
**Symbols:**

```
ffffffff816fce20-ffffffff816fce77: clk_core_get.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/clk/clk.c (ffffffff81719d60)
Location: drivers/clk/clk.c:392
Inline: True
Direct callers:
  - drivers/clk/clk.c:clk_core_get_parent_by_index
```
**Symbols:**

```
ffffffff81719d60-ffffffff81719db7: clk_core_get.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/clk/clk.c (ffffffff816fb060)
Location: drivers/clk/clk.c:392
Inline: True
Direct callers:
  - drivers/clk/clk.c:clk_core_get_parent_by_index
```
**Symbols:**

```
ffffffff816fb060-ffffffff816fb0b7: clk_core_get.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/clk/clk.c (ffffffff817757e0)
Location: drivers/clk/clk.c:392
Inline: True
Direct callers:
  - drivers/clk/clk.c:clk_core_get_parent_by_index
```
**Symbols:**

```
ffffffff817757e0-ffffffff81775837: clk_core_get.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/clk/clk.c (ffffffff818abc60)
Location: drivers/clk/clk.c:385
Inline: True
Direct callers:
  - drivers/clk/clk.c:clk_fetch_parent_index
  - drivers/clk/clk.c:clk_core_get_parent_by_index
```
**Symbols:**

```
ffffffff818abc60-ffffffff818abcca: clk_core_get.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/clk/clk.c (ffffffff819f7310)
Location: drivers/clk/clk.c:385
Inline: True
Direct callers:
  - drivers/clk/clk.c:clk_fetch_parent_index
  - drivers/clk/clk.c:clk_core_get_parent_by_index
```
**Symbols:**

```
ffffffff819f7310-ffffffff819f737a: clk_core_get.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/clk/clk.c (ffffffff81a3f430)
Location: drivers/clk/clk.c:396
Inline: True
Direct callers:
  - drivers/clk/clk.c:clk_fetch_parent_index
  - drivers/clk/clk.c:clk_core_get_parent_by_index
```
**Symbols:**

```
ffffffff81a3f430-ffffffff81a3f49a: clk_core_get.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/clk/clk.c (ffffffff81a8ad60)
Location: drivers/clk/clk.c:396
Inline: True
Direct callers:
  - drivers/clk/clk.c:clk_fetch_parent_index
  - drivers/clk/clk.c:clk_core_get_parent_by_index
```
**Symbols:**

```
ffffffff81a8ad60-ffffffff81a8adca: clk_core_get.isra.0 (STB_LOCAL)
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
struct clk_core *clk_core_get(struct clk_core *core, u8 p_index);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffff8000107bd058)
Location: drivers/clk/clk.c:388
Inline: False
Direct callers:
  - drivers/clk/clk.c:clk_core_get_parent_by_index
```
**Symbols:**

```
ffff8000107bd058-ffff8000107bd14c: clk_core_get (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
struct clk_core *clk_core_get(struct clk_core *core, u8 p_index);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (c08e9120)
Location: drivers/clk/clk.c:388
Inline: False
Direct callers:
  - drivers/clk/clk.c:clk_core_get_parent_by_index
```
**Symbols:**

```
c08e9120-c08e921c: clk_core_get (STB_LOCAL)
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
struct clk_core *clk_core_get(struct clk_core *core, u8 p_index);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffe00050c4a4)
Location: drivers/clk/clk.c:388
Inline: False
Direct callers:
  - drivers/clk/clk.c:clk_core_get_parent_by_index
```
**Symbols:**

```
ffffffe00050c4a4-ffffffe00050c570: clk_core_get (STB_LOCAL)
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
struct clk_core *clk_core_get(struct clk_core *core, u8 p_index);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffff81613160)
Location: drivers/clk/clk.c:388
Inline: False
Direct callers:
  - drivers/clk/clk.c:clk_core_get_parent_by_index
```
**Symbols:**

```
ffffffff81613160-ffffffff816131bf: clk_core_get (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
struct clk_core *clk_core_get(struct clk_core *core, u8 p_index);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffff816076b0)
Location: drivers/clk/clk.c:388
Inline: False
Direct callers:
  - drivers/clk/clk.c:clk_core_get_parent_by_index
```
**Symbols:**

```
ffffffff816076b0-ffffffff8160770f: clk_core_get (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
struct clk_core *clk_core_get(struct clk_core *core, u8 p_index);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffff81640f40)
Location: drivers/clk/clk.c:388
Inline: False
Direct callers:
  - drivers/clk/clk.c:clk_core_get_parent_by_index
```
**Symbols:**

```
ffffffff81640f40-ffffffff81640f9f: clk_core_get (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
struct clk_core *clk_core_get(struct clk_core *core, u8 p_index);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffff8165b140)
Location: drivers/clk/clk.c:388
Inline: False
Direct callers:
  - drivers/clk/clk.c:clk_core_get_parent_by_index
```
**Symbols:**

```
ffffffff8165b140-ffffffff8165b19f: clk_core_get (STB_LOCAL)
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
