# Function: <code>loop_set_status_from_info</code>

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
<summary>In <code>5.8</code>: ✅</summary>

```c
int loop_set_status_from_info(struct loop_device *lo, const struct loop_info64 *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/block/loop.c (ffffffff817e94b0)
Location: drivers/block/loop.c:1054
Inline: False
Direct callers:
  - drivers/block/loop.c:loop_set_status
  - drivers/block/loop.c:loop_set_status
  - drivers/block/loop.c:loop_configure
```
**Symbols:**

```
ffffffff817e94b0-ffffffff817e982f: loop_set_status_from_info (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
int loop_set_status_from_info(struct loop_device *lo, const struct loop_info64 *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/block/loop.c (ffffffff817fdf30)
Location: drivers/block/loop.c:1050
Inline: False
Direct callers:
  - drivers/block/loop.c:loop_set_status
  - drivers/block/loop.c:loop_set_status
  - drivers/block/loop.c:loop_configure
```
**Symbols:**

```
ffffffff817fdf30-ffffffff817fe2af: loop_set_status_from_info (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
int loop_set_status_from_info(struct loop_device *lo, const struct loop_info64 *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/block/loop.c (ffffffff817e2ae0)
Location: drivers/block/loop.c:1063
Inline: False
Direct callers:
  - drivers/block/loop.c:loop_set_status
  - drivers/block/loop.c:loop_set_status
  - drivers/block/loop.c:loop_configure
```
**Symbols:**

```
ffffffff817e2ae0-ffffffff817e2e54: loop_set_status_from_info (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
int loop_set_status_from_info(struct loop_device *lo, const struct loop_info64 *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/block/loop.c (ffffffff8186dc00)
Location: drivers/block/loop.c:1167
Inline: False
Direct callers:
  - drivers/block/loop.c:loop_set_status
  - drivers/block/loop.c:loop_set_status
  - drivers/block/loop.c:loop_configure
```
**Symbols:**

```
ffffffff8186dc00-ffffffff8186df91: loop_set_status_from_info (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Transformation ⚠️</summary>

```c
int loop_set_status_from_info(struct loop_device *lo, const struct loop_info64 *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** True

**Instances:**

```
In drivers/block/loop.c (0)
Location: drivers/block/loop.c:961
Inline: False
Direct callers:
  - drivers/block/loop.c:loop_set_status
  - drivers/block/loop.c:loop_configure
```
**Symbols:**

```
ffffffff819b4ec0-ffffffff819b4f95: loop_set_status_from_info (STB_LOCAL)
ffffffff81ece0f7-ffffffff81ece119: loop_set_status_from_info.cold (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
int loop_set_status_from_info(struct loop_device *lo, const struct loop_info64 *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/block/loop.c (ffffffff81b2a160)
Location: drivers/block/loop.c:961
Inline: False
Direct callers:
  - drivers/block/loop.c:loop_set_status
  - drivers/block/loop.c:loop_configure
```
**Symbols:**

```
ffffffff81b2a160-ffffffff81b2a25f: loop_set_status_from_info (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
int loop_set_status_from_info(struct loop_device *lo, const struct loop_info64 *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/block/loop.c (ffffffff81b7a390)
Location: drivers/block/loop.c:961
Inline: False
Direct callers:
  - drivers/block/loop.c:loop_set_status
  - drivers/block/loop.c:loop_configure
```
**Symbols:**

```
ffffffff81b7a390-ffffffff81b7a48f: loop_set_status_from_info (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
int loop_set_status_from_info(struct loop_device *lo, const struct loop_info64 *info);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/block/loop.c (ffffffff81bce2f0)
Location: drivers/block/loop.c:957
Inline: False
Direct callers:
  - drivers/block/loop.c:loop_set_status
  - drivers/block/loop.c:loop_configure
```
**Symbols:**

```
ffffffff81bce2f0-ffffffff81bce3ef: loop_set_status_from_info (STB_LOCAL)
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
