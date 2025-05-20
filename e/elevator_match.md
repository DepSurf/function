# Function: <code>elevator_match</code>

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
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
bool elevator_match(const struct elevator_type *e, const char *name);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/elevator.c (ffffffff81448f60)
Location: block/elevator.c:86
Inline: True
Direct callers:
  - block/elevator.c:elv_iosched_show
  - block/elevator.c:elv_iosched_store
  - block/elevator.c:elv_register
  - block/elevator.c:elv_register
  - block/elevator.c:elevator_find
```
**Symbols:**

```
ffffffff81448f60-ffffffff81448fa9: elevator_match (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
bool elevator_match(const struct elevator_type *e, const char *name);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/elevator.c (ffffffff8147bf90)
Location: block/elevator.c:86
Inline: True
Direct callers:
  - block/elevator.c:elv_iosched_show
  - block/elevator.c:elv_iosched_store
  - block/elevator.c:elv_register
  - block/elevator.c:elv_register
  - block/elevator.c:elevator_find
```
**Symbols:**

```
ffffffff8147bf90-ffffffff8147bfd9: elevator_match (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
bool elevator_match(const struct elevator_type *e, const char *name);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/elevator.c (ffffffff8149a1d0)
Location: block/elevator.c:85
Inline: True
Direct callers:
  - block/elevator.c:elv_iosched_show
  - block/elevator.c:elv_iosched_store
  - block/elevator.c:elevator_find
```
**Symbols:**

```
ffffffff8149a1d0-ffffffff8149a219: elevator_match (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In block/elevator.c (ffffffff814c82a0)
Location: block/elevator.c:86
Inline: True
Direct callers:
  - block/elevator.c:elv_iosched_show
  - block/elevator.c:elv_iosched_store
  - block/elevator.c:elevator_find
```
**Symbols:**

```
ffffffff814c82a0-ffffffff814c82e3: elevator_match.isra.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
bool elevator_match(const struct elevator_type *e, const char *name, unsigned int required_features);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/elevator.c (ffffffff814e1390)
Location: block/elevator.c:101
Inline: True
Direct callers:
  - block/elevator.c:elv_iosched_show
  - block/elevator.c:elv_iosched_show
  - block/elevator.c:elv_iosched_store
  - block/elevator.c:elevator_find
```
**Symbols:**

```
ffffffff814e1390-ffffffff814e13ea: elevator_match (STB_LOCAL)
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
In block/elevator.c (ffffffff81540e2e)
Location: block/elevator.c:101
Inline: True
Inline callers:
  - block/elevator.c:elv_iosched_show
  - block/elevator.c:elv_iosched_show
  - block/elevator.c:elv_iosched_show
  - block/elevator.c:__elevator_change
  - block/elevator.c:__elevator_change
  - block/elevator.c:elevator_find
  - block/elevator.c:elevator_find
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
In block/elevator.c (ffffffff8155d59a)
Location: block/elevator.c:101
Inline: True
Inline callers:
  - block/elevator.c:elv_iosched_show
  - block/elevator.c:elv_iosched_show
  - block/elevator.c:elv_iosched_show
  - block/elevator.c:__elevator_change
  - block/elevator.c:__elevator_change
  - block/elevator.c:elevator_find
  - block/elevator.c:elevator_find
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
In block/elevator.c (ffffffff81565e3a)
Location: block/elevator.c:101
Inline: True
Inline callers:
  - block/elevator.c:elv_iosched_show
  - block/elevator.c:elv_iosched_show
  - block/elevator.c:elv_iosched_show
  - block/elevator.c:__elevator_change
  - block/elevator.c:__elevator_change
  - block/elevator.c:elevator_find
  - block/elevator.c:elevator_find
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
In block/elevator.c (ffffffff815ca20a)
Location: block/elevator.c:101
Inline: True
Inline callers:
  - block/elevator.c:elv_iosched_show
  - block/elevator.c:elv_iosched_show
  - block/elevator.c:elv_iosched_show
  - block/elevator.c:__elevator_change
  - block/elevator.c:__elevator_change
  - block/elevator.c:elevator_find
  - block/elevator.c:elevator_find
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
In block/elevator.c (ffffffff8167564c)
Location: block/elevator.c:101
Inline: True
Inline callers:
  - block/elevator.c:elv_iosched_show
  - block/elevator.c:elv_iosched_show
  - block/elevator.c:elv_iosched_show
  - block/elevator.c:__elevator_change
  - block/elevator.c:__elevator_change
  - block/elevator.c:elevator_find
  - block/elevator.c:elevator_find
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
In block/elevator.c (ffffffff817312b7)
Location: block/elevator.c:100
Inline: True
Inline callers:
  - block/elevator.c:elv_iosched_store
  - block/elevator.c:__elevator_find
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
In block/elevator.c (ffffffff8176d4fb)
Location: block/elevator.c:100
Inline: True
Inline callers:
  - block/elevator.c:elv_iosched_store
  - block/elevator.c:__elevator_find
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
In block/elevator.c (ffffffff817af728)
Location: block/elevator.c:100
Inline: True
Inline callers:
  - block/elevator.c:elv_iosched_store
  - block/elevator.c:__elevator_find
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: Selective Inline ⚠️</summary>

```c
bool elevator_match(const struct elevator_type *e, const char *name, unsigned int required_features);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/elevator.c (ffff8000105de368)
Location: block/elevator.c:101
Inline: True
Direct callers:
  - block/elevator.c:elv_iosched_show
  - block/elevator.c:elv_iosched_show
  - block/elevator.c:elv_iosched_store
  - block/elevator.c:elevator_find
```
**Symbols:**

```
ffff8000105de368-ffff8000105de3e0: elevator_match (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
bool elevator_match(const struct elevator_type *e, const char *name, unsigned int required_features);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/elevator.c (c078b420)
Location: block/elevator.c:101
Inline: True
Direct callers:
  - block/elevator.c:elv_iosched_show
  - block/elevator.c:elv_iosched_show
  - block/elevator.c:elv_iosched_store
  - block/elevator.c:elevator_find
```
**Symbols:**

```
c078b420-c078b488: elevator_match (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
bool elevator_match(const struct elevator_type *e, const char *name, unsigned int required_features);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/elevator.c (c00000000076fbb0)
Location: block/elevator.c:101
Inline: True
Direct callers:
  - block/elevator.c:elv_iosched_show
  - block/elevator.c:elv_iosched_show
  - block/elevator.c:elv_iosched_store
  - block/elevator.c:elevator_find
```
**Symbols:**

```
c00000000076fbb0-c00000000076fef8: elevator_match (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
bool elevator_match(const struct elevator_type *e, const char *name, unsigned int required_features);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/elevator.c (ffffffe000420f76)
Location: block/elevator.c:101
Inline: True
Direct callers:
  - block/elevator.c:elv_iosched_show
  - block/elevator.c:elv_iosched_show
  - block/elevator.c:elv_iosched_store
  - block/elevator.c:elevator_find
```
**Symbols:**

```
ffffffe000420f76-ffffffe000420fda: elevator_match (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: Selective Inline ⚠️</summary>

```c
bool elevator_match(const struct elevator_type *e, const char *name, unsigned int required_features);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/elevator.c (ffffffff814d9970)
Location: block/elevator.c:101
Inline: True
Direct callers:
  - block/elevator.c:elv_iosched_show
  - block/elevator.c:elv_iosched_show
  - block/elevator.c:elv_iosched_store
  - block/elevator.c:elevator_find
```
**Symbols:**

```
ffffffff814d9970-ffffffff814d99ca: elevator_match (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
bool elevator_match(const struct elevator_type *e, const char *name, unsigned int required_features);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/elevator.c (ffffffff814ca320)
Location: block/elevator.c:101
Inline: True
Direct callers:
  - block/elevator.c:elv_iosched_show
  - block/elevator.c:elv_iosched_show
  - block/elevator.c:elv_iosched_store
  - block/elevator.c:elevator_find
```
**Symbols:**

```
ffffffff814ca320-ffffffff814ca37a: elevator_match (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
bool elevator_match(const struct elevator_type *e, const char *name, unsigned int required_features);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/elevator.c (ffffffff814d5a00)
Location: block/elevator.c:101
Inline: True
Direct callers:
  - block/elevator.c:elv_iosched_show
  - block/elevator.c:elv_iosched_show
  - block/elevator.c:elv_iosched_store
  - block/elevator.c:elevator_find
```
**Symbols:**

```
ffffffff814d5a00-ffffffff814d5a5a: elevator_match (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
bool elevator_match(const struct elevator_type *e, const char *name, unsigned int required_features);
```

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In block/elevator.c (ffffffff814ee620)
Location: block/elevator.c:101
Inline: True
Direct callers:
  - block/elevator.c:elv_iosched_show
  - block/elevator.c:elv_iosched_show
  - block/elevator.c:elv_iosched_store
  - block/elevator.c:elevator_find
```
**Symbols:**

```
ffffffff814ee620-ffffffff814ee67a: elevator_match (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
<li>
No changes between <code>amd64</code> and <code>arm64</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>armhf</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>ppc64el</code> ✅
</li>
<li>
No changes between <code>amd64</code> and <code>riscv64</code> ✅
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>generic</code> and <code>aws</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>azure</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>gcp</code> ✅
</li>
<li>
No changes between <code>generic</code> and <code>lowlatency</code> ✅
</li>
</ul>
