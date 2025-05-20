# Function: <code>migrate_vma_unmap</code>

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
<summary>In <code>4.15</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In mm/migrate.c (ffffffff8124c3d7)
Location: mm/migrate.c:2557
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma
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
In mm/migrate.c (ffffffff8126ff79)
Location: mm/migrate.c:2570
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma
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
In mm/migrate.c (ffffffff8128462c)
Location: mm/migrate.c:2549
Inline: True
Inline callers:
  - mm/migrate.c:migrate_vma
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
In mm/migrate.c (ffffffff812b00e1)
Location: mm/migrate.c:2552
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
void migrate_vma_unmap(struct migrate_vma *migrate);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/migrate.c (ffffffff812e2f10)
Location: mm/migrate.c:2572
Inline: False
Direct callers:
  - mm/migrate.c:migrate_vma_setup
```
**Symbols:**

```
ffffffff812e2f10-ffffffff812e30f0: migrate_vma_unmap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void migrate_vma_unmap(struct migrate_vma *migrate);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/migrate.c (ffffffff812ee350)
Location: mm/migrate.c:2742
Inline: False
Direct callers:
  - mm/migrate.c:migrate_vma_setup
```
**Symbols:**

```
ffffffff812ee350-ffffffff812ee52d: migrate_vma_unmap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void migrate_vma_unmap(struct migrate_vma *migrate);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/migrate.c (ffffffff812f44f0)
Location: mm/migrate.c:2705
Inline: False
Direct callers:
  - mm/migrate.c:migrate_vma_setup
```
**Symbols:**

```
ffffffff812f44f0-ffffffff812f46cd: migrate_vma_unmap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void migrate_vma_unmap(struct migrate_vma *migrate);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/migrate.c (ffffffff8133ec90)
Location: mm/migrate.c:2638
Inline: False
Direct callers:
  - mm/migrate.c:migrate_vma_setup
```
**Symbols:**

```
ffffffff8133ec90-ffffffff8133ee67: migrate_vma_unmap (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void migrate_vma_unmap(struct migrate_vma *migrate);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/migrate_device.c (ffffffff813b6730)
Location: mm/migrate_device.c:345
Inline: False
Direct callers:
  - mm/migrate_device.c:migrate_vma_setup
```
**Symbols:**

```
ffffffff813b6730-ffffffff813b6bb1: migrate_vma_unmap (STB_LOCAL)
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
In mm/migrate_device.c (ffffffff8143875a)
Location: mm/migrate_device.c:450
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
In mm/migrate_device.c (ffffffff8146e44b)
Location: mm/migrate_device.c:444
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
In mm/migrate_device.c (ffffffff8149edeb)
Location: mm/migrate_device.c:447
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
In mm/migrate.c (c0000000004361d0)
Location: mm/migrate.c:2552
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
In mm/migrate.c (ffffffff812a86c1)
Location: mm/migrate.c:2552
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
In mm/migrate.c (ffffffff8129a081)
Location: mm/migrate.c:2552
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
In mm/migrate.c (ffffffff812a64d1)
Location: mm/migrate.c:2552
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
In mm/migrate.c (ffffffff812b67ec)
Location: mm/migrate.c:2552
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
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
<li>
No changes between <code>5.13</code> and <code>5.15</code> ✅
</li>
<li>
No changes between <code>5.15</code> and <code>5.19</code> ✅
</li>
</ul>
