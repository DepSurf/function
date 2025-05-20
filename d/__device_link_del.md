# Function: <code>__device_link_del</code>

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
<details>
<summary>In <code>4.10</code>: ✅</summary>

```c
void __device_link_del(struct device_link *link);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff815c72e0)
Location: drivers/base/core.c:297
Inline: False
Direct callers:
  - drivers/base/core.c:device_del
  - drivers/base/core.c:device_del
  - drivers/base/core.c:__device_links_no_driver
  - drivers/base/core.c:device_link_del
```
**Symbols:**

```
ffffffff815c72e0-ffffffff815c7368: __device_link_del (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: ✅</summary>

```c
void __device_link_del(struct device_link *link);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff815dbfc0)
Location: drivers/base/core.c:298
Inline: False
Direct callers:
  - drivers/base/core.c:device_del
  - drivers/base/core.c:device_del
  - drivers/base/core.c:__device_links_no_driver
  - drivers/base/core.c:device_link_del
```
**Symbols:**

```
ffffffff815dbfc0-ffffffff815dc048: __device_link_del (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: ✅</summary>

```c
void __device_link_del(struct device_link *link);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff81642ff0)
Location: drivers/base/core.c:298
Inline: False
Direct callers:
  - drivers/base/core.c:device_del
  - drivers/base/core.c:device_del
  - drivers/base/core.c:__device_links_no_driver
  - drivers/base/core.c:device_link_del
```
**Symbols:**

```
ffffffff81642ff0-ffffffff81643078: __device_link_del (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void __device_link_del(struct kref *kref);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff8167e1c0)
Location: drivers/base/core.c:325
Inline: False
Direct callers:
  - drivers/base/core.c:device_del
  - drivers/base/core.c:device_del
  - drivers/base/core.c:__device_links_no_driver
  - drivers/base/core.c:device_link_del
```
**Symbols:**

```
ffffffff8167e1c0-ffffffff8167e249: __device_link_del (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void __device_link_del(struct kref *kref);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff8169dbd0)
Location: drivers/base/core.c:327
Inline: False
Direct callers:
  - drivers/base/core.c:device_del
  - drivers/base/core.c:device_del
  - drivers/base/core.c:device_links_driver_cleanup
  - drivers/base/core.c:__device_links_no_driver
  - drivers/base/core.c:device_link_remove
  - drivers/base/core.c:device_link_del
```
**Symbols:**

```
ffffffff8169dbd0-ffffffff8169dc59: __device_link_del (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void __device_link_del(struct kref *kref);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff816d4f80)
Location: drivers/base/core.c:420
Inline: False
Direct callers:
  - drivers/base/core.c:device_del
  - drivers/base/core.c:device_del
  - drivers/base/core.c:device_links_driver_cleanup
  - drivers/base/core.c:__device_links_no_driver
```
**Symbols:**

```
ffffffff816d4f80-ffffffff816d501c: __device_link_del (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void __device_link_del(struct kref *kref);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff816f8dc0)
Location: drivers/base/core.c:450
Inline: False
Direct callers:
  - drivers/base/core.c:device_del
  - drivers/base/core.c:device_del
  - drivers/base/core.c:device_links_driver_cleanup
  - drivers/base/core.c:__device_links_no_driver
```
**Symbols:**

```
ffffffff816f8dc0-ffffffff816f8e5c: __device_link_del (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void __device_link_del(struct kref *kref);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff817b1b70)
Location: drivers/base/core.c:558
Inline: False
Direct callers:
  - drivers/base/core.c:device_links_purge
  - drivers/base/core.c:device_links_purge
  - drivers/base/core.c:device_link_drop_managed
```
**Symbols:**

```
ffffffff817b1b70-ffffffff817b1c12: __device_link_del (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void __device_link_del(struct kref *kref);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff817c7ec0)
Location: drivers/base/core.c:825
Inline: False
Direct callers:
  - drivers/base/core.c:device_del
  - drivers/base/core.c:device_del
  - drivers/base/core.c:device_link_drop_managed
```
**Symbols:**

```
ffffffff817c7ec0-ffffffff817c7f6a: __device_link_del (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void __device_link_del(struct kref *kref);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff817ab3d0)
Location: drivers/base/core.c:872
Inline: False
Direct callers:
  - drivers/base/core.c:device_del
  - drivers/base/core.c:device_del
  - drivers/base/core.c:device_link_drop_managed
```
**Symbols:**

```
ffffffff817ab3d0-ffffffff817ab47a: __device_link_del (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void __device_link_del(struct kref *kref);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff81834730)
Location: drivers/base/core.c:882
Inline: False
Direct callers:
  - drivers/base/core.c:device_del
  - drivers/base/core.c:device_del
  - drivers/base/core.c:device_link_drop_managed
```
**Symbols:**

```
ffffffff81834730-ffffffff818347d7: __device_link_del (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void __device_link_del(struct kref *kref);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff81976200)
Location: drivers/base/core.c:894
Inline: False
Direct callers:
  - drivers/base/core.c:device_del
  - drivers/base/core.c:device_del
  - drivers/base/core.c:device_link_drop_managed
```
**Symbols:**

```
ffffffff81976200-ffffffff819762b5: __device_link_del (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void __device_link_del(struct kref *kref);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff81ae22d0)
Location: drivers/base/core.c:969
Inline: False
Direct callers:
  - drivers/base/core.c:device_del
  - drivers/base/core.c:device_del
  - drivers/base/core.c:device_link_drop_managed
```
**Symbols:**

```
ffffffff81ae22d0-ffffffff81ae2385: __device_link_del (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void __device_link_del(struct kref *kref);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff81b301f0)
Location: drivers/base/core.c:911
Inline: False
Direct callers:
  - drivers/base/core.c:device_del
  - drivers/base/core.c:device_del
  - drivers/base/core.c:device_link_drop_managed
```
**Symbols:**

```
ffffffff81b301f0-ffffffff81b302a5: __device_link_del (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void __device_link_del(struct kref *kref);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff81b879f0)
Location: drivers/base/core.c:914
Inline: False
Direct callers:
  - drivers/base/core.c:device_del
  - drivers/base/core.c:device_del
  - drivers/base/core.c:device_link_drop_managed
```
**Symbols:**

```
ffffffff81b879f0-ffffffff81b87aa5: __device_link_del (STB_LOCAL)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>arm64</code>: ✅</summary>

```c
void __device_link_del(struct kref *kref);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffff8000108e2c80)
Location: drivers/base/core.c:450
Inline: False
Direct callers:
  - drivers/base/core.c:device_del
  - drivers/base/core.c:device_del
  - drivers/base/core.c:device_link_drop_managed
```
**Symbols:**

```
ffff8000108e2c80-ffff8000108e2d3c: __device_link_del (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void __device_link_del(struct kref *kref);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (c09d1888)
Location: drivers/base/core.c:450
Inline: False
Direct callers:
  - drivers/base/core.c:device_del
  - drivers/base/core.c:device_del
  - drivers/base/core.c:device_link_drop_managed
```
**Symbols:**

```
c09d1888-c09d1940: __device_link_del (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void __device_link_del(struct kref *kref);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (c000000000977910)
Location: drivers/base/core.c:450
Inline: False
Direct callers:
  - drivers/base/core.c:device_del
  - drivers/base/core.c:device_del
  - drivers/base/core.c:device_link_drop_managed
```
**Symbols:**

```
c000000000977910-c000000000977a08: __device_link_del (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: ✅</summary>

```c
void __device_link_del(struct kref *kref);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffe0005781e2)
Location: drivers/base/core.c:450
Inline: False
Direct callers:
  - drivers/base/core.c:device_del
  - drivers/base/core.c:device_del
  - drivers/base/core.c:device_links_driver_cleanup
  - drivers/base/core.c:__device_links_no_driver
```
**Symbols:**

```
ffffffe0005781e2-ffffffe000578290: __device_link_del (STB_LOCAL)
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
void __device_link_del(struct kref *kref);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff816be5b0)
Location: drivers/base/core.c:450
Inline: False
Direct callers:
  - drivers/base/core.c:device_del
  - drivers/base/core.c:device_del
  - drivers/base/core.c:device_links_driver_cleanup
  - drivers/base/core.c:__device_links_no_driver
```
**Symbols:**

```
ffffffff816be5b0-ffffffff816be64c: __device_link_del (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void __device_link_del(struct kref *kref);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff81699860)
Location: drivers/base/core.c:450
Inline: False
Direct callers:
  - drivers/base/core.c:device_del
  - drivers/base/core.c:device_del
  - drivers/base/core.c:device_links_driver_cleanup
  - drivers/base/core.c:__device_links_no_driver
```
**Symbols:**

```
ffffffff81699860-ffffffff816998fc: __device_link_del (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void __device_link_del(struct kref *kref);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff816eca80)
Location: drivers/base/core.c:450
Inline: False
Direct callers:
  - drivers/base/core.c:device_del
  - drivers/base/core.c:device_del
  - drivers/base/core.c:device_links_driver_cleanup
  - drivers/base/core.c:__device_links_no_driver
```
**Symbols:**

```
ffffffff816eca80-ffffffff816ecb1c: __device_link_del (STB_LOCAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void __device_link_del(struct kref *kref);
```

**Collision:** Unique Static

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/base/core.c (ffffffff817072c0)
Location: drivers/base/core.c:450
Inline: False
Direct callers:
  - drivers/base/core.c:device_del
  - drivers/base/core.c:device_del
  - drivers/base/core.c:device_links_driver_cleanup
  - drivers/base/core.c:__device_links_no_driver
```
**Symbols:**

```
ffffffff817072c0-ffffffff8170735c: __device_link_del (STB_LOCAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>4.15</code> and <code>4.18</code> ⚠️</summary>
<ul>
<li>
<b>Param added. </b>
<code>struct kref *kref</code>
</li>
<li>
<b>Param removed. </b>
<code>struct device_link *link</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>4.18</code> and <code>5.0</code> ✅
</li>
<li>
No changes between <code>5.0</code> and <code>5.3</code> ✅
</li>
<li>
No changes between <code>5.3</code> and <code>5.4</code> ✅
</li>
<li>
No changes between <code>5.4</code> and <code>5.8</code> ✅
</li>
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
