# Function: <code>clk_core_is_prepared</code>

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
In drivers/clk/clk.c (ffffffff816e738a)
Location: drivers/clk/clk.c:151
Inline: True
Inline callers:
  - drivers/clk/clk.c:clk_hw_is_prepared
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
In drivers/clk/clk.c (ffffffff8174c838)
Location: drivers/clk/clk.c:151
Inline: True
Inline callers:
  - drivers/clk/clk.c:clk_hw_is_prepared
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
In drivers/clk/clk.c (ffffffff81535098)
Location: drivers/clk/clk.c:151
Inline: True
Inline callers:
  - drivers/clk/clk.c:clk_hw_is_prepared
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
In drivers/clk/clk.c (ffffffff81548488)
Location: drivers/clk/clk.c:151
Inline: True
Inline callers:
  - drivers/clk/clk.c:clk_hw_is_prepared
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
bool clk_core_is_prepared(struct clk_core *core);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffff815a8ee0)
Location: drivers/clk/clk.c:173
Inline: True
Direct callers:
  - drivers/clk/clk.c:clk_hw_is_prepared
```
**Symbols:**

```
ffffffff815a8ee0-ffffffff815a8f5e: clk_core_is_prepared (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
bool clk_core_is_prepared(struct clk_core *core);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffff815e0890)
Location: drivers/clk/clk.c:188
Inline: True
Direct callers:
  - drivers/clk/clk.c:clk_hw_is_prepared
```
**Symbols:**

```
ffffffff815e0890-ffffffff815e090c: clk_core_is_prepared (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
bool clk_core_is_prepared(struct clk_core *core);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffff815fa970)
Location: drivers/clk/clk.c:186
Inline: True
Direct callers:
  - drivers/clk/clk.c:clk_hw_is_prepared
```
**Symbols:**

```
ffffffff815fa970-ffffffff815fa9ec: clk_core_is_prepared (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
bool clk_core_is_prepared(struct clk_core *core);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffff8162ce30)
Location: drivers/clk/clk.c:196
Inline: True
Direct callers:
  - drivers/clk/clk.c:clk_hw_is_prepared
```
**Symbols:**

```
ffffffff8162ce30-ffffffff8162ceb3: clk_core_is_prepared (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
bool clk_core_is_prepared(struct clk_core *core);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffff8164e4f0)
Location: drivers/clk/clk.c:202
Inline: True
Direct callers:
  - drivers/clk/clk.c:clk_hw_is_prepared
```
**Symbols:**

```
ffffffff8164e4f0-ffffffff8164e573: clk_core_is_prepared (STB_LOCAL)
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
In drivers/clk/clk.c (ffffffff82d1646d)
Location: drivers/clk/clk.c:206
Inline: True
Inline callers:
  - drivers/clk/clk.c:clk_unprepare_unused_subtree
  - drivers/clk/clk.c:clk_unprepare_unused_subtree
  - drivers/clk/clk.c:clk_hw_is_prepared
  - drivers/clk/clk.c:clk_hw_is_prepared
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
In drivers/clk/clk.c (ffffffff8300411f)
Location: drivers/clk/clk.c:206
Inline: True
Inline callers:
  - drivers/clk/clk.c:clk_unprepare_unused_subtree
  - drivers/clk/clk.c:clk_unprepare_unused_subtree
  - drivers/clk/clk.c:clk_hw_is_prepared
  - drivers/clk/clk.c:clk_hw_is_prepared
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
In drivers/clk/clk.c (ffffffff8320ec3c)
Location: drivers/clk/clk.c:206
Inline: True
Inline callers:
  - drivers/clk/clk.c:clk_unprepare_unused_subtree
  - drivers/clk/clk.c:clk_unprepare_unused_subtree
  - drivers/clk/clk.c:clk_hw_is_prepared
  - drivers/clk/clk.c:clk_hw_is_prepared
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
In drivers/clk/clk.c (ffffffff832f7a09)
Location: drivers/clk/clk.c:206
Inline: True
Inline callers:
  - drivers/clk/clk.c:clk_unprepare_unused_subtree
  - drivers/clk/clk.c:clk_unprepare_unused_subtree
  - drivers/clk/clk.c:clk_hw_is_prepared
  - drivers/clk/clk.c:clk_hw_is_prepared
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
In drivers/clk/clk.c (ffffffff834b0024)
Location: drivers/clk/clk.c:199
Inline: True
Inline callers:
  - drivers/clk/clk.c:clk_unprepare_unused_subtree
  - drivers/clk/clk.c:clk_unprepare_unused_subtree
  - drivers/clk/clk.c:clk_hw_is_prepared
  - drivers/clk/clk.c:clk_hw_is_prepared
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
In drivers/clk/clk.c (ffffffff83ee987f)
Location: drivers/clk/clk.c:199
Inline: True
Inline callers:
  - drivers/clk/clk.c:clk_unprepare_unused_subtree
  - drivers/clk/clk.c:clk_unprepare_unused_subtree
  - drivers/clk/clk.c:clk_hw_is_prepared
  - drivers/clk/clk.c:clk_hw_is_prepared
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
In drivers/clk/clk.c (ffffffff8370f26f)
Location: drivers/clk/clk.c:199
Inline: True
Inline callers:
  - drivers/clk/clk.c:clk_unprepare_unused_subtree
  - drivers/clk/clk.c:clk_unprepare_unused_subtree
  - drivers/clk/clk.c:clk_hw_is_prepared
  - drivers/clk/clk.c:clk_hw_is_prepared
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
In drivers/clk/clk.c (ffffffff83942a3f)
Location: drivers/clk/clk.c:199
Inline: True
Inline callers:
  - drivers/clk/clk.c:clk_unprepare_unused_subtree
  - drivers/clk/clk.c:clk_unprepare_unused_subtree
  - drivers/clk/clk.c:clk_hw_is_prepared
  - drivers/clk/clk.c:clk_hw_is_prepared
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
bool clk_core_is_prepared(struct clk_core *core);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffff8000107bdab8)
Location: drivers/clk/clk.c:202
Inline: True
Direct callers:
  - drivers/clk/clk.c:clk_hw_is_prepared
```
**Symbols:**

```
ffff8000107bdab8-ffff8000107bdb74: clk_core_is_prepared (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
bool clk_core_is_prepared(struct clk_core *core);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (c08e9518)
Location: drivers/clk/clk.c:202
Inline: True
Direct callers:
  - drivers/clk/clk.c:clk_hw_is_prepared
```
**Symbols:**

```
c08e9518-c08e95b0: clk_core_is_prepared (STB_LOCAL)
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
bool clk_core_is_prepared(struct clk_core *core);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffe00050cf92)
Location: drivers/clk/clk.c:202
Inline: True
Direct callers:
  - drivers/clk/clk.c:clk_hw_is_prepared
```
**Symbols:**

```
ffffffe00050cf92-ffffffe00050d022: clk_core_is_prepared (STB_LOCAL)
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
bool clk_core_is_prepared(struct clk_core *core);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffff81614550)
Location: drivers/clk/clk.c:202
Inline: True
Direct callers:
  - drivers/clk/clk.c:clk_hw_is_prepared
```
**Symbols:**

```
ffffffff81614550-ffffffff816145d3: clk_core_is_prepared (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
bool clk_core_is_prepared(struct clk_core *core);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffff81608a80)
Location: drivers/clk/clk.c:202
Inline: True
Direct callers:
  - drivers/clk/clk.c:clk_hw_is_prepared
```
**Symbols:**

```
ffffffff81608a80-ffffffff81608b03: clk_core_is_prepared (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
bool clk_core_is_prepared(struct clk_core *core);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffff81642330)
Location: drivers/clk/clk.c:202
Inline: True
Direct callers:
  - drivers/clk/clk.c:clk_hw_is_prepared
```
**Symbols:**

```
ffffffff81642330-ffffffff816423b3: clk_core_is_prepared (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
bool clk_core_is_prepared(struct clk_core *core);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clk/clk.c (ffffffff8165c710)
Location: drivers/clk/clk.c:202
Inline: True
Direct callers:
  - drivers/clk/clk.c:clk_hw_is_prepared
```
**Symbols:**

```
ffffffff8165c710-ffffffff8165c793: clk_core_is_prepared (STB_LOCAL)
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
