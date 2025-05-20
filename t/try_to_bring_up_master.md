# Function: <code>try_to_bring_up_master</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/base/component.c (ffffffff81545b30)
Location: drivers/base/component.c:157
Inline: True
Inline callers:
  - drivers/base/component.c:component_master_add_with_match
  - drivers/base/component.c:component_add
Direct callers:
  - drivers/base/component.c:component_master_add_with_match
  - drivers/base/component.c:component_add
```
**Symbols:**

```
ffffffff81545b30-ffffffff81545c10: try_to_bring_up_master.part.2 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
int try_to_bring_up_master(struct master *master, struct component *component);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/component.c (ffffffff81597470)
Location: drivers/base/component.c:140
Inline: True
Direct callers:
  - drivers/base/component.c:component_add
```
**Symbols:**

```
ffffffff81597470-ffffffff815976cc: try_to_bring_up_master (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
int try_to_bring_up_master(struct master *master, struct component *component);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/component.c (ffffffff815c4fc0)
Location: drivers/base/component.c:140
Inline: True
Direct callers:
  - drivers/base/component.c:component_add
```
**Symbols:**

```
ffffffff815c4fc0-ffffffff815c521c: try_to_bring_up_master (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
int try_to_bring_up_master(struct master *master, struct component *component);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/component.c (ffffffff815d9f30)
Location: drivers/base/component.c:140
Inline: True
Direct callers:
  - drivers/base/component.c:component_add
```
**Symbols:**

```
ffffffff815d9f30-ffffffff815da17b: try_to_bring_up_master (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
int try_to_bring_up_master(struct master *master, struct component *component);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/component.c (ffffffff81640ca0)
Location: drivers/base/component.c:140
Inline: True
Direct callers:
  - drivers/base/component.c:component_add
```
**Symbols:**

```
ffffffff81640ca0-ffffffff81640ef4: try_to_bring_up_master (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
int try_to_bring_up_master(struct master *master, struct component *component);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/component.c (ffffffff8167bf90)
Location: drivers/base/component.c:213
Inline: True
Direct callers:
  - drivers/base/component.c:component_add
  - drivers/base/component.c:component_master_add_with_match
```
**Symbols:**

```
ffffffff8167bf90-ffffffff8167c206: try_to_bring_up_master (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
int try_to_bring_up_master(struct master *master, struct component *component);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/component.c (ffffffff8169b550)
Location: drivers/base/component.c:203
Inline: False
Direct callers:
  - drivers/base/component.c:component_add
  - drivers/base/component.c:component_master_add_with_match
```
**Symbols:**

```
ffffffff8169b550-ffffffff8169b7c6: try_to_bring_up_master (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
int try_to_bring_up_master(struct master *master, struct component *component);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/component.c (ffffffff816d3ff0)
Location: drivers/base/component.c:235
Inline: False
Direct callers:
  - drivers/base/component.c:__component_add
  - drivers/base/component.c:component_master_add_with_match
```
**Symbols:**

```
ffffffff816d3ff0-ffffffff816d4283: try_to_bring_up_master (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
int try_to_bring_up_master(struct master *master, struct component *component);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/component.c (ffffffff816f7eb0)
Location: drivers/base/component.c:235
Inline: False
Direct callers:
  - drivers/base/component.c:__component_add
  - drivers/base/component.c:component_master_add_with_match
```
**Symbols:**

```
ffffffff816f7eb0-ffffffff816f8143: try_to_bring_up_master (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int try_to_bring_up_master(struct master *master, struct component *component);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/component.c (0)
Location: drivers/base/component.c:234
Inline: False
Direct callers:
  - drivers/base/component.c:__component_add
  - drivers/base/component.c:component_master_add_with_match
```
**Symbols:**

```
ffffffff817b0c90-ffffffff817b0dbe: try_to_bring_up_master (STB_LOCAL)
ffffffff817b17ea-ffffffff817b1802: try_to_bring_up_master.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int try_to_bring_up_master(struct master *master, struct component *component);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/component.c (0)
Location: drivers/base/component.c:234
Inline: False
Direct callers:
  - drivers/base/component.c:__component_add
  - drivers/base/component.c:component_master_add_with_match
```
**Symbols:**

```
ffffffff817c55e0-ffffffff817c570e: try_to_bring_up_master (STB_LOCAL)
ffffffff81c0db46-ffffffff81c0db5e: try_to_bring_up_master.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int try_to_bring_up_master(struct master *master, struct component *component);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/component.c (0)
Location: drivers/base/component.c:231
Inline: False
Direct callers:
  - drivers/base/component.c:__component_add
  - drivers/base/component.c:component_master_add_with_match
```
**Symbols:**

```
ffffffff817a8930-ffffffff817a8a5e: try_to_bring_up_master (STB_LOCAL)
ffffffff81bffee0-ffffffff81bffef8: try_to_bring_up_master.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int try_to_bring_up_master(struct master *master, struct component *component);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/base/component.c (0)
Location: drivers/base/component.c:231
Inline: False
Direct callers:
  - drivers/base/component.c:__component_add
  - drivers/base/component.c:component_master_add_with_match
```
**Symbols:**

```
ffffffff818318b0-ffffffff818319de: try_to_bring_up_master (STB_LOCAL)
ffffffff81d0237c-ffffffff81d02394: try_to_bring_up_master.cold (STB_LOCAL)
```
</details>
</li>
<li>
In <code>5.19</code>: Absent ⚠️
</li>
<li>
In <code>6.2</code>: Absent ⚠️
</li>
<li>
In <code>6.5</code>: Absent ⚠️
</li>
<li>
In <code>6.8</code>: Absent ⚠️
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
int try_to_bring_up_master(struct master *master, struct component *component);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/component.c (ffff8000108e1a48)
Location: drivers/base/component.c:235
Inline: False
Direct callers:
  - drivers/base/component.c:__component_add
  - drivers/base/component.c:component_master_add_with_match
```
**Symbols:**

```
ffff8000108e1a48-ffff8000108e1d40: try_to_bring_up_master (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
int try_to_bring_up_master(struct master *master, struct component *component);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/component.c (c09d0ef4)
Location: drivers/base/component.c:235
Inline: True
Direct callers:
  - drivers/base/component.c:__component_add
  - drivers/base/component.c:component_master_add_with_match
```
**Symbols:**

```
c09d0ef4-c09d11d8: try_to_bring_up_master (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
int try_to_bring_up_master(struct master *master, struct component *component);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/component.c (c000000000976830)
Location: drivers/base/component.c:235
Inline: True
Direct callers:
  - drivers/base/component.c:__component_add
  - drivers/base/component.c:component_master_add_with_match
```
**Symbols:**

```
c000000000976830-c000000000976c2c: try_to_bring_up_master (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
int try_to_bring_up_master(struct master *master, struct component *component);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/base/component.c (ffffffe000577666)
Location: drivers/base/component.c:235
Inline: True
Direct callers:
  - drivers/base/component.c:__component_add
  - drivers/base/component.c:component_master_add_with_match
```
**Symbols:**

```
ffffffe000577666-ffffffe0005778b6: try_to_bring_up_master (STB_LOCAL)
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
int try_to_bring_up_master(struct master *master, struct component *component);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/component.c (ffffffff816bd6a0)
Location: drivers/base/component.c:235
Inline: False
Direct callers:
  - drivers/base/component.c:__component_add
  - drivers/base/component.c:component_master_add_with_match
```
**Symbols:**

```
ffffffff816bd6a0-ffffffff816bd933: try_to_bring_up_master (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
int try_to_bring_up_master(struct master *master, struct component *component);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/component.c (ffffffff81698950)
Location: drivers/base/component.c:235
Inline: False
Direct callers:
  - drivers/base/component.c:__component_add
  - drivers/base/component.c:component_master_add_with_match
```
**Symbols:**

```
ffffffff81698950-ffffffff81698be3: try_to_bring_up_master (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
int try_to_bring_up_master(struct master *master, struct component *component);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/component.c (ffffffff816ebb70)
Location: drivers/base/component.c:235
Inline: False
Direct callers:
  - drivers/base/component.c:__component_add
  - drivers/base/component.c:component_master_add_with_match
```
**Symbols:**

```
ffffffff816ebb70-ffffffff816ebe03: try_to_bring_up_master (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
int try_to_bring_up_master(struct master *master, struct component *component);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/component.c (ffffffff817063b0)
Location: drivers/base/component.c:235
Inline: False
Direct callers:
  - drivers/base/component.c:__component_add
  - drivers/base/component.c:component_master_add_with_match
```
**Symbols:**

```
ffffffff817063b0-ffffffff81706643: try_to_bring_up_master (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
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
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
<li>
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
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
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
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
