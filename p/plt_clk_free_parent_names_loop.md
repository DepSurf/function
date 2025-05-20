# Function: <code>plt_clk_free_parent_names_loop</code>

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
void plt_clk_free_parent_names_loop(const char **parent_names, unsigned int i);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/x86/clk-pmc-atom.c (ffffffff8154b970)
Location: drivers/clk/x86/clk-pmc-atom.c:256
Inline: False
Direct callers:
  - drivers/clk/x86/clk-pmc-atom.c:plt_clk_probe
  - drivers/clk/x86/clk-pmc-atom.c:plt_clk_probe
  - drivers/clk/x86/clk-pmc-atom.c:plt_clk_probe
```
**Symbols:**

```
ffffffff8154b970-ffffffff8154b9b0: plt_clk_free_parent_names_loop (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void plt_clk_free_parent_names_loop(const char **parent_names, unsigned int i);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/x86/clk-pmc-atom.c (ffffffff815aef00)
Location: drivers/clk/x86/clk-pmc-atom.c:256
Inline: False
Direct callers:
  - drivers/clk/x86/clk-pmc-atom.c:plt_clk_probe
  - drivers/clk/x86/clk-pmc-atom.c:plt_clk_probe
  - drivers/clk/x86/clk-pmc-atom.c:plt_clk_probe
```
**Symbols:**

```
ffffffff815aef00-ffffffff815aef40: plt_clk_free_parent_names_loop (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void plt_clk_free_parent_names_loop(const char **parent_names, unsigned int i);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/x86/clk-pmc-atom.c (ffffffff815e7110)
Location: drivers/clk/x86/clk-pmc-atom.c:256
Inline: False
Direct callers:
  - drivers/clk/x86/clk-pmc-atom.c:plt_clk_probe
  - drivers/clk/x86/clk-pmc-atom.c:plt_clk_probe
  - drivers/clk/x86/clk-pmc-atom.c:plt_clk_probe
```
**Symbols:**

```
ffffffff815e7110-ffffffff815e714d: plt_clk_free_parent_names_loop (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void plt_clk_free_parent_names_loop(const char **parent_names, unsigned int i);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/x86/clk-pmc-atom.c (ffffffff81601540)
Location: drivers/clk/x86/clk-pmc-atom.c:250
Inline: False
Direct callers:
  - drivers/clk/x86/clk-pmc-atom.c:plt_clk_probe
  - drivers/clk/x86/clk-pmc-atom.c:plt_clk_probe
  - drivers/clk/x86/clk-pmc-atom.c:plt_clk_probe
```
**Symbols:**

```
ffffffff81601540-ffffffff8160157d: plt_clk_free_parent_names_loop (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void plt_clk_free_parent_names_loop(const char **parent_names, unsigned int i);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/x86/clk-pmc-atom.c (ffffffff81633e80)
Location: drivers/clk/x86/clk-pmc-atom.c:251
Inline: False
Direct callers:
  - drivers/clk/x86/clk-pmc-atom.c:plt_clk_probe
  - drivers/clk/x86/clk-pmc-atom.c:plt_clk_probe
  - drivers/clk/x86/clk-pmc-atom.c:plt_clk_probe
```
**Symbols:**

```
ffffffff81633e80-ffffffff81633ebb: plt_clk_free_parent_names_loop (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void plt_clk_free_parent_names_loop(const char **parent_names, unsigned int i);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/x86/clk-pmc-atom.c (ffffffff81655bb0)
Location: drivers/clk/x86/clk-pmc-atom.c:251
Inline: False
Direct callers:
  - drivers/clk/x86/clk-pmc-atom.c:plt_clk_probe
  - drivers/clk/x86/clk-pmc-atom.c:plt_clk_probe
  - drivers/clk/x86/clk-pmc-atom.c:plt_clk_probe
```
**Symbols:**

```
ffffffff81655bb0-ffffffff81655beb: plt_clk_free_parent_names_loop (STB_LOCAL)
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
In drivers/clk/x86/clk-pmc-atom.c (ffffffff81706102)
Location: drivers/clk/x86/clk-pmc-atom.c:251
Inline: True
Inline callers:
  - drivers/clk/x86/clk-pmc-atom.c:plt_clk_probe
  - drivers/clk/x86/clk-pmc-atom.c:plt_clk_probe
  - drivers/clk/x86/clk-pmc-atom.c:plt_clk_register_parents
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
In drivers/clk/x86/clk-pmc-atom.c (ffffffff817233a2)
Location: drivers/clk/x86/clk-pmc-atom.c:251
Inline: True
Inline callers:
  - drivers/clk/x86/clk-pmc-atom.c:plt_clk_probe
  - drivers/clk/x86/clk-pmc-atom.c:plt_clk_probe
  - drivers/clk/x86/clk-pmc-atom.c:plt_clk_register_parents
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
In drivers/clk/x86/clk-pmc-atom.c (ffffffff817045a4)
Location: drivers/clk/x86/clk-pmc-atom.c:251
Inline: True
Inline callers:
  - drivers/clk/x86/clk-pmc-atom.c:plt_clk_probe
  - drivers/clk/x86/clk-pmc-atom.c:plt_clk_probe
  - drivers/clk/x86/clk-pmc-atom.c:plt_clk_register_parents
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
In drivers/clk/x86/clk-pmc-atom.c (ffffffff8177fbd6)
Location: drivers/clk/x86/clk-pmc-atom.c:251
Inline: True
Inline callers:
  - drivers/clk/x86/clk-pmc-atom.c:plt_clk_probe
  - drivers/clk/x86/clk-pmc-atom.c:plt_clk_probe
  - drivers/clk/x86/clk-pmc-atom.c:plt_clk_register_parents
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
In drivers/clk/x86/clk-pmc-atom.c (ffffffff818b6345)
Location: drivers/clk/x86/clk-pmc-atom.c:251
Inline: True
Inline callers:
  - drivers/clk/x86/clk-pmc-atom.c:plt_clk_probe
  - drivers/clk/x86/clk-pmc-atom.c:plt_clk_probe
  - drivers/clk/x86/clk-pmc-atom.c:plt_clk_register_parents
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
In drivers/clk/x86/clk-pmc-atom.c (ffffffff81a03805)
Location: drivers/clk/x86/clk-pmc-atom.c:251
Inline: True
Inline callers:
  - drivers/clk/x86/clk-pmc-atom.c:plt_clk_probe
  - drivers/clk/x86/clk-pmc-atom.c:plt_clk_probe
  - drivers/clk/x86/clk-pmc-atom.c:plt_clk_register_parents
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
In drivers/clk/x86/clk-pmc-atom.c (ffffffff81a4c655)
Location: drivers/clk/x86/clk-pmc-atom.c:251
Inline: True
Inline callers:
  - drivers/clk/x86/clk-pmc-atom.c:plt_clk_probe
  - drivers/clk/x86/clk-pmc-atom.c:plt_clk_probe
  - drivers/clk/x86/clk-pmc-atom.c:plt_clk_register_parents
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
In drivers/clk/x86/clk-pmc-atom.c (ffffffff81a982a5)
Location: drivers/clk/x86/clk-pmc-atom.c:251
Inline: True
Inline callers:
  - drivers/clk/x86/clk-pmc-atom.c:plt_clk_probe
  - drivers/clk/x86/clk-pmc-atom.c:plt_clk_probe
  - drivers/clk/x86/clk-pmc-atom.c:plt_clk_register_parents
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
void plt_clk_free_parent_names_loop(const char **parent_names, unsigned int i);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/x86/clk-pmc-atom.c (ffffffff8161bc10)
Location: drivers/clk/x86/clk-pmc-atom.c:251
Inline: False
Direct callers:
  - drivers/clk/x86/clk-pmc-atom.c:plt_clk_probe
  - drivers/clk/x86/clk-pmc-atom.c:plt_clk_probe
  - drivers/clk/x86/clk-pmc-atom.c:plt_clk_probe
```
**Symbols:**

```
ffffffff8161bc10-ffffffff8161bc4b: plt_clk_free_parent_names_loop (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void plt_clk_free_parent_names_loop(const char **parent_names, unsigned int i);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/x86/clk-pmc-atom.c (ffffffff81610140)
Location: drivers/clk/x86/clk-pmc-atom.c:251
Inline: False
Direct callers:
  - drivers/clk/x86/clk-pmc-atom.c:plt_clk_probe
  - drivers/clk/x86/clk-pmc-atom.c:plt_clk_probe
  - drivers/clk/x86/clk-pmc-atom.c:plt_clk_probe
```
**Symbols:**

```
ffffffff81610140-ffffffff8161017b: plt_clk_free_parent_names_loop (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void plt_clk_free_parent_names_loop(const char **parent_names, unsigned int i);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/x86/clk-pmc-atom.c (ffffffff816499f0)
Location: drivers/clk/x86/clk-pmc-atom.c:251
Inline: False
Direct callers:
  - drivers/clk/x86/clk-pmc-atom.c:plt_clk_probe
  - drivers/clk/x86/clk-pmc-atom.c:plt_clk_probe
  - drivers/clk/x86/clk-pmc-atom.c:plt_clk_probe
```
**Symbols:**

```
ffffffff816499f0-ffffffff81649a2b: plt_clk_free_parent_names_loop (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void plt_clk_free_parent_names_loop(const char **parent_names, unsigned int i);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/clk/x86/clk-pmc-atom.c (ffffffff81663f80)
Location: drivers/clk/x86/clk-pmc-atom.c:251
Inline: False
Direct callers:
  - drivers/clk/x86/clk-pmc-atom.c:plt_clk_probe
  - drivers/clk/x86/clk-pmc-atom.c:plt_clk_probe
  - drivers/clk/x86/clk-pmc-atom.c:plt_clk_probe
```
**Symbols:**

```
ffffffff81663f80-ffffffff81663fbb: plt_clk_free_parent_names_loop (STB_LOCAL)
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
