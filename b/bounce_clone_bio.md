# Function: <code>bounce_clone_bio</code>

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
<details>
<summary>In <code>5.0</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/bounce.c (ffffffff814be330)
Location: block/bounce.c:217
Inline: True
Inline callers:
  - block/bounce.c:blk_queue_bounce
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
In block/bounce.c (ffffffff814eca48)
Location: block/bounce.c:217
Inline: True
Inline callers:
  - block/bounce.c:__blk_queue_bounce
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
In block/bounce.c (ffffffff81505e98)
Location: block/bounce.c:217
Inline: True
Inline callers:
  - block/bounce.c:__blk_queue_bounce
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
In block/bounce.c (ffffffff81566660)
Location: block/bounce.c:217
Inline: True
Direct callers:
  - block/bounce.c:__blk_queue_bounce
```
**Symbols:**

```
ffffffff81566660-ffffffff81566a05: bounce_clone_bio.constprop.0 (STB_LOCAL)
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
In block/bounce.c (ffffffff815815a0)
Location: block/bounce.c:217
Inline: True
Direct callers:
  - block/bounce.c:__blk_queue_bounce
```
**Symbols:**

```
ffffffff815815a0-ffffffff815818a1: bounce_clone_bio.constprop.0 (STB_LOCAL)
```
</details>
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
<details>
<summary>In <code>armhf</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/bounce.c (c07b3288)
Location: block/bounce.c:217
Inline: True
Inline callers:
  - block/bounce.c:__blk_queue_bounce
```
</details>
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
<details>
<summary>In <code>aws</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In block/bounce.c (ffffffff814fe478)
Location: block/bounce.c:217
Inline: True
Inline callers:
  - block/bounce.c:__blk_queue_bounce
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
In block/bounce.c (ffffffff814ee988)
Location: block/bounce.c:217
Inline: True
Inline callers:
  - block/bounce.c:__blk_queue_bounce
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
In block/bounce.c (ffffffff814fa508)
Location: block/bounce.c:217
Inline: True
Inline callers:
  - block/bounce.c:__blk_queue_bounce
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
In block/bounce.c (ffffffff81513568)
Location: block/bounce.c:217
Inline: True
Inline callers:
  - block/bounce.c:__blk_queue_bounce
```
</details>
</li>
</ul>

## Differences
