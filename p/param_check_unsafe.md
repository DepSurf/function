# Function: <code>param_check_unsafe</code>

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
In kernel/params.c (ffffffff8109f5a1)
Location: kernel/params.c:111
Inline: True
Inline callers:
  - kernel/params.c:param_attr_store
  - kernel/params.c:parse_args
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
In kernel/params.c (ffffffff810a2c51)
Location: kernel/params.c:111
Inline: True
Inline callers:
  - kernel/params.c:param_attr_store
  - kernel/params.c:parse_args
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
In kernel/params.c (ffffffff810a7ef1)
Location: kernel/params.c:111
Inline: True
Inline callers:
  - kernel/params.c:param_attr_store
  - kernel/params.c:parse_args
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
In kernel/params.c (ffffffff810a4e91)
Location: kernel/params.c:111
Inline: True
Inline callers:
  - kernel/params.c:param_attr_store
  - kernel/params.c:parse_args
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/params.c (ffffffff810ab160)
Location: kernel/params.c:111
Inline: True
Direct callers:
  - kernel/params.c:param_attr_store
  - kernel/params.c:parse_args
```
**Symbols:**

```
ffffffff810ab160-ffffffff810ab1c6: param_check_unsafe.isra.4 (STB_LOCAL)
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
In kernel/params.c (0)
Location: kernel/params.c:111
Inline: True
Direct callers:
  - kernel/params.c:param_attr_store
  - kernel/params.c:parse_args
```
**Symbols:**

```
ffffffff810b1c10-ffffffff810b1c5a: param_check_unsafe.isra.6 (STB_LOCAL)
ffffffff810b2905-ffffffff810b292b: param_check_unsafe.isra.6.cold.15 (STB_LOCAL)
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
In kernel/params.c (ffffffff810bad73)
Location: kernel/params.c:111
Inline: True
Direct callers:
  - kernel/params.c:param_attr_store
  - kernel/params.c:parse_args
```
**Symbols:**

```
ffffffff810bad50-ffffffff810bad9a: param_check_unsafe.isra.6 (STB_LOCAL)
ffffffff810bba35-ffffffff810bba5b: param_check_unsafe.isra.6.cold.14 (STB_LOCAL)
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
In kernel/params.c (ffffffff810c0c93)
Location: kernel/params.c:99
Inline: True
Direct callers:
  - kernel/params.c:param_attr_store
  - kernel/params.c:parse_args
```
**Symbols:**

```
ffffffff810c0c70-ffffffff810c0cba: param_check_unsafe.isra.0 (STB_LOCAL)
ffffffff810c18f4-ffffffff810c191a: param_check_unsafe.isra.0.cold (STB_LOCAL)
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
In kernel/params.c (ffffffff810c7ce4)
Location: kernel/params.c:100
Inline: True
Direct callers:
  - kernel/params.c:param_attr_store
  - kernel/params.c:parse_args
```
**Symbols:**

```
ffffffff810c7070-ffffffff810c70b4: param_check_unsafe.isra.0 (STB_LOCAL)
ffffffff810c7ce4-ffffffff810c7d0a: param_check_unsafe.isra.0.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/params.c (ffffffff810cf6c3)
Location: kernel/params.c:100
Inline: True
Inline callers:
  - kernel/params.c:param_attr_store
  - kernel/params.c:parse_one
Direct callers:
  - kernel/params.c:param_attr_store
  - kernel/params.c:parse_one
```
**Symbols:**

```
ffffffff810cfd94-ffffffff810cfdbc: param_check_unsafe.part.0.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/params.c (ffffffff810ca213)
Location: kernel/params.c:100
Inline: True
Inline callers:
  - kernel/params.c:param_attr_store
  - kernel/params.c:parse_one
Direct callers:
  - kernel/params.c:param_attr_store
  - kernel/params.c:parse_one
```
**Symbols:**

```
ffffffff81bdc164-ffffffff81bdc18c: param_check_unsafe.part.0.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/params.c (ffffffff810cbb53)
Location: kernel/params.c:100
Inline: True
Inline callers:
  - kernel/params.c:param_attr_store
  - kernel/params.c:parse_one
Direct callers:
  - kernel/params.c:param_attr_store
  - kernel/params.c:parse_one
```
**Symbols:**

```
ffffffff81bce289-ffffffff81bce2b1: param_check_unsafe.part.0.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/params.c (ffffffff810ded53)
Location: kernel/params.c:100
Inline: True
Inline callers:
  - kernel/params.c:param_attr_store
  - kernel/params.c:parse_one
Direct callers:
  - kernel/params.c:param_attr_store
  - kernel/params.c:parse_one
```
**Symbols:**

```
ffffffff81ca55c7-ffffffff81ca55ef: param_check_unsafe.part.0.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
bool param_check_unsafe(const struct kernel_param *kp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/params.c (0)
Location: kernel/params.c:100
Inline: False
Direct callers:
  - kernel/params.c:param_attr_store
  - kernel/params.c:parse_one
```
**Symbols:**

```
ffffffff810f7dc0-ffffffff810f7e0a: param_check_unsafe (STB_LOCAL)
ffffffff81e54dcc-ffffffff81e54dec: param_check_unsafe.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
bool param_check_unsafe(const struct kernel_param *kp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/params.c (ffffffff8111a650)
Location: kernel/params.c:100
Inline: False
Direct callers:
  - kernel/params.c:param_attr_store
  - kernel/params.c:parse_one
```
**Symbols:**

```
ffffffff8111a650-ffffffff8111a6b5: param_check_unsafe (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
bool param_check_unsafe(const struct kernel_param *kp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/params.c (ffffffff811278c0)
Location: kernel/params.c:101
Inline: False
Direct callers:
  - kernel/params.c:param_attr_store
  - kernel/params.c:parse_one
```
**Symbols:**

```
ffffffff811278c0-ffffffff81127925: param_check_unsafe (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
bool param_check_unsafe(const struct kernel_param *kp);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/params.c (ffffffff81131ea0)
Location: kernel/params.c:102
Inline: False
Direct callers:
  - kernel/params.c:param_attr_store
  - kernel/params.c:parse_one
```
**Symbols:**

```
ffffffff81131ea0-ffffffff81131f05: param_check_unsafe (STB_LOCAL)
```
</details>
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
In kernel/params.c (ffff800010126040)
Location: kernel/params.c:100
Inline: True
Direct callers:
  - kernel/params.c:param_attr_store
  - kernel/params.c:parse_args
```
**Symbols:**

```
ffff800010126040-ffff8000101260bc: param_check_unsafe.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
bool param_check_unsafe(const struct kernel_param *kp);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In kernel/params.c (c0378f54)
Location: kernel/params.c:100
Inline: True
Direct callers:
  - kernel/params.c:param_attr_store
  - kernel/params.c:parse_args
```
**Symbols:**

```
c0378f54-c0378fc8: param_check_unsafe (STB_LOCAL)
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
In kernel/params.c (c000000000170400)
Location: kernel/params.c:100
Inline: True
Direct callers:
  - kernel/params.c:param_attr_store
  - kernel/params.c:parse_args
```
**Symbols:**

```
c000000000170400-c0000000001704e8: param_check_unsafe.isra.0 (STB_LOCAL)
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
In kernel/params.c (ffffffe0000ddb44)
Location: kernel/params.c:100
Inline: True
Direct callers:
  - kernel/params.c:param_attr_store
  - kernel/params.c:parse_args
```
**Symbols:**

```
ffffffe0000ddb44-ffffffe0000ddbb6: param_check_unsafe.isra.0 (STB_LOCAL)
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
In kernel/params.c (ffffffff810c2064)
Location: kernel/params.c:100
Inline: True
Direct callers:
  - kernel/params.c:param_attr_store
  - kernel/params.c:parse_args
```
**Symbols:**

```
ffffffff810c13f0-ffffffff810c1434: param_check_unsafe.isra.0 (STB_LOCAL)
ffffffff810c2064-ffffffff810c208a: param_check_unsafe.isra.0.cold (STB_LOCAL)
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
In kernel/params.c (ffffffff810b0884)
Location: kernel/params.c:100
Inline: True
Direct callers:
  - kernel/params.c:param_attr_store
  - kernel/params.c:parse_args
```
**Symbols:**

```
ffffffff810afbe0-ffffffff810afc24: param_check_unsafe.isra.0 (STB_LOCAL)
ffffffff810b0884-ffffffff810b08aa: param_check_unsafe.isra.0.cold (STB_LOCAL)
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
In kernel/params.c (ffffffff810c15b4)
Location: kernel/params.c:100
Inline: True
Direct callers:
  - kernel/params.c:param_attr_store
  - kernel/params.c:parse_args
```
**Symbols:**

```
ffffffff810c0940-ffffffff810c0984: param_check_unsafe.isra.0 (STB_LOCAL)
ffffffff810c15b4-ffffffff810c15da: param_check_unsafe.isra.0.cold (STB_LOCAL)
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
In kernel/params.c (ffffffff810c99fd)
Location: kernel/params.c:100
Inline: True
Direct callers:
  - kernel/params.c:param_attr_store
  - kernel/params.c:parse_args
```
**Symbols:**

```
ffffffff810c8ef0-ffffffff810c8f34: param_check_unsafe.isra.0 (STB_LOCAL)
ffffffff810c99fd-ffffffff810c9a23: param_check_unsafe.isra.0.cold (STB_LOCAL)
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
<b>Arch</b>
<ul>
</ul>
