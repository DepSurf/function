# Function: <code>cgroup1_root_to_use</code>

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
<details>
<summary>In <code>5.3</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In kernel/cgroup/cgroup-v1.c (ffffffff8115d8c3)
Location: kernel/cgroup/cgroup-v1.c:1131
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_get_tree
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
In kernel/cgroup/cgroup-v1.c (ffffffff811694d3)
Location: kernel/cgroup/cgroup-v1.c:1113
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_get_tree
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Transformation ⚠️</summary>

```c
int cgroup1_root_to_use(struct fs_context *fc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/cgroup/cgroup-v1.c (0)
Location: kernel/cgroup/cgroup-v1.c:1107
Inline: False
Direct callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_get_tree
```
**Symbols:**

```
ffffffff81179f90-ffffffff8117a224: cgroup1_root_to_use (STB_LOCAL)
ffffffff8117b3b4-ffffffff8117b3c5: cgroup1_root_to_use.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Transformation ⚠️</summary>

```c
int cgroup1_root_to_use(struct fs_context *fc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/cgroup/cgroup-v1.c (0)
Location: kernel/cgroup/cgroup-v1.c:1112
Inline: False
Direct callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_get_tree
```
**Symbols:**

```
ffffffff81176cf0-ffffffff81176fa0: cgroup1_root_to_use (STB_LOCAL)
ffffffff81be475b-ffffffff81be476c: cgroup1_root_to_use.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Transformation ⚠️</summary>

```c
int cgroup1_root_to_use(struct fs_context *fc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/cgroup/cgroup-v1.c (0)
Location: kernel/cgroup/cgroup-v1.c:1118
Inline: False
Direct callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_get_tree
```
**Symbols:**

```
ffffffff81177880-ffffffff81177b21: cgroup1_root_to_use (STB_LOCAL)
ffffffff81bd6584-ffffffff81bd6595: cgroup1_root_to_use.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Transformation ⚠️</summary>

```c
int cgroup1_root_to_use(struct fs_context *fc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/cgroup/cgroup-v1.c (0)
Location: kernel/cgroup/cgroup-v1.c:1139
Inline: False
Direct callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_get_tree
```
**Symbols:**

```
ffffffff8119f190-ffffffff8119f44a: cgroup1_root_to_use (STB_LOCAL)
ffffffff81cb3125-ffffffff81cb3166: cgroup1_root_to_use.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int cgroup1_root_to_use(struct fs_context *fc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/cgroup/cgroup-v1.c (0)
Location: kernel/cgroup/cgroup-v1.c:1130
Inline: False
Direct callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_get_tree
```
**Symbols:**

```
ffffffff811cf7d0-ffffffff811cfaa8: cgroup1_root_to_use (STB_LOCAL)
ffffffff81e63f19-ffffffff81e63f5a: cgroup1_root_to_use.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Transformation ⚠️</summary>

```c
int cgroup1_root_to_use(struct fs_context *fc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/cgroup/cgroup-v1.c (0)
Location: kernel/cgroup/cgroup-v1.c:1142
Inline: False
Direct callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_get_tree
```
**Symbols:**

```
ffffffff81213010-ffffffff8121330c: cgroup1_root_to_use (STB_LOCAL)
ffffffff8205c3b7-ffffffff8205c3e7: cgroup1_root_to_use.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Transformation ⚠️</summary>

```c
int cgroup1_root_to_use(struct fs_context *fc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/cgroup/cgroup-v1.c (0)
Location: kernel/cgroup/cgroup-v1.c:1142
Inline: False
Direct callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_get_tree
```
**Symbols:**

```
ffffffff81228920-ffffffff81228c1c: cgroup1_root_to_use (STB_LOCAL)
ffffffff820dabca-ffffffff820dabfa: cgroup1_root_to_use.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Transformation ⚠️</summary>

```c
int cgroup1_root_to_use(struct fs_context *fc);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In kernel/cgroup/cgroup-v1.c (0)
Location: kernel/cgroup/cgroup-v1.c:1141
Inline: False
Direct callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_get_tree
```
**Symbols:**

```
ffffffff81240730-ffffffff81240a67: cgroup1_root_to_use (STB_LOCAL)
ffffffff821b685d-ffffffff821b688d: cgroup1_root_to_use.cold (STB_LOCAL)
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
In kernel/cgroup/cgroup-v1.c (ffff8000101dc718)
Location: kernel/cgroup/cgroup-v1.c:1113
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_get_tree
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
In kernel/cgroup/cgroup-v1.c (c041e9c0)
Location: kernel/cgroup/cgroup-v1.c:1113
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_get_tree
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
In kernel/cgroup/cgroup-v1.c (c00000000024a40c)
Location: kernel/cgroup/cgroup-v1.c:1113
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_get_tree
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
In kernel/cgroup/cgroup-v1.c (ffffffe0001546a2)
Location: kernel/cgroup/cgroup-v1.c:1113
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_get_tree
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
In kernel/cgroup/cgroup-v1.c (ffffffff81161af3)
Location: kernel/cgroup/cgroup-v1.c:1113
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_get_tree
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
In kernel/cgroup/cgroup-v1.c (ffffffff81154d53)
Location: kernel/cgroup/cgroup-v1.c:1113
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_get_tree
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
In kernel/cgroup/cgroup-v1.c (ffffffff8115f8c3)
Location: kernel/cgroup/cgroup-v1.c:1113
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_get_tree
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
In kernel/cgroup/cgroup-v1.c (ffffffff8116cb66)
Location: kernel/cgroup/cgroup-v1.c:1113
Inline: True
Inline callers:
  - kernel/cgroup/cgroup-v1.c:cgroup1_get_tree
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
