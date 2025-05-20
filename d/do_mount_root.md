# Function: <code>do_mount_root</code>

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
In init/do_mounts.c (ffffffff81f5a450)
Location: init/do_mounts.c:363
Inline: True
Inline callers:
  - init/do_mounts.c:mount_block_root
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
In init/do_mounts.c (ffffffff81f823f2)
Location: init/do_mounts.c:363
Inline: True
Inline callers:
  - init/do_mounts.c:mount_block_root
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
In init/do_mounts.c (ffffffff81fbe490)
Location: init/do_mounts.c:363
Inline: True
Inline callers:
  - init/do_mounts.c:mount_block_root
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
In init/do_mounts.c (ffffffff8209e5d6)
Location: init/do_mounts.c:363
Inline: True
Inline callers:
  - init/do_mounts.c:mount_block_root
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
In init/do_mounts.c (ffffffff826a45a6)
Location: init/do_mounts.c:363
Inline: True
Inline callers:
  - init/do_mounts.c:mount_block_root
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
In init/do_mounts.c (ffffffff826cd6b6)
Location: init/do_mounts.c:363
Inline: True
Inline callers:
  - init/do_mounts.c:mount_block_root
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
In init/do_mounts.c (ffffffff82883694)
Location: init/do_mounts.c:385
Inline: True
Inline callers:
  - init/do_mounts.c:mount_block_root
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
In init/do_mounts.c (ffffffff8289a6ae)
Location: init/do_mounts.c:386
Inline: True
Inline callers:
  - init/do_mounts.c:mount_block_root
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
In init/do_mounts.c (ffffffff8289d693)
Location: init/do_mounts.c:386
Inline: True
Inline callers:
  - init/do_mounts.c:mount_block_root
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
In init/do_mounts.c (ffffffff82cc3c70)
Location: init/do_mounts.c:390
Inline: True
Inline callers:
  - init/do_mounts.c:mount_block_root
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
In init/do_mounts.c (ffffffff82fafd9e)
Location: init/do_mounts.c:374
Inline: True
Inline callers:
  - init/do_mounts.c:mount_block_root
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
In init/do_mounts.c (ffffffff831b9e01)
Location: init/do_mounts.c:374
Inline: True
Inline callers:
  - init/do_mounts.c:mount_block_root
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int do_mount_root(const char *name, const char *fs, const int flags, const void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In init/do_mounts.c (ffffffff8329a01f)
Location: init/do_mounts.c:358
Inline: False
Direct callers:
  - init/do_mounts.c:mount_root
  - init/do_mounts.c:mount_block_root
```
**Symbols:**

```
ffffffff8329a01f-ffffffff8329a134: do_mount_root (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int do_mount_root(const char *name, const char *fs, const int flags, const void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In init/do_mounts.c (ffffffff834482dc)
Location: init/do_mounts.c:357
Inline: False
Direct callers:
  - init/do_mounts.c:mount_nodev_root
  - init/do_mounts.c:mount_block_root
```
**Symbols:**

```
ffffffff834482dc-ffffffff83448401: do_mount_root (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int do_mount_root(const char *name, const char *fs, const int flags, const void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In init/do_mounts.c (ffffffff83e61ec0)
Location: init/do_mounts.c:357
Inline: False
Direct callers:
  - init/do_mounts.c:mount_nodev_root
  - init/do_mounts.c:mount_block_root
```
**Symbols:**

```
ffffffff83e61ec0-ffffffff83e620ab: do_mount_root (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int do_mount_root(const char *name, const char *fs, const int flags, const void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In init/do_mounts.c (ffffffff836822e0)
Location: init/do_mounts.c:122
Inline: False
Direct callers:
  - init/do_mounts.c:mount_nodev_root
  - init/do_mounts.c:mount_root_generic
```
**Symbols:**

```
ffffffff836822e0-ffffffff836824cb: do_mount_root (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int do_mount_root(const char *name, const char *fs, const int flags, const void *data);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In init/do_mounts.c (ffffffff838b1370)
Location: init/do_mounts.c:148
Inline: False
Direct callers:
  - init/do_mounts.c:mount_nodev_root
  - init/do_mounts.c:mount_root_generic
```
**Symbols:**

```
ffffffff838b1370-ffffffff838b1558: do_mount_root (STB_LOCAL)
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
In init/do_mounts.c (ffff8000114317d4)
Location: init/do_mounts.c:386
Inline: True
Inline callers:
  - init/do_mounts.c:mount_block_root
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
In init/do_mounts.c (c15017dc)
Location: init/do_mounts.c:386
Inline: True
Inline callers:
  - init/do_mounts.c:mount_block_root
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
In init/do_mounts.c (c000000001344b88)
Location: init/do_mounts.c:386
Inline: True
Inline callers:
  - init/do_mounts.c:mount_block_root
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
In init/do_mounts.c (ffffffe00000148a)
Location: init/do_mounts.c:386
Inline: True
Inline callers:
  - init/do_mounts.c:mount_block_root
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
In init/do_mounts.c (ffffffff8288b693)
Location: init/do_mounts.c:386
Inline: True
Inline callers:
  - init/do_mounts.c:mount_block_root
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
In init/do_mounts.c (ffffffff82889610)
Location: init/do_mounts.c:386
Inline: True
Inline callers:
  - init/do_mounts.c:mount_block_root
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
In init/do_mounts.c (ffffffff8289e693)
Location: init/do_mounts.c:386
Inline: True
Inline callers:
  - init/do_mounts.c:mount_block_root
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
In init/do_mounts.c (ffffffff8289e698)
Location: init/do_mounts.c:386
Inline: True
Inline callers:
  - init/do_mounts.c:mount_block_root
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
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
