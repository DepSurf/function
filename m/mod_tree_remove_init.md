# Function: <code>mod_tree_remove_init</code>

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
In kernel/module.c (ffffffff811077b7)
Location: kernel/module.c:184
Inline: True
Inline callers:
  - kernel/module.c:free_module
  - kernel/module.c:do_init_module
  - kernel/module.c:load_module
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
In kernel/module.c (ffffffff81110b82)
Location: kernel/module.c:186
Inline: True
Inline callers:
  - kernel/module.c:load_module
  - kernel/module.c:do_init_module
  - kernel/module.c:free_module
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
In kernel/module.c (ffffffff811183e1)
Location: kernel/module.c:186
Inline: True
Inline callers:
  - kernel/module.c:load_module
  - kernel/module.c:do_init_module
  - kernel/module.c:free_module
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
In kernel/module.c (ffffffff81119818)
Location: kernel/module.c:189
Inline: True
Inline callers:
  - kernel/module.c:load_module
  - kernel/module.c:do_init_module
  - kernel/module.c:free_module
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
In kernel/module.c (ffffffff81124dc9)
Location: kernel/module.c:189
Inline: True
Inline callers:
  - kernel/module.c:load_module
  - kernel/module.c:do_init_module
  - kernel/module.c:free_module
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
In kernel/module.c (ffffffff811333ab)
Location: kernel/module.c:190
Inline: True
Inline callers:
  - kernel/module.c:load_module
  - kernel/module.c:do_init_module
  - kernel/module.c:free_module
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
In kernel/module.c (ffffffff8113ed58)
Location: kernel/module.c:190
Inline: True
Inline callers:
  - kernel/module.c:load_module
  - kernel/module.c:do_init_module
  - kernel/module.c:free_module
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
In kernel/module.c (ffffffff8114a0b5)
Location: kernel/module.c:181
Inline: True
Inline callers:
  - kernel/module.c:load_module
  - kernel/module.c:do_init_module
  - kernel/module.c:free_module
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
In kernel/module.c (ffffffff81155d1f)
Location: kernel/module.c:182
Inline: True
Inline callers:
  - kernel/module.c:load_module
  - kernel/module.c:do_init_module
  - kernel/module.c:free_module
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
In kernel/module.c (ffffffff81166f6a)
Location: kernel/module.c:185
Inline: True
Inline callers:
  - kernel/module.c:load_module
  - kernel/module.c:do_init_module
  - kernel/module.c:free_module
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
In kernel/module.c (ffffffff8116361a)
Location: kernel/module.c:187
Inline: True
Inline callers:
  - kernel/module.c:load_module
  - kernel/module.c:do_init_module
  - kernel/module.c:free_module
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
In kernel/module.c (ffffffff811641e2)
Location: kernel/module.c:186
Inline: True
Inline callers:
  - kernel/module.c:load_module
  - kernel/module.c:do_init_module
  - kernel/module.c:free_module
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
In kernel/module.c (ffffffff811898f0)
Location: kernel/module.c:187
Inline: True
Inline callers:
  - kernel/module.c:load_module
  - kernel/module.c:do_init_module
  - kernel/module.c:free_module
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void mod_tree_remove_init(struct module *mod);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/module/tree_lookup.c (ffffffff81190e11)
Location: kernel/module/tree_lookup.c:93
Inline: True
Inline callers:
  - kernel/module/tree_lookup.c:mod_tree_remove
  - kernel/module/tree_lookup.c:mod_tree_remove
Direct callers:
  - kernel/module/main.c:do_init_module
```
**Symbols:**

```
ffffffff81190d60-ffffffff81190dc6: mod_tree_remove_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void mod_tree_remove_init(struct module *mod);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/module/tree_lookup.c (ffffffff811ce401)
Location: kernel/module/tree_lookup.c:93
Inline: True
Inline callers:
  - kernel/module/tree_lookup.c:mod_tree_remove
  - kernel/module/tree_lookup.c:mod_tree_remove
Direct callers:
  - kernel/module/main.c:do_init_module
```
**Symbols:**

```
ffffffff811ce340-ffffffff811ce3a6: mod_tree_remove_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void mod_tree_remove_init(struct module *mod);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/module/tree_lookup.c (ffffffff811e24a0)
Location: kernel/module/tree_lookup.c:87
Inline: False
Direct callers:
  - kernel/module/main.c:do_init_module
```
**Symbols:**

```
ffffffff811e24a0-ffffffff811e2524: mod_tree_remove_init (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void mod_tree_remove_init(struct module *mod);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/module/tree_lookup.c (ffffffff811f8230)
Location: kernel/module/tree_lookup.c:87
Inline: False
Direct callers:
  - kernel/module/main.c:do_init_module
```
**Symbols:**

```
ffffffff811f8230-ffffffff811f82b4: mod_tree_remove_init (STB_GLOBAL)
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
In kernel/module.c (ffff8000101c4f1c)
Location: kernel/module.c:182
Inline: True
Inline callers:
  - kernel/module.c:load_module
  - kernel/module.c:do_init_module
  - kernel/module.c:free_module
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
In kernel/module.c (c040bf2c)
Location: kernel/module.c:182
Inline: True
Inline callers:
  - kernel/module.c:load_module
  - kernel/module.c:do_init_module
  - kernel/module.c:free_module
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/module.c (c00000000022c8ec)
Location: kernel/module.c:182
Inline: True
Inline callers:
  - kernel/module.c:load_module
  - kernel/module.c:do_init_module
  - kernel/module.c:free_module
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/module.c (ffffffe000145876)
Location: kernel/module.c:182
Inline: True
Inline callers:
  - kernel/module.c:load_module
  - kernel/module.c:do_init_module
  - kernel/module.c:free_module
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
In kernel/module.c (ffffffff8114e33f)
Location: kernel/module.c:182
Inline: True
Inline callers:
  - kernel/module.c:load_module
  - kernel/module.c:do_init_module
  - kernel/module.c:free_module
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
In kernel/module.c (ffffffff811415ef)
Location: kernel/module.c:182
Inline: True
Inline callers:
  - kernel/module.c:load_module
  - kernel/module.c:do_init_module
  - kernel/module.c:free_module
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
In kernel/module.c (ffffffff8114c1ef)
Location: kernel/module.c:182
Inline: True
Inline callers:
  - kernel/module.c:load_module
  - kernel/module.c:do_init_module
  - kernel/module.c:free_module
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
In kernel/module.c (ffffffff81158ed5)
Location: kernel/module.c:182
Inline: True
Inline callers:
  - kernel/module.c:load_module
  - kernel/module.c:do_init_module
  - kernel/module.c:free_module
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
