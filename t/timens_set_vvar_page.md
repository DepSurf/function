# Function: <code>timens_set_vvar_page</code>

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
In <code>4.15</code>: Absent ⚠️
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
<details>
<summary>In <code>5.8</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In kernel/time/namespace.c (ffffffff8115a264)
Location: kernel/time/namespace.c:201
Inline: True
Inline callers:
  - kernel/time/namespace.c:timens_on_fork
  - kernel/time/namespace.c:timens_install
Direct callers:
  - kernel/time/namespace.c:timens_on_fork
  - kernel/time/namespace.c:timens_install
```
**Symbols:**

```
ffffffff81159ce0-ffffffff81159dec: timens_set_vvar_page.part.0 (STB_LOCAL)
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
In kernel/time/namespace.c (ffffffff8115618e)
Location: kernel/time/namespace.c:201
Inline: True
Inline callers:
  - kernel/time/namespace.c:timens_commit
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
In kernel/time/namespace.c (ffffffff8115758e)
Location: kernel/time/namespace.c:201
Inline: True
Inline callers:
  - kernel/time/namespace.c:timens_commit
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
In kernel/time/namespace.c (ffffffff8117c3de)
Location: kernel/time/namespace.c:201
Inline: True
Inline callers:
  - kernel/time/namespace.c:timens_commit
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
In kernel/time/namespace.c (ffffffff811b1b9e)
Location: kernel/time/namespace.c:201
Inline: True
Inline callers:
  - kernel/time/namespace.c:timens_commit
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
In kernel/time/namespace.c (ffffffff811f299e)
Location: kernel/time/namespace.c:219
Inline: True
Inline callers:
  - kernel/time/namespace.c:timens_commit
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
In kernel/time/namespace.c (ffffffff8120711e)
Location: kernel/time/namespace.c:219
Inline: True
Inline callers:
  - kernel/time/namespace.c:timens_commit
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
In kernel/time/namespace.c (ffffffff8121e32e)
Location: kernel/time/namespace.c:219
Inline: True
Inline callers:
  - kernel/time/namespace.c:timens_commit
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
