# Function: <code>migrate_vma_collect</code>

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
<details>
<summary>In <code>4.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In mm/migrate.c (ffffffff81249740)
Location: mm/migrate.c:2352
Inline: True
Direct callers:
  - mm/migrate.c:migrate_vma
```
**Symbols:**

```
ffffffff81249740-ffffffff8124981b: migrate_vma_collect.constprop.57 (STB_LOCAL)
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
In mm/migrate.c (ffffffff8126cf90)
Location: mm/migrate.c:2365
Inline: True
Direct callers:
  - mm/migrate.c:migrate_vma
```
**Symbols:**

```
ffffffff8126cf90-ffffffff8126d067: migrate_vma_collect.constprop.64 (STB_LOCAL)
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
In mm/migrate.c (ffffffff81281760)
Location: mm/migrate.c:2345
Inline: True
Direct callers:
  - mm/migrate.c:migrate_vma
```
**Symbols:**

```
ffffffff81281760-ffffffff8128183b: migrate_vma_collect.constprop.60 (STB_LOCAL)
```
</details>
</li>
<li>
In <code>5.3</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>5.4</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/migrate.c (ffffffff812afe87)
Location: mm/migrate.c:2365
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_setup
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void migrate_vma_collect(struct migrate_vma *migrate);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/migrate.c (ffffffff812e21c0)
Location: mm/migrate.c:2385
Inline: False
Direct callers:
  - mm/migrate.c:migrate_vma_setup
```
**Symbols:**

```
ffffffff812e21c0-ffffffff812e22b0: migrate_vma_collect (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void migrate_vma_collect(struct migrate_vma *migrate);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/migrate.c (ffffffff812ed4c0)
Location: mm/migrate.c:2549
Inline: False
Direct callers:
  - mm/migrate.c:migrate_vma_setup
```
**Symbols:**

```
ffffffff812ed4c0-ffffffff812ed5b6: migrate_vma_collect (STB_LOCAL)
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
In mm/migrate.c (ffffffff812f5254)
Location: mm/migrate.c:2512
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_setup
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
In mm/migrate.c (ffffffff8133f854)
Location: mm/migrate.c:2445
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_setup
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
In mm/migrate_device.c (ffffffff813b6cc1)
Location: mm/migrate_device.c:274
Inline: True
Inline callers:
  - mm/migrate_device.c:migrate_vma_setup
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
In mm/migrate_device.c (ffffffff814386bf)
Location: mm/migrate_device.c:299
Inline: True
Inline callers:
  - mm/migrate_device.c:migrate_vma_setup
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
In mm/migrate_device.c (ffffffff8146e388)
Location: mm/migrate_device.c:293
Inline: True
Inline callers:
  - mm/migrate_device.c:migrate_vma_setup
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
In mm/migrate_device.c (ffffffff8149ed28)
Location: mm/migrate_device.c:296
Inline: True
Inline callers:
  - mm/migrate_device.c:migrate_vma_setup
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
<details>
<summary>In <code>ppc64el</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/migrate.c (c000000000435e34)
Location: mm/migrate.c:2365
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_setup
```
</details>
</li>
<li>
In <code>riscv64</code>: Absent ⚠️
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
In mm/migrate.c (ffffffff812a8467)
Location: mm/migrate.c:2365
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_setup
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
In mm/migrate.c (ffffffff81299e27)
Location: mm/migrate.c:2365
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_setup
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
In mm/migrate.c (ffffffff812a6277)
Location: mm/migrate.c:2365
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_setup
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
In mm/migrate.c (ffffffff812b65b7)
Location: mm/migrate.c:2365
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma_setup
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
