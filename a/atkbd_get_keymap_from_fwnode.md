# Function: <code>atkbd_get_keymap_from_fwnode</code>

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
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int atkbd_get_keymap_from_fwnode(struct atkbd *atkbd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/input/keyboard/atkbd.c (0)
Location: drivers/input/keyboard/atkbd.c:1038
Inline: False
Direct callers:
  - drivers/input/keyboard/atkbd.c:atkbd_set_keycode_table
```
**Symbols:**

```
ffffffff81932140-ffffffff81932240: atkbd_get_keymap_from_fwnode (STB_LOCAL)
ffffffff81933dd0-ffffffff81933df2: atkbd_get_keymap_from_fwnode.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int atkbd_get_keymap_from_fwnode(struct atkbd *atkbd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/input/keyboard/atkbd.c (0)
Location: drivers/input/keyboard/atkbd.c:1038
Inline: False
Direct callers:
  - drivers/input/keyboard/atkbd.c:atkbd_set_keycode_table
```
**Symbols:**

```
ffffffff819393a0-ffffffff819394a0: atkbd_get_keymap_from_fwnode (STB_LOCAL)
ffffffff81c235b3-ffffffff81c235d5: atkbd_get_keymap_from_fwnode.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int atkbd_get_keymap_from_fwnode(struct atkbd *atkbd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/input/keyboard/atkbd.c (0)
Location: drivers/input/keyboard/atkbd.c:1038
Inline: False
Direct callers:
  - drivers/input/keyboard/atkbd.c:atkbd_set_keycode_table
```
**Symbols:**

```
ffffffff8191cac0-ffffffff8191cbc0: atkbd_get_keymap_from_fwnode (STB_LOCAL)
ffffffff81c15689-ffffffff81c156ab: atkbd_get_keymap_from_fwnode.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int atkbd_get_keymap_from_fwnode(struct atkbd *atkbd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/input/keyboard/atkbd.c (0)
Location: drivers/input/keyboard/atkbd.c:1038
Inline: False
Direct callers:
  - drivers/input/keyboard/atkbd.c:atkbd_set_keycode_table
```
**Symbols:**

```
ffffffff819bf4a0-ffffffff819bf5e2: atkbd_get_keymap_from_fwnode (STB_LOCAL)
ffffffff81d23b9e-ffffffff81d23bc5: atkbd_get_keymap_from_fwnode.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int atkbd_get_keymap_from_fwnode(struct atkbd *atkbd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/input/keyboard/atkbd.c (0)
Location: drivers/input/keyboard/atkbd.c:1026
Inline: False
Direct callers:
  - drivers/input/keyboard/atkbd.c:atkbd_set_keycode_table
```
**Symbols:**

```
ffffffff81b1f680-ffffffff81b1f7ce: atkbd_get_keymap_from_fwnode (STB_LOCAL)
ffffffff81eef9ae-ffffffff81eef9d5: atkbd_get_keymap_from_fwnode.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int atkbd_get_keymap_from_fwnode(struct atkbd *atkbd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/input/keyboard/atkbd.c (ffffffff81cb18a0)
Location: drivers/input/keyboard/atkbd.c:1026
Inline: False
Direct callers:
  - drivers/input/keyboard/atkbd.c:atkbd_set_keycode_table
```
**Symbols:**

```
ffffffff81cb18a0-ffffffff81cb1a11: atkbd_get_keymap_from_fwnode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int atkbd_get_keymap_from_fwnode(struct atkbd *atkbd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/input/keyboard/atkbd.c (ffffffff81d18f10)
Location: drivers/input/keyboard/atkbd.c:1045
Inline: False
Direct callers:
  - drivers/input/keyboard/atkbd.c:atkbd_set_keycode_table
```
**Symbols:**

```
ffffffff81d18f10-ffffffff81d19081: atkbd_get_keymap_from_fwnode (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int atkbd_get_keymap_from_fwnode(struct atkbd *atkbd);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/input/keyboard/atkbd.c (ffffffff81dcec30)
Location: drivers/input/keyboard/atkbd.c:1089
Inline: False
Direct callers:
  - drivers/input/keyboard/atkbd.c:atkbd_set_keycode_table
```
**Symbols:**

```
ffffffff81dcec30-ffffffff81dceda1: atkbd_get_keymap_from_fwnode (STB_LOCAL)
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
