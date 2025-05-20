# Function: <code>find_components</code>

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
In drivers/base/component.c (ffffffff81545b45)
Location: drivers/base/component.c:109
Inline: True
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
In drivers/base/component.c (ffffffff81597492)
Location: drivers/base/component.c:87
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
In drivers/base/component.c (ffffffff815c4fe2)
Location: drivers/base/component.c:87
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
In drivers/base/component.c (ffffffff815d9f52)
Location: drivers/base/component.c:87
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
In drivers/base/component.c (ffffffff81640cc2)
Location: drivers/base/component.c:87
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
In drivers/base/component.c (ffffffff8167bfb2)
Location: drivers/base/component.c:160
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
In drivers/base/component.c (ffffffff8169b572)
Location: drivers/base/component.c:150
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
In drivers/base/component.c (ffffffff816d4012)
Location: drivers/base/component.c:182
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
In drivers/base/component.c (ffffffff816f7ed2)
Location: drivers/base/component.c:182
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
int find_components(struct master *master);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/component.c (ffffffff817b0b20)
Location: drivers/base/component.c:181
Inline: False
Direct callers:
  - drivers/base/component.c:try_to_bring_up_master
  - drivers/base/component.c:try_to_bring_up_master
```
**Symbols:**

```
ffffffff817b0b20-ffffffff817b0c29: find_components (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int find_components(struct master *master);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/component.c (ffffffff817c5470)
Location: drivers/base/component.c:181
Inline: False
Direct callers:
  - drivers/base/component.c:try_to_bring_up_master
  - drivers/base/component.c:try_to_bring_up_master
```
**Symbols:**

```
ffffffff817c5470-ffffffff817c5579: find_components (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int find_components(struct master *master);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/component.c (ffffffff817a8750)
Location: drivers/base/component.c:178
Inline: False
Direct callers:
  - drivers/base/component.c:try_to_bring_up_master
  - drivers/base/component.c:try_to_bring_up_master
```
**Symbols:**

```
ffffffff817a8750-ffffffff817a88cf: find_components (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int find_components(struct master *master);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/component.c (ffffffff81831730)
Location: drivers/base/component.c:178
Inline: False
Direct callers:
  - drivers/base/component.c:try_to_bring_up_master
  - drivers/base/component.c:try_to_bring_up_master
```
**Symbols:**

```
ffffffff81831730-ffffffff818318ac: find_components (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int find_components(struct aggregate_device *adev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/component.c (ffffffff81972d30)
Location: drivers/base/component.c:173
Inline: False
Direct callers:
  - drivers/base/component.c:try_to_bring_up_aggregate_device
  - drivers/base/component.c:try_to_bring_up_aggregate_device
```
**Symbols:**

```
ffffffff81972d30-ffffffff81972ecf: find_components (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int find_components(struct aggregate_device *adev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/component.c (ffffffff81ade0d0)
Location: drivers/base/component.c:173
Inline: False
Direct callers:
  - drivers/base/component.c:try_to_bring_up_aggregate_device
  - drivers/base/component.c:try_to_bring_up_aggregate_device
```
**Symbols:**

```
ffffffff81ade0d0-ffffffff81ade26f: find_components (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int find_components(struct aggregate_device *adev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/component.c (ffffffff81b2c340)
Location: drivers/base/component.c:173
Inline: False
Direct callers:
  - drivers/base/component.c:try_to_bring_up_aggregate_device
  - drivers/base/component.c:try_to_bring_up_aggregate_device
```
**Symbols:**

```
ffffffff81b2c340-ffffffff81b2c4dc: find_components (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int find_components(struct aggregate_device *adev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/component.c (ffffffff81b83ae0)
Location: drivers/base/component.c:173
Inline: False
Direct callers:
  - drivers/base/component.c:try_to_bring_up_aggregate_device
  - drivers/base/component.c:try_to_bring_up_aggregate_device
```
**Symbols:**

```
ffffffff81b83ae0-ffffffff81b83c7c: find_components (STB_LOCAL)
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
In drivers/base/component.c (ffff8000108e1a70)
Location: drivers/base/component.c:182
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
In drivers/base/component.c (c09d0f28)
Location: drivers/base/component.c:182
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
In drivers/base/component.c (c00000000097686c)
Location: drivers/base/component.c:182
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
In drivers/base/component.c (ffffffe0005776a6)
Location: drivers/base/component.c:182
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
In drivers/base/component.c (ffffffff816bd6c2)
Location: drivers/base/component.c:182
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
In drivers/base/component.c (ffffffff81698972)
Location: drivers/base/component.c:182
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
In drivers/base/component.c (ffffffff816ebb92)
Location: drivers/base/component.c:182
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
In drivers/base/component.c (ffffffff817063d2)
Location: drivers/base/component.c:182
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
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.15</code> and <code>5.19</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct aggregate_device *adev</code>
</li>
<li>
<b>Param removed. </b>
<code>struct master *master</code>
</li>
</ul>
</details>
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
