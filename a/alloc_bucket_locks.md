# Function: <code>alloc_bucket_locks</code>

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
In lib/rhashtable.c (ffffffff8140010b)
Location: lib/rhashtable.c:63
Inline: True
Inline callers:
  - lib/rhashtable.c:bucket_table_alloc
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
In lib/rhashtable.c (ffffffff81447892)
Location: lib/rhashtable.c:63
Inline: True
Inline callers:
  - lib/rhashtable.c:bucket_table_alloc
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
In lib/rhashtable.c (ffffffff81466260)
Location: lib/rhashtable.c:63
Inline: True
Direct callers:
  - lib/rhashtable.c:bucket_table_alloc
```
**Symbols:**

```
ffffffff81466260-ffffffff81466365: alloc_bucket_locks.isra.11 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In lib/rhashtable.c (ffffffff8146b3e0)
Location: lib/rhashtable.c:69
Inline: True
Direct callers:
  - lib/rhashtable.c:bucket_table_alloc
  - lib/rhashtable.c:bucket_table_alloc
```
**Symbols:**

```
ffffffff8146b3e0-ffffffff8146b4c7: alloc_bucket_locks.isra.10 (STB_LOCAL)
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
In lib/rhashtable.c (ffffffff814976d0)
Location: lib/rhashtable.c:69
Inline: True
Direct callers:
  - lib/rhashtable.c:bucket_table_alloc
  - lib/rhashtable.c:bucket_table_alloc
```
**Symbols:**

```
ffffffff814976d0-ffffffff814977b7: alloc_bucket_locks.isra.10 (STB_LOCAL)
```
</details>
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
In <code>5.8</code>: Absent ⚠️
</li>
<li>
In <code>5.11</code>: Absent ⚠️
</li>
<li>
In <code>5.13</code>: Absent ⚠️
</li>
<li>
In <code>5.15</code>: Absent ⚠️
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
