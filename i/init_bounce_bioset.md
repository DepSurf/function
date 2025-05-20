# Function: <code>init_bounce_bioset</code>

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
In block/bounce.c (ffffffff814be873)
Location: block/bounce.c:34
Inline: True
Inline callers:
  - block/bounce.c:init_emergency_isa_pool
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
In block/bounce.c (ffffffff814ed107)
Location: block/bounce.c:34
Inline: True
Inline callers:
  - block/bounce.c:init_emergency_isa_pool
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
In block/bounce.c (ffffffff81506544)
Location: block/bounce.c:34
Inline: True
Inline callers:
  - block/bounce.c:init_emergency_isa_pool
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void init_bounce_bioset();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bounce.c (ffffffff81566e81)
Location: block/bounce.c:34
Inline: False
Direct callers:
  - block/bounce.c:init_emergency_isa_pool
```
**Symbols:**

```
ffffffff81566e81-ffffffff81566eed: init_bounce_bioset (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void init_bounce_bioset();
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In block/bounce.c (ffffffff81bf369a)
Location: block/bounce.c:34
Inline: False
Direct callers:
  - block/bounce.c:init_emergency_isa_pool
```
**Symbols:**

```
ffffffff81bf369a-ffffffff81bf3706: init_bounce_bioset (STB_LOCAL)
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
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void init_bounce_bioset();
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/bounce.c (c07b39f8)
Location: block/bounce.c:34
Inline: True
Direct callers:
  - block/bounce.c:init_emergency_isa_pool
  - block/bounce.c:init_emergency_pool
```
**Symbols:**

```
c07b39f8-c07b3a7c: init_bounce_bioset (STB_LOCAL)
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
In block/bounce.c (ffffffff814feb24)
Location: block/bounce.c:34
Inline: True
Inline callers:
  - block/bounce.c:init_emergency_isa_pool
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
In block/bounce.c (ffffffff814ef034)
Location: block/bounce.c:34
Inline: True
Inline callers:
  - block/bounce.c:init_emergency_isa_pool
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
In block/bounce.c (ffffffff814fabb4)
Location: block/bounce.c:34
Inline: True
Inline callers:
  - block/bounce.c:init_emergency_isa_pool
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
In block/bounce.c (ffffffff81513c64)
Location: block/bounce.c:34
Inline: True
Inline callers:
  - block/bounce.c:init_emergency_isa_pool
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
<b>Arch</b>
<ul>
</ul>
