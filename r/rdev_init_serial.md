# Function: <code>rdev_init_serial</code>

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
In drivers/md/md.c (ffffffff8196d440)
Location: drivers/md/md.c:148
Inline: True
Inline callers:
  - drivers/md/md.c:md_run
  - drivers/md/md.c:mddev_create_serial_pool
  - drivers/md/md.c:mddev_create_serial_pool
Direct callers:
  - drivers/md/md.c:md_run
  - drivers/md/md.c:mddev_create_serial_pool
  - drivers/md/md.c:mddev_create_serial_pool
```
**Symbols:**

```
ffffffff81962e20-ffffffff81962eb2: rdev_init_serial.part.0 (STB_LOCAL)
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
In drivers/md/md.c (ffffffff81974312)
Location: drivers/md/md.c:146
Inline: True
Inline callers:
  - drivers/md/md.c:md_run
  - drivers/md/md.c:mddev_create_serial_pool
  - drivers/md/md.c:mddev_create_serial_pool
Direct callers:
  - drivers/md/md.c:md_run
  - drivers/md/md.c:mddev_create_serial_pool
  - drivers/md/md.c:mddev_create_serial_pool
```
**Symbols:**

```
ffffffff819696c0-ffffffff81969752: rdev_init_serial.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/md/md.c (ffffffff81958348)
Location: drivers/md/md.c:146
Inline: True
Inline callers:
  - drivers/md/md.c:md_run
  - drivers/md/md.c:mddev_create_serial_pool
  - drivers/md/md.c:mddev_create_serial_pool
Direct callers:
  - drivers/md/md.c:md_run
  - drivers/md/md.c:mddev_create_serial_pool
  - drivers/md/md.c:mddev_create_serial_pool
```
**Symbols:**

```
ffffffff8194d5c0-ffffffff8194d652: rdev_init_serial.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline, Transformation ⚠️</summary>

**Collision:** Unique Static

**Inline:** Selective

**Transformation:** True

**Instances:**

```
In drivers/md/md.c (ffffffff819fdac8)
Location: drivers/md/md.c:147
Inline: True
Inline callers:
  - drivers/md/md.c:md_run
  - drivers/md/md.c:mddev_create_serial_pool
  - drivers/md/md.c:mddev_create_serial_pool
Direct callers:
  - drivers/md/md.c:md_run
  - drivers/md/md.c:mddev_create_serial_pool
  - drivers/md/md.c:mddev_create_serial_pool
```
**Symbols:**

```
ffffffff819f29d0-ffffffff819f2a62: rdev_init_serial.part.0 (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
int rdev_init_serial(struct md_rdev *rdev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/md.c (ffffffff81b555b0)
Location: drivers/md/md.c:148
Inline: False
Direct callers:
  - drivers/md/md.c:md_run
  - drivers/md/md.c:mddev_create_serial_pool
  - drivers/md/md.c:mddev_create_serial_pool
  - drivers/md/md.c:mddev_create_serial_pool
```
**Symbols:**

```
ffffffff81b555b0-ffffffff81b55667: rdev_init_serial (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int rdev_init_serial(struct md_rdev *rdev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/md.c (ffffffff81cee650)
Location: drivers/md/md.c:160
Inline: False
Direct callers:
  - drivers/md/md.c:md_run
  - drivers/md/md.c:mddev_create_serial_pool
  - drivers/md/md.c:mddev_create_serial_pool
  - drivers/md/md.c:mddev_create_serial_pool
```
**Symbols:**

```
ffffffff81cee650-ffffffff81cee707: rdev_init_serial (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int rdev_init_serial(struct md_rdev *rdev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/md.c (ffffffff81d57380)
Location: drivers/md/md.c:146
Inline: False
Direct callers:
  - drivers/md/md.c:md_run
  - drivers/md/md.c:mddev_create_serial_pool
  - drivers/md/md.c:mddev_create_serial_pool
  - drivers/md/md.c:mddev_create_serial_pool
```
**Symbols:**

```
ffffffff81d57380-ffffffff81d57437: rdev_init_serial (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int rdev_init_serial(struct md_rdev *rdev);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/md.c (ffffffff81e0e2e0)
Location: drivers/md/md.c:166
Inline: False
Direct callers:
  - drivers/md/md.c:md_run
  - drivers/md/md.c:mddev_create_serial_pool
  - drivers/md/md.c:mddev_create_serial_pool
```
**Symbols:**

```
ffffffff81e0e2e0-ffffffff81e0e397: rdev_init_serial (STB_LOCAL)
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
<b>Regular</b>
<ul>
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
