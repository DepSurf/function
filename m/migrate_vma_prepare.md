# Function: <code>migrate_vma_prepare</code>

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
In mm/migrate.c (ffffffff8124c16f)
Location: mm/migrate.c:2447
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
In mm/migrate.c (ffffffff8126fc96)
Location: mm/migrate.c:2460
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
In mm/migrate.c (ffffffff8128433d)
Location: mm/migrate.c:2439
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
In mm/migrate.c (ffffffff812aff4b)
Location: mm/migrate.c:2442
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
void migrate_vma_prepare(struct migrate_vma *migrate);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/migrate.c (ffffffff812e37c0)
Location: mm/migrate.c:2462
Inline: False
Direct callers:
  - mm/migrate.c:migrate_vma_setup
```
**Symbols:**

```
ffffffff812e37c0-ffffffff812e3b55: migrate_vma_prepare (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void migrate_vma_prepare(struct migrate_vma *migrate);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/migrate.c (ffffffff812eec30)
Location: mm/migrate.c:2632
Inline: False
Direct callers:
  - mm/migrate.c:migrate_vma_setup
```
**Symbols:**

```
ffffffff812eec30-ffffffff812eefb8: migrate_vma_prepare (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void migrate_vma_prepare(struct migrate_vma *migrate);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/migrate.c (ffffffff812f4dc0)
Location: mm/migrate.c:2595
Inline: False
Direct callers:
  - mm/migrate.c:migrate_vma_setup
```
**Symbols:**

```
ffffffff812f4dc0-ffffffff812f5148: migrate_vma_prepare (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void migrate_vma_prepare(struct migrate_vma *migrate);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/migrate.c (ffffffff8133f3c0)
Location: mm/migrate.c:2528
Inline: False
Direct callers:
  - mm/migrate.c:migrate_vma_setup
```
**Symbols:**

```
ffffffff8133f3c0-ffffffff8133f745: migrate_vma_prepare (STB_LOCAL)
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
In mm/migrate.c (c000000000435f24)
Location: mm/migrate.c:2442
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
In mm/migrate.c (ffffffff812a852b)
Location: mm/migrate.c:2442
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
In mm/migrate.c (ffffffff81299eeb)
Location: mm/migrate.c:2442
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
In mm/migrate.c (ffffffff812a633b)
Location: mm/migrate.c:2442
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
In mm/migrate.c (ffffffff812b6656)
Location: mm/migrate.c:2442
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
</ul>
