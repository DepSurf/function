# Function: <code>mod_tree_remove</code>

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
In kernel/module.c (ffffffff81107794)
Location: kernel/module.c:190
Inline: True
Inline callers:
  - kernel/module.c:free_module
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
In kernel/module.c (ffffffff81110b61)
Location: kernel/module.c:192
Inline: True
Inline callers:
  - kernel/module.c:load_module
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
In kernel/module.c (ffffffff811183c0)
Location: kernel/module.c:192
Inline: True
Inline callers:
  - kernel/module.c:load_module
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
In kernel/module.c (ffffffff811197f5)
Location: kernel/module.c:195
Inline: True
Inline callers:
  - kernel/module.c:load_module
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
In kernel/module.c (ffffffff81124da6)
Location: kernel/module.c:195
Inline: True
Inline callers:
  - kernel/module.c:load_module
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
In kernel/module.c (ffffffff811333a6)
Location: kernel/module.c:196
Inline: True
Inline callers:
  - kernel/module.c:load_module
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
In kernel/module.c (ffffffff8113ed53)
Location: kernel/module.c:196
Inline: True
Inline callers:
  - kernel/module.c:load_module
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
In kernel/module.c (ffffffff8114a0b0)
Location: kernel/module.c:187
Inline: True
Inline callers:
  - kernel/module.c:load_module
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
In kernel/module.c (ffffffff81155d1a)
Location: kernel/module.c:188
Inline: True
Inline callers:
  - kernel/module.c:load_module
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
In kernel/module.c (ffffffff81166f36)
Location: kernel/module.c:191
Inline: True
Inline callers:
  - kernel/module.c:load_module
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
In kernel/module.c (ffffffff811635e6)
Location: kernel/module.c:193
Inline: True
Inline callers:
  - kernel/module.c:load_module
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
In kernel/module.c (ffffffff811641ae)
Location: kernel/module.c:192
Inline: True
Inline callers:
  - kernel/module.c:load_module
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
In kernel/module.c (ffffffff811898bc)
Location: kernel/module.c:193
Inline: True
Inline callers:
  - kernel/module.c:load_module
  - kernel/module.c:free_module
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void mod_tree_remove(struct module *mod);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/module/tree_lookup.c (ffffffff81190dd0)
Location: kernel/module/tree_lookup.c:99
Inline: False
Direct callers:
  - kernel/module/main.c:load_module
  - kernel/module/main.c:free_module
```
**Symbols:**

```
ffffffff81190dd0-ffffffff81190e6f: mod_tree_remove (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void mod_tree_remove(struct module *mod);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/module/tree_lookup.c (ffffffff811ce3c0)
Location: kernel/module/tree_lookup.c:99
Inline: False
Direct callers:
  - kernel/module/main.c:load_module
  - kernel/module/main.c:free_module
```
**Symbols:**

```
ffffffff811ce3c0-ffffffff811ce45f: mod_tree_remove (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void mod_tree_remove(struct module *mod);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/module/tree_lookup.c (ffffffff811e2540)
Location: kernel/module/tree_lookup.c:95
Inline: False
Direct callers:
  - kernel/module/main.c:load_module
  - kernel/module/main.c:free_module
```
**Symbols:**

```
ffffffff811e2540-ffffffff811e25ea: mod_tree_remove (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void mod_tree_remove(struct module *mod);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/module/tree_lookup.c (ffffffff811f82d0)
Location: kernel/module/tree_lookup.c:95
Inline: False
Direct callers:
  - kernel/module/main.c:load_module
  - kernel/module/main.c:free_module
```
**Symbols:**

```
ffffffff811f82d0-ffffffff811f837a: mod_tree_remove (STB_GLOBAL)
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
In kernel/module.c (ffff8000101c4f18)
Location: kernel/module.c:188
Inline: True
Inline callers:
  - kernel/module.c:load_module
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
In kernel/module.c (c040bf28)
Location: kernel/module.c:188
Inline: True
Inline callers:
  - kernel/module.c:load_module
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
In kernel/module.c (c00000000022c8e8)
Location: kernel/module.c:188
Inline: True
Inline callers:
  - kernel/module.c:load_module
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
In kernel/module.c (ffffffe000145860)
Location: kernel/module.c:188
Inline: True
Inline callers:
  - kernel/module.c:load_module
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
In kernel/module.c (ffffffff8114e33a)
Location: kernel/module.c:188
Inline: True
Inline callers:
  - kernel/module.c:load_module
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
In kernel/module.c (ffffffff811415ea)
Location: kernel/module.c:188
Inline: True
Inline callers:
  - kernel/module.c:load_module
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
In kernel/module.c (ffffffff8114c1ea)
Location: kernel/module.c:188
Inline: True
Inline callers:
  - kernel/module.c:load_module
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
In kernel/module.c (ffffffff81158ed0)
Location: kernel/module.c:188
Inline: True
Inline callers:
  - kernel/module.c:load_module
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
