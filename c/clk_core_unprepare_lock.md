# Function: <code>clk_core_unprepare_lock</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffff8174ae42)
Location: drivers/clk/clk.c:496
Inline: True
Inline callers:
  - drivers/clk/clk.c:clk_core_disable_unprepare
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
In drivers/clk/clk.c (ffffffff815336c2)
Location: drivers/clk/clk.c:496
Inline: True
Inline callers:
  - drivers/clk/clk.c:clk_core_disable_unprepare
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
In drivers/clk/clk.c (ffffffff81545f12)
Location: drivers/clk/clk.c:496
Inline: True
Inline callers:
  - drivers/clk/clk.c:clk_core_disable_unprepare
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
In drivers/clk/clk.c (ffffffff815a8a72)
Location: drivers/clk/clk.c:552
Inline: True
Inline callers:
  - drivers/clk/clk.c:clk_core_disable_unprepare
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
In drivers/clk/clk.c (ffffffff815e1eb2)
Location: drivers/clk/clk.c:709
Inline: True
Inline callers:
  - drivers/clk/clk.c:clk_core_disable_unprepare
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
In drivers/clk/clk.c (ffffffff815fc062)
Location: drivers/clk/clk.c:710
Inline: True
Inline callers:
  - drivers/clk/clk.c:clk_core_disable_unprepare
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
In drivers/clk/clk.c (ffffffff8162ecc3)
Location: drivers/clk/clk.c:831
Inline: True
Inline callers:
  - drivers/clk/clk.c:clk_core_disable_unprepare
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
In drivers/clk/clk.c (ffffffff816507f3)
Location: drivers/clk/clk.c:839
Inline: True
Inline callers:
  - drivers/clk/clk.c:clk_core_disable_unprepare
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void clk_core_unprepare_lock(struct clk_core *core);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffff8170164d)
Location: drivers/clk/clk.c:843
Inline: True
Inline callers:
  - drivers/clk/clk.c:clk_change_rate
  - drivers/clk/clk.c:clk_unprepare
Direct callers:
  - drivers/clk/clk.c:clk_disable_unused_subtree
```
**Symbols:**

```
ffffffff81702849-ffffffff8170286d: clk_core_unprepare_lock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void clk_core_unprepare_lock(struct clk_core *core);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffff8171eb2d)
Location: drivers/clk/clk.c:837
Inline: True
Inline callers:
  - drivers/clk/clk.c:clk_change_rate
  - drivers/clk/clk.c:clk_unprepare
Direct callers:
  - drivers/clk/clk.c:clk_disable_unused_subtree
```
**Symbols:**

```
ffffffff81c04103-ffffffff81c04127: clk_core_unprepare_lock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void clk_core_unprepare_lock(struct clk_core *core);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffff816ffb6d)
Location: drivers/clk/clk.c:837
Inline: True
Inline callers:
  - drivers/clk/clk.c:clk_change_rate
  - drivers/clk/clk.c:clk_unprepare
Direct callers:
  - drivers/clk/clk.c:clk_disable_unused_subtree
```
**Symbols:**

```
ffffffff81bf5b0f-ffffffff81bf5b33: clk_core_unprepare_lock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void clk_core_unprepare_lock(struct clk_core *core);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffff8177a340)
Location: drivers/clk/clk.c:837
Inline: True
Inline callers:
  - drivers/clk/clk.c:clk_change_rate
  - drivers/clk/clk.c:clk_unprepare
Direct callers:
  - drivers/clk/clk.c:clk_disable_unused_subtree
```
**Symbols:**

```
ffffffff81cf31ac-ffffffff81cf31d0: clk_core_unprepare_lock (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void clk_core_unprepare_lock(struct clk_core *core);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffff818b07e4)
Location: drivers/clk/clk.c:849
Inline: True
Inline callers:
  - drivers/clk/clk.c:clk_change_rate
  - drivers/clk/clk.c:clk_unprepare
Direct callers:
  - drivers/clk/clk.c:clk_disable_unused_subtree
```
**Symbols:**

```
ffffffff81ebb30d-ffffffff81ebb335: clk_core_unprepare_lock (STB_LOCAL)
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
In drivers/clk/clk.c (ffffffff819fcccd)
Location: drivers/clk/clk.c:933
Inline: True
Inline callers:
  - drivers/clk/clk.c:clk_change_rate
  - drivers/clk/clk.c:clk_disable_unused_subtree
  - drivers/clk/clk.c:clk_unprepare
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
In drivers/clk/clk.c (ffffffff81a4573d)
Location: drivers/clk/clk.c:975
Inline: True
Inline callers:
  - drivers/clk/clk.c:clk_change_rate
  - drivers/clk/clk.c:clk_disable_unused_subtree
  - drivers/clk/clk.c:clk_unprepare
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
In drivers/clk/clk.c (ffffffff81a9122d)
Location: drivers/clk/clk.c:975
Inline: True
Inline callers:
  - drivers/clk/clk.c:clk_change_rate
  - drivers/clk/clk.c:clk_disable_unused_subtree
  - drivers/clk/clk.c:clk_unprepare
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffff8000107c0af0)
Location: drivers/clk/clk.c:839
Inline: True
Inline callers:
  - drivers/clk/clk.c:clk_core_disable_unprepare
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (c08ec0f0)
Location: drivers/clk/clk.c:839
Inline: True
Inline callers:
  - drivers/clk/clk.c:clk_core_disable_unprepare
```
</details>
</li>
<li>
In <code>ppc64el</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffe00050ec40)
Location: drivers/clk/clk.c:839
Inline: True
Inline callers:
  - drivers/clk/clk.c:clk_core_disable_unprepare
```
</details>
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
In drivers/clk/clk.c (ffffffff81616853)
Location: drivers/clk/clk.c:839
Inline: True
Inline callers:
  - drivers/clk/clk.c:clk_core_disable_unprepare
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
In drivers/clk/clk.c (ffffffff8160ad83)
Location: drivers/clk/clk.c:839
Inline: True
Inline callers:
  - drivers/clk/clk.c:clk_core_disable_unprepare
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
In drivers/clk/clk.c (ffffffff81644633)
Location: drivers/clk/clk.c:839
Inline: True
Inline callers:
  - drivers/clk/clk.c:clk_core_disable_unprepare
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
In drivers/clk/clk.c (ffffffff8165eae3)
Location: drivers/clk/clk.c:839
Inline: True
Inline callers:
  - drivers/clk/clk.c:clk_core_disable_unprepare
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
</ul>
