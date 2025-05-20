# Function: <code>rcu_init_geometry</code>

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
In kernel/rcu/tree.c (ffffffff81f7f689)
Location: kernel/rcu/tree.c:4475
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_init
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
In kernel/rcu/tree.c (ffffffff81fa8751)
Location: kernel/rcu/tree.c:4095
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_init
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
In kernel/rcu/tree.c (ffffffff81fe45c3)
Location: kernel/rcu/tree.c:4121
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_init
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
In kernel/rcu/tree.c (ffffffff820c525f)
Location: kernel/rcu/tree.c:4114
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_init
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
In kernel/rcu/tree.c (ffffffff826cd916)
Location: kernel/rcu/tree.c:4179
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_init
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
In kernel/rcu/tree.c (ffffffff826f7a82)
Location: kernel/rcu/tree.c:3977
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_init
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
In kernel/rcu/tree.c (ffffffff828ae6ae)
Location: kernel/rcu/tree.c:3677
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_init
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
In kernel/rcu/tree.c (ffffffff828c7162)
Location: kernel/rcu/tree.c:3358
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_init
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
In kernel/rcu/tree.c (ffffffff828cf770)
Location: kernel/rcu/tree.c:3422
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_init
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void rcu_init_geometry();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff82cf0ab0)
Location: kernel/rcu/tree.c:4148
Inline: False
Direct callers:
  - kernel/rcu/tree.c:rcu_init
```
**Symbols:**

```
ffffffff82cf0ab0-ffffffff82cf0be6: rcu_init_geometry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void rcu_init_geometry();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/rcu/tree.c (ffffffff82fdd48c)
Location: kernel/rcu/tree.c:4469
Inline: False
Direct callers:
  - kernel/rcu/tree.c:rcu_init
```
**Symbols:**

```
ffffffff82fdd48c-ffffffff82fdd5c2: rcu_init_geometry (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
void rcu_init_geometry();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/rcu/tree.c (0)
Location: kernel/rcu/tree.c:4585
Inline: False
Direct callers:
  - kernel/rcu/srcutree.c:init_srcu_struct_nodes
  - kernel/rcu/tree.c:rcu_init
```
**Symbols:**

```
ffffffff81bd4cbb-ffffffff81bd4d85: rcu_init_geometry.cold (STB_LOCAL)
ffffffff81134b70-ffffffff81134c44: rcu_init_geometry (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
void rcu_init_geometry();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/rcu/tree.c (0)
Location: kernel/rcu/tree.c:4556
Inline: False
Direct callers:
  - kernel/rcu/srcutree.c:init_srcu_struct_nodes
  - kernel/rcu/tree.c:rcu_init
```
**Symbols:**

```
ffffffff81caf640-ffffffff81caf795: rcu_init_geometry.cold (STB_LOCAL)
ffffffff81157320-ffffffff81157416: rcu_init_geometry (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
void rcu_init_geometry();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/rcu/tree.c (0)
Location: kernel/rcu/tree.c:4745
Inline: False
Direct callers:
  - kernel/rcu/srcutree.c:init_srcu_struct_nodes
  - kernel/rcu/tree.c:rcu_init
```
**Symbols:**

```
ffffffff81e602e4-ffffffff81e60440: rcu_init_geometry.cold (STB_LOCAL)
ffffffff81180460-ffffffff81180577: rcu_init_geometry (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
void rcu_init_geometry();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/rcu/tree.c (0)
Location: kernel/rcu/tree.c:4653
Inline: False
Direct callers:
  - kernel/rcu/srcutree.c:init_srcu_struct_nodes
  - kernel/rcu/tree.c:rcu_init
```
**Symbols:**

```
ffffffff8205a384-ffffffff8205a398: rcu_init_geometry.cold (STB_LOCAL)
ffffffff811baa10-ffffffff811bacaf: rcu_init_geometry (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
void rcu_init_geometry();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/rcu/tree.c (0)
Location: kernel/rcu/tree.c:4813
Inline: False
Direct callers:
  - kernel/rcu/srcutree.c:init_srcu_struct_nodes
  - kernel/rcu/tree.c:rcu_init
```
**Symbols:**

```
ffffffff820d8bb2-ffffffff820d8bc6: rcu_init_geometry.cold (STB_LOCAL)
ffffffff811cd350-ffffffff811cd5ef: rcu_init_geometry (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
void rcu_init_geometry();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/rcu/tree.c (0)
Location: kernel/rcu/tree.c:4968
Inline: False
Direct callers:
  - kernel/rcu/srcutree.c:init_srcu_struct_nodes
  - kernel/rcu/tree.c:rcu_init
```
**Symbols:**

```
ffffffff821b42eb-ffffffff821b42ff: rcu_init_geometry.cold (STB_LOCAL)
ffffffff811e1fc0-ffffffff811e225f: rcu_init_geometry (STB_GLOBAL)
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
In kernel/rcu/tree.c (ffff800011446f4c)
Location: kernel/rcu/tree.c:3422
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_init
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
In kernel/rcu/tree.c (c152160c)
Location: kernel/rcu/tree.c:3422
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_init
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
In kernel/rcu/tree.c (c00000000136c018)
Location: kernel/rcu/tree.c:3422
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_init
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
In kernel/rcu/tree.c (ffffffe0000089fc)
Location: kernel/rcu/tree.c:3422
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_init
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
In kernel/rcu/tree.c (ffffffff828b8468)
Location: kernel/rcu/tree.c:3422
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_init
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
In kernel/rcu/tree.c (ffffffff828b079e)
Location: kernel/rcu/tree.c:3422
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_init
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
In kernel/rcu/tree.c (ffffffff828cb3a4)
Location: kernel/rcu/tree.c:3422
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_init
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
In kernel/rcu/tree.c (ffffffff828d079d)
Location: kernel/rcu/tree.c:3422
Inline: True
Inline callers:
  - kernel/rcu/tree.c:rcu_init
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
