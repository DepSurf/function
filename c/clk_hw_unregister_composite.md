# Function: <code>clk_hw_unregister_composite</code>

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
In <code>5.3</code>: Absent ⚠️
</li>
<li>
In <code>5.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void clk_hw_unregister_composite(struct clk_hw *hw);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/clk-composite.c (ffffffff81704d60)
Location: drivers/clk/clk-composite.c:397
Inline: False
```
**Symbols:**

```
ffffffff81704d60-ffffffff81704d81: clk_hw_unregister_composite (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void clk_hw_unregister_composite(struct clk_hw *hw);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clk/clk-composite.c (ffffffff81721fae)
Location: drivers/clk/clk-composite.c:399
Inline: True
Inline callers:
  - drivers/clk/clk-composite.c:devm_clk_hw_release_composite
```
**Symbols:**

```
ffffffff81721f70-ffffffff81721f91: clk_hw_unregister_composite (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void clk_hw_unregister_composite(struct clk_hw *hw);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clk/clk-composite.c (ffffffff817033be)
Location: drivers/clk/clk-composite.c:399
Inline: True
Inline callers:
  - drivers/clk/clk-composite.c:devm_clk_hw_release_composite
```
**Symbols:**

```
ffffffff81703380-ffffffff817033a1: clk_hw_unregister_composite (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void clk_hw_unregister_composite(struct clk_hw *hw);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clk/clk-composite.c (ffffffff8177e0be)
Location: drivers/clk/clk-composite.c:399
Inline: True
Inline callers:
  - drivers/clk/clk-composite.c:devm_clk_hw_release_composite
```
**Symbols:**

```
ffffffff8177e080-ffffffff8177e0a1: clk_hw_unregister_composite (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void clk_hw_unregister_composite(struct clk_hw *hw);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clk/clk-composite.c (ffffffff818b4b1d)
Location: drivers/clk/clk-composite.c:429
Inline: True
Inline callers:
  - drivers/clk/clk-composite.c:devm_clk_hw_release_composite
```
**Symbols:**

```
ffffffff818b4ae0-ffffffff818b4b06: clk_hw_unregister_composite (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void clk_hw_unregister_composite(struct clk_hw *hw);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clk/clk-composite.c (ffffffff81a017bd)
Location: drivers/clk/clk-composite.c:431
Inline: True
Inline callers:
  - drivers/clk/clk-composite.c:devm_clk_hw_release_composite
```
**Symbols:**

```
ffffffff81a01770-ffffffff81a01796: clk_hw_unregister_composite (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void clk_hw_unregister_composite(struct clk_hw *hw);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clk/clk-composite.c (ffffffff81a4a4cd)
Location: drivers/clk/clk-composite.c:434
Inline: True
Inline callers:
  - drivers/clk/clk-composite.c:devm_clk_hw_release_composite
```
**Symbols:**

```
ffffffff81a4a480-ffffffff81a4a4a6: clk_hw_unregister_composite (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void clk_hw_unregister_composite(struct clk_hw *hw);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/clk/clk-composite.c (ffffffff81a9601d)
Location: drivers/clk/clk-composite.c:434
Inline: True
Inline callers:
  - drivers/clk/clk-composite.c:devm_clk_hw_release_composite
```
**Symbols:**

```
ffffffff81a95fd0-ffffffff81a95ff6: clk_hw_unregister_composite (STB_GLOBAL)
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
In <code>aws</code>: Absent ⚠️
</li>
<li>
In <code>azure</code>: Absent ⚠️
</li>
<li>
In <code>gcp</code>: Absent ⚠️
</li>
<li>
In <code>lowlatency</code>: Absent ⚠️
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
