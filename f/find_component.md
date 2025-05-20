# Function: <code>find_component</code>

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
In drivers/base/component.c (ffffffff815974e1)
Location: drivers/base/component.c:71
Inline: True
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
In drivers/base/component.c (ffffffff815c5031)
Location: drivers/base/component.c:71
Inline: True
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
In drivers/base/component.c (ffffffff815d9fa0)
Location: drivers/base/component.c:71
Inline: True
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
In drivers/base/component.c (ffffffff81640d10)
Location: drivers/base/component.c:71
Inline: True
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
In drivers/base/component.c (ffffffff8167bffe)
Location: drivers/base/component.c:144
Inline: True
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
In drivers/base/component.c (ffffffff8169b5be)
Location: drivers/base/component.c:134
Inline: True
Inline callers:
  - drivers/base/component.c:try_to_bring_up_master
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
In drivers/base/component.c (ffffffff816d4054)
Location: drivers/base/component.c:162
Inline: True
Inline callers:
  - drivers/base/component.c:try_to_bring_up_master
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
In drivers/base/component.c (ffffffff816f7f14)
Location: drivers/base/component.c:162
Inline: True
Inline callers:
  - drivers/base/component.c:try_to_bring_up_master
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
struct component *find_component(struct master *master, struct component_match_array *mc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/component.c (ffffffff817b0880)
Location: drivers/base/component.c:161
Inline: False
Direct callers:
  - drivers/base/component.c:find_components
```
**Symbols:**

```
ffffffff817b0880-ffffffff817b0912: find_component (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
struct component *find_component(struct master *master, struct component_match_array *mc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/component.c (ffffffff817c51f0)
Location: drivers/base/component.c:161
Inline: False
Direct callers:
  - drivers/base/component.c:find_components
```
**Symbols:**

```
ffffffff817c51f0-ffffffff817c5282: find_component (STB_LOCAL)
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
In drivers/base/component.c (ffffffff817a87a9)
Location: drivers/base/component.c:158
Inline: True
Inline callers:
  - drivers/base/component.c:find_components
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
In drivers/base/component.c (ffffffff81831789)
Location: drivers/base/component.c:158
Inline: True
Inline callers:
  - drivers/base/component.c:find_components
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
In drivers/base/component.c (ffffffff81972d89)
Location: drivers/base/component.c:153
Inline: True
Inline callers:
  - drivers/base/component.c:find_components
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
In drivers/base/component.c (ffffffff81ade129)
Location: drivers/base/component.c:153
Inline: True
Inline callers:
  - drivers/base/component.c:find_components
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
In drivers/base/component.c (ffffffff81b2c399)
Location: drivers/base/component.c:153
Inline: True
Inline callers:
  - drivers/base/component.c:find_components
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
In drivers/base/component.c (ffffffff81b83b39)
Location: drivers/base/component.c:153
Inline: True
Inline callers:
  - drivers/base/component.c:find_components
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
In drivers/base/component.c (ffff8000108e1acc)
Location: drivers/base/component.c:162
Inline: True
Inline callers:
  - drivers/base/component.c:try_to_bring_up_master
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
In drivers/base/component.c (c09d0fa0)
Location: drivers/base/component.c:162
Inline: True
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
In drivers/base/component.c (c0000000009768d0)
Location: drivers/base/component.c:162
Inline: True
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
In drivers/base/component.c (ffffffe0005776c4)
Location: drivers/base/component.c:162
Inline: True
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
In drivers/base/component.c (ffffffff816bd704)
Location: drivers/base/component.c:162
Inline: True
Inline callers:
  - drivers/base/component.c:try_to_bring_up_master
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
In drivers/base/component.c (ffffffff816989b4)
Location: drivers/base/component.c:162
Inline: True
Inline callers:
  - drivers/base/component.c:try_to_bring_up_master
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
In drivers/base/component.c (ffffffff816ebbd4)
Location: drivers/base/component.c:162
Inline: True
Inline callers:
  - drivers/base/component.c:try_to_bring_up_master
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
In drivers/base/component.c (ffffffff81706414)
Location: drivers/base/component.c:162
Inline: True
Inline callers:
  - drivers/base/component.c:try_to_bring_up_master
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
</ul>
