# Function: <code>tracing_map_alloc_elts</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4</code>: Absent ⚠️
</li>
<li>
<details>
<summary>In <code>4.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/trace/tracing_map.c (ffffffff8116079e)
Location: kernel/trace/tracing_map.c:378
Inline: True
Inline callers:
  - kernel/trace/tracing_map.c:tracing_map_init
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
In kernel/trace/tracing_map.c (ffffffff8116b1fe)
Location: kernel/trace/tracing_map.c:378
Inline: True
Inline callers:
  - kernel/trace/tracing_map.c:tracing_map_init
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
In kernel/trace/tracing_map.c (ffffffff8116e1ae)
Location: kernel/trace/tracing_map.c:381
Inline: True
Inline callers:
  - kernel/trace/tracing_map.c:tracing_map_init
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
In kernel/trace/tracing_map.c (ffffffff8117b28e)
Location: kernel/trace/tracing_map.c:381
Inline: True
Inline callers:
  - kernel/trace/tracing_map.c:tracing_map_init
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
In kernel/trace/tracing_map.c (ffffffff8118a441)
Location: kernel/trace/tracing_map.c:489
Inline: True
Inline callers:
  - kernel/trace/tracing_map.c:tracing_map_init
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
In kernel/trace/tracing_map.c (ffffffff81197da1)
Location: kernel/trace/tracing_map.c:480
Inline: True
Inline callers:
  - kernel/trace/tracing_map.c:tracing_map_init
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
In kernel/trace/tracing_map.c (ffffffff811a597f)
Location: kernel/trace/tracing_map.c:480
Inline: True
Inline callers:
  - kernel/trace/tracing_map.c:tracing_map_init
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
In kernel/trace/tracing_map.c (ffffffff811b11af)
Location: kernel/trace/tracing_map.c:480
Inline: True
Inline callers:
  - kernel/trace/tracing_map.c:tracing_map_init
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int tracing_map_alloc_elts(struct tracing_map *map);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/tracing_map.c (ffffffff811c92c0)
Location: kernel/trace/tracing_map.c:480
Inline: False
Direct callers:
  - kernel/trace/tracing_map.c:tracing_map_init
```
**Symbols:**

```
ffffffff811c92c0-ffffffff811c938b: tracing_map_alloc_elts (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int tracing_map_alloc_elts(struct tracing_map *map);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/tracing_map.c (ffffffff811c6980)
Location: kernel/trace/tracing_map.c:480
Inline: False
Direct callers:
  - kernel/trace/tracing_map.c:tracing_map_init
```
**Symbols:**

```
ffffffff811c6980-ffffffff811c6a4b: tracing_map_alloc_elts (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int tracing_map_alloc_elts(struct tracing_map *map);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/trace/tracing_map.c (ffffffff811c7830)
Location: kernel/trace/tracing_map.c:480
Inline: False
Direct callers:
  - kernel/trace/tracing_map.c:tracing_map_init
```
**Symbols:**

```
ffffffff811c7830-ffffffff811c7a40: tracing_map_alloc_elts (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int tracing_map_alloc_elts(struct tracing_map *map);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/tracing_map.c (0)
Location: kernel/trace/tracing_map.c:483
Inline: False
Direct callers:
  - kernel/trace/tracing_map.c:tracing_map_init
```
**Symbols:**

```
ffffffff811f2fd0-ffffffff811f329b: tracing_map_alloc_elts (STB_LOCAL)
ffffffff81cb5af0-ffffffff81cb5bb0: tracing_map_alloc_elts.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int tracing_map_alloc_elts(struct tracing_map *map);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/tracing_map.c (0)
Location: kernel/trace/tracing_map.c:483
Inline: False
Direct callers:
  - kernel/trace/tracing_map.c:tracing_map_init
```
**Symbols:**

```
ffffffff8122c760-ffffffff8122c8ad: tracing_map_alloc_elts (STB_LOCAL)
ffffffff81e66af7-ffffffff81e66bb7: tracing_map_alloc_elts.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int tracing_map_alloc_elts(struct tracing_map *map);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/tracing_map.c (0)
Location: kernel/trace/tracing_map.c:483
Inline: False
Direct callers:
  - kernel/trace/tracing_map.c:tracing_map_init
```
**Symbols:**

```
ffffffff812782c0-ffffffff8127840d: tracing_map_alloc_elts (STB_LOCAL)
ffffffff8205dbb5-ffffffff8205dc75: tracing_map_alloc_elts.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int tracing_map_alloc_elts(struct tracing_map *map);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/tracing_map.c (0)
Location: kernel/trace/tracing_map.c:483
Inline: False
Direct callers:
  - kernel/trace/tracing_map.c:tracing_map_init
```
**Symbols:**

```
ffffffff8128fcf0-ffffffff8128fe44: tracing_map_alloc_elts (STB_LOCAL)
ffffffff820dc4e6-ffffffff820dc59d: tracing_map_alloc_elts.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int tracing_map_alloc_elts(struct tracing_map *map);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/trace/tracing_map.c (0)
Location: kernel/trace/tracing_map.c:483
Inline: False
Direct callers:
  - kernel/trace/tracing_map.c:tracing_map_init
```
**Symbols:**

```
ffffffff812ab2b0-ffffffff812ab404: tracing_map_alloc_elts (STB_LOCAL)
ffffffff821b8315-ffffffff821b83cc: tracing_map_alloc_elts.cold (STB_LOCAL)
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
In kernel/trace/tracing_map.c (ffff80001022edfc)
Location: kernel/trace/tracing_map.c:480
Inline: True
Inline callers:
  - kernel/trace/tracing_map.c:tracing_map_init
```
</details>
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
In kernel/trace/tracing_map.c (c0000000002b8524)
Location: kernel/trace/tracing_map.c:480
Inline: True
Inline callers:
  - kernel/trace/tracing_map.c:tracing_map_init
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
In kernel/trace/tracing_map.c (ffffffff811a97cf)
Location: kernel/trace/tracing_map.c:480
Inline: True
Inline callers:
  - kernel/trace/tracing_map.c:tracing_map_init
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
In kernel/trace/tracing_map.c (ffffffff8119c74f)
Location: kernel/trace/tracing_map.c:480
Inline: True
Inline callers:
  - kernel/trace/tracing_map.c:tracing_map_init
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
In kernel/trace/tracing_map.c (ffffffff811a759f)
Location: kernel/trace/tracing_map.c:480
Inline: True
Inline callers:
  - kernel/trace/tracing_map.c:tracing_map_init
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
In kernel/trace/tracing_map.c (ffffffff811b533f)
Location: kernel/trace/tracing_map.c:480
Inline: True
Inline callers:
  - kernel/trace/tracing_map.c:tracing_map_init
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
