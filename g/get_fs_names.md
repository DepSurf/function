# Function: <code>get_fs_names</code>

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
In init/do_mounts.c (ffffffff81f5a3b2)
Location: init/do_mounts.c:336
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
In init/do_mounts.c (ffffffff81f82360)
Location: init/do_mounts.c:336
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
In init/do_mounts.c (ffffffff81fbe3fe)
Location: init/do_mounts.c:336
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
In init/do_mounts.c (ffffffff8209e53c)
Location: init/do_mounts.c:336
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
In init/do_mounts.c (ffffffff826a450a)
Location: init/do_mounts.c:336
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
In init/do_mounts.c (ffffffff826cd62f)
Location: init/do_mounts.c:336
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
In init/do_mounts.c (ffffffff82883606)
Location: init/do_mounts.c:358
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
In init/do_mounts.c (ffffffff8289a623)
Location: init/do_mounts.c:359
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
In init/do_mounts.c (ffffffff8289d608)
Location: init/do_mounts.c:359
Inline: True
Inline callers:
  - init/do_mounts.c:mount_block_root
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void get_fs_names(char *page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In init/do_mounts.c (ffffffff82cc3af9)
Location: init/do_mounts.c:363
Inline: False
Direct callers:
  - init/do_mounts.c:mount_block_root
```
**Symbols:**

```
ffffffff82cc3af9-ffffffff82cc3b80: get_fs_names (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void get_fs_names(char *page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In init/do_mounts.c (ffffffff82fafbe6)
Location: init/do_mounts.c:347
Inline: False
Direct callers:
  - init/do_mounts.c:mount_block_root
```
**Symbols:**

```
ffffffff82fafbe6-ffffffff82fafc6d: get_fs_names (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void get_fs_names(char *page);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In init/do_mounts.c (ffffffff831b9c4a)
Location: init/do_mounts.c:347
Inline: False
Direct callers:
  - init/do_mounts.c:mount_block_root
```
**Symbols:**

```
ffffffff831b9c4a-ffffffff831b9cd1: get_fs_names (STB_LOCAL)
```
</details>
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
<details>
<summary>In <code>arm64</code>: Full Inline ⚠️</summary>

**Collision:** Unique Static

**Inline:** Full

**Transformation:** False

**Instances:**

```
In init/do_mounts.c (ffff800011431738)
Location: init/do_mounts.c:359
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
In init/do_mounts.c (c1501730)
Location: init/do_mounts.c:359
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
In init/do_mounts.c (c000000001344ac0)
Location: init/do_mounts.c:359
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
In init/do_mounts.c (ffffffe0000013f8)
Location: init/do_mounts.c:359
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
In init/do_mounts.c (ffffffff8288b608)
Location: init/do_mounts.c:359
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
In init/do_mounts.c (ffffffff82889585)
Location: init/do_mounts.c:359
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
In init/do_mounts.c (ffffffff8289e608)
Location: init/do_mounts.c:359
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
In init/do_mounts.c (ffffffff8289e60d)
Location: init/do_mounts.c:359
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
No changes between <code>5.8</code> and <code>5.11</code> ✅
</li>
<li>
No changes between <code>5.11</code> and <code>5.13</code> ✅
</li>
</ul>
