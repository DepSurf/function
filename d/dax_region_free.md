# Function: <code>dax_region_free</code>

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
<summary>In <code>5.3</code>: ✅</summary>

```c
void dax_region_free(struct kref *kref);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dax/bus.c (ffffffff8173fb20)
Location: drivers/dax/bus.c:205
Inline: False
Direct callers:
  - drivers/dax/bus.c:dev_dax_release
  - drivers/dax/bus.c:dax_region_unregister
```
**Symbols:**

```
ffffffff8173fb20-ffffffff8173fb34: dax_region_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void dax_region_free(struct kref *kref);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dax/bus.c (ffffffff81763d00)
Location: drivers/dax/bus.c:205
Inline: False
Direct callers:
  - drivers/dax/bus.c:dev_dax_release
  - drivers/dax/bus.c:dax_region_unregister
```
**Symbols:**

```
ffffffff81763d00-ffffffff81763d14: dax_region_free (STB_LOCAL)
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
In drivers/dax/bus.c (ffffffff81824423)
Location: drivers/dax/bus.c:205
Inline: True
Inline callers:
  - drivers/dax/bus.c:dev_dax_release
  - drivers/dax/bus.c:alloc_dax_region
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
In drivers/dax/bus.c (ffffffff81833db3)
Location: drivers/dax/bus.c:520
Inline: True
Inline callers:
  - drivers/dax/bus.c:dev_dax_release
  - drivers/dax/bus.c:alloc_dax_region
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
In drivers/dax/bus.c (ffffffff81816fa3)
Location: drivers/dax/bus.c:521
Inline: True
Inline callers:
  - drivers/dax/bus.c:dev_dax_release
  - drivers/dax/bus.c:alloc_dax_region
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
In drivers/dax/bus.c (ffffffff818a15f3)
Location: drivers/dax/bus.c:519
Inline: True
Inline callers:
  - drivers/dax/bus.c:dev_dax_release
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
In drivers/dax/bus.c (ffffffff819ead0d)
Location: drivers/dax/bus.c:549
Inline: True
Inline callers:
  - drivers/dax/bus.c:dev_dax_release
  - drivers/dax/bus.c:alloc_dax_region
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
In drivers/dax/bus.c (ffffffff81b6781d)
Location: drivers/dax/bus.c:549
Inline: True
Inline callers:
  - drivers/dax/bus.c:dev_dax_release
  - drivers/dax/bus.c:alloc_dax_region
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
In drivers/dax/bus.c (ffffffff81bba410)
Location: drivers/dax/bus.c:449
Inline: True
Inline callers:
  - drivers/dax/bus.c:dax_region_unregister
  - drivers/dax/bus.c:__free_dev_dax_id
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
In drivers/dax/bus.c (ffffffff81c0e7e0)
Location: drivers/dax/bus.c:450
Inline: True
Inline callers:
  - drivers/dax/bus.c:dax_region_unregister
  - drivers/dax/bus.c:__free_dev_dax_id
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
In drivers/dax/bus.c (ffff800010963d58)
Location: drivers/dax/bus.c:205
Inline: True
Inline callers:
  - drivers/dax/bus.c:dax_region_put
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
In drivers/dax/bus.c (c0a3a9b0)
Location: drivers/dax/bus.c:205
Inline: True
Inline callers:
  - drivers/dax/bus.c:dax_region_put
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
In drivers/dax/bus.c (c000000000a1a504)
Location: drivers/dax/bus.c:205
Inline: True
Inline callers:
  - drivers/dax/bus.c:dax_region_put
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
In drivers/dax/bus.c (ffffffe0005d1150)
Location: drivers/dax/bus.c:205
Inline: True
Inline callers:
  - drivers/dax/bus.c:dev_dax_release
  - drivers/dax/bus.c:dax_region_unregister
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>aws</code>: ✅</summary>

```c
void dax_region_free(struct kref *kref);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dax/bus.c (ffffffff817183f0)
Location: drivers/dax/bus.c:205
Inline: False
Direct callers:
  - drivers/dax/bus.c:dev_dax_release
  - drivers/dax/bus.c:dax_region_unregister
```
**Symbols:**

```
ffffffff817183f0-ffffffff81718404: dax_region_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void dax_region_free(struct kref *kref);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dax/bus.c (ffffffff816f0920)
Location: drivers/dax/bus.c:205
Inline: False
Direct callers:
  - drivers/dax/bus.c:dev_dax_release
  - drivers/dax/bus.c:dax_region_unregister
```
**Symbols:**

```
ffffffff816f0920-ffffffff816f0934: dax_region_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void dax_region_free(struct kref *kref);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dax/bus.c (ffffffff817571c0)
Location: drivers/dax/bus.c:205
Inline: False
Direct callers:
  - drivers/dax/bus.c:dev_dax_release
  - drivers/dax/bus.c:dax_region_unregister
```
**Symbols:**

```
ffffffff817571c0-ffffffff817571d4: dax_region_free (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void dax_region_free(struct kref *kref);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/dax/bus.c (ffffffff81772660)
Location: drivers/dax/bus.c:205
Inline: False
Direct callers:
  - drivers/dax/bus.c:dev_dax_release
  - drivers/dax/bus.c:dax_region_unregister
```
**Symbols:**

```
ffffffff81772660-ffffffff81772674: dax_region_free (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
</ul>
<b>Arch</b>
<ul>
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
