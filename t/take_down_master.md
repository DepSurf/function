# Function: <code>take_down_master</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: ✅</summary>

```c
void take_down_master(struct master *master);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/component.c (ffffffff81545980)
Location: drivers/base/component.c:216
Inline: False
Direct callers:
  - drivers/base/component.c:component_master_del
  - drivers/base/component.c:component_del
```
**Symbols:**

```
ffffffff81545980-ffffffff815459b8: take_down_master (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/base/component.c (ffffffff815973c8)
Location: drivers/base/component.c:189
Inline: True
Inline callers:
  - drivers/base/component.c:component_del
  - drivers/base/component.c:component_master_del
Direct callers:
  - drivers/base/component.c:component_del
  - drivers/base/component.c:component_master_del
```
**Symbols:**

```
ffffffff81597290-ffffffff815972ba: take_down_master.part.5 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/base/component.c (ffffffff815c4f18)
Location: drivers/base/component.c:189
Inline: True
Inline callers:
  - drivers/base/component.c:component_del
  - drivers/base/component.c:component_master_del
Direct callers:
  - drivers/base/component.c:component_del
  - drivers/base/component.c:component_master_del
```
**Symbols:**

```
ffffffff815c4de0-ffffffff815c4e0a: take_down_master.part.7 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void take_down_master(struct master *master);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/component.c (ffffffff815d9c00)
Location: drivers/base/component.c:189
Inline: False
Direct callers:
  - drivers/base/component.c:component_del
  - drivers/base/component.c:component_master_del
```
**Symbols:**

```
ffffffff815d9c00-ffffffff815d9c32: take_down_master (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void take_down_master(struct master *master);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/component.c (ffffffff81640970)
Location: drivers/base/component.c:189
Inline: False
Direct callers:
  - drivers/base/component.c:component_del
  - drivers/base/component.c:component_master_del
```
**Symbols:**

```
ffffffff81640970-ffffffff816409a8: take_down_master (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/base/component.c (ffffffff8167be04)
Location: drivers/base/component.c:262
Inline: True
Inline callers:
  - drivers/base/component.c:component_del
  - drivers/base/component.c:component_master_del
Direct callers:
  - drivers/base/component.c:component_del
  - drivers/base/component.c:component_master_del
```
**Symbols:**

```
ffffffff8167bcd0-ffffffff8167bd00: take_down_master.part.9 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/base/component.c (ffffffff8169bb04)
Location: drivers/base/component.c:252
Inline: True
Inline callers:
  - drivers/base/component.c:component_del
  - drivers/base/component.c:component_master_del
Direct callers:
  - drivers/base/component.c:component_del
  - drivers/base/component.c:component_master_del
```
**Symbols:**

```
ffffffff8169ba50-ffffffff8169ba80: take_down_master.part.9 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/base/component.c (ffffffff816d469a)
Location: drivers/base/component.c:284
Inline: True
Inline callers:
  - drivers/base/component.c:component_del
  - drivers/base/component.c:component_master_del
Direct callers:
  - drivers/base/component.c:component_del
  - drivers/base/component.c:component_master_del
```
**Symbols:**

```
ffffffff816d4550-ffffffff816d4580: take_down_master.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/base/component.c (ffffffff816f84ca)
Location: drivers/base/component.c:284
Inline: True
Inline callers:
  - drivers/base/component.c:component_del
  - drivers/base/component.c:component_master_del
Direct callers:
  - drivers/base/component.c:component_del
  - drivers/base/component.c:component_master_del
```
**Symbols:**

```
ffffffff816f8410-ffffffff816f8440: take_down_master.part.0 (STB_LOCAL)
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
In drivers/base/component.c (ffffffff817b173e)
Location: drivers/base/component.c:284
Inline: True
Inline callers:
  - drivers/base/component.c:component_del
  - drivers/base/component.c:component_del
  - drivers/base/component.c:component_master_del
  - drivers/base/component.c:component_master_del
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
In drivers/base/component.c (ffffffff817c608e)
Location: drivers/base/component.c:284
Inline: True
Inline callers:
  - drivers/base/component.c:component_del
  - drivers/base/component.c:component_del
  - drivers/base/component.c:component_master_del
  - drivers/base/component.c:component_master_del
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
In drivers/base/component.c (ffffffff817a93ee)
Location: drivers/base/component.c:281
Inline: True
Inline callers:
  - drivers/base/component.c:component_del
  - drivers/base/component.c:component_del
  - drivers/base/component.c:component_master_del
  - drivers/base/component.c:component_master_del
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

```c
void take_down_master(struct master *master);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/base/component.c (ffffffff81831ee4)
Location: drivers/base/component.c:282
Inline: True
Direct callers:
  - drivers/base/component.c:component_del
  - drivers/base/component.c:component_master_del
```
**Symbols:**

```
ffffffff81831ec0-ffffffff81831f0a: take_down_master (STB_LOCAL)
ffffffff81d02470-ffffffff81d02485: take_down_master.cold (STB_LOCAL)
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
<summary>In <code>arm64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/base/component.c (ffff8000108e2174)
Location: drivers/base/component.c:284
Inline: True
Inline callers:
  - drivers/base/component.c:component_del
  - drivers/base/component.c:component_master_del
Direct callers:
  - drivers/base/component.c:component_del
  - drivers/base/component.c:component_master_del
```
**Symbols:**

```
ffff8000108e20a0-ffff8000108e20e0: take_down_master.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/base/component.c (c09d0e54)
Location: drivers/base/component.c:284
Inline: True
Inline callers:
  - drivers/base/component.c:component_del
  - drivers/base/component.c:component_master_del
Direct callers:
  - drivers/base/component.c:component_del
  - drivers/base/component.c:component_master_del
```
**Symbols:**

```
c09d0cdc-c09d0d1c: take_down_master.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/base/component.c (c000000000976498)
Location: drivers/base/component.c:284
Inline: True
Inline callers:
  - drivers/base/component.c:component_del
  - drivers/base/component.c:component_master_del
Direct callers:
  - drivers/base/component.c:component_del
  - drivers/base/component.c:component_master_del
```
**Symbols:**

```
c000000000976350-c0000000009763bc: take_down_master.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/base/component.c (ffffffe00057743c)
Location: drivers/base/component.c:284
Inline: True
Inline callers:
  - drivers/base/component.c:component_del
  - drivers/base/component.c:component_master_del
Direct callers:
  - drivers/base/component.c:component_del
  - drivers/base/component.c:component_master_del
```
**Symbols:**

```
ffffffe00057739a-ffffffe0005773d2: take_down_master.part.0 (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/base/component.c (ffffffff816bdcba)
Location: drivers/base/component.c:284
Inline: True
Inline callers:
  - drivers/base/component.c:component_del
  - drivers/base/component.c:component_master_del
Direct callers:
  - drivers/base/component.c:component_del
  - drivers/base/component.c:component_master_del
```
**Symbols:**

```
ffffffff816bdc00-ffffffff816bdc30: take_down_master.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/base/component.c (ffffffff81698f6a)
Location: drivers/base/component.c:284
Inline: True
Inline callers:
  - drivers/base/component.c:component_del
  - drivers/base/component.c:component_master_del
Direct callers:
  - drivers/base/component.c:component_del
  - drivers/base/component.c:component_master_del
```
**Symbols:**

```
ffffffff81698eb0-ffffffff81698ee0: take_down_master.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/base/component.c (ffffffff816ec18a)
Location: drivers/base/component.c:284
Inline: True
Inline callers:
  - drivers/base/component.c:component_del
  - drivers/base/component.c:component_master_del
Direct callers:
  - drivers/base/component.c:component_del
  - drivers/base/component.c:component_master_del
```
**Symbols:**

```
ffffffff816ec0d0-ffffffff816ec100: take_down_master.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/base/component.c (ffffffff817069ca)
Location: drivers/base/component.c:284
Inline: True
Inline callers:
  - drivers/base/component.c:component_del
  - drivers/base/component.c:component_master_del
Direct callers:
  - drivers/base/component.c:component_del
  - drivers/base/component.c:component_master_del
```
**Symbols:**

```
ffffffff81706910-ffffffff81706940: take_down_master.part.0 (STB_LOCAL)
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
</ul>
