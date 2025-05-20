# Function: <code>reassign_resources_sorted</code>

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
In drivers/pci/setup-bus.c (ffffffff8143ea58)
Location: drivers/pci/setup-bus.c:232
Inline: True
Inline callers:
  - drivers/pci/setup-bus.c:__assign_resources_sorted
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
In drivers/pci/setup-bus.c (ffffffff8148a8ac)
Location: drivers/pci/setup-bus.c:231
Inline: True
Inline callers:
  - drivers/pci/setup-bus.c:__assign_resources_sorted
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
In drivers/pci/setup-bus.c (ffffffff814ac09c)
Location: drivers/pci/setup-bus.c:232
Inline: True
Inline callers:
  - drivers/pci/setup-bus.c:__assign_resources_sorted
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
In drivers/pci/setup-bus.c (ffffffff814b63c9)
Location: drivers/pci/setup-bus.c:223
Inline: True
Inline callers:
  - drivers/pci/setup-bus.c:__assign_resources_sorted
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
In drivers/pci/setup-bus.c (ffffffff814f6089)
Location: drivers/pci/setup-bus.c:223
Inline: True
Inline callers:
  - drivers/pci/setup-bus.c:__assign_resources_sorted
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
In drivers/pci/setup-bus.c (ffffffff81526d88)
Location: drivers/pci/setup-bus.c:218
Inline: True
Inline callers:
  - drivers/pci/setup-bus.c:__assign_resources_sorted
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
In drivers/pci/setup-bus.c (ffffffff8153cc28)
Location: drivers/pci/setup-bus.c:218
Inline: True
Inline callers:
  - drivers/pci/setup-bus.c:__assign_resources_sorted
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
In drivers/pci/setup-bus.c (ffffffff8156c2ce)
Location: drivers/pci/setup-bus.c:213
Inline: True
Inline callers:
  - drivers/pci/setup-bus.c:__assign_resources_sorted
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
In drivers/pci/setup-bus.c (ffffffff8158d2ae)
Location: drivers/pci/setup-bus.c:213
Inline: True
Inline callers:
  - drivers/pci/setup-bus.c:__assign_resources_sorted
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
void reassign_resources_sorted(struct list_head *realloc_head, struct list_head *head);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/setup-bus.c (0)
Location: drivers/pci/setup-bus.c:214
Inline: False
Direct callers:
  - drivers/pci/setup-bus.c:__assign_resources_sorted
```
**Symbols:**

```
ffffffff81633cf0-ffffffff81633e3a: reassign_resources_sorted (STB_LOCAL)
ffffffff816374be-ffffffff816374e1: reassign_resources_sorted.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
void reassign_resources_sorted(struct list_head *realloc_head, struct list_head *head);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/pci/setup-bus.c (0)
Location: drivers/pci/setup-bus.c:215
Inline: False
Direct callers:
  - drivers/pci/setup-bus.c:__assign_resources_sorted
```
**Symbols:**

```
ffffffff81658da0-ffffffff81658eea: reassign_resources_sorted (STB_LOCAL)
ffffffff81bf8920-ffffffff81bf8943: reassign_resources_sorted.cold (STB_LOCAL)
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
In drivers/pci/setup-bus.c (ffffffff8163c848)
Location: drivers/pci/setup-bus.c:215
Inline: True
Inline callers:
  - drivers/pci/setup-bus.c:__assign_resources_sorted
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
In drivers/pci/setup-bus.c (ffffffff816ad2a8)
Location: drivers/pci/setup-bus.c:215
Inline: True
Inline callers:
  - drivers/pci/setup-bus.c:__assign_resources_sorted
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
In drivers/pci/setup-bus.c (ffffffff817d0731)
Location: drivers/pci/setup-bus.c:215
Inline: True
Inline callers:
  - drivers/pci/setup-bus.c:__assign_resources_sorted
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
In drivers/pci/setup-bus.c (ffffffff818f0ab1)
Location: drivers/pci/setup-bus.c:215
Inline: True
Inline callers:
  - drivers/pci/setup-bus.c:__assign_resources_sorted
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
In drivers/pci/setup-bus.c (ffffffff81933ed1)
Location: drivers/pci/setup-bus.c:212
Inline: True
Inline callers:
  - drivers/pci/setup-bus.c:__assign_resources_sorted
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void reassign_resources_sorted(struct list_head *realloc_head, struct list_head *head);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/pci/setup-bus.c (ffffffff8197b040)
Location: drivers/pci/setup-bus.c:212
Inline: False
Direct callers:
  - drivers/pci/setup-bus.c:__assign_resources_sorted
```
**Symbols:**

```
ffffffff8197b040-ffffffff8197b1cd: reassign_resources_sorted (STB_LOCAL)
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
In drivers/pci/setup-bus.c (ffff8000106f25a0)
Location: drivers/pci/setup-bus.c:213
Inline: True
Inline callers:
  - drivers/pci/setup-bus.c:__assign_resources_sorted
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
In drivers/pci/setup-bus.c (c088d02c)
Location: drivers/pci/setup-bus.c:213
Inline: True
Inline callers:
  - drivers/pci/setup-bus.c:__assign_resources_sorted
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
In drivers/pci/setup-bus.c (c000000000870260)
Location: drivers/pci/setup-bus.c:213
Inline: True
Inline callers:
  - drivers/pci/setup-bus.c:__assign_resources_sorted
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
In drivers/pci/setup-bus.c (ffffffe0004c59a8)
Location: drivers/pci/setup-bus.c:213
Inline: True
Inline callers:
  - drivers/pci/setup-bus.c:__assign_resources_sorted
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
In drivers/pci/setup-bus.c (ffffffff8158112e)
Location: drivers/pci/setup-bus.c:213
Inline: True
Inline callers:
  - drivers/pci/setup-bus.c:__assign_resources_sorted
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
In drivers/pci/setup-bus.c (ffffffff8156ff0e)
Location: drivers/pci/setup-bus.c:213
Inline: True
Inline callers:
  - drivers/pci/setup-bus.c:__assign_resources_sorted
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
In drivers/pci/setup-bus.c (ffffffff81580ffe)
Location: drivers/pci/setup-bus.c:213
Inline: True
Inline callers:
  - drivers/pci/setup-bus.c:__assign_resources_sorted
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
In drivers/pci/setup-bus.c (ffffffff8159b4ae)
Location: drivers/pci/setup-bus.c:213
Inline: True
Inline callers:
  - drivers/pci/setup-bus.c:__assign_resources_sorted
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
