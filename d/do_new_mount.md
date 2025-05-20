# Function: <code>do_new_mount</code>

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
In fs/namespace.c (ffffffff8122ecf6)
Location: fs/namespace.c:2378
Inline: True
Inline callers:
  - fs/namespace.c:do_mount
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
In fs/namespace.c (ffffffff81257517)
Location: fs/namespace.c:2381
Inline: True
Inline callers:
  - fs/namespace.c:do_mount
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
In fs/namespace.c (ffffffff8126a9a7)
Location: fs/namespace.c:2500
Inline: True
Inline callers:
  - fs/namespace.c:do_mount
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
In fs/namespace.c (ffffffff81278147)
Location: fs/namespace.c:2442
Inline: True
Inline callers:
  - fs/namespace.c:do_mount
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
In fs/namespace.c (ffffffff8129abae)
Location: fs/namespace.c:2507
Inline: True
Inline callers:
  - fs/namespace.c:do_mount
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
In fs/namespace.c (ffffffff812c0d44)
Location: fs/namespace.c:2538
Inline: True
Inline callers:
  - fs/namespace.c:do_mount
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
In fs/namespace.c (ffffffff812d5fb1)
Location: fs/namespace.c:2508
Inline: True
Inline callers:
  - fs/namespace.c:do_mount
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
In fs/namespace.c (ffffffff812f472c)
Location: fs/namespace.c:2757
Inline: True
Inline callers:
  - fs/namespace.c:do_mount
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
In fs/namespace.c (ffffffff813062d9)
Location: fs/namespace.c:2790
Inline: True
Inline callers:
  - fs/namespace.c:do_mount
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
int do_new_mount(struct path *path, const char *fstype, int sb_flags, int mnt_flags, const char *name, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff8133f230)
Location: fs/namespace.c:2843
Inline: False
Direct callers:
  - fs/namespace.c:do_mount
```
**Symbols:**

```
ffffffff8133f230-ffffffff8133f3c5: do_new_mount (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int do_new_mount(struct path *path, const char *fstype, int sb_flags, int mnt_flags, const char *name, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff8134b290)
Location: fs/namespace.c:2849
Inline: False
Direct callers:
  - fs/namespace.c:path_mount
```
**Symbols:**

```
ffffffff8134b290-ffffffff8134b425: do_new_mount (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int do_new_mount(struct path *path, const char *fstype, int sb_flags, int mnt_flags, const char *name, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff81351a00)
Location: fs/namespace.c:2882
Inline: False
Direct callers:
  - fs/namespace.c:path_mount
```
**Symbols:**

```
ffffffff81351a00-ffffffff81351cc2: do_new_mount (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int do_new_mount(struct path *path, const char *fstype, int sb_flags, int mnt_flags, const char *name, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff8139fd70)
Location: fs/namespace.c:2956
Inline: False
Direct callers:
  - fs/namespace.c:path_mount
```
**Symbols:**

```
ffffffff8139fd70-ffffffff813a0032: do_new_mount (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int do_new_mount(struct path *path, const char *fstype, int sb_flags, int mnt_flags, const char *name, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff814233a0)
Location: fs/namespace.c:2999
Inline: False
Direct callers:
  - fs/namespace.c:path_mount
```
**Symbols:**

```
ffffffff814233a0-ffffffff814236bf: do_new_mount (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int do_new_mount(struct path *path, const char *fstype, int sb_flags, int mnt_flags, const char *name, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff814afaf0)
Location: fs/namespace.c:3104
Inline: False
Direct callers:
  - fs/namespace.c:path_mount
```
**Symbols:**

```
ffffffff814afaf0-ffffffff814afe0f: do_new_mount (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int do_new_mount(struct path *path, const char *fstype, int sb_flags, int mnt_flags, const char *name, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff814e4b20)
Location: fs/namespace.c:3294
Inline: False
Direct callers:
  - fs/namespace.c:path_mount
```
**Symbols:**

```
ffffffff814e4b20-ffffffff814e4e48: do_new_mount (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int do_new_mount(struct path *path, const char *fstype, int sb_flags, int mnt_flags, const char *name, void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In fs/namespace.c (ffffffff81518940)
Location: fs/namespace.c:3305
Inline: False
Direct callers:
  - fs/namespace.c:path_mount
```
**Symbols:**

```
ffffffff81518940-ffffffff81518c76: do_new_mount (STB_LOCAL)
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
In fs/namespace.c (ffff8000103b98d0)
Location: fs/namespace.c:2790
Inline: True
Inline callers:
  - fs/namespace.c:do_mount
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
In fs/namespace.c (c05973dc)
Location: fs/namespace.c:2790
Inline: True
Inline callers:
  - fs/namespace.c:do_mount
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
In fs/namespace.c (c0000000004b6e8c)
Location: fs/namespace.c:2790
Inline: True
Inline callers:
  - fs/namespace.c:do_mount
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
In fs/namespace.c (ffffffe00027bbe6)
Location: fs/namespace.c:2790
Inline: True
Inline callers:
  - fs/namespace.c:do_mount
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
In fs/namespace.c (ffffffff812fe8b9)
Location: fs/namespace.c:2790
Inline: True
Inline callers:
  - fs/namespace.c:do_mount
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
In fs/namespace.c (ffffffff812ef4d9)
Location: fs/namespace.c:2790
Inline: True
Inline callers:
  - fs/namespace.c:do_mount
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
In fs/namespace.c (ffffffff812fc6a9)
Location: fs/namespace.c:2790
Inline: True
Inline callers:
  - fs/namespace.c:do_mount
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
In fs/namespace.c (ffffffff8130da09)
Location: fs/namespace.c:2790
Inline: True
Inline callers:
  - fs/namespace.c:do_mount
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
