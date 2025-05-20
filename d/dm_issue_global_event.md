# Function: <code>dm_issue_global_event</code>

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
<summary>In <code>4.15</code>: ✅</summary>

```c
void dm_issue_global_event();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffff817c0bb0)
Location: drivers/md/dm.c:56
Inline: False
Direct callers:
  - drivers/md/dm.c:dm_swap_table
  - drivers/md/dm.c:event_callback
  - drivers/md/dm-ioctl.c:ctl_ioctl
```
**Symbols:**

```
ffffffff817c0bb0-ffffffff817c0bda: dm_issue_global_event (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18</code>: ✅</summary>

```c
void dm_issue_global_event();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffff818092c0)
Location: drivers/md/dm.c:56
Inline: False
Direct callers:
  - drivers/md/dm.c:dm_swap_table
  - drivers/md/dm.c:event_callback
  - drivers/md/dm-ioctl.c:ctl_ioctl
```
**Symbols:**

```
ffffffff818092c0-ffffffff818092ea: dm_issue_global_event (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0</code>: ✅</summary>

```c
void dm_issue_global_event();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffff818353f0)
Location: drivers/md/dm.c:56
Inline: False
Direct callers:
  - drivers/md/dm.c:dm_swap_table
  - drivers/md/dm.c:event_callback
  - drivers/md/dm-ioctl.c:ctl_ioctl
```
**Symbols:**

```
ffffffff818353f0-ffffffff8183541a: dm_issue_global_event (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3</code>: ✅</summary>

```c
void dm_issue_global_event();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffff81878240)
Location: drivers/md/dm.c:56
Inline: False
Direct callers:
  - drivers/md/dm.c:dm_swap_table
  - drivers/md/dm.c:event_callback
  - drivers/md/dm-ioctl.c:ctl_ioctl
```
**Symbols:**

```
ffffffff81878240-ffffffff8187826a: dm_issue_global_event (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4</code>: ✅</summary>

```c
void dm_issue_global_event();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffff818aa080)
Location: drivers/md/dm.c:56
Inline: False
Direct callers:
  - drivers/md/dm.c:dm_swap_table
  - drivers/md/dm.c:event_callback
  - drivers/md/dm-ioctl.c:ctl_ioctl
```
**Symbols:**

```
ffffffff818aa080-ffffffff818aa0aa: dm_issue_global_event (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8</code>: Selective Inline ⚠️</summary>

```c
void dm_issue_global_event();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffff8197ae91)
Location: drivers/md/dm.c:59
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_swap_table
  - drivers/md/dm.c:event_callback
Direct callers:
  - drivers/md/dm-ioctl.c:ctl_ioctl
```
**Symbols:**

```
ffffffff8197a5e0-ffffffff8197a60a: dm_issue_global_event (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11</code>: Selective Inline ⚠️</summary>

```c
void dm_issue_global_event();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffff8197f6b6)
Location: drivers/md/dm.c:59
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_swap_table
  - drivers/md/dm.c:event_callback
Direct callers:
  - drivers/md/dm-ioctl.c:ctl_ioctl
```
**Symbols:**

```
ffffffff8197ee80-ffffffff8197eeaa: dm_issue_global_event (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13</code>: Selective Inline ⚠️</summary>

```c
void dm_issue_global_event();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffff819637d6)
Location: drivers/md/dm.c:60
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_swap_table
  - drivers/md/dm.c:event_callback
Direct callers:
  - drivers/md/dm-ioctl.c:ctl_ioctl
```
**Symbols:**

```
ffffffff81962cd0-ffffffff81962cfa: dm_issue_global_event (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15</code>: Selective Inline ⚠️</summary>

```c
void dm_issue_global_event();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffff81a0b776)
Location: drivers/md/dm.c:61
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_swap_table
  - drivers/md/dm.c:event_callback
Direct callers:
  - drivers/md/dm-ioctl.c:ctl_ioctl
```
**Symbols:**

```
ffffffff81a09d00-ffffffff81a09d2a: dm_issue_global_event (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19</code>: Selective Inline ⚠️</summary>

```c
void dm_issue_global_event();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffff81b73bf8)
Location: drivers/md/dm.c:68
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_swap_table
  - drivers/md/dm.c:event_callback
Direct callers:
  - drivers/md/dm-ioctl.c:ctl_ioctl
```
**Symbols:**

```
ffffffff81b73170-ffffffff81b731a6: dm_issue_global_event (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2</code>: Selective Inline ⚠️</summary>

```c
void dm_issue_global_event();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffff81d10b36)
Location: drivers/md/dm.c:68
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_swap_table
  - drivers/md/dm.c:event_callback
Direct callers:
  - drivers/md/dm-ioctl.c:ctl_ioctl
```
**Symbols:**

```
ffffffff81d0fc40-ffffffff81d0fc78: dm_issue_global_event (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5</code>: Selective Inline ⚠️</summary>

```c
void dm_issue_global_event();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffff81d79fb6)
Location: drivers/md/dm.c:69
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_swap_table
  - drivers/md/dm.c:event_callback
Direct callers:
  - drivers/md/dm-ioctl.c:ctl_ioctl
```
**Symbols:**

```
ffffffff81d790c0-ffffffff81d790f8: dm_issue_global_event (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8</code>: Selective Inline ⚠️</summary>

```c
void dm_issue_global_event();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffff81e31153)
Location: drivers/md/dm.c:69
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_swap_table
  - drivers/md/dm.c:event_callback
Direct callers:
  - drivers/md/dm-ioctl.c:ctl_ioctl
```
**Symbols:**

```
ffffffff81e30230-ffffffff81e30268: dm_issue_global_event (STB_GLOBAL)
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
void dm_issue_global_event();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffff800010affcc8)
Location: drivers/md/dm.c:56
Inline: False
Direct callers:
  - drivers/md/dm.c:dm_swap_table
  - drivers/md/dm.c:event_callback
  - drivers/md/dm-ioctl.c:ctl_ioctl
```
**Symbols:**

```
ffff800010affcc8-ffff800010affd2c: dm_issue_global_event (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>armhf</code>: ✅</summary>

```c
void dm_issue_global_event();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (c0bdf8ec)
Location: drivers/md/dm.c:56
Inline: False
Direct callers:
  - drivers/md/dm.c:dm_swap_table
  - drivers/md/dm.c:event_callback
  - drivers/md/dm-ioctl.c:ctl_ioctl
```
**Symbols:**

```
c0bdf8ec-c0bdf940: dm_issue_global_event (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>ppc64el</code>: ✅</summary>

```c
void dm_issue_global_event();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (c000000000bef120)
Location: drivers/md/dm.c:56
Inline: False
Direct callers:
  - drivers/md/dm.c:dm_swap_table
  - drivers/md/dm.c:event_callback
  - drivers/md/dm-ioctl.c:ctl_ioctl
```
**Symbols:**

```
c000000000bef120-c000000000bef184: dm_issue_global_event (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>riscv64</code>: Selective Inline ⚠️</summary>

```c
void dm_issue_global_event();
```

**Collision:** Unique Global

**Inline:** Selective

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffe0006f0ef0)
Location: drivers/md/dm.c:56
Inline: True
Inline callers:
  - drivers/md/dm.c:dm_swap_table
  - drivers/md/dm.c:event_callback
Direct callers:
  - drivers/md/dm-ioctl.c:ctl_ioctl
```
**Symbols:**

```
ffffffe0006f050e-ffffffe0006f054c: dm_issue_global_event (STB_GLOBAL)
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
void dm_issue_global_event();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffff8184ff00)
Location: drivers/md/dm.c:56
Inline: False
Direct callers:
  - drivers/md/dm.c:dm_swap_table
  - drivers/md/dm.c:event_callback
  - drivers/md/dm-ioctl.c:ctl_ioctl
```
**Symbols:**

```
ffffffff8184ff00-ffffffff8184ff2a: dm_issue_global_event (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>azure</code>: ✅</summary>

```c
void dm_issue_global_event();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffff81817510)
Location: drivers/md/dm.c:56
Inline: False
Direct callers:
  - drivers/md/dm.c:dm_swap_table
  - drivers/md/dm.c:event_callback
  - drivers/md/dm-ioctl.c:ctl_ioctl
```
**Symbols:**

```
ffffffff81817510-ffffffff8181753a: dm_issue_global_event (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>gcp</code>: ✅</summary>

```c
void dm_issue_global_event();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffff8189f530)
Location: drivers/md/dm.c:56
Inline: False
Direct callers:
  - drivers/md/dm.c:dm_swap_table
  - drivers/md/dm.c:event_callback
  - drivers/md/dm-ioctl.c:ctl_ioctl
```
**Symbols:**

```
ffffffff8189f530-ffffffff8189f55a: dm_issue_global_event (STB_GLOBAL)
```
</details>
</li>
<li>
<details>
<summary>In <code>lowlatency</code>: ✅</summary>

```c
void dm_issue_global_event();
```

**Collision:** Unique Global

**Inline:** No

**Transformation:** False

**Instances:**

```
In drivers/md/dm.c (ffffffff818bb790)
Location: drivers/md/dm.c:56
Inline: False
Direct callers:
  - drivers/md/dm.c:dm_swap_table
  - drivers/md/dm.c:event_callback
  - drivers/md/dm-ioctl.c:ctl_ioctl
```
**Symbols:**

```
ffffffff818bb790-ffffffff818bb7ba: dm_issue_global_event (STB_GLOBAL)
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
