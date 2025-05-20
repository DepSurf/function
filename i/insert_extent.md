# Function: <code>insert_extent</code>

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
In kernel/user_namespace.c (ffffffff8113e7fe)
Location: kernel/user_namespace.c:765
Inline: True
Inline callers:
  - kernel/user_namespace.c:map_write
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
In kernel/user_namespace.c (ffffffff8114d394)
Location: kernel/user_namespace.c:765
Inline: True
Inline callers:
  - kernel/user_namespace.c:map_write
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
In kernel/user_namespace.c (ffffffff81159f54)
Location: kernel/user_namespace.c:765
Inline: True
Inline callers:
  - kernel/user_namespace.c:map_write
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
In kernel/user_namespace.c (ffffffff8116667d)
Location: kernel/user_namespace.c:759
Inline: True
Inline callers:
  - kernel/user_namespace.c:map_write
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
In kernel/user_namespace.c (ffffffff8117253d)
Location: kernel/user_namespace.c:759
Inline: True
Inline callers:
  - kernel/user_namespace.c:map_write
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/user_namespace.c (ffffffff81184233)
Location: kernel/user_namespace.c:759
Inline: True
Inline callers:
  - kernel/user_namespace.c:map_write
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
In kernel/user_namespace.c (ffffffff81180f93)
Location: kernel/user_namespace.c:759
Inline: True
Inline callers:
  - kernel/user_namespace.c:map_write
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
In kernel/user_namespace.c (ffffffff811821a3)
Location: kernel/user_namespace.c:760
Inline: True
Inline callers:
  - kernel/user_namespace.c:map_write
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
In kernel/user_namespace.c (ffffffff811aa16d)
Location: kernel/user_namespace.c:776
Inline: True
Inline callers:
  - kernel/user_namespace.c:map_write
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
In kernel/user_namespace.c (ffffffff811db6f8)
Location: kernel/user_namespace.c:781
Inline: True
Inline callers:
  - kernel/user_namespace.c:map_write
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int insert_extent(struct uid_gid_map *map, struct uid_gid_extent *extent);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/user_namespace.c (ffffffff81220280)
Location: kernel/user_namespace.c:781
Inline: False
Direct callers:
  - kernel/user_namespace.c:map_write
```
**Symbols:**

```
ffffffff81220280-ffffffff81220356: insert_extent (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int insert_extent(struct uid_gid_map *map, struct uid_gid_extent *extent);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/user_namespace.c (ffffffff812364f0)
Location: kernel/user_namespace.c:781
Inline: False
Direct callers:
  - kernel/user_namespace.c:map_write
```
**Symbols:**

```
ffffffff812364f0-ffffffff812365e2: insert_extent (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int insert_extent(struct uid_gid_map *map, struct uid_gid_extent *extent);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In kernel/user_namespace.c (ffffffff81250170)
Location: kernel/user_namespace.c:784
Inline: False
Direct callers:
  - kernel/user_namespace.c:map_write
```
**Symbols:**

```
ffffffff81250170-ffffffff81250298: insert_extent (STB_LOCAL)
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
In kernel/user_namespace.c (ffff8000101e61d0)
Location: kernel/user_namespace.c:759
Inline: True
Inline callers:
  - kernel/user_namespace.c:map_write
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
In kernel/user_namespace.c (c0426c70)
Location: kernel/user_namespace.c:759
Inline: True
Inline callers:
  - kernel/user_namespace.c:map_write
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
In kernel/user_namespace.c (c000000000256c00)
Location: kernel/user_namespace.c:759
Inline: True
Inline callers:
  - kernel/user_namespace.c:map_write
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
In kernel/user_namespace.c (ffffffe00015bd6a)
Location: kernel/user_namespace.c:759
Inline: True
Inline callers:
  - kernel/user_namespace.c:map_write
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
In kernel/user_namespace.c (ffffffff8116ab5d)
Location: kernel/user_namespace.c:759
Inline: True
Inline callers:
  - kernel/user_namespace.c:map_write
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
In kernel/user_namespace.c (ffffffff8115dd5d)
Location: kernel/user_namespace.c:759
Inline: True
Inline callers:
  - kernel/user_namespace.c:map_write
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
In kernel/user_namespace.c (ffffffff8116892d)
Location: kernel/user_namespace.c:759
Inline: True
Inline callers:
  - kernel/user_namespace.c:map_write
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
In kernel/user_namespace.c (ffffffff8117601d)
Location: kernel/user_namespace.c:759
Inline: True
Inline callers:
  - kernel/user_namespace.c:map_write
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>6.2</code> and <code>6.5</code> ✅
</li>
<li>
No changes between <code>6.5</code> and <code>6.8</code> ✅
</li>
</ul>
