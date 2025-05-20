# Function: <code>all_vm_events</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4</code>: Selective Inline ⚠️</summary>

```c
void all_vm_events(long unsigned int *ret);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/vmstat.c (ffffffff811ac720)
Location: mm/vmstat.c:57
Inline: True
Inline callers:
  - mm/vmstat.c:vmstat_start
Direct callers:
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
```
**Symbols:**

```
ffffffff811ac720-ffffffff811ac742: all_vm_events (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8</code>: Selective Inline ⚠️</summary>

```c
void all_vm_events(long unsigned int *ret);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/vmstat.c (ffffffff811c61b4)
Location: mm/vmstat.c:57
Inline: True
Inline callers:
  - mm/vmstat.c:vmstat_start
Direct callers:
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
```
**Symbols:**

```
ffffffff811c55b0-ffffffff811c55d2: all_vm_events (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10</code>: Selective Inline ⚠️</summary>

```c
void all_vm_events(long unsigned int *ret);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/vmstat.c (ffffffff811d6301)
Location: mm/vmstat.c:57
Inline: True
Inline callers:
  - mm/vmstat.c:vmstat_start
Direct callers:
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
```
**Symbols:**

```
ffffffff811d56c0-ffffffff811d56e2: all_vm_events (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13</code>: Selective Inline ⚠️</summary>

```c
void all_vm_events(long unsigned int *ret);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/vmstat.c (ffffffff811df032)
Location: mm/vmstat.c:57
Inline: True
Inline callers:
  - mm/vmstat.c:vmstat_start
Direct callers:
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
```
**Symbols:**

```
ffffffff811de440-ffffffff811de462: all_vm_events (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15</code>: Selective Inline ⚠️</summary>

```c
void all_vm_events(long unsigned int *ret);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/vmstat.c (ffffffff811f4c97)
Location: mm/vmstat.c:130
Inline: True
Inline callers:
  - mm/vmstat.c:vmstat_start
Direct callers:
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
```
**Symbols:**

```
ffffffff811f3ef0-ffffffff811f3f12: all_vm_events (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: Selective Inline ⚠️</summary>

```c
void all_vm_events(long unsigned int *ret);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/vmstat.c (ffffffff81215f3c)
Location: mm/vmstat.c:130
Inline: True
Inline callers:
  - mm/vmstat.c:vmstat_start
Direct callers:
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
```
**Symbols:**

```
ffffffff81215340-ffffffff81215362: all_vm_events (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: Selective Inline ⚠️</summary>

```c
void all_vm_events(long unsigned int *ret);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/vmstat.c (ffffffff81228e3c)
Location: mm/vmstat.c:130
Inline: True
Inline callers:
  - mm/vmstat.c:vmstat_start
Direct callers:
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
```
**Symbols:**

```
ffffffff81228220-ffffffff81228242: all_vm_events (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: Selective Inline ⚠️</summary>

```c
void all_vm_events(long unsigned int *ret);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/vmstat.c (ffffffff81238b22)
Location: mm/vmstat.c:131
Inline: True
Inline callers:
  - mm/vmstat.c:vmstat_start
Direct callers:
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
```
**Symbols:**

```
ffffffff81237e30-ffffffff81237e54: all_vm_events (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: Selective Inline ⚠️</summary>

```c
void all_vm_events(long unsigned int *ret);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/vmstat.c (ffffffff81246e12)
Location: mm/vmstat.c:131
Inline: True
Inline callers:
  - mm/vmstat.c:vmstat_start
Direct callers:
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
```
**Symbols:**

```
ffffffff812460e0-ffffffff81246104: all_vm_events (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: ✅</summary>

```c
void all_vm_events(long unsigned int *ret);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmstat.c (ffffffff81273d00)
Location: mm/vmstat.c:131
Inline: False
Direct callers:
  - mm/vmstat.c:vmstat_start
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
```
**Symbols:**

```
ffffffff81273d00-ffffffff81273d94: all_vm_events (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: ✅</summary>

```c
void all_vm_events(long unsigned int *ret);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmstat.c (ffffffff8127e560)
Location: mm/vmstat.c:131
Inline: False
Direct callers:
  - mm/vmstat.c:vmstat_start
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
```
**Symbols:**

```
ffffffff8127e560-ffffffff8127e5f4: all_vm_events (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: ✅</summary>

```c
void all_vm_events(long unsigned int *ret);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmstat.c (ffffffff812836c0)
Location: mm/vmstat.c:131
Inline: False
Direct callers:
  - mm/vmstat.c:vmstat_start
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
```
**Symbols:**

```
ffffffff812836c0-ffffffff81283755: all_vm_events (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: ✅</summary>

```c
void all_vm_events(long unsigned int *ret);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmstat.c (ffffffff812c1910)
Location: mm/vmstat.c:130
Inline: False
Direct callers:
  - mm/vmstat.c:vmstat_start
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
```
**Symbols:**

```
ffffffff812c1910-ffffffff812c19cc: all_vm_events (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: ✅</summary>

```c
void all_vm_events(long unsigned int *ret);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmstat.c (ffffffff8131ea30)
Location: mm/vmstat.c:131
Inline: False
Direct callers:
  - mm/vmstat.c:vmstat_start
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
```
**Symbols:**

```
ffffffff8131ea30-ffffffff8131eb07: all_vm_events (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: ✅</summary>

```c
void all_vm_events(long unsigned int *ret);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmstat.c (ffffffff81393cc0)
Location: mm/vmstat.c:130
Inline: False
Direct callers:
  - mm/vmstat.c:vmstat_start
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
```
**Symbols:**

```
ffffffff81393cc0-ffffffff81393da5: all_vm_events (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: ✅</summary>

```c
void all_vm_events(long unsigned int *ret);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmstat.c (ffffffff813c6440)
Location: mm/vmstat.c:131
Inline: False
Direct callers:
  - mm/vmstat.c:vmstat_start
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
```
**Symbols:**

```
ffffffff813c6440-ffffffff813c6550: all_vm_events (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: ✅</summary>

```c
void all_vm_events(long unsigned int *ret);
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In mm/vmstat.c (ffffffff813f0e40)
Location: mm/vmstat.c:130
Inline: False
Direct callers:
  - mm/vmstat.c:vmstat_start
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
```
**Symbols:**

```
ffffffff813f0e40-ffffffff813f0f50: all_vm_events (STB_GLOBAL)
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
void all_vm_events(long unsigned int *ret);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/vmstat.c (ffff8000102da17c)
Location: mm/vmstat.c:131
Inline: True
Inline callers:
  - mm/vmstat.c:vmstat_start
Direct callers:
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
```
**Symbols:**

```
ffff8000102d9770-ffff8000102d97a4: all_vm_events (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: Selective Inline ⚠️</summary>

```c
void all_vm_events(long unsigned int *ret);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/vmstat.c (c0500ea8)
Location: mm/vmstat.c:131
Inline: True
Inline callers:
  - mm/vmstat.c:vmstat_start
Direct callers:
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
```
**Symbols:**

```
c05007d0-c05007fc: all_vm_events (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: Selective Inline ⚠️</summary>

```c
void all_vm_events(long unsigned int *ret);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/vmstat.c (c00000000039a99c)
Location: mm/vmstat.c:131
Inline: True
Inline callers:
  - mm/vmstat.c:vmstat_start
Direct callers:
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
```
**Symbols:**

```
c000000000399490-c0000000003994d8: all_vm_events (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void all_vm_events(long unsigned int *ret);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/vmstat.c (ffffffe0001f4356)
Location: mm/vmstat.c:131
Inline: True
Inline callers:
  - mm/vmstat.c:vmstat_start
Direct callers:
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
```
**Symbols:**

```
ffffffe0001f39bc-ffffffe0001f39e6: all_vm_events (STB_GLOBAL)
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
void all_vm_events(long unsigned int *ret);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/vmstat.c (ffffffff8123f462)
Location: mm/vmstat.c:131
Inline: True
Inline callers:
  - mm/vmstat.c:vmstat_start
Direct callers:
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
```
**Symbols:**

```
ffffffff8123e730-ffffffff8123e754: all_vm_events (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: Selective Inline ⚠️</summary>

```c
void all_vm_events(long unsigned int *ret);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/vmstat.c (ffffffff81232462)
Location: mm/vmstat.c:131
Inline: True
Inline callers:
  - mm/vmstat.c:vmstat_start
Direct callers:
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
```
**Symbols:**

```
ffffffff81231730-ffffffff81231754: all_vm_events (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: Selective Inline ⚠️</summary>

```c
void all_vm_events(long unsigned int *ret);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/vmstat.c (ffffffff8123d202)
Location: mm/vmstat.c:131
Inline: True
Inline callers:
  - mm/vmstat.c:vmstat_start
Direct callers:
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
```
**Symbols:**

```
ffffffff8123c4d0-ffffffff8123c4f4: all_vm_events (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: Selective Inline ⚠️</summary>

```c
void all_vm_events(long unsigned int *ret);
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In mm/vmstat.c (ffffffff8124c932)
Location: mm/vmstat.c:131
Inline: True
Inline callers:
  - mm/vmstat.c:vmstat_start
Direct callers:
  - drivers/virtio/virtio_balloon.c:update_balloon_stats
```
**Symbols:**

```
ffffffff8124bc30-ffffffff8124bc54: all_vm_events (STB_GLOBAL)
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4</code> and <code>4.8</code> ✅
</li>
<li>
No changes between <code>4.8</code> and <code>4.10</code> ✅
</li>
<li>
No changes between <code>4.10</code> and <code>4.13</code> ✅
</li>
<li>
No changes between <code>4.13</code> and <code>4.15</code> ✅
</li>
<li>
No changes between <code>4.15</code> and <code>4.18</code> ✅
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
